<h1> Q1.	Provide an overview and description of a standard source control process for a large project</h1>

Source Control of a large project involves the management of changes to documents, computer programs, large web sites, and other collections of information. Changes will usually be identified by a number or letter code, termed the "revision number", "revision level", or simply "revision". For example, an initial set of files might be called "revision 1". When the first change is made, the resulting set might then be called "revision 1.1", another change is made at it's then "revision 1.2.1" and so on. Each revision is associated with a timestamp and the person making the change. Revisions can be compared, restored, and with some types of files, merged. 

Source Control is the best way to keep track of your code and allows developers to branch off on their own full knowing that if there are major flaws in the latest code it can easily be rerolled back to a more stable version number.

Resource - https://en.wikipedia.org/wiki/Version_control

<h1>Q2.	What are the most important aspects of quality software?</h1>

The most important aspects of quality software is that it should be 

Reliable

- Software is reliable when it behaves consistently. Errors should occur rarely or preferably not at all. Errors that do occur should be handled gracefully and proactively.

Easy to understand

- The structure, components, and source code must be understandable and well-organized. They should behave the way a developer would expect. High-quality source code should always be easy to read.

Easy to modify

- It should be easy to Create, Read, Update or Delete the code within the software ;-). 

Easy to use

- Software products should be simple and easy to use. Users should feel comfortable with the software interface.

Efficient

- Software is efficient when it uses as few physical resources as possible. It should utilize the system hardware available as effectively as possible.

Good Testability 

- The functionality of software should be verifiable, concise and clear.Testing the software should offer clear verification. This also makes debugging is as easy as possible. 

Portable

-  Portable software is able to be run on multiple different systems, using multiple different types of hardware or operating systems.

Secure

- Lastly it is very important that above all the software is secure for all parties intending on using it.

<h1>Q3.	Outline a standard high level structure for a MERN stack application and explain the components</h1>

- Mongo 
  - MongoDb is a document based database program. Classified as a NoSQL non relational database program that uses JSON-like documents. Instead of using tables and rows like a traditional relational database it uses collections and documents.

  Reference - https://www.guru99.com/what-is-mongodb.html

- Express
  - Express.js is a free and open source back end framework that has been often called the standardised framework for Node.js. Express is well known for speed and reliability.

  Reference - https://en.wikipedia.org/wiki/Express.js

- React
  - React was created by Facebook and is an open source component-based front end JavaScript library used for building user interfaces (The views). It has grown to be very popular.

  Reference - https://www.edureka.co/blog/what-is-react/#3

- Node.js
  - Node.js is a cross platform JavaScript runtime environment. Node is built on Google Chrome's JavaScript Engine (V8 Engine) and is open source.

  Reference - https://www.tutorialspoint.com/nodejs/nodejs_introduction.htm


<h1>Q4.	A team is about to engage in a project, developing a website for a small business. What knowledge and skills would they need in order to develop the project?</h1>

- The team would need to know as much information about the small business, client and clientele as possible so that the website can reflect information accurately. 
- They need to know the clients expectations and goals and decide if it is an appropriate project in terms of difficulty as well as to take into consideration if it is profitable in some way.
- They will want to appoint someone as a Project Manager/Team Leader as well as allocate tasks to other team members based on skills, experience and strength.
- Outline their own goals with the website
- Set an approximate timeline for tasks to be completed along the way and check for dead line dates that must be met.
- They will need to be capable of both front and back end preferably using a full-stack such as MERN.
- They will also need to be experienced in testing, debugging and deployment for the project to run smoothly.

<h1>Q5.	With reference to one of your own projects, discuss what knowledge or skills were required to complete your project, and to overcome challenges</h1>

In reference to my last project, the 2 way market place, I had many challenges along the way. One of the harder parts for me was the routing requests and it was very challenging to have all the paths correct and pointing to the correct pages. After several routes are added it feels like things start becoming tangled like a web. Having to remember the correct locations where code should be sitting and in which file in order to function as intended. 

To overcome my challenges I would simply go back to the correct day's lesson and then make sure to follow along step by step for that particular task that needed to be completed. I found it's best for me to try tackle one step at a time to avoid my own confusion. To complete the project it was necessary to be comfortable with Ruby on rails, CSS, HTML, AMAZON S3 image storage, Authentication with Devise, Rails Routing, Database relations (many to many etc) as well as needing to implement stripe as a payment gateway. Postgresql was used for this projects database storage and Heroku was used to deploy the site.

<h1>Q6.	With reference to one of your own projects, evaluate how effective your knowledge and skills were for this project, and suggest changes or improvements for future projects of a similar nature</h1>

I will make reference again to the my 2 way Market Place app. I had a lot of doubt in myself with this project especially with the back end routes. However with little help and the previous course content I was able to have the website up and running without any major issue. I remembered to push to heroku often to test the live website instead of only locally and my experience with Git this time around was a big improvement. I feel much more comfortable with Front end than I do with Backend at the moment.

Changes and improvements for me at this point is to just keep at it don't stop. I need to stop feeling intimidated from big code. I need to learn how to break tasks down individually even smaller if I need too and I need to be more strict with my time dedicated to studies. I should focus on repeating topics over to help retain that information. I must ensure pre planning such as mood boards, EDR, user stories etc are filled 

