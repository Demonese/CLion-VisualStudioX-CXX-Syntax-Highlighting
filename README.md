# 用于 CLion 的 Visual Studio 风格 C/C++ 语法高亮配色

## 简介

这是一个基于自带的暗色主题Darcula制作的语法高亮配色。

色全都是在`Visual Studio`和`Visual Studio Code`里面里面吸的 ~~Visual Studio 娘原味配色~~ 。目前能还原的都尽可能还原了，并加上了我的一些个人风格的 ~~调教~~ 改动。

_CLion：啊~我的C/C++语法高亮配色，已经变成 Visual Studio 的形状了。_

特别感谢 [@Xiliusha](https://github.com/Xiliusha) 帮我吸色和提出了一些改进意见。

## 特点

* 同时吸收了`Visual Studio`和`Visual Studio Code`的变量配色风格，全局是粉红色 ~~可爱~~ ，局部变量或者成员变量是天蓝色，参数是灰色，方便识别。
* 命名空间的配色来自于ReSharper ~~ReSharper真好用，可惜比CLion贵，还经常卡死我的 Visual Studio~~
* 注释换成灰色，不要那么健康的颜色（指绿色）

## 使用方法

在CLion里导入Custom.icls，然后应用语法高亮主题即可。

## 预览

![1](res/1.png)

![2](res/3.png)

![3](res/4.png)

![4](res/2.png)
