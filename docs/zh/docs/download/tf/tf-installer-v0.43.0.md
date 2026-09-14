---
date: 2026-08-13
hide:
  - navigation
---

# d.run Token 工厂效能平台 v0.43.0

本页可下载 d.run Token 工厂效能平台的离线安装包和校验文件。

[返回下载导览页](../index.md#_2){ .md-button } [更多历史版本](./index.md){ .md-button }

## 下载

| 文件名称 | 版本 | 架构 | 文件大小 | 下载 | 更新日期 |
| ------- | --- | ---- | ------ | --- | ------- |
| offline-v0.43.0-amd64.tar | v0.43.0 | AMD 64 | 38.88 GB | [:arrow_down: 下载](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.43.0-amd64.tar) | 2026-08-13 |
| offline-v0.43.0-arm64.tar | v0.43.0 | <font color="green">ARM 64</font> | 35.41 GB | [:arrow_down: 下载](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.43.0-arm64.tar) | 2026-08-13 |

## 校验

进入离线安装包下载目录。

=== "AMD 64"

    执行以下命令校验安装包：

    ```sh
    echo "24378ae59ed136cf906c789be71d341c7f2e5ad747909036c9b768a812c8c7219194526036d0f71b14920743f3a5053298b421c570834414cc11db0315ee4979  offline-v0.43.0-amd64.tar" | sha512sum -c
    ```

    校验成功会打印：

    ```none
    offline-v0.43.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    执行以下命令校验安装包：

    ```sh
    echo "9880714eed9fd6eb3deff1cb162c56cd4a0ef33a82bc1ba7c0ac1c88dce17ec238734c57907f1a40e67015cf566a59d00505f48f7e2327dda7786661862591eb  offline-v0.43.0-arm64.tar" | sha512sum -c
    ```

    校验成功会打印：

    ```none
    offline-v0.43.0-arm64.tar: OK
    ```

## 安装

成功校验离线包之后，

=== "AMD 64"

    执行以下命令解压缩 tar 包：

    ```sh
    tar -zxvf offline-v0.43.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    执行以下命令解压缩 tar 包：

    ```sh
    tar -zxvf offline-v0.43.0-arm64.tar
    ```

- 安装请参阅[商业版安装流程](../../install/commercial/start-install.md)
- 成功安装之后请联系我们授权：电邮 info@daocloud.io 或致电 400 002 6898

## 模块

d.run Token 工厂效能平台包含以下模块，按需即插即用满足各类应用场景：

| 模块 | 介绍 | 最新动态 |
| ---- | --- | ------ |
| ClawOS | 多智能体运行和治理平台 | [v0.4.0](../../tf/clawos/workspace/index.md) |
| AI 应用 | 构造智能应用 | [v0.5.0](../../tf/dak/index.md) |
| 大模型服务平台 | 提供从模型部署到运维管理的全生命周期服务，帮助企业和开发者高效地接入和使用各类大模型能力 | [v0.17.1](../../insight/intro/release-notes.md#v0171) |
| InferX | 推理加速管理 | [v0.4.0](../../inferx/index.md) |
| 算力云 | 运营算力的平台 | [v0.17.0](../../tf/zestu/index.md) |
| 容器管理 | 管理集群、节点、工作负载、Helm 应用、CRD、命名空间等 K8s 核心功能 | [v0.49.0](../../kpanda/intro/release-notes.md#v0490) |
| 设备管理 | 面向智算中心打造的 Kubernetes 云原生基础设施管理组件，能够统一管理主机、交换机等硬件资源 | [v0.6.0](../../mspider/intro/release-notes.md#v060) |
| 镜像仓库 | 用于存储 K8s、DevOps 和容器应用开发的镜像 | [v0.26.0](../../kangaroo/intro/release-notes.md#v0260) |
| 云原生网络 | 针对不同的 Linux 内核，支持多种 CNI 组合方案 | [v0.19.0](../../network/intro/release-notes.md#v0190) |
| 云原生存储 | 提供统一数据存储服务，支持文件、对象、块、本地存储，轻松接入存储厂商方案 | [v1.1.1](../../storage/hwameistor/release-notes.md#v111) |
| 费用中心 | 费用和账单管理系统 | [v0.1.0](../../tf/leopard/index.md) |
| 全局管理 | 负责用户访问控制、权限、工作空间与层级、审计日志、个性化外观设置等 | [v0.48.1](../../ghippo/intro/release-notes.md#v0481) |
| 可观测性 | 提供丰富的仪表盘、场景监控、数据查询、告警等图文信息 | [v0.43.1](../../insight/intro/release-notes.md#v0431) |

## 更多

- [在线文档](../../index.md)
- [报告 bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
