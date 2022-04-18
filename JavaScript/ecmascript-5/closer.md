## 作用域链

```javascript
if( true ){
```

上述代码在 if 语句中定义了变量 color。但该变量的作用域是全局域，原因是 JavaScript 中没有块级作用域。
function fun(){
```

上述代码在函数 fun 内部定义了变量 JavaScript，该变量的作用域是 fun 函数作用域。所以在全局域访问该变量时会出错。
var a = 1; 
```

上述代码的作用域链如下图所示:

![](14.png)

## 什么是闭包



如下代码就是一个最简单形式的闭包结构:

```javascript
var b;
```

上述代码的作用域链如下图所示:

![](15.png)

## 闭包的特点
var getValue, setValue;
```