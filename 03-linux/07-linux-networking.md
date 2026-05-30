# Linux Networking

## Metadata

| Field | Value |
|---------|---------|
| Priority | P0 |
| Estimated Time | 20-25 Hours |
| Interview Frequency | ⭐⭐⭐⭐⭐ |
| Prerequisites | Networking Fundamentals |

---

## Learning Objectives

- Diagnose network issues
- Understand Linux networking tools
- Analyze application connectivity

---

# Network Interfaces

Subtopics:
- NIC
- Loopback Interface
- Interface Configuration

Commands:

```bash
ip addr
ip link
ifconfig
```

Interview Questions:
- What is loopback?

---

# Routing

Subtopics:
- Routing Tables
- Default Gateway

Commands:

```bash
ip route
route -n
```

Interview Questions:
- How does routing work?

---

# DNS

Subtopics:
- Name Resolution
- Resolver

Commands:

```bash
nslookup
dig
host
```

Interview Questions:
- How does DNS resolution work?

---

# Connectivity Testing

Commands:

```bash
ping
traceroute
mtr
```

Interview Questions:
- What does ping test?

---

# Port Inspection

Commands:

```bash
ss -tulpn
netstat -tulpn
lsof -i
```

Interview Questions:
- How do you find which process is using a port?

---

# Packet Analysis

Commands:

```bash
tcpdump
wireshark
```

Interview Questions:
- How do you inspect network traffic?

---

# HTTP Debugging

Commands:

```bash
curl
wget
```

Interview Questions:
- How do you debug an API issue from Linux?

---

# Most Important Commands

```bash
ip
ping
dig
ss
lsof
curl
tcpdump
```
