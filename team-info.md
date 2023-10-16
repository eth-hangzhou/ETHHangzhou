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



序号：30
1. 项目名称
    Supervised-RingSig-Privacy-Transaction-Protocol

2. 所选赛道
    Public Goods

3. 项目图片
    https://github.com/tokenlin/Supervised-RingSig-Privacy-Transaction-Protocol/blob/main/ProjectLogo.png

4. 简介
    本项目是一种基于以太坊的去中心化的可监管的隐私解决方案（对标Tornado.cash）。它使用环向签名证明来获得隐私，使用智能合约接受主币存款。这些存款可以从网络上的任何地址提取。每当通过新地址提取资产时，都无法将提取与存款联系起来，从而确保资产隐私。并且用户在使用该协议前其地址及资金均需要全网曝光一定的时间，接受全网的监督，未通过监督的地址或和资金不能使用该协议，从而达到监督要求。本项目是一种基于以太坊的去中心化的可监管的隐私解决方案。它使用环向签名证明来获得隐私，使用智能合约接受主币存款。这些存款可以从网络上的任何地址提取。每当通过新地址提取资产时，都无法将提取与存款联系起来，从而确保资产隐私。并且用户在使用该协议前其地址及资金均需要全网曝光一定的时间，接受全网的监督，未通过监督的地址或和资金不能使用该协议，从而达到监督要求。

5. 队长和队员
    队长：@token_lin 
    队员：@supredu

6. 本项目在这次黑客松的目标
    完成项目功能，并测试链Demo部署

7. 黑客松前两日的进度
    D1:
    完成组队，GitHub org&repo的新建
    细化任务：
    a. 完成工厂合约factory.sol
    b. 完成监管合约supervisor.sol
    c. 完成交易合约pool.sol
    d. 链下辅助计算程序
    e. 主要测试脚本

    D2:
    完成步骤a,b，以及部分步骤c

8. Demo 视频链接
   Loom: https://www.loom.com/share/433a41bdcc6e4a31ba7a70c9c47697d0?sid=bcbd3f3c-fa18-47fa-a0c8-8697a0cedf27

   Bilibili（备用）：https://www.bilibili.com/video/BV1iu411T7oK/?vd_source=caf38d321cd67a07e1eb500b5bdfaf57

9. 项目 github repo 链接
    https://github.com/tokenlin/Supervised-RingSig-Privacy-Transaction-Protocol

10. 声明未基于之前的项目
    该项目是本次hackathon期间，从0到1开发的项目，完全原创。

11. 项目 Demo 链接（选填）
    Factory: https://goerli.etherscan.io/address/0x94DB04Ae252bd16c92344c325cAf81D4B141FdB1
    Supervisor: https://goerli.etherscan.io/address/0x6da689a87E23fc2d71388113C26927aa697B6925
    Pools[0]：https://goerli.etherscan.io/address/0xEaB206e40dc9CE93d0ACeBF2693521616ce4244a
