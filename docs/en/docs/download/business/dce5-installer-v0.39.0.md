---
MTPE: windsonsea
date: 2026-04-09
hide:
  - navigation
---

# DCE 5.0 Enterprise with Installer v0.39.0

This page provides downloads for the offline installation package and verification files for DCE 5.0 Enterprise.

[Return to Download Guide](../index.md#download-dce-50-enterprise){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| --------- | ------ | ------------ | ---- | -------- | ---- |
| offline-v0.39.0-amd64.tar | v0.39.0 | AMD 64 | 34.98 GB | [:arrow_down: 下载](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.39.0-amd64.tar) | 2026-04-09 |
| offline-v0.39.0-arm64.tar | v0.39.0 | <font color="green">ARM 64</font> | 31.66 GB | [:arrow_down: 下载](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.39.0-arm64.tar) | 2026-04-09 |

## Verification

Go to the offline installation package download directory.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "5dbfd0ffcc56d499c2f0df9e3a3eb3e0cc07b56cbf4fa6d9702df671c374ea26948cbe8cef6a475dddc08b7415e314112137ecd7527eefb482c25913b6111752  offline-v0.39.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-v0.39.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "91bf81122c86e00f34e8b70acfd2397f0b903a3e2b9ab62a5c3e48b03fafdf87aba6ab169075ecfee31fdb5fa458d67b02c08ddca449ef5b3cce468f3886b446  offline-v0.39.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-v0.39.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-v0.39.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-v0.39.0-arm64.tar
    ```

- For installation instructions, refer to [Enterprise Installation Process](../../install/commercial/start-install.md)
- After successful installation, contact us for authorization: email info@daocloud.io or call 400 002 6898

## Modules

DCE 5.0 Enterprise includes the following modules, which can be used on-demand to meet various application scenarios:

| Modules | Description | Versions |
| ------- | ----------- | -------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.45.1](../../ghippo/intro/release-notes.md#v0451) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.46.0](../../kpanda/intro/release-notes.md#v0460) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.41.0](../../insight/intro/release-notes.md#v0410) |
| Workbench | A container-based DevOps application platform that supports Jenkins, Tekton, GitOps, and other pipeline jobs. | [v0.40.1](../../amamba/intro/release-notes.md#v0401) |
| MultiCloud Management | Centralized management of multicloud, hybrid cloud, and cross-cloud resources for application orchestration, with capabilities such as multicloud disaster recovery and fault recovery. | [v0.24.0](../../kairship/intro/release-notes.md#v0240) |
| Microservice Engine | Provides governance capabilities such as service registration, discovery, configuration management, and microservice gateway. | [v0.54.0](../../skoala/intro/release-notes.md#v0540) |
| Service Mesh | Next-generation service mesh built on Istio open-source technology for cloud-native applications. | [v0.38.0](../../mspider/intro/release-notes.md#v0380) |
| Middleware Elasticsearch | Currently the preferred full-text search engine. | [v0.27.0](../../middleware/elasticsearch/release-notes.md#v0270) |
| Middleware Kafka | Distributed message queue service based on the open-source software Kafka. | [v0.29.0](../../middleware/kafka/release-notes.md#v0290) |
| Middleware MinIO | A lightweight, open-source object storage solution that is very popular. | [v0.24.0](../../middleware/minio/release-notes.md#v0240) |
| Middleware MySQL | The most widely used open-source relational database. | [v0.29.0](../../middleware/mysql/release-notes.md#v0290) |
| Middleware RabbitMQ | Open-source message broker software that implements the Advanced Message Queuing Protocol (AMQP). | [v0.31.0](../../middleware/rabbitmq/release-notes.md#v0310) |
| Middleware Redis | An in-memory database caching service. | [v0.30.0](../../middleware/redis/release-notes.md#v0300) |
| Container Registry | Used to store images for K8s, DevOps, and container application development. | [v0.24.1](../../kangaroo/intro/release-notes.md#v0241) |
| Networking | Supports multiple CNI combination solutions for different Linux kernels. | [v0.16.6](../../network/intro/release-notes.md#v0166) |
| Storage | Provides unified data storage services, supporting file, object, block, and local storage, easily integrating with storage vendor solutions. | [v1.0.2](../../storage/hwameistor/release-notes.md#v102) |
| AI Lab | Integrates heterogeneous compute resources, optimizes GPU performance, and enables unified scheduling and operation. | [v0.25.1](../../baize/intro/release-notes.md#v0251) |
| LLM Studio | Provides end-to-end lifecycle services from model deployment to operation and maintenance, helping enterprises and developers efficiently integrate and use various large model capabilities | [v0.13.1](../../hydra/intro/release-notes.md#v0131) |
| Cloud Edge Collaboration | Extends cloud native capabilities to the edge. Uses an edge node model to offload data processing, business applications, and AI models to the edge. | [v0.22.0](../../kant/intro/release-notes.md#v0220) |

## More

- [Online Documentation](../../dce/index.md)
- [Report a Bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
