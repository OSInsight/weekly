![image.png](https://cdn.nlark.com/yuque/0/2022/png/85771/1663513314828-379e670c-b4dc-4a68-b042-3bc0e4c8066e.png#clientId=u40fdd697-6069-4&crop=0&crop=0&crop=1&crop=1&errorMessage=unknown%20error&from=paste&height=412&id=u4bf5de45&margin=%5Bobject%20Object%5D&name=image.png&originHeight=824&originWidth=1315&originalType=binary&ratio=1&rotation=0&showTitle=false&size=1260493&status=error&style=none&taskId=u0f0a24a7-fb08-4475-9b80-1a68c6ea751&title=&width=658)
Source: [Thanks iPhone 14, designing for device sizes is dead](https://polypane.app/blog/thanks-i-phone-14-designing-for-device-sizes-is-dead/)
### 大前端
#### JS
比 eval 和 iframe 更强的新一代 JavaScript 沙箱！
[https://mp.weixin.qq.com/s/t2VjwrewFuE0DHo_HeJ2zw](https://mp.weixin.qq.com/s/t2VjwrewFuE0DHo_HeJ2zw)
今天我们来看一个进入 statge3 的新的 JavaScript 提案：ShadowRealm API。

#### React
关于 React Re-Render
[https://mp.weixin.qq.com/s/BPFJSkvv_UPMux0dSZuh-A](https://mp.weixin.qq.com/s/BPFJSkvv_UPMux0dSZuh-A)
汇总下关于 re-render 相关的知识点：原因、如何避免等。

An apparent React bug
[https://phelipetls.github.io/posts/surprising-react-bug/](https://phelipetls.github.io/posts/surprising-react-bug/)
It seems React is “doing the right thing”, but in the end things break because the details element has state of its own that React doesn’t know about. In short, the issue is that there are two sources of truth for the open attribute – React and the browser.

#### Performance
How To Improve Largest Contentful Paint for Faster Load Times
[https://calibreapp.com/blog/largest-contentful-paint](https://calibreapp.com/blog/largest-contentful-paint)
Optimising your page’s LCP has an outsized impact on page speed and user experience. It’s important that Google has even made LCP and the other Core Web Vital metrics a ranking factor.

#### 跨端
京东APP OpenHarmony化的跨端开发探索
[https://mp.weixin.qq.com/s/oCHNxoE_4Dzr6-g-K7A9MQ](https://mp.weixin.qq.com/s/oCHNxoE_4Dzr6-g-K7A9MQ)
本文主要介绍了京东App在适配OpenHarmony的预研情况，表现了业务和技术复杂度，同时介绍了JDMCube动态化框架在适配OpenHarmony的进展和阶段性成功以及后续规划。京东App内用到的技术栈也很多，主要包括原生、H5&小程序、跨端，占比分别是55%、40%、5%（其中RN、Flutter占比较少，所以不展开介绍）。

#### 脚手架
前端脚手架开发入门
[https://mp.weixin.qq.com/s/oFo43lbfdueVcdaOlJQ_tg](https://mp.weixin.qq.com/s/oFo43lbfdueVcdaOlJQ_tg)
本文将介绍脚手架需要的一些工具 commander、chalk、inquirer、ora等，以及package.json中的一些重要字段，最后通过实例demo来展示如何开发脚手架

RTC 脚手架的设计和实现
[https://mp.weixin.qq.com/s/Hx9eic1garSk6dF4_wlDsQ](https://mp.weixin.qq.com/s/Hx9eic1garSk6dF4_wlDsQ)
本文介绍了 RTC 脚手架产生的背景，并以通俗易懂的方式一步步阐述设计过程以及最终实现。

#### SwiftUI
The SwiftUI Layout Protocol – Part 1
[https://swiftui-lab.com/layout-protocol-part-1/](https://swiftui-lab.com/layout-protocol-part-1/)
One of the best SwiftUI additions this year has to be the Layout protocol. Not only we finally get our hands in the layout process, but it is also a great opportunity to better understand how layout works in SwiftUI.

#### RN
基于 React Native 的动态列表方案探索
[https://mp.weixin.qq.com/s/5Oa45FN3SECveu6_N89k2A](https://mp.weixin.qq.com/s/5Oa45FN3SECveu6_N89k2A)
基于 ReactNative 的动态列表方案简单来说就是将 ReactNative 容器内嵌在 RecyclerView 的 ViewHolder 中，由于页面主体框架还是由 Native 开发和渲染，所以首屏加载速度得到了保证，局部的RN实现也使页面获得动态化的能力，从而在性能、”完备逻辑执行“的动态化能力之间取得了一个平衡点。

#### 测试
Getting started with Playwright component testing
[https://blog.logrocket.com/getting-started-playwright-component-testing/](https://blog.logrocket.com/getting-started-playwright-component-testing/)
If you have been using Playwright to implement E2E tests for your application, you may be aware that Playwright now provides the ability to test your frontend components individually.
This tutorial will walk you through the process of writing unit tests for your Svelte, Vue, and React components using Playwright’s recently released, currently experimental component testing feature.

#### Responsive
Thanks iPhone 14, designing for device sizes is dead
[https://polypane.app/blog/thanks-i-phone-14-designing-for-device-sizes-is-dead/](https://polypane.app/blog/thanks-i-phone-14-designing-for-device-sizes-is-dead/)
Testing on specific device widths is an evolutionary dead end: If you optimize for a device today, it's going to break in a year. Your design has to be fluid and flexible to make it look good regardless of a device's width. Today, in a year, in a decade.

How iOS Apps Adapt to the various iPhone 14 Screen Sizes
[https://hacknicity.medium.com/how-ios-apps-adapt-to-the-various-iphone-14-screen-sizes-b2504a39b58f](https://hacknicity.medium.com/how-ios-apps-adapt-to-the-various-iphone-14-screen-sizes-b2504a39b58f)
To see the new resolutions of the iPhone 14 Pro and 14 Pro Max, apps must be built with Xcode 14 or later.

#### 监控
详聊前端异常原理
[https://mp.weixin.qq.com/s/dYWVAxorJ-L1IJdSYM427g](https://mp.weixin.qq.com/s/dYWVAxorJ-L1IJdSYM427g)
本文将详细的阐述异常原理，把笔者近 2 年在前端监控领域中与异常打交道的经验分享给大家。

基于自建 VTree 的全链路埋点方案
[https://mp.weixin.qq.com/s/FuL2zynvf1xGjg_RCZcc4Q](https://mp.weixin.qq.com/s/FuL2zynvf1xGjg_RCZcc4Q)
我们自研了一套全链路埋点方案，从埋点设计、到客户端三端(iOS、Android、H5)开发、以及埋点校验&稽查、再到埋点数据使用，目前已经广泛应用于云音乐各个主要APP。

#### 浏览器插件
Plasmo Framework：次世代的浏览器插件开发框架
[https://mp.weixin.qq.com/s/VKpHtRVIJh669SLz2nUJuQ](https://mp.weixin.qq.com/s/VKpHtRVIJh669SLz2nUJuQ)
本文将尝试介绍关于插件、插件开发、基于 Plasmo 的插件开发以及业务实践等相关内容。

### 产品
火出圈的《羊了个羊》，到底做了什么？
[https://mp.weixin.qq.com/s/QEO4vSGB-p-SqGa1SCzU5g](https://mp.weixin.qq.com/s/QEO4vSGB-p-SqGa1SCzU5g)
我不知道《羊了个羊》具体是什么时候火起来的，不过今天是我第一次体验这个款游戏，这篇文章就来说下我的一点点思考。

iOS 16: The MacStories Review
[https://www.macstories.net/stories/ios-16-the-macstories-review/](https://www.macstories.net/stories/ios-16-the-macstories-review/)
When is the last time your iPhone truly surprised you? My point is: if you ask someone about the last time an iPhone truly surprised them, chances are they’ll reply with a hardware feature. Software-related surprises are more rarefied on iOS these days, but the kind of people who are reading this story can point to a few examples in our recent history.

从零开始的新跨平台浏览器：Ladybird 正式起飞
[https://mp.weixin.qq.com/s/4LeNsBLiTQLZS5KhHEFYCg](https://mp.weixin.qq.com/s/4LeNsBLiTQLZS5KhHEFYCg)
近期，SerenityOS 的发起者 Andreas Kling 在博客中宣布了他最新开源跨平台浏览器项目 Ladybird，Ladybird 浏览器基于 SerenityOS 的 LibWeb 和 LibJS 引擎，LibWeb 始于 2019 年开发，其 JavaScript 引擎 LibJS 则于 2020 年开发。

### 设计
高概念美学的风格探索与落地
[https://mp.weixin.qq.com/s/JM9bZdBpSKl4nXzAcC_yfg](https://mp.weixin.qq.com/s/JM9bZdBpSKl4nXzAcC_yfg)
扎根真实世界，构筑无限幻想。跟大家一起分享一下我对于世界观和游戏美术风格的探索，并且跟大家解析开放世界的设计流程、关键要素，并分享从高概念到落地的流程和规范。我将以《孤岛惊魂》系列为例，介绍如何设计并打造一个真实可信而且引人入胜的开放世界。

可视化大屏业务之设计方案制定（下）
[https://mp.weixin.qq.com/s/SMdmP7mpTsGjkXyqS0vqsA](https://mp.weixin.qq.com/s/SMdmP7mpTsGjkXyqS0vqsA)
本文将从以下五个方面讲解可视化大屏从0到1的设计过程：首先，确定画板大小；然后，合理安排模块布局；其次，明确整体界面的设计风格；再次，对业务数据进行梳理、合理安排信息层级以及选择合适的图表去精准的表达业务数据；最后，就是快速的搭建一块可视化大屏。

Space, Grids, and Layouts
[https://www.designsystems.com/space-grids-and-layouts/](https://www.designsystems.com/space-grids-and-layouts/)
Spatial systems, grids, and layouts provide rules that give your designs a consistent rhythm, constrain decision making, and help teams stay aligned. In this guide, we’ll walk through the basics of defining spatial base units, creating relationship rules with grids, and bringing it all together for modern UI layouts.

### 启发
25 Frontend Refactoring Tips and Techniques
[https://pranavjoglekarcodes.web.app/blogs/posts/2021/frontend_refactoring_tips/](https://pranavjoglekarcodes.web.app/blogs/posts/2021/frontend_refactoring_tips/)
In this blog post I am going to explain a list of 25 techniques I used to make my TypeScript NextJS Tailwind code easier to understand.

一个十年前端的职业发展之路和职场建议
[https://mp.weixin.qq.com/s/mjJxWtqzh4oxZTwkJamRkA](https://mp.weixin.qq.com/s/mjJxWtqzh4oxZTwkJamRkA)
前端生涯的总结和一些职场建议

科技爱好者周刊（第 223 期）：程序员需要担心裁员吗？
[http://www.ruanyifeng.com/blog/2022/09/weekly-issue-223.html](http://www.ruanyifeng.com/blog/2022/09/weekly-issue-223.html)
与其担心宏观经济，不如关注自己。你对自己生活的影响，往往比宏观经济对你的影响大得多。公司裁员肯定会对一个人产生影响，但是它决定不了你的未来，你自己才是最大的影响因素。
![image.png](https://cdn.nlark.com/yuque/0/2020/png/85771/1605930034828-7fc81343-651f-4a15-8465-eebe5a23cf61.png#crop=0&crop=0&crop=1&crop=1&height=31&id=C5Hpa&margin=%5Bobject%20Object%5D&name=image.png&originHeight=90&originWidth=2186&originalType=binary&ratio=1&rotation=0&showTitle=false&size=14325&status=done&style=none&title=&width=746)


欢迎加入，一起共建「前端小报」

