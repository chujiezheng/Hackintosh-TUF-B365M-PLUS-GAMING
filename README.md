# Hackintosh-TUF-B365M-PLUS-GAMING
## 硬件配置

- 主板：ASUS-TUF-B365M-PLUS-GAMING
- CPU：i7-9700
- GPU：GT630 (DDR5, Kepler)
- 蓝牙网卡：BCM94360CD
- 机箱：机械大师C26（前置2个USB3.0接口）

## 安装流程

1. 制作带引导的macOS系统启动盘，系统安装文件可以从[黑果小兵](https://blog.daliansky.net/)下载
2. 将本仓库下的EFI复制到启动盘对应分区，**并自行替换三码**
   - 注：如果发现本仓库的EFI无法引导安装，可采用黑果小兵提供的默认EFI
3. 设置BIOS（参照[建议设置](https://blog.daliansky.net/macOS-Monterey-12.1-21C52-Release-version-with-OC-0.7.6-CLOVER-5143-and-FirPE-original-image.html)），并按照[这个教程](https://blog.daliansky.net/MacOS-installation-tutorial-XiaoMi-Pro-installation-process-records.html)安装

