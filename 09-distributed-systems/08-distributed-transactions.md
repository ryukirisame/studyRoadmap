# Distributed Transactions

## Metadata

| Field | Value |
|---------|---------|
| Priority | P0 |
| Estimated Time | 12-18 Hours |
| Interview Frequency | ⭐⭐⭐⭐⭐ |
| Prerequisites | Transactions, Consistency Models |

---

## Learning Objectives

- Understand transactions across multiple systems
- Learn coordination techniques

---

# Distributed Transaction Fundamentals

Subtopics:
- Multi-Service Transactions
- Coordination
- Consistency

Interview Questions:
- Why are distributed transactions difficult?

---

# Two Phase Commit (2PC)

Subtopics:
- Prepare Phase
- Commit Phase
- Coordinator

Interview Questions:
- How does 2PC work?

---

# Problems with 2PC

Subtopics:
- Blocking
- Coordinator Failure
- Scalability

Interview Questions:
- Why is 2PC unpopular in microservices?

---

# Saga Pattern

Subtopics:
- Choreography
- Orchestration
- Compensation

Interview Questions:
- What is Saga?

---

# Transactional Outbox

Subtopics:
- Reliable Messaging
- Event Publishing

Interview Questions:
- What problem does Transactional Outbox solve?

---

# Most Important Topics

- 2PC
- Saga
- Transactional Outbox
