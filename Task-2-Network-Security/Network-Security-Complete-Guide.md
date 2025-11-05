# Complete Network Security & Scanning Guide
## Task 2: Network Security & Scanning (Days 13-24)

---

## Table of Contents
1. [Network Reconnaissance](#1-network-reconnaissance)
2. [Port & Service Scanning](#2-port--service-scanning)
3. [Vulnerability Scanning](#3-vulnerability-scanning)
4. [Packet Analysis](#4-packet-analysis)
5. [Firewall Configuration](#5-firewall-configuration)
6. [Deliverables & Reporting](#6-deliverables--reporting)

---

## 1. Network Reconnaissance

### 1.1 Passive Reconnaissance

#### Whois Lookup
**Purpose:** Gather domain registration information
```bash
# Basic whois query
whois example.com

# For IP addresses
whois 192.168.1.1

# With specific server
whois -h whois.radb.net 192.168.1.0/24