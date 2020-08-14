# API Gateway using Netflix Zuul 
```
RUN ACME Vacations http://localhost:8080/vacations
```
### Access ACME from Zuul API Gateway
```
Git Hub Authentication/Authorization will happen on Zuul API Gateway through OAuth2.0 
and then it then forward (proxy) the request to ACME service
```
http://localhost:8090/acme/vacations/
````
