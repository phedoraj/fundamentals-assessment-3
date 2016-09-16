#Note:
**There is no READme or JS file for this prompt.**

Answer each question below in your own words and be as thorough as possible.
In addition to answering these questions and completing the other exercises, pushing your self-assessments to github is also an assessment in itself. By now you should know how to fork, clone, and ultimately push the repo using your command line (terminal) interface.
* [ ] Did you fork, clone, and push this repo?

-

* [ ] What are the two types of for loops that we have used in the course?
	* [ ] When would you use each type?
	We used a regular for loop for looping through arrays and we used "for in" loops for looping through objects. 

* [ ] How would you access an element in an array?
Accessing an element in an array requires that you state the name of the array and then specify the index [i] or position of the first value which is a specification of the starting point of the elements that you are attempting to access. 

* [ ] What is the difference between "=" and "==="?
The single equal sign is an assignment of value to something like 3-1 = 2. The double and triple equal signs are to check if an expression is equal to something else. 

* [ ] How many times will "Hello World" print in this loop? Justify your reasoning.
```Javascript
for ( var i = 0; i < 10; i++ ){
	var string = "Hello World";
}
console.log("Hello World")
```
"Hello World" will print at least 9 times. You are requsting that it print less than 10. 

* [ ] What's the difference between forking a repo and cloning a repo?
Cloning gives you a copy of a repo to your local machine whereas forking means that you are able to make changes to the work that you have cloned. 

* [ ] What is a conditional? Provide an example as well.
Condtional statements are statements used to perform different actions based on different conditions.

* [ ] Given the following loop :
```Javascript
for (var key in myObj){
myObject.name = "LeBron"
	var myObject = (name: "LeBron")
}
```
What does "key" represent? Is this something you can rename? If so, to what? If not, why not?
A key is a property or an object description. You can change this by overriding the original key or property. 
* [ ] How do you execute the code in a function? For example, how do I get this function to execute?
```Javascript
var func = function(){
	console.log("function executed");

	You have to "call" or invoke the function at the end of the code. You type the name of the function and then you pass in the argument(s).
}
```

* [ ] How many arguments can a function take in?
The number of arguments that a function can take is directly proportional to the number of parameters that are declared when the function was initially set up. 
* [ ] What is the difference between "arguments" and "parameters"?

Arguments are the values passed in at the time that you are invoking or calling a function. Perameters are the place holders indicating the number of arguments that will be passed at the time that the function is initially declared. 

* [ ] "Not all properties of an object are methods, but all methods are properties." True or false? Justify your reasoning (you may use code to do so). This is a true statement. Methods indicate a certain action that will be taken on a property. A property can't perform an action. It's more like a description. For instance, property === raw,  poached
method === cookFood

* [ ] What is an anonymous function? What is the opposite of an anonymous function?
An anonymous function is a function that can be passed in as an argument. It is an unnamed function. The opposite of an anonymous function is a named function. 

