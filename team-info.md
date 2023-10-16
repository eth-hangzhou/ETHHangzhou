# AI-based Smart Contract Explorer

**1 项目名称：**

AI-based Smart Contract Explorer

**2 所选赛道：** 

公共物品 （Public Goods）

**3 项目图片：**

![avatar](img/Team37_Architecture.png)



**4 简介：**

AI-based Smart Contract Explorer 是一个 基于向量数据库和 LLM 进行 ETH 智能合约代码检索的浏览器，搜索结果包含智能合约原文、出处、代码解析等多维度内容。向量数据库技术是人工智能应用中的一项重要技术，通过 ANN 最似近邻算法，我们可以通过自然语言进行联想式搜索，而非传统的关键字搜索。立项起因是传统搜索代码的浏览器，例如 Etherscan，仅能搜索出原始代码。我们希望通过 AI 赋能，建立关于智能合约代码的全维度搜索，让合约开发者的效率指数倍增。

**5 队长和队员：**

队长：Keighteen777

队友：Taki WANG

**6 本项目在这次黑客松的目标:**

搭建项目雏形，打通数据流，进行关键代码的提交和小规模数据量的功能完成展示。例如: 输入find all the smart contracts about DID ,能够返回对应语义的代码数据。

**7 黑客松前两日的进度**

| Day0: |      |                                                              |
| ----- | ---- | ------------------------------------------------------------ |
|       |      | 完成组队 & 新建repo：<br />https://github.com/NonceGeek/ai-based-smart-contract-explorer<br />https://github.com/NonceGeek/movespace_db_uploader_cli |
|       |      | 任务梳理：                                                   |
|       |      | 1. **数据同步：**通过 Syncer同步全链上智能合约代码。         |
|       |      | 2. **代码解析：**通过Semantics Analyser将代码按语义解析归类。 |
|       |      | 3. **数据存储：**将解析过的合约代码数据存入向量数据库集群。  |
|       |      | 4. **CLI 工具：**提供 CLI 工具实现 1、2、3功能。             |
|       |      | 5. **提供服务API:** 梳理功能，建立对应的内外部 API。         |
|       |      | 6. **前端页面：**绘制前端页面，并联调接口。                  |
|       |      | 7. **治理合约：**完成关键治理合约。                          |
|       |      | 8. **线上部署：**将合约部署至 Mumbai 网络，将 App 部署至 Vercel。 |
| Day1: |      | 完成3、4，完成基础 6。                                       |
|       |      | 完成7，升级 6。                                              |
|       |      | 完成 8。                                                     |
|       |      | 完成 team info 以及Demo视频录制等。                          |

**8 视频链接:**

Todo

**9 项目 github repo 链接:**

https://github.com/NonceGeek/ai-based-smart-contract-explorer

https://github.com/NonceGeek/movespace_db_uploader_cli

**10 是否基于之前的项目:**

该项目是本次 hackathon 期间，从0到1开发的项目，完全原创。

**11 项目demo:** 

> https://smart-contract-explorer.movespace.xyz/



