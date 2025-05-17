[![CI](https://github.com/alimas-performance/performance_api_monitor/actions/workflows/main.yml/badge.svg)](https://github.com/alimas-performance/performance_api_monitor/actions/workflows/main.yml)
# performance_api_monitor
Repo with how to use jmeter to monitor APIs and getting results to be processed in different ways.



### Opening API documentation with Swagger.io :

```shell
docker run -d -p 80:8080 -v ${pwd}/docs:/tmp -e SWAGGER_FILE=/tmp/spotify.yaml docker.swagger.io/swaggerapi/swagger-editor
```

