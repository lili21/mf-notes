# module federation
> 学习过程中收集的一些资料

- ~~[作者写的介绍文章](https://indepth.dev/webpack-5-module-federation-a-game-changer-in-javascript-architecture)~~
  - 配置已过时，无法在新版wepback5中运行
  - `exposes`中的`key`需要以相对路径开头

- [作者写的介绍文章](https://medium.com/swlh/webpack-5-module-federation-a-game-changer-to-javascript-architecture-bcdd30e02669)
  - 可正常运行

- [module-federation-examples]
  - MF作者创建和维护的示例，更新及时，用例丰富，非常好的参考资料

- [angular11-microfrontends](https://github.com/module-federation/module-federation-examples/blob/master/angular11-microfrontends/projects/mdmf-shell/src/app/utils/federation-utils.ts)
  - [module-federation-examples]中angular11微前端示例
  - 把这个单独拉出来是因为这个示例展示了如何在运行时动态加载remote module

- ~~[mfe-webpack-demo](https://github.com/ScriptedAlchemy/mfe-webpack-demo/tree/master/packages)~~
  - MF作者创建的基于MF，简单的微前端架构
  - 配置已过时，但对想要基于MF做微前端的有一定参考意义


- [MF Proposal](https://github.com/webpack/webpack/issues/10352)
  - MF特性提案
  - 包含MF作者和webpack作者关于该特性的交流

- [module federation官方文档](https://webpack.js.org/concepts/module-federation/)
  - 有点晦涩，概念上的讲解

- [MF插件中shared配置的详细说明](https://github.com/webpack/webpack.js.org/issues/3757)
  - [module-federation-examples]中会有复杂的`shared`配置，比如`singleton`, `version`等
  - 这个issue是webpack作者提交的，对于`shared`配置有详细说明

- [MF作者分享](https://www.youtube.com/watch?v=-ei6RqZilYI)
  - 讲了一些内部架构，原理
  - 正在做的事情，即将支持的特性

[module-federation-examples]: https://github.com/module-federation/module-federation-examples