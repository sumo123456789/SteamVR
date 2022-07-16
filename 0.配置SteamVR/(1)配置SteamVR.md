# OpenVR
```
OpenVR是Valve公司开发的一套包含一系列SDK和API的工具集，旨在从驱动层级为硬件厂商提供软硬件开发支持。
硬件设备制造商可以为设备开发OpenVR 驱动程序，以使设备能够运行在SteamVR平台上。
作为Unity开发者来说，并不需要太多关心OpenVR及其SDK，因为这更多的是面向VR硬件平台和游戏引擎开发商来进行使用的。
```

# SteamVR
```
SteamVR是Valve基于OpenVR推出的一套VR体验解决方案，以软件客户端形式存在，面向终端用户，故也常被称为SteamVR客户端.
SteamVR客户端作为桥梁，介于OpenVR底层驱动与用户之间工作——SteamVR获取到用户的输入，如控制器按键的按下、头显在空间中移动等，
将这些数据信息传递给OpenVR进行处理，OpenVR将处理后的数据通过SteamVR呈现给用户。
```
# SteamVR Plugin
[SteamVR Plugin技术网站](https://valvesoftware.github.io/steamvr_unity_plugin/index.html)

[Unity Asset Store](https://assetstore.unity.com/packages/tools/integration/steamvr-plugin-32647)
```
SteamVR Plugin是Valve公司提供给Unity开发者的开发工具，以.unitypackage文件的形式存在，
在使用方面符合一般的Unity插件导入流程，开发者可使用该插件开发面向SteamVR平台的VR应用程序。
```
# 配置SteamVR 
## 设备:OculusQuest2 、装有Oculus、Unity以及SteamVR的Windows电脑
```
在Windows电脑安装响应软件后，先在unity的Asset Store中安装SteamVR Plugin插件。
然后打开windows->Steam Input选项，在该页面中，可以定义SteamVR中的动作集和动作。
在点击save and generate后。先打开SteamVR，并让Oculus设备连接上电脑，并进入SteamVR应用。
此时即可点击unity中的play按钮开始调试。
```
## Steam Input
![image](https://github.com/sumo123456789/SteamVR/blob/main/0.%E9%85%8D%E7%BD%AESteamVR/image/1657949248725.png)
