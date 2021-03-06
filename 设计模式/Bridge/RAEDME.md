## 桥接模式

### 概述
桥接模式将抽象部分与它的实现部分分离，使他们都可以独立地变化。通俗地说，桥接就是在不同的东西之间搭一个桥，让它们能够连接起来，可以相互通讯和使用。在桥接模式中的桥接是在被分离的抽象部分和实现部分之间搭一个桥。为了达到让抽象部分和实现部分分离开，而且在抽象部分实现的时候，还是需要使用具体的实现，可以使用桥接模式来实现。这里的桥接，就是让抽象部分拥有实现部分的接口对象，就桥接上了。

### 实现
使用发送信息的例子来实现桥接模式。信息的发送方式如：手机信息、普通信息、Email信息作为抽象部分，信息的分类如：普通信息、紧急信息、加急信息作为具体实现部分。

### 总结与分析
桥接模式是用来解决有两个变化纬度的情况下，如何灵活地扩展功能的一个很好的方案。其实，桥接模式主要是把继承改成了使用对象组合，从而把两个纬度分开，让每一个纬度单独地去变化，最后通过对象组合的方式，把两个纬度组合起来。桥接模式也从侧面体现了使用对象组合的方式比继承要来得更灵活。
