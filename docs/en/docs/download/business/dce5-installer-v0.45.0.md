---
MTPE: windsonsea
date: 2026-10-14
hide:
  - navigation
---

# DCE Enterprise with Installer v0.45.0

This page provides offline installation packages and checksum files for DCE Enterprise edition.

[Return to Download Index](../index.md#download-dce-enterprise){ .md-button } [More Historical Versions](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| ------- | --- | ---- | ------ | --- | ------- |
| offline-v0.45.0-amd64.tar | v0.45.0 | AMD 64 | 41.28 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.45.0-amd64.tar) | 2026-10-14 |
| offline-v0.45.0-arm64.tar | v0.45.0 | <font color="green">ARM 64</font> | 38.06 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.45.0-arm64.tar) | 2026-10-14 |

## Verification

Go to the directory where the offline package is downloaded.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "703ecee8d2512a6a14386d6fb7ea443c11f34a4792c41ce13aa59862147bda6912c79cad1edef8e16f3b2385095d9c56c1f5ae2e0365fd1bbfff0cb7ab6d9617  offline-v0.45.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-v0.45.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "401db857d9973bc8f6bc96fcda8dedd106f5d81e31213914ead76df61b021796ec214d981c9da205913289e8d23640446bf53479b7d92e19dbda5712704a6051  offline-v0.45.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

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

- See [Enterprise Installation Guide](../../install/commercial/start-install.md)
- Contact: info@daocloud.io or 400 002 6898

## Modules

DCE Enterprise includes the following modules, which can be used on-demand to meet various application scenarios:

| Modules | Description | Versions |
| ---- | --- | ------ |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.50.0](../../ghippo/intro/release-notes.md#v0500) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.50.1](../../kpanda/intro/release-notes.md#v0501) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.45.0](../../insight/intro/release-notes.md#v0450) |
| Workbench | A container-based DevOps application platform that supports Jenkins, Tekton, GitOps, and other pipeline jobs. | [v0.41.3](../../amamba/intro/release-notes.md#v0413) |
| MultiCloud Management | Centralized management of multicloud, hybrid cloud, and cross-cloud resources for application orchestration, with capabilities such as multicloud disaster recovery and fault recovery. | [v0.24.0](../../kairship/intro/release-notes.md#v0240) |
| Microservice Engine | Provides governance capabilities such as service registration, discovery, configuration management, and microservice gateway. | [v0.57.2](../../skoala/intro/release-notes.md#v0572) |
| Service Mesh | Next-generation service mesh built on Istio open-source technology for cloud-native applications. | [v0.40.0](../../mspider/intro/release-notes.md#v0400) |
| Middleware Elasticsearch | Currently the preferred full-text search engine. | [v0.29.0](../../middleware/elasticsearch/release-notes.md#v0290) |
| Middleware Kafka | Distributed message queue service based on the open-source software Kafka. | [v0.31.0](../../middleware/kafka/release-notes.md#v0310) |
| Middleware MinIO | A lightweight, open-source object storage solution that is very popular. | [v0.25.0](../../middleware/minio/release-notes.md#v0250) |
| Middleware MySQL | The most widely used open-source relational database. | [v0.31.0](../../middleware/mysql/release-notes.md#v0310) |
| Middleware RabbitMQ | Open-source message broker software that implements the Advanced Message Queuing Protocol (AMQP). | [v0.34.0](../../middleware/rabbitmq/release-notes.md#v0340) |
| Middleware Redis | An in-memory database caching service. | [v0.31.2](../../middleware/redis/release-notes.md#v0312) |
| Container Registry | Used to store images for K8s, DevOps, and container application development. | [v0.26.0](../../kangaroo/intro/release-notes.md) |
| Networking | Supports multiple CNI combination solutions for different Linux kernels. | [v0.19.1](../../network/intro/release-notes.md) |
| Storage | Provides unified data storage services, supporting file, object, block, and local storage, easily integrating with storage vendor solutions. | [v1.1.1](../../storage/hwameistor/release-notes.md) |


## More

- [Online Docs](../../dce/index.md)
- [Report Bugs](https://github.com/DaoCloud/DaoCloud-docs/issues)
