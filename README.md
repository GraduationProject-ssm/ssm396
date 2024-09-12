# [首页查询更多项目](https://github.com/GraduationProject-ssm) 包安装运行


# ssm396社区团购系统的设计与实现+vue

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)]()


# 绪论
## 1.1 研究背景
现在大家正处于互联网加的时代，这个时代它就是一个信息内容无比丰富，信息处理与管理变得越加高效的网络化的时代，这个时代让大家的生活不仅变得更加地便利化，也让时间变得更加地宝贵化，因为每天的每分钟，每秒钟这些时间都能让人们处理大批量的日常事务，这些场景，是之前的手工模式无法与之相抗衡的。对于社区团购信息的管理来说，传统的通过纸质文档记录信息的方式已经落后了，依靠手工管理这些信息，不仅花费较长的工作时间，在对记录各种信息的文档进行信息统计以及信息核对操作时，也不能及时保证信息的准确性，基于这样的办公低效率环境下，对于社区团购信息的处理就要提出新的解决方案。因为这个时代的信息一直都在高速发展，要是不抱着发展的观念看待事情，极有可能被这个市场快速遗忘，甚至被无情地淘汰掉。所以尽早开发一款社区团购系统进行信息的快速处理，既跟上了时代的发展脚步，也能让自己的核心竞争力有所提升。
## 1.2目的和意义
互联网加的时代一方面是加快信息的发展，另一方面也是对传统行业进行筛选，能够继续发展的，肯定是那些能够充分运用互联网技术进行自身升级改革的行业。那些停步不前的行业只能就此结束，进而被大家所遗忘。这次设计出来的社区团购系统，它不仅能够让管理人员在信息增加，信息的编辑等事务处理上，节省很多的时间，也会砍掉一部分的人工成本，节省不必要开支的资金。另外，此系统的操作界面是可视化的界面，管理人员无需付费培训就能尽快上手。社区团购系统的开发意义如下：

1、管理人员再也不用在查询信息上花费大量宝贵的时间了，通过信息关键词字段就可以在几秒内获取需要的信息，在各种突发事件面前管理人员也不用慌张，可以从容淡定地处理各种相关信息。

2、该系统在每天的24小时期间都是不会停止服务的，只要有信息操作的需要，管理人员都能使用常用的360浏览器，或者百度浏览器，2345浏览器等大众浏览器都能登录系统，然后操作对应的功能。

3、有了这款信息管理类操作软件，所有需要进行处理的数据不用在纸质版本的文档上进行记载，而是基于电脑进行信息录入。

4、社区团购信息都是通过网站进行显示，其实质是这些信息都保存在网站对应的数据库里面。只要操作员不去恶意删除信息，那么这些信息将会永久保存。
## 1.3 论文结构安排
编写社区团购系统相对应的论文，其实就是对开发完成的程序进行再次解读的过程。本论文从七个方面的内容讲解了开发的程序，具体内容如下：

第一个部分：就是论文的绪论，这个部分就是介绍在什么样的背景下开发的程序，以及这个程序开发出来具有什么意义等内容。

第二个部分：就是介绍开发这个程序使用了什么技术，使用什么数据库保存程序的数据信息，程序开发的语言是使用的什么语言等内容。

第三个部分：就是介绍这个程序开发在现实生活的可行性问题，也讲述了程序开发需要设置什么功能等内容。

第四个部分：就是已经知晓程序的大致功能，需要对程序的功能进行更为严格的细分，也需要出具相应的功能结构图，同时，也要设计程序对应的数据库，包括数据库里面的数据表的设计等内容。

第五个部分：就是在系统的编码阶段，需要使用编程语言完成程序的功能，完成程序的界面设计，最终以界面实现的效果图展示设计成果等内容。

第六个部分：就是程序已经完成了开发的前提之下，需要检测程序的各个模块是否衔接正常，程序各个功能能否在网络等一切外部条件正常的情况下运行，这期间要是出现任何错误都需要及时记录并在后期进行修补完善。

第七个部分：就是论文最后的总结部分，描述遇到的问题，采用的解决思路等内容。
# 2 相关技术
## 2.1 SSM框架介绍
SSM框架是有Spring+SpringMVC+MyBatis组成。

