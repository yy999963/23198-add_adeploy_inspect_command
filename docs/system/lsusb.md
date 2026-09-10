---
sidebar_position: 1
---

# lsusb

### 操作概述

查询 USB 设备信息

### 命令参数

```bash
-v    显示设备详细信息
-s bus:devnum    按总线/设备号过滤
-d vendor:product    按厂商/产品 ID 过滤
-t    以树形结构显示设备
-V    显示版本信息
```

### 使用示例

```bash
acli system lsusb -v
```

### 结果示例

```bash
Bus 001 Device 001: ID 1d6b:0002 Linux Foundation 2.0 root hub
Bus 001 Device 002: ID 8087:0024 Intel Corp. Integrated Rate Matching Hub
```
