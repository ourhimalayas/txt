###  [:house:返回首頁](https://github.com/ourhimalayas/txt)
---


## 科技灭共 教育治国系列之芯片技术（5）
` 英國倫敦喜莊園 Himalaya London Club UK` [轉載自GNews](https://gnews.org/zh-hans/2266018/)

**芯片技术导言**

**作者**：Sima(正道主义)（英喜）|足球队长\_Capitain8（香草山）

![](https://assets.gnews.org/wp-content/uploads/2022/03/38d13bb5b9b84130a8733a629ed84d90.jpg)网络图片

在上一讲里，我们讨论的重点，是以数字电路的原理图为中心的集成电路的前端设计方法。到了上世纪 80 年代末，使用基于原理图的芯片设计流程，对于逻辑门的数量比较大的电路（&gt;10K）变得很困难。因此，硬件描述语言(HDL)被引入来解决这个问题。

HDL是一种用于描述数字系统的语言，小到一个逻辑门，大到存储器模块、微处理器都可以很好的处理。而且采用HDL的流程，易于设计和调试，对于大型电路更是如此。

我们这里要谈论的HDL之一，Verilog，是今天整个半导体行业采用的最流行的硬件描述语言。

Verilog的设计流程，请见下图：

![](https://assets.gnews.org/wp-content/uploads/2022/03/image-4031.png)

上面的前五个步骤，是芯片的前端设计。后面的布局布线和时序仿真，就是芯片的后端设计。时序仿真通过以后，就可以送到芯片制造厂去生产出芯片来了。

在HDL前端设计的流程中，HDL描述和逻辑综合是核心，我们这里来探讨一下。

HDL描述，说的是用Verilog语言来描述逻辑电路的功能和规范。我们还是以最简单的非门为例子：
![](https://assets.gnews.org/wp-content/uploads/2022/03/image-4032.png)
它的文本描述：
module My\_inv(A,Q);
output Q;
input A;
assign Q=~A;
endmodule
这里，My\_inv是设计者给它起的名字，module、endmodule是模块的起始和结束用语。output、input是语言的保留用语，它们定义了端口Q和A的属性。assign 语句赋予了Q逻辑状态（取A相反的值）。

逻辑综合：

综合（synthesize），就是在给定的设计规范的基础上，将设计的高层次逻辑模块（Verilog 建模）转换为标准单元库中元器件的过程。逻辑综合的目的是产生物理电路元器件的集合，并在逻辑、时序上进行一定程度的优化，寻求芯片面积、功耗的平衡。

也就是说，逻辑综合把抽象的逻辑电路模块，按照设计规范，映射为物理上已经实现了的标准元器件的集合。

![](https://assets.gnews.org/wp-content/uploads/2022/03/033121.jpg)

后面两个步骤，也是芯片的后端设计，这里只简单介绍。在下一讲里，我们再深入展开。

**布局布线（Placement & Autorout）**

根据逻辑综合的结果，利用晶片制造厂家提供的，先进工艺制备的标准元器件库，对得到的元器件集合在给定面积上进行布局布线。

**时序仿真（Static Timing Analysis）**

布局布线完成之后，电路物理模型中已经包含了时间延迟信息。利用在布局布线中获得的精确参数，用仿真软件验证电路的时序满足设计规范。

至此，我们讨论了目前芯片设计最流行也是最重要的设计方法。下一讲我们要认真讨论芯片的后端设计，布局布线和时序仿真。它们是芯片设计的最后两个步骤，也是芯片设计的关键所在。

参考资料：[Introduction to Verilog design](http://mtv.ece.ucsb.edu/courses/ece156A_14/lecture02.pdf)

*校对：仙女儿-文善|审核：文明明*

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
