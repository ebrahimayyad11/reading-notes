# summarizing 

## **chapter** 10 :
- what is css ? 
CSS stands for Cascading Style Sheets. CSS describes how HTML elements are to be displayed on screen, paper, or in other media. CSS saves a lot of work. It can control the layout of multiple web pages all at once. External stylesheets are stored in CSS files.

- how css works ? 
 The browser loads the HTML (e.g. receives it from the network) .
 It converts the HTML into a DOM (Document Object Model). The DOM represents the document in the computer's memory The DOM is explained in a bit more detail in the next section.
 The browser then fetches most of the resources that are linked to by the HTML document, such as embedded images  and videos ... and linked CSS! JavaScript is handled a bit later on in the process, and we won't talk about it
here to keep things simpler.
The browser parses the fetched CSS, and sorts the different rules by their selector types into different "buckets", e.g. element, class, ID, and so on. Based on the selectors it finds, it works out which rules should be applied to which nodes in the DOM, and attaches style to them as required (this intermediate step is called a render tree).
The render tree is laid out in the structure it should appear in after the rules have been applied to it.
The visual display of the page is shown on the screen (this stage is called painting) .


![circle](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_works/rendering.svg)

- css syntax and properties and values : 


this is a syntax of css . 


![syntax](https://www.w3schools.com/css/selector.gif)

- this is a properties of css : 

align-content : 	Specifies the alignment of flexible container's items within the flex container.
align-items : 	Specifies the default alignment for items within the flex container.
align-self :  	Specifies the alignment for selected items within the flex container.
animation :  	Specifies the keyframe-based animations.
animation-delay :	Specifies when the animation will start.
animation-direction :	Specifies whether the animation should play in reverse on alternate cycles or not.

- css values : 
1. integers and real numbers . 
2. lengths . 
3. units . 
4. percentage .
5. colors . 

***
### chapter 11 (color) : 

* we can specify the color of text inside an element by using color property through 3 ways in css :
1. RGB values like : rgb(102,205,170) .
2. HEX codes like : #66cdaa .
3. color names like : MediumAquaMarine .

* also we can give a text background color because css treats the html elemnts as if it apeears in box by using background-color , and also we can add the color by using the three ways that i mentioned upove this point . 

![css](https://miro.medium.com/max/1840/1*DyWnyyAO1pzdPx7a7-KEUA.png) 

* also in css we can determine the opacity of the color by using opacity property and it's value between 0.0 and 1.0 . 

### thanks for reading . 