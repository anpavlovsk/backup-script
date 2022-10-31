# backup-script
Simple Backup Bash Shell Script

````
admin@ip-172-31-89-163:~$ ./backup.sh
Files to be included: 7
Directories to be included: 13
Files archived: 7
Directories archived: 13
Backup of /home/admin completed!
Details about the output backup file:
-rw-r--r-- 1 admin admin 4363 Oct 31 19:15 /tmp/admin_home_2022-10-31_191555.tar.gz
````

````
alp@master1:~/backup-script$ ./backup.sh
find: '/home/alp/docker_volumes/grafana/png': Permission denied
find: '/home/alp/docker_volumes/grafana/alerting': Permission denied
find: '/home/alp/docker_volumes/grafana/csv': Permission denied
find: '/home/alp/docker_volumes/grafana/png': Permission denied
find: '/home/alp/docker_volumes/grafana/alerting': Permission denied
find: '/home/alp/docker_volumes/grafana/csv': Permission denied
Files to be included: 21109
Directories to be included: 3204
Files archived: 21112
Directories archived: 3201
Backup of /home/alp failed!
````
