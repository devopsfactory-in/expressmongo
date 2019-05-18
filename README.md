# expressmongo
A simple demo application which integrates Express with Mongo DB. 

## Prerequisites

Mongo db (either local setup or Atlas cluster)
No need to change any config if Mongo DB available locally.
For Atlas cluster change the Mongodb connection string on the 'app.js' file.

replace the following line with mongoose.connect('mongodb+srv://<uname>:<password>@<clusterurl>/<schema>?retryWrites=true');

mongoose.connect('mongodb://localhost/mydb001');

## Run Locally
To run this application locally just use the below command.

```
> npm install
> npm start
```

The express server runs on 3000 port

http://localhost:3000/
