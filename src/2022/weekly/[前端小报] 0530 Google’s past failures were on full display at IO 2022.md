> _There are only two hard things in Computer Science: cache invalidation and naming things.-- Phil Karlton_

### 技术热闻
**Google’s past failures were on full display at I/O 2022**
[https://arstechnica.com/gadgets/2022/05/googles-past-failures-were-on-full-display-at-i-o-2022/](https://arstechnica.com/gadgets/2022/05/googles-past-failures-were-on-full-display-at-i-o-2022/)
Google held its I/O conference earlier this month, and for longtime Google watchers, the event felt like a seance. By my count, "resurrecting the past" accounted for around half of the company's major announcements. | 你来教 Goggle 做事？

**More thoughts on SPAs**
[https://nolanlawson.com/2022/05/25/more-thoughts-on-spas/](https://nolanlawson.com/2022/05/25/more-thoughts-on-spas/)
My main point was: if the only reason you’re using an SPA is because “it makes navigations faster,” then maybe it’s time to re-evaluate that. | 由于上周作者的文章 [“The balance has shifted away from SPAs”](https://nolanlawson.com/2022/05/21/the-balance-has-shifted-away-from-spas/) 引起了一些争议，故继续做了解释。作者表明之所以这样来评价 SPA 首先更多的是结合 Google 的 [Core Web Vitals](https://web.dev/vitals/)，引用下作者非常精彩的总结
> The only constant in software is change. Browsers have changed a lot over the years, but in many ways our habits as web developers have not really adjusted to fit the new reality. There’s a lot of prototyping and research yet to be done, and the one thing I’m sure of is that the best web apps in 10 years will look a lot different from the best web apps built today.


### 大前端
#### Framework
**From PHP to Next.js: What Trivago Learned Rewriting Its Web App**
[https://thenewstack.io/from-php-to-next-js-what-trivago-learned-rewriting-its-web-app/](https://thenewstack.io/from-php-to-next-js-what-trivago-learned-rewriting-its-web-app/)
Hotel search service Trivago rewrote its frontend in Typescript on the Next.js framework, replacing a PHP codebase on a homegrown JavaScript framework, Melody. | [WARP - A Web Application Rewrite Project](https://tech.trivago.com/post/2022-05-16-warp-a-web-application-rewrite-project/) | 使用 React 开发大型 Web 应用时都需要考虑哪些？

**Using Ultra, the new React web framework**
[https://blog.logrocket.com/using-ultra-new-react-web-framework/](https://blog.logrocket.com/using-ultra-new-react-web-framework/)
In this article, you’ll learn about a new React framework called Ultra, which uses Deno and React and focuses on using web streams and native features within the browser. | 国外前端社区甚是活跃，轮子满天飞

#### Bundler
**Faster JavaScript Builds with Metro**
[https://medium.com/airbnb-engineering/faster-javascript-builds-with-metro-cfc46d617a1f](https://medium.com/airbnb-engineering/faster-javascript-builds-with-metro-cfc46d617a1f)
How Airbnb migrated from Webpack to Metro and made the development feedback loop nearly instantaneous, the largest production build 50% faster, with marginal end-user runtime improvements. | Metro 是为 RN 打包而生的，Airbnb Web 团队从 Webpack 迁移到 Metro

#### Deno
**How we converted our Node.js library to Deno (using Deno)**
[https://www.edgedb.com/blog/how-we-converted-our-node-js-library-to-deno-using-deno](https://www.edgedb.com/blog/how-we-converted-our-node-js-library-to-deno-using-deno)
This is a broadly generalizable pattern for converting an existing Node.js module to Deno.

#### React
**React Native 资源更新增量包的优化实践**
[https://juejin.cn/post/7099686565365940261](https://juejin.cn/post/7099686565365940261)
shopee团队RN资源增量更新优化最佳实践方案FolderBsdp。优点如下：

- 降低了打补丁时的内存峰值
- 免了在客户端保留多余的 ZIP 包占用空间
- 额外提供了逐个文件的 MD5 精准校验，无需新增依赖库

**搞懂这12个Hooks，保证让你玩转React**
[https://juejin.cn/post/7101486767336849421](https://juejin.cn/post/7101486767336849421)
本文通过自定义hooks来带你学习hooks，并结合 ts，ahooks中的钩子，以案列的形式去演示。

#### Angular
**Angular’s Vision for the Future**
[https://blog.angular.io/angulars-vision-for-the-future-3cfca5e7b448](https://blog.angular.io/angulars-vision-for-the-future-3cfca5e7b448)
Improving and simplifying the developer experience is a major theme we started to work on in 2022 and will continue into 2023 and beyond.

#### JS
**JavaScript中的继承和组合**
[https://mp.weixin.qq.com/s/mJCoubKJne2uLCDcZoseMw](https://mp.weixin.qq.com/s/mJCoubKJne2uLCDcZoseMw)
继承与组合都是面向对象中代码复用的方式，了解各自有什么特点，可以让我们写出更简洁的代码，设计出更好的代码架构。

**Destructuring Arrays in JavaScript**
[https://programmingwithshahan.medium.com/destructuring-arrays-in-javascript-cf7530f013f9](https://programmingwithshahan.medium.com/destructuring-arrays-in-javascript-cf7530f013f9)
JS 结构入门，作者使用的插画挺有意思的

**Processing Arrays non-destructively: for-of vs. .reduce() vs. .flatMap()**
[https://2ality.com/2022/05/processing-arrays-non-destructively.html](https://2ality.com/2022/05/processing-arrays-non-destructively.html)
通过demo带你了解三种非破坏性数组函数的功能和使用场景。

**Building a button component**
[https://web.dev/building-a-button-component/](https://web.dev/building-a-button-component/)
A foundational overview of how to build color-adaptive, responsive, and accessible <button> components.

#### 低代码
**云音乐低代码：基于 CodeSandbox 的沙箱性能优化**
[https://mp.weixin.qq.com/s/R5NZdvAzHKG-MtTzQG8dcg](https://mp.weixin.qq.com/s/R5NZdvAzHKG-MtTzQG8dcg)
采用私有化部署的 CodeSandbox 来替换低代码平台的自研沙箱，本文主要介绍 CodeSandbox 沙箱性能优化过程。

#### Book
[https://books.goalkicker.com/JavaBook/](https://books.goalkicker.com/JavaBook/)
一本免费的 Java 学习材料，将 Stack Overflow 上面 Java 的常见解答，分门别类整理成了一本书。

**Jest 实践指南**
[http://github.yanhaixiang.com/jest-tutorial/](http://github.yanhaixiang.com/jest-tutorial/)

### 设计
**2022-2023设计趋势ISUX报告·NFT玩法应用篇**
[https://mp.weixin.qq.com/s/Gb79Ohipene-A-ANuPfG_g](https://mp.weixin.qq.com/s/Gb79Ohipene-A-ANuPfG_g)
本文尝试从NFT的应用与玩法出发，为大家梳理当下市场上涌现的具有一定代表性的NFT项目，以期提供一些启发。

**SYSTEM FONT STACK**
[https://systemfontstack.com/](https://systemfontstack.com/)

### 发现
**Sites vs. Apps defined: the Documents‐to‐Applications Continuum**
[https://ar.al/notes/the-documents-to-applications-continuum/](https://ar.al/notes/the-documents-to-applications-continuum/)
Web sites are documents; they are content‐centric. Sites are geared towards content consumption.
Web apps are tools; they are behaviour‐centric. Apps are geared towards content creation and manipulation.

### 更多
科技爱好者周刊（第 208 期）：晋升制度的问题[
http://www.ruanyifeng.com/blog/2022/05/weekly-issue-208.html](http://www.ruanyifeng.com/blog/2022/05/weekly-issue-208.html)
![image.png](https://cdn.nlark.com/yuque/0/2020/png/85771/1605930034828-7fc81343-651f-4a15-8465-eebe5a23cf61.png#crop=0&crop=0&crop=1&crop=1&height=31&id=C5Hpa&margin=%5Bobject%20Object%5D&name=image.png&originHeight=90&originWidth=2186&originalType=binary&ratio=1&rotation=0&showTitle=false&size=14325&status=done&style=none&title=&width=746)


欢迎加入，一起共建「前端小报」
