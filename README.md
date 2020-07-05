# podcast


```
docker run --rm -d -p 8080:8080 -v C:\obs\data:/data -e BASEDIR=/data domix/obs-util:0.0.8
```

```
docker run -it -v C:\obs\data:/data --rm --net=host alpine/httpie:2.2.0  --form POST :8080/v1/videos video@/data/video.yaml 
```

```
docker run -it -v C:\obs\data:/data --rm --net=host alpine/httpie:2.2.0 put :8080/v1/videos/goo
```