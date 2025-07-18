<h1 align="center">APISIX Gateway</h1>
<p align="center">
    <strong>English</strong> | <a href="README_ZH.md">简体中文</a>
</p>

## Table of Contents

- [Repository Introduction](#project-introduction)
- [Prerequisites](#prerequisites)
- [Image Description](#image-description)
- [Get Help](#get-help)
- [How to Contribute](#how-to-contribute)

## Project Introduction

[apisix](https://github.com/apache/apisix) is a cloud-native API gateway with features such as dynamic, real-time, and high performance. This product provides an out-of-the-box apisix based on the Huawei Cloud EulerOS 2.0 64-bit system of Kunpeng servers.

## Core Features

- **Dynamic Configuration**: Supports hot-loading of configurations. You can update routing rules and plugin parameters without restarting the service, and configuration changes can take effect within milliseconds.
- **High Performance**: Adopts the RadixTree routing matching algorithm, with a single-core QPS of over 23,000 and extremely low latency.
- **Multi-platform Support**: Compatible with bare metal, Kubernetes, and cloud function environments (such as AWS Lambda and Azure Function).
- **Security Protection**: Built-in multiple authentication methods (such as JWT, search for [IP blacklist/whitelist]), and supports custom plugin development.

The open-source image product [**APISIX Gateway**](https://marketplace.huaweicloud.com/intl/contents/bfab1544-a53b-4b72-8616-577993465729) provided by this project has pre-installed the 3.12.0 version of apisix and its related runtime environment, and provides deployment templates. Come and refer to the usage guide to easily start an efficient "out-of-the-box" experience!

> **System requirements are as follows:**
> - CPU: 2 vCPUs or higher
> - RAM: 4GB or larger
> - Disk: At least 40GB

## Prerequisites

[Register a Huawei account and activate Huawei Cloud](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## Image Description

| Image Specification                                                                                                    | Feature Description | Remarks |
|------------------------------------------------------------------------------------------------------------------------| --- | --- |
| [apisix-3.12.0-kunpeng](https://github.com/HuaweiCloudDeveloper/apisix-image/tree/apisix-3.12.0-kunpeng) | Installed and deployed based on Kunpeng servers + Huawei Cloud EulerOS 2.0 64-bit |  |

## Get Help

- For more questions, you can contact us through [issues](https://github.com/HuaweiCloudDeveloper/apisix-image/issues) or the service support of the specified product in the Huawei Cloud Marketplace.
- For other open-source images, please refer to [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos).

## How to Contribute

- Fork this repository and submit a merge request.
- Synchronously update README.md based on your open-source image information.
