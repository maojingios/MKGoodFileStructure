# MKGoodFileStructure
MVC文件结构，参考这里就够啦！

# MVC工程文件结构

## 引言

“代码虐我千百遍，我待代码如初念”，晚上脑海莫名闪出此金典语句，哈哈！MVC设计模式下，是否曾某个类的归属纠结过，甚至比自己另一半没着落还要纠结；是否接手项目一段时间后，苦于不知如何整理工程文件，让结构清晰明了，到最后就算了、罢了，把自己负责部分维护好就OK啦！下面这张图和注释供大家参考借鉴，反正我先收藏了！你们看着办吧！（谢谢原创分享）。


## 正文

直接贴高清福利大图😀：

![](https://github.com/maojingios/MKGoodFileStructure/blob/master/项目结构.png)

* Class:存放的是App中所有的模块功能；

* Base:存放一些基类,比如BaseViewController,BaseModel等,共性直接在基类中去修改；
* Vendor:三方,因为我的项目中使用cocopods管理三方,所以这个文件夹中我在此放的是一些比较小的功能的第三方；
* Framework:存放一些类库或者自己封装的一些静态库；
* Resource:存放app中一些索引资源,比如图片,文本等,或者将图片打包的Bundle；
* Custom:这个文件夹我用来存放自己项目或者公司自己风格的一些自定义的视图,比如我们常见的上拉加载,下拉刷新的自定义头部空间等；
* API:这个只专门用来做网络处理的,因为这个项目基本上都会用到网络请求,算是比较重要的一个部分,所以在此单独拿出来作为一个分类；
* Support:这个用来存放一些比较小的模块,比如常用的一些工具类,分类,宏定义,PCH文件等；
* Main:专门存放AppDelegate或者AppDelegate的Category。

## 总结

对于天生讲究的coder来说，我们是不能容忍紊乱的目录结构，更加接受不了找个类还得遍历整个工程，当然每个人可能都有自己的标准，但参照这个标准来，新旧项目定会结构清晰，拓展性好。再也不用为文件找不到归属苦恼了！拿走不谢！




