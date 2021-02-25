# LiquibaseH2Issue

This project demonstrates an issue with liquibase and H2. When inserting the string 'scale values mean' it instead attempts to insert 'scale KEY(version) values mean'

run the test using the command<br/>
```mvn liquibase:update```
