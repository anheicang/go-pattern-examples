# 装饰模式

装饰模式就是比较简单了，就是在不改变原有对象和类型的情况下，对其进行装饰，扩展，以达到公共强化和扩展的目的，装饰模式的目的是在原有功能或者能力的基础上提供额外的更多的能力和特性，这一点和代理模式、复合模式是有很大不同的，了解每一种模式，重点是要了解这个模式的最初的设计者应用场景和其解决目的，以便加以利用。

Go语言借助于匿名组合和非入侵式接口可以很方便实现装饰模式。使用匿名组合，在装饰器中不必显式定义转调原对象方法。