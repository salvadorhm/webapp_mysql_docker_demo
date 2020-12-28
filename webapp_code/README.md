# Webapp

## Build webapp

```
docker build -t webapp:latest .
```

## Run webapp

```
docker run --rm -p 8080:8080 --name=webapp webapp:latest
```

## Stop webapp

```
$docker stop webapp
```
