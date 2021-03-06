# interview-questions
Interview questions for developer


Job Interview Questions

This file contains a number of interview questions. It is by no means recommended to use every single question here on the same candidate.

Note: These questions are open-ended and could lead to interesting discussions that tell you more about the person's capabilities than a straight answer would.

Table of Contents

    General Questions
    HTML Questions
    CSS Questions
    JS Questions
    Testing Questions
    Performance Questions
    Network Questions
    Coding Questions
    Fun Questions
    Android Questions
    php Quuestions
    Laravel Questions
    MongoDb Questions

General Questions:

    What did you learn yesterday/this week?
    What excites or interests you about coding?
    What is a recent technical challenge you experienced and how did you solve it?
    What UI, Security, Performance, SEO, Maintainability or Technology considerations do you make while building a web application or site?
    Talk about your preferred development environment.
    Which version control systems are you familiar with?
    Can you describe your workflow when you create a web page?
    If you have 5 different stylesheets, how would you best integrate them into the site?
    Can you describe the difference between progressive enhancement and graceful degradation?
    How would you optimize a website's assets/resources?
    How many resources will a browser download from a given domain at a time?
        What are the exceptions?
    Name 3 ways to decrease page load (perceived or actual load time).
    If you jumped on a project and they used tabs and you used spaces, what would you do?
    Describe how you would create a simple slideshow page.
    If you could master one technology this year, what would it be?
    Explain the importance of standards and standards bodies.
    What is Flash of Unstyled Content? How do you avoid FOUC?
    Explain what ARIA and screenreaders are, and how to make a website accessible.
    Explain some of the pros and cons for CSS animations versus JavaScript animations.
    What does CORS stand for and what issue does it address?

HTML Questions:

    What does a doctype do?
    What's the difference between standards mode and quirks mode?
    What's the difference between HTML and XHTML?
    Are there any problems with serving pages as application/xhtml+xml?
    How do you serve a page with content in multiple languages?
    What kind of things must you be wary of when design or developing for multilingual sites?
    What are data- attributes good for?
    Consider HTML5 as an open web platform. What are the building blocks of HTML5?
    Describe the difference between a cookie, sessionStorage and localStorage.
    Describe the difference between <script>, <script async> and <script defer>.
    Why is it generally a good idea to position CSS <link>s between <head></head> and JS <script>s just before </body>? Do you know any exceptions?
    What is progressive rendering?
    Have you used different HTML templating languages before?

CSS Questions:

    What is the difference between classes and ID's in CSS?
    What's the difference between "resetting" and "normalizing" CSS? Which would you choose, and why?
    Describe Floats and how they work.
    Describe z-index and how stacking context is formed.
    Describe BFC(Block Formatting Context) and how it works.
    What are the various clearing techniques and which is appropriate for what context?
    Explain CSS sprites, and how you would implement them on a page or site.
    What are your favourite image replacement techniques and which do you use when?
    How would you approach fixing browser-specific styling issues?
    How do you serve your pages for feature-constrained browsers?
        What techniques/processes do you use?
    What are the different ways to visually hide content (and make it available only for screen readers)?
    Have you ever used a grid system, and if so, what do you prefer?
    Have you used or implemented media queries or mobile specific layouts/CSS?
    Are you familiar with styling SVG?
    How do you optimize your webpages for print?
    What are some of the "gotchas" for writing efficient CSS?
    What are the advantages/disadvantages of using CSS preprocessors?
        Describe what you like and dislike about the CSS preprocessors you have used.
    How would you implement a web design comp that uses non-standard fonts?
    Explain how a browser determines what elements match a CSS selector.
    Describe pseudo-elements and discuss what they are used for.
    Explain your understanding of the box model and how you would tell the browser in CSS to render your layout in different box models.
    What does * { box-sizing: border-box; } do? What are its advantages?
    List as many values for the display property that you can remember.
    What's the difference between inline and inline-block?
    What's the difference between a relative, fixed, absolute and statically positioned element?
    The 'C' in CSS stands for Cascading. How is priority determined in assigning styles (a few examples)? How can you use this system to your advantage?
    What existing CSS frameworks have you used locally, or in production? How would you change/improve them?
    Have you played around with the new CSS Flexbox or Grid specs?
    How is responsive design different from adaptive design?
    Have you ever worked with retina graphics? If so, when and what techniques did you use?
    Is there any reason you'd want to use translate() instead of absolute positioning, or vice-versa? And why?

