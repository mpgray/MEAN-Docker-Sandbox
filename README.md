
<h1 align="center">A Sandbox Docker MEAN Stack for Developement</h1>

<p align="center">
  <a href="https://angular.io/"><img src="https://img.shields.io/badge/Front--end-Angular-red.svg"></a>
  <a href="https://expressjs.com/"><img src="https://img.shields.io/badge/Back--end-Express-blue.svg"></a>
  <a href="https://www.mongodb.com/"><img src="https://img.shields.io/badge/Database-MongoDb-green.svg"></a>

</p>

# Description
<h4>A web application that I use as a base to sandbox projects.</h4>

Front-end application written using Angular, a Back-end that uses Express, backed by a MongoDB Database.



##### NOTE
I created this while learning, tutorials, and walk-throughs. I use a version of this for my own development purposes as a base to build more interesting applications. 

* Some work based on information and code provided by [Dan Wahlin](https://www.codewithdan.com/) . <em>docker container is his entirely</em>

# Installation 
### Requirements:
* [Nodejs](https://nodejs.org/en/download/)  8.10 or higher.
* [Docker and Docker Compose](https://www.docker.com/products/docker-desktop) 
Works on Linux/MacOSX but docker requires WinPro to install. WinHome doesn't cut it.

First you must install all needed depencies from this program's base directory.

```
npm install 
ng build --watch
```

Do the followning on first run to build the container:
``` 
docker-compose build
```
Now you can just run:
``` 
docker-compose up
```
or for daemon mode
``` 
docker-compose up -D
```

#### <em>Now go to http://localhost:3000 <em>

