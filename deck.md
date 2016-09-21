![GeneralAssemb.ly](images/ga.jpg)

## Javascript 101

---

## Greetings!

Did you know that there are over one billion websites that are live today?

In this workshop, we'll be learning the building blocks that will allow you to get creative and bring your ideas to life.

Note:
5 min

---

## Learning Objectives

- Gain an overview of the JavaScript landscape and its placement in the web ecosystem.
- Practice programmatic thinking by writing pseudo-code.
- Write expressions that both assign and evaluate variables.
- Explain the difference between jQuery and vanilla JS.
- Register and trigger event handlers for jQuery events.  

---

## Introduction: Web Production Workflow

![](images/wp.png)

Note:
10 min

The process of going from an idea to a fully developed and launched site is pretty cool! However, there are many components to building a website that allows for the type of functionality most clients seek today such as in an e-commerce website. A "full stack" developer is someone who can work on both the back-end and front-end of a website. But what exactly do those terms mean? Let's take a closer look to help us understand the web production workflow.

---

## Web Production Workflow

- UX (or User Experience)
- Design
- Front End
- Back End

---

## Front End vs Back End

- Front End: Everything the user can see and interact with on a site.
- Back End:  Involves the database, the server, and application logic that the user does not see.

Note:
Sometimes it can be challenging to describe how the front-end really differentiates from the back-end. Let's further illustrate the difference between the two.

Back-end application logic examples: validation of username and password entered

---

## Languages

- HTML = noun (responsible for the 'things' on the page, e.g image vs paragraph)
- CSS = adjective (responsible for styles like color or font family)
- JavaScript = verb (responsible for behaviors, like drop-down menus)

Note:
We'll mostly be focusing on JavaScript as a front end language in this lesson. So let's break down the THREE front end languages - HTML, CSS, and JavaScript.

---

## Activity

Let's go to [lyft.com](https://www.lyft.com/)

Which parts of the site are front end and which are back end?

Note:
Hover over "Explore".

Turn to the person next to you and navigate through the site.

In summary, and in your own words, how would you describe how the front end is different from the back end of a website?

---

## What is JavaScript?

So what exactly is JavaScript and what is it responsible for?

- modify the behavior of content
- create interactions and add functionality
- animations
- manipulating what we call the DOM

Note:
10 min

---

## Let's review the DOM

The **Document Object Model (DOM)** is a collection of document nodes that are treated as objects in JavaScript. It is an object model and programming interface for HTML.

Note:
In order for us to truly understand what JavaScript is and what it is used for, we need to first take a look at the DOM (Document Object Model). As we pointed out earlier, JavaScript is responsible for the behavior of content, interactions on the page, animations on the page and manipulating the DOM!

---

## The DOM

![](images/dom.jpg)

Note:
Figuring out the DOM might sound intimidating at first, but not to worry! We've broken it down further here to illustrate how it's related to JavaScript.

---

## Pseudo Code

A way to 'plan out' your program in plain English before coding it.

It will serve as a detailed yet readable description of what a computer program must do.

Note:
(5 min)

Before we start writing any Javascript, we'll learn a bit about how to plan out your code by writing pseudocode. What is pseudocode? Pseudocode is a way to 'plan out' your program in plain English before coding it.

Take, for example, a program that lets a player know whether he or she has passed the current level. Pseudo code for this program might look like the following:

---

## Pseudo Code Example

```js
passingScore = 50 points

get playerScore

if playerScore >= passingScore
    display message "Current level: Passed"
otherwise
    display message "Current level: Failed"
```

Note:
Again, the goal is to think through the problem and break it down into simple steps, which can then be written out in code. Since there are no formal rules as to how pseudo code must be written, each person's version will likely vary slightly. Indentation is often used to keep statements organized and grouped together.

Check: "Why do you think it is important to plan out your program before coding it?"

---

## Independent Practice: Thermostat

With a partner, write pseudo code for an application that would monitor the room temperature and adjust it so the room remains at a certain temperature.

Note:
10 min

Have students open Sublime and type their pseudocode in the text editor.  Then have students share their answers - focus on the logic.  5 min working; 5 minutes summary.

---

## Variables, Data Types and Arithmetic

Now that we've learned a bit about pseudocode, let's begin to code!

Note:
10 min

The first step to learning the fundamentals of JS involves learning to tell our program to remember (store) values. This helps us use them later on!

---

## Variables

The 'container' we use to store a value is called a **variable**. Remember these properties of a variable:
- A variable has a **name** and a **value**.
- The value can change.

---

## Variables

To **declare** a variable, we'll use the following syntax:

```javascript
var age = 29;
```

---

## Variables

If you want to **reassign** a variable, which means change the value of a variable, you can do the following:

```javascript
var age = 29;
age = 30;

```

---

## Data Types

What can be stored in variables?

Note:
There are three main data types or values that we'll want to learn about here.

---

## Strings

Groups of characters (either letters, numbers, or special characters like punctuation, spaces, or parentheses).

- 'hello'
- 'goodbye'
- 'moc.liamg@gmail.com'

Note:
They come in two varieties, 'single-quote' (also sometimes called 'string literals') and "double-quote". Though there are some differences between the two, don't worry about them for now. Strings are typically used to store text for people to read.

