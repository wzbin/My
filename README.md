# NewEgg
my code

这份代码可以爬取新蛋网上手机分类页面所有商品的名称与价格
新蛋网的价格及竟然是一张图片，无法忍受！
主要思路：
1、递归找到所有商品页面
2、下载价格图片
3、分析图中数字并转换成字符串


主要的代码是TestNewegg.java 直接运行就可以了

价格图片默认下载到G盘里，可以在TestNewegg.java里修改

Demo.java是识别图片中数字的程序

GetImage.java 是从网页下载图片的程序

识别图片用到了AspriseORC，将AspriseOCR.dll, DevIL.dll,ILU.dll 复制到jdk/bin目录下就可以使用了

所有的jar包都在项目中弄好了

如果有时运行不起的话，把下载好的图片删除了，再运行一次
