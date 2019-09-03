# 多核平台下的内存问题

### 文章一：MemGuard: Memory Bandwidth Reservation System for Efficient Performance Isolation in Multi-core Platforms

### 作者：[Heechul Yun](http://www.ittc.ku.edu/~heechul/), Graduated from University of Illinois at Urbana-Champaign, USA

### 文章来源：RTAS'13

    这篇文章的贡献在于：1、用实验证实并解释了多核平台下，多任务的内存访问存在相互干扰（主要是指内存带宽）；2、提出利用性能隔离方法，将系统整体带宽分解为保证和尽力组件：为每个处理器动态预留保证的带宽，将多余带宽部分用于性能或其他达不到保证的处理器，并在linux内核层面设计并实现了这一套系统。3、利用SPEC benchmark测试和评价该系统。

