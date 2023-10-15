# ETH Hangzhou Hackathon 项目提交说明

ETH Hangzhou Hackathon 的项目需要提交到本页，PR（Pull-Request）截止时间为 2023年10月16日 下午14:00（北京时间，UTC+8）。你需要在你的项目下更新以下内容:
1. 项目名称
2. 所选赛道（Public Goods，Layer2 Application，Zero Knowledge 主赛道三选一）
3. 项目图片（1张有代表性的图片，不要过长）
4. 简介
5. 队长和队员
6. 本项目在这次黑客松的目标
7. 黑客松前两日的进度
8. Demo 视频链接（可以是录屏或其他形式），可以选择的视频平台：[Youtube](https://youtube.com)，[Bilibili](https://bilibili.com)，[Loom](https://www.loom.com/)，视频长度不能超过3分钟，否则扣分。
9. 项目 github repo 链接
10. 声明未基于之前的项目, 如: 该项目是本次hackathon期间，从0到1开发的项目，完全原创。
11. 项目 Demo 链接（选填）

在截止时间前提交 PR，且包含前 10 项信息的项目，视为提交成功，否则不参与评奖。

评委将在2023年10月16日下午14-18点期间，根据以下4个维度对项目进行第一轮打分，每个赛道的前5名可以参加晚上19点的Demo Day：
1. 代码 🧱
2. 创新性 💡
3. Demo完整度 📝
4. 对以太坊生态的重要性 ♻️

进入Demo Day的每个项目有 5 分钟展示时间。


# SPARKY

**1 项目名称**: SPARKY

**2 所选赛道**: Public Goods

**3 项目图片**:

![Sparky](https://lh3.googleusercontent.com/pw/ADCreHcihYH4cTmkf0QgdSXmOmv_kSC4injIezePovbaUZ6HKAxkPKos9NR3mHbSqlmgQ9iYuWywOCq8CAkt1tCTJkdCU7CDdLHGKgabEQ9SK92ltj_rlRKrU8_IhotXL309nOiwwvOY_7Krg-c79FNccXs=w1080-h810-s-no?authuser=0)

**4 简介**: 

Sparky是一个可信的链上交易工具，它通过引入账户抽象模型来解决同类工具因私钥托管带来的安全性问题。Sparky为用户提供链上私有交易，限价单交易，跟单抢跑等功能，同时享有Gas-Free，操作优化等账户抽象所带来的特性。在实现过程中，针对跟单抢跑这类场景下无法对`UserOperation`中 `CALLDATA`进行预定义和预编码的问题，Sparky通过中继账户代理用户完成交易，再基于zk proof证明代理交易的合法性，最终完成和用户钱包进行结算。

**5 队长和队员**: 

队长: [@aolin.eth](https://github.com/aolin118) 队友：[@Bin.W](https://github.com/binwang-neu)    [@markdai754](https://github.com/markdai754)

**6 本项目在这次黑客松的目标:**

目标：

> 由于时间限制，本次黑客松期间Sparky仅实现简介中的前半部分功能，即完成可预定义的UserOperation的交易服务，它包含：在web中允许用户创建和管理智能合约账户，并基于智能合约账户提供基础交易，私有交易，限价交易功能。

分为以下几个子任务：

1. 完成EIP-4337 compatible & 可升级的UUPS账户合约，并在账户合约中实现基于EIP-712结构体签名的`_validateSignature`函数；实现一个可以替Bot支付Gas费用的Paymaster合约，并且完成对@infinitism EntryPoint合约的支持和联调。

2. 前端完成对抽象账户的支持，可以在页面创建和管理智能合约账户，并且可以构造调用UniswapV3 Router的`UserOperation`和结构体签名。

3. relayer服务端完成BOT交易服务和链上价格监控服务

**7 黑客松前两日的进度**

- Day 0:
  - [x] 完成组队，GitHub org&repo 的新建：https://github.com/orgs/Sparky-Technology/repositories
  - [x] 开发任务：
    1. 确定功能规划和接口命名。
    2. 确定智能合约，前端以及relayer服务基本框架和实现路径。
    3. 账户抽象合约实现UUPS账户，并成功联调EntryPoint合约与SparkyAccountFactory合约。
    4. 前端完成静态页面的开发，并实现抽象账户的创建和资产管理（即对转账`UserOperation`的封装）
    5. 后端开始私有交易以及链上价格轮询的服务开发。
- Day 1:
  - [x] 开发任务：
    1. 智能合约完成抽象账户对EIP712的结构体签名和基础Paymaster合约，并fork了sepolia测试网数据到本地完成单元测试。
    1. 前端完成对调用UniswapV3 Router的`UserOperation`封装，并实现了价格查询和消息弹窗等辅助功能。
    1. relayer服务完成对EntryPoint合约的联调，接口实现基于`UserOperation`进行模拟执行和执行上链的流程。
  - [x] 其他任务：
    1. 完成视频录制
    2. 编写PR
  

**8 视频链接:**



**9 项目 github repo 链接:**
    https://github.com/orgs/Sparky-Technology/repositories
**10 是否基于之前的项目:**
    该项目是本次hackathon期间，从0到1开发的项目，完全原创。
**11 项目 Demo 链接（选填）:**

