"# zuul_api_gateway" 
```
RUN ACME Vacations http://localhost:8080/vacations
```
###Access ACME from Zuul API Gateway 
Authentication/Authorization will happen on Zuul API Gateway and then it then forward (proxy) the request to ACME service
```
http://localhost:8090/acme/vacations/
````
