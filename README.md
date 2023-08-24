<h1 align="center">
  <span style="font-size: 32px;">PinTravel</span>
</h1>

<h2 align="center">
  🏞️
</h2>

<h1 align="center">
  Depin with Your Travel.
</h1>

<h2 align="center">
  Link tourists' travel notes in scenic spots with DePin.
</h2>


<h5 align="center">
  2023 Shanghai International Hackathon Week - Shanhaiwu Subvenue Works
</h5>


![PIN](https://github.com/yanboishere/PinTravel/assets/76860915/5bbc70f3-0930-486d-a990-54377293fe50)

DePin+Cultural tourism ecology




## Intro
本团队的灵感来源于山海坞之行，夏日优美如画的北大湖景区在Web2世界却仅仅是寥寥几行文字的闭塞山沟。

随着小红书，大众点评等经典Web2社交点评类应用的发展，通过网络照片了解景区已经成为游客出游必不可少的环节。热门景区可以通过聘请专业摄影团队对旅游景区进行拍摄取景，以便在社交媒体上进行宣传。然而很多地方性的小景点由于缺少资金，难以获得优质的宣传照片，使得宣传工作陷入恶性循环。本团队决定通过利用景区游客的手机，组成去中心化的摄影基础设施网络，充分挖掘DePIN赛道的潜力。



## Feature

- PinTravel 向所有拥有手机终端设备的用户开放使用
- 用户可以使用手机来在景区内游览的过程中 通过相机拍摄照片 以及LBS通讯运营商定位基础设施 每个景区的各个景点 分别生成含有拍摄图片 地理位置戳的SBT纪念证明
- 使用ERC6551 将用户所获得的SBT证明集合成为一个含有多个景点的链上地图 🗺️
- 与中小景区合作 特别是经济相对不发达地区的中小景区 为其提供链上数字化景区解决方案
  - 充分利用用户手机相机形成的物理设施网络 为景区搭建起一套链上景区照片地图
  - 利用景区游客相机以及其生成的SBT 构建起景区的宣传范式
- 构建一个SBT销售平台 激励用户的使用频率
- 在项目上线的1年内完成与至少3家景区的合作（可选）


## Why DePIN?
热门景区拥有大量的资金去聘请专业的摄影团队进行取景拍照。从`Web3`的角度分析，专业团队可以视为一系列由相机、摄影师组成的`CePIN`（中心化摄影基础设施网络）。然而出于成本考量，`CePIN`并不适用于中小景区。

根据XXXX调查显示，中国智能手机用户相机闲置率为XXXX。在手机相机性能内卷的今天，依旧有很多游客缺乏拍照的积极性，而这正是中小旅游景区可以调动利用的。

`DePIN`意为分布式物理基础设施网络，根据MESSARI的调研显示，主流的`DePIN`赛道可以分为四个部分，其中`物理资源网络PRN`是目前参与企业较多的赛道。即通过大规模的分布式硬件基础设施，提供原本专业团队才能够提供的服务。

从`DePIN`赛道的角度分析，游客手机的相机可以视为分布式物理基础设施网络的节点，而游客利用手机拍摄的照片以及其生成的`SBT`可以作为独属于每个人的旅行记忆NFT。景区通过空投发放代币、优惠券等方式回馈用户对网络作出的贡献。`PinTravel`的设想是景区通过代币等虚拟资产来获得现实世界中有形的资产，比如景区的宣传照片与视频。而游客通过利用智能手机不仅可以获得独属于自己的旅行记忆，还能够通过与`DePIN`网络进行交互来获得代币、优惠券等奖励，形成良性循环。

## PinTravel API
本项目在lens基础上二次迭代了一系列接口，具体如下
- 用户在景区固定的位置扫描二维码，并同时可以记录当前位置，上传拍摄的照片lbs
  > `usePinQRCode`, `usePinLocation`, `usePinPhoto`
- 完成景区游览之后，可以生成本次浏览的记录
  > `usePinRoute`, `usePinTravel`, `usePinAlbum`
- 旅程记录作为NFT，旅途的照片，打卡点都可以存在此NFT账户名下 
- 旅游景区可以在链上与旅客的NFT发生买卖行为，旅客可以获得代币，优惠券等奖励，进而鼓励其二刷，三刷
  > `useExchange`, `useShare`, `useSell`(用来区分是换代币，还是优惠券，还只是单纯的允许共享转发)

  > `usePinAgain` 奖励多刷用户
- 旅游景区利用收集到的海量旅客nft资产，可以进行
  - 利用照片做景区采景宣传工作
  - 利用旅客的旅游路线进行推荐路线规划
- 相关的惩戒措施
  - 景区通过截图等方式窃取nft照片
  - 游客在景区内部的不文明行为

## Contributer


[![contrib graph](https://contrib.rocks/image?repo=yanboishere/PinTravel）](https://github.com/yanboishere/PinTravel/graphs/contributors)



<h3 align="center">
  Yanbo
</h3>





<h3 align="center">
  nuttt
</h3>




