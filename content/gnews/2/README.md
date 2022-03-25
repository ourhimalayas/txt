###  [:house:返回首頁](https://github.com/ourhimalayas/txt)
---


## 科技灭共 教育治国系列之芯片技术（2）
` 英國倫敦喜莊園 Himalaya London Club UK` [轉載自GNews](https://gnews.org/zh-hans/2231386/)

**作者**：Sima(正道主义)（英喜）     足球队长\_Capitain8（香草山）

![](https://assets.gnews.org/wp-content/uploads/2022/03/serverguard2-1.jpg)



从芯片技术导言的第一讲里，我们已经清楚地了解到，芯片就是在半导体材料上制造出的晶体管集成电路。这里，让我们对电路加深一些理解。

**电子电路分为模拟电路和数字电路两种。顾名思义，对模拟信号进行处理的电路称为模拟电路，对数字信号进行处理的叫做数字电路。**

**1.模拟电路**
我们先说说什么是模拟信号，自然界中的声音、温度、位移、压力这些物理量随时间都是连续变化的，它们就被称为是模拟信号。

![](https://assets.gnews.org/wp-content/uploads/2022/03/image-3020.png)

上面这个简图，给出了一个典型的模拟电路的应用场景。

人们去参加歌手的演唱会，歌手和乐器的声音通过麦克风转换成了模拟电信号，经过模拟放大器，增强了的电信号送到扬声器，推动扬声器的纸盆振动，把歌手的歌声传到人们的耳朵里。

**2.数字电路**
数字信号：一般情况下，数字信号是以二进制数位表示的，所以它只有 0 和1 两个逻辑电平。

![](https://assets.gnews.org/wp-content/uploads/2022/03/image-3022.png)

用数字信号进行算术运算和逻辑运算的电路称为数字电路。

数字电路既能进行算术运算又能方便地进行逻辑运算(与、或、非、判断、比较等)，因此极其适合于运算、存储、决策等应用。

我们的课程主要将围绕数字电路展开。

**数字电路又可以分成两大类，一类叫组合逻辑电路，另一类叫做时序逻辑电路。组合逻辑电路的特点是任意时刻的输出仅仅取决于该时刻的输入。**

我们现在就来讨论组合逻辑电路。

**1.组合逻辑电路**

逻辑门是组合逻辑电路的基本结构。组合逻辑电路就是各种逻辑门搭建而成的复杂电路。

最基本的三种逻辑门：与门（AND），或门（OR），非门（INV）
与门的逻辑功能：两个输入端A，B同时为 1，输出Q为1.

![](https://assets.gnews.org/wp-content/uploads/2022/03/image-3024.png)

或门的逻辑功能：两个输入端 A，B任何1个为 1，输出Q为1.

![](https://assets.gnews.org/wp-content/uploads/2022/03/image-3027.png)

**非门的**逻辑功能：输出Q永远和输入端A相反.

![](https://assets.gnews.org/wp-content/uploads/2022/03/image-3029.png)

这里是一个应用的例子：
某安保系统有三个密码，分别由主任与两个安保人员持有。主任的密码可以直接开机，而两个安保人员的密码只有同时输入才能开机。该系统还有一个保险装置，激活时无论那个密码都无法开机。

对应的组合逻辑电路图：

![](https://assets.gnews.org/wp-content/uploads/2022/03/image-3031.png)

我们让A、B、C分别表示三个输入端，D表示保险装置，你能看懂这个应用吗？

**2.时序逻辑电路**

时序逻辑电路在逻辑功能上的特点是任意时刻的输出不仅取决于当时的输入信号，而且还取决于电路原来的状态，或者说，还与以前的输入有关。

时序逻辑电路比较复杂，我们不作过多介绍，只要记住，时序逻辑电路是由组合逻辑电路加上存储或记忆电路构成的。

![](https://assets.gnews.org/wp-content/uploads/2022/03/image-3033.png)

时序逻辑电路包括：计数器、寄存器、顺序脉冲发生器等。

有了上面的基础知识，我们下一讲就来看看怎么设计半导体数字集成电路。

**参考资料：**

1. [Combinatorial Logic](https://www.sciencedirect.com/topics/computer-science/combinatorial-logic)

2. [Basics of Sequential Circuits, Types & Their Working](https://www.elprocus.com/different-types-of-sequential-circuits/)

*校对/审核：仙女儿-文善*

* * *

- [点击阅读英国伦敦喜庄园在G-News 的更多精彩文章](https://gnews.org/zh-hans/author/himalaya_hawk/)
- [点击观看英国伦敦喜庄园在G-TV的精彩视频](https://gtv.org/web/#/UserInfo/5ee680a45bd6f123dd104807)
- [欢迎加入【英国伦敦喜庄园】Discord官方群](https://discord.gg/VsNaHaMUsy)


编辑：【英国伦敦喜庄园编辑部】

![](https://assets.gnews.org/wp-content/uploads/2021/08/41bf97c0-3bb2-4a07-ad75-91b96dc3203c.jpg)







 

免责声明：本文内容仅代表作者个人观点，平台不承担任何法律风险。

- [ROL Foundation](https://rolfoundation.org/)
- [ROL Society](https://rolsociety.org/)
- [Terms of use](https://gnews.org/terms-of-use-3/)
- [Privacy Policy](https://gnews.org/privacy-policy/)
