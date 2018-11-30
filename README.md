# CMPE 273 Demo 

#### Team Alpha Group Member Names
- Yang Chen
- Huy Vo
- Chungchen Ran
- Kevin Ta
- Chunchen Lin

#### Notes 
```
NewSQL is a class of modern relational database management systems that seek to provide the same scalable performance of NoSQL systems for 
online transaction processing (OLTP) read-write workloads while still maintaining the ACID guarantees of a traditional database system. 

The lack of transactions in Bigtable led to frequent complaints from users, so Google made distributed transactions central to Spanner's design. 



Based on its experience with Bigtable, Google argues that it is better to have application programmers deal with 
performance problems due to overuse of transactions as bottlenecks arise, rather than always coding around the lack of transactions. 

Spanner uses the Paxos algorithm as part of its operation to shard data across hundreds of datacenters.
It makes heavy use of hardware-assisted clock synchronization using GPS clocks and atomic clocks to ensure global consistency.

About Spanner: 

Schema
SQL
Consistency 
Availability
Scalability
Replication 
```
