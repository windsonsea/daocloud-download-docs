---
MTPE: windsonsea
date: 2026-02-09
hide:
  - navigation
---

# DCE 5.0 Community with Installer v0.38.0

This page provides downloads for the offline installation package and verification files for DCE 5.0 Community.

[Return to Download Guide](../index.md){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| --------- | ------- | ----------- | ---- | -------- | ---- |
| offline-community-v0.38.0-amd64.tar | v0.38.0 | AMD 64 | 14.09 GB | [:arrow_down: 下载](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.38.0-amd64.tar) | 2026-02-09 |
| offline-community-v0.38.0-arm64.tar | v0.38.0 | <font color="green">ARM 64</font> | 13.38 GB | [:arrow_down: 下载](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.38.0-arm64.tar) | 2026-02-09 |

## Verification

Go to the offline installation package download directory.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "d2d62e1faaac67b29ee65b90d61716de4651aa80be5dcc5dc58f70f8d19ca066ab6ffd3a347c714889f3c368874006062a40cadb44b294536d437c188159adaf  offline-community-v0.38.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.38.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "bf36c4ea44e505fb024d7baf45b0f1d40712e7492b453f2018201c6f37915d10f226f4cef3f7c24ce932e6a656b3f849169c76f2066817a72616e7fc6324588e  offline-community-v0.38.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.38.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.38.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.38.0-arm64.tar
    ```

- For installation instructions, refer to [Community Installation Process](../../install/community/k8s/online.md#_2)
- After successful installation, [apply for a free community experience](../../dce/license0.md)

## Modules

DCE 5.0 Community includes the following modules by default:

| Modules | Introduction | What's New |
| -------- | ----------- | ---------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.44.0](../../ghippo/intro/release-notes.md#v0440) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.45.0](../../kpanda/intro/release-notes.md#v0450) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.40.1](../../insight/intro/release-notes.md#v0401) |

## More

- [Online Documentation](../../dce/index.md)
- [Report a Bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
