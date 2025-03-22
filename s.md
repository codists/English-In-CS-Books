# semophore

- semaphore: sema("sign, signal"，参考 semantic) + phoros("bearer") 

u. Semaphore literally means "mechanical apparatus for signaling to distant points(向远距离点发送信号的机械装置)"，refer to "a system of sending signals using visual cues(视觉线索)， such as flags(旗子) or lights(灯光)"。

- 示例

A semaphore S is an integer variable that, apart from initialization, is accessed only through two standard atomic operations: wait() and signal()(《Operating System Concepts》第 272 页)。

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

## storage

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