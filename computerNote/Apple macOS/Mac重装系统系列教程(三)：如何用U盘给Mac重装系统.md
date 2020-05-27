![Mac重装系统系列教程(三)：如何用U盘给Mac重装系统](https://pic4.zhimg.com/v2-36b258c86c2f4fc0dd183e6aebb3c721_1200x500.jpg)

# Mac重装系统系列教程(三)：如何用U盘给Mac重装系统

[![一点通](https://pic2.zhimg.com/v2-7ec833f42102504fbc4df535105b8809_xs.jpg)](https://www.zhihu.com/people/leng-yue-47-97-38)

[一点通](https://www.zhihu.com/people/leng-yue-47-97-38)

推荐Mac软件及教程类文章

关注他

8 人赞同了该文章

上次我们提到的「网络在线重装」最多只能实现 3 个版本的系统重装：电脑当前装有的系统、官方最新的系统、出厂系统。所以，如果你想装的系统属于这三者之外，就只能使用「U盘引导重装」！今天给大家带来的教程就是通过U盘来给MAC重装系统。

先在 App Store 或者网盘等第三方渠道下载系统，然后在 Mac 上用「终端代码」或者「引导盘制作工具」将系统写入 U盘，制作成一个引导盘。开机时，按住 option 键进入引导盘，即可开始安装。整个过程在一个小时左右，具体时间取决于你的网速、U盘写入速度和机器性能。

**首先我们需要知道几个大前提：**

1，重装的版本不能低于你购买MAC的出厂版本，2015年款预装的是10.10（ OS X Yosmite），2016年款预装的是10.11(OS X EI Capiton)，2017年款是10.12（MAC OS Sierra），这个是大版本号，每个大版本随着时间的推移还会推出一些小功能和修复Bug的版本，例如10.10.1，10.11.4，10.12.6。

2，重装请提前备份自己的资料，抹盘安装最干净，但是机器有价，数据无价

3，由于Mac采用的是索引式文件系统，如果你是通过在APP STORE中下载的APP文件升级系统，可能会存在升级后卡顿，发热甚至升级失败进不去系统的情况（尤其是跨大版本的升级，10.12升级到10.13这样的情况），所以，还是推荐你使用U盘对你的MAC进行系统升级和重装。

**接下来我们开始重装系统**

假设我们现在已经有了系统U盘（后续我会发制作系统U盘的教程），在开机的时候按住电脑的Option键，就是这个



![img](https://pic3.zhimg.com/80/v2-715559ed27b022dcda37fe7c1f6078a6_720w.jpg)



然后电脑会出现以下画面



![img](https://pic3.zhimg.com/80/v2-a346ddc7e7709da01a2d26e7e3df4202_720w.jpg)



以我的电脑为例，左边三个是本机的硬盘，后面两个就是我的U盘，因为U盘容量比较大，本着不浪费的原则我做了两个平时用的比较多的版本在U盘了，我们通过键盘上的方向键移动光标，回车键确认从U盘启动。

接下来会有一个读条，速度取决于U盘的读取速度，出现如下界面说明已经成功从U盘启动，进入到了恢复分区

我们先进入磁盘工具



![img](https://pic2.zhimg.com/80/v2-3bcbf1867fc37af4835f1e5262cf62cd_720w.jpg)



这里以macos High Sierra10.13为例，先点击磁盘工具左上角的箭头，下拉选项改成显示所有设备



![img](https://pic4.zhimg.com/80/v2-d385cdfa994ca2df91ad040bccab46db_720w.jpg)



最上面的APPLE SSD就是你的硬盘，选中这个，点磁盘工具这几个字下面的抹盘，名称使用英文或数字，不要使用中文，格式选择MAC OS扩展日至式，方案为GUID分区表

有的朋友会问10.13不是APFS格式吗，确实是这样，现在选择MAC OS扩展日志式，安装完成后系统会自动将分区格式转换成APFS格式。



![img](https://pic2.zhimg.com/80/v2-03534dc68c445e0724dffbd7f9a3f6c9_720w.jpg)



抹盘完成后，推出磁盘工具（提出的快捷键为command+q），选择 安装macos



![img](https://pic1.zhimg.com/80/v2-6d1865dea1f7ff2e21291a525c4a3b84_720w.jpg)



接下来的操作看图就好



![img](https://pic1.zhimg.com/80/v2-0d77fa84edeea5c9ad4a221b442c3cbc_720w.jpg)





![img](https://pic4.zhimg.com/80/v2-44e22a10e532cb80137acb7fb163ab13_720w.jpg)





![img](https://pic4.zhimg.com/80/v2-78c3f6f10f90420b12b464326b66477f_720w.jpg)





![img](https://pic3.zhimg.com/80/v2-10eca07ea968c04d33f5982cfcf9eb36_720w.jpg)



中间会重启2-3次



![img](https://pic2.zhimg.com/80/v2-1786fefea71d3b5bf9a182a1e55b9109_720w.jpg)





![img](https://pic4.zhimg.com/80/v2-c304b27092a68a4e4bd2b17ccaa15707_720w.jpg)



看到这个界面就说明已经重装完成了 ， 接下来进行自定义设置就可以了

![img](https://pic2.zhimg.com/80/v2-5f509972d660de89fa4f8af002d9f4b5_720w.jpg)

相关教程

[一点通：Mac重装系统系列教程(一)：哪些情况下需要重装系统？zhuanlan.zhihu.com![图标](https://pic2.zhimg.com/v2-36b258c86c2f4fc0dd183e6aebb3c721_180x120.jpg)](https://zhuanlan.zhihu.com/p/101196884)[一点通：Mac重装系统系列教程(二)：网络在线重装系统zhuanlan.zhihu.com![图标](https://pic2.zhimg.com/v2-36b258c86c2f4fc0dd183e6aebb3c721_180x120.jpg)](https://zhuanlan.zhihu.com/p/101197829)



编辑于 2020-01-06