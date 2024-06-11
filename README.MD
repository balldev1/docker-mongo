# docker
# docker-compose up -d
# mongodb://balldev:balldev1@localhost:27023/?authSource=admin
# docker-compose exec <container_name> mongosh -u balldev -p balldev1 --authenticationDatabase admin

# Mongo

Show dbs

db.createCollection("posts")

show collections

db.<collectionsname>.insertOne({title:"Post 1",body:"test"})

db.<collectionsname>.find()

db.<collectionsname>.deleteOne({ _id: ObjectId("6667c02ca03802942c8db5fb") })

https://www.w3schools.com/mongodb/mongodb_mongosh_insert.php

# mongose
MongoDB mongosh Insert (w3schools.com)

mongodb://<USERNAME>:<PASSOWRD>@localhost:<PORT>/?authSource=admin"

docker -it exec <container_name> mongosh -u <USERNAME> -p <PASSOWRD> --authenticationDatabase admin