<h1>Q7.	Explain control flow, using an example from the JavaScript programming language</h1>

When we talk about control flow in any programming language we are talking about the way in which the order of code can execute or be manipulated.

```
let adamAge = false;
const age = 31;
const guess = prompt('How old was Adam when he passed workbook3 ?');

if ( +guess === age ) {
  adamAge = true;
}

if ( adamAge === true ) {
  console.log("Yes I got a pass at the magical confusing age of 31")
} else {
console.log("I'm sorry but that's not how old I was")
}
```
With my above code example depending on if you have guessed correctly or not depends on which line of code will execute. The answer manipulates or controls the "flow" of the code.


<h1>Q8.	Explain type coercion, using examples from the JavaScript programming language</h1>

Type coercion is when values convert from one data type to another like a string to number.

```
true + false
``` 

If you open terminal and start node. Simply typing true + false (both of these are booleans) will return a 1 (number) and has now converted its data type to a number

another example would be
```
1 + 2 + 3 = 6
```
but if change say the 2 into a string

```
1 + '2' + 3 = '123'
```
Even though I still use 2 data types that are numbers they have now being coerced or converted into a string as the final data type.


<h1>Q9.	Explain data types, using examples from the JavaScript programming language</h1>

JavaScript data types are powerful tools used to provide functionality within your code.

- Boolean 
  - A boolean is a conditional data type that can only have true or false values. These values will be often used to execute sections of code in a certain order if at all.

``` 
let yourGuess = false;
const number = 1;
const guess = prompt('Guess a number between 1 and 10.');

if ( +guess === number ) {
  yourGuess = true; 
}

if ( yourGuess ) {
  alert('You guessed the number!');
} 
else {
  alert(`Sorry. The number was ${number}.`);
}
```

- Undefined
  - A variable without any value has the value of undefined

  ```
  workbook3 = undefined;
  ```

- Null
  - The data type of null is actually an object despite being nothing. Below workbook3 would then be assigned the value null

  ```
  var workbook3 = {
    name:"workbook3",
    completed:"yes"
  };

  workbook3 = null;
  ```

  - Numbers
    - This is an integer or floating point number

    ```
    3 - 777.77 = 774.77
    ```
- String
  - Like other programming languages a string is a sequence of characters used to represent data stored in a text form.

  ```
  const string1 = 'Would you like a string';
  const string2 = 'Maybe another string?';
  const string3 = 'Workbook 4, let's have some more';
  ```

- BigInt
  - BigInt is an object that provides a way to represent whole numbers larger than 253 - 1, which is the largest number JavaScript can reliably represent using the numbers datatype.

  ```
  const theBiggestInt = 9007199254740991n
  ```

- Symbol
  - After creating a symbol its value is stored privately for internal use

  ```
  console.log(Symbol()) //Symbol()
  console.log(Symbol('Some Test')) //Symbol(Some Test)

  (this is a direct copy paste from https://flaviocopes.com/javascript-symbols/ for my example as I wasn't able to offer my own example)
  ```

- Objects
  - When you create an object you are storing data about that object inside a container.

  ```
  var workbook = {
    revisionName: "3",
    dayDue: 31,
    monthDue: "May"
  };

References - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Grammar_and_Types and https://www.w3schools.com/js/js_datatypes.asp

<h1>Q10. Explain how arrays can be manipulated in JavaScript, using examples from the JavaScript programming language</h1>

The Javascript language has many ways to manipulate code with examples as following.

- Array to string

In Javascript we can convert arrays into strings like this 
 ```
 <html>
<body>

<h1>How many workbooks are there ?</h1>

<p id="workbook"></p>

<script>
var workbookNumber = ["Workbook 1", "Workbook 2", "Workbook 3"];
document.getElementById("workbook").innerHTML = workbookNumber.toString();
</script>

</body>
</html>
```
The result looks like this and we now get back a string.

```
How many workbooks are there ?

Workbook 1,Workbook 2,Workbook 3
```

- Pop
  - You can pop off the last element inside an array using the method
  ```
  pop()
  ```
  Below is an example of pop()
```
<html>
<body>

<h2>Where has workbook 3 gone ?</h2>

<p id="workbook"></p>

<script>
var workbookNumber = ["Workbook 1", "Workbook 2", "Workbook 3"];
document.getElementById("workbook").innerHTML = workbookNumber;
workbookNumber.pop();
document.getElementById("workbook").innerHTML = workbookNumber;
</script>

</body>
</html>
```

This gives us the result 
```
Where has workbook 3 gone ?

Workbook 1,Workbook 2
```

- Push
  - You can push in an element to the last position inside of an array

  ```
  Push()
  ```

Lets see an example 
```
<html>
<body>

<h2>I see another workbook in your future</h2> 

<p id="workbook"></p>

<script>
var workbookNumber = ["Workbook 1", "Workbook 2", "Workbook 3"];
document.getElementById("workbook").innerHTML = workbookNumber;
workbookNumber.push("Workbook 4");
document.getElementById("workbook").innerHTML = workbookNumber;
</script>

