<h1>express</h1> <br>
Express is a popular web application framework for Node.js. 
It simplifies the process of building web applications by providing a robust set of features for web and mobile applications

<h2>thread</h2>
<br> can do something<br>

<h2> HTTP</h2>
hyper text transfer protocol

<h2> HTTP server</h2>
where your logic is exposed<br>

<h2> express (framework)</h2>
how to create http server<br>
it is not a node library<br>

<h2> port</h2>
in a machine we can run various http server <br>
so unique port<br>

you ----->req algorithm (single threaded one thing at a time)<br>
you <-----res algorithm (single threaded one thing at a time)<br>

<h2> send req</h2>
localhost:3000/?(query)<br>
note: It shoul be a string because a number it will think as a status code<br>

<h2> to install express</h2>
npm install express<br>

<h2> boiler plate code</h2>
const express = require("express");<br>
const app-express();<br>
app.get("/",function(req,res){ //route<br>
//logic<br>
})<br>
app.listen(3000);<br>

<h2> cannot GET </h2>
not open or mot ready or nothing<br>

<h2> / is route</h2>
accepting route and doing something deployed on local network<br>

<h2> 2 ways of input</h2>
query parameter- after ? everything<br>
Data sent in the URL after a question mark (?), typically as key-value pairs.
<br>
request body- Data sent in the body of an HTTP request, often used for larger amounts of data or complex structures.<br>

<h2> request methods</h2>
get - asking<br>
post - insert<br>
post - replace<br>
delete - remove<br>

<h2> status code </h2>
(by default, can be changed)<br>
200- fine<br>
404 - not found<br>
505 - something went wrong<br>
414 - incorrect input<br>
403 - not allowed<br>

<h2> postman </h2>
test the get , post , post , delete <br>

<h2> res.json({})</h2>
otherwise program will be hung<br>

same thing log <br>



