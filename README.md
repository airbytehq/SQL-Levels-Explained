# SQL-Levels-Explained

explaining sql levels based on one meme:

![image](https://user-images.githubusercontent.com/6764957/185188888-e06ef45b-c749-4f19-b918-1d3530f4f634.png)

## Level 0

- Concepts
  - ORMs
  - data types
  - foreign keys
  - indexes
- SQL
  - SELECT/INSERT/UPDATE/DELETE
  - ORDER BY
  - GROUP BY
  - LIMIT/OFFSET
  - CREATE TABLE
  - JOIN


## Level 1

- Concepts
  - ACID
  - transactions
  - keyset pagination
  - normal forms
  - computed columns
  - stored columns
  - inverted indexes
  - window functions
- SQL
  - outer joins
  - ORDER BY in aggregates
  - CTEs
  - query plans and EXPLAIN

## Level 2

- Concepts
  - Connection pools
  - plan hints
  - cursors
  - MVCC garbage collection
  - recursive CTEs
  - LATERAL joins
- Insights
  - ORMs create bad queries
  - optimizers don't work without table statistics
  - there are no non-null;able types
  
## Level 3

- Concepts
  - MERGE
  - COUNT(*) vs COUNT(1)
  - isolation levels
  - zigzag join
  - grouping sets, cube, rollup
  - write skew
  - partial indexes
  - sharding
  - phantom reads
  - triggers
- Insights
  - serializable restarts require retry loops on all statements
  - generator functions zip when cross joined
  
## Level 4

- Concepts
  - SELECT FOR UPDATE
  - denormalization
  - transaction contention
  - sargability
  - star schemas
  - utf8mb4
- Insights
  - Ascending Key Problem
  - Ambiguous network errors
  - NULLs in CHECK constraints are truthy
  
## Level 5

- Concepts
  - DEFERRABLE INITIALLY IMMEDIATE
  - MATCH PARTIAL foreign keys
  - EXPLAIN approximates SELECT COUNT(*)
  - causual reverse
- Insights
  - TPCC requires wait times
  - cost models don't reflect reality
  - 'null'::jsonb IS NULL = false

## Level 6
  
  
  
  
  
  
  
