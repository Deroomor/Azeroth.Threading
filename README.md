# Azeroth.Threading
线程池和线程同步的一些知识点

* 线程池

* 线程同步
  * 用户模式同步基元构造
    * 易失构造
      * volatile修饰符
      * synchronized修饰符
      * System.Threading.Thread.VolatileRead方法和System.Threading.Thread.VolatileWrite方法
    * 互锁构造
      * System.Threading.Interlocked.Add
      * System.Threading.Interlocked.Increment
      * System.Threading.Interlocked.Exchange
      * 其它相关的方法
  * 内核模式同步基元构造
    * 互斥体
      * lock关键字
      * System.Threading.Monitor.Enter方法，System.Threading.Monitor.Exit方法
      * System.Threading.Mutex
    * 事件
      * System.Threading.ManualResetEvent
    * 信号量
      * System.Threading.Semaphore
  
