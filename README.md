- [🚴‍♂️ 基础知识](#️-基础知识)
  - [样式布局](#样式布局)
      - [1. 不定宽高元素水平垂直居中有哪些实现方式？](#1-不定宽高元素水平垂直居中有哪些实现方式)
      - [2. rem 是什么？跟 px 如何转换？说下原理及使用场景](#2-rem-是什么跟-px-如何转换说下原理及使用场景)
      - [3. 同一套代码如何适配PC、移动两个端？](#3-同一套代码如何适配pc移动两个端)
      - [4. position 的几个值代表啥意思？是否脱离文档流？分别是相对于谁定位的？](#4-position-的几个值代表啥意思是否脱离文档流分别是相对于谁定位的)
  - [javascript](#javascript)
      - [1. promise 的实现原理是什么？讲一下链式调用的过程。](#1-promise-的实现原理是什么讲一下链式调用的过程)
      - [2. 说说事件委托。](#2-说说事件委托)
      - [3. js 事件循环是什么？为什么要引入 js 事件循环，并介绍下它的原理？](#3-js-事件循环是什么为什么要引入-js-事件循环并介绍下它的原理)
      - [4. 哪些地方存在 this 指向问题？如何解决？](#4-哪些地方存在-this-指向问题如何解决)
      - [5. 什么是闭包？](#5-什么是闭包)
  - [前端存储](#前端存储)
      - [1. 前端存储有哪些方式？cookie 跟 indexDB 有啥区别？是否持久化？](#1-前端存储有哪些方式cookie-跟-indexdb-有啥区别是否持久化)
- [🤺 前端框架/库](#-前端框架库)
  - [React](#react)
      - [1. react hooks 跟之前的 class 写法有什么不同？有哪些优势？](#1-react-hooks-跟之前的-class-写法有什么不同有哪些优势)
      - [2. react hooks 为什么没有生命周期？如果要使用生命周期怎么做？](#2-react-hooks-为什么没有生命周期如果要使用生命周期怎么做)
      - [3. 了解 fiber 吗？它的原理是什么？](#3-了解-fiber-吗它的原理是什么)
      - [4. 讲讲 React 技术栈的最佳实践](#4-讲讲-react-技术栈的最佳实践)
      - [5. React 性能优化需要考虑哪些？](#5-react-性能优化需要考虑哪些)
      - [6. React 依赖注入是怎么实现的？](#6-react-依赖注入是怎么实现的)
  - [Vue](#vue)
      - [1. 讲讲 Vue 技术栈的最佳实践。](#1-讲讲-vue-技术栈的最佳实践)
  - [微前端](#微前端)
      - [1. 微前端框架（例如qiankun）实现js隔离的原理是什么？css 是如何隔离？常见微前端框架有哪些？能否比较下他们的实现原理？为什么选择 qiankun？](#1-微前端框架例如qiankun实现js隔离的原理是什么css-是如何隔离常见微前端框架有哪些能否比较下他们的实现原理为什么选择-qiankun)
      - [2. 微前端使用过程中遇到哪些问题？挑一个难点讲下。](#2-微前端使用过程中遇到哪些问题挑一个难点讲下)
  - [低代码](#低代码)
      - [1. 低代码开发平台如何实现？比如说从拖动组件到生成元素到我们应用页面上的过程是怎样的？](#1-低代码开发平台如何实现比如说从拖动组件到生成元素到我们应用页面上的过程是怎样的)
  - [跨端开发（移动端/桌面端）](#跨端开发移动端桌面端)
      - [1. 介绍下 Flutter，并说下 Flutter 和 RN 的区别。](#1-介绍下-flutter并说下-flutter-和-rn-的区别)
- [⚔️ 工程化](#️-工程化)
      - [1. 结合过往经验，如何理解前端工程化？](#1-结合过往经验如何理解前端工程化)
  - [模块化](#模块化)
  - [组件化](#组件化)
      - [1. 封装一个模态弹窗需要考虑哪些点？](#1-封装一个模态弹窗需要考虑哪些点)
  - [错误监控](#错误监控)
      - [1. 错误上报/捕获全局 sdk 如何写？需要捕获哪些东西？在哪写？](#1-错误上报捕获全局-sdk-如何写需要捕获哪些东西在哪写)
  - [构建工具](#构建工具)
      - [1. webpack plugin 跟 loader 有何不同？有没有使用 plugin 写过一些插件？](#1-webpack-plugin-跟-loader-有何不同有没有使用-plugin-写过一些插件)
  - [devOps](#devops)
      - [1. 说说你对 devOps 的理解。](#1-说说你对-devops-的理解)
      - [2. CI/CD这些了解吗？说下自己之前的使用经验。](#2-cicd这些了解吗说下自己之前的使用经验)
- [☎️ 数据通信](#️-数据通信)
  - [http \& http2](#http--http2)
      - [1. http2 有什么新的东西，哪些场景下适用？](#1-http2-有什么新的东西哪些场景下适用)
  - [JSBrange](#jsbrange)
      - [1. web 与原生应用如何交互通信？](#1-web-与原生应用如何交互通信)
  - [websocket](#websocket)
      - [1. websocket 是什么？有哪些应用场景？](#1-websocket-是什么有哪些应用场景)
- [👑 性能优化](#-性能优化)
  - [语义化 \& SEO](#语义化--seo)
  - [高性能页面](#高性能页面)
      - [1. web缓存有哪些？](#1-web缓存有哪些)
      - [2. 如何全链路优化应用访问性能？](#2-如何全链路优化应用访问性能)
      - [3. svg、base64 格式图片跟 png、jpg 等格式有啥不同？](#3-svgbase64-格式图片跟-pngjpg-等格式有啥不同)
      - [4. 如果一个页面有很多图片，怎么优化这个页面的加载速度？](#4-如果一个页面有很多图片怎么优化这个页面的加载速度)
  - [架构设计](#架构设计)
      - [1. 高性能页面如何实现？高可用方面前端能做些啥？](#1-高性能页面如何实现高可用方面前端能做些啥)
      - [2. 讲一下哪个项目最能体现你的技术架构设计能力？](#2-讲一下哪个项目最能体现你的技术架构设计能力)
      - [3. 一个好的架构设计需要关注哪些方面？](#3-一个好的架构设计需要关注哪些方面)
      - [4. 架构上如何保证 node 服务的高可用？](#4-架构上如何保证-node-服务的高可用)
  - [监控预警](#监控预警)
      - [1. 官网类应用是如何提升 SLA 实现高可用的？你采取了哪些前端措施？](#1-官网类应用是如何提升-sla-实现高可用的你采取了哪些前端措施)
      - [2. 如何去避免 node 内存泄露这种问题？如何更好的监控？](#2-如何去避免-node-内存泄露这种问题如何更好的监控)
- [🎯 web 安全](#-web-安全)
      - [1. web 安全中跟前端有关的攻击有哪些？是什么原理？](#1-web-安全中跟前端有关的攻击有哪些是什么原理)
      - [2. cookie 的安全问题怎么避免？](#2-cookie-的安全问题怎么避免)
- [🤡 兼容](#-兼容)
- [⚓️ 后端知识等](#️-后端知识等)
  - [node.js](#nodejs)
      - [1. node 的动态扩展如何实现？](#1-node-的动态扩展如何实现)
  - [linux运维](#linux运维)
      - [1. 服务器操作、Linux 命令这块有哪些实践？](#1-服务器操作linux-命令这块有哪些实践)
- [📚 项目管理](#-项目管理)
  - [项目经验](#项目经验)
      - [1. 如果给你一个代码年久失修、文档缺失的项目，你准备如何去整理文档，方便后续维护？](#1-如果给你一个代码年久失修文档缺失的项目你准备如何去整理文档方便后续维护)
  - [沟通协作](#沟通协作)
      - [1. 前端如何与后端更高效的协作开发？](#1-前端如何与后端更高效的协作开发)
  - [敏捷Scrum](#敏捷scrum)
      - [1. 敏捷 scrum 是如何开展各项活动的？逐个介绍下。](#1-敏捷-scrum-是如何开展各项活动的逐个介绍下)

> 根据个人亲身面试经验积累的前端面试题库（含答案解析）

# 🚴‍♂️ 基础知识

## 样式布局

#### 1. 不定宽高元素水平垂直居中有哪些实现方式？

Flex、Grid、table-cell、绝对定位配合transform、以及JavaScript等。

#### 2. rem 是什么？跟 px 如何转换？说下原理及使用场景

#### 3. 同一套代码如何适配PC、移动两个端？

#### 4. position 的几个值代表啥意思？是否脱离文档流？分别是相对于谁定位的？

## javascript

#### 1. promise 的实现原理是什么？讲一下链式调用的过程。

Promise 主要是通过`状态机`和`回调函数`来实现异步编程的。它是 JavaScript 中处理异步操作的一种机制，实现原理是**链式调用**。

当执行异步操作时，Promise 对象会立即返回一个 promise 实例，该实例会在未来的某个时刻返回异步操作的结果。这个 promise 实例可以在代码中被传递、处理和操作。

一个 promise 实例`状态机`的3种状态：
- 等待（Pending，实例被创建）
- 已完成（Resolved，返回异步操作的结果）
- 已拒绝（Rejected，出现错误时，返回错误信息）

需要注意的是：
- 异步的操作结果只有一个，也就是说 then 和 catch 里面的回调函数参数只能接受 1 个
- 创建 promise 时 Resolved 或 Resolved 写多次也只会执行一次（一旦状态机处于 Resolved 和 rejected ，状态就不会再变了。）
- `.catch()` 其实是`.then()` 方法的语法糖，只接受 rejected 态的数据。
- 如果不设置回调函数，Promise 内部抛出的错误，不会反应到外部，会触发[`unhandledrejection`](https://developer.mozilla.org/zh-CN/docs/Web/API/Window/unhandledrejection_event "unhandledrejection")事件

Promise 也还是基于回调函数来实现的，只不过是把回调封装在了内部，使用上是通过 then/catch 方法的成功/错误回调函数与 promise 的异步结果做关联的。

promise 对象实例存在的几种地方：
- new Promise()
- then的返回值
- catch 的返回值
- finally 的返回值
- async 函数的返回值
- Promise.resolve(xxx)

**链式调用**的定义：

连续执行两个或者多个异步操作是一个常见的需求，在上一个操作执行成功之后，开始下一个的操作，并带着上一步操作所返回的结果。

如：
``` js
fetch('https://api.example.com/data')
  .then(response => response.json())
  .then(data => console.log(data))
  .catch(error => console.error(error));
```

`链式调用原理`：
Promise 链式调用的原理在于每个 then() 方法都会返回一个新的 Promise 对象，这个新的 Promise 对象可以接收到前一个 Promise 对象的状态，并将前一个 Promise 对象的状态传递给下一个 then() 方法。
#### 2. 说说事件委托。

**事件委托**：通过共同的父节点设置事件统一执行子节点的事件，只需设置一个父节点的事件绑定，能减少内存占用。

```html
<!--未进行事件委托-->
<div id="box">
    <input type="button" id="add" value="添加" />
    <input type="button" id="remove" value="删除" />
    <input type="button" id="move" value="移动" />
    <input type="button" id="select" value="选择" />
</div>
<script>
window.onload = function(){
    var Add = document.getElementById("add");
    var Remove = document.getElementById("remove");
    var Move = document.getElementById("move");
    var Select = document.getElementById("select");
    
    Add.onclick = function(){
        alert('添加');
    };
    Remove.onclick = function(){
        alert('删除');
    };
    Move.onclick = function(){
        alert('移动');
    };
    Select.onclick = function(){
        alert('选择');
    }
}
</script>

<!--进行事件委托-->
<div id="box">
    <input type="button" id="add" value="添加" />
    <input type="button" id="remove" value="删除" />
    <input type="button" id="move" value="移动" />
    <input type="button" id="select" value="选择" />
</div>
<script>
window.onload = function(){
    var oBox = document.getElementById("box");
    oBox.onclick = function (ev) {
        var ev = ev || window.event;
        var target = ev.target || ev.srcElement;
        if(target.nodeName.toLocaleLowerCase() == 'input'){
            switch(target.id){
                case 'add' :alert('添加');break;
                case 'remove' :alert('删除');break;
                case 'move' :alert('移动');break;
                case 'select' :alert('选择');break;
            }
        }
    }
}
</script>
```

#### 3. js 事件循环是什么？为什么要引入 js 事件循环，并介绍下它的原理？
js 事件循环（EventLoop）指的是 JS 引擎在执行异步代码时会将异步任务分成两个队列（宏任务、微任务）去执行，当前可执行代码执行完以后会按顺序执行微任务队列，等微任务队列执行完又开始执行宏任务队列的下一个任务，再然后继续执行微任务队列......循环往复，所以成为 JS 事件循环。

引入 js 事件循环的目的：
> 解决 js 单线程的阻塞问题。

更细致的原理讲解可参考：https://juejin.cn/post/7229372047414902839

**EventLoop**
- 在JavaScript中，任务被分为MacroTask（宏任务）和MicroTask（微任务）两种。
    - MicroTask
        - process.nextTick（node独有）
        - Promise（new Promise()内的程序是同步代码，而 then 部分的程序才是 MicroTask 任务）
        - Object.observe(废弃)
        - MutationObserver
        - 因为 async await 本身就是 promise+generator 的语法糖。所以 await 后面的代码是 microtask。
    - MacroTask
        - script(整体代码)
        - setTimeout
        - setInterval
        - setImmediate（node独有）
        - MessageChannel
        - I/O
        - UI rendering
    - 执行顺序：在同一个上下文（执行环境）中，总的执行顺序为：执行同步代码 —> microTask（微任务） —> macroTask（宏任务）
- 分类
    - 浏览器的Event loop
    - Nodejs的EventLoop

```js
setTimeout(function () {
    console.log(1);
},0);
console.log(2);
process.nextTick(() => {
    console.log(3);
});
new Promise(function (resolve, rejected) {
    console.log(4);
    resolve()
}).then(res=>{
    console.log(5);
})
setImmediate(function () {
    console.log(6)
})
console.log('end');
// 2 4 end 3 5 1 6
```
```js
var outer = document.querySelector('.outer');
var inner = document.querySelector('.inner');
new MutationObserver(function() {
    console.log('mutate');
}).observe(outer, {
    attributes: true
});
function onClick() {
    console.log('click');
    setTimeout(function() {
        console.log('timeout');
    }, 0);
    Promise.resolve().then(function() {
        console.log('promise');
    });
    outer.setAttribute('data-random', Math.random());
}
inner.addEventListener('click', onClick);
outer.addEventListener('click', onClick);

// 点击 click，结果控制台输出：click、promise、mutate、click、promise、mutate、timeout、timeout
// 运行 inner.click()，结果控制台输出：click、click、promise、mutate、promise、timeout、timeout，注意：对一个节点添加观察器，就像使用addEventListener方法一样，多次添加同一个观察器是无效的，回调函数依然只会触发一次，因此此处虽然两次调用 observe(outer, {attributes: true})，但只有一次有效，只打印一次 mutate
```
```js
console.log('1');
async function async1() {
    console.log('2');
    await async2();
    console.log('3');
}
async function async2() {
    console.log('4');
}
 
process.nextTick(function() {
    console.log('5');
})
 
setTimeout(function() {
    console.log('6');
    process.nextTick(function() {
        console.log('7');
    })
    new Promise(function(resolve) {
        console.log('8');
        resolve();
    }).then(function() {
        console.log('9')
    })
})
 
async1();
 
new Promise(function(resolve) {
    console.log('10');
    resolve();
}).then(function() {
    console.log('11');
});
console.log('12');
// 1 2 4 10 12 5 11 3 6 8 7 9
```

#### 4. 哪些地方存在 this 指向问题？如何解决？

- 全局作用域下，this 指向 window 对象
- 对象内部方法中的 `this` 指向调用该方法的对象
- 构造函数中使用 `this` 关键字时，`this` 指向新创建的对象实例
- 箭头函数本身没有 `this` 绑定，它的 `this` 是继承自外层作用域的
#### 5. 什么是闭包？

**闭包**：闭包是指有权访问另一个函数作用域中的变量的函数。创建闭包的常见方式就是在一个函数内部创建一个引用了函含数内部的私有变量的函数。
- 作用域链：包含闭包的作用域、包含该闭包的外部函数的作用域、全局作用域
- 闭包的缺点：当该闭包（函数）一直存在时，这个闭包的引用的外部变量的函数的作用域会一直保留在内存中而不会销毁。
- 闭包的用途
    - 块级作用域（匿名自执行函数 IIFE）
    - 私有变量
        - 私有变量的问题：定义特权方法需要使用构造函数
        - 静态私有变量：静态私有变量可以解决定义特权需要使用构造函数的问题
    - 静态私有变量
    - 模块模式（单例）
    - 结果缓存
    - 柯里化


```js
// 示例：闭包的用途

// 块级作用域（匿名自执行函数 IIFE）
function func(){
    // 块级作用域
    (function(){
        for(var i=0;i<10;i++){
            console.log(i)
        }
    })()
    // i 不存在
    console.log(i)
}

// 私有变量
function Person(){
    // 私有变量
    var _name
    // 特权方法
    this.getName = function(){
        return _name
    }
    // 特权方法
    this.setName = function(name){
        _name = name
    }
}
var person = new Person()
person.setName('person')
person.getName()

// 静态私有变量
function Person(){}
(function(){
    Person = function(){}
    // 私有变量
    var _name
    // 公有方法
    Person.prototype.getName = function(){
        return _name
    }
    // 公有方法
    Person.prototype.setName = function(name){
        _name = name
    }
})()
var person = new Person()
person.setName('person')
person.getName()

// 模块模式（单例）
var application = function(){
    // 私有变量
    var components = new Array()
    // 返回公有属性和方法
    return {
        getComponents: function(){
            return components
        }
    }
}

// 增强模块模式
var application = function(){
    // 私有变量
    var components = new Array()
    // 公有
    var app = {}
    app.getComponents = function(){
        return components
    }
    // 返回公有副本
    return app
}
```
```js
// 测试题
function fun(n, o) {
    console.log(o);
    return {
        fun: function(m) {
            return fun(m, n);
        }
    };
}

var a = fun(0); // ?
a.fun(1); // ?
a.fun(2); // ?
a.fun(3); // ?
var b = fun(0).fun(1).fun(2).fun(3); // ?
var c = fun(0).fun(1); // ?
c.fun(2); // ?
c.fun(3); // ?
```

## 前端存储

#### 1. 前端存储有哪些方式？cookie 跟 indexDB 有啥区别？是否持久化？
前端存储方式有多种，包括：
1. `Cookie`：通过在客户端保存键值对的方式进行存储，在后续请求中可以携带 Cookie 信息进行验证和识别。Cookie 有一定的大小限制（通常为 4KB），且需要在每个 HTTP 请求中传递，可能会影响网络性能。

2. `Local Storage`：HTML5 新增的存储方式，将数据以键值对的形式存储在客户端的本地文件中，可以长期保存数据，并且与 Cookie 不同，不会在每次 HTTP 请求中携带数据，因此性能更好。

3. `Session Storage`：类似于 Local Storage，但是它的生命周期是与当前浏览器 Tab 页相关联的，当用户关闭 Tab 页时，Session Storage 中的数据也会被清除。

4. `IndexedDB`：一种高级的客户端存储技术，允许存储大量的数据，而且支持复杂的查询操作，通常用于构建离线应用程序。

Cookie 和 IndexedDB 的主要区别在于：

- 存储空间：Cookie 存储量较小，IndexedDB 可以存储大量数据。
- 查询能力：基于键值对的 Cookie 主要用于简单的存储和检索操作，而 IndexedDB 具备强大的查询能力，可以进行复杂的数据查询和排序操作。
- 数据结构：Cookie 数据结构比较简单，只能存储字符串类型的数据；而 IndexedDB 支持多种数据类型，包括二进制和复杂对象等。

无论是 Cookie、LocalStorage 还是 IndexedDB，都可以将数据持久化保存，但是在不同的场景下需要考虑安全性问题。特别是对于 Cookie，需要注意以下几点：

- 避免存储敏感信息：例如密码、信用卡信息等，这些信息可能被黑客窃取。
- 使用 HttpOnly 属性：设置 HttpOnly 属性后，JavaScript 无法读取 Cookie 的值，可以防止 XSS 攻击。
- 设置 Secure 属性：设置 Secure 属性后，浏览器只会在 HTTPS 连接中发送 Cookie，可以防止网络监听攻击。
- 对 Cookie 进行加密：可以使用加密算法对 Cookie 进行加密，提高安全性。

# 🤺 前端框架/库

## React

#### 1. react hooks 跟之前的 class 写法有什么不同？有哪些优势？

#### 2. react hooks 为什么没有生命周期？如果要使用生命周期怎么做？

#### 3. 了解 fiber 吗？它的原理是什么？

#### 4. 讲讲 React 技术栈的最佳实践

#### 5. React 性能优化需要考虑哪些？

#### 6. React 依赖注入是怎么实现的？

React 本身并没有依赖注入的功能，但是我们可以通过使用第三方库或手动实现来达到类似的效果。

下面介绍两种常见的方式：

1. 使用 React Context 实现依赖注入

React Context 是 React 提供的一种跨组件层级共享数据的机制，可以用来实现依赖注入。在使用 React Context 实现依赖注入时，我们需要定义一个 Context，并将其传递给需要访问该依赖的组件。然后，我们可以使用 Provider 组件来提供该依赖，并使用 Consumer 组件来访问该依赖。

```jsx
// 创建一个 Context 对象
const AppContext = React.createContext({});

// 在父组件中使用 Provider 组件提供依赖
function App() {
  const [dependency, setDependency] = useState("Dependency");
  return (
    <AppContext.Provider value={dependency}>
      <ChildComponent />
    </AppContext.Provider>
  );
}

// 在子组件中使用 Consumer 组件访问依赖
function ChildComponent() {
  const dependency = useContext(AppContext);
  return <div>{dependency}</div>;
}
```

2. 使用 HOC（高阶组件）实现依赖注入

HOC 是一个函数，接受一个组件作为参数，并返回一个新的增强组件。使用 HOC 实现依赖注入时，我们可以编写一个 HOC 函数，接受依赖作为参数，并返回一个包装了组件的新组件。然后，我们可以通过将该新组件作为另一个组件的子组件来访问依赖。

```jsx
// 创建一个 HOC 函数
function withDependency(Component, dependency) {
  return function() {
    return <Component dependency={dependency} />;
  };
}

// 使用 HOC 函数包装组件
const ChildComponent = ({ dependency }) => <div>{dependency}</div>;
const EnhancedChildComponent = withDependency(ChildComponent, "Dependency");

// 渲染增强后的组件
function App() {
  return <EnhancedChildComponent />;
}
```

## Vue

#### 1. 讲讲 Vue 技术栈的最佳实践。

## 微前端

#### 1. 微前端框架（例如qiankun）实现js隔离的原理是什么？css 是如何隔离？常见微前端框架有哪些？能否比较下他们的实现原理？为什么选择 qiankun？

#### 2. 微前端使用过程中遇到哪些问题？挑一个难点讲下。

## 低代码

#### 1. 低代码开发平台如何实现？比如说从拖动组件到生成元素到我们应用页面上的过程是怎样的？

## 跨端开发（移动端/桌面端）

#### 1. 介绍下 Flutter，并说下 Flutter 和 RN 的区别。

# ⚔️ 工程化

#### 1. 结合过往经验，如何理解前端工程化？

前端工程化是指在 Web 前端开发中，通过使用一系列的技术、工具和方法来提高开发效率，减少重复劳动和出错率，保证项目的可维护性和可扩展性。它包括以下方面：

1. 代码管理和版本控制

使用 Git 等版本控制系统进行代码管理，可以跟踪代码变更、协同开发和发布等操作，并且在出现问题时可以回滚代码。

2. 模块化开发

通过模块化开发，将整个应用程序分解为多个小模块，每个模块只负责完成单一功能，从而提高代码可维护性和可重用性，减少代码冗余。

3. 自动化构建和部署

使用自动化构建工具（如 webpack、gulp 等）将代码文件打包合并成最终的静态资源，然后自动发布到服务器上，从而减少人工干预，提高开发效率和代码质量。

4. 代码质量检查和测试

使用 Lint 工具对代码进行静态检查，以确保代码符合规范；使用单元测试、集成测试等方式，对代码进行测试，从而保证代码的正确性和鲁棒性。

5. 性能优化

通过使用优化工具（如 PageSpeed Insights、YSlow 等）对网页性能进行评估和优化，从而提高网页的加载速度、响应速度等。

6. 团队协作和项目管理

通过使用协同工具（如 Trello、Slack 等）对团队进行协作和管理，从而在开发过程中保证沟通的顺畅和信息的透明。

总之，前端工程化不仅仅是一种开发模式，而是一种完整的开发思想。通过采用前端工程化的方式，可以规范化开发流程，提高代码质量和可维护性，降低开发成本，从而达到更好的开发效果。
## 模块化

## 组件化

####  1. 封装一个模态弹窗需要考虑哪些点？

- 功能需求：模态弹窗通常包括打开和关闭两个基本功能。此外，还需要考虑是否支持拖拽、缩放、最大化等高级功能。

- 样式设计：模态弹窗需要考虑样式风格、布局、背景颜色、字体大小等方面，以提供良好的视觉效果，并与整个页面的风格保持一致。

- 参数配置：需要考虑如何通过参数进行配置，包括标题、宽度、高度、位置、遮罩层、动画效果等方面，以便灵活使用。

- 事件处理：需要考虑模态弹窗打开和关闭时的事件处理逻辑，包括回调函数、数据传递、状态管理等方面，以便处理业务逻辑。

- 兼容性和性能优化：需要考虑模态弹窗在不同浏览器和设备上的兼容性问题，并且需要注意性能优化，以确保模态弹窗的加载速度和响应时间。

- 调试和测试：需要考虑如何进行模态弹窗的调试和测试工作，如何定位问题和解决问题。

- 安全性：需要考虑模态弹窗中是否存在安全风险，如防止恶意跨站脚本攻击（XSS）等。



## 错误监控

#### 1. 错误上报/捕获全局 sdk 如何写？需要捕获哪些东西？在哪写？



## 构建工具

#### 1. webpack plugin 跟 loader 有何不同？有没有使用 plugin 写过一些插件？

定位不同：

- **loader** 是文件加载器，能够加载资源文件，并对这些文件进行一些处理，诸如转换、编译等，最终再一起打包到指定的文件中，例如：less-loader、babel-loader 等。（原理：将一个 js 字符串转换成另一个 js 字符串）

- **plugin** 赋予了 webpack 各种灵活的功能，例如`打包优化`、`资源管理`、`环境变量注入`等，目的是解决 loader 无法实现的其他事。

运行时机上有差别：

- **loader** 运行在打包文件之前。

- **plugins** 在整个编译周期都起作用。

在 Webpack 运行的生命周期中会广播出许多事件，Plugin 可以监听这些事件，在合适的时机通过 Webpack 提供的 API 改变输出结果。

对于 loader，实质是一个转换器，将 A 文件进行编译形成 B 文件，操作的是文件，比如将 A.scss 或 A.less 转变为 B.css，单纯的文件转换过程。

> 敲重点：plugin 是对 loader 的补充。

之前写过一个打包时自动加入发布版本号信息的 plugin。
## devOps

#### 1. 说说你对 devOps 的理解。

#### 2. CI/CD这些了解吗？说下自己之前的使用经验。

# ☎️ 数据通信
## http & http2

#### 1. http2 有什么新的东西，哪些场景下适用？

-   二进制分帧
-   首部压缩 ✅
-   流量控制
-   多路复用 ✅
-   请求优先级
-   服务器推送 ✅

## JSBrange

#### 1. web 与原生应用如何交互通信？

## websocket

#### 1. websocket 是什么？有哪些应用场景？

# 👑 性能优化

## 语义化 & SEO

## 高性能页面

#### 1. web缓存有哪些？

**强缓存**：利用http的返回头中的Expires或者Cache-Control两个字段来控制的，用来表示资源的缓存时间。
- 原理
    - 浏览器先根据这个资源的http头信息的字段Expires、Cache-Control来判断是否命中强缓存，
    - 如果命中强缓存时，直接加载缓存中的资源，浏览器并不会将请求发送给服务器，在Chrome的开发者工具中看到http的返回码是200，但是在Size列会显示为(from cache)。
    - 若未命中强缓存，则浏览器会将请求发送至服务器。服务器根据http头信息中的Last-Modify/If-Modify-Since或Etag/If-None-Match来判断是否命中协商缓存。详情查看下方协商缓存。
- 字段
    - Expires：缓存过期时间，用来指定资源到期的时间，需要和Last-modified结合使用。Expires是Web服务器响应消息头字段，在响应http请求时告诉浏览器在过期时间前浏览器可以直接从浏览器缓存取数据，而无需再次请求。该字段会返回一个时间，例如，`Expires:Thu,31 Dec 2037 23:59:59 GMT`，这个时间代表着这个资源的失效时间，也就是说在2037年12月31日23点59分59秒之前都是有效的，即命中缓存。这种方式有一个明显的缺点，由于失效时间是一个绝对时间，所以当客户端本地时间被修改以后，服务器与客户端时间偏差变大以后，就会导致缓存混乱。于是发展出了Cache-Control。
    - Cache-Control：Cache-Control是一个相对时间，例如，`Cache-Control:3600`，代表着资源的有效期是3600秒。由于是相对时间，并且都是与客户端时间比较，所以服务器与客户端时间偏差也不会导致问题。Cache-Control可以由多个字段组合而成，主要有以下几个取值。
        - max-agex(单位秒)：指定一个时间长度，在这个时间段内缓存是有效的，单位是s。例如设置 `Cache-Control:max-age=31536000`，也就是说缓存有效期为（31536000 / 24 / 60 * 60）天，第一次访问这个资源的时候，服务器端也返回了 Expires 字段，并且过期时间是一年后。在没有禁用缓存并且没有超过有效时间的情况下，再次访问这个资源就命中了缓存，不会向服务器请求资源而是直接从浏览器缓存中取。
        - s-maxage：代理服务器请求源站缓存后的X秒不再发起请求，只对CDN缓存有效。等同max-age，覆盖max-age、Expires，但仅适用于共享缓存，在私有缓存中被忽略。
        - public：表明响应可以被任何对象（发送请求的客户端、代理服务器等等）缓存。
        - private：表明响应只能被单个用户（可能是操作系统用户、浏览器用户）缓存，是非共享的，不能被代理服务器缓存，即只有客户端可以缓存。
        - no-cache：缓存，但是浏览器使用缓存前，都会请求服务器判断缓存资源是否是最新。
        - no-store：禁止缓存，每次请求都要向服务器重新获取数据。
        - must-revalidate：指定如果页面是过期的，则去服务器进行获取。这个指令并不常用，就不做过多的讨论了。
    - 优先级：Cache-Control与Expires可以在服务端配置同时启用或者启用任意一个，同时启用的时候Cache-Control优先级高。
- 注意
    - 浏览器设置页面是否缓存：通过HTML meta标签设置，例如，`<META HTTP-EQUIV="Pragma" CONTENT="no-store">`，含义是让浏览器不缓存当前页面，但注意，代理服务器不解析HTML内容，浏览器强缓存设置一般使用HTTP头信息控制。


**协商缓存**：主要用到HTTP请求头的Last-Modify/If-Modify-Since或者Etag/If-None-Match两个字段。
- 原理
    - 若未命中强缓存，则浏览器会将请求发送至服务器。服务器根据http头信息中的Last-Modify/If-Modify-Since或Etag/If-None-Match来判断是否命中协商缓存。如果命中，则http返回码为304，浏览器从缓存中加载资源。
    - 浏览器第一次请求一个资源的时候，服务器返回的header中会加上Last-Modify，Last-modify是一个时间标识该资源的最后修改时间，例如，`Last-Modify: Thu,31 Dec 2037 23:59:59 GMT`。当浏览器再次请求该资源时，发送的请求头中会包含If-Modify-Since，该值为缓存之前返回的Last-Modify。服务器收到If-Modify-Since后，根据资源的最后修改时间判断是否命中缓存。
    - 如果命中协商缓存，则返回http304，并且不会返回资源内容，并且不会返回Last-Modify。由于对比的服务端时间，所以客户端与服务端时间差距不会导致问题。但是有时候通过最后修改时间来判断资源是否修改还是不太准确（资源变化了最后修改时间也可以一致）。于是出现了ETag/If-None-Match。
    - 如果未命中协商缓存，则服务器会将完整的资源返回给浏览器，浏览器加载新资源，并更新缓存。
- HTTP1.1中Etag的出现主要是为了解决几个Last-Modified比较难解决的问题。
    - Last-Modified标注的最后修改只能精确到秒级，如果某些文件在1秒钟以内，被修改多次的话，它将不能准确标注文件的修改时间。
    - 如果某些文件会被定期生成，当有时内容并没有任何变化，但Last-Modified却改变了，导致文件没法使用缓存。
    - 有可能存在服务器没有准确获取文件修改时间，或者与代理服务器时间不一致等情形。
- Last-Modified和Etag优先级：Etag是服务器自动生成或者由开发者生成的对应资源在服务器端的唯一标识符，能够更加准确的控制缓存。Last-Modified与ETag是可以一起使用的，服务器会优先验证ETag，一致的情况下，才会继续比对Last-Modified，最后才决定是否返回304。


**用户行为与缓存**：浏览器缓存行为还与用户的行为有关。

|用户操作|Expires/Cache-Control|Last-Modified/Etag|
|-|-|-|
|地址栏回车|有效|有效|
|页面链接跳转|有效|有效|
|新开窗口|有效|有效|
|前进、后退|有效|有效|
|F5刷新|无效|有效|
|Ctrl+F5刷新|无效|无效|

**总结**

浏览器第一次请求

![浏览器第一次请求]

浏览器再次请求时

![浏览器再次请求]

HTTP整体缓存流程

![HTTP缓存流程]

#### 2. 如何全链路优化应用访问性能？

#### 3. svg、base64 格式图片跟 png、jpg 等格式有啥不同？

#### 4. 如果一个页面有很多图片，怎么优化这个页面的加载速度？

在 Web 前端开发中，对于一个页面中有很多图片的情况，可以通过以下几种方式来优化页面加载速度：

1. 图片压缩：使用图片压缩工具（如 TinyPNG、JPEGmini 等）将图片进行压缩，以减小图片的大小，从而加快图片的加载速度。

2. 懒加载：懒加载是指当用户滚动到可见区域时才加载图片，而不是一次性全部加载。通过使用 LazyLoad 等 JS 库可以实现图片的懒加载，从而提高页面的加载速度。

3. WebP 格式：WebP 是一种由 Google 开发的新型图片格式，能够在保证图片质量的情况下减小图片的大小。如果浏览器支持 WebP 格式，可以考虑将图片转换为 WebP 格式，以提高页面的加载速度。

4. CDN 加速：使用 CDN（Content Delivery Network）可以将图片等静态资源存储在离用户更近的服务器上，从而加快资源的加载速度。

5. 响应式图片：使用响应式图片可以根据不同设备的屏幕分辨率显示不同大小的图片，从而减少不必要的网络流量和加载时间。

6. CSS Sprite：CSS Sprite 是将多个图片合并成一张大图，并通过 CSS 控制每个小图的显示位置和大小，从而减少 HTTP 请求的数量，提高页面性能。

7. 缓存策略：在服务器端设置适当的缓存策略，可以让客户端在下一次请求时直接从浏览器缓存中读取图片，而不是再次从服务器请求。

总之，在优化页面加载速度时，需要根据具体情况综合考虑多种因素，包括图片大小、网络状况、设备类型等。通过以上方式进行优化，可以提高页面的响应速度和用户体验。

## 架构设计

#### 1. 高性能页面如何实现？高可用方面前端能做些啥？

#### 2. 讲一下哪个项目最能体现你的技术架构设计能力？

#### 3. 一个好的架构设计需要关注哪些方面？

#### 4. 架构上如何保证 node 服务的高可用？
## 监控预警
#### 1. 官网类应用是如何提升 SLA 实现高可用的？你采取了哪些前端措施？

一些常见的措施：

- 负载均衡：通过负载均衡器将流量分发到多个服务器上，可以避免单点故障，提高系统的容错能力和扩展能力。同时，通过监控负载均衡器的性能指标，可以及时发现并解决性能瓶颈问题。
- 横向扩展：当单台服务器无法满足用户需求时，可以通过横向扩展来增加服务器数量，以提高系统的吞吐量和性能。通常可以使用自动化工具或云计算服务来实现快速部署和扩容。
- 数据库设主从：通过数据库复制技术，将数据备份到多个节点中，可以避免单点故障和数据丢失风险。同时，通过读写分离和集群技术，可以提高数据库的读写性能和可靠性【非前端重点】
- 缓存技术：通过使用缓存技术（如 Memcached、Redis 等），可以将访问频率较高的数据缓存在内存中，加快数据的读写速度，提高系统的响应速度和性能。
- 监控和预警：通过监控系统的关键指标（如 CPU、内存、网络流量等），可以及时发现性能问题并进行处理。同时，如果出现异常情况，需要能够通过预警机制及时通知开发人员或运维人员进行快速响应和解决。
- 灰度发布：通过灰度发布技术，将新版本的应用程序逐步部署到目标用户中，以确保新版本的稳定性和兼容性。这样可以避免一次性发布导致的风险。
#### 2. 如何去避免 node 内存泄露这种问题？如何更好的监控？

# 🎯 web 安全

#### 1. web 安全中跟前端有关的攻击有哪些？是什么原理？

**跨站脚本攻击（XSS攻击）**：攻击者通过在页面注入脚本代码，来获取用户的敏感信息或者执行恶意操作。常见的攻击方式包括反射型、存储型和 DOM 型 XSS 攻击。
> 解决方法：过滤用户输入脚本，对特殊字符如”<”,”>”转义

**跨站请求伪造(CSRF攻击)**：攻击者通过伪造 HTTP 请求，以受害者名义发送恶意请求到服务器上，从而完成攻击。这种攻击方式通常需要借助受害者已登录的状态，比较难以防范。
> 解决办法：请求头增加一个token字段校验cookie是否被劫持

**点击劫持**：最常见的是恶意网站使用`<iframe>`标签把我方的一些含有重要信息类如交易的网页嵌入进去，然后把iframe设置透明，用定位的手段的把一些引诱用户在恶意网页上点击。这样用户不知不觉中就进行了某些不安全的操作。
> 解决办法
> - 使用JS防范：判断顶层视口的域名是不是和本页面的域名一致，如果不一致就让恶意网页自动跳转到我方的网页。当然你还可以恶心一下这些恶意网站，比如说弹窗十几次，或者跳转到某些404页面。
> - 使用HTTP头防范：通过配置nginx发送X-Frame-Options响应头，这样浏览器就会阻止嵌入网页的渲染。更详细的可以查阅MDN上关于X-Frame-Options响应头的内容。

```js
// 使用JS防范
if (top.location.hostname !== self.location.hostname) {
    alert("您正在访问不安全的页面，即将跳转到安全页面！");
    top.location.href = self.location.href;
}

// 使用HTTP头防范
add_header X-Frame-Options SAMEORIGIN;
```

**请求劫持**
- DNS劫持，顾名思义，DNS服务器(DNS解析各个步骤)被篡改，修改了域名解析的结果，使得访问到的不是预期的ip。
- HTTP劫持：此时只能升级HTTPS了。

**SQL注入**：攻击者在HTTP请求中注入恶意的SQL代码，并在服务端执行。比如用户登录，输入用户名camille，密码 ‘ or ‘1‘=‘1 ，如果此时使用参数构造的方式，就会出现。
- 解决办法
    - 客户端：有效性检验，限制字符串输入的长度。
    - 服务端
        - 使用预编译的PrepareStatement（java）；
        - 有效性检验，防止攻击者绕过客户端请求；
        - 永远不要使用动态拼装SQL，可以使用参数化的SQL或者直接使用存储过程进行数据查询存取；
        - 过滤SQL需要的参数中的特殊字符，比如单引号、双引号。
```sql
/* SQL注入场景示例：不管用户名和密码是什么，查询出来的用户列表都不为空，这样可以随意看其他用户的信息。 */
select * from user where name = ‘camille‘ and password = ‘‘ or ‘1‘=‘1‘
```
```js
// 解决办法
// 客户端：过滤URL非法SQL字符，或者过滤文本框非法字符。
var sUrl = location.search.toLowerCase();
var sQuery = sUrl.substring(sUrl.indexOf("=")+1);
reg=/select|update|delete|truncate|join|union|exec|insert|drop|count|‘|"|;|>|<|%/i;
if(reg.test(sQuery))
{
    alert("请勿输入非法字符");
    location.href = sUrl.replace(sQuery,"");
}
```

**OS命令注入**：不是针对数据库，针对操作系统的。

**DDOS分布式拒绝服务攻击(英文意思是Distributed Denial of Service，简称DDoS)**：指处于不同位置的多个攻击者同时向一个或数个目标发动攻击，或者一个攻击者控制了位于不同位置的多台机器并利用这些机器对受害者同时实施攻击。由于攻击的发出点是分布在不同地方的，这类攻击称为分布式拒绝服务攻击，其中的攻击者可以有多个。

#### 2. cookie 的安全问题怎么避免？

需要注意以下几点：

- 避免存储敏感信息：例如密码、信用卡信息等，这些信息可能被黑客窃取。
- 使用 HttpOnly 属性：设置 HttpOnly 属性后，JavaScript 无法读取 Cookie 的值，可以防止 XSS 攻击。
- 设置 Secure 属性：设置 Secure 属性后，浏览器只会在 HTTPS 连接中发送 Cookie，可以防止网络监听攻击。
- 对 Cookie 进行加密：可以使用加密算法对 Cookie 进行加密，提高安全性。
# 🤡 兼容
（暂未遇到，先占位后续再补充）

# ⚓️ 后端知识等

## node.js

#### 1. node 的动态扩展如何实现？

使用 PM2 充分发挥服务器多核的优势，将 node 进程拓展为多个，提高 node 服务运行的容错性。

## linux运维

#### 1. 服务器操作、Linux 命令这块有哪些实践？

# 📚 项目管理

## 项目经验

#### 1. 如果给你一个代码年久失修、文档缺失的项目，你准备如何去整理文档，方便后续维护？
## 沟通协作

#### 1. 前端如何与后端更高效的协作开发？
## 敏捷Scrum

#### 1. 敏捷 scrum 是如何开展各项活动的？逐个介绍下。











[浏览器第一次请求]:./image/webcache_request_first.png
[浏览器再次请求]:./image/webcache_request_again.png
[HTTP缓存流程]:./image/webcache.png

