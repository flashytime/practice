## 工厂模式

### 概述
定义一个用于创建对象的接口，让子类决定实例化哪一个类，工厂方法使一个类的初始化延迟至其子类

### 优点
- 集中封装了对象创建，充分解耦
- 扩展程度高，适当地修改具体地工厂类或者扩展工厂类就可以完成变动
- 屏蔽产品类，产品的变化影响不了调用者，调用者只需调用接口

### 缺点
- 需要大量类，增加代码复杂度

### 场景
- 灵活、可扩展的项目中
- 异构项目中

### 扩展
- 简单工厂模式
- 替代单例
- 抽象工厂