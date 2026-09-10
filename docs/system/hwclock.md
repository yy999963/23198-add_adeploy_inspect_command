---
sidebar_position: 1
---

# hwclock

### 操作概述

查询硬件时钟时间

### 命令参数

```bash
-r / --show    显示硬件时钟时间（默认行为）
-c / --compare    比较硬件时钟与系统时钟
--verbose    详细输出
--getepoch    读取 RTC epoch
-rc 等组合短选项    只含 r/c 字符的组合短选项
```

### 使用示例

```bash
acli system hwclock -r
```

### 结果示例

```bash
2026-09-09 10:07:03.992012+08:00
```
