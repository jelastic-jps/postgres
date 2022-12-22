**Admin Panel**: [${nodes.sqldb.master.url}](${nodes.sqldb.master.url})  
**User**: webadmin  
**Password**: ${globals.pswd}  

**You can connect to PostgreSQL cluster through the Pgpool-II leader node**:    

**Pgpool-II Leader Node**: node${nodes.pgpool.master.id}-${env.domain}:5432    
**Credentials**: the same as for the PostgreSQL nodes

**Use this credentials to manage the Pgpool-II nodes in PgpoolAdmin**:
**PgpoolAdmin Url**: [${nodes.pgpool.master.url}](${nodes.pgpool.master.url})  
**PgpoolAdmin User**: postgres  
**PgpoolAdmin Password**: ${globals.pgpoolPasswd}   

* [Database Replication with PostgreSQL](https://docs.jelastic.com/postgresql-database-replication/)
* [Remote Access to PostgreSQL](https://docs.jelastic.com/remote-access-postgres/)
* [Import and Export Dump to PostgreSQL](https://docs.jelastic.com/dump-postgres/)
