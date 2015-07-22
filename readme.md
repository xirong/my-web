# 说明
学习 WEB 需要的内容整理，包括前端思想、框架、css、js（框架）、http协议等等 ……
欢迎 `fork` 后贡献自己的，提交 `RP` 即可，一起努力打造更好的 `http` 学习资料~

# 目录

# HTTP 协议
### HTTP Response Code
- [理解HTTP/304响应](http://www.cnblogs.com/ziyunfei/archive/2012/11/17/2772729.html)  English version [Understanding HTTP/304 Responses](http://www.telerik.com/blogs/understanding-http-304-responses)

## HTTPS
什么是HTTPS？ [zh-wikipedia 超文本传输安全协议](http://zh.wikipedia.org/zh/%E8%B6%85%E6%96%87%E6%9C%AC%E4%BC%A0%E8%BE%93%E5%AE%89%E5%85%A8%E5%8D%8F%E8%AE%AE) （目前大陆已经被封需要翻墙才能阅读，可以阅读英文版[en-wikipedia HTTPS](http://en.wikipedia.org/wiki/HTTPS)）

微博[@BAIDU罗成](http://weibo.com/u/1822556675)的一篇文章 [中国互联网全站HTTPS的时代已经到来](http://blog.csdn.net/luocn99/article/details/39777707)对HTTPS的原理、遇到的问题、有哪些影响做出了介绍，比较容易理解。

百度在2015年3月份全站正式转入HTTPs，下面的几篇文章正是其运维团队的总结经验，很有阅读价值。
- [全站 https 时代的号角 : 大型网站的 https 实践系列](http://op.baidu.com/2015/04/https-index/)
- [大型网站的 HTTPS 实践（一）—— HTTPS 协议和原理](http://op.baidu.com/2015/04/https-s01a01/)
- [大型网站的 HTTPS 实践（二）——HTTPS 对性能的影响](http://op.baidu.com/2015/04/https-s01a02/)
- [大型网站的 HTTPS 实践（三）——基于协议和配置的优化](http://op.baidu.com/2015/04/https-s01a03/)
- [大型网站的 HTTPS 实践（四）——协议层以外的实践](http://op.baidu.com/2015/04/https-s01a04/)

#### 既然 HTTPS 解决了我们关注的隐私、安全问题，那么为什么这么少的网站使用呢？
- [Stackoverflow.com: the road to SSL](http://nickcraver.com/blog/2013/04/23/stackoverflow-com-the-road-to-ssl/) statckoverflow 的创始人解答，大型网站的转型需要众多依赖的组件、服务商都支持HTTPS，最关键的还是CA证书问题。
- [知乎-如何看待百度全站搜索进入 HTTPS 时代？](http://www.zhihu.com/question/28379088)


#### 业界的支持
- [HTTPS as a ranking signal](http://www.googlewebmastercentral.blogspot.ch/2014/08/https-as-ranking-signal.html) 2014-08 google宣布全站HTTPS化，并且调整page rank 算法，搜索中支持搜索 HTTPS 的站点。
- 2015-03 月份百度全站 HTTPS 化，并且在2015-05-25日宣布[百度开放收录https站点公告](http://zhanzhang.baidu.com/wiki/392)，从此百度也能搜索HTTPS的站点内容了。

#### 如何申请
- [https的免费申请流程](http://ljinkai.github.io/2015/06/30/https-2/)

## HTTP/2
- [Home page for http/2](http://http2.github.io/) http/2 协议官网发布网站，内容更新均在此发布
- [Http/2 wikipedia](http://en.wikipedia.org/wiki/HTTP/2) 维基百科 http/2 资料，很多参考连接
- [http2 详解（中文）](https://www.gitbook.com/book/ye11ow/http2-explained)， English version follow this [http2 explained](http://daniel.haxx.se/http2/)，详细讲述http/1.1 的各种不足以及http/2所有的各种优化等，值得一看。github地址为[http2-explained-chinese](https://github.com/ye11ow/http2-explained-chinese)

[@qgy18](https://twitter.com/qgy18)在他的小站中写了三篇对比 HTTP1 和 HTTP2 性能优化的文章，对比两种协议里面为了共同的浏览体验、性能所做出的不同的优化，值得看一看。同时，他的小站已经全面支持 HTTPS，赞一个！
- [HTTP/2 与 WEB 性能优化（一）](https://www.imququ.com/post/http2-and-wpo-1.html)
- [HTTP/2 与 WEB 性能优化（二）](https://www.imququ.com/post/http2-and-wpo-2.html)
- [HTTP/2 与 WEB 性能优化（三）](https://www.imququ.com/post/http2-and-wpo-3.html)

# 前端开发
- [Web前端知识体系大全](http://www.cnblogs.com/wangfupeng1988/p/4649709.html) cnblog 上的一哥们写的，挺全面的。
- [Web 基本法则-现代 web 开发最佳实践](https://developers.google.com/web/fundamentals/) google 官方现代多设备 web 开发指南，特别是针对pc web、移动端的设计原则实践，值得每个web开发人员仔细阅读。
- [前端代码规范及最佳实践](http://coderlmn.github.io/code-standards/) [Isobar公司](http://www.isobar.com/global/)的创意技术部（前端工程）开发web应用的规范，此连接为中文翻译版本，英文版本见 [github-isobar-idev](https://github.com/isobar-idev/code-standards)
- [前端开发-好习惯、用法](http://coderlmn.github.io/Front-End-Development-Guidelines/) 一些不错的建议，很多在前面的文章中也有描述。
- [比较全面的前端面试资料收集](https://github.com/hawx1993/Front-end-Interview-questions)

# javascript
- [MDN javascript资料](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript) firefox js 资料库

# html5
- [极客学院-h5学习计划系列视频](http://e.jikexueyuan.com/html5.html?hmsr=osc_word_html5_07.01)

# 性能优化
- [书籍：高性能网站建设](http://book.douban.com/subject/26411563/)，[高性能网站-Web开发者性能优化最佳实践](http://book.douban.com/subject/4719162/)
- [书籍：High Performance Browser Networking](http://book.douban.com/subject/25856314/) 全书以性能优化为主线，从TCP、UDP 和TLS 协议讲起，解释了如何针对这几种协议和基础设施来优化应用。然后深入探讨了无线和移动网络的工作机制。最后，揭示了HTTP 协议的底层细节，同时详细介绍了HTTP 2.0、 XHR、SSE、WebSocket、WebRTC 和DataChannel 等现代浏览器新增的具有革命性的新能力。（-豆瓣简介）
- [Web性能优化：What? Why? How?](http://www.cnblogs.com/dojo-lzz/p/4591446.html) 文章从`减少http请求`、`页面内优化`、`启用缓存`、`减少下载量`、`网络优化`等几个方面进行阐述如何让页面加载更快！

# 前后端交互
- [撰写合格的REST API：设计准则](http://mp.weixin.qq.com/s?__biz=MzA3NDM0ODQwMw==&mid=208060670&idx=1&sn=ce67b8896985e8448137052b338093e0) 从RFC一致性、接口的安全性、丰富的接口文档、访问限制等方面进行阐述，通俗易懂，很是推荐阅读。
