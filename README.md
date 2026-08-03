# Apache Derby (apache-derby)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Apache Derby is an open-source relational database implemented entirely in Java, formerly governed by the Apache Software Foundation (retired October 2025). It provides a small-footprint (~3.5MB) database engine with full SQL support, JDBC compliance, ACID transactions, stored procedures, and triggers. Derby operates in both embedded mode (bundled inside Java applications) and client/server mode via the Derby Network Server.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/apache-derby/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Apache, Database, Embedded, Java, JDBC, Open Source, Relational, SQL

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Derby
Derby provides a standard JDBC API for database operations in both embedded (org.apache.derby.jdbc.EmbeddedDriver) and client/server (org.apache.derby.jdbc.ClientDriver) modes, supporting full SQL, stored procedures, triggers, views, indexes, and complete ACID transaction management. The Derby Network Server also exposes a simple text-based administrative protocol.

**Human URL:** [https://db.apache.org/derby/manuals/index.html](https://db.apache.org/derby/manuals/index.html)

#### Tags:

 - Embedded, Java, JDBC, Network Server, SQL, Transactions

#### Properties

- [Documentation](https://db.apache.org/derby/manuals/index.html)
- [GettingStarted](https://db.apache.org/derby/quick_start.html)
- [APIReference](https://db.apache.org/derby/javadoc/publishedapi/jdbc4/)
- [GitHubRepository](https://github.com/apache/derby)
- [derby (Maven Central)](https://mvnrepository.com/artifact/org.apache.derby/derby)
- [derbyclient (Maven Central)](https://mvnrepository.com/artifact/org.apache.derby/derbyclient)
- [derbynet Network Server (Maven Central)](https://mvnrepository.com/artifact/org.apache.derby/derbynet)
- [Connection Config](https://raw.githubusercontent.com/api-evangelist/apache-derby/refs/heads/main/json-schema/apache-derby-connection-config-schema.json)
- [Table Info](https://raw.githubusercontent.com/api-evangelist/apache-derby/refs/heads/main/json-schema/apache-derby-table-info-schema.json)
- [JSONStructure](https://raw.githubusercontent.com/api-evangelist/apache-derby/refs/heads/main/json-structure/apache-derby-connection-config-structure.json)
- [JSONStructure](https://raw.githubusercontent.com/api-evangelist/apache-derby/refs/heads/main/json-structure/apache-derby-table-info-structure.json)
- [JSONLD](https://raw.githubusercontent.com/api-evangelist/apache-derby/refs/heads/main/json-ld/apache-derby-context.jsonld)
- [Example](https://raw.githubusercontent.com/api-evangelist/apache-derby/refs/heads/main/examples/apache-derby-connection-config-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/apache-derby/refs/heads/main/examples/apache-derby-table-info-example.json)

## Common Properties

- [Portal](https://db.apache.org/derby/)
- [Documentation](https://db.apache.org/derby/manuals/index.html)
- [GettingStarted](https://db.apache.org/derby/quick_start.html)
- [GitHubRepository](https://github.com/apache/derby)
- [GitHubOrganization](https://github.com/apache)
- [StackOverflow](https://stackoverflow.com/questions/tagged/apache-derby)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/apache-derby/refs/heads/main/vocabulary/apache-derby-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Embedded Mode | Derby can be embedded directly in Java applications as a library, providing a zero-administration database with no separate server process required. |
| Client/Server Mode | Derby Network Server supports multiple concurrent JDBC clients connecting over TCP/IP using the Derby Network Client driver. |
| Full SQL Support | Supports ANSI SQL-92 with extensions including subqueries, joins, constraints, triggers, views, stored procedures, and user-defined functions. |
| ACID Transactions | Full ACID transaction support with row-level locking, MVCC-style isolation levels, and savepoints. |
| Small Footprint | The base Derby engine and embedded JDBC driver is approximately 3.5MB, making it suitable for desktop and embedded applications. |
| Java Stored Procedures | Supports Java-based stored procedures and functions callable directly from SQL using standard JDBC interfaces. |

## Use Cases

| Name | Description |
|------|-------------|
| Embedded Application Database | Embed Derby in desktop Java applications, IDEs, or tools that need a local SQL database without a separate server. |
| Unit and Integration Testing | Use Derby as an in-memory or on-disk test database for Java application integration tests with JDBC. |
| Lightweight Development Database | Use Derby as a development database when production uses a heavier RDBMS, without installing MySQL or PostgreSQL. |
| Data Migration and ETL | Use Derby as a staging database for ETL processes in Java-based data pipelines. |

## Integrations

| Name | Description |
|------|-------------|
| JDBC | Derby provides JDBC 4.0/4.1/4.2 compliant embedded and network client drivers. |
| Spring Framework | Commonly used with Spring DataSource and JPA/Hibernate for test database configuration. |
| Hibernate / JPA | Derby has a Hibernate dialect (DerbyDialect) for ORM integration. |
| Apache Maven | Derby artifacts are available on Maven Central under org.apache.derby group ID. |
| Eclipse IDE | Eclipse IDE includes Derby as a built-in SQL explorer and development database. |

## Artifacts

Machine-readable schemas for Apache Derby configuration and metadata models.

### JSON Schema

- [Connection Config](json-schema/apache-derby-connection-config-schema.json)
- [Table Info](json-schema/apache-derby-table-info-schema.json)

### JSON Structure

- [Connection Config](json-structure/apache-derby-connection-config-structure.json)
- [Table Info](json-structure/apache-derby-table-info-structure.json)

### JSON-LD

- [Apache Derby](json-ld/apache-derby-context.jsonld)

### Examples

- [Connection Config](examples/apache-derby-connection-config-example.json)
- [Table Info](examples/apache-derby-table-info-example.json)

## Vocabulary

- [Apache Derby Vocabulary](vocabulary/apache-derby-vocabulary.yaml) — Taxonomy mapping 5 resources, 5 actions, and 2 personas for the Apache Derby embedded relational database

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
