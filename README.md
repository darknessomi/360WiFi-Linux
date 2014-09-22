360WiFi-Linux
===================
360随身WiFi 2代 小米随身WiFi 小度随身WiFi Linux通用版

360随身WiFi 2代 小米随身WiFi 小度随身WiFi kali Linux特别版

一定支持：360随身WiFi 2代 、360随身WiFiU盘版、小米随身WiFi、小度随身WiFi等基本所有采用MT7601U芯片的网卡  

可能支持：采用Ralink 6570、MT7650、Ralink 6370等芯片的一些基于Ralink RT2870开发而来的网卡

测试平台:
 
```
kali-linux-1.0.9-amd64   		 
CentOS-7.0-x86_64
```

## 使用方法

### 下载

通用版

```
http://sdut-zrt.qiniudn.com/DPO_MT7601U_LinuxSTA_3.0.0.4_20130913_360wifi2.zip
```
kali版

```
http://sdut-zrt.qiniudn.com/DPO_MT7601U_LinuxSTA_3.0.0.4_20130913_360Wifi2_Kali.zip
```

### 安装

解压之后进入目录

```
sudo make
sudo make install
sudo modprobe rt2x00usb
```
### enjoy wifi!

![](http://sdut-zrt.qiniudn.com/E62870D7-3FB5-4065-8FAC-E926A11070F8.png)
