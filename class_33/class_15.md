# 第十五课: 均仓策略并回测

均仓策略是网格策略的一种变种。它原理就是通过不断平衡现金和持有的资产使其动态平衡。

假设你现在有20,000美金，btc的价格是18，000美金。 你如果全部梭哈了，只能买到

20,000/18,000 = 1.11个btc(不计算手续费), 但是你可能担心买在高位，不买又怕继续涨
这时候，你可以半仓操作买10000美金的btc，留一办的现金

如果你的网格或者动态调整仓位的比例是5%,
那么如果下跌的5%的时候回加点仓位，涨5%的时候会减少仓位 一直循环操作。
这个就是动态网格。 

## 策略实现过程分析
1. 首先得知道你有多少本金，有多少币
2. 然后比较他们所持仓的价值，如果他们的价值超过一定的误差，我们就调整仓位

## howtrader里面的实现过程
1. 需要订阅我们的资产




## 均仓策略特点
1. 相比其他网格来说逻辑简单，算法也很简单.






