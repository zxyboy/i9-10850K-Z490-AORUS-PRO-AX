# i9-10850K-Z490-AORUS-PRO-AX
黑苹果PC台式机EFI： I9-10850K +  Z490 AORUS PRO AX 

# PC机器配置
- 主板： [Z490 AORUS PRO AX](https://item.jd.com/100012824420.html)
- CPU：  [i9-10850K](https://item.jd.com/100008072593.html)
- 显卡： [蓝宝石（Sapphire）RX 5600 XT 6G D6 白金版PRO](https://item.jd.com/100007967097.html)
- 内存： [金士顿(Kingston) DDR4 3200 32G(16GX2)套装 -买2套（64G）](https://item.jd.com/100007628368.html)
- 固态硬盘：[三星（SAMSUNG）500GB SSD固态硬盘 M.2接口(NVMe协议PCIe 4.0 x4) 980 PRO （MZ-V8P500BW）](https://item.jd.com/100008757399.html)
- 机械硬盘：[希捷(Seagate)2TB 256MB 7200RPM 台式机机械硬盘 SATA接口 希捷酷鱼BarraCuda系列(ST2000DM008)](https://item.jd.com/6856662.html)
- 有线网卡：主板板载2.5G有线网卡
- 无线网卡和蓝牙：[奋威T919双频5GWiFi接收器适用黑苹果免驱BCM94360CD台式机pcie无线网卡蓝牙4.0 FV-T919(1750M黑苹果免驱版）](https://item.jd.com/18967921252.html#none)
  说明：主板自带的WiFi6无线网卡，不支持黑苹果。
- 声卡：主板板载声卡
- 电源：[长城（Great Wall）额定700W V7金牌全模组电源（单路12V/全电压/DC-DC/固态电容/双CPU线+双显卡口）](https://item.jd.com/100010194560.html)
- CPU扇热器：[酷冷至尊( CoolerMaster )冰神B360 ARGB水冷散热器(I9 2066、AM4/ARGB灯珠/双腔水泵/低阻冷排)](https://item.jd.com/100011674030.html)
- 机箱：[酷冷至尊(CoolerMaster)MB520(旋风520）台式电脑中塔机箱(ATX主板/前镜面板/玻璃侧板/独立电源仓)](https://item.jd.com/100000154107.html)
- 键盘：[ikbc W200 机械键盘 2.4G无线 游戏键盘 87键 cherry轴 樱桃轴 无线机械键盘 黑色 红轴](https://item.jd.com/100006367830.html)
- 鼠标：[Apple Magic Mouse/妙控鼠标 2代 - 银色 适用MacBook 无线鼠标](https://item.jd.com/2187061.html)
# OpenCore 0.63引导
- 机型：iMac20,2
- 系统：Big Sur 11.01 

# 黑苹果那些功能能够使用
- 有线网卡
- 无线网卡
- 蓝牙（外置音箱、无线蓝牙鼠标、隔空传送等）
- 声卡(耳机)
- 独显（核显没有测试）
- 休眠（休眠以后，需要按下开机键，才能唤醒）
- USB3.2/3.1/2.0
- 键盘
- 鼠标
# 黑苹果那些功能不能使用
- 无

# 怎么使用？
- 下载EFI文件
- 修改3码，具体参考: 这里(https://dortania.github.io/OpenCore-Install-Guide/config.plist/comet-lake.html#platforminfo)
- bios中一定要禁用：CFG Lock 这个选项，否则可能不能启动
- 将EFI拷贝到你U盘启动的EFI分区，启动安装系统
- 安装完成，将U盘中的EFI文件夹拷贝到你硬盘的EFI分区去中，大功告成！

# 特别感谢
- [shagua517/Gigabyte-Z490-AORUS-Pro-AX-10900k-5700xt-OpenCore](https://github.com/shagua517/Gigabyte-Z490-AORUS-Pro-AX-10900k-5700xt-OpenCore)
- [OpenCore网站指导](https://dortania.github.io/OpenCore-Install-Guide/)
- [SchmockLord/Hackintosh-Intel-i9-10900k-Gigabyte-Z490-Vision-D)](https://github.com/SchmockLord/Hackintosh-Intel-i9-10900k-Gigabyte-Z490-Vision-D)
- [tonymacx86](https://www.tonymacx86.com/threads/success-asus-rog-strix-z490-e-gaming-i9-10900k-opencore.299137/)

# 一些截图

## 系统信息
![系统信息](https://github.com/zxyboy/i9-10850K-Z490-AORUS-PRO-AX/blob/main/images/system-overview.png)
![系统信息](https://github.com/zxyboy/i9-10850K-Z490-AORUS-PRO-AX/blob/main/images/system.png)

## 存储信息
![存储信息](https://github.com/zxyboy/i9-10850K-Z490-AORUS-PRO-AX/blob/main/images/disk.png)
![存储信息](https://github.com/zxyboy/i9-10850K-Z490-AORUS-PRO-AX/blob/main/images/storage.png)
## 内存信息
![内存信息](https://github.com/zxyboy/i9-10850K-Z490-AORUS-PRO-AX/blob/main/images/memory.png)
![内存信息](https://github.com/zxyboy/i9-10850K-Z490-AORUS-PRO-AX/blob/main/images/meory-detail.png)
## 有线网卡信息
![网卡信息](https://github.com/zxyboy/i9-10850K-Z490-AORUS-PRO-AX/blob/main/images/network-ui.png)
![网卡信息](https://github.com/zxyboy/i9-10850K-Z490-AORUS-PRO-AX/blob/main/images/Network.png)
![网卡信息](https://github.com/zxyboy/i9-10850K-Z490-AORUS-PRO-AX/blob/main/images/ethernet.png)
## 无线网卡信息
![无线网卡信息](https://github.com/zxyboy/i9-10850K-Z490-AORUS-PRO-AX/blob/main/images/Wifi.png)
## 声卡信息
![声卡信息](https://github.com/zxyboy/i9-10850K-Z490-AORUS-PRO-AX/blob/main/images/audio.png)
## 显卡信息
![显卡信息](https://github.com/zxyboy/i9-10850K-Z490-AORUS-PRO-AX/blob/main/images/graphics.png)
## USB信息
![USB信息](https://github.com/zxyboy/i9-10850K-Z490-AORUS-PRO-AX/blob/main/images/USB.png)
## NVMe固态信息
![固态](https://github.com/zxyboy/i9-10850K-Z490-AORUS-PRO-AX/blob/main/images/ssd.png)
## 蓝牙信息
![蓝牙](https://github.com/zxyboy/i9-10850K-Z490-AORUS-PRO-AX/blob/main/images/bluetooth-ui.png)
![蓝牙](https://github.com/zxyboy/i9-10850K-Z490-AORUS-PRO-AX/blob/main/images/Bluetooth.png)















