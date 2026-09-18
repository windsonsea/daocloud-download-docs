---
MTPE: windsonsea
date: 2026-09-14
hide:
  - navigation
---

# DCE Community with Installer v0.44.0

This page provides downloads for the offline installation package and verification files for DCE Community.

[Return to Download Guide](../index.md#download-dce-community){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| ------- | --- | ---- | ------ | --- | ------- |
| offline-community-v0.44.0-amd64.tar | v0.44.0 | AMD 64 | 18.20 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.44.0-amd64.tar) | 2026-09-14 |
| offline-community-v0.44.0-arm64.tar | v0.44.0 | <font color="green">ARM 64</font> | 17.28 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.44.0-arm64.tar) | 2026-09-14 |

## Verification

Go to the offline installation package download directory.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "543a48fb8c53efc77a045d35bb2b2f6bae872029b2f1e722c4789940ae3b099266f0625c60c09ec8d16e712996b6fbec04ec1416093726fb576c14a10871dc9f  offline-community-v0.44.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.44.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "3075733240d05b8e2b713c9c1fe227f640f0682620a0b50c7ff64e0b5743a50083c0ac73664000823d6e138deb5948849c38163facd00724989a99672a6ea1fd  offline-community-v0.44.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.44.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.44.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.44.0-arm64.tar
    ```

- For installation instructions, refer to [Community Installation Process](../../install/community/k8s/online.md#_2)
- After successful installation, [apply for a free community experience](../../dce/license0.md)

## Modules

DCE Community includes the following modules by default:

| Modules | Introduction | What's New |
| -------- | -------------- | -------------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.49.2](../../ghippo/intro/release-notes.md#v0492) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.50.0](../../kpanda/intro/release-notes.md#v0500) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.44.1](../../insight/intro/release-notes.md#v0441) |

## More

- [Online Documentation](../../dce/index.md)
- [Report a Bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
