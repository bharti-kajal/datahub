# DataHub

Master databases, one module at a time.

DataHub is a structured, module-wise learning repository covering database fundamentals, database technologies, ORMs, ODMs, schema design, performance optimization, and advanced database engineering.

The goal is to understand not only how to use databases, but also how they work internally and how to choose the right solutions for real-world applications.

## Learning Modules

### 1. Database Fundamentals
- Database basics and terminology
- DBMS, RDBMS, and NoSQL
- Database architecture and storage
- Tables, schemas, and data types
- Keys, constraints, and relationships
- Normalization and data modeling
- Transactions and ACID properties
- Indexing and query execution

### 2. Database Technologies

Each database has its own directory, divided into modules from beginner to advanced.

- PostgreSQL — SQL, data types, JSONB, indexes, transactions, query planning, replication, and optimization.
- MySQL — SQL fundamentals, storage engines, indexes, transactions, replication, and optimization.
- MongoDB — Documents, collections, CRUD, aggregation, schema design, indexing, and sharding.
- Redis — Data structures, caching, expiration, persistence, transactions, and replication.

Additional databases and technologies can be added as learning progresses.

### 3. ORMs, ODMs, and Database Access

Each ORM or ODM will have its own directory, with independent modules and submodules.

- Sequelize — Models, associations, validations, hooks, queries, transactions, and migrations.
- Prisma — Schema, models, relations, Client, queries, migrations, and performance.
- Mongoose — Schemas, models, validation, middleware, population, aggregation, and indexes.
- TypeORM — Entities, repositories, relations, migrations, and transactions.
- Drizzle ORM — Schema definitions, queries, relations, migrations, and type safety.

Database drivers, connection pooling, raw queries, and ORM internals will also be covered.

### 4. Cross-Database Concepts
- SQL vs NoSQL
- Relational vs document data modeling
- B-tree vs GIN vs Hash indexes
- Transactions and concurrency
- Consistency and isolation levels
- Replication and sharding
- Caching and performance
- Database security and backups

### 5. Practical Engineering Scenarios
- Designing database schemas from requirements
- Preventing duplicate usernames
- Handling concurrent wallet updates
- Debugging slow queries
- Designing scalable pagination
- Choosing between SQL and NoSQL
- Investigating ORM-generated queries
- Solving real-world data consistency problems

## Repository Structure

The repository is organized hierarchically:

```text
datahub/
├── 00-database-fundamentals/
│   ├── 01-introduction/
│   ├── 02-database-architecture/
│   ├── 03-data-modeling/
│   ├── 04-keys-and-constraints/
│   ├── 05-normalization/
│   ├── 06-transactions-and-acid/
│   └── 07-indexing-basics/
│
├── 01-databases/
│   ├── postgresql/
│   │   ├── 01-fundamentals/
│   │   ├── 02-sql/
│   │   ├── 03-schema-design/
│   │   ├── 04-data-types/
│   │   ├── 05-indexes/
│   │   ├── 06-transactions/
│   │   ├── 07-query-optimization/
│   │   └── 08-advanced/
│   │
│   ├── mysql/
│   │   ├── 01-fundamentals/
│   │   ├── 02-sql/
│   │   ├── 03-schema-design/
│   │   ├── 04-indexes/
│   │   ├── 05-transactions/
│   │   └── 06-advanced/
│   │
│   ├── mongodb/
│   │   ├── 01-fundamentals/
│   │   ├── 02-crud-operations/
│   │   ├── 03-document-modeling/
│   │   ├── 04-aggregation/
│   │   ├── 05-indexes/
│   │   ├── 06-replication-and-sharding/
│   │   └── 07-advanced/
│   │
│   └── redis/
│       ├── 01-fundamentals/
│       ├── 02-data-structures/
│       ├── 03-caching/
│       ├── 04-expiration-and-eviction/
│       ├── 05-persistence/
│       └── 06-advanced/
│
├── 02-orms-and-odms/
│   ├── sequelize/
│   │   ├── 01-fundamentals/
│   │   ├── 02-models-and-fields/
│   │   ├── 03-associations/
│   │   ├── 04-queries/
│   │   ├── 05-validations-and-hooks/
│   │   ├── 06-transactions/
│   │   ├── 07-migrations/
│   │   └── 08-advanced/
│   │
│   ├── prisma/
│   │   ├── 01-fundamentals/
│   │   ├── 02-schema-and-models/
│   │   ├── 03-relations/
│   │   ├── 04-crud-and-queries/
│   │   ├── 05-migrations/
│   │   ├── 06-transactions/
│   │   └── 07-advanced/
│   │
│   ├── mongoose/
│   │   ├── 01-fundamentals/
│   │   ├── 02-schemas-and-models/
│   │   ├── 03-validation-and-middleware/
│   │   ├── 04-queries/
│   │   ├── 05-population-and-aggregation/
│   │   ├── 06-indexes/
│   │   └── 07-advanced/
│   │
│   ├── typeorm/
│   └── drizzle/
│
├── 03-database-concepts/
│   ├── indexing/
│   ├── transactions/
│   ├── concurrency/
│   ├── replication/
│   ├── sharding/
│   └── performance/
│
├── 04-scenario-based-learning/
├── 05-comparisons/
├── 06-practical-projects/
├── 07-tools-and-resources/
└── README.md
```

## How Each Module Will Be Documented

Each module will contain individual topic files covering:

1. Basics — Definition, terminology, and purpose.
2. Internal working — How the feature works behind the scenes.
3. Syntax and examples — Practical commands and code.
4. Real-world usage — Where and why engineers use it.
5. Advantages and trade-offs — Performance, limitations, and alternatives.
6. Common mistakes — Bugs, pitfalls, and misconceptions.
7. Scenario-based questions — Engineering problems and solutions.
8. Advanced concepts — Optimization, internals, scalability, and edge cases.
9. Hands-on practice — Exercises with solutions and test results.
10. References — Official documentation and related modules.

## Learning Principles

- Learn module by module, progressing from beginner to advanced.
- Keep database-specific concepts inside their respective database folders.
- Keep ORM-specific features inside their respective ORM or ODM folders.
- Document shared concepts separately and link to related modules.
- Include practical examples and scenario-based questions.
- Track completed modules and revisit important concepts.

## Goal

Build a long-term database engineering reference that connects database theory, practical implementation, ORM behavior, performance optimization, and real-world system design.

One repository. Multiple technologies. Structured learning from fundamentals to advanced engineering.