[![RU](https://img.shields.io/badge/RU-lightgrey?style=for-the-badge)](README.md)
[![EN](https://img.shields.io/badge/EN-blue?style=for-the-badge)](README.en.md)
[![BE](https://img.shields.io/badge/BE-red?style=for-the-badge)](README.be.md)
[![ZH](https://img.shields.io/badge/中文-yellow?style=for-the-badge)](README.zh.md)
[![UK](https://img.shields.io/badge/UK-gold?style=for-the-badge)](README.uk.md)

# TP-Link TL-MR3020 — 固件与安装说明

本仓库包含 **TP-Link TL-MR3020** 便携路由器的固件文件和详细的刷机说明。

## 内容

- 📦 **固件文件**（`.bin`）— 可通过路由器网页界面安装，或通过 TFTP 恢复使用的成品镜像
- 📖 **安装说明** — 逐步刷机指南
- 🔧 刷机失败后的恢复说明（TFTP 恢复方式）

## 快速开始

1. 确认您路由器的硬件版本（标注在设备底部的标签上）
2. 从本仓库下载对应的固件文件
3. 按照说明通过网页界面（`系统工具 → 软件升级`）安装,若路由器无法启动，则通过 TFTP 恢复方式安装

## TFTP 恢复（路由器变砖时）

简要步骤：在给设备通电时按住 RESET/WPS 按钮，运行 TFTP 服务器并将固件文件放在根目录下，等待传输完成——路由器会自动加载该镜像。

## 警告

⚠️ 刷机风险自负。错误的固件或刷机过程中断电可能导致设备无法使用。

视频说明:
https://youtu.be/I5PSXwQ-GoA
https://rutube.ru/video/private/aa385e46797a7de9f1f5cfa6f6f4784f/?p=dYtD3NQnxpJyHjc8QRHLuQ
https://vkvideo.ru/video-240166090_456239072?list=4vdv2ra6ysfiycei
