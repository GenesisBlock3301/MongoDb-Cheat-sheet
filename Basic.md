# MongoDb-Cheat-sheet

## Show database
```
show dbs
```
## Create database
if database haven't any collections(table) . We need to create minimum one collection on the database.
```
use database_name
```

## Create Collections
```
db.createCollection('Collection_name')
```

## Database Delete
```
db.dropDatabase()
```
## Show Collection
```
show collections
```
## Delete Collection
```
db.collection_name.drop()
```
## Insert Field
**Insert one:**
```
db.collection_name.insertOne({'_id':1,'name':'Sifat','class':12})
```
**Insert Many:**
```
db.collection_name.insertMany([{id:1,name:'Sifat',class:12},{id:2,name:'Nas',class:11}])
```
## Collection Read Operation
```
db.collection_name.find()
```
## Insert into Collection
```
db.collection_name.insert({_id:4,name:"Sifat",class:12})
```
