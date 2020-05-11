**DynamoDB** - https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Limits.html 

“The maximum item size in DynamoDB is **400 KB**, which includes both attribute name binary length (UTF-8 length) and attribute value lengths (again binary length). The attribute name counts towards the size limit.”

The limit is not 64KB - https://www.quora.com/Why-is-the-Amazon-DynamoDB-item-size-limited-to-64-Kilobytes

Secondary Indexes Per Table
* 5 local secondary indexes
* initial limit of 20 global secondary indexes per table

**Cassandra** - https://docs.datastax.com/en/cql-oss/3.x/cql/cql_reference/refLimits.html

* Cells in a partition: ~2 billion (2^31); single column value size: 2 GB ( **1 MB is recommended** )
* Blob size: 2 GB ( less than 1 MB is recommended)

**CosmosDB** - https://docs.microsoft.com/en-us/azure/cosmos-db/concepts-limits

* Maximum size of an item -	2 MB (UTF-8 length of JSON representation)
* API's:
  * Cassandra
  * MongoDB
  * Gremlin
  * Table
  * Etcd
