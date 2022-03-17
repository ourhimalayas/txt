###  [:house:返回首頁](https://github.com/ourhimalayas/txt)
---


## 科技灭共 &#8211; 教育治国系列 芯片技术（3）
` 英國倫敦喜莊園 Himalaya London Club UK` [轉載自GNews](https://gnews.org/zh-hans/2180792/)

**作者：Sima(正道主义)（英喜）、足球队长\_Capitain8（香草山）**
[![](https://express.adobe.com/page/l6QwdYLTrWZf2/images/0cc263d1-df7d-43a4-980f-67e261237a40.jpg?asset_id=51767c1f-88db-4b7d-97ec-c29e8cb2467c&amp;img_etag=%22a9651e810195a40ba37862164d3a0a99%22&amp;size=2560)](https://express.adobe.com/page/l6QwdYLTrWZf2/images/0cc263d1-df7d-43a4-980f-67e261237a40.jpg?asset_id=51767c1f-88db-4b7d-97ec-c29e8cb2467c&amp;img_etag=%22a9651e810195a40ba37862164d3a0a99%22&amp;size=1024)
**芯片技术导言**

在第二讲里，我们了解了模拟电路和数字电路的基本概念，也讨论了组合逻辑和时序逻辑电路。在这一讲里，首先复习一下数字电路的基础——二进制，然后我们介绍简单逻辑电路的设计。有了逻辑电路设计的概念，我们就可以深入讨论逻辑电路设计的几种方法。等到我们设计出了所需要的逻辑电路，就可以进入到电路在硅芯片上物理实现的过程了。

**二进制**

二进制（binary）在数字电路中指以2为基数的记数系统。这一系统中，通常用两个不同的符号0和1来表示。数字电子电路中，逻辑门的实现直接应用了二进制，因此现代的计算机的设备里都采用二进制。

我们来看看熟悉的十进制数字和二进制数字的对应表达：
[![](https://express.adobe.com/page/l6QwdYLTrWZf2/images/20d322cf-36c3-4e2d-94c3-08af6ad95895.png?asset_id=8e099395-b812-4220-9395-c34e33d9334b&amp;img_etag=%22608201f41abacfaa428e3ec740ebb312%22&amp;size=1024)](https://express.adobe.com/page/l6QwdYLTrWZf2/images/20d322cf-36c3-4e2d-94c3-08af6ad95895.png?asset_id=8e099395-b812-4220-9395-c34e33d9334b&amp;img_etag=%22608201f41abacfaa428e3ec740ebb312%22&amp;size=1024)
二进制化为十进制

100101转换为十进制形式如下：

100101=1×25+0×24+0×23+1×22+0×2+1×1

100101=1×32+0×16+0×8+1×4+0×2+1×1

100101=37

十进制的数当然也可以转化为二进制，我们这里就不多说了。

**简单逻辑电路的设计**

我们还是从简单的组合逻辑电路的设计说起。设计的基本步骤如下：

依据电路规范，确定所需的输入和输出端口的数目

根据每个输出与输入的逻辑关系，推导出每个输出端的真值表

简化每个输出的逻辑表达式（使用卡诺图或布尔代数）

画出简化的逻辑表达式的逻辑图，通过分析或仿真来验证设计

我们通过一个例子来给大家说明：

1.设计规范

一个具有3位二进制输入和单个输出的电路，指定如下：

输入（3位）标记为 C、B、A

输出（1位）标记为 Z

逻辑功能

Z=0-&gt;输入小于二进制的5

Z=1-&gt;其他情况

2.导出真值表
[![](https://express.adobe.com/page/l6QwdYLTrWZf2/images/6cffbf9e-e06e-4983-9b5b-971ebe18467e.png?asset_id=58360bb3-b727-42c9-bf29-95a68e30dd9c&amp;img_etag=%22cf15cabf364abeea3affd5a58205c02b%22&amp;size=2560)](https://express.adobe.com/page/l6QwdYLTrWZf2/images/6cffbf9e-e06e-4983-9b5b-971ebe18467e.png?asset_id=58360bb3-b727-42c9-bf29-95a68e30dd9c&amp;img_etag=%22cf15cabf364abeea3affd5a58205c02b%22&amp;size=1024)
真值表清楚地表明：

Z=0-&gt;输入小于二进制的5（000、001、010、011、100）

Z=1-&gt;其他情况（101、110、111）

从真值表可以推导出电路的逻辑表达式（使用卡诺图或布尔代数），这里我们不做深入讨论。

3.电路的逻辑表达式：

Z=(A+B)\*C

4.画出逻辑电路图
[![](https://express.adobe.com/page/l6QwdYLTrWZf2/images/772a3cd9-e2d1-4a4e-b50b-2d026d50d947.png?asset_id=42589160-b441-40fb-bf86-1a00a99150ec&amp;img_etag=%226dcf23e5bd25cc5c4688bb6eb0d7c90c%22&amp;size=2560)](https://express.adobe.com/page/l6QwdYLTrWZf2/images/772a3cd9-e2d1-4a4e-b50b-2d026d50d947.png?asset_id=42589160-b441-40fb-bf86-1a00a99150ec&amp;img_etag=%226dcf23e5bd25cc5c4688bb6eb0d7c90c%22&amp;size=1024)
我们看到，2个基本的逻辑门（或门，与门）构建了这个所规范的逻辑功能。读者可以自行验证这个电路确实满足设计规范。

**数字逻辑电路的设计方法**

至此，我们已经了解了数字逻辑电路设计的基本程序。当然，现代集成电路的设计，不是这样以人工来进行的，设计的每一个步骤都是用计算机辅助设计的软件来完成的。

主要的数字逻辑电路设计方法是：

1. 用计算机软件在电脑屏幕上画出逻辑电路图，然后转化为多层的物理平面图，经过验证后，送去芯片制造厂，生产出芯片。

2. 采用硬件描述语言（DHL），把整个逻辑电路写出来，然后转化为多层的物理平面图。验证后送去芯片制造厂，生产出芯片。

3. 采用预制好逻辑门数组的芯片（FPGA），把原始设计出来的逻辑电路映射到逻辑门阵列芯片上，通过特殊布线方式，把逻辑门阵列连接成原始设计的功能。验证后，芯片就完成了。
[![](https://express.adobe.com/page/l6QwdYLTrWZf2/images/7759e717-5b01-4b9c-8739-ccbb26d0f143.png?asset_id=47620a68-b46d-40d2-84ab-f4d6a25abe9a&amp;img_etag=%22893ea0f359a92c099f8aaebfa4e72cf7%22&amp;size=1024)](https://express.adobe.com/page/l6QwdYLTrWZf2/images/7759e717-5b01-4b9c-8739-ccbb26d0f143.png?asset_id=47620a68-b46d-40d2-84ab-f4d6a25abe9a&amp;img_etag=%22893ea0f359a92c099f8aaebfa4e72cf7%22&amp;size=1024)
我们下一讲，就来讨论这几种逻辑电路的设计方法。

Refer: [Digital Logic Design](https://www.csie.ntu.edu.tw/~pjcheng/course/asm2008/asm_ch2_dl.pdf) (PDF文件下载）

*编辑：【英国伦敦喜庄园编辑部】*

*校对：仙女儿-文善|审核：文明明| Page：小六月*

- [点击阅读英国伦敦喜庄园在G-News 的更多精彩文章](https://gnews.org/zh-hans/author/himalaya_hawk/)
- [点击观看英国伦敦喜庄园在G-TV的精彩视频](https://gtv.org/web/#/UserInfo/5ee680a45bd6f123dd104807)
- [欢迎加入【英国伦敦喜庄园】Discord官方群](https://discord.com/invite/VsNaHaMUsy)

[![](https://express.adobe.com/page/l6QwdYLTrWZf2/images/743201f9-58fc-4293-a06f-95392264cc21.jpg?asset_id=02cb6ee0-4cc9-44e1-8183-c5d8c5bf112e&amp;img_etag=%22fb035768c8cb9d7a5024d2e8b5ca4124%22&amp;size=1024)](https://express.adobe.com/page/l6QwdYLTrWZf2/images/743201f9-58fc-4293-a06f-95392264cc21.jpg?asset_id=02cb6ee0-4cc9-44e1-8183-c5d8c5bf112e&amp;img_etag=%22fb035768c8cb9d7a5024d2e8b5ca4124%22&amp;size=1024)
 

免责声明：本文内容仅代表作者个人观点，平台不承担任何法律风险。

- [ROL Foundation](https://rolfoundation.org/)
- [ROL Society](https://rolsociety.org/)
- [Terms of use](https://gnews.org/terms-of-use-3/)
- [Privacy Policy](https://gnews.org/privacy-policy/)
