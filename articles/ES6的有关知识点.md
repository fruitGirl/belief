> let 和 const区别

const用于声明常量，其值一旦被设定就不能再修改，否则会报错。值得一提的是：const声明不允许修改绑定值，但允许修改值。

```
const data = {
    name: linda,
    value: 1,
}
data.value = 2; // 没有问题的
data.age = 12; // 没有问题的
data = {}; // 报错 Uncaught TypeError: Assignment to constant variable.
```
