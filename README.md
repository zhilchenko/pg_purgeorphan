pg_purgeorphan
==============

Tiny bash script that helps to find and drop orphan tables in PostgreSQL databases.

Orphan tables may occur when software doesn't properly cleans their stuff or if they were terminated. Orphan tables will be automatically removed by autovacuum, but before they can reduce disk performance by writing huge amount of messages to log files.
