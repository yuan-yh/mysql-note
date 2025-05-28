## Course Exercise
When is MySQL Enterprise Support available?
- 24 hours a day, 7 days a week

What does the Oracle commercial licensing option allow businesses to do?
- Allows businesses to use MySQL code in their products and keep their code private

Which statement is true about MySQL Workbench Enterprise?
- It simplifies MySQL database migrations.

How many major editions does MySQL offer?
- Two

Which service does MySQL HeatWave offer?
- A fully managed MySQL service

For which language does MySQL Shell offer support?
- Python

Which installation method requires that you manually configure the service user?  
- binary archive  

How often are MySQL Innovation versions released?
- Every quarter

Which permissions are required for the MySQL service user?
- Data directory privileges

Which statement is true about the data directory?
- It is a mandatory setting in the my.cnf file.

Which statement is true about upgrades?
- You can upgrade MySQL while the server is offline by replacing the binaries with new versions.

What is performed by the JOIN clause in SQL?
- Connects rows from two or more tables on some condition

Which statement is true about PRIMARY indexes?
- PRIMARY index values are replicated to every secondary index.

Which data type stores string values?
- ENUM

What can you accomplish using MySQL Partitioning?
- Specify a physical file for each row based on a rule.

Which product can mitigate the risk of SQL Injection attacks?
- MySQL Enterprise Firewall

What is the default MySQL authentication plugin used to encrypt passwords?
- caching_sha2_password

Which MySQL Enterprise feature supports Kerberos, PAM, and FIDO?
- Authentication

Which type of compliance do GDPR, HIPAA, FERPA, and GLBA impose that MySQL can implement?
- Regulatory

Which statement about dynamic privileges is true?
- They are assigned by the server, a plugin, or a component at load time.

Which two formatting options are supported by MySQL Enterprise Audit?
- XML, JSON

Against what does MySQL Enterprise Firewall provide real-time protection?
- SQL Injection

What file can you encrypt using MySQL Enterprise Transparent Data Encryption (TDE)?
- Tablespace File

When using MySQL Enterprise Transparent Data Encryption (TDE), which key must be stored outside the database?
- Master

In which two ways can you install the MySQL Enterprise Masking and De-Identification feature?
- Component, Plugin

Which statement is true about the mysqldump utility?
- The mysqldump output is a human-readable text file with SQL statements.

What is the MySQL Enterprise Backup utility designed for?
- Create Physical backup of MySQL systems

What must you do to restore from a backup using MySQL Enterprise Backup?
- Remove any previous files from the MySQL data directory.

How does MySQL Enterprise Backup support optimistic backup?
- It records all data including data from busy tables.

What makes a database backup effective?
- Being able to restore the backup data

What uses the Relay Log?
- Replica

Which thread maintains an open connection to the source when the replica connects and is used to send the binary log contents from the source to a replica?
- I/O binlog dump thread (I feel either the statement or the answer is wrong though -> this statement leads to `I/O thread`)

Which thread is responsible for taking a copy of the binary log events from the source and writing those to a relay log?
- I/O thread

Which thread reads the relay log and executes the transactions that it contains on the replica?
- SQL thread

What is one requirement on the source to enable source-replica replication?
- Source must have binary logging enabled.

What is the Recovery Point Objective (RPO) or data loss tolerance within a region when using MySQL InnoDB Cluster?
- Zero

Which MySQL component redirects application queries to available nodes in an InnoDB Cluster?
- MySQL Router

Which MySQL component automates InnoDB Cluster creation and makes managing the Cluster easy?
- MySQL Shell

Which two are NOT used when setting up MySQL InnoDB ReplicaSet?
- MySQL Workbench, MySQL Group Replication

Which MySQL component provides automatic failover when using InnoDB Cluster?
- MySQL Group Replication

What does the MySQL Performance Schema do?
- It provides statistics about your MySQL instance.

Slow query log is used to capture long-running SQL statements. Which is NOT logged by default?
- Administrative statements or Queries that do not use an index

What can you do with MySQL in Oracle Enterprise Manager?
- Monitor MySQL Performance.

Which part of the database is the highest source of Database Performance Problems?
- The SQL, index, and Schema group

