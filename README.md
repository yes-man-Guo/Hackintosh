华擎Z270 SLI
装机清单
名称	品牌型号	备注
中央处理器	英特尔i7 9700k	
主板	华擎Z390 Phantom Gaming itx / ac	
散热器	九州风神船长240 EX白色RGB	
内存	海盗船Vengeance LPX DDR4 3000 16G x 1	
SSD	三星970 EVO 250G	
机箱	追风者215P ITX侧透RGB	
电源	讯景XTR550	
显卡	蓝宝石RX580 8G 1411MHz Nitro +超白金	矿卡
无线网卡/蓝牙	博通BCM94360CS2	需转接卡替换主板原有模块M.2 Key E口
显示器	LG 27UL600 4k HDR400 IPS	DisplayPort接入
更多说明请看攒了一台4K视频剪辑黑苹果。

兼容情况
完美
 macOS版本
 10.14.3
 10.14.5
 显卡（DisplayPort接显示器）
 Intel UHD630核显
 AMD RX580
 声卡（Realtek ALC1220）
 主板后置
 机箱前置
 DisplayPort声音输出
 睡眠/唤醒
 有线网卡
 无线WiFi
 蓝牙
 耳机
 触控板2
 空投
 不可触摸
 所有USB插口
无法使用
雷电3口（type-c接口）
EFI
幸运草r4930
ACPI
修补
SSDT-UIAC-ALL.aml
drivers64UEFI
ApfsDriverLoader-64.efi
AptioMemoryFix-64.efi
EmuVariableUefi-64.efi
FSInject-64.efi
kext文件
启动必备
FakeSMC.kext
Lilu.kext
WhateverGreen.kext
显卡
NoVPAJpeg.kext（解决AMD独立显卡无法预览和打开JPG图片，macOS 10.14.5之后AMD支持HEVC可不用）
声卡
AppleALC.kext
有线网卡
IntelMausiEthernet.kext
无线网卡
AirportBrcmFixup.kext
蓝牙（配合Kext Utility / KextBeast安装到系统）
BrcmFirmwareRepo.kext
BrcmPatchRAM2.kext
安装教程
前期准备
开机F2进入BIOS再按F6切换高级模式，至少需要做如下修改具体情况还需要看硬件情况：

高级（高级）>芯片配置（芯片组配置）> VT-d - >禁用
高级（高级）> USB配置（USB配置）> XHCI切换 - >启用
安装黑苹果
请移步至华擎Z390 Gaming ITX黑苹果安装教程

相同主板EFI
