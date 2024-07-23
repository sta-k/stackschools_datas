# stackschools_datas

load data:

```
cd stackschools_datas
tar xvf data_sql.tar.xz
psql -U postgres -d stackschools < keralaschools.sql
psql -U postgres -d stackschools < schools.sql
psql -U postgres -d stackschools < colleges.sql
rm keralaschools.sql schools.sql colleges.sql
```


Dump database:

```
sudo su postgres
pg_dump --data-only -d stackschools2 -t schools_keralaschool -t schools_staffdesig -t schools_staffdetails > /tmp/keralaschools.sql
```



