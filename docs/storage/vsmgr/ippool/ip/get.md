---
sidebar_position: 1
---

# get

### 操作概述

查询主机在指定类型 IP 池中已分配的 IP

### 命令参数

```bash
--type=string                 必要参数，枚举=['OverVolume'] IP使用类型，目前仅支持OverVolume（卷超分VIP池）
--host=string                 必要参数，主机名，示例：host-0050568ec35e
```

### 使用示例

```bash
acli storage vsmgr ippool ip get --type <string> --host host-0050568ec35e
```

### 结果示例

IP 池未配置时命令执行失败。

```bash
192.168.1.100
```
