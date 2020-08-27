# Awesome Tester

一个精心策划的软件测试资源清单，包括测试工具、测试框架、学习资源和测试网站。

灵感来源于 [awesome-python](https://github.com/vinta/awesome-python)

- [测试工具](#测试工具)
    - [抓包工具](#抓包工具)
    - [接口工具](#接口工具)
    - [压力测试](#压力测试)
    - [Android 测试工具](#Android 测试工具)
    - [iOS 测试工具](#iOS 测试工具)
    - [Web 测试工具](#Web 测试工具)
    - [自动化工具](#自动化工具)
    - [IDE工具](#IDE工具)
    - 编译/反编译
    - 终端
    - 云测
    - 数据库
    - 移动端性能
    - 监控/报表
    - 用例设计
    - 测试环境
    - 持续集成
    - 项目管理
    - 在线文档
    - 版本控制
    - 安全测试
    - 代码扫描
- 测试框架
    - 整站项目
    - 前端模版
    - 后端项目
- 学习资源
    - 视频资源
    - 测试书籍
    - 编程学习
    - 面试相关
- 测试网站
    - 测试社区
- 服务器
    - 

---

# 测试工具

## 抓包工具

*业内常用的抓包工具*

* [Charles](https://www.charlesproxy.com/) - 支持HTTP/HTTPS，支持Mock数据/弱网测试
* [Fiddler](https://www.telerik.com/fiddler) - 支持HTTP/HTTPS，支持Mock数据/弱网测试
* [Wireshark](https://www.wireshark.org/) - 网络封包分析软件，支持TCP、UDP等传输层协议抓包
* [mitmproxy](https://www.mitmproxy.org/) - 基于Python的网络抓包工具，支持HTTP/HTTPS，支持二次开发
* [anyproxy](https://github.com/alibaba/anyproxy) - 阿里巴巴开源，基于Node.js的网络抓包工具，支持HTTP/HTTPS，支持二次开发
* [Stream（iOS）](https://apps.apple.com/cn/app/stream/id1312141691) - iOS最好用的抓包工具，不用PC做代理
* [tcpdump](http://www.androidtcpdump.com/android-tcpdump/downloads) - 安卓抓包工具

## 接口工具

*业内常用的接口调试工具*

* [Postman](https://www.postman.com/) - 谷歌出品的优秀接口调试工具
* [Postwoman](https://github.com/hoppscotch/hoppscotch) - Postman开源替代品
* [Jmeter](https://jmeter.apache.org/) - Apache开源项目，适合压测/接口测试
* [Swagger](https://swagger.io/) - 丝袜哥，适配多种编程语言，接口文档和调试工具
* [Yapi](https://gitee.com/suxiaoxin123/yapi) - 接口管理平台，支持Mock数据，支持Postman/Swagger导入接口数据
* [requests](http://python-requests.org/) - python的HTTP请求库
* [grequests](https://github.com/spyoungtech/grequests) - requests + gevent for 异步 HTTP 请求库
* [aiohttp](https://github.com/aio-libs/aiohttp) - 基于python的asyncio的HTTP请求库

## 压测工具

*业内常用的压测工具*

* [Jmeter](https://jmeter.apache.org/) - Apache开源项目，适合压测/接口测试
* [Loadrunner](https://www.microfocus.com/en-us/products/performance-engineering/overview) - 老牌压测工具
* [go-stress-testing](https://github.com/link1st/go-stress-testing) - 基于Go语言开发的开源压测工具
* [ab](http://httpd.apache.org/) - ab是apache自带的压力测试工具
* [pts](https://www.aliyun.com/product/pts) - 阿里云的商业压测软件
* [wrk](https://github.com/wg/wrk) - C语言开源压测工具

## Android 测试工具

*移动端测试工程师常用的 Android 测试工具*

- [adb](https://developer.android.com/studio/command-line/adb.html) - Android 调试桥，Android SDK自带的调试工具
- [Android Studio](https://developer.android.google.cn/studio/) - Android IDE工具，自带调试功能
- [aapt]() - Android 资源包管理工具，Android SDK自带的工具
- [Chrome Inspect](chrome://inspect/#devices) - Chrome浏览器调试 Android webview 的工具
- [uiautomatorviewer](https://android-sdk.en.softonic.com/mac) - Android 控件树定位工具，Android SDK自带

## iOS 测试工具

*移动端测试工程师常用的 iOS 测试工具*

* [libimobiledevice](https://github.com/libimobiledevice/libimobiledevice) - 与iOS设备进行通信的跨平台协议库
* [pymobiledevice](https://github.com/iOSForensics/pymobiledevice) - libimobiledevice的Python实现
* [imobiledevice](http://docs.quamotion.mobi/docs/imobiledevice/download/) - Quamotion提供的libimobiledevice的Windows平台可执行版本
* [XCode](https://developer.apple.com/xcode/) - iOS IDE工具，自带调试功能
* [XCTest](https://developer.apple.com/documentation/xctest) - iOS 单元测试工具
* [testflight](https://testflight.apple.com/) - iOS 灰度测试工具

## Web 测试工具

*Web测试工程师常用的测试工具*

- [chrome](https://www.google.cn/chrome/) - 谷歌浏览器，F12 调试
- [firefox](http://www.firefox.com.cn/) - 火狐浏览器
- [IE](https://support.microsoft.com/zh-cn/help/17621/internet-explorer-downloads) - 远古时代的浏览器
- [Edge](https://www.microsoft.com/zh-cn/edge) - 微软出品的浏览器，IE的替代品
- [IETester](http://www.my-debugbar.com/wiki/IETester/HomePage) - 浏览器兼容性测试工具
- [Browsershots](http://browsershots.org/) - 在线的浏览器兼容性测试工具
- [在线工具](https://tool.lu/) - 实用在线小工具（json解析/时间戳/IP地址查询）

## 自动化工具

*常用的自动化测试底层框架（工具）*

- [Appium](http://appium.io/) - 最主流的 APP UI 自动化测试框架，可支持 Android/iOS
- [Selenium](http://www.selenium.org.cn/) - 最主流的 WEB UI 自动化测试框架
- [uiautomator2](https://github.com/openatx/uiautomator2) - 基于 Python 的 UI 自动化测试框架，可支持 Android/iOS
- [wda](https://github.com/facebookarchive/WebDriverAgent) - facebook 开源的 iOS 自动化测试工具
- [Appetizer](https://www.appetizer.io/) - 移动开发智能化平台，集成多种移动端测试套件
- [Airtest](http://airtest.netease.com/) - 网易开源的游戏自动化测试工具
- [unittest](https://docs.python.org/3/library/unittest.html) - 基于 Python 的单元测试工具，常用于管理自动化测试用例
- [Pytest](https://learning-pytest.readthedocs.io/zh/latest/) - 基于 Python 的单元测试工具，常用于管理自动化测试用例
- [Junit](https://junit.org/junit5/) - 基于 Java 的单元测试工具，常用于管理自动化测试用例
- [TestNG](https://testng.org/doc/) - 基于 Java 的单元测试工具，常用于管理自动化测试用例

## IDE工具

*常用的代码编写和调试工具*

- [IntelliJ IDEA](https://www.jetbrains.com/idea/) - Java 开发工具
- [PyCharm](https://www.jetbrains.com/pycharm/) - Python 开发工具
- [Jupyter Notebook](https://jupyter.org/install) - Python 算法/数据分析/可视化演示
- [PhpStorm](https://www.jetbrains.com/phpstorm/) - PHP（拍黄片） 开发工具
- [WebStorm](https://www.jetbrains.com/webstorm/) - 前端 开发工具
- [Goland](https://www.jetbrains.com/go/) - Go（够烂的） 开发工具
- [Android Studio](https://developer.android.google.cn/studio/) - Android 开发工具
- [XCode](https://developer.apple.com/xcode/) - iOS 开发工具
- [VSCode](https://code.visualstudio.com/) - 轻量级 开发工具
- [Visual Studio](https://visualstudio.microsoft.com/zh-hans/products/) - C/C++ 开发工具
- [Hbuider](https://www.dcloud.io/) - 轻量级 前端 开发工具
- [微信开发者工具](https://developers.weixin.qq.com/miniprogram/dev/devtools/download.html) - 微信小程序 开发工具
- [小程序开发者工具](https://render.alipay.com/p/f/fd-jwq8nu2a/pages/home/index.html) - 支付宝小程序 开发工具
- [sublime](http://www.sublimetext.com/) - 轻量级 开发工具

## 编译/反编译

*常用的代码编译和反编译工具*

- [Maven](https://maven.apache.org/) - Java 工程依赖管理和构建工具
- [Ant](http://ant.apache.org/) - Java 工程构建工具
- [Gradle](https://gradle.org/) - Java 工程依赖管理和构建工具
- [webpack](https://www.webpackjs.com/) - 前端资源加载/打包工具
- [npm](https://www.npmjs.com/) - Node.js包管理工具
- [gulp](https://www.gulpjs.com.cn/) - 前端 基于流的自动化构建工具
- [jd-gui](https://github.com/java-decompiler) - Java 反编译工具
- [ApkTool](http://ibotpeaches.github.io/Apktool/) - APK反编译工具
- [NET.Reflector](https://www.red-gate.com/products/dotnet-development/reflector/) - Unity安卓DLL代码文件反编译工具
- [AssetStudio](https://github.com/Perfare/AssetStudio) - Unity AssetBundle破解
- [dotPeek](http://www.jetbrains.com/decompiler/) - .NET 反编译工具

## 终端

*常用的终端连接工具*

- [Xshell](https://www.netsarang.com/zh/xshell/) - Windows 下好用的终端连接工具
- [SecureCRT](https://www.vandyke.com/download/securecrt/6.7/index.html) - Windows 下好用的终端连接工具
- [MobaXterm](https://moba.en.softonic.com/) -  Windows 下好用的终端连接工具
- [iTerm2](https://www.iterm2.com/) - MacOS 下最好用的终端连接工具

## 云测平台

*知名的云测平台（以及设备管理平台）*

- [STF](https://openstf.io/) - Web端知名的移动设备管理控制工具
- [Testin](https://www.testin.cn/) - 知名的商业测试平台
- [WeTest](https://wetest.qq.com/) - 腾讯质量开放平台
- [ATX-SERVER](https://github.com/openatx/atx-server) - Go语言编写的安卓设备集群管理
- [atxserver2](https://github.com/openatx/atxserver2) - ATX-SERVER 的 Python 版本

## 数据库

## 移动端性能

## 监控/报表

## 用例设计

## 测试环境

## 持续集成

## 项目管理

## 在线文档

## 版本控制

## 安全测试

## 代码扫描

# 测试框架

## 整站项目

## 前端模版

## 后端项目

# 学习资源

## 视频资源

## 测试书籍

## 编程学习

## 面试相关

# 测试网站

## 测试社区

## 服务器环境