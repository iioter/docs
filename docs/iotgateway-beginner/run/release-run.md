---
sidebar_position: 0
title: 2.1.1 发行包运行
---

- 为了项目更健康长久的发展，从`1.0版本`开始区分`社区版(c)`和`企业版(e)`
- 作为开源网关，这个版本足够稳定，已经在多个项目生产落地
- 企业版会有更多特性，可以下载体验，也会逐步更新在社区版中

### 下载对应版本

| 版本       | Windows                                                      | Linux64                                                      | Arm64                                                        | Arm                                                          |
| ---------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| **企业版** | [下载Release-v1.0.3](https://gitee.com/iioter/iotgateway/releases/download/v1.0.1/iotgateway-e-v1.0.3-win-x86.zip) | [下载Release-v1.0.3](https://gitee.com/iioter/iotgateway/releases/download/v1.0.1/iotgateway-e-v1.0.3-linux-x64.zip) | [下载Release-v1.0.3](https://gitee.com/iioter/iotgateway/releases/download/v1.0.1/iotgateway-e-v1.0.3-linux-arm64.zip) | [下载Release-v1.0.3](https://gitee.com/iioter/iotgateway/releases/download/v1.0.1/iotgateway-e-v1.0.3-linux-arm.zip) |
| 社区版     | [下载Release-v1.0.1](https://gitee.com/iioter/iotgateway/releases/download/v1.0.1/iotgateway-c-v1.0.1-win-x86.zip) | [下载Release-v1.0.1](https://gitee.com/iioter/iotgateway/releases/download/v1.0.1/iotgateway-c-v1.0.1-linux-x64.zip) | [下载Release-v1.0.1](https://gitee.com/iioter/iotgateway/releases/download/v1.0.1/iotgateway-c-v1.0.1-linux-arm64.zip) | [下载Release-v1.0.1](https://gitee.com/iioter/iotgateway/releases/download/v1.0.1/iotgateway-c-v1.0.1-linux-arm.zip) |

### 发布记录
[详见：https://gitee.com/iioter/iotgateway/releases](https://gitee.com/iioter/iotgateway/releases)

### 运行

- #### windows

1. 解压
3. 管理员权限 运行IoTGateway.exe
4. Chrome访问518端口
- ### linux

1. 解压

```bash
sudo chmod 777 IoTGateway
sudo ./IoTGateway
```

2. 修改权限并运行
3. Chrome访问518端口