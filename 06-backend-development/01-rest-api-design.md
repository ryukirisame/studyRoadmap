# REST API Design

## Metadata

| Field | Value |
|---------|---------|
| Priority | P0 |
| Estimated Time | 12-15 Hours |
| Interview Frequency | ⭐⭐⭐⭐⭐ |
| Prerequisites | HTTP |

---

## Learning Objectives

- Design clean REST APIs
- Understand resource-oriented design
- Build maintainable APIs

---

# REST Fundamentals

Subtopics:
- What is REST?
- Resources
- Resource Identifiers
- Statelessness
- Client-Server Architecture

Resources:

Primary:
- RESTful Web APIs

Interview Questions:
- What is REST?
- Why is REST stateless?

---

# Resource Design

Subtopics:
- Nouns vs Verbs
- URI Design
- Hierarchical Resources

Examples:

```http
GET /users
GET /users/123
GET /users/123/orders
```

Interview Questions:
- How should resources be named?

---

# HTTP Methods

Subtopics:
- GET
- POST
- PUT
- PATCH
- DELETE

Interview Questions:
- PUT vs PATCH?
- Why should GET be idempotent?

---

# Request & Response Design

Subtopics:
- JSON APIs
- Request Validation
- Error Responses

Interview Questions:
- How should API errors be structured?

---

# Idempotency

Subtopics:
- Safe Operations
- Idempotent Operations
- Idempotency Keys

Interview Questions:
- What is idempotency?

---

# API Versioning

Subtopics:
- URI Versioning
- Header Versioning

Interview Questions:
- How do you version APIs?

---

# Most Important Topics

- Resource Design
- HTTP Methods
- Idempotency
- Versioning
