# ThreadManager
## 一个关于线程管理的框架

ThreadManager V1

ThreadManager完成了,主要有以下特性:

* 支持单机版的线程管理
* 通过线程管理,避免同样的目的的线程被执行多遍,浪费资源
* 对整体的项目(一个JVM),提供一个共有的线程池
* 可以提供图形界面以供查看,当前时间点正在运行的线程(未完成)
* 提供了线程失败重试机制
* 可以按照优先级/任务组来隔离线程池,使一些重要的/组别的线程可以次要的线程的执行可以隔离开

对V2版的憧憬:
* 支持多机版本
* 支持任务返回
* 可以解决任务依赖
