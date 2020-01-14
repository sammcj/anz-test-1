# ANZx Platform Test 1

When built, this Docker image runs a container that exposes a HTTP endport on port 8000.


## Build

```
docker build . -t anzxtest1:v1.0.0
```

## Run

```
docker run -p 8000:8000 anzxtest1:v1.0.0
```

## Test

```
curl http://localhost:8000
```

Expected output:

```
Hello, world.%
```