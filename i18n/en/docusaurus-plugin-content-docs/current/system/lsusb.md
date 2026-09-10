---
sidebar_position: 1
---

# lsusb

### Overview

List USB devices

### Command Parameters

```bash
-v    Show detailed device information
-s bus:devnum    Filter by bus/device number
-d vendor:product    Filter by vendor/product ID
-t    Display devices as a tree
-V    Show version information
```

### Usage Example

```bash
acli system lsusb -v
```

### Output Example

```bash
Bus 001 Device 001: ID 1d6b:0002 Linux Foundation 2.0 root hub
Bus 001 Device 002: ID 8087:0024 Intel Corp. Integrated Rate Matching Hub
```
