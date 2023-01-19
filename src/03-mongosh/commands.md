## connect to container

```
sh
docker-compose exec mongodb bash
```

## connect with mongsh

```
sh
mongosh "mongodb://root:root@localhost:27017/?authMechanism=DEFAULT&tls=false" #mongo docker
mongo sh "mongodb+srv://feradmin:<password>@mongodb101.dtohz4d.mongodb.net/test" # mongo atlas
```

```
sh
show dbs
show collections
```

```
sh
use("platzi_store")
db.products.find()
```
