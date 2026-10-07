## Shapnesh Singh Tiwari

Backend engineer working on search and indexing infrastructure for a SaaS commerce
platform — roughly 15K dealers and 1M storefront visits a day.

Most of what I do sits where correctness and performance meet: ordering guarantees
under concurrency, hot paths that allocate too much, search that has to stay fast
as data grows.

**Currently building [keyflow](https://github.com/shapnesht/keyflow)** — a key-ordered
event processing library in Go. Events sharing a key are processed sequentially;
different keys run in parallel. The same guarantee Kafka partitions and RabbitMQ's
consistent-hash exchange provide, implemented in-process so the mechanism is visible
rather than delegated.

**At work:** C# · .NET 8 · Elasticsearch · RabbitMQ · Redis · SQL Server · Docker ·
Kubernetes · Terraform · AWS

**Building with:** Go · Java · Spring Boot · PostgreSQL

**Elsewhere:** [LinkedIn](https://linkedin.com/in/shapnesht) ·
[LeetCode](https://leetcode.com/u/shapnesht) (top 5%) · CodeChef 4★
