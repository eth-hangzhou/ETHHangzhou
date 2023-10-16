# LuckyFT

**1 项目名称**: LuckyFT

**2 所选赛道**: Layer2 创新应用

**3 项目图片**:

![LuckyFT](https://luckyft.vercel.app/lucky-ft.jpg)

**4 简介**: 

项目基于 Scaffold ETH 2 开源框架基础上开发的。
最近 Friend.Tech 比较火，但是他就纯庞氏了，靠拉人头来赚手续费或者 key 涨价，早卖的人赚钱，最后跑路的人血亏。
LuckyFT 则考虑引入“运气” 来改变这个庞氏的逻辑。一切的一切都是运气！

**5 队长和队员**: 

Solo 黑客： Stark: https://twitter.com/StarkEVM99

**6 本项目在这次黑客松的目标:**

目标：做个好运 FT

LuckyFT 使用了 ChainLink 的 VRF 功能来产生随机数，部署到 sepolia 和 scrollSepolia

**7 黑客松前两日的进度**
- Day 0:
  - [x] GitHub fork scaffold eth 2：https://github.com/HelloRWA/eth-hangzhou
  - [x] 学习 chainLink 及 scroll 相关知识
- Day 1: 实现具体功能
 
1. 用户首先得 createFT，持有一个 FT 后，才可以买别人的 key
2. 买 key 时，支付 price 费用，是 `buy` 方法，里面会触发 chainlink 的 requestRandomWords 方法，同时给用户发 key
3. chainlink 的 VRF 回调 fulfillRandomWords时，则会根据获得的随机数来决定运气分配
4. 同个房的某个人有好运获得 10% 的分成
5. 其他某个好运房的房主获得 10% 的分成
6. 上面好运房的某个key 持有者有好运获得 10% 的分成

**8 视频链接:**
https://www.bilibili.com/video/BV1zN41147N8/

**9 项目 github repo 链接:**
所有代码都在
https://github.com/HelloRWA/eth-hangzhou/pull/1

**10 是否基于之前的项目:**
该项目是本次hackathon期间，从0到1开发的项目，完全原创。

**24.11 项目 Demo 链接（选填）:**

https://luckyft.vercel.app/
