---
layout: post
title: “我不想把一生奉献给计算机”
description: 我只想说，任何一门科学都有她存在的价值。都有冠上明珠等着勇敢的人去摘取。我没有想过把一生奉献给任何事情，我只想过，我要把当下奉献给热爱的。
category: blog
---

WTF. 这是我学生跟我说的。这是怎么了？

高考结束后，我志愿里写过几个专业：

* 西北工业大学－飞行器设计与工程
* 华南农业大学－农学

很奇葩吗？我来说说为什么要做这些：

* 妈蛋现在的水果太难吃了。草莓没有草莓味，苹果吃起来像洗锅水；青菜硬邦邦一点都没有动感。我觉得水果就是大自然的恩赐，不应该是那样无味的。
* WX造飞机打倒侵略者啊。其实我是看了航空发动机之父－吴大观老先生的自传《我的中国心》过的高三，那时每天熄灯以后，我给宿舍的同学读文章，读着文字，感受到书里淳朴的情怀。 我曾经离这个梦想很近，模拟考也一次比一次好。我觉得我就要去西北了，要跟我的朋友们道别了；但高考那次不很理想，所以没能去。我也报了哈工大，那年HIT的录取分数出奇的低，我能上，可是因为没敢把HIT的写在第一个，所以最后来了华师学数学。
但我从不后悔，甚至，我感谢这个安排。


##生活就像海洋

最近一周，我又有高考前的那种感觉：每天晚上给喜欢的女孩发信息道晚安，然后心里默念着：“生活就像海洋，只有意志坚强的人才能到达彼岸。”

我记得，当时和另外一个同学一同早起，然后出宿舍门时大喊“生活就像海洋，我每天6点起床”。把他们都叫醒的感觉真有意思。

妹子决定考研，我支持她。便不时买零食，然后坐地铁、转车拿给她。那个家伙就像小孩一样，拿到东西以后就不管我了；我说拿回宿舍给同学一起吃嘛，她都快哭了，不要。昨天她对我说，宿舍一个同学去另一个城市实习了，她临走前流了眼泪。但只有我妹子看到了。
我们都感受到，那种被时间的潮水推上岸的感觉。而这一大批人，有的穿了衣服，自信满满；有的发现自己在裸泳，惊慌失措。

##我的第一次面试

上周四去深圳B家面试NLP部的实习生了。我的第一面啊，我紧张得拉肚子了。还好面试官很nice，第一部分结束后我渐渐进入状态了。可惜，第一部分是写代码，我听到他连声叹息...Oh不..

	一对一面的，大概一个半小时。三部分的内容：写代码、聊做过的项目、提一些实际的机器学习问题。
	第一部分砸了，面试官出了两道题。一个是希望我用数据结构，可是我当时虽然想到了用map，
	但是不熟用法，就一直憋着。到后面他教我怎样用以后我才写出来了，不过也写的不好。>< 
	我的经验是，下次先把东西写出来再算。管他好坏，再慢慢改进。
	第二个是对两个排序好了的数组找中位数，先是O(nlogn)、然后说再快一点我就想到O(n)，
	然后问还有没有，我一时间想不到，他最后解释了怎样做到O(logN)
	
	第二部分聊项目。问我社会网络分析里面，大家一般怎样衡量节点影响力啊？
	我就说xxx..然后说了prof.周涛的论文里面是怎样做的。他说嗯有道理的。
	然后又问情感分析你们怎么做的啊？我就说搞一个RB-tree，然后衡量节点间的距离作为语义的相似度。
	他说明白。还给了我一些建议，提到了click model，因为我问了他我搞不懂的事情。
	
	第三是机器学习的题目啦。也是两题，一个是linear regression与logistic的区别，哪个好些？我这个说的不是很清楚。第二个是文本分类，说如何把新闻标题做成二分类？我就参照anti-spam里面的例子说了一下，还笑着问他有没有无监督的方法？他哈哈说这个很难的啦。应该没有。然后看到我简历里面写了mini-batch，就说：啊你还知道mini-batch啊，说说。我就解释了一下，不过有一个小点我忘了。
	最后他就说嗯你算法懂的挺多的，不过代码怎么写不好呢？是不是有点紧张。我当时一直还在发蒙的状态...
	
最后握手道别。留我一人等了一周，还没有消息。做梦都梦到自己被rejected了。

##嗯，我该正常干活了

我想起老师问过我的一个问题，“如果你这次没能选上，你会怎么样？”。我说：“我还有事要做，我要把手头上的事情做好。”

我说的事情是什么呢？嗯...是我答应各位知友的：[大二的学生想从事科学研究工作，但是感觉理论知识不够，同龄人都是怎么做到的？][6]


跟大家说一下我们做了的，以及想做的事情吧：
* 用户回答与评论的情感分析。我们也在思考社区该如何运营，如何保护我们的用户不受到莫名的攻击；所以我们先对帖子内容和对应的评论做情感分析，建立了6个情感类，并计算每个帖子中的情感值分布。

