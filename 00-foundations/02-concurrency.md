# Concurrency

## Metadata

| Field | Value |
|---------|---------|
| Priority | P0 |
| Estimated Time | 15-20 Hours |
| Interview Frequency | ⭐⭐⭐⭐⭐ |
| Prerequisites | Computer Fundamentals |

---

## Learning Objectives

- Understand concurrent execution
- Understand the challenges of shared state
- Understand synchronization techniques
- Understand common concurrency problems
- Understand atomic operations and memory visibility
- Build the foundation required for Java Concurrency, Operating Systems, Databases, and Distributed Systems

---

# Concurrency Fundamentals

Priority: P0

Why it matters:
- Operating Systems
- Java Backend Development
- Databases
- Distributed Systems
- System Design

Subtopics:
- What is Concurrency?
- What is Parallelism?
- Concurrency vs Parallelism
- Processes vs Threads
- Shared State
- Critical Section
- Thread Safety
- Deterministic vs Non-Deterministic Execution

Resources:

Primary:
- Java Concurrency in Practice
- OSTEP - Concurrency
  - https://pages.cs.wisc.edu/~remzi/OSTEP/

Secondary:
- Oracle Concurrency Tutorial
  - https://docs.oracle.com/javase/tutorial/essential/concurrency/

Interview Questions:

Basic:
- What is concurrency?
- What is parallelism?

Intermediate:
- Concurrency vs parallelism?
- What is a critical section?
- What is thread safety?

Advanced:
- Why is concurrent code difficult to reason about?
- Why can the same concurrent program produce different outputs?

Hands-On:
- Observe multiple threads running in a process
- Use:
  - top
  - htop
  - ps -T

Common Mistakes:
- Treating concurrency and parallelism as the same thing
- Assuming thread execution order is deterministic

---

# Race Conditions

Priority: P0

Why it matters:
- Backend Services
- Databases
- Financial Systems

Subtopics:
- Race Condition
- Lost Update Problem
- Check-Then-Act Pattern
- Read-Modify-Write Pattern

Resources:

Primary:
- Java Concurrency in Practice

Secondary:
- OSTEP - Concurrency

Interview Questions:

Basic:
- What is a race condition?

Intermediate:
- How does a race condition occur?

Advanced:
- Why are race conditions difficult to reproduce?

Hands-On:
- Implement a shared counter without synchronization
- Observe inconsistent results

Common Mistakes:
- Assuming simple operations are always safe
- Ignoring shared mutable state

---

# Synchronization Fundamentals

Priority: P0

Why it matters:
- Thread Safety
- Databases
- Distributed Systems

Subtopics:
- Mutual Exclusion
- Locking
- Mutex
- Semaphore
- Read-Write Lock
- Condition Variables
- Monitor

Resources:

Primary:
- Java Concurrency in Practice

Secondary:
- OSTEP - Locks

Interview Questions:

Basic:
- What is a mutex?
- What is a semaphore?

Intermediate:
- Mutex vs Semaphore?
- When would you use a Read-Write Lock?

Advanced:
- Why do synchronization primitives exist?
- What tradeoffs do locks introduce?

Hands-On:
- Implement Producer-Consumer using synchronization primitives

Common Mistakes:
- Using locks too aggressively
- Locking large critical sections

---

# Atomic Operations

Priority: P0

Why it matters:
- High Performance Systems
- Lock-Free Algorithms
- Databases

Subtopics:
- Atomicity
- Atomic Operations
- Compare-And-Swap (CAS)
- Lock-Free Programming
- Wait-Free Programming (High Level)

Resources:

Primary:
- Java Concurrency in Practice

Secondary:
- Martin Thompson Articles
  - https://mechanical-sympathy.blogspot.com/

Interview Questions:

Basic:
- What is an atomic operation?

Intermediate:
- What is CAS?

Advanced:
- Why can CAS outperform locks?
- What is lock-free programming?