</body>
</html>
```
This gives us the result 

```
I see another workbook in your future

Workbook 1,Workbook 2,Workbook 3,Workbook 4
```

- Shift
  - Shifting is the same as popping only working in reverse by removing the first item in the array rather than the last 

```
shift()
```

An example below

```
<html>
<body>

<h2>Goodbye Workbook 1</h2> 

<p id="workbookNumber"></p>

<script>
var workbookNumber = ["Workbook 1", "Workbook 2", "Workbook 3"];
document.getElementById("workbookNumber").innerHTML = workbookNumber;
workbookNumber.shift();
document.getElementById("workbookNumber").innerHTML = workbookNumber;
</script>

</body>
</html>
```
The end result removes Workbook 1 like this 
```
Goodbye Workbook 1

Workbook 2,Workbook 3
```
- Unshift
  - Unshift adds a new element to the start of your array

  ```
  unshift()
  ```

  Below is an example of how unshift works

```
<html>
<body>

<h2>Who was the original workbook ?</h2> 

<p id="workbook"></p>

<script>
var workbookNumber = ["Workbook 1", "Workbook 2", "Workbook 3"];
document.getElementById("workbook").innerHTML = workbookNumber;
workbookNumber.unshift("Workbook 0");
document.getElementById("workbook").innerHTML = workbookNumber[0];
</script>

</body>
</html>
```

The end result would look like this 
```
Who was the original workbook ?

Workbook 0
```
- Delete
  - delete allows you to change elements value to undefined

For example
```
<html>
<body>

<h2>When Workbook 0 is pushed into the array with unshift(), Workbook 2 then ends up in position 2 within the array. That is why we end up with 0, 1 and 3. Workbook 2 is already deleted when it displays to the screen. If I did delete workbook with out specifying the array index than nothing would display because all of it would be deleted and not just the index specified</h2> 

<p id="workbook"></p>

<script>
var workbookNumber = ["Workbook 1", "Workbook 2", "Workbook 3"];
document.getElementById("workbook").innerHTML = workbookNumber;
workbookNumber.unshift("Workbook 0");
document.getElementById("workbook").innerHTML = workbookNumber;
delete workbookNumber[2];
document.getElementById("workbook").innerHTML = workbookNumber;
</script>

</body>
</html>
```

The result of this code looks like this 
```
When Workbook 0 is pushed into the array with unshift(), Workbook 2 then ends up in position 2 within the array. That is why we end up with 0, 1 and 3. Workbook 2 is already deleted when it displays to the screen. If I did delete workbook with out specifying the array index than nothing would display because all of it would be deleted and not just the index specified

Workbook 0,Workbook 1,,Workbook 3
```

The element Workbook 2 within the array is now classed as undefined.

<h1>Q11. Explain how objects can be manipulated in JavaScript, using examples from the JavaScript programming language</h1>

<h1>Q12. Explain how JSON can be manipulated in JavaScript, using examples from the JavaScript programming language</h1>

JSON data can be directly manipulated in javascript by using parse or stringify. Stringify converts JavaScript objects into strings. The JSON.parse() method can then parse that string and return a JavaScript object.

Example of JSON  parse.

```
<html>
<body>

<h1>Did Adam pass workbook 3?</h1>

<p id="answer"></p>

<script>
var obj = JSON.parse('{"hePassed":"Yes", "noPass":"No"}');

document.getElementById("answer").innerHTML = obj.hePassed;
</script>

</body>
</html>
```

results in 

```
Did Adam pass workbook 3?
Yes
```


Example of JSON.stringify.

```
<html>
<body>

<p id="mystring"></p>

<script>
var obj = { "name":"Adam", "age":31, "pass workbook 3":"Yes"};
var myJSON = JSON.stringify(obj);
document.getElementById("mystring").innerHTML = myJSON;
</script>

</body>
</html>
```
Which will output this result 
```
{"name":"Adam","age":31,"pass workbook 3":"Yes"}
```


Reference - https://www.w3schools.com/jsref/jsref_parse_json.asp

<h1>Q13. For the code snippet provided below, write comments for each line of code to explain its functionality. In your comments you must demonstrates your ability to recognise and identify functions, ranges and classes</h1>

<h1>Q13. Code Snippet</h1>

class Car {
  constructor(brand) {
    this.carname = brand;
  }
  present() {
    return 'I have a ' + this.carname;
  }
}

class Model extends Car {
  constructor(brand, mod) {
    super(brand);
    this.model = mod;
  }
  show() {
    return this.present() + ', it was made in ' + this.model;
  }
}

let makes = ["Ford", "Holden", "Toyota"]
let models = Array.from(new Array(40), (x,i) => i + 1980)

function randomIntFromInterval(min,max) { // min and max included
    return Math.floor(Math.random()*(max-min+1)+min);
}

for (model of models) {

  make = makes[randomIntFromInterval(0,makes.length-1)]
  model = models[randomIntFromInterval(0,makes.length-1)]
    
  mycar = new Model(make, model);
  console.log(mycar.show())
}