Spring

Spring是一个开源框架，Spring是于2003年兴起的一个轻量级的Java开发框架，由Rod Johnson在其著作Expert One-On-One J2EE Development and Design中阐述的部分理念和原型衍生而来。它是为了解决企业应用开发的复杂性而创建的。Spring使用基本的JavaBean来完成以前只可能由EJB完成的事情。然而，Spring的用途不仅限于服务器端的开发。从简单性、可测试性和松耦合的角度而言，任何Java应用都可以从Spring中受益。简单来说，Spring是一个轻量级的控制反转(IoC)和面向切面(AOP)的容器框架。

SpringMVC

Spring MVC属于SpringFrameWork的后续产品，已经融合在Spring Web Flow里面。Spring MVC分离了控制器、模型对象、分派器以及处理程序对象的角色，这种分离让它们更容易进行定制。

MyBatis

MyBatis本是apache的一个开源项目iBatis,2010年这个项目由apache software foundation迁移到了google code，并且改名为MyBatis。MyBatis是一个基于Java的持久层框架。iBATIS提供的持久层框架包括SQL Maps和Data Access Objects(DAO)MyBatis消除了几乎所有的JDBC代码和参数的手工设置以及结果集的检索。MyBatis使用简单的XML或注解用于配置和原始映射，将接口和Java的POJOs(Plain Old Java Objects，普通的Java对象)映射成数据库中的记录。
## 2.2 B/S架构介绍  
在早期的程序开发中，使用得最多的莫过于C/S架构了，现在的生活中软件在生活的各个方面落地，使用了C/S架构开发出来的软件也是不在少数的，比如企业日常办公使用到的微软的OFFICE软件，我国自己研发的文档处理软件WPS，还有娱乐软件腾讯的QQ，腾讯的微信，以及电脑上安装的杀毒软件金山杀毒软件，瑞金杀毒软件等都是C/S架构。但是在Internet网络盛行之后，鉴于大家对数据信息共享的需求，在原来的C/S架构上进行了升级改进之后，有了现在的主流架构B/S架构，B/S架构就是在C/S架构上多了一个浏览器，让原来的直接访问服务器的方式，变成了通过浏览器去访问服务器。充分运用到了当下不断成熟的浏览器技术。也让软件的开发成本以及维护成本降低了。可以说B/S这种新型的架构模式让软件的开发变得便利化。
## 2.3 MySQL数据库介绍
有了程序功能的操作，也需要对程序操作的各个功能所产生的数据信息存放在一个固定的仓库里面，这个所谓的仓库就是大家最熟悉的程序开发需要使用的数据库了，数据库能够发展到至今的模样，其实也是经历了很多的变化历程的，在最开始由于数据信息处理的需要开始推出最低级的数据管理，这个阶段也是数据库早期的人工管理的阶段，后来也经历了文件管理的阶段，这个阶段的数据管理因为信息不能够进行共享，加上管理的数据对配套的程序产生了较强的依赖性，在数据信息管理上也存在很多数据的重复记载造成数据冗余等问题。所以为了解决上述一系列文件管理阶段所产生的数据管理的问题，对数据管理方式进行了全方位的升级改造，也就让数据管理进入了一个全新的阶段——数据库系统的阶段。这个阶段也是数据库管理数据的一个全新的相当高级的阶段。

说到数据库，也不得不说数据库的模型，数据库拥有的数据模型有网状，还有层次，以及关系型这三样数据库模型。网状的结构就是把记录的每条信息都比喻成一个点，点跟点之间也有联系，最终就形成了一个像网一样的结构，就是所谓的网状数据模型。也有对数据记录使用树状结构的方式进行数据保存，这个就是层次数据模型，关系数据库模型运用在现在市面上常见的数据库当中了，像本系统开发使用的MySQL数据库，还有安装过程比较复杂的Sqlserver数据库，也有一些比较小巧的关系型数据库，像Access数据库，FoxPro数据库等数据库。这样的关系型数据库将数据表里面的行还有列进行相互关联形成一个二维矩阵的方式来保存程序所产生的数据信息。

