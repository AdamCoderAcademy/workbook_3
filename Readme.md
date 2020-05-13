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

<h1>Q4.	A team is about to engage in a project, developing a website for a small business. What knowledge and skills would they need in order to develop the project?</h1>

- The team would need to know as much information about the small business, client and clientele as possible so that the website can reflect information accurately. 
- They need to know the clients expectations and goals and decide if it is an appropriate project in terms of difficulty as well as to take into consideration if it is profitable in some way.
- They will want to appoint a Project Manager that the rest of the team trust to run the project without issues.
- Outline their own goals with the website
- Set an approximate timeline for tasks to be completed along the way and check for dead line dates that must be met.
- They will need to be capable of both front and back end coding preferably using a "full-stack" such as MERN.

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

