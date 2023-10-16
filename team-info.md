# PIVOT
1. 项目名称：PIVOT
2. 所选赛道：Layer2 Application
3. 项目图片：https://github.com/GitVerse-Web3/ETHHangzhou/blob/main/img/Team%2341_ScreenShot.png
4. 简介：PIVOT（一个全去中心化的不贬值资产的众包估值协议）旨在帮助各类开源项目（代码、视频、文档、数据集等）在不影响开源性的情况下获取收益。P.I.V.O.T.协议本质上是一个股份无限增发的偏佛系的机制，其价值不依赖稀缺性。该协议结合了例如打赏、股份、股指、分红、等机制的优势。  其特点如下：
- 股价在所有时间恒定
- 打赏即买股
- 买股即灵魂绑定（SBT）
- 卖股即增发
    - 卖多少增发多少
    - 增发股份等比稀释
- 卖股即盈利
- 盈利即分红
- 所有股份在同一时间权益平等
    - 权益即分红权
- 股东数量即股指
  
5. 队长和队员：
  Zaki（产品）/Linus（前端）/Bruce（合约）
6. 本项目在这次黑客松的目标
   - 创建一个简单的DAPP，可实现Hacker/Youtuber/Writter上传自己的项目并Mint NFT，用户/玩家可以实现购买、怒退等简单功能
   - 创建合约来管理NFT的发行，这里我们采用ERC-1155来铸造NFT
7. 黑客松前两日的进度：
- day1
  - 确定使用的技术栈：react
  - 搭建页面的layout和静态页面的编写
  - 使用etherjs连接钱包
  - 创建pivot合约继承了 OpenZeppelin 的 ERC1155 标准合约，并使用了 Ownable、ERC1155Burnable 和 ERC1155Supply 扩展。
    合约功能：
    Pivot 合约是一个 ERC1155 标准代币合约，支持多资产代币。
    合约有一个拥有者（owner），拥有者可以设置 URI（Uniform Resource Identifier）来引用代币元数据。
    合约提供了创建新代币的功能（initToken），新代币可以设置价格和最大供应量。
    用户可以购买代币（mint）并获得权益，这需要支付与代币价格相等的 ETH。购买后，代币供应量将减少，用户的余额将增加。
    用户可以查询代币的所有权、价格和余额。
    用户可以领取代币余额（claimUserBalance），将 ETH 转入其钱包。
    合约还记录了每种代币的铸造者，并支持向多个用户分发奖励。
- day2
  - 使用etherjs连接部署至Scroll的合约
  - 调用合约的接口（initToken，mint等）完成相应的功能
  - 读取合约信息完善页面
8. Demo 视频链接：
9. 项目 github repo 链接：https://github.com/NftTopBest/pivot
10. 该项目是本次hackathon期间，从0到1开发的项目，完全原创。
