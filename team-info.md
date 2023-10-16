# 哗啦啦（hualala）

**1 项目名称**：hualala

**2 所选赛道**：Public Goods

**3 项目图片**：
![image](https://github.com/PhiloCwh/ETHHangzhou/assets/105807963/7b951bb5-644e-4797-a232-ae25bf1cf053)


![]()

**4  简介**：
hualala～是一个defi流动性解决方案的底层平台。
在此平台上用户可以让流动性利用率得到解放。

例子1:用户可以在添加流动性后，做市资金同时为抵押资产可通过超额抵押借出资产。
一份做市资金得到n份收益，同时引入healthfactor（health factor = reserve/virtual reserve(其中 0 < health factor <1)）来调控风险和贷款利率和
和清算。

例子2:土狗币的杠杆。
单边流动性做多token
某个pair有tokenA，tokenB
质押tokenA到pair里面，可贷出总资产tokenA 1-准备金率（p）
p对于非白名单的lp对应该为（0.6～0.9）

其中理论最大的杠杆为1/p
即做多tokenA的方式，就是存入A借出B，用B买A，再存入A借出B，
个人账本就是 抵押资产A，负债B
单A涨价时用户卖出更少的A可以偿还负债B

实现做多杠杆的效果

此处为做多tokenA做空tokenB反之为做多B做空A

包装为简单的合约杠杆。

例子3:rwa为优质资产（稳定币）提供利息兜底服务，有稳定的优质资产利用率如 如房地产 https://twitter.com/PlanetariumRWA 或算力租借平台如 https://cephalon.ai/#/home
等等进行稳定的合作，能获得外部收入来源。兜低apr高于5%。




**5 队长和队员**：

队长：[Philo](https://github.com/PhiloCwh)  队友：[Howe](https://github.com/DestinyWei)  [deli](https://github.com/yyyhakuna)  78

**6 本项目在此次黑客松的目标**：

​ 6.1 完成defi协议的数据底层框架开发

​ 6.2 完成对于应用层面流动性和可借贷共享流动性的开发。
对于lp——pair里面token对的杠杆设计。
完成对于杠杆做多做空的接口。

**7 黑客松前两日的进度**：

- Day 0：
  - [x] 完成组队，分配任务
  - [x] 完成dex和借贷协议框架设计
  
  1. 

- Day 1:
  - [x] 完成city walk
  - [x] 完成前端的页面设计
  - [x] 完成通宵两天写合约的成就
  - [x] 完成做多做空的合约接口和逻辑设计
  - [x]对接前端和合约 

**8 视频链接**：
https://www.bilibili.com/video/BV1xy4y1N7wS/?spm_id_from=333.999.0.0&vd_source=9518fd55781e9b29aea5cf5115e97ecc
https://www.bilibili.com/video/BV1W841167aY/?vd_source=9518fd55781e9b29aea5cf5115e97ecc



**9 项目Github repo链接**：

前端：https://github.com/DestinyWei/hualala-frontend

合约：https://github.com/DestinyWei/hualala-contract

**10 是否基于之前的项目**：

该项目是本次Hackthon期间，从0到1开发的项目，完全原创。

**11 项目Demo链接（选填）**：
