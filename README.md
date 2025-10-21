# Backend

Day 01 of learning Backend:
Learnt basics about backend development

Day 02:
Create a basic http server using express

Example for basic express server:
const express = require('express')    //import express


const app = express()    //create express instance


const port = 3000    //create port for the server


app.get('/', (req,res) => {    //create a simple function:

  res.send("My first server")
})

app.listen(port, () => {   //initialise the server
  console.log(`server runnning on port ${port}`)
})
  
