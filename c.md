# canonical

- canon

c. a general principle by which sth is judge(准则，标准)。

- canonical

ad. according a rule(遵循标准的，规范的)。

- 示例

"In fact, in the early days of the ARPANET there was a canonical host file that was copied to every system periodically(《Operating System Concepts》第 739 页)。

# capability

- capable: capere("to grasp, take, catch")

  **"capable"** originally referred to being able to grasp, hold, or handle something, and its meaning evolved to signify having the ability or capacity to do something.

- capability: capable + -ity(word-forming element making abstract nouns from adjectives and meaning "condition or quality of being )

1. c/u. ability to do something(能力，才干)。

2. c/u. A feature or function that makes something able to perform a specific task(功能)。

示例：Master CPython’s memory management capabilities(注：《CPython Internals》第 14 页)。这句话应该理解为“掌握 CPython 的内存管理功能”。我遇到好几本书有这个用法，如果理解为”能力“则不大准确。

# chassis

- chassis: capsa("box, case")

c. the frame of sth。

- 示例

To allow a system to gain access to more storage, either an individual storage device, a device in a chassis, or multiple drives in a chassis can be connected via USB FireWire or Thunderbolt ports and cables(《Operating System Concepts》第 470 页)。

#  check

- **定义**

vi/vt. to exam sth to ensure it is correct, true, or in good condition.

- **示例**

1.After I'd finished the test, I checked my answers for mistakes.

这种用法比较常见。

2.Unlike PEP 8, there are few tools for checking compliance with PEP 7(《CPython Internals》第78页).

在这里，compliance 的意思是 following rules or standards，Unlike PEP 8 (Python's style guide for code), there are fewer tools available to check if your code adheres to or follows the standards set by PEP 7 (the style guide for C code in CPython).

# check out

- to take something from a library (= a place with a collection of books, music, etc.)，取出。

示例：

1.A sophisticated application amortizes the cost of thread-creation by keeping idle threads in a thread pool, then checking them out to reuse them for subsequent tasks; it does the same with sockets in a connection pool(《500 Lines or Less》第 130 页)。

上面这句话的意思是：成熟的应用程序通过以下方式来分摊创建线程的成本：将空闲线程保留在线程池中，供后续线程重复使用。同理，对于连接池中的套接字，也采用相同的处理方式。

注：在上面这个例子中，check out 可翻译为“取出“——“当后续有任务时，可**取出**这些空闲线程重复使用”。只是为了简洁，所以直接翻译成了“供后续线程重复使用”。

- to explore，investigate("探索，了解")

示例：We’ll also integrate a documentation utility called Swagger for creating API documentation, write unit and integration tests, learn application debugging, and, finally, check out different methods of deploying and monitoring our REST APIs on cloud platforms for production use.(《Building REST APIs with Flask》第 4 页)

上面这句话的意思是：我们还将集成一个名为 Swagger 的文档工具来生成 API 文档、编写单元测试盒集成测试、学习应用程序调试，最后还会探讨在云平台上部署和监控 REST API 以用于生产环境的不同方法。

# coherency

- coherence: co-("together") + haerere("to adhere, stick")

u. sth logically or structurally connected and consistent(连贯性)。

- coherence vs coherency

 两者意思一样，暂时没看出有啥区别，先记录。

1)However, HTM does require that existing cache hierarchies and cache coherency protocols be modified to support transactional memory(《Operating System Concepts》第 312 页)。

2)Discuss, with examples, how the problem of maintaining coherence of cached data manifests itself in the following processing environments:

a.Single-processor systems

b.Multiprocessor systems

c.Distributed systems

# coherent

- coherent：co-("together") + haerere("to stick")

adj. logically connected and having the quality of cohering(连贯统一的)。

- 示例

NFS provides a means to attach remote directories to local directories, thus giving the appearance of a coherent directory tree(《Operating System Concepts》第 763 页)。

# commodity

- commodity:  com-("together, with") + modus("measure, manner"，*med- "take appropriate measures")

c. a mass-produced unspecialized product/good。

- 示例

Typically, this occurs on commodity hardware rather than RAID arrays. For example, HDFS can store N copies of an object on N different computers(《Operating System Concepts》第 484 页)。

刚看到 commodity hardware 的时候很不理解这两个词项组合在一起想表达什么意思，之所以不理解，是因为对commodity 理解不到位，刚开始的时候将commodity 理解为了“products can be bought and sold(即商品，good)”，其实， commodity 还暗含"mass-produced, unspecialized, economic(经济的，大量生产的)" 之意，

所以上面这句话的意思：通常，这种情况发生在商用硬件(”指普通、低成本的标准硬件，区别于专用高端设备)/普通硬件上，而非RAID阵列。例如，HDFS可以在N台不同的计算机上存储一个对象的N个副本。

Commodity hardware in computing is computers or components that are readily available, inexpensive and easily interchangeable with other commodity hardware. Almost all PCs use commodity hardware. The term is most used for general-purpose servers that can be used in any role. Commodity hardware is synonymous with off-the-shelf hardware. It is contrasted with proprietary, custom or bespoke hardware.

# compensate

- compensate: com-("together, with") + pensare("weight, pay")