本次之所以选择MySQL数据库来当程序数据存放的仓库，则是因为此数据库安装不用费时，也不需要各种百度信息去解决安装过程中出现的任何问题，而且由于自己的电脑内存比较小，才4个G，为了更好的开发项目程序，针对低配置的电脑选择MySQL数据库也是情理之中。
## 2.4 JAVA语言介绍
在1995年这一年的5月份，著名的Sun Microsystems公司在程序开发设计上面郑重推出一种面向对象开发的程序设计语言——Java，最开始的时候Java是由詹姆斯.高斯林这位伟大的JAVA之父来进行主导，但是在后来由于各种原因，让甲骨文公司这个针对商业程序创建了oracle大型数据库的公司收购了Java。Java的平台总共算下来有3个，分别为javaME和javaSE以及javaEE这3个java平台。下面将对其进行分别介绍。

1.在电脑桌面程序的开发上面需要选择JavaME，这个用得也比较多。

2.企业也会根据工作以及业务需要开发各种软件，那么就会选用JavcEE这个支持企业版软件的开发的Java平台，JavcEE主攻运用在企业领域上面的web应用，JavcEE也在javaSE的基础上获得了比如jsp技术 ，Servlet技术等程序开发技术的支持。

3.现在生活中手机的普及化，也使得手机端这样的移动设备的软件的兴起，JavaME这个迷你版java平台就能运用于移动端的软件开发操作。



# 3 系统分析
## 3.1系统可行性分析
需要使用大部分精力开发的社区团购系统为了充分降低开发风险，特意在开发之前进行可行性分析这个验证系统开发是否可行的步骤。本文就会从技术角度，经济角度，还有用户使用的程序的运行角度进行综合阐述。
### 3.1.1 技术可行性分析
开发程序选择的是面向对象的，功能强大的，简单易用的Java程序设计语言，数据库的开发工具使用到了MySQL数据库，由于自己之前接触过一些简单的程序开发方面的设计作品，所以对Eclipse工具的使用比较熟练，对于数据库的操作技巧也有一定的积累。另外，程序开发需要在自己电脑上安装的软件并不多，在win7操作系统的大环境下，能够完全搭建好程序开发的操作环境，比如Eclipse工具，MySQL数据库工具，以及处理程序图片的Photoshop工具等都能安装在自己的电脑上。总的说来，开发这个程序在技术上是可以实现的。
### 3.1.2 经济可行性分析
开发出来的程序并不是朝着商业程序的方向进行设计开发的，它只是作为一个毕业设计项目进行开发，主要用于检验学生在学校所学知识的一个检验，也锻炼学生运用网络，图书等工具进行自学的能力。所以开发这个程序软件并不会涉及到经济上面的开销，在开发软件的选择上也不会额外付费安装软件，在开发软件的官网上面就可以下载需要的软件，并根据提示的安装步骤安装软件到自己的电脑上面。总的说来，开发这个程序在经济上也不存在经费支出。
### 3.1.3 运行可行性分析
因为这个程序软件从开始开发到开发截止都是根据用户的需求进行定制，考虑到此程序软件是面向广大普通操作用户，鉴于他们的知识文化水平，特意开发出一个可操作性强的，能够很容易让使用用户上手的，具有可视化操作界面的一个程序软件。总的说来，这个程序站在用户运行程序的角度上分析，是不存在操作难的问题的。用户只要打开程序就可以免去专人培训进行程序功能操作。

经过上面从技术的角度，从经济的角度，从程序运行的角度这三个角度分析现打算开发的程序，可以得出该程序软件是可以进行开发操作的。
## 3.2系统性能分析
### 3.2.1 系统安全性
程序在使用中是不允许其他访问者随意窃取程序里面的隐秘信息，也不允许其他操作者越权操作其他管理用户操作的功能，要真正杜绝这些现象就必须在程序开发之前把程序的安全性给考虑进去。

