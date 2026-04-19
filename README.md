# Apache Derby (apache-derby)
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
