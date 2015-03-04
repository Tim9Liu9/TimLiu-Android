TimLiu-Android
==============

自己总结的Android开源项目及库 

###  目录
- [UI](#UI)
    
- [动画](#动画)

- [响应式编程](#响应式编程)

- [网络相关](#网络相关)
    
- [数据库](#数据库)
- [图像浏览及处理](#图像浏览及处理)
- [测试及调试](#测试及调试)
- [消息推送](#消息推送)
- [其他](#其他)
- [UI资源](#UI资源)
- [开发资源](#开发资源)
    - [他人开源总结](#他人开源总结)
    - [中文开发博客列表](#中文开发博客列表)

========
### 具体内容 =============================
========
#### UI
* [awesome-android-ui](https://github.com/wasabeef/awesome-android-ui) - ui库，非常多的ui及特效。
* [PagerSlidingTabStrip](https://github.com/jpardogo/PagerSlidingTabStrip) - 一个支持Material Design的PagerSlidingTabStrip。
* [ChipsLibrary](https://github.com/AndroidDeveloperLB/ChipsLibrary) - 在Android EditText中实现打Tag功能。
* [bitmapMesh](https://github.com/7heaven/bitmapMesh) - 拉窗帘效果。
* [ObservableScrollView](https://github.com/ksoichiro/Android-ObservableScrollView) - 在滚动的视图观测滚动事件的Android库
它易于与在Android 5.0 Lollipop中引入的工具条Toolbar相交互，并能够帮助实现Material Design apps的外观。
* [iconify](https://github.com/JoanZapata/android-iconify) - iconify 图片与文字同一行显示。
* [iosched](https://github.com/google/iosched) - The Google I/O 2014 Android App，Android 5.0 and Material Design。
* [MaterialList](https://github.com/dexafree/MaterialList) - MaterialList 。
* [material design card](https://dribbble.com/search?q=material+design+card) - material design card 。 
* [NavigationDrawer-MaterialDesign](https://github.com/rudsonlive/NavigationDrawer-MaterialDesign) - 一个Material Design的抽屉模板库，分分钟搭起一个程序框架。
* [MaterialEditText](https://github.com/rengwuxian/MaterialEditText) - 直接继承EditText，无需修改Java文件即能实现自定义控件颜色， [直接拿来用！十大Material Design开源项目](http://www.csdn.net/article/2014-11-21/2822753-material-design-libs)。
* [fab](https://github.com/shell-software/fab) - Floating Action Button library for Android。
* [labelview](https://github.com/linger1216/labelview) - 贴纸效果，如：淘宝商品侧贴折扣。
* [SearchMenuAnim](https://github.com/kongnanlive/SearchMenuAnim) - 一个很棒的带动画的搜索框。
* [快速支持emoji表情显示](http://www.eoeandroid.com/thread-567299-1-1.html) - 让项目快速支持emojicon表情的显示，并可判断用户输入的内容中是否含有emojicon表情以及过滤掉emojicon。
* [Side-Menu.Android](https://github.com/Yalantis/Side-Menu.Android) - 分类侧滑菜单。
* [Context-Menu.Android](https://github.com/Yalantis/Context-Menu.Android) - 可以方便快速集成漂亮带有动画效果的上下文菜单。
* [Pull-to-Refresh.Rentals-Android](https://github.com/Yalantis/Pull-to-Refresh.Rentals-Android) - 提供一个简单可以自定义的下拉刷新实现。
* [Titanic](https://github.com/RomainPiel/Titanic) - 可以显示水位上升下降的TextView。
* [AndroidSwipeLayout](https://github.com/daimajia/AndroidSwipeLayout) - 滑动Layout，支持单个View，ListView，GridView，[demo-apk](https://github.com/daimajia/AndroidSwipeLayout/releases/download/v1.0.0/AndroidSwipeLayout-Demo-1.0.1-snapshot.apk)。
* [android-typeface-helper](https://github.com/norbsoft/android-typeface-helper) - Android Typeface Helper 可以帮你轻松实现自定义字体的库。
* [android-lockpattern](https://code.google.com/p/android-lockpattern/) - Android的图案密码解锁, [文档介绍](https://code.google.com/p/android-lockpattern/wiki/QuickUse)。
* [ToggleButton](https://github.com/zcweng/ToggleButton) - 状态切换的 Button，类似 iOS，用 View 实现。
* [android-typeface-helper](https://github.com/norbsoft/android-typeface-helper) - Android Typeface Helper 可以帮你轻松实现自定义字体的库。
* [GuideBackgroundColorAnimation](https://github.com/TaurusXi/GuideBackgroundColorAnimation) - 实现滑动ViewPager渐变背景色。


##### 下拉刷新

##### 模糊效果

* [Android Wheel](https://code.google.com/p/android-wheel/) - 带有刻度的旋转器：日历、三级联动

##### HUD与Toast



========
#### 动画
* [SwitchLayout](http://blog.csdn.net/jay100500/article/details/42227365) - 国内开发者， Android的Activity切换动画特效库SwitchLayout，视图切换动画库，媲美IOS。 
* [ActivityOptionsICS](https://github.com/tianzhijiexian/ActivityOptionsICS) - 一个低版本activity动画兼容库——ActivityOptionsICS，可以很好的实现MD的动画效果。
* [SwipeBack](https://github.com/liuguangqiang/SwipeBack) - 一个可以通过手势返回到上一个Activity的开源库，支持上下左右四个方向返回，支持多个View为Child。

========
#### 网络相关
##### 网络连接


##### 图像获取
* [glide](https://github.com/bumptech/glide) - glide 。
* [Universal Image Loader](https://github.com/nostra13/Android-Universal-Image-Loader) - Universal Image Loader 是一个强大的、可高度定制的图片缓存，简称：UIL，可以高度配置的网络图片缓存库，非常灵活，用户量最多 。
* [picasso](https://github.com/square/picasso) - picasso 功能单一，没有缓存过期，同androidQuery一样链式调用，载入本地文件速度慢（没有生成thumbnails） ,[Picasso and Android-Universal-Image-Loader](http://donal-tong.github.io/blog/2014/05/21/picasso-and-auil/),另外的一些诸如裁剪图片：Picasso.with(context)  .load(url)  .resize(50, 50)  .centerCrop()  .into(imageView)。
* [ImageLoader](https://github.com/novoda/ImageLoader) - ImageLoader 。
* [Volley](https://github.com/mcxiaoke/android-volley) - Volley 综合框架,包含图片部分。
* [enif](code.google.com/p/enif/) - enif 。


##### 响应式编程
* [RxAndroid](https://github.com/ReactiveX/RxAndroid/) - RxAndroid：函数响应式编程 。
* 


========
##### 网络测试


========
#### 数据库
* [ORMLite](http://ormlite.com/sqlite_java_android_orm.shtml) - ORMLite做的最棒但是学习成本有点儿高，ORMLite的文档有点儿烂。
* [SugarORM](http://satyan.github.io/sugar/index.html) - SugarORM比较轻便， 支持Has a 和 Has many映射，但无法保存集合，没有映射关系。
* [GreenDAO](http://greendao-orm.com/) - GreenDAO要先建立一个java项目来生成对应的表，一变动又要生成，很不方便。
* [ActiveDriod](https://github.com/pardom/ActiveAndroid) - ActiveDriod也不错 [官网](http://www.activeandroid.com/)。
* [ORMDroid](https://github.com/roscopeco/ormdroid) - ormdroid 。
* [sqlbrite](https://github.com/square/sqlbrite) - 良心企业Square的又一开源项目，当你不想给用ContentProvider，只想简单监听SQLite表增删改的数据变更时可以试试它。

========
#### 图像浏览及处理
* [MPAndroidChart](https://github.com/ggchxx/MPAndroidChart) - MPAndroidChart是一个功能强大的图表开源类库：曲线图、柱形图、环形图。
* [XCL-Charts](https://github.com/xcltapestry/XCL-Charts) - (国人开发)基于Android Canvas来绘制各种图表,使用简便,定制灵活。
* [WilliamChart](https://github.com/diogobernardino/WilliamChart) - 绘制图表的库，支持LineChartView、BarChartView和StackBarChartView三中图表类型，并且支持 Android 2.2及以上的系统。
* [CropImageView](https://github.com/cesards/CropImageView) - 原生ImageView只支持centerCrop，这里有支持9个方向裁剪的ImageView。
* [DrawableView](https://github.com/PaNaVTEC/DrawableView) - DrawableView实现画板功能，可以改变画笔粗细，颜色，支持撤销功能。 


========
#### 测试及调试




========
#### 消息推送
##### 客户端

##### 服务器端

#### 其他
* [java-zhconverter](http://code.google.com/p/java-zhconverter/) - java-zhconverter是一个简繁体中文互换的Java开源类库。
* [joda-time-android](https://github.com/dlew/joda-time-android) - 一个超赞的时间处理的库，Joda-Time ！ 他能帮你轻松处理时区，处理时间加减，计算到期时间等等场景下的问题。[java版本](http://www.joda.org/joda-time/key_partial.html)
* [AssistiveTouch](https://github.com/luozi/AssistiveTouch) - 配合Android手机沉浸式隐藏虚拟按键后快捷操作 (Nexus5屏幕变大了)。
* [S-Tools](https://github.com/naman14/S-Tools) - S-Tools一个可以实时查看的CPU状态和手机各类传感器数据，还有一些例如颜色选择、指南针和设备信息等功能。
* [JsBridge](https://github.com/lzyzsd/JsBridge) - 模仿微信webview的JsBridge，安全方便的实现js和Java的互相调用，主要通过loadUrl和shouldOverrideUrl实现。
* [android-best-practices](https://github.com/futurice/android-best-practices) - android最佳实践。
* [Sample Of All Samples](https://github.com/MostafaGazar/soas) - 提供大部分Android5.0组件的示例应用。


========
### UI资源
* [fontawesome](http://fontawesome.io/icons/) - Font-Awesome图标。
* [material-design-responsive-design](http://www.uisdc.com/material-design-responsive-design) - 深聊Material Design复杂响应式设计，[comprehensive-material-design-note](http://www.uisdc.com/comprehensive-material-design-note) - 帮你全面彻底搞定Material design的学习笔记。


========
#### 开发资源
##### 他人开源总结
* [awesome-java](https://github.com/akullpp/awesome-java) - java库列表，[中文版](http://app.memect.com/doc/android.html)。
* [material design 的android开源代码整理](https://github.com/soyoungboy/android-material-design-Open-source-projects/blob/master/README.md) - material design 的android开源代码整理。
* [Android开源项目分类汇总](https://github.com/Trinea/android-open-project) - [Trinea](http://www.trinea.cn/) 国内最多好的开源库总结。  [Android 开源库获取途径整理](http://www.trinea.cn/android/android-open-project-summary/)
* [Android开源库源码分析](https://github.com/android-cn/android-open-project-analysis) - [Trinea](http://www.trinea.cn/) 我们从 Android 开始建了了协作项目，从简介、总体设计、流程图、详细设计全方面分析开源库源码。目前第一期完成，包括10个开源库及5个公共技术点的全面介绍。  [在线网页](http://www.codekk.com/open-source-project-analysis)

* [年薪30万的Android程序员必须知道的帖子](http://www.itlanbao.com/forum.php?mod=viewthread&tid=45&fromuid=1) - Android开源项目汇总，带效果gif图。


* [Android官方培训课程中文版](https://github.com/kesenhoo/android-training-course-in-chinese) - Google Android官方培训课程中文版。


* [GitHub优秀Android开源项目](http://www.cnblogs.com/hawkon/p/3593709.html) - GitHub 优秀的 Android 开源项目,很多中文现成项目。

* [Android开发工具及文档](http://www.androiddevtools.cn/) - 收集整理Android开发所需的Android SDK、开发中用到的工具、Android开发教程、Android设计规范，免费的设计素材等。

* [material_design](https://github.com/1sters/material_design_zh) - eoeAndroid Material Design 中文协同翻译。
* [Android-Open-Sourse-Library](https://github.com/1sters/Android-Open-Sourse-Library/) - eoeAndroid 开源组件深度剖析: 1.Http请求组件:Volley\android-async-http\okhttp 2.json数据解析组件:Gson\fast-json\json-smart\Jackson。
* [wiki-eoeandroid](http://wiki.eoeandroid.com/) - wiki-eoeandroid : Android Develop - 开发技术、Android Design - 设计规范、Android Distribute - 软件发布 。

* [Java资源大全](http://www.importnew.com/14429.html) - 国外程序员整理的Java资源大全。


##### 中文开发博客列表
* [donal-tong](http://donal-tong.github.io/) - Android [ListView or GridView for ScrollView](http://donal-tong.github.io/blog/2014/05/28/listview-for-scrollview/). 
* [脉脉不得语](http://www.inferjay.com/) - Android开发周报
 