比如现在很多程序都会把用户注册的功能给考虑进去，让用户在注册页面功能区填写自己的个人信息，这些数据信息涵盖了用户本人的姓名，用户对程序登录设置的密码，用户经常使用的邮箱，用户的常用联系方式还有用户的所住地址等信息，这些信息都是设计到用户本人的隐私，那么这些信息在传输给程序后台时，是需要进行管理并保存至对应的数据库文件里面。要是有人恶意窃取程序的数据信息，也就会让那些注册了此程序软件的用户的个人隐秘信息都会遭到泄露。这些信息落入其他不法分子手里，他们极有可能根据用户的隐私信息去骚扰用户，并把这些信息用于各种商业用途谋取其他非法的利益。所以数据安全性是一个系统能不能使用的首要标准。
### 3.2.2 数据完整性
数据完整性是确保数据信息是否具有可靠性，是否具有参考价值的一个重要因素，数据信息只描述一部分，或者必有的数据信息反而为空等现象都是代表着这个数据信息不完整，有数据缺陷，这是个很严肃的问题，因为这样的数据信息跟垃圾信息没什么两样。

说到数据完整性，不得不提最常用的程序表单功能。这些表单主要就是提取广大用户的数据信息的，需要广大用户根据表单上的要求，填写自己的姓名信息，以及自己的联系方式信息，有些也会有额外的信息填写要求，有必须要填的选项，也有不需要必填的选项。假如广大用户为了保护自己的隐私，或者不想受到其他人的骚扰，不填写必填项等信息，广大用户在最后提交此表单的时候，往往都是提交不了的。

数据完整性不仅仅限于登记的数据要完整，它也需要程序里面的所有数据信息之间存在关联，而且这种联系也是要求不能出差错的。

由于数据表之间也会存在一定的联系，所以同一个数据也会出现在另一个表格里面，那么这两个表格记录的同一个数据应该是一样的。不能够是同样的数据信息在不同表中不一样。
### 3.2.3系统可扩展性
一切事物都是一直在发展，程序员开发软件也需要带着发展的思维去进行软件开发操作，这样的话，开发出来的程序在应对管理所需时，也会相对应的进行程序升级与更新。不论是功能完善还是数据库升级都能在原来的基础上对原有程序进行迭代升级。让开发出来的程序能够走得越来越远。这也是广大用户对程序软件的使用要求。
## 3.3系统流程分析
管理员假如要操作系统提供的功能，那么管理员就要在系统的登录界面，填写管理员登录的账号信息，填写相应的密码信息，管理员需要保证这两者能够验证身份的账号以及密码信息的正确性，这样管理员就可以通过登录界面进入系统后台操作界面。图3.1就是开发的程序软件社区团购系统它的操作流程图。

![](/md/blog.001.png)

图3.1 系统操作流程图
### 3.3.1系统登录流程
社区团购系统的登录流程，针对的角色就是操作员的操作角色。在登录界面需要的必填信息就是账号信息，配上登录的密码信息就能登录社区团购系统，需要注意的就是必填的账号信息和登录密码信息，都需要进行验证，系统会判断账号还有填写的密码信息的正确性，只有这两者信息都正确了，就能成功登录社区团购系统了。系统登录流程图如下图。

![](/md/blog.002.png)

图3.2　系统登录流程图
### 3.3.2信息添加流程
用户在添加信息的界面填写的任何数据信息也是需要验证的，系统会判断用户填写信息的格式还有数据信息是不是合法信息，如果用户填写的信息是合法内容，系统就会在数据库对应的数据表里面添加信息。添加信息流程如下图。

![](/md/blog.003.png)

图3.3 添加信息流程图
### 3.3.3信息删除流程
对于那些已经失效的信息，需要用户及时进行删除，这样有利于腾出空间存放其他信息。删除信息也是先从数据库对应数据表里面删除数据，接着就是更新数据表的信息。这样删除的数据，在用户操作界面就查看不到了。信息删除流程如下图所示。

![](/md/blog.004.png)

图3.4 信息删除流程图

# 4 系统设计
## 4.1系统概要设计
社区团购系统并没有使用C/S结构，而是基于网络浏览器的方式去访问服务器，进而获取需要的数据信息，这种依靠浏览器进行数据访问的模式就是现在用得比较广泛的适用于广域网并且没有网速限制要求的B/S结构，图4.1就是开发出来的程序工作原理图。

![](/md/blog.005.png)

图4.1 程序工作的原理图
## 4.2系统功能结构设计
下图就是系统功能结构图。

![](/md/blog.006.png)

