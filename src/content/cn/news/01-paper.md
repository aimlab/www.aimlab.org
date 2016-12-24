pageTitle: 论文
menuTitle: 论文


## 2013

### [0720] 论文: 论文: BAG: Managing GPU as Buffer Cache in Operating Systems，被TPDS录用

Abstract—This paper presents the design, implementation and evaluation of BAG, a system that manages GPU as the buffer cache in operating systems. Unlike previous uses of GPUs, which have focused on the computational capabilities of GPUs, BAG is designed to explore a new dimension in managing GPUs in heterogeneous systems where the GPU memory is an exploitable but always ignored resource. With the carefully designed data structures and algorithms, such as concurrent hashtable, log-structured data store for the management of GPU memory, and highly-parallel GPU kernels for garbage collection, BAG achieves good performance under various workloads. In addition, leveraging the existing abstraction of the operating system not only makes the implementation of BAG non-intrusive, but also facilitates the system deployment.

### [0715] 论文: A Fast RPC system for Virtual Machines，被TPDS刊出

论文“A Fast RPC system for Virtual Machines”被IEEE Transactions on Parallel and Distributed Systems (TPDS)在2013年7月刊出。

Abstract—Despite the advances in high performance interdomain communications for virtual machines (VM), data intensive applications developed for VMs based on the traditional remote procedure call (RPC) mechanism still suffer from performance degradation due to the inherent inefficiency of data serialization/deserilization operations. This paper presents VMRPC, a lightweight RPC framework specifically designed for VMs that leverages the heap and stack sharing mechanism to circumvent unnecessary data copy and serialization/deserilization. Our evaluation shows that the performance of VMRPC is an order of magnitude better than traditional RPC systems and existing alternative interdomain communication optimization systems. The evaluation on a VMRPCenhanced networked file system across a varied range of benchmarks further reveals the competitiveness of VMRPC in IO-intensive applications.

## 2012

### [1221] 论文: 一种针对JVM运行时库安全策略的全自动检测方法，被电子学报录用

汪宁的论文“一种针对JVM运行时库安全策略的全自动检测方法”被电子学报录用。论文的主要内容是：JVM运行时库通过调用自身库函数的安全管理器类能够实现各种各样的安全策略，其中非常重要的一条安全策略是保证程序在执行敏感操作之前必须进行相应的访问控制权限检查。传统上依赖于人工分析来确保JVM运行时库满足该安全策略，由于Java标准类库涵盖上千个类，上万个方法，而且处于快速的发展和演化过程中，人工分析费时费力，容易出错。本文提出一种全自动、高效、快速的模型检测方法评估JVM是否遵守这一安全策略，扫描Java标准类库字节码文件，将类的成员方法生成控制流图，通过定义检验模型，结合污点分析计算出方法摘要，自动检测出风险方法。

## 2011
### [0730] 论文: 一种轻量级安全可信的虚拟执行环境，被《中国科学》录用

《中国科学》是我国自然科学基础理论研究领域里权威性的学术刊物, 在国内外都有着长期而广泛的影响。刘琛的论文“一种轻量级安全可信的虚拟执行环境”被该杂志录用。

论文针对传统TCB (Trusted Computing Base) 庞大复杂的问题，设计并实现了一个 最小化的TCB 系统架构。利用CPU 的系统管理模式(SMM) 提供的硬件隔离特性， 通过将应用程序中对安全敏感的代码放入虚拟环境中执行，从而将应用程序本身非安全敏感部分代码、操作系统及其上运行的其他应用程序排除在TCB 之外，使 得TCB 的软件部分只包含安全敏感代码和虚拟执行环境包含的少量代码，实现了 TCB 的最小化。本系统的强隔离性使得在操作系统和部分硬件(如DMA、硬件调试器等) 被攻击者控制后，依然可以保证安全敏感代码执行过程的隐秘性和执行结果的完整性。同时，本系统还为执行结果提供了细粒度的可靠验证，保证结果是在本系统的保护下得到的，没有被任何恶意程序篡改。

### [0610] 石林博士生论文被 IEEE Transactions on Computers(TOC) 录用

IEEE Transactions on Computers(TOC)是计算机领域国际顶级刊物，石林的论文被该杂志录用。该论文针对现有的虚拟机技术对通用计算支持的不足，提出了一种基于系统调用重定向方法的GPU通用计算平台CUDA虚拟化方案—vCUDA。该研究首次提出了一种GPU设备虚拟化方法，使得在虚拟化环境中部署基于硬件加速的高性能计算成为可能，而以前鲜有将高性能计算应用部署到虚拟化环境中。这在学术界和工业界第一次验证了在虚拟机平台下，在API层次进行高效虚拟化是有可能的。这为在虚拟机系统下进行GPU通用计算、高性能计算、分布式计算提供了前提和技术准备。

## 2008

### [1203] 博士生石林论文被并行与分布式知名会议IPDPS09录用

IEEE International Parallel and Distributed Processing Symposium（IPDPS）是并行与分布式计算领域非常有影响的会议，石林博士的论文“vCUDA: GPU Accelerated High Performance Computing in Virtual Machines”被第23届IPDPS录用。