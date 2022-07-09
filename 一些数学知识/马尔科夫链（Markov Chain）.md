# 马尔科夫链（Markov Chain）

**马尔可夫链：将来的状态分布只取决于现在，跟过去无关！（无记忆性的）**

![preview](https://pic1.zhimg.com/v2-a37633055694cccb8532ebafc15b66d8_r.jpg)

![preview](https://pic2.zhimg.com/v2-6f323d3b7b9a48382541e59d77906871_r.jpg)

可以理解为Tn时刻的状态分布只与Tn-1时刻的状态分布有关。

## 1.离散时间的马尔科夫链

### （1）三个核心概念

离散时间的马尔科夫链有三个核心概念点：**离散时间**、**状态空间**、**转移概率**。

**状态空间：**我们通常使用***n***来表示时刻，用 ***Xn***来表示马尔科夫链在此时的状态，那么马尔科夫链所有的状态会构成一个如下的集合***S={1,...,m}*** ，这个集合 ***S*** 我们把他称作是这个离散时间马尔科夫链的状态空间。

**转移概率：**当离散时间的马尔科夫链当前的状态是 ***i*** 时，下一个状态等于 ***j*** 的概率就是转移概率，我们记作是![[公式]](https://www.zhihu.com/equation?tex=p_%7Bij%7D)。转移概率 ![[公式]](https://www.zhihu.com/equation?tex=p_%7Bij%7D) 本质上用一个条件概率就可以表达：![[公式]](https://www.zhihu.com/equation?tex=p_%7Bij%7D%3DP%28X_%7Bn%2B1%7D%3Dj%7CX_n%3Di%29%2Ci%2Cj%5Cin+S)

![img](https://pic3.zhimg.com/80/v2-a7fecb992179ce3d54d8dfb5a2e318ce_720w.jpg)

图中表明了三种状态，第一天的不同状态和第二天不同状态的概率。

