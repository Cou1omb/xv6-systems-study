# xv6 Systems Study

Source history and eleven retrospectives from my study of MIT's RISC-V teaching operating system.

以下编号沿用个人学习顺序。每篇按实际改动、对机制的认识和学习收获整理，作为可继续修订的回顾初稿。首页所在的 `study-guide` 分支展示网络实验源码和全部回顾。各篇注明源码分支和提交，可用 `git show 分支:文件路径` 阅读其他实验文件，无需切换工作区。

1. [Unix 工具与 xargs](reviews/lab-01.md) · `util`
2. [系统调用与内核观测](reviews/lab-02.md) · `util`
3. [页表与虚拟地址](reviews/lab-03.md) · `pgtbl`
4. [陷阱与定时通知](reviews/lab-04.md) · `traps`
5. [惰性分配](reviews/lab-05.md) · `lazy-study`
6. [写时复制](reviews/lab-06.md) · `cow`
7. [POSIX 线程练习](reviews/lab-07.md) · `thread-study`
8. [锁、分配器与缓冲缓存](reviews/lab-08.md) · `lock-study`
9. [文件系统](reviews/lab-09.md) · `fs-study`
10. [文件内存映射](reviews/lab-10.md) · `mmap-study`
11. [网络驱动与 UDP 接收](reviews/lab-11.md) · `net-study`

基础代码来自 [MIT xv6 Labs 2025](https://pdos.csail.mit.edu/6.1810/2025/)。原始许可见 [LICENSE](LICENSE)。含实验实现的仓库供个人私有保存。
