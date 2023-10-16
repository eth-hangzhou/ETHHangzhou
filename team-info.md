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


1. 项目名称 : StellarX 基于[CCIP](https://docs.chain.link/ccip)的双边利率优化跨链借贷协议
2. 所选赛道 : Public Goods
3. 项目图片

    ![](https://github.com/xiaoyuanxun/StellarX/blob/main/page.png)

4. 简介

    StellarX是基于[CCIP](https://docs.chain.link/ccip)的双边利率优化跨链借贷协议。我们使用ChainLink的CCIP来进行链间的消息以及Token的通信，创新自研了双边利率优化算法模型，利用P2P撮合使存款人的收益率更高，借款人的利率更低。我们整合了多个链的借贷协议池流动性，使用户可以在任意链存入Token，并一键在另一链借出Token。

5. 队长和队员

    队长 : [Harlen009](https://github.com/beyond009)

    队员 : [Xun勋](https://github.com/xiaoyuanxun) , [0xNan](https://github.com/zn66665)

6. 本项目在这次黑客松的目标

    完成MVP的构建，能够实现存入资产、跨链借贷、资产清算。

7. 黑客松前两日的进度

    第一天进度 : 项目idea讨论确定，讨论研究双边利率优化算法模型，调研CCIP的使用，前端框架搭建，初步构建借贷合约和CCIP通信合约。

    第二天进度 : 完成借贷合约和CCIP通信合约，合约测试与部署，前后端对接。

8. Demo 视频链接 : 
    


9. 项目 github repo 链接

    合约 : https://github.com/xiaoyuanxun/StellarX

    前端 : https://github.com/beyond009/stellarX
    
10. 该项目是本次hackathon期间，从0到1开发的项目，完全原创
11. 项目 Demo 链接 : https://stellar-x-three.vercel.app/