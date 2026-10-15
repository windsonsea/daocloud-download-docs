---
MTPE: windsonsea
date: 2026-10-14
hide:
  - navigation
---

# d.run AI OS v0.45.0

This page provides offline installation packages and checksum files for d.run AI OS.

[Return to Download Index](../index.md#download-drun-ai-os){ .md-button } [More Historical Versions](./index.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| ------- | --- | ---- | ------ | --- | ------- |
| offline-v0.45.0-amd64.tar | v0.45.0 | AMD 64 | 41.28 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.45.0-amd64.tar) | 2026-10-14 |
| offline-v0.45.0-arm64.tar | v0.45.0 | <font color="green">ARM 64</font> | 38.06 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.45.0-arm64.tar) | 2026-10-14 |

## Verification

Navigate to the directory where the offline package is downloaded.

=== "AMD 64"

    Run the following command to verify the package:

    ```sh
    echo "703ecee8d2512a6a14386d6fb7ea443c11f34a4792c41ce13aa59862147bda6912c79cad1edef8e16f3b2385095d9c56c1f5ae2e0365fd1bbfff0cb7ab6d9617  offline-v0.45.0-amd64.tar" | sha512sum -c
    ```

    If the verification succeeds, the output will be:

    ```none
    offline-v0.45.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the package:

    ```sh
    echo "401db857d9973bc8f6bc96fcda8dedd106f5d81e31213914ead76df61b021796ec214d981c9da205913289e8d23640446bf53479b7d92e19dbda5712704a6051  offline-v0.45.0-arm64.tar" | sha512sum -c
    ```

    If the verification succeeds, the output will be:

    ```none
    offline-v0.45.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to extract the tar package:

    ```sh
    tar -zxvf offline-v0.45.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to extract the tar package:

    ```sh
    tar -zxvf offline-v0.45.0-arm64.tar
    ```

- For installation instructions, see [Enterprise Installation Guide](../../install/commercial/start-install.md).
- After successful installation, contact us for a license: email info@daocloud.io or call 400 002 6898.

## Modules

d.run AI OS includes the following modules, which can be used on-demand to meet various application scenarios:

| Modules | Description | Versions |
| ---- | --- | ------ |
| ClawOS | Multi-agent runtime and governance platform | [v0.7.0](../../drun/clawos/workspace/index.md) |
| LLM Studio | Provides end-to-end lifecycle services from model deployment to operation and maintenance, helping enterprises and developers efficiently integrate and use various large model capabilities. | [v0.19.3](../../hydra/intro/release-notes.md#v0193) |
| AI Lab | An integrated training and inference platform with unified scheduling of compute resources, simplifying AI application development and deployment. | [v0.30.0](../../baize/intro/release-notes.md#v0300) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and other core Kubernetes features. | [v0.50.1](../../kpanda/intro/release-notes.md#v0501) |
| Device Management | A Kubernetes cloud native infrastructure management component built for intelligent computing centers, enabling unified management of hosts, switches, and other hardware resources. | [v0.6.0](../../topohub/intro/release-notes.md#v060) |
| Container Registry | Used to store images for K8s, DevOps, and container application development. | [v0.26.0](../../kangaroo/intro/release-notes.md) |
| Cloud Native Network | Supports multiple CNI combination solutions for different Linux kernels. | [v0.19.1](../../network/intro/release-notes.md) |
| Cloud Native Storage | Provides unified data storage services, supporting file, object, block, and local storage, easily integrating with storage vendor solutions. | [v1.1.1](../../storage/hwameistor/release-notes.md) |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.50.0](../../ghippo/intro/release-notes.md#v0500) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.45.0](../../insight/intro/release-notes.md#v0450) |

## More

- [Online Docs](../../index.md)
- [Report Bugs](https://github.com/DaoCloud/DaoCloud-docs/issues)
