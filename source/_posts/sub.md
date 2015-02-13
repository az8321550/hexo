title: 对substr,substring,slice的一些理解
---
#对substr,substring,slice的一些理解

近期，碰到了一些对字串符处理的问题，

对substr,substring,slice的区别一直很困惑

今天就让我们去一探究竟吧

以下就是他们的一些区别
substring(start,end)
substr(start [, length ])
slice(start，[end])

下面是分别用"0123456789"参数1，5
substring---------------------"1234"
substr------------------------"12345"
slice-----------"1234"

区别显而易见了吧

唯一要注意的就是当传参是负数的时候
下面是分别用"0123456789"参数-2
只有substr，slice才能返回正确的值

谢谢大家捧场