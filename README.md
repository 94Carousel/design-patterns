# design-patterns
设计模式学习笔记
设计模式定义：
  设计模式是一种针对软件设计问题的形式化解决方案，主要用来解决在特定条件下会反复发生的软件设计问题，简单的理解就是别人总结出来的软件设计经验。
1、单例模式
  单例模式应用比较广泛。主要应用场景是在应用程序整个生命周期中，对象只有一个实例的时候。单例类总是在第一次被访问的时候完成实例化，直至应用程序退出之前，都只会使用同一个实例。
  单例模式中：
    单例类只允许存在一个实例
    需要为该单一实例提供一个全局访问点
  单例模式创建策略：
    通过限制构造函数（设置为私有）从而限制单例类的实例化。之后在定义类时包含一个该类的静态私有对象，以便创建单例类的实例。
2、工厂模式
3、抽象工厂模式


