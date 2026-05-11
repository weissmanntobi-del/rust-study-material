
# Rust for Java Developers

This guide is for Java, Spring Boot, and backend developers learning Rust.

Java developers already understand many useful ideas:

- types
- interfaces
- backend services
- HTTP APIs
- databases
- dependency management
- production systems

But Rust uses a different mental model.

---

## Java vs Rust

| Concept       | Java              | Rust                   |
|---------------|-------------------|------------------------|
| Memory        | Garbage collector | Ownership              |
| Classes       | Central           | No traditional classes |
| Interfaces    | Interfaces        | Traits                 |
| Exceptions    | try/catch         | Result<T, E>           |
| Null          | null              | Option<T>              |
| Build tool    | Maven/Gradle      | Cargo                  |
| Web framework | Spring Boot       | Axum / Actix Web       |
| ORM           | Hibernate/JPA     | SQLx / Diesel          |
| Concurrency   | Threads/executors | Tokio + async/await    |

---

## What Java Developers Must Unlearn

In Java, you often rely on:

- garbage collection
- inheritance
- runtime exceptions
- null
- framework magic
- annotations
- dependency injection containers

Rust is more explicit.

Rust prefers:

- ownership
- composition
- traits
- explicit error handling
- `Option` instead of null
- small libraries instead of heavy frameworks

---

## Rust Traits vs Java Interfaces

Java:

```java
interface PaymentProcessor {
    void pay();
}