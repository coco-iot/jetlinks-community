```shell
cd docker/run-all
sudo docker-compose up -d

http://82.157.54.206:8848/
http://82.157.54.206:9000
admin
admin

http://localhost:8000/jetlinks/authorize/login
http://82.157.54.206:8848/jetlinks/authorize/login
http://82.157.54.206:9000/jetlinks/authorize/login

sudo docker exec -it jetlinks-ce-postgres bash
psql -U postgres
su postgres
psql
\l
\c jetlinks
\dt
\d dev_product
select * from dev_product;
```