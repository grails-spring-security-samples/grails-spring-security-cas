# grails-spring-security-cas

## Start CAS server:

```
grails-spring-security-samples/grails-spring-security-cas $ cd server/bin
grails-spring-security-samples/grails-spring-security-cas/server/bin $ ./startup.sh
```

CAS Server will start at : 
http://localhost:9090/cas/

## Start Grails 2.5.6 app: 

```
grails-spring-security-samples/grails-spring-security-cas $ cd grails.2.5.6
grails-spring-security-samples/grails-spring-security-cas/grails.2.5.6 $ grails run-app
```

Grails app will start at:

`http://localhost:8080`

Visit 

`http://localhost:8080/secure/admins`

You will be redirect to authenticate in the CAS Server use credentials `admin/admin`


