swagger-springmvc-demo
======================



sample app using https://github.com/martypitt/swagger-springmvc/tree/rel-0.8-upgrade-spec-preview

fldskfafafjkaj


- Running the app:
```mvn jetty:run```
- Oauth Support
Update swagger-oauth.js as appropriate to your app
```javascript
var redirectUrl = host.protocol + '//' + host.host + "/swagger-springmvc-demo/o2c.html";
```

## Versions

This repo is tagged in the following format in an attempt to keep track of changing swagger-springmvc and swagger-ui versions
-- swagger-springmvc--<swagger-springmvc version>-swagger-ui--<swagger-ui version or branch>
-- e.g. swagger-springmvc--0.8.2-SNAPSHOT-swagger-ui--oauth

## Swagger UI Business Example
http://127.0.0.1:8097/swagger-springmvc-demo/swaggerBusiness

## Relative URL example (Relative URLS not recommended)
http://127.0.0.1:8097/swagger-springmvc-demo/swaggerRelative

## Functional Tests
1. Run the app: mvn jetty:run
2. Run the functional tests: mvn test
