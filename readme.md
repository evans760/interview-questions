#Interview Prep

(Partially from https://github.com/h5bp/Front-end-Developer-Interview-Questions)

Go through all of the following questions and think about how you would respond to each. You should be able to answer many of the questions from memory, but you may have to research a few of them.

**Copy this md file to your homework folder and add a short answer under each item.** You should try to be as concise as possible, and list any handy resources you used to answer the question. This will be useful for studying for interviews after class.

## General Questions

* What did you learn yesterday/this week?
** this week i was working on ____

* What excites or interests you about coding?

* What is a recent technical challenge you experienced and how did you solve it?
** At GA hack a thon chanllenges where a great way to solve challenging techinal problems. Working as a team is always a great experience. Durring the last hack a thon our biggest techinal challenge was getting our user info to be stored in the database. After everyone gave it a solid shot induviually we decided to tackle it as a team and we all ganged up on one computer and went threw the code line by line intill we solved the problem. went to stack overflow and googled questions. asked people. read documentation.

* What UI, Security, Performance, SEO, Maintainability or Technology considerations do you make while building a web application or site?
** I value keeping things clean and simple... user interface to keep the user ingaged and has no troubble surfing the site

* Talk about your preferred development environment.
** I use sublime i enjoy the color scheam. console in browser (chrome) and the terminal. I use a mac.

* Which version control systems are you familiar with?
** Git we fork, clone, create new respitories, do lots of commits, ext. 

* Can you describe your workflow when you create a web page?
** The first thing is to create a plan. What exactly is the purpose of the projcet. Then i'll do some wire framing to get a good visualization of what i want to create. 

* If you have 5 different stylesheets, how would you best integrate them into the site?
** If I have 5 diffrent style sheets I would make a style folder and put them in order as to how I would like them to appear. depending on the purpous of each style sheet.

* Can you describe the difference between progressive enhancement and graceful degradation?
** these are 2 development approcehes. Graceful degradation is where you start with the most up to date technoigies (modern browsers) then move down to

* Describe how you would create a simple slideshow page, without any frameworks (HTML/CSS/JS only).
** first i would make a div to list my images inside of. second I would set the javascript to hide all the pictures but one and then go threw the pictures showing them one by one to give the slide show effect. I would achieve this by creating a function and iterating threw the slides with a loop.

* If you could master one technology this year, what would it be?
** I would love to master Javasript and css. I will continue to learn about javascript and css forever. and ever. I love javasript because it is constantlly a challenge.

* Explain the importance of standards and standards bodies.
** if you follow standards its like follwing guidelines and everyone will know what and how you created something. Standards bodies are stardards used by computer programmers to have a standard for the internet. It's the bar to achive to. accessablilty is a big standerd for today. 

## HTML Questions

* What does a `doctype` do?
** the doctype is the very first thing in an html doc. although it is not a html tag. it is a instruction to the web browser about what version of the mark up language the page is written in. 

* What's the difference between HTML and XHTML?
**hyper text mark up language and extensible hyper text mark up language. XHTML is stricter than html. Xhtml is supported by all major browsers.

* What are `data-` attributes good for?
** any attribute on any element whos attrributes name starts with a data- is a data attribute. say you have an article and you want to store some extra informaiton that dosent have any visual representation. just use the data attribute for that. it stores data in a tag. 

* Describe the difference between a `cookie`, `sessionStorage` and `localStorage`.
** localStorage and sessionStorage are both so called webStorages. localStorage stores information as log as the user does not delete them. SessionStorage stores information as long as the session is going. Ushally intill the user closes the session/tab/or browser. cookies are supported by older browsers and ushally are fallbacks for frameworks that use the above mentioined web storages. in contrast cookies can store way less than webstorages. and information in webStorages is never transfured to the server.

* Why is it generally a good idea to position CSS `<link>`s between `<head></head>` and JS `<script>`s just before `</body>`? Do you know any exceptions?
** Here is how things happen when a browser loads a website. 1. Fetch the html page. (index.html) 2. begin parsing the html. 3. THe parser incounters the <script> tags refrecing an exteral script file. 4. the browser requests the script file. Meanwhile the parser blocks and stops parsing the other html on your page. 5. after some time the <script> is downloaded and subsequently executed. 6. the parser continues parsing the rest of the html document. It is a good idea to put the css links before the <body> starts so that your styles load quickly and the user sees somthing right away instead of a blank page. 


## CSS Questions

* What is the difference between classes and IDs in CSS?
** the implied rule is no two elements should have the same ids. many elements on a page can have the same class. an identifier (id) must be specific to a certin indentifer. An Id is unique and a class is not. 

* What's the difference between "resetting" and "normalizing" CSS? Which would you choose, and why?
** resetting css means getting rid of all styining and normalizing css means making sure the styling is consistant threwout all browsers. normalizing css is faster since it maintains some styles that makes sence for certian classes such as headings. Normalizing is mainly a set of default styles, based on what the author thought would look good, and consistant across browsers. Reset basiclly stips styinings from elements so you have more controll over the stying of everything.

* Describe Floats and how they work.
** A float specifies that an element sould be taken from the normal flow and placed along the left or right side of the container, where the text and inline elements will wrap around it. floats allow elements to be pushed to the left or the right  allowing other elements to be wrapped around it. floats are often used with images but they are also useful when working with layouts.

* Describe z-index and how stacking context is formed.
** with out z-index divs stack in a specific order. without z-index you content will mostlikley overlap. if you want to specificy the stcking order you have to position the element and use the z-index property. the z index specifies the stack order of an element. an element with a greater stack order is allways in front of an element with a lower stack order. 

* Have you ever used a grid system, and if so, what do you prefer?
** bootstrap and http://materializecss.com/ http://foundation.zurb.com/ THey are straight forward and easy to use some are better for a qick layout some are more versitile.  

* Have you used or implemented media queries or mobile specific layouts/CSS?
 
* How do you optimize your webpages for print?
** you can create a style sheet for print. you can create a style sheet and set the media querry to "print" at the end of the element in the header. this will allow you to create custom css classes applied only at the time of print. make sure your structured css file is given a media attribute "all". Set content area to 600px. to insure the words dont run off the page. you can remove the header and any background images.

* What are the advantages/disadvantages of using CSS preprocessors?
** A css processor is a scripting language that extends css by allowing developers to write code in one languge and then compile it into css. SCSS is a css processer allows you to use things like variables, nested rules, inline imports and more. they also help keep things organized.

  * Describe what you like and dislike about the CSS preprocessors you have used.

* How would you implement a web design comp that uses non-standard fonts?
** Ifs its a google font just use a link tag with the minimum amout of fonts neccessary. online font generators are easy to use. they can be put in css files if they are caarzy long. 

* Explain how a browser determines what elements match a CSS selector.
** Browsers read selectors from right to left. First looking for all elements matching the key selector(the right most). then it checks if it matches or is under the next (left most) element.

* Explain your understanding of the box model and how you would tell the browser in CSS to render your layout in different box models.
** the box model is the box that wraps around every html element. It consists of margins, borders padding and the actual content. 
* What does ```* { box-sizing: border-box; }``` do? What are its advantages?
** if you set a width, and add padding and boarders, the total width won't change. The inner width will adapt. The Advantages are you can play with the padding and boarder values without worring about expanding you box. very convient for column layouts. You can mix percentages with pixel values, so you don't have to worry about a child element for the padding.
* List as many values for the display property that you can remember.
* What's the difference between inline and inline-block?
** elements with display inline-block are like display inline elements but they can have a width and height. That means you can use an inline-block elements as a block while flowing it within textor other elements.
* What's the difference between a relative, fixed, absolute and statically positioned element?
* The 'C' in CSS stands for Cascading.  How is priority determined in assigning styles (a few examples)?  How can you use this system to your advantage?
* What existing CSS frameworks have you used locally, or in production? How would you change/improve them?
* Have you played around with the new CSS Flexbox or Grid specs?
* Have you ever worked with retina graphics? If so, when and what techniques did you use?
* Explain some of the pros and cons for CSS animations versus JavaScript animations.

## JS Questions

* Explain event delegation
* Explain how `this` works in JavaScript
* Explain how prototypal inheritance works
* Why is it called a Ternary expression, what does the word "Ternary" indicate?
* What's the difference between a variable that is: `null`, `undefined` or `undeclared`?
  * How would you go about checking for any of these states?
* What is a closure, and how/why would you use one?
* What's a typical use case for anonymous functions?
** ajax calls... if you are exucuting a block of code only once... 
* Difference between: `function Person(){}`, `var person = Person()`, and `var person = new Person()`?
** 1st.function called person  2nd calling a person function 3rd. creating an object out of this function...more to this

* What's the difference between `.call` and `.apply`?
* Explain `Function.prototype.bind`.
* What's the difference between feature detection, feature inference, and using the User Agent string?
* Explain AJAX in as much detail as possible.
** ajax is used to make things such as api requests happens after the page is loaded without reloading the page. ajax is a request and respose to a server. 
* Have you ever used JavaScript templating?
  * If so, what libraries have you used?
* Explain "hoisting".
* Describe event bubbling.
* What's the difference between an "attribute" and a "property"?
* Why is extending built-in JavaScript objects not a good idea?
* What is the difference between `==` and `===`?
* Explain the same-origin policy with regards to JavaScript.
* What is the extent of your experience with Promises and/or their polyfills?
* What are the pros and cons of using Promises instead of callbacks?
* What tools and techniques do you use debugging Javascript code?
* What language constructions do you use for iterating over object properties and array items?

## Database Questions

* Design a database schema for Facebook, with at least 4 models, a complete set of attributes for each model, a 1:M association, and a M:M association.

## Ruby/Rails
* What are ruby gems?
* What is the difference between a symbol and a string?
* What is the difference between a class method and an instance method?
* What is the difference between local variables, instance variables, and class variables?
* What is a range?
* In ruby, what does attr_accessor do?  
* What is the purpose of environment files under the config folder in Rails? (development, test, production)
* What is the purpose of the application.rb file in Rails?
* How can you define a constant?
* What is the purpose of `yield`?
* How do you store API keys when creating an app?
* How do I send parameters through a url?
* Explain MVC
* What is a `before_action`? When would you use it?
* What do controllers do in rails?
* What is RESTful routing?
* What is a polymorphic association?
* What are params?
* How do I make a migration to add a column in Rails?
* What is CSRF? How does Rails protect an app against this?
** 
* What's the difference between `User.find_by_id(1)` and `User.find(1)`?
* What's are classes in Ruby? What are modules? And what's the difference?

## Testing Questions

* What are some advantages/disadvantages to testing your code?
** advantages code is going to come out working downfall is time. 
* What tools would you use to test your code's functionality?
* What is the difference between a unit test and a functional/integration test?
* What is the purpose of a code style linting tool?
* What is End-to-end (E2E) testing? How can it be implemented in frameworks like Angular and Rails?

## Coding Questions:

*Question: What is the value of `foo`?*
```javascript
var foo = 10 + '20';
```

*Question: How would you make this work?*
```javascript
add(2, 5); // 7
add(2)(5); // 7
```

*Question: What value is returned from the following statement?*
```javascript
"i'm a lasagna hog".split("").reverse().join("");
```

*Question: What is the outcome of the two alerts below?*
```javascript
var foo = "Hello";
(function() {
  var bar = " World";
  alert(foo + bar);
})();
alert(foo + bar);
```

*Question: What is the value of `foo.length`?*
```javascript
var foo = [];
foo.push(1);
foo.push(2);
```

*Question: What is the value of `foo.x`?*
```javascript
var foo = {n: 1};
var bar = foo;
foo.x = foo = {n: 2};
```

*Question: What does the following code print?*
```javascript
console.log('one');
setTimeout(function() {
  console.log('two');
}, 0);
console.log('three');
```

## Fun Questions:

* What's a cool project that you've recently worked on?
* What are some things you like about the developer tools you use?
* Do you have any pet projects? What kind?
* How do you like your coffee?
