# ORIGIN-GEN1

你好呀，这是模块化键盘ORIGIN-GEN1的简介页。

如果需要这个项目的源代码，原理图或上位机软件，可以单击下面的标签跳转。

[![ORIGIN GEN1 FIRMWARE](./README.assets/FirmwareLabel.svg)](https://github.com/Challenger-0/ORIGIN-GEN1-KeyboardFirmware) 键盘固件

[![ORIGIN GEN1 PCB](./README.assets/PCBLabel.svg)](https://github.com/Challenger-0/ORIGIN-GEN1-PCB)原理图

[![UNDEFINE HUB](./README.assets/SoftwareLabel.svg)](https://github.com/Challenger-0/ORIGIN-GEN1-KeyboardFirmware)上位机



## 简介

ORIGIN-GEN1 是一个以模块化思想主导设计的键盘，除键盘本体外，还可以通过外接模块的方式扩展各种各样的功能（例如小键盘，转盘、电池，性能监视屏幕等），旨在把设计的权力交还给用户。

键盘以ESP32-S3为主控，可以通过一个全速USB接口和低功耗蓝牙与计算机连接。得益于ESP32-S3较高的性能和较大的 Flash 与 ROM，模块可以利用其进行性能消耗较大的运算（如绘图等），而无需在模块内置高性能的主控。

模块与键盘之间通过一个标准SPI接口通讯，其时钟频率最高可达80MHz，可以实现较高速率的通信。（若传输屏幕数据，可以使用增量更新的方式，刷新更改过后的部分，以提升屏幕刷新率）

键盘固件使用Arduino环境进行开发，有一定C/Cpp基础者可轻松上手编写设计自己的键盘固件和模块。

## 投喂作者(捐赠) / 购买成品

这是一个开源项目，身为作者的我无法从中获取任何收益，但我确实为这个项目投入了很多。如果这个项目确实对你有所帮助或启发，那么就可以通过下方的二维码向我投喂。

如果需要键盘成品，也可以通过下方链接购买，同时我也可以从中获取一些利润。

**无论如何，感谢您支持开源硬件！**

- **二维码捐赠**

  所有的捐赠都可以在7天之内联系作者原路退回（手续费除外）。
   <div>
  <img src="./README.assets/1676903631547.jpg" height="300px" alt="alipay" >
  <img src="./README.assets/image-20230220223642646.png" height="300px" alt="wechatpay" >
  </div>

- **购买成品**

  若通过上方链接购买，我可以从中获取一点点的利润，感谢支持开源硬件！

  同时，若三个月内出现非人为因素的硬件故障，可以联系作者远程指导修复。若无法远程修复，可以享受一次免费维修服务，只需承担去程快递费用。
