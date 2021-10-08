# Docker Mysql 설치

1. sudo docker run -d -p 9876:3306 -e MYSQL_ROOT_PASSWORD=password mysql:5.6

2. sudo docker exec -it ddd225c1d4e9 /bin/bash

3. mysql -u root -p

4. ```
   exit
     docker ps -a
     docker inspect ddd225c1d4e9
   ```