###  [:house:返回首頁](https://github.com/ourhimalayas/txt)
---


## 科技灭共 教育治国系列之芯片技术（4）
` 英國倫敦喜莊園 Himalaya London Club UK` [轉載自GNews](https://gnews.org/zh-hans/2231471/)

**芯片技术导言**

**作者**：Sima(正道主义)（英喜） 足球队长\_Capitain8（香草山）

![](https://assets.gnews.org/wp-content/uploads/2022/03/download-1-4.jpg)网络图片

在前面的第三讲里，我们介绍了简单逻辑电路的设计步骤。今天我们就分别来讨论芯片设计的几种主要方法。我们首先从早期比较经典的方法谈起，那就是用计算机软件在电脑屏幕上画出逻辑电路图，然后转化为多层的物理平面图。在电脑上画出电路原理图，被称作是芯片的前端设计，把它转化为多层的物理平面图，被称作是芯片的后端设计。

芯片的前端设计和后端设计，都需要经过验证它们符合设计规范，然后把多层的物理平面图，送去晶片制造厂，生产出芯片。

**早期的集成电路设计：**
第一步，把电路原理图输入到计算机的原理图编辑器中。
第二步，引导计算机的电路仿真系统来对设计进行分析和验证。
第三步，基于采用制造工艺的物理设计规范（design rules），进行多层的几何平面图形设计。

而芯片制造厂所需要的完备电路设计，就是多层的几何平面图形。这真是出乎不少人的意料和想象。

**集成电路的前端设计：**
我们先介绍现代集成电路最重要的形式——CMOS电路。“CMOS”代表“互补对称金属氧化物半导体”，CMOS 器件的主要特点是低静态功耗和高抗噪性。CMOS反相器是一个非常简单的逻辑门。

**逻辑电路的表达式：**
**1.非门的逻辑符号 （Inverter logic Gate）**

![](https://assets.gnews.org/wp-content/uploads/2022/03/image-3029.png)

**2.非门的晶体管电路图（CMOS）**

![](https://assets.gnews.org/wp-content/uploads/2022/03/image-3036.png)

我们来看一看输入到原理图编辑器中的反相器（非门）。

![](https://assets.gnews.org/wp-content/uploads/2022/03/image-3038.png)

得到了电路原理图，就可以调用计算机电路仿真软件来对设计进行分析和验证。

**电路仿真结果：**

![](https://assets.gnews.org/wp-content/uploads/2022/03/image-3039.png)

电路仿真的结果可以得到很多有用的信息，比如状态转换时间、功率消耗等。如果发现不符合设计规范的地方，就可以及时修改。

**集成电路的后端设计（Layout）**：
现在来看看简单的反相器的布局平面设计（CMOS 工艺）。

同样，从电路原理图中，我们可以看到器件标注的几何尺寸，它们是布局设计的依据。电脑平面布局的软件，此时被调用来做设计。

1. **平面布局示意图（layout）**


![](https://assets.gnews.org/wp-content/uploads/2022/03/image-3040.png)

** 2. 反相器的横截面图**

![](https://assets.gnews.org/wp-content/uploads/2022/03/image-3042.png)

从横截面图可以看出，这个基本逻辑门，至少要用四到五层平面掩膜，才能在硅晶片上被“刻画”出来。

**小结：**
集成电路的前端设计以电原理图为中心的方法，有不少好处：
• 原理图设计师和平面布局（layout）工程师可以并行工作
• 提高工作效率，例如将以前原理图的某些部分重新使用
• 平滑连接到平面布局前的电路仿真和信号分析

在数字集成电路的早期时代，对于一些常用的小型逻辑电路，比如译码器、计数器等，都会被做成芯片。
但是，当集成电路越来越复杂，芯片上的晶体管数量达到百万的时候，可以看到，这种设计方法在时间和人力成本上就完全无法承受了。

因此，集成电路设计的需求，大大促进了电子设计自动化（EDA）行业，由此发展出了基于硬件描述语言（HDL）的设计和验证流程，这种流程可以使用代码文本来描述电路的功能与结构。我们知道，计算机最擅长处理的信息表达方式，是文本和代码，计算机最方便重复使用的信息格式，也是文本和代码。

![](https://assets.gnews.org/wp-content/uploads/2022/03/032210.jpg)

我们下一讲就来讨论使用HDL代码来描述电路，相比于电路原理图而言，这是一种更加有效率的设计方法。

**参考资料：**

1. [Front-End Electronic Design and Schematic Capture](https://www.cadence.com/ko_KR/home/tools/pcb-design-and-analysis/design-authoring.html)


2. [FULL-CUSTOM MASK LAYOUT DESIGN](http://lad.dsc.ufcg.edu.br/epfl/ch03.html)

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
