# PSQLY
This project is a quick bootstrap to start database learning for sql beginner 

## Test Environment
- Linux Ubuntu 20.04 ( mac or wsl2 also should work)

## Pre-Install
- install git
- install docker
- install make
- install pgadmin gui 

## Getting Started
start the postgres server
```
docker-compose up 
```
shell to connect postgres server
```
make psql
```

## Restore Database
- use gui to restore dvdrental.tar 

## Command Used 
```
\c database_name  ( use database)
\dt               (list table) 
select * from table_name;
```



## References
tutorial: https://www.udemy.com/course/the-complete-sql-course-go-from-zero-to-hero/