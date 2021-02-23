# Summarizing: Dinamic pages with java script.

## Like other objects that represent real-world things, the document object has: 
1. PROPERTIES: Properties describe characteristics of the current web page (such as the title of the page). 
2. METHODS: Methods perform tasks associated with the document currently loaded in the browser (such as getting information from a specified element or adding new content). 
3. EVENTS: You can respond to events, such as a user clicking or tapping on an element. 

## HOW A BROWSER SEES A WEB PAGE?

* In order to understand how you can change the content of an HTML page using JavaScript, you need to know how a browser interprets the HTML code and applies styling to it. 

1. RECEIVE A PAGE AS HTML CODE .
2. CREATE A MODEL OF THE PAGE AND STORE IT IN MEMORY .
3. USE A RENDERING ENGINE TO SHOW THE PAGE ON SCREEN .




## Before diving into the JavaScript language, we need to know how it will fit together with the HTML and CSS in your web pages. 

### html files 
* This is where the content of the page lives. The HTML gives the page structure and adds semantics. 

### css files 
* The CSS enhances the HTML page with rules that state how the HTML content is presented (backgrounds, borders, box dimensions, colors, fonts, etc... .

### js files 
* This is where we can change how the page behaves, adding interactivity. We will aim to keep as much of our JavaScript as possible in separate files. 

### HTML ONLY 
* Starting with the HTML layer allows you to focus on the most important thing about your site: its content. 
* Being plain HTML, this layer should work on all kinds of devices, be accessible to all users, and load quite quickly on slow connections. 

### HTML+CSS 
* Adding the CSS rules in a separate file keeps rules regarding how the page looks away from the content itself. 
* You can use the same style sheet with all of your site, making your sites faster to load and easier to maintain. Or you can use different style sheets with the same content to create different views of the same data. 

### HTML+CSS+JAVASCRIPT 
* The JavaScript is added last and enhances the usability of the page or the experience of interacting with the site. 
* Keeping it separate means that the page still works if the user cannot load or run the JavaScript. You can also reuse the code on several pages (making the site faster to load and easier to maintain). 
