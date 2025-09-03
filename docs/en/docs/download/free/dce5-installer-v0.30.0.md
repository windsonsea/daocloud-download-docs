---
MTPE: windsonsea
date: 2025-06-11
hide:
  - navigation
---

# DCE 5.0 Community with Installer v0.30.0

This page provides downloads for the offline installation package and verification files for DCE 5.0 Community.

[Return to Download Guide](../index.md){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| --------- | ------- | ----------- | ---- | -------- | ---- |
| offline-community-v0.30.0-amd64.tar | v0.30.0 | AMD 64 | 13.17 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.30.0-amd64.tar) | 2025-06-09 |
| offline-community-v0.30.0-arm64.tar | v0.30.0 | <font color="green">ARM 64</font> | 12.48 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.30.0-arm64.tar) | 2025-06-09 |

## Verification

Go to the offline installation package download directory.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "25ed66ad9bc619a292230851dd0d67c54a33928bd6b6aeb5926cccfb52bc7ca26b9d6c6c2eb094674613a75cfa985104dcfbf2452e844b486c08f30dff85450f  offline-community-v0.30.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.30.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "90f2a8d0d06781c1f3419808dd35b163cc9989aa6cc207e3bb56805b23a0f08b3bd308de2ba7a15703589833d10d8ac239e28dad3a91cf59f8694e6df456db59  offline-community-v0.30.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.30.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.30.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.30.0-arm64.tar
    ```

- For installation instructions, refer to [Community Installation Process](../../install/community/k8s/online.md#_2)
- After successful installation, [apply for a free community experience](../../dce/license0.md)

## Modules

DCE 5.0 Community includes the following modules by default:

| Modules | Introduction | What's New |
| -------- | ----------- | ---------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.37.0](../../ghippo/intro/release-notes.md#v0370) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.40.0](../../kpanda/intro/release-notes.md#v0400) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.36.1](../../insight/intro/release-notes.md#v0361) |

## More

- [Online Documentation](../../dce/index.md)
- [Report a Bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
