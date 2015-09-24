# IntelliJ IDEA 的Java热部署插件JRebel安装及使用

## JRebel 介绍
在Java Web开发中, 一般更新了Java文件后要手动重启Tomcat服务器, 才能生效, 浪费不少生命啊, 自从有了JRebel这神器的出现, 不论是更新class类还是更新Spring配置文件都能做到立马生效,大大提高开发效率.

## JRebel 安装
JRebel的安装方法有两种, 一种是直接在Tomcat启动参数上面加上JRebel的参数, 另外一种是以插件的形式装到IDEA上, 比较推荐后者.

首先先介绍第一种安装方法, 先在硬盘某个位置把JRebel解压出来

然后配置IDEA的Tomcat

![enter description here][1]

点+号选择Tomcat Server->Local

![enter description here][2]

默认显示如图

![enter description here][3]

几个关键的地方需要注意的, 就是首先要选择Deployment这个选项卡

![enter description here][4]

选择自己的项目, 建议选择带exploded, 这个相当于改Tomcat的CATALINA_HOME, 效率比较高
![enter description here][5]

选择好后, 删掉默认的Make, 提高效率

![enter description here][6]

接下来返回Server选项卡, 会发现多了一项 On frame deactivation, 如果你刚才没有配置Deployment选项卡的话的这项是不会出现的


按如图所示的来配置, 特别需要注意的是On 'Update' action和On frame deactivation这两项目一定要选择Update classes and resources, 否则类修改热部署不生效, 或者第三方模版框架例如Freemarker热部署不生效

![enter description here][7]

接下来就是很关键的需要引入JRebel的地方了, 在VM options的最右边有个箭头, 点进去

![enter description here][8]

Windows输入:

    -noverify
    -agentpath:D:/dev_env/jrebel/jrebel_running/lib/jrebel64.dll

![enter description here][9]

Linux用这个：

    -agentpath:/dev_env/jrebel/jrebel_running/lib/libjrebel64.so

![enter description here][10]

Mac OS用这个：

    -agentpath:/dev_env/jrebel/jrebel_running/lib/libjrebel64.dylib

![enter description here][11]

配置完成, 直接启动Tomcat即可, 不过此方法麻烦, 每次新建项目都要从新配置


接下来介绍使用IDEA插件的方式启动JRebel


首先是安装JRebel的插件, 安装方法和其他插件安装方法一样, 不过这里不采用在线安装, 直接选择本地安装, 直接选择插件安装即可

![enter description here][12]

安装好后在设置里面会多出一项JRebel的配置


查看一下插件是否有效

![enter description here][13]

绿色的VALID表示破解成功


在原来运行项目的按钮边上会多出两个绿色的按钮, 如图, 前面那个是Run, 后面那个是Debug

![enter description here][14]

配置Tomcat的方法和直接上面说的直接调用配置方法一样, 同样需要注意的是On 'Update' action和On frame deactivation这两项目一定要选择Update classes and resources, 唯一不同的是VM options这项不需要填, 放空就好
接下来直接启动项目, 一般选择后面那个Debug按钮

![enter description here][15]

看到Log有JRebel输出的版本信息, 没有报错就是表示成功执行了, 随便改一个类试试吧

最后这边附上最新的JRebel


直接调用下这个[直接调用下这个][16]


IDEA插件用这个[IDEA插件用这个][17]


  [1]: ./images/1443104046716.jpg "1443104046716.jpg"
  [2]: ./images/1443104141276.jpg "1443104141276.jpg"
  [3]: ./images/1443104220547.jpg "1443104220547.jpg"
  [4]: ./images/1443104300210.jpg "1443104300210.jpg"
  [5]: ./images/1443104322321.jpg "1443104322321.jpg"
  [6]: ./images/1443104460839.jpg "1443104460839.jpg"
  [7]: ./images/1443104689559.jpg "1443104689559.jpg"
  [8]: ./images/1443105116696.jpg "1443105116696.jpg"
  [9]: ./images/1443105245779.jpg "1443105245779.jpg"
  [10]: ./images/1443105310229.jpg "1443105310229.jpg"
  [11]: ./images/1443105389359.jpg "1443105389359.jpg"
  [12]: ./images/1443105630806.jpg "1443105630806.jpg"
  [13]: ./images/1443106276407.jpg "1443106276407.jpg"
  [14]: ./images/1443105723628.jpg "1443105723628.jpg"
  [15]: ./images/1443106100250.jpg "1443106100250.jpg"
  [16]: ./attachments/jrebel_6.2.3-agent-crack.zip
  [17]: ./attachments/jr-ide-idea-6.2.3-idea-13-14.zip
