---
MTPE: windsonsea
date: 2025-04-11
hide:
  - navigation
---

# DCE 5.0 Enterprise with Installer v0.28.0

This page provides downloads for the offline installation package and verification files for DCE 5.0 Enterprise.

[Return to Download Guide](../index.md#download-dce-50-enterprise){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| --------- | ------ | ------------ | ---- | -------- | ---- |
| offline-v0.28.0-amd64.tar | v0.28.0 | AMD 64 | 29.27 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.28.0-amd64.tar) | 2025-04-11 |
| offline-v0.28.0-arm64.tar | v0.28.0 | <font color="green">ARM 64</font> | 26.01 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.28.0-arm64.tar) | 2025-04-11 |

## Verification

Go to the offline installation package download directory.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "1dcdb7ec775610e7f0bdade37284533949163fd7d1f377e3f4fcb03e1f42391576fe6afbab928ded6368899c7d4d94e9e6d3dd4e5ab0c9a17750be676b2bd7fa  offline-v0.28.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-v0.28.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "da12128060633d08313ee1edb2738aa9637b12707c4ff0a6500670202747ed765fb513124ba826a19427adcf1f78103afa124de59ee91c00f6c869cb7876b10a  offline-v0.28.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-v0.28.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-v0.28.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-v0.28.0-arm64.tar
    ```

- For installation instructions, refer to [Enterprise Installation Process](../../install/commercial/start-install.md)
- After successful installation, contact us for authorization: email info@daocloud.io or call 400 002 6898

## Modules

DCE 5.0 Enterprise includes the following modules, which can be used on-demand to meet various application scenarios:

| Modules | Description | Versions |
| ------- | ----------- | -------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [0.35.0](../../ghippo/intro/release-notes.md#v0350) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [0.37.0](../../kpanda/intro/release-notes.md#v0370) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [0.35.1](../../insight/intro/release-notes.md#v0351) |
| Workbench | A container-based DevOps application platform that supports Jenkins, Tekton, GitOps, and other pipeline jobs. | [0.35.0](../../amamba/intro/release-notes.md#v0350) |
| MultiCloud Management | Centralized management of multicloud, hybrid cloud, and cross-cloud resources for application orchestration, with capabilities such as multicloud disaster recovery and fault recovery. | [0.24.0](../../kairship/intro/release-notes.md#v0240) |
| Microservice Engine | Provides governance capabilities such as service registration, discovery, configuration management, and microservice gateway. | [0.45.0](../../skoala/intro/release-notes.md#v0450) |
| Service Mesh | Next-generation service mesh built on Istio open-source technology for cloud-native applications. | [v0.34.1](../../mspider/intro/release-notes.md#v0341) |
| Middleware Elasticsearch | Currently the preferred full-text search engine. | [0.24.0](../../middleware/elasticsearch/release-notes.md#v0240) |
| Middleware Kafka | Distributed message queue service based on the open-source software Kafka. | [0.23.0](../../middleware/kafka/release-notes.md#v0230) |
| Middleware MinIO | A lightweight, open-source object storage solution that is very popular. | [0.21.0](../../middleware/minio/release-notes.md#v0210) |
| Middleware MySQL | The most widely used open-source relational database. | [0.26.0](../../middleware/mysql/release-notes.md#v0260) |
| Middleware RabbitMQ | Open-source message broker software that implements the Advanced Message Queuing Protocol (AMQP). | [0.27.0](../../middleware/rabbitmq/release-notes.md#v0270) |
| Middleware Redis | An in-memory database caching service. | [0.27.0](../../middleware/redis/release-notes.md#v0270) |
| Container Regisry | Used to store images for K8s, DevOps, and container application development. | [0.24.0](../../kangaroo/intro/release-notes.md#v0240) |
| Networking | Supports multiple CNI combination solutions for different Linux kernels. | [0.16.2](../../network/intro/release-notes.md#v0162) |
| Storage | Provides unified data storage services, supporting file, object, block, and local storage, easily integrating with storage vendor solutions. | [v0.16.2](../../storage/hwameistor/release-notes.md#v0162) |

## More

- [Online Documentation](../../dce/index.md)
- [Report a Bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
