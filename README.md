# Jorge Herrera

Backend developer on a production agricultural traceability platform, building the API behind its web and mobile applications.

---

### Projects

**[ColdChain](https://github.com/jorge-lherrera/coldchain-api)** — Java 25, Spring Boot 4, Oracle 23ai

Cold chain custody and compliance API. A pharmaceutical shipment passes from hand to hand between organizations, its temperature is measured for the entire journey, and when it closes it either has a certificate or it doesn't.

Five modules that talk through domain events, hexagonal inside: a pure-Java domain model, a repository port it declares, and a JPA adapter behind it. Module boundaries are declared in code, and an import that crosses one fails the build. Every rule in the catalogue has a machine that checks it, and the walkthrough in the README runs in CI against an Oracle raised from nothing, it fails if the verdict is not the one written down.

**[inconclusive](https://github.com/jorge-lherrera/inconclusive)** — TypeScript, bash

A test that passes proves the DOM exists today. It does not prove your fix did anything. This runs the same spec against two live instances, the fix and the commit before it, and refuses to call it verified unless the spec fails without the fix.

Three outcomes instead of two, each with its own exit code, so a machine can insist on the difference between "my fix does not work" and "my test proves nothing".


---

### Stack

**Backend** Java, Spring Boot, JPA/Hibernate, REST APIs

**Data** Oracle, PostgreSQL, SQL, Flyway

**Practices** Clean Architecture, DDD, Hexagonal Architecture, Spring Modulith, ArchUnit, JUnit, Testcontainers

**Also** TypeScript, React, Git, Docker

---

Previously more than a decade in IT infrastructure and networks.

[LinkedIn](https://www.linkedin.com/in/jorge-lherrera)
