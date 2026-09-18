---
MTPE: windsonsea
date: 2026-09-14
hide:
  - navigation
---

# d.run AI OS v0.44.0

This page provides offline installation packages and checksum files for d.run AI OS.

[Return to Download Index](../index.md#download-drun-ai-os){ .md-button } [More Historical Versions](./index.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| ------- | --- | ---- | ------ | --- | ------- |
| offline-v0.44.0-amd64.tar | v0.44.0 | AMD 64 | 38.95 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.44.0-amd64.tar) | 2026-09-14 |
| offline-v0.44.0-arm64.tar | v0.44.0 | <font color="green">ARM 64</font> | 35.62 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.44.0-arm64.tar) | 2026-09-14 |

## Verification

Navigate to the directory where the offline package is downloaded.

=== "AMD 64"

    Run the following command to verify the package:

    ```sh
    echo "7b58ca770d57915947607aa34078132d3770977083cddafe4c37a78555e931be69e3c5f3c32580713d514d57a4ae30458b083d5f3a0dba8ffd8779b7ed5402a7  offline-v0.44.0-amd64.tar" | sha512sum -c
    ```

    If the verification succeeds, the output will be:

    ```none
    offline-v0.44.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the package:

    ```sh
    echo "8a5db891d6ca1288405fb0137cf0bd1acdcd71a7cbdd58e0e0853146c7920f9171257e6c4058dfcc532cee87d90b1b2bc5baab1a52053d9273654f5f6df873a1  offline-v0.44.0-arm64.tar" | sha512sum -c
    ```

    If the verification succeeds, the output will be:

    ```none
    offline-v0.44.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to extract the tar package:

    ```sh
    tar -zxvf offline-v0.44.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to extract the tar package:

    ```sh
    tar -zxvf offline-v0.44.0-arm64.tar
    ```

- For installation instructions, see [Enterprise Installation Guide](../../install/commercial/start-install.md).
- After successful installation, contact us for a license: email info@daocloud.io or call 400 002 6898.

## Modules

d.run AI OS includes the following modules, which can be used on-demand to meet various application scenarios:

| Modules | Description | Versions |
| ---- | --- | ------ |
| ClawOS | Multi-agent runtime and governance platform | [v0.5.0](../../drun/clawos/workspace/index.md) |
| LLM Studio | Provides end-to-end lifecycle services from model deployment to operation and maintenance, helping enterprises and developers efficiently integrate and use various large model capabilities. | [v0.18.3](../../insight/intro/release-notes.md#v0183) |
| AI Lab | An integrated training and inference platform with unified scheduling of compute resources, simplifying AI application development and deployment. | [v0.29.2](../../insight/intro/release-notes.md#v0292) |
| InferX | Inference acceleration management | [v0.5.0](../../inferx/index.md) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and other core Kubernetes features. | [v0.50.0](../../kpanda/intro/release-notes.md#v0500) |
| Device Management | A Kubernetes cloud native infrastructure management component built for intelligent computing centers, enabling unified management of hosts, switches, and other hardware resources. | [v0.6.0](../../mspider/intro/release-notes.md#v060) |
| Container Registry | Used to store images for K8s, DevOps, and container application development. | [v0.26.0](../../kangaroo/intro/release-notes.md#v0260) |
| Cloud Native Network | Supports multiple CNI combination solutions for different Linux kernels. | [v0.19.0](../../network/intro/release-notes.md#v0190) |
| Cloud Native Storage | Provides unified data storage services, supporting file, object, block, and local storage, easily integrating with storage vendor solutions. | [v1.1.1](../../storage/hwameistor/release-notes.md#v111) |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.49.2](../../ghippo/intro/release-notes.md#v0492) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.44.1](../../insight/intro/release-notes.md#v0441) |

## More

- [Online Docs](../../index.md)
- [Report Bugs](https://github.com/DaoCloud/DaoCloud-docs/issues)
