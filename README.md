## 第四期白帽黑客大赛

### 赛事规则说明

本期大赛规则与相关代码见[白帽黑客挑战赛 赛制与规则说明](https://shimo.im/doc/oYO9Qf5Gxx4tfhQb/)

### 合约分析

大赛涉及合约共有四个：`GamerVerifier `、`CommonWalletLibrary`、`oobserver`和`TimeDelayedVault`。

> GamerVerifier
> 该合约存有本次大赛所有组参赛选手的比赛账号地址，我们可通过在etherscan上查询这些地址的交易信息，得知所有选手的分组情况以及他们组比赛合约地址。`addGamer`函数允许选手向该合约中添加非比赛账号，不过需要破解magic的值。

