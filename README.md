# node-cn
Nodejs with cnpm package from npm.taobao.org.  
  
[![DockerHub Badge](http://dockeri.co/image/zhangsean/node-cn)](https://hub.docker.com/r/zhangsean/node-cn/)

### Usage
```
docker run -it --rm -v $PWD:/app -w /app zhangsean/node-cn cnpm install
docker run -it --rm -v $PWD:/app -w /app zhangsean/node-cn cnpm run dev
docker run -it --rm -v $PWD:/app -w /app zhangsean/node-cn cnpm run build:prod
```