图4.1 系统功能结构图
## 4.3数据库设计
### 4.3.1数据库E-R图设计
程序设计是离不开对应数据库的设计操作的，这样的做法就是减少数据对程序的依赖性，所以数据库的设计也是需要花费大量的日常时间来进行设计的，在设计中对程序开发需要存储的数据信息进行实体划分，先确认实体，然后设计实体的属性等操作，这种设计就是数据库设计里面不能少的必须有的E-R模型设计。为了降低程序设计的对应的数据库设计难度，开发人员也可以使用相应的工具来进行E-R模型设计，现在市面上设计E-R模型的工具有PowerDesigner建模工具，Navicat制作工具，还有微软的Visio绘图工具。为了简便起见，本程序在设计E-R模型的时候，就选用了微软的Visio这款功能强大，操作便利的绘图工具。

下面就展示社区团购系统的实体E-R图。

（1）下图就是管理员实体E-R图

![](/md/blog.007.png)

图4.7 管理员实体E-R图

（2）下图就是留言板实体E-R图

![](/md/blog.008.png)

图4.8 留言板实体E-R图

（3）下图就是商品分类信息实体E-R图

![](/md/blog.009.png)

图4.9 商品分类信息实体E-R图
### 4.3.2 数据库表结构设计
本次程序开发选用的数据库管理工具是MySQL数据管理工具，使用它存放数据也需要创建程序对应的数据库文件，并命名刚创建的数据库文件，有了数据库也需要创建各种数据表来充实数据库，在数据表的创建中，不仅需要对数据表命名，也需要对数据表的字段进行设计，包括每个数据表里面需要设置的字段名称，字段对应的数据类型信息，字段的主键设置这个也是不可缺少的，因为每个数据表里面的主键就是标记着这个数据表跟其他数据表相区分的唯一标志。就相当于生活中的每个人都有姓名，但是上网搜索自己的名字，会发现全国上下有很多人的名字跟自己的名字一模一样，包括姓氏以及名字，区分每个人的唯一信息就是每个人的身份证号信息，主键在数据表里面也是起着这样的重要作用。下面就介绍本次开发的程序社区团购系统的数据表结构信息。

