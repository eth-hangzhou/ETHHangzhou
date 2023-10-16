# Attention Flow

**1 项目名称**: Attention Flow

**2 所选赛道**: Layer2 Application

**3 项目图片**:

![AttentionFlow](https://upload-images.jianshu.io/upload_images/6201627-4b59cab4ed7d8357.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

**4 简介**:

我们的项目旨在利用用户的浏览历史记录和书签记录实现变现。每天，用户在浏览网页时会产生大量的记录。我们的插件能够探测并统计用户在各个网页上的使用时长。通过前端获取这些数据，并将其存储在 Ceramic 上进行加密处理。其他用户可以选择付费来查看这些加密的数据，从而获得有关用户的浏览习惯和兴趣的洞察。这为用户提供了一种将其浏览行为转化为经济价值的机会，同时为其他用户提供了一种获取有价值数据的途径。

**5 队长和队员**:

队长: [@hypotyposis](https://github.com/hypotyposis)

队友: [@canvas](https://github.com/CanvasL) [@z2m2020](https://github.com/z2m2020)

**6 本项目在这次黑客松的目标:**

目标：

1. 写一个变现数据 data 的付费模块合约，并在 scroll 上部署，同时写好 ts 脚本。
2. 写一个浏览器插件，用来探测用户每一天（UTC 时间 0 点至下一天的 UTC 时间 0 点）的浏览历史信息（URL、访问次数、网页使用时长、网站分类等信息）和书签变更情况（增删改）。
3. 写一个产品 App，让用户可以从插件注入的方法去获取某一天的浏览详情、书签信息，存储到 Ceramic 上，然后去合约上变现；其他用户也能购买数据，并且经过 Lit 访问控制解锁内容。

**7 黑客松前两日的进度**

- Day 0:
  - [x] 完成组队，GitHub org&repo 的新建：https://github.com/AttentionFlow
  - [x] 细化任务：
    1. [@z2m2020](https://github.com/z2m2020) 负责写合约付费模块。写了合约本身
    2. [@canvas](https://github.com/CanvasL) 负责写浏览器插件。写了获取数据事件监听逻辑
    3. [@hypotyposis](https://github.com/hypotyposis) 负责写 App。写了 UI。
- Day 1:
  - [x] 完成任务 1-4.
    1. 给合约写 ts 脚本
    2. 浏览器插件写 content.js 的注入逻辑。修复 bug
    3. 前端 app 接入浏览器插件，完成 ceramic 存储以及 lit 访问控制逻辑
  - [x] 完善项目 README。
  - [x] 完成 team info 以及视频录制等。

**8 视频链接:**

https://www.bilibili.com/video/BV1LT411x72Q/

**9 项目 github repo 链接:**

所有代码都在

https://github.com/AttentionFlow

**10 是否基于之前的项目:**

该项目是本次 hackathon 期间，从 0 到 1 开发的项目，完全原创。

**11 项目 Demo 链接（选填）:**
https://github.com/0xevm/sloads_demo#sloads-demo----
·