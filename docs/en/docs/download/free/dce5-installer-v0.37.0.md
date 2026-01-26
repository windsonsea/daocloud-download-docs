---
MTPE: windsonsea
date: 2026-01-26
hide:
  - navigation
---

# DCE 5.0 Community with Installer v0.37.0

This page provides downloads for the offline installation package and verification files for DCE 5.0 Community.

[Return to Download Guide](../index.md){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| --------- | ------- | ----------- | ---- | -------- | ---- |
| offline-community-v0.37.0-amd64.tar | v0.37.0 | AMD 64 | 13.88 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.37.0-amd64.tar) | 2026-01-12 |
| offline-community-v0.37.0-arm64.tar | v0.37.0 | <font color="green">ARM 64</font> | 13.17 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.37.0-arm64.tar) | 2026-01-12 |

## Verification

Go to the offline installation package download directory.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "6da0226c447fe8eadb7c370b580bbad27dddee4cb9f2edbd7175d6fb31c61b4fdeb59db13f579dd1876219dbd65cd834cc00bee0fcb052fbfc8890ab78dc0ae5  offline-community-v0.37.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.37.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "f45ed0e88b578b02b71927b3fe82030eabbbc48e430de62c11ac0b36774de3d959a762cc95c6683cb394be88d45fad05a37163f51a49d11cb89966114ed2e634  offline-community-v0.37.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.37.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.37.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.37.0-arm64.tar
    ```

- For installation instructions, refer to [Community Installation Process](../../install/community/k8s/online.md#_2)
- After successful installation, [apply for a free community experience](../../dce/license0.md)

## Modules

DCE 5.0 Community includes the following modules by default:

| Modules | Introduction | What's New |
| -------- | ----------- | ---------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.44.0](../../ghippo/intro/release-notes.md#v0440) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.44.0](../../kpanda/intro/release-notes.md#v0440) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.40.0](../../insight/intro/release-notes.md#v0400) |

## More

- [Online Documentation](../../dce/index.md)
- [Report a Bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
