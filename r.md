# RAM

General-purpose computers run most of their programs from rewritable memory, called main memory (also called random-access memory, or RAM). Main memory commonly is implemented in a semiconductor technology called dynamic random-access memory (DRAM)。

main memory也称为 RAM， primary memory，一边来说，当只使用 memory 时，其实指的是 main memory(RAM)。 关于 memory 的术语非常多，需要根据上下文去理解具体指的是什么，不能一味套用 。

# reaper

- reap

vi/vt. to cut and collect a grain crop(收割)。

- reaper

c. a machine that cut and collect crops(收割机)。

- 示例

Such kernel routines are often known as reapers, and they may apply any of the page-replacement algorithms covered in Section 10.4(《Operating System Concepts》第 417 页)。

# reclaim

- reclaim: re-("again") + clamare("cry out, shout, call")

vt. recalim litterally means "to claim back", "to take back", or "to demand the return of sth"。It is often used to describe restoring something to a better state  or asserting ownership over something that was lost or taken away(回收).

- 示例

When the process terminates, the operating system will reclaim any reusable resources(《Operating System Concepts》第 18 页)。

# reference implementation

- refer: re-("back") + fere("to carry")

Refer literally means "to carry back", and over time, it evolved to mean "to direct attention to sth(引导注意力到xxx)" or "to mention sth(提及)"。

- reference: refer + -ance(word-forming element attached to verbs to form abstract nouns of process or fact)

reference 有三种用法：1）c/u. the act of mentioning sth。2) vt. to refer to sth。3) adj. used or usable for reference。

CPython is the “official” or reference implementation of Python(注：《CPython Internals》第 21 页).

这里的 reference 用作 adjective，意思是“供参考的，供参照的”，reference implementation 常译作“参考实现”，有时候也称为 sample example、model implementation。

- 定义

In the software development process, a reference implementation is a program that implements all requirements from a corresponding specification(在软件开发过程中，参考实现是一种实现了对应规范中所有需求的程序)。

例如上面的 CPython 就是一种参考实现。

- 含义

reference implementation means the implementation that serves as a standard, guide, or basis(我们称某种实现为参考实现，意思是把这种实现当做一种标准、指南或者基础)。

- 说明

其实 reference implementation 的定义比较模糊，并不是很绝对。

# reserve

- reserve: re-("back") + servare("to keep")

vt. to keep back for further use。

- 示例 

Most CPUs have two interrupt request lines. One is the nonmaskable interrupt, which is reserved for events such as unrecoverable memory errors(《Operating System Concepts》第 496 页)。

- reserve vs preserve

reserve: to save sth for later use。

preserve: maintain sth in its original manner/state。

# resiliency

- resilience: re-("back") + salire("to jump, leap")

u. resilience literally means to jump back. the ability to recover from difficulty(恢复力)，主要用在英式英语中。

- resiliency: resilience + -cy

意思和 resilience 一样，主要用在美式英语中。

- 示例

Although some networks have built-in resiliency, including multiple paths between hosts, many do not. Any single failure can thus interrupt the flow of DFS commands.(《Operating System Concepts》第 608 页)。

# resolve

- resolve: re-("again") + solvere("to loosen, untie, release")

vt. resolve literally means "to loosen or release sth back to its original state", over time, it envolves to mean "to find a solution(untie a problem，解决)"。

-  resolve vs solve

暂没看到比较明显的区分。下面是本人认为相而言还说的过去的一个对比：

solve, resolve, unfold, unravel, decipher can all mean to make clear or apparent or intelligible what is obscure or mysterious or incomprehensible. Solve is the most general in meaning and suggestion in this group; it implies the finding of a satisfactory answer or solution, usually to something of at least moderate difficulty {the mystery and disquieting meaninglessness of existence ... were solved for me now—L. P. Smith} {create a difficulty rather than solve one—A. M. Young} Resolve [...], as contrasted with solve, is likely to indicate analytic arrangement and consideration of the various phases or items of a problem or situation rather than finding a final solution or answer and is likely to suggest dispelling of confusion or perplexity by a clear formulation of questions or issues {you may find it of some interest to be told that the law has had to struggle with these problems and to know how it has resolved them—[Benjamin] Cardozo} In some situations this process may achieve an answer, especially a ready or summary one {he was at the same time resolving successive tangles of intrigue against himself and his policy—[Hilaire] Belloc} {it was realized that the method of resolving apparent contradictions by liquidating one of the contradictories is not the way to arrive at true solutions—Times Lit[erary] Sup[plement]}

- 示例

To resolve differences like this, many RPC systems define a machine-independent representation of data(《Operating System Concepts》第 548 页)。

If the directory entry is marked as a link, then the name of the real file is included in the link information. We resolve the link by using that path name to locate the real file(《Operating System Concepts》第 548 页)。

# resume

- resume: re-("again") + sumere("to take")

vi/vt. Resume literally means "to take again", over time, it envolve to mean "continue doing sth after a pause"。

- 示例

When a server receives a request, rather than creating a thread, it instead submits the request to the thread pool and resumes waiting for additional requests(《Operating System Concepts》第 177 页)。

在上面这个句子中，resume 也是“continue doing sth after a pause”的意思。当然，英语中有时候为了简洁，往往会省略一些内容，为了更好的理解，这里句子可以改成：

When a server receives a request, rather than creating a thread, it instead stop waiting to submit the request to the thread pool. After submitting the request, server resumes waiting for additional requests.

总之，要理解resume的在具体上下文中的含义，就要把握住“continue doing sth after a pause”的思想。如果句子不全不好理解，就先把句子补全去理解。

# rewind

- rewind: re-("again") + wind("to turn, to twist")

vi/vt. go back to the beginning, move back to the start.

- 示例

We may also read(), write(), or reposition() (rewind or skip to the end of the file, for example)(《Operating System Concepts》第 71 页)。

# rigidly

- rigid: rigere("be stiff(firm or hard)")

adj. stiff or fixed; not able to bent or moved.

**Mnemonic**：**RIGID = Really Inflexible, Greatly Immovable, Definitely stiff.**

- rigidly

adv. in a stiff or fixed way.

示例：Files may be free-form (for example, text files), or they may be formatted rigidly (for example, fixed fields such as an mp3 music file)(《Operating System Concepts》第 29 页)。

在上面这句话中，rigidly 的意思是“strictly, inflexibly, in a highly structured manner”,当然，这种描述比较抽象。