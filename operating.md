# 提升公司知名度的提议（技术方面）

## 一、 对公司必要项目进行SEO优化，利用搜索引擎进行引流

### 1. 将 console 项目『首页、发行列表页、发行详情页』等不需要用户权限的页面、首次加载页面时，在服务端进行渲染

*原因：*

- 搜索引擎只会抓取静态页面内容，现有项目都是在浏览器通过Ajax加载数据，异步渲染界面，搜索引擎获取不到页面内容

*参考：*

- [浅谈SPA、SEO、SSR](https://www.jianshu.com/p/fcb98533bc18)

### 2. 改进节点渲染流程，对节点管理者欲免费开放的节点，也进行服务端渲染

*原因：*

- 现在节点渲染时，直接会把自己组件渲染出来，其内部内容，为异步加载，且对搜索引擎不可变，所以最好能在服务端把自定义组件展开，到浏览器时，重新对自定义组件进行组装 （目前还没有完全实验成功）


### 3. 对现有 www 子域名下的项目进行改造，加入对公司以及项目的介绍

*原因：*

- www子域名对一个网站来说权重是最高的，所以要充分利用起来

### 4. 对需要被收录的每个页面慎重的设置TDK，把节点设置TDK的权限酌情开放给用户

*原因：*

-  网页TDK分别是Title、Description和Keywords。是网页的最基础信息，网站SEO的先行步骤之一。
-  目前我们项目只有 Title，并没有Description和Keywords，所以需要设置一下，这里需要产品或运营的帮忙

*参考：*

- [关于网站TDK三大标签的重要性](https://zhuanlan.zhihu.com/p/105015743)

### 5. 增设移动端网站

*原因：*

- 当移动端用户访问网站时，至少应有公司及项目的介绍内容，并且体验良好，只有这样，才能引导用户在PC上真正的使用我们的平台

### 6. 规范代码，使用SEO友好的方式去写

*原因：*

- 合理使用标签，如 header footer nav 等
- 合理使用属性，如 img 标签的 alt 属性
- ......

*参考：*

* [百度搜索引擎优化指南 2.0](https://developer.baidu.com/resources/online/doc/seo/search-engine-optimization-guide.html)
* [Google搜索引擎优化 (SEO) 指南](https://support.google.com/webmasters/answer/7451184?hl=zh-Hans)
* [打造方便Google处理的网站的步骤](https://support.google.com/webmasters/answer/40349?hl=zh-Hans)

## 二、为运营准备好统计和分析的工具

### 1. 增加统计功能

*原因：*

- 可以使运营更清晰的掌握用户信息

*参考：*

- 百度统计 [https://tongji.baidu.com](https://tongji.baidu.com)
- Google Search Console [https://search.google.com/search-console](https://search.google.com/search-console)

### 2. 增加用户分析功能

*原因：*

- 可以更好的辅助运营提出改进建议

*参考：*

- 百度流量研究 [https://tongji.baidu.com/research](https://tongji.baidu.com/research)
- Google Analytics [https://analytics.google.com/analytics/web/provision/?authuser=0#/provision](https://analytics.google.com/analytics/web/provision/?authuser=0#/provision)