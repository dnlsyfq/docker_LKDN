
### Backend

* create image
```
docker build -t danial/backend .

```

* run container
```
docker run -p 4000:4000 danial/backend
```

* see docker images
```
docker images
```

* remove docker images
```
docker rmi <image id 4 characters>
```

* see running container
```
docker ps
```

* start & stop container
```
docker start <container id 4 characters>
docker stop <container id 4 characters>
```