# Quorum-based voting in commit protocols
In a distributed database system, a transaction could be executing its operations at multiple sites. 
Since atomicity requires every distributed transaction to be atomic, 
the transaction must have the same fate (commit or abort) at every site. 
In case of network partitioning, sites are partitioned and the partitions may not be able to communicate 
with each other. This is where a quorum-based technique comes in. 
The fundamental idea is that a transaction is executed if the majority of sites vote to execute it.

This project has the prupose to learn about different voting protocols and improve my distributed security skills