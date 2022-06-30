# 使用STM32播放数码宝贝视频。
## 简介
通过串口，电脑发送视频数据给单片机，然后单片机在0.96寸OLED显示屏上显示视频画面。

效果见链接：https://www.bilibili.com/video/BV1e94y1278H?share_source=copy_web

播放原理见链接：https://www.bilibili.com/video/BV1N34y1Y7SH?share_source=copy_web

## 使用说明
本代码使用STM32CubeIDE(1.9.0版本)创建。
IO口的连接关系直接看代码。

单片机上电后，运行python程序，OLED显示屏就会开始播放视频(注意设置正确的端口号，也需要安装串口库pyserial)


