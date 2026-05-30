# SOLID Principles

## Metadata

| Field | Value |
|---------|---------|
| Priority | P0 |
| Estimated Time | 12-15 Hours |
| Interview Frequency | ⭐⭐⭐⭐⭐ |
| Prerequisites | OOP |

---

## Learning Objectives

- Understand why SOLID principles exist
- Learn the responsibilities of each principle
- Understand the tradeoffs of applying SOLID
- Learn how SOLID influences Design Patterns and Architecture
- Improve maintainability, extensibility, and testability of software

---

# Introduction to SOLID

Priority: P0

Why it matters:
- Clean Code
- Design Patterns
- Spring Framework
- Software Architecture

Subtopics:
- What is SOLID?
- History of SOLID
- Robert C. Martin (Uncle Bob)
- Maintainability
- Extensibility
- Testability

Resources:

Primary:
- Clean Architecture

Secondary:
- Agile Software Development: Principles, Patterns, and Practices

Interview Questions:

Basic:
- What is SOLID?

Intermediate:
- Why do SOLID principles exist?

Advanced:
- Can SOLID ever make code worse?

Hands-On:
- Review an existing class and identify SOLID violations

Common Mistakes:
- Treating SOLID as strict rules instead of design guidelines

---

# Single Responsibility Principle (SRP)

Priority: P0

Why it matters:
- Maintainability
- Change Management

Definition:
- A class should have only one reason to change.

Subtopics:
- Responsibilities
- Separation of Concerns
- Cohesion
- God Classes

Resources:

Primary:
- Clean Architecture

Secondary:
- Clean Code

Interview Questions:

Basic:
- What is SRP?

Intermediate:
- What is a responsibility?

Advanced:
- How do you identify multiple responsibilities?

Hands-On:
- Refactor a God Class

Common Mistakes:
- Creating tiny classes for every method

---

# Open Closed Principle (OCP)

Priority: P0

Why it matters:
- Extensibility
- Framework Design

Definition:
- Software entities should be open for extension but closed for modification.

Subtopics:
- Extension Points
- Polymorphism
- Strategy Pattern
- Plugin Architectures

Resources:

Primary:
- Clean Architecture

Secondary:
- Head First Design Patterns

Interview Questions:

Basic:
- What is OCP?

Intermediate:
- How does polymorphism help OCP?

Advanced:
- Can OCP lead to over-engineering?

Hands-On:
- Replace conditionals with polymorphism

Common Mistakes:
- Introducing abstractions prematurely

---

# Liskov Substitution Principle (LSP)

Priority: P0

Why it matters:
- Correctness
- Inheritance Design

Definition:
- Subtypes must be substitutable for their base types.

Subtopics:
- Behavioral Contracts
- Preconditions
- Postconditions
- Inheritance Pitfalls

Resources:

Primary:
- Clean Architecture

Secondary:
- Effective Java

Interview Questions:

Basic:
- What is LSP?

Intermediate:
- Why does the Rectangle-Square example violate LSP?

Advanced:
- How does LSP affect API design?

Hands-On:
- Identify LSP violations in inheritance hierarchies

Common Mistakes:
- Assuming inheritance automatically implies substitutability

---

# Interface Segregation Principle (ISP)

Priority: P0

Why it matters:
- API Design
- Framework Design

Definition:
- Clients should not be forced to depend on methods they do not use.

Subtopics:
- Fat Interfaces
- Role-Based Interfaces
- Interface Design

Resources:

Primary:
- Clean Architecture

Secondary:
- Effective Java

Interview Questions:

Basic:
- What is ISP?

Intermediate:
- What is a fat interface?

Advanced:
- How can ISP improve maintainability?

Hands-On:
- Split a large interface into focused interfaces

Common Mistakes:
- Creating excessively granular interfaces

---

# Dependency Inversion Principle (DIP)

Priority: P0

Why it matters:
- Spring Framework
- Testability
- Architecture

Definition:
- High-level modules should not depend on low-level modules. Both should depend on abstractions.

Subtopics:
- Dependency Direction
- Abstractions
- Dependency Injection
- Inversion of Control
- Framework Design

Resources:

Primary:
- Clean Architecture

Secondary:
- Spring Framework Documentation

Interview Questions:

Basic:
- What is DIP?

Intermediate:
- What is Dependency Injection?

Advanced:
- How does Spring implement DIP?

Hands-On:
- Refactor concrete dependencies into abstractions

Common Mistakes:
- Creating interfaces without a clear abstraction boundary

---

# SOLID Tradeoffs

Priority: P1

Why it matters:
- Real-World Software Development

Subtopics:
- Over-Engineering
- Premature Abstraction
- Complexity vs Flexibility
- YAGNI
- Practical Design

Resources:

Primary:
- Clean Architecture

Secondary:
- A Philosophy of Software Design

Interview Questions:

Basic:
- Can SOLID be overused?

Intermediate:
- When should SOLID be ignored?

Advanced:
- How do you balance flexibility and simplicity?

Hands-On:
- Analyze a project for unnecessary abstractions

Common Mistakes:
- Applying SOLID mechanically

---

# SOLID and Design Patterns

Priority: P1

Why it matters:
- Design Patterns
- Architecture

Subtopics:
- SOLID and Strategy Pattern
- SOLID and Factory Pattern
- SOLID and Decorator Pattern
- SOLID and Observer Pattern

Resources:

Primary:
- Head First Design Patterns

Secondary:
- Clean Architecture

Interview Questions:

Basic:
- How are SOLID and Design Patterns related?

Intermediate:
- Which SOLID principles does Strategy Pattern support?

Advanced:
- Can Design Patterns violate SOLID?

Hands-On:
- Identify SOLID principles inside common design patterns

---

# Most Important Topics

P0 Topics:

- SRP
- OCP
- LSP
- ISP
- DIP

Additional Important Topics:

- Cohesion
- Coupling
- Dependency Injection
- Separation of Concerns

Study these thoroughly before moving to Design Patterns.

---

# Module Completion Checklist

Topics Covered:

- Introduction to SOLID
- SRP
- OCP
- LSP
- ISP
- DIP
- SOLID Tradeoffs
- SOLID and Design Patterns

Recommended Follow-Up:

- 01-programming-fundamentals/03-design-patterns.md

---

# Related Modules

Previous:
- OOP

Next:
- Design Patterns

Dependencies For:
- Spring Framework
- Clean Architecture
- Microservices
- Domain-Driven Design
- System Design
