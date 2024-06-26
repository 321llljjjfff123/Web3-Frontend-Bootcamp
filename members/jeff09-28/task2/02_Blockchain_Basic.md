# Task2 Blockchain Basic

本任务分为简答题、分析题和选择题，以此为模板，在下方填写你的答案即可。

选择题，请在你选中的项目中，将 `[ ]` 改为 `[x]` 即可

## [单选题] 如果你莫名奇妙收到了一个 NFT，那么

- [ ] 天上掉米，我应该马上点开他的链接
- [x] 这可能是在对我进行诈骗！

## [单选题] 群里大哥给我发的网站，说能赚大米，我应该

- [ ] 赶紧冲啊，待会米被人抢了
- [x] 谨慎判断，不在不信任的网站链接钱包

## [单选题] 下列说法正确的是

- [x] 一个私钥对应一个地址
- [ ] 一个私钥对应多个地址
- [ ] 多个私钥对应一个地址
- [ ] 多个私钥对应多个地址

## [单选题] 下列哪个是以太坊虚拟机的简称

- [ ] CLR
- [x] EVM
- [ ] JVM

## [单选题] 以下哪个是以太坊上正确的地址格式？

- [ ] 1A4BHoT2sXFuHsyL6bnTcD1m6AP9C5uyT1
- [ ] TEEuMMSc6zPJD36gfjBAR2GmqT6Tu1Rcut
- [ ] 0x997fd71a4cf5d214009619808176b947aec122890a7fcee02e78e329596c94ba
- [x] 0xf39Fd6e51aad88F6F4ce6aB8827279cffFb92266

## [多选题] 有一天某个大哥说要按市场价的 80% 出油给你，有可能

- [x] 他在洗米
- [ ] 他良心发现
- [x] 要给我黒米
- [x] 给我下套呢

## [多选题] 以下哪些是以太坊的二层扩容方案？

- [ ] Lightning Network（闪电网络）
- [x] Optimsitic Rollup
- [x] Zk Rollup

## [简答题] 简述区块链的网络结构

```
区块链网络是由分布在全世界的各个节点相互连接组成的，每个节点都存储并相互广播数据，用户可以通过节点参与到区块链网络的交互；
结构：1、去中心化；2、对等网络（P2P）；3、共识机制；4、分布式；5、加密技术；6、可编程性。
```

## [简答题] 智能合约是什么，有何作用？

```
智能合约部署在链上运行在去区块链上的程序。
用来给用户调用，智能合约是自动执行的合约，条件满足时自动执行，减少消耗。
数据具有自动执行、透明化、不可篡改、节省成本、安全等优势。
```

## [简答题] 怎么理解大家常说的 `EVM` 这个词汇？

```
EVM 是 Ethereum Virtual Machine（以太坊虚拟机）的缩写，它是以太坊区块的核心组件，负责执行智能合约。
每个以太坊节点都运行EVM，所以，这个链上的所有智能合约都运行在这个虚拟机上并保持各个节点的一致性和安全性。
```

## [分析题] 你对去中心化的理解

```
去中心化，就是把资源或者权力打散分开，让其不再集中到一个中心，通过分布式方法分散到各个节点，每个节点都独立但又与所有节点相互链接；
这种设计可以提高信息透明度，也更加安全。
```

## [分析题] 比较区块链与传统数据库，你的看法？

```
1、数据的管理方面：
    传统数据库：中心化管理，数据的修改变动通过一个集中点广播出去
    区块链：去中心化分布式管理，数据的变动会在每个节点都获得广播并保持一致性变动
2、透明度和安全性
    传统数据库：只由服务器管理员掌握，生死全系一人之上；
    区块链：任何人都可以参看链上的数据，数据一旦确定，无法轻易修改
3、性能效率
    传统数据库：处理数据快，点对点传输
    区块链：眉笔交易都要经过验证，所有节点同步，效率低
4、应用场景  
    区块链：适合需要高度透明度和不可更改性的应用，如金融交易、供应链管理、身份验证等领域。
    传统数据库：适用于需要高效数据处理和管理的场景，如企业数据管理、在线交易处理等。
```

## 操作题

安装一个 WEB3 钱包，创建账户后与 [openbuild.xyz](https://openbuild.xyz/profile) 进行绑定，截图后文件命名为 `./bind-wallet.jpg`.
