---
hide:
  - toc
---

# LLM Studio

On this page, you can download the offline packages of each version of the LLM Studio module.

## Downloads

| Version | Architecture | Size | Package | Checksum | Date |
| ------- | ------------ | ---- | ------- | -------- | ---- |
| [v0.9.0](../../hydra/intro/release-notes.md) | <font color="green">ARM 64</font> | 653 MB | [:arrow_down: hydra_v0.9.0_arm64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/hydra_v0.9.0_arm64.tar) | [:arrow_down: hydra_v0.9.0_arm64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/hydra_v0.9.0_arm64_checksum.sha512sum) | 2025-09-01 |
| [v0.9.0](../../hydra/intro/release-notes.md) | AMD 64 | 678 MB | [:arrow_down: hydra_v0.9.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/hydra_v0.9.0_amd64.tar) | [:arrow_down: hydra_v0.9.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/hydra_v0.9.0_amd64_checksum.sha512sum) | 2025-09-01 |

## Verification

In the directory where the offline packages and checksum files are downloaded,
take `v0.9.0_amd64` as an example, run the following command to verify the integrity:

```sh
echo "$(cat hydra_v0.9.0_amd64_checksum.sha512sum)" | sha512sum -c
```

After the verification is successful, the output is similar to:

```none
hydra_v0.9.0_amd64.tar: ok
```

## Installation

If you are installing for the first time, please [apply for a free trial](../../dce/license0.md) or contact us for authorization: email info@daocloud.io or call 400 002 6898.
If you have any license key related questions, please contact DaoCloud delivery team.
