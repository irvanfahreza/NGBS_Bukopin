## Run the app
 
```bash
mvn spring-boot:run
```
 
App runs on `http://localhost:8080`.
 
## Run tests
 
```bash
mvn clean test
```
 
Coverage report unit tests is generated at:
```
target/site/jacoco/index.html
```

## Postman
 
Import `postman_collection.json` from the project root. It includes working request bodies for every endpoint, matching the dummy data from `data.sql`.
