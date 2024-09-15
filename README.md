# express

thread- can do something<br>

<h2> HTTP</h2>
hyper text transfer protocol<br>

<h3> HTTP server</h3>
where your logic is exposed<br>

<h3> express (framework)</h3>
how to create http server<br>
it is not a node library<br>

<h3> port</h3>
in a machine we can run various http server <br>
so unique port<br>

you ----->req algorithm (single threaded one thing at a time)<br>
you <-----res algorithm (single threaded one thing at a time)<br>

<h3> send req</h3>
localhost:3000/?(query)<br>
note: It shoul be a string because a number it will think as a status code<br>

<h3> to install express</h3>
npm install express<br>

<h3> boiler plate code</h3>
const express = require("express");<br>
const app-express();<br>
app.get("/",function(req,res){ //route<br>
//logic<br>
})<br>
app.listen(3000);<br>

<h3> cannot GET </h3>
not open or mot ready or nothing<br>

<h3> / is route</h3>
accepting route and doing something deployed on local network<br>

<h3> 2 ways of input</h3>
query parameter- after ? everything<br>
body<br>

<h3> request methods</h3>
get - asking<br>
post - insert<br>
post - replace<br>
delete - remove<br>

<h3> status code </h3>
(by default, can be changed)<br>
200- fine<br>
404 - not found<br>
505 - something went wrong<br>
414 - incorrect input<br>
403 - not allowed<br>

<h3> postman </h3>
test the get , post , post , delete <br>

<h3> res.json({})</h3>
otherwise program will be hung<br>

same thing log <br>



