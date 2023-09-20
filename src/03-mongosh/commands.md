## Connect to container

```sh
docker-compose exec mongodb bash
```

## Connect with mongosh

```sh
mongosh "mongodb://localhost:27017/?tls=false"
mongosh "mongodb+srv://bryanccc11:landrover11@mongodb195.vj9hhvh.mongodb.net/"
```

```sh
show dbs
show collections
```


```sh
use("platzi_store")
db.products.find()
```