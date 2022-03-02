# Linux perf little book
When talking about `perf` in `Linux`, it actually refers to `2` things:  

a) `Perf_events` (also be called as `perf` for short): a subsystem which was merged into Linux `kernel` since `2.6.31`;  

b) A powerful and comprehensive user-space tool: `perf`, which leverages `perf_events` subsystem to do performance analysis. 

`Perf` is a really powerful tool. As Brendan Greeg wrote in his [Choosing a Linux Tracer (2015)](http://www.brendangregg.com/blog/2015-07-08/choosing-a-linux-tracer.html):  

>  If there's one tracer I'd recommend people learn, it'd be perf, as it can solve a ton of issues, and is relatively safe.
  
In this small tutorial, I will give a whirlwind tool of the user-space `perf` utility.  

------------------------
# Linux perf 小小书
当我们在讨论`Linux`里的`perf`的时候，实际上是两个事情：

a) `Perf_events`(有时候也简称为`Perf`): 一个从`2.6.31`版本被合并到Linux Kernel的子系统

b) 一个功能强大且全面的用户工具：`perf`, 它利用`perf_event`子系统来进行性能分析。

`Perf`是一个很棒的工具。正如Brendan Greeg在他的[Choosing a Linux Tracer (2015)](http://www.brendangregg.com/blog/2015-07-08/choosing-a-linux-tracer.html)写的那样: 

> 如果让我推荐给大家一个追踪器，那它一定会是perf.它可以解决一吨的问题并且是十分安全的。

在这一篇小的教程里，大家可以快速地入门`perf`这个工具。

