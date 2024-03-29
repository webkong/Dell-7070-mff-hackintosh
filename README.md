# Dell-7070-mff-hackintosh

分享一下用了多年的黑苹果 EFI。从 Clover5137 引导的 MacOS10.15 的升级到 OC0.7.4 引导的 MacOS11.6。

后续不断更新。

戴尔 Micro Optiplex 7070 黑苹果 EFI，所有硬件均正常工作。网卡使用 itlwm 驱动，正常使用网络，无法使用 AirDrop。

## **硬件**

处理器：(英特尔)Intel(R) Core(TM) i7-9700T CPU @ 2.00GHz(1992 MHz)

芯片组：Intel Q370

内存：32GB 2666MHz DDR4 三星

显卡：Intel UHD Graphics 630

声卡：ALC255(内置扬声器+耳麦一体+音频输出)

网卡：Intel I219LM7

无线网卡：Intel 9560ac

硬盘 1：INTEL SSD PEKNW 512G 固态

## **正常工作**

1.变频 HWP

2.显卡、网卡、声卡、无线网卡、蓝牙

3.USB 已定制

4.睡眠(电源键菜单+电源键唤醒+键盘唤醒+鼠标唤醒+蓝牙唤醒+网卡唤醒)

## 注意

OTA 升级前，必须先升级 kexts。使用 OCC 进行升级就可以。或者替换新的 EFI 再升级。

## 更新记录

### 2024-03-23

1. MacOS OTA 升级为 14.4.0 从 14.0.0 升级
2. 更新 AppleALC.kext
3. OC 升级 0.9.9

### 2023-10-10

1. MacOS OTA 升级为 14.0.0 从 13.5.2 升级
2. 更新了蓝牙内核 IntelBluetooth-v2.3.0
3. 更新了 BlueToolFixup.kext

### 2023-10-09

1. MacOS OTA 升级为 13.5.2 从 13.2.1 升级
2. 部分内核升级
3. OC 升级 0.9.5

### 2023-02-26

1. MacOS OTA 升级为 13.2.1 从 13.0.1 升级
2. 部分内核升级

### 2023-02-19

1. MacOS OTA 升级为 13.0.1 从 13.0.0 升级
2. OC 升级 0.8.8
3. kexts 升级（大量内核升级）

### 2022-07-21

1. MacOS OTA 升级为 12.5
2. OC 升级 0.8.2
3. kexts 升级

### 2022-05-19

1. MacOS OTA 升级为 12.4
2. AppleALC.kext 升级为 1.7.1
3. OC 升级为 0.8.0

### 2022-04-02

1. MacOS OTA 升级为 12.3.1
2. 升级音频驱动，配置 Layout id 为 66 ，所有音频设备均正常。
3. 升级 itlwm 网卡驱动

### 2022-03-15

1. 升级 OC 的版本为 0.7.9
2. MacOS OTA 升级为 12.3
3. 添加一个自己喜欢的主题，不需要可自行移除

### 2022-02-18

1. 修改 OC 的版本为 0.7.8
2. MacOS OTA 升级为 12.2.1
3. 将 ALC255 的 Layout id 改为 15 耳机和外放都好用。

### 2022-02-08

1. 升级 OC 为 0.7.7 MacOS 12.2

### 2022-01

1. 支持 MacOS12.0.1
2. 升级 OC 为 0.7.5
3. 添加蓝牙 BlueToolFixup.kext 内核
