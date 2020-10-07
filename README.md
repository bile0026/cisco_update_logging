# cisco_update_logging

update logging from old server to new.

Adds a new syslog server with the `new_syslog` var, and removes an old server with `old_syslog`. If `old_syslog` is not defined the task will just update the new IP.
