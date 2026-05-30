# Garbage Collection

## Metadata

| Field | Value |
|---------|---------|
| Priority | P0 |
| Estimated Time | 15-20 Hours |
| Interview Frequency | ⭐⭐⭐⭐⭐ |
| Prerequisites | JVM |

---

## Learning Objectives

- Understand automatic memory management
- Understand GC algorithms
- Understand JVM memory behavior

---

# GC Fundamentals

Subtopics:
- What is Garbage Collection?
- Reachability
- Memory Leaks
- GC Roots

Resources:

Primary:
- Oracle GC Documentation

Interview Questions:
- What is GC?
- Why is GC needed?

---

# Heap Structure

Subtopics:
- Young Generation
- Eden Space
- Survivor Spaces
- Old Generation

Interview Questions:
- What are JVM generations?

---

# GC Algorithms

Subtopics:
- Mark-Sweep
- Mark-Compact
- Copying Collection
- Generational Collection

Interview Questions:
- Mark-Sweep vs Mark-Compact?

---

# GC Events

Subtopics:
- Minor GC
- Major GC
- Full GC

Interview Questions:
- Minor vs Major GC?
- Why is Full GC expensive?

---

# Modern Collectors

Subtopics:
- Serial GC
- Parallel GC
- G1 GC
- ZGC
- Shenandoah

Interview Questions:
- Why was G1 introduced?
- G1 vs ZGC?

---

# GC Tuning

Subtopics:
- Heap Sizing
- Pause Times
- Throughput
- Latency

Tools:
- jstat
- jcmd
- VisualVM

Interview Questions:
- How do you investigate GC issues?

---

# Most Important Topics

- Heap Structure
- GC Roots
- Minor GC
- Major GC
- Full GC
- G1 GC
