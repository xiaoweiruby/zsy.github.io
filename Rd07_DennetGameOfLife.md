#Rd07_DennetGameOfLife

```
本文感谢 阳志平老师推荐书籍
同时感谢 永澄、大雨 给予启发
2017年09月16日15:01:12
```

稀罕的是，背景完全不同的两位人物，在捍卫各自优先级别后，却对 **某一些规则保持一致**。这些规则包括，重视抗风险、重视非线性机会、重视日常积累、且都对金钱薪金没有比较心态。千变万化的选择中，却隐约遵循相同法则。这让我想起了，丹尼特的一则计算机哲学实验——生命游戏。


### 原文

> 以下摘自「丹尼特的自然主义认知哲学」第35页

生命游戏（Game of Life）是英国数学家康威John Conway发明的细胞自动机。游戏发生在一个二维坐标方格内，每一个方格都代表一个或”生“或”死“的细胞，所有细胞构成一个”生命世界“。

游戏参与者只需要设定每个细胞的初始状态（第0代细胞状态），之后细胞便开始遵循以下三条生命规则自动演化。

1. 有2个活邻居的细胞保持当前状态至下一代（当前状态为”生“则下一代仍为”生“；当前状态为”死“则下一代扔为”死“）；
2. 有3个活邻居的细胞在下一代为”生“（无论当前状态如何）；
3. 在其他情况下，该细胞下一代为”死“。

生命游戏已经在计算机上得以实现。...生命世界是一个不折不扣的决定论世界，这里不存在任何意外。

尽管生命游戏的规则相当简单，但它能够产生的效果却大大出乎人们的预料。下图1代表某一次设定下的，第0代细胞。（黑格代表活细胞，白格代表死细胞）。

`图1`
![1](https://user-images.githubusercontent.com/19412465/30510311-584ae6d0-9af4-11e7-87a1-96cc2a8d8293.JPG)

该状态下只有5个活细胞，但它的演化过程却相当有趣。（见图2）

`图2`

![2](https://user-images.githubusercontent.com/19412465/30510313-5a8bd44a-9af4-11e7-817e-62c4677fce24.JPG)

第4代活细胞的分布与第0代完全一致，只是整体位置向东南方向移动了一格，同样第5、6、7代活细胞分布也与第1、2、3代相同，但整体位置向东南移动。由此可见，该初始状态的演化过程呈现出明显的规律性：它只有四种形态，这四种形态一词出现，形成一个周期。

丹尼特指出，在生命世界里，我们可以通过
1. 运用规则逐一计算每个细胞的下一代的状态
2. 借助细胞结构变化规律来进行预测

- 第1种运用规则计算，代表我们对生命世界采取”物理立场（the physical stance）“策略，因为我们完全是根据细胞的物理状态和生命世界里的物理规则来进行预测的。在此策略下，我们只能看到生与死的细胞。

- 第2种借助结构变化预测，代表我们采用了”设计立场“(the design stance)策略，借助结构或功能属性来进行预测。这时我们看到的不再是生于死的细胞，而是细胞演化的”模式“。

### 感悟

记录每个细胞生死状态的工作量是巨大而繁重的
如果能简化记录过程
而采用模式预测结果
也许能节省更多精力在体验生死本身

比如用最小成本记录运动情况
而更多精力放在创造舒适的运动环境上

再比如用最简单方式做保值
比如购买黄金美元
而更多精力放在阅读和陪伴家人的节奏上（此条为大雨提供）

### GameOfLife维基
[Conway's Game of Life - Wikipedia](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life)