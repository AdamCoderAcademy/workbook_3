<h1> Q1.	Provide an overview and description of a standard source control process for a large project</h1>

<h1>Q2.	What are the most important aspects of quality software?</h1>

<h1>Q3.	Outline a standard high level structure for a MERN stack application and explain the components</h1>

<h1>Q4.	A team is about to engage in a project, developing a website for a small business. What knowledge and skills would they need in order to develop the project?</h1>

<h1>Q5.	With reference to one of your own projects, discuss what knowledge or skills were required to complete your project, and to overcome challenges</h1>

<h1>Q6.	With reference to one of your own projects, evaluate how effective your knowledge and skills were for this project, and suggest changes or improvements for future projects of a similar nature</h1>

<h1>Q7.	Explain control flow, using an example from the JavaScript programming language</h1>

<h1>Q8.	Explain type coercion, using examples from the JavaScript programming language</h1>

<h1>Q9.	Explain data types, using examples from the JavaScript programming language</h1>

<h1>Q10. Explain how arrays can be manipulated in JavaScript, using examples from the JavaScript programming language</h1>

<h1>Q11. Explain how objects can be manipulated in JavaScript, using examples from the JavaScript programming language</h1>

<h1>Q12. Explain how JSON can be manipulated in JavaScript, using examples from the JavaScript programming language</h1>

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
