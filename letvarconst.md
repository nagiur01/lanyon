Var
---
我们用 ‘var’ 关键字对于宣布变量.我们可以用这个关键字函数的里面和外面.如果使用在函数的里面这叫本地的变量和使用在函数的外面这叫全球变量.当在函数中声明时，它在函数中可用。

```javascript
var a = 10;

function add(){
    var b = 20;
    console.log("Sum : " + (a+b));
}

add();
console.log("a : " + a); // 可以接近
// console.log("b : " + b); // 不可以接近 
```
在这个程序 ‘a’ 是一个全球变量.可以用函数的里面.'b'是一个本地变量.不可以用函数的外面.



let
---
我们用 let 关键字对于宣布变量在有限的块,语句或表达式.

```javascript
for(let i = 0; i < 5; i++){
    console.log(i);
}

console.log("i : " + i); // 不可以接近 
```
这个程序 i 不接近外面的块.

const
---
我们用 const 关键字对于宣布只读变量.不可以重新分配.


```javascript
const a = 10;
a = 30; // 不允许
```

