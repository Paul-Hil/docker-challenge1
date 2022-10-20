# Commande pour lancer le serveur d'apache
```
 docker run -it -p 8080:80 image:v0.1
```

# build pour docker hub
```
 docker build . -t paulhil/image:v0.1
```

# push pour docker hub
```
 docker push paulhil/image:v0.1
```