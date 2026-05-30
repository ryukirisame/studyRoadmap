# Chat System

## Metadata

| Field | Value |
|---------|---------|
| Priority | P0 |
| Difficulty | Medium |
| Interview Frequency | ⭐⭐⭐⭐⭐ |

---

## Functional Requirements

- One-to-One Messaging
- Group Messaging
- Message History
- Online Presence
- Read Receipts

---

## Non-Functional Requirements

- Real-Time Delivery
- High Availability
- Low Latency

---

## Capacity Estimation

Subtopics:
- Concurrent Users
- Messages Per Second
- Storage Growth

---

## High Level Design

Subtopics:
- Chat Gateway
- WebSocket Servers
- Message Service
- Storage

---

## Core Components

Subtopics:
- Connection Manager
- Message Broker
- Presence Service

---

## Data Model

Subtopics:
- Conversations
- Messages
- Participants

---

## Scaling Strategy

Subtopics:
- Horizontal Scaling
- Partitioning
- Regional Deployment

---

## Reliability Considerations

Subtopics:
- Message Persistence
- Retry Mechanisms
- Offline Delivery

---

## Security Considerations

Subtopics:
- Authentication
- Authorization
- End-to-End Encryption

---

## Tradeoffs

Subtopics:
- WebSocket vs Polling
- SQL vs NoSQL

---

## Deep Dive Topics

- Presence Tracking
- Read Receipts
- Message Ordering
