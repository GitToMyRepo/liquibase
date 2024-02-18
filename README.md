# The purpose of this project is for learning Liquibase.

## The exercises
Run the following to create/start up PostgreSQL server in Docker container
```
docker run --name postgres-container -e POSTGRES_PASSWORD=mysecretpassword -p 5432:5432 -d postgres
```

| Exercise  | Directory | Description | Command |
| ------------- | ------------- | ------------- | ------------- |
| liquibase  | liquibase\exercises\postgresql  | This is a very simple exercise that creates an empty table in a PostgrsSQL database | PS C:\idev\liquibase\exercises\postgresql> liquibase --defaultsFile=liquibase.properties update |
| postgresql-multiplefiles  | liquibase\exercises\postgresql-multiplefiles | This exercise separate the table and data creations | PS C:\idev\liquibase\exercises\postgresql-multiplefiles> liquibase --defaultsFile=liquibase.properties update | 
