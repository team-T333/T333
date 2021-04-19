至诚打卡小程序需求分析书

所属学校： 福州大学至诚学院

团队名称： T333

指导老师： 张栋

项目时间：2020-2021第二学期

**1.引言**

1.1目的

>   为了保证项目团队按时保质地完成项目目标，便于读者更好地了解项目情况，使项目工作开展的各个过程合理有序，有必要以文件化的形式帮助阅读者了解文档如何编写，大体浏览报告内容

>   本项目开发计划用于交流沟通、学习、资源共享等面向校内人员。

1.2 项目风险

>   出于安全性的考虑，并未直接对接数据库，而是面对需求做一个初级开发，本阶段未呈现出风险性，且主要包括以下人员：

>   ·任务提出者：[任务链接](https://edu.cnblogs.com/campus/fzzcxy/2018CS/homework/11936)

>   ·软件开发者：[T333团队](https://www.cnblogs.com/T333/p/14594659.html)

>   ·产品使用者：校内人员

1.3 产品范围

>   为了更好地促进我校学生学习氛围，增添读书兴趣，T333团队开发图书馆打卡小程序面向我校师生。

1.4 模块分配

1.5 参考文献

>   ·《软件需求规格说明书》国标文本（GBT8567-2006 && GBT9385-2008）

>   ·构建之法（第三版）作者:
>   [邹欣](https://book.douban.com/search/%E9%82%B9%E6%AC%A3) 出版社:
>   人民邮电出版社

**2.**图例

2.1项目LOGO：

2.2用例图：

2.3类图：

2.4活动图：

2.5顺序图：

2.6状态图：

2.7通信图：

**3 用户场景**

小明——普通大学生一个，使用的主要用户

| 名字             | 小明                                               |
|------------------|----------------------------------------------------|
| 性别、年龄       | 男、20                                             |
| 职业             | 学生                                               |
| 收入             | 无                                                 |
| 知识层次和能力   | 在校大学上、玩手机很娴熟                           |
| 生活/工作情况    | 有点宅，除了上课，周末偶尔出去玩以外没有多余的活动 |
| 动机，目的，困难 | 需要完成学校的硬性阅读要求，但是懒得去图书馆       |
| 用户偏好         | 玩手机，上网                                       |
| 典型描述         | 阿宅                                               |

小红—一个文艺的小青年

| 名字             | 小红                                                             |
|------------------|------------------------------------------------------------------|
| 性别、年龄       | 女 19                                                            |
| 职业             | 学生                                                             |
| 收入             | 无                                                               |
| 知识层次和能力   | 在校大学生、文艺小青年                                           |
| 生活/工作情况    | 学校生活比较丰富，闲暇时间喜欢运动、阅读                         |
| 动机，目的，困难 | 日常有一定的阅读需求，喜欢做一点阅读记录，需要有一个更简便的渠道 |
| 用户偏好         | 运动，阅读                                                       |
| 典型描述         | 校园生活丰富                                                     |

场景/故事/Story

1、背景：

（1）典型用户：小明

（2）用户的需求/迫切需要解决的问题：

a、小明：学校规定一个学期要阅读多少天，但是我懒得去图书馆

b、小明：我想借一些书回宿舍读，不知道该借哪些书

（3）假设：

A、已经注册账号，点击登陆

B、看一下有哪些推荐阅读的书，去图书馆借或者看电子书

C、每天阅读的时候只要点一下打卡

2、场景：

关于这个场景的文字描述：

·小明上完课回到宿舍，突然想起自己的阅读任务，他打开了app，看了一下推荐借阅的书籍，准备下次下课之后顺路去图书馆借回来。

·小明又一次上完课回到宿舍，他想起了自己的阅读任务，他翻出了之前借的书开始阅读，阅读一个小时后他打开手机进行打卡。

1、背景：

（1）典型用户：小红

（2）用户的需求/迫切需要解决的问题：

a、小红：我这个学期阅读了许多书，我想做一个阅读记录

b、小红：最近有点书荒，不知道有哪些合我口味的书

（3）假设：

A、已经注册账号，点击登陆

B、打开签到记录，看到自己本学年阅读天数，打开阅读记录，看到本学年借阅过的书

C、打开推荐阅读，系统根据平时阅读的书籍类型展示一批未阅读过的书

2、场景：

关于这个场景的文字描述：

·一个普通的晚上，小红开始阅读，她打开app进行签到打卡，看到自己本学年已经阅读了两百多天，感觉非常有成就感，读的更起劲了，顺便截图分享朋友圈，晒一下自己的阅读记录

·一个普通的晚上，小红读完了一本书，但她还意犹未尽，她打开了app，在推荐阅读栏目中根据书籍简介筛选了一些自己感兴趣的书，存入自己的收藏夹准备明天去图书馆借。

四、界面效果：

引导页，按跳过按钮就会跳转到打卡程序首页。

首页-未授权，是还未登陆的首页，点击去打卡进行登陆。

登录界面，输入学号密码进行登陆，没有账号可以进行注册

注册界面，需要勾选上用户协议才能进行注册

首页-已授权-今日未打卡。是可以滚动的长页面，登陆后进入的界面，可以进行打卡、查看打卡历史、查看排行榜、分享日签、查看好友海报等功能。

弹窗-打卡成功，是提示打开成功的弹窗。

历史记录，可以查看你打卡的记录。

排行榜-总榜。可以看到别人的打卡积累天数，与自己作比较。

弹窗-好友海报。可以查看好友的学习海报，进行保存或分享。

弹窗-分享日签。向别人分享你的日签。

五、功能描述：

1.每日打卡:（获取地理位置，仅身在图书馆才能完成打卡，可以查看历史打卡记录）；

2.时长查询:（今日打卡时长，可得知今日在图书馆学习时间）

3.排行榜:（然后根据在馆时长生成好友排行）；

4.周目标:（打卡后可制定属于自己的周目标，以此激励自己学习，安排自己的学习时间）

5.分享/邀请好友（可通过分享日签和生成好友海报的形式让自己的好友同学看到你的学习日程，鼓动他们一起加入学习，让学习的路不再孤单）

六、验收验证标准

| 测试功能       | 测试项     | 输入/操作          | 校验点                         | 预测结果                                 | 验收情况 |
|----------------|------------|--------------------|--------------------------------|------------------------------------------|----------|
| 注册界面       | 新建账户   | 点击账号输入框     | 账号为学号                     | 账号符合学号格式且未被注册过才可注册     |          |
|                |            | 点击验证码输入框   | 验证码为四位数                 | 验证码为发出验证码                       |          |
|                |            | 点击密码输入框     | 密码长度8-16位                 | 密码文本符合格式才可注册                 |          |
|                |            | 点击密码重复验证框 | 重复密码与上个文本输入密码相同 | 重复密码与上个密码文本框输入相同才可注册 |          |
|                |            | 点击注册           | 账号密码是否符合注册规则       | 输入框全部符合输入规则注册成功，否则提示 |          |
|                | 用户协议   | 点击勾选框         |                                | 成功勾选                                 |          |
| 登录界面       | 登陆操作   | 点击账号输入框     | 账号为学号                     | 账号符合学号格式且注册过才可登录         |          |
|                |            | 点击密码输入框     | 密码长度8-16位                 | 密码符合格式且与账号绑定才可登录         |          |
|                |            | 点击登录           | 账号密码是否符合登录规则       | 输入框全部符合输入规则登录成功，否则提示 |          |
| 主界面         | 打卡操作   | 点击去打卡         | 转入打卡界面                   | 成功跳转至打卡界面                       |          |
|                | 打卡历史   | 点击打卡历史       | 转入打卡历史界面               | 成功跳转且能看到数据                     |          |
|                | 打卡排行榜 | 点击打卡排行榜     | 转入打卡排行榜界面             | 成功跳转且能看到数据                     |          |
|                | 打卡分享   | 点击打卡分享       | 转入打卡分享界面               | 成功跳转至打卡分享界面                   |          |
| 打卡界面       | 打卡操作   | 点击去分享         | 转入打卡分享界面               | 成功跳转至打卡分享界面                   |          |
|                |            |                    | 显示打卡成功                   | 显示打卡成功并记录数据                   |          |
|                |            | 点击 \< 返回       | 转入主界面                     | 成功跳转至主界面                         |          |
| 打卡历史界面   | 打卡历史   |                    | 看到历史打卡数据               | 成功看到历史打卡数据                     |          |
|                |            | 点击 \< 返回       | 转入主界面                     | 成功跳转至主界面                         |          |
| 打卡排行榜界面 | 打卡排行榜 |                    | 看到排行榜数据                 | 成功看到排行榜数据                       |          |
|                |            | 点击 \< 返回       | 转入主界面                     | 成功跳转至主界面                         |          |
| 打卡分享界面   | 打卡分享   | 点击分享海报       | 分享给好友                     | 成功分享                                 |          |
|                | 本地存图   | 点击保存到相册     | 保存到相册                     | 成功保存到相册                           |          |
|                |            | 点击 \< 返回       | 转入主界面                     | 成功跳转至主界面                         |          |