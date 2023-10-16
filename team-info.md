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


# iStone

**1 项目名称**: iStone

**2 所选赛道**: Social

**3 项目图片**:

等待补充

<!-- ![foundry](https://book.getfoundry.sh/images/foundry-banner.png) -->

**4 简介**:

iStone 是一个基于区块链的跨链交流聚合协议，解决不同网络的信息孤岛问题！通过 iStone 你可以使用自己喜欢的公链永久记录你的作品；其他人也可以使用他们喜欢的公链对你的信息进行点评和互动。虽然我们使用不同的公链（Bitcoin network/Ethereum network/BSC/Optimism/Arbitrum/Solana/Sui ...），但这并影响我们在一起愉快的交流。

iStone 有委托发布功能

- 你可以授权指定地址作为代理发布人，由他代表你发表媒体信息。（类似 ERC20 的授权转账）
- 你可以通过支付报酬和签名给代发服务。由代发服务帮助你发布。（类似 离线签名 + 广播交易）
- 你可以通过支付报酬和签名给代发不误。发表至其他网络。
  - 比如你在 ETH 网络 支付 USDT 和签名，将内容发布到 Bitcoin 网络。

**5 队长和队员**:

队长: [@Anban Chu](https://github.com/anbang) （独自完成设计，前端，后端，合约的开发）

**6 本项目在这次黑客松的目标:**

目标：完成基于 EVM 网络的跨链交流。完成委托发布功能。

**7 黑客松进度**

- Day 1:
  - 完成仓库搭建新建：
    - 前端: https://github.com/anbang/frontend-istone
    - 后端: https://github.com/anbang/backend-istone
    - 合约: https://github.com/anbang/contract-istone
  - 细化任务：
    1. 合约: 需要保证设计和代码完成。
       1. 单元测试完成核心逻辑可以。
       2. 覆盖测试，覆盖核心即可。
    2. 前端: 完成架构搭建，钱包连接，核心静态页面。
    3. 后端: 完成架构搭建，表结构完成，API 的结构定义。
- Day 2:
  - 合约: 完成最初版本。
  - 前端: 核心交互功能。
  - 后端: 完成核心功能。
- Day3:
  - 整体连调
  - 买域名作为演示和后端 API
  - 买服务器运行服务
  - 为演示坐最终准备

**8 视频链接:** 无

**9 项目 github repo 链接:**

- 前端: https://github.com/anbang/frontend-istone
- 后端: https://github.com/anbang/backend-istone
- 合约: https://github.com/anbang/contract-istone

**10 是否基于之前的项目:**

该项目是本次 hackathon 期间，从 0 到 1 开发的项目，完全原创。

**11 项目 Demo 链接（选填）:**

https://github.com/0xevm/iStone_demo#iStone-demo----
