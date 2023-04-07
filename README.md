# fail2ban_pgbouncer
Ban bad login tries

Prerequisite are some settings in the pgbouncer.ini
logfile = /var/log/postgresql/pgbouncer.log
log_connections = 1
log_pooler_errors = 1
