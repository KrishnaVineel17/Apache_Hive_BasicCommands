# Apache_Hive_BasicCommands
This repository consists of all basic instructions/commands that are used in Apache Hive. 

**Brief Description**: Apache Hive is an open source data warehouse software for reading, writing and managing large data set files that are stored directly in either the Apache Hadoop Distributed File System (HDFS) or other data storage systems such as Apache HBase. Hive enables SQL developers to write Hive Query Language (HQL) statements that are similar to standard SQL statements for data query and analysis.  It is designed to make MapReduce programming easier because you don’t have to know and write lengthy Java code. Instead, you can write queries more simply in HQL, and Hive can then create the map and reduce the functions.

Included with the installation of Hive is the Hive metastore, which enables you to apply a table structure onto large amounts of unstructured data. Once you create a Hive table, defining the columns, rows, data types, etc., all of this information is stored in the metastore and becomes part of the Hive architecture. Other tools such as Apache Spark and Apache Pig can then access the data in the metastore.

As with any database management system (DBMS), you can run your Hive queries from a command-line interface (known as the Hive shell), from a Java™ Database Connectivity (JDBC) or from an Open Database Connectivity (ODBC) application, using the Hive JDBC/ODBC drivers. You can run a Hive Thrift Client within applications written in C++, Java, PHP, Python or Ruby, similar to using these client-side languages with embedded SQL to access a database such as IBM Db2® or IBM Informix®.

Hive looks like traditional database code with SQL access. However, Hive is based on Apache Hadoop and Hive operations, resulting in key differences. First, Hadoop is intended for long sequential scans and, because Hive is based on Hadoop, queries have a very high latency (many minutes). This means Hive is less appropriate for applications that need very fast response times. Second, Hive is read-based and therefore not appropriate for transaction processing that typically involves a high percentage of write operations. It is better suited for data warehousing tasks such as extract/transform/load (ETL), reporting and data analysis and includes tools that enable easy access to data via SQL.

Source: https://www.ibm.com/analytics/hadoop/hive