表4.1 地址

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|userid|bigint(20)|否||用户id|
|address|varchar(200)|否||地址|
|name|varchar(200)|否||收货人|
|phone|varchar(200)|否||电话|
|isdefault|varchar(200)|否||是否默认地址[是/否]|
表4.2 购物车表

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|tablename|varchar(200)|是|shangpintuangou|商品表名|
|userid|bigint(20)|否||用户id|
|goodid|bigint(20)|否||商品id|
|goodname|varchar(200)|是|NULL|商品名称|
|picture|varchar(200)|是|NULL|图片|
|buynumber|int(11)|否||购买数量|
|price|float|是|NULL|单价|
|discountprice|float|是|NULL|会员价|
|shangjiazhanghao|varchar(200)|是|NULL|商户名称|
表4.3 商品团购评论表

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|refid|bigint(20)|否||关联表id|
|userid|bigint(20)|否||用户id|
|nickname|varchar(200)|是|NULL|用户名|
|content|longtext|否||评论内容|
|reply|longtext|是|NULL|回复内容|
表4.4 留言板

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|userid|bigint(20)|否||留言人id|
|username|varchar(200)|是|NULL|用户名|
|content|longtext|否||留言内容|
|reply|longtext|是|NULL|回复内容|
表4.5 社区资讯

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|title|varchar(200)|否||标题|
|introduction|longtext|是|NULL|简介|
|picture|varchar(200)|否||图片|
|content|longtext|否||内容|
表4.6 订单

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|orderid|varchar(200)|否||订单编号|
|tablename|varchar(200)|是|shangpintuangou|商品表名|
|userid|bigint(20)|否||用户id|
|goodid|bigint(20)|否||商品id|
|goodname|varchar(200)|是|NULL|商品名称|
|picture|varchar(200)|是|NULL|商品图片|
|buynumber|int(11)|否||购买数量|
|price|float|否|0|价格/积分|
|discountprice|float|是|0|折扣价格|
|total|float|否|0|总价格/总积分|
|discounttotal|float|是|0|折扣总价格|
|type|int(11)|是|1|支付类型|
|status|varchar(200)|是|NULL|状态|
|address|varchar(200)|是|NULL|地址|
|tel|varchar(200)|是|NULL|电话|
|consignee|varchar(200)|是|NULL|收货人|
|shangjiazhanghao|varchar(200)|是|NULL|商户名称|
表4.7 商家

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|shangjiazhanghao|varchar(200)|否||商家账号|
|mima|varchar(200)|否||密码|
|shangjiamingcheng|varchar(200)|是|NULL|商家名称|
|touxiang|varchar(200)|是|NULL|头像|
|lianxidianhua|varchar(200)|是|NULL|联系电话|
|dizhi|varchar(200)|是|NULL|地址|
|money|float|是|0|余额|
表4.8 商品分类

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|shangpinfenlei|varchar(200)|是|NULL|商品分类|
表4.9 商品团购

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|shangjiazhanghao|varchar(200)|是|NULL|商家账号|
|shangjiamingcheng|varchar(200)|是|NULL|商家名称|
|shangpinfenlei|varchar(200)|是|NULL|商品分类|
|shangpinbianma|varchar(200)|是|NULL|商品编码|
|shangpinmingcheng|varchar(200)|是|NULL|商品名称|
|shangpinxiangqing|longtext|是|NULL|商品详情|
|shangpintupian|varchar(200)|是|NULL|商品图片|
|beizhu|varchar(200)|是|NULL|备注|
|thumbsupnum|int(11)|是|0|赞|
|crazilynum|int(11)|是|0|踩|
|clicktime|datetime|是|NULL|最近点击时间|
|price|float|否||价格|
表4.10 收藏表

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|userid|bigint(20)|否||用户id|
|refid|bigint(20)|是|NULL|收藏id|
|tablename|varchar(200)|是|NULL|表名|
|name|varchar(200)|否||收藏名称|
|picture|varchar(200)|否||收藏图片|
表4.11 团购公告

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|gonggaobiaoti|varchar(200)|是|NULL|公告标题|
|gonggaoneirong|longtext|是|NULL|公告内容|
|gonggaofengmian|varchar(200)|是|NULL|公告封面|
|gonggaoshijian|datetime|是|NULL|公告时间|
表4.12 管理员表

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|username|varchar(100)|否||用户名|
|password|varchar(100)|否||密码|
|role|varchar(100)|是|管理员|角色|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|新增时间|
表4.13 用户

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|zhanghao|varchar(200)|否||账号|
|mima|varchar(200)|否||密码|
|xingming|varchar(200)|是|NULL|姓名|
|xingbie|varchar(200)|是|NULL|性别|
|shouji|varchar(200)|是|NULL|手机|
|shenfenzheng|varchar(200)|是|NULL|身份证|
|youxiang|varchar(200)|是|NULL|邮箱|
|zhaopian|varchar(200)|是|NULL|照片|
|money|float|是|0|余额|





# 5 系统实现
## 5.1 用户信息管理
管理员可以添加，修改，删除用户信息。下图就是用户信息管理页面。

![](/md/blog.010.png)

图5.1 用户信息管理页面
## 5.2 商家信息管理
管理员可以对商家信息进行添加，查询和修改操作。下图就是商家信息管理页面。

![](/md/blog.011.png)

图5.2商家信息管理页面
## 5.3 商品分类管理
管理员可以对商品分类信息进行添加，修改，删除操作。下图就是商品分类信息管理页面。

![](/md/blog.012.png)

图5.3 商品分类信息管理页面
## 5.4 商品团购管理
商家可以对商品团购信息进行添加，修改删除操作。下图就是商品团购信息管理页面。

![](/md/blog.013.png)

图5.4 商品团购信息管理页面
## 5.5 商品团购
用户登录以后可以对商品团购信息进行购买和评论。下图就是商品团购信息页面。

![](/md/blog.014.png)

图5.4 商品团购信息页面

## 5.6 购物车
用户点击购买后可以在购物车进行下单操作，下单后就会产生订单。下图就是购物车页面。

![](/md/blog.015.png)

图5.6 购物车页面
## 5.7 我的订单
用户可以在个人中心查看我的订单。下图就是我的订单页面。

![](/md/blog.016.png)

图5.7我的订单页面




# 系统










