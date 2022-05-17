# BANKI: All the questions to prep for interviews
- Any questions on this list are fair game for technical interviews. 
- Resources where you can find most answers are at the end.
- Origianl list without anwsers courtesy of https://leonnoel.com/100devs/
  
## Behavioral
Most of the behavioral questions should be answered in the CAR format. At least three sentences for each question (one for cause, one for action and one for result). When answering being with "At my last opportunity..." or "At my last company" Don't sell yourself out and say "bootcamp" or "school"

### CAR
- **Cause**
	- Why did you need to take action?
- **Action**
	- Steps you took so solve problem.
	- Be positive
	- Don't be humble
- **Result**
	- How are you better?

### Questions
- [x] Give me an example of a project or initiative that you started on your own. What prompted you to get started?
	- **Cause:** At a previous company we had project managers assigned to several different teams where workload would fluctuate quite a bit.
	- **Action:** I noticed an opportunity to flatten the workload of the PM's, by creating a shared PM pool. 
	- **Result:** This was possible by running a high level kanban of all projects assigned by PM to get visibility to workload. It also allowed knowledge sharing such that it was much easier for a PM to step in on any given team.
- [x] Tell me about a time you had to work on several projects at once. How did you handle this?
	- **Cause:** I was working on two large projects for two separate clients that were at different stages of their lifecycle. One project was in production and the other project was in the implementation phase.
	- **Action:** I decided to send a less experienced colleague to the installation site while I went to do a production check-in on the other project in China. Prior to leaving I briefed my colleague in on the project and told then what to look out for.
	- **Result:** While in China I had daily calls with my colleague as well as received daily photo reports to review the installation. Both projects end up being financially successful. The tight communication and teamwork is ultimately what allowed it to be so.
- [ ] Describe a situation in which you felt you had not communicated well enough. What did you do? How did you handle it?
	- **Cause:**
	- **Action:**
	- **Result:**
- [ ] Tell me about when you had to deal with conflict within your team. How was the conflict solved? How did you handle that? How would you deal with it now?
	- **Cause:**
	- **Action:**
	- **Result:**
- [ ] Give me an example of a time you had to take a creative and unusual approach to solve coding problem. How did this idea come to your mind? Why do you think it was unusual?
	- **Cause:**
	- **Action:**
	- **Result:**
- [ ] Describe a situation in which you worked diligently on a project and it did not produce the desired results. Why didn't you get the desired results? What did you learn from the experience?
 	- **Cause:**
	- **Action:**
	- **Result:**
- [ ] Give an example of an important project goal you reached and how you achieved it.
 	- **Cause:**
	- **Action:**
	- **Result:**
- [ ] Describe a situation in which you experienced difficulty in getting others to accept your ideas? What was your approach? How did this work? Were you able to successfully persuade someone to see things your way
	- **Cause:**
	- **Action:**
	- **Result:**
- [ ] Tell me about a situation when you were responsible for project planning. Did everything go according to your plan? If not, then why and what kind of counteractions did you have to take?
 	- **Cause:**
	- **Action:**
	- **Result:**
- [ ] Tell me about a situation when you made a mistake at work. What happened exactly and how did you deal with it? What steps did you take to improve the situation?
 	- **Cause:**
	- **Action:**
	- **Result:**
- [ ] Tell me about a time when you worked with someone who was not completing his or her share of the work. How did you handle the situation? Did you discuss your concern with your coworker? With your manager? If yes, how did your coworker respond to your concern? What was your manager's response?
 	- **Cause:**
	- **Action:**
	- **Result:**
- [ ] Describe a situation when you worked effectively under pressure. How did you feel when working under pressure? What was going on, and how did you get through it?
 	- **Cause:**
	- **Action:**
	- **Result:**
- [ ] Tell me about yourself.
 	- **Cause:**
	- **Action:**
	- **Result:**
- [ ] Tell me about your experience at 100Devs. 
 	- **Cause:**
	- **Action:**
	- **Result:**
- [ ] What do you know about our company?
 	- **Cause:**
	- **Action:**
	- **Result:**
