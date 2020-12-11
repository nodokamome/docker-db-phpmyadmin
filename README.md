# docker-db-phpmyadmin
docker-composeでMariaDBとphpMyAdmin環境を構成できます。

phpMyAdminにアクセスするにはnginx-proxyのネットワークが構築されていることが前提です。
なお、phpMyAdminのアクセスURLは.envで設定したドメインとなっています。
ポートでアクセスを希望の場合は、port:で指定してください。

### 使用Image
```
▼MariaDB
https://hub.docker.com/_/mariadb

▼phpMyAdmin
https://hub.docker.com/_/phpmyadmin

▼nginx-proxy
https://hub.docker.com/r/jwilder/nginx-proxy
```
