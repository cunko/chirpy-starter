---
title: Windows
author: cotes
date: 2019-08-08 14:10:00 +0800
categories: [Blogging, Tutorial]
tags: [writing]
render_with_liquid: false
---

## 虚拟桌面：

> win10的虚拟桌面真是一个好东西，我们可以在不同的桌面做不同的事情，互不干扰。每个人都有自己的隐私，我们可以在桌面1里办公，在桌面2里看电影。在没其他人时，我们就切换到桌面2看看电影，放松放松；在有人的时候，我们再切换到桌面1办公。可将任务分别在不同的桌面运行，从而提高桌面整洁与速度，当一个桌面任务太多时使用第二桌面，第二桌面上的任务不会受到第一桌面的任务干扰，运行速度会提高，第一桌面的任务会被暂时冻结，就和苹果手机一样，后台任务都是 冻结状态直到你切换回后台任务。

打开虚拟桌面的快捷键    win + Tab
新建虚拟桌面的快捷键  win + ctrl + D
切换虚拟桌面的快捷键    win + ctrl + 左/右方向键 
关闭当前虚拟桌面的快捷键  win + ctrl + F4
简单切换：Alt+Tab
小视图切换：Ctrl+Alt+Tab

## 打开设备管理器：

Win+X组合键或右键点击Win10开始按钮即可打开系统快捷菜单，在里面找

## 常用快捷键：

调出运行对话框    win+r
启动剪贴板      win+v
返回桌面    esc+ctrl 
一键返回桌面      win+d 
撤销操作：Ctrl+z
恢复之前所撤销的操作：Ctrl+y
快速创建同级界面：Ctrl+n
召唤任务管理器：Shift+Ctrl+Esc
锁屏：Win+L
打开我的电脑：Win+e
放大镜：Win++/-
快速关闭网页：Ctrl+W
恢复关闭的网页：Ctrl+Shift+T
强制关闭软件和关机：Alt+F4
软件透明化：Win+,
快速打开任务栏应用：Win+1~9
应用程序分屏：Win+/一>
文件多选：   点击其中一个文件，按Ctrl键依次点击选中

打开设置    win + i

打开控制面板：win + r   ,然后control



## 截图录屏：

window系统截图：  Shift+Win+s
微信截屏   alt+A
QQ录屏         Ctrl+alt+S
QQ截屏      ctrl+alt+A

## 其它：

Devi++中代码对齐   Ctrl+shift+a  
微软Xbox录屏     Win+g

对于习惯使用快捷键的朋友，这应该不陌生。这是是最快的恢复chrome已关闭网页的方法。很多人不知道Chrome浏览器撤销关闭页面的快捷键是什么，其实这是一个组合键，即Crtl+Shift+T。



# PyCharm常用快捷键：

**Ctrl+/**：用于注释或取消注释

**Ctrl+R**：快速替换

Ctrl+F是搜索

**Ctrl+Alt+L**：快速整理代码

**Shift**两次：查看项目资源

**Ctrl+shift+A**:万能命令行

**Ctrl+C**:复制当前行

**Ctrl+D**:快速复制上一行

Shift + Enter开始新行

Ctrl + Enter智能换行

Ctrl+Shift+左右键：快速选中，并进行移动 

Ctrl+Shift+F10:运行代码

###**debug**

![](https://liuliutuku.oss-cn-hangzhou.aliyuncs.com/tupian0/kdeaw43ozhj44_bf2a59bbd7e34796821116607f44de8b.png)

**debug窗口几个图标分别代表的意思**

1.show execution point (F10)
显示当前所有断点

2.step over(F8) 
单步调试。若函数A内存在子函数a时，不会进入子函数a内执行单步调试，而是把子函数a当作一个整体，一步执行

3.step into(F7) 单步调试。
若函数A内存在子函数a时，会进入子函数a内执行单步调试。

4.step into my code(Alt + Shift +F7) 
执行下一行但忽略libraries（导入库的语句）

5.force step into(Alt + Shift +F7) 
执行下一行忽略lib和构造对象等

6.step out（Shift+F8）
当目前执行在子函数a中时，选择该调试操作可以直接跳出子函数a，而不用继续执行子函数a中的剩余代码。并返回上一层函数。

7.run to cursor(Alt +F9) 
直接跳到下一个断点，然后接着来看变量查看器。

在调试过程中观察变量的状态。我们需要对其设置一个查看器。在Watches窗口中，单击加号，输入期望查看的变量名称，例如这里输入delay，然后回车。我试了三个变量，这里我们看到这三个变量目前都是没被定义的，我们可以在控制台里给它定义，也可以通过执行下一步，利用代码中的赋值来定义。

![](https://liuliutuku.oss-cn-hangzhou.aliyuncs.com/tupian0/kdeaw43ozhj44_71e01838c2ce4a4ab31a30ff947bdf17.png)

可以通过点击这个眼睛图标，将这两个窗口连在一起查看

![](https://liuliutuku.oss-cn-hangzhou.aliyuncs.com/tupian0/kdeaw43ozhj44_b62da6079fb145b48f642db6be65edf0.png)


一般操作步骤就是，设置好断点，debug运行，然后 F8 单步调试，遇到想进入的函数 F7 进去，想出来在 shift + F8，跳过不想看的地方，直接设置下一个断点，然后 F9 过去。

**控制台窗口：**

![](https://liuliutuku.oss-cn-hangzhou.aliyuncs.com/tupian0/kdeaw43ozhj44_514654dbc041498983b942b707d004ea.png)