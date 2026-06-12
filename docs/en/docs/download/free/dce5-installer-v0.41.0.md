---
MTPE: windsonsea
date: 2026-04-09
hide:
  - navigation
---

# DCE 5.0 Community with Installer v0.41.0

This page provides downloads for the offline installation package and verification files for DCE 5.0 Community.

[Return to Download Guide](../index.md){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| --------- | ------- | ----------- | ---- | -------- | ---- |
| offline-community-v0.41.0-amd64.tar | v0.41.0 | AMD 64 | 12.97 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.41.0-amd64.tar) | 2026-06-08 |
| offline-community-v0.41.0-arm64.tar | v0.41.0 | <font color="green">ARM 64</font> | 12.21 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.41.0-arm64.tar) | 2026-06-08 |

## Verification

Go to the offline installation package download directory.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "fa21dd042cc92f118bc3febf3f6ecde3985f96b373b52d680e6bd2f212c12cc56f696bc117d43090c5981f7c319aed85d10d575d7523cff521bbc7ee0e2e981a  offline-community-v0.41.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.41.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "4b62866c50e631908e23aef234fa3e65a95b196fe0bf344bc819bb1d819ce639f8f8aea95ba1ce7a45e3c40f1f5e1eec95596046f504256e8b71e690da40f203  offline-community-v0.41.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.41.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.41.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.41.0-arm64.tar
    ```

- For installation instructions, refer to [Community Installation Process](../../install/community/k8s/online.md#_2)
- After successful installation, [apply for a free community experience](../../dce/license0.md)

## Modules

DCE 5.0 Community includes the following modules by default:

| Modules | Introduction | What's New |
| -------- | ----------- | ---------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.46.0](../../ghippo/intro/release-notes.md#v0460) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.47.0](../../kpanda/intro/release-notes.md#v0470) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.42.0](../../insight/intro/release-notes.md#v0420) |

## More

- [Online Documentation](../../dce/index.md)
- [Report a Bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
