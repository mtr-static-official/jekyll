---
title: 安装黑苹果的过程与坑，还有后续
---

# MTR的黑苹果安装教程，坑，与结果

* *MTR已经安装过黑苹果了，但是他没有拍照。

## 你需要准备的材料

* 一台电脑

16 GB USB2.0 USB存储。
* 黑苹果镜像（自己去找，有的直接带EFI）

* 耐心

* 折腾劲

## 准备工作

### 资源准备

我这里**没有**准备资源。

需要的资源清单：

* TransMac

* 黑苹果镜像+EFI

针对您的型号的 EFI
### 安装准备

1. TransMac写入

2. 对照你的机型，替换EFI

## 开始安装

1. 将8-16GB的USB2.0 USB存储插入计算机

2.进入到BIOS，*重要*：**设定BIOS时间为11 月、07日、13时、21分、2015年、30秒，并将Clover设为第一启动项！！！我当初就卡在这一步！！！！！非常重要！！！！！**

3.选择“Install macOS XX”（XX为版本号）

* *由于MTR的电脑是Intel + NVDIA，所以MTR选择了安装10.13.6（High Sierra）

4.先不要着急安装，你先需要抹盘。选择磁盘工具，点击抹掉即可。

5.还是不要着急安装，因为目前Apple在High Sierra时代颁发的证书如今已经过期了，所以：

* 1.拔掉网线

* 2.实用工具-终端

* 3.输入 

```

date 110713212015.30

```

6.放心地安装吧

7.*MTR很幸运，镜像自带的配置就可以完美黑果了。

## 配置

安装好，经过多次跑条，我们终于轮到选地区了。

按照你的偏好选择。

如果你的显卡为AMD，你可以跳过。

如果你是N卡，那么你可能会感到卡顿。

安装WebDriver并在Clover配置文件里选择Inject NVDIA

重新启动，如果 Dock和 Finder透明
祝贺您，显卡驱动！
* *MTR的无线网卡、蓝牙也很幸运，全部免驱。声卡也免驱，网卡也免驱。

# 坑

* 1.如果你没设定BIOS时间为11 月、07日、13时、21分、2015年、30秒，并未将Clover设为第一启动项，macOS则会报错。安装将无法继续。

* 2.不 要 动 黑 苹 果 的 配 置 文 件 了 ！ ！ ！真 的 不 要！ ！ ！详 情 见 结 果 。

# 结果

这是个惨案。

* 1.我尝试在AppStore下载应用，失败。

* 2.打算更新下三码，于是安装某网站教程，删掉了一些配置文件，重启，无信号。

![1](https://tb2.bdstatic.com/tb/editor/images/face/i_f01.png)

![1](https://tb2.bdstatic.com/tb/editor/images/face/i_f01.png)

![1](https://tb2.bdstatic.com/tb/editor/images/face/i_f01.png)

![1](https://tb2.bdstatic.com/tb/editor/images/face/i_f01.png)

![1](https://tb2.bdstatic.com/tb/editor/images/face/i_f01.png)

* 3.RecoveryHD，无法进入，同无信号

* 4.删除显卡驱动 无效。

* 5.安装盘进不去。

* 6.换显卡，无效。

# 结束语

懒得写（）