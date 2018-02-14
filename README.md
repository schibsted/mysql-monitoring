# mysql-monitoring

Some mysql monitoring plugins

For now this is for monitoring mysql connection usage by user / database / client host.  The target environment is where a shared / common mysql server with max_user_connections set golbaly or pr. user.

Next up, a nagios plugin to monitor these limited users so ops can discover if the app gets close to their connection limits.
