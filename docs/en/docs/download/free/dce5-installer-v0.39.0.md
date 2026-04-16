---
MTPE: windsonsea
date: 2026-04-09
hide:
  - navigation
---

# DCE 5.0 Community with Installer v0.39.0

This page provides downloads for the offline installation package and verification files for DCE 5.0 Community.

[Return to Download Guide](../index.md){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| --------- | ------- | ----------- | ---- | -------- | ---- |
| offline-community-v0.39.0-amd64.tar | v0.39.0 | AMD 64 | 14.09 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.39.0-amd64.tar) | 2026-04-09 |
| offline-community-v0.39.0-arm64.tar | v0.39.0 | <font color="green">ARM 64</font> | 13.38 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.39.0-arm64.tar) | 2026-04-09 |

## Verification

Go to the offline installation package download directory.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "b69cc327f49be1a2e9210db054a243d23de679b5856e05f5ded5c634ccc8b8b8e723768630ebe74be910498ff5e86bebf7b4e89915c1f274d4a7710a831af298  offline-community-v0.39.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.39.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "d51628923406b790e4712e3d75b5dc8a656f48a6a6501360873da375b56d46081b8fbd1578ab165fdb5d39abb9305ab369bc5ce1d577ec09d279574752221a29  offline-community-v0.39.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.39.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.39.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.39.0-arm64.tar
    ```

- For installation instructions, refer to [Community Installation Process](../../install/community/k8s/online.md#_2)
- After successful installation, [apply for a free community experience](../../dce/license0.md)

## Modules

DCE 5.0 Community includes the following modules by default:

| Modules | Introduction | What's New |
| -------- | ----------- | ---------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.45.1](../../ghippo/intro/release-notes.md#v0451) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.46.0](../../kpanda/intro/release-notes.md#v0460) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.41.0](../../insight/intro/release-notes.md#v0410) |

## More

- [Online Documentation](../../dce/index.md)
- [Report a Bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
