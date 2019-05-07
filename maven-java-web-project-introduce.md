# Maven 的单模块 / 多模块之 Spring MVC + Spring + Mybatis 项目讲解


## 初衷

- 为了更加明了地展示 IntelliJ IDEA 的设置，本章教程为视频教程
- 本章展示 IntelliJ IDEA 高度集成化的效果，降低 IntelliJ IDEA 入门时间


## 视频下载

- **单模块的 Spring MVC + Spring + Mybatis 讲解（基于 IntelliJ IDEA）**
    - 百度云盘：<http://pan.baidu.com/s/1dEuxWh7>
    - 360 云盘（6d49）：<https://yunpan.cn/cY444GphNgMe3>
- **多模块的 Spring MVC + Spring + Mybatis 讲解（基于 IntelliJ IDEA）**
    - 百度云盘：<http://pan.baidu.com/s/1hr0x6sc>
    - 360 云盘（e319）：<https://yunpan.cn/cY4INmfJn8yvm>


## 开发环境

- JDK 7（理论上支持 JDK 6、JDK 7、JDK 8）
- Mysql 5.6
- Maven 3.1.1
- Tomcat 7
- Git 2.7.0.2-64-bit
- IntelliJ IDEA 15.0.4
- 所有编码：UTF-8


## 视频中项目源码


- 环境相关：
    - [Maven 配置文件](maven-skill-introduce.md)
    - 我的 Maven 本地依赖包环境下载：<http://pan.baidu.com/s/1bnPZU2b>
    - 建议你也跟我一样直接解压在 D 盘根目录，这样其他就不需要设置了
    - Git 环境的说明（默认安装）：<http://www.youmeek.com/hexo-install/>
    - IntelliJ IDEA 基础教程系列：<https://github.com/judasn/IntelliJ-IDEA-Tutorial>

---

- IntelliJ IDEA 设置：
	- Fork 单模块项目：<https://github.com/judasn/Basic-Single-Module-SSM>
	- Fork 多模块项目：<https://github.com/judasn/Basic-Multi-Module-SSM>
    - Checkout 项目并导入
    - IntelliJ IDEA Maven 设置
    - IntelliJ IDEA 文件编码设置
    - IntelliJ IDEA Mybatis 插件安装（该插件收费）：<https://plugins.jetbrains.com/plugin/7293?pr=>

---

- 项目设置：
    - 项目 JDK 设置
    - 项目 Facet 加入 Spring 配置

---

- 代码相关：
    - 简单讲解 pom.xml 文件
    - 用 IntelliJ IDEA 的 Database 初始化数据库
    - 单元测试
    - 启动 Tomcat 加上 Make Project 事件
    - 访问 Controller 演示 Debug
    - 讲解 Controller 中代码左侧的各个按钮效果
    - JSP 页面直接点击请求地址直接跳转到 Controller
    - 静态资源映射特别提醒下，比如你做图片上传等等，如果你没有映射好可能都会遇到 404
    - 查看 Druid 提供监控
    - 演示用 Mybatis 插件自动生成代码
