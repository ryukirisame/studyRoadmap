# Distributed Cache

## Metadata

| Field | Value |
|---------|---------|
| Priority | P0 |
| Difficulty | Medium |
| Interview Frequency | ⭐⭐⭐⭐⭐ |
| Prerequisites | Caching, Distributed Systems |

---

## Functional Requirements

- Store frequently accessed data
- Fast retrieval
- Cache invalidation
- Horizontal scaling

---

## Non-Functional Requirements

- Low Latency
- High Availability
- Scalability

---

## Capacity Estimation

Subtopics:
- Cache Size
- Request Volume
- Memory Consumption

---

## High Level Design

Subtopics:
- Cache Cluster
- Client Layer
- Consistent Hashing

---

## Core Components

Subtopics:
- Cache Nodes
- Partition Manager
- Replication Layer

---

## Data Model

Subtopics:
- Cache Keys
- Cache Values
- TTL

---

## Cache Strategies

Subtopics:
- Cache Aside
- Read Through
- Write Through
- Write Back

Interview Questions:
- Cache Aside vs Write Through?

---

## Eviction Policies

Subtopics:
- LRU
- LFU
- FIFO

Interview Questions:
- LRU vs LFU?

---

## Scaling Strategy

Subtopics:
- Consistent Hashing
- Sharding
- Replication

Interview Questions:
- Why use Consistent Hashing?

---

## Reliability Considerations

Subtopics:
- Cache Failures
- Hot Keys
- Cache Stampede

Interview Questions:
- What is Cache Stampede?

---

## Tradeoffs

Subtopics:
- Consistency vs Performance
- Memory vs Cost

---

## Deep Dive Topics

- Redis Cluster
- Consistent Hashing
- Hot Key Mitigation
