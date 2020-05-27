![用U盘重装Mac全新的操作系统（Mojave）](https://pic3.zhimg.com/v2-0b85287cac264c8ce37e8f9a444f2da2_1200x500.jpg)

# 用U盘重装Mac全新的操作系统（Mojave）

[![晨 Sir](https://pic2.zhimg.com/v2-8a696a3ce8e5774dbbd4cd599bb8c297_xs.jpg)](https://www.zhihu.com/people/chin-sir)

[晨 Sir](https://www.zhihu.com/people/chin-sir)

关注他

28 人赞同了该文章

**mac重装系统一共有三种方法：**

1、网络恢复：适用于无法进入系统的电脑，但相当耗费时间，短则几小时，长则一两天

2、从电脑自带的App Store里直接下载安装：操作非常简单，适用于电脑系统升级

3、用优盘进行系统重装：适用于电脑故障，无法进入系统并且想节约时间以最快的速度重装系统的用户

前两种方法没有什么技术含量可谓是傻瓜式操作，第三种方法相对前两种方法比较难一些，我详细介绍一下第三种用优盘给电脑重转系统

**准备工作：**

**1、制作优盘启动盘：**

优盘要求是8G或者8G以上的，准备好优盘后需要在电脑上下载系统安装程序，咱们直接下载最新版的 macOS Mojave，具体操作步骤如下：

（1）打开App Store 搜索 Mojave，点击查看，再点击获取。等待下载完成，下载完成后先不要启动安装，如果下载速度较慢可以到网盘或者其他地方找下载资源，但一定要注意安全。

![img](https://pic4.zhimg.com/80/v2-0fbee180e61f9a52b23204562ee16b0b_720w.jpg)

![img](https://pic1.zhimg.com/80/v2-f653eb41fb46465c0f07204c5e4adc70_720w.jpg)

![img](data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='1560' height='668'></svg>)

（2）系统安装程序下载完之后，将准备好的优盘插到电脑上（桌面会显示优盘的名称），打开“应用程序—>其他—>磁盘工具”，如下图：

![img](https://pic2.zhimg.com/80/v2-0977915d8c5a2d360948210d9445b4f9_720w.jpg)

打开磁盘工具之后，将优盘抹掉（格式化）成「Mac OS X 扩展（日志式）」格式、GUID 分区图，并将优盘命名为「Mojave」如下图所示：

按照途图中顺序依次检查，检查没问题后点抹掉。

![img](https://pic3.zhimg.com/80/v2-c7f357eb59e49704d43812725099f8d2_720w.jpg)

（3）优盘抹掉之后，打开“应用程序—>其他—>终端”，如下图：

![img](https://pic1.zhimg.com/80/v2-5ef1cbe4acd8c428836090018859eec8_720w.jpg)

打开终端之后 将下列代码一字不差的粘贴到终端里面去

```text
sudo /Applications/Install\ macOS\ Mojave.app/Contents/Resources/createinstallmedia --volume /Volumes/Mojave /Applications/Install\ macOS\ Mojave.app —nointeraction
```

粘贴进去之后按回车键，会提示你输入密码，这个密码是你电脑的开机密码，输入的过程因为输入密码是加密的所以屏幕不会有任何反应，输完密码回车即可，然后是漫长漫长漫长的等待，等待的时间长短取决于你电脑的配置。如下图：

![img](https://pic3.zhimg.com/80/v2-8d28940743fcc1d1f2558a47ce1a4296_720w.jpg)

![img](https://pic3.zhimg.com/80/v2-62d695700f8cf589bd12d1a1af17c696_720w.jpg)

出现0%...10%...说明正在制作启动盘,那是制作进度，进度条君到100%并出现下图Install media now 的字样 说明优盘启动制作成功了。

![img](https://pic1.zhimg.com/80/v2-d6bdb707d766f48af97b77cb727ca77c_720w.jpg)

优盘启动盘可以一直留着，可以随时帮助别人或者随时给自己的电脑重装系统。

**2、启动盘制作好之后，就可以用它给电脑重装系统了**，首先 把电脑里的重要文件进行备份，有移动硬盘拷贝出来或者上传网盘。

（1）再重复一次，给电脑重要信息备份

（2）将制作好的启动盘插到电脑上，如果制作好没拔就查着吧，给电脑关机。

（3）确认电脑关机之后，按下电源键，听到“当”的一声后，按住Option键不放，就是电脑键盘最后一排从左往右数第三个键，按住不放，直到出现启动菜单选项，如下图：

![img](https://pic1.zhimg.com/80/v2-3fbef85dcad1eef4160bdb4d196de5e4_720w.jpg)


选择之后 会计入到Mac实用工具界面，如下界面：

（如果需要将硬盘格式化可以选择磁盘工具，然后将硬盘格式化，操作跟抹掉优盘是一样的，抹掉之后点击左上角的✘就可以回到下图界面）

选择，安装Mac OS 然后是漫长的等待，具体等待多少长时间看你电脑的配置了，装完系统，开机会有提示根据提示操作即可。教程到此为止，你学会了吗？

![img](https://pic4.zhimg.com/80/v2-6768f4fb10a9fc5feb29673135a0ac0f_720w.jpg)



发布于 2019-03-20