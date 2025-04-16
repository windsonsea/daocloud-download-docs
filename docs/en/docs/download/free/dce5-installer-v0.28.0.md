---
MTPE: windsonsea
date: 2025-04-11
hide:
  - navigation
---

# DCE 5.0 Community with Installer v0.28.0

This page provides downloads for the offline installation package and verification files for DCE 5.0 Community.

[Return to Download Guide](../index.md){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| --------- | ------- | ----------- | ---- | -------- | ---- |
| offline-community-v0.28.0-amd64.tar | v0.28.0 | AMD 64 | 9.50 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.28.0-amd64.tar) | 2025-04-11 |
| offline-community-v0.28.0-arm64.tar | v0.28.0 | <font color="green">ARM 64</font> | 8.99 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.28.0-arm64.tar) | 2025-04-11 |

## Verification

Go to the offline installation package download directory.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "53012a52a8cdc07644f403e77fc9d01b7c06a2a1564c811ccb6dfb6894e192aa7b0f485412271343ca6db6896dd3c18a2dc48cb9d099ba4cbd58eaa06679cc60  offline-community-v0.28.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.28.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "1c1b890e11337335b54bd79e089582b2e73c56a7728abccf62b01364b8eede70a7a8332f92aed5fc03d6d6a8033589a514df771e2b8bc7472db6b03556e0b688  offline-community-v0.28.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.28.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.28.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.28.0-arm64.tar
    ```

- For installation instructions, refer to [Community Installation Process](../../install/community/k8s/online.md#_2)
- After successful installation, [apply for a free community experience](../../dce/license0.md)

## Modules

DCE 5.0 Community includes the following modules by default:

| Modules | Introduction | What's New |
| -------- | ----------- | ---------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [0.35.0](../../ghippo/intro/release-notes.md#v0350) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [0.37.0](../../kpanda/intro/release-notes.md#v0370) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [0.35.1](../../insight/intro/release-notes.md#v0351) |

## More

- [Online Documentation](../../dce/index.md)
- [Report a Bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
