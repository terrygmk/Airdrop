# zkSync空投交互

[toc]

- [zkSync空投交互](#zksync空投交互)
  - [1. zkSync1.0主网交互](#1-zksync10主网交互)
    - [1.1 官方桥充值](#11-官方桥充值)
    - [1.2 DEX 交易](#12-dex-交易)
    - [1.3 转账](#13-转账)
    - [1.4 跨链 Orbiter](#14-跨链-orbiter)
    - [1.5 mint NFT](#15-mint-NFT)
  - [2. zkSync2.0 测试网交互](#2-zksync20-测试网交互)
  - [3. crew3任务](#3-crew3任务)

## 1. zkSync1.0主网交互



### 1.1 官方桥充值

1. 进入官网 https://wallet.zksync.io/
2. 连接L1钱包
3. 充值ETH L1->L2 https://wallet.zksync.io/transaction/deposit gas=1u

### 1.2 DEX 交易

1. 进入 [Zigzag](https://trade.zigzag.exchange/?market=ETH-USDC&network=zksync)
2. ETH->USDC
3. USDC->USDT
4. USDT->ETH

### 1.3 转账

1. [进入这里](https://wallet.zksync.io/transaction/transfer?token=ETH) 向其它自己的小号转账


### 1.4 跨链 Orbiter

1. 进入 [Orbiter](https://www.orbiter.finance/?source=ZkSync)
2. zksync 转ETH 到以太坊 （费用 0.005ETH 多一些，如果跨其它链费用会比较少）
3. 从以太坊 转ETH 到zksync 

### 1.5 mint NFT

1. 上传图片到IPFS 进入 https://app.pinata.cloud/ 注册后上传一个图片，复制好CID
2. https://wallet.zksync.io/account/nft mint nft ，注意这里要签名俩次


## 2. zkSync2.0 测试网交互

1. 进入2.0测试网 https://portal.zksync.io/ ，系统可能会随机给你的地址发送一些erc20测试代币
2. 充值 https://portal.zksync.io/bridge 充值Goerli测试网的ETH 到zkSync2.0
3. 转账 https://portal.zksync.io/transfer 转ETH，DAI，USDC 
4. 提取 https://portal.zksync.io/bridge/withdraw 将ETH 或其它ERC20提取到 Goerli测试网




## 3. crew3任务

1. https://zksync.crew3.xyz/ 完成一些问答任务
2. 每周五都有zkSync Weekly Rollup，会发poap，注意参加一下。
