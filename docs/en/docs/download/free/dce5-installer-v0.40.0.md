---
MTPE: windsonsea
date: 2026-05-15
hide:
  - navigation
---

# DCE 5.0 Community v0.40.0

This page provides offline installation packages and checksum files for DCE 5.0 Community edition.

[Return to Download Index](../index.md){ .md-button } [More Historical Versions](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| -------- | ------- | ------------ | ---- | -------- | ---- |
| offline-community-v0.40.0-amd64.tar | v0.40.0 | AMD64 | 12.94 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.40.0-amd64.tar) | 2026-05-15 |
| offline-community-v0.40.0-arm64.tar | v0.40.0 | <font color="green">ARM64</font> | 12.24 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.40.0-arm64.tar) | 2026-05-15 |

## Verification

Go to the directory where the offline package is downloaded.

=== "AMD64"

    Run the following command to verify the package:

    ```sh
    echo "eb5192c19e0e9beb8ab474269050ac1d5db0dc89a5e737464cbd8eff7374eda957a7631edc77c3b0b03fa1b257db9040db88b62baf690c421229d26cfdedb11e  offline-community-v0.40.0-amd64.tar" | sha512sum -c
    ```

    If successful, it will print:

    ```none
    offline-community-v0.40.0-amd64.tar: OK
    ```

=== "<font color="green">ARM64</font>"

    Run the following command to verify the package:

    ```sh
    echo "ba2bf22c37203c2442bd8f185651ceaa35730e568ac8b5f23f635277e25bc506dd07ed72e8f730f09f8465525d35a1cbf3d0dd02bf970e2871c9e104465e3ffa  offline-community-v0.40.0-arm64.tar" | sha512sum -c
    ```

    If successful, it will print:

    ```none
    offline-community-v0.40.0-arm64.tar: OK
    ```

## Installation

After successful verification,

=== "AMD64"

    Extract the tar package:

    ```sh
    tar -xvf offline-community-v0.40.0-amd64.tar
    ```

=== "<font color="green">ARM64</font>"

    Extract the tar package:

    ```sh
    tar -xvf offline-community-v0.40.0-arm64.tar
    ```

- Please refer to [Community Installation Guide](../../install/community/k8s/online.md#_2)
- After successful installation, please [apply for free community trial](../../dce/license0.md)

## Modules

DCE 5.0 Community includes the following modules by default:

| Module | Introduction | Latest Update |
|--------|--------------|---------------|
| Global Management | Responsible for user access control, permissions, workspaces and hierarchies, audit logs, personalized appearance settings, etc. | [v0.46.0](../../ghippo/intro/release-notes.md#v0460) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRD, namespaces and other K8s core features | [v0.46.1](../../kpanda/intro/release-notes.md#v0461) |
| Observability | Provides rich dashboards, scene monitoring, data queries, alerts and other graphical information | [v0.41.2](../../insight/intro/release-notes.md#v0412) |

## More

- [Online Documentation](../../dce/index.md)
- [Report Bugs](https://github.com/DaoCloud/DaoCloud-docs/issues)
