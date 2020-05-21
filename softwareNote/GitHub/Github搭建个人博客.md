# **基础**



## **第一步：注册Github账号**。

请点击这里[github.com](https://link.zhihu.com/?target=https%3A//github.com/)注册。注意，账号的取名很重要，因为你的username将成为你免费网站域名的核心部分，它将长成这样：*yourusername*.[http://github.io](https://link.zhihu.com/?target=http%3A//github.io)，比如我选的用户名是klovien，所以网站名就是：[klovien.github.io](https://link.zhihu.com/?target=https%3A//klovien.github.io/)。（当然，如果你打算注册使用付费域名，账号取名就不重要了。）

## **第二步：复制我的网站**。

注册登录Github后，请点击这里[klovien/klovien.github.io](https://link.zhihu.com/?target=https%3A//github.com/klovien/klovien.github.io)进入到我的仓库，看到如下界面，然后请点击最右上角的“Fork”按钮。

![img](https://pic2.zhimg.com/80/v2-82b8be6b74040645c0c5ea41e614ed75_720w.jpg)图1 待复制的目标仓库

等几秒钟，复制完成后，你会看到界面几乎还是上图这样一个界面，但左上角的仓库名改成了*yourusername*/[http://klovien.github.io](https://link.zhihu.com/?target=http%3A//klovien.github.io)。她是你的了！

并且这个时候在标签行的最后面，增加了一个“Settings”标签（就在刚刚那个Fork按钮下面靠左一点点的地方）。注意你目前在你的仓库的“Code"标签页，所以请点击换到“Settings”标签页，进去后看到下图的界面。现在你只要把下图中仓库名中的“klovien"这个单词改成**你账号的username**，注意保留.[http://github.io](https://link.zhihu.com/?target=http%3A//github.io)不要变啊，点击Rename。哈哈，搞定了。

![img](https://pic2.zhimg.com/80/v2-249351ec94754166ca841a5e9af1cbfd_720w.jpg)图2 把仓库名的第一部分改为你的用户名

现在新开个浏览器窗口输入*yourusername*.[http://github.io](https://link.zhihu.com/?target=http%3A//github.io)看看效果吧，这就是你的博客主页面了。是不是很简单很爽的一件事？（若没出现下图，而是显示404错误，那就是上图中的改名没改对，请仔细检查一下输入的是不是你的username，有没有拼错）

![img](https://pic2.zhimg.com/80/v2-22b8885746cef5e0083b91bb58a981a9_720w.jpg)图3 你复制完成后的网站模样

等等！这招牌是什么？？？—— 嗯，招牌当然需要改成你的咯，请继续往下走。

**第三步，改成你的招牌**。现在，回到你仓库的Code标签界面，往下慢慢瞧，找到这个文件：_config.yml，点击进去看到下面的界面。点击右上角的那只笔进入编辑模式，把红箭头指到的地方，一一改成你想要的东西吧。最后一个箭头，是头像文件，假定你暂时还不知道怎么上传文件，所以改成这个好了：/img/about-someone.jpg，嗯，我放了个空白头像在那里 。

![img](https://pic4.zhimg.com/80/v2-bca63121fccabc05cb6566c0dc59c84f_720w.jpg)图4 修改网站关键信息，成为你自己的网站

**至此，大功告成**！再到你的博客主页面（*yourusername*.[http://github.io](https://link.zhihu.com/?target=http%3A//github.io)）看看，是不是这些信息都改成你的了？

下一步，你就可以在仓库的“Code"标签页的_posts目录下面，添加你自己的博客文章了：点击进入_posts目录，点击右上角的“Create new file"按钮，文件名设为“yyyy-mm-dd-文章标题.md”（注意后缀名），复制下面的模板内容到编辑框里面，写好你想写的内容，然后在最下面点”Commit new file" 按钮保存即可。现在回到你的博客主页面，多刷新几次，你的第一篇博客就能出现了！（我原有的文章，你尽可以删掉）

> \---
> layout: post
> title: （文章标题）
> subtitle:（副标题）
> date: 2018-12-01
> author: （作者名）
> header-img: img/the-first.png
> catalog: true
> tags:
> \- 我的往事
> \---
> \# 一级标题
> \## 二级标题
> （正文内容）

至此，建站已完成，没有用到一行代码。只做了复制和改几个字的事情，足够简单吧！

为了方便你自己，把你的仓库的描述（Description/Website）改一下。就是对应于第一张图的 “Wellcome to contribute. https:// klovien.github.io” 那个地方，改一下，尤其要把Website改成你自己的域名，这样，你就可以点击它直接进入到你的博客了。

进一步的完善修改，请看我下一篇文章《[在Github上搭建免费个人网站和博客（进阶篇）](https://zhuanlan.zhihu.com/p/111832962)》。我建议你不要急，慢慢来，可以先写几篇文章玩玩，慢慢再来改网站。

> 在进阶前，如果你看到复制来的About和Resources的内容很烦，暂时又不知道怎么改的话，请把仓库Code标签下的两个文件：1-resources.html、2-about.html，删掉（点击该文件，再点击类似图4中那支笔旁边的垃圾桶）。放心，如果需要的话，等你学会修改了，还可以从我这里copy回去改的。

致谢

特别致谢BY，我的博客是从他那里Fork来的，而且他也写了很详细的教程[《快速搭建个人博客》](https://link.zhihu.com/?target=https%3A//qiubaiying.github.io/2017/02/06/%E5%BF%AB%E9%80%9F%E6%90%AD%E5%BB%BA%E4%B8%AA%E4%BA%BA%E5%8D%9A%E5%AE%A2/)。如果我的下一篇进阶的文章还没写出来，而你急着要完善自己的网站，不妨继续参考BY的教程。

我之所以重新编写教程，是基于两个原因：

1. BY的教程虽然已经浅显易懂了，但对真正的小白来说，内容还是有些复杂有点儿长。我第一次尝试的时候，就觉得还是太麻烦了，所以放弃了。然而到Wix转了几个月回来后，才发现这个方法真的是很简单又好用的。所以我现在把BY的教程按我的理解做了重新的编排，确保从零开始到发表第一篇博客的过程中，涉及到的知识量最少。
2. BY貌似已经停止更新这个博客，也不再回答问题，所以我希望能通过我这个工作，把这件事情继续下去，发扬光大。

希望BY如果看到这篇文章，是欣慰而不是介意。

------

> 注：我们实际上使用的是Github Pages在搭建网站，但这名字是什么并不重要。

# **提高**

## 1、如何修改、删除或创建文件？

从我这里Fork网站过去后，你的第一件事是改配置（_config.yml文件**）**，然后除了写博客，就是改“About”（about.html文件**）**，因为你不想里面的内容还是介绍我的。我们在初级篇中讲到了这个，就是在每个文件点开后，右上角有一只笔，点击可以修改文件。笔旁边有一个垃圾桶，点击可以删除文件。

![img](https://pic3.zhimg.com/80/v2-ba1369778abc1d81a5e965413c977072_720w.jpg)

那么创建新文件，就是在每一级目录文件列表的页面，右上角有一个“Create new file”，点击它就可以新建文件。旁边还有个“Upload files”，想上传文件也可以。

![img](https://pic1.zhimg.com/80/v2-6c293afa8debf5d271587ba7e265873c_720w.jpg)

而Gitee的这些东西都是中文按钮，所以看看就懂，这里就不讲了。

关于文件操作知道这些就够了。更复杂的操作在客户端上做要方便得多，下面第3部分讲如何安装使用客户端。

## 2、如何调整菜单？

你看到网站的右上角的菜单，其实是指向一个个文件。这些文件就是主目录下的所有.html文件，除了index.html代表Home所以必定在第一个位置之外，其它文件都是按照文件名排序从左到右排列过去的。

![img](https://pic1.zhimg.com/80/v2-68273c394a4f8e289e8b557f0c91c020_720w.jpg)

所以为了控制菜单次序，需要在文件名前加上1、2、3这样的数字。至于这个按钮的名字，是在文件内容中第一行的“title:”后面写的，所以若你要中文菜单的话，改那个地方就可以了，不需要改文件名。

如果你要增加菜单按钮，那么也要创建相应的.html文件，并如上所述控制好次序。

## 3、客户端与本地调试

以上都是少量修改。如果有比较大量的修改，建议安装Github客户端：[GitHub Desktop](https://link.zhihu.com/?target=https%3A//desktop.github.com/)。

下载安装好后，用你的github账号登录，然后选择你的仓库名，克隆（Clone）到本地。点左边栏（或左上角）的仓库名，右边会出现这样的内容：

![img](https://pic1.zhimg.com/80/v2-87ece8b0a9ffd56927b24b81eb49d9b8_720w.jpg)

上面一行的按钮是打开文件管理器，点击你就可以看到你本地电脑上的对应Github仓库的文件目录，跟网上的目录结构完全一样：

![img](https://pic3.zhimg.com/80/v2-4bcffce35639815a2187b03284c3097e_720w.jpg)

然后你就可以在本地修改、删除、增加文件，包括文件目录操作。其中_posts是存放你的博客文章的地方，img存放图片的地方。

若在本地文件夹里有任何改动，当你回到Github Desktop时，它会列出你刚才做的改动，然后你点左下角的“Commit”之后，是这个样子：

![img](https://pic1.zhimg.com/80/v2-68dbbf71f11e82efe1ff3285df9af580_720w.jpg)

然后点右边的“Push origin”，就把本地的改动同步到网上去了。

现在你想修改头像就简单了：先把头像图片放到本地img目录下，修改_config.yml文件中关于头像的那一行为你的图片文件名，然后Commit、Push同步到网上就可以了。

对于大量的修改来说（例如批量删除文章，或批量修改文章的文件名），本地修改文章比直接在网上改要方便得多。但这还算不上“本地调试”，本地调试的预备过程比较麻烦，这里就不讲了，想了解可以去看看BY的原文。

那么有人问，Gitee也有客户端吗？答案是没有。但我悄悄告诉你，Github Desktop是可以用于Gitee的。方法很简单：点击左上角的Add，选择Clone Repository，然后在下面这个界面上选URL，把你Gitee仓库的URL地址拷贝进去，点击“Clone”，就可以了。这样你左边栏会增加一个Gitee的项目仓库，类别是“other”。

![img](https://pic3.zhimg.com/80/v2-6396bab18a97d509317a20bab8b89e0a_720w.jpg)

2. 