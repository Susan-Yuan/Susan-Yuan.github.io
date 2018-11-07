---
layout: post
title: Google Shopping 不可信
subtitle: 搜索结果可能出现诈骗网站
tags: Google Shopping Scam
---

第二篇文章竟然隔了整整三个月···

一到11月就进入了买买买的季节。在北美买东西有个好用的比价工具就是Google自带的Shopping搜索，其中有一项按价格排序非常实用，可以找到收录商家的最低价（不过有时候会收录一堆eBay商家看起来就非常头疼了）。今天搜索了一个厨师机，按价格排序后得到了如下结果

![比价结果](/img/googleshopping/prices.png)

第一个商家比别家便宜不少，但是没有rating，名字也起得很奇（乡）怪（土），成功引起了我的注意。点进去看了一下，页面设计的倒是很简洁，退货政策，隐私声明，联系我们都填了，但是浓浓的一股虚假网站的气息啊——怎么看都是模板做出来的网站。

对Google Shopping的怀疑不是一两天了，这源于暑假一次购物经历，买instant pot（怎么都是厨具···）时最低价网站几乎一样的套路：明显的低价（但又不是低的离谱），模板化的网站，无评价。当时虽然充满了怀疑但是本（迷）能（信）地相信Google推荐的网站应该都是审核过的，而且支持PayPal支付，我倒要看看这网站能玩出什么花样来。

于是结果就是···PayPal付完钱后网站迟迟不发货。还以为摸清了网站骗人套路，走PayPal投诉等着退款的时候，在申诉期的最后一天网站竟然发货了···货也没问题，锅用的好好的，虽然怀疑是诈骗网站可是人家毕竟发货了不是么，走PayPal也骗不到我的信用卡信息，不过怀疑的种子就这么种下了。

但是今天我准备抓实锤了。

先看了看网站的结账方式，只能用信用卡，推测是收集信用卡信息的虚假网站。接下来查域名历史，在scamadviser这个网站上查到如下结果

![查询结果](/img/googleshopping/facts.png)

这么短的注册时间，隐藏地址，代理域名，结果应该很明显了，引用网站的评论

> The website has been newly registered with a short life expectancy, which follows the pattern used by many **fraudulent** and **fake selling** websites. Please be vigilant and take extra care before providing any payment information.

但是具体是怎么骗的呢？于是又Google了一下网站域名（此时还是离不开狗），果然有人[发帖控诉](https://www.complaintsboard.com/complaints/pricechoppingcom-decline-of-my-card-a-way-to-get-credit-card-info-c1047080.html)。手段就是刷卡不通过，但是信用卡信息已经盗取了。

随顺一提，查的时候发现Google Trusted Stores 项目已经[停止运行](https://support.google.com/faqs/answer/7422701?visit_id=636771566524456885-3628683560&hl=en&rd=1)了。

所以Gooogle Shopping的搜索结果不可全信，还是需要练就火眼金睛。至于搜索引擎有没有过滤虚假信息，防止诈骗网站的义务呢？百度似乎给了前车之鉴。在搜索这个网站的过程中，我还看到了不少类似的[投诉](https://productforums.google.com/forum/#!topic/websearch/nySrPhtrxck)在Google自己的论坛里，然而回复基本就是给一个投诉诈骗网站的链接。至少在搜索结果页面给个提示“Google不保证这些网站真实可靠”吧，毕竟收录的商家都是给了钱的呢。

最后，Google，要锤得锤~