- [ ] Why do you want to work for us?
 	- **Cause:**
	- **Action:**
	- **Result:**
- [ ] Why are you interested in this opportunity?
 	- **Cause:**
	- **Action:**
	- **Result:**
- [ ] Tell me about your dream job?  What do you really want to do with your career?
 	- **Cause:**
	- **Action:**
	- **Result:**
- [ ] Tell me a time when you failed.
 	- **Cause:**
	- **Action:**
	- **Result:**
- [ ] What do you read on a regular basis?
 	- **Cause:**
	- **Action:**
	- **Result:**
- [ ] What's some critical feedback you've gotten recently?
 	- **Cause:**
	- **Action:**
	- **Result:**
- [ ] Do you have any questions?
 	- **Cause:**
	- **Action:**
	- **Result:**

## Technical Questions

Most of the technical questions should have a three sentence response in the EUE format:
- **Explanation**
- **Use**
- **Example**

### HTML
- [x]  What does a doctype do?
	- **Explanation:** Instruction to the browser about what version of HTML the webpage is written in, ensuring the web page is parsed the same way across web browsers.
	- **Use:** It's the first line of code in the HTML document.
	- **Example:** For an HTML5 document the tag would be `<!DOCTYPE html>`
- [ ]   How do you serve a page with content in multiple languages?  
	- Explanation:
	- Use:
	- Example:
- [ ]   What kind of things must you be wary of when design or developing for multilingual sites?   
	- Explanation:
	- Use:
	- Example:
- [ ]   What are data- attributes good for?   
	- Explanation:
	- Use:
	- Example:
- [ ]   Consider HTML5 as an open web platform. What are the building blocks of HTML5?   
	- Explanation:
	- Use:
	- Example:
- [ ]   Describe the difference between a cookie, sessionStorage and localStorage.   
	- Explanation:
	- Use:
	- Example:
- [ ]   Describe the difference between `<script>, <script async> and <script defer>`.  
	- Explanation:
	- Use:
	- Example:
- [ ]   Why is it generally a good idea to position CSS `<link>s between <head></head> and JS <script>s just before </body>`? Do you know any exceptions?   
- [ ]   What is progressive rendering?   
- [ ]   Why you would use a srcset attribute in an image tag? Explain the process the browser uses when evaluating the content of this attribute.   
- [ ]   Have you used different HTML templating languages before?  

### CSS
- [x]  What is CSS selector specificity and how does it work?  
	- Explanation: The means by which browsers decide which CSS property values are the most relevant to an element and, therefore, will be applied.
	- Use: Specificity is a weight that is applied to a given CSS declaration, determined by the number of each selector type in the matching selector.
	- Example: A selector of `#id .class tag` would have 111 points as id's count for 100, classes for 10 and tags 1.
- [ ]  What's the difference between "resetting" and "normalizing" CSS? Which would you choose, and why?   
	- Explanation
	- Use
	- Example
- [ ]  Describe floats and how they work.  
	- Explanation
	- Use
	- Example
- [ ]  Describe z-index and how stacking context is formed.   
	- Explanation
	- Use
	- Example
- [ ]  Describe BFC (Block Formatting Context) and how it works.   
	- Explanation
	- Use
	- Example
