# SysWatch
**Echo Arts | Elemental Domain: Cross-Domain (Earth / Fire / Air)**

---

## Overview
SysWatch is a Bash-based system health snapshot tool built for Ubuntu WSL. It reports disk space, memory, CPU load, top memory-consuming processes, and active network connections in a single pass. Part of the Bash_Tools collection.

---

## Identity
|Field|Info|
|---|---|
|**Tool Name**|SysWatch|
|**File**|`syswatch`|
|**Domain**|Cross-Domain (Earth / Fire / Air)|
|**Type**|Bash System Health Tool|
|**Environment**|Ubuntu WSL|
|**Status**|v1 Complete (built on a prior machine, no original build log survived the move)|

---

## Purpose
> _"One glance, whole system."_

SysWatch doesn't belong to a single Element because a system's health doesn't either, storage is Earth, running processes are Fire, live connections are Air. This tool reads across all three at once to give a fast, honest snapshot of what a machine is actually doing right now.

---

## What It Does
- Reports disk usage for the root filesystem (`df -h /`)
- Reports memory usage, used and available (`free -h`)
- Reports current CPU load average (`uptime`)
- Lists the top 5 processes by memory consumption (`ps aux --sort=-%mem`)
- Lists up to 5 currently established network connections (`ss -tunap`)

---

## Usage
```bash
git clone https://github.com/StoneyLee63/Bash_Tools.git
cd Bash_Tools
./syswatch
```

---

## Tags
`#echo-arts` `#cross-domain` `#bash` `#linux` `#wsl` `#system-monitoring` `#syswatch`