Hands-On:
- Compare lock-based vs atomic implementations conceptually

Common Mistakes:
- Confusing atomicity with thread safety

---

# Memory Visibility

Priority: P0

Why it matters:
- Multi-Core Systems
- JVM
- Modern CPUs

Subtopics:
- Memory Visibility
- CPU Cache
- Stale Reads
- Memory Reordering
- Happens-Before Relationship (Conceptual)

Resources:

Primary:
- Java Concurrency in Practice

Secondary:
- Java Memory Model Articles

Interview Questions:

Basic:
- What is memory visibility?

Intermediate:
- What is a stale read?

Advanced:
- Why can one thread fail to see another thread's updates?
- What is memory reordering?

Hands-On:
- Study CPU cache hierarchy from Computer Fundamentals chapter

Common Mistakes:
- Assuming memory updates become instantly visible to all threads

---

# Common Concurrency Problems

Priority: P0

Why it matters:
- Production Systems
- Backend Applications

Subtopics:
- Race Conditions
- Deadlocks
- Livelocks
- Starvation

Resources:

Primary:
- Java Concurrency in Practice

Secondary:
- OSTEP

Interview Questions:

Basic:
- What is a deadlock?

Intermediate:
- Deadlock vs Livelock?

Advanced:
- How can deadlocks be prevented?
- How can starvation occur?

Hands-On:
- Create a simple deadlock example
- Analyze lock acquisition order

Common Mistakes:
- Acquiring locks in inconsistent order

---

# Concurrency Patterns

Priority: P0

Why it matters:
- Backend Services
- Message Processing
- Distributed Systems

Subtopics:
- Producer Consumer
- Worker Queue
- Thread Pool
- Pipeline Pattern
- Future / Promise (Conceptual)

Resources:

Primary:
- Java Concurrency in Practice

Secondary:
- Enterprise Integration Patterns

Interview Questions:

Basic:
- What is Producer Consumer?

Intermediate:
- Why are thread pools useful?

Advanced:
- What problems do thread pools solve?
- What happens if a worker queue grows indefinitely?

Hands-On:
- Implement Producer Consumer
- Implement a simple Worker Queue

Common Mistakes:
- Creating unbounded queues
- Creating too many threads

---

# Performance Considerations

Priority: P1

Why it matters:
- Scalability
- High Throughput Systems

Subtopics:
- Context Switching
- Lock Contention
- Throughput
- Latency
- Scalability
- False Sharing (High Level)

Resources:

Primary:
- Java Concurrency in Practice

Secondary:
- Mechanical Sympathy Blog

Interview Questions:

Basic:
- What is context switching?

Intermediate:
- What is lock contention?

Advanced:
- Why can excessive locking reduce performance?
- What is false sharing?

Hands-On:
- Measure performance impact of synchronization

Common Mistakes:
- Optimizing prematurely
- Ignoring contention hotspots

---

# Most Important Topics

P0 Topics:

- Concurrency vs Parallelism
- Critical Sections
- Thread Safety
- Race Conditions
- Mutex
- Semaphore
- CAS
- Memory Visibility
- Deadlocks
- Producer Consumer
- Thread Pools

Study these thoroughly before moving to:
- Operating Systems
- Java Concurrency
- Databases
- Distributed Systems

---

# Module Completion Checklist

Topics Covered:

- Concurrency Fundamentals
- Race Conditions
- Synchronization Fundamentals
- Atomic Operations
- Memory Visibility
- Common Concurrency Problems
- Concurrency Patterns
- Performance Considerations

Recommended Follow-Up:

- 00-foundations/05-operating-system-fundamentals.md
- 02-java-backend/04-java-concurrency.md

---

# Related Modules

Previous:
- Computer Fundamentals

Next:
- Data Structures

Dependencies For:
- Operating Systems
- Java Concurrency
- Databases
- JVM
- Distributed Systems
- System Design
