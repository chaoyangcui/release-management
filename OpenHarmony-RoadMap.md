###### OpenHarmony社区版本发布计划





# OpenHarmony社区版本发布计划：

| **迭代计划** | **版本号**            |**API版本号**| **版本构建** | **版本转测试** | **版本测试完成** |
| ------------ | --------------------- | --------- | ------------ | -------------- | ---------------- |
| IT1          | OpenHarmony 2.2 Beta2  | 6         | 2021/7/21    | 2021/7/21      | **2021/7/30**    |
| IT2          | OpenHarmony 3.0 LTS   | 7         | 2021/9/22    | 2021/9/22      | **2021/9/28**    |
| IT3          | OpenHarmony 3.1 Beta1 | 8         | 2021/11/17   | 2021/11/17     | **2021/11/23**   |
| IT4          | OpenHarmony 3.1 Beta2 | 8         | 2022/1/10    | 2022/1/10      | **2022/1/17**    |

# 各版本特性交付清单：

## OpenHarmony 2.2 beta2版本特性清单：

状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)

第一批需求列表：

| no   | issue                                                        | feture description                                  | status     | sig                  | owner                                         |
| :--- | ------------------------------------------------------------ | :-------------------------------------------------- | :--------- | :------------------- | :-------------------------------------------- |
| 1    | [I3ICFO](https://gitee.com/openharmony/utils_native_lite/issues/I3ICFO) | 【分布式数据管理】提供数据库内容的删除能力          | developing | SIG_DataManagement   | [@widecode](https://gitee.com/widecode)       |
| 2    | [I3ICH0](https://gitee.com/openharmony/utils_native_lite/issues/I3ICH0) | 【分布式数据管理】提供统一的HAL文件系统操作函数实现 | developing | SIG_DataManagement   | [@widecode](https://gitee.com/widecode)       |
| 3    | [I3ICG4](https://gitee.com/openharmony/utils_native_lite/issues/I3ICG4) | 【分布式数据管理】提供相关数据存储的原子操作能力    | developing | SIG_DataManagement   | [@widecode](https://gitee.com/widecode)       |
| 4    | [I3ICGH](https://gitee.com/openharmony/utils_native_lite/issues/I3ICGH) | 【分布式数据管理】提供二进制Value的写入读取能力     | developing | SIG_DataManagement   | [@widecode](https://gitee.com/widecode)       |
| 5    | [I3HX0V](https://gitee.com/openharmony/hiviewdfx_hilog_lite/issues/I3HX0V) | 【HiLog】L1系统HiLog功能增强                        | developing | SIG_BscSoftSrv       | [@shenchenkai](https://gitee.com/shenchenkai) |
| 7    | [I3INEZ](https://gitee.com/openharmony/ai_engine/issues/I3INEZ) | 【AI子系统】AI引擎支持基于共享内存的数据传输        | developing | SIG_AI               | [@armylee0](https://gitee.com/armylee0)       |
| 8    | [I3NSPB](https://gitee.com/openharmony/graphic_ui/issues/I3NSPB) | 【轻量级图形】UIKit组件支持margin/padding           | developing | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)       |
| 9    | [I3NSZH](https://gitee.com/openharmony/graphic_ui/issues/I3NSZH) | 【轻量级图形】圆形/胶囊按钮支持缩放和白色蒙层动效   | developing | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)       |

第二批需求列表：

| no   | issue                                                        | feture description                                           | status     | sig                  | owner                                               |
| :--- | ------------------------------------------------------------ | :----------------------------------------------------------- | :--------- | :------------------- | :-------------------------------------------------- |
| 1    | [I3NN2K](https://gitee.com/openharmony/ace_engine_lite/issues/I3NN2K) | 【ACE开发框架】支持设备侧Bytecode转换后验证应用运行正常测试跟踪 | developing | SIG_AppFramework     | [@borne](https://gitee.com/borne)                   |
| 2    | [I3O2G8](https://gitee.com/openharmony/aafwk_aafwk_lite/issues/I3O2G8) | 【应用程序框架】按照应用粒度的存储资源使用统计               | developing | SIG_AppFramework     | [@autumn](https://gitee.com/autumn330)              |
| 3    | [I3NN3P](https://gitee.com/openharmony/ace_engine_lite/issues/I3NN3P) | 【应用程序框架】支持在设备侧Bytecode转换                     | developing | SIG_AppFramework     | [@autumn](https://gitee.com/autumn330)              |
| 4    | [I3NCKH](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NCKH) | 【轻内核子系统】L0上支持基于NOR Flash的littlefs文件系统      | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 5    | [I3NCTE](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NCTE) | 【轻内核子系统】L0上对外提供统一的文件系统操作接口           | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 6    | [I3NCX2](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NCX2) | 【轻内核子系统】L0 补充120个POSIX接口                        | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 7    | [I3NT2C](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT2C) | 【轻内核子系统】移植mksh命令解析器                           | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 8    | [I3NT2K](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT2K) | 【轻内核子系统】shell交互友好性提升                          | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 9    | [I3NT2V](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT2V) | 【轻内核子系统】移植toybox命令集                             | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 10   | [I3NT4N](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT4N) | 【轻内核子系统】Namecache模块                                | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 11   | [I3NT58](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT58) | 【轻内核子系统】Vnode管理                                    | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 12   | [I3NT5Q](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT5Q) | 【轻内核子系统】Lookup模块                                   | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 13   | [I3NT6H](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT6H) | 【轻内核子系统】文件系统维测增强                             | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 14   | [I3NT6U](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT6U) | 【轻内核子系统】liteos-a內核模块可配置                       | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 15   | [I3NT78](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT78) | 【轻内核子系统】liteos-a小系统三方芯片适配                   | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 16   | [I3NT48](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT48) | 【轻内核子系统】proc文件系统增强                             | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 17   | [I3ND6Y](https://gitee.com/openharmony/kernel_liteos_a/issues/I3ND6Y) | 【性能】OS内核&驱动启动优化                                  | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 18   | [I3ND6P](https://gitee.com/openharmony/kernel_liteos_a/issues/I3ND6P) | 【性能】安全启动优化                                         | developing | SIG_Security         | [@jiang-xiaofeng](https://gitee.com/jiang-xiaofeng) |
| 19   | [I3NCB9](https://gitee.com/openharmony/third_party_Linux_Kernel/issues/I3NCB9) | 【L1 Linux开源】编译器替换后的内核代码适配                   | developing | SIG_Kernel           | [@zzzuo](https://gitee.com/zzzuo)                   |
| 20   | [I3NBVI](https://gitee.com/openharmony/build_lite/issues/I3NBVI) | 【L1 Linux开源】clang替换                                    | developing | SIG_CompileRuntime   | [@zhuoli72](https://gitee.com/zhuoli72)             |
| 21   | [I3NC8H](https://gitee.com/openharmony/build_lite/issues/I3NC8H) | 【L1 Linux开源】musl库替换                                   | developing | SIG_CompileRuntime   | [@zhuoli72](https://gitee.com/zhuoli72)             |
| 22   | [I3NCEF](https://gitee.com/openharmony/build_lite/issues/I3NCEF) | 【L1 Linux开源】工具集替换                                   | developing | SIG_CompileRuntime   | [@taiyipei](https://gitee.com/taiyipei)             |
| 23   | [I3NCF7](https://gitee.com/openharmony/build_lite/issues/I3NCF7) | 【L1 Linux开源】rootfs替换                                   | developing | SIG_CompileRuntime   | [@taiyipei](https://gitee.com/taiyipei)             |
| 24   | [I3NCG0](https://gitee.com/openharmony/build_lite/issues/I3NCG0) | 【L1 Linux开源】镜像制作工具替换                             | developing | SIG_CompileRuntime   | [@taiyipei](https://gitee.com/taiyipei)             |
| 25   | [I3NCGM](https://gitee.com/openharmony/build_lite/issues/I3NCGM) | 【L1 Linux开源】开源编译构建                                 | developing | SIG_CompileRuntime   | [@taiyipei](https://gitee.com/taiyipei)             |
| 26   | [I3NCCT](https://gitee.com/openharmony/drivers_adapter/issues/I3NCCT) | 【L1 Linux开源】编译器替换后的HDF适配                        | developing | SIG_DriverFramework  | [@zianed](https://gitee.com/zianed)                 |
| 27   | [I3NE8P](https://gitee.com/openharmony/powermgr_powermgr_lite/issues/I3NE8P) | 【电源管理】充放电状态查询接口                               | developing | SIG_HardwareMng      | [@zianed](https://gitee.com/zianed)                 |
| 28   | [I3NIEJ)](https://gitee.com/openharmony/powermgr_powermgr_lite/issues/I3NIEJ) | 【电源管理】电量查询接口                                     | developing | SIG_HardwareMng      | [@zianed](https://gitee.com/zianed)                 |
| 29   | [I3NIFG](https://gitee.com/openharmony/powermgr_powermgr_lite/issues/I3NIFG) | 【电源管理】实现并提供低功耗模式                             | developing | SIG_HardwareMng      | [@zianed](https://gitee.com/zianed)                 |
| 30   | [I3NIFR](https://gitee.com/openharmony/powermgr_powermgr_lite/issues/I3NIFR) | 【电源管理】提供低功耗模式统一API                            | developing | SIG_HardwareMng      | [@zianed](https://gitee.com/zianed)                 |
| 31   | [I3N0LP](https://gitee.com/openharmony/global_i18n_lite/issues/I3N0LP?from=project-issue) | 【全球化子系统】构建自定义数据编译能力                       | developing | SIG_AppFramework     | [@zhengbin5](https://gitee.com/zhengbin5)           |
| 32   | [I3N0OP](https://gitee.com/openharmony/global_i18n_lite/issues/I3N0OP?from=project-issue) | 【全球化子系统】构建星期、单复数、数字开关国际化能力         | developing | SIG_AppFramework     | [@zhengbin5](https://gitee.com/zhengbin5)           |
| 33   | [I3I1V8](https://gitee.com/openharmony/global_resmgr_lite/issues/I3I1V8) | 【全球化子系统】构建应用资源解析和加载机制                   | developing | SIG_AppFramework     | [@zhengbin5](https://gitee.com/zhengbin5)           |
| 34   | [I3I1VJ](https://gitee.com/openharmony/global_resmgr_lite/issues/I3I1VJ) | 【全球化子系统】构建资源回溯机制                             | developing | SIG_AppFramework     | [@zhengbin5](https://gitee.com/zhengbin5)           |
| 33   | [I3NIME](https://gitee.com/openharmony/startup_appspawn_lite/issues/I3NIME) | 【启动恢复子系统】支持恢复出厂设置                           | developing | SIG_BscSoftSrv       | [@handyohos](https://gitee.com/handyohos)           |
| 34   | [I3NTBC](https://gitee.com/openharmony/startup_appspawn_lite/issues/I3NTBC) | 【启动恢复子系统】L0/L1/L2接口优化                           | developing | SIG_BscSoftSrv       | [@handyohos](https://gitee.com/handyohos)           |
| 35   | [I3NTCT](https://gitee.com/openharmony/startup_appspawn_lite/issues/I3NTCT) | 【启动恢复子系统】Linux版本init支持热插拔                    | developing | SIG_BscSoftSrv       | [@handyohos](https://gitee.com/handyohos)           |
| 36   | [I3NN4H](https://gitee.com/openharmony/hiviewdfx_hiview_lite/issues/I3NN4H) | 【DFX子系统】【HiLog】L0系统HiLog功能增强                    | developing | SIG_BscSoftSrv       | [@shenchenkai](https://gitee.com/shenchenkai)       |
| 37   | [I3NN53](https://gitee.com/openharmony/hiviewdfx_hiview_lite/issues/I3NN53) | 【DFX子系统】【HiEvent】L0系统HiEvent功能增强                | developing | SIG_BscSoftSrv       | [@shenchenkai](https://gitee.com/shenchenkai)       |
| 38   | [I3NN7D](https://gitee.com/openharmony/hiviewdfx_hiview_lite/issues/I3NN7D) | 【DFX子系统】【HiDumper】LiteOS_A系统信息dump工具            | developing | SIG_BscSoftSrv       | [@kkup180](https://gitee.com/kkup180)               |
| 39   | [I3ID9Q](https://gitee.com/openharmony/distributedschedule_dms_fwk_lite/issues/I3ID9Q) | 【分布式调度】建立轻量设备DMS与富设备DMS通信通道             | developing | SIG_AppFramework     | [@lijiarun](https://gitee.com/lijiarun)             |
| 40   | [I3ID9V](https://gitee.com/openharmony/distributedschedule_dms_fwk_lite/issues/I3ID9V) | 【分布式调度】轻量设备启动富设备上的Ability                  | developing | SIG_AppFramework     | [@lijiarun](https://gitee.com/lijiarun)             |
| 41   | [I3QEVG](https://gitee.com/openharmony/distributedschedule_dms_fwk_lite/issues/I3QEVG) | 【分布式调度】轻量设备启动富设备Ability的安全校验            | developing | SIG_AppFramework     | [@lijiarun](https://gitee.com/lijiarun)             |
| 42   | [I3NK7D](https://gitee.com/openharmony/multimedia_utils_lite/issues/I3NK7D) | 【多媒体子系统】适配新南向接口                               | developing | SIG_GraphicsAndMedia | [@zhu-mingliang](https://gitee.com/zhu-mingliang)   |
| 43   | [I3NM60](https://gitee.com/openharmony/multimedia_utils_lite/issues/I3NM60) | 【多媒体子系统】相机metadata管理及相机静态能力查询           | developing | SIG_GraphicsAndMedia | [@zhu-mingliang](https://gitee.com/zhu-mingliang)   |
| 44   | [I3NM6F](https://gitee.com/openharmony/multimedia_utils_lite/issues/I3NM6F) | 【多媒体子系统】相机设备管理                                 | developing | SIG_GraphicsAndMedia | [@zhu-mingliang](https://gitee.com/zhu-mingliang)   |
| 45   | [I3NM73](https://gitee.com/openharmony/multimedia_utils_lite/issues/I3NM73) | 【多媒体子系统】相机图像帧管理                               | developing | SIG_GraphicsAndMedia | [@zhu-mingliang](https://gitee.com/zhu-mingliang)   |
| 46   | [I3NM8J](https://gitee.com/openharmony/multimedia_utils_lite/issues/I3NM8J) | 【多媒体子系统】本地mp3播放支持                              | developing | SIG_GraphicsAndMedia | [@zhu-mingliang](https://gitee.com/zhu-mingliang)   |
| 47   | [I3NMMU](https://gitee.com/openharmony/multimedia_utils_lite/issues/I3NMMU) | 【多媒体子系统】编码视频流和音频流处理支持                   | developing | SIG_GraphicsAndMedia | [@zhu-mingliang](https://gitee.com/zhu-mingliang)   |
| 48   | [I3NIJT](https://gitee.com/openharmony/communication_softbus_lite/issues/I3NIJT) | 【软总线】软总线平台传输信道管理                             | developing | SIG_SoftBus          | [@yinyouzhan](https://gitee.com/yinyouzhan)         |
| 49   | [I3NIK6](https://gitee.com/openharmony/communication_softbus_lite/issues/I3NIK6) | 【软总线】软总线平台传输消息能力                             | developing | SIG_SoftBus          | [@yinyouzhan](https://gitee.com/yinyouzhan)         |
| 50   | [I3NIMY)](https://gitee.com/openharmony/communication_softbus_lite/issues/I3NIMY) | 【软总线】【连接】BR/EDR模块管理                             | developing | SIG_SoftBus          | [@yinyouzhan](https://gitee.com/yinyouzhan)         |
| 51   | [I3NINO](https://gitee.com/openharmony/communication_softbus_lite/issues/I3NINO) | 【软总线】【传输】会话协商                                   | developing | SIG_SoftBus          | [@yinyouzhan](https://gitee.com/yinyouzhan)         |
| 52   | [I3NIO5](https://gitee.com/openharmony/communication_softbus_lite/issues/I3NIO5) | 【软总线】【传输】UDP通道打开和关闭                          | developing | SIG_SoftBus          | [@yinyouzhan](https://gitee.com/yinyouzhan)         |
| 53   | [I3NIOF](https://gitee.com/openharmony/communication_softbus_lite/issues/I3NIOF) | 【软总线】【传输】传输SDK                                    | developing | SIG_SoftBus          | [@yinyouzhan](https://gitee.com/yinyouzhan)         |
| 54   | [I3NIOT](https://gitee.com/openharmony/communication_softbus_lite/issues/I3NIOT) | 【软总线】【传输】蓝牙通道打开和关闭                         | developing | SIG_SoftBus          | [@yinyouzhan](https://gitee.com/yinyouzhan)         |
| 55   | [I3NIPH](https://gitee.com/openharmony/communication_softbus_lite/issues/I3NIPH) | 【软总线】【传输】消息传输                                   | developing | SIG_SoftBus          | [@yinyouzhan](https://gitee.com/yinyouzhan)         |
| 56   | [I3NIPO](https://gitee.com/openharmony/communication_softbus_lite/issues/I3NIPO) | 【软总线】【传输】Byte传输                                   | developing | SIG_SoftBus          | [@yinyouzhan](https://gitee.com/yinyouzhan)         |
| 57   | [I3NIQ0](https://gitee.com/openharmony/communication_softbus_lite/issues/I3NIQ0) | 【软总线】【组网】【自组网管理】安全：提供通道级加密和设备级认证能力 | developing | SIG_SoftBus          | [@yinyouzhan](https://gitee.com/yinyouzhan)         |
| 58   | [I3NIQ7](https://gitee.com/openharmony/communication_softbus_lite/issues/I3NIQ7) | 【软总线】【组网】【系统API】组网节点设备信息设置、查询      | developing | SIG_SoftBus          | [@yinyouzhan](https://gitee.com/yinyouzhan)         |
| 59   | [I3NIQM](https://gitee.com/openharmony/communication_softbus_lite/issues/I3NIQM) | 【软总线】【组网】【北向API】设备入网&上下线通知             | developing | SIG_SoftBus          | [@yinyouzhan](https://gitee.com/yinyouzhan)         |
| 60   | [I3NIQX](https://gitee.com/openharmony/communication_softbus_lite/issues/I3NIQX) | 【软总线】【连接】BLE模块管理                                | developing | SIG_SoftBus          | [@yinyouzhan](https://gitee.com/yinyouzhan)         |
| 62   | [I3NIRY](https://gitee.com/openharmony/communication_softbus_lite/issues/I3NIRY) | 【软总线】【连接】连接管理模块功能实现                       | developing | SIG_SoftBus          | [@yinyouzhan](https://gitee.com/yinyouzhan)         |
| 62   | [I3NIZD](https://gitee.com/openharmony/communication_softbus_lite/issues/I3NIZD) | 【软总线】【连接】连接策略的定义与管理                       | developing | SIG_SoftBus          | [@yinyouzhan](https://gitee.com/yinyouzhan)         |
| 63   | [I3NJ05](https://gitee.com/openharmony/communication_softbus_lite/issues/I3NJ05) | 【软总线】【发现】BLE发现                                    | developing | SIG_SoftBus          | [@yinyouzhan](https://gitee.com/yinyouzhan)         |
| 64   | [I3NJ0R](https://gitee.com/openharmony/communication_softbus_lite/issues/I3NJ0R) | 【软总线】【发现】发现调度模块功能实现                       | developing | SIG_SoftBus          | [@yinyouzhan](https://gitee.com/yinyouzhan)         |
| 65   | [I3NJ3I](https://gitee.com/openharmony/communication_softbus_lite/issues/I3NJ3I) | 【软总线】【发现】CoAP发现                                   | developing | SIG_SoftBus          | [@yinyouzhan](https://gitee.com/yinyouzhan)         |
| 66   | [I3NJ4P](https://gitee.com/openharmony/communication_softbus_lite/issues/I3NJ4P) | 【软总线】【发现】发现连接模块内部接口                       | developing | SIG_SoftBus          | [@yinyouzhan](https://gitee.com/yinyouzhan)         |
| 67   | [I3NJ57](https://gitee.com/openharmony/communication_softbus_lite/issues/I3NJ57) | 【软总线】【发现】发现服务模块                               | developing | SIG_SoftBus          | [@yinyouzhan](https://gitee.com/yinyouzhan)         |
| 68   | [I3NJ5N](https://gitee.com/openharmony/communication_softbus_lite/issues/I3NJ5N) | 【软总线】【发现】发现连接模块外部接口                       | developing | SIG_SoftBus          | [@yinyouzhan](https://gitee.com/yinyouzhan)         |
| 69   | [I3NQR3](https://gitee.com/openharmony/communication_softbus_lite/issues/I3NQR3) | 【软总线】大屏软总线支持门锁画中画功能需求                   | developing | SIG_SoftBus          | [@yinyouzhan](https://gitee.com/yinyouzhan)         |
| 70   | [I3NQRN](https://gitee.com/openharmony/communication_softbus_lite/issues/I3NQRN) | 【软总线】L1软总线支持WiFi UDP消息通信                       | developing | SIG_SoftBus          | [@yinyouzhan](https://gitee.com/yinyouzhan)         |
| 71   | [I3NQTJ](https://gitee.com/openharmony/communication_softbus_lite/issues/I3NQTJ) | 【软总线】L1软总线支持WiFi UDP组网                           | developing | SIG_SoftBus          | [@yinyouzhan](https://gitee.com/yinyouzhan)         |
| 72   | [I3NQUA](https://gitee.com/openharmony/communication_softbus_lite/issues/I3NQUA) | 【软总线】L1软总线支持WiFi发现连接                           | developing | SIG_SoftBus          | [@yinyouzhan](https://gitee.com/yinyouzhan)         |
| 73   | [I3QE85](https://gitee.com/openharmony/drivers_framework/issues/I3QE85) | 【驱动子系统】L0支持HDF框架                                  | developing | SIG_DriverFramework  | [@zianed](https://gitee.com/zianed)                 |
| 74   | [I3NSVQ](https://gitee.com/openharmony/graphic_ui/issues/I3NSVQ) | 【轻量级图形】DFX维测能力：UIKit支持显示控件轮廓             | developing | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)             |
| 75   | [I3NSWY](https://gitee.com/openharmony/graphic_ui/issues/I3NSWY) | 【轻量级图形】ScrollView/List支持通过弧形进度条展示滑动进度  | developing | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)             |
| 76   | [I3NSZZ](https://gitee.com/openharmony/graphic_ui/issues/I3NSZZ) | 【轻量级图形】支持开关按钮/复选框/单选按钮动效               | developing | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)             |
| 77   | [I3NSQ6](https://gitee.com/openharmony/graphic_ui/issues/I3NSQ6) | 【轻量级图形】UIKit支持点阵字体产品化解耦                    | developing | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)             |
| 78   | [I3NSZ1](https://gitee.com/openharmony/graphic_ui/issues/I3NSZ1) | 【轻量级图形】UI框架提供统一多后端框架支持多芯片平台         | developing | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)             |
| 79   | [I3NSY0](https://gitee.com/openharmony/graphic_ui/issues/I3NSY0) | 【轻量级图形】支持A4\A8、LUT8、TSC图片格式作为输入           | developing | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)             |
| 80   | [I3NT0R](https://gitee.com/openharmony/graphic_ui/issues/I3NT0R) | 【轻量级图形】支持多语言字体对齐                             | developing | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)             |
| 81   | [I3SNIP](https://gitee.com/openharmony/kernel_liteos_m/issues/I3SNIP) | 【轻内核子系统】L0支持三方组件Mbedtls编译                    | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 82   | [I3SNKK](https://gitee.com/openharmony/kernel_liteos_m/issues/I3SNKK) | 【轻内核子系统】L0支持三方组件curl编译                       | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 83   | [I3SMI1](https://gitee.com/openharmony/distributeddatamgr_appdatamgr/issues/I3SMI1) | 【分布式数据管理】支持轻量级设备上分布式数据对象跨设备同步到手机/PAD | developing | SIG_DataManagement   | [@widecode](https://gitee.com/widecode)             |
| 84   | [I3SNGO](https://gitee.com/openharmony/build_lite/issues/I3SNGO) | 【编译子系统】build_lite支持开源软件的通用patch框架          | developing | SIG_CompileRuntime   | [@taiyipei](https://gitee.com/taiyipei)             |
| 85   | [I3WLDI](https://gitee.com/openharmony/kernel_liteos_m/issues/I3WLDI) | 【轻内核子系统】L0支持轻量级shell框架和常用调测命令              | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 86   | [I3WLCN](https://gitee.com/openharmony/kernel_liteos_m/issues/I3WLCN) | 【轻内核子系统】L0 LiteOS-M支持ARM9架构                     | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |

## OpenHarmony 3.0 LTS版本特性清单：

状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)

| no   | issue                                                        | feture description                                           | status     | sig                  | owner                                               |
| :--- | ------------------------------------------------------------ | :----------------------------------------------------------- | :--------- | :------------------- | :-------------------------------------------------- |
| 1    | [I3NJDR](https://gitee.com/openharmony/graphic_utils/issues/I3NJDR) | 【图形子系统】avatar窗口合成器适配surfaceview等控件          | developing | SIG_GraphicsAndMedia | [@lz-230](https://gitee.com/lz-230)                 |
| 2    | [I3NJQ2](https://gitee.com/openharmony/graphic_utils/issues/I3NJQ2) | 【图形子系统】avatar窗口适配                                 | developing | SIG_GraphicsAndMedia | [@lz-230](https://gitee.com/lz-230)                 |
| 3    | [I3NJUK](https://gitee.com/openharmony/graphic_utils/issues/I3NJUK) | 【图形子系统】图形子系统提供系统级的BufferQueue管理，memory接口适配 | developing | SIG_GraphicsAndMedia | [@lz-230](https://gitee.com/lz-230)                 |
| 4    | [I3NJV2](https://gitee.com/openharmony/graphic_utils/issues/I3NJV2) | 【图形子系统】图形子系统提供系统级的BufferQueue IPC适配      | developing | SIG_GraphicsAndMedia | [@lz-230](https://gitee.com/lz-230)                 |
| 5    | [I3NMO8](https://gitee.com/openharmony/multimedia_utils_lite/issues/I3NMO8) | 【媒体子系统】支持音频数据输出                               | developing | SIG_GraphicsAndMedia | [@zhu-mingliang](https://gitee.com/zhu-mingliang)   |
| 6    | [I3NMP5](https://gitee.com/openharmony/multimedia_utils_lite/issues/I3NMP5) | 【媒体子系统】支持相机数据采集                               | developing | SIG_GraphicsAndMedia | [@zhu-mingliang](https://gitee.com/zhu-mingliang)   |
| 7    | [I3NMQ8](https://gitee.com/openharmony/multimedia_utils_lite/issues/I3NMQ8) | 【媒体子系统】支持音视频编解码，适配硬解插件                 | developing | SIG_GraphicsAndMedia | [@zhu-mingliang](https://gitee.com/zhu-mingliang)   |
| 8    | [I3NN1Z](https://gitee.com/openharmony/aafwk_aafwk_lite/issues/I3NN1Z) | 【应用程序框架】轻量级实现弹窗授权动态授权机制               | developing | SIG_AppFramework     | [@autumn](https://gitee.com/autumn330)              |
| 9    | [I3NN5Y](https://gitee.com/openharmony/hiviewdfx_hiview_lite/issues/I3NN5Y) | 【DFX子系统】【HiEvent】L1系统HiSysEvent功能                 | developing | SIG_BscSoftSrv       | [@shenchenkai](https://gitee.com/shenchenkai)       |
| 10   | [I3NN88](https://gitee.com/openharmony/hiviewdfx_hiview_lite/issues/I3NN88) | 【DFX子系统】【HiDumper】LiteOS_M系统信息dump工具            | developing | SIG_BscSoftSrv       | [@pcwlno1](https://gitee.com/pcwlno1)               |
| 11   | [I3NN9B](https://gitee.com/openharmony/hiviewdfx_hiview_lite/issues/I3NN9B) | 【DFX子系统】【BBoxDetector】LiteOS_M死机重启维测框架        | developing | SIG_BscSoftSrv       | [@pcwlno1](https://gitee.com/pcwlno1)               |
| 12   | [I3NN7V](https://gitee.com/openharmony/hiviewdfx_hiview_lite/issues/I3NN7V) | 【DFX子系统】【BBoxDetector】LiteOS_A死机重启维测框架        | developing | SIG_BscSoftSrv       | [@pcwlno1](https://gitee.com/pcwlno1)               |
| 13   | [I3NT3F](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT3F) | 【轻内核子系统】内核支持trace功能                            | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 14   | [I3NT63](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT63) | 【轻内核子系统】pagecache功能完善                            | developing | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 15   | [I3NTAZ](https://gitee.com/openharmony/security_huks/issues/I3NTAZ) | 【安全】轻量级实现弹窗授权动态授权机制                       | developing | SIG_Security         | [@scuteehuangjun](https://gitee.com/scuteehuangjun) |
| 16   | [I3NIN8](https://gitee.com/openharmony/communication_softbus_lite/issues/I3NIN8) | 【软总线】【RPC】支持RPC对象跨进程串行化                     | developing | SIG_SoftBus          | [@yinyouzhan](https://gitee.com/yinyouzhan)         |
| 17   | [I3O2G8](https://gitee.com/openharmony/aafwk_aafwk_lite/issues/I3O2G8?from=project-issue) | 【应用程序框架】轻量级应用实现entity标签                     | developing | SIG_AppFramework     | [@autumn](https://gitee.com/autumn330)              |

## OpenHarmony 3.1 beta1版本特性清单：

状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)

| no   | issue                                                        | feture description                                        | status     | sig                  | owner                                   |
| :--- | ------------------------------------------------------------ | :-------------------------------------------------------- | :--------- | :------------------- | :-------------------------------------- |
| 1    | [I3NJ69](https://gitee.com/openharmony/sensors_sensor_lite/issues/I3NJ69) | 【Sensor】霍尔传感器数据上报                              | developing | SIG_HardwareMng      | [@hhh2](https://gitee.com/hhh2)         |
| 2    | [I3NJ6P](https://gitee.com/openharmony/sensors_sensor_lite/issues/I3NJ6P) | 【Sensor】重力传感器数据上报                              | developing | SIG_HardwareMng      | [@hhh2](https://gitee.com/hhh2)         |
| 3    | [I3NJ76](https://gitee.com/openharmony/sensors_sensor_lite/issues/I3NJ76) | 【Sensor】磁力计传感器数据上报                            | developing | SIG_HardwareMng      | [@hhh2](https://gitee.com/hhh2)         |
| 4    | [I3NJ7J](https://gitee.com/openharmony/sensors_sensor_lite/issues/I3NJ7J) | 【Sensor】环境光传感器数据上报                            | developing | SIG_HardwareMng      | [@hhh2](https://gitee.com/hhh2)         |
| 5    | [I3NJ8H](https://gitee.com/openharmony/sensors_sensor_lite/issues/I3NJ8H) | 【Sensor】陀螺仪传感器数据上报                            | developing | SIG_HardwareMng      | [@hhh2](https://gitee.com/hhh2)         |
| 6    | [I3NJ96](https://gitee.com/openharmony/sensors_sensor_lite/issues/I3NJ96) | 【Sensor】加速度传感器数据上报                            | developing | SIG_HardwareMng      | [@hhh2](https://gitee.com/hhh2)         |
| 7    | [I3NTOO](https://gitee.com/openharmony/sensors_sensor_lite/issues/I3NTOO) | 【多模输入子系统】服务框架                                | developing | SIG_GraphicsAndMedia | [@zianed](https://gitee.com/zianed)     |
| 8    | [I3NTR7](https://gitee.com/openharmony/sensors_sensor_lite/issues/I3NTR7) | 【多模输入子系统】输入管理器                              | developing | SIG_GraphicsAndMedia | [@zianed](https://gitee.com/zianed)     |
| 9    | [I3NTS8](https://gitee.com/openharmony/sensors_sensor_lite/issues/I3NTS8) | 【多模输入子系统】窗口状态管理                            | developing | SIG_GraphicsAndMedia | [@zianed](https://gitee.com/zianed)     |
| 10   | [I3NTT2](https://gitee.com/openharmony/sensors_sensor_lite/issues/I3NTT2) | 【多模输入子系统】事件采集与分发                          | developing | SIG_GraphicsAndMedia | [@zianed](https://gitee.com/zianed)     |
| 11   | [I3NTUA](https://gitee.com/openharmony/sensors_sensor_lite/issues/I3NTUA) | 【多模输入子系统】多模事件分发到合适的窗口上              | developing | SIG_GraphicsAndMedia | [@zianed](https://gitee.com/zianed)     |
| 12   | [I3NTTQ](https://gitee.com/openharmony/sensors_sensor_lite/issues/I3NTTQ) | 【ACE子系统】支持JS多模能力                               | developing | SIG_AppFramework     | [@borne](https://gitee.com/borne)       |
| 13   | [I3NJAP](https://gitee.com/openharmony/graphic_utils/issues/I3NJAP) | 【图形子系统】图形构建统一南向接口，适配HDI adapter层接口 | developing | SIG_GraphicsAndMedia | [@lz-230](https://gitee.com/lz-230)     |
| 14   | [I3NJPD](https://gitee.com/openharmony/graphic_utils/issues/I3NJPD) | 【图形子系统】图形合成器适配HWC驱动                       | developing | SIG_GraphicsAndMedia | [@lz-230](https://gitee.com/lz-230)     |
| 15   | [I3NTDP](https://gitee.com/openharmony/communication_wifi_aware/issues/I3NTDP) | 【电话服务】支持轻量级mbed TLS协议栈                      | developing | SIG_SoftBus          | [@rain_myf](https://gitee.com/rain_myf) |
| 16   | [I3NTEK](https://gitee.com/openharmony/communication_wifi_aware/issues/I3NTEK) | 【电话服务】wifi服务支持STA模式                           | developing | SIG_SoftBus          | [@rain_myf](https://gitee.com/rain_myf) |
| 17   | [I3NTFH](https://gitee.com/openharmony/communication_wifi_aware/issues/I3NTFH) | 【电话服务】WIFI管理服务支持AP模式                        | developing | SIG_SoftBus          | [@rain_myf](https://gitee.com/rain_myf) |
| 18   | [I3NTG9](https://gitee.com/openharmony/communication_wifi_aware/issues/I3NTG9) | 【电话服务】WIFI服务支持LINUX内核                         | developing | SIG_SoftBus          | [@rain_myf](https://gitee.com/rain_myf) |

>  


###### 以上计划由OpenHarmony社区版本发布SIG组织发布
