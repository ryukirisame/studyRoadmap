# System Administration

## Metadata

| Field | Value |
|---------|---------|
| Priority | P1 |
| Estimated Time | 15-20 Hours |
| Interview Frequency | ⭐⭐⭐ |
| Prerequisites | Linux Basics |

---

## Learning Objectives

- Manage Linux servers
- Understand services and logs
- Perform common administrative tasks

---

# Users and Groups

Commands:

```bash
id
who
groups
useradd
usermod
```

Interview Questions:
- User vs Group?

---

# Permissions

Subtopics:
- Ownership
- Permissions
- sudo

Commands:

```bash
chmod
chown
sudo
```

Interview Questions:
- What does sudo do?

---

# Services

Subtopics:
- systemd
- Units
- Service Lifecycle

Commands:

```bash
systemctl status
systemctl start
systemctl stop
systemctl restart
```

Interview Questions:
- What is systemd?

---

# Logging

Subtopics:
- Syslog
- Journald

Commands:

```bash
journalctl
tail -f
grep
```

Interview Questions:
- How do you investigate service failures?

---

# Scheduling

Subtopics:
- Cron
- Timers

Commands:

```bash
crontab -e
```

Interview Questions:
- What is cron?

---

# Most Important Topics

- systemd
- journalctl
- sudo
- Services
