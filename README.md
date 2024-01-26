# ROG-STRIX-B760-G-D5-黑苹果EFI
## 系统版本
* MacOS Sonoma 14.2.1

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

![WeChatbe4e21f74e65c4ec898e4bcc90e551bc](https://github.com/rhwQwQ/ROG-STRIX-B760-G-D5-EFI/assets/14314953/3df7b366-503d-430a-9a64-dc1d2942e951)
![2127679419](https://github.com/rhwQwQ/ROG-STRIX-B760-G-D5-EFI/assets/14314953/c6cb761f-49b2-4af4-abe6-845d637e8bda)
![1282294418](https://github.com/rhwQwQ/ROG-STRIX-B760-G-D5-EFI/assets/14314953/8a7d23ef-2027-4280-9f12-1fac1dc733a7)
![431427723](https://github.com/rhwQwQ/ROG-STRIX-B760-G-D5-EFI/assets/14314953/7f0a7e69-137c-4a50-adee-943845c37867)
![3305690265](https://github.com/rhwQwQ/ROG-STRIX-B760-G-D5-EFI/assets/14314953/de1e5806-50e3-4e31-8785-61db44b6ff5f)




## 已知问题：
* 蓝牙在Sonoma上没有成功驱动，可以打开开关但无法连接设备。

## BIOS设置 

重要：

| 项                                | 选择 | 备注                                  |
| --------------------------------- | --------- | ------------------------------------- |
| Fast Boot                         | 禁用      |                                       |
| VT-d                              | 禁用      | 安装系统后启用此项，以启用 *AppleVTD* |
| CSM                               | 禁用      |                                       |
| CFG Lock                          | 禁用      |                                       |
| Secure Boot                       | 禁用      |                                       |
| Serial/COM Port                   | 禁用      |                                       |
| Resizable BAR Support             | 禁用      | *64bit Bar2* 缺失                     |
| VT-x                              | 启用      |                                       |
| UEFI startup mode                 | 启用      |                                       |
| Hard disk mode                    | *AHCI*   |                                       |
| Above 4G decoding                 | 启用      |                                       |
| Hyper-Threading                   | 启用      |                                       |
| EHCI/XHCI Hand-off                | 启用      |                                       |
| DVMT Pre-Allocated(iGPU Memory)   | 64MB and above |                                 |

其他

| 项                        | 启用/禁用 | 备注                            |
| ------------------------- | --------- | ------------------------------- |
| Thunderbolt               | 禁用      |                                 |
| Intel SGX                 | 禁用      |                                 |
| Intel Platform Trust(TPM) | 禁用      |                                 |
| Parallel Port             | 禁用      |                                 |
| iGPU                      | 禁用      | 会出现 *Reserved Memory Region* |
| Execute Disable Bit       | 启用          |                                 |
| Legacy RTC Device         | 启用          |                                 |
