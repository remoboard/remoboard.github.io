---
layout: default
title: 远程输入法实验室
---

实验室中包含若干开发中的功能（也包含一些即将下线的功能），**有若干bug，不够稳定**。目前通过实验室，可以切换「连接模式」。

「连接模式」包含三种：

1. Web连接模式（默认的连接模式）
2. 蓝牙连接模式（优化中，目前还不够好用）
3. IP连接模式（即将下线）

其中「Web连接方式」是默认的连接方式，只需要用浏览器访问指定地址，不需要额外电脑客户端。「蓝牙连接方式」目的是用于一些「电脑」和「手机」不能连接到同一个网络（例如同一个Wi-Fi）下的场景，这个模式需要安装额外的电脑端软件。「IP连接模式」是老版本的一种连接模式，需要安装额外的电脑端软件，但功能上完全可以被「Web连接模式」替代，因此未来不继续优化，未来某个版本会下线。

下面包含「蓝牙」和「IP」连接模式的一些使用说明，仅供娱乐。

---


## 电脑端下载地址

默认的`Web连接模式不需要`安装电脑端，当使用`IP连接模式`或者`蓝牙连接模式`时，需要安装电脑端。

- macOS [Download](https://github.com/remoboard/remoboard.github.io/releases)
- Windows [Download](https://github.com/remoboard/remoboard.github.io/releases)



## 电脑端使用方法

默认情况下，电脑和手机的连接模式是`Web连接模式`，`不需要安装电脑端`。当切换连接模式为`IP连接模式`或者`蓝牙连接模式`时，就需要额外安装`电脑端`了。



### macOS安装

(1) 下载macOS 应用 `RemoboardMac.zip`，[GitHubRelease下载](https://github.com/remoboard/remoboard.github.io/releases)  或[百度云](https://pan.baidu.com/s/1F0LpkM4FJeYssJXmRGb6kA)

![](/media/15664933426375.jpg)


(2) 解压 RemoboardMac.zip，双击 Remoboard.dmg ，把Remoboard.app拖入Applications。

![](/media/15682475631662.jpg)


### Windows安装

(1) 下载Windows 应用 `RemoboardWindows.zip`，[GitHubRelease下载](https://github.com/remoboard/remoboard.github.io/releases) 或[百度云](https://pan.baidu.com/s/1F0LpkM4FJeYssJXmRGb6kA)

(2) 解压后，安装。

### iOS配合macOS使用方法

(1) 在手机上，打开任意可以输入文字的应用，长按左下角切换到`远程输入法`

![](/media/15672686555396.jpg)


现在，远程输入法会显示一个`连接码`，以及`IP地址`。当然前提是**确保iPhone连接到了Wi-Fi**

![](/media/15672686708979.jpg)



(2) 打开macOS上的远程输入法

![](/media/15664935874846.jpg)


输入法手机上显示的连接码, 然后点击 `Connect`. 如果一切正常，则连接成功。如果连接失败，请检查手机和电脑是否连接在`同一个内网`中（电脑可以ping通手机的IP地址）。

![](/media/15664949917624.jpg)

对应的手机上会显示 `已连接，打字啦 :)`

![](/media/15672686865059.jpg)

一旦熟悉了，就很简单易用啦 :)

有「三种输入模式」，请见下文。


### Android配合Windows使用方法


(1) 首先切换输入法到「远程输入法」

![](/media/15677838792591.jpg)


（2）在可输入文字的位置，远程输入法默认会显示连接码。

![](/media/15677837375419.jpg)

（3） 打开Windows客户端，输入连接码，点击「连接」。如果连接成功，则可以在下面的输入框中打字。

![](/media/15677831476448.jpg)



### 连接模式切换

![](/media/15673534850484.jpg)


### 输入模式切换

有三种输入模式：

![](/media/15673533973864.jpg)

(1) 标准输入模式

这种模式下可以输入「一行文字」，然后「按回车发送」。

![](/media/15673534147742.jpg)



(2) 多行输入模式

这种模式下，可以「输入或粘贴多行文字」，「点击按钮」发送。

![](/media/15673534464766.jpg)


---


[返回](/)

