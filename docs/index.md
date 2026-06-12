---
layout: default
---

# Mohit Khullar

Engineer at Bloomberg LP | Comdb2

---

## About

I work on **Comdb2**, a clustered RDBMS at Bloomberg LP.

---

## Published Work

- **HASQL: A Method of Masking System Failures** — EBDT 2019. Methodology for transparent failure masking in clustered database systems using Comdb2.
- **Comdb2: Bloomberg's Highly Available Relational Database System** — Very Large Data Base (VLDB), January 2016. Distributed database design with emphasis on geographical replication and high availability.

---

## Experience

**Bloomberg LP** (Aug 2010 - Present) — New York
- Contributor to Comdb2, working on various areas including database client libraries, stored procedures, replication, and authentication
- Designed and implemented **cdb2api**, the client library for connection pooling, discovery, and reconnect
- Designed and implemented **Lua-based stored procedures** for server-side transaction execution
- Designed and implemented **Consul-based service discovery** for database clients using DNS SRV/A record lookups with proximity-aware routing
- Designed and implemented **Expert Mode** — automated index recommendation engine that analyzes SQL queries and recommends optimal indexes using the cost-based optimizer
- Worked on **authentication & authorization** with caching and federated query (remsql) support
- Worked on **logical replication** for distributed consistency
- General feature development, performance optimization, and system maintenance

**Commvault** (Sep 2009 - Aug 2010) — New Jersey
- Member Technical Staff on backup systems

**Google** (Jul 2007 - Sep 2009) — Hyderabad, Telangana, India
- Software Engineer on data warehousing team

**Microsoft** (Feb 2006 - Jul 2007) — Hyderabad, Telangana, India
- Software Design Engineer on SQL CE team

**Hughes Software Systems** (Jan 2004 - Feb 2006) — Gurgaon, India
- Senior Software Engineer on SIP and MGCP servers

---

## Projects & Contributions

### Comdb2
Clustered RDBMS with Snapshot and Serializable Isolation, transparent client reconnect, and distributed transactions. Written in C, deployed across Bloomberg infrastructure.

- [Mohit Khullar](https://www.linkedin.com/in/mohitk)
- [My Contributions](https://github.com/bloomberg/comdb2/commits?author=mohitkhullar) — Commits and PRs
- [Comdb2 Documentation](https://mohitkhullar.github.io/comdb2/) — Architecture and development guides
- [Architecture Diagram](comdb2-architecture.html) — Interactive component diagram: cdb2api, sockpool, thread pool, query engine, storage engine, auth, replication
- [Life of a Query](comdb2-query-lifecycle.html) — Interactive animated walkthrough of a query from client to cluster and back
- [Life of an Expert Mode Query](comdb2-expert-mode.html) — How Comdb2 analyzes SQL and recommends optimal indexes
- [Life of a Stored Procedure](comdb2-stored-procedures.html) — From CREATE PROCEDURE through Lua VM execution to result emission

---

## Technologies & Skills

**Languages:** C, C++, Python, SQL, Shell
**Core Expertise:** Distributed systems, transaction processing, replication, concurrency control, high availability
**Tools & Platforms:** Git, Linux, GDB/debugging, performance profiling, CMake

---

## Connect

- [GitHub](https://github.com/mohitkhullar)
- [Comdb2 Contributions](https://github.com/bloomberg/comdb2/commits?author=mohitkhullar)

---
