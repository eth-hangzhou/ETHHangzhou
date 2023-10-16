# ETH Hangzhou Hackathon 项目提交说明

ETH Hangzhou Hackathon 的项目需要提交到本页，PR（Pull-Request）截止时间为 2023 年 10 月 16 日 下午 14:00（北京时间，UTC+8）。你需要在你的项目下更新以下内容:

1. 项目名称
2. 所选赛道（Public Goods，Layer2 Application，Zero Knowledge 主赛道三选一）
3. 项目图片（1 张有代表性的图片，不要过长）
4. 简介
5. 队长和队员
6. 本项目在这次黑客松的目标
7. 黑客松前两日的进度
8. Demo 视频链接（可以是录屏或其他形式），可以选择的视频平台：[Youtube](https://youtube.com)，[Bilibili](https://bilibili.com)，[Loom](https://www.loom.com/)，视频长度不能超过 3 分钟，否则扣分。
9. 项目 github repo 链接
10. 声明未基于之前的项目, 如: 该项目是本次 hackathon 期间，从 0 到 1 开发的项目，完全原创。
11. 项目 Demo 链接（选填）

在截止时间前提交 PR，且包含前 10 项信息的项目，视为提交成功，否则不参与评奖。

评委将在 2023 年 10 月 16 日下午 14-18 点期间，根据以下 4 个维度对项目进行第一轮打分，每个赛道的前 5 名可以参加晚上 19 点的 Demo Day：

1. 代码 🧱
2. 创新性 💡
3. Demo 完整度 📝
4. 对以太坊生态的重要性 ♻️

进入 Demo Day 的每个项目有 5 分钟展示时间。

❗❗❗ 项目提交 PR 示例详见：https://github.com/eth-hangzhou/ETHHangzhou/pull/6

# TradaoOrder

**1 项目名称**: TradaoOrder

**2 所选赛道**: Layer2 Application

**3 项目图片**:

![img_v2_1c73f816-fd2a-4c00-94a7-a1cc35790ehu](img/TradaoOrder.jpeg)

**4 简介**:
借助 passkey，用户可以使用指纹和面部识别等生物识别技术登录应用程序。passkey 可以用作 AA 钱包的签名者/所有者。用户可以使用生物识别技术创建自我托管 AA 钱包，而无需记住任何助记词。
我们将用 passkey 的方案 为 tg 用户生成一个自托管的 aa 钱包地址。目标将 web2 的 tg 用户和交易所的未持有钱包地址用户带入到 l2

**5 队长和队员**:

队长: [@qddd.eth](https://github.com/mcfang) 队友：[@LaceLetho](https://github.com/LaceLetho)

**6 本项目在这次黑客松的目标**

目标：

1. 利用 Passkey 和 AA 以及 SessionKey 技术帮助 web2 用户简单创建 AA 钱包
2. 结合 Telegram 方便用户使用

**7 黑客松前两日的进度**

- Day 0:
  - [x] 调研 Passkey，Zerodev 等库的可用性
  - [x] 搭建项目基础框架
- Day 1:
  - [x] 完成主体：Passkey 创建部分，sessionKey 签名部分
  - [x] 完成主体：机器人部分

**8 视频链接**
https://www.youtube.com/shorts/AOnW99HE0ok
**9 项目 github repo 链接**
所有代码都在
https://github.com/tradao-xyz/hackathon_order_server
https://github.com/tradao-xyz/hackason_AA

**10 是否基于之前的项目**
该项目是本次 hackathon 期间，从 0 到 1 开发的项目，完全原创。
**24.11 项目 Demo 链接（选填）**
https://t.me/TradaoOrderBot
