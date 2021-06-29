
<!--
**zhangkn/zhangkn** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
![微信搜一搜公众号：iOS逆向](https://img-blog.csdnimg.cn/20210628165010364.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3UwMTEwMTg5Nzk=,size_16,color_FFFFFF,t_70#pic_center)



### 👋你好，欢迎 👻


<img align="right" src="https://img-blog.csdnimg.cn/20210628165010364.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3UwMTEwMTg5Nzk=,size_16,color_FFFFFF,t_70#pic_center" />

- 🔭 I’m currently working on [blog](https://kunnan.blog.csdn.net)
- 🌱 I’m currently learning [LLVM](https://llvm.org)
- 👯 I’m currently learning [Swift](https://swift.org)
- 🤔 I’m currently learning [frida.re](https://frida.re)
- 📫 How to reach me: [About](https://blog.csdn.net/z929118967/article/details/107957165)


[![csdn](https://img.shields.io/badge/-csdn-c14438?style=flat-square&logo=c&logoColor=white)](https://kunnan.blog.csdn.net)
[![Gmail Badge](https://img.shields.io/badge/-gmail-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:929118967@qq.com)](mailto:929118967@qq.com)


- 公众号【微信搜一搜：iOS逆向】

# 工作经验 



## 2018年-11月-至今 



### 全城淘信息技术服务有限公司



* 负责新版的全城淘 AppV3.0的整体功能开发(V3.0.0-3.1.1)：
  * 采用MVVM，支持中英文版本切换、新增购物车、收款信息、收银台模块
  * 新增注册模块、防止crash框架；适配iOS13API，提高app整体的操作流畅度和UI用户体验;
  * 负责蓝牙标签打印、票据打印模块（码牌等不具备打印功能的设备，收款成功时在蓝牙打印机打印）； 负责有品的开单模块（购物车、SKU、下单、结算、订单捡起、退款、退货、打印小票）、无品的收银台流程、收款信息报表模块（账单流水、收款报表、收银员报表、终端报表）、店铺模块（快捷订单、销售订单、会员、商品管理）。
  * 新增商户开户申请模块，包括电子签名功能。解决iOS12以上版本app杀死之后无法播报问题，支持后台码牌语言播报。新增扫码支付防掉单功能(推送+递归轮循)。
* 负责淘管家CRM app 的框架搭建，包括以下功能的开发维护（V3.0.0-3.1.11）：
  * 代理商系统：商户进件、公海商户模块、待办事项模块、软件订单、订货单、终端绑定、终端维修、收费管理、报表模块（商户交易汇总、代理商交易汇总、终端激活汇总）
  * 解决进件协议照片模糊问题


## 2017年07月-2018年-11月

### 湖南微流网络科技有限公司 

> - 主要负责逆向分析，开发iOS加固产品；越狱环境下Tweak、守护进程的开发与维护，非越狱环境下dylib注入重签集成。具体的有：逆向系统应用,负责aso 项目;开发iOS逛有钱app、阿布云隧道 app 。
> - iOS&macOS应用逆向与安全工程师,高级iOS工程师:  
>   - 正向开发： iOS逛有钱app、阿布云隧道 app 。
>   - 逆向开发：利用[Hopper](https://kunnan.github.io/2018/07/02/Hopper/)、[class-dump](https://kunnan.github.io/2018/07/01/class-dump/)、[ios-ssl-kill-switch](https://kunnan.github.io/2018/05/30/ios-ssl-kill-switch/)、[Keychain-Dumper](https://kunnan.github.io/2018/05/30/Keychain-Dumper/)、[KNParseClangLib](https://github.com/zhangkn/KNParseClangLib)([MachOParser](https://github.com/AloneMonkey/iOSREBook/tree/master/chapter-8/8.3%20%E5%8A%A8%E6%80%81%E4%BF%9D%E6%8A%A4/MachOParser))进行静态分析；使用[CycriptTricks](https://kunnan.github.io/2018/04/20/CycriptTricks/)（Powerful_private_methods）、[hookClass_knhook_hookClassLog](https://kunnan.github.io/2018/06/06/hookClass_knhook_hookClassLog/)、[UIButton_sendActionsForControlEvents](https://kunnan.github.io/2018/06/08/UIButton_sendActionsForControlEvents/)、[DerekSelander_LLDB](https://kunnan.github.io/2018/07/07/DerekSelander_LLDB/)(Python scripts to aid in your debugging sessions)、[frida](https://kunnan.github.io/2018/06/11/install_frida_on_device_and_mac/) 进行动态调试分；采用[Theos](https://kunnan.github.io/2018/06/07/Theos/)、[MonkeyDev](https://kunnan.github.io/2018/06/11/MonkeyDev_Tricks/)进行开发调试iphone/tool、iphone/tweak。
>   - [安全保护](https://kunnan.github.io/tags/#security)
>     - 静态混淆: [Static_obfuscation](https://kunnan.github.io/2018/08/17/Static_obfuscation/)
>     - [动态保护：反调试(`PT_DENY_ATTACH = 31`参数用于告诉系统阻止调试器的依附;利用`sysctl`函数查看当前进程信息，判断是否有此标志位来检测是否处理调试状态)、反反调试、反注入(`通过_dyld_get_image_name()获取加载的模块名，判断是否都在白名单中`)、hook检测（通过`dladdr`函数得到imp地址所在的模块`info.dli_fname`；遍历符号表中的每一个指针，然后判断指针是不是指向`__stub_helper`或者系统模块； 分析函数的内存前几条指令中有没有跳转）、完整性校验（检查文件load command 的修改，获取内存中运行代码的md5值；是否重签名，从可执行文件的LC_CODE_SIGNATURE 读取信息，拿到当前的签名文件的签名信息和编译前的签名信息比对；）](https://kunnan.github.io/2018/08/17/HookDetection/)
>     - 代码混淆：
>       - [静态库混淆：混淆带有bitcode的静态](https://kunnan.github.io/2018/08/20/Confusing_static_libraries_with_Bitcode_Sectname/)
>       - [采用LLVM针对源代码混淆](https://kunnan.github.io/2018/06/05/iosObfuscation/)



## 2013年09月-2017年07月 

### 湖南高阳通联信息技术有限公司 

IOS开发工程师、Java程序员

> - 负责iOS的app包括：和包商户版、和包客户端、和聚宝、和包刷卡、商户接入和包支付能力项目 以及为和飞信app 提供安全支付组件
>   - 对iOS商户和包支付插件项目进行代码重构，进行底层的网络框架进行封装。独立设计iOS应用架构。
> - java  服务端开发
>   - 对高阳ICS 金融平台有较深刻的理解，能熟练开发与第三方系统的接入接出接口
> - 主要职责：完成app的设计、开发、测试、修改bug等工作，包括业务需求的沟通，功能模块详细设计，业务功能实现与单元测试。
>   - 除了担任iOS工程师角色外，还担任过项目经理，以及维护支付平台的UI后台管理系统。UI对Portal、IPOS、SMS、Wap、CAS、IVR一共6个渠道提供了规则的配置。



# 项目经验 

## 2017年07月-至今 

### ASO(机刷)

> - 项目描述 : AppStore Search optimize
>   - 下载流程：清理进程和数据（包括修改设备信息）、切换IP、登录appID、打开App Store、在App Store搜索应用、下载并安装app（打码）、注销app ID、关闭App Store、卸载app
>   - 评论流程：在下载流程的基础上进行评论
> - 使用的技术( 部分）
>   - [Wi-Fi的切换和控制](https://zhangkn.github.io/2018/04/SBWiFiManager/)、IP的切换、图形验证码的识别。
>   - [使用制作 cydia repo 进行部署](https://zhangkn.github.io/2018/02/how_to_host_cydia_repo/) 
>   - [进程通信](https://zhangkn.github.io/2018/01/Inter-processCommunicationByRrocketbootstrap/)：[librocketbootstrap](http://iphonedevwiki.net/index.php/RocketBootstrap#How_to_use_this_library)
>   - [设备信息的修改](https://github.com/zhangkn/knaso/blob/master/ASO/ChangeCode/ChangeCode.m)：[`使用capstone 对二进制文件进行反汇编来定位方法的地址，以便于MSHookFunction `](https://kunnan.github.io/2018/07/16/capstoneHook64_capstoneHook32/)
>     - [`  MSHookFunction(&sysctlbyname, &new_sysctlbyname, &old_sysctlbyname);](https://kunnan.github.io/2018/08/24/macaddressOfJOJOWang/#hook)
> - 职责描述 ：
>   - 负责开发、维护、运维；其中包括适配最新的操作系统版本iOS11 
> - 项目业绩 ：
>   - 下载任务的成功率由40%提升到60%； 
>   - 优化打码流程，节约成本； 
>   - 优化进程间的通信； 
>   - 更换 cydia repo 的方式进行部署，降低运维成本； 
>   - 优化VPN的切换IP方式； 
>   - 新增网络等异常自动处理流程:自动设置永不锁屏；自动处理进程通信的问题；网络异常的时候自动关闭VPN（防止VPN有效性过期），并且自动断开Wi-Fi，再次重新连接（防止IP有效期超时）；重启sb、在sb 进行搭建操作界面等。

## 2017年10月-至今 

### app逆向开发(非越狱App集成、tweak)

- 项目描述： WeChat、Moon;macOS WeChat;逆向系统应用；实现一些特殊的功能。
- 职责描述：基于特殊app的现有功能，进行功能的优化延展以及关键数据的获取。
- 项目业绩：快速按时实现需求功能，集成tweak的App支持非越狱环境以及越狱环境，[支持多架构（arm_v7、arm64; 采用`lipo -create `解决 dumpdecrypted 之后的架构不匹配的问题）](https://kunnan.github.io/2018/07/01/dumpdecrypted/#%E8%A7%A3%E5%86%B3%E6%96%B9%E6%A1%88)。以及支持系统版本范围：V8-V12
- 使用的技术
  - 动态库的注入原理：
    - 一个是基于修改[Mach-O ](https://zhangkn.github.io/2018/03/Hopper/) 的Load Commands
    - 一个是利用环境变量DYLD_INSERT_LIBRARIES,例如使用它进行dumpdecrypted（补充：**Clutch** 通过`posix_spawnp`生成一个新的进程，然后暂停进程并dump内存）
    - 另一个是在挂载的进程上创建一个挂起的线程, 然后在这个线程里申请一片用于加载动态库的内存,然后恢复线程,动态库就被注入(通过 taskfor_pid函数获取目标进程句柄，然后通过在进程内创建新线程并执行自己的代码。) cycript 就是以这种方式执行脚本代码。
  - hook 的方式： fishhook（符号表替换）、cydia substrate: 
  - object-c 的运行时API： 动态新增属性(objc_setAssociatedObject、objc_getAssociatedObject)；修改和获取属性（class_getInstanceVariable、object_setIvar、object_getIvar）；swizzling交换替换方法的实现
  - [LLDB](https://github.com/zhangkn/LLDB)+[chisel](https://github.com/zhangkn/chisel)
    - [给/usr/bin/debugserver添加task_for_pid权限](https://blog.csdn.net/z929118967/article/details/78262460), 并开启` debugserver host:port --attach=<process_name>`(有五种启动方式：auto、posix、fork、backboard 、frontboard)，常用backboard 从头开始调试，例如进行[anti ptrace](https://kunnan.github.io/2018/08/17/Dynamic_protection/#ptrace)。
    - 使用symbolic breakpoint 进行条件断点。
  - 开发的ide和分析工具： theos、monkeydev、[lipo](https://kunnan.github.io/2018/07/01/dumpdecrypted/#vi-%E6%9E%B6%E6%9E%84%E4%B8%8D%E5%8C%B9%E9%85%8D%E7%9A%84%E6%97%B6%E5%80%99%E6%8A%A5mach-o-but-wrong-architecture)、[cycript](https://kunnan.github.io/2018/04/20/CycriptTricks/)、[hopper](https://kunnan.github.io/2018/07/02/Hopper/#修改汇编) 进行查看交叉引用，修改汇编、[frida-ios-dump](https://github.com/zhangkn/frida-ios-dump)、[mach-oView](https://kunnan.github.io/2018/05/29/Mach-O_introduce/#mach-o)、[KNtoggle-pie：changes the MH_PIE flag of the MACH-O header on iOS applications to disable ASLR on applications](https://github.com/zhangkn/KNtoggle-pie)、[AntiAntiDebug](https://github.com/AloneMonkey/MonkeyDev-Xcode-Templates/blob/master/MonkeyAppLibrary.xctemplate/AntiAntiDebug/AntiAntiDebug)

## 2017年07月-2017年10月 

### 阿布云隧道、 逛有钱 app

> - 项目描述：
>   - vpn类 app 阿布云隧道；导购返利类iOS app 逛有钱
> - 使用的技术：
>   - Swift、lua、iOS逆向开发、iOS正向开发、`git "https://github.com/zhuhaow/NEKit" "master"`(A toolkit for Network Extension Framework )、[gzip格式传输数据](https://github.com/zhangkn/MIFI-APP-IOS/blob/master/Roaming/General/Utils/DDGzip.h)
>   - ips 文件的分析： 主要分析3块，一块是Triggered by Thread线程的调用栈回溯信息，该部分保存了崩溃进程的所有线程的方法栈信息;一块是与架构相关崩溃的线程状态；最后是Binary Images信息;。[通过命令行工具 symbolicatecrash 来手动符号化 crash log
>   - [把函数名隐藏在结构体里,以函数指针成员的形式存储，编译后，只留了下地址。](https://blog.csdn.net/z929118967/article/details/83746545)
> - 职责描述 ：开发、维护
>   - AppStore应用协助审核，马甲包制作
>   - App代码加密和混淆工具开发；
>   - AppStore排行榜提升，ASO关键词优化；
>   - 阿里百川SDK 的集成
>   - iOS app  功能开发
> - 项目业绩： 完成app上线，在优化时期，对应的关键词排名前三



## 2016年02月-2017年07月 



### 和飞信（iOS APP） 

> - 项目描述: 和飞信是中国移动基础通信服务，力求满足客户基础通信升级和社交需求的新产品。
> - 职责描述 :
>   - 担任iOS工程师角色:负责和飞信中的扫码付、支付密码管理、绑卡、充流量、发红包功能，以静态库的形式提供
>   - 负责书写接入文档，维护技术方案文档，解决联调问题
> - 技术
>   - 支付插件中截图反馈功能的实现 `pod 'KNPodlib'`
>   - 设备信息的获取:除了使用_idfa、_idfv，  还使用`sysctl` 获取cpu、[macaddress](https://kunnan.github.io/2018/08/24/macaddressOfJOJOWang/)信息，以及使用[`sysctlbyname`](https://kunnan.github.io/2018/08/24/macaddressOfJOJOWang/#hook)获取设备型号等信息、  使用`CNCopyCurrentNetworkInfo`获取ssid、[bssid](https://kunnan.github.io/2018/08/24/bssid/)
>   - 关于设备ID的心得： 通过逆向研究，发现大部分的app设备ID以及OpenUDID都是基于CFUUIDCreate、CFUUIDCreateString 进行创建

## 2015年05月-2015年07月 

### 搭建一个提高开发效率的iOS静态库工程

> - 项目描述： 由于经常要以静态库的形式提供支付能力，因此搭建一个通用的效率调试静态库代码的工程模板是很有必要的
> - 职责描述 ：
>   - 负责完善此模板
> - 技术
>   - [搭建一个提高开发效率的iOS静态库工程](https://kunnan.github.io/2018/04/25/setup_Cocoa_Touch_Static_Library/)
>   - 这段期间的技术提升:对自定义控件、消息推送、通知、键盘处理、屏幕适配、iPad的开发等实用技术进行锻炼；加强自身对UIKit以及Map Kit的理解以及谓词NSPredicate技术的应用。
>   - 体会了真正的MVC思想：视图不依赖于具体的数据类型，而是依赖于遵守特定协议的数据源。
>     - [M 和V 是不存在依赖关系：就像UIKit中的UItableview一样，什么样的数据M，UItableview都可以展示，只要M遵守实现了UITableViewDataSource协议。](http://blog.csdn.net/z929118967/article/details/74066993)
>   - [最后发现如果使用采用 `pod lib` 开发并打包静态库也是很方便的](https://kunnan.github.io/2018/04/26/pod_lib_create/),并从此学会了[how_to_Using_CocoaPods](https://kunnan.github.io/2017/04/13/how_to_Using_CocoaPods/)

## 2015年03月-至今 

### 和包支付能力SDK（iOS CocoaTouchStaticLibrary） 

> - 项目描述 :主要用来向其它的应用程序提供便捷、安全以及可靠的支付服务。
> - 职责描述
>   - 担任iOS工程师角色。负责整个静态库工程的搭建，以及demo工程的创建
>   - 负责和包商户接入支付能力组件的问题解决。
>   - 维护接入文档，以及技术方案文档
> - 技术心得体会
>   - 体会了采用xcworkspace 进行对xcodeproj的管理的方便。
>   - 使用`pod lib`进行静态库的开发和打包

## 2015年01月-2017年07月

#### 和包商户版（iOS app） 

> - 项目描述 :中国移动面向手机用户及合作商户提供的一项综合性移动支付管理服务.
> - 职责描述 :负责整体app开发和维护
>   - 主要功能有消息中心，订单查询，订单消息推送功能、收款。
> - 业务上的收获
>   - 商户收款的流程：主要有扫码付、动态密码支付、客户端支付方式进行收款。
>     此项目嵌入的“我要开店”、“商户资料维护”功能模块 使用H5 实现，方便以后的功能更新;
> - 技术心得
>   - 使用coreData 实现消息中心的功能
>   - [使用了谓词技术](https://blog.csdn.net/z929118967/article/details/74066170)，实现按照日期分组订单列表
>   - 使用PushMeBaby工具调试消息推送
>   - 采用Charles工具进行问题分析，进行报文分析，修改报文进行开发以及单元测试
>   - 总结出app嵌入H5页面的通用模版
>     - `pod 'KNBaseWebViewController'`,主要适配webView使用相册的功能。

## 2014年01月-2017年-07月

### 和包支付（和包官方iOS客户端） 

> - 项目描述 :和包客户端是中国移动和包业务针对手机推出的综合性生活服务平台.和包已发展成为融合了支付、生活服务、购物等多个场景的开放性平台。用户可通过和包客户端在手机上不仅能使用中国移动提供的移动支付服务，如缴话费、收付款、生活缴费、订单支付等， 主要功能包括：
>   - 1、话费缴纳、流量充值； 
>   - 2、生活缴费（水费/电费/燃气费）；
>   - 3、收付款、订单支付、账户充值、提现、账户及交易明细查询、注册和更新；
>   - 4、在电子券商城购买商品
> - 职责描述: 担任iOS工程师角色，并担任V3.6-3.9 的项目经理。负责整个项目的进度、风险包括，协调厂商以及技术设计
> - 业务收获
>   - 收获了支付产品的业务知识：支付方式主要有有账户和无账户体系。这两个体系下有借记卡和贷记卡支付，以及快捷和无磁有密支付方式。
> - 技术
>   - 采用静态库的形式提供安全支付组件给主端集成。优化静态库工程的网络框架的代码，解决了由于更换第三方开源框架导致业务逻辑代码大范围修改的问题。
>   - 总结出一套，集成方唤起支付插件，以及支付插件自己退出界面的方法。

## 2013年11月-2014年01月 

### UI后台管理系统 

> - UI对Portal、IPOS、SMS、Wap、CAS、IVR一共6个渠道提供了规则的配置。包括商户的接入流程审核，用户的身份证审核，清结算、风控、银行入账规则的维护等等。
> - 职责描述 :
>   - 负责基础（用户和商户）模块的规则维护
>   - 包括以下需求的开发:
>     - 平台的报文验签
>     - 商户结算打款成功短信通知优化
>     - UI系统银行入账配置
>     - UI增加商户信用级别商户清单查询
>     - UI商户清单信息查询
>     - 2014现场商户线上签约协议优化
>     - UI系统客户端侧的CCA接口权限配置的快照改造
>     - 安卓3.9客户端启动页面配置
>     - 客户端公众服务号管理
>     - 公众服务消息推送列表查询。
> - 业务收获
>   - 熟悉并掌握了支付平台的支付流程、基础模块以及客户端模块的业务
> - 技术收获
>   - 对JS、JSP、SQL、Linux技术的进一步巩固.



## 2013年09月-2014年02月 

### 和包支付平台 (ICS)

> - 项目描述 : 中国移动面向个人和企业客户提供的一项综合性移动支付业务
> - 职责描述 : 担任java工程师。
>   - 在无线渠道部门，设计和开发移动客户端的接口，来满足app需求的开发。
>   - 通过此角色，能熟练使用高阳的ICS金融平台,对职责链模式有更深刻的理解。掌握了支付密码、登陆密码的加密、转加密流程。

# 技能清单

## 1、逆向开发技能

### 1.1 熟悉的领域 

> - iOS 逆向开发,熟悉`iphone/tweak`、`iphone/tool`、`cydia的repo 制作` 、`cocoapods的Specs repo制作`(using-pod-lib-create、private-cocoapods)、使用capstone 对二进制文件进行反汇编来定位方法的地址，以便于MSHookFunction 。
>
>   - 结合MachOView、class dump、tcpdump、Wireshark(rvictl)、nm、usbMuxd、lldb、Cycript、hopper、[KNHook](https://github.com/zhangkn/hookClass)、以及AFLEXLoader进行分析快速找到入口。

### 1.2 例子 

> - [iphone/tool 项目例子:DaemonDemo ](https://github.com/zhangkn/knDaemonDemo)
>
> - iphone/tweak类型举例：[tweak中使用WebSocket 的例子](https://github.com/zhangkn/KN_ws_tweak)


### 1.3 熟悉的iOS模块

> - <Foundation/NSTask.h>、SpringBoard
> - iOS PrivateFrameworks(MobileWiFi、SpringBoardServices、SSAccountStore、AppStoreDaemon)
> - [<mach-o/dyld.h>(_dyld_get_image_name)](https://kunnan.github.io/tags/#dyld)
> - jailbreak toolkit
>
>   - [Electra iOS 11.0 - 11.1.2 jailbreak toolkit:定制一些自己的功能]( https://github.com/jailbreakTool/KNelectra)
>
>   - [yalu102 iOS 10.0.0 -> iOS 10.2 : 修改jailbreak.m、dropbear，适配Xcode9 ；](https://github.com/jailbreakTool/KNyalu102)
>
>     - [ 替换掉一些过期的API(用peopen、posix_spawn来替换system)](https://zhangkn.github.io/2018/04/SystemIsUnavailable/)


## 2、 正向技能

> - 熟悉Swift/Objective C/Java，[cocoapods的Specs repo制作(using-pod-lib-create、private-cocoapods)](https://kunnan.github.io/tags/#CocoaPods)
>
>   - 1） 消息推送机制、KVC、KVO、[GCD(dispatch_group、semaphore)](https://github.com/idetool/JSPatch/blob/master/Extensions/JPDispatch.m)、block、CocoaPod、IAP内购、runtime、lldb、UIBackgroundModes、NSPredicate； 
>   - 2）[ iOS CocoaTouchStaticLibrary: 探索了出了一个提高静态库工程开发的搭建方法 ](https://github.com/zhangkn/KNCocoaTouchStaticLibrary)；目前比较喜欢using-pod-lib 进行静态库的开发、打包以及维护
>
> - 深入理解MRC和ARC内存管理机制；
>
>   - 1) 需要释放的资源：imageCache、queue、operations、view、通知监听者的移除、销毁soundID  
>   - 2） 释放的方法：dealloc 、applicationDidReceiveMemoryWarning、didReceiveMemoryWarning 
>   - 3）凡是函数名中带有create、copy、new、retain等字眼的，都应该在不需要它的时候进行release。 GCD的数据类型在ARC环境下不需要进行release；[而CF的数据类型在ARC、MRC环境下都需要做release的
>
> - 熟练使用AFNetworking, MBProgressHUD, MJRefresh, Masonry, SDWebImage等第三方库；熟悉Making CocoaPods；熟练使用git和svn等版本管理工具。
>
> - 良好的英文开发文档阅读能力、面向对象编程、链式编程以及常用的设计模式:MVC、职责链模式
>
> - [unix](https://github.com/zhangkn/KNBin) （文件目录结构、df、dm、sort、find、grep、cat、vi、ssh、scp） 
>
> - 对前端后台开发技术也有一定的了解；
>
>   - jQuery、JSP、css、html、数据库(sql基本操作)、j2ee(Spring + Struts +Hibernate)、tomcat



# 技术文章

- [安全相关的文章](https://kunnan.github.io/tags/#security)
  - [混淆带有bitcode sectname 的静态库](https://kunnan.github.io/2018/08/20/Confusing_static_libraries_with_Bitcode_Sectname/)
- [逆向相关的文章](https://kunnan.github.io/tags/#iosret)
  - [搭建私有Cydia源](https://kunnan.github.io/2018/04/20/how_to_host_cydia_repo/)
  - [Common hook methods in iOS](https://kunnan.github.io/2018/08/14/hook_methods_in_ios/)
  - [ 设备信息的修改：capstoneHook64_capstoneHook32 for libMobileGestalt](https://kunnan.github.io/2018/07/16/capstoneHook64_capstoneHook32/)

- [正向相关的文章](https://kunnan.github.io/tags/#CocoaTouchStaticLibrary)
  - [making_private_cocoapods](https://kunnan.github.io/2017/03/10/making_private_cocoapods/)
  - [how_to_Using_CocoaPods(翻译文章)](https://kunnan.github.io/2017/04/13/how_to_Using_CocoaPods/)
  - [搭建一个针对iOS静态库开发的主项目，提高开发效率，方便调试](https://kunnan.github.io/2018/04/25/setup_Cocoa_Touch_Static_Library/)
  - [git_subtree的使用例子](https://kunnan.github.io/2018/04/25/git_subtree/)
- [调试相关的文章](https://kunnan.github.io/tags/#Debug)
  - [CycriptUsefulCommand](https://kunnan.github.io/2018/06/23/CycriptUsefulCommand/)
  - [symbolicatecrash](https://zhangkn.github.io/2018/03/symbolicatecrash/)

# 培训经历

 2013.07-2014.01 中信软件教育中心 培训课程: java工程师

# 自我评价

- [充满激情的iOS逆向与安全工程师、高级iOS工程师](https://about.me/kunnan)

  - 1、有前后端开发经验者:`熟悉Object-C、Swift、lua、java、js开发以及iOS&macOS应用逆向与安全。`

    - 1 年的java开发经验，3年的iOS app 开发经验，2年的iOS&macOS 逆向开发经验

  - 2、近期的学习计划：x86和arm的指令集转换，参考Xcode模拟器的系统库;go 语言；常逛的技术论坛是http://iosre.com/。

  - 3 [实时更新的简历](https://github.com/zhangkn/zhangkn)、[整体的附件简历]( https://kunnan.github.io/resume/2018-11-07-Resume.pdf) 

# 致谢

感谢您花时间阅读我的简历，期待能有机会和您共事。
