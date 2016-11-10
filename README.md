# Android 最新学习资料收集                                                        
收集这份资料的灵感来源于我的浏览器收藏夹快爆了，后来在github 上也看到了很优秀的开源库的收集资料，非常的好，但是太过于多，也不够新，所以决定自己来做一个。原始的markdowm文件已经放到github上，欢迎[下载和star](https://github.com/forezp/AndroidMaterialLatest) 。这份资料我会不断的完善，也欢迎一些经验丰富的开发者可以一起来完善，直接[pull request](https://github.com/forezp/AndroidMaterialLatest/pulls) 或者[issue](https://github.com/forezp/AndroidMaterialLatest/issues)，我会定期筛选合并，有一些好的建议和意见随时[联系我](#联系我)，欢迎转载，谢谢收藏。
## 目录
- [安卓流行框架](#安卓流行框架推荐)
- [常用网站](#常用网站)
- [博客推荐](#博客推荐)
- [微信公众号推荐](#微信公众号推荐)
- [书籍推荐](#书籍推荐)
- [RxJava系列](#RxJava系列)
- [retrofi系列](#retrofi系列)
- [MVP系列](#MVP系列)
- [MaterialDesign系列](#MaterialDesign系列)
- [MVP-retrofit-rxjava-materialDesign系列](#MVP-retrofit-rxjava-materialDesign系列)
- [Kotlin系列](#Kotlin系列)
- [开源项目学习](#开源项目学习)
- [开源库收集](#开源库收集)
- [Android开发者杂志周刊](#Android开发者杂志周刊)
- [工具](#工具)
- [开发环境](#开发环境)
- [素材](#素材)
- [设计模式](#设计模式)
- [文档](#文档)
- [感谢](#感谢)
- [联系我](#联系我)


=========================================================

## 安卓流行框架
 
 分类  |  框架名称  | 推荐理由 
  --------- | --------- | --------
 缓存 | [DiskLruCache](https://github.com/JakeWharton/DiskLruCache) |  DiskLruCache ，JakeWharton开源，缓存神器
 图片加载 | [Glide](https://github.com/bumptech/glide) | 可播放gif，谷歌推荐的图片加载
 图片加载 | [Fresco](https://github.com/facebook/fresco) | 可播放gif，流畅性最好的加载框架，Facebook 出品
 图片加载 | [Picasso](https://github.com/square/picasso) |  squre inc.开源的图片加载框架。
 图片处理 | [Picasso—transformations](https://github.com/wasabeef/picasso-transformations) |  图片处理框架。
 图片处理 | [Glide—transformations](https://github.com/wasabeef/glide-transformations) |  图片处理框架。
 网络请求 | [Okhttp](https://github.com/square/okhttp) |   非常强大的一个网络请求框架。
 网络请求 | [Retrofit](https://github.com/square/retrofit) |  基于okhttp ,squire出品，必属精品。。
 网络请求 | [volley](https://github.com/mcxiaoke/android-volley) |  谷歌之前出品的网络框架。
 数据解析 | [Gson](https://github.com/google/gson) |   非常好用的JSOn解析。
 数据解析 | [jackson](https://github.com/FasterXML/jackson) |  这个也不错。
 数据库   | [greendao](https://github.com/greenrobot/greenDAO) |   一个轻量、效率快的数据库。
 数据库   | [realm](https://github.com/realm/realm-java) |  好用，替代sqlite。
 数据库   | [Sugar](https://github.com/satyan/sugar) |   另外一个好用的数据库，个人推荐GreenDao。
 依赖注入 | [ButterKnife](https://github.com/JakeWharton/butterknife) |  注解，让你的代码整洁，配合ButterKnife Zelezny，一键生成注解。
 图表 | [WilliamChart](https://github.com/diogobernardino/WilliamChart) |  强大的图标库。
 图表 | [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart) |  强大的图标库。
 事件总线 | [EventBus](https://github.com/greenrobot/EventBus) |   一个简单移动的事件总线。
 事件总线 | [otto](https://github.com/square/otto) |   另一个简单移动的事件总线。
 响应式 | [RXjava](https://github.com/ReactiveX/RxJava) |  响应式编程 ，功能强大，值得学习。
 响应式 | [RXAndroid](https://github.com/ReactiveX/RxAndroid) |  响应式编程 ，功能强大，值得学习。。
 响应式 | [RXBinding](https://github.com/JakeWharton/RxBinding) |  响应式编程 ，功能强大，值得学习。。
 Log | [logger](https://github.com/orhanobut/logger) |   一个logger框架。
 Log | [Hugo](https://github.com/spf13/hugo) |   一个logger框架。
 Log | [Timber](https://github.com/JakeWharton/timber) |   一个logger框架。
 测试框架 | [mockito](https://github.com/mockito/mockito) |  一个强大的用于 Java 开发的模拟测试框架。
 测试框架 | [robotium](https://github.com/RobotiumTech/robotium) |  是一款国外的Android自动化测试框架。
 调试框架 | [stetho](https://github.com/facebook/stetho) |  facebook的Android调试工具Stetho。
 性能优化 | [leakcanary](https://github.com/square/leakcanary) |  一个检查内存泄露的插件，非常的强大。

## 常用网站
网站名称  |  推荐理由
  --------- | --------
 [Google](google.com) | google搜索，让信息传遍世界
 [Github](http://www.github.com/) | 面向世界的代码托管平台，在GitHub，你可以十分轻易地找到海量的开源代码
 [StackOverFlow](http://stackoverflow.com/) | 一个与程序相关的IT技术问答网站
 [SegmentFault]( https://segmentfault.com/t/android) | 中文的开发者社区及媒体,中国的StackOverFlow
 [开源中国](http://www.oschina.net/) | 开源中国社区
 [安卓开发社区]( http://developer.android.com/) |  安卓官网
 [掘金](http://gold.xitu.io/) |  掘金，号称中国质量最高的技术分享社区
 [csdn](http://www.csdn.net/) |  CSDN，全球最大的中文IT技术社区
 [泡在网上的日子](http://www.csdn.net/) |  泡在网上的日子，一个正对移动开发的技术分享论坛。
 [干货集中营](http://gank.io/) |  干货集中营，每日分享。
 
 
## 博客推荐

 博客地址 | 博主信息
 -------- | --------
[Android Developers Blog](http://android-developers.blogspot.com/) | Android官网博客 ，有Android 的最新资讯，要翻墙。
[郭霖](http://blog.csdn.net/guolin_blog) | 博主郭霖是大神, 人人都称"郭神", 是第一行代码的作者, 博主在 CSDN 上所写的文章都非常值得学习
[张鸿洋](http://blog.csdn.net/lmj623565791/) | 张鴻洋是 CSDN 博客专家, "洋神", 他的每一篇博客都很值得大家去学习
[代码家](http://blog.daimajia.com/) |  Android 大神, 博主收集了很多 Android 开源库, 博主自己也做了很多开源库, 非常值得学习，另外是[gank.io](gank.io)的组织者。
[Trinea](http://www.trinea.cn/) | 目前在滴滴负责 Android 客户端技术, 他是开源库项目收集达人, 你想要的开源库[上面](https://github.com/Trinea)都有,并且有源码解析，大家可以去关注一下, [地址](http://p.codekk.com) .
[张兴业](http://blog.csdn.net/xyz_lmn) | 张兴业同样也是 CSDN 博客专家
[大头鬼](http://blog.csdn.net/lzyzsd/) | hi大头鬼hi 是阿里巴巴集团的一名 Android 工程师, 写了一系列RXJava 资料。
[农民伯伯](http://over140.cnblogs.com/) | 资深博客写手，他的博客非常值得一看。
[任玉刚](http://blog.csdn.net/singwhatiwanna) | 《安卓开发艺术探索》作者。
[罗升阳](http://blog.csdn.net/Luoshengyang) | CSDN博客专家，《安卓系统源代码情景分析》。


##  微信公众号推荐

 微信公众号ID | 博主信息
 -------- | --------
 guolin_blog  |  郭霖的公众号，有每日推荐文章，《第一行代码》作者。
 hongyangAndroid  | 张鸿洋的公众号。有每日推荐文字，Csdn博客专家。
 AndroidDeveloper |  他是上海薄荷科技开发主管, 他的博客分享了他从编程白痴到自学 Android 一路走过的经验, 写了一篇 [Android学习之路](http://stormzhang.com/android/2014/07/07/learn-android-from-rookie/) 帮助了无数人, 里面还有很多好的文章非常适合新手入门, 

## 书籍推荐

  书籍名称  |   备注
  --------- | --------
[第一行代码](https://book.douban.com/subject/25942191/)   | 郭霖大杰作，适合新人
[Java核心技术 卷I](https://book.douban.com/subject/25762168/) | java入门书籍
[Effective Java](https://book.douban.com/subject/3360807/) |进阶书 
[Java并发编程](https://book.douban.com/subject/10484692/) |Java并发编程
[给大忙人看的Java8](https://book.douban.com/subject/26274206/) | 给大忙人看的Java8
[Thinking In Java 中文版](https://book.douban.com/subject/1723199/) | 学习Java 语言必备书籍
[Android群英传](https://book.douban.com/subject/26599539/) | 本书作者 @Tomcat 的猫。
[Android开发艺术探索](http://product.china-pub.com/4806147) | 由任玉刚所著.
[深入理解Java虚拟机](https://book.douban.com/subject/24722612/)  | 不是很难 ，需要看看
[鸟哥的Linux私房菜](https://book.douban.com/subject/4889838/)  | 太经典。
[图解Http](https://book.douban.com/subject/25863515/)  |  让你很快上手http。
[Head First设计模式](https://book.douban.com/subject/2243615/)  | Head First设计模式
[程序员修炼之道](https://book.douban.com/subject/5387402/)   | 程序员修炼之道
[Git权威指南中文手册](http://iissnan.com/progit/html/zh/ch1_0.html) | Git权威指南中文手册
[数据结构与算法基础](https://book.douban.com/subject/1139426/) | 数据结构和算法的书，比较全
[JavaScript权威指南](https://book.douban.com/subject/2228378/) | JavaScript权威指南，学习js一本书差不多了


## RxJava系列

  名称  |   备注
  --------- | --------
[ReactiveX/RxJava文档中文版](https://mcxiaoke.gitbooks.io/rxdocs/content/) | 大神们在百忙之中翻译的文档，感谢开源。
[ReactiveX/RxJava官方API](http://reactivex.io/RxJava/javadoc/) | ReactiveX/RxJava官方API
[给 Android 开发者的 RxJava 详解](http://gank.io/post/560e15be2dca930e00da1083) | 给 Android 开发者的 RxJava 详解 ,作者：扔物线
[深入浅出RxJava](http://blog.csdn.net/lzyzsd/article/details/41833541/) | 大头鬼写的Rxjava 系列
[老罗Rxjava视频](http://www.apkbus.com/forum.php?mod=viewthread&tid=257703&extra=page%3D1%26filter%3Dauthor%26orderby%3Ddateline&_dsign=43e9b95f) | 老罗Rxjava视频

## retrofi系列

  名称  |   备注
  --------- | --------
[官方文档](http://square.github.io/retrofit/) |  squire出品，必属精品。
[Retrofit 2.0：有史以来最大的改进](http://www.jcodecraeer.com/a/anzhuokaifa/androidkaifa/2015/0915/3460.html) |  泡在网上的日子，翻译。
[Retrofit2.0使用详解](http://blog.csdn.net/ljd2038/article/details/51046512) |  讲解了基本的使用方法

## MVP系列

  名称  |   备注
  --------- | --------
[Android中的MVP](http://www.jcodecraeer.com/a/anzhuokaifa/androidkaifa/2015/0227/2503.html) |  泡在网上的日子翻译。
[google写的列子](https://github.com/googlesamples/android-architecture) |  google写的MvP例子。
[Android-CleanArchitecture](https://github.com/android10/Android-CleanArchitecture) |  一个适合新人的MVP例子

## MaterialDesign系列
名称  |   备注
  --------- | --------
- [Material Design 教程](https://www.google.com/design/spec/material-design/introduction.html) |  google官方提高的materail design 指导。
- [Material Design 教程(中文版)](https://github.com/1sters/material_design_zh_2) |  翻译的中文文档。
- [Material Design Android Library ](https://github.com/navasmdc/MaterialDesignLibrary)(Material Design 开源库) |  一些非常优秀的material design 开源库。


## MVP-retrofit-rxjava-materialDesign系列

  名称  |   备注
  --------- | --------
[瓣呀](https://github.com/forezp/banya) |  [瓣呀，一个基于豆瓣API仿网易音乐的开源项目（本人写的，欢迎star）](https://github.com/forezp/banya)
[大象](https://github.com/Freelander/Elephant) |  一个第三放PHPHUB客户端
[开发资料](http://www.jianshu.com/p/8c3898eed1bb) |  开发 Material Design+RxJava+Retrofit+MVP App 参考资料


## Kotlin系列

  名称  |   备注
  --------- | --------
 [kotlin 介绍](http://www.weibo.com/ttarticle/p/show?id=2309403942933815527259)  |  kotlin 介绍
 [kotlin 官网](http://kotlinlang.org/)  |   kotlin 官网，最新的资讯。
 [kotlin,网友对其评价](https://www.zhihu.com/question/25289041) | 网友对其评价 ，很中肯。本人已经在学习，觉得如果熟练，开发速度大大提高，代码可读性也提高。
  

## 开源项目学习

 项目名称 | 项目简介 
 -------- | --------
[Google I/O 2014](https://github.com/google/iosched) | Google I/O Android App 使用了当时最新推出的 Material Design 设计 
[Google play music](https://github.com/googlesamples/android-UniversalMusicPlayer) | 一个跨多个平台音乐播放器 
[github客户端](https://github.com/pockethub/PocketHub) | 开源者 github 团队, 支持项目的 lssues 和 Gists 并集成了新闻 feed 以便及时获取来自组织好友和资料库的更新信息, 还提供了一个用于快速访问你创建,监控以及发布 issue 面板, 可查看并将问题加到收藏夹
[MIUI 便签](https://github.com/MiCode/Notes) | MiCode 便签是小米便签的社区开源版, 由 MIUI 团队(ww.miui.com)发起并贡献第一批代码, 遵循 NOTICE 文件所描述的开源协议
[oschina](http://git.oschina.net/oschina/android-app) | 开源中国社区 Android 客户端, 此开源的是 v1 版本, v2 版本将在 2015 年年中开源
[ZXing](https://github.com/zxing/zxing) | 二维码扫描工具,市场上许多应用的二维码扫描工具都是从这个修改得到的
[Meizhi](https://github.com/drakeet/Meizhi) | 开发者是许晓峰(Drakeet), 该 app 是数据来自代码家干货网站 [gank.io](http://gank.io), 有很多开发者都纷纷为这网站做客户端 app, 因为代码家大神开放该网站的 Api, 更重要的是该网站每天除了有干货还有漂亮妹子看呢, 该 App 使用到的技术有 RxJava + Retrofit, 代码结构非常清晰, 值得一看的开源 App.
[鲁班](https://github.com/Curzibn/Luban) | Android图片压缩工具，仿微信朋友圈压缩策略,一个优秀的压缩图片框架
[ZhihuDailyPurify ](https://github.com/izzyleung/ZhihuDailyPurify) | 知乎日报·净化
[瓣呀](https://github.com/forezp/banya) | [瓣呀，一个基于豆瓣API仿网易音乐的开源项目（本人写的，欢迎star）](https://github.com/forezp/banya)

## 开源库收集
- [awesome-android-ui](https://github.com/wasabeef/awesome-android-ui)
- [awesome-android-libraries](https://github.com/wasabeef/awesome-android-libraries)
- [泡在网上的日子](http://www.jcodecraeer.com/plus/list.php?tid=31)
- [Android Libraries and Resources ](http://alamkanak.github.io/android-libraries-and-resources/)
- [Android Arsenal ](http://android-arsenal.com/)(一个专门收集 android 开源库的网站, 网站经常更新)
- [Android 开源项目汇总 ](https://github.com/Trinea/android-open-project)(Trinea 大神收集的)
- [Android 开源项目源码分析 ](http://codekk.com/open-source-project-analysis)(在懂得使用这些开源项目同时, 也应该了解当中的原理)
- [安卓巴士](http://www.apkbus.com/forum-417-1.html)
- [看源社区](http://www.see-source.com/androidwidget/list.html)

## Android开发者杂志周刊
  周刊名 | 周刊简介
  ------ | -------
[干货集中营](http://gank.io/) | 由 [代码家](http://blog.daimajia.com/) 维护更新, 分享内容有漂亮妹子, Android 干货, iOS 干货, App, 技术以外推荐, 还有休息视频
[Android Weekly](http://androidweekly.net/) | Android Weekly 是由Android 团队的成员和国外知名的 Android 开发者维护, 分享的都是干货。


## 工具
工具名称  | 推荐理由 
  --------- | --------
 [蓝灯](https://github.com/getlantern/lantern) |  Lantern ，免费翻墙神器
 [bejson](http://www.bejson.com/) |  Json查看，Json生成实体 
 [sql]( http://tool.lu/sql/) |  sql语句验证
 [矢量图]( http://www.iconfont.cn/) |  阿里巴巴的矢量图库
 [dp px 转换]( http://labs.rampinteractive.co.uk/android_dp_px_calculator/) |  阿里巴巴的矢量图库
 [谷歌翻译]( http://translate.google.cn/) |  谷歌翻译

 
## 开发环境

 环境/工具 | 简述
 -------- | --------
[AndroidDevTools]( http://www.androiddevtools.cn/) |  一个收集整理Android开发所需的Android SDK、开发中用到的工具、Android开发教程、Android设计规范，免费的设计素材的网站,很齐全，有它够用了。
[Android Studio](http://developer.android.com/sdk/index.html) |  安卓官方开发工具，基于IDEA , 比Eclipse好太多，没有用的同学赶紧转吧。
[Genymotion](https://www.genymotion.com/#!/download) |  安卓模拟器。
[jadx](https://github.com/skylot/jadx) |   Android 反编译神器, 不同于常见的 [dex2jar](https://github.com/pxb1988/dex2jar)
[GradleDependenciesHelperPlugin](https://github.com/ligi/GradleDependenciesHelperPlugin) | Gradle 依赖自动补全插件
[LeakCanary](https://github.com/square/leakcanary) |  Square开源的一个非常有用的工具,检测出内存泄的问题
[ButterKnife Zelezny](https://github.com/avast/android-butterknife-zelezny) | ButterKnife 生成器, 使用起来非常简单方便, 为你简写了很多代码。
[idea-markdown](https://github.com/nicoulaj/idea-markdown) | 在 AS 中编写 Markdown 文件, 可以直接预览网页显示效果
[Stetho](http://facebook.github.io/stetho/) | Stetho 是 Facebook 出品的一个强大的 Android 调试工具,使用该工具你可以在 Chrome Developer Tools 查看 App 的布局
[GsonFormat](https://github.com/zzz40500/GsonFormat) | 现在大多数服务端 api 都以 json 数据格式返回, 而客户端需要根据 api 接口生成相应的实体类, 这个插件把这个过程自动化了


## 素材

- [阿里巴巴矢量图](http://www.iconfont.cn/)
- [Material Design设计模板与素材](http://www.materialup.com/)
- [Icon Store](https://iconstore.co/)
- [Material icons](https://design.google.com/icons/)
- [awesome-design](https://github.com/gztchan/awesome-design/)


## 设计模式

- [java-design-patterns](https://github.com/iluwatar/java-design-patterns#model-view-presenter)
- [Effective Java](https://github.com/HackathonHackers/programming-ebooks/blob/master/Java/Effective%20Java%20%282nd%20Edition%29.pdf)
- [Java之美[从菜鸟到高手演变]之设计模式](http://blog.csdn.net/zhangerqing/article/details/8194653)


## 文档
- [Fresco文档](http://www.fresco-cn.org/)
- [Glide 中文非官方文档](http://mrfu.me/2016/02/27/Glide_Getting_Started/)
- [Android 官方 API 文档](http://developer.android.com/reference/android/package-summary.html)(网站需要翻墙)
- [Android 官方培训课程中文版](http://hukai.me/android-training-course-in-chinese/index.html)(Google Android 官方培训课程翻译的中文版)


## 感谢
 - 感谢这么多伟大的开源者，感谢这么多伟大的开源公司，因为开源，世界变得更加美好。


## 联系我
 - Email:124746406@qq.com 
 - GitHub: [Forezp](https://github.com/forezp)
 - Blog : [csdn blog](http://blog.csdn.net/forezp)
 - 原文件: [AndroidMaterialLatest](https://github.com/forezp/AndroidMaterialLatest/issues)



