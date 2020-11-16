# Lenovo yoga 710 i7-7500U BigSur OpenCore EFI

> 首先感谢 [https://github.com/HowieHye/Dell-7460-Hackintosh-OC](https://github.com/HowieHye/Dell-7460-Hackintosh-OC) , 本EFI基于该项目修改而成，该博主细心回答了我所有问题，非常感谢他！

**配置表：**

| 项目     | 版本     |
| -------- | -------- |
| OpenCore | 0.6.3    |
| CPU      | i7 7500U |
| 核显     | HD620    |

**驱动情况：**

| 项目                     | 是否完美                                   |
| ------------------------ | ------------------------------------------ |
| WiFi（Broadcom BCM43xx） | ✅                                          |
| 蓝牙                     | ✅                                          |
| 键盘                     | ✅                                          |
| 摄像头                   | ✅                                          |
| 触摸板                   | 不显示触控面板选项，不支持多指手势，待改进 |
| CPU睿频                  | ✅                                          |

**总结**

* 理论上，本EFI支持第七代CPU。
* 升级到Big Sur前务必要备份重要文件！极大概率出现无法启动的现象！
* Intel网卡请更换博通网卡，实现蓝牙wifi的完美兼容！
* kexts部分可能有一些多余的待删除，解决该问题需要一一删除调试，所导致的无法启动风险巨大！





