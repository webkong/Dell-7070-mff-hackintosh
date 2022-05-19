# Dell-7070-mff-hackintosh

分享一下用了 1 年多的黑苹果 EFI。从 Clover5137 引导的 MacOS10.15 的升级到 OC0.7.4 引导的 MacOS11.6。

戴尔 Micro Optiplex 7070 黑苹果 EFI，所有硬件均正常工作。网卡使用 itlwm 驱动，正常使用网络，无法 AirDrop。

**硬件**

处理器：(英特尔)Intel(R) Core(TM) i7-9700T CPU @ 2.00GHz(1992 MHz)

芯片组：Intel Q370

内存：32GB 2666MHz DDR4 三星

显卡：Intel UHD Graphics 630

声卡：ALC255(内置扬声器+耳麦一体+音频输出)

网卡：Intel I219LM7

无线网卡：Intel 9560ac

硬盘 1：INTEL SSD PEKNW 512G 固态

**正常工作**

1.变频 HWP

2.显卡、网卡、声卡、无线网卡、蓝牙

3.USB 已定制

4.睡眠(电源键菜单+电源键唤醒+键盘唤醒+鼠标唤醒+蓝牙唤醒+网卡唤醒)

随时更新

## 更新记录

1. 支持 MacOS12.0.1
2. 升级 OC 为 0.7.5
3. 添加蓝牙 BlueToolFixup.kext 内核

### 2022-02-08

1. 升级 OC 为 0.7.7 MacOS 12.2

### 2022-02-18

1. 修改 OC 的版本为 0.7.8
2. MacOS OTA 升级为 12.2.1
3. 将 ALC255 的 Layout id 改为 15 耳机和外放都好用。

### 2022-03-15

1. 升级OC 的版本为0.7.9
2. MacOS OTA升级为12.3
3. 添加一个自己喜欢的主题，不需要可自行移除

### 2022-04-02

1. MacOS OTA升级为12.3.1
2. 升级音频驱动，配置Layout id为 66 ，所有音频设备均正常。
3. 升级itlwm网卡驱动

### 2022-05-13

1. MacOS OTA升级为12.4
2. AppleALC.kext升级为1.7.1
3. OC升级为0.8.0
