# spring-log4j2-example-mule4

### Setup
1. Download and import project into Anypoint Studio
2. Set VM Argument in Run Configuration to pass the app.name
3. Change `arguments` property in `springbeans.xml` to point to log4j2.xml file. An example is in the `docs` folder.
4. Run project

### VM Argument
```-Dapp.name=test-app-1 -M-Dlog4j.debug=true```
