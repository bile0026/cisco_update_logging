# cisco_update_logging

update logging from old server to new.

Adds a new syslog server with the `new_syslog` var, and removes an old server with old_syslog.

set `remove_old` to true to remove an old server. Otherwise it will just add the new server by default.
