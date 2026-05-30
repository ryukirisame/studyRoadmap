# Computer Fundamentals


| Field | Value |
|---------|---------|
| Priority | P0 |
| Estimated Time | 8-12 Hours |
| Interview Frequency | ⭐⭐⭐⭐⭐ |
| Prerequisites | None |



## Learning Objectives

- Understand how computers execute programs
- Understand how data is represented and stored
- Understand how CPU, memory, storage, and operating systems interact
- Build the foundation required for Operating Systems, Networking, Databases, JVM, and System Design
- Develop a mental model of how software runs on hardware



# Computer Architecture

Priority: P0

Why it matters:
- Operating Systems
- JVM
- Databases
- Performance Optimization

Subtopics:
- What is a Computer?
- Von Neumann Architecture
- CPU
- Main Memory (RAM)
- Storage
- Input Devices
- Output Devices
- System Bus
- Memory Hierarchy

Resources:

Primary:
- Computer Systems: A Programmer's Perspective (CSAPP)
- https://csapp.cs.cmu.edu/

Secondary:
- Crash Course Computer Science
  - https://www.youtube.com/playlist?list=PL8dPuuaLjXtNlUrzyH5r6jN9ulIgZBpdo

Deep Dive:
- Computer Organization and Design (Patterson & Hennessy)

Interview Questions:

Basic:
- What are the main components of a computer?
- What is RAM?

Intermediate:
- What is the Von Neumann Architecture?
- What is the difference between RAM and Storage?

Advanced:
- Why is RAM faster than SSD?
- Why does memory hierarchy exist?

Hands-On:
- View system information using:
  - `lscpu`
  - `free -h`
  - `lsblk`

---

# Data Representation

Priority: P0

Why it matters:
- Networking
- Databases
- Serialization
- Distributed Systems

Subtopics:
- Binary Number System
- Decimal Number System
- Hexadecimal Number System
- Bits
- Bytes
- Character Encoding
- ASCII
- Unicode
- UTF-8
- Integer Representation
- Floating Point Representation

Resources:

Primary:
- CSAPP
- Computer Systems: Bits, Bytes, and Representation

Secondary:
- https://www.javatpoint.com/binary-number-system

Deep Dive:
- IEEE 754 Floating Point Standard

Interview Questions:

Basic:
- What is a bit?
- What is a byte?

Intermediate:
- Difference between ASCII and Unicode?
- Why is UTF-8 popular?

Advanced:
- Why are floating point calculations inaccurate?
- How are negative numbers stored?

Hands-On:
- Convert numbers between binary and decimal
- Convert text into ASCII and UTF-8 representations

---

# CPU Fundamentals

Priority: P0

Why it matters:
- Performance Engineering
- JVM
- Operating Systems
- Concurrency

Subtopics:
- CPU Core
- CPU Clock
- CPU Cycles
- Instructions
- Instruction Execution Cycle
- Registers
- ALU
- Control Unit
- Single Core vs Multi Core
- Hyper-Threading (High Level)

Resources:

Primary:
- CSAPP

Secondary:
- Computer Organization and Design

Interview Questions:

Basic:
- What is a CPU?

Intermediate:
- What are CPU cores?
- What are CPU registers?

Advanced:
- Why are registers faster than RAM?
- What is Hyper-Threading?

Hands-On:
- Inspect CPU information using:
  - `lscpu`
  - `cat /proc/cpuinfo`

---

# Memory Fundamentals

Priority: P0

Why it matters:
- Operating Systems
- JVM
- Databases
- Redis

Subtopics:
- RAM
- Volatile vs Non-Volatile Memory
- Memory Hierarchy
- Registers
- CPU Cache
- L1 Cache
- L2 Cache
- L3 Cache
- Main Memory
- Storage

Resources:

Primary:
- CSAPP

Secondary:
- OSTEP

Interview Questions:

Basic:
- What is RAM?

Intermediate:
- What is CPU Cache?
- Difference between RAM and Cache?

Advanced:
- Why is cache important?
- What is cache locality?

Hands-On:
- Inspect memory information:
  - `free -h`
  - `vmstat`

---

# Storage Fundamentals

Priority: P0

Why it matters:
- Databases
- Kafka
- File Systems

Subtopics:
- HDD
- SSD
- NVMe
- Sequential Reads
- Sequential Writes
- Random Reads
- Random Writes
- Latency
- Throughput
- IOPS

Resources:

Primary:
- Designing Data-Intensive Applications (DDIA)
- Chapters 1-3

Secondary:
- AWS Storage Fundamentals

Interview Questions:

Basic:
- What is an SSD?

Intermediate:
- Difference between HDD and SSD?

Advanced:
- Why are sequential writes faster than random writes?
- What are IOPS?

Hands-On:
- Inspect storage devices:
  - `lsblk`
  - `df -h`
  - `du -sh`

---

# Caching Fundamentals

Priority: P0

Why it matters:
- CPU Design
- Databases
- Redis
- Web Applications

Subtopics:
- What is a Cache?
- Cache Hit
- Cache Miss
- Locality of Reference
- Temporal Locality
- Spatial Locality
- Multi-Level Caching

Resources:

Primary:
- CSAPP

Secondary:
- DDIA

Interview Questions:

Basic:
- What is a cache?

Intermediate:
- What is a cache hit?

Advanced:
- Why does caching improve performance?
- What is locality of reference?

Hands-On:
- Observe CPU cache information:
  - `lscpu`

---

# Computer Networking Basics

Priority: P1

Why it matters:
- Networking Module
- Distributed Systems
- Backend Development

Subtopics:
- What is a Network?
- Client
- Server
- IP Address
- Port
- Packet
- Request
- Response

Resources:

Primary:
- Computer Networking: A Top-Down Approach

Secondary:
- Cloudflare Learning Center

Interview Questions:

Basic:
- What is an IP address?
- What is a port?

Intermediate:
- What is the difference between a client and server?

Advanced:
- Why do applications need ports?

Hands-On:
- Inspect network information:
  - `ip addr`
  - `ifconfig`
  - `ping`

---

# Operating System Basics

Priority: P0

Why it matters:
- Linux
- Concurrency
- JVM
- Databases

Subtopics:
- What is an Operating System?
- Kernel
- User Space
- System Calls
- Processes
- Threads
- Memory Management
- File Systems
- Device Drivers

Resources:

Primary:
- OSTEP
  - https://pages.cs.wisc.edu/~remzi/OSTEP/

Secondary:
- Modern Operating Systems (Tanenbaum)

Interview Questions:

Basic:
- What is an Operating System?

Intermediate:
- What is a Kernel?

Advanced:
- What is a System Call?
- Why do Operating Systems exist?

Hands-On:
- Inspect OS information:
  - `uname -a`
  - `hostnamectl`

---

# Most Important Topics

P0 Topics:

- Computer Architecture
- CPU Fundamentals
- Memory Fundamentals
- Storage Fundamentals
- Data Representation
- Caching Fundamentals
- Operating System Basics

Study these thoroughly before moving to:
- Concurrency
- Linux
- Networking
- JVM
- Databases

---

# Module Completion Checklist

Topics Covered:

- Computer Architecture
- Data Representation
- CPU Fundamentals
- Memory Fundamentals
- Storage Fundamentals
- Caching Fundamentals
- Computer Networking Basics
- Operating System Basics

Recommended Follow-Up:

- 00-foundations/02-concurrency.md
- 00-foundations/05-operating-system-fundamentals.md

---

# Related Modules

Previous:
- None

Next:
- Concurrency

Dependencies For:
- Linux
- Networking
- JVM
- Databases
- System Design
- Distributed Systems
