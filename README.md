oracle-ant
==========

This is an ant script for backing up/restoring databases.
An oracle-client needs to be installed, because the 
script uses the commandline utilities of the oracle-client.
You need to set up your build.properties file with the 
appropriate settings.
If you configure multiple users, all of them will be created
with the same password.
Additionally you can configure users that should receive dba 
permissions.

I tested this on Windows with Oracle XE.
Use at your own risk.
