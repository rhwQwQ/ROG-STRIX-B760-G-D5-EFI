# ROG-STRIX-B760-G-D5-黑苹果EFI
## 系统版本
* MacOS Sonoma 14.1.2

## Opencore版本
* 0.9.7

## 相关硬件

| 硬件       | 型号                           | 是否驱动 |
|----------|-------------------------------|---------|
| 主板      | ROG-STRIX-B760-G-D5小吹雪        | &#9745;   |
| CPU       | 13600kf                       | &#9745;   |
| 显卡      | rx6800                        | &#9745;   |
| 内存      | 阿斯加特女武神16G6000MHzx2      | &#9745;   |
| 硬盘      | 西数sn770 1TB                   | &#9745;   |
| 网卡      | AX211                         | &#9745;   |



## 已知问题：
* 蓝牙在Sonoma上没有成功驱动，可以打开开关但无法连接设备。

## 注意：安装之前需设置好相关BIOS，相关设置请查阅官方说明。
* SATA模式：将SATA模式设置为AHCI模式，以确保macOS能够正确地识别硬盘驱动器。

* 禁用Secure Boot：Secure Boot是一种电脑安全功能，但在黑苹果上可能会导致启动问题，因此需要禁用。

* 关闭VT-d（Virtualization Technology for Directed I/O）：在某些情况下，开启VT-d可能会导致系统不稳定或无法正常启动，因此建议关闭。

* 关闭CFG Lock：如果你的BIOS支持，可以尝试关闭CFG Lock。这有助于避免某些系统参数锁定而导致的问题。

* 关闭CSM（Compatibility Support Module）：CSM是一种兼容性支持模块，但在黑苹果上可能会导致启动问题，因此需要关闭。

* 启用XHCI Handoff：这可以确保USB 3.0设备在macOS上正常工作。

* 启用Intel Virtualization Technology：根据需要启用或禁用Intel虚拟化技术。

* 关闭Fast Boot：在某些情况下，开启Fast Boot可能会导致黑苹果无法正常启动，因此建议关闭。