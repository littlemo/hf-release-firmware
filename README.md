hf-release-firmware
===================

汉枫WiFi模块的量产版本固件

## 文件说明

1. **General**: 通用型量产版本固件
2. **HTTPS**: HTTPS量产版本固件，即删除了原有的SocketA，SocketB，谨将UART数据透传到HTTPS输出到网络
3. **SPI**: SPI量产版本固件，即将原有UART的数据通道改为SPI接口，从而保证3M左右的传输速度