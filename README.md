# Yaroslav Mykhailov

Backend Engineer specializing in high-throughput data processing and low-latency system architecture.

### Technical Focus
* **High-Concurrency Systems:** Implementation of race-free, thread-safe backend services in Go.
* **Data Processing Pipelines:** Design of distributed ingestion layers using Redis Streams and batch processing.
* **Storage Architecture:** Relational (PostgreSQL) and analytical (ClickHouse) database optimization, including partitioning and idempotency logic.
* **Observability:** Integration of structured logging (`slog`), Prometheus metrics, and Grafana dashboards for real-time monitoring.

### Technical Stack

| Category | Technologies |
| :--- | :--- |
| **Languages** | Go (Standard Library, `net/http`, Concurrency Primitives) |
| **Databases** | PostgreSQL (`pgx`, `sqlc`), ClickHouse, Redis |
| **Infrastructure** | Docker, Docker Compose, Linux, Caddy, Nginx |
| **Observability** | Prometheus, Grafana, `pprof` |
| **Serialization** | Protobuf, JSON |

### Implementation Standards
* **Idiomatic Go:** Strict adherence to Go conventions, minimized heap allocations, and zero-dependency core logic where applicable.
* **Security:** Network isolation, server-side validation, and secure authentication flows.
* **Data Integrity:** "At-least-once" delivery patterns with database-level idempotency for "exactly-once" outcomes.
* **Performance:** Use of zero-copy parsing, atomic operations, and lock-free primitives in hot paths.

### Contact
* **LinkedIn:** [linkedin.com/in/yaroslav-mykhailov](https://www.linkedin.com/in/yaroslav-mykhailov-a19211406/)
* **Email:** [mykhailov.yar@gmail.com](mailto:mykhailov.yar@gmail.com)