![1](/images/pursue-your-dream-with-whole-life/1.png)
![2](/images/pursue-your-dream-with-whole-life/2.png)
![3](/images/pursue-your-dream-with-whole-life/3.png)
![4](/images/pursue-your-dream-with-whole-life/4.png)
![5](/images/pursue-your-dream-with-whole-life/5.png)
![6](/images/pursue-your-dream-with-whole-life/6.png)
![7](/images/pursue-your-dream-with-whole-life/7.png)
![8](/images/pursue-your-dream-with-whole-life/8.png)
![9](/images/pursue-your-dream-with-whole-life/9.png)
![10](/images/pursue-your-dream-with-whole-life/10.png)


我们希望通过呈现“帖子情感分布－用户活跃度”，向大家说明可能影响用户的原因。不过，现在还没出活跃度的结果。初步是打算周活跃度（每周出现3次活动）则为活跃，或是其回答的频率，或是给一个numerical的结果。

* [知乎会出现盲目赞同名人现象吗？][3]

![11](/images/pursue-your-dream-with-whole-life/11.png)

从上面的点赞网络来看。相当部分用户都只投出1票，我想知道，随着时间变化。得票数的变化是怎么样的？也就是说，第一名是否有位置优势？也就是说，大家会更多地看第一名的答案。 另外，下面这个有向图我是以信息传播的角度画的，即我想知道：这个问题是通过谁出现在我们的时间线上的？从图上看，如果没有jin-chen-yu，会少掉很多流量（jin-chen-yu并非回答者）；

![12](/images/pursue-your-dream-with-whole-life/12.png)

所以大家知道么？如果这些用户都不玩了，我们会少掉很多信息源。回到我们想要探讨的问题，这里有一个：只通过时间线看内容的用户有多少？如果人们只看自己时间线上的内容，某种程度上便是盲从。可是，我目前没有想到好的方法可以估计这个问题。不过，我有看到zhihu在收集数据（大家可以打开浏览器的监控，然后进入页面后往下滚动，你会看到有信号发送到zhihu的服务器里）

**我最想做的。是用社会网络分析和自然语言处理做一个寻人系统。在知乎上，找到你事业的帮手，发现你人生的导师，找到与你志趣相投的同龄人。**

[http://www.youtube.com/watch?v=hyT2ERp7zQs][4]

**其实这件事情已经有人在做了对不对？** 上面的视频是LinkedIn的Principle Researcher做的keynote



##大家可能会问，我为什么要去实习？

其实，这个项目做得收获虽然很多。但很累，我不太会跟队友合作；有一些想法，都是我自己在YY，所以我们为了按时完成这个东西。就不得不分开两部分，一些是可以做的出来的，能交差的。其他的，就看大家的兴趣了。

不过，越到后面，大家都在找工作，申请学校。没太多时间精力跟我一起讨论，是我不好，把事情拖太久。之所以去实习，是希望有人可以指导我，一个人找资料，在互联网上瞎晃的感觉挺孤独。

[@吴俣][5] 说为什么不投MSRA。我还是有点没底，我会快一点准备的。毕竟现在的东西都很水，面完B家以后觉得自己不会写代码了。其实我很想找到面试官，跟他说，我不懂开发，可是我会写代码！

我想谢谢我的导师，他鼓励我，给我足够的空间发挥创意。老师还关心我面试的事情。其实从言语中，还能看到老师在为我的冒险担忧：
   有一天晚上下课，和老师一起走在校道上。老师说，“你看啊，选题挺重要的。有时候选题好，就能做到很多看得到的东西。虽然你现在通过这个东西学了不少东西，也比别的同学优秀，但你还是要考虑一下以后就业的事情啊。对了，你申请的事情怎么样？”

...

   “要不你去深圳那家公司实习吧？他们做的事情挺有意思的，而且你懂一些相关的东西，他们可能会让你做跟别的实习生不一样的工作。而且他们在招人呐~”

我没有说话。我知道，老师在担心我如果没法去读PhD，要怎么办；所以他还给我介绍了一些工作机会。我不觉得这些想法都是虚无缥缈，我反倒觉得这些事情都是可以让人们的生活更好的事情，是可以让社区更好的事情；而且，技术上的困难，并不代表做不到啊。


##“我不想把一生奉献给计算机”

我只想说，任何一门科学都有她存在的价值。都有冠上明珠等着勇敢的人去摘取。我没有想过把一生奉献给任何事情，我只想过，我要把当下奉献给热爱的。





[zihaolucky]:    http://zihaolucky.github.io  "zihaolucky"
[1]:    {{ page.url}}  ({{ page.title }})
[2]: http://www.zhihu.com/question/22002224/answer/20080481
[3]: http://www.zhihu.com/question/20750977/answer/16070780
[4]: http://pan.baidu.com/s/1dDrGMEt
[5]: http://www.zhihu.com/people/wu-yu-52gc