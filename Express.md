It seems that the first step in learning Node.JS would be to learn what Express is.

So I read in the course https://web.digitalinnovation.one/course/introducao-ao-nodejs-com-expresses

That Express is a minimalistic and fast web framework for Node.js that provides a robust framework and 
feature set for web and mobile applications.

It features HTTP utility methods and middleware to create a fast and secure API. So it is very useful
in API and microservices development which is what I am currently studying both in college and at work.
 
 
To start using Express in your project just type the following code

`npm install express --save`
 
 Simple as that, you can now upload an application to any port on your LocalHost.
 
 Example : 
 
  Create a file like as: `index.js`
  
  Put this content:

  ~~~~javascript      
  const express = require('express')
  const app = express()
  const port = 3000

  app.get('/', (req, res) => res.send('Node running express!'))
  app.listen(port, () => console.log('application running on port 3000'))
  ~~~~
  
  Open the Promt in the same folder which is the file and run 
  
  `node index.js`
  
Check: `http://localhost:3000/`

Basically this was my first contact with Node.js using the Express framework.



##Thanks
