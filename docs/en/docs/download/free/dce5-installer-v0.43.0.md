---
MTPE: windsonsea
date: 2026-07-07
hide:
  - navigation
---

# DCE Community with Installer v0.43.0

This page provides downloads for the offline installation package and verification files for DCE Community.

[Return to Download Guide](../index.md){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| --------- | ------- | ----------- | ---- | -------- | ---- |
| offline-community-v0.43.0-amd64.tar | v0.43.0 | AMD 64 | 17.44GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.43.0-amd64.tar) | 2026-08-13 |
| offline-community-v0.43.0-arm64.tar | v0.43.0 | <font color="green">ARM 64</font> | 16.69GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.43.0-arm64.tar) | 2026-08-13 |

## Verification

Go to the offline installation package download directory.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "5ec270cdf63dd6ddcc3da35419c20a118bb7256986cff919af3c72cf0c0dea13943b92cee69f3bc52446ff21fc98bff5fdf892521db729a0288c37947d40ddad  offline-community-v0.43.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.43.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "cdf718eabb1f277777f3ec1da5f86b0bae6c53b5263fcd044580c7d7181aed5d04cdb81feb4310dc317187a66824063530fefea220c6682a0747d00bbc659370  offline-community-v0.43.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.43.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.43.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.43.0-arm64.tar
    ```

- For installation instructions, refer to [Community Installation Process](../../install/community/k8s/online.md#_2)
- After successful installation, [apply for a free community experience](../../dce/license0.md)

## Modules

DCE Community includes the following modules by default:

| Modules | Introduction | What's New |
| -------- | ----------- | ---------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.48.1](../../ghippo/intro/release-notes.md#v0481) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.49.0](../../kpanda/intro/release-notes.md#v0490) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.43.1](../../insight/intro/release-notes.md#v0431) |

## More

- [Online Documentation](../../dce/index.md)
- [Report a Bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
