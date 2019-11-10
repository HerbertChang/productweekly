# 产品爱好者周刊：第 4 期（20191110）

![Wu_Zhen_Fisherman.jpg](https://cdn.nlark.com/yuque/0/2019/jpeg/535404/1573351721939-916f0d17-30db-45df-8f51-74d471d24a2e.jpeg#align=left&display=inline&height=480&name=Wu_Zhen_Fisherman.jpg&originHeight=480&originWidth=716&search=&size=112590&status=done&width=716)<br />欢迎来到产品爱好者周刊。这里用于分享我个人对产品行业的一些观点，计划每周更新一期，内容设计如下：

- **新产品介绍：**值得关注的新产品，包括但不限于 APP、网站、小程序、企业服务。
- **本期聚焦：**某个/某类产品详细解读。
- **佳文推介：**产品/商业/管理类文章，中英都有。
- **每周一书：**偏向于社会科学类书籍。我个人认为产品从业者要尽可能吸收社会科学的见解来提升思考力。
- **浴室沉思：**书桌前想不明白的问题，浴室也未必能想明白。

个人见识有限，偏颇之处在所难免。本杂志开源（GitHub: [HerbertChang/pmweekly](https://github.com/HerbertChang/pmweekly)），欢迎提交 issue，也欢迎你通过评论/邮件的方式来分享你的看法，我的邮箱是：[herbertchang19@gmail.com](mailto:herbertchang19@gmail.com)。

本期封面：吴镇《渔父图》（局部）。

<a name="QnOEd"></a>
### 值得关注的新产品
<a name="Qzmeq"></a>
#### 1. [The New Microsoft Office（iOS & Android）](https://testflight.apple.com/join/eHAKJBtM)

        ![image.png](https://cdn.nlark.com/yuque/0/2019/png/535404/1573283903113-237fabc3-34cd-40bd-bdd4-78fabbcea9db.png)
          
  
  
          
      
    
  

微软针对移动端即将推出的新版 Office （仍在测试阶段），将三件套在移动端合而为一。
> 来源：[https://www.producthunt.com/posts/the-new-microsoft-office](https://www.producthunt.com/posts/the-new-microsoft-office)
> [https://www.youtube.com/watch?v=QDPzKA1v32o](https://www.youtube.com/watch?v=QDPzKA1v32o)


<a name="ANqgD"></a>
#### 2. [Visual Studio Online](https://online.visualstudio.com/)
![image.png](https://cdn.nlark.com/yuque/0/2019/png/535404/1573291738734-69a3bcb3-8e44-4a7e-a9cf-505bca427c66.png#align=left&display=inline&height=293&name=image.png&originHeight=586&originWidth=1042&search=&size=368694&status=done&width=521)

微软家的开发工具 Visual Studio 推出了在线版。
> 参考资料：
> [https://visualstudio.microsoft.com/zh-hans/services/visual-studio-online/](https://visualstudio.microsoft.com/zh-hans/services/visual-studio-online/)
> [https://techcrunch.com/2019/11/04/you-can-now-try-microsofts-web-based-version-of-visual-studio/](https://techcrunch.com/2019/11/04/you-can-now-try-microsofts-web-based-version-of-visual-studio/)


<a name="0M7ue"></a>
#### 3.  [8b Website Builder](https://8b.com/)
![image.png](https://cdn.nlark.com/yuque/0/2019/png/535404/1573292125760-e44e0d07-09ed-4a74-b40b-719fbaf8e425.png#align=left&display=inline&height=293&name=image.png&originHeight=585&originWidth=1025&search=&size=323084&status=done&width=512.5)<br />快速建站工具，提供模板，提供免费 HTTPS SSL 证书。

<a name="8z26o"></a>
#### 4.  听筒
![image.png](https://cdn.nlark.com/yuque/0/2019/png/535404/1573292398540-37db32fb-e59a-48d2-8b30-718e332e3955.png#align=left&display=inline&height=588&name=image.png&originHeight=1920&originWidth=1080&search=&size=1099280&status=done&width=331)

百度上线定位校园场景的匿名社交软件「听筒」。试用了一下，目前没什么亮点可以说道，等迭代看看……
> 参考资料：[https://36kr.com/p/5263898](https://36kr.com/p/5263898)

<br />
<a name="QsHjN"></a>
### 本期聚焦：Telegram 及其功能设计品鉴

Telegram 这款鼎鼎大名的软件由尼古拉·杜洛夫（Nikolai Durov）与保罗·杜洛夫（Pavel Durov）兄弟于 2013 年创立。知名开发者霍炬曾撰文《[Telegram 传奇：俄罗斯富豪、黑客高手、极权和阴谋](http://mp.weixin.qq.com/s/y3wQOb6gwMxCDhRKbiSz4Q)》来介绍 Telegram 的发展史，杜洛夫兄弟的故事十分具有理想主义色彩，推荐阅读。这篇文章中微有瑕疵的一处是「所有代码都是开源的」，事实上 Telegram 的官方客户端软件是开源的、而服务器端软件是属于非开源的专有软件。Telegram 使用专有加密协议，密码学社群认为这是一个弱点。创始人兄弟俩是土豪，不缺钱，并表示电报的主要重点不是[带来利润](https://link.zhihu.com/?target=https%3A//telegram.org/faq%23q-how-are-you-going-to-make-money-out-of-this)，所以商业利益永远不会妨碍他们的使命。2018 年 3 月 23 日，Pavel Durov 宣布它的月活跃用户[突破了 2 亿](https://telegram.org/blog/200-million)。俄罗斯法庭曾要求 Telegram 交出加密密钥，否则将有可能在俄遭屏蔽，最终 Telegram 拒绝提供。

![Encryption-ranking-detailed-table_CH-final.jpg](https://cdn.nlark.com/yuque/0/2019/jpeg/535404/1573303849777-a457f571-0f33-4114-a67d-d000fbd707d6.jpeg#align=left&display=inline&height=897&name=Encryption-ranking-detailed-table_CH-final.jpg&originHeight=1328&originWidth=829&search=&size=1033996&status=done&width=560)<br />图：[通讯软件隐私排名](https://zh.amnesty.org/more-resources/news/%E8%85%BE%E8%AE%AF%E3%80%81snapchat%E3%80%81%E5%BE%AE%E8%BD%AF%E7%AD%89%E5%BA%94%E7%94%A8%E8%BD%AF%E4%BB%B6%E6%9C%AA%E4%BF%9D%E6%8A%A4%E7%94%A8%E6%88%B7%E9%9A%90%E7%A7%81/)

为了表明 Telegram 技术值得信赖，2013 年 12 月 Pavel Durov 表示只要有人能成功破解已拦截的通话讯息，他愿意提供 20 万比特币做为奖金。后来，一名使用者在发现 Telegram 的信息安全隐患（不算漏洞）后，确实获得了 10 万美元的现金奖励。在 2014 年 3 月的一场竞赛中，虽然有多名挑战者试图破解从 Telegram 截获的流量，但却没有任何人成功。即使到现在，Telegram 依然在[官方页面](https://telegram.org/faq)中称，任何能证明自己可以破译 Telegram 信息的人都可以得到 30 万美元的奖金。

目前，Telegram 支持 Android、iOS、Windows Phone、Mac OS 、Windows、Linux 等常见操作系统，而且还提供了 Web 版。Telegram 支持的会话有一对一聊天（非端对端加密）、私密聊天（端对端加密，可设置阅后即焚）、群组聊天。Telegram 的群组聊天没有开启端对端加密，这一点曾遭到 Signal （另一款端对端加密聊天软件）开发者炮轰。私密聊天支持设置阅后即焚定时器，且当会话对方执行截图操作时发出提醒。Telegram 的群组聊天人数无上限，有的群组人数超过 14 万人，Telegram 开发者的技术实力真是可怕（QQ支持的群组上限为 500 人，氪金也只能增加到最多两千人）。

Telegram 一些有趣的功能设计：<br />（1）群组功能：加群只需要点一下 t.me/打头的链接（加载语言包、配置专属 MTProto 甚至也可以通过点击链接完成）。群组聊天中群主可以精细设置成员权限，提供了慢速模式（强迫群成员在发言前思考），十分适合人数很多的群避免无脑吵架。<br />![photo_2019-11-09_21-43-21.jpg](https://cdn.nlark.com/yuque/0/2019/jpeg/535404/1573307055329-1f09d4c1-869c-467a-a1e9-6bc0f95d4d48.jpeg#align=left&display=inline&height=410&name=photo_2019-11-09_21-43-21.jpg&originHeight=1280&originWidth=768&search=&size=66176&status=done&width=246)

（2）Channel：Telegram 的 Channel 功能比微信订阅号支持的内容丰富太多，且不限制每天发送次数、不限制文件大小、允许设为私有（故私有 Channel 可以当个人备份网盘用）。包括 Channel 在内的所有对话中发送的超过两千个主流网站链接支持 instant view， 底部按钮可以直接跳转群组。Readhub 在页面交互上曾借鉴过这个 [instant view 功能](https://telegram.org/blog/instant-view)。<br />![4233a17be835481dc4.jpg](https://cdn.nlark.com/yuque/0/2019/jpeg/535404/1573305266517-3a7b0d2d-0c95-40ac-b6eb-e7f9b10c052a.jpeg#align=left&display=inline&height=394&name=4233a17be835481dc4.jpg&originHeight=1138&originWidth=720&search=&size=134511&status=done&width=249)<br />![photo_2019-11-09_21-50-12.jpg](https://cdn.nlark.com/yuque/0/2019/jpeg/535404/1573307453997-47ff2ede-9176-4feb-b62e-46787090ca11.jpeg#align=left&display=inline&height=427&name=photo_2019-11-09_21-50-12.jpg&originHeight=1280&originWidth=744&search=&size=154149&status=done&width=248)

（3）魔性贴纸（表情包）：Telegram 自带表情包就很有特色，并支持自制表情包，不限数量。<br />![TIM图片20180406233914.jpg](https://cdn.nlark.com/yuque/0/2019/jpeg/535404/1573305055983-82a56324-997e-413c-8dd5-23f59dc6111f.jpeg#align=left&display=inline&height=407&name=TIM%E5%9B%BE%E7%89%8720180406233914.jpg&originHeight=1712&originWidth=1080&search=&size=499889&status=done&width=257)

（4）Bot（机器人）：向 Bot 发送关键字可以获取导航信息，在其他应用上没有看到过类似的交互。而且在部分群里看到过采用 Bot 进行信息识别来踢出广告党。通过特定的 API 接口可以开发适合自身功能需求的 Bot。<br />![TIM图片20180407000808.jpg](https://cdn.nlark.com/yuque/0/2019/jpeg/535404/1573305140050-e67532dd-afe6-4218-b76d-624068558eb3.jpeg#align=left&display=inline&height=429&name=TIM%E5%9B%BE%E7%89%8720180407000808.jpg&originHeight=1833&originWidth=1080&search=&size=526500&status=done&width=253)

Telegram 有特色的功能实在太多，此处挂一漏万，只是一个引子。最后提醒一下，出于安全起见，如果想体验这款软件请尽量买一个国外虚拟手机号注册。
> 参考资料：<br />[https://www.pingwest.com/a/39818](https://www.pingwest.com/a/39818)
> [https://zhuanlan.zhihu.com/p/43641891](https://zhuanlan.zhihu.com/p/43641891)
> Telegram——真正定义即时通讯 [https://arminli.com/blog/177](https://arminli.com/blog/177)
> [https://www.playpcesor.com/2015/12/telegram-10.html](https://www.playpcesor.com/2015/12/telegram-10.html)
> [https://einverne.github.io/post/2016/07/telegram-review.html](https://einverne.github.io/post/2016/07/telegram-review.html)


<a name="iuyES"></a>
### 佳文推介
<a name="rQVNz"></a>
#### 1. [设计考古：工具类产品 Office](https://www.yuque.com/ant-design/ant-design/kff9g2)
详细阐述了微软 Office 界面 40 年演变史和 Ribbon （功能区）设计模式，对理解复杂 B 端产品设计有帮助。

<a name="MTAwk"></a>
#### 2. [UNIX 50 年：KEN THOMPSON 的密码](https://coolshell.cn/articles/19996.html)
以 Ken Thompson 几十年前的密码被破解为切入点漫谈 Unix 文化与黑客大佬们。上个世纪五六十年代麻省理工一帮聪明又精力充沛的年轻人群体中兴起的黑客（hacker，中性含义）文化衍生出 Unix、互联网、自由软件运动与开源软件等影响到今日世界的物件与观念，真是不可思议。

<a name="zJH0f"></a>
#### 3. [跟踪了解西方传媒业前沿动态的 15 个网站](http://fangkc.cn/2015/12/media-websites/)
作者方可成的「人生经验」，提供了解西方媒体动态的最佳资源。

<a name="2KPRl"></a>
#### 4. [How to use Google Sheets as a CMS or a database](https://blog.usejournal.com/how-to-use-google-sheets-as-a-cms-or-a-database-f9d8e736fdce)
采用 Google Sheet、Google API 和 PHP 搭建了一个 CMS 系统做出了类似 Product Hunt 的网站。

<a name="tGudp"></a>
### 每周一书
![image.png](https://cdn.nlark.com/yuque/0/2019/png/535404/1573284690432-b8cdd5d9-88fb-4af6-a1e5-4179caa904d7.png#align=left&display=inline&height=313&name=image.png&originHeight=626&originWidth=432&search=&size=226045&status=done&width=216)<br />埃尔温·薛定谔[《生命是什么：活细胞的物理观》](https://book.douban.com/subject/26309060/)

没错，此书作者就是那位坊间戏称「虐猫狂魔」的薛定谔大神，内容源自于 1943 年在英国都柏林三一学院高等研究院的系列演讲内容整理。这本小册子被称为「分子生物学中的《汤姆叔叔的小屋》」，许多生物学大佬（例如 DNA 双螺旋结构发现者之一的克里克）承认受到过这本书的影响。作者从物理学基础的角度谈了对于生命现象的理解，讨论了遗传密码、量子力学角度考量基因、生命与熵等主题。希望读者在阅读过程中暂且放下直奔结果的惯性，体会薛定谔思考的脉络和论述方法。同名书不同时期有多个译本，此处选取张卜天 2015 年商务社译本，可与湖南科学技术出版社 2007 年译本（收入「第一推动丛书」）互参。

<a name="ZyGsv"></a>
### 浴室沉思
2019 年初前后大批营销广告党涌入 Telegram，污染群组环境，迫使此软件将所有 +86 用户降低建群权限。为什么 +86 营销用户总是在一些平台搞得像蝗虫过境？？

<a name="b0GzR"></a>
### 订阅
本周刊每周日发布，同步更新在 [GitHub](https://github.com/HerbertChang/pmweekly)、[个人博客](https://herbertchang.github.io/)、[微信公众号](https://weixin.sogou.com/weixin?type=1&s_from=input&query=%E8%8B%A5%E6%84%9A%E8%8B%A5%E6%98%8F&ie=utf8&_sug_=y&_sug_type_=&w=01019900&sut=10610&sst0=1571666684054&lkt=0%2C0%2C0)和[语雀](https://yuque.com/herbert-chang/pmweekly/)。<br />微信搜索「若愚若昏」，即可订阅。<br />![qrcode_for_gh_8aa200a62b9a_258.jpg](https://cdn.nlark.com/yuque/0/2019/jpeg/535404/1571989117002-cef6be63-7b29-4ac4-a35f-3b5a43e7ce88.jpeg#align=left&display=inline&height=149&name=qrcode_for_gh_8aa200a62b9a_258.jpg&originHeight=258&originWidth=258&search=&size=27692&status=done&width=149)

<a name="KpBFu"></a>
### 致谢
想法来自阮一峰老师的《科技爱好者周刊》。特此致谢！ [https://github.com/ruanyf/weekly](https://github.com/ruanyf/weekly)
