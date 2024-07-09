Ce repository contient une application dockerisée (live-coding Docker organisé chez Ada Tech School le 12/07/2024)

## Liens utiles
- [Docker Compose](https://docs.docker.com/compose/gettingstarted/)
- [Dockerfile Reference](https://docs.docker.com/reference/dockerfile/)

## Cheatsheet de commandes

Builder une image
```sh
docker build -t node-api-sample .
```

Exécuter un container à partir d'une image 
```sh
docker run -dp 127.0.0.1:8888:8888 node-api-sample
```  
