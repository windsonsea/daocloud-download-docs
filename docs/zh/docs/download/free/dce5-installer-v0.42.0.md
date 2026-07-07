---
date: 2026-07-07
hide:
  - navigation
---

# DCE 5.0 社区版 v0.42.0

本页可下载 DCE 5.0 社区版的离线安装包和校验文件。

[返回下载导览页](../index.md){ .md-button } [更多历史版本](./dce5-installer-history.md){ .md-button }

## 下载

| 文件名称 | 版本 | 架构 | 文件大小 | 下载 | 更新日期 |
| ------- | --- | ---- | ------ | --- | ------- |
| offline-community-v0.42.0-amd64.tar | v0.42.0 | AMD 64 | 14.21 GB | [:arrow_down: 下载](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.42.0-amd64.tar) | 2026-07-07 |
| offline-community-v0.42.0-arm64.tar | v0.42.0 | <font color="green">ARM 64</font> | 12.73 GB | [:arrow_down: 下载](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.42.0-arm64.tar) | 2026-07-07 |

## 校验

进入离线安装包下载目录。

=== "AMD 64"

    执行以下命令校验安装包：

    ```sh
    echo "53af1f5fb6258d74977ab34e645c95701326710a187d48251e3866a91975623edd8f1fc823a1ea63efc19d372bf4bbe1e95b443e2ddadba05847b76dcb63ffe8  offline-community-v0.42.0-amd64.tar" | sha512sum -c
    ```

    校验成功会打印：

    ```none
    offline-community-v0.42.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    执行以下命令校验安装包：

    ```sh
    echo "69a9e3a81a0dff0674afd83dcf67c4cb27f05a280d8336ce4165143fa545dbf2e1a047ae3ab6191bccb9888c4e557e777dc28d260c2ce5b7961d96bd80612b8f  offline-community-v0.42.0-arm64.tar" | sha512sum -c
    ```

    校验成功会打印：

    ```none
    offline-community-v0.42.0-arm64.tar: OK
    ```

## 安装

成功校验离线包之后，

=== "AMD 64"

    执行以下命令解压缩 tar 包：

    ```sh
    tar -xvf offline-community-v0.42.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    执行以下命令解压缩 tar 包：

    ```sh
    tar -xvf offline-community-v0.42.0-arm64.tar
    ```

- 安装请参阅[社区版安装流程](../../install/community/k8s/online.md#_2)
- 成功安装之后请[申请免费社区体验](../../dce/license0.md)

## 模块

DCE 5.0 社区版默认包含以下模块：

| 模块     | 介绍            | 最新动态         |
| -------- | -------------- | -------------- |
| 全局管理 | 负责用户访问控制、权限、工作空间与层级、审计日志、个性化外观设置等 | [v0.48.0](../../ghippo/intro/release-notes.md#v0480) |
| 容器管理 | 管理集群、节点、工作负载、Helm 应用、CRD、命名空间等 K8s 核心功能 | [v0.48.1](../../kpanda/intro/release-notes.md#v0481) |
| 可观测性 | 提供丰富的仪表盘、场景监控、数据查询、告警等图文信息 | [v0.42.2](../../insight/intro/release-notes.md#v0422) |

## 更多

- [在线文档](../../dce/index.md)
- [报告 bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
