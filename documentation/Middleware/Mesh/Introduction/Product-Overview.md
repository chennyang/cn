# 产品概述
京东云网格（Mesh），是京东云上的服务治理的工具，是Service Mesh在京东云平台上的具体实现。它依托于京东云Kubernetes集群，为应用提供了基础设施层，以Sidecar模式与微服务应用一起运行，适用所有云原生应用。目前尚不支持自建K8S的治理。

-  与开发语言和框架无关
-  业务开发者不用深入研究服务治理的实现
-  业务模块与服务治理解耦
-  服务治理功能升级、独立于业务模块升级
-  运行时动态调整各种规则和策略

![](../../../../image/Internet-Middleware/JD-Distributed-Service-Framework/struct-sidecar.png)

