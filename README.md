# React-hook
函数式组件，函数式逻辑

## Lambda Caculus
是一套从数学逻辑中发展，以变量绑定和替换的规则，来研究函数如何抽象化定义、函数如何被应用以及递归的形式系统。
Lambda表达式是一种高效的类似于函数式编程的表达式，Lambda简化了开发中需要编写的代码量。
什么是匿名方法？
匿名方法是一个委托的拓展,无命名的方法。
```
//通过命名的方法
function greater(num){
  if(num >19){
    return 19;
  }
  return num;
}


// 在实际应用过程
// 判断用户年龄，如果年龄小于19岁告诉我具体年龄，如果不是标记为满19岁。
// 获得一组年龄

const arr1 = [19, 2,8,87,3,56,23,10,7].map(greater)   //命名方法名称作为参数传递
const arr2 = [19, 2,8,87,3,56,23,10,7].map(function(num){ //匿名函数作为参数传递
  if(num >19){
    return 19;
  }
  return num;
})
// 易读性的Lambda 表达式
const arr3 = [19, 2,8,87,3,56,23,10,7].map( Age=> (Age>19?19:Age) )
```
