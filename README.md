# Awesome Tester

一个精心策划的软件测试资源清单，包括测试工具、测试框架、学习资源和测试网站。

灵感来源于 [awesome-python](https://github.com/vinta/awesome-python)

- [测试工具](#测试工具)
    - [抓包工具](#抓包工具)
    - [接口工具](#接口工具)
    - [压力测试](#压力测试)
    - [Android测试工具](#Android测试工具)
    - [iOS测试工具](#iOS测试工具)
    - [Web测试工具](#Web测试工具)
    - [自动化工具](#自动化工具)
    - [IDE工具](#IDE工具)
    - [编译/反编译](#编译/反编译)
    - [终端](#终端)
    - [云测](#云测)
    - [数据库](#数据库)
    - [移动端性能](#移动端性能)
    - [监控/报表](#监控/报表)
    - [用例设计](#用例设计)
    - [测试环境](#测试环境)
    - [持续集成](#持续集成)
    - [项目管理](#项目管理)
    - [在线文档](#在线文档)
    - [版本控制](#版本控制)
    - [安全测试](#安全测试)
    - [代码扫描](#代码扫描)
- [测试框架](#测试框架)
    - [整站项目](#整站项目)
    - [前端模版](#前端模版)
    - [后端项目](#后端项目)
- [学习资源](#学习资源)
    - [视频资源](#视频资源)
    - [测试书籍](测试书籍)
    - [编程学习](#编程学习)
    - [面试相关](#面试相关)
- [测试网站](#测试网站)
    - [测试社区](#测试社区)

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
* [Locust](https://www.locust.io/) - 开源的压测工具
* [go-stress-testing](https://github.com/link1st/go-stress-testing) - 基于Go语言开发的开源压测工具
* [ab](http://httpd.apache.org/) - ab是apache自带的压力测试工具
* [pts](https://www.aliyun.com/product/pts) - 阿里云的商业压测软件
* [wrk](https://github.com/wg/wrk) - C语言开源压测工具

## Android测试工具

*移动端测试工程师常用的 Android 测试工具*

- [adb](https://developer.android.com/studio/command-line/adb.html) - Android 调试桥，Android SDK自带的调试工具
- [Android Studio](https://developer.android.google.cn/studio/) - Android IDE工具，自带调试功能
- [aapt]() - Android 资源包管理工具，Android SDK自带的工具
- [Chrome Inspect](chrome://inspect/#devices) - Chrome浏览器调试 Android webview 的工具
- [uiautomatorviewer](https://android-sdk.en.softonic.com/mac) - Android 控件树定位工具，Android SDK自带

## iOS测试工具

*移动端测试工程师常用的 iOS 测试工具*

* [libimobiledevice](https://github.com/libimobiledevice/libimobiledevice) - 与iOS设备进行通信的跨平台协议库
* [pymobiledevice](https://github.com/iOSForensics/pymobiledevice) - libimobiledevice的Python实现
* [imobiledevice](http://docs.quamotion.mobi/docs/imobiledevice/download/) - Quamotion提供的libimobiledevice的Windows平台可执行版本
* [XCode](https://developer.apple.com/xcode/) - iOS IDE工具，自带调试功能
* [XCTest](https://developer.apple.com/documentation/xctest) - iOS 单元测试工具
* [testflight](https://testflight.apple.com/) - iOS 灰度测试工具

## Web测试工具

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
- [按键精灵](http://www.anjian.com/download.htm) - Windows 自动化工具
- [PyAutoGUI](https://muxuezi.github.io/posts/doc-pyautogui.html) - Python库，可以模拟鼠标键盘操作
- [uiautomator2](https://github.com/openatx/uiautomator2) - 基于 Python 的 UI 自动化测试框架，可支持 Android/iOS
- [wda](https://github.com/facebookarchive/WebDriverAgent) - facebook 开源的 iOS 自动化测试工具
- [ATX](https://github.com/NetEaseGame/ATX) - 基于图像识别完成游戏的自动化操作
- [Appetizer](https://www.appetizer.io/) - 移动开发智能化平台，集成多种移动端测试套件
- [Airtest](http://airtest.netease.com/) - 网易开源的游戏自动化测试工具
- [unittest](https://docs.python.org/3/library/unittest.html) - 基于 Python 的单元测试工具，常用于管理自动化测试用例
- [Pytest](https://learning-pytest.readthedocs.io/zh/latest/) - 基于 Python 的单元测试工具，常用于管理自动化测试用例
- [Junit](https://junit.org/junit5/) - 基于 Java 的单元测试工具，常用于管理自动化测试用例
- [TestNG](https://testng.org/doc/) - 基于 Java 的单元测试工具，常用于管理自动化测试用例
- [Allure](https://docs.qameta.io/allure/#_about) - 自动化报告生成框架（搭配 Pytest 使用）
- [HTMLTestRunnerCN](https://github.com/findyou/HTMLTestRunnerCN) - 自动化报告生成框架（搭配 unittest 使用）

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

*常用的数据库连接工具*

- 关系型数据库
  - [Navicat](http://www.navicat.com.cn/) - 数据库可视化工具
  - [phpMyAdmin](https://www.phpmyadmin.net/) - MySQL管理平台
  - [Hue](https://gethue.com/) - 大数据交互平台
- 非关系型数据库
  - [Robo 3T](https://robomongo.org/download) - MongoDB可视化工具
  - [RDM](https://redisdesktop.com/) - Redis可视化工具

## 移动端性能

*移动端性能测试工具*

- [Monkey](https://developer.android.com/studio/test/monkey.html) - Android adb自带的稳定性测试工具
- [WeTest助手](https://wetest.qq.com/cloud/help/effective) - WeTest平台出品的APP性能数据采集工具
- [GT](https://github.com/Tencent/GT) - 腾讯开源的APP的性能监控工具
- [Emmagee](https://github.com/NetEase/Emmagee) - 网易开源的APP性能监控工具
- [PerfDog](https://perfdog.qq.com/) - 腾讯WeTest出品的性能数据采集/分析工具，支持 Android/iOS
- [Xcode Instruments](https://help.apple.com/instruments/mac/10.0/) - Xcode自带的性能调试工具集
- [SoloPi](https://github.com/alipay/SoloPi) - 支付宝开源的Android自动化工具，支持用作性能测试
- [AppCrawler](https://github.com/seveniruby/AppCrawler) - 一个 Scala 编写的 APP 自动遍历工具，支持 Android/iOS
- [UiCrawler](https://github.com/lgxqf/UICrawler) - 基于Appium的 App UI 遍历 & Monkey工具 (支持操作步骤回放)
- [Maxim](https://github.com/zhangzhao4444/Maxim) - 基于遍历规则的高性能Android Monkey

## 监控/报表

*监控和报表工具*

- [Grafana](https://grafana.com/) - Go编写的开源可视化指标监控平台
- [Sentry](https://sentry.io/welcome/) - 开源的日志记录和监控平台
- [Echart](https://echarts.apache.org/zh/index.html) - Apache开源的前端图表可视化工具
- [Allure](https://docs.qameta.io/allure/#_about) - 自动化报告生成框架（搭配 Pytest 使用）
- [HTMLTestRunnerCN](https://github.com/findyou/HTMLTestRunnerCN) - 自动化报告生成框架（搭配 unittest 使用）
- [Fabric](https://get.fabric.io/) - APP开发平台，可以监控Crash及APP版本数据
- [Tableau](https://www.tableau.com/) - 数据分析和可视化工具

## 用例设计

*用例设计常用工具*

- [Xmind](https://www.xmind.net/) - 思维脑图形式的用例编写工具
- [Excel](https://www.microsoft.com/zh-cn/microsoft-365/excel) - 表格形式的用例编写工具 
- [behave](https://pypi.org/project/behave/) - python 的 BDD 库，用例组织
- [禅道](https://www.zentao.net/) - 项目管理平台，也支持用例管理
- [kityminder](https://github.com/fex-team/kityminder) - 百度脑图开源版本，支持二开和本地化部署

## 测试环境

*测试环境维护常用工具*

- [Ansible](https://www.ansible.com/) - 流行的自动化运维工具
- [fabric](http://www.fabfile.org/) - 非编译型语言部署工具
- [Docker](https://www.docker.com/) - 开源的应用容器引擎
- [k8s](https://www.kubernetes.org.cn/k8s) - 容器化应用管理云平台解决方案
- [uWSGI](https://uwsgi-docs.readthedocs.io/en/latest/) - 一个Python Web服务器
- [Nginx](http://nginx.org/en/) - 高性能的HTTP和反向代理web服务器
- [walle](http://www.walle-web.io/) - 高颜值项目部署系统

## 持续集成

*常用的持续集成工具*

- [Jenkins](https://www.jenkins.io/) - 最主流的持续集成工具

## 项目管理

*业内常用的项目管理软件*

- [Jira]() - Atlassian公司出品的项目与事务跟踪工具，也是目前最流行的项目管理工具
- [禅道](https://www.zentao.net/) - 项目管理平台
- [普兰能效平台](https://github.com/purang-fintech) - 开源的效能平台，支持本地化部署和二次开发
- [tower](https://tower.im/) - 团队和项目管理平台

## 版本控制

*业内主流的代码版本管理工具*

- [Git](https://git-scm.com/) - 开源的分布式版本控制系统
- [Gitlab](https://about.gitlab.com/) - 支持本地化部署的Git项目托管平台
- [Github](https://github.com/) - 面向开源及私有软件项目的托管平台
- [Gitee](https://gitee.com/) - 码云，面向中国国内的软件项目的托管平台
- [SVN](https://tortoisesvn.net/) - 一个开放源代码的中心化的版本控制系统

## 安全测试

*业界知名的安全测试工具精选*

- [AppScan](https://www.ibm.com/developerworks/cn/downloads/r/appscan/learn.html) - IBM 网络安全测试工具
- [Nmap](https://nmap.org/) - 网络扫描和嗅探工具包
- [sqlmap](http://sqlmap.org/) - sql 注入漏洞检查工具
- [nessus](https://zh-cn.tenable.com/products/nessus?tns_redirect=true) - 目前全世界最多人使用的系统漏洞扫描与分析软件
- [Drozer]() - Android 渗透测试工具
- [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF) - 移动端应用安全问题检测框架和工具（支持Android/iOS）
- [QARK](https://github.com/linkedin/qark) - Linkin 开源的一款静态代码分析工具

## 代码扫描

*业界知名的代码扫描工具*

- [SonarQube](https://www.sonarqube.org/) - 代码质量管理平台
- [QARK](https://github.com/linkedin/qark) - Linkin 开源的一款静态代码分析工具
- [ESLint](https://eslint.bootcss.com/) - JavaScript 语法规则和代码风格的检查工具
- [Jlint](http://jlint.sourceforge.net/) - Java 语法规则和代码风格的检查工具
- [p3c](https://github.com/alibaba/p3c) - 阿里巴巴 Java 代码风格检查工具
- [pylint](https://www.pylint.org/) - Python 语法规则和代码风格检查工具

# 测试框架

## 整站项目

*测试平台整站项目*

- [metersphere](https://github.com/metersphere/metersphere) - 一站式的开源企业级持续测试平台
- [普兰能效平台](https://github.com/purang-fintech) - 开源的效能平台，支持本地化部署和二次开发
- [sosotest](https://github.com/LianjiaTech/sosotest) - 贝壳找房测试团队开源的整站接口自动化测试平台，支持 HTTP 和 DUBBO
- [LuckyFrameWeb](https://gitee.com/seagull1985/LuckyFrameWeb) - 开源自动化测试平台
- [HttpRunner](https://github.com/HttpRunner/HttpRunner) - HttpRunner 是一款面向 HTTP(S) 协议的通用测试框架
- [ATX-Test](https://github.com/pengchenglin/ATX-Test) - 基于ATX-Server的UI自动化测试框架，目前也支持运行Monkey
- [APT](https://github.com/ooqitech/ATP) - Flask + vue.js 的测试服务平台

## 前端模版

- [Vue-element-admin](https://github.com/PanJiaChen/vue-element-admin) - 基于 vue.js 和 ElementUI 的后台管理系统前端脚手架项目
- [inspinia](https://github.com/Chuibility/inspinia) - 基于 Bootstrap 的后台管理系统前端框架模版
- [xenon](https://github.com/GroupOfStar/xenon) - 基于 Bootstrap 的后台管理系统前端框架模版
- [lin-cms-vue](https://github.com/TaleLin/lin-cms-vue) - 林间有风团队开源，cms后台工程，前端部分

## 后端项目

- [lin-cms-springboot](https://github.com/TaleLin/lin-cms-spring-boot) - 林间有风团队开源，cms后台工程，后端 Java
- [lin-cms-flask](https://github.com/TaleLin/lin-cms-flask) - 林间有风团队开源，cms后台工程，后端 Python
- [lin-cms-koa](https://github.com/TaleLin/lin-cms-koa) - 林间有风团队开源，cms后台工程，后端 Node.js

# 学习资源

## 视频资源

- [程序员臻叔](https://space.bilibili.com/382166537) - B站上测试开发领域的小UP主
- [Python移动自动化测试面试](https://coding.imooc.com/class/182.html) - 慕课网无线测试面试

## 学习路线

- [测开学习路线](https://mp.weixin.qq.com/s/H6ULJUe30REadme9-7wKGQ) - 从0开始，入职大厂测试开发学习路线
- [测试开发技术图谱](https://camo.githubusercontent.com/d1064bfadc97d2a7f3491aa4c6e545a9aba8ea66/687474703a2f2f7777312e73696e61696d672e636e2f6c617267652f36396235373764346779316735726471636372366c6a32307a6b316561616c302e6a7067) - 霍格沃滋测试学院出品

## 测试书籍

- [测试开发必读书单](https://mp.weixin.qq.com/s/LKG0PBGkUR1qlsBZ769EJw) - 软件测试必读的48本书

## 编程学习

- [菜鸟教程](https://www.runoob.com/) - 基本上涵盖了大多数的主流编程语言的教程
- [廖雪峰Python](https://www.liaoxuefeng.com/wiki/1016959663602400) - python基础知识教程，学完应该能入门了
- [Python3高级核心技术97讲](https://coding.imooc.com/class/200.html) - 慕课网 Python 进阶最优视频
- [廖雪峰Git](https://www.liaoxuefeng.com/wiki/896043488029600) - 优质 Git 教程
- [How2J](https://how2j.cn/) - 优质 Java 教程
- [Mall](https://github.com/macrozheng/mall) - 优质Java项目，SpringBoot + Mybatis
- [JavaGuide](https://github.com/Snailclimb/JavaGuide) - 「Java学习+面试指南」一份涵盖大部分Java程序员所需要掌握的核心知识。
- [JavaGuide 面试突击版](https://github.com/Snailclimb/JavaGuide-Interview) - Java 面试突击版  

## 面试相关

- [牛客网](https://www.nowcoder.com/) - 刷题、面经
- [leetcode](leetcode) - 算法学习、算法面试题
- [测试开发面试专辑](https://mp.weixin.qq.com/mp/appmsgalbum?action=getalbum&__biz=MzAxMTA2OTY0Nw==&scene=1&album_id=1485856836774838273#wechat_redirect) - 程序员臻叔面试专辑汇总
- [测试开发面试复习资料](https://github.com/GitDzreal93/dev-tester) - 测试开发面试资源、复习资料汇总
- [500丁简历](https://www.500d.me/) - 简历模版
- [ResumeSample](https://github.com/geekcompany/ResumeSample) - 程序员简历模版
- [冷熊简历](http://cv.ftqq.com/?fr=github) - 冷熊简历md格式 

# 测试网站

## 测试社区

- [TesterHome](https://testerhome.com/) - 中国最好的测试社区