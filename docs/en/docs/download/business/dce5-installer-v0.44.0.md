---
MTPE: windsonsea
date: 2026-09-14
hide:
  - navigation
---

# DCE Enterprise with Installer v0.44.0

This page provides offline installation packages and checksum files for DCE Enterprise edition.

[Return to Download Index](../index.md#download-dce-enterprise){ .md-button } [More Historical Versions](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| ------- | --- | ---- | ------ | --- | ------- |
| offline-v0.44.0-amd64.tar | v0.44.0 | AMD 64 | 38.95 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.44.0-amd64.tar) | 2026-09-14 |
| offline-v0.44.0-arm64.tar | v0.44.0 | <font color="green">ARM 64</font> | 35.62 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.44.0-arm64.tar) | 2026-09-14 |

## Verification

Go to the directory where the offline package is downloaded.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "7b58ca770d57915947607aa34078132d3770977083cddafe4c37a78555e931be69e3c5f3c32580713d514d57a4ae30458b083d5f3a0dba8ffd8779b7ed5402a7  offline-v0.44.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-v0.44.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "8a5db891d6ca1288405fb0137cf0bd1acdcd71a7cbdd58e0e0853146c7920f9171257e6c4058dfcc532cee87d90b1b2bc5baab1a52053d9273654f5f6df873a1  offline-v0.44.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

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

- See [Enterprise Installation Guide](../../install/commercial/start-install.md)
- Contact: info@daocloud.io or 400 002 6898

## Modules

DCE Enterprise includes the following modules, which can be used on-demand to meet various application scenarios:

| Modules | Description | Versions |
| ---- | --- | ------ |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.49.2](../../ghippo/intro/release-notes.md#v0492) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.50.0](../../kpanda/intro/release-notes.md#v0500) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.44.1](../../insight/intro/release-notes.md#v0441) |
| LLM Studio | Provides end-to-end lifecycle services from model deployment to operation and maintenance, helping enterprises and developers efficiently integrate and use various large model capabilities | [v0.18.3](../../hydra/intro/release-notes.md#v0183) |
| AI Lab | Integrates heterogeneous compute resources, optimizes GPU performance, and enables unified scheduling and operation. | [v0.29.2](../../baize/intro/release-notes.md#v0292) |
| Workbench | A container-based DevOps application platform that supports Jenkins, Tekton, GitOps, and other pipeline jobs. | [v0.41.3](../../amamba/intro/release-notes.md#v0413) |
| MultiCloud Management | Centralized management of multicloud, hybrid cloud, and cross-cloud resources for application orchestration, with capabilities such as multicloud disaster recovery and fault recovery. | [v0.24.0](../../kairship/intro/release-notes.md#v0240) |
| Microservice Engine | Provides governance capabilities such as service registration, discovery, configuration management, and microservice gateway. | [v0.57.0](../../skoala/intro/release-notes.md#v0570) |
| Service Mesh | Next-generation service mesh built on Istio open-source technology for cloud-native applications. | [v0.40.0](../../mspider/intro/release-notes.md#v0400) |
| Cloud Edge Collaboration | Extends cloud native capabilities to the edge. Uses an edge node model to offload data processing, business applications, and AI models to the edge. | [v0.24.0](../../kant/intro/release-notes.md#v0240) |
| Device Management | A Kubernetes cloud-native infrastructure management component built for intelligent computing centers, enabling unified management of hardware resources such as hosts and switches. | [v0.6.0](../../topohub/intro/release-notes.md#v060) |
| Middleware Elasticsearch | Currently the preferred full-text search engine. | [v0.29.0](../../middleware/elasticsearch/release-notes.md#v0290) |
| Middleware Kafka | Distributed message queue service based on the open-source software Kafka. | [v0.31.0](../../middleware/kafka/release-notes.md#v0310) |
| Middleware MinIO | A lightweight, open-source object storage solution that is very popular. | [v0.25.0](../../middleware/minio/release-notes.md#v0250) |
| Middleware MySQL | The most widely used open-source relational database. | [v0.31.0](../../middleware/mysql/release-notes.md#v0310) |
| Middleware RabbitMQ | Open-source message broker software that implements the Advanced Message Queuing Protocol (AMQP). | [v0.33.2](../../middleware/rabbitmq/release-notes.md#v0332) |
| Middleware Redis | An in-memory database caching service. | [v0.31.1](../../middleware/redis/release-notes.md#v0311) |
| Container Registry | Used to store images for K8s, DevOps, and container application development. | [v0.26.0](../../kangaroo/intro/release-notes.md#v0260) |
| Networking | Supports multiple CNI combination solutions for different Linux kernels. | [v0.19.0](../../network/intro/release-notes.md#v0190) |
| Storage | Provides unified data storage services, supporting file, object, block, and local storage, easily integrating with storage vendor solutions. | [v1.1.1](../../storage/hwameistor/release-notes.md#v111) |


## More

- [Online Docs](../../dce/index.md)
- [Report Bugs](https://github.com/DaoCloud/DaoCloud-docs/issues)
