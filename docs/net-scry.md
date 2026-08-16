# Net-Scry
**Echo Arts | Elemental Domain: Air**

---

## Overview
Net-Scry is a Bash-based LAN discovery and port-visibility tool built for Ubuntu WSL. It sweeps the local subnet for live hosts, resolves their hostnames, and reports the top open TCP ports on each one. Part of the Bash_Tools collection.

---

## Identity
|Field|Info|
|---|---|
|**Tool Name**|Net-Scry|
|**File**|`net-scry`|
|**Location**|`~/projects/Bash_Tools/`|
|**Domain**|Air|
|**Type**|Bash Network Discovery Tool|
|**Environment**|Ubuntu WSL|
|**Status**|v1 Complete (built on a prior machine, no original build log survived the move)|

---

## Purpose
> _"Know who's on the network before you trust the network."_

Net-Scry answers a basic but essential visibility question: what's actually alive on this subnet right now, and what's it exposing? Air domain: networking, signal, what's moving and reachable.

---

## What It Does
- Detects the local subnet automatically from the routing table (`ip route`)
- Ping-sweeps the subnet with `fping` to find live hosts
- Skips broadcast addresses automatically
- Resolves each host's name two ways: NetBIOS lookup first (`nmblookup`), falling back to reverse DNS (`host`) if that fails
- Scans each live host's top 10 most common TCP ports with `nmap` in a low-noise timing mode
- Prints one line per host: IP, resolved name, open ports

---

## Dependencies
Not on a stock Ubuntu install, install before running:
```bash
sudo apt install fping nmap samba-common-bin dnsutils
```

---

## Usage
```bash
cd ~/projects/Bash_Tools
./net-scry
```

---

## Tags
`#echo-arts` `#air-domain` `#bash` `#linux` `#wsl` `#network-discovery` `#net-scry`
