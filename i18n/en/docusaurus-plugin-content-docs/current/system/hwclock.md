---
sidebar_position: 1
---

# hwclock

### Overview

Get hardware clock time

### Command Parameters

```bash
-r / --show    Show hardware clock time (default behavior)
-c / --compare    Compare hardware clock with system clock
--verbose    Verbose output
--getepoch    Read RTC epoch
-rc and similar combined short options    Combined short options containing only r/c characters
```

### Usage Example

```bash
acli system hwclock -r
```

### Output Example

```bash
2026-09-09 10:07:03.992012+08:00
```
