---
MTPE: windsonsea
date: 2025-08-08
hide:
  - navigation
---

# DCE 5.0 Community with Installer v0.32.0

This page provides downloads for the offline installation package and verification files for DCE 5.0 Community.

[Return to Download Guide](../index.md){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| --------- | ------- | ----------- | ---- | -------- | ---- |
| offline-community-v0.32.0-amd64.tar | v0.32.0 | AMD 64 | 13.48 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.32.0-amd64.tar) | 2025-08-08 |
| offline-community-v0.32.0-arm64.tar | v0.32.0 | <font color="green">ARM 64</font> | 12.78 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.32.0-arm64.tar) | 2025-08-08 |

## Verification

Go to the offline installation package download directory.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "6ac2b4a2e93a5e267525ae2a726421b24f420be49a57da696bb53c23881336469b8ea835ebd69af07d10b6ece5905b3a6fc7a4bb4723ae5601bb077db9ddf4dc  offline-community-v0.32.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.32.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "e9c815d7d87467cb47a9c286d4b161182618a10dc04834c740201d4f59e6fc69ed2fffc8de1900da87e5ea23fb604246cc9cbd7f6de5b6e97a6239f3b6f8227c  offline-community-v0.32.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-community-v0.32.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.32.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-community-v0.32.0-arm64.tar
    ```

- For installation instructions, refer to [Community Installation Process](../../install/community/k8s/online.md#_2)
- After successful installation, [apply for a free community experience](../../dce/license0.md)

## Modules

DCE 5.0 Community includes the following modules by default:

| Modules | Introduction | What's New |
| -------- | ----------- | ---------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.40.0](../../ghippo/intro/release-notes.md#v0400) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.41.0](../../kpanda/intro/release-notes.md#v0410) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.37.0](../../insight/intro/release-notes.md#v0370) |

## More

- [Online Documentation](../../dce/index.md)
- [Report a Bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
