# Dropbox

## Metadata

| Field | Value |
|---------|---------|
| Priority | P0 |
| Difficulty | Very Hard |
| Interview Frequency | ⭐⭐⭐⭐ |
| Prerequisites | Distributed Storage, Cloud Storage, Distributed Systems |

---

## Functional Requirements

- Upload Files
- Download Files
- Synchronize Files
- Share Files
- Version History

---

## Non-Functional Requirements

- High Durability
- High Availability
- Efficient Synchronization
- Massive Storage Scale

---

## Capacity Estimation

Subtopics:
- Storage Growth
- Upload Throughput
- Download Throughput

---

## High Level Design

Subtopics:
- Metadata Service
- File Storage Service
- Sync Service
- Sharing Service

---

## Core Components

Subtopics:
- Chunking Service
- Synchronization Engine
- Version Manager

---

## Data Model

Subtopics:
- Files
- Chunks
- Metadata
- Versions

---

## File Storage Architecture

Subtopics:
- Chunk Storage
- Deduplication
- Replication

Interview Questions:
- Why split files into chunks?

---

## Synchronization

Subtopics:
- Delta Sync
- Conflict Detection
- Conflict Resolution

Interview Questions:
- How does Dropbox sync files efficiently?

---

## Scaling Strategy

Subtopics:
- Metadata Sharding
- Storage Clusters
- Regional Replication

---

## Reliability Considerations

Subtopics:
- Data Replication
- Backup
- Disaster Recovery

---

## Tradeoffs

Subtopics:
- Storage Cost vs Durability
- Consistency vs Performance

---

## Deep Dive Topics

- Chunking
- Deduplication
- Delta Sync
- File Versioning
