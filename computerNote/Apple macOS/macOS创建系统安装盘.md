![一步一步教你为macOS创建系统安装盘](https://pic1.zhimg.com/v2-f9983fe3ad289f3ee84821882c073a2e_1200x500.jpg)

# 一步一步教你为macOS创建系统安装盘

[![李元](https://pic1.zhimg.com/21d298785a0b858ca9cd85a34821c0c3_xs.jpg)](https://www.zhihu.com/people/serfan)

[李元](https://www.zhihu.com/people/serfan)

低阶码农,游戏开发菜鸟 http://www.kaifaxueyuan.com

关注他

2 人赞同了该文章

电脑用久了就会比较卡，一般用户此时选择最多的是格式化硬盘重新安装系统，这在windows下非常容易，微软官方提供了安装盘制作工具。macOS稍微复杂一点，不过整理过程也是很简单的，本文就简单介绍一下如何制作macOS安装U盘。

**必要条件**

首先我们需要容量至少8G的U盘，最好16G,另外USB接口最好是3.0标准的，这样可以加快写入和安装的速度。

还需要macOS的安装文件，目前最新版为Majove，可以直接从苹果应用商店下载。安装程序的大小大约是6GB左右，下载它大概需要一些时间，以国内的网速，估计需要1-3个小时的样子。

注意:如果您希望在已经安装了macOS Mojave的Mac上创建可引导磁盘，您可能无法使用应用商店下载安装程序，这个时候就要选择第三方工具了，文章的后面会介绍他们。

**格式化U盘**

打开磁盘实用程序，从左侧列表中选择您的U盘。单击面板上方中的“抹掉”按钮，弹出抹掉磁盘的弹框。在名称栏输入你希望起的名字，例如“macOSInstaller”。此处的名称必须跟下面命令行的的名称完全一致，格式–选择“Mac OS X 扩展（日志式）”作为驱动器格式。



![img](https://pic1.zhimg.com/80/v2-e0793f62fa4db44df9c0d1489241def8_720w.jpg)



选择这些选项后，单击“抹掉”按钮开始格式化U盘，此时等待即可，完成后macOS会通知你。

**使用终端创建安装盘**

打开终端，粘贴下面的命令到终端：

```text
sudo /Applications/Install\ macOS\ Mojave.app/Contents/Resources/createinstallmedia --volume /Volumes/macOSInstaller
```

注意：命令中的macOSInstaller就是你上一步格式化时输入的卷标，一定要一致，否则会失败。另外本例以Mojave作为例子，如果你要制作其他版本的安装盘，需要把Mojave改成对应的名字，比如Sierra。

执行上述命令后，系统会要求你输入管理员密码，验证通过后会开始整个制作过程。这个过程需要一段时间，耐心等待进度到100%即可。

一旦所有工作都结束，就可以拿这个U盘引导并重新安装macOS了。

**使用DiskMaker X制作安装盘**

如果你不喜欢使用命令行的方式来创建，那么也可以使用第三方工具，比较知名的工具DiskMaker X。DiskMaker X是一个用苹果脚本构建的应用程序，您可以在多个版本的macOS中使用该脚本构建一个可引导安装盘，用户只需点击几下鼠标就可以构建一个macOS安装盘。

打开DiskMaker X官网，首页下载最新的安装文件并安装，如图。



![img](https://pic4.zhimg.com/80/v2-64fdcb0c81e0535c6cb1986c9b3a8a6f_720w.jpg)





![img](https://pic3.zhimg.com/80/v2-a7ac02ae2ef47409fb398c50f8d07426_720w.jpg)



打开DiskMaker，选择“select a macOS installation App”，然后选择下载的安装镜像。



![img](https://pic4.zhimg.com/80/v2-17f5dd37e25195de5cbd8eb3c84dd6ff_720w.jpg)



选择好后，会询问如何格式化U盘，选择最后面的“An 8GB USB thumb drive（ERASE ALL DISK）”即可。



![img](https://pic2.zhimg.com/80/v2-e8b691ae445caecb96f349452ecf5d6d_720w.jpg)



接下来是选择U盘，根据实际情况选择要格式化的U盘即可，选择好之后就会开始制作过程，制作完毕后就可以重新启动安装了。



![img](https://pic1.zhimg.com/80/v2-c3b04ad97d7518d2ac57750b6b54b06c_720w.jpg)



**其他的方式**

如果已经已经安装过macOS Mojave，那么应用商店不会允许用户再次下载安装文件。在这种情况下，需要从国外的技术大神 dosdude1的个人网站上面下载dosdude Mojave安装文件。dosdude1大神为那些不受苹果支持的老旧电脑提供了一个补丁，使他们可以安装最新版的macOS，这个我们后面会额外写一篇教程，本文只下载安装文件，不做过多讲解。

到大神 dosdude1网站上面下载最新的macMojavePatcher.dmg，下载后安装。



![img](https://pic2.zhimg.com/80/v2-edc138b36cb751e169cd0d7955f72c21_720w.jpg)



安装后打开软件，从顶部的菜单中选择“Download macOS Mojave”，然后选择一个路径来保存下载的文件。此时等待完成即可。





![img](https://pic1.zhimg.com/80/v2-f30913192e390ae493ebab0a72747d9c_720w.jpg)





![img](https://pic4.zhimg.com/80/v2-90a8a8eb8455d0967777bb304904a8fb_720w.jpg)



安装程序下载完毕后，软件会自动提示你是否制作安装盘，选择是即可进入制作安装安装盘界面。



![img](https://pic4.zhimg.com/80/v2-7e187e7a144e9fd8312cbaf93b115567_720w.jpg)



依次选择下载的镜像和目标U盘，再点击“Start operation”即可，中途可能会弹出U盘的文件，此时不要误认为是完成了写入，等待进度条走完。



![img](https://pic4.zhimg.com/80/v2-c189e5a63d545f843ee99c2b17f2dd0b_720w.jpg)



一旦成功创建了可引导安装盘，就可以进行macOS Mojave的全新安装了。

如果本文能够帮助到您，请记得关注pc玩家，再次感谢您的阅读。

发布于 2019-06-25