# oddity

- oddity: odd + -ity

c. odd characteristic or trait.

- 示例

To encapsulate the details and oddities of different devices, the kernel of an operating system is structured to use device-driver modules(《Operating System Concepts》第 490 页)。

# optimal & optimum

- optimal: optimum + -al

adj. best。

- optimal vs optimum
- 示例

optimum也可以做形容词，意思和 optimal 一样，意为"best"。看到一种说法是“In some areas of mathematics, an optimal value is essentially a local optimum; i.e. it's an optimum value in its neighborhood.”。这里记录一些用例，方便后续比较，理解。

The SJF scheduling algorithm is provably optimal, in that it gives the minimum average waiting time for a given set of processes(《Operating System Concepts》第 207 页)。

# order of growth/rate of growth

刚开始看到 order 的时候感觉很别扭，因为平时遇到的 order 的意思大多是：1.“顺序(the arrangement of things according to a particular pattern)”; 2. "命令(command)"。

在 “order of growth”中， order 的意思是“层级，阶级，等级，量级(rank, level, category, class)” ，理解了这个意思之后，反而觉得 order of growth(增长量级)更准确一些——“算法运行时间在哪个量级，有一种分类的思想在里面”，而 rate of growth(增长率)更通俗易懂一些——“仅仅体现了算法运行时间变化的快慢”。

*f(n) = 4n**2* *,  g(n) = 2n + 2000*

上面的 f(n) 和 g(n) 分别表示两个算法的最差运行时间(worst-case running time)，因为随着输入 n 的变大，f(n) 变化更快，需要的时间更多，则可以说： f(n) has higher order of growth as it grows quadratically in terms of input size。

# order statistics(顺序统计量)

If the random variables x<sub>1</sub>, ...,  x<sub>n</sub> are arranged in order of magnitude and then written as X<sub>(1)</sub> ≤ ... ≤ X<sub>(n)</sub>, we call X<sub>(i)</sub> the  order statistic (i = 1, ..., n).

# overhead

- overhead: over-("above") + head(“top part, uppermost section”)

overhead的字面意思是：above the head,后来演变成"represent things situated above or metaphorically referring to additional costs".

adv. above the head. 

adj. operating, lying, or comming from above. 示例: This room needs overhead lighting(这个房间需要顶灯).

n(c/u). business expenses(such as rent, insurance, or heating)not chargeable to a particular of the work.

- overhead costs vs direct costs

direct costs(直接支出/直接开销/直接成本)：Costs that can be directly traced to a specific product(Example: raw materials, labor costs).

overhead costs(间接支出/间接开销/间接成本，同 indirect costs):  Costs that can be not directly traced to a specific product but are necessary for general operations(Example: rent, insurance, heating)。

在计算机书籍里面，overhead 大多表示的也是“overhead costs”这个意思，会被笼统的翻译成“开销”。

Because the CPython interpreter process has a significant overhead, the Pool will consider each process in the pool a worker. If a worker has completed, it will be reused(《CPython Internals》第232页)。

# oversubscribe

- oversubscribed: over("beyond") + subscribe + -ed

adj. applied for in greater quantities than are available(超额订阅).

- 示例

The advantage of standard swapping is that it allows physical memory to be oversubscribed, so that the system can accommodate more processes than there is actual physical memory to store them(《Operating System Concepts》第 377 页)。