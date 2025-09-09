---
MTPE: windsonsea
date: 2025-09-08
hide:
  - navigation
---

# DCE 5.0 Enterprise with Installer v0.33.0

This page provides downloads for the offline installation package and verification files for DCE 5.0 Enterprise.

[Return to Download Guide](../index.md#download-dce-50-enterprise){ .md-button } [More Version History](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| --------- | ------ | ------------ | ---- | -------- | ---- |
| offline-v0.33.0-amd64.tar | v0.33.0 | AMD 64 | 33.90 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.33.0-amd64.tar) | 2025-09-08 |
| offline-v0.33.0-arm64.tar | v0.33.0 | <font color="green">ARM 64</font> | 30.77 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.33.0-arm64.tar) | 2025-09-08 |

## Verification

Go to the offline installation package download directory.

=== "AMD 64"

    Run the following command to verify the installation package:

    ```sh
    echo "2625e28c2dbab5e8f1ba70a00b00121a1591d068d2145f35b6dec37894e42add32a3b6c83b25d9785fef798c9a85c0b6d7d49d3ae4309f50acd9f60d3ffa2b9a  offline-v0.33.0-amd64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-v0.33.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to verify the installation package:

    ```sh
    echo "73f21609af92149c71524bcf9fe53472e59431c69d6db3bc41d2525e81983599c5275b07fcf5e5dca41bb43f9a96d880b7ecc0713353cdc777439f4bf179800f  offline-v0.33.0-arm64.tar" | sha512sum -c
    ```

    If the verification is successful, the following will be printed:

    ```none
    offline-v0.33.0-arm64.tar: OK
    ```

## Installation

After successfully verifying the offline package,

=== "AMD 64"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-v0.33.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    Run the following command to decompress the tar package:

    ```sh
    tar -zxvf offline-v0.33.0-arm64.tar
    ```

- For installation instructions, refer to [Enterprise Installation Process](../../install/commercial/start-install.md)
- After successful installation, contact us for authorization: email info@daocloud.io or call 400 002 6898

## Modules

DCE 5.0 Enterprise includes the following modules, which can be used on-demand to meet various application scenarios:

| Modules | Description | Versions |
| ------- | ----------- | -------- |
| Global Management | Responsible for user access control, permissions, workspace and hierarchy, audit logs, and custom appearance. | [v0.41.0](../../ghippo/intro/release-notes.md#v0410) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRDs, namespaces, and more Kubernetes features. | [v0.42.1](../../kpanda/intro/release-notes.md#v0421) |
| Insight | Provides rich dashboards, scene monitoring, data querying, and alert information. | [v0.38.1](../../insight/intro/release-notes.md#v0381) |
| Workbench | A container-based DevOps application platform that supports Jenkins, Tekton, GitOps, and other pipeline jobs. | [v0.38.0](../../amamba/intro/release-notes.md#v0380) |
| MultiCloud Management | Centralized management of multicloud, hybrid cloud, and cross-cloud resources for application orchestration, with capabilities such as multicloud disaster recovery and fault recovery. | [v0.24.0](../../kairship/intro/release-notes.md#v0240) |
| Microservice Engine | Provides governance capabilities such as service registration, discovery, configuration management, and microservice gateway. | [v0.48.0](../../skoala/intro/release-notes.md#v0480) |
| Service Mesh | Next-generation service mesh built on Istio open-source technology for cloud-native applications. | [v0.36.0](../../mspider/intro/release-notes.md#v0360) |
| Middleware Elasticsearch | Currently the preferred full-text search engine. | [v0.25.0](../../middleware/elasticsearch/release-notes.md#v0250) |
| Middleware Kafka | Distributed message queue service based on the open-source software Kafka. | [v0.25.0](../../middleware/kafka/release-notes.md#v0250) |
| Middleware MinIO | A lightweight, open-source object storage solution that is very popular. | [v0.21.1](../../middleware/minio/release-notes.md#v0211) |
| Middleware MySQL | The most widely used open-source relational database. | [v0.27.0](../../middleware/mysql/release-notes.md#v0270) |
| Middleware RabbitMQ | Open-source message broker software that implements the Advanced Message Queuing Protocol (AMQP). | [v0.27.3](../../middleware/rabbitmq/release-notes.md#v0273) |
| Middleware Redis | An in-memory database caching service. | [v0.28.0](../../middleware/redis/release-notes.md#v0280) |
| Container Registry | Used to store images for K8s, DevOps, and container application development. | [v0.24.1](../../kangaroo/intro/release-notes.md#v0240) |
| Networking | Supports multiple CNI combination solutions for different Linux kernels. | [v0.16.4](../../network/intro/release-notes.md#v0164) |
| Storage | Provides unified data storage services, supporting file, object, block, and local storage, easily integrating with storage vendor solutions. | [v0.16.4](../../storage/hwameistor/release-notes.md#v0164) |
| AI Lab | Integrates heterogeneous compute resources, optimizes GPU performance, and enables unified scheduling and operation. | [v0.20.2](../../baize/intro/release-notes#v0202) |
| LLM Studio | Provides end-to-end lifecycle services from model deployment to operation and maintenance, helping enterprises and developers efficiently integrate and use various large model capabilities | [v0.9.0](../../insight/intro/release-notes.md#v090) |
| Cloud Edge Collaboration | Extends cloud native capabilities to the edge. Uses an edge node model to offload data processing, business applications, and AI models to the edge. | [v0.20.0](../../kant/intro/release-notes#v0200) |

## More

- [Online Documentation](../../dce/index.md)
- [Report a Bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
