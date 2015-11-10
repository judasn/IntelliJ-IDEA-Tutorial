# 关于

## 学习前提

由于 IntelliJ IDEA 官网在亚洲没有设服务器，且官网用到一些类似 Twitter、Facebook 等站的脚本会使得你在国内出现访问巨慢或是不允许访问的特殊情况，所以建议你在访问官网、访问插件库、小版本本地迭代更新等操作的时候出现奇怪问题的时候，请自备VPN等网络加速工具。
 
很多用户都是先学习了 Eclipse、MyEclipse 再转到 IntelliJ IDEA 的，这里需要先说明的是，在学习 IntelliJ IDEA 过程中，你暂且要放下 Eclipse 下的开发思维方式，不能按 Eclipse 的软件思想或是结构去要求 IntelliJ IDEA，这样对你学习 IntelliJ IDEA 非常不利。

## 适用人群

用 IntelliJ IDEA 进行开发语言的学习者。

用 IntelliJ IDEA 进行开发语言的开发工作者。

其中对于语言开发学习者我是非常建议你使用 IntelliJ IDEA，因为一些代码格式、命名规范在 IntelliJ IDEA 下都是有良好的提示，对于我们所处的输入法下的中文全角符号也可以得到快速发现。特别是学习 Python 的学习者，当你在用 Pycharm 进行学习的时候，Pycharm 会时刻告诉你什么时候要注意空格、换行，提醒你有 PEP8 编码规范，你也可以通过快捷键快速格式化出适合 Python 要求的代码，这对于学习者来讲，真的很重要，它可以让你更专注于自己的代码。

## 教程演示的 IntelliJ IDEA 版本

IntelliJ IDEA 13 版本和 14 版本，在设置上差异很大，14 版本 IntelliJ IDEA 对整个 IDE 的设置进行了重新编排、归类，但是细节设置上所沿用的介绍是没有多大改变的。

目前（2015 年 06 月）IntelliJ IDEA 官网最新版本信息为：**Version:14.1.4 Build:141.1532.4 Released:June 19th, 2015**。

IntelliJ IDEA 有旗舰版和社区版本之分，本系列教程将以 `14.1.4` 的旗舰版进行演示和讲解。

其中旗舰版（Ultimate Edition）为收费版本，有 30 天试用期。如果你是学生、老师、开源项目参与者都可以向官网免费试用旗舰版，具体你可以查看下面链接。社区版（Community Edition）为免费版本，功能较旗舰版少了很多。

本教程使用的 IntelliJ IDEA 主题为较受欢迎的黑色：**Darcula**。

> * 申请免费版本：<https://www.jetbrains.com/idea/buy/>
> * 旗舰版和社区版差异细节：<https://www.jetbrains.com/idea/features/editions_comparison_matrix.html>

## 教程演示的系统环境

> * 系统：Windows 8.1 64 位 简体中文版
> * JDK 版本：1.8.0_05 64 位
> * 建议使用 JDK 版本为：1.6 及 1.6 以上，更加详细的系统要求会在安装教程篇中进行讲解。

## IntelliJ IDEA 版本迭代习惯

2015 年 IntelliJ IDEA 主版本是 14，目前（2015 年 06 月）最新版本是 14.1.4。与此同时，2015 年 06 月 17 日，官网开始提供 15 EAP 版本（Early Access Program 早期预览版）。如果你对 IntelliJ IDEA 下个大版本的新特性很感兴趣，你可以随时关注官网博客最新动态。

按正常情况来讲，IntelliJ IDEA 大版本是一年迭代一次。大版本下的小版本迭代时间没有固定，快的是一个月不到就迭代一次，慢的话基本在两到三个月迭代一次。相对其他 IDE 来讲迭代周期还是比较紧凑，但是作为用户你不用担心因为频繁迭代更新而引起的项目配置问题或是软件配置问题，后面有课程会专门对此进行说明。

> * IntelliJ IDEA 官网博客：<http://eap.jetbrains.com/idea>