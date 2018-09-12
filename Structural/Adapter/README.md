## 适配器模式

### 概述
将一个类的接口变成客户端所期待的另一种接口，从而使原本因接口不匹配而无法在一起工作的两个类能一起工作

### 优点
- 可以让两个没有任何关系的类在一起运行，只要适配器这个角色能搞定它们就行
- 增加了类的透明性
- 提高了类的复用度
- 灵活性非常好

### 场景
- 有动机修改一个已经投产中的接口

### 注意
- 在详细设计的时候不要考虑它，它不是为了解决还处在开发阶段的问题