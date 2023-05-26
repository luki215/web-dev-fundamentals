# Databases
- database types
    - relational
    - fulltext
    - document based
    - graph
    - vector

## Relational DBs
- tables, columns, rows
- representation
    - by BTrees
    - int, varchar, text
- data modeling
    - keys
        - primary, foreign
    - relations
        - 1:1, 1:M, M:M
    - normal forms
        - 1NF
        - 2NF
        - 3NF
- data consistency
    - SQL pool principles
    - race conditions
    - database locks
    - transactions
    - constraints
    - triggers
    - migrations
- performance & scaling
    - indexes
    - query planner
    - replicas (read, read-write)
- postgres
    - functions
    - users&roles
    - plugins
        - example: pg_trgm, PostGIS
    - backup & restore
    - working with `psql` - localy & remotely
- SQL
    - `CREATE TABLE`
    - `DROP TABLE`
    - `INSERT INTO`
    - `SELECT FROM`
        - `JOIN`
            - `LEFT/RIGHT OUTER`, `INNER`
        - `WHERE`
            - `IN`, `ANY`, `LIKE`, `SOME`, `ALL`
        - `GROUP_BY`
        - `HAVING`
    - `UPDATE`
    - `DELETE`

## Fulltext
- ElasticSearch - why, when and basics how to use it
    - indexing
    - scoring, weights

## Document based
- documents, collections
- strengths, usecases
    - price, scaling
    - structured data
- data modeling
- querying

# Graph
- strengths, usecases
    - 
# Vector
- strengths, usecases
    - AI
    - fast similarity querying