装MySQL的时候，第一步成功安装完成很是开心，怀着开心的心情继续安装第二步的时候就遇到了问题，从网上搜了很多的资料还是安装不上，骑虎难下。于是想到重新安装，重装必须先把原来的安装卸载干净才行，我花了3个晚上搜集了很多资料，反复实验，终于安装成功了，为了自己能记住这些来之不易的解决办法，并能帮助跟我遇到一样问题的小伙伴，希望能节约他们的时间，我把解决办法写了下来，步骤如下，供参考！

1. 先停止MySQL服务，cmd模式下输入net stop mysql;

2、找到“任务管理器下“-“服务”-“MySQL,把“正在运行”改成“停止”或者“禁用”

![img](https://pic2.zhimg.com/80/v2-f4b0ff16a8c6fb0b56f44f04619ad385_720w.jpg)

3、进入控制面板“程序和功能”卸载;

4、删除MySQL文件夹下的my.ini文件及所有文件;

5、运行“regedit”文件,打开注册表，删除MySQL文件HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Services\Eventlog\Application\MySQL

HKEY_LOCAL_MACHINE\SYSTEM\ControlSet002\Services\Eventlog\Application\MySQL

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\Eventlog\Application\MySQL

6、删除C盘下的“C:\ProgramData\MySQL ”所有文件，有的ProgramData文件是隐藏

的，设置显示后即可见。

7、然后是删除MySQL的安装位置（没有的可忽略）

C:\Program Files\MySQL文件夹

C:\Program Files (x86)\MySQL文件夹

8、环境变量下“系统变量”下面的两个路径删掉

![img](https://pic1.zhimg.com/80/v2-20d442b41f21db64541385163d2cf2d8_720w.jpg)

9、最后可能MySQL服务还存在：

有时候按照所有的步骤完成了卸载后，服务中却还有MySQL的相关服务存在，为此我们应该删除相关的服务。具体的做法就是：以管理员权限的方式打开cmd命令窗口，然后将在cmd命令中输入命令：sc delete mysql ，通过该命令就可以删除相关的服务。



经过这么多的步骤，总算卸载干净了，是不是重新安装就能成功了呢？那也不一定，还有2个安装的小细节需要注意一下：

1、需要重新启动MySQL服务（因为前面第2步把SQL“停止”或者“禁用”了）,否则出现下面的错误。



![img](https://pic1.zhimg.com/80/v2-9cb28c5324e6ff62622c2a826a885434_720w.jpg)

2、配置文件my.ini编码应为:ANSI，如果是UTF-8会显示找不到文件，或者出错之类的

![img](https://pic3.zhimg.com/80/v2-9ffd1e84f782cc7dc7f83999b3e9a58e_720w.jpg)

**经过以上的设置终于重新安装完成了，真心的不容易呀！**







编辑于 2019-06-05