# k3_official_firmware

提取自官方最新固件V24.1.1.206

## 屏幕

使用CCluv制作特别版k3screenctrl程序升级屏幕固件，命令为k3screenctrl -u app.xxxx.bin(hex)

## 无线

已经从官方dhd.ko里提取完成（brcmfmac4366c-pcie.bin），但是这并不意味着openwrt可以直接替换使用。

brcmfmac4366c-pcie.bin_dhd 为RT-AC88U（3.0.0.4.386.43129 2021/05/18）版本固件最新无线固件，支持160Mhz

## 完整原版固件

SW_K3_703005003_V24.1.1.206.bin
