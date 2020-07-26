# Js 快速入门

## 基本语法

[Js ]()

## 常用库

### 切片

js 通过切片模拟栈和队列

栈

```js
// 创建栈
let stack = []
// push压入
stack.push(10)
// pop弹出
stack.pop()
stack.length--
// 检查栈空
stack.length === 0
```

队列

```js
// 创建队列
let queue = []
// enqueue入队
queue.push(10)
// dequeue出队
queue.shift()
queue.slice(1)
// 长度0为空
queue.length === 0
```

注意点

- slice(start,end) 返回一个新的数组
- 默认 s=s[0:len(s)]，取下限不取上限，数学表示为：[)，含头不含尾

### 字典

基本用法

```js
// 创建
let m = {}
// 设置kv
m["hello"]=1
// 删除k
delete m.hello
// 遍历
for(const key in m){
    console.log(m[key])
}
```

注意点
- 暂时没有，后续补充

### 标准库

后续有需要针对每个部分进行补充

JavaScript Object对象
JavaScript Array 对象
JavaScript 包装对象和Boolean对象
JavaScript Number对象
JavaScript String对象
JavaScript Math对象
JavaScript Date对象
JavaScript RegExp对象
JavaScript JSON对象
JavaScript console对象
JavaScript 属性描述对象

math

```js


```


### 常用技巧

类型转换

```js

```

## 刷题注意点

- leetcode 中，全局变量不要当做返回值，否则刷题检查器会报错
