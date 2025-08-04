---
date: 2025-04-11
hide:
  - navigation
---

# DCE 5.0 社区版 v0.27.1

本页可下载 DCE 5.0 社区版的离线安装包和校验文件。

[返回下载导览页](../index.md){ .md-button } [更多历史版本](./dce5-installer-history.md){ .md-button }

## 下载

| 文件名称 | 版本 | 架构 | 文件大小 | 下载 | 更新日期 |
| ------- | --- | ---- | ------ | --- | ------- |
| offline-community-v0.27.1-amd64.tar | v0.27.1 | AMD 64 | 9.50 GB | [:arrow_down: 下载](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.27.1-amd64.tar) | 2025-04-11 |
| offline-community-v0.27.1-arm64.tar | v0.27.1 | <font color="green">ARM 64</font> | 8.99 GB | [:arrow_down: 下载](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.27.1-arm64.tar) | 2025-04-11 |

## 校验

进入离线安装包下载目录。

=== "AMD 64"

    执行以下命令校验安装包：

    ```sh
    echo "c48356ee72102cb4ce821f9da6ee26db19672d88e87e681a2eb396957ab52c59206041ca25284bd3bb0c56058b93dac1ef5f1d8dfda316db45918b2ecb0975f5  offline-community-v0.27.1-amd64.tar" | sha512sum -c
    ```

    校验成功会打印：

    ```none
    offline-community-v0.27.1-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    执行以下命令校验安装包：

    ```sh
    echo "c55fe39fb564899337ea9535ee51f285f525432025780c5bd4ce82640196d821c8a8c16ba1e54c193a20798f6d1d3b449347c149dfab0b2dbf00d45e06b8ef28  offline-community-v0.27.1-arm64.tar" | sha512sum -c
    ```

    校验成功会打印：

    ```none
    offline-community-v0.27.1-arm64.tar: OK
    ```

## 安装

成功校验离线包之后，

=== "AMD 64"

    执行以下命令解压缩 tar 包：

    ```sh
    tar -zxvf offline-community-v0.27.1-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    执行以下命令解压缩 tar 包：

    ```sh
    tar -zxvf offline-community-v0.27.1-arm64.tar
    ```

- 安装请参阅[社区版安装流程](../../install/community/k8s/online.md#_2)
- 成功安装之后请[申请免费社区体验](../../dce/license0.md)

## 模块

DCE 5.0 社区版默认包含以下模块：

| 模块     | 介绍            | 最新动态         |
| -------- | -------------- | -------------- |
| 全局管理 | 负责用户访问控制、权限、工作空间与层级、审计日志、个性化外观设置等 | [v0.35.0](../../ghippo/intro/release-notes.md#v0350) |
| 容器管理 | 管理集群、节点、工作负载、Helm 应用、CRD、命名空间等 K8s 核心功能 | [v0.37.0](../../kpanda/intro/release-notes.md#v0370) |
| 可观测性 | 提供丰富的仪表盘、场景监控、数据查询、告警等图文信息 | [v0.35.1](../../insight/intro/release-notes.md#v0351) |

## 更多

- [在线文档](../../dce/index.md)
- [报告 bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
