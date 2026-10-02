## Denys Lindenson <sub>aka wolper</sub>

**Software Architect · Senior Software Engineer · Team Lead** — Alicante, Spain

> *Prompts are guidance. Architecture is a contract.*

Thirty years in software — from C and assembly in the process-control system of a chemical plant
to high-load distributed platforms in telecom, banking and e-commerce.
I'm at home where the CAP theorem actually matters: transactions and sagas, distributed locks,
event streams, idempotency, and the trade-offs between them.
A dedicated Java engineer who enjoys reactive and functional styles, and writes Go when it fits.

---

### Now

**Co-founder & Software Architect — Hormigas** (marketplace startup, 2025–)
High-load marketplace platform built on DDD and event-driven patterns: Java · Go · Quarkus,
a transactional payment subsystem with idempotency and anti-double-charge guarantees,
real-time messaging, Ory Kratos / OAuth2 / OIDC identity, Kafka as the event backbone.

**Senior Software Engineer — Vodafone** (2023–)
Multi-market conversational orchestration platform behind TOBi, Vodafone's virtual assistant:
session lifecycle, dialog management, failover, distributed locks, consistent-hash routing.
Among the first at Vodafone to integrate OpenAI; built an internal enterprise alternative to Spring AI.
Drove the move to Java 21 virtual threads, plus JVM, GC and Kubernetes tuning.

### Before

- **iSolutions.IO** (2019–2022) — banking and payment platforms, city-scale CRM, Camunda orchestration, fraud detection
- **Institute of Industrial Economics, NAS of Ukraine** (2017–2019) — [SiForeca](https://github.com/wol-pruebas/si-foreca), a national platform for economic forecasting and large-scale data processing
- **Zuma Energy, Nigeria** (2014–2016) — technical consultant and digitalization lead on a 1,200 MW power project
- Earlier — banking process automation, university teaching, industrial process control

PhD in Economics (mathematical economics, econometrics) · Engineer, Donetsk National Technical University

---

### Open source

| Project | What it shows |
|---|---|
| [**big-messenger**](https://github.com/Lindenson/big-messenger) | Reactive message-delivery engine (Quarkus · Mutiny · PostgreSQL · Redis). Committed before ACK, at-least-once with leases and an outbox. Measured over real WebSockets: **~3,000 msg/s end-to-end, p95 20 ms, zero loss** |
| [**architecture-workspace**](https://github.com/Lindenson/architecture-workspace) | A living digital twin of a software system: MCP servers (Spring AI, Java 21) feed Claude facts from Jira, Git, SonarQube and jQAssistant, so architectural answers come from the real code |
| [**karate-authflow**](https://github.com/Lindenson/karate-authflow) | Transparent auth layer for Karate API tests — Basic, Ory Kratos sessions, encrypted device onboarding — so tests describe behaviour, not credentials |
| [**garageAlarms**](https://github.com/wol-micro/garageAlarms) | ESP32-S3 firmware in service: smoke and motion alarms to Telegram with a power-cut-safe delivery queue |

### How I work

- **Architecture is code.** ArchUnit and jQAssistant rules fail the build — especially when AI agents write the code.
- **Guarantees are written down and tested.** If the README promises it, an e2e test checks it.
- **Measure, then claim.** Load tests before performance numbers.
- **Leave notes for whoever comes next.** ADRs, C4 models, design essays, mentoring.

### Toolbox

**Languages** Java · Kotlin · Go · Python · TypeScript · Scala · C
**Backend** Spring Boot / Cloud · Quarkus · Mutiny · Akka Streams · Camunda
**Data & messaging** PostgreSQL · MongoDB · Redis · Kafka · Elasticsearch · MinIO
**Security** Ory Kratos / Hydra · OAuth2 / OIDC · JWT · Signal protocol (X3DH, Double Ratchet)
**Platform** Kubernetes · AWS (EKS, RDS, S3, Lambda) · GitOps CI/CD · observability
**Quality** JUnit 5 · Karate · Gatling · ArchUnit · jQAssistant · SonarQube
**AI** OpenAI · Claude · MCP · Spring AI
**Embedded** ESP32 · STM32 · Zigbee · MQTT

---

🔌 [wol-micro](https://github.com/wol-micro) — smart home & microcontrollers ·
🎮 [wol-juegos](https://github.com/wol-juegos) — small games, [playable in the browser](https://wol-juegos.github.io/TresEnRaya/) ·
🧪 [wol-pruebas](https://github.com/wol-pruebas) — drafts and experiments
