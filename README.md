
<img src="./food1.jpg">

### REST API with Express Server

This is our eight REST API for React js App

## First clone this repo and then install this packages

```console
$ npm install
```

## Server stucture 

```js
const express = require('express')
const dotenv = require('dotenv')
const colors = require('colors');

//init enviroment variable
dotenv.config();
const PORT = process.env.PORT  || 5050; 

//init express
const app = express();

//express middleware
app.use(express.json())
app.use(express.urlencoded({ extended : false }))



//routes
app.listen(PORT, () => {
console.log(`this  is for rest api ${PORT}`.bgMagenta);
})

```

## Packages

-Exprss Js
-Nodemon
-Colors
-dotenv
-multer
-nodemailer



## Live button 
[Education Bord](http://www.educationboardresults.gov.bd/)


