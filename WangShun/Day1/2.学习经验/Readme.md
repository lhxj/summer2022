##学习经验
# 线程的创建分为静态线程与动态线程
# 静态线程创建本质是初始化预先是设置的堆栈（数组）以及任务句柄，动态线程采用的是动态分配的方式
# RTT支持软件定时器与硬件定时器 软件定时器以系统tick为基时，使用起来方便但不太准
# 硬件定时器使用本质和裸机没有区别 只是需要在RTT框架下使用
# WangShun 2022-7-19