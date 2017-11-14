### 关于TDSQL
TDSQL是腾讯TEG计费平台部打造的一套基于MySQL的金融级分布式数据库解决方案，旨在解决多副本强一致性、高可用、高性能、分布式、配套设施、安全保障等方面难题，其在腾讯内部有大量的使用场景，最开始诞生于2012年的TEG计费平台部，承载了腾讯公司所有数字支付相关业务，截止目前已承载200亿账户数据；2014年被微众银行（WeBank）选中，作为其核心交易系统的数据库解决方案，以私有云方式交付；2015年，在腾讯云上正式推出。目前已经为大量金融政企机构提供数据库的公有云及专有云服务，客户覆盖银行、保险、证券、互联网金融、计费、第三方支付、物联网、互联网+、政务等领域。

### 关键特性
- **基于Raft的强同步机制**。保证强一致性前提下实现高可用，确保数据能实现跨机架、跨IDC、跨城的数据可靠性，强同步节点故障自动切换，实现数据零丢失。


- **灵活的全球部署架构**。99.99%高可用性，轻松支持异地多活：两IDC对等架构；两地三中心架构；两地四中心架构；多地多中心。


- **数据库内核深度优化**。使得在主备网络延迟5ms的情况下，能做到跨IDC强同步性能相较于异步同步零损耗；同时sysbench OLTP TPS是原生MySQL版本185%。


- **安全增强**。在安全方面做了大量优化及增强，包括数据文件加密、SQL防火墙、SSL接入、安全审计等。


- **分布式水平扩展**。提供Auto Sharding机制，可实现实时在线无缝扩容，确保集群性能和容量呈线性增长；同时提供健壮的2PC分布式事务机制，在性能损耗极低的情况下，大大降低了传统业务迁移分布式架构的难度，从此彻底告别数据库中间件。


- **自动化运营体系**。提供完善的运营体系，自动化运营发布平台，机器资源自动管理，智能监控平台及展示，数据库智能诊断等。


- **完善的配套设施**。TDSQL还提供Binlog订阅、冷备系统、多源同步等配套系统，供客户选择。

### 相关文章

- [拓路前行-TDSQL追求极致体验的这一路](https://mp.weixin.qq.com/s/U05lBie3kUK4zhNOpAK4Vw)
- [腾讯云分布式数据库DCDB发布，解决容量、并发、扩展等难题](https://mp.weixin.qq.com/s/SsSx7zWZj37kyGW1qdBivA)
- [腾讯私有云MySQL解决方案—TDSQL](https://mp.weixin.qq.com/s/p2yJw2T9TdSlyQ7eRV5uAA)
- [破局者 - 腾讯金融级数据库TDSQL](https://mp.weixin.qq.com/s/cnAcTjHr3xh-cbnW0sTEmQ)

* [探寻腾讯金融数据库TDSQL的十年之路](http://www.infoq.com/cn/news/2016/11/tencent-tdsql-for-finance)
* [腾讯金融级分布式数据库TDSQL的前世今生](http://mp.weixin.qq.com/s/cYQx5JaZJXf9Woi28STT0w)
* [腾讯云金融级数据库TDSQL分析](http://www.csdn.net/article/2015-11-06/2826138-SDCC)
* [分布式MySQL数据库TDSQL架构分析](http://www.csdn.net/article/2015-06-02/2824824)


### 联系我们
微信扫码关注TDSQL官方公众号    
​     
![](https://raw.githubusercontent.com/TDSQL/homepage/gh-pages/qrcode_for_tdsql.jpg)