---
MTPE: windsonsea
date: 2025-09-08
hide:
  - navigation
---

# DCE 5.0 Community with Installer v0.34.0

This page provides downloads for the offline installation package and verification files for DCE 5.0 Community.

[Return to Download Guide](../index.md){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| --------- | ------- | ----------- | ---- | -------- | ---- |
| offline-community-v0.34.0-amd64.tar | v0.34.0 | AMD 64 | 13.67 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.34.0-amd64.tar) | 2025-10-15 |
| offline-community-v0.34.0-arm64.tar | v0.34.0 | <font color="green">ARM 64</font> | 12.98 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.34.0-arm64.tar) | 2025-10-15 |

## Verification

Go to the offline installation package download directory.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "70cded84498f492574a2d7a4839b0eff29f29705c5653494467225bd66273ea9be4423137c64b8e05b9082c80aee35fbf456d11067d4427fd521fbc538ee744c  offline-community-v0.34.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.34.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "1f8c8d433454b1972f76408db95a193a12efcbdd3ce5320baecd19d9cb00749a3a15f6dda7b0f4cc189b9df4b5aa749ea16869f548184ab91f2675eac580da18  offline-community-v0.34.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.34.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.34.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.34.0-arm64.tar
    ```

- For installation instructions, refer to [Community Installation Process](../../install/community/k8s/online.md#_2)
- After successful installation, [apply for a free community experience](../../dce/license0.md)

## Modules

DCE 5.0 Community includes the following modules by default:

| Modules | Introduction | What's New |
| -------- | ----------- | ---------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.41.0](../../ghippo/intro/release-notes.md#v0410) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.43.0](../../kpanda/intro/release-notes.md#v0430) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.38.2](../../insight/intro/release-notes.md#v0382) |

## More

- [Online Documentation](../../dce/index.md)
- [Report a Bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
