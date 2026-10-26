### Hi, I'm Ian 👋

Computer Engineering student (4th year, UADE) building **backend systems that real businesses depend on**.

My main project is **[Fluo](https://getfluo.com.ar)**, a point-of-sale and management platform for cafés and restaurants that I designed, built and run in production on my own — Java 17 / Spring Boot, PostgreSQL, multi-tenant, with Mercado Pago payments, AFIP electronic invoicing and an offline mode that keeps selling when the connection drops.
→ **[Read the case study](https://github.com/ISch-1/fluo-case-study)** (architecture, decisions and incidents; the code is private but I'm happy to walk through it in an interview).

### What I've worked on

- **Fluo** — 576 Java classes, 92 Flyway migrations, 70+ REST controllers, deployed on Render behind its own domain. Highlights: tenant isolation enforced at the ORM layer, AES-256-GCM encrypted per-tenant credentials, TOTP 2FA, a durable offline sales queue, and a login-bypass bug I found and fixed.
- **[ai-research-labs](https://github.com/ISch-1/ai-research-labs)** — reproducible ML / NLP / computer-vision experiments where every result comes with a confidence interval or a significance test. Live demo on [Hugging Face](https://huggingface.co/spaces/Iansha/pet-breeds-gradcam).

### Smaller projects

One topic each, and all of them build and pass their CI.

- **[ecommerce-polyglot](https://github.com/ISch-1/ecommerce-polyglot)** — Java 21 / Spring Boot modular monolith: PostgreSQL, Redis cache-aside and a transactional outbox to Kafka, with module boundaries checked by Spring Modulith. Integration tests run against real Postgres, Redis and Kafka.
- **[url-shortener](https://github.com/ISch-1/url-shortener)** — Go: Snowflake IDs encoded in base62, a Redis + Lua token-bucket rate limiter, REST and gRPC. Integration tests against real Postgres and Redis.
- **[event-stream-platform](https://github.com/ISch-1/event-stream-platform)** — Java: HTTP ingest → Avro on Kafka → ClickHouse, deduplicated on replay, with a dead-letter queue. End-to-end test from HTTP to ClickHouse.
- **[order-book](https://github.com/ISch-1/order-book)** — Rust: limit-order matching engine with one tokio actor per symbol, property-based tests on the book's invariants and criterion benchmarks.
- **[db-sentinel](https://github.com/ISch-1/db-sentinel)** — SRE sandbox: a Python agent with Isolation Forest anomaly detection and self-healing rules, a Java service that tracks SLO error budgets, and Terraform for AWS (run on LocalStack).
- **[evm-vuln-lab](https://github.com/ISch-1/evm-vuln-lab)** — Solidity / Foundry: The DAO's reentrancy exploit reproduced as a passing test, plus the patched contract the same attack fails against.

### Tech I use day to day

`Java` · `Spring Boot` · `PostgreSQL` · `Flyway` · `Docker` · `Python` · `JavaScript` · `GitHub Actions`

Also explored in the projects above: `Go` · `Rust` · `Kafka` · `Redis` · `ClickHouse` · `Solidity`

### Looking for

Backend or full-stack **internships and junior roles** (Buenos Aires or remote).

📫 [LinkedIn](https://www.linkedin.com/in/ian-schaschin-0554aa370/) · ischaschin@gmail.com
