
# Running Locally 
Standard Node.js `npm install` and start with `npm start` from the 'src' directory. Web app will be listening on the usual Express port of 3000, but this can be changed by setting the `PORT` environmental variable. Tested with Node v8.x and 10.x


# Docker 
Public Docker image is [available on Dockerhub](https://hub.docker.com/r/bencuk/nodejs-demoapp/).  

Run in a container with:
```
docker run -d -p 3000:3000 bencuk/nodejs-demoapp
```