JS Questions:

    Explain event delegation
    Explain how this works in JavaScript
    Explain how prototypal inheritance works
    What do you think of AMD vs CommonJS?
    Explain why the following doesn't work as an IIFE: function foo(){ }();.
        What needs to be changed to properly make it an IIFE?
    What's the difference between a variable that is: null, undefined or undeclared?
        How would you go about checking for any of these states?
    What is a closure, and how/why would you use one?
    What's a typical use case for anonymous functions?
    How do you organize your code? (module pattern, classical inheritance?)
    What's the difference between host objects and native objects?
    Difference between: function Person(){}, var person = Person(), and var person = new Person()?
    What's the difference between .call and .apply?
    Explain Function.prototype.bind.
    When would you use document.write()?
    What's the difference between feature detection, feature inference, and using the UA string?
    Explain AJAX in as much detail as possible.
    Explain how JSONP works (and how it's not really AJAX).
    Have you ever used JavaScript templating?
        If so, what libraries have you used?
    Explain "hoisting".
    Describe event bubbling.
    What's the difference between an "attribute" and a "property"?
    Why is extending built-in JavaScript objects not a good idea?
    Difference between document load event and document ready event?
    What is the difference between == and ===?
    Explain the same-origin policy with regards to JavaScript.
    Make this work:

duplicate([1,2,3,4,5]); // [1,2,3,4,5,1,2,3,4,5]

    Why is it called a Ternary expression, what does the word "Ternary" indicate?
    What is "use strict";? what are the advantages and disadvantages to using it?
    Create a for loop that iterates up to 100 while outputting "fizz" at multiples of 3, "buzz" at multiples of 5 and "fizzbuzz" at multiples of 3 and 5
    Why is it, in general, a good idea to leave the global scope of a website as-is and never touch it?
    Why would you use something like the load event? Does this event have disadvantages? Do you know any alternatives, and why would you use those?
    Explain what a single page app is and how to make one SEO-friendly.
    What is the extent of your experience with Promises and/or their polyfills?
    What are the pros and cons of using Promises instead of callbacks?
    What are some of the advantages/disadvantages of writing JavaScript code in a language that compiles to JavaScript?
    What tools and techniques do you use debugging JavaScript code?
    What language constructions do you use for iterating over object properties and array items?
    Explain the difference between mutable and immutable objects.
        What is an example of an immutable object in JavaScript?
        What are the pros and cons of immutability?
        How can you achieve immutability in your own code?
    Explain the difference between synchronous and asynchronous functions.
    What is event loop?
        What is the difference between call stack and task queue?

Testing Questions:

    What are some advantages/disadvantages to testing your code?
    What tools would you use to test your code's functionality?
    What is the difference between a unit test and a functional/integration test?
    What is the purpose of a code style linting tool?

Performance Questions:

    What tools would you use to find a performance bug in your code?
    What are some ways you may improve your website's scrolling performance?
    Explain the difference between layout, painting and compositing.

Network Questions:

    Traditionally, why has it been better to serve site assets from multiple domains?
    Do your best to describe the process from the time you type in a website's URL to it finishing loading on your screen.
    What are the differences between Long-Polling, Websockets and Server-Sent Events?
    Explain the following request and response headers:
        Diff. between Expires, Date, Age and If-Modified-...
        Do Not Track
        Cache-Control
        Transfer-Encoding
        ETag
        X-Frame-Options
    What are HTTP actions? List all HTTP actions that you know, and explain them.


Android Questions:

    Describe Android Application Architecture.
    What are the different phases of the Activity life cycle? 
    What is an Explicit Intent?
    What is an AndroidManifest file?
    What is the significance of the .dex files?
    What does ADT stand for?
    What are the different tools in Android? Explain them?
    What is the difference between Service and Thread? 
    What is a Content Provider? 
    What is the difference between a regular bitmap and a nine-patch image?
    Difference between Activity and Fragment.
    Where do you use fragments?
    Describe fragment life cycle?
    What life cycle methods are called on rotating or changing the orientation of the phone?
    How do you prevent data loss on rotating or changing the orientation of the phone?
    What is the relationship between the life cycle of an AsyncTask and an Activity? What problems can this result in? How can these problems be avoided?
    What do you do for memory management in your app?
    Explain RecyclerView.
    Explain ViewPager.
    Explain design patterns used in app- singleton, MVC, MVP etc.
    Explain JSON parsing. Why is JSON parsing preferred over XML parsing?
    Explain Network libraries used in project.
    What is Service?Explain different types of service in Android.
    What are BroadcastReceiver?
    How do you check Network Connection in your App?
    Explain SQLite and its usage in your app.
    Difference between View.GONE and View.INVISIBLE?
    New Features in Android
    Explain material design in Android
    Notifications and deeplinking in android.
    Image Libraries used in app and how do they work.
    Third party libraries used in app.
    Explain the layouts and views in a given screen.    




Core Java:

    Expalin OOPS concepts.- Inheritance and Polymorphism
    Explain Access Modifiers
    Difference between Overloading and Overriding.
    Explain HashMap and ArrayMap and where do you use it.
    What is the difference between String, String Builder and string buffer.
    Explain ArrayList





Laravel Questions

	What are the main differences between Laravel 4 and Laravel 5.x?
	What is routing and how, and what are the different ways to write it?
	What is Composer?
	How to implement you own package in Laravel?
	What is database migration? And how to use it to add insert initial data to database?
	Explain Events in Laravel ?
	Which template engine Laravel use ?
	What are service providers in laravel ?
	What does “composer dump-autoload” do?
	What are Implicit Controllers ?
	Explain Laravel service container ?
	How can you get users IP address in Laravel ?
	What are Laravel Facades ?
	What is Method Spoofing in Laravel ?



PHP Quuestions

	Have you created or managed some web service?
 	What web service protocols do you know?



General SQL

	What is the difference between a View and a Table?
	What does the HAVING clause do?
	How do you choose a column to be indexed?

Do you know MySQL?

	How would you backup and restore data using `mysqldump` from the command line?
	When should you use SQL_CACHE and S_NO_CACHE on your queries?
	Question: describe five functions that disable cache on queries and describe why. **Answer: BENCHMARK(), CONNECTION_ID(), CONVERT_TZ(), CURDATE(), CURRENT_DATE(), CURRENT_TIME(), CURRENT_TIMESTAMP(), CURTIME(), DATABASE(), ENCRYPT(), with one parameter FOUND_ROWS(), GET_LOCK(), LAST_INSERT_ID(), LOAD_FILE(), MASTER_POS_WAIT(), NOW(), RAND(), RELEASE_LOCK(), SLEEP(), SYSDATE(), UNIX_TIMESTAMP(), USER(), UUID(), UUID_SHORT()**
	Have you tinkered with MySQL server optimization, and if so, what did you do to alleviate what problems?










Coding Questions:

Question: What is the value of foo?

var foo = 10 + '20';

Question: How would you make this work?

add(2, 5); // 7
add(2)(5); // 7

Question: What value is returned from the following statement?

"i'm a lasagna hog".split("").reverse().join("");

Question: What is the value of window.foo?

( window.foo || ( window.foo = "bar" ) );

Question: What is the outcome of the two alerts below?

var foo = "Hello";
(function() {
  var bar = " World";
  alert(foo + bar);
})();
alert(foo + bar);

Question: What is the value of foo.length?

var foo = [];
foo.push(1);
foo.push(2);

Question: What is the value of foo.x?

var foo = {n: 1};
var bar = foo;
foo.x = foo = {n: 2};

Question: What does the following code print?

console.log('one');
setTimeout(function() {
  console.log('two');
}, 0);
console.log('three');






MongoDb Questions

	1. What are NoSQL databases?
	2. What are the different types of NoSQL databases?
	3. What kind of NoSQL database MongoDB is?
	4. Which are the most important features of MongoDB?
	5. What is a Namespace in MongoDB?
	6. Which all languages can be used with MongoDB?
	7. Compare SQL databases and MongoDB at a high level. How is MongoDB better than other SQL databases?
	8. Compare MongoDB and CouchDB at high level. Does MongoDB support foreign key constraints?
	9. Does MongoDB support ACID transaction management and locking functionalities?
	10.  How can you achieve primary key – foreign key relationships in MongoDB?
	11. Does MongoDB need a lot of RAM?
	12. Does MongoDB pushes the writes to disk immediately or lazily?
	13. Explain the structure of ObjectID in MongoDB.
	14. MongoDB uses BSON to represent document structures. True or False?
	15. If you remove a document from database, does MongoDB remove it from disk?
	16. Mention the command to insert a document in a database called school and collection called persons.
	17. What are Indexes in MongoDB?
	18. How many indexes does MongoDB create by default for a new collection?
	19. Can you create an index on an array field in MongoDB? If yes, what happens in this case?
	20. What is a covered query in MongoDB?
	21. Why is a covered query important?
	22. Does MongoDB provide a facility to do text searches? How?
	23. What happens if an index does not fit into RAM?
	24. Mention the command to list all the indexes on a particular collection.At what interval does MongoDB write updates to the disk?
	25. How can you achieve transaction and locking in MongoDB?
	26. What is Aggregation in MongoDB?
	27. What is Sharding in MongoDB? Explain.
	28. What is Replication in MongoDB? Explain.
	29. What are Primary and Secondary Replica sets?
	30. By default, MongoDB writes and reads data from both primary and secondary replica sets. True or False.
	31. Why are MongoDB data files large in size?
	32. When should we embed one document within another in MongoDB?
	33. Why MongoDB is not preferred over a 32-bit system?
	34. What is a Storage Engine in MongoDB
	35. Which are the two storage engines used by MongoDB?
	36. What is the role of a profiler in MongoDB?
	37. Where does the writes all the data?
	38. How does Journaling work in MongoDB?
	39. Mention the command to check whether you are on the master server or not. Can you configure the cache size for MMAPv1? How?
	40. Can you configure the cache size for WiredTiger? How?
	41. How does MongoDB provide concurrency?
	42. How can you isolate your cursors from intervening with the write operations?
	43. Can one MongoDB operation lock more than one databases? If yes, how?
	44. How can concurrency affect replica sets primary?
	45. What is GridFS?
	46. Can you run multiple Javascript operations in a single mongod instance?
	47  Which command can be used to provide various information on the query plans used by a MongoDB query?



