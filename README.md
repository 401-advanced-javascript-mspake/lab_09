![CF](http://i.imgur.com/7v5ASc8.png) LAB   
=================================================  
  
## Lab - 09  
  
### Author: Morgana Spake  
  
### Links and Resources  
* [submission PR](https://github.com/401-advanced-javascript-mspake/lab_09/pull/1)  
<!-- * [back-end](http://xyz.com) (when applicable)
* [front-end](http://xyz.com) (when applicable) -->
  
#### Documentation  
* [api docs](http://xyz.com) (API servers)
* [jsdoc](http://xyz.com) (Server assignments)

### Modules  
#### `app.js, v1.js, 404.js, 500.js, model-finder.js, memory-model.js, mongo-model,js, categories-model.js, players-model.js, players-schema.js, teams-model.js, teams-schema.js`  
  
##### Exported Values and Methods  
  
###### `app -> express server`  
###### `router -> express Router instance`   
###### `404 -> middelware`  
###### `500 -> middelware error handler`  
###### `model-finder -> middelware`  
###### `memory-model -> Model class constructor`  
###### `mongo-model -> Model class constructor`  
###### `categories-model -> new instance of the Categories class`  
###### `players-model -> new instance of the Players class`  
###### `teams-model -> new instance of the Teams class`  
###### `teams-schema -> mongoose schema`  
###### `players-schema -> mongoose schema`  


### Setup   
#### `.env` requirements  
* `PORT` - Port Number (ie: 3000)  
* `MONGODB_URI` - URL to the running mongo instance/db (ie: mongodb://localhost:27017/databaseName)  

#### Running the app  
* `npm start`  
Endpoints:  
* `/api/v1/:model`  
* `/api/v1/:model`  
* `/api/v1/:model/:id`  
* `/api/v1/:model/:id`  
* `/api/v1/:model/:id`  
  
#### UML
Link to an image of the UML for your application and response to events