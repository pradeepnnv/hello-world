### Command to build and run the dropwizard example
`mvn package & java -jar target/helloworldexample-1.0-SNAPSHOT.jar server hello-world.yaml`

###Testing

```
curl http://localhost:8080/hello-world/
curl http://localhost:8080/hello-world?name=Successful+Dropwizard+User
curl http://localhost:8081/healthcheck
```

###Source
https://www.dropwizard.io/0.9.2/docs/getting-started.html
