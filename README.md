duso docker run -p 3306:3306 --name mysql \
-v /opt//docker/mysql/conf:/etc/mysql \
-v /opt//docker/mysql/logs:/var/log/mysql \
-v /opt//docker/mysql/data:/var/lib/mysql \
-e MYSQL_ROOT_PASSWORD=123456 \
-d mysql:8.0
