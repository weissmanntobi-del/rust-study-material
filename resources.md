# Rust Learning Resources

This page contains carefully selected resources for learning Rust.

The goal is not to collect hundreds of links.

The goal is to help you follow a clear path:

1. Learn Rust basics
2. Understand ownership and borrowing
3. Practice with small exercises
4. Build real projects
5. Move toward async and production Rust

---

## 1. Official Rust Resources

### The Rust Programming Language Book

Best starting point for most Rust learners.

Link: https://doc.rust-lang.org/book/

Recommended chapters:

- Getting Started
- Common Programming Concepts
- Understanding Ownership
- Structs
- Enums and Pattern Matching
- Error Handling
- Generic Types, Traits, and Lifetimes
- Smart Pointers
- Fearless Concurrency

Why it is useful:

This book explains the core Rust mental model, especially ownership, borrowing, lifetimes, structs, enums, traits, and error handling.

---

### Rust by Example

Best for learning Rust through small examples.

Link: https://doc.rust-lang.org/rust-by-example/

Use this when you want to see simple working code for:

- variables
- functions
- structs
- enums
- match
- traits
- generics
- error handling
- modules
- standard library examples

---

### Rustlings

Best for hands-on practice.

Link: https://github.com/rust-lang/rustlings

Rustlings gives you small exercises where you fix Rust code and learn from compiler errors.

Recommended approach:

1. Read a chapter from the Rust Book
2. Solve related Rustlings exercises
3. Repeat until ownership, borrowing, and error handling feel natural

---

## 2. Rust Mental Model

Rust is not just another syntax.

Rust teaches you to think about:

- who owns a value
- whether a value is moved or copied
- whether data is borrowed
- whether data can be mutated
- how long a reference lives
- how errors should be handled
- how to write safe concurrent code

Before going deep into Rust projects, focus on these concepts:

- ownership
- borrowing
- mutable borrowing
- lifetimes
- stack vs heap
- move vs copy
- clone vs copy
- `String` vs `&str`
- `Option<T>`
- `Result<T, E>`

---

## 3. Rust for Developers Coming from Other Languages

### If You Come from Python

Focus on:

- memory management
- stack vs heap
- values vs references
- ownership
- borrowing
- structs instead of classes
- enums instead of string-based states
- `Result` instead of exceptions
- `Option` instead of `None`

Python hides many low-level details.

Rust makes those details explicit.

---

### If You Come from Java

Focus on:

- ownership instead of garbage collection
- traits instead of interfaces
- `Result` instead of exceptions
- `Option` instead of null
- composition instead of inheritance-heavy design
- Cargo instead of Maven/Gradle
- Axum or Actix Web instead of Spring Boot
- SQLx or Diesel instead of Hibernate/JPA

---

### If You Come from JavaScript or TypeScript

Focus on:

- static typing
- ownership
- borrowing
- explicit error handling
- pattern matching
- enums
- traits
- modules
- async Rust with Tokio

---

## 4. Beginner Rust Practice Topics

Practice these topics first:

- variables and mutability
- functions
- control flow
- loops
- ownership
- borrowing
- mutable borrowing
- structs
- enums
- pattern matching
- `Option`
- `Result`
- vectors
- hash maps
- modules
- basic testing

Good beginner projects:

- CLI calculator
- file word counter
- todo CLI app
- password generator
- JSON reader
- CSV parser
- log file analyzer

---

## 5. Intermediate Rust Resources

After learning the basics, move into:

- traits
- generics
- lifetimes
- modules
- crates
- error handling
- testing
- iterators
- smart pointers
- closures
- collections

Important crates to explore:

- `serde` for serialization and deserialization
- `clap` for command-line applications
- `thiserror` for custom errors
- `anyhow` for application-level error handling
- `reqwest` for HTTP clients
- `tokio` for async programming

---

## 6. Async Rust Resources

Do not start with async Rust too early.

Before async Rust, you should understand:

- ownership
- borrowing
- lifetimes basics
- structs
- enums
- traits
- `Result`
- modules
- Cargo

Then learn:

- `async fn`
- `.await`
- futures
- Tokio runtime
- tasks
- channels
- timeouts
- cancellation
- streams
- backpressure

Good async Rust projects:

- async HTTP client
- concurrent web scraper
- background worker
- job queue
- WebSocket server
- async REST API
- API client with retries and timeout

---

## 7. Backend Rust Resources

For backend Rust, explore:

- Axum
- Actix Web
- Tokio
- SQLx
- Diesel
- PostgreSQL
- Serde
- Tracing
- Prometheus metrics
- Docker
- GitHub Actions

Good backend projects:

- REST API
- CRUD API with PostgreSQL
- authentication service
- URL shortener
- incident management API
- job queue service
- notification service
- log ingestion API

---

## 8. Production Rust Checklist

A production-ready Rust project should usually include:

- [ ] clean project structure
- [ ] configuration from environment variables
- [ ] database migrations
- [ ] connection pool
- [ ] structured error handling
- [ ] request logging
- [ ] tracing
- [ ] metrics endpoint
- [ ] health check endpoint
- [ ] readiness endpoint
- [ ] integration tests
- [ ] Dockerfile
- [ ] docker-compose.yml
- [ ] CI pipeline
- [ ] secure secrets handling
- [ ] graceful shutdown

---

## 9. Recommended Learning Order

If you are not sure where to start, follow this order:

1. Rust syntax basics
2. Ownership and borrowing
3. Structs and enums
4. Pattern matching
5. `Option<T>` and `Result<T, E>`
6. Traits
7. Modules and Cargo
8. Error handling
9. Testing
10. CLI projects
11. File processing projects
12. HTTP APIs
13. Async Rust
14. Database integration
15. Docker and deployment
16. Production project structure

---

## 10. Advanced Resources

### The Rustonomicon

Link: https://doc.rust-lang.org/nomicon/

This is an advanced resource.

Do not start here.

Read it later if you want to understand:

- unsafe Rust
- low-level memory behavior
- advanced ownership patterns
- unsafe abstractions
- Rust internals

---

## 11. Paid Structured Learning Paths

This repository is free.

I also created paid Rust learning bundles for developers who want a more structured path.

You do not need to buy anything to use this repository.

But if you prefer organized material instead of collecting random resources, these may help.

### Rust Beginners Learning Bundle

Best for complete beginners.

https://tobiweissmann.gumroad.com/l/louvvk

---

### Rust for Java Developer

Best for Java, Spring Boot, and backend developers moving into Rust.

https://tobiweissmann.gumroad.com/l/etcbtr

---

### Async Rust

Best for developers who already know Rust basics and want to learn Tokio, async programming, and concurrent systems.

https://tobiweissmann.gumroad.com/l/issyq

---

### Rust Complete Material

Best for serious learners who want a broader Rust learning system.

https://tobiweissmann.gumroad.com/l/gnuvxu

---

## 12. Final Advice

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
- `Option`
- `Result`
- small projects

Once these ideas become natural, Rust becomes much easier.