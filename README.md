# stackschools_datas
```
    cd stackschools_datas
	tar xvf data_sql.tar.xz
	psql -U postgres -d stackschools < keralaschools.sql
	psql -U postgres -d stackschools < schools.sql
	psql -U postgres -d stackschools < colleges.sql
	rm keralaschools.sql schools.sql colleges.sql
```
