start my-sql:

```cmd
docker run -p 5000:3306 --name my-sql -e MYSQL_ROOT_PASSWORD=root -d mysql:latest
```

view container

```cmd
docker ps
```

Download [sample database](https://www.databasestar.com/sample-database-olympic-games/) from [here](https://github.com/bbrumm/databasestar/tree/main/sample_databases/sample_db_olympics/mysql)

Import those 8 individual datasets in this db through my-sql workbench.
Now our local db is ready.
