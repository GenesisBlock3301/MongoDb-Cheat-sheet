# Logical Operation of MongoDB

## Comparesion Operator
```
db.collection_name.find(query,projection)

db.collection_name.find({class: {$eq: 12}})
```
## Method

## Count Item
```
db.collection_name.find(query,projection).count()
```

## Sorting the collections item
```
db.collection_name.find(query,projection).sort({fieldName,using that sort the item:-1})
```
**-1 that means decending order**

## Limit of collections
```
db.collection_name.find(query,projection).limit(2)
```
## Update One Item in Collections
```
db.collection_name.updateOne({_id:1},{$set:{age:21}})
```
**Select {_id:1} and then set {age:21} that means _id=1 item is update.**

## Delete one Item from collections

```
db.collection_name.deleteOne({_id:1})
```
**id:1 is deleted from collections**