vt. give (sb) sth, like money, in recognition of loss, suffering or injure(补偿)。vi. to offset an error, defect, or undesired effect(弥补(错误，缺陷，不希望的结果))。

- 示例

示例1：His enthusiasm compensates for his lack of skil(他的热情弥补了他技术上的不足)。

在这个例子中，使用 “enthusiasm” 来弥补 “lack of skill”。

示例2：Operating systems can often compensate effectively for transient failures. For instance, a disk read() failure results in a read() retry, and a network send() error results in a resend(), if the protocol so specifies(《Operating System Concepts》第 512 页)。

在这个例子中，如果只看第一句“通常，操作系统能有效弥补(应对)暂时性故障”，其实不大好理解，因为没有直接体现“使用什么来弥补什么”？翻译为“弥补”也不大通畅。需要结合后面一句来理解。operating system 是怎么弥补 transient failures 的呢？使用 “ read() retry” 来弥补 “read() failure”, 使用 “resend()” 来弥补 “send() error”。

从技术上来说不难理解，其实就是“重试机制”，但是如果不理解词的意思，有时候就不能很好的理解作者想表达的意思。

# con-

- together, with(一起)

示例：connect(join together, 连接)。

- merely intensive(强化作用)

示例：consume(to use up entirly, 消耗，消费)。

# conceive

- conceive: con-(intensive prefix, 强调作用) + capere("to take")

vi/vt. conceive literally means "to take in", to image。

- 示例

Protection was originally conceived as an adjunct to multiprogramming operating systems, so that untrustworthy users might safely share a common logical name space, such as a directory of files, or a common physical name space, such as memory(《Operating System Concepts》第 667 页)。

# conduit

- **conduit: con-("with, together") + ducere("to lead")**

c. A conduit is a channel often used for protedction(（保护线路的）导线管)。

- **示例**

TBD

# confer

- confer: con-("together") + fere("to bear, carry")

vi/vt. to give sth(a title, degree, benefit or right)(给予)。

- 示例

The ability to execute a program that is only partially in memory would confer many benefits(《Operating System Concepts》第 390 页)。

# consequently

- consequence: con-("together, with") + sequi(from root *sekw-, "to follow")

c. a result of a action/cause(结果，后果)。

- consequent

adj. happening as a result of a action/cause(作为结果的，随之而来的)。

- consequently: 

adv. as a result(因此，所以)。

- 示例

By default, socket operations are blocking: when the thread calls a method like connect or recv, it pauses until the operation completes. Consequently to download many pages at once, we need many threads(《500 Lines or Less》第 130 页)。

上面这句话的意思是：默认情况下，套接字操作是阻塞的，当线程调用函数(如：connect(), recv())时，线程会暂停(pause)直到操作完成。因此，如果想同时下载多个页面，就需要使用多线程。

理解 consequently，要搞清楚“cause > result”是什么。以前总是不理解这个词，今天突然想到其实就是“cause > result”，瞬间就理解了这个单词的使用，于是记一下。

# convoy

- convoy: con-("together") + via("road")

c. a group of vehicles traveling together(车队，船队等)。

vt. accompany (a group of vehicles) for protection(护送)。

- 示例

There is a convoy effect as all the other processes wait for the one big process to get off the CPU(《Operating System Concepts》第 207 页)。

以下是个人的理解：其它所有进程(all the other processes)排在一个重量级的进程(one big process后等待，这种场景很像“护送，护航”，所以称为“convoy effect”，effect的意思是"a result or consequence of an action "。convoy effect 直译就是“护航效应”、“护送效应”。

# compiler-compiler 

- **定义**

tools used to generate compilers。也称为compiler generator。在一些不严谨的表述中，本来应该属于 parser generator的工具也称为 compiler generator——Well first the term compiler-compiler has been degraded to include parser generators. I blame that on yacc(yet another compiler-compiler) calling itself a compiler compiler. 

- **示例**

 META II, TREEMETA, CWIC。

# corruption

- corrupt: com-("completely") + rup-("to break")

vt. corrupt literally means "to completely break", over time, it evolves to mean "to change from good to bad"(腐败，损坏)。

- 示例

If the cached changes do not reach the storage device before a crash occurs, more corruption is possible(《Operating System Concepts》第 586 页)。

# counter

- counter: contra-("against, opposite")

vt. in an opposite direction(反对，反驳)。

- 示例

Thus, output to the disk through the file system is often faster than is input for small transfers, counter to intuition(《Operating System Concepts》第 586 页)。

count 和 counter 的词根竟然是不一样的。

# craft

- craft vs make

craft: to create something with care, skill or ingenuity(强调技巧感，艺术性，设计感，对细节的关注，可理解为“精心制作，匠心打造”)。

make:  to create  something(中性词，可理解为“制作，制造”)。

注意：1. craft 和 make 这两个词在翻译中往往需要根据上下文进行灵活调整。2.两者有时可以交换使用，其实本人看到 craft 的时候更多的是将其理解为 make。

- 示例

1.Craft essential Python patterns by following core design principles(《Mastering Python Design Patterns(third edition)》封面)。

上面这句话的意思是：遵循核心设计原则，打造关键的 Python 设计模式。

其实个人觉得在这个例子中将 craft 替换为 make 也不影响，本质都是 code。 
