## IoT 笔记
> 40 年前热衷于硬件的创客们成就了个人电脑辉煌年代，统一的闭源系统使得软件业高速发展。如今，热衷于开源硬件的创客们姗姗来临，五花八门的智能硬件层出不穷，又一个辉煌年代。我在这里做点记录。GitHub：[ideaTouch/IoTNotes](https://github.com/ideaTouch/IoTNotes)，
微博：[@IoT笔记](http://weibo.com/u/5592401903)

### 开发板一览

平台商 | 开发板 | 操作系统 | 开发工具 | 常用语言 | 通讯协议 | 文档 |备注
------------ | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | -------------
[Auduino](http://www.arduino.cc/)|[Arduino](http://www.arduino.cc/en/Main/Products)|RTOS|[Auduino IDE](http://www.arduino.cc/en/Main/Software/)|C/C++|[Firmata](http://www.arduino.cc/en/reference/firmata)|[入门](http://www.arduino.cc/en/Guide/HomePage)|最流行的开源开发板
[Raspberry Pi](https://www.raspberrypi.org/)|[Raspberry Pi](https://www.raspberrypi.org/products/)|[Raspbian](https://www.raspbian.org/)|[Top 8 IDEs](https://blog.idrsolutions.com/2014/12/top-8-ides-programmers-coders-beginners-raspberry-pi/)|不限|TCP/IP,Firmata|[入门](https://www.raspberrypi.org/resources/learn/)|最火热的 Linux 开发板
[ARM mbed](https://mbed.org/)|[ARM mbed](https://developer.mbed.org/platforms/)|[mbed RTOS](https://developer.mbed.org/handbook/RTOS)|[mbed Compiler](https://developer.mbed.org/handbook/mbed-Compiler)|C/C++|[TCP/IP](https://developer.mbed.org/handbook/TCP-IP-protocols-and-APIs)|[入门](http://mbed.smeshlink.com/guide)|ARM 低功耗物联网平台
[Marvell](http://www.marvell.com/solutions/internet-of-things/)|[88MC200](http://www.marvell.com/microcontrollers/wi-fi-microcontroller-platform/)|[FreeRTOS](http://www.freertos.org/)|[Kinoma Create](http://kinoma.com/create/)|不限|TCP/IP|[入门](http://www.marvell.com/microcontrollers/wi-fi-microcontroller-platform/software/)|小米物联平台
[Tessel](https://tessel.io/)|[Tessel](https://shop.tessel.io/)|[JavaScript MCU]()|[tessel](http://start.tessel.io/usage)|Javascript|[Protocols](https://tessel.io/docs/communicationProtocols)|[入门]()|Javascript微内核/NodeJs开发环境
[Espruino](http://www.espruino.com/)|[EspruinoBoard](http://www.espruino.com/EspruinoBoard)|Javascript MCU|[Espruino Web IDE](https://chrome.google.com/webstore/detail/espruino-web-ide/bleoifhkdalbjfbobjackfdifdneehpo)|Javascript||[入门](http://www.espruino.com/Quick+Start)|首个 JavaScript 微处理器
Samsung|[ARTIK](https://www.artik.io)|[Nucleus](http://www.mentor.com/embedded-software/nucleus/)|Auduino IDE, [Eclipse-based](http://www.mentor.com/embedded-software/nucleus/ide)|不限|Firmata,TCP/IP|[入门](https://www.artik.io/gettingstarted)|处于内测中
[微信](http://iot.weixin.qq.com/)|[Sensoro](http://www.sensoro.com/zh/iot)|RTOS|[Auduino IDE](http://www.arduino.cc/en/Main/Software/)|Objetive-C/Java/C++|[Firmata](http://www.arduino.cc/en/reference/firmata),[AirSync](http://iot.weixin.qq.com/document-7_2.html)|[开发者](http://www.sensoro.com/zh/developer)|基于 Arduino 的微信硬件开发、体验板。
[mbientlab](https://mbientlab.com)|[MetaWear](https://mbientlab.com/metawear/)|MetaWear OS|Xcode/Android Studio|Objetive-C/Java|Bluetooth|[入门](https://mbientlab.com/gettingstarted/)|可穿戴微芯片
[WRTnode](http://cn.wrtnode.com/w/)|[WRTnode](http://cn.wrtnode.com/sale.html)|[OpenWrt](https://openwrt.org/)|[Eclipse C/C++ IDE ](http://www.eclipse.org/downloads/packages/eclipse-ide-cc-developers/keplersr2)|C/C++|TCP/IP|[入门](http://wiki.wrtnode.com/index.php?title=Main_Page/zh-cn)|最小Linux开发板
[NodeMCU](http://www.nodemcu.com/index_cn.html)|[NodeMCU](https://github.com/nodemcu/nodemcu-firmware)|[eLua](http://www.eluaproject.net/)|[eLua IDE](https://github.com/nuraci/Goat-IDE)|Lua|[XMODEM](http://en.wikipedia.org/wiki/XMODEM)|[文档](http://wiki.wrtnode.com/index.php?title=Main_Page/zh-cn)|基于 Lua 语言开发板
[RAYSHOBBY](http://rayshobby.net/)|[SquareWear](http://rayshobby.net/sqrwear/)|RTOS|Arduino IDE|C/C++|Firmata|
[Damien George](http://dpgeorge.net/)|[MicroPython](http://micropython.org/)|[Python 3](https://www.python.org/)|[Python IDEs](https://wiki.python.org/moin/IntegratedDevelopmentEnvironments)|Python 3||[文档](http://docs.micropython.org/en/latest/)|

### 开发平台
* [Arduino](http://www.arduino.cc/)
	* [Products](http://www.arduino.cc/en/Main/Products)
	* [NodeJs on Arduino Yun](http://www.appsaloon.be/blog/node-js-arduino-yun/)
* [Raspberry Pi](https://www.raspberrypi.org/)
	* [Getting Started](https://www.raspberrypi.org/resources/learn/)
	* [Raspbian：世界上“最小的”操作系统是怎样炼成的？](http://www.pingwest.com/building-the-raspbian-os/)
	* [专访树莓派创始人 Eben Upton：坚持 35 美元不动摇](http://www.ifanr.com/442783)
	* [能搭载 windows 10 的树莓派](http://www.ifanr.com/489504) 
	* [Raspberry PI Jasper安装,Raspberry PI语音控制](http://www.phodal.com/blog/raspberry-pi-install-jasper/)
	* [用树莓派 + Python 和 OpenCV 检测和跟踪运动对象（上）](http://python.jobbole.com/81593/)，[（下）](http://python.jobbole.com/81645/)
* [ARM mbed](https://mbed.org/)
	* [GitHub：mbedmicro/mbed](https://github.com/mbedmicro/mbed)
	* [mbed 快速入门](http://mbed.smeshlink.com/guide)
* [Contiki](http://www.contiki-os.org/)
	* [Contiki：鲜为人知的物联网系统](http://www.leiphone.com/news/201406/internet-of-things-contiki.html)
* [Nucleus OS](http://www.mentor.com/embedded-software/nucleus/)
	* [构筑基于物联网操作系统的物联网生态环境](http://blog.csdn.net/hellochina15/article/details/23206691)
* [RedBearLab](http://redbearlab.com/)
	* [blend](http://redbearlab.com/blendmicro/)：集成蓝牙4.0 Arduino 开发板。 
	* [GitHub: RedBearLab/Blend](https://github.com/RedBearLab/Blend)
	* [单线路板蓝牙智能 Arduino 解决方案](http://www.eepw.com.cn/article/247864.htm)
* [Particle](https://www.particle.io/) 
	* [Gettting Started](http://docs.particle.io/photon/start/)
	* [让 Arduino 便捷联网的模块 Spark](http://cn.technode.com/post/2013-09-26/haxlr8r-spark/)
* [Tessel](https://tessel.io/)：基于 Linux + NodeJs 的硬件开发平台
	* [GitHub：tessel](https://github.com/tessel/project) 
	* [Tessel：用JavaScript做嵌入式开发](http://blog.jobbole.com/46055/)
* [Espruino](http://www.espruino.com/)：首个 JavaScript 微处理器
	* [购买](http://item.taobao.com/item.htm?spm=a230r.1.14.1.YSdV7Y&id=43421292301&ns=1&abbucket=3#detail)
* [Marvell](http://www.marvell.com.cn/)
	* [Kinoma Create](http://kinoma.com/create/about/) ：物联网开发工具包
	* 相关报道：
		* [
Marvell 推出 Kinoma Create 物联网开发套件 专案设计带着走](http://technews.cn/2014/10/29/marvell-kinoma-create/) 
		* [Marvell 开源 KinomaJS 应用框架，加速物联网行业成长](http://www.marvell.com.cn/company/news/pressDetail.do?releaseID=6223) 
		* [Marvell IoT平台在业界率先为硬件制造商提供全面HomeKit支持](http://www.marvell.com.cn/company/news/pressDetail.do?releaseID=6296) 
		* [Marvell 推出业界领先的ZigBee无线微控制器SoC，促进智能家居和IoT创新](http://	www.marvell.com.cn/company/news/pressDetail.do?releaseID=6438)
		* [Marvell 一流端到端物联网平台助力小米推出最新智能家居产品](http://www.marvell.com.cn/company/news/pressDetail.do?releaseID=6224)
* Apple
	* [HomeKit](https://developer.apple.com/homekit/) 
	* [首批苹果HomeKit认证智能家居设备有望下月（2015-6）面市](http://www.forbeschina.com/review/201505/0042736.shtml)
* Google
	* [【I/O 2015】Google 的物联网平台来了！叫 Brillo](http://www.ifanr.com/news/526455)：
Brillo 基于 Android 开发，它是一个物联网的底层系统，属于硬件的操作系统。通讯协议 Weave。 
	* [谷歌正开发物联网安卓版本 欲统一智能家居](http://tech.qq.com/a/20150522/009319.htm)
	* [Brillo：Google的物联网野心](http://jandan.net/2015/05/27/hello-brillo.html)
* [微软](https://www.microsoft.com/windowsembedded/zh-cn/internet-of-things.aspx)
	* [Developer](https://dev.windows.com/en-US/iot) 
* 英特尔
	* [IoT](https://software.intel.com/zh-cn/iot/home)
	* [英特尔® 物联网开发套件v1.0正式发布](https://software.intel.com/zh-cn/blogs/2015/02/20/intel-iot-developer-kit-v10-is-here)
* IBM
	* [IoT Foundation](https://developer.ibm.com/iotfoundation/) 
* Facebook
  * [Parse for IoT：Facebook的物联网SDK](http://www.infoq.com/cn/news/2015/03/parse-for-iot-facebook-sdk)
* [华为](http://www.oiotc.cc/)
	* [LiteOS](http://www.oiotc.cc/index.php?m=project&a=kernel)：LiteOS 只有10KB，是目前最轻量级的物联网开源操作系统。
	* [海思单板 poplar](http://forum.oiotc.cc/forum.php?mod=viewthread&tid=110)
	* [解决方案：物联网（M2M）](http://www.huawei.com/cn/solutions/arpu-up/hw-083596-------------------------m2m.htm#.VWp8SJOUdd8)
	* [
为 IoT 建立统一标准，华为推出开源物联网操作系统 LiteOS](http://technews.cn/2015/05/30/huawei-iot-liteo/)
	* [我们应该用什么姿势，看待华为的Liteos？](http://www.leiphone.com/news/201505/qYBPMOnaYyntp5KR.html) 
* 三星
	* [ARTIK](https://www.artik.io)	：采用 [Nucleus OS](http://www.mentor.com/embedded-software/nucleus/)
		* [三星发布物联网系列芯片Artik 硬件巨人也开始玩软件生态了](http://geek.csdn.net/news/detail/32526)
		* [三星加入 Arduino 认证计划，推出强大的物联网开发工具 ARTIK](http://oszine.com/samsung-arduino-artikboard/)	
	* [SmartThings](http://www.smartthings.com/)
		* [SmartThings 简介](http://blog.csdn.net/panjunbiao/article/details/9425431)
		* [收购智能家居平台SmartThings，三星的“物联网”也来了](http://www.pingwest.com/weibo-2014-q2/)
* 腾讯
	* [腾讯物联网开放平台](http://iot.open.qq.com/)
* [LABView](http://www.ni.com/labview/zhs/)
	* [物联网离不开LABView嵌入式开发](http://home.eeworld.com.cn/my/space-uid-431262-blogid-74658.html) 
* [Sensoro](http://www.sensoro.com/zh/iot)：基于 Arduino 的微信硬件开发、体验板。
  * 开发者指南：[Sensoro/IOT](https://github.com/Sensoro/IOT)
  * [解密让微信成为物联网中枢的 AirSync](http://www.ifanr.com/524162)
* [MetaWear](https://mbientlab.com/metawear/)：“MetaWear是一款迷你的无线传感器，可用手机进行设置和管理。此外，通过平板电脑、蓝牙设备等也可以和它进行连接”。参考价: $35 ~ $80
  * [ARM Cortex-M0（MCU）](http://www.arm.com/zh/products/processors/cortex-m/cortex-m0.php) + 蓝牙。
  * [相较于智能手环和手表，它要迷你得多](http://mt.sohu.com/20150522/n413532308.shtml)
  * [动手制作属于自己的可穿戴设备](http://www.cnbeta.com/articles/291331.htm)
* [WRTnode](http://cn.wrtnode.com/w/)：[OpenWrt](https://openwrt.org/)开源硬件，极小型Linux+Wi-Fi开发板，简单完整的IDE，智能机器之心
	* [WRTnode罗未：开放制造的机器之心](http://www.leiphone.com/news/201406/wrtnode-machine-openhardware.html)
* [OSBean](http://www.osbean.com/)
	* [OSBean Air](http://www.osbean.com/portfolio_page/nano/) 
	* [OSBean Air，一块只有硬币大小的带 WiFi的Arduino](http://36kr.com/p/532549.html)
* [NodeMCU](http://www.nodemcu.com/index_cn.html)：基于 Lua 语言开发板
	* [firmware](https://github.com/nodemcu/nodemcu-firmware)
* [RoboPeak](http://www.robopeak.com/)
	* [激光雷达RPLidar，成本仅为工业级产品的十分之一](http://36kr.com/p/211924.html)
	* [RoboPeak 从团队到公司跨越](http://www.ifanr.com/295248)
* [Open Hybrid](http://www.openhybrid.org/index.html)：“一个针对于物理计算与物联网的开源增强现实平台，它基于Web与Arduino。”
* [Macchina.io](http://macchina.io/)：运行于Raspberry Pi, Beaglebone 或者 RED brick 等基于 Linux 系统的开发板。编程环境：Javascript 或 C++
* [GeoThings](http://geothings.io/)：野外作业 Arduino 开发板。配备 GPS、Mobile、SD、太阳能，云支持。

### 编程环境
* [NodeJs](http://nodejs.org)
	* [Getting Started](https://cnodejs.org/getstart) 
* [CylonJS](http://cylonjs.com)：提供 36 硬件平台开发支持 
	* [GitHub](https://github.com/hybridgroup/cylon/)
* [JohnnyFive](http://johnny-five.io/)：基于 Arduino Firmata 协议的 NodeJs 开发库
	* [GitHub](https://github.com/rwaldron/johnny-five) 
* [JerryScript](http://samsung.github.io/jerryscript/)：专为 IoT 的轻量级 Javascript 引擎
	* [GitHub](https://github.com/Samsung/jerryscript) 
* [Arduino](http://www.arduino.cc/en/Main/Software)
	* [Getting Started](http://www.arduino.cc/en/Guide/HomePage)
	* [GitHub: Arduino](https://github.com/arduino/Arduino)
	* [firmata](https://github.com/firmata/arduino)：Firmata 协议开源实现大全
	* [Arduino Experimenter's Guide for NodeJS](http://node-ardx.org/)
	* [Firmata 解析](http://blog.csdn.net/changesway/article/details/5503099) 
	* [CylonJS for Arduino](http://cylonjs.com/documentation/platforms/arduino/)
	* [codebender.cc](https://codebender.cc/)：在线 arduino IDE
* [Kinoma Studio](http://kinoma.com/studio/)
* [Particle](https://www.particle.io/dev)
	* [Gettting Started](http://docs.particle.io/photon/start/)
	* Web IDE
* [Eclipse IoT](http://iot.eclipse.org/)
	* [2013 年度 Eclipse M2M 现状](http://www.infoq.com/cn/news/2013/11/eclipse-m2m)
	* [2014 年度 Eclipse 社区报告](http://www.oschina.net/translate/2014-annual-eclipse-community-report)
* [Mongoose](https://github.com/cesanta/mongoose): 嵌入式 Web 服务器。支持MQTT、CoAP、Websocket、HTTP等物联网相关协议。 
* [meshblu](https://github.com/octoblu/meshblu)：M2M 即时通信平台
* [Smart.js](https://www.cesanta.com/)：硬件无关地全栈物联网软件平台。
* [IoT.js](https://github.com/Samsung/iotjs)：三星轻量级面向物联网 JavaScript 框架。基于 [JerryScript](http://samsung.github.io/jerryscript/) 引擎
* 相关文档
	* [物联网的真正关键：IoT Open Architecture](http://www.ctimes.com.tw/DispCols-cn.asp?o=1505071535QS)

### 协议
* [MGTT](http://mqtt.org/)：MQTT 是一种轻量级的发布/订阅协议，旨在最大限度地降低网络带宽和设备资源要求。此外，MQTT 还支持使用 TLS 进行安全通信。MQTT 常用在 IoT 用例中。MQTT v3.1.1 是一种 OASIS 标准，AWS IoT 设备网关支持大部分 MQTT 规范。[更多...](http://www.infoq.com/cn/news/2014/12/mqtt-ibm-iot)	

### 创客社区
* [@SeeedStudio](http://weibo.com/seeedstudio)
* [@DFRobot](http://weibo.com/dfrobot)
* [@Microduino](http://weibo.com/microduino)
* [@Espruino中文社区](http://weibo.com/p/1006065034520011)
* [@EEboard爱板网](http://weibo.com/eeboard)
* [@柴火创客空间](http://weibo.com/chaihuomakerspace)
* [MakerFaire 深圳](http://www.makerfaireshenzhen.com/)

### 资源合集
* [phodal/awesome-iot](https://github.com/phodal/awesome-iot)：这份物联网学习参考大全太给力。从物联网协议、嵌入式系统、相关开源库、相关书籍、博客、学习笔记、标准应有尽有。对于新入行者，来一弹这个也是很受用的。作者：[@Phodal](http://weibo.com/phodal)

### 硬件零售
* [SparkFun](https://www.sparkfun.com/)
  * [淘宝代理：奥松机器人](http://robotbase.taobao.com/)
* [seeedstudio](http://www.seeedstudio.com/)
  * [天猫](http://xidikaiyuanshuma.tmall.com/)：零售自己设计开发板
  * [淘宝](http://seeed-studio.taobao.com/)：代理主流开源硬件
  * [专访 Seeed Studio：开源硬件的创新种子](http://www.ifanr.com/136507)
  * [Seeedstudio：硬件电商](http://www.bundpic.com/2013/07/22790.shtml)
* [DFRobot](http://www.dfrobot.com.cn)：Arduino 授权经销商
  * [商城](http://www.dfrobot.com.cn/index.php)
* [Microduino](https://www.microduino.cc/)：Arduino 的兼容开发板（小又可堆叠）
  * [淘宝](http://microduino.taobao.com/index.htm)
  * [可堆叠的创意 开源硬件 Microduino 开发团队专访](http://www.csdn.net/article/1970-01-01/2816170)

### 智能家居
#### 1. 平台商
* 苹果
	* [HomeKit](https://developer.apple.com/homekit/)
	* [在线零售](http://store.apple.com/cn/accessories/all-accessories/connected-home)
* 亚马逊
	* [AWS IoT](https://aws.amazon.com/cn/iot/)
* [小米](http://home.mi.com/)
	* [开发合作者平台](http://open.home.mi.com/index.html#/intro)
	* [在线零售](http://list.mi.com/26)
	* 媒体报道
		* [关于智能家居平台，小米回答了这 5 个问题](http://www.ifanr.com/545101)
* [360](http://home.360.cn/)
	* [开发合作者平台](http://open.home.360.cn/)
	* [在线零售](http://www.qikoo.com/)
* [庆科](http://mxchip.com/)
	* [MiCO](http://mico.io/)：“MiCO是一款基于32位微控制器（MCU）、满足IoT应用特点的物联网操作系统。” 
	* [FogCloud](http://www.fogcloud.io/)：“FogCloud为开发者提供便捷的智能硬件接入服务，真正实现敏捷开发，快速迭代。”
* [heimcontrol.js](https://github.com/ni-c/heimcontrol.js)：家庭自动化开源软件。基于 Node.js、MongoDB、HTML5、Websockets，运行于 Raspberry Pi、Arduino

#### 1. 集成商
* [Nest](https://nest.com/)
* [海尔](http://www.haier.com/cn/business/Uhome/)
* [中兴](http://www.ztehome.com.cn/)
* [broadlink](http://www.broadlink.com.cn/)

#### 2. 智能摄像
>智能摄像目前是智能家居领域进驻厂商最多的，竟争也最为白热化（定价迥异）。目标用户通常是亲情关怀及室内、外监控（把玩）。

  * [海康威视 － 荧石 C6 云台摄像机](http://www.ys7.com/product-130.html)
  * [小米 － 小蚁智能摄像机](http://www.mi.com/xiaoyi/)
  * [奇虎 － 360智能摄像机](http://www.qikoo.com/preorder/jia)
  * [中兴 － 小兴看看](http://www.ztehome.com.cn/index.php/home/14-camera/20-xiaoxinkankan)
  * [百度 － 小度i耳目](http://camera.baidu.com/)
  * [爱耳目智能摄像机](http://www.iermu.com/)
  * [Nest 推出了一个强大的智能安全摄像头，但是大部分人可能只买得起它的“国产”版](http://www.pingwest.com/what-is-the-next-big-thing-of-nest/)

#### <a id="desk"></a>3. 智能桌
>带来惬意学习的环境的居家环境是书房，直接提供舒适学习体验的则是书桌。当前的智能办公/书桌已经达到了什么样功能。感兴趣的同学看看以下产品。

* [Stir M1](http://www.stirworks.com/stir-kinetic-desk-m1/)
  * 价格：$2999+
  * [媒体报道：更轻巧，更贴心，更便宜](http://www.7huoxing.com/?p=7709)
* [Autonomous](https://www.autonomous.ai/)
  * [kickstarter ERGO: World's First Smart Standing Desk That Talks & Listens](https://www.kickstarter.com/projects/403524037/autonomous-desk-the-smartest-office-desk-yet-power)
  * [indiegogo ERGO: World's First Smart Standing Desk That Talks](https://www.indiegogo.com/projects/ergo-world-s-first-smart-standing-desk-that-talks)
  * 价格：$399 ~ $499+
  * 上市日期： 2015年7月出货
  * 媒体报道
    * [全新办公体验](http://digi.163.com/15/0521/16/AQ5F6AHH001668B4.html)
    * [智能家居？我要智能办公室！](http://www.leiphone.com/news/201506/96RvmqtLn6OPaDpC.html)
* [LIFT PRO](http://iskelter.com/)
  * [indiegogo](https://www.indiegogo.com/projects/lift-pro-quite-possibly-the-best-electric-desk)
  * 价格：$899+
  * 上市日期： 2015年9月出货
  * [媒体报道：多功能智能办公桌](http://www.hitnology.com/video-377.html)  
* 相关配件
  * [suspa - 电动高度调节系统](http://www.suspa.com/index.php?id=4144)
  * [电动执行器](http://www.jimi-tech.com/9/page1/)
  * [爱格升](http://ergotron.com)：知名显示器液压臂。也有升降桌及配件。
  * [智升源](http://zsn.tmall.com/)
  * [力美](http://www.leemc.cn/)
* 相关报道
  * [脑洞大开的桌子](http://www.ifanr.com/520408)：宜家厨房桌、办公桌（Stir, Autonomous）等介绍及视频
  * [智能会议桌：捕捉谈话人员声音告别会议记录]( http://tech.sina.com.cn/q/tech/2015-05-14/doc-icpkqeaz4162345.shtml)
  * [这把办公椅能自动归位](http://www.ifanr.com/620289)

#### 4. 智能锁
  * [Noki：kickstarter](https://www.kickstarter.com/projects/1227497591/noki-the-smart-doorlock-for-europe)
  * [Noki：你还在担心门没锁？](http://www.leiphone.com/news/201505/VjV2wiuDFrGJxcIe.html)
  
#### 5. 智能开关
  * [Gecko Switch](http://www.geckoswitch.com/)
    * [kickstarter](https://www.kickstarter.com/projects/121630918/gecko-switch-your-movable-light-switch)
    * [丧心病狂？一个开关想颠覆整个智能家居](http://www.leiphone.com/news/201507/mj7uHI8YmNvq2HTG.html)
  
#### 6. 室内定位
  *	[室内定位技术的前世今生](http://36kr.com/p/204953.html)
  * [室内定位的前景如何，国内是否有与之相关的创业公司？](http://www.zhihu.com/question/20485136)
  * [iBeacon定位与Wi-Fi定位相比，在准确度、建设成本、应用开发容易程度上有什么差异？iBeacon在国内有无案例？](http://www.zhihu.com/question/24092917)
	
### 智能骑行
* [小牛电动](http://niu.com)
* [启孜－自行车](http://www.bi-ci.com/qizi)

### 智能穿戴
* 智能手表
	* [ticwear](https://github.com/ticwear/sdk) ：开源项目
	* [Meta Watch Gen2](https://github.com/MetaWatchOpenProjects/MetaWatch-Gen2)
* 智能耳机
	* [耳朵上的智能穿戴 Here，能把声音变成玩具](http://mp.weixin.qq.com/s?__biz=MjgzMTAwODI0MA==&mid=219432275&idx=1&sn=d66771a42a4f868290bc4c657113c956&key=c468684b929d2be2139d58db46b5a7fd480e47b1f1a9c47caf41ba753cc2b4f638c564b374b152ccc59017749ce067bd&ascene=0&uin=MTYxMDU2MzQ4MQ%3D%3D)，[kickstarter](https://www.kickstarter.com/projects/dopplerlabs/here-active-listening-change-the-way-you-hear-the)

* [生活号](186life.com)
	* [媒体文章](https://knewone.com/things/shuang-xiang-hao) 

### <a id="uav"></a>无人机
> 无人机极具想象空间，也是蠢蠢欲动的梦想家们向往的领域。当前最大的应用领域大概是摄像机，这也是能相对清楚看到其未来发展的消费领域；还有自然是快递领域，可惜涉及空间使用权限及规则的制定，其大规模应用或许还有较长的路要走。

* [大疆无人机](http://www.dji.com/cn)：国产最牛无人机
	* [航拍还不够，大疆想把无人机与虚拟现实结合起来](http://www.ifanr.com/531698) 
* [Lily Camera](https://www.lily.camera)：“傻瓜式”自拍无人机。通过GPS返回。
	* [Lily 无人机的出现，或许最先撼动的是 GoPro 的地位](http://36kr.com/p/532831.html)
* [Sprite](http://www.ascentaerosystems.com/sprite/)：“蜻蜓式”驴友无人机。通过可佩戴的追踪器返回
	* [kickstarter](https://www.kickstarter.com/projects/ascentaerosystems/sprite-the-portable-rugged-totally-different-small) 
	* [Sprite 无人机竟然是个竹蜻蜓](http://www.ifanr.com/524707)
* [3DR Solo](http://3drobotics.com/solo-drone/)：设定飞行轨迹后自己飞
	* [可以自己飞的智能无人机，你只用负责对焦](http://mt.sohu.com/20150414/n411274751.shtml) 
* [Zano](http://www.flyzano.com/)：最小的拍照无人机 （项目已失败）
	* [kickstarter](https://www.kickstarter.com/projects/torquing/zano-autonomous-intelligent-swarming-nano-drone)
	* [让自拍党“剁手”的神器](http://www.ifanr.com/472892)
* [Onagofly](http://www.onagofly.com/)
	* [indiegogo](https://www.indiegogo.com/projects/onagofly-the-smart-nano-drone--2) 
	* [小到不用登记的自拍无人机](http://techcrunch.cn/2016/02/02/a-tiny-selfie-drone-you-dont-need-to-register-with-the-faa/)：仅 140g，GPS + 1500万高清摄像头
* [Micro Drone](www.microdrones.com/)
	* [indiegogo](http://www.indiegogo.com/projects/micro-drone-3-0-flight-in-the-palm-of-your-hand--2)
	* [当无人机遇上VR，真的带你装逼带你飞](http://www.leiphone.com/news/201506/oez99YY5MoMF48Ke.html)
* [Infinium Robotics](http://www.infiniumrobotics.com/)：室内飞行服务员
	* [室内无人机还是有待挖掘的处女地](http://www.leiphone.com/news/201506/dN1uEs7udxwvT02b.html)
* [比GPS更准，新型无人机导航系统问世](http://www.leiphone.com/news/201505/fJxLEvFRqAGarWsV.html)：通过预制卫星地图及视觉识别技术。

### 工业控制
* [SCADA](http://baike.baidu.com/view/592871.htm)：监控与数据采集（系统）
	* [组态软件](http://baike.baidu.com/view/380099.htm)：组态软件，又称组态监控软件系统软件。译自英文SCADA,即 Supervisory Control and Data Acquisition（数据采集与监视控制）。
	* 开源
		* [openSCADA](http://openscada.org/)
		* [Eclipse SCADA](https://eclipse.org/eclipsescada/)
		* [hashmapinc/scada-iot](https://github.com/hashmapinc/scada-iot)
		* [openSCADA 1.0 发布](http://www.oschina.net/news/38716/openscada-1-0)
	* 商用
		* [Ignition](https://inductiveautomation.com/scada-software/)
			* [WebHMI/SCADA & MES系统软件介绍 2014](http://wenku.baidu.com/view/48917d775727a5e9846a6120.html)
		* [西门子](https://www.industry.siemens.com.cn/automation/cn/zh/Pages/Default.aspx) 
			* [WinCC](http://www.wincc.com.cn/)
			* [西门子全集成能源管理系统](http://www.wincc.com.cn/xxym.aspx?id=12676)
		* [施耐德](http://www.schneider-electric.cn/zh/)
			* [施耐德 SCADA 软件Vijeo Citect产品目录](http://wenku.baidu.com/view/3e787b44561252d380eb6ec5.html)
			* [施耐德 SCADA 产品介绍](http://wenku.baidu.com/view/db83247802768e9951e7389c.html)
		* [GE](http://www.geautomation.com/)
			* [GE SCADA](http://www.geautomation.com/products/hmiscada-software)
		* [iconicsSCADA](http://www.iconics.com/Home/Products/HMI-SCADA.aspx)
		* [teslaSCADA](http://teslascada.com/)
		* [mySCADA](http://www.myscadatechnologies.com/)
		* [B-Scada](http://scada.com/)
		* [力控科技 － SCADA](http://www.sunwayland.com/index_c_nei/78.html)
		* [亚控科技 － 组态王](http://www.kingview.com/kingview/kingview.html)
		* [Hightopo](http://www.hightopo.com/)
			* [基于 HTML5 的 Web SCADA 工控移动应用](http://segmentfault.com/a/1190000004215173) 
* [OPC UA](https://opcfoundation.org/about/opc-technologies/opc-ua/)
	* [Open OPC UA](http://www.openopcua.org/)
	* [开源 OPC UA 列表](https://github.com/acplt/open62541/wiki/List-of-Open-Source-OPC-UA-Implementations)
	* [NI - OPC Server](http://sine.ni.com/nips/cds/view/p/lang/zhs/nid/209059)
	* [OPC-UA进入嵌入式新阶段](http://article.cechina.cn/15/0324/04/20150324041119.htm)
	* [GE首发新的基于OPC - UA标准的“全球发现服务器（GDS）”](http://www.ca800.com/news/d_1ntn74138k5d1.html)
* 机械臂
	* [7Bot](7bot.cc) 
		* [买个机械臂还要自己写编码？你应该让它自己来学习](http://www.ifanr.com/576174)
* [FPGA（Field－Programmable Gate Array）](https://zh.wikipedia.org/wiki/现场可编程逻辑门阵列)：现场可编程逻辑门阵列
	* [Xilinx](http://www.xilinx.com/)：FPGA 芯片的主要生产商。 
		* [Vivado High-Level Synthesis](http://www.xilinx.com/products/design-tools/vivado/integration/esl-design.html): HLS, OpenCV 等高级接口调用 
	* [VHDL（Very-High-Speed Integrated Circuit Hardware Description Language）](https://zh.wikipedia.org/wiki/VHDL)：超高速集成电路（VHSIC）硬件描述语言（HDL）。
	* [NI Single-board RIO](http://sine.ni.com/nips/cds/view/p/lang/zhs/nid/212788)：图形化开发平台，无需掌握 HDL。采用 NI CompactRIO 相同硬件架构。

### 人工智能
* 微软
	* [Project Oxford](https://www.projectoxford.ai/)：开放支持人脸、视觉、视频、声音识别。
	* [DMTK](https://github.com/Microsoft/DMTK)：机器学习库
* Google
	* [TensorFlow](http://tensorflow.org/)：机器学习库
* Facebook
	* [torch](http://torch.ch/)：“一个支持大量机器学习算法的科学计算框架。”
* 语音识别
	* [Nuance Mix](https://developer.nuance.com/public/index.php?task=mix)：相关[中文介绍](http://www.infoq.com/cn/news/2015/12/Nuance-Mix) 
	
### 相关产品
* Android 衍生 
	* [Cyanogen OS](https://cyngn.com/)：试图脱离谷歌生态的原生 Android OS
		* [媒体报道：脱离谷歌 Cyanogen说出了手机厂商的心里话](http://tech.163.com/15/0325/09/ALHS4870000915BD.html) 
	* [Remix Mini](http://www.jide.com/index?)
		* [kickstarter](https://www.kickstarter.com/projects/1123481999/remix-mini-the-worlds-first-true-android-pc)
		* [以 PC 之名，一个国产 Android 小盒子竟创众筹记录](http://www.ifanr.com/545311)
		* [Remix OS](http://www.jide.com/remixos)
* [兰桂智能管家](http://www.cassianetworks.com/cn/products/hub/)：蓝牙路由器
	* [他认为物联网的通讯标准是蓝牙，于是做了一款传输距离300米远的蓝牙路由器](http://36kr.com/p/5035772.html)
	 
### 行业动态
* [InfoQ 物联网技术周报](http://www.infoq.com/cn/adf)
* [编程要从娃娃做起，于是 BBC 要给 100 万名儿童免费提供给微型电脑](http://www.ifanr.com/538427)
* [Zero UI：当界面摆脱了屏幕的束缚](http://www.ifanr.com/537092)
* [RealSense（实感）技术，英特尔想做什么？](http://www.leiphone.com/news/201507/AgQzzehYtoqbWZO3.html)
* [Google 正在开发物联网系统 Brillo](http://www.ifanr.com/523481)
* [富士康布局传感器](http://36kr.com/p/533169.html)
* [腾讯人脸识别](http://www.leiphone.com/news/201505/ViZ5mGak3mjd28v2.html)
* [9 美元的电脑到底长成什么样？](http://www.ifanr.com/519571)
* [DIY 高性能树莓派OpenWrt无线路由器](http://www.shuyz.com/install-openwrt-on-raspberry-as-a-wireless-router.html)
* [MicroPython：针对微控制器的Python](http://www.iteye.com/news/30549)
* [艾拉物联张南雄：物联网想落地？还得从企业层入手](http://www.pingwest.com/ayla-networks-iot-enterprise/)
* [Google I/O 2015 - Project Tango 手机亮相](http://www.ifanr.com/527040)
* [Google 给出了可穿戴设备的终极答案](http://www.ifanr.com/527206)
* [那些基于Arduino/树莓派的家庭物联网项目](http://www.leiphone.com/news/201406/arduino-raspberrypi-connected-home.html)
* [机器人开发框架项目汇总](http://www.csdn.net/article/2014-04-29/2819556-5-open-source-reboot-framework-summary)
* [第一批可以用Siri操作的智能家居产品亮相——什么都好，除了价格](http://www.pingwest.com/first-homekit-products-have-been-launched/)
* [Siri 终于到你家了 ：简便科技生活从此开启](http://www.feng.com/apple/news/2015-06-02/For-one-year-Forward-to-the-first-paragraph-HomeKit-product-listed-finally_615644.shtml)
* [李一男牛电科技发布智能电动踏板车“小牛 N1”](http://techcrunch.cn/2015/06/01/xiaoniu-n1/?ncid=rss)
* [物联网时代的35款开源工具](http://os.51cto.com/art/201409/451092.htm)
* [从 10 米到 1 米，GPS 定位精度将迎来飞跃？](http://www.ifanr.com/619494)
* [OpenCV进阶之路：神经网络识别车牌字符](http://www.cnblogs.com/ronny/p/opencv_road_more_01.html)
* [也许智能家居还是需要一个“大脑”](http://www.ifanr.com/622842)：
* [2016全球最具影响力的50家机器人公司](http://www.almosthuman.cn/2016/02/19/g7wan/)

### 观点评论
* [智能家居中心论与平台观的破产](http://www.leikeji.com/article?675) By 陶军宝 from [@欧瑞博智能家居](http://weibo.com/oruibo)

### 开源协议
* [Comparison of free and open-source software licenses](https://en.wikipedia.org/wiki/Comparison_of_free_and_open-source_software_licenses#cite_note-epl-9)
* [Simple description of popular open source licences](https://www.freebsdnews.com/2011/05/25/simple-description-popular-open-source-licences/)