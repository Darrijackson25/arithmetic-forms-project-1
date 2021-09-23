1. Describe what the id attribute is.

An id attribute is a way of identifing an html element, by giving it a specific name.

2. What is the id attribute most used for? Name two uses.

It is used for the style sheet to customize a specfic part of your html and also used for javascript to manipulate certain elements.

3. Should an id be unique within a page?

It should be unique so that it is easily identified for styling or when using for your javavscript.

4. Which built-in Javascript method do you use in your arithmetic project code to retrieve an element's id? Please name the method and describe what it does.

WE use The document.getElementById() to retrieve the different elements. It is basically selecting that element when you put the name into the parentheses that you want and telling it to do something.

5. If more than one element with the specified id does happen to exist, what does document.getElementById() return?

It will return both because they both have the same name so they will be treated the same, until it is changed.

6. If no element with the specified id passed to document.getElementById() exists, what does document.getElementById() return?

It will not return anything because there is no id that exist for it.

7. What is .value and why do we use it in our arithmetic functions?

The .value is  property that sets or returns the value of a certain id. We use the .value to retrieve the value of the specfic id we want to get.

8. Describe the difference between a referenced function and an invoked (aka called) function. Please provide a code example for both a referenced function and an invoked function. Please provide examples of each using code from the Arithmetic Forms Project 1.

A referenced function is when you refer to something by the name of it and omit the parentheses of that function. An invoked function is when you would use the parentheses to basically call it.
ex refernece function:

Element.addEventListener(“event”, function reference);

ex invoked function:

Element.addEventListener(“event”);


9. Describe what the parseInt() method is, what it does, and why we use it in our arithmetic forms project. Include its syntax and parameters, and provide a code example from your project code using the function expression where it is implemented.

The parseInt() method parses a string that contains a number and returns an integer. We use it for additon part of the project because the number or value is going to be an integer which isnt a fraction or a decimal so it will come out to be a number like 2 or 45 or 80.
Syntax:
parseInt(a) + parseInt(b)

code ex:
const sum = parseInt(num1) + parseInt(num2)

10. variable naming: Go into Mathias Byen's blog post entitled Valid JavaScript variable names in ES2015, and down to his variable name validator tool. Test 3 variable names you think up and check whether they are valid or not using the validator. Describe the 3 variable names that you checked in the variable name validator, whether they passed or not, and if not, why not.

I Used different letter which passed as well as the dollar sign $, and that also passed and the underscore _ also passed. Others like The hastag # and percent % didnt because its said that only letters and digits and nonpunctuation characters are allowed.

11. Declare and initialize a variable with var. Then re-assign the variable to another value.

Describe the outcome, what it was, and why. Make sure to console.log() everything you want to have printed to the Developer Tools Console. Copy and paste the results from the Developer Tools Console into your .md file to show the outcomes. Whatever youconsole.log() inside your JavaScript code will show up in the Chrome Developer Tools Console. console.logging will also help you to better describe the outcome.

ex:
var makeupName = "MAC";
makeuoName = "ELF"
console.log(makeupName) 

This was my statement and what was printed in the console was "MAC" because the makeupName from the first statement seemed to be picked up instead of the second.

12. Declare and initialize a variable with let. Then re-assign the variable to another value.
Describe the outcome, what it was, and why. Make sure to console.log() everything you want to have printed to the Developer Tools Console. Copy and paste the results from the Developer Tools Console into your .md file to show the outcomes. Whatever you console.log() inside your JavaScript code will show up in the Chrome Developer Tools Console. console.logging will also help you to better describe the outcome.

ex:
let n = "ICE CREAM";
n = "HOTDOG"
console.log(n)

This is my statement and what was printed in the console was "HOTDOG". THis was the result because it seems like the console picked up what was re-assigned instead of the previous statement.

13. Declare and initialize a variable with const. Then re-assign the variable to another value.
Describe the outcome, what it was, and why. Make sure to console.log() everything you want to have printed to the Developer Tools Console. Copy and paste the results from the Developer Tools Console into your .md file to show the outcomes. Whatever youconsole.log() inside your JavaScript code will show up in the Chrome Developer Tools Console. console.logging will also help you to better describe the outcome.

ex:
const water = ice;
water = liquid:
console.log(water)

In the console it came up as error, because it is said that you cannot re-assign a const value, array or object. it can only be assigned to one thing.

14. Describe what it means for a var variable to have global scope. Please provide an example.

This means that the var variable would be declared outside of a function

ex:
var HOT = "Fire";

function myFunction() {}

15. Describe what it means for a var variable to have local scope. Please provide a code example.

This means that the variable would have to be declared inside a javascript function.

ex:
function myFunction() {
var HOT = "Fire";
}

16. Describe what it means for a let or const variable to have global scope. Please provide a code example.

What it means for a let or const variable to have global scope is that they would have to be outside of that function.

ex:
let hairLength = "short";
const hairColor = "Brown";

function myFunction() {}

17. Describe what it means for a let or const variable to have block scope. Please provide a code example.

What that means for them to have a block scope is for them to be declared inside of the {} curly braces only.

ex:
{
  let n = 2;
  const y = 1;
}

18. Describe what lexical scope means. And what does it mean in the context of let or const variables? Please provide a code example.

Lexical scope means a variable defined outside of a function can be accessed in another function after the variable that was declared.

ex:
var x = 2;
var add = function() {
    var y = 1;
    return x + y;
};

19. Why do you think it would be preferable (when possible) for a variable to be declared and initialized in the local (or block) scope instead of the global scope?

I think it would be preferable because it would be easier to see what functions are to what variables because they are within the function and easier to read, as opposed to global where one is after the other which could get confusing.

20. What do Mathias Byens and Wes Bos (and I) think about using var with Modern JavaScript (ES6 and beyond)? Please explain their reasoning. And is there a right or wrong choice to make between var vs let and const? Refer to Wes Bos' post s var Dead? What should I use? as a reference.

They think that you should never use var in ES6 because var is mainly used in larger scopes as opposed to const and let for local or smaller scopes. There is no right or wrong choice but something most people prefer to use because let would let you re-assign and const they say you would use by defualt.

21. Take your arithmetic addition form and describe to me what your JavaScript code is doing and what each part is called. For instance, are you using a named function, arrow function, or anonymous function? Are you using a built-in property of Document? Etc. Then describe what these parts do in relation to the DOM (your html markup), and in relation to css selectors, if applicable. Remember, there is a relationship between HTML, CSS, AND JavaScript. Break it down, step by step.

What the javascript code is doing is getting the element by id which is "num1" and "num2" or the id attribute. Then basically trying to get the result by using .innerHTML and addNums when you click on the button. The pareInt is also used to be able to get the numbers which would be integers for this particular one.