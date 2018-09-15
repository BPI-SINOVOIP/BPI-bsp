# BPI-bsp

## Getting Started

1. Choose a board doing:
-   For BananaPI-M1: `./configure BananaPi_M1`
-   For BananaPI-M1-Plus: `./configure BananaPi_M1_Plus`.

2. Run `make` to build hwpack or `make help` to list available targets

## Overview

This repository provides various scripts to help hacking devices with Allwinner SOC.

| script | description |
| --- | --- |
| `./scripts/a1x-initramfs.sh` | Create initramfs inside target device |
| `./scripts/mk_ext4_rootfs.sh` | Ext4 rootfs from tar.gz |
| `./scripts/mk_hwpack.sh ` | Helper script for Makefile |
| `./scripts/mk_livesuit_img.sh` | Android or Linux livesuit image |
| `./scripts/sunxi-media-create.sh` | Flash SD card from hwpack |
| `./scripts/mk_android.sh` | Helper script for Makefile |
