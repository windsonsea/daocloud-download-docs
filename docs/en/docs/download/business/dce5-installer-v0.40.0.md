---
MTPE: windsonsea
date: 2026-05-15
hide:
  - navigation
---

# DCE 5.0 Enterprise with Installer v0.40.0

This page provides offline installation packages and checksum files for DCE 5.0 Enterprise edition.

[Return to Download Index](../index.md#download-dce-50-enterprise){ .md-button } [More Historical Versions](./dce5-installer-history.md){ .md-button }

## Download

| Filename | Version | Architecture | Size | Download | Date |
| -------- | ------- | ------------ | ---- | -------- | ---- |
| offline-v0.40.0-amd64.tar | v0.40.0 | AMD64 | 35.06 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.40.0-amd64.tar) | 2026-05-15 |
| offline-v0.40.0-arm64.tar | v0.40.0 | <font color="green">ARM64</font> | 31.66 GB | [:arrow_down: Download](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.40.0-arm64.tar) | 2026-05-15 |

## Verification

Go to the directory where the offline package is downloaded.

=== "AMD64"

    Run the following command to verify the package:

    ```sh
    echo "ce970ee13c534fdebdbaa610087f026d865586a4641bef36cf391321b1d0542ffda89b6b88424d33edc9bc84a712e3d05abf9eabe5ea9309c31236a82cecdc91  offline-v0.40.0-amd64.tar" | sha512sum -c
    ```

    If successful, it will print:

    ```none
    offline-v0.40.0-amd64.tar: OK
    ```

=== "<font color="green">ARM64</font>"

    Run the following command to verify the package:

    ```sh
    echo "d9c44b69c25bc5e26f4b722bfb6c1d274c7f707edb31af6fbd2e2427c51299a4c6379daa847bf551927117fca15ab0ed4dde14bea81845272bd09476fa087227  offline-v0.40.0-arm64.tar" | sha512sum -c
    ```

    If successful, it will print:

    ```none
    offline-v0.40.0-arm64.tar: OK
    ```

## Installation

After successful verification,

=== "AMD64"

    Extract the tar package:

    ```sh
    tar -xvf offline-v0.40.0-amd64.tar
    ```

=== "<font color="green">ARM64</font>"

    Extract the tar package:

    ```sh
    tar -xvf offline-v0.40.0-arm64.tar
    ```

- Please refer to [Enterprise Installation Guide](../../install/commercial/start-install.md)
- After successful installation, please contact us for authorization: email info@daocloud.io or call 400 002 6898

## Modules

DCE 5.0 Enterprise includes the following modules, plug-and-play as needed to meet various application scenarios:

| Module | Introduction | Latest Update |
|--------|--------------|---------------|
| Global Management | Responsible for user access control, permissions, workspaces and hierarchies, audit logs, personalized appearance settings, etc. | [v0.46.0](../../ghippo/intro/release-notes.md#v0460) |
| Container Management | Manages clusters, nodes, workloads, Helm applications, CRD, namespaces and other K8s core features | [v0.46.1](../../kpanda/intro/release-notes.md#v0461) |
| Observability | Provides rich dashboards, scene monitoring, data queries, alerts and other graphical information | [v0.41.2](../../insight/intro/release-notes.md#v0412) |
| LLM Studio | Provides full lifecycle services from model deployment to O&M management, helping enterprises and developers efficiently access and use various LLM capabilities | [v0.14.0](../../insight/intro/release-notes.md#v0140) |
| AI Lab | Training and inference integration platform, unified scheduling of computing resources, simplifies AI application development and deployment | [v0.26.0](../../insight/intro/release-notes.md#v0260) |
| Workbench | Container-based DevOps application platform, supports Jenkins, Tekton, GitOps and other pipeline jobs | [v0.40.1](../../amamba/intro/release-notes.md#v0401) |
| Multi-Cloud Orchestration | Centralized management of multi-cloud, hybrid cloud, cross-cloud resource application orchestration, with multi-cloud disaster recovery and fault recovery capabilities | [v0.24.0](../../kairship/intro/release-notes.md#v0240) |
| Microservice Engine | Provides service governance, configuration management, microservice gateway and other governance capabilities | [v0.55.0](../../skoala/intro/release-notes.md#v0550) |
| Service Mesh | Next-generation service mesh for cloud-native applications based on open-source Istio technology | [v0.39.0](../../mspider/intro/release-notes.md#v0390) |
| Cloud-Edge Collaboration | Extends cloud-native capabilities to the edge, using edge node mode to push data processing, business applications, AI models, etc. to the edge for execution | [v0.22.0](../../mspider/intro/release-notes.md#v0220) |
| Device Management | Kubernetes cloud-native infrastructure management component for intelligent computing centers, can uniformly manage hosts, switches and other hardware resources | [v0.6.0](../../mspider/intro/release-notes.md#v060) |
| Middleware Elasticsearch | The preferred full-text search engine | [v0.28.0](../../middleware/elasticsearch/release-notes.md#v0280) |
| Middleware Kafka | Distributed message queue service based on open-source Kafka | [v0.30.0](../../middleware/kafka/release-notes.md#v0300) |
| Middleware MinIO | A very popular lightweight, open-source object storage solution | [v0.25.0](../../middleware/minio/release-notes.md#v0250) |
| Middleware MySQL | The most widely used open-source relational database | [v0.30.1](../../middleware/mysql/release-notes.md#v0301) |
| Middleware RabbitMQ | Open-source message broker software implementing Advanced Message Queuing Protocol (AMQP) | [v0.32.0](../../middleware/rabbitmq/release-notes.md#v0310) |
| Middleware Redis | An in-memory database caching service | [v0.31.0](../../middleware/redis/release-notes.md#v0300) |
| Image Repository | Used for storing images for K8s, DevOps and container application development | [v0.24.1](../../kangaroo/intro/release-notes.md#v0241) |
| Network | Supports multiple CNI combination schemes for different Linux kernels | [v0.16.6](../../network/intro/release-notes.md#v0166) |
| Storage | Provides unified data storage services, supports file, object, block, and local storage, easily integrates storage vendor solutions | [v1.0.2](../../storage/hwameistor/release-notes.md#v102) |

## More

- [Online Documentation](../../dce/index.md)
- [Report Bugs](https://github.com/DaoCloud/DaoCloud-docs/issues)
