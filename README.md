# T113-i Linux BSP Development

基于创龙 TLT113-MiniEVM 开发板的 Linux BSP 与驱动开发项目。

## Hardware

- SoC: Allwinner T113-i
- Board: Tronlong TLT113-MiniEVM
- Storage: eMMC
- SDK: Tina 5.0
- Kernel: Linux 5.4

## Project Structure

- drivers/: 自定义 Linux 驱动
- apps/: 用户态测试程序
- patches/: 厂商 SDK 修改补丁
- scripts/: 编译和测试脚本
- docs/: 开发记录和技术文档

## Development Goals

1. Linux 启动流程分析
2. Device Tree 与 Platform Driver
3. GPIO 与中断驱动
4. SPI 外设驱动
5. 网络与工业通信开发

## Note

本仓库不包含完整的厂商 SDK。
