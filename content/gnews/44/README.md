###  [:house:返回首頁](https://github.com/ourhimalayas/txt)
---


## 比特币的安全隐患
` 秘密翻譯組G-Translators` [轉載自GNews](https://gnews.org/zh-hans/1631413/)

撰稿：billwilliam

校对：Ermat
![](https://assets.gnews.org/wp-content/uploads/2021/10/unnamed-3-1.jpg)图源：thebalance.com
加密货币是使用区块链技术记录交易账簿的数字货币。区块链技术具有隐私、交易不可逆、数据不可更改等优点。作为去中心化的加密货币，比特币号称其最大发行量为2100万枚。然而，网上一些新闻显示，历史上比特币曾多次存在安全漏洞，骇客可能利用这些隐患对比特币系统造成严重破坏。

郭文贵先生10月29日的爆料称：“比特币的价值就是（总发行量）那2100万个币，没有人会怀疑。只要有一个人说，它是2110万个，它就彻底归零。我告诉大家，比特币一定不是2100万个。”【1】换句话说，比特币的价值在于它有限的发行量，但是如果比特币的实际数量多于宣称的总量，那么比特币的信誉就毁于一旦。虽然没有直接证据证明这个论点，一些间接证据显示比特币历史上曾多次出现安全漏洞。

一些网络来源称，曾有骇客伪造过上千亿枚比特币，但是错误数据已被纠正，这就是有名的“数据过载事件”（Value Overflow Incident）。发生在2010年8月15日的这次攻击中，一位骇客利用矿机发布虚假交易信息，声称向两个账号发送总共约1840多亿枚比特币，这个数字是2100万枚总发行量的8700多倍。骇客利用的漏洞就是当时比特币的验证系统无法处理很大的天文数字，尤其是交易额大于比特币的发行量。这就好比汽车的里程表最多只能记载99.9999万公里里程，再加1公里里程表就会调零。同理，这个巨大的数字使比特币系统出现故障，将错误的交易登记在账簿中。在区块链的记账方式中，只要被记入账簿就相当于凭空创造出这个数额的比特币。所幸比特币的开发团队及时发现了这笔荒唐的交易数字，创始人中本聪在3小时内编写出补丁代码，5小时内公布更新的0.3.1版本代码，修补该漏洞，并且更新的数据链删除了错误数据。【2，3，4】笔者个人认为，如果骇客利用某种其它漏洞，采取较隐蔽的方式小额伪造（比如每天伪造1万枚），开发团队可能很难发现超发的比特币。

2013年3月11日，比特币还出现过另一次漏洞CVE-2013-3220，原因是当时新版的0.8.0代码和旧版的0.7.0不兼容，造成新旧两个版本的账簿对不上。当时有些矿机使用新版本代码，有些还在用旧代码。有人曾利用这个漏洞进行二次消费，也就是说同一笔比特币被同时发给了两个账号（或者说同样的比特币花了两遍）。其操作方法是先将这笔比特币发给第一个账号，由新版本的账簿登记交易；然后再将同样的比特币发给另一个账号，由老版本的账簿登记。发现新旧版账簿不一致后，一些矿场联盟将节点降级为0.7.0版本，这样使区块链数据回归到旧版本，保证了数据的一致性。【4】

甚至距离现在很近的2018年还出现过更严重的漏洞。这个缺陷名为CVE-2018-17144，自比特币核心代码0.14.0版公布起就存在，直到一年半后的2018年才有匿名人士在推特上举报。如果骇客利用这个漏洞进行DOS攻击，可以瘫痪95%的节点。同时，骇客可以超量发行比特币，甚至可以进行任意金额的二次消费。二次消费本身就可以创造出超过2100万枚比特币。比如有人利用区块链记账的错误把1万枚比特币同时发给A、B两个账号，那么1万枚比特币就变成了2万枚。另一个名为CVE-2018-17145的漏洞也能超发比特币。这些漏洞出现的原因是当时的代码为了提升运算速度，省略了多重验证。网上的公开信息称，虽然漏洞存在很长时间，但并未发现有骇客利用这些漏洞。【4，5】

在去中心化的加密货币中，不仅仅是比特币，以太币也曾遭到骇客攻击。2016年6月18日，骇客侵入以太币的一个DAO架构，并将其中360万枚以太币转入另一个一模一样的子架构，相当于骇客把以太币转入了自己的钱包。（DAO又名分布自治公司，是一种没有董事会也无国界的众筹基金。）发现袭击后，以太币的开发团队更新代码，任何试图从DAO或DAO子架构中提取以太币都会被系统默认无效，这样使骇客无法转走这些以太币。这次攻击严重伤害以太币的信誉，其价格从20美元跌至13美元。虽然最终骇客没能偷走任何以太币，但是有人认为骇客还是赚到钱了：如果骇客事先大量做空以太币，那么价格暴跌时仍然有机会获利。【6】

另外，去中心化加密货币的弱点是，如果交易平台遭骇客攻击或出现意外事故，很难追回被盗或丢失的加密货币。例如，位于东京的Mt. Gox在早年曾是最大的比特币交易平台。2014年发现，骇客逐渐从该平台偷走了约85万枚比特币，当时价值4.6亿美元。Mt. Gox平台的破产加剧了比特币价格的雪崩，当年价格从800美元跌至400美元。【3，7】又例如，位于香港的Bitfinex交易平台在2016年遭到骇客攻击，约12万枚比特币被盗，当时价值约7200万美元。【3，8】又例如，QuadrigaCX曾是加拿大最大的加密货币交易平台。该平台CEO是唯一能进入客户资产账户的人。这位CEO于2019年离奇死亡，价值约1. 45亿美元的加密货币从此丢失（加上现金总计损失1.9亿万美元）。当然，有分析师认为钱包里的加密货币很少，CEO的死亡（不论真死假死）是为了掩盖该平台的财务危机或洗钱行为，其实账上现金也远远不够。【3，9】

未来更安全的加密货币应当由负责任的法人中心化管理，这样即使遭到骇客攻击，也能及时修改错误数据或追回被盗的资产。相比而言，去中心化的加密货币没有人负责，所以会出现各种安全隐患。去中心化加密货币只有一个优势，就是可以用来洗钱或转脏钱。但是随着各国政府加大反洗钱的力度，去中心化加密货币最终可能消亡。

参考文献：

1. 郭先生10月29日直播

[https://gtv.org/video/id=617be96f11d1862968fccc4b](https://gtv.org/video/id=617be96f11d1862968fccc4b)

2. Shrem, Charlie. “Bitcoin’s Biggest Hack in History: 184.4 Billion Bitcoin from Thin Air.” January 11, 2019.

[https://hackernoon.com/bitcoins-biggest-hack-in-history-184-4-ded46310d4ef](https://hackernoon.com/bitcoins-biggest-hack-in-history-184-4-ded46310d4ef)

3. Copeland, Tim. “7 most-damaging Bitcoin scams and hacks of all time.” April 6, 2019.

[https://decrypt.co/6236/biggest-hacks-and-scams-in-bitcoin-history](https://decrypt.co/6236/biggest-hacks-and-scams-in-bitcoin-history)

4. Zafar, Taha. “Bitcoin Immutability is a Shared Myth—A Brief History of Tx Reversals And Chain Rollbacks.” October 10, 2021.

[https://cryptoticker.io/en/bitcoin-immutability-shared-myth/](https://cryptoticker.io/en/bitcoin-immutability-shared-myth/)

5. Smirnova, Daria. “CVE-2018-17144: A Lot of Frightening Letters for an Equally Frightening Vulnerability.” September 25, 2018.

[https://decenter.org/en/cve-2018-17144-a-lot-of-frightening-letters-for-an-equally-frightening-vulnerability](https://decenter.org/en/cve-2018-17144-a-lot-of-frightening-letters-for-an-equally-frightening-vulnerability)

6. Siegel, David. “Understanding the DAO Attack.” June 25, 2016.

[https://www.coindesk.com/learn/2016/06/25/understanding-the-dao-attack/](https://www.coindesk.com/learn/2016/06/25/understanding-the-dao-attack/)

7. McMillan, Robert. “The Inside Story of Mt. Gox, Bitcoin’s $460 Million Disaster.” March 3, 2014.

[https://www.wired.com/2014/03/bitcoin-exchange/](https://www.wired.com/2014/03/bitcoin-exchange/)

8. Higgins, Stan. “The Bitfinex Bitcoin Hack: What We Know (And Don’t Know).” August 3, 2016.

[https://www.coindesk.com/markets/2016/08/03/the-bitfinex-bitcoin-hack-what-we-know-and-dont-know/](https://www.coindesk.com/markets/2016/08/03/the-bitfinex-bitcoin-hack-what-we-know-and-dont-know/)

9. Copeland, Tim. “The complete story of the QuadrigaCX $190 million scandal.” March 13, 2019.

[https://decrypt.co/5853/complete-story-quadrigacx-190-million](https://decrypt.co/5853/complete-story-quadrigacx-190-million)

（本文仅代表作者个人观点）

 

免责声明：本文内容仅代表作者个人观点，平台不承担任何法律风险。

- [ROL Foundation](https://rolfoundation.org/)
- [ROL Society](https://rolsociety.org/)
- [Terms of use](https://gnews.org/terms-of-use-3/)
- [Privacy Policy](https://gnews.org/privacy-policy/)
