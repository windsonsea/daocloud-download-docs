---
MTPE: windsonsea
date: 2026-07-07
hide:
  - navigation
---

# DCE 5.0 Community with Installer v0.42.0

This page provides downloads for the offline installation package and verification files for DCE 5.0 Community.

[Return to Download Guide](../index.md){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| --------- | ------- | ----------- | ---- | -------- | ---- |
| offline-community-v0.42.0-amd64.tar | v0.42.0 | AMD 64 | 14.21 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.42.0-amd64.tar) | 2026-07-07 |
| offline-community-v0.42.0-arm64.tar | v0.42.0 | <font color="green">ARM 64</font> | 12.73 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.42.0-arm64.tar) | 2026-07-07 |

## Verification

Go to the offline installation package download directory.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "53af1f5fb6258d74977ab34e645c95701326710a187d48251e3866a91975623edd8f1fc823a1ea63efc19d372bf4bbe1e95b443e2ddadba05847b76dcb63ffe8  offline-community-v0.42.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.42.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "69a9e3a81a0dff0674afd83dcf67c4cb27f05a280d8336ce4165143fa545dbf2e1a047ae3ab6191bccb9888c4e557e777dc28d260c2ce5b7961d96bd80612b8f  offline-community-v0.42.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.42.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.42.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.42.0-arm64.tar
    ```

- For installation instructions, refer to [Community Installation Process](../../install/community/k8s/online.md#_2)
- After successful installation, [apply for a free community experience](../../dce/license0.md)

## Modules

DCE 5.0 Community includes the following modules by default:

| Modules | Introduction | What's New |
| -------- | ----------- | ---------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.48.0](../../ghippo/intro/release-notes.md#v0480) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.48.1](../../kpanda/intro/release-notes.md#v0481) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.42.2](../../insight/intro/release-notes.md#v0422) |

## More

- [Online Documentation](../../dce/index.md)
- [Report a Bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
