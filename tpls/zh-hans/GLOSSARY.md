# 术语

### DEX
Decenralized EXchange的简称，即去中心化交易所。**路印交易所**是搭建在以太坊公有链上的去中心化交易所。

### 零知识证明。
一种证明者能够在不向验证者提供任何有用的信息的情况下，使验证者相信某个论断是正确的一种技术。

### 中继
路印交易所的后台系统，负责订单操作，交易撮合，零知识证明生成等。

### 链上请求
通过交易，在以太坊上发送给路印交易所智能合约的请求。

### 链下请求
通过路印中继的API，绕过以太坊区块链，直接发送给路印交易所的请求。

### 基础代币（Base Token）
指一个交易对的交易对象。如LRC-ETH市场对中，LRC即为该市场对的基础代币。

### 计价代币（Quote Token）
指一个交易对的定计价代币。如LRC-ETH市场对中，ETH即为该市场对的计价代币。

### Size
指订单的base Token数量。对于 2000 LRC 买 1 EHT的订单，size为2000。

### Volume
指订单的quote Token 数量。对于 2000 LRC 买 1 EHT的订单，Volume为1。

### EdDSA
路印协议用于对链下请求做签名的算法。路印交易所的链上请求需要用户使用以太坊地址对应的ECDSA私钥签名，而链下请求则需要使用交易账号的EdDSA私钥来签名。