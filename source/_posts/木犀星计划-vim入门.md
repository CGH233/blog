---
title: 木犀星计划--vim入门
date: 2018-07-23 18:40:28
tags:
---

什么是Vim
-----
+ Vim是从 vi 发展出来的一个文本编辑器。代码补完、编译及错误跳转等方便编程的功能特别丰富，在程序员中被广泛使用。和Emacs并列成为类Unix系统用户最喜欢的编辑器。
+ 官方网站[Vim](http://www.vim.org)。 



Vim安装
-----
+  一般Ubuntu系统会自带Vim，但我们还是在命令行运行一下安装命令保险。(以下操作均需英文输入法。)
	1. 打开虚拟机
    2. 调出终端
        + 在虚拟机桌面时，同时按下`Ctrl`+`Alt`+`T`三键即可调出终端。
        + 如果不成功也可点击左侧菜单最上方的`搜索您的计算机`按钮或键盘上的`微软图标键`(如果有)唤出搜索框，输入`terminal`找到终端并打开。
    3. 安装Vim
        + 在终端命令行输入以下命令并回车
        ```
        sudo apt-get install vim
        ```
        + 系统会提示你输入本机的开机密码，输入后回车。（ps：输入密码时是完全没有显示的，并不是没输进去。）
        + 安装完成。
    4. 测试
        + 继续在终端中输入`vim`并回车即可打开vim。
        + 输入`:q`并回车以退出vim回到终端或直接左上角关闭。

        

Vim简单使用
-----
+ Vim运行于终端，用于创建并编辑文本(敲代码~~装X~~就靠他了)，以后要学的C,Python,C++等都可以用Vim编写。
+ 这里编辑一个a.txt文件演示一下。
	1. 打开终端
	2. 创建文本
		+ 在命令行中输入
		  ```
		  vim a.txt
		  ```
		  即可创建一个名为a的txt文件，其实不加拓展名也可以，但加了有助于Vim识别文本类型并高亮一些内容以增加可读性。
	3. 编辑文本
		+ 刚打开a.txt只能阅读它，编辑需要按`i`进入编辑模式。
	4. 保存
		+ 按`Esc`键可退出编辑模式，之后输入`:w`即可保存已编辑内容。
	5. 退出
		+ 退出Vim
			退出编辑模式后输入`:q`
		+ 保存并退出Vim
			退出编辑模式后输入`:wq`
		+ 强制退出
			退出编辑模式后输入`:q!` 

*深入
-----
现在应该已经可以使用Vim了，但Vim之所以很火是因为其上手后强大的编辑能力，这里不细讲，贴几个网址，有兴趣可以深入学习。
+ [简明Vim练级攻略](https://coolshell.cn/articles/5426.html)
+ [Vim 菜鸟教程](http://www.runoob.com/linux/linux-vim.html)
+ [Vim入门基础](https://www.jianshu.com/p/bcbe916f97e1)


