同步/异步日志系统
==============

block_queue（阻塞队列）模块：
1.当队列为空时，从队列获取元素的操作将会被阻塞，直到队列中被放入了元素；
2.当队列满时，唤醒所有线程，直接返回，不执行添加元素操作
