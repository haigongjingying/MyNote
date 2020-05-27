![制作 macOS Mojave U盘USB启动安装盘方法教程 (全新安装 Mac 系统)](https://pic4.zhimg.com/v2-7104ffd0c5cc689aad0d26d7addfcc3b_1200x500.jpg)

# 制作 macOS Mojave U盘USB启动安装盘方法教程 (全新安装 Mac 系统)

[![王健旭](https://pic2.zhimg.com/v2-3a0f1542ea04f1f49f727864cffad012_xs.jpg)](https://www.zhihu.com/people/wang-jian-xu-57-36)

[王健旭](https://www.zhihu.com/people/wang-jian-xu-57-36)

关注他

1 人赞同了该文章

随着苹果 [macOS Mojave 正式版](https://link.zhihu.com/?target=https%3A//www.iplaysoft.com/macos-mojave.html)发布，很多[使用 Mac 电脑](https://link.zhihu.com/?target=https%3A//www.iplaysoft.com/go/mac)的同学都已升级到最新版了。但如果你对系统有洁癖或原本系统已凌乱不堪，那么可能还是希望能格式化「**全新安装 macOS**」的。

不过由于[苹果官方](https://link.zhihu.com/?target=https%3A//www.iplaysoft.com/go/apple)只提供了 macOS 的[升级](https://link.zhihu.com/?target=https%3A//www.iplaysoft.com/tag/%E5%8D%87%E7%BA%A7)程序，并没提供完整 dmg 镜像，想要全新安装的话，只能自己制作一个 macOS Mojave 的U盘启动盘/安装盘了。今天异次元就给大家提供一个简单的制作[教程](https://link.zhihu.com/?target=https%3A//www.iplaysoft.com/tag/%E6%95%99%E7%A8%8B)，这样以后给 Mac 重装系统、在没网络的情况下给多台机器[装机](https://link.zhihu.com/?target=https%3A//www.iplaysoft.com/tag/%E8%A3%85%E6%9C%BA)都方便许多……

[访问：Apple 中国官网](https://link.zhihu.com/?target=https%3A//www.iplaysoft.com/go/apple)

相关阅读：[简单几步制作 Windows 10 USB 启动安装盘图文教程](https://link.zhihu.com/?target=https%3A//www.iplaysoft.com/windows-10-udisk-install.html)

### 方法一：使用命令行创建制作 macOS Mojave 正式版 USB 安装盘

制作 **macOS Mojave** 正式版 [USB](https://link.zhihu.com/?target=https%3A//www.iplaysoft.com/tag/usb) 启动盘的方法有很多，用户可以选择使用命令行来创建，也可以选择第三方U盘制作工具来制作，大家可以根据自己的喜好选择。



![img](https://pic4.zhimg.com/80/v2-7104ffd0c5cc689aad0d26d7addfcc3b_720w.png)



本教程首先介绍命令行的方式，因为这是苹果官方系统内置的命令，优点是稳妥而且没有兼容性问题，只是需要通过命令行操作，对新手来说可能看似有点复杂，但其实步骤还是非常简单的。

1. 首先，准备一个 [8GB 或更大容量的 U盘](https://link.zhihu.com/?target=https%3A//www.iplaysoft.com/go/upan)，并[备份](https://link.zhihu.com/?target=https%3A//www.iplaysoft.com/tag/%E5%A4%87%E4%BB%BD)好里面的所有资料。

2. [下载好 macOS Mojave 正式版的安装程序](https://link.zhihu.com/?target=https%3A//www.iplaysoft.com/macos-mojave.html)备用，先不要启动安装。

3. 打开 “应用程序 → 实用工具 → 磁盘工具”，将U盘「抹掉」(格式化) 成「Mac OS X 扩展（日志式）」格式、GUID 分区图，并将 U 盘命名为「Mojave」(下图序号3处)。注意：**这个盘符名称必须与后面的命令里的名称一致，需要认真看清楚**，很多新手容易出错在这里)

   

![img](https://pic3.zhimg.com/80/v2-ba20818d7c6732a8d976282f94b45c12_720w.png)



1. 打开 “应用程序→实用工具→终端”，将下面的一段命令复制并粘贴进去：

   如要制作 **macOS Mojave 启动盘**，U盘名称要改成「Mojave」(必须与下面命令对应)，然后拷贝这段命令：sudo /Applications/Install\ macOS\ Mojave.app/Contents/Resources/createinstallmedia --volume /Volumes/Mojave /Applications/Install\ macOS\ Mojave.app --nointeraction

------

如要制作 **macOS High Sierra 启动盘**，U盘名称要改成 HighSierra (要与下面命令对应)，拷贝这段命令：
sudo /Applications/Install\ macOS\ High\ Sierra.app/Contents/Resources/createinstallmedia --volume /Volumes/HighSierra --applicationpath /Applications/Install\ macOS\ High\ Sierra.app --nointeraction

------

如要制作「**旧版本的 macOS Sierra**」，U盘名称改成 Sierra，拷贝这段命令：
sudo /Applications/Install\ macOS\ Sierra.app/Contents/Resources/createinstallmedia --volume /Volumes/Sierra --applicationpath /Applications/Install\ macOS\ Sierra.app --nointeraction

1. 回车并执行该命令，这时会提示让你输入管理员密码，便会开始制作过程了：

   

![img](https://pic3.zhimg.com/80/v2-2201f563dd51bb7e5e56c155783ded96_720w.png)



1. 如上图，这时系统已经在制作中了，请耐心等待直到屏幕最后出现 Done. 字样即表示大功告成了！然后，就带着[U盘](https://link.zhihu.com/?target=https%3A//www.iplaysoft.com/tag/U%E7%9B%98)出去浪吧……

### 方法二：使用 DiskMaker X 启动盘制作工具：

如果你不喜欢任何[代码](https://link.zhihu.com/?target=https%3A//www.iplaysoft.com/tag/%E4%BB%A3%E7%A0%81)、命令之类的操作，那么除了上面使用命令行来制作 macOS 的启动/安装盘的方法外，我们也有更加傻瓜直观一点的方法，那就是通过 **DiskMaker X** 工具来制作 macOS 安装U盘。



![img](https://pic3.zhimg.com/80/v2-b8bef7468c484c9649cb083f76e709de_720w.png)



[Diskmaker X](https://link.zhihu.com/?target=https%3A//www.iplaysoft.com/macos-usb-install-drive.html) 是一款免费的 **macOS USB 启动盘制作软件**，当然前提也是要先下载好 macOS Mojave 正式版的安装程序。最新的 **DiskMaker X 8 已更新支持制作 macOS Mojave** / High Sierra / Sierra / OS X Yosemite / El Capitan 等不同版本的系统安装盘，启动后会让你选择，按照你的需要选择即可。



![img](https://pic2.zhimg.com/80/v2-c39404f5350864c9d577226f2b614b69_720w.png)



如果你已经下载好 macOS 的安装程序，那么正常情况下，Diskmaker X 会自动帮你找到其路径的，点击 Use This Copy 继续下一步：



![img](https://pic4.zhimg.com/80/v2-3daa7195bc288be339a037ac1e73f273_720w.png)



之后，DiskMaker X 会提示你需要一个至少 [8GB 容量的U盘](https://link.zhihu.com/?target=https%3A//www.iplaysoft.com/go/upan)，将 U 盘插入 Mac 之后，点击 “An 8 GB USB thumb drive” 按钮下一步



![img](https://pic4.zhimg.com/80/v2-ce4bbd5a82ac74526138f924a950c8b7_720w.png)



这时会出现选择 U 盘盘符的窗口（请注意千万不要选错盘符哦！！）：



![img](https://pic1.zhimg.com/80/v2-274250fd477dfe9c44985a939d4e8b64_720w.png)



确认格式化并抹除 U盘 (Erase then create the disk)，然后就开始一条龙制作过程了。

### 通过 U 盘安装 macOS Mojave / 格式化重装 (抹盘全新安装系统) 方法

当你制作好 macOS Mojave 的安装盘 U 盘之后，你就可以利用它来给 [Mac 电脑](https://link.zhihu.com/?target=https%3A//www.iplaysoft.com/go/mac)格式化重装 (抹盘安装)了。操作的方法非常简单：

1. 当然还是要想办法[备份](https://link.zhihu.com/?target=https%3A//www.iplaysoft.com/tag/%E5%A4%87%E4%BB%BD)好 Mac 里所有的重要数据了。

2. 插上制作好的安装U盘，如果系统能识别出来即可，这时我们先关机了。

3. 按下电源键开机，当听到“噹”的一声时，按住 Option 键不放，直到出现启动菜单选项：

   

![img](https://pic3.zhimg.com/80/v2-7f74167282bfd0f5c24702dde086211a_720w.png)



1. 这时选择安装U盘 (黄色图标) 并回车，就可以开始安装了，在过程中你可以通过“磁盘工具”对 Mac 的磁盘式化或者重新分区等操作。
2. 之后就是一步一步的安装直到完成了。

发布于 2020-01-13