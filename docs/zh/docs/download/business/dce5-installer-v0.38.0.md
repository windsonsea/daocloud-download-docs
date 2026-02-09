---
date: 2026-02-09
hide:
  - navigation
---

# DCE 5.0 商业版 v0.38.0

本页可下载 DCE 5.0 商业版的离线安装包和校验文件。

[返回下载导览页](../index.md#_2){ .md-button } [更多历史版本](./dce5-installer-history.md){ .md-button }

## 下载

| 文件名称 | 版本 | 架构 | 文件大小 | 下载 | 更新日期 |
| ------- | --- | ---- | ------ | --- | ------- |
| offline-v0.38.0-amd64.tar | v0.38.0 | AMD 64 | 34.98 GB | [:arrow_down: 下载](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.38.0-amd64.tar) | 2026-02-09 |
| offline-v0.38.0-arm64.tar | v0.38.0 | <font color="green">ARM 64</font> | 31.66 GB | [:arrow_down: 下载](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.38.0-arm64.tar) | 2026-02-09 |

## 校验

进入离线安装包下载目录。

=== "AMD 64"

    执行以下命令校验安装包：

    ```sh
    echo "0306ae42705919f19ab656fda806c9d1c3d93d46e3497c18dc8273ea9d59d9b391e00ae5cc385b75023f0ea1b8549f9d1cdd12e25ba2f23338c9855b9d15304e  offline-v0.38.0-amd64.tar" | sha512sum -c
    ```

    校验成功会打印：

    ```none
    offline-v0.38.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    执行以下命令校验安装包：

    ```sh
    echo "3d4dae43a7f3cc4eb34f62909f0952c03e5503026600ac0a5e5b14570cbbba52893e28447f32622c0ecd3bd9325f21b4f5d0b76a8b4a723b59cd0baaf235fdf2  offline-v0.38.0-arm64.tar" | sha512sum -c
    ```

    校验成功会打印：

    ```none
    offline-v0.38.0-arm64.tar: OK
    ```

## 安装

成功校验离线包之后，

=== "AMD 64"

    执行以下命令解压缩 tar 包：

    ```sh
    tar -zxvf offline-v0.38.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    执行以下命令解压缩 tar 包：

    ```sh
    tar -zxvf offline-v0.38.0-arm64.tar
    ```

- 安装请参阅[商业版安装流程](../../install/commercial/start-install.md)
- 成功安装之后请联系我们授权：电邮 info@daocloud.io 或致电 400 002 6898

## 模块

DCE 5.0 商业版包含以下模块，按需即插即用满足各类应用场景：

| 模块 | 介绍 | 最新动态 |
| ---- | --- | ------ |
| 全局管理 | 负责用户访问控制、权限、工作空间与层级、审计日志、个性化外观设置等 | [v0.44.0](../../ghippo/intro/release-notes.md#v0440) |
| 容器管理 | 管理集群、节点、工作负载、Helm 应用、CRD、命名空间等 K8s 核心功能 | [v0.45.0](../../kpanda/intro/release-notes.md#v0450) |
| 可观测性 | 提供丰富的仪表盘、场景监控、数据查询、告警等图文信息 | [v0.40.1](../../insight/intro/release-notes.md#v0401) |
| 大模型服务平台 | 提供从模型部署到运维管理的全生命周期服务，帮助企业和开发者高效地接入和使用各类大模型能力 | [v0.12.1](../../insight/intro/release-notes.md#v0121) |
| AI Lab | 训推一体化平台，算力资源统一调度，简化 AI 应用开发和部署 | [v0.24.1](../../insight/intro/release-notes.md#v0241) |
| 应用工作台 | 基于容器的 DevOps 应用平台，支持 Jenkins, Tekton, GitOps 等流水线作业 | [v0.39.2](../../amamba/intro/release-notes.md#v0392) |
| 多云编排 | 集中管理多云、混合云、跨云资源的应用编排，具备多云灾备、故障恢复等能力 | [v0.24.0](../../kairship/intro/release-notes.md#v0240) |
| 微服务引擎 | 提供注册发现、服务治理、配置管理、微服务网关等治理能力 | [v0.53.0](../../skoala/intro/release-notes.md#v0530) |
| 服务网格 | 基于 Istio 开源技术构建的面向云原生应用的下一代服务网格 | [v0.38.0](../../mspider/intro/release-notes.md#v0380) |
| 云边协同 | 将云原生能力延伸至边缘，采用边缘节点模式，将数据处理、业务应用、AI模型等下沉到边缘端执行 | [v0.22.0](../../mspider/intro/release-notes.md#v0220) |
| 设备管理 | 面向智算中心打造的 Kubernetes 云原生基础设施管理组件，能够统一管理主机、交换机等硬件资源 | [v0.6.0](../../mspider/intro/release-notes.md#v060) |
| 中间件 Elasticsearch | 目前首选的全文搜索引擎 | [v0.26.1](../../middleware/elasticsearch/release-notes.md#v0261) |
| 中间件 Kafka | 基于开源软件 Kafka 提供的分布式消息队列服务 | [v0.28.0](../../middleware/kafka/release-notes.md#v0280) |
| 中间件 MinIO | 一款非常热门的轻量、开源对象存储方案 | [v0.23.1](../../middleware/minio/release-notes.md#v0231) |
| 中间件 MySQL | 应用最广泛的开源关系数据库 | [v0.28.2](../../middleware/mysql/release-notes.md#v0282) |
| 中间件 RabbitMQ | 实现了高级消息队列协议 (AMQP) 的开源消息代理软件 | [v0.30.0](../../middleware/rabbitmq/release-notes.md#v0300) |
| 中间件 Redis | 一款内存数据库缓存服务 | [v0.29.2](../../middleware/redis/release-notes.md#v0292) |
| 镜像仓库 | 用于存储 K8s、DevOps 和容器应用开发的镜像 | [v0.24.1](../../kangaroo/intro/release-notes.md#v0241) |
| 网络 | 针对不同的 Linux 内核，支持多种 CNI 组合方案 | [v0.16.6](../../network/intro/release-notes.md#v0166) |
| 存储 | 提供统一数据存储服务，支持文件、对象、块、本地存储，轻松接入存储厂商方案 | [v1.0.2](../../storage/hwameistor/release-notes.md#v102) |

## 更多

- [在线文档](../../dce/index.md)
- [报告 bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
