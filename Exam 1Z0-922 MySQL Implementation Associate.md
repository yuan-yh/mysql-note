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


