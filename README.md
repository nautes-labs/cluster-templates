# Cluster Templates

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![version](https://img.shields.io/badge/version-v0.3.0-green)]()

Cluster Templates 提供了向租户管理集群注册运行时集群时所需的一组模板文件，支持的集群类型包括：宿主集群、物理运行时集群、虚拟运行时集群。

## 功能简介

Cluster Templates 包含以下内容：

- host-clusters 目录：包含宿主集群的部署模板以及宿主集群下虚拟集群的部署模板。
- nautes 目录：包含用于声明集群的 `Cluster` 资源的模板。
- runtimes 目录：包含运行时集群的部署模板。
- tenant 目录：包含定义宿主机群和运行时集群的 ArgoCD ApplicationSet 的模板。
- clusterignorerule.yaml 文件：描述如何通过模板生成文件实例的规则文件。
