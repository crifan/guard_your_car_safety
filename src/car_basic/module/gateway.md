# 车载网关

* `车载网关`
  * 概述
    * 车载网关为各网段ECU提供报文路由转发服务,与车内所有ECU均有数据交互，有些网关还承担OTA升级的主刷控制器功能
    * 车载网关通过不同网络间的物理隔离和不同通信协议间的转换，在各个共享通信数据的功能域
      * 如动力总成域、底盘和安全域、车身控制域、信息娱乐域、远程信息处理域、ADAS域之间进行信息交互
        * `ADAS`=`Advanced Driving Assistance System`=`高级驾驶辅助系统`
  * 汽车网关是整车电子电器架构的核心部件，可通过`CAN`协议与车内其它ECU进行交互，是车内网络的数据交互枢纽
