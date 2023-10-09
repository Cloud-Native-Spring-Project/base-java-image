# base-java-image

Repo to understand how to use docker images and Github Container Registry

### To login into Github Container registry (ghcr)

```
docker login ghcr.io
```

### To Tag the image

```
docker tag base-java-image:1.0.0 ghcr.io/<your_github_username>/base-java-image:1.0.0
```

### To Push the image

```
docker push ghcr.io/<your_github_username>/base-java-image:1.0.0
```

test content
