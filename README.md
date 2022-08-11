Axum-based webserver based on rustdb database, with database browsing, timed jobs, password hashing, data compression, email transmission and database replication.

Command line arguments:

Master mode: address:port 

Default address:port is 0.0.0.0:80

Slave mode: address:port slave {master-URL} {login cookies}

In slave mode, the master database is replicated, and only GET queries are allowed.

crates.io : https://crates.io/crates/rustdb-axum-example