# ETH Hangzhou Hackathon 项目提交说明

ETH Hangzhou Hackathon 的项目需要提交到本页，PR（Pull-Request）截止时间为 2023年10月16日 下午14:00（北京时间，UTC+8）。你需要在你的项目下更新以下内容:
1. 项目名称: PartyBet
2. 所选赛道: Layer2 Application
3. 项目图片: (https://github.com/lessthanno/partybet/blob/main/public/img1.jpg)
4. 简介
  Partybet是一个 telegram群组内的竞猜拼手气红包 bot。它包含两种玩法：
  1.去中心化的 telegram 群拼手气红包。好友们在群内竞猜下一个整点的BTC价格，每人提交 0.008eth 作为赌注，整点到时，最接近实际价格的人获得奖池内所有eth 奖励（若出现平手，则平分奖池）。
  2.瓜分大奖池拼手气红包。所有人可提交 0.008eth 作为赌注进入项目大奖池，整点到时，最接近的人赢得奖池内所有 eth 奖励（若出现平手，则平分奖池）。

  项目特色：
  1.借助 telegram 群和 bot交互，用户进入门槛低，可实现裂变式增长；
  2.竞猜机制公平公正，也富有参与感，可上瘾有粘性；
  3.参与资金门槛低、回报潜力高，web2 和 web3 用户都可以体验，高流动性为 web3破圈增长。
  4.机制本身有很强的延展潜力，可以成为社群服务工具、项目营销利器、叠加代币经济学成为去中心化交易所等等。

5. 队长和队员
  队长: [@haozi](https://github.com/lessthanno)
  队友：[@chinesemark](https://github.com/chinesemark)  [@Simon C](https://github.com/zhongyusimon)
        
6. 本项目在这次黑客松的目标
  - 完成通过telegramBot，让用户实现更简单更快速的交易体验，以游戏娱乐化的方式，让用户体验到交易的乐趣，同时尝试解决流动性问题
  - 细化任务：
    1.确定技术方向，采用UXUYProtocl协议实现一个tgBot基础能力。
    2.配置partyBot机器人
    3.开发/betting功能，实现用户输入BTC的价格的竞猜输入
    4.设计开奖结果机制
    5.设计数据库，记录开奖记录
    6.设计合约的实现逻辑
    7.实现群功能，tg群里能支持多人下注
    8.用户下注充值ETH前端页面

7. 黑客松前两日的进度
  - Day1
    [x] 完成partyBot合约交互，接口优化设计
    [x] 合约加入日志,支持用户可以查看下注历史和全部历史
  - Day2
    [x] tg用户通过PartyBot实现下注功能
    [x] 到指定时间实现开奖功能提示，bot交互界面开发
    [x] 完成bot机器人基础信息配置
  - Day3
    [x] Showcase

8. Demo 视频链接（可以是录屏或其他形式）[Youtube](https://youtu.be/EDzqivO4rlM?si=uopK32tzS_qAbEdQ)
9. 项目 github repo 链接(https://github.com/lessthanno/partybet)
10. 该项目是本次hackathon期间，从0到1开发的项目，完全原创。
11. 项目 Demo 链接 (https://t.me/partybet_bot)


