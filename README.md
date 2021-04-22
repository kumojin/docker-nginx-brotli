# Docker image for nginx with brolti module

## Build
```
docker build --build-arg ENABLED_MODULES="brotli" -t kumojin/nginx:1.19-alpine-brotli .
```

