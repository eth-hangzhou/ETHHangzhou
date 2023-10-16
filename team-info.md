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

ETH Hangzhou Hackathon 的项目需要提交到本页，PR（Pull-Request）截止时间为 2023年10月16日 下午14:00（北京时间，UTC+8）。你需要在你的项目下更新以下内容:
1. 项目名称 Netfusion
2. 所选赛道 Public Goods
3. 项目图片

![netfusion](/img/netfusion.png)

4. 简介

   Netfusion 的定位是为区块链及其他分布式系统提供消息广播服务，将分布式系统的广播通信逻辑从其他业务逻辑中解耦出来。
   
   区块链系统自上而下可以大致分为状态机层（链上数据及逻辑）、共识算法层（选择具体的区块来进行状态迁移）、P2P广播网络层（负责节点之间的广播数据传输）。为了提升区块链系统的TPS，行业中提出了各种链上链下的方案，但从P2P层进行研究和优化的却很少，并且P2P通讯网络的效率直接影响着上层逻辑的效率。
   
   当一个节点初始化一条广播数据时，如果只向部分邻居节点转发消息，会从另外一部分的节点中收到自己向网络中广播的这条消息。我们可以通过这些反馈数据来对广播时选择的转发节点进行评估。Netfusion 即利用这个机制对广播算法进行优化。

   Netfusion 为需要广播网络的分布式系统提供了十分便捷的开发支持，将服务实例化后，通过 `Feed` 方法即可向网络中广播一条消息，通过 `Take` 方法从网络中获取一条消息。在后续我们会在项目中提供更多的广播算法。
5. 队长和队员

   队长：[@trenlinhuang](https://github.com/trenlinhuang) 队友：[@JiangMoCeng](https://github.com/JiangMoCeng) [@quanquanii](https://github.com/quanquanii)

6. 本项目在这次黑客松的目标
   
   完成一个支撑P2P广播的通讯服务层组件
7. 黑客松前两日的进度
- Day 0: 
  - 节点间的通讯，连接管理，一个简单的可以区分不同类型数据的通讯协议设计与实现
  - 实现 `Gossip` 广播协议，进行两个节点的消息接收与转发测试
  - 将 `Netfusion` 项目打包成镜像并测试
- Day 1:
  - 通过 `boot-server` 项目进行容器管理
  - 镜像启动测试、连接建立测试、P2P网络广播测试
  - 将一些参数放到配置文件中便于修改配置
8. Demo 视频链接
   
   https://youtu.be/ntBWEXLbUzo
9.  项目 github repo 链接

   - netfusion: https://github.com/deffusion/netfusion
   - boot-server: https://github.com/deffusion/boot-server
10.  声明未基于之前的项目:
   
     该项目是本次hackathon期间，从0到1开发的项目，完全原创。

在截止时间前提交 PR，且包含前 10 项信息的项目，视为提交成功，否则不参与评奖。

评委将在2023年10月16日下午14-18点期间，根据以下4个维度对项目进行第一轮打分，每个赛道的前5名可以参加晚上19点的Demo Day：
1. 代码 🧱
2. 创新性 💡
3. Demo完整度 📝
4. 对以太坊生态的重要性 ♻️

进入Demo Day的每个项目有 5 分钟展示时间。

❗❗❗项目提交PR示例详见：https://github.com/eth-hangzhou/ETHHangzhou/pull/6