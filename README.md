# Rust Learning Hub

A practical Rust learning roadmap for developers who want to move from beginner Rust to real-world Rust projects.

This repository is designed for:

- complete Rust beginners
- Python developers learning Rust
- Java/backend developers learning Rust
- developers confused by ownership and borrowing
- developers who want to understand async Rust
- developers who want to build real Rust projects

Rust can feel difficult at first because it is not just another syntax to learn.

It requires a different mental model.

You need to understand:

- ownership
- borrowing
- lifetimes
- stack vs heap
- move vs copy
- structs
- enums
- traits
- error handling
- async programming
- production-level project structure

This repository gives you a practical roadmap.

---

## Start Here

Choose the path that matches your current level.

| Your Background | Recommended Path |
|---|---|
| I am completely new to Rust | Start with Beginner Rust |
| I know Python | Start with Rust for Python Developers |
| I know Java / Spring Boot | Start with Rust for Java Developers |
| I know basic Rust but struggle with async | Start with Async Rust |
| I want complete Rust mastery | Start with Rust Complete Material |

---

## Path 1: Complete Beginner Rust

Start here if you are new to Rust.

Learn:

- variables
- functions
- control flow
- ownership basics
- borrowing basics
- structs
- enums
- pattern matching
- error handling
- modules
- Cargo
- beginner projects

Recommended beginner projects:

- CLI calculator
- todo CLI app
- file word counter
- password generator
- JSON reader
- CSV parser
- simple HTTP API

Paid structured path:

