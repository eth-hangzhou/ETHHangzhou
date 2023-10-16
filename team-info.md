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

❗❗❗项目提交PR示例详见：https://github.com/eth-hangzhou/ETHHangzhou/pull/6



# MOD 6551

**1 项目名称**: MOD 6551

**2 所选赛道**: Public Goods

**3 项目图片**:


**4 简介**: 

ERC6551 是一个让人兴奋的协议，它让任何 NFT 可以作为一个钱包。从钱包的角度讲，我们终于可以有一个固定的钱包地址，并且私钥则可以经常更新，以保证资产安全。

但是，6551 和 AA 一样，需要每个用户部署一个合约，带来两个问题 1. 用户需要支付昂贵的 gas 2. 链上状态爆炸。
我们正在设计建设的以太坊兼容 L1 BitPoW 公链的重要目标，确实可以在不牺牲安全和去中心化的条件下，把 gas 降低到几乎为0，同时，我们也必须抑制状态爆炸！因为节点的膨胀会导致区块链的中心化。
所以我们选择魔改 ERC6551 来实现我们的目标，在新的 L1 和大量 L2 上，我们完全有条件部署升级版本的 ERC20，避免每个用户部署一个新的智能合约。

**5 队长和队员**: 

队长: [KJ](https://github.com/kernel1983)

**6 本项目在这次黑客松的目标:**

目标：
1. 修改 ERC20 数据结构，能够使 balances 和 allowed 能够支持 tokenid。
    ```solidity
    mapping (address => mapping (uint256 => uint256)) public balances;
    mapping (address => mapping (uint256 => mapping (address => mapping (uint256 => uint256)))) public allowed;
    ```

2. 本地快速合约测试脚本，用于测试驱动开发。

    https://github.com/kernel1983/mod6551/blob/main/scripts/mod6551.py
    ```bash
    brownie run mod6551 --network hardhat
    ```

   

**7 黑客松前两日的进度**
- Day 0:
  - [x] 确定项目和目标 GitHub repo 的新建：https://github.com/kernel1983/
  - [x] 细化任务：
    1. 修改 ERC20 数据结构。
    2. 修改 ERC20 transfer 方法，以及快速测试脚本。
    3. 修改 ERC721，增加erc20_transfer方法。
    4. 修改 ERC20 approve 方法和 transferFrom 方法。
    5. Option，创建一个UI。
  - [x] 查看 foundry 文档，以及源码，确定修改路径。
- Day 1:
  - [x] 完成任务 1-3。
  修改数据结构比较顺利，在修改 transfer 方法的时候，使用 brownie 调试代码比较烧脑，为了增加效率引入了快速测试脚本。
- Day 2:
  - [x] 完成任务 4。
  - [ ] 开始任务 5 快速学习 CSS 框架。
  因为 solidity 代码我们之后也要用 python 再做一遍，但是构建的 UI 前端未来可以复用，所哟我们佛系的开发了 UI。
- Day 3:
  - [x] 完成 team info。
  - [ ] 持续完善任务 5。

**8 视频链接:**


**9 项目 github repo 链接:**
所有代码都在
https://github.com/kernel1983/mod6551

**10 是否基于之前的项目:**
该项目是本次hackathon期间，从0到1开发的项目，完全原创。
本项目服务以太坊生态，同时也用于我们的新公链 L1 BitPoW。

**24.11 项目 Demo 链接（选填）:**
https://bitpow.org/mod6551.html
