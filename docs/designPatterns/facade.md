# 门面模式

门面模式是对象的结构模式，外部与一个子系统的通信必须通过一个统一的门面对象进行。门面模式提供一个高层次的接口，使得子系统更易于使用。

![门面模式](../../images/门面模式.png)

隐藏了系统的复杂性，并向客户端提供了一个可以访问系统的接口。这种类型的设计模式属于结构性模式。为子系统中的一组接口提供了一个统一的访问接口，这个接口使得子系统更容易被访问或者使用。

使用场景：
1. 为复杂的模块或子系统提供外界访问的模块
2. 子系统相互独立
3. 层析结构中，可以使用外观模式定义系统的每一层的入口

优点：
1. 松散耦合
2. 简单易用
3. 更好的划分层次访问
