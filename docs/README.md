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

https://www.sjkjc.com/postgresql/show-tables/#:~:text=PostgreSQL%20%E6%8F%90%E4%BE%9B%E4%BA%86%E4%B8%A4%E7%A7%8D%E6%96%B9%E6%B3%95%E5%88%97%E5%87%BA%E4%B8%80%E4%B8%AA%E6%95%B0%E6%8D%AE%E5%BA%93%E4%B8%AD%E7%9A%84%E6%89%80%E6%9C%89%E8%A1%A8%EF%BC%9A%20%E5%9C%A8%20psql,%E5%B7%A5%E5%85%B7%E4%B8%AD%E4%BD%BF%E7%94%A8%20dt%20%E6%88%96%E8%80%85%20dt%2B%20%E5%88%97%E5%87%BA%E5%BD%93%E5%89%8D%E5%BD%93%E5%89%8D%E6%95%B0%E6%8D%AE%E5%BA%93%E4%B8%AD%E7%9A%84%E6%89%80%E6%9C%89%E7%9A%84%E8%A1%A8%E3%80%82

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