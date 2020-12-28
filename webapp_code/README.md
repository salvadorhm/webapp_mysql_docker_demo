# Webapp

## Build webapp

```
$docker build -t webapp_image:latest .
```

## Run webapp

```
$docker run --rm -p 80:8080 -name=webapp webapp_image:latest
```

## Stop webapp

```
$docker stop webapp
```
