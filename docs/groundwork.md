# Groundwork
**Echo Arts | Elemental Domain: Earth**
**Operator: SoulRa**

---

## Overview
Groundwork is a Bash-based system maintenance tool built for Ubuntu WSL. It handles package updates, upgrades, and cleanup operations — keeping the system's foundation stable, clean, and current. Part of the Bash_Tools collection.

---

## Identity
|Field|Info|
|---|---|
|**Tool Name**|Groundwork|
|**File**|`groundwork`|
|**Location**|`~/projects/Bash_Tools/`|
|**Domain**|Earth|
|**Type**|Bash Maintenance Tool|
|**Environment**|Ubuntu WSL|
|**Operator**|SoulRa|
|**Status**|v1 Complete|

---

## Purpose
> _"Laying the Foundation....."_

Groundwork handles the maintenance layer of the system — the unglamorous but essential work of keeping software current, removing what's no longer needed, and verifying the health of the machine. Earth domain: structure, stability, renewal.

---

## Phases

### Phase 0 — Scaffold ✓
- File created and made executable
- Strict mode enabled (`set -euo pipefail`)
- Metadata block defined
- Header function built and tested
- `main()` entry point wired

### Phase 1 — Update ✓
- `apt-get update`
- Syncs package lists from repositories

### Phase 2 — Upgrade ✓
- `apt-get upgrade -y`
- Upgrades all installed packages

### Phase 3 — Clean ✓
- `apt-get autoremove -y`
- `apt-get autoclean -y`
- `apt-get clean`
- Removes orphaned packages and clears apt cache

### Phase 4 — Check ✓
- Kernel version
- Uptime
- Disk usage
- Memory usage
- Confirms ground is clear

---

## Header Output
---

## Usage
```bash
cd ~/projects/Bash_Tools
./groundwork
```

Or once installed system-wide:
```bash
sudo cp groundwork /usr/local/bin/groundwork
groundwork
```

---

## Tags
`#echo-arts` `#earth-domain` `#bash` `#linux` `#wsl` `#maintenance` `#groundwork`
