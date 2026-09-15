# Jorge Herrera

Backend developer working with **Java and Spring Boot** on a production agricultural traceability platform: layered architecture, domain services, JPA/Hibernate over Oracle, REST APIs serving web and mobile clients.

Before writing software I spent more than a decade in IT infrastructure, networks and servers, in Cuba and Brazil. That background is why I tend to ask what a system does at 3am, not just whether the tests are green.

Based in Florianopolis, Brazil.

---

### Current focus

Clean architecture and domain modeling, database performance and query behaviour under load, and making tests prove something rather than merely pass.

---

### Projects

**[inconclusive](https://github.com/jorge-lherrera/inconclusive)** — TypeScript, Playwright, bash

A browser test that passes proves the DOM exists today. It does not prove your fix did anything. `inconclusive` runs the same spec against two live instances, the fix and the commit before it, and refuses to say *verified* unless the spec fails without the fix. Three outcomes instead of two, each with its own exit code, so a machine can insist on the difference between "my fix does not work" and "my test proves nothing".

**AgTrace core API** — Java, Spring Boot, Oracle (private)

Production traceability platform. REST endpoints over a layered architecture of use cases, domain services, entities, mappers and JPA repositories. Dashboards with sharing between users, PDF report generation and data export.

---

### Stack

**Backend** Java, Spring Boot, JPA/Hibernate, REST APIs, Maven

**Data** Oracle, PostgreSQL, SQL, query performance

**Practices** Clean Architecture, DDD, Hexagonal Architecture, JUnit, Testcontainers

**Frontend** TypeScript, React

**Tooling** Git, Docker, Playwright, bash

---

### Writing

I publish short technical posts on backend engineering, mostly about the gap between what a system appears to do and what it actually does. Recent ones: the N+1 query problem and why `@BatchSize` can make it worse, and why a plain `UNIQUE` index breaks on tables that use soft delete.

[LinkedIn](https://www.linkedin.com/in/jorge-lherrera)
