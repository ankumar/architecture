| Database type | Databases        |                  | Formal methods                           | 
| --------------| ---------------- | ---------------- | ---------------- |
|               |                  |                  | https://github.com/lemmy/awesome-tlaplus |
|               |                  |                  | https://github.com/jepsen-io/jepsen |
|               |                  |                  | https://github.com/jepsen-io/elle |
| 1. Relational | | | |
|  | [PostgreSQL](https://dbdb.io/db/postgresql) | | |
|  |  [MySQL](https://dbdb.io/db/mysql) | Sharding - https://vitess.io/ |  |
|  | | | |
| 2. Key-Value |  |  | |
|  | [Cassandra](https://dbdb.io/db/cassandra) | | |
|  | [CosmosDB](https://dbdb.io/db/cosmos-db) |  | TLA+ - https://docs.microsoft.com/en-us/azure/cosmos-db/consistency-levels |
|  | | | |
| 3. In-Memory | | | |
|  | [Redis](https://dbdb.io/db/redis) | | |
|  | [Memcached](https://dbdb.io/db/memcached)| | |
| 4. Document | | | |
|  | | | |
| 5. Graph | | | |
|  | | | |
| 6. Timeseries | | | |
|  | | | |
| 7. Ledger | | | |
|  | | | |

1. [Database of Databases](https://dbdb.io/)
2. [A DB Ranking](https://db-engines.com/en/ranking)
3. [Database Application Catalog](https://db.cs.cmu.edu/projects/dbac/)
* [DynamoDB](https://aws.amazon.com/dynamodb/)
  * [Global Tables](https://aws.amazon.com/dynamodb/global-tables/) 
  * Single Table Design - https://www.alexdebrie.com/posts/dynamodb-single-table/
    * GraphQL/Single Table - https://www.goingserverless.com/blog/single-table-dynamodb-for-appsync
    * GraphQL/Multi Table - https://www.alexdebrie.com/posts/dynamodb-single-table/#graphql--single-table-design
  * https://dynobase.dev/
    * [AWS Workbench](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/workbench.html)
* [Document Databases](https://db.cs.cmu.edu/projects/document-databases/)
* [Big Table](https://www.cs.rutgers.edu/~pxk/417/notes/content/bigtable.html): "Containers" like keyspace is the top-level database object that controls the replication for the object it contains at each datacenter in the cluster. Keyspaces contain tables, materialized views and user-defined types, functions and aggregates. Typically, a cluster has one keyspace per application. Since replication is controlled on a per-keyspace basis, store data with different replication requirements (at the same datacenter) in different keyspaces. Keyspaces are not a significant map layer within the data model.
  * [Cassandra](https://www.datastax.com/blog/2020/05/why-astra-good-cassandra)
  * [ScyllaDB](https://www.scylladb.com/2020/05/07/introducing-scylla-open-source-4-0/)
* [Spanner](https://static.googleusercontent.com/media/research.google.com/en//archive/spanner-osdi2012.pdf) is a relational database with 99.999% availability which means it is down roughly 5 mins a year
  * [CockroachDB](https://www.cockroachlabs.com/docs/stable/architecture/overview.html)
  * [YugabyteDB](https://docs.yugabyte.com/latest/comparisons/)
* [CosmosDB](https://docs.microsoft.com/en-us/azure/cosmos-db/consistency-levels)
