###  [:house:返回首頁](https://github.com/ourhimalayas/txt)
---


## 科技灭共 教育治国系列之芯片技术 （1）
` 英國倫敦喜莊園 Himalaya London Club UK` [轉載自GNews](https://gnews.org/zh-hans/2116144/)

![](https://assets.gnews.org/wp-content/uploads/2022/03/cubes-g106e72de8_1280.jpg)网络图片
**作者：Sima(正道主义) （英喜） 、足球队长\_Capitain8 （香草山）**

**芯片技术导言**

**前言**

通俗来说，芯片是一种把电子电路小型化并制造在硅晶片上的集成电路产品。

现代文明的人类生活已经无法离开芯片，因为智能手机、电脑、iPad、互联网等的核心部件就是芯片。而且，现今发展最快的AI产业也完全依赖专为AI研发出来的芯片提供的功能和数据处理能力来超越人类自身的智慧。

我们智能手机上的芯片只有指甲壳大小，包含有超过150 亿个基本元件（晶体管）。它们搭建了上千种逻辑电路模块，构造出各种功能：电子显示屏、谷歌地图导航、短视屏播放和朋友通话等等。
[![](https://express.adobe.com/page/9CX4H2SapBRoX/images/a1370539-23ce-4502-92d7-375e25784169.png?asset_id=c55162ef-2da1-4b3a-af89-cac1fcb0f52c&amp;img_etag=%2276dded10860e327b3e01bb2dae681044%22&amp;size=1024)](https://express.adobe.com/page/9CX4H2SapBRoX/images/a1370539-23ce-4502-92d7-375e25784169.png?asset_id=c55162ef-2da1-4b3a-af89-cac1fcb0f52c&amp;img_etag=%2276dded10860e327b3e01bb2dae681044%22&amp;size=1024)网络图片
芯片技术已经成为文明社会发展的强大推动力，人们的日常生活、工业、医疗、太空科技和军事科技都严重依靠芯片技术。任何国家要引领科技进步，保持经济强盛，掌控国家安全都必须拥有芯片设计制造的主导权。

新中国联邦人创造了G系列产品，推出了代表未来先进生产力的G生态平台，当然要在芯片技术上有她的话语权。
[![](https://express.adobe.com/page/9CX4H2SapBRoX/images/886cc055-84d1-4bfc-a7f0-a13a7c486347.png?asset_id=00f46d84-20f5-4294-a105-89c8c6b21a80&amp;img_etag=%22792ac0803173969142c263c784ab24e4%22&amp;size=2560)](https://express.adobe.com/page/9CX4H2SapBRoX/images/886cc055-84d1-4bfc-a7f0-a13a7c486347.png?asset_id=00f46d84-20f5-4294-a105-89c8c6b21a80&amp;img_etag=%22792ac0803173969142c263c784ab24e4%22&amp;size=1024)网络图片
在这个系列文章里，我们先来谈谈集成电路的起源和发展，然后再介绍芯片技术的三个主要环节。它们是：芯片设计，EDA软件开发和应用，芯片制造工艺、设备和材料。

**集成电路的起源和发展**

1.半导体和晶体管

要谈集成电路就必须了解什么是半导体和晶体管。半导体是导电性能介于导体和绝缘体之间的那些材料，最重要的就是硅晶体。

经过几十年的探索和研究，1947年12月，美国贝尔实验室的研究小组（巴丁(J·Bardeen)、布拉顿(W·Brattain)、肖克莱(W·Shockley)）采用半导体材料研制出一种实用的晶体管。晶体管是一种器件，它具有放大、开关等多种功能。晶体管的这些功能正是数字电路的核心所在——逻辑功能。通过电信号来控制晶体管的接通和阻断，这就代表了逻辑0和逻辑1。就是从神奇的数字0和1演变出了今天不可估量的数字时代。

晶体管被认为是现代史中最伟大的发明之一。

2.集成电路（integrated circuit）

集成电路指的是把一组电子电路集成制造在半导体晶片上。

集成电路是1958年由美国德州仪器（TI）公司和仙童公司（Fairchild Semiconductor）各自独立研制发明的。
[![](https://express.adobe.com/page/9CX4H2SapBRoX/images/5a898968-7fc6-4286-87e4-068df2bfcb89.png?asset_id=d8652369-ad3d-47eb-b64c-ada45a94f3be&amp;img_etag=%22787a99c6f99ecde09ebdc9d74e73700a%22&amp;size=1024)](https://express.adobe.com/page/9CX4H2SapBRoX/images/5a898968-7fc6-4286-87e4-068df2bfcb89.png?asset_id=d8652369-ad3d-47eb-b64c-ada45a94f3be&amp;img_etag=%22787a99c6f99ecde09ebdc9d74e73700a%22&amp;size=1024)网络图片
64年前的集成电路看上去很粗糙。它将包括晶体管在内的五个元器件集成在一起，做成了简易集成电路。

量产芯片最初是在1英吋的晶圆上，而今天最大的芯片是在12吋晶圆上制造出的AI芯片。整个晶圆只容下一个芯片，而不是像通常那样一个晶圆切割出几十到几百个同样的芯片。
[![](https://express.adobe.com/page/9CX4H2SapBRoX/images/da1baeb0-901c-4a4a-8faa-9bdfee3190c3.png?asset_id=e1b35c0e-f561-49b1-80d1-508d2fe663f3&amp;img_etag=%2247ea0ea04628386097c260d03a8e3b94%22&amp;size=1024)](https://express.adobe.com/page/9CX4H2SapBRoX/images/da1baeb0-901c-4a4a-8faa-9bdfee3190c3.png?asset_id=e1b35c0e-f561-49b1-80d1-508d2fe663f3&amp;img_etag=%2247ea0ea04628386097c260d03a8e3b94%22&amp;size=1024)网络图片
2021年，最新的一颗AI加速芯片封装了2.6万亿个晶体管，占据了12寸晶圆的全部。集成电路发明后的60多年来，芯片技术的进步真是太神奇了！

我们现在知道：采用半导体材料制造出了晶体管，而晶体管的集成电路就是芯片。

*下一讲，我们将聚焦在集成电路的设计方法。*

参考资料: [integrated circuit](https://www.britannica.com/technology/integrated-circuit)

*编辑：【英国伦敦喜庄园编辑部】*

*校对：仙女儿-文善|审核：文明明| Page：小六月*

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
