### 大前端
#### React
[40行代码实现React核心Diff算法](https://mp.weixin.qq.com/s/wlb_CtUsoiDIZwqHV0Mm_w)
作者通过亲手实践带我们理解React核心Diff算法

Cleaner Codes — React Subcomponents
[https://medium.com/@marioserano55/cleaner-codes-react-subcomponents-1c2ebe178566](https://medium.com/@marioserano55/cleaner-codes-react-subcomponents-1c2ebe178566)
作者总结了一种简洁书写子组件的方法；通过对比，我们可以看到这种写法的优势。

#### Android
深入理解 Android 系统 Back Gesture 的实现
[https://mp.weixin.qq.com/s/S44b5c8tlo9ytDdRRoy86g](https://mp.weixin.qq.com/s/S44b5c8tlo9ytDdRRoy86g)
深入理解 Android 系统 Back Gesture 的实现：SystemUI 利用 InputMonitor 监视系统 Touch 事件、监听和获取 WMS 中保存的手势停用区域 Region、依据 Touch 事件展示动画和触发返回、通过 InputManager 注入返回按键事件、Dispatcher分发返回事件给APP。

Android 12 还没用上，Android 13 已经来了！
[https://juejin.cn/post/7088605710728036359?share_token=8253f97c-a85d-4644-b6ef-2cc5dcb4c3e7](https://juejin.cn/post/7088605710728036359?share_token=8253f97c-a85d-4644-b6ef-2cc5dcb4c3e7)
Android 13 适配指南：从用户体验、安全和隐私设置、性能和电池等维度，介绍针对特定SDK Version和所有应用的行为变更，提供相应的兼容性适配指南。详见[Android 13 开发者概览版官方文档](https://developer.android.com/about/versions/13?hl=zh-cn)。

MVVM 进阶版：MVI 架构了解一下~
[https://juejin.cn/post/7022624191723601928#heading-5](https://juejin.cn/post/7022624191723601928#heading-5)
Android 应用架构进阶 —— MVI架构：MVP引入Presenter层与View进行交互，并负责业务逻辑，MVVM架构通过双向数据绑定在View层监控反映Model数据变化，MVI架构强调数据单向流动，ViewModel通过ViewState与Action通信，类似于变体版的redux。

#### CSS
CSS Toggles Explainer & Proposal
[https://css.oddbird.net/toggles/explainer/](https://css.oddbird.net/toggles/explainer/)
We propose generalizing the pattern so that it can be applied to any element using a declarative syntax in CSS, with built-in accessibility and performance.

[W3C 发布 WebAssembly 2.0 初版草案](https://www.oschina.net/news/191993/wasm-2-0-public-drafts)
[https://www.oschina.net/news/191993/wasm-2-0-public-drafts](https://www.oschina.net/news/191993/wasm-2-0-public-drafts)
W3C 今天[发布](https://www.oschina.net/action/GoToLink?url=https%3A%2F%2Fwww.w3.org%2Fblog%2Fnews%2Farchives%2F9509)了 WebAssembly 2.0 的首批公开工作草案 (Public Working Drafts)

#### Flutter
Flutter 音视频开发新思路
[https://mp.weixin.qq.com/s/ZpHfkz8CQmPhKY4--WYTWw](https://mp.weixin.qq.com/s/ZpHfkz8CQmPhKY4--WYTWw)
音视频在现代 App 中越来越重要，对于 Flutter 开发来说，音视频场景也是不可或缺的一环，功能逻辑跨端与 UI 跨端同样重要，这样才能做到真正的跨平台开发，提升研发效率。文中提到的技术框架 PowerMedia 已经在闲鱼多个场景应用落地

Flutter 新一代图形渲染器 Impeller
[https://mp.weixin.qq.com/s/PLvlSt3tlX6AjufDm0XVMA](https://mp.weixin.qq.com/s/PLvlSt3tlX6AjufDm0XVMA)
Flutter在2022年的Roadmap中提出需要重新考虑着色器的使用方式，计划重写图像渲染后端。最近该渲染后端 Impeller（叶轮）初见端倪，本文将介绍 Impeller 解决的问题、目标、架构和渲染细节。

#### 构建工具
前端框架源码解读之Vite
[https://mp.weixin.qq.com/s/_w1b04nsEZk1AfaKDiRiUg](https://mp.weixin.qq.com/s/_w1b04nsEZk1AfaKDiRiUg)
Webpack、Rollup 、Esbuild、Vite ?本次分享主要介绍最核心的两个功能的实现原理：依赖预构建、浏览器模块加载流程

超全面的前端新一代构建工具对比: esbuild、Snowpack、Vite、wmr
[https://mp.weixin.qq.com/s/JZbsIqsqNeJmc__QFKpo1Q](https://mp.weixin.qq.com/s/JZbsIqsqNeJmc__QFKpo1Q)
我们的目标更多的是为了更好地了解运行任务的开发者工具的格局，让我们的工作更轻松。通过这种方式，我们就能看到有哪些选择，以及它们是如何配合的，这样我们就能在需要的时候做出最好的选择。

#### DevTools
Chrome DevTools Inspector 扩展实践
[https://mp.weixin.qq.com/s/gsq9du1Xaabl1YlJm8ONIQ](https://mp.weixin.qq.com/s/gsq9du1Xaabl1YlJm8ONIQ)
本文从 chrome devtools inspector 扩展为出发点，介绍了 devtools frontend 调试原理及模块加载方式，react native debugger 调试原理，跨域调试方案，最终实现 devtools inspector 的调试扩展。

#### Node.js
面向前端与未来标准的Node.js Web 框架再进化
[https://mp.weixin.qq.com/s/BdYjscsqmD3GnqPfOhYR3g](https://mp.weixin.qq.com/s/BdYjscsqmD3GnqPfOhYR3g)
Node.js Web 框架的发展历程，分析各类框架的适用场景及利弊，并基于阿里的 Node.js 框架 Midway，为大家介绍在过去这两年，我们对下一代 Node.js Web 框架的思考、设计、实践，包含如何面向前端做一款前端“爱用”的 Node.js 框架，如何面向未来标准甚至参与标准来设计 Node.js Web 框架两部分。

[The Most Popular Node.js Frameworks in 2022](https://stackdiary.com/node-js-frameworks/)
2022年最流行的Node.js的框架，对各个框架做了一个简单的介绍，并附有各个框架的Github、Docs、和官网地址链接，方便查阅。

Node v18.0.0 (Current)
[https://nodejs.org/en/blog/release/v18.0.0/](https://nodejs.org/en/blog/release/v18.0.0/)

#### 低代码
不发版灵活实现前端定制化UI——阿波罗动态布局介绍
[https://mp.weixin.qq.com/s/zoNKmZQE1AP-BFwyaEqQrQ](https://mp.weixin.qq.com/s/zoNKmZQE1AP-BFwyaEqQrQ)
阿波罗动态布局方案能够快捷高效的支持不同业务对布局的多样化需求，客户端楼层样式自动渲染生成，无需开发编码，减少发版 样式布局后台配置，所见即所得，调试验证方便 元件类型丰富，布局属性灵活。

### 行业资讯
为什么说加快建立全国统一大市场，最利好供应链及物流行业？
[https://mp.weixin.qq.com/s/MO9AtuJTdILzL9F6CtrQVg](https://mp.weixin.qq.com/s/MO9AtuJTdILzL9F6CtrQVg)
本篇将为各位读者，从政策解读的视角进行梳理，回答为什么供应链及物流行业被资本认为是“加快建设全国统一大市场”最利好的行业赛道？
### 设计
浅谈动作捕捉技术：从电影游戏特效到元宇宙交互变革
[https://mp.weixin.qq.com/s/ZVyBjSO11qvWS-2eLkjUxQ](https://mp.weixin.qq.com/s/ZVyBjSO11qvWS-2eLkjUxQ)
动作捕捉主要包含身体捕捉、手指捕捉和面部捕捉三种。目前动作捕捉系统有光学式和惯性式两大主流技术路线。可以预见，随着动捕技术的应用推广，人的表情、姿势、行为、加速等信息都可以实现虚拟世界的数字化，这将极大地提升3D动作资产的创作效率，并最终带来人机交互的变革。

从0到1搭建年轻化游戏社区设计语言
[https://mp.weixin.qq.com/s/ZMNvmYDxc-k-96izJ1mX7Q](https://mp.weixin.qq.com/s/ZMNvmYDxc-k-96izJ1mX7Q)
在这个案例中，无论是产品前期的业务理解，世界观构建，还是设计过程中的每一次尝试，设计师都是从打造一致的品牌印象出发。通过丰富的设计表现手法勾勒出品牌性格，多场景强化渗透，向用户传递出一致的品牌印象。

### 发现
Explain the First 10 Lines of Twitter’s Source Code to Me
[https://css-tricks.com/explain-the-first-10-lines-of-twitter-source-code/](https://css-tricks.com/explain-the-first-10-lines-of-twitter-source-code/)

Avoiding 404 errors with Single-Page Apps
[https://oliverjam.es/blog/avoid-spa-404/](https://oliverjam.es/blog/avoid-spa-404/)

### 更多
科技爱好者周刊（第 204 期）：如何度过疫情、裁员、还有战争
[http://www.ruanyifeng.com/blog/2022/04/weekly-issue-204.html](http://www.ruanyifeng.com/blog/2022/04/weekly-issue-204.html)[
](http://www.ruanyifeng.com/blog/2021/05/weekly-issue-160.html)
技术周报·深入理解 React Scheduler 原理
[https://mp.weixin.qq.com/s/d5Newmsl1zMsGkBQQ9wP6Q](https://mp.weixin.qq.com/s/d5Newmsl1zMsGkBQQ9wP6Q)
![image.png](https://cdn.nlark.com/yuque/0/2020/png/85771/1605930034828-7fc81343-651f-4a15-8465-eebe5a23cf61.png#crop=0&crop=0&crop=1&crop=1&height=31&id=C5Hpa&margin=%5Bobject%20Object%5D&name=image.png&originHeight=90&originWidth=2186&originalType=binary&ratio=1&rotation=0&showTitle=false&size=14325&status=done&style=none&title=&width=746)


欢迎加入，一起共建「前端小报」
