---
layout: post
title:  "github+jekyll搭建个人博客"
date:   2017-7-6
excerpt: "github+jekyll搭建纯静态个人博客电脑小白也可以(*^__^*) 嘻嘻……."
tag:
- markdown 
- syntax
- sample
- test
- jekyll
comments: true
---

## 下载安装git
	
##  	什么是git？

##  	卧槽，好吧…

##	git是一个“版本控制”工具。

## 	什么是版本控制？

## 	伙计，你看，这是一把菜刀对不对？它可以用来砍死你！

##	你自己去Google啊！

## 	那怎么装git呢？


## [git传送门](https://git-scm.com/)
## 第一步 
<figure>
	<a href="https://xiongsu.github.io/img/gitone.png"><img src="https://xiongsu.github.io/img/gitone.png"></a>
	<figcaption><a href="https://git-scm.com/" title="传送门">点击图片去往git</a>.</figcaption>
</figure> 
##	所有点击下一步即可完成安装.
##	装好之后，打开你机器上的终端，Windows上叫“命令提示符”，在里面敲git试试，如果出现了这样的内容，说明安装成功了.
<img src="http://damoqiongqiu.github.io/assets/img/jekyll-3/cmd-git.png">

##可是我不喜欢这样的命令行界面啊！

##那就对了，所以你需要小乌龟啊！

##	[点击这个传送门](https://download.tortoisegit.org/tgit/)	
##	安装完小乌龟之后，在你的桌面的任意空白位置右键，你会看到多出来几个和小乌龟相关的菜单. 
<img src="http://damoqiongqiu.github.io/assets/img/jekyll-3/tortoise-menu.png">
##	这就说明git和小乌龟都安装成功了！
# 第二步 
# 创建github账号
##这颗星球上有一个神奇的网站叫github，它是男人的乐园，女人的噩梦。这么好的网站，你一定想要一个账号对不对？
<img src="http://damoqiongqiu.github.io/assets/img/jekyll-4/github-register.png">

## 注册成功之后Sign in（登录）进去，点击Your profile菜单到你自己的用户资料页去看看都有什么内容：
<img src="https://xiongsu.github.io/img/githubuser.png">
##	点击New Repository菜单，进入创建仓库界面，下面的内容请看仔细：
<img src="https://xiongsu.github.io/img/githubnew.png">
<img src="https://xiongsu.github.io/img/githubnewre.png">
## 	我这里有错误提示，因为我已经创建过同名的仓库啦！
##	创建完成之后，进入项目主页，就像这样：
<img src="https://xiongsu.github.io/img/githubprotion.png">
##下一步，用小乌龟把这个项目克隆到你本地去，在项目主页上点这里：
<img src="https://xiongsu.github.io/img/githubclone.png">
##然后在你的电脑里面任意选择一个目录用来放内容，在任意空白处右键，选择”Git clone”
<img src="https://xiongsu.github.io/img/gitclone.png">
##	看到Success了不？说明克隆成功，这样仓库的内容就到你本地了：
<img src="https://xiongsu.github.io/img/gitsuceec.png">
##接下来测试一下commit和push。
##用你机器上的任意编辑器打开项目根目录下的README.md，如果没有这个文件，你可以手动创建一个，随意输入一些内容，然后在项目根目录里面任意空白处右键，选择Git commit->”master”这个菜单，弹出以下界面：
<img src="https://xiongsu.github.io/img/gitcommit.png">
##	commit完成之后，再次在空白处右键：
<img src="http://damoqiongqiu.github.io/assets/img/jekyll-4/git-push.png">
##	操作完成之后，你刚才修改的内容就被push到仓库里面去啦！
##	不信？去你的项目主页上刷新一下，确认一下刚才的内容有没有进来。
##	现在，你可以打开你的主页看看有没有内容，http://你刚才注册的名字.github.io
##当然，你也可以到项目的Settings菜单里面去设置一个theme（主题），然后刷新看看有没有效果。不过这个不重要，因为紧接下来我们会安装jekyll，到时候有更多样式可以选择。
Lorem ipsum dolor sit amet, test link adipiscing elit. **This is strong**. Nullam dignissim convallis est. Quisque aliquam.

![Smithsonian Image](https://mmistakes.github.io/minimal-mistakes/images/3953273590_704e3899d5_m.jpg)
{: .image-right}

*This is emphasized*. Donec faucibus. Nunc iaculis suscipit dui. 53 = 125. Water is H2O. Nam sit amet sem. Aliquam libero nisi, imperdiet at, tincidunt nec, gravida vehicula, nisl. The New York Times (That’s a citation). Underline.Maecenas ornare tortor. Donec sed tellus eget sapien fringilla nonummy. Mauris a ante. Suspendisse quam sem, consequat at, commodo vitae, feugiat in, nunc. Morbi imperdiet augue quis tellus.

HTML and CSS are our tools. Mauris a ante. Suspendisse quam sem, consequat at, commodo vitae, feugiat in, nunc. Morbi imperdiet augue quis tellus. Praesent mattis, massa quis luctus fermentum, turpis mi volutpat justo, eu volutpat enim diam eget metus.

### Blockquotes

> Lorem ipsum dolor sit amet, test link adipiscing elit. Nullam dignissim convallis est. Quisque aliquam.

## List Types

### Ordered Lists

1. Item one
   1. sub item one
   2. sub item two
   3. sub item three
2. Item two

### Unordered Lists

* Item one
* Item two
* Item three

## Tables

| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|----
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|=====
| Foot1   | Foot2   | Foot3
{: rules="groups"}

## Code Snippets

{% highlight css %}
#container {
  float: left;
  margin: 0 -240px 0 0;
  width: 100%;
}
{% endhighlight %}

## Buttons

Make any link standout more when applying the `.btn` class.

{% highlight html %}
<a href="#" class="btn btn-success">Success Button</a>
{% endhighlight %}

<div markdown="0"><a href="#" class="btn">Primary Button</a></div>
<div markdown="0"><a href="#" class="btn btn-success">Success Button</a></div>
<div markdown="0"><a href="#" class="btn btn-warning">Warning Button</a></div>
<div markdown="0"><a href="#" class="btn btn-danger">Danger Button</a></div>
<div markdown="0"><a href="#" class="btn btn-info">Info Button</a></div>

## KBD

You can also use `<kbd>` tag for keyboard buttons.

{% highlight html %}
<kbd>W</kbd><kbd>A</kbd><kbd>S</kbd><kbd>D</kbd>
{% endhighlight %}

Press <kbd>W</kbd><kbd>A</kbd><kbd>S</kbd><kbd>D</kbd> to move your car. **Midtown Maddness!!**

## Notices

**Watch out!** You can also add notices by appending `{: .notice}` to a paragraph.
{: .notice}
