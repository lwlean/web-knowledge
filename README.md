# web-knowledge

## 盒子模型
margin border padding content

## 文档流和脱离文档流
块级元素独占一行，内联元素从左到右排列的流式布局
脱离文档流从文档流脱离出来

#### 脱离文档流的方式
- float
- position:float position:fixed

## BFC
块级格式化上下文
#### BFC渲染规则
- 同一个bfc内部box的margin会发生重叠
- BFC可以包含浮动的元素
- 容器内的子元素不会影响外部
#### BFC实现方式
- float 不为none
- overflow 不为visible
- display 不为 inline-block,table-cell,table-caption
- positon: absolute fixed

## js 常用数据类型
#### 常用数据类型有：
- 基本数据类型：string, number, boolean, null, undefined，symbol
- 引用数据类型: function array date

## js构造函数返回值
默认return 是对象本身，如果retrun其他引用类型，则返回该引用类型

## js中this指向
- 普通函数指向被调用者
- 箭头函数指向window

## js 类型判断
#### typeof
- [] null被解释称object类型 （typeof 只是不精准而已）
#### instanceof
- 只对引用数据类型
#### constructor
- 更改原型不可以
#### object.prototype.toString.call()
- 完美的解决方案，获取的数组通过slice截取判断即可。

