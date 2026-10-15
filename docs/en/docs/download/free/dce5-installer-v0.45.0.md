---
MTPE: windsonsea
date: 2026-10-14
hide:
  - navigation
---

# DCE Community with Installer v0.45.0

This page provides downloads for the offline installation package and verification files for DCE Community.

[Return to Download Guide](../index.md#download-dce-community){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| ------- | --- | ---- | ------ | --- | ------- |
| offline-community-v0.45.0-amd64.tar | v0.45.0 | AMD 64 | 21.02 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.45.0-amd64.tar) | 2026-10-14 |
| offline-community-v0.45.0-arm64.tar | v0.45.0 | <font color="green">ARM 64</font> | 19.93 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.45.0-arm64.tar) | 2026-10-14 |

## Verification

Go to the offline installation package download directory.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "6850986ed120b7320317fc72f9b0409c7c24a1def22786c92da22151f36bf87caef80797193e25d1a33aeaf7a32b187f652ab9142d2fb87ccd8d2cef15fcb182  offline-community-v0.45.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.45.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "4e91d576de32fc9a10779b6179f1888e72671158623c5ca51c9f57b35b74c0cb48a64447a11cb7a26ec1cbce49499ebfb84fa571878b1b9afb099b3a0354ea2d  offline-community-v0.45.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.45.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.45.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.45.0-arm64.tar
    ```

- For installation instructions, refer to [Community Installation Process](../../install/community/k8s/online.md#_2)
- After successful installation, [apply for a free community experience](../../dce/license0.md)

## Modules

DCE Community includes the following modules by default:

| Modules | Introduction | What's New |
| -------- | -------------- | -------------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.50.0](../../ghippo/intro/release-notes.md#v0500) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.50.1](../../kpanda/intro/release-notes.md#v0501) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.45.0](../../insight/intro/release-notes.md#v0450) |

## More

- [Online Documentation](../../dce/index.md)
- [Report a Bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
