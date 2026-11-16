# Faxriyor To'rayev

Java backend developer from Tashkent and Software Engineering student. I build REST APIs with Spring Boot and PostgreSQL, and I like the parts of backend work that are easy to get wrong: transactions, concurrency and messaging. Currently looking for a junior Java backend developer role.

## Featured project

### [Digital Wallet API](https://github.com/FaxriyorBT/digital-wallet)

[![CI](https://github.com/FaxriyorBT/digital-wallet/actions/workflows/ci.yml/badge.svg)](https://github.com/FaxriyorBT/digital-wallet/actions/workflows/ci.yml)

Multi-currency wallets with peer-to-peer transfers and currency conversion at the official Central Bank of Uzbekistan rate.

- Double-entry ledger with a nightly reconciliation job
- Pessimistic row locks taken in a fixed order, checked with a 40-thread concurrency test
- Idempotency keys on every money operation
- Transactional outbox with Kafka, idempotent consumers and dead-letter topics
- JWT with refresh token rotation, Redis-based login throttling, Resilience4j around the external rates API

`Java 25` `Spring Boot 4` `PostgreSQL` `Kafka` `Redis` `Docker` `Testcontainers`

## Tech stack

- **Backend:** Java, Spring Boot, Spring Security, Spring Data JPA, Hibernate
- **Data and messaging:** PostgreSQL, Flyway, Redis, Apache Kafka
- **Testing:** JUnit 5, Mockito, Testcontainers
- **Tools:** Docker, Docker Compose, GitHub Actions, Maven, Git, IntelliJ IDEA

## Contact

Email: faxadev@gmail.com · Telegram: [@Fakhriyor13](https://t.me/Fakhriyor13)
