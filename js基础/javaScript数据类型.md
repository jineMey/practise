#### 基础类型
Number String Boolean undefined null symbol 

#### 引用类型
Object Array function

![这是图片](./image/Javascript-DataType.png)


#### undefined与null的区别

- null表示一个值被定义了，但是这个值是空值。 
  - 作为函数的参数，表示函数的参数不是对象。
  - 作为对象原型链的终点Object.getPrototypeOf(Object.prototype)。

- undefined表示不存在该值的定义。
  - 变量被声明了还没有赋值，表现为undefined
  - 调用函数时应该提供的参数没有提供，参数值表现为undefined
  - 对象没有赋值的属性，该属性的值就表现为undefined
  - 函数没有返回值，默认返回undefined