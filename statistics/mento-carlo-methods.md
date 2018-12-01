---
description: 'https://en.wikipedia.org/wiki/Monte_Carlo_method'
---

# Mento Carlo Methods

> 通常蒙特卡罗方法可以粗略地分成两类：一类是所求解的问题本身具有内在的随机性，借助计算机的运算能力可以直接模拟这种随机的过程。例如在核物理研究中，分析中子在反应堆中的传输过程。中子与原子核作用受到量子力学规律的制约，人们只能知道它们相互作用发生的概率，却无法准确获得中子与原子核作用时的位置以及裂变产生的新中子的行进速率和方向。科学家依据其概率进行随机抽样得到裂变位置、速度和方向，这样模拟大量中子的行为后，经过统计就能获得中子传输的范围，作为反应堆设计的依据。  
>
>
> 另一种类型是所求解问题可以转化为某种随机分布的特征数，比如[随机事件](https://zh.wikipedia.org/wiki/%E9%9A%8F%E6%9C%BA%E4%BA%8B%E4%BB%B6)出现的[概率](https://zh.wikipedia.org/wiki/%E6%A6%82%E7%8E%87)，或者[随机变量](https://zh.wikipedia.org/wiki/%E9%9A%8F%E6%9C%BA%E5%8F%98%E9%87%8F)的[期望值](https://zh.wikipedia.org/wiki/%E6%9C%9F%E6%9C%9B%E5%80%BC)。通过随机抽样的方法，以随机事件出现的[频率](https://zh.wikipedia.org/wiki/%E9%A2%91%E7%8E%87)估计其[概率](https://zh.wikipedia.org/wiki/%E6%A6%82%E7%8E%87)，或者以[抽样](https://zh.wikipedia.org/wiki/%E6%8A%BD%E6%A8%A3)的[数字特征](https://zh.wikipedia.org/w/index.php?title=%E6%95%B0%E5%AD%97%E7%89%B9%E5%BE%81&action=edit&redlink=1)估算[随机变量](https://zh.wikipedia.org/wiki/%E9%9A%8F%E6%9C%BA%E5%8F%98%E9%87%8F)的[数字特征](https://zh.wikipedia.org/w/index.php?title=%E6%95%B0%E5%AD%97%E7%89%B9%E5%BE%81&action=edit&redlink=1)，并将其作为问题的解。这种方法多用于求解复杂的多维积分问题。  
>
>
> 假设我们要计算一个不规则图形的面积，那么图形的不规则程度和分析性计算（比如，积分）的复杂程度是成正比的。蒙特卡罗方法基于这样的思想：假想你有一袋豆子，把豆子均匀地朝这个图形上撒，然后数这个图形之中有多少颗豆子，这个豆子的数目就是图形的面积。当你的豆子越小，撒的越多的时候，结果就越精确。借助计算机程序可以生成大量均匀分布坐标点，然后统计出图形内的点数，通过它们占总点数的比例和坐标点生成范围的面积就可以求出图形面积。

