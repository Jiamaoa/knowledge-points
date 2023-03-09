# fe-interview

## HTML
### 如何理解 HTML 中的语义化标签?
- 使用恰当的标签来展示内容
- 例如段落用 p 标签
- 语义化标签指一眼看去就知道是什么意思，从而知道其用法的标签。作用是增强代码的可读性
- 如：视频<video> 音频<audio> 

### HTML5 有哪些新标签?
- video    视频
- audio    音频
- header   头部
- section  文档
- footer   尾部
- aside    侧边栏
- nav      导航
- main     主体
- article  内容
- mark     文本高亮
- progress 进度条

### Canvas 和 SVG 的区别是什么?
- canvas 是 HTML5 提供的新元素，通过 js 来绘制 2D 图形
- svg 是 xml 描述的 2D 图像，可以使用 js 给任意元素添加事件

### meta viewport 是做什么用的, 怎么写?
- 控制页面在移动端不要缩小显示
```js
<meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
```

## CSS
### BFC 是什么?

### 如何实现垂直居中?

- CSS 选择器优先级如何确定?

- 如何清除浮动?

### 两种盒模型(box-sizing)的区别?
- content-box: width === content宽度
- border-box: width === content宽度 + padding 宽度 + border 宽度

### css.reset 和 normalize.css 有什么区别？
-	reset 抛弃默认样式
-	normalize 统一各浏览器上的标签默认样式

## JS 基础题
- JS 的数据类型有哪些?

- 原型链是什么?

- 这段代码中的 this 是多少?

- JS 的 new 做了什么?

- JS 的立即执行函数是什么?

- JS 的闭包是什么?怎么用?

- JS 如何实现类?

- JS 如何实现继承?

- JS 垃圾回收是什么?

## JS 手写题
- 手写节流throttle、debounce

- 手写发布订阅

- 手写 AJAX

- 手写简化版 Promise

- 手写 Promise.all

- 手写深拷贝

- 手写数组去重

## DOM
- 请简述 DOM 事件模型

- 手写事件委托

- 手写可拖曳 div

## HTTP
- GET 和 POST 的区别有哪些?

- HTTP 缓存有哪些方案?

- HTTP 和 HTTPS 的区别有哪些?

- HTTP/1.1 和 HTTP/2 的区别有哪些?

- TCP 三次握手和四次挥手是什么?

- 说说同源策略和跨域

- Session、CookieLocalStorage、SessionStorage 的区别

## TypeScript
- TS 和 JS 的区别是什么?有什么优势?

- any、unknown、never的区别是什么?

- type 和 interface 的区别是什么?

- TS工具类型Partial、Required、Readonly、
Exclude、Extract、Omit、ReturnType的作用
和实现?

## Vue2
- Vue2 的生命周期钩子有哪些?数据请求放在哪
个钩子?

- Vue2 组件间通信方式有哪些?

- Vuex 用过吗?怎么理解?

- VueRouter 用过吗?怎么理解?

- 如何用路由守卫实现权限控制和加载进度?

- Vue2 是如何实现双向绑定的?

## Vue3
- Vue3 为什么使用 Proxy?

- Vue3 为什么使用 CompositionAPI?

- Vue3 对比 Vue2 做了哪些改动?

## React
- 虚拟 DOM 的原理是什么?

- DOM diff 算法是怎样的?

- React 如何实现组件间通信?

- React 有那些生命周期钩子函数? 数据请求放在哪个钩子里?

- Redux、ReduxThunk、ReduxSaga、dva、UmiJS 的区别和联系是什么?

- 什么是高阶组件?

## Node.js
- Node.js 的 EventLoop 是什么?

- 浏览器里的微任务和宏任务是什么?

- express.js 和 koa.js 的区别是什么?

## 算法
- 大数相加

- 两数之和

- 整数排序

- LazyMan

## 工程化
- 常见 loader 和 plugin 有哪些?二者的区别是
什么?
- webpack 如何解决开发时的跨域问题?

- 如何实现 tree-shaking?

- 如何提高webpack构建速度?

- webpack 与 vite 的区别是什么?

- webpack 怎么配置多页应用?

- swc、esbuild 是什么?

## 非技术
- 你遇到最难的 bug 是什么?

- 你为什么从上一家公司离职?

- 你的缺点是什么?

- 你的薪资要求是多少?

- 何时可以到岗?

- 你对加班的看法?

## 结果输出题
### [1,2,3].map(parselnt)
- a.x=a={}
- function a;a=2