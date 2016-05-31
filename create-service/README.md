# Linux

Example file to place a php script as a service on CentOS 6.

- Copy to /etc/init.d/new-service-php

- Change {PATH} to file path 
- Change new-service-php to file name of your script

# Use
- /etc/init.d/new-service-php status
- /etc/init.d/new-service-php start
- /etc/init.d/new-service-php stop
- /etc/init.d/new-service-php restart


# Start with SO
- chkconfig --level 345 new-service-php on
