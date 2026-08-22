# João Paulo (JP)

Backend engineer focused on distributed and event-driven systems.

I work at Volkswagen Group Digital Solutions on a connected-vehicle data
platform — event-driven microservices on Java, Spring Boot and Apache Kafka.
Before that I spent years as a full-stack developer in JavaScript, TypeScript
and PHP, and moved progressively toward backend and distributed architecture,
including a legacy Java to Node.js migration at Toyota Motor Europe with
RabbitMQ for event-driven workflows.

## Projects

**[tremr.live](https://tremr.live)** — Real-time global earthquake monitor,
with dedicated coverage for Portugal, Spain and the Azores. Live WebSocket
feed straight from EMSC alongside a server-owned ingestion path, at-least-once
delivery with idempotent upserts keyed on the source's event id, and derived
fields computed server-side only. Next.js, React, Supabase/Postgres, Mapbox,
in PT/ES/EN.

**[finances.tremr.live](https://finances.tremr.live)** — Multi-currency
finance app for households. FastAPI with async SQLAlchemy, Next.js frontend,
PostgreSQL, Docker on a self-managed VPS. The typed API client is generated
from the OpenAPI spec and CI fails on any drift; tenant isolation runs through
a single dependency plus a service-layer recheck that returns 404 rather
than 403.

**watt-do-we-have-here** — Open-source energy monitoring dashboard.
React, FastAPI, PostgreSQL. Work in progress.

## Stack

**Backend** — Java, Spring Boot, Python, FastAPI, Node.js, TypeScript
**Messaging & streaming** — Apache Kafka, Kafka Streams, Avro, RabbitMQ
**Data** — PostgreSQL, MySQL, Redis, SQLAlchemy
**Infra & delivery** — Docker, Kubernetes, Helm, GitHub Actions, Jenkins, AWS
**Frontend** — React, Next.js

## Currently

Learning Rust and low-level systems programming. Also German, piano and theatre.
