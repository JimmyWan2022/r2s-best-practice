# r2s-openwrt 固件安装教程（时长10分钟）

### 网速效果图
100M的小水管，差不多跑满网速

![image](https://github.com/JimmyWan2022/r2s-best-practice/blob/master/%E6%97%81%E8%B7%AF%E7%94%B1%20%E6%9C%80%E4%BD%B3%E5%AE%9E%E8%B7%B5.assets/%E7%BD%91%E9%80%9F.jpg)


固件下载地址，推荐骷髅头,插件齐全,如Passwall Hello World

https://github.com/DHDAXCW/NanoPi-R2S-rk3328/releases/tag/2023.02.14-Lean1

![image](https://user-images.githubusercontent.com/113830395/219377381-2301f962-a87b-413d-8733-eabacc4579e0.png)
## 刷机教程5步
刷机工具：https://www.balena.io/etcher#download-etcher

1.采购硬件，R2S+内存卡（读卡器），推荐CNC加工金属外壳的R2S

2.[下载固件1](https://github.com/anaelorlinski/OpenWrt-NanoPi-R2S-R4S-Builds)，[下载固件2](https://github.com/QiuSimons/YAOF) 用读卡器连接PC，写入固件（个人推荐下载带docker版本）

*推荐：Docker-friendlyarm_nanopi-r2s-squashfs-sysupgrade.img.gz*

3.LAN口连接PC，后台地址：192.168.11.1，用户名root 密码 password

4.在passwall中添加节点

5.完成
## 图--NC加工金属外壳的R2S
![NanoPi R2S Mini Router RK3328 Dual Gigabit Ethernet Ports For OpenWrt5.4  2023 | eBay](https://i.ebayimg.com/images/g/N4QAAOSwxstgUbAe/s-l500.jpg)


## 其他教程
[旁路由最佳实践](https://github.com/JimmyWan2022/r2s-best-practice/blob/master/%E6%97%81%E8%B7%AF%E7%94%B1%20%E6%9C%80%E4%BD%B3%E5%AE%9E%E8%B7%B5.md)

树莓派+openwrt：https://doc.openwrt.cc/2-OpenWrt-Rpi/1-Download/
