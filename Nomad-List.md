## 游民列表是什么? - What is Nomad List?

[Nomad List](https://nomadlist.com/) 为远程工作者寻找适合工作和生活的城市。上面有 500+ 个城市的超过 5 万条数据。包括生活成本，温度，安全度，等等。通过这些数据，网站可以帮你估算出下一个可以去的地方。


## 谁创造了这个网站? - Who's behind it?

Nomad List 是 2014 年由 [Pieter Levels](https://twitter.com/levelsio) 写的，他当时在做 [12个月 12 个创业项目](https://levels.io/12-startups-12-months/)。 Nomad List 是第 4 个项目，Pieter 从 2010 年就经常看 Hacker News，激励了他自学编程然后做东西，patio11 发的帖对他影响最大。

## 刚开始时是怎样的? - What were things like in the beginning?

Pieter [把故事在这里写得很详细](https://levels.io/product-hunt-hacker-news-number-one/)。这个点子来自于解决他自己的问题 :

> 我之前一边全世界到处旅行一边工作，然后认识了很多和我一样的人。他们有的是自由职业者，有的为公司远程工作，有的是初创公司的创始人。我知道有些城市有很多这样的人，比如泰国清迈那边，但是很难弄清其他城市是否适合这种远程工作的生活方式.. 所以我觉得远程工作者们需要一个城市索引之类的东西

Pieter 从一开始就积极寻求反馈:

> 我想写个简单的城市列表，标明各个城市是否适合这种生活方式。2 个很重要的因素是生活成本和生活质量。所以我马上开始收集各个城市的生活成本和生活质量数据。我知道我没法一个人收集齐 50 个城市，这样的话有 2500 个数据点要收集。我知道我得先验证需求再做。
>
> 所以我没有马上写代码，而是弄了个可以公开访问的 Google 电子表格来收集数据，然后看看其他人有没有兴趣。
>
> 大家的积极度让我有点意外，不仅有人往里填数据，还有人往里加新指标，比如安全度，咖啡馆密集度，和 LGBTQ 友好度...

产品第一次发布 (launch) 其实是个意外:

> 6 月 24 号我把链接发到了 Twitter 上。大概一个月后， 7月29号, 我重启 Linode 服务器时不小心把本地的 nginx.conf 配置文件也传了上去，然后网站就上线了，我还不知道。后来有很多人发 Twitter 圈我我才知道。然后那天刚好有篇关于我的报道发布在了 TechInAsia 上。Emiel Janson 还在我不知道的情况下提交到了 Product Hunt 。
>
> 后来在 Product Hunter 上我们得到的赞是全站第 5 高。之后我还提交到了 Hacker News，在上面直接蹦到了当日第一… 因为不知道这俩事具体带来了多少用户，我只能用现有数据估，Hacker News 大概给我带了 50,000 个访问。Product Hunt 大概是 12,000 个。

## Nomad List 带来了多少收入? - How much revenue does Nomad List generate?

据 Pieter 所说，[Nomad List 一年差不多 $40 万美金](https://news.ycombinator.com/item?id=12067113) ，而且还在上升：

> 主站是完全免费的，所以能吸引用户注册，然后说不定还能变成付费用户。付费得到是聊天群和论坛 (和一些额外功能，比如旅程规划工具 [NomadTrips.co](http://NomadTrips.co))。一年价格是 $75 美金
>
> 我刚开始收费时只加了些简单功能（比如聊天）然后一次性收 5 美金。后来有人发垃圾信息，即便 5 美金的门槛还有人发垃圾信息，所以我不断提高价格，25 美金，50美金，65美金。然后 2016 年 4 月我换成了一年收费一次。注册数依然平稳且缓慢上升。

这 $40 万里大概有 $8 万来自于远程工作招聘网站 [RemoteOK.io](https://remoteok.io/) Pieter 后来把它和 Nomad list 整合了起来。另外的话，这 $40 万里有 25% 收入来自广告。

在 RemoteOK 发一个招聘贴的价格是 200 美金一个月，关于这个价格， Pieter 说：

> 我一般都从低价开始，然后逐渐提价，直到看到统计数据下滑才停，这个方法不是特别科学但是对我来说管用。

## Nomad List 是怎么增长的？ - How does Nomad List grow?

Pieter 完全没在广告，市场，或公共关系上面花时间。Nomad List 完全是靠口碑增长的：

> 免费的主站 ([https://nomadlist.com](https://nomadlist.com)) 在主流媒体上如 Time, Times 和 HuffPo 被报道过几次。 我完全没做 PR 或市场营销。所以我的 CAC(用户获取成本) 是 0。另外，网站在 Google 搜索里排名很前，因为有很多网站引用了我们。我没有主动找他们去引用我们，他们这么做纯粹是喜欢我的网站。我上个月试了下 Facebook 广告，效果不是很好，只来了 4 个用户。所以我觉得 “有机获取”（organic acquisition） 对我来说最管用。有机获取的意思是：造个有用的网站，加上付费功能，然后按时间收费，没了。

Pieter 雇过至少 4 个兼职合同工帮忙，不过他自己还是做了大部分的事，他说 “95% 的事都是我做的”

## 碰到过一些什么大挑战？ - What have been some of the biggest challenges?

刚开始时 Pieter 担心过用户存留率的问题：

> 我写了网站之后想，他们离开之后估计就再也不会回来了，所以我加了 [MailChimp](http://eepurl.com/cb60-X) 吸引用户留邮箱地址，之后弄了聊天群，还有论坛。吸引用户不断回来甚至付费。

Pieter 还写了 “旅程” 中最困难的部分：

> 我觉得要尽早占领市场，然后保持住，挡住各类竞争者的进攻（有些甚至还拿了投资），那些竞争者会复制所有功能并且试着做得比你好。还有就是脸皮要厚，刚开始收费的时候有些人可不喜欢。

## Nomad List 怎么应对竞争者? - How has Nomad List handled competition?

> 我都忽略竞争者，做自己要的功能，因为这个产品解决的是我自己的问题，所以我大概知道用户想要什么。
>
> 我想另一个大因素是就我一个人在做，所以我比那些大团队要快。我做的东西不是顶尖的，但足够好用。网站本身不是特别好看，但足够完成用户想要的功能了。我见过很多其他产品（特别拿了投资的） 20人+ 的团队做了个特别好看的产品，但不好用。

## 技术栈是什么？ - What tech stack does Nomad List run on?

> HTML, CSS, JavaScript 和 PHP。服务器用的是 Linode VPS，操作系统 Ubuntu 然后还用了 Nginx。
>
> 网站大部分都是纯代码，没用框架。论坛的话我是拿 Discourse 开源论坛改的，做了深度定制。聊天用的是 Slack。

<div>partner</div>

## 想了解更多? - Where can we learn more about Pieter and Nomad List?

Pieter [经常在 Hacker News 发帖](https://news.ycombinator.com/user?id=pieterhg)。

他比较喜欢用 Twitter 联系： [@levelsio](https://twitter.com/levelsio).

他也在 [个人博客发东西](https://levels.io)。

最后别忘了看下 [Nomad List](http://nomadlist.com/) itself！

### Translated by Zheng Cheng
[Github@1c7](https://github.com/1c7)，Ruby on Rails developer and side project enthusiast. currently living in GuangZhou, China. Remote working.

### 译者：郑诚
[Github@1c7](https://github.com/1c7)，[新浪微博@糖醋陈皮](http://weibo.com/u/2004104451)，现居广州，Ruby on Rails 远程工作中。在一边工作一边在忙美国留学。
