# 高效阅读Github源代码

[![陈龙](https://pic2.zhimg.com/v2-95f6230923f3e3af243b7fe6cef222aa_xs.jpg)](https://www.zhihu.com/people/chenlong7890)

[陈龙](https://www.zhihu.com/people/chenlong7890)

代码不停思考不止

关注他

3,487 人赞同了该文章

三种办法。如果你主要看前端项目的代码，直接看第三种。



1，用Chrome插件Octotree，左侧会出现树形结构，方便你浏览源代码。

![img](https://pic4.zhimg.com/80/v2-d26c4b7b877a60ea0db19e116dc724cb_720w.jpg)

地址：

[https://chrome.google.com/webstore/detail/octotree/bkhaagjahfmjljalopjnoealnfndnagcchrome.google.com](https://link.zhihu.com/?target=https%3A//chrome.google.com/webstore/detail/octotree/bkhaagjahfmjljalopjnoealnfndnagc)

类似的插件还有Sourcegraph：

![img](https://pic1.zhimg.com/80/v2-c1e4fda46ced0ab0b55e1fc975273cb4_720w.jpg)

地址：

[https://chrome.google.com/webstore/detail/sourcegraph/dgjhfomjieaadpoljlnidmbgkdffpack?utm_source=chrome-ntp-iconchrome.google.com](https://link.zhihu.com/?target=https%3A//chrome.google.com/webstore/detail/sourcegraph/dgjhfomjieaadpoljlnidmbgkdffpack%3Futm_source%3Dchrome-ntp-icon)

2，用Github Desktop桌面应用。方便把代码clone到本地，然后进行各种git操作。

![img](https://pic3.zhimg.com/80/v2-f5ebdd6628c0a29a531516c9d28b57b6_720w.jpg)

Github Desktop地址：

[Simple collaboration from your desktopdesktop.github.com![图标](https://pic3.zhimg.com/v2-f1e06a1ec075eeda12cce2c37635af7e_180x120.jpg)](https://link.zhihu.com/?target=https%3A//desktop.github.com/)

至于为什么不提SourceTree，是因为我的题目是高效阅读Github源代码，Github Desktop是官方提供用来操作Github的工具。虽然当然并不仅限于Github上托管的git库，但是用于Github毕竟更方便。



3，如果你开发前端(Angular,React,ES6,Typescipt)，**那么最推荐这种方式**！直接把Chrome变成一个在线IDE。帮你把npm包都准备好，直接可以运行。

只要把github地址改成[https://stackblitz.com/](https://link.zhihu.com/?target=https%3A//stackblitz.com/)github开头就可以了。

例如下面视频中，Github项目地址是

```http
https://github.com/gothinkster/angular-realworld-example-app
```

改成

```http
https://stackblitz.com/github/gothinkster/angular-realworld-example-app
```

<iframe frameborder="0" allowfullscreen="" src="https://www.zhihu.com/video/969595475871170560?autoplay=false&amp;useMSE=" style="display: block; width: 687.993px; height: 386.996px;"></iframe>



Stackblitz官方地址：

[Online VS Code IDE for Modern Web Applicationsstackblitz.com![图标](https://pic4.zhimg.com/v2-e8f746f9d53910f46bc19370424ca297_180x120.jpg)](https://link.zhihu.com/?target=https%3A//stackblitz.com/)

Stackblitz可以算是一个在线VS Code，关于Stackblitz等多内容可以看：

[https://blog.angular.io/run-angular-cli-repos-directly-in-your-browser-41332fd80901blog.angular.io](https://link.zhihu.com/?target=https%3A//blog.angular.io/run-angular-cli-repos-directly-in-your-browser-41332fd80901)[https://medium.com/@ericsimons/stackblitz-online-vs-code-ide-for-angular-react-7d09348497f4medium.com](https://link.zhihu.com/?target=https%3A//medium.com/%40ericsimons/stackblitz-online-vs-code-ide-for-angular-react-7d09348497f4)



如果你觉得修改URL还是太麻烦，那么看这里：

[NG-NOWjdjuan.github.io](https://link.zhihu.com/?target=https%3A//jdjuan.github.io/ng-now/)

拖拽左上角的图标成为Bookmark，以后只需要访问Github上的Angular项目，然后点击书签就可以了。





最后想说，用Stackblitz配合GitHub Pages开发个人主页什么的，那简直是太绝配了！！！你们想到了没有？

[GitHub Pagespages.github.com![图标](https://pic3.zhimg.com/v2-3b40b9cb37daf99cb55038deae0d64aa_180x120.jpg)](https://link.zhihu.com/?target=https%3A//pages.github.com/)



\--------------------------------------------------------

评论区有人指出第三种方法只适用于@angular/cli创建的项目，我试了一下，确实是：

![img](https://pic4.zhimg.com/80/v2-b8c16a1352debc18130a1965e870f767_720w.jpg)

但是在官方文档里是这么写的：

> Yup, you can point directly at Github repos containing Angular/React projects and it'll automatically pull them down & run them.

[Documentation - StackBlitzstackblitz.com![图标](https://pic4.zhimg.com/v2-317023786387a95ff87e06e6fc8c6ed3_180x120.jpg)](https://link.zhihu.com/?target=https%3A//stackblitz.com/docs%23open-and-embed-github-repos)

所以React的项目，敬请期待吧！



------

想学习Java Web开发，成为Web全栈？

服务器端想学习Spring Boot和Spring Cloud？

前端想学习Typescript和Angular？

不知道前后端如何分离如何配合？

请关注：

[陈龙：用JHipster做Java Web全栈开发zhuanlan.zhihu.com![图标](https://pic2.zhimg.com/v2-71d39341a1c16ab2dc53950d4ef191f5_180x120.jpg)](https://zhuanlan.zhihu.com/p/36382239)



编辑于 2018-11-01