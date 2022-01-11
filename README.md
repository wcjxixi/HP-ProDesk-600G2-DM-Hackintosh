HP ProDesk 600 G2 DM Hackintosh EFI（OpenCore），同时也支持 800 G2，并且[在 800 G2 下睡眠正常](https://github.com/wcjxixi/HP-ProDesk-600G2-DM-Hackintosh/issues/1)。

## 适用系统

macOS Big Sur 11.0.1（11.3.1 下若出现全部 USB 口不能使用请[参考](https://github.com/wcjxixi/HP-ProDesk-600G2-DM-Hackintosh/pull/3) ）

## OpenCore

0.6.3 正式版

## 我的机器配置

机型：[HP ProDesk 600 G2 DM](https://support.hp.com/cn-zh/product/hp-prodesk-600-g2-desktop-mini-pc/8376393/model/8376394/document/c04844247)

+ CPU：Intel Core i5-6600t @ 2.7GHz 4 核 4 线程
+ 内存：枭鲸 DDR4 2666Mhz 8GBx2
+ 显卡：集成 Intel® HD Graphics 530
+ 硬盘：海康威视 C2000Pro 512G 2280x
+ 声卡：板载 Realtek ALC221
+ LAN：板载 Intel I210-T1 千兆
+ WLAN：BCM943224PCIBT2+转接卡（最便宜的黑苹果 M.2 网卡，注意避坑：尽量不要买带 BX 后缀的。[BCM943224PCIBT2+转接卡介绍](https://youtu.be/ycKhGNuPM2M)）
+ 芯片组：Q150
+ BIOS：N22 02.51 Rev.A（2020-11-06）

HP ProDesk 600 G2 DM 这款机器大部分是锁蓝牙的，需要[解锁蓝牙](https://ppgg.in/blog/13060.html)

## 存在的问题

+ 睡眠后显示器无法唤醒，只能强制关机，目前无解。解决方法就是关闭睡眠（**系统偏好设置 → 节能**，设置为**永不关闭显示器**）（[在 800 G2 下睡眠正常](https://github.com/wcjxixi/HP-ProDesk-600G2-DM-Hackintosh/issues/1)）
+ 其他问题待发现

## 相关链接

+ [HP ProDesk 600 G2 DM 黑苹果教程](https://ppgg.in/blog/13067.html)
+ [HP ProDesk 600 G2 DM 解除蓝牙锁](https://ppgg.in/blog/13060.html)
