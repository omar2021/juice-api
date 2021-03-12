# juice-api
my favorite juices api!

To access and modify resources, you can make:

GET POST PUT PATCH DELETE etc

Heroku live visit [here]{https://my-fav-juices-api.herokuapp.com/}
 
Fetch
```
fetch('https://my-fav-juices-api.herokuapp.com/juices/0')
    .then(response => response.json())
    .then(data => console.log(data));
```
