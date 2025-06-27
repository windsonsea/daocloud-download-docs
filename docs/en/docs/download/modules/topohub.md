---
hide:
  - toc
---

# Device Management

This page provides offline packages for different versions of the device management module.

!!! tip

    `topohub` is the internal dev code for device management.

## Download


| Version  | Architecture | Size | Package | Checksum | Date |
| ---- | ---- | -------- | ------ | -------- | -------- |
| [v0.2.0](../../topohub/intro/release-notes.md) | AMD64 | 47.89 MB | [:arrow_down: topohub_v0.2.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub_v0.2.0_amd64.tar) | [:arrow_down: topohub_v0.2.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub_v0.2.0_amd64_checksum.sha512sum) | 2025-06-17 |
| [v0.3.0](../../topohub/intro/release-notes.md) | AMD64 | 47.89 MB | [:arrow_down: topohub_v0.3.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub_v0.3.0_amd64.tar) | [:arrow_down: topohub_v0.3.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/topohub_v0.3.0_amd64_checksum.sha512sum) | 2025-06-27 |

## Verification

To verify the integrity of the downloaded offline package and checksum file,
run the following command in the directory:

```sh
echo "$(cat topohub_v0.2.0_amd64_checksum.sha512sum)" | sha512sum -c
```

Upon successful verification, the result will be similar to:

```none
topohub_v0.2.0_amd64.tar: ok
```

## Installation

If this is your first installation, please [apply for a free trial](../../dce/license0.md)
or contact us for authorization: email info@daocloud.io or call 400 002 6898.
For any license key-related inquiries, please contact the DaoCloud delivery team.
