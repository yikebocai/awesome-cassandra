Awesome Cassandra
=================
Cassandra documents and resouces

## Document

### Offical by DataStax
- [Cassandra 2.0](http://www.datastax.com/documentation/cassandra/2.0/index.html): offical document,show you the architecture, installation, database internals, configurations, operations, backup and restore data, etc.
- [CQL for Cassandra 2.0](http://www.datastax.com/documentation/cql/3.1/index.html): understand the SQL-like CQL of Cassandra
- [DataStax Java Driver 2.0 API](http://www.datastax.com/documentation/developer/java-driver/2.0/index.html): access to Cassandra with Java Driver.

### RDBMS -> Cassandra
- [RDBMS to NoSQL](http://www.datastax.com/relational-database-to-nosql): Your roadmap to understanding whether NoSQL is right for you.
- [MySQL to C*](http://planetcassandra.org/mysql-to-cassandra-migration/): mysql to cassandra migration guide

###  Use with Spark
- [Install Cassandra and Spark](http://tobert.github.io/post/2014-07-15-installing-cassandra-spark-stack.html): quick user guide for integration with Cassandra and Spark

## Tools
### Java Driver
- [DataStax Java Driver](https://github.com/datastax/java-driver): A Java client driver for Apache Cassandra. This driver works exclusively with the Cassandra Query Language version 3 (CQL3) and Cassandra's binary protocol.
- [Netflix Astyanax](https://github.com/Netflix/astyanax): Astyanax is a high level Java client for Apache Cassandra, based with Thrift protocal.
- [Hector](https://github.com/hector-client/hector) : Hector is a high level Java client for Apache Cassandra, based with Thrift protocal.

### ORM Driver

- [Caffinitas](http://caffinitas.org/mapper/): Caffinitas is an advanced object mapper for Apache Cassandra which has been especially designed to work with Datastax Java Driver 2.1+ against Apache Cassandra 2.1, 2.0 or 1.2.
- [Achilles](http://doanduyhai.github.io/Achilles/): Achilles is an open source Persistence Manager for Apache Cassandra,with the features like Advanced bean mapping (compound primary key, composite partition key, timeUUID...),Native collections and map support,and so.

### Model
- [basic-rules-of-cassandra-data-modeling](http://www.datastax.com/dev/blog/basic-rules-of-cassandra-data-modeling): Picking the right data model is the hardest part of using Cassandra. If you have a relational background, CQL will look familiar, but the way you use it can be very different.

### With Spark
- [DataStax Spark Cassandra Connector](https://github.com/datastax/spark-cassandra-connector): This library lets you expose Cassandra tables as Spark RDDs, write Spark RDDs to Cassandra tables, and execute arbitrary CQL queries in your Spark applications.
- [Stratio Deep](https://github.com/Stratio/stratio-deep): Deep is a thin integration layer between Apache Spark and several NoSQL datastores. We actually support Apache Cassandra and MongoDB, but in the near future we will add support for sever other datastores.

### With Search Engine
- [Solandra](https://github.com/tjake/Solandra): Solandra is a real-time distributed search engine built on Apache Solr and Apache Cassandra.

### Admin and Monitor
- [DataStax OpsCenter](http://www.datastax.com/what-we-offer/products-services/datastax-opscenter): Simplified management for DataStax Enterprise and Cassandra database clusters.
- [Cassandra Cluster Admin](https://github.com/sebgiroux/Cassandra-Cluster-Admin): Cassandra Cluster Admin is a GUI tool to help people administrate their Apache Cassandra cluster.
- [How to Monitor Cassandra](https://www.datadoghq.com/blog/how-to-monitor-cassandra-performance-metrics/): A guide to help you monitor Cassandra performance and work metrics regardles of which monitoring tool you choose to use.
