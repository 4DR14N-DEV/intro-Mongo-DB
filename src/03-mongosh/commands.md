## Connect to container

```sh
doker-compose exec mongodb bash
```

## Connect with mongosh

```sh
mongosh "mongodb://root:root123@localhost:27018/?tls=false"
mongosh "mongodb+srv://adrian_DB:<db_password>@cluster0.8osd6cg.mongodb.net/"
```

```sh
show dbs
show collection
```

```sh
use("Adrian_store")
db.products.find()
```


