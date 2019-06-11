#####Example migration run
```"<pathToLiquibase>/liquibase-3.6.3-bin/liquibase[.bat]" update```
#####Example migration rollback
```"<pathToLiquibase>/liquibase-3.6.3-bin/liquibase[.bat]" rollbackCount 1```

#### Example properties file
```driver: com.mysql.jdbc.Driver
classpath: liquibase-3.6.3-bin/lib/mysql-connector-java-5.1.13.jar
url: jdbc:mysql://localhost:3306/liquibase_test
username: root
password:
changeLogFile: migrations/migrations.master.xml