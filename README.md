# 带你入门前端工程
前端工程化，其实是软件工程在前端方面的应用。什么是软件工程？来看一下百度百科的定义：
>软件工程是一门研究用工程化方法构建和维护有效的、实用的和高质量的软件的学科

换句话说，工程化的目的就是为了提升团队的开发效率。例如大家所熟悉的构建打包、性能优化、自动化部署等知识，都属于工程化的内容。

我写这本小书的原因，是想对过去两年的工程化实践经验和学习心得做一个总结。希望能全面地、系统地对前端工程化知识做一个总结。

小书大部分的内容都是以理论知识 + 代码示例 + 图片的方式来讲解的，努力争取让读者更容易理解。另外还有小部分的章节在讲解完理论知识后，还有相应的实践教程。例如前端监控这一节，在讲解完前端监控原理后，将会教你如何利用现有的监控工具对项目实行监控。

可能有人会问，什么时候开始做工程化？我认为在需求评审阶段就可以做工程化了，根据需求选用适当的技术栈（技术选型），然后制定相关规范...

## 在线访问
* [访问入口一](https://woai3c.gitee.io/introduction-to-front-end-engineering)
* [访问入口二](https://woai3c.github.io/introduction-to-front-end-engineering/)

## 目录
1. 技术选型：如何进行技术选型？
2. 统一规范：如何制订规范并利用工具保证规范被严格执行？
3. 前端组件化：什么是模块化、组件化？
4. 测试：如何写单元测试和 E2E（端到端） 测试？
5. 构建工具：构建工具有哪些？都有哪些功能和优势？
6. 自动化部署：如何利用 Jenkins、Github Actions 自动化部署项目？
7. 前端监控：讲解前端监控原理及如何利用 sentry 对项目实行监控。
8. 性能优化（一）：如何检测网站性能？有哪些实用的性能优化规则？
9. 性能优化（二）：如何检测网站性能？有哪些实用的性能优化规则？
10. 重构：为什么做重构？重构有哪些手法？
11. 微服务：微服务是什么？如何搭建微服务项目？
12. Severless：Severless 是什么？如何使用 Severless？

微服务、Severless 按理说不属于工程化的内容，但从提升开发效率的角度来看，也可以归纳到这一范围。

目录的顺序是以一个项目的生命周期来分配的：
1. 接到新需求，进行需求评审后根据具体情况做技术选型。
2. 开发前需要统一规范。
3. 学会模块化、组件化，对于写代码很有好处。
4. 开发完，需要对代码进行测试。
5. 构建打包。
6. 部署上线。
7. 对项目进行监控，随时发现问题。
8. 根据项目运行情况决定是否要做性能优化。
9. 项目越来越复杂，需要重构以提高可维护性。
10. 项目越来越大，可以考虑是否用微服务对其进行拆分（或者使用 git submodule 和 monorepo 的方式管理项目）。
11. 不想自己管理服务器或数据库，可以考虑使用 Serverless。

## 注意
本书的定位是**入门**级教程，主要对前端能接触到的工程知识做一个较全面的介绍。适合对前端工程化不了解或了解得不多的“菜鸟”同学。如果你是个“老鸟”，那本书可能不太适合你。

另外，建议读者在阅读本书时，能够配合书本的实践部分去做实践。如果读者能够严格按照指示去做实践，在阅读完本书后，不仅会收获前端工程化的理论知识，还会获得对应的实践经验。

## 你会学到什么？
* 对前端工程化有一个全面、清晰的了解
* 为架构师之路打下扎实的基础

## 适宜人群
* 想学习工程化的前端
* 具备基础的 HTML、CSS、JavaScript 知识

## 扩展
由于这本小书主要就是针对一个技术点讲解它是什么？怎么做？对于更细的点不会有深入的讲解。为了弥补这一点，我写了一些其他文章来对此做为补充：
* [前端规范](https://woai3c.github.io/front-end-specification/)
* [手把手教你写一个脚手架](https://github.com/woai3c/Front-end-articles/issues/22)
* [深入了解 webpack 模块加载原理](https://github.com/woai3c/Front-end-articles/issues/7)
* [实现一个 webpack loader 和 webpack plugin](https://github.com/woai3c/Front-end-articles/issues/6)
* [从 rollup 初版源码学习打包原理](https://github.com/woai3c/Front-end-articles/issues/5)

## License
MIT

## 赞助
![](https://github.com/woai3c/nand2tetris/blob/master/img/wx.jpg)
![](https://github.com/woai3c/nand2tetris/blob/master/img/zfb.jpg)