- [ ]  What are the various clearing techniques and which is appropriate for what context?   
- [ ]  Explain CSS sprites, and how you would implement them on a page or site.   
- [ ]  How would you approach fixing browser-specific styling issues?   
- [ ]  How do you serve your pages for feature-constrained browsers? What techniques/processes do you use?   
- [ ]  What are the different ways to visually hide content (and make it available only for screen readers)?   
- [ ]  Have you ever used a grid system, and if so, what do you prefer?   
- [ ]  Have you used or implemented media queries or mobile specific layouts/CSS?   
- [ ]  Are you familiar with styling SVG?   
- [ ]  Can you give an example of an @media property other than screen?   
- [ ]  What are some of the "gotchas" for writing efficient CSS?   
- [ ]  What are the advantages/disadvantages of using CSS preprocessors?   
- [ ]  Describe what you like and dislike about the CSS preprocessors you have used.   
- [ ]  How would you implement a web design comp that uses non-standard fonts?   
- [ ]  Explain how a browser determines what elements match a CSS selector.   
- [ ]  Describe pseudo-elements and discuss what they are used for.   
- [ ] Explain your understanding of the box model and how you would tell the browser in CSS to render your layout in different box models.   
- [ ]  What does * { box-sizing: border-box; } do? What are its advantages?   
- [ ]  What is the CSS display property and can you give a few examples of its use?   
- [ ]  What's the difference between inline and inline-block?   
- [ ]  What's the difference between a relative, fixed, absolute and statically positioned element?   
- [ ] What existing CSS frameworks have you used locally, or in production? How would you change/improve them?   
- [ ]  Have you played around with the new CSS Flexbox or Grid specs?   
- [ ] Can you explain the difference between coding a web site to be responsive versus using a mobile-first strategy?   
- [ ]  How is responsive design different from adaptive design?   
- [ ]  Have you ever worked with retina graphics? If so, when and what techniques did you use?   
- [ ] Is there any reason you'd want to use translate() instead of absolute positioning, or vice-versa? And why?   

### Javascript
- [x] Explain event delegation   
	- Explanation: Setting an event listener on a parent element an having events that happen on a child element bubble up to the parent.
	- Use: When you want some code to run when the user interacts with any one of a large number of child elements.
	- Example: ```
	<div id="container">
	  <div class="tile"></div>
	</div>
	container.addEventListener('click', event => event.target.style.backgroundColor = bgChange());```
- [ ] Explain how this works in JavaScript   
	- Explanation
	- Use
	- Example
- [ ] Explain how prototypal inheritance works   
	- Explanation
	- Use
	- Example
- [ ] What do you think of AMD vs CommonJS?   
	- Explanation
	- Use
	- Example
- [ ]  Explain why the following doesn't work as an IIFE: function foo(){ }();. What needs to be changed to properly make it an IIFE?   
	- Explanation
	- Use
	- Example
- [ ]  What's the difference between a variable that is: null, undefined or undeclared? How would you go about checking for any of these 
	- Explanation
	- Use
	- Examplestates?   
