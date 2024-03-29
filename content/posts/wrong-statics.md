---
title: "一个经典的数据统计问题"
date: 2021-03-16T11:36:13+08:00
draft: false
tags: ['数据统计','足球']
categories: ['数据统计']
---

最近，在看足球社区的一个讨论时，看到一个有些让人意外的数字，稍微分析后，立刻意识到这是一个经典的统计问题。

数据统计有太多可被动手脚的地方，尤其是在足球数据统计领域，可偏偏却是社区内「黑粉大战」常常引以为豪的一种武器。

![image-20210316114043909](https://tva1.sinaimg.cn/large/e6c9d24egy1gollhfm21fj20b40enwht.jpg)

### 数据的背景

在此前的一场比赛中，阿森纳2-1战胜了热刺。比赛中，热刺被罚下一名球员，而且被判罚了一粒点球，因此，比赛结束后，热刺主教练穆里尼奥质疑主裁判的公正性。

回帖的阿森纳球迷则拿出了这个数据来证明：迈克尔- 奥利弗这名裁判不可能是阿森纳球迷，因为他执法的比赛，阿森纳胜率只有26%。

如果是一名普通的球迷，很可能就会认可这个结论。从图上也能看出，有130人都为这个数字送上了「点亮」，表示赞同。

毕竟，作为一名执法公正的主裁判，阿森纳不可能只有26%的胜率。

但是，如果你是对英超非常熟悉的球迷，可能已经意识到是哪里出了问题。

### 数据没告诉你的

当你把注意力放在26%这个数字上时，其实应该回头来仔细看看迈克尔-奥利弗这名裁判。

迈克尔-奥利弗（Michael Oliver），出生于1985年2月，今年只有36岁，是一名非常年轻的裁判。更了不起的是，他从2010年起就开始执法英超的比赛，那时他仅仅只有25岁而已。

自出道以来，他已经执法过英格兰国内各种杯赛决赛，包括2018年足总杯决赛。在欧洲，他也执法过欧冠八强战皇马vs尤文图斯的比赛。

问题就出在这里：作为一名英足总力捧的年轻裁判，奥利弗执法的大多是强强对话，也就是豪门与豪门的对决，而近几年，阿森纳对英超其他强队的战绩处于下风，因此26%的胜率是完全可以理解的数字。

### 主裁判的执法记录

为了验证以上说法是否正确，我找到了迈克尔-奥利弗执法阿森纳比赛的记录：

| 对手         | 场次 | 胜场 | 负场 | 平场 |
| ------------ | ---- | ---- | ---- | ---- |
| 热刺         | 6    | 2    | 2    | 2    |
| 切尔西       | 4    | 2    | 0    | 2    |
| 曼联         | 2    | 0    | 1    | 1    |
| 利物浦       | 5    | 0    | 3    | 2    |
| 曼城         | 2    | 0    | 2    | 0    |
| 埃弗顿       | 2    | 1    | 0    | 1    |
| 水晶宫       | 2    | 1    | 1    | 0    |
| 狼队         | 3    | 1    | 1    | 1    |
| 莱斯特城     | 1    | 0    | 1    | 0    |
| 西布朗       | 2    | 1    | 1    | 0    |
| 西汉姆       | 1    | 1    | 0    | 0    |
| 哈德斯菲尔德 | 1    | 1    | 0    | 0    |
| 伯恩茅斯     | 1    | 0    | 0    | 1    |
| 斯旺西       | 1    | 0    | 1    | 0    |
| 维拉         | 1    | 0    | 1    | 0    |
| 合计         | 34   | 10   | 14   | 10   |

从执法记录能看出以下几个结论：

- 强强对话居多，与TOP6当中的其他五强交手场次占了19场；
- 伯恩茅斯、维拉等对手主要出现在迈克尔-奥利弗执法英超比赛的前2个赛季；
- 阿森纳的胜率 10/34 = 29.41%，要比截图说的略高一些

虽然实际胜率要比截图的同学说的略高一些，但也偏低。但不管怎么样，它都不能说明裁判的倾向性。

要想说明裁判的倾向性，最合理的还是应当就具体的判罚做出讨论，并且证明这位裁判是一贯如此做出不利于阿森纳的判罚。

### 结论

胜率这个数字妙在有很强的引导性，让人对裁判的中立性产生怀疑，让人很容易忽略胜率巧妙地隐藏了比赛对手这个事实。

在产品数据当中，也存在数不胜数的类似数据，《人人都是产品经理》的作者苏杰将一些常见的类似数据称为“虚荣性指标”，就是指无法真实反馈业务情况，只是看起来美好的数字变化。

在最后，引用《学会提问》一书中，对于统计数据的一些建议，引以为戒。

> 评估数据的一些线索：
>
> 1. 尽量找出数据是如何获得的相关信息，越多越好。问一下：“这位作者或演说者是怎么知道的？”立论者想要用大量的数字来让你动心或者让你惊心的时候你尤其要警惕。
> 2. 要对描述的平均值的类型感到好奇，分析一下知道事件的数值全距和分布情况是不是会对数据多了一个有用的视角。
> 3. 数据使用者拿一件事的结论来证明另一件事时你要特别当心。
> 4. 先不去看作者或演说者使用的数据，把所需的统计数字证据和实际提供的数据作比较。
> 5. 从数据中得出你自己的结论。如果这结论和作者或说话者的结论不一致，那么很可能其中有什么地方出错了。
> 6. 判断缺少了什么信息。对于误导的数字和百分比，以及缺少的比较你要特别当心。

