## 手写代码：订阅-发布模式

- [https://github.com/LasyIsLazy/code-collections/tree/master/front-end/%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F/%E5%8F%91%E5%B8%83%E8%80%85-%E8%AE%A2%E9%98%85%E8%80%85%E6%A8%A1%E5%BC%8F%EF%BC%88%E8%A7%82%E5%AF%9F%E8%80%85%E6%A8%A1%E5%BC%8F%EF%BC%89](https://github.com/LasyIsLazy/code-collections/tree/master/front-end/%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F/%E5%8F%91%E5%B8%83%E8%80%85-%E8%AE%A2%E9%98%85%E8%80%85%E6%A8%A1%E5%BC%8F%EF%BC%88%E8%A7%82%E5%AF%9F%E8%80%85%E6%A8%A1%E5%BC%8F%EF%BC%89)

## 格式化数字。输入：12345，输出：12,234；输入：2345.6789，输出：2,345.6789。要求：使用正则和非正则两种方式实现

## http 常用的请求方式，区别和用途

- [https://developer.mozilla.org/zh-CN/docs/Web/HTTP/Methods](https://developer.mozilla.org/zh-CN/docs/Web/HTTP/Methods)

## http 常用的状态码和使用场景

- [https://developer.mozilla.org/zh-CN/docs/Web/HTTP/Status](https://developer.mozilla.org/zh-CN/docs/Web/HTTP/Status)

## HTTP 缓存

- [https://developer.mozilla.org/zh-CN/docs/Web/HTTP/Caching_FAQ](https://developer.mozilla.org/zh-CN/docs/Web/HTTP/Caching_FAQ)

## http2

## css div 垂直水平居中，并完成 div 高度永远是宽度的一半（宽度可以不指定）

- [https://www.jianshu.com/p/e2540496370a](https://www.jianshu.com/p/e2540496370a)
- [https://juejin.im/post/5b0784566fb9a07abd0e14ae](https://juejin.im/post/5b0784566fb9a07abd0e14ae)

## 深度克隆

- [https://stackoverflow.com/a/4460624/6638065](https://stackoverflow.com/a/4460624/6638065)
- [https://github.com/LasyIsLazy/code-collections/tree/master/front-end/%E6%B7%B1%E5%BA%A6%E5%85%8B%E9%9A%86](https://github.com/LasyIsLazy/code-collections/tree/master/front-end/%E6%B7%B1%E5%BA%A6%E5%85%8B%E9%9A%86)

## 任务队列

下面代码执行顺序，并解释

```JavaScript
async function async1() {
    console.log('async1 start');
    await async2();
    console.log('async1 end');
  }

  async function async2() {
    console.log('async2');
  }

  console.log('script start');

  setTimeout(function () {
    console.log('setTimeout');
  }, 0);

  async1();

  new Promise(function (resolve) {
    console.log('promise1');
    resolve();
  }).then(function () {
    console.log('promise2');
  });

  console.log('script end');
```

## new 的原理

- [javascript中，new操作符的工作原理是什么? - 鲁小夫的回答 - 知乎](https://www.zhihu.com/question/36440948/answer/67513171)

## CDN 原理、DNS 查询、负载均衡

## V8 内存回收机制

## Vue diff 算法

## VueX 原理

## Vue 有哪些钩子

## Vue 生命周期

## 前端安全： XSS、CSRF


面试题来源：

- [https://www.nowcoder.com/discuss/163165](https://www.nowcoder.com/discuss/163165)