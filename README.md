# CI-CD

## Exercício de CI/CD para uma API Uvicorn C/Docker

## Como Rodar

### 1.

``` shell
sudo docker build -t my-api .
```
-----

### 2.

``` shell
sudo docker run -d --name my-api  -p 8000:8000 my-api
```
-----

### 3.

``` shell
sudo docker logs -f my-api
```
-----

``` shell

INFO:     Started server process [1]

INFO:     Waiting for application startup.

INFO:     Application startup complete.

INFO:     Uvicorn running on http://0.0.0.0:8000 (Press CTRL+C to quit)
```
---
