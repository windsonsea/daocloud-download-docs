---
MTPE: windsonsea
date: 2026-08-13
hide:
  - navigation
---

# d.run Token Factory v0.43.0

This page provides offline installation packages and checksum files for d.run Token Factory.

[Return to Download Index](../index.md#download-drun-token-factory){ .md-button } [More Historical Versions](./index.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| ------- | --- | ---- | ------ | --- | ------- |
| offline-v0.43.0-amd64.tar | v0.43.0 | AMD 64 | 38.88 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.43.0-amd64.tar) | 2026-08-13 |
| offline-v0.43.0-arm64.tar | v0.43.0 | <font color="green">ARM 64</font> | 35.41 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.43.0-arm64.tar) | 2026-08-13 |

## Verification

Navigate to the directory where the offline package is downloaded.

=== "AMD 64"

    Run the following command to verify the package:

    ```sh
    echo "24378ae59ed136cf906c789be71d341c7f2e5ad747909036c9b768a812c8c7219194526036d0f71b14920743f3a5053298b421c570834414cc11db0315ee4979  offline-v0.43.0-amd64.tar" | sha512sum -c
    ```

    If the verification succeeds, the output will be:

    ```none
    offline-v0.43.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the package:

    ```sh
    echo "9880714eed9fd6eb3deff1cb162c56cd4a0ef33a82bc1ba7c0ac1c88dce17ec238734c57907f1a40e67015cf566a59d00505f48f7e2327dda7786661862591eb  offline-v0.43.0-arm64.tar" | sha512sum -c
    ```

    If the verification succeeds, the output will be:

    ```none
    offline-v0.43.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to extract the tar package:

    ```sh
    tar -zxvf offline-v0.43.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to extract the tar package:

    ```sh
    tar -zxvf offline-v0.43.0-arm64.tar
    ```

- For installation instructions, see [Enterprise Installation Guide](../../install/commercial/start-install.md).
- After successful installation, contact us for a license: email info@daocloud.io or call 400 002 6898.

## Modules

d.run Token Factory includes the following modules, which can be used on-demand to meet various application scenarios:

| Modules | Description | Versions |
| ---- | --- | ------ |
| ClawOS | Multi-agent runtime and governance platform | [v0.4.0](../../tf/clawos/workspace/index.md) |
| AI Apps | Build intelligent applications | [v0.5.0](../../tf/dak/index.md) |
| LLM Studio | Provides end-to-end lifecycle services from model deployment to operation and maintenance, helping enterprises and developers efficiently integrate and use various large model capabilities. | [v0.17.1](../../insight/intro/release-notes.md#v0171) |
| InferX | Inference acceleration management | [v0.4.0](../../inferx/index.md) |
| Compute Cloud | A platform for operating compute resources | [v0.17.0](../../tf/zestu/index.md) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and other core Kubernetes features. | [v0.49.0](../../kpanda/intro/release-notes.md#v0490) |
| Device Management | A Kubernetes cloud native infrastructure management component built for intelligent computing centers, enabling unified management of hosts, switches, and other hardware resources. | [v0.6.0](../../mspider/intro/release-notes.md#v060) |
| Container Registry | Used to store images for K8s, DevOps, and container application development. | [v0.26.0](../../kangaroo/intro/release-notes.md#v0260) |
| Cloud Native Network | Supports multiple CNI combination solutions for different Linux kernels. | [v0.19.0](../../network/intro/release-notes.md#v0190) |
| Cloud Native Storage | Provides unified data storage services, supporting file, object, block, and local storage, easily integrating with storage vendor solutions. | [v1.1.1](../../storage/hwameistor/release-notes.md#v111) |
| Billing Center | A billing and invoice management system | [v0.1.0](../../tf/leopard/index.md) |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.48.1](../../ghippo/intro/release-notes.md#v0481) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.43.1](../../insight/intro/release-notes.md#v0431) |

## More

- [Online Docs](../../index.md)
- [Report Bugs](https://github.com/DaoCloud/DaoCloud-docs/issues)
