本指南将帮助新人了解ctfweb的内容，方便入坑~
# 使用之前想说的话
web这个方向是学的人最多，相对而言最卷的一个方向，不过目前来说需求量似乎也蛮大的。
学习的话，主要以刷题和观看师傅们的文章为主，多参加比赛，能学到很多东西。
## 刷题网站
[BUUCTF](https://buuoj.cn/)
buuctf，梦开始的地方，里面收集了很多老题，很适合新人刷。

[ctfhub](https://www.ctfhub.com/#/)
扩展技能树，在学习每个基本漏洞的过程中配套使用，学会新姿势~

[ctfshow](https://ctf.show/)
非常适合打基础的刷题网站，萌新友好型，真正意义上从零开始。

[NSSCTF](https://www.ctfer.vip/index)
收录了较多近两年的题目，打好基础后在这刷题。
## 学习网站

[CSDN社区](https://www.csdn.net/)
前期重要的学习资源，很多基础的内容都可以在这上面找到文章。

[先知社区](https://xz.aliyun.com/)
关于一些技术、漏洞的利用的文章的网站。

[安全客](https://www.anquanke.com/)
很多安全的技术文章
[github](https://github.com/)
很多大佬都会发表东西在这上面，并且里面有各种强力的脚本，需要的时候下载。

除了上面提到的一些网站，同样重要的就是去看圈内大佬的博客，他们的博客技术文章质量很高，网站上面不好搜索到。
善于利用搜索引擎，浏览器推荐google、firebox、edge这种，搞好信息搜集。
# 如何优雅地提问
想要学好web，甚至是网络安全，信息搜集是很重要的一环，首先就是要加入调查兵团。
大部分时候要学会借助某只魔法🐱的帮助上网。

然后有能力一定要找到大G老师，有问题向他提问，尤其是学习的初期，很多问题问他很快就能解答，但是上网搜个半天，基础的问题大G老师他都能回答得很好，甚至一些简单的脚本，他也会帮你写。(或者找语核当代餐)
# 基础内容的学习
前期学一些语言知识菜鸟教程
[菜鸟教程](https://www.runoob.com/)
## 网页前端的内容
学习一下html和javascript的一些内容，不用学太多。
html文档：[https://developer.mozilla.org/zh-CN/docs/Learn/HTML](https://developer.mozilla.org/zh-CN/docs/Learn/HTML)
javascript：[https://zh.javascript.info/](https://zh.javascript.info/)
简单看一下就行，javascript由于涉及到语言学习，并不建议现在学太深，可以之后php、python之类的学精了再去学深度学习javascript。
然后，随便打开一个网页，按下 F12 或者 Ctrl+U，对照着打开的文档，尝试去理解那些被尖括号包围着的文字和我们所看到的花花绿绿的网页之间的联系吧，看网页源码也是信息搜集的一部分。
## 网络协议基础
了解一下访问网页的数据包各部分内容的含义。
同样菜鸟教程有相关内容：[https://www.runoob.com/http/http-tutorial.html](https://www.runoob.com/http/http-tutorial.html)
也可以看文档：[https://developer.mozilla.org/zh-CN/docs/Web/HTTP](https://developer.mozilla.org/zh-CN/docs/Web/HTTP)

# 语言
网站的服务端通常是由某种语言写的，入坑初期，主要学习php，如果零基础的话，php就是你人生学的第一门语言，这个语言相对其它语言而言简单好上手的。
菜鸟教程：[PHP 教程](https://www.runoob.com/php/php-tutorial.html)
手册：[PHP手册](https://www.php.net/manual/zh/)
语言一般下载的东西有两个，一个是编辑器(或开发继承环境)，另一个是解释器，通常也说语言环境。
学习php本地环境：
[PHPStudy 2018 安装包](https://public.xp.cn/upgrades/PhpStudy2018.zip)
编辑器的选择：
vscode或phpstorm。
个人偏好于phpstorm，后期debug作用很大。

## linux命令行
大多数网站的主机都是linux系统，要对其进行一些操作，就得熟悉一些Linux命令。
[Linux 常用命令学习](https://www.runoob.com/w3cnote/linux-common-command-2.html)
这些命令学一学就行。
至于linux操作系统的安装，个人建议VMware虚拟机装kali，这个虚拟机后期还有用。
## SQL语言基础
SQL 是用户与数据库进行交互的语言。严格意义上可能不算“编程语言”，但同样十分重要。前期主要接触到的数据库是 MySQL，需要了解数据库的库、表、列、视图的概念，并掌握基本的增、删、查、改四个动作的语法。
[菜鸟教程——SQL](https://www.runoob.com/sql/sql-tutorial.html)
[MySQL 5.7 参考手册](https://dev.mysql.com/doc/refman/5.7/en/)
这玩意语言简单，但是我个人认为可以放到php后期来看，因为数据库与php的联动操作设计到php比较深的内容，以及有时候需要python的辅助。
## 基础漏洞
web的一些被打烂了的漏洞已经罗列出来了十大漏洞，
[什么是 OWASP？什么是 OWASP 十大？](https://www.cloudflare-cn.com/learning/security/threats/owasp-top-10/)
个人推荐web漏洞学习顺序：
1.命令执行
在php中执行linux命令，推荐刷ctfshow命令执行。
2.文件包含
[文件包含漏洞原理利用方式及修复](https://segmentfault.com/a/1190000021835492)
同样刷专题。
3.文件上传
[文件上传漏洞靶场:upload-labs安装+第一关教程（一）](https://blog.csdn.net/qq_36711453/article/details/84788215)
可以ctfshow刷文件上传，了解各种姿势。
4.XSS
全称跨站脚本，XSS 漏洞的发生大都是由于没控制好用户输入，让用户输入的恶意数据被解析为浏览器中合法的 JavaScript 代码并执行，因此在学习 XSS 漏洞之前请先了解 JavaScript 编程语言。注意最后代码执行的地方是在客户端的浏览器中，而不是服务器。
[https://xss.haozi.me/#/0x00](https://xss.haozi.me/#/0x00)
5.sql注入
推荐配合 PHPStudy 在本地搭建 sqli-labs 靶场，就可以在里面学习各种 SQL 注入相关的测试了。
靶场：[https://www.jianshu.com/p/9acc9dd79cc9](https://www.jianshu.com/p/9acc9dd79cc9)
笔记：[sqlilabs笔记](https://www.yuque.com/r/goto?url=https%3A%2F%2Fcloud.tencent.com%2Fdeveloper%2Farticle%2F1982432)
ctfshow也有靶场，不过感觉太多，看着刷。

6.ssrf
全称服务端请求伪造，攻击的目标是服务端，控制服务端以服务端的身份发起请求，读文件，攻击内网应用等
[ssrf学习](https://uknowsec.cn/posts/notes/SSRF%E6%BC%8F%E6%B4%9E%E7%9A%84%E5%88%A9%E7%94%A8%E4%B8%8E%E5%AD%A6%E4%B9%A0.html)
ctfshow简单刷一下，不过感觉不全。
7.xxe
一种完全不一样的漏洞，语法源自xml，可以找个时间单独学。
[一篇文章带你理解漏洞之 XXE 漏洞](https://www.k0rz3n.com/2018/11/19/%E4%B8%80%E7%AF%87%E6%96%87%E7%AB%A0%E5%B8%A6%E4%BD%A0%E6%B7%B1%E5%85%A5%E7%90%86%E8%A7%A3%20XXE%20%E6%BC%8F%E6%B4%9E/)
8.php反序列化
php最难的部分，也是需要你有很强的php语言功底的一个漏洞。
学习反序列化之前，请确保你已经学过php类的相关知识。
[php反序列化](https://blog.csdn.net/solitudi/article/details/113588692)
从 PHP 的基础反序列化开始学起，之后学构造 POP 链、Session 反序列化、Phar 反序列化，再到后面学不同语言的反序列化，如 Python 反序列化和 Java 反序列化。不过这些也是后话了，简单的php反序列化先整明白先。

9.ssti
这个需要有一定的python基础了，能在第一个学期学到这的话，你就是下一届的web✌，下一届的光。
[一篇文章带你理解漏洞之 SSTI 漏洞](https://www.k0rz3n.com/2018/11/12/%E4%B8%80%E7%AF%87%E6%96%87%E7%AB%A0%E5%B8%A6%E4%BD%A0%E7%90%86%E8%A7%A3%E6%BC%8F%E6%B4%9E%E4%B9%8BSSTI%E6%BC%8F%E6%B4%9E/)

# 工具
打网络安全，基本的工具还是需要的。
[BurpSuitePro](https://portswigger.net/burp/pro) ：神中神，打web不能没有burpsuite，就像pwn区不能没有korey0sh1，后续可能会出个该工具的配置，这玩意能一直用。
[HackBar](https://chrome.google.com/webstore/detail/hackbar/ginpbkfigcoaokgflihfhhmglmbchinc?utm_source=ext_sidebar&hl=zh-CN) - 浏览器插件，方便修改与重放 HTTP 数据包
[AdBlocker Ultimate](https://chrome.google.com/webstore/detail/adblocker-ultimate/ohahllgiabjaoigichmmfljhkcfikeof?utm_source=ext_sidebar&hl=zh-CN) - 浏览器插件，和蔼！任何广告，终将绳之以法！
[沉浸式翻译](https://chrome.google.com/webstore/detail/immersive-translate/bpoadfkcbjbfhfodiogcnhhhpibjhbnh?utm_source=ext_sidebar&hl=zh-CN) - 浏览器插件，一键中英文对照翻译，看英文文章有用
[010 editor](https://www.sweetscape.com/010editor/) ：misc用的多，不过对于我们了解文件结构啥的帮助很大。
[蚁剑(菜刀)](https://github.com/AntSwordProject/antSword)： 管理shell用的。

剩下的大多数工具都是github上的python写的项目，等你学到的时候自己去github上下就成了！




# 总结
总之每天都要学点东西，无论是几年前被打烂了的姿势，还是最近爆出来的漏洞，多复现，多学。平时可能会加各种ctf群，少水群，多学习。愿你们都能找到自己真正喜欢的事物去学习，你所热爱的就是你的生活！
![微信截图_20230801232440.png](https://cdn.nlark.com/yuque/0/2023/png/34502958/1690903492538-72d91e67-00f5-4a42-85bf-c7ed9dab68f5.png#averageHue=%23ada67a&clientId=u968c1e2e-857b-4&from=paste&height=92&id=u7b8728dc&originHeight=115&originWidth=153&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=47945&status=done&style=none&taskId=u30762290-6a43-4f6b-9cc8-88fb4512d9b&title=&width=122.4)
附上我的编辑器六君子：
![微信截图_20230801230831.png](https://cdn.nlark.com/yuque/0/2023/png/34502958/1690902531253-2661a371-ddb5-4db8-9e38-c84167916f0d.png#averageHue=%23e0dfd3&clientId=u968c1e2e-857b-4&from=paste&height=208&id=uc7e40cfe&originHeight=260&originWidth=351&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=88935&status=done&style=none&taskId=ue68e96de-9d20-4b33-990f-28128d7c1fd&title=&width=280.8)


# contact with us
本人活跃时用的id是Enterpr1se，企业号航空母舰的意思，微信号:Enterpr1se0721 qq:1296285271

## 推荐校内web手
1.shanhe 微信号:CXH2542972797    21届的web神
2.kangqi 微信号:kq1395480051 21届的web佬
3.we1lkin  微信号:welkin703  22届的web佬
4.zymic  微信号:zyc2003128 22届的web佬。
