> 如何找到优秀的源码，进行深度的框架解读，学习其他高手的代码，自己共享贡献。

- 常用词含义
watch:会持续收到该项目的动态。
fork:复制某个项目到自己的Github仓库中。
star:可以理解为点赞。
clone:将项目下载至本地。
follow：关注你感兴趣的作者，会收到他们的动态。

- in 关键字限制搜索范围

xxx关键字  in:name或description或readme
如：收索秒杀的。seckill in:name ，即表示在项目名称中含有seckill关键字。seckill in:description，项目描述包含seckill关键字。seckill in:readme，项目的readme文件中包含seckill关键字。
组合使用seckill in:name,description,readme。要求在项目名称，项目描述，项目的readme文件中要包含seckill关键字。

- stars或者fork数量关键词去查找

xxx关键字 stars  通配符（:> 或 :>=）
区间范围数字：xxx关键字 stars 数字1..数字2

如查找stars数大于等于5000的springboot项目 : 
springboot stars :>= 5000
如查找fork数大于500的springboot项目:
springboot forks :> 500

组合使用： 查找fork在100到200之间并且stars数在80到100之间的springboot项目，即springboot forks:100..200 stars:80..100。

- awesome加强搜索

awesome 关键字
一般是用来收集学习，工具，书籍类相关的项目。
awesome  redis
- 高亮显示某一行代码

给别人指出关键代码的行号
地址+#L行号
地址后面紧跟#L数字-L数字
如查看redis的源码ae.c的48行代码，该行会高亮
https://github.com/antirez/redis/blob/unstable/src/ae.c#L48
如查看redis的源码ae.c的48至100行代码，该范围会高亮
https://github.com/antirez/redis/blob/unstable/src/ae.c#L48-#L100

- 项目内搜索

在该作者项目主页上按t键
![image.png](https://upload-images.jianshu.io/upload_images/10679860-4be796d29545c824.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
[github快捷键](https://help.github.com/en/articles/using-keyboard-shortcuts)
- 搜索某个地区的大佬

location:地区
language:语言
如：北京地区Java方向的用户,即location:beijing language:java
