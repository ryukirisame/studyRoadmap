# Processes and Threads

## Metadata

| Field | Value |
|---------|---------|
| Priority | P0 |
| Estimated Time | 15-20 Hours |
| Interview Frequency | ⭐⭐⭐⭐⭐ |
| Prerequisites | Operating System Fundamentals |

---

## Learning Objectives

- Monitor running processes
- Manage applications
- Debug production systems

---

# Process Fundamentals

Subtopics:
- PID
- PPID
- Process Lifecycle
- Foreground Processes
- Background Processes

Commands:

```bash
ps
pstree
pidof
pgrep
```

Interview Questions:
- What is a PID?

---

# Process Monitoring

Commands:

```bash
top
htop
ps aux
```

Interview Questions:
- How do you find a CPU-hungry process?

---

# Signals

Subtopics:
- SIGTERM
- SIGKILL
- SIGINT
- SIGHUP

Commands:

```bash
kill
killall
pkill
```

Interview Questions:
- SIGTERM vs SIGKILL?

---

# Background Jobs

Commands:

```bash
jobs
bg
fg
nohup
```

Interview Questions:
- What is nohup?

---

# Thread Inspection

Commands:

```bash
ps -T
top -H
```

Interview Questions:
- How do you inspect threads?

---

# Java Process Debugging

Commands:

```bash
jps
jstack
jcmd
```

Interview Questions:
- How do you debug a stuck Java process?

---

# Most Important Commands

```bash
ps
top
htop
kill
pgrep
nohup
jstack
```