- [ ] What is a closure, and how/why would you use one?   
- [ ]  Can you describe the main difference between a .forEach loop and a .map() loop and why you would pick one versus the other?   
- [ ] What's a typical use case for anonymous functions?   
- [ ] How do you organize your code? (module pattern, classical inheritance?)   
- [ ] What's the difference between host objects and native objects?   
- [ ] Difference between: function Person(){}, var person = Person(), and var person = new Person()?   
- [ ]   What's the difference between .call and .apply?   
- [ ]   Explain Function.prototype.bind.   
- [ ]   When would you use document.write()?   
- [ ]   What's the difference between feature detection, feature inference, and using the UA string?   
- [ ]   Explain Ajax in as much detail as possible.  
- [ ]   What are the advantages and disadvantages of using Ajax?  
- [ ]   Explain how JSONP works (and how it's not really Ajax).   
- [ ]   Have you ever used JavaScript templating? If so, what libraries have you used?   
- [ ]   Explain "hoisting".   
- [ ]   Describe event bubbling.  
- [ ]   What's the difference between an "attribute" and a "property"?   
- [ ]   Why is extending built-in JavaScript objects not a good idea?   
- [ ]   Difference between document load event and document DOMContentLoaded event?   
- [ ]   What is the difference between == and ===?   
- [ ]   Explain the same-origin policy with regards to JavaScript.   
- [ ]   Make this work: duplicate([1,2,3,4,5]); // [1,2,3,4,5,1,2,3,4,5]   
- [ ]   Why is it called a Ternary expression, what does the word "Ternary" indicate?   
- [ ]   What is "use strict";? what are the advantages and disadvantages to using it?  
- [ ]  Create a for loop that iterates up to 100 while outputting "fizz" at multiples of 3, "buzz" at multiples of 5 and "fizzbuzz" at multiples of 3 and 5   
- [ ]   Why is it, in general, a good idea to leave the global scope of a website as-is and never touch it?   
- [ ]  Why would you use something like the load event? Does this event have disadvantages? Do you know a ny alternatives, and why would you use those?   
- [ ]   Explain what a single page app is and how to make one SEO-friendly.   
- [ ]   What is the extent of your experience with Promises and/or their polyfills?   
- [ ]   What are the pros and cons of using Promises instead of callbacks?   
- [ ]  What are some of the advantages/disadvantages of writing JavaScript code in a language that compiles to JavaScript?  
- [ ]   What tools and techniques do you use debugging JavaScript code? 
- [ ]   What language constructions do you use for iterating over object properties and array items?
- [ ]   Explain the difference between mutable and immutable objects. 
- [ ]   Explain the difference between synchronous and asynchronous functions.  
- [ ]   What is event loop? What is the difference between call stack and task queue?  
- [ ]   Explain the differences on the usage of foo between function foo() {} and var foo = function() {} 
- [ ]   What are the differences between variables created using let, var or const?   
- [ ]   What are the differences between ES6 class and ES5 function constructors?  
- [ ] Can you offer a use case for the new arrow => function syntax? How does this new syntax differ from other functions?   
- [ ]   What advantage is there for using the arrow syntax for a method in a constructor? 
- [ ]   What is the definition of a higher-order function? 
- [ ]   Can you give an example for destructuring an object or an array? 
- [ ]   ES6 Template Literals offer a lot of flexibility in generating strings, can you give an example? 
- [ ]   Can you give an example of a curry function and why this syntax offers an advantage? 
- [ ]   What are the benefits of using spread syntax and how is it different from rest syntax?
- [ ]   How can you share code between files?  
- [ ]   Why you might want to create static class members? 

### Javascript General
- [x] Can you name two programming paradigms important for JavaScript app developers?   
	- OOP and Functional Programming are the most often used. OOP allows inheritance via different "classes". Functional is pure-functions without side effects.
- [ ] What is functional programming?  
	- Explanation
	- Use
	- Example
- [ ] What is the difference between classical inheritance and prototypal inheritance?   
	- Explanation
	- Use
	- Example
- [ ] What are the pros and cons of functional programming vs object-oriented programming?  
	- Explanation
	- Use
	- Example
- [ ] What are two-way data binding and one-way data flow, and how are they different?  
	- Explanation
	- Use
	- Example
- [ ] What is asynchronous programming, and why is it important in JavaScript?  
	- Explanation
	- Use
	- Example

### Node
- [x] What is Node.js? Where can you use it?   
	- Node.js is a single-threaded, open-source, cross-platform runtime environment used to build server side and networking applications. IT uses event-driven, non-blocking I/O architecture, which makes it efficient and suitable for real-time applications.
- [ ] Why use Node.js?  
	- Explanation
	- Use
	- Example
- [ ] What are the features of Node.js?   
	- Explanation
	- Use
	- Example
- [ ] How do you update NPM to a new version in Node.js?   
	- Explanation
	- Use
	- Example
- [ ] Why is Node.js Single-threaded?   
	- Explanation
	- Use
	- Example
- [ ] Explain callback in Node.js.   
- [ ] What is callback hell in Node.js?   
- [ ] How do you prevent/fix callback hell?   
- [ ] Explain the role of REPL in Node.js.   
- [ ] Name the types of API functions in Node.js.  
- [ ] What are the functionalities of NPM in Node.js?   
- [ ] What is the difference between Node.js and Ajax?  
- [ ] What are “streams” in Node.js? Explain the different types of streams present in Node.js.  
- [ ] Explain chaining in Node.js.   
- [ ] What are Globals in Node.js?   
- [ ] What is Event-driven programming?   
- [ ] What is Event loop in Node.js work? And How does it work?  
- [ ] What is the purpose of module.exports in Node.js?  
- [ ] What is the difference between Asynchronous and Non-blocking?   
- [ ] What is Tracing in Node.js?   
- [ ] How will you debug an application in Node.js?  
- [ ] Difference between setImmediate() vs setTimeout()?   
- [ ] What is process.nextTick()   
- [ ] What is package.json? What is it used for?   
- [ ] What is libuv?   
- [ ] What are some of the most popular modules of Node.js?   
- [ ] What is EventEmitter in Node.js?   

### CS Theory 
- [x] What is recursion and give an example using javascript?   
	- Explanation: Recursion is when a function call itself within it's own body. Besides the recursive call it should always have a base case which stops it from calling itself which prevents infinite loops.
	- Use: Recursion is made for solving problems that can be broken down into smaller, repetitive problems. It is especially good for working on things that have many possible branches and are too complex for an iterative approach.
	- Example: A classic example is computing a factorial given a number "num":
	- ```function factorial(num){
	    if(num === 1){
	        return num;
	    }
		return num * factorial(num-1)
	}```
- [ ] What are types?   
	- Explanation
	- Use
	- Example
- [ ] What are data structures?   
	- Explanation
	- Use
	- Example
- [ ] What is an algorithm?    
	- Explanation
	- Use
	- Example
- [ ] What is scope / lexical scope in javascript?    
	- Explanation
	- Use
	- Example
- [ ] What is polymorphism?   
	- Explanation
	- Use
	- Example
- [ ] What is encapsulation?    
	- Explanation
	- Use
	- Example
- [ ] What is a Linked List   
- [ ] What is a Doubly Linked List   
- [ ] What is a Queue   
- [ ] What is a Stack   
- [ ] What is a Hash Table   
- [ ] What is a Heap   
- [ ] What is a Trie   
- [ ] What is a Tree   
- [ ] What is a Binary Search Tree   
- [ ] What is a Disjoint Set   
- [ ] What is a Bloom Filter   
- [ ] Demonstrate Bubble Sort and explain when you might use it?   
- [ ] Demonstrate Insertion Sort and explain when you might use it?  
- [ ] Demonstrate Merge Sort and explain when you might use it?   
- [ ] Demonstrate Quicksort and explain when you might use it?

## Questions to ask your interviewer
1. How does Bob’s Burgers measure the success of their engineers?
2. What challenges can an engineer come across working at Bob’s Burgers?
3. Can you explain "thing you read on their engineering blog" and how it affects Bob’s Burgers Engineers?
4. What traits in an engineer are hard to find in an engineer that Bob’s Burgers would like to have?
5. How is critique given to engineers at Bob’s Burgers?
6. Do you have any questions or concerns about my qualifications?  

Here is a helpful list of other reverse interview questions: [https://github.com/viraptor/reverse-interview](https://github.com/viraptor/reverse-interview)


## Whiteboard
When talking through a whiteboard problem or a coding challenge with an interviewer you should use the PREP method. (Don't write PREP in the actual interview, but use it now while doing codewars/leetcode). Going through this will help you engage with the interviewer (and possibly burn up some time 😉)

- **Parameters**
	- Inputs
	- Ask questions
		- Will it always be a number? 
		- Will it ever be negative? 
		- Any gotchas? 
- **Returns**
	- Ask questions
		- Do you want it returned or is a console.log better?
		- Should I pass a whole array of solutions back or just a single solution?
- **Examples**
	- Show a couple black box examples aka test cases
		- I pass in these arguments and get these results, is that correct?
	- Examples are a good idea because "you have the receipts" if the interviewer decides to change things.
- **Pseudocode**
	- Write pseudocode of each of the steps

## Resources:
- [https://eloquentjavascript.net/](https://eloquentjavascript.net/)
- [https://github.com/getify/You-Dont-Know-JS](https://github.com/getify/You-Dont-Know-JS)
- [https://github.com/yangshun/front-end-interview-handbook](https://github.com/yangshun/front-end-int- erview-handbook)
- [https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95)
- [https://www.simplilearn.com/node-js-interview-questions-and-answers-article](https://www.simplilearn.com/node-js-interview-questions-and-answers-article)
- [https://medium.com/@vigowebs/frequently-asked-node-js-interview-questions-and-answers-b74fa1f20678](https://medium.com/@vigowebs/frequently-asked-node-js-interview-questions-and-answers-b74fa1f20678)
