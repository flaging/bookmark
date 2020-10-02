Linux系统接口
===

[open(2) — Linux manual page](https://man7.org/linux/man-pages/man2/open.2.html)

C格式下的文件接口，用于打开文件。

[mkfs.xfs(8) - Linux man page](https://linux.die.net/man/8/mkfs.xfs)

构建xfs类型的文件系统。

[2mib_fs_dax](https://nvdimm.wiki.kernel.org/2mib_fs_dax)

设置PMDK的页表大小为2MiB。

[引导期间Linux内核空间中的页表](https://www.thinbug.com/q/16688540)

启动过程中的页表到MMU启动后的切换方式一览。

[如何配置大型数据库的x86内存性能](https://www.oracle.com/cn/technical-resources/articles/it-infrastructure/dev-hugepages.html)

通过使用更大的页面，可以减少页表条目数，从而最大程度减少开销。使用 HugePages 可显著提升性能，增加系统中的内存数量和 SGA 大小。

[Why does the speed of memcpy() drop dramatically every 4KB?](https://stackoverflow.com/questions/21038965/why-does-the-speed-of-memcpy-drop-dramatically-every-4kb)

memcpy的4KB除性能下降。

[memcpy](http://www.cplusplus.com/reference/cstring/memcpy/)

memcpy的使用手册。

[Time in milliseconds in C](https://stackoverflow.com/questions/10192903/time-in-milliseconds-in-c)

系统耗时检测。

[Linux下直接读写物理地址内存](https://blog.csdn.net/fz835304205/article/details/16963755)

物理地址的转换方法。

[mmap映射内存的大小是不是不能超过文件大小？](https://bbs.csdn.net/topics/390088020)

lseek用法。

[lseek函数的用法](https://blog.csdn.net/u012349696/article/details/50083881)

lseek用法。

[C语言lseek()函数：移动文件的读写位置](http://c.biancheng.net/cpp/html/236.html)

lseek用法。

[lseek(2) — Linux manual page](https://www.man7.org/linux/man-pages/man2/lseek.2.html)

lseek用法。

mmap
---

[MMAP and PMDK](https://zedware.github.io/MMAP-PMDK/)

主要讲了mmap函数在处理不断增大的文件的一些分析。

[认真分析mmap](https://www.cnblogs.com/huxiao-tee/p/4660352.html)

分析了mmap的内部调用机制。

[mmap(2) — Linux manual page](https://man7.org/linux/man-pages/man2/mmap.2.html)

C格式下的接口，用于将文件映射至内存空间。

BPF
---

[BPF介绍](https://mp.weixin.qq.com/s?__biz=MzA5OTAyNzQ2OA==&mid=2649712754&idx=1&sn=891d7166c02693b8af7b36f8a44c5990&chksm=88935711bfe4de074a72f761c1b4d094c5b2ce57b579cea0fedf2baf62516763d1fd5619624f#rd)

一种用于Linux网络过滤的机制或者工具（没有看懂）。

[为什么我说C/C++程序员都要阅读Redis源码之：通过Redis学习事件驱动设计](https://zhuanlan.zhihu.com/p/57882822)

redis的简单介绍：

* 一种内存数据库系统
* 使用C++的思想设计，使用C语言实现
* 本文推荐一个下午就能看完该部分代码
* Github上的源码在[这里](https://github.com/redis/redis)

[CPU简介](https://mp.weixin.qq.com/s?__biz=MzUzODQ0MDY2Nw==&mid=2247483925&idx=1&sn=03170614c1a54c3cecf64d09dd17940f&chksm=fad6e4a1cda16db73e7f011f2fcea2a69454bad8e3eb8c09dad544b722f9425fde585dbb0edb#rd)

介绍类CPU的一些基础知识。

* Cache/Cache line/缓存一致性