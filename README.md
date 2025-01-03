# My-hackintool-Opencore

> **用前须知：**
> 笔记本型号：神舟z7-kp7sc
> N卡独显：只能在clover/macOS10.13.6驱动。
> Platform参数：默认是错的，请自行生成！！！！
> 引导主题文件：个人自制主题，请自行修改。

![](/1.png)

## opencore

OC版本：1.0.2

适用版本：macOS10.14-14.7

功能完善：基本正常
- 核显 IntelUHD630 (正常)
- WiFi 蓝牙 声卡 摄像头 睡眠 USB/Type-C (正常)
- 系统 可正常系统更新，15.0以上未知 (正常)
- 电源 插电(正常)，单独电池使用会死机
- 独显Nvdia 1060（无解），可用：OCLP，BigSur和Monterey，不支持 Metal
- 外接显示器 HDMI DP（无解），可用：Dell D6000+DisplayLink Manager解决

## clover

适用版本：macOS10.13.6

功能完善：完美黑苹果
- 核显Intel UHD630(正常)
- WiFi 蓝牙 声卡 摄像头 睡眠 电池(正常)
- Nvdia独显1060（正常），需要安装WebDriver-387.10.10.10.40.139.pkg
- HDMI，USB/Type-C（正常）