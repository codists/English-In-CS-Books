# paradigm

-  pradadigm: para-("beside(next to)") + *deik-("to show")

c. Paradigm refere to sth serves as a typical example, model or pattern(范式)。

- 示例

One of the most common forms of remote service is the RPC paradigm, which was designed as a way to abstract the procedure-call mechanism for use between systems with network connections(《Operating System Concepts》第 149 页)。

# parser generator

- 定义

A parser generator is a tool that generates a parser from a formal description of a language's grammar. 

- 示例

Bison，YACC()，ANTLR。

# peculiarity

- peculiar: peculium("private property, personal possession")

adj. Peculiar literally means "sth that is specially one's own", like personal propery, over time, peculiar envolves to mean "sth that is distinct, unusual or different"。

- peculiarity: peculiar + -ity

c/u. the distinctive, unusual, or unique feature or characteristic of sth(特性).

示例：Only the device driver knows the peculiarities of the specific device to which it is assigned(《Operating System Concepts》第 32 页)。

# preempt

- preemption: pre-("before") + emption(*em-, "to take, to buy")

也写作 pre-emption。c/u. Preemption originally means "a purchase by one before an opportunity is offered to others(有限购买权)"， which later evolved to mean "the act of preventing sth from happening by taking action first(优先采取行动预防某事发生，即先发制人) "

- preempt: back-formation of pre-emption.

也写作pre-empt。vt. to prevent sth from happening by taking action first, to take action before others（抢占，先占）。

示例：The interrupt mechanism also implements a system of interrupt priority levels. These levels enable the CPU to defer the handling of low-priority interrupts without masking all interrupts and makes it possible for a high-priority interrupt to preempt the execution of a low-priority interrupt(《Operating System Concepts》第 11 页)。

# prevalent

- prevalent: pre-("before, in front of") + valere("have power, be strong")

adj. widespread, existing every commonly(普遍).

- 示例

Embedded computers are the most prevalent form of computers in existence(《Operating System Concepts》第 45 页)。

# primitive

- 语言中的 primitive 

primitive: primus("first", 参考 prime) + -itive(a suffix that forms adjectives, indicating the characteristic of sth)

adj. Primitive  literally means "relating to the first or original state". In a broader sense, it describes sth is fundamental or simple in nature。

c. sth primitive。

- 编程中的 primitive

primitive 在英语中的意思不难理解，意为"原始的"。难以理解的是在编程中，primitive 作为名词的定义是什么，到底什么样的东西可以称为 primitive？下面是一些个人的理解：

Primitive is the most simple operation or function that are provied by a sytem, programming language, hardware, which serves as the foundation for more complex funtionality.

个人认为，primitive 想描述某个东西是"basic(基础的), simple(简单的), fundamental(不能再分的)"，但 primitive 的定义是笼统的，相对的，没有明确的分界线——比如操作系统的 send(), receive() 称为 primitive, 那么我自己定义的某个函数(如：myfunc()) 能不能称为 primitive?

个人不大喜欢这个术语，因为没有明确的分界线，也尽量不用这个词，但我们要能做到：看到别人用这个词的时候，明白别人想表达的意思。

- 示例

1.operating system primitiv

Under direct communication, each process that wants to communicate must explicitly name the recipient or sender of the communication. In this scheme, the send() and receive() primitives are defined as: 

send(P, message)—Send a message to process P. 

receive(Q, message)—Receive a message from process Q

个人认为，从操作系统层面来看，send(), receive() 是不可再分的，原始的，所以称为 primitive。但是从代码层面来说，其实这些函数是由许多语句组成的，那就不再适合称为 primitive。所以个人认为primitive 的定义是笼统的，相对的，没有明确的分界线，看所处的角度(层面)。

# processing

- adjective 用法

In fact, a process may be interrupted at any point in its instruction stream, and the processing core may be assigned to execute instructions of another process(《Operating System Concepts》第 257 页)。

在上面这个例子中，processing 用于修饰 core, 表示“ core is used for processing”。

# provable

- prove: *per-("forward") + *buh("to be")

vt. to show sth is true。

- provable:

adj. be able to be proven。

- probably:

adv. in a way that be able to be proven。

- 示例

The SJF scheduling algorithm is provably optimal, in that it gives the minimum average waiting time for a given set of processes(《Operating System Concepts》第 207 页)。