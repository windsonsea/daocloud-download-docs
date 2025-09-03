---
MTPE: windsonsea
date: 2025-05-22
hide:
  - navigation
---

# DCE 5.0 Community with Installer v0.29.0

This page provides downloads for the offline installation package and verification files for DCE 5.0 Community.

[Return to Download Guide](../index.md){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| --------- | ------- | ----------- | ---- | -------- | ---- |
| offline-community-v0.29.0-amd64.tar | v0.29.0 | AMD 64 | 9.54GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.29.0-amd64.tar) | 2025-05-14 |
| offline-community-v0.29.0-arm64.tar | v0.29.0 | <font color="green">ARM 64</font> | 9.02GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.29.0-arm64.tar) | 2025-05-14 |

## Verification

Go to the offline installation package download directory.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "7956a3e72fbe2bf95bc800a2b640849d277f854eeba4256aef50c083e1f9d43583583612182fc60e688d39eeb560bb54d1842ddcf281aaeb3831d8ac9e0a8ab6  offline-community-v0.29.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.29.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "32d7aafc7ad6b8052561b613d2338e6c17e2fd0840258d6d1882646cf2ba3094b0b57e27a637e9836e87385d1ffad6c3b2c18f5fe9180a13f26e3d4c8d2390d0  offline-community-v0.29.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.29.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.29.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.29.0-arm64.tar
    ```

- For installation instructions, refer to [Community Installation Process](../../install/community/k8s/online.md#_2)
- After successful installation, [apply for a free community experience](../../dce/license0.md)

## Modules

DCE 5.0 Community includes the following modules by default:

| Modules | Introduction | What's New |
| -------- | ----------- | ---------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.36.0](../../ghippo/intro/release-notes.md#v0360) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.39.0](../../kpanda/intro/release-notes.md#v0390) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.36.1](../../insight/intro/release-notes.md#v0361) |

## More

- [Online Documentation](../../dce/index.md)
- [Report a Bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
