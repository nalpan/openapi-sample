# start(dcoker)

```
docker run -p 80:8080 -v $(pwd)/api-with-examples.yaml:/usr/share/nginx/html/sample.yaml -e API_URL=sample.yaml swaggerapi/swagger-ui
```
