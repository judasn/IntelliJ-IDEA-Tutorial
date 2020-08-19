# IntelliJ IDEA 插件开发视频教程

## 重要说明

- IntelliJ IDEA 的插件理论上是同时也适用于 JetBrains 公司下的其他大多数 IDE 的，因为这些 IDE 都是基于 IntelliJ IDEA 的基础平台进行开发的，请牢记这一点。

## 环境准备

- 当前时间：2020-06
- 官网说明：<https://www.jetbrains.org/intellij/sdk/docs/basics/getting_started.html>
- IntelliJ IDEA 2020.1.2 旗舰版
- 插件 Plugin DevKit 必装
- 插件 Gradle 必装，以及 Gradle 开发环境
- 设置 Plugin SDK：<https://www.jetbrains.org/intellij/sdk/docs/basics/getting_started/setting_up_environment.html>

## 文档

- 官网文档：<https://www.jetbrains.org/intellij/sdk/docs/intro/welcome.html>
- 官网示例：<https://github.com/JetBrains/intellij-sdk-code-samples>
- 其他文档：
    - <https://blog.csdn.net/dc_726/article/details/14139155>
    - <https://blog.xiaohansong.com/idea-plugin-development.html>


## 运行调试方法

- 选择右侧 Gradle > Tasks > intellij > runIde > 右键 Debug xxxxxx，会启动一个新的 IntelliJ IDEA 自动帮我们安装正在开发的插件进行调试
- 并且当前环境是 debug 状态，可以用来调试代码


## 打包

- 选择右侧 Gradle > Tasks > build > jar，项目根目录会有一个 build 目录生成，里面有一个 libs 子目录可以看到一个 jar 文件。
- 在 IntelliJ IDEA 项目里面可能会看不到，被隐藏了，需要打开电脑文件管理器查看这个目录


-------------------------------------------------------------------

## 教程视频下载和介绍

- 视频章节结构：
	- `01_AS插件是什么_和IntellijIDEA关系`
	- `02_常见的AS开发插件`
	- `03_创建第一个Plugin插件`
	- `04_翻译插件需求`
	- `05_翻译开发过程整理`
	- `06_获取用户选中的文本`
	- `07_翻译插件显示气泡`
	- `08_把插件上传到公共仓库`
- 视频教程下载地址
	- 下载地址：<https://pan.baidu.com/s/1i7grrpV>，密码：gnpl，如果哪天下载地址失效，请在本 Github 项目发 Issues。
- 这套教程视频不是本人录制的，所以需要特别强调下，本套视频来自：[传智播客公开课：Android Studio插件开发](http://open.itcast.cn/java/14-539.html)，在此特别感谢别人的付出（鞠躬）。

## 其他图文资料介绍

- <http://blog.csdn.net/dc_726/article/details/14139155>
- <http://www.mobile-open.com/2016/973070.html>

## 插件开发说明

- 如果你 Java 基础还算过关，看完这套教程简单的插件基本不会有任何问题的。
- IntelliJ IDEA 本身平台就自带了很多依赖包，如果能尽量用 IntelliJ IDEA 平台的依赖包就尽量别自己添加 jar，减少插件的容量。

## IntelliJ IDEA 官网插件开发相关资料

- [插件提交地址](https://plugins.jetbrains.com/?idea)
- [官网插件开发指导文档](http://www.jetbrains.org/intellij/sdk/docs/)
- [IntelliJ IDEA Community 源码](https://github.com/JetBrains/intellij-community)

## 一些开源的 IntelliJ IDEA 插件介绍

- 阅读别人插件有助于你的开发，希望你有一天能开发一个好用的插件。
- IntelliJ IDEA 的大量插件都是开源的，如果你有遇到你喜欢的插件，可以到 JetBrains 官网上找到这个插件的主页，很有可能在介绍中就有 Github 地址。感谢 Github 的存在。
- [我写的插件：ChineseTypography，也是一个最简单的插件](https://github.com/judasn/ChineseTypography-IDEA-Plugin)
- <https://github.com/Skykai521/ECTranslation>
- <https://github.com/YiiGuxing/TranslationPlugin>
- <https://github.com/avast/android-butterknife-zelezny>
- <https://github.com/zzz40500/GsonFormat>
- <https://github.com/kstenschke/shifter-plugin>
- <https://github.com/jansorg/SmarterEditor>
- <https://github.com/jansorg/BashSupport>
- <https://github.com/hsz/idea-gitignore>
- <https://github.com/JetBrains/ideavim>
- <https://github.com/krasa/EclipseCodeFormatter>
- <https://github.com/krasa/StringManipulation>
- <https://github.com/krasa/GrepConsole>
- <https://github.com/HexarA/Json2Pojo>


