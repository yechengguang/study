S基础, 随便操作系统书籍

2.对Linux kernel有全面了解, 关键模块有理解(走读kernel源码, 对流程有印象). 推荐书籍: 深入Linux内核架构(+1)或者深入理解LINUX内核.

3.hypervisor虚拟化, Intel的《系统虚拟化》, 很老很实用, 看Qemu, KVM, Xen代码

某个部分有疑问, 可以多个hypervisor代码对比着看:

kvm:

xen:

ACRN: https://github.com/projectacrn/acrn-hypervisor

4.容器虚拟化, 读cgroup,lxc,docker代码.

Linux虚拟化技术: http://tinylab.org/tiny-salon-phase-ii-virtualization-technology/

VT源码: https://github.com/zzhouhe/VT_Learn

VT源码学习: https://github.com/tandasat/HyperPlatform

虚拟化技术入门: https://edu.aliyun.com/course/38?spm=5176.8764728.aliyun-edu-course-tab.1.5a852addFAVPBd&previewAs=member

<操作系统与虚拟化安全>: https://www.coursera.org/learn/os-virtsecurity/home/welcome

维基百科: https://zh.wikipedia.org/wiki/%E8%99%9B%E6%93%AC%E5%8C%96

Intel虚拟化技术: https://www.intel.com/content/www/us/en/virtualization/virtualization-technology/intel-virtualization-technology.html
KVM网站: http://www.linux-kvm.org/page/Main_Page

KVM博客: http://blog.csdn.net/RichardYSteven/article/category/841588

KVM介绍: http://www.cnblogs.com/sammyliu/p/4543110.html

https://www.bbsmax.com/R/B0zqPN73dv/

https://kernelgo.org/categories.html#virtualization-ref

Kvm代码解析连载: http://www.aiuxian.com/article/p-2337268.html

虚拟化: https://blog.csdn.net/wanthelping/category_5682983.html

KVM(Kernel-based Virtual Machine)是Linux下基于X86硬件(包含虚拟化扩展<Intel VT 或 AMD-V>)的全虚拟化解决方案. KVM包含一个可加载的内核模块(kvm.ko), 这个模块提供了核心的虚拟化基础架构和一个特定的处理器模块(kvm-intel.ko或kvm-amd.ko)

使用KVM, 可以运行多个虚拟机, 这些虚拟机是未修改过的Linux或Windows镜像. 每个虚拟机都有独自的虚拟硬件: 网卡、磁盘、图形适配器等.

KVM是一个开源软件. KVM的核心组件被包含在Linux的主线版本中(2.6.20). KVM的用户空间组件包含在QEMU的主线版本(1.3).

活跃在KVM相关虚拟化发展的人们的博客被组织在 http://planet.virt-tools.org/ 这个网站.

先学习关于KVM实践相关的, 比如 <任永杰>的相关的书, 目前2019年最新的是<KVM实战: 原理、进阶与性能调优>
以kvm unit test/简单benchmark为例, 通过ftrace查看流程

虚拟化系列, 偏ARM: https://www.cnblogs.com/LoyenWang/tag/%E8%99%9A%E6%8B%9F%E5%8C%96/

虚拟化很多系列: https://kernelgo.org/archives.html

https://github.com/luohao-brian/interrupt-virtualization

https://www.blogsebastian.cn/?cat=1

逻辑很清晰: https://blog.csdn.net/huang987246510/category_6939709.html (左边分类专栏)



