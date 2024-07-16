# security-patch-rollout
Automation script to check for current patch version on a specific program, then compare it to the current release version. 

Script just checks for version and program existence on a list of computers called computers.txt. 
It uses WMI to query the machines, so WMI permissions should exiist for the queries and with the firewalls. 

Script may be redundant with patch management tools located on the enterprise server, but can still be useful. 
