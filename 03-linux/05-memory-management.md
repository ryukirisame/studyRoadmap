# Memory Management

## Metadata

| Field | Value |
|---------|---------|
| Priority | P0 |
| Estimated Time | 15-20 Hours |
| Interview Frequency | ⭐⭐⭐⭐⭐ |
| Prerequisites | Operating System Fundamentals |

---

## Learning Objectives

- Understand Linux memory management
- Diagnose memory issues
- Analyze memory consumption
- Understand virtual memory behavior

---

# Memory Fundamentals

Subtopics:
- Physical Memory
- Virtual Memory
- Address Space
- Memory Mapping

Resources:

Primary:
- Linux Kernel Documentation
- OSTEP Memory Virtualization

Interview Questions:
- Physical vs Virtual Memory?
- Why does virtual memory exist?

---

# Memory Layout

Subtopics:
- Text Segment
- Data Segment
- Heap
- Stack

Commands:

```bash
pmap <pid>
cat /proc/<pid>/maps
```

Interview Questions:
- Heap vs Stack?
- What is stored in each segment?

---

# Paging

Subtopics:
- Pages
- Frames
- Page Tables
- Page Faults

Interview Questions:
- What is a page fault?
- Why is paging used?

---

# TLB

Subtopics:
- Translation Lookaside Buffer
- TLB Hits
- TLB Misses

Interview Questions:
- What is the purpose of TLB?

---

# Swap Space

Subtopics:
- Swap
- Swapping
- Memory Pressure

Commands:

```bash
free -h
swapon --show
```

Interview Questions:
- What is swap?
- Why is excessive swapping bad?

---

# Memory Monitoring

Commands:

```bash
free -h
vmstat
top
htop
```

Interview Questions:
- How do you diagnose high memory usage?

---

# Out Of Memory (OOM)

Subtopics:
- OOM Killer
- Memory Exhaustion

Commands:

```bash
dmesg
journalctl
```

Interview Questions:
- What is the OOM Killer?

---

# Most Important Topics

- Virtual Memory
- Paging
- Page Faults
- Swap
- OOM Killer
- Heap vs Stack
