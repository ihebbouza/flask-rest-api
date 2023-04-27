# CONTRIBUTING

## How to run app locally
```
```

## How to build Docker image
```
docker build -t IMAGE_NAME .
```

## How to run Docker file locally
```
docker run -dp 5000:5000 -v "%cd%:/app" IMAGE_NAME sh -c "flask run"
```