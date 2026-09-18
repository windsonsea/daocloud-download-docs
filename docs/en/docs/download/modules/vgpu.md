---
MTPE: windsonsea
hide:
  - navigation
---

# AI & Video Acceleration Card Driver Downloads

Authorized Organization: DaoCloud

This page lists the drivers of each version of the acceleration card for users to download.

## 2024-05

### k8s_v0.0.4-1

!!! note "Release Notes 20240530"

    K8s Docker supports the multi-card DC1000 environment

| Board Type | Software Type | OS | Architecture | Size | Download | md5 | Release Time |
| :-----: | :-----: | :-----: | :----: | :-----: | :--: | :----: | :-----: |
| SG100 | Driver | Linux | arm | 72.24 MB | [:arrow_down: v0.0.4-1.tar.gz](https://harbor-test2.cn-sh2.ufileos.com/docs/drivers/v0.0.4-1.tar.gz) | f96b90e0629b91451086fef82336cd61 | **2024-05-30** 10:58:11 |

### tools_3.0.1-20240430-vaqual_sg-aarch64-mfg

!!! note "Release Notes 20240529"

    This version is for factory testing only.

    - The test tool depends on the PCIe driver of the board. For driver installation, refer to sections 2.3 DKMS and 2.4 PCIe Driver Installation in the test guide.
    - For board stress testing and power consumption testing, refer to section 3.2.13 Power Consumption Test in the test guide. (This version does not depend on the GPU DDK driver, so skip steps 1-3 during testing.)
    - For board video memory testing, refer to section 3.2.10 DDR Bandwidth Test in the test guide.

| Board Type | Software Type | OS | Architecture | Size | Download | md5 | Release Time |
| :-----: | :-----: | :-----: | :----: | :-----: | :--: | :----: | :-----: |
| VG1000 | Driver | Linux | arm | 5.63 MB| [:arrow_down: va-pci-mainline-hwtype-0_00.24.01.15_aarch64.rpm](https://harbor-test2.cn-sh2.ufileos.com/docs/drivers/va-pci-mainline-hwtype-0_00.24.01.15_aarch64.rpm) | 3088c42bc2fd79b77ecc6f59e706a560 | **2024-05-29** 12:25:42 |
| VG1000 | Driver | Linux | arm | 4.52 MB | [:arrow_down: va-pci-mainline-hwtype-0_00.24.01.15_aarch64.deb](https://harbor-test2.cn-sh2.ufileos.com/docs/drivers/va-pci-mainline-hwtype-0_00.24.01.15_aarch64.deb) | 331399104cd5df7de02a1c3ee51e5a9c | **2024-05-29** 12:25:42 |
| VG1000 | Driver | Linux | arm | 269.62 MB | [:arrow_down: tools_3.0.1-20240430-vaqual_sg-aarch64-mfg.tar.gz](https://harbor-test2.cn-sh2.ufileos.com/docs/drivers/tools_3.0.1-20240430-vaqual_sg-aarch64-mfg.tar.gz) | ea44811c92ef880adb3e5d67d9bb56ba | **2024-05-29** 12:25:42 |

See [DC1000 Acceleration Card Test Guide_A1.pdf](https://harbor-test2.cn-sh2.ufileos.com/docs/drivers/DC1000-test-manual_A1.pdf).

### VAGPU-KP-24.01.02.09-DC

!!! note "Release Notes 20240516"

    - Fixed rendering errors caused by optimization for Honkai: Star Rail
    - Fixed driver errors caused by deleting containers under high load
    - Added querying of the driver version number in both kernel space and user space
    - Removed the code related to fps_lock
    - Fixed the issue that ion_linux.ko could not be unloaded
    - Fixed the 3D rendering errors in Amap
    - kernel 5.10.0-136.12 and 5.10.0-182 use the same ko

| Board Type | Software Type | OS | Architecture | Size | Download | md5 | Release Time |
| :-----: | :-----: | :-----: | :----: | :-----: | :--: | :----: | :-----: |
| SG100 | Driver | Linux | arm | 285.22 MB | [:arrow_down: VAGPU-KP-24.01.02.09-DC.tgz](https://harbor-test2.cn-sh2.ufileos.com/docs/drivers/VAGPU-KP-24.01.02.09-DC.tgz) | f16714db3a86e1a03c3407dfd065a425 | **2024-05-16** 16:34:41 |

### VAGPU-KP-24.01.02.08-DC

!!! note "Release Notes 20240516"

    - Fixed rendering errors caused by optimization for Honkai: Star Rail
    - Fixed driver errors caused by deleting containers under high load
    - Added querying of the driver version number in both kernel space and user space
    - Removed the code related to fps_lock
    - Fixed the issue that ion_linux.ko could not be unloaded
    - Fixed the 3D rendering errors in Amap

| Board Type | Software Type | OS | Architecture | Size | Download | md5 | Release Time |
| :-----: | :-----: | :-----: | :----: | :-----: | :--: | :----: | :-----: |
| SG100 | Driver | Linux | arm | 303.85 MB | [:arrow_down: VAGPU-KP-24.01.02.08-DC.tgz](https://harbor-test2.cn-sh2.ufileos.com/docs/drivers/VAGPU-KP-24.01.02.08-DC.tgz) | b4e0a259b540a65506cb5f7bff3a8b67 | **2024-05-16** 14:12:06 |

## 2024-04

### tools_3.0.1-20240430-vaqual_sg-aarch64

!!! note "Release Notes 20240430"

    Fixed the decode timeout issue during power consumption stress testing.

| Board Type | Software Type | OS | Architecture | Size | Download | md5 | Release Time |
| :-----: | :-----: | :-----: | :----: | :-----: | :--: | :----: | :-----: |
| VG1000 | Application | Linux | arm | 269.68 MB | [:arrow_down: tools_3.0.1-20240430-vaqual_sg-aarch64.tar.gz](https://harbor-test2.cn-sh2.ufileos.com/docs/drivers/tools_3.0.1-20240430-vaqual_sg-aarch64.tar.gz) | 8d825f1127d8101c4d4167db3db9ba99 | **2024-04-30** 13:23:45 |

### VAGPU-KP-24.01.02.07-DC

!!! note "Release Notes 20240426"

    - Fixed some dEQP crash issues
    - Updated the HWC SDK for NDK builds
    - Updated gpu_config.sh for k8s deployment

| Board Type | Software Type | OS | Architecture | Size | Download | md5 | Release Time |
| :-----: | :-----: | :-----: | :----: | :-----: | :--: | :----: | :-----: |
| SG100 | Driver | Linux | arm | 286.06 MB | [:arrow_down: VAGPU-KP-24.01.02.07-DC.tgz](https://harbor-test2.cn-sh2.ufileos.com/docs/drivers/VAGPU-KP-24.01.02.07-DC.tgz) | 8d825f1127d8101c4d4167db3db9ba99 | **2024-04-26** 12:54:32 |

### VAGPU-KP-24.01.02.06-DC

!!! note "Release Notes 20240419"

    - Fixed the system hang when restarting containers under high load
    - Fixed driver errors and system crashes caused by excessive video memory usage
    - Fixed the incorrect decode rate reported when queried with tools
    - Modified the SDK header files for NDK compilation

| Board Type | Software Type | OS | Architecture | Size | Download | md5 | Release Time |
| :-----: | :-----: | :-----: | :----: | :-----: | :--: | :----: | :-----: |
| SG100 | Driver | Linux | arm | 146.86 MB| [:arrow_down: VAGPU-KP-24.01.02.06-DC.tgz](https://harbor-test2.cn-sh2.ufileos.com/docs/drivers/VAGPU-KP-24.01.02.06-DC.tgz) | 4762c05b45c5a62f69013c7ca730116d | **2024-04-19** 21:13:59 |

### VAGPU-KP-24.01.02.05-DC

!!! note "Release Notes 20240412"

    - Added ion_linux.ko for the two kernels 5.10.0-136.12.0 and 5.10.0-182.0.0
    - Updated the va_gfx.ini file to fix the green screen issue when playing Douyin videos
    - libstagefright.so/libstagefright_omx.so are no longer provided. Customers need to integrate them using the corresponding patch in the omx release.

| Board Type | Software Type | OS | Architecture | Size | Download | md5 | Release Time |
| :-----: | :-----: | :-----: | :----: | :-----: | :--: | :----: | :-----: |
| SG100 | Driver | Linux | arm | 157.67 MB| [:arrow_down: VAGPU-KP-24.01.02.05-DC.tgz](https://harbor-test2.cn-sh2.ufileos.com/docs/drivers/VAGPU-KP-24.01.02.05-DC.tgz) | 799dd7e30daf2a7460da644f6699f5db | **2024-04-12** 18:46:56 |

## 2024-03

### VAGPU-KP-24.01.02.04-DC

!!! note "Release Notes 20240329"

    Optimized the encoding latency and fixed the high decoding latency issue on Xiaomi phones.

| Board Type | Software Type | OS | Architecture | Size | Download | md5 | Release Time |
| :-----: | :-----: | :-----: | :----: | :-----: | :--: | :----: | :-----: |
| SG100 | Driver | Linux | arm | 160.30 MB | [:arrow_down: VAGPU-KP-24.01.02.04-DC.tgz](https://harbor-test2.cn-sh2.ufileos.com/docs/drivers/VAGPU-KP-24.01.02.04-DC.tgz) | d24f598c5a82820d9f8b54a277d72755 | **2024-03-29** 16:23:47 |

### VAGPU-KP-24.01.02.03-DC

!!! note "Release Notes 20240319"

    - Fixed the reconnection failure of multi-card streaming output
    - Added ffmpeg printing to logcat and optimized the log printing level

| Board Type | Software Type | OS | Architecture | Size | Download | md5 | Release Time |
| :-----: | :-----: | :-----: | :----: | :-----: | :--: | :----: | :-----: |
| SG100 | Driver | Linux | arm | 279.25 MB | [:arrow_down: VAGPU-KP-24.01.02.03-DC.tgz](https://harbor-test2.cn-sh2.ufileos.com/docs/drivers/VAGPU-KP-24.01.02.03-DC.tgz) | 1be5c82eb13cbfb881968dbd8750e2b8 | **2024-03-19** 16:45:54 |

### VAGPU-KP-24.01.02.02-DC

!!! note "Release Notes 20240308"

    - Optimized the display effect and user experience when swiping the interface
    - Added the continuous frame delivery feature for static images

    Use the default value of the displayServer.maxInterval property; no additional setting is required.

| Board Type | Software Type | OS | Architecture | Size | Download | md5 | Release Time |
| :-----: | :-----: | :-----: | :----: | :-----: | :--: | :----: | :-----: |
| DC1000 | Driver | Linux | arm | 141.28 MB | [:arrow_down: VAGPU-KP-24.01.02.02-DC.tgz](https://qiniu-download-public.daocloud.io/gpu-tools/VAGPU-KP-24.01.02.02-DC/VAGPU-KP-24.01.02.02-DC.tgz) | 2c2c376e6da30972d19f6e5d63a61084 | **2024-03-08** 15:45:31 |

## 2024-02

### GPU-tools-docs-datasets-24.02.07

!!! note "Release Notes 20240207"

    GPU supporting tools as well as related documentation and datasets.

| Board Type | Software Type | OS | Architecture | Size | Download | md5 | Release Time |
| :-----: | :-----: | :-----: | :----: | :-----: | :--: | :----: | :-----: |
| DC1000 | Driver | Linux | arm | 234.00 B | [:arrow_down: README.txt](https://qiniu-download-public.daocloud.io/gpu-tools/GPU-tools-docs-datasets-24.02.07/README.txt) | c258740c0a7f700aefd100d7afb5141d | **2024-02-07** 11:00:11 |

**Attachments**

| Size | Download | Release Time |
| :-----: | :--: | :----: |
| 10.16 GB | [:arrow_down: 2012img_sv100_DC1000.tar](https://qiniu-download-public.daocloud.io/gpu-tools/GPU-tools-docs-datasets-24.02.07/2012img_sv100_sg100.tar) | 2024-02-18 15:58:51 |
| 5.42 GB | [:arrow_down: dc1000_1.0.0_rc2_kunpeng.tar](https://qiniu-download-public.daocloud.io/gpu-tools/GPU-tools-docs-datasets-24.02.07/dc1000_1.0.0_rc2_kunpeng.tar) | 2024-02-18 15:58:51 |

### FW-release-BL02.3.6R-BMCU1.6R-PMCU1.0R

!!! note "Release Notes 20240206"

    Version correspondence:

    - BL0: vastai_bl0_DC1000_2.3.6R-20231122
    - BMCU: vastai_bmcu_VG1x00_1.6R-20231127
    - PMCU: vastai_pmcu_VG1x00_1.0R-20231110

| Board Type | Software Type | OS | Architecture | Size | Download | md5 | Release Time |
| :-----: | :-----: | :-----: | :----: | :-----: | :--: | :----: | :-----: |
| DC1000 | Driver | Linux | arm | 287.54 KB | [:arrow_down: BL0_BMCU_PMCU-24.02.06.01.tar.gz](https://qiniu-download-public.daocloud.io/gpu-tools/FW-release-BL02.3.6R-BMCU1.6R-PMCU1.0R/BL0_BMCU_PMCU-24.02.06.01.tar.gz) | 83395b33b5411048852e786cd7c7b5d0 | **2024-02-06** 18:19:38 |

### VAGPU-KP-24.01.02.01-DC

!!! note "Release Notes"

    VAGPU-KP-24.01.02.01

| Board Type | Software Type | OS | Architecture | Size | Download | md5 | Release Time |
| :-----: | :-----: | :-----: | :----: | :-----: | :--: | :----: | :-----: |
| DC1000 | Driver | Linux | arm | 139.18 MB | [:arrow_down: VAGPU-KP-24.01.02.01-Android11.tgz](https://qiniu-download-public.daocloud.io/gpu-tools/VAGPU-KP-24.01.02.01-DC/VAGPU-KP-24.01.02.01-Android11.tgz) | 7a032236d6a3846d587cc47eb98d388f | **2024-02-05** 09:53:46 |