[Recommended: Rust Beginners Learning Bundle — From Zero to Real Projects](https://tobiweissmann.gumroad.com/l/louvvk)

---

## Path 2: Rust for Python Developers

Start here if you already know Python and want to understand Rust.

Python hides many low-level details from you.

Rust makes those details explicit.

Python developers often struggle with:

- ownership
- borrowing
- references
- mutable borrowing
- stack vs heap
- String vs &str
- structs instead of classes
- enums and pattern matching
- Result instead of exceptions
- Option instead of None

Recommended learning order:

1. Understand stack vs heap
2. Understand values vs references
3. Understand ownership
4. Understand borrowing
5. Learn structs and impl blocks
6. Learn enums and pattern matching
7. Learn traits
8. Build small CLI tools

Useful comparison:

| Concept | Python | Rust |
|---|---|---|
| Memory management | Automatic | Ownership and borrowing |
| Errors | Exceptions | Result<T, E> |
| Null values | None | Option<T> |
| Data modeling | Classes, dicts | Structs, enums |
| Shared behavior | Duck typing / ABCs | Traits |
| Mutation | Flexible | Controlled |
| Type checking | Runtime / optional hints | Compile-time |

---

## Path 3: Rust for Java Developers

Start here if you are coming from Java, Spring Boot, or enterprise backend development.

Java developers often understand backend architecture, OOP, interfaces, dependency injection, and production systems.

But Rust requires a different way of thinking.

Java developers should focus on:

- ownership instead of garbage collection
- traits instead of interfaces
- composition instead of inheritance-heavy design
- Result instead of exceptions
- Option instead of null
- Cargo instead of Maven/Gradle
- Axum instead of Spring MVC
- SQLx/Diesel instead of JPA/Hibernate
- explicit error handling
- async runtime with Tokio

Useful comparison:

| Concept | Java | Rust |
|---|---|---|
| Memory | Garbage collector | Ownership |
| Classes | Central | No traditional classes |
| Interfaces | Interfaces | Traits |
| Exceptions | try/catch | Result<T, E> |
| Null | null | Option<T> |
| Build tool | Maven/Gradle | Cargo |
| Backend framework | Spring Boot | Axum, Actix Web |
| Concurrency | Threads, executors | Tokio, async/await |

Paid structured path:

[Rust for Java Developer](https://tobiweissmann.gumroad.com/l/etcbtr)

---

## Path 4: Async Rust

Async Rust is not the first thing you should learn.

Before learning async Rust, you should already understand:

- ownership
- borrowing
- lifetimes basics
- structs
- enums
- traits
- Result
- modules
- basic Rust projects

Then learn:

- async/await
- futures
- Tokio
- tasks
- channels
- async traits
- timeouts
- cancellation
- streams
- backpressure
- concurrent API calls
- async web servers

Good async Rust projects:

- concurrent web scraper
- async HTTP API
- background worker
- job queue
- WebSocket server
- async file processor
- API client with retries and timeout

Paid structured path:

[Async Rust](https://tobiweissmann.gumroad.com/l/issyq)

---

## Path 5: Complete Rust Material

This path is for serious learners who want a complete Rust learning system.

Recommended after you understand the basics.

It should help you go deeper into:

- ownership
- borrowing
- lifetimes
- generics
- traits
- error handling
- modules
- testing
- async Rust
- backend Rust
- real projects
- production-level structure

Paid structured path:

[Rust Complete Material](https://tobiweissmann.gumroad.com/l/gnuvxu)

---

## Recommended Learning Order

For most learners, this order works well:

1. Rust syntax basics
2. Ownership and borrowing
3. Structs and enums
4. Pattern matching
5. Option and Result
6. Traits
7. Modules and Cargo
8. Error handling
9. Testing
10. CLI projects
11. HTTP APIs
12. Async Rust
13. Database integration
14. Production project structure

---

## Beginner Project Checklist

Start with small projects before jumping into advanced backend systems.

- [ ] CLI calculator
- [ ] Todo CLI app
- [ ] File word counter
- [ ] Password generator
- [ ] JSON reader with Serde
- [ ] CSV parser
- [ ] Log file analyzer
- [ ] Markdown note converter
- [ ] Simple HTTP API
- [ ] PostgreSQL CRUD API
- [ ] Authentication API
- [ ] Async background worker

---

## Core Rust Concepts Checklist

Use this checklist to track your progress.

- [ ] Variables and mutability
- [ ] Functions
- [ ] Control flow
- [ ] Ownership
- [ ] Borrowing
- [ ] Mutable borrowing
- [ ] Move vs copy
- [ ] Clone vs Copy
- [ ] String vs &str
- [ ] Vec<T>
- [ ] Structs
- [ ] Impl blocks
- [ ] Enums
- [ ] Match
- [ ] Option<T>
- [ ] Result<T, E>
- [ ] Traits
- [ ] Generics
- [ ] Lifetimes basics
- [ ] Modules
- [ ] Cargo
- [ ] Testing
- [ ] Error handling
- [ ] Async/await
- [ ] Tokio
- [ ] Axum or Actix Web
- [ ] SQLx or Diesel
- [ ] Dockerizing Rust apps

---

## Free Official Resources

Useful official Rust resources:

- The Rust Programming Language Book  
  https://doc.rust-lang.org/book/

- Rust by Example  
  https://doc.rust-lang.org/rust-by-example/

- Rustlings  
  https://github.com/rust-lang/rustlings

- Rust Standard Library Documentation  
  https://doc.rust-lang.org/std/

- The Rustonomicon  
  https://doc.rust-lang.org/nomicon/  
  Note: advanced resource. Do not start here.

---

## Paid Structured Learning Paths

This repository is free.

I also created paid Rust learning bundles for developers who want a more structured path.

### Rust Beginners Learning Bundle

Best for complete beginners.

https://tobiweissmann.gumroad.com/l/louvvk

### Rust for Java Developer

Best for Java, Spring Boot, and backend developers moving into Rust.

https://tobiweissmann.gumroad.com/l/etcbtr

### Async Rust

Best for developers who already know Rust basics and want to understand async Rust, Tokio, and concurrent systems.

https://tobiweissmann.gumroad.com/l/issyq

### Rust Complete Material

Best for serious learners who want a broader Rust learning system.

https://tobiweissmann.gumroad.com/l/gnuvxu

You do not need to buy anything to use this free roadmap.

But if you want a guided structure instead of collecting random resources, these bundles may help.

---

## Final Advice

Do not rush Rust.

The hardest part is usually not the syntax.

The hardest part is changing your mental model.

Focus first on:

- ownership
- borrowing
- stack vs heap
- structs
- enums
- traits
- Option
- Result
- small projects

Once these ideas become natural, Rust becomes much easier.



