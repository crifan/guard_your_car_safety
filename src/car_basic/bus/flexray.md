# FlexRay

* `FlexRay`
  * 是什么：汽车领域的网络通信（总线）协议
  * 谁开发的：FlexRay联合会
    * 核心成员
      * Freescale Semiconductor
      * Robert Bosch GmbH
      * NXP Semiconductors
      * BMW AG
      * Volkswagen AG
      * Daimler AG
      * General Motors
  * 目的：用于管理汽车中的计算资源
    * 希望比`CAN`和`TTP`速度更快更可靠
  * 优点
    * 速度更快 = 传输速率更高
    * 更可靠
    * 容错率更高
  * 缺点：成本更高=更贵
  * 发展历史
    * 2009年，FlexRay联合会，已解散
      * 但FlexRay的协议标准已成为ISO标准：`ISO 17458-1`到`ISO 17458-5`
  * 内部机制
    * 基于时间循环内操作，被拆分成静态或动态的时间段segment，用于基于事件触发或基于时间触发的通讯
