# SuperBitcoin
Infinitely scalable with minimalism while keeping Bitcoin decentralized and secure.
SuperBitcoin 协议 旨在 让 web3 分散割裂的独立共识区块链扩展技术方案 回归 到 以BTC 为核心且受 BTC 网络共享共识安全保障的多链系统，链与链之间通过闪电网络互联 的 价值（web3）网络。
做一个以 BTC为核心且受BTC共享共识安全保障的可无限扩展的 价值网络上来。 而 SuperBitcoin 协议 可以类比于 互联网的TCP/IP 协议，以 BTC为核心，闪电网络为 链路通信层，taproot concenus 协议为 扩展层， BEVM-stack 去致力于构建一键起 链且受BTC 网络共享安全共识保障的 多链（万链）层， 而在这之上是 应用层，即dapp层。 
从而聚集当下割裂的独立共识公链系统的区块链技术，完成重塑一个以 BTC共识为核心且去中心化的无限扩展BTC网络的价值互联网。


## 摘要
Bitcoin 终极目的是成为中本聪所描述的 去中心化的点对点 电子货币。
区块链技术 的发展 是为了 解决 Bitcoin 的无限扩展问题， 使得 Bitcoin 成为去中心化货币。
而因为 以前没有找到 在 Bitcoin 上 去中心化扩展的方案， 所以像 Ethereum 这些新智能合约 公链开始 在做自己的独立共识下自由发展探索区块链的发展。
诞生了大量的新 扩展技术，如 Polkadot/Cosmos 的同构链 扩展方案，如 Ethereum 的Layer2 拓展方案，再如 高性能公链 EOS/SUI 等等的前赴后继 提高单链的并发。 
现在 区跨链技术的 扩展架构 已经很成熟，像 L2的集中落地商业化就是一个事实证明。 而大家似乎忘记了 做区块链技术扩展开发的初衷： 去中心化扩展Bitcoin，让Bitcoin 成为去中心化电子货币。
而 BEVM开发团队 从2016年一直致力于 研究 创新： Bitcoin 的去中心化扩展方案。 通过 8年的努力奋斗， 终于提出了一个 完整的 Taproot Concensus 方案。 
Taproot Concensus 方案 保证 Bitcoin的去中心化和安全的前提下 可以对 Bitcoin 网络和共识进行无限的扩展。
其中 Taproot Concensus 方案融合了闪电网络状态通道、Bitcoin SPV 轻节点、 Taproot 升级带来的 Shnorr + Mast 合约技术， BFT POS， Substrate 等区块链技术 让Bitcoin 可以保持原生的去中心化网络进行无限的扩展。
而我们把这个可以无限扩展的延展网络叫： SuperBitcoin。


![image](https://github.com/user-attachments/assets/577b5cfc-2934-4e07-89c0-25943cfb9a1a)
## SuperBitcoin 架构
SuperBitcoin 是以 Bitcoin原生网络为内核，闪电网络为通信协议，Taproot Concensus 为闪电节点的放大层 组成的一个去中心化无限拓展的同构万链互联网络。
### 第一层： Bitcoin 网络： SuperBitcoin 内核层
最大且最去中心化的 BTC 原生网络，只能做 BTC的 transfer 功能，只能做基础的 opcode 。
### 第二层： 闪电网络： SuperBitcoin 通信层
通过闪电网络状态通道实现去中心化的 点对点的链接。
### 第三层： TaprootConcesus： SuperBitcoin 扩展层
融合了闪电网络状态通道、Bitcoin SPV 轻节点、 Taproot 升级带来的 Shnorr + Mast 合约技术， BFT POS， Substrate 等区块链技术 让Bitcoin 可以保持原生的去中心化网络进行无限的扩展。
BEVM 团队 借鉴 Polkadot 的同构万链互联方案， 把 闪电网络的每个节点可以升级为 基于 substrate/BEVM-stack 框架开发的 同构链， 从而形成以 Bitcoin 网络为核心的 同构万链互联系统，且去中心化的无限扩展。 
这样可以使得 Bitcoin 网络可以去中心化的 支持 WASM，EVM，Cario，SVM，MoveMV 等等一系列优秀的区块链扩展VM 平台。 真正做到了让所有的区块链技术融合且增强维护BTC的共识，而BTC的共享共识安全可以 通过各种创新的区块链技术去中心化的扩展开来。

#### TaprootConcensus Layer 层包含 3个子层
- 1， 闪电网络连接层
融合闪电网络状态通道到 TaprootConcensus 层
- 2， 闪电网络激励层 以及 万链调度分配层
 闪电网络 的激励 以及 基于TaprootConcensus 协议链接的 多链系统的协调调度分配。
- 3， 万链层的连接层
BEVM-stack 所做的 多链（万链）系统 接口提供

### 第4层： 万链互联层
通过集成了 Taproot Concensus 接口的BEVM-stack 开发 各种 VM 链，应用链等一键 去中心化和 Bitcoin 网络融为一体， 当下已经使用BEVM-stack 部署的链，如： Satchain，BEVM chain， ChainX。
以 Bitcoin 的共享安全 来保障所有基于 BEVM-stack 来开发的 链的安全。 BTC 为安全中心的共享安全。
我们把兼容TaprootConcensus协议接口的 链平台称为：***lightningchain*** , 基于 BEVM-stack 可以一键 部署 ***lightningchain*** 。 

### 第5层： 应用层
在SuperBitcoin 这个以BTC 为内核实现的万链互联系统生态的 上的任意 图灵完备 的VM 上 部署 Defi，Gamefi 等一系列应用，或者单独开发一条专有的应用链。 而这一切可以自动继承 BTC 的共识和安全保障。
![image](https://github.com/user-attachments/assets/f7f54ac2-1a6e-4129-91f2-bcea884e1492)





## Taproot Concensus

## 当前区块链技术方案的对比

### 案例1 Polkadot 的 万链互联 和 SuperBitcoin 的万链互联
-  都是共享共识安全， 但DOT 共享的共识是 DOT， 而 SuperBitcoin 共享的共识是 Bitcoin。 BTC的共识远大于DOT，所以 原则上 SueprBitcoin 架构的安全性 是 Polkadot 网络安全性 的 BTC市值/DOT 市值，当前约等于 1.3万亿/65亿 = 200 倍。即 SuperBitcoin 上的 lightning chain 比 polkadot 上的平行链安全200倍。
-  lightning chain VS parachain， SuperBitcoin 上是基于 BEVM-stack 一键发链的 lightning chain， 而polkadot 上是基于 substrate 一键发链的 parachain。
-  lightning channel VS XCMP， SuperBitcoin 是通过 lightning channel 作为 lightning chain 之间的通信协议， 而Polkadot 是通过XCMP 作为 parachain 之间的通信协议。
