# SpotLive

**1 项目名称**: SpotLive

**2 所选赛道**: Layer2 Application

**3 项目图片**:

![SpotLive Logo](https://github.com/HackingOnWeb3/SpotLiveImage/blob/main/SpotLiveCover.png?raw=true)

![SpotLive Description 1](https://github.com/HackingOnWeb3/SpotLiveImage/blob/main/SpotLiveView1.png?raw=true)

![SpotLive Description 2](https://github.com/HackingOnWeb3/SpotLiveImage/blob/main/SpotLiveView2.png?raw=true)

**4 简介**: 

SpotLive通过用户在地点的打卡构成活动地标（SBT）。参与者上传活动记录，数据GPT化之后提供问答服务。不同的服务定价模式一致，用户通过铸造或赎回服务凭证（Pass）影响价格供需曲线波动。上传者根据Pass价格和使用量获得收益。
活动地标和问答服务既给用户提供学习（自我实现）价值，也给用户提供情绪价值。整个平台给活动和事件提供更多的时间维度和热度信息，不同活动之间的关系也得以体现，从长期来看，能构建出一个多彩的增强现实世界。

**5 队长和队员**: 

队长: Harry Ma

队员: Stella Zhang

队员: Leon Li


**6 本项目在这次黑客松的目标:**

目标：
一共六个主要功能。
1. 地图打卡 
2. 建立活动 
3. 活动文件上传及openai embending
4. 活动问答 
5. 钱包管理 
6. 问答凭证Pass铸造 

**7 黑客松前两日的进度**

- Day 0:
  - 项目方案讨论, 产品原型设计
  

- Day 1:
    - 需求分析与技术方案设计
        + 前端方案设计
            * React作为主语言开发
            * 使用google js sdk 完成地位空间信息的获取与展示
            * metamask钱包作为操作对象
        + 后端方案设计
            * 使用golang作为后端开发语言，提供rest等接口
            * 调用4everland的ipfs接口完成文件上传
            * 使用openai接口完成数据embeding与接口调用问题(借助于[开源项目](https://github.com/mayooear/gpt4-pdf-chatbot-langchain))
            * 使用chainlink 更新资产价格
        + 合约方案设计
            * ERC721作为NFT的标准,作为活动凭证
            * 部署在goerli和sepolia测试网上，测试与验证
            * 使用foundry-rs作为合约开发部署测试工具

- Day 2:
    - 前后端方案实现
    - 合约方案实现
    - 项目整合,联调测试
    - 项目部署
- Day 3:
  - 项目材料编写、完善、补充、提交
  - 部分问题修复

**8 视频链接:**
+ [B站](https://b23.tv/6VmV8uw)

**9 项目 github repo 链接:**


+ 合约代码(https://github.com/HackingOnWeb3/SpotLiveSmartContract)


+ 前端代码(https://github.com/HackingOnWeb3/SpotLiveWebsite)


+ 后端代码(https://github.com/HackingOnWeb3/SpotLiveServer)


**10 是否基于之前的项目:**

+ 该项目是本次hackathon期间，从0到1开发的项目，完全原创。

**24.11 项目 Demo 链接（选填）:**

+ https://spot-live-website.vercel.app/