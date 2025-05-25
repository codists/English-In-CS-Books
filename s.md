# sacrifice

- sacrifice: sacr-("sacred, holy, 神圣的") + -fice("to do, to make")

vt. sacrifice literally means "to make sacred, to make holy", over time, it evolves to mean "give up sth valuable for a higher purpose(牺牲)"。

- 示例

For example, a temporary file system is used for fast storage and retrieval of nonpersistent files, while the default secondary storage file system (such as Linux ext4) sacrifices performance for reliability and features(《Operating System Concepts》第 563 页)。

# save someone the trouble/bother (of doing sth)

- 释义

idiom. to do something so that someone else does not have to do it.

- 示例

1. I'll make the appointment for you to save you the trouble/bother.

2. This convention saves us the trouble of naming the bounding constant, allowing it to remain anonymous while we focus on more important variables in an analysis.

上面这句话的意思是：这一约定省去了我们为界限常数(bounding constant)命名的麻烦, 让界限常数保持匿名使得我们在分析中能将注意力集中在更重要的变量上。

# semophore

- semaphore: sema("sign, signal"，参考 semantic) + phoros("bearer") 

u. Semaphore literally means "mechanical apparatus for signaling to distant points(向远距离点发送信号的机械装置)"，refer to "a system of sending signals using visual cues(视觉线索)， such as flags(旗子) or lights(灯光)"。

- 示例

A semaphore S is an integer variable that, apart from initialization, is accessed only through two standard atomic operations: wait() and signal()(《Operating System Concepts》第 272 页)。

# slice vs slice up

- slice

vt. to cut with or as if with a knif(切)。

示例：Could you slice a very thin piece of cake for me?

- slice up

slice up 偏向于 "to cut into multiple pieces" 之意。

示例：As you have seen in the preceding chapters, a general-purpose computer system can have multiple storage devices, and those devices can be sliced up into partitions, which hold volumes, which in turn hold file systems(《Operating System Concepts》第 597 页)。

- 某些场景下两者也可以交换使用

示例：Slice the mushrooms thinly and fry in butter。

示例：A disk can be sliced into multiple partitions, or a volume can span multiple partitions on multiple disks(《Operating System Concepts》第 601 页)。

# snapshot

- snapshot: snap("to seize quickly, suddenly") + shot("an act of shooting")

c. snapshot literally means "a quick shot with a gun"。in 1890, it was used to mean "photograph shot with a handheld camera", and figuratively, snapshot  is  used  of sth captured at a moment in time.

- 示例

The file system can then remove the old pointers and the old blocks and make them available for reuse. If the old pointers and blocks are kept, a snapshot is created; the snapshot is a view of the file system at a specific point in time (before any updates after that time were applied)(《Operating System Concepts》第 588 页)。

# spawn

- spawn: 来自于词根 expandere。

- expandere: ex-("out") + pandere("to spread")

spawn原来的意思是“spreading out of fish eggs released in water”，后来演变为“vt. to engender in large number(大量产生), give rise to(产生)， generate(), bring forth sth(产生，创造)”。

- create vs spawn

CPython provides both a high-level and a low-level API for creating, spawning, and controlling threads from Python(《CPython Internals》第250页)。

# spontaneously

- spontaneous: sponte("of one's own accord, willingly(自愿)")

adj. in a way that is natural, often sudden, and not planned or forced(自发的)。

- spontaneously

- 示例

Error detection determines if a problem has occurred — for example a bit in DRAM spontaneously changed from a 0 to a 1, the contents of a network packet changed during transmission, or a block of data changed between when it was written and when it was read(《Operating System Concepts》第 462 页)。

# squint

- squint

vi. look askance(斜视)；look at things with eyes partly closed(眯着眼看)。

- 示例

Since the difference between ⌈n/2⌉ and ⌊n/2⌋ is at most 1, which for large n is much smaller than the effect of dividing n by 2, we’ll squint a little and just call them both size n=2。

注：

1.⌈n/2⌉ is the ceiling of n/2 — it rounds up。

。⌊n/2⌋ is the floor of n/2 — it rounds down。

在上面这个例子中"squint a little(斜视一点)"是一种比喻用法，意思是“ignore the small difference to simplify the situation”。

# storage

下面是根据本人理解的进行总结，基于“虚实”进行分类。

1.虚(逻辑上的)

- register
- cache
- primary storage

也称为 primary memory, main memory，RAM等。

- secondary storage

也称为 secondary memory。

2.实(物理上的)

- register
- cache
- primary storage

RAM，ROM。

- secondary storage

使用的物理材料是：HDDS(Hard Disk Drivers)， NVM。

# stub

- stub

c. the short end which is left after the main part of sth has beend remove(存根， 树桩)。

In programming, a stub is a small, incomplete piece of code that stands in for a larger or more complex component(function, or procedure)。

- 示例

The RPC system hides the details that allow communication to take place by providing a stub on the client side(《Operating System Concepts》第 150 页)。

如上, stub想表达的意思：In RPC systems, the term "stub" is used because it represents a simplified, local version of a remote service, much like a "stub" is a small, leftover part of something larger。

# symmetric & symmetrical

- 释义

adj. having similarity in size, shape, and relative position of corresponding parts(对称的)。symmetric 和 symmetrical 的意思是一样的。

- 区别

symmetric: 多用于 technical，mathematical field(如：mathematics, phsics，CS)。

symmetrical: 多用于 common field(如：art, design, nature)。

注：查资料的时候发现有些人对以上区别也不是很认同，从个人有限的阅读中，CS书籍用 symmetric 比较多。

- 示例

1)symmetric matrix(对称矩阵)

