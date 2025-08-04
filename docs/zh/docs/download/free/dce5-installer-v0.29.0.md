---
date: 2025-05-14
hide:
  - navigation
---

# DCE 5.0 社区版 v0.29.0

本页可下载 DCE 5.0 社区版的离线安装包和校验文件。

[返回下载导览页](../index.md){ .md-button } [更多历史版本](./dce5-installer-history.md){ .md-button }

## 下载

| 文件名称 | 版本 | 架构 | 文件大小 | 下载 | 更新日期 |
| ------- | --- | ---- | ------ | --- | ------- |
| offline-community-v0.29.0-amd64.tar | v0.29.0 | AMD 64 | 9.54GB | [:arrow_down: 下载](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.29.0-amd64.tar) | 2025-05-14 |
| offline-community-v0.29.0-arm64.tar | v0.29.0 | <font color="green">ARM 64</font> | 9.02GB | [:arrow_down: 下载](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-community-v0.29.0-arm64.tar) | 2025-05-14 |

## 校验

进入离线安装包下载目录。

=== "AMD 64"

    执行以下命令校验安装包：

    ```sh
    echo "7956a3e72fbe2bf95bc800a2b640849d277f854eeba4256aef50c083e1f9d43583583612182fc60e688d39eeb560bb54d1842ddcf281aaeb3831d8ac9e0a8ab6  offline-community-v0.29.0-amd64.tar" | sha512sum -c
    ```

    校验成功会打印：

    ```none
    offline-community-v0.29.0-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    执行以下命令校验安装包：

    ```sh
    echo "32d7aafc7ad6b8052561b613d2338e6c17e2fd0840258d6d1882646cf2ba3094b0b57e27a637e9836e87385d1ffad6c3b2c18f5fe9180a13f26e3d4c8d2390d0  offline-community-v0.29.0-arm64.tar" | sha512sum -c
    ```

    校验成功会打印：

    ```none
    offline-community-v0.29.0-arm64.tar: OK
    ```

## 安装

成功校验离线包之后，

=== "AMD 64"

    执行以下命令解压缩 tar 包：

    ```sh
    tar -zxvf offline-community-v0.29.0-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    执行以下命令解压缩 tar 包：

    ```sh
    tar -zxvf offline-community-v0.29.0-arm64.tar
    ```

- 安装请参阅[社区版安装流程](../../install/community/k8s/online.md#_2)
- 成功安装之后请[申请免费社区体验](../../dce/license0.md)

## 模块

DCE 5.0 社区版默认包含以下模块：

| 模块     | 介绍            | 最新动态         |
| -------- | -------------- | -------------- |
| 全局管理 | 负责用户访问控制、权限、工作空间与层级、审计日志、个性化外观设置等 | [v0.36.0](../../ghippo/intro/release-notes.md#v0360) |
| 容器管理 | 管理集群、节点、工作负载、Helm 应用、CRD、命名空间等 K8s 核心功能 | [v0.39.0](../../kpanda/intro/release-notes.md#v0390) |
| 可观测性 | 提供丰富的仪表盘、场景监控、数据查询、告警等图文信息 | [v0.36.1](../../insight/intro/release-notes.md#v0361) |

## 更多

- [在线文档](../../dce/index.md)
- [报告 bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
