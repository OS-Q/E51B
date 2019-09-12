# [Framework N12](https://github.com/OS-Q/N12)
[![sites](OS-Q/OS-Q.png)](http://www.OS-Q.com)
#### 关于系统架构：[OS-Q](https://github.com/OS-Q/OS-Q)

[EDGE-Q](https://github.com/OS-Q/EDGE-Q) -> Q[4] -> M[12] -> W[52] -> D[365] -> H[24] -> N[60] -> S[60]

### [Framework描述](https://github.com/OS-Q/N12/wiki) 

[Framework N12](https://github.com/OS-Q/N12) 用于支持ESP8266平台运行RTOS，基于Espressif [ESP8266_RTOS](https://github.com/espressif/ESP8266_RTOS_SDK)

使用 freeRTOS 系统，引入 OS 多任务处理的机制，用户可以使用 freeRTOS 的标准接口实 现资源管理、循环操作、任务内延时、任 务间信息传递和同步等面向任务流程的设计方式。

网络操作接口是标准 lwIP API，同时提供了 BSD Socket APIsocket 接口的封装实现，用户可以直接按照socket API的使用方式来开发软件应用，也可以直接编译运行其他平台的标准 Socket 应用。

SDK 引入了 cJSON 库，使用该库函数可以更加方便的实现对 JSON 数据包的解析。

兼容non-OS SDK中的Wi-Fi接 口、smart config接口、Sniffer相关接口、系统接口、定时器接 口、FOTA接口和外围驱动接口，不支持AT实现。

### [关联资源](https://github.com/OS-Q/)

 *  [ Platform H8](https://github.com/OS-Q/H8) 
*   [Framework N13](https://github.com/OS-Q/N13)


### [OS-Q = Open Solutions | Open Source |  Operating System ](http://www.OS-Q.com/N12)
####  2019-9-6