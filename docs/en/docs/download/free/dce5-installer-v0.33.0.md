---
MTPE: windsonsea
date: 2025-09-08
hide:
  - navigation
---

# DCE 5.0 Community with Installer v0.33.0

This page provides downloads for the offline installation package and verification files for DCE 5.0 Community.

[Return to Download Guide](../index.md){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| --------- | ------- | ----------- | ---- | -------- | ---- |
| offline-community-v0.33.0-amd64.tar | v0.33.0 | AMD 64 | 13.69 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.33.0-amd64.tar) | 2025-09-08 |
| offline-community-v0.33.0-arm64.tar | v0.33.0 | <font color="green">ARM 64</font> | 12.94 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.33.0-arm64.tar) | 2025-09-08 |

## Verification

Go to the offline installation package download directory.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "554a715d5773bf41ac3993cba0c48de8130aee2ddbbfb9930ad7f63e62fdaa4caa2597965ab57eb21ba09715d1bee386d81a97b313ebf8b3d782fdf2a2af85b2  offline-community-v0.33.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.33.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "0bf2ecb4ef5c2a906ff8bfbc9f51bb3719174fe8614f45c70a2ae91cc6ccd78c9a9972eac827c71966ec5dddc1d4185b819fbb804709c599ac2280e0356a246f  offline-community-v0.33.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.33.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.33.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.33.0-arm64.tar
    ```

- For installation instructions, refer to [Community Installation Process](../../install/community/k8s/online.md#_2)
- After successful installation, [apply for a free community experience](../../dce/license0.md)

## Modules

DCE 5.0 Community includes the following modules by default:

| Modules | Introduction | What's New |
| -------- | ----------- | ---------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.41.0](../../ghippo/intro/release-notes.md#v0410) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.42.1](../../kpanda/intro/release-notes.md#v0421) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.38.1](../../insight/intro/release-notes.md#v0381) |

## More

- [Online Documentation](../../dce/index.md)
- [Report a Bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
