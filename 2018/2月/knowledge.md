## JS 相关

- [Node定时器详解](http://www.ruanyifeng.com/blog/2018/02/node-event-loop.html)
- [原生JS数据绑定](https://mp.weixin.qq.com/s?__biz=MjM5MTA1MjAxMQ==&mid=2651227803&idx=1&sn=aa90993cf4711f99f6f8203cf2fb4e6b&chksm=bd495f1f8a3ed60972c9f8e66c8405265ec3b86c128ba44ede405872d758642d0c5286e60502&mpshare=1&scene=1&srcid=0224bSSD795JDR60ZynlFPfr#rd)
- [前端HTML5几种存储方式的总结](https://mp.weixin.qq.com/s?__biz=MzIzNTU2ODM4Mw==&mid=2247485935&idx=1&sn=b3faae7b8e21c4ff296d64b4dfaaeb58&chksm=e8e4647fdf93ed696db04e9b0dbd4fe1a06df6221ea1c2ede19ce1baf91d911be14110516d3b&mpshare=1&scene=1&srcid=02242xNs4l2IA16v4qOcJPA6#rd)
- [ES2018 & 2019](http://exploringjs.com/es2018-es2019/toc.html)
- [从一道题浅说 JavaScript 的事件循环](https://github.com/dwqs/blog/issues/61)
- [深入理解JavaScript系列](http://www.cnblogs.com/TomXu/archive/2011/12/15/2288411.html)
- [基于 Docker 打造前端持续集成开发环境](https://juejin.im/post/5a142d7b6fb9a0451170c2c7)
- [移动端自定义虚拟键盘](https://juejin.im/post/5a44c5eef265da432d2868f6)
- [前端本地文件操作与上传](https://juejin.im/post/5a193b4bf265da43052e528a)
- [Vue.js 源码解析](https://github.com/answershuto/learnVue)
- [数据动态绑定的简单实现](https://zhuanlan.zhihu.com/p/25003235?refer=e-mill)
- [解析神奇的 Object.defineProperty](https://segmentfault.com/a/1190000004346467)
- [【译】关于 Promise 的 9 个提示](https://juejin.im/post/5a9600526fb9a06333155141)
- Event Loop
	- [这一次，彻底弄懂 JavaScript 执行机制](https://juejin.im/post/59e85eebf265da430d571f89)
	- [Tasks, microtasks, queues and schedules](https://jakearchibald.com/2015/tasks-microtasks-queues-and-schedules/)
	- [书籍第三章](https://www.kancloud.cn/thinkphp/nodejs-mini-book)
	- [【朴灵评注】JavaScript 运行机制详解：再谈Event Loop](http://blog.csdn.net/lin_credible/article/details/40143961)


## CSS 相关

- [z-index深入理解](https://zhuanlan.zhihu.com/p/33984503)
- [CSS: 潜藏着的BFC](https://mp.weixin.qq.com/s/HlvuVCamWUY_euxCVTsT4Q)
- [借助HTML5 details,summary无JS实现各种交互效果](http://www.zhangxinxu.com/wordpress/2018/01/html5-details-summary-no-js-ux/)
- `height`、`min-height` 问题
    
```CSS
<style>
.parent{
	min-height: 300px;
    // height: 1px;
}
.child{
	height: 100%;
	background: red;
}
</style>

<div class="parent">
    <div class="child">1</div>
</div>
```
    
[Demo 地址](https://codepen.io/wangerxiao/pen/EQgqzr)

以上情况如何是 `child` 元素撑满父级元素：答案是给 `parent `一个具体高度 `height：1px`


## 性能相关

#### 图片加载优化

从三方面来说

- 图片相关
    - 图片格式 `webP`
    - 根据屏幕大小裁剪图片尺寸
- 图片加载相关
    - 首先加载首屏图片再加载别的
    - 懒加载
    - 预加载
- 网络相关
    - HTTP/2 多路复用
        - [Web性能优化与HTTP/2
](https://www.kancloud.cn/digest/web-performance-http2/74817)
        - [http2-explained](https://github.com/bagder/http2-explained/tree/master/zh)
    - 使用 cdn
    - 对于不升级的 HTTP 版本来说加载慢的原因
        - 每一个连接需要3次握手，RTT 需要时间
        - 慢启动
    
## 面试相关

- [前端面试题集锦](https://fe.padding.me/#/)
- [前端开发面试题 Star 8000+](https://github.com/markyun/My-blog/tree/master/Front-end-Developer-Questions/Questions-and-Answers)
- [专科面试阿里分享](https://juejin.im/post/5a92c23b5188257a6b06110b)
- [收集的面试题](https://github.com/calabash519/interview-questions)
- [前端面试题答案](https://github.com/yangshun/front-end-interview-handbook)
- [CSS基础面试题](https://funteas.com/topic/5a8f1a74f7f37aa60a177d86)

## PWA相关

- [网站渐进式增强体验(PWA)改造：Service Worker 应用详解
](https://lzw.me/a/pwa-service-worker.html)
- [第一本 PWA 中文书](https://github.com/SangKa/PWA-Book-CN)

## 计算机通用知识

- [HTTPS 科普](https://juejin.im/entry/5a8f5fd06fb9a06340522087)
- [油管上网络视频教学](https://www.youtube.com/user/eaterbc/playlists)
- [操作系统相关](https://pdos.csail.mit.edu/6.828/2012/schedule.html)

## 工具

- [前端文档集合](https://www.docschina.org/home/doc)
- [标注工具](http://www.biaonimeia.com/)
- [VSCode 代码截图工具](https://github.com/octref/polacode)
- [Chrome 插件推荐](https://funteas.com/topic/5a9461649a2833b84c481b3b)

