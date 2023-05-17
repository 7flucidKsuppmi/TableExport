## Percona Server for MongoDB 3.6.11-3.1 Is Now Available: What's New and How to Upgrade

 


 
# Percona Server for MongoDB 3.6.11-3.1 Is Now Available: What's New and How to Upgrade
 
Percona Server for MongoDB is a free and open-source drop-in replacement for MongoDB Community Edition that offers enterprise-grade features and performance. Percona Server for MongoDB 3.6.11-3.1 is the latest release of this software, and it is now available for download.
 
## Percona Server for MongoDB 3.6.11-3.1 Is Now Available


[**Download Zip**](https://www.google.com/url?q=https%3A%2F%2Ftinurll.com%2F2tKpTu&sa=D&sntz=1&usg=AOvVaw3YpHz4ZVEALrvrukR7qKdb)

 
In this article, we will highlight some of the new features and improvements in Percona Server for MongoDB 3.6.11-3.1, and show you how to upgrade from a previous version.
 
## New Features and Improvements in Percona Server for MongoDB 3.6.11-3.1
 
Percona Server for MongoDB 3.6.11-3.1 is based on MongoDB 3.6.11 and includes the following new features and improvements:
 
- A new configuration option `--auditFilter` that allows you to filter audit events based on various criteria, such as user, database, collection, operation, or result.
- A new configuration option `--enableMajorityReadConcern` that enables the majority read concern by default for all clients. This ensures that read operations return data that has been written to a majority of nodes in a replica set or a sharded cluster.
- A new configuration option `--oplogMaxSizeMB` that allows you to specify the maximum size of the oplog (the collection that stores the history of operations) in megabytes.
- A new configuration option `--replBatchLimitOperations` that allows you to limit the number of operations in a single batch applied by a secondary node during replication.
- A new configuration option `--replBatchLimitBytes` that allows you to limit the size of a single batch applied by a secondary node during replication.
- A new configuration option `--transactionLifetimeLimitSeconds` that allows you to specify the maximum time a transaction can run before it is aborted.
- A new configuration option `--wiredTigerConcurrentReadTransactions` that allows you to specify the maximum number of concurrent read transactions supported by WiredTiger storage engine.
- A new configuration option `--wiredTigerConcurrentWriteTransactions` that allows you to specify the maximum number of concurrent write transactions supported by WiredTiger storage engine.
- A new feature compatibility version (FCV) 3.6 that enables the use of new features and behavior changes introduced in MongoDB 3.6.
- A new command `setFeatureCompatibilityVersion` that allows you to change the FCV of your cluster.
- A new command `getParameter` that allows you to get the value of a configuration option.
- A new command `setParameter` that allows you to set the value of a configuration option.
- A new command `replSetResizeOplog` that allows you to resize the oplog without restarting the mongod process.
- A new command `abortTransaction` that allows you to abort an active transaction.
- A new command `commitTransaction` that allows you to commit an active transaction.
- A new command `startSession` that allows you to start a session for transactions.
- A new command `endSession` that allows you to end a session for transactions.
- A new aggregation stage `$lookup` that allows you to perform a left outer join with another collection.
- A new aggregation stage `$graphLookup` that allows you to perform a recursive search on a collection.
- A new aggregation stage `$facet` that allows you to perform multiple sub-pipelines on the same input documents.
- A new aggregation stage `$bucketAuto` that allows you to group documents into buckets with automatically determined boundaries.
- A new aggregation stage `$sortByCount` that allows you to group documents by a given expression and sort them by count.
- A new aggregation stage `$count` that allows you to count the number of documents in 0f148eb4a0
