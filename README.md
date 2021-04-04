# Setup
You need `compilerbook` image first.

```shell
docker build -t compilerbook https://www.sigbus.info/compilerbook/Dockerfile
```

# Enter interactive mode
```shell
docker-compose up -d && docker-compose exec compiler bash
```
