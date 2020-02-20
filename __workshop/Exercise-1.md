# Questions

**With a partner**, answer these questions as completely as possible. Feel free to look at past lecture notes, the web, anything. 

Take the time to explain it to each other. 

The power of this exercise is in the act of _formulating_ and _explaining_ the concepts to someone else (your teammate).

## One

Run the app. Write out the steps, the _pseudo code_, required to create this app. It doesn't have to be totally accurate, or in the right order.

Only move on to the next question when you have enough detail that you would be able to start coding it yourself.

```
// Answer here


GET/POST 
Add the input value in an array {object} — see top50 Song example
pass input in a <li>
function (param input) === user input




```

## Two - `server.js`

Take a look at the `server.js` file.

We have a new module in there, `body-parser` that is required on line `4`. What is it for? What is its use-case? What other lines are related to this module?

_The NPM site might be a good place to start. Feel free to provide links as relevant._

```
// Answer here

Middle man between the user input and the database to parse the data and see if it matches. 

line 18 
line 24
```

## Three - `server.js`

Look at lines `23` and `24`. Explain the methods used. How are they different? What are the usecases for each?




```
// Answer here
req.body is parsing the user input into the array. using the POST
```

## Four - `server.js`

Line `6`. That's new. What do you think it's for?

```
// Answer here

tell the server that the function exist in an external file 

```

## Five - `handlers.js`

Explain line `1`. Where, why and how is `items` being used?

```
// Answer here

it's use to handle form data from the user input, store the object to be parsed and are used to be displayed in the todoInput.


```

## Six - `handlers.js`

Why is there `redirect` on line `11`;

```
// Answer here

once the data is parsed, need an action to be redirect 

``` 

## Seven - `handlers.js`

The `handle404` function is a more complex than we've seen thus far, what is the extra functionality for?

```
// Answer here

res a html if the req is for a browser 
res a json if the req is for the server 
if not both of these case, req a txt



```

## Eight - `ejs`

Take a look at `homepage.ejs` and `todoInput.ejs`. What is happening in there? Explain line-by-line...
```
// Answer here

see files sudo comment 


```

## Nine - `styles.scss`

What are lines `2` to `7` for this file? Where are these values being used? Take a look at `_homepage.scss` as well? What do you notice?

```
// Answer here

variable declaired to be reused thru the whole scss files


```

## Ten - `_homepage.scss`

Line `16`. See if by searching the Sass documentation, you can determine what _exactly_ is going on here. That `#{}` notation very specific to this use-case. Why?

```
// Answer here

use the # only in the calc to pass the variable value 


```







