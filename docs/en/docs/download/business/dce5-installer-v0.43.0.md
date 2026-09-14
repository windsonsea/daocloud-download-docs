---
MTPE: windsonsea
date: 2026-09-11
hide:
  - navigation
---

# DCE Enterprise with Installer v0.43.0

This page provides offline installation packages and checksum files for DCE Enterprise edition.

[Return to Download Index](../index.md#download-dce-50-enterprise){ .md-button } [More Historical Versions](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| -------- | ------- | ------------ | ---- | -------- | ---- |
| offline-v0.43.0-amd64.tar | v0.43.0 | AMD 64 | 38.88GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.43.0-amd64.tar) | 2026-08-13 |
| offline-v0.43.0-arm64.tar | v0.43.0 | <font color="green">ARM 64</font> | 35.41GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.43.0-arm64.tar) | 2026-08-13 |

## Verification

Go to the directory where the offline package is downloaded.

=== "AMD64"

    Run the following command to verify:

    ```sh
    echo "24378ae59ed136cf906c789be71d341c7f2e5ad747909036c9b768a812c8c7219194526036d0f71b14920743f3a5053298b421c570834414cc11db0315ee4979  offline-v0.43.0-amd64.tar" | sha512sum -c
    ```

    If successful:

    ```none
    offline-v0.43.0-amd64.tar: OK
    ```

=== "<font color="green">ARM64</font>"

    Run the following command to verify:

    ```sh
    echo "9880714eed9fd6eb3deff1cb162c56cd4a0ef33a82bc1ba7c0ac1c88dce17ec238734c57907f1a40e67015cf566a59d00505f48f7e2327dda7786661862591eb  offline-v0.43.0-arm64.tar" | sha512sum -c
    ```

    If successful:

    ```none
    offline-v0.43.0-arm64.tar: OK
    ```

## Installation

After verification, extract:

=== "AMD64"

    ```sh
    tar -xvf offline-v0.43.0-amd64.tar
    ```

=== "<font color="green">ARM64</font>"

    ```sh
    tar -xvf offline-v0.43.0-arm64.tar
    ```

- See [Enterprise Installation Guide](../../install/commercial/start-install.md)
- Contact: info@daocloud.io or 400 002 6898

## Modules

DCE Enterprise includes the following modules, which can be used on-demand to meet various application scenarios:

| Modules | Description | Versions |
| ------- | ----------- | -------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.48.1](../../ghippo/intro/release-notes.md#v0481) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.49.0](../../kpanda/intro/release-notes.md#v0490) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.43.1](../../insight/intro/release-notes.md#v0431) |
| Workbench | A container-based DevOps application platform that supports Jenkins, Tekton, GitOps, and other pipeline jobs. | [v0.41.1](../../amamba/intro/release-notes.md#v0411) |
| MultiCloud Management | Centralized management of multicloud, hybrid cloud, and cross-cloud resources for application orchestration, with capabilities such as multicloud disaster recovery and fault recovery. | [v0.24.0](../../kairship/intro/release-notes.md#v0240) |
| Microservice Engine | Provides governance capabilities such as service registration, discovery, configuration management, and microservice gateway. | [v0.56.0](../../skoala/intro/release-notes.md#v0560) |
| Service Mesh | Next-generation service mesh built on Istio open-source technology for cloud-native applications. | [v0.40.0](../../mspider/intro/release-notes.md#v0400) |
| Middleware Elasticsearch | Currently the preferred full-text search engine. | [v0.28.1](../../middleware/elasticsearch/release-notes.md#v0281) |
| Middleware Kafka | Distributed message queue service based on the open-source software Kafka. | [v0.31.0](../../middleware/kafka/release-notes.md#v0310) |
| Middleware MinIO | A lightweight, open-source object storage solution that is very popular. | [v0.25.0](../../middleware/minio/release-notes.md#v0250) |
| Middleware MySQL | The most widely used open-source relational database. | [v0.31.0](../../middleware/mysql/release-notes.md#v0310) |
| Middleware RabbitMQ | Open-source message broker software that implements the Advanced Message Queuing Protocol (AMQP). | [v0.33.2](../../middleware/rabbitmq/release-notes.md#v0332) |
| Middleware Redis | An in-memory database caching service. | [v0.31.1](../../middleware/redis/release-notes.md#v0311) |
| Container Registry | Used to store images for K8s, DevOps, and container application development. | [v0.25.0](../../kangaroo/intro/release-notes.md#v0250) |
| Networking | Supports multiple CNI combination solutions for different Linux kernels. | [v0.19.0](../../network/intro/release-notes.md#v0190) |
| Storage | Provides unified data storage services, supporting file, object, block, and local storage, easily integrating with storage vendor solutions. | [v1.1.1](../../storage/hwameistor/release-notes.md#v111) |
| AI Lab | Integrates heterogeneous compute resources, optimizes GPU performance, and enables unified scheduling and operation. | [v0.28.0](../../baize/intro/release-notes.md#v0280) |
| LLM Studio | Provides end-to-end lifecycle services from model deployment to operation and maintenance, helping enterprises and developers efficiently integrate and use various large model capabilities | [v0.17.1](../../hydra/intro/release-notes.md#v0171) |
| Cloud Edge Collaboration | Extends cloud native capabilities to the edge. Uses an edge node model to offload data processing, business applications, and AI models to the edge. | [v0.22.0](../../kant/intro/release-notes.md#v0220) |

## More

- [Online Docs](../../dce/index.md)
- [Report Bugs](https://github.com/DaoCloud/DaoCloud-docs/issues)
