[![RU](https://img.shields.io/badge/RU-lightgrey?style=for-the-badge)](README.md)
[![EN](https://img.shields.io/badge/EN-blue?style=for-the-badge)](README.en.md)
[![BE](https://img.shields.io/badge/BE-red?style=for-the-badge)](README.be.md)
[![ZH](https://img.shields.io/badge/中文-yellow?style=for-the-badge)](README.zh.md)
[![UK](https://img.shields.io/badge/UK-gold?style=for-the-badge)](README.uk.md)

# TP-Link TL-MR3020 — Firmware and Installation Guide

This repository contains firmware files and a step-by-step guide for reflashing the **TP-Link TL-MR3020** pocket router.

## Contents

- 📦 **Firmware files** (`.bin`) — ready-to-use images for installation via the router's web interface or recovery via TFTP
- 📖 **Installation guide** — step-by-step instructions for flashing the device
- 🔧 Notes on recovering from a failed flash (TFTP recovery)

## Quick Start

1. Identify your router's hardware version (printed on the label on the bottom of the device)
2. Download the matching firmware file from this repository
3. Follow the guide to install it via the web interface (`System Tools → Firmware Upgrade`) or via TFTP recovery if the router doesn't boot

## TFTP Recovery (if the router is "bricked")

In short: hold the RESET/WPS button while powering on the device, run a TFTP server with the firmware file in its root folder, and wait for the transfer to complete — the router will load the image automatically.

## Warning

⚠️ Flashing is done at your own risk. An incorrect firmware or a power loss during the process may render the device inoperable.

Video instructions:
https://youtu.be/I5PSXwQ-GoA
https://rutube.ru/video/private/aa385e46797a7de9f1f5cfa6f6f4784f/?p=dYtD3NQnxpJyHjc8QRHLuQ
https://vkvideo.ru/video-240166090_456239072?list=4vdv2ra6ysfiycei
