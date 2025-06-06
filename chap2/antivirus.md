# 我需要杀毒软件吗

对于本文的大部分读者来说，答案是显而易见的：**需要**

尽管在2023年计算机病毒已经很少见到，但是一款杀毒软件依然是必须的。因为它不仅仅能够帮助你防护病毒软件，也能够帮助你防护流氓软件(广告弹窗，恶意推广)等。

## 我应该选择哪一款杀毒软件

不推荐系统自带的 `Windows 安全中心`，因为它容易误报文件，并且有些功能非常鸡肋且耗费资源

杀毒软件最多只需要安装一款即可，不需要安装多款。以下是我用过的安全软件和大致介绍

1. 火绒安全

火绒安全的最大特点是十分纯净，甚至默认情况也不会有开机速度提示，在大部分情况下你都可以忘记他的存在。它还具有可高度自定义的主动防御以及一些专业工具，适合对计算机熟悉的用户使用。但是火绒在病毒查杀等方面弱于360，腾讯电脑管家等软件。

2. 360安全卫士

无论360在网络上有多少争议，不可否认的是360在国内杀毒软件中属于第一梯队；他的病毒查杀能力十分优秀，但是弹窗提示和诱导安装其他软件的现象也是比较多的。使用360时可以在设置内关闭不需要的弹窗和功能，同时也需要注意在主菜单内使用功能时可能会安装上的各种软件。

3. 腾讯电脑管家

同以上360

## 我需要如何配置杀毒软件

无论你使用上面的哪一个杀毒软件，强烈建议你将`捆绑安装拦截`,`弹窗拦截`等功能打开。(不同软件叫法可能也都不一样，请自行配置)

同时可以在设置内关闭不需要的弹窗和功能。一般来说保留上面的两个功能和`主动防御`打开就可以，别的功能几乎不需要。

对于垃圾清理，可以每隔一段时间清理一次，想起来的时候清理即可。

对于`全盘扫描`和`电脑体检`，其实很多时候是不需要使用这两个功能的，因为主动防御已经能够在病毒运行前进行拦截。

如果你正在使用360和腾讯电脑管家，这两个软件可能会接管系统自动升级，如果你需要自动升级可以在设置内将系统自动升级控制权交回设置页面。


ps：以上个人免费软件是通过广告进行盈利，但是可能会影响个人用户正常使用，用户可以在 **设置** 降低广告频率
***
## 那么Windows防火墙呢

也许大部分读者根本不清楚防火墙究竟对什么起作用；Windows防火墙的一个典型应用是：控制网络上的其他人是否可以访问你的计算机。

但在国内大部分家庭宽带并不具有公网IP地址，也就是说网络上的其他人根本就无法通过常规方式访问你的计算机。然而随着IPV6的普及，很多家庭宽带都会为每一台连入家庭网络的设备分配IPV6地址。这时候防火墙就是非常重要的安全保障了。

但是请注意，上面的访问并不是说你关闭了防火墙就等于别人可以完全控制你的电脑。

综上，我建议保持防火墙开启，更多内容在第三节。