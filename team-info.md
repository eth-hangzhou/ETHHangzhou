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

# Artemis

**1 项目名称**: Artemis (trading tg bot)

**2 所选赛道**: Public Goods

**3 项目图片**:

![Artemis](https://cdn.discordapp.com/attachments/1111544309859237908/1162945239267426304/latest.png?ex=653dc827&is=652b5327&hm=96a0842deb58676ac36bf99bd708d8b645e06397c96a8b685ab52b617b1fd965&)

**4 简介**: 

链上有很多像pepe这样的alpha机会，但也是一个门槛较高，且充满危险的黑暗森林（比如貔貅盘、三明治攻击）。  

tg bot是一种有趣的尝试，融合了交易与钱包，让用户在telegram中就能便捷地去参与链上交易。  
但目前出现的tg bot们有极大的风险：项目方会将用户私钥上传到服务器，并可以直接接触和操作私钥。换言之，项目方随时可以卷走用户的所有资产。  

Artemis希望在坚持“**私钥完全本地存储、且只由用户掌握**”的前提下，同样实现限价单等复杂交易场景。  

此外，Artemis选择了用有**用户界面的telegram web app**来实现tg bot，而非是传统的消息对话式交互，让交易操作更直观、易用。  

总之，Artemis是一个**安全、易用的trading tg bot**，让更多用户可以安全、轻松地进行链上交易，为massive adaption降低门槛。  

**5 队长和队员**: 

队长: [@potatooo](https://github.com/llgoody)   队友：[@jack](https://github.com/jack23615)    [@baiyang](https://github.com/baiyang1994)    [@zys](https://github.com/zhangyongshuai123)

**6 本项目在这次黑客松的目标:**

1. 通过telegram web app实现有用户界面的tg bot（参考telegram bot官方文档）。
2. 实现tg bot内的私钥加密、签名及本地存储（参考Metamask开源代码）。
3. 实现ETH对ERC20 Token的市价、限价买卖。
   1. 使用uniswap v2的流动性。
   2. 限价买卖方案基于permit2实现，无需用户提供私钥。

**7 黑客松前两日的进度**  

- Day 0:
  - [x] 完成组队，GitHub org&repo 的新建：https://github.com/orgs/amazingtgbot/repositories
  - [x] 细化方案&任务分工：
    1. potatooo 负责交互及界面设计。
    2. zys 负责搭建telegram web app，实现前端交互及界面。
    3. zys+baiyang 负责tg bot内的私钥加密、签名及本地存储。
    4. jack 负责市价买卖的合约交互，包括anti-MEV。
    5. jack 负责限价单合约的实现及交互。
    6. baiyang 负责限价单监听服务的搭建。
    7. 提供token合约的安全信息（goplus API接入）。
    8. 其他细节优化。主要包括智能滑点、gas设置等。
- Day 1:
  - [x] 完成任务1.
  - [x] 完成任务3、4的主要部分，跑通无界面的市价交易流程。
- Day 2:
  - [x] 完成所有开发。
  - [x] 完成联调。
  - [x] 完成 team info 以及视频录制等。
  
**8 视频链接:**  

https://youtu.be/nrTygAL2O3c

**9 项目 github repo 链接:**  

所有代码都在  

https://github.com/amazingtgbot/tradingbot

**10 是否基于之前的项目:**  

该项目是本次hackathon期间，从0到1开发的项目，完全原创。

**11 项目 Demo 链接（选填）:**  

@zys_1366_bot   （telegram搜这个bot。部署在goerli测试网。）

----
