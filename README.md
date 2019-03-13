# demo_java_jersey

Build the app
```
mvn package
```

Run as embedded Grizzly container
```
mvn exec:java
```

View the page
http://localhost:8080/demo_java_jersey/whoami

This relies on container managed security, which is not handled here at all. 

