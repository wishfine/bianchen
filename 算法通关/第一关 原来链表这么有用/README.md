# 第一关｜原来链表这么有用

 关卡介绍 

链表是一种最基本的结构，普通的单链表就是只给你一个指向链表头的指针head，如果想访问其他元素，就只能从head开始一个个向后找，遍历链表最终会在访问尾结点之后如果继续访问，就会返回null。

在工程应用，极少见到普通单链表，比较多的是带头结点的单链表和双向循环链表。 有时候会将多个链表组合从而实现更丰富的功能，这种操作在很多底层软件里大量使用，例如操作系统、虚拟机等。

由于Java和python都是面向对象的语言，实现链表的方式基本类似，因此我们一起来讲解。C语言的实现方式与之有较大的区别，我们单独讲解。

链表及其拓展的应用是非常广的，但是好在常见的面试题并没有想象中那么多。我们将采用两关来征服链表的问题，第一关是链表的基本问题。第二关则是链表反转以及拓展问题。每一关都包含大量的超高频考题，只要过了这两关，我敢保证，以后面试遇到链表，一定不会害怕。