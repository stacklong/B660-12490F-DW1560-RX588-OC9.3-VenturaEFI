# B660-12490F-DW1560-RX588-OC9.3-VenturaEFI

#### 配置
CPU：i5-12490F
主板：华硕B660
显卡：蓝宝石RX588
网卡/蓝牙：BCM94352Z（DW1560）

#### 定制
1、CPU12代通用，如果CPU和我型号不一样可以修改\EFI\OC\config.plist 【revcpuname】改为你想显示的CPU型号；
2、网卡/蓝牙（DW1560/DW1830, BCM94360CS2, BCM94XXXX）都能用；
3、显卡免驱卡都能使用；
4、USB已按照华硕B660M-T-D4主板进行定制，主板不同可以删除\EFI\OC\Kexts\USBPorts.kext文件即可；
5、建议重新生成三码使用，不会可以跳过直接使用。

#### 主板设置
CPU电源管理 -> CFG锁定 -> 关闭
BOOT -> CSM -> Disabled
BOOT -> Secure Boot -> Other OS
BOOT -> Boot Configuration -> Fast Boot -> Disabled