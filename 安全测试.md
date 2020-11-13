博客园Logo
首页
新闻
博问
专区
闪存
云上钜惠
代码改变世界
搜索
我的博客
短消息
用户头像
返回主页
mithrandirw's Coding Road.
博客园首页新随笔管理订阅订阅随笔- 36  文章- 0  评论- 3 
IDEA 实用功能Auto Import：自动优化导包（自动删除、导入包）
JetBrains公司的intellij Idea堪称JAVA编程界的苹果，用户体验非常好

下面介绍一下IDEA的一个能显著提升写代码效率的非常好用的功能设置—— Auto Import

 

Auto Import的功能是可以帮助我们自动删除无用的包Import(未被引用)，以及自动Import填充尚未导入的包。完全智能化地帮助我们在开发程序时，省略了导包的操作，大大优化了开发的效率。

并且，当你移动某个类改变其路径的时候，这个功能会相应的改变关联的文件中包的路径。

堪称神器。

 

下面是Auto Import设置步骤详解。

Settings→Editor→General→Auto Import 
然后勾选Add unambiguous imports on the fly以及Optimize imports on the fly



Add unambiguous imports on the fly：快速添加明确的导入。

Optimize imports on the fly：快速优化导入，优化的意思即自动帮助删除无用的导入。

 

 
标签: IDE
好文要顶 关注我 收藏该文  
mithrandirw
关注 - 0
粉丝 - 1
+加关注
140
« 上一篇： Spring注解 @Transactional(rollbackFor = Exception.class)
» 下一篇： 负载均衡软件LVS 三种实现模式对比
posted @ 2018-04-13 11:33  mithrandirw  阅读(111948)  评论(2)  编辑  收藏

评论
   回复 引用#1楼 2018-08-09 07:58 | 黑夜,我累了
这个eclipse也有
支持(0) 反对(0)
   回复 引用#2楼 2019-04-10 09:34 | Eiji_g
@ 黑夜,我累了
idea这个可以检查xml头文件配置是否在使用，并自动删除无用的dtd头文件。
支持(0) 反对(0)
刷新评论刷新页面返回顶部
发表评论 【福利】注册AWS账号，立享12个月免费套餐
编辑
预览
支持 Markdown
 退出 订阅评论 我的博客

[Ctrl+Enter快捷键提交]

首页 新闻 博问 专区 闪存 班级
【推荐】News: 大型组态、工控、仿真、CADGIS 50万行VC++源码免费下载
【推荐】博客园 & 陌上花开HIMMR 给单身的程序员小哥哥助力脱单啦～
【推荐】博客园 & 示说网联合策划，AI实战系列公开课第二期
【推荐】了不起的开发者，挡不住的华为，园子里的品牌专区
【推荐】未知数的距离，毫秒间的传递，声网与你实时互动
【福利】AWS携手博客园为开发者送免费套餐与抵扣券
【推荐】 阿里云折扣价格返场，错过再等一年

声网专区
最新 IT 新闻:
· 没有李佳琦薇娅，天猫双十一的4982亿GMV要打几折
· 特斯拉连续第九次发布车辆安全报告：开我们的车受伤概率最低
· 资金链断裂！前途汽车被曝全国首家门店已撤出 交付中心也人去楼空
· 苹果带来iOS 14.3：全新图像格式、单张体积超大
· vivo首发！一文了解旗舰级处理器Exynos 1080：首款5nm A78芯
» 更多新闻...
昵称： mithrandirw
园龄： 2年8个月
粉丝： 1
关注： 0
+加关注
<	2020年11月	>
日	一	二	三	四	五	六
1	2	3	4	5	6	7
8	9	10	11	12	13	14
15	16	17	18	19	20	21
22	23	24	25	26	27	28
29	30	1	2	3	4	5
6	7	8	9	10	11	12
搜索
 
 
常用链接
我的随笔
我的评论
我的参与
最新评论
我的标签
最新随笔
1.IDEA git无法拉取ssh远程地址解决
2..gitignore文件无效解决
3.Docker安装教程（翻译Get Docker CE for CentOS官网文档）
4.虚拟机、容器与Docker
5.线程互斥与同步
6.JAVA 线程调度与优先级
7.进程与线程
8.Mysql 外键级联约束(Default、Restrict、NO ACTION、 Cascade、SET NULL)
9.负载均衡调度算法（LVS）
10.负载均衡软件LVS 三种实现模式对比
我的标签
IDE(3)
版本控制(3)
前端(3)
数据库(3)
Mysql语法(2)
负载均衡(2)
编程语言(2)
JAVA GUI编程学习(2)
JAVA 多线程(2)
随笔(2)
更多
随笔档案 (36)
2020年3月(1)
2019年9月(1)
2018年5月(2)
2018年4月(14)
2018年3月(5)
2018年2月(13)
最新评论
1. Re:gitee码云项目协作：fork项目以及更新
Soga，了解，今天第一次Fork人家项目，之前都是直接玩的

--大雄小顾
2. Re:IDEA 实用功能Auto Import：自动优化导包（自动删除、导入包）
@ 黑夜,我累了idea这个可以检查xml头文件配置是否在使用，并自动删除无用的dtd头文件。...
--Eiji_g
3. Re:IDEA 实用功能Auto Import：自动优化导包（自动删除、导入包）
这个eclipse也有
--黑夜,我累了
阅读排行榜
1. IDEA 实用功能Auto Import：自动优化导包（自动删除、导入包）(111946)
2. IDEA 统计插件Statistic：查看你的代码数据(17076)
3. IDEA 启动tomcat 端口占用原因以及解决方法（ 使用debug模式）(16836)
4. H5上传前预览视频（结合 video标签 &&h5 fileApi）(11355)
5. gitee码云项目协作：fork项目以及更新(10927)
评论排行榜
1. IDEA 实用功能Auto Import：自动优化导包（自动删除、导入包）(2)
2. gitee码云项目协作：fork项目以及更新(1)
推荐排行榜
1. IDEA 实用功能Auto Import：自动优化导包（自动删除、导入包）(14)
2. IDEA 统计插件Statistic：查看你的代码数据(2)
3. gitee码云项目协作：fork项目以及更新(2)
4. 线程互斥与同步(1)
5. JAVA 右移运算符>>和>>>(1)
Copyright © 2020 mithrandirw
Powered by .NET 5.0.0 on Kubernetes