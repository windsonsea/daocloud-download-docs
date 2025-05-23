---
date: 2025-02-13
hide:
  - navigation
---

# DCE 5.0 社区版 v0.26.0

本页可下载 DCE 5.0 社区版的离线安装包和校验文件。

[返回下载导览页](../index.md){ .md-button } [更多历史版本](./dce5-installer-history.md){ .md-button }

## 下载

| 文件名称 | 版本 | 架构 | 文件大小 | 下载 | 更新日期 |
| ------- | --- | ---- | ------ | --- | ------- |
| offline-community-v0.26.0-amd64.tar | v0.26.0 | AMD 64 | 8.57 GB | [:arrow_down: 下载](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.26.0-amd64.tar) | 2025-02-13 |
| offline-community-v0.26.0-arm64.tar | v0.26.0 | <font color="green">ARM 64</font> | 8.21 GB | [:arrow_down: 下载](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.26.0-arm64.tar) | 2025-02-13 |

## 校验

进入离线安装包下载目录。

=== "AMD 64"

    执行以下命令校验安装包：

    ```sh
    echo "b32454b25963729bbc297b6ea20519deedc2ac8c750f43d7d373b1b0248b7f485d19261a3c8b6f760f3433ef67805a4d1f16460b389a2fbce1c89b300cd88ea0  offline-community-v0.26.0-amd64.tar" | sha512sum -c
    ```

    校验成功会打印：

    ```none
    offline-community-v0.26.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    执行以下命令校验安装包：

    ```sh
    echo "f1adf2d9cfe767e3a2b3e5438fb61dbdbbd1d980a00d58b1b15a592ba6ee4462c57c29bd5c113d9fcbd7e6032b18d221cc348f68bd11bc437bd39df06d6a166f  offline-community-v0.26.0-arm64.tar" | sha512sum -c
    ```

    校验成功会打印：

    ```none
    offline-community-v0.26.0-arm64.tar: OK
    ```

## 安装

成功校验离线包之后，

=== "AMD 64"

    执行以下命令解压缩 tar 包：

    ```sh
    tar -zxvf offline-community-v0.26.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    执行以下命令解压缩 tar 包：

    ```sh
    tar -zxvf offline-community-v0.26.0-arm64.tar
    ```

- 安装请参阅[社区版安装流程](../../install/community/k8s/online.md#_2)
- 成功安装之后请[申请免费社区体验](../../dce/license0.md)

## 模块

DCE 5.0 社区版默认包含以下模块：

| 模块     | 介绍            | 最新动态         |
| -------- | -------------- | -------------- |
| 全局管理 | 负责用户访问控制、权限、工作空间与层级、审计日志、个性化外观设置等 | [v0.34.0](../../ghippo/intro/release-notes.md#v0340) |
| 容器管理 | 管理集群、节点、工作负载、Helm 应用、CRD、命名空间等 K8s 核心功能 | [v0.36.0](../../kpanda/intro/release-notes.md#v0360) |
| 可观测性 | 提供丰富的仪表盘、场景监控、数据查询、告警等图文信息 | [v0.34.1](../../insight/intro/release-notes.md#v0341) |

## 更多

- [在线文档](../../dce/index.md)
- [报告 bug](https://github.com/DaoCloud/DaoCloud-docs/issues)