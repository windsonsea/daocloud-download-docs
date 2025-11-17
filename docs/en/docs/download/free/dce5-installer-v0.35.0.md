---
MTPE: windsonsea
date: 2025-11-10
hide:
  - navigation
---

# DCE 5.0 Community with Installer v0.35.0

This page provides downloads for the offline installation package and verification files for DCE 5.0 Community.

[Return to Download Guide](../index.md){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| --------- | ------- | ----------- | ---- | -------- | ---- |
| offline-community-v0.35.0-amd64.tar | v0.35.0 | AMD 64 | 13.78 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.35.0-amd64.tar) | 2025-11-10 |
| offline-community-v0.35.0-arm64.tar | v0.35.0 | <font color="green">ARM 64</font> | 13.09 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.35.0-arm64.tar) | 2025-11-10 |

## Verification

Go to the offline installation package download directory.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "2322e2ae0254213ea493e9b48e56bf26290c9352295250b70abc28ac33692030e2d6d84646369a33c206b424e6cffe807284d8ed3faf4699ac79acbbaa331ebd  offline-community-v0.35.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.35.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "01f76ba8a48d5b5f72dac3df5a1422c7ce541189050fb783e0c8a8bcd53d11f21e738d1f5b1b397ce567a9da4ca00db6849b1636e5916d8084061aa1fc08eb92  offline-community-v0.35.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.35.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.35.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.35.0-arm64.tar
    ```

- For installation instructions, refer to [Community Installation Process](../../install/community/k8s/online.md#_2)
- After successful installation, [apply for a free community experience](../../dce/license0.md)

## Modules

DCE 5.0 Community includes the following modules by default:

| Modules | Introduction | What's New |
| -------- | ----------- | ---------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.42.2](../../ghippo/intro/release-notes.md#v0422) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.43.1](../../kpanda/intro/release-notes.md#v0431) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.39.0](../../insight/intro/release-notes.md#v0390) |

## More

- [Online Documentation](../../dce/index.md)
- [Report a Bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
