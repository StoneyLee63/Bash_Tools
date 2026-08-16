# Session-Time
**Echo Arts | Elemental Domain: Water**

---

## Overview
Session-Time is a Bash-based utility built for Ubuntu WSL that reports system uptime and how long the current user has been logged in. Part of the Bash_Tools collection.

---

## Identity
|Field|Info|
|---|---|
|**Tool Name**|Session-Time|
|**File**|`session-time`|
|**Domain**|Water|
|**Type**|Bash Session Utility|
|**Environment**|Ubuntu WSL|
|**Status**|v1 Complete (built on a prior machine, no original build log survived the move)|

---

## Purpose
> _"Know how long you've been in the water."_

Session-Time answers a simple identity question: how long has this system been running, and how long has this specific user been active on it? Water domain: user state, access, presence.

---

## What It Does
- Reports total system uptime in human-readable form (`uptime -p`)
- Reports the current user's active login session (`who -u`, filtered to `$USER`)

---

## Usage
```bash
git clone https://github.com/StoneyLee63/Bash_Tools.git
cd Bash_Tools
./session-time
```

---

## Tags
`#echo-arts` `#water-domain` `#bash` `#linux` `#wsl` `#session-tracking` `#session-time`