Which MySQL schema has its own dedicated storage engine?
- Performance schema

Which database platform does HeatWave use to store OLTP data?
- MySQL

Which HeatWave feature allows you to query data from Object Storage?
- Lakehouse

Which machine learning technique is NOT supported by HeatWave ML?
- Clustering

Which action can you perform using the HeatWave service web-based console?
- Deploy your instances and manage their backups.

From which cloud service can you use HeatWave?
- Oracle Cloud Infrastructure, Amazon Web Services (AWS) or Azure

Which MySQL client program would you use to emulate client load?
- mysqlslap

Assume that the database world exists and does not contain a table called poi. You execute this statement immediately after logging in:
CREATE TABLE IF NOT EXISTS world.poi (x INT, y INT, z INT);
- The poi table is created in the world database.

Which two statements about the download of MySQL Enterprise Backup are correct?
- MySQL Enterprise Backup can be downloaded from My Oracle Support (MOS).
- MySQL Enterprise Backup is a separate package from MySQL Enterprise Edition. It can be downloaded from https://edelivery.oracle.com.

-----------------------------------------------------------------------------------------------------------------------------------------
## Mockup

By using MySQL replication, data can be replicated from source to replica. What are two advantages of MySQL replication?
- Scale out, Analytics

The replica connects to the source and asks for updated records. What command was issued for this to happen?
- START REPLICA

What is the benefit of using MySQL Enterprise Thread Pool?
- Scalability

Which MySQL Enterprise Edition component or plug-in replaces real values with substitutes?
- MySQL Enterprise Masking

Which MySQL Enterprise Security tool allows DBAs to track user activities such as Who, What, When, How, Status, From Where, DB version, OS version?
- MySQL Enterprise Audit

Which three languages are supported by MySQL Shell?
- JavaScript, Python, SQL

Which three operating systems are supported by MySQL?
- macOS, Windows, Linux

Where would you look to find easy-to-understand views that contain information about IO hot spots, locking, and costly SQL statements?
- sys schema

Which schema provides runtime statistics to monitor MySQL server execution at a low level?
- Performance schema

Which MySQL storage engine is fully ACID compliant and also the default when creating a table?
- InnoDB

Which backup method allows you to back up only the data that has changed since the last FULL backup?
- Incremental

Which three components are part of the core MySQL database architecture?
- Optimizer, Parser, Storage Engine

How would you replicate between two InnoDB Clusters?
- Set up MySQL InnoDB ClusterSet.

Which three components can MySQL InnoDB Cluster use to achieve database high availability?
- MySQL Servers with Group Replication, to replicate data to all members of the cluster
- MySQL Shell, to create and administer InnoDB Cluster using the built-in AdminAPI
- MySQL Router, to ensure client requests are load balanced and routed to the correct server

Which statement would you use to add a role in MySQL?
- CREATE ROLE

Which uniquely defines each user account identity in MySQL?
- Username and host

What statement allows you to assign a password to a MySQL user account?
- SET PASSWORD

What type of backups do mydumper and MySQL Shell take?
- Logical

Your container has a 7.5 GB MySQL database. They are using mydumper to back up their database, which is taking hours to complete. What can your container do to decrease backup time?
- Use MySQL Enterprise Backup.

Which log file is used to perform Point-in-Time Recovery (PITR)?
- Binary log

Which data type would you use for a column to store large chunks of binary data (e.g., images, audio)?
- BLOB

What are the minimum and maximum number of MySQL Servers you can have in an InnoDB Cluster?
- Minimum 3 and maximum 9

What does the InnoDB Cluster provide?
- Automatic failover

MySQL has many variables. Which two are mandatory MySQL variables?
- datadir, basedir

Which monitoring tool is included with MySQL Enterprise Edition?
- Oracle Enterprise Manager

You just installed MySQL using a package manager on Linux. Where is the default data directory (datadir) located that holds InnoDB log files (e.g., undo/redo logs)?
- /var/lib/mysql

When creating a table, which data type would you use for a column that contains only whole numbers (no fractions)?
- INT

Which replication is the default in MySQL?
- Asynchronous

Which statement is true about MySQL Replication?
- Multiple replicas are possible.

