# Rate Limiter

## Metadata

| Field | Value |
|---------|---------|
| Priority | P0 |
| Difficulty | Easy |
| Interview Frequency | ⭐⭐⭐⭐⭐ |

---

## Functional Requirements

- Limit requests per user
- Limit requests per IP
- Support multiple rate limits
- Support distributed deployment

---

## Non-Functional Requirements

- Low Latency
- High Throughput
- Consistency
- Fault Tolerance

---

## Capacity Estimation

Subtopics:
- Request Volume
- Memory Usage
- Counter Storage

---

## High Level Design

Subtopics:
- API Gateway
- Rate Limiter Service
- Redis

---

## Core Components

Subtopics:
- Request Counter
- Rule Engine
- Enforcement Layer

---

## Algorithms

Subtopics:
- Fixed Window
- Sliding Window
- Sliding Log
- Token Bucket
- Leaky Bucket

Interview Questions:
- Which algorithm would you choose?

---

## Data Model

Subtopics:
- Counters
- Expiration

---

## Scaling Strategy

Subtopics:
- Redis Cluster
- Partitioning
- Distributed Counters

---

## Reliability Considerations

Subtopics:
- Redis Failures
- Fallback Strategies

---

## Tradeoffs

Subtopics:
- Accuracy vs Performance
- Fixed Window vs Sliding Window

---

## Deep Dive Topics

- Redis Atomic Operations
- Distributed Rate Limiting
