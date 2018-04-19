# Helper lines of code

## Mongoose

```
MONGODB_URI=mongodb://localhost/testing

mongoose.Promise = Promise;

mongoose.connect(process.env.MONGODB_URI, {useMongoClient : true});

MongooseModelObject.find({})

```
- Find takes in a .limit and possible .skip
- Delete Crud is findByIdAndRemove()

## npm scripts
```
"dbon": "mkdir -p ./db && mongod --dbpath ./db",
"dboff": "killall mongod"

```

## Express Server Steps

- require correct modules
- instantiate an express instance
- set up a catch all route
- listen on a port
- connect to your db

## Jquery/handlebars
```
<script src="https://code.jquery.com/jquery-3.2.1.min.js"></script>

<script src="https://cdnjs.cloudflare.com/ajax/libs/handlebars.js/4.0.11/handlebars.min.js"></script>

<script type="text/x-handlebars-template"></script>

```
- Update requires $.ajax and uses url method and data
