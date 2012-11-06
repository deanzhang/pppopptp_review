# pppopptp review
=================

1. 该库为了理解lixnu下的accel-pptp的原理（主要是其与pppd之间的交互等），填写注释用。
2. pptp.c用于运行callmgr管理进程，并建立一个pppox套接字返回给pppd;
3. 其他文件主要都是处理callmgr的内容。
