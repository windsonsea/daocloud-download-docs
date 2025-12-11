---
MTPE: windsonsea
date: 2025-12-09
hide:
  - navigation
---

# DCE 5.0 Community with Installer v0.36.0

This page provides downloads for the offline installation package and verification files for DCE 5.0 Community.

[Return to Download Guide](../index.md){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| --------- | ------- | ----------- | ---- | -------- | ---- |
| offline-community-v0.36.0-arm64.tar | v0.36.0 | <font color="green">ARM 64</font> | 13.12 GB | [:arrow_down: 下载](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.36.0-arm64.tar) | 2025-12-09 |
| offline-community-v0.36.0-amd64.tar | v0.36.0 | AMD 64 | 13.82 GB | [:arrow_down: 下载](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.36.0-amd64.tar) | 2025-12-09 |

## Verification

Go to the offline installation package download directory.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "ed26cb0ed889ee2b4179c2f81ecc456667bcc99241f98af5acf2d7d8129154280a73ed08020e967eb179ba395ec5296546f42d227d298bd2841dddd695964566  offline-community-v0.36.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.36.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "d1f9ad5591509e2374d616911563b11712d11aa4ae73b47e2392a64ca310258737a09aa6157131502c387b486aa0ae42846a51f5f76d6d12aa6e04022806b352  offline-community-v0.36.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.36.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.36.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.36.0-arm64.tar
    ```

- For installation instructions, refer to [Community Installation Process](../../install/community/k8s/online.md#_2)
- After successful installation, [apply for a free community experience](../../dce/license0.md)

## Modules

DCE 5.0 Community includes the following modules by default:

| Modules | Introduction | What's New |
| -------- | ----------- | ---------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.43.0](../../ghippo/intro/release-notes.md#v0430) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.43.3](../../kpanda/intro/release-notes.md#v0433) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.39.2](../../insight/intro/release-notes.md#v0392) |

## More

- [Online Documentation](../../dce/index.md)
- [Report a Bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
