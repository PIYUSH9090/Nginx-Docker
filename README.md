# Nginx Docker 

=> Here I'll show you how can run nginx server on container with docker image of nginx server.

With these three files in the same folder we can run:

First build the docker image :

```
docker build . -t our-server
```

And run it using this port:

```
docker run -it --rm -p 8080:80 our-server
```

Our static HTML web server will be up at [Here](http://localhost:8080/)


Hope this helps anyone trying to host static content! 