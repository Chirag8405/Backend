# Backend

Day 01 of learning Backend:
Learnt basics about backend development

Day 02:
Create a basic http server using express

Example for basic express server:
//import express
const express = require('express')

//create express instance
const app = express()

//create port for the server
const port = 3000

//create a simple function:
app.get('/', (req,res) => {
  res.send("My first server")
})

//initialise the server
app.listen(port, () => {
  console.log(`server runnning on port ${port}`)
})
  
