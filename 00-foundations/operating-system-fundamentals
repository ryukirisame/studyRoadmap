# Operating System Fundamentals

## Metadata

| Field | Value |
|---------|---------|
| Priority | P0 |
| Estimated Time | 20-25 Hours |
| Interview Frequency | ⭐⭐⭐⭐⭐ |
| Prerequisites | Computer Fundamentals, Concurrency |

---

## Learning Objectives

- Understand the purpose of an operating system
- Understand process and thread management
- Understand CPU scheduling
- Understand memory management
- Understand file systems
- Understand I/O fundamentals
- Build the foundation for Linux, JVM, Databases, Redis, Kafka, and System Design

---

# Operating System Basics

Priority: P0

Why it matters:
- Linux
- JVM
- Databases
- System Design

Subtopics:
- What is an Operating System?
- Resource Management
- Hardware Abstraction
- Kernel
- User Space
- Kernel Space
- System Calls
- Privileged vs Non-Privileged Operations

Resources:

Primary:
- OSTEP
  - https://pages.cs.wisc.edu/~remzi/OSTEP/

Secondary:
- Modern Operating Systems (Tanenbaum)

Interview Questions:

Basic:
- What is an operating system?
- Why do operating systems exist?

Intermediate:
- What is a kernel?
- What is a system call?

Advanced:
- Why can't applications directly access hardware?
- What is the difference between kernel space and user space?

Commands:
- uname -a
- hostnamectl
- cat /proc/version

Common Mistakes:
- Thinking the OS is just a user interface
- Confusing kernel and operating system

---

# Processes

Priority: P0

Why it matters:
- Linux
- JVM
- Databases
- Backend Services

Subtopics:
- Process
- Program vs Process
- Process Control Block (PCB)
- Process Lifecycle
- Process States
- Parent Process
- Child Process
- fork()
- exec()
- Zombie Processes
- Orphan Processes

Resources:

Primary:
- OSTEP — Processes

Secondary:
- fork(2)
  - https://man7.org/linux/man-pages/man2/fork.2.html
- exec(3)
  - https://man7.org/linux/man-pages/man3/exec.3.html

Interview Questions:

Basic:
- What is a process?

Intermediate:
- Program vs Process?
- What is a PCB?
- What is a zombie process?

Advanced:
- Why is fork() efficient?
- What is Copy-On-Write?

Commands:
- ps
- top
- htop
- pstree
- pgrep
- pidof

Common Mistakes:
- Confusing programs and processes
- Assuming fork() copies all memory immediately

---

# Threads

Priority: P0

Why it matters:
- Backend Applications
- JVM
- High Concurrency Systems

Subtopics:
- Thread
- Process vs Thread
- User Threads
- Kernel Threads
- Multithreading
- Context Switching
- Scheduler Interaction

Resources:

Primary:
- OSTEP — Concurrency

Secondary:
- Java Concurrency in Practice

Interview Questions:

Basic:
- What is a thread?

Intermediate:
- Process vs Thread?
- Why are threads lightweight?

Advanced:
- Why are context switches expensive?
- User Threads vs Kernel Threads?

Commands:
- ps -T
- top -H

Common Mistakes:
- Thinking threads have independent memory spaces

---

# CPU Scheduling

Priority: P0

Why it matters:
- Performance
- Scalability
- Operating Systems

Subtopics:
- CPU Scheduler
- Scheduling Goals
- Time Slice
- Context Switching
- CPU-bound Workloads
- I/O-bound Workloads
- Throughput
- Latency
- Fairness

Resources:

Primary:
- OSTEP — Scheduling

Secondary:
- Linux Scheduler Documentation

Interview Questions:

Basic:
- What is CPU scheduling?

Intermediate:
- CPU-bound vs I/O-bound?

Advanced:
- Why is context switching expensive?
- Why do I/O-bound processes often feel faster?

Commands:
- top
- htop
- vmstat

Common Mistakes:
- Assuming CPU utilization equals performance

---

# Memory Management

Priority: P0

Why it matters:
- JVM
- Redis
- Databases

Subtopics:
- Virtual Memory
- Address Spaces
- Paging
- Frames
- Page Tables
- Multi-Level Page Tables
- TLB
- TLB Miss
- Page Faults
- Heap
- Stack
- Shared Memory

Resources:

Primary:
- OSTEP — Memory Virtualization

Secondary:
- Linux Memory Management Documentation

Interview Questions:

Basic:
- What is virtual memory?

Intermediate:
- What is paging?
- What is a page fault?

Advanced:
- Why does virtual memory exist?
- What is the purpose of the TLB?

Commands:
- free -h
- vmstat
- pmap
- cat /proc/meminfo

Common Mistakes:
- Confusing RAM with virtual memory
- Ignoring the role of the TLB

---

# File Systems

Priority: P0

Why it matters:
- Databases
- Kafka
- Linux

Subtopics:
- File Systems
- Files
- Directories
- Inodes
- Metadata
- Hard Links
- Symbolic Links
- Mount Points

Resources:

Primary:
- OSTEP — File Systems

Secondary:
- Linux Filesystem Hierarchy Standard
  - https://refspecs.linuxfoundation.org/FHS_3.0/fhs/

Interview Questions:

Basic:
- What is a file system?

Intermediate:
- What is an inode?
- Hard Link vs Symbolic Link?

Advanced:
- Why do file systems use inodes?
- What happens when a file is deleted?

Commands:
- df -h
- du -sh
- lsblk
- mount
- stat

Common Mistakes:
- Confusing hard links and symbolic links

---

# I/O Fundamentals

Priority: P0

Why it matters:
- Databases
- Kafka
- Redis
- Networking

Subtopics:
- File Descriptors
- stdin
- stdout
- stderr
- Blocking I/O
- Non-Blocking I/O
- Buffered I/O
- Direct I/O
- Memory Mapped Files (mmap)
- Page Cache

Resources:

Primary:
- OSTEP — I/O

Secondary:
- open(2)
  - https://man7.org/linux/man-pages/man2/open.2.html
- mmap(2)
  - https://man7.org/linux/man-pages/man2/mmap.2.html

Interview Questions:

Basic:
- What is a file descriptor?

Intermediate:
- What is mmap()?
- What is the page cache?

Advanced:
- Why does Kafka use mmap()?
- Why is sequential I/O generally faster?

Commands:
- lsof
- strace
- iostat

Common Mistakes:
- Thinking files are the only things represented by file descriptors

---

# Most Important Topics

P0 Topics:

- Kernel vs User Space
- System Calls
- Processes
- Threads
- Context Switching
- CPU Scheduling
- Virtual Memory
- Paging
- Page Faults
- TLB
- File Descriptors
- mmap()
- Page Cache

Study these thoroughly before moving to Linux and Databases.

---

# Module Completion Checklist

Topics Covered:

- Operating System Basics
- Processes
- Threads
- CPU Scheduling
- Memory Management
- File Systems
- I/O Fundamentals

Recommended Follow-Up:

- 03-linux/01-linux-basics.md
- 05-databases/01-relational-databases.md

---

# Related Modules

Previous:
- Computer Fundamentals
- Concurrency

Next:
- Data Structures

Dependencies For:
- Linux
- JVM
- Databases
- Redis
- Kafka
- Networking
- System Design
