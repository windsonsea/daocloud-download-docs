---
MTPE: windsonsea
date: 2026-04-09
hide:
  - navigation
---

# DCE Community with Installer v0.40.0

This page provides downloads for the offline installation package and verification files for DCE Community.

[Return to Download Guide](../index.md){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| --------- | ------- | ----------- | ---- | -------- | ---- |
| offline-community-v0.40.0-amd64.tar | v0.40.0 | AMD 64 | 12.94 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.40.0-amd64.tar) | 2026-05-15 |
| offline-community-v0.40.0-arm64.tar | v0.40.0 | <font color="green">ARM 64</font> | 12.24 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.40.0-arm64.tar) | 2026-05-15 |

## Verification

Go to the offline installation package download directory.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "eb5192c19e0e9beb8ab474269050ac1d5db0dc89a5e737464cbd8eff7374eda957a7631edc77c3b0b03fa1b257db9040db88b62baf690c421229d26cfdedb11e  offline-community-v0.40.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.40.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "ba2bf22c37203c2442bd8f185651ceaa35730e568ac8b5f23f635277e25bc506dd07ed72e8f730f09f8465525d35a1cbf3d0dd02bf970e2871c9e104465e3ffa  offline-community-v0.40.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.40.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.40.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.40.0-arm64.tar
    ```

- For installation instructions, refer to [Community Installation Process](../../install/community/k8s/online.md#_2)
- After successful installation, [apply for a free community experience](../../dce/license0.md)

## Modules

DCE Community includes the following modules by default:

| Modules | Introduction | What's New |
| -------- | ----------- | ---------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.46.0](../../ghippo/intro/release-notes.md#v0460) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.46.1](../../kpanda/intro/release-notes.md#v0461) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.41.2](../../insight/intro/release-notes.md#v0412) |

## More

- [Online Documentation](../../dce/index.md)
- [Report a Bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
