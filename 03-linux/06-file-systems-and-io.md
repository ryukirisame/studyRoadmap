# File Systems and I/O

## Metadata

| Field | Value |
|---------|---------|
| Priority | P0 |
| Estimated Time | 15-20 Hours |
| Interview Frequency | ⭐⭐⭐⭐⭐ |
| Prerequisites | Files and Directories |

---

## Learning Objectives

- Understand Linux file systems
- Understand disk I/O
- Diagnose storage bottlenecks

---

# File System Fundamentals

Subtopics:
- ext4
- XFS
- Btrfs
- Mounting

Interview Questions:
- What file systems have you used?

---

# Inodes

Subtopics:
- Inode Structure
- Metadata
- File Lookup

Commands:

```bash
stat
df -i
```

Interview Questions:
- What is an inode?
- Can a disk run out of inodes?

---

# File Descriptors

Subtopics:
- FD Table
- stdin
- stdout
- stderr

Commands:

```bash
lsof
ls /proc/<pid>/fd
```

Interview Questions:
- What is a file descriptor?

---

# Page Cache

Subtopics:
- Disk Caching
- Buffered Reads
- Buffered Writes

Interview Questions:
- What is page cache?
- Why is page cache important?

---

# I/O Models

Subtopics:
- Blocking I/O
- Non-Blocking I/O
- Multiplexing
- mmap()

Interview Questions:
- Why does Kafka use mmap()?

---

# Disk Performance

Subtopics:
- Latency
- Throughput
- IOPS
- Sequential I/O
- Random I/O

Commands:

```bash
iostat
iotop
```

Interview Questions:
- Sequential vs Random I/O?

---

# Most Important Topics

- Inodes
- File Descriptors
- Page Cache
- mmap()
- IOPS
