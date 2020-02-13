README
===

### Intro.
This project base on [here](https://github.com/tantanieli/docker-nginx-rtsp-hls). 
The RTSP source from [wowza](https://www.wowza.com/html/mobile.html)

### How to used?

- Build & Run  

```shell=
docker build . -t rtsp2hls
docker run -d -p 0.0.0.0:1935:1935 -p 0.0.0.0:8080:8080 rtsp2hls
```
- View 

You can see the result in browser: http://localhost:8080
or via http://localhost:8080/cam1/stream.m3u8 on player 


