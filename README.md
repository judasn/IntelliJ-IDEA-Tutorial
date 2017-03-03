# 重要说明，看三遍

## 介绍(Introduce)

- 本套教程适用于：IntelliJ IDEA 14、15、2016 版本
- 教程主要面向中文用户，如果你英文良好，建议直接阅读官网帮助文档
	- 官网帮助中心：<http://www.jetbrains.com/idea/webhelp/getting-help.html>
- 教程目前在不定时进行调整和补充，需要关注更新的请 `Watch`、`Star`、`Fork`。
- 特别需要友情提醒的是：请 `Fork` 之后，在我的基础上按你自己喜欢的方式整理一套属于你自己的快捷键列表，并导出为 PDF，以备不时查阅，对于提升开发效率是很有帮助的！文章的图片建议在需要的时候可以 `右键 - 查看图像（在新标签页打开图片）` 进行原图查看。或者建议你放大页面缩放比例（快捷键 `Ctrl + 鼠标滚轮`），可以更加清楚地看清图片细节。
- 同时邀请您一起参与完善该教程，帮助更多的人，欢迎反馈错误和意见！
- 本系列文章唯一授权的商业网站是：[极客学院](http://www.jikexueyuan.com/)，其他商业网站一律禁止转载。公益站点、个人博客、公众号等载体请在转载写明出处链接。
- 如果你只是单纯要阅读的话，建议移步极客学院上观看，访问速度快很多：
    - 地址：<http://wiki.jikexueyuan.com/project/intellij-idea-tutorial/>
- 如果你想参与完善该教程，请移步到 Github 上进行 Fork：
    - 地址：<https://github.com/judasn/IntelliJ-IDEA-Tutorial/>
- 如果你需要一份电子版，请查看（制作电子版很费精力，不会常更新此文件）：
    - 百度云：<http://pan.baidu.com/s/1i3wFYPB>
    - Google Drive：[https://drive.google.com/file/d/0B5...UU/view?usp=sharing](https://drive.google.com/file/d/0B5gjjw8peC5Sa19vVEswbTRYYUU/view?usp=sharing "Google Drive")
- 2016-10-25 更新，感谢 district10 童鞋做的一个在线阅读版本以及提供打包下载功能：
    - district10 主页：<https://github.com/district10>
    - 在线阅读：<http://whudoc.qiniudn.com/2016/IntelliJ-IDEA-Tutorial>
    - 下载打包：<http://whudoc.qiniudn.com/2016/publish-IntelliJ-IDEA-Tutorial-newMaster.zip> （90.4 MB）
    - 提供的转换脚本: [把文件夹下的 Markdown 文件，转化成 GitHub 风格的 HTML。。](https://github.com/district10/md2html)

## 目录(Contents)

- [1.IntelliJ IDEA 介绍（新用户必看）](introduce.md)
- [2.本教程介绍（新用户必看）](about-this-tutorial.md)
- [3.Windows 下安装](windows-install.md)
- [4.Ubuntu 下安装](ubuntu-install.md)
- [5.Mac 下安装](mac-install.md)
- [6.安装总结（新用户必看）](install-summarize.md)
- [7.首次运行（新用户必看）](first-run-wizard.md)
- [8.安装目录讲解、IDE 设置云同步（新用户必看）](installation-directory-introduce.md)
- [9.界面讲解（新用户必看）](interface-introduce.md)
- [10.主题、字体、编辑区主题、文件编码修改、乱码问题（新用户必看）](theme-settings.md)
- [11.各类文件类型图标讲解（新用户必看）](file-symbols-introduce.md)
- [12.索引的讲解（新用户必看）](IntelliJ-IDEA-cache.md)
- [13.编译方式讲解（新用户必看）](make-introduce.md)
- [14.项目相关概念讲解（新用户必看）](project-composition-introduce.md)
- [15.Hello World 的 Java 项目创建和项目配置文件讲解](project-settings.md)
- [16.版本控制讲解](vcs-introduce.md)
- [17.实时代码模板讲解](live-templates-introduce.md)
- [18.文件代码模板讲解](file-templates-introduce.md)
- [19.Emmet 讲解](emmet-introduce.md)
- [20.Postfix Completion 讲解](postfix-completion-introduce.md)
- [21.插件讲解](plugins-settings.md)
- [22.Eclipse 的 Java Web 项目环境搭建](eclipse-java-web-project-introduce.md)
- [23.Maven 项目介绍](maven-project-introduce.md)
- [24.Maven 的单模块 / 多模块之 Spring MVC + Spring + Mybatis 项目讲解（重点）](maven-java-web-project-introduce.md)
- [25.Maven 的单模块之 Spring MVC + Spring + Spring Data JPA 项目（基于 IntelliJ IDEA）](maven-java-web-project-introduce2.md)
- [26.Debug 讲解](debug-introduce.md)
- [27.重构讲解](refactor-introduce.md)
- [28.数据库管理工具](database-introduce.md)
- [29.IntelliJ IDEA 常用设置-1](settings-introduce-1.md)
- [30.IntelliJ IDEA 常用设置-2](settings-introduce-2.md)
- [31.IntelliJ IDEA 常用设置-3](settings-introduce-3.md)
- [32.IntelliJ IDEA 常用设置-4](settings-introduce-4.md)
- [33.IntelliJ IDEA 常用快捷键讲解（Win+Linux）（新用户必看）](keymap-introduce.md)
- [34.IntelliJ IDEA 常用快捷键讲解（Mac）（新用户必看）](keymap-mac-introduce.md)
- [35.从 Windows 过度到 Mac 必备快捷键对照表（新用户必看）](keymap-win-mac.md)
- [36.IntelliJ IDEA 的 Java 热部署插件 JRebel 安装及使用](jrebel-setup.md)
- [37.IntelliJ IDEA 远程调试（Tomcat+Jetty）](remote-debugging.md)
- [38.最特殊的快捷键 Alt + Enter 介绍（新用户必看）](hotkey-alt-enter-introduce.md)
- [39.IntelliJ IDEA 插件开发视频教程](plugins-develop.md)
- [40.本教程总结](this-tutorial-the-end.md)


## 联系(Contact)

- Email：`judas.n@qq.com`（常用） or `admin@youmeek.com`（备用）
- Blog：<http://code.YouMeek.com>
- IntelliJ IDEA QQ 交流群：入群请看：<https://github.com/judasn/IntelliJ-IDEA-Java-Conversation>
- 欢迎捐赠 ^_^：<http://www.youmeek.com/donate>


## Gtihub 协同视频教程(Participate)

- 如果您不会使用 Git 或是 Github 也没关系，请认真学习下面视频教程：
- Judas.n 录制
    - 视频格式：MP4
    - 分辨率：1920 X 1080
    - 片长：16 Min
    - 文件大小：62 M
- 下载
    - 百度云盘：<http://pan.baidu.com/s/1bogmTLd>
    - 360 网盘（2fb5）：<https://yunpan.cn/cYez7W9xnHs3c>


## Github 常用按钮说明

- Watch：关注该项目，作者有更新的时候，会在你的 Github 主页有通知消息。
- Star：收藏该项目，在你的头像上有一个 “Your stars” 链接，可以看到你的收藏列表，以方便下次进来。
- Fork：复制一份项目到自己的 Github 空间上，你可以自己开发自己的这个地址项目，然后 Pull Request 给项目原主人。 


## 参与作者汇总(Author)

- 真心感谢这些志同道合的人，这个真的很重要，也希望你能一起参与（鞠躬）！
- 同时感谢那些通过私聊方式指出一些错误地方的朋友，使得该教程能得以更加完善，真心感谢（鞠躬）！


|作者(按参与时间排序)|地址|
|:---------|:---------|
|Judas.n|<http://code.YouMeek.com>|
|温泉|<https://github.com/wenquan0hf>|
|zhenhappy|<https://github.com/zhenhappy>|
|two8g|<https://github.com/two8g>|
|Dectinc|<https://github.com/Dectinc>|
|Caliven|<https://github.com/caliven>|
|MinjieTao|<https://github.com/MinjieTao>|
|classloader|<https://github.com/classloader>|
|challengeof|<https://github.com/challengeof>|
|district10|<https://github.com/district10>|
|duanluan|<https://github.com/duanluan>|
|binarywang|<https://github.com/binarywang>|
|chenhui7373|<https://github.com/chenhui7373>|

## AD

- [我个人开发的个性化定制网址导航：GitNavi.com](http://www.gitnavi.com)
