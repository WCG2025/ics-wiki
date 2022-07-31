# 关于课程

jyy的操作系统在国内属于比较有名的操作系统课程，在[csdiy](https://csdiy.wiki)这样的网站上也有收录。jyy也是很有耐心很负责任人的老师，值得体验一下。

关于这门课的信息具体可以看[jyywiki](https://jyywiki.cn)

# 成绩构成

笔者在2022年春季选修的时候成绩构成如下

- OSLab+MiniLab 50%
- 期中(线上)      10%
- 期末           40%

# 关于考试

期中考是可选的，如果不参加期中考的话期末将以50%计入成绩

期中考主要是一个小的并发编程oj，一个简单的构造题(提交一组解)。成功提交即可获得90%的成绩，也就是说只要交一个空的repo就有%9的总评了...

期末考是5~6道大题，每道大题都是内部有联系的若干简答题，内容包括但不限于：

- 列举出至少五个binutils中的工具
- 简述如何为虚拟机提供“快照”功能
- 写出`execve`的参数类型(不要求与手册完全一致)
- 用 信号量/自旋锁/条件变量 实现读写锁(给出伪代码)

据称每年jyy都会调整曲线让大家的成绩好看一些

# 关于实验

## MiniLab

有5个小实验，主要是一些Linux上的C语言编程，结合了一点点调API的知识就可以做，都是不超过200行就能完成的小程序

- 打印进程列表
- 实现用户态线程
- 统计程序在各系统调用上花费的时间
- 利用动态链接实现C程序的“解释”执行
- 恢复FAT32镜像里的图片文件

都是非常有意思的实验，做完就会对探索操作系统和写程序有新的体会了。

## OSLab

有5个实验，2022年因为jyy要监考APIO的原因，实验4变成了选做(根本没有发布)

- 熟悉AM平台
- 并发的内存分配器
- 任务调度和并发原语(锁和信号量)
- 用户态进程和若干系统调用
- 文件系统

做OSLab需要掌握一些debug技巧，比较熟悉工具的使用，还要有一点耐心。做完就会发现操作系统没有原本那么神秘了。

# 生存技巧

课堂上会推荐MIT的xv6代码作为参考，比较合适的做法是：自己写一遍->Debug->看xv6-book->看xv6代码->恍然大悟->回到步骤1
实际上也可以对着xv6抄，不过抄代码也是有技巧的，个人建议抄设计>>抄实现。

官方推荐的教材OSTEP读起来有轻飘飘的感觉，如果觉得不够过瘾可以看SJTU的OS教材《现代操作系统》，那本要更新一些。

jyy在课堂上会演示非常多的代码片段，最好是每周找一个时间过一遍，弄清楚代码是怎么跑起来的。课程在B站也有回放。

# 给分

还没出分。

# 总结

这门课与大班的操作系统相差非常大，侧重点也完全不同。如果是为了准备考研or选修学分的话，完全可以选择大班的课程。但是这门课的优点在于它非常硬核，jyy也是年轻的前沿研究者，你可以在这堂课上看到很多CS的前沿研究方向、研究方法，一些关于出路和未来的话题也可以在Office Hour向jyy咨询。