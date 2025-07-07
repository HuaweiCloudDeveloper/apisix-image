 <h1 align="center">APISIX网关</h1>
  <p align="center">
    <a href="README.md"><strong>English</strong></a> | <strong>简体中文</strong>
  </p>


## 目录

- [仓库简介](#项目介绍)
- [前置条件](#前置条件)
- [镜像说明](#镜像说明)
- [获取帮助](#获取帮助)
- [如何贡献](#如何贡献)

## 项目介绍

[apisix](https://github.com/apache/apisix)  是一个具有动态、实时、高性能等特点的云原生 API 网关‌。本商品基于鲲鹏服务器的Huawei Cloud EulerOS 2.0 64bit系统，提供开箱即用的apisix。

## 核心特性

- **‌动态配置‌：** 支持热加载配置，无需重启服务即可更新路由规则和插件参数，配置变更可实现毫秒级生效 
- **‌高性能‌：** 采用 RadixTree 路由匹配算法，单核QPS可达23000以上，延迟极低 
- **‌多平台支持‌：** 适配裸机、 Kubernetes 及云函数环境（如 AWS Lambda 、 Azure Function ） 
- **‌安全防护‌：** 内置多种认证方式（如 JWT 、 搜索【IP黑白名单】），支持自定义插件开发 

本项目提供的开源镜像商品 [**APISIX网关**](https://marketplace.huaweicloud.com/contents/ab5930b5-64ce-4bfd-88bc-325f38b18fcc#productid=OFFI1136589009567784960) 已预先安装3.12.0版本的apisix及其相关运行环境，并提供部署模板。快来参照使用指南，轻松开启“开箱即用”的高效体验吧。


> **系统要求如下：**
> - CPU: 2vCPUs 或更高
> - RAM: 4GB 或更大
> - Disk: 至少 40GB

## 前置条件
[注册华为账号并开通华为云](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## 镜像说明

| 镜像规格                                                                                                    | 特性说明 | 备注 |
|---------------------------------------------------------------------------------------------------------| --- | --- |
| [apisix-3.12.0-kunpeng](https://github.com/HuaweiCloudDeveloper/apisix-image/tree/apisix-3.12.0-kunpeng) | 基于鲲鹏服务器 + Huawei Cloud EulerOS 2.0 64bit 安装部署 |  |

## 获取帮助
- 更多问题可通过 [issue](https://github.com/HuaweiCloudDeveloper/apisix-image/issues) 或 华为云云商店指定商品的服务支持 与我们取得联系
- 其他开源镜像可看 [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos)

## 如何贡献
- Fork 此存储库并提交合并请求
- 基于您的开源镜像信息同步更新 README.md