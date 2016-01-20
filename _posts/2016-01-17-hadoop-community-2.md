---
layout:     post
title:      "Hadoop PMC养成记"
subtitle:   "讲述如何在开源社区里打怪升级的故事"
categories: big-data
tags:       [big-data, hadoop, community]
date:       2016-01-17 12:00:00
author:     "Zhijie Shen"
header-img: "img/post-bg-04.jpg"
---

在上一篇博文的最后，小编说好了要和大家讲讲如何在Hadoop社区里打怪升级，这两天忙里偷闲，来写写自己
的成长故事和心得体会，希望这个话题大家会感兴趣，也对要混迹开源社区的小伙伴们有所帮助。

小编的开源故事开始于五年前，通过一个叫做[Google Summer of Code(GSOC)]
(https://developers.google.com/open-source/gsoc/)的项目，参与了Apache PIG的开发。小编
特地挖出了当年给Hadoop ecosystem贡献的第一个[patch](https://issues.apache.org/jira/browse/PIG-1916)。
Hadoop并不参与GSOC，所以小编选了从一个相关的项目开始，积累了做开源项目的经验，并且认识了H家（全名
参见之前的博文）的员工。

之后，小编来到美帝M家开始了码公生涯，但是不久就联系上了H家的旧识。因为非常看好Hadoop，所以小编
毅然决然地选择加入了H家，选择了YARN组，成为了社区的一员。之后一路从修复bug，到负责重要的feature，
再到主导子项目。两年内，从Contributor，升级为Committer，再升级为PMC，加上Apache Foundation
的Member。此外，还在Hadoop Summit和ApacheCon上代表项目和公司做presentation。流水账就不细
报了，着重分享一下升级的重要经验。

![Career Ladder in Hadoop]({{ baseurl }}/img/2016-01-17-elephant-ladder.jpg)

- 首先，就是是要对项目的热情。听上去是比较假大空，但是小编还是想把它作为第一条。因为热情，才会愿
意做后面说到的事情，才会愿意在下班后，在周末也利用业余时间也来参与项目和社区的事情。

- 虽然，小编觉得相比之下，开源社区是个更重视你做了什么事，而不是你说了什么的地方。但是，积极发言
非常挺重要。强烈建议要follow一些重要的feature jira和discussion，如果能提供一些有用的见解，
那是很加分的。

- 刷数据是有用的！道理上来说，评价一个contributor的贡献不仅看他关了多少个jira，而是他的整体贡
献，是个多维度的评价。但是，实际操作起来，其它东西不容易量化，PMC提名一个contributor的时候，最
常用的佐证就是他完成了多少jira。但凡事有个度，把一个小bug，再细分成多个子任务，还增加review负
担，就不太好了。

- 重点突破比广撒网来的有效。要有自己拿的出手的东西，最好是主导了某个feature，成为某个方面的
point of contact（POC），让别人一讲到这个feature，就能想起你。

- Review别人的代码也是另一个很重要的贡献。它说明你不仅能做好自己的工作，而且帮助社区里的其他人。
这点，大家普遍做得不太好，贡献代码的人远比review的人多，以至于积压了很多无法提交的代码。如果能在
大家做得不好的地方做好，影响可能会更大哦。

- 又譬如vote release，举手之劳的事情，但是经常连Committer和PMC都不积极反馈。检查一下checksum，
build一下code，跑一些job等等，然后给vote email上回个＋1，简简单单的事情，却反应你对社区事务
的关心。

- 要保持好和大家的良好关系，不但包括一个公司的，还有来自第三方的。到评选Committer或PMC的
时候，第三方的支持更有说服力。

- 最后，有机会的话要多参加meetup，conference或summit，最好能自己投稿，争取做presentation
的机会，让更多的人认识你和你的工作。

此外，小编也觉得在H家工作的机会给小编提供了很多有利资源：有问题能找到人问，可以拿到大feature，
代码有人帮忙及时review等等。所以，总体感觉是想要快速升级，就是要自己有效地努力工作加上利用上各种
资源。要是对Hadoop有兴趣的话，C家和H家是不错的选择。同样，对Spark有ambition的小伙伴也应该能在
Databricks找到最大的支持。

但是不在其中的小伙伴，也不用气馁，多花点心思，没有办不到的事儿。给点正能力，讲讲一个小编觉得
值得学习的案例。日本有个公司叫NTT，有点中国电信的感觉，它家有几个攻城狮来参与Hadoop社区，和其他
人给社区贡献代码不一样的是，他们专注给项目写文档。也许有小伙伴会觉得他们的活没啥技术含量，但是得
肯定这对一个正在普及的项目非常重要（开源项目的文档大家懂的＝。＝b）。所以，他们也顺理成章的被提
升了Committer，其中一个也已经是PMC了。现在很流行一个概念叫low hanging fruit，指的是很重要又
很容易做的事，documentation就是这么一个，他们抓住了机会。小伙伴们可要看准咯！

最后，小编想跑个题，讲讲GSOC，因为小编就是利用这个机会，迈进了Hadoop这个圈子的第一步。简单地讲，
GSOC就是Google付你工资（5000刀哦），让你在暑假里帮一个开源项目干活。小编强烈推荐这个项目，
尤其是对于不在国内或北美念书的童鞋（小编那时在狮城），找一个更好的暑期实习很不容易。好好准备自己的
proposal，认真写好项目的实施方案，和mentor搞好关系，还是非常有可能申请上的。如果，提前在社区里
发发言，甚至小修小补一些东西那就更好了。

![GSOC]({{ baseurl }}/img/2016-01-17-gsoc.jpg)

Hadoop社区的故事就先讲到这里了，还有一些零散的故事，apache模式和github模式的区别，某些大公司
对开源的态度,以后有机会再和大家说说。希望这两篇博文能给对Hadoop以及开源项目有兴趣的朋友们提供一
些参考。
