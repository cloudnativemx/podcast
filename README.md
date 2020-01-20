# podcast

docker run -it -v C:\obs\data:/data --rm --net=host alpine/httpie:1.0.3  --form POST :8080/v1/videos video@/data/video.yaml 


docker run -it -v C:\obs\data:/data --rm --net=host alpine/httpie:1.0.3 put :8080/v1/videos/goo