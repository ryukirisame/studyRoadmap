# MVCC (Multi-Version Concurrency Control)

## Metadata

| Field | Value |
|---------|---------|
| Priority | P0 |
| Estimated Time | 15-20 Hours |
| Interview Frequency | ⭐⭐⭐⭐⭐ |
| Prerequisites | Transactions |

---

## Learning Objectives

- Understand database concurrency
- Understand isolation without excessive locking

---

# MVCC Fundamentals

Subtopics:
- What is MVCC?
- Why MVCC Exists

Resources:

Primary:
- DDIA
- PostgreSQL Documentation

Interview Questions:
- What is MVCC?

---

# Versions

Subtopics:
- Row Versions
- Snapshots

Interview Questions:
- How does MVCC work?

---

# Snapshot Isolation

Subtopics:
- Read Snapshots
- Transaction Views

Interview Questions:
- What is snapshot isolation?

---

# MVCC vs Locks

Subtopics:
- Readers vs Writers
- Concurrency Tradeoffs

Interview Questions:
- Why is MVCC faster than locking for reads?

---

# Visibility Rules

Subtopics:
- Transaction IDs
- Visibility Checks

Interview Questions:
- How does a database determine visible rows?

---

# Most Important Topics

- Row Versions
- Snapshots
- Snapshot Isolation
- MVCC vs Locks
