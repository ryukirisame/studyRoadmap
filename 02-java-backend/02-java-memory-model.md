# Java Memory Model (JMM)

## Metadata

| Field | Value |
|---------|---------|
| Priority | P0 |
| Estimated Time | 10-15 Hours |
| Interview Frequency | ⭐⭐⭐⭐⭐ |
| Prerequisites | Concurrency, JVM |

---

## Learning Objectives

- Understand visibility guarantees
- Understand ordering guarantees
- Understand happens-before relationships

---

# JMM Fundamentals

Subtopics:
- What is JMM?
- Why JMM Exists
- Shared Memory Model

Resources:

Primary:
- Java Concurrency in Practice

Interview Questions:
- What is the Java Memory Model?

---

# Visibility

Subtopics:
- Shared Variables
- Stale Reads
- Cache Coherence
- Visibility Problems

Interview Questions:
- Why can one thread not see another thread's updates?

---

# Happens-Before

Subtopics:
- Happens-Before Relationship
- Synchronization Order
- Visibility Guarantees

Interview Questions:
- What is Happens-Before?

---

# Reordering

Subtopics:
- Compiler Reordering
- CPU Reordering
- Instruction Reordering

Interview Questions:
- Why does instruction reordering occur?

---

# volatile

Subtopics:
- Visibility Guarantees
- Ordering Guarantees
- Limitations

Interview Questions:
- What does volatile guarantee?
- What does volatile NOT guarantee?

---

# Synchronization and Memory

Subtopics:
- synchronized
- Locks
- Memory Barriers

Interview Questions:
- How does synchronized affect visibility?

---

# Most Important Topics

- Visibility
- Happens-Before
- volatile
- Reordering