---

## Numbers

Can be positive, negative, decimals.

- 20
- -4.5
- 300
- 99.99

---

## Booleans

A data type that has a value of either ```true``` or ```false```

---

## Arithmetic

We use operators to work with data in JavaScript.

```js
2 + 4
=> 6

8 - 1
=> 7

4 / 2
=> 2

2 * 3
=> 6
```

Note:
10 min

The standard arithmetic operators—which you have been learning since grade school—are supported here, including addition, subtraction, division, and so forth. Check it out!

---

## Assignment Operators

Values are assigned using =

```js
var num = 8;
=> 8
```

---

## Assignment Operators

Compound assignment statements, such as += and -=, can also be used.

```js
num += 2;
=> 10

num -= 4;
=> 6
```

---

## Let's Practice!: Variables

http://codepen.io/thatdevgirl/pen/zKoqdK?editors=0010#0

Note:
10 min

---

## jQuery, a JS Library

jQuery is an open-source project that was released in 2006.

It is currently the most widely used JavaScript library on the web.

Note:
10 min

Originally, it was going to be called "JSelect", but the domain name "JSelect.com" was taken, so its creator, John Resig, decided to call it jQuery instead. jQuery allows us to query (i.e. select elements from) the DOM using the exact same selector syntax that we've used in CSS.  It makes it faster and easier to write cross-browser JavaScript and  allows us to find elements using CSS-style selectors and then do something to them using jQuery methods.

---

## jQuery

Here's some basic syntactical differences between Javascript and jQuery

JS
```js
 document.getElementById('heading').innerHTML = "Your Name";
```

jQuery

```js
  $('#heading').html('Your Name');
```

---

## Loading jQuery

Download the compressed version from [online](https://jquery.com/download/).

Or, link to jQuery directly:

	<script src="https://code.jquery.com/jquery-3.1.0.min.js"></script>

Note:
jQuery is a Javascript file, but before you start using jQuery, you'll need to include it in our HTML page.

---

## What does jQuery do?

jQuery can be used to manipulate the DOM. Manipulating the DOM is possible because with jQuery you can:

- select certain elements
- work with these elements in some way

---

## What does jQuery do?

You select an element by doing the following:

```js
$('li')
```

or

```js
$('#firstParagraph')
```

Note:
The dollar sign specifies that you are using jQuery, what goes inside the parentheses and quotes is what you are selecting. As you can see, you can use your CSS-style selectors!

---

## What does jQuery do?

You can manipulate or work with certain elements.

```js
.addClass('about-me');

$('h1').html('Content to insert goes here');
```

Note:
For example, ```.addClass``` is a method that you would append to the selected object. In this example you are adding a class called 'about-me'.

In the second example you start by selecting the h1 and then you append the method .html which will change the HTML content that is currently in between the opening and closing h1 tags.  

---

## Let's Practice!
## jQuery Code Along Part 1

http://codepen.io/thatdevgirl/pen/qaqkYP?editors=1010

Note:
15 min

---

## jQuery Effects and Animations

With jQuery you can also add effects and animations.

```js
$('h1').fadeOut(200);
```

Note:
10 min

---

## jQuery Effects and Animations

Additionally, with jQuery you can add what is called an **event listener**.

```js
$('li').on('click', function() {
  // your code here
});
```

Note:
This means that the browser is waiting for an event to occur, the event can be a mouseover or a scroll, for an action to be triggered.

---

## Let's Practice!
## jQuery Code Along Part 2

Back to our code pen!

http://codepen.io/thatdevgirl/pen/qaqkYP?editors=1010

Note:
10 min

---

## jQuery + Conditionals

If something is true, do one thing. If it is not, do something else.

Note:
10 min

This type of logic or statement is a condition. In JavaScript (and coding in general) you'll need to make comparisons all the time:

- Is a user logged in?
- Has the user chosen three or more colors?
- Is the password correct?
- Does a user have enough money in their bank account?
etc.

---

## jQuery + Conditionals

```javascript
if (age > 65) {
    $('h1').html("Senior Discount Applied");

} else if (age < 18) {
    $('h1').html("Student Discount Applied");

} else {
	  $('h1').html("Sorry, you don't qualify for a discount");
}
```

---

## Let's Practice!
## jQuery Code Along Part 3

Back to our code pen!

http://codepen.io/thatdevgirl/pen/qaqkYP?editors=1010

Note:
10 min

---

## Conclusion
So, who needs to know about this stuff? Everyone!

Note:
5 min

Even if you’re not the one doing the coding, being able to communicate effectively with developers and understand what’s going on behind the scenes of a product is a very important and highly valued skill in today’s job market.  

---

## A couple last things.

You are going to get lots of errors...

- Google first, ask questions later (but don't be afraid to ask)
- Stack Overflow is great for this stuff!
- Get immersed!  Coding is hard if you don't get really involved.

---

![GeneralAssemb.ly](images/ga.jpg)

Connect with us for 15% off your next class or workshop!

- Snapchat: GA-DC
- Twitter: GA_DC
- Facebook: GENERALASSEMBLYWASHINGTONDC
- Instagram: GA_DC

---

![GeneralAssemb.ly](images/ga.jpg)

## Thank you!!
