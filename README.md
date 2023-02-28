# LearningMongodb

<code><img src="https://github.com/devicons/devicon/blob/master/icons/mongodb/mongodb-original-wordmark.svg" title="mongodb" alt="mongodb" width="200" height="100"/></code>

- ### mongodb install directory `cd "C:\Program Files\MongoDB\Server\5.0\bin\" `

- ### mongo version check `mongo --version`

- ### mongodb version check `mongod --version`

- ### mongos version check `mongos --version`

<h2>mongodb install directory type this commands</h2>

- ### mongo start `mongo.exe`

- ### show databases `show dbs`

- ### check current working database `db`

### Syntax (use DatabaseName)
- ### new create database & switch database `use ecommerce`

### Such a collection has to be created so that the database is not show

### Syntax (db.createCollection(CollectionName))
- ### database in create collection `db.createCollection("user")`

- ### show all collections `show collections`

### Syntax (db.CollectionName.drop())
### delete collection `db.user.drop()`

### Syntax (db.dropDatabase())
- ### drop database `db.dropDatabase()`

- ### collection in insertOne row of data
### Syntax (db.CollectionName.insertOne({field:'value',field:'value'}))
### `db.user.insertOne({"name":"vipul","school":{"name":"abcds","city":"asdas"}})`

- ### collection in insertMany rows of data
### Syntax (db.CollectionName.insertMany([{field:'value'},{field:'value'}]))
### `db.user.insertMany([{"name":"vipul","school":{"name":"abcds","city":"asdas"}},{"name":"vipul","school":{"name":"abcds","city":"asdas"}}])`

### Syntax (db.CollectionName.find())
- ### collection in show all rows `db.user.find()`

### Syntax (db.CollectionName.find({field:'value'}))
- ### collection in show all matching rows `db.user.find({name:"vipul"})`

### Syntax (db.CollectionName.findOne({field:'value'}))
- ### collection in show One matching row `db.user.findOne({name:"vipul"})`
