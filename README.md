# Todo List v1

The first thing that we need to learn is html, css and javascript. These are the building blocks of all webpages. So this time I want you to build an html page that has a textbox and a button. When you click the button the description in the text box should be shown on the page as a todo item on the same page that the button and text box are on. I am providing you with some starter files. 

index.html
index.js
index.css

1. Browse each file and look at the starter code. 
    * Everything in the .css file is called cascading style sheets or CSS. This is how you make the elements on the html page pretty.
    * Everyting in the .html file is the description of the webpage. These are basic and not pretty elements. You make them pretty with the css.
    * Everything in the .js file is javascript. This is the programming language you can use to make different things happen in the webpage.

2. Open the index.html file in your browser of choice(chrome has the best developer tools around).
3. To apply the css to the html you need to link the external css to the html page. So step 1 is google how to do this and do it. You should see the header of the page "Todo List" change a bit when this works. 
4. To attach the javascript to the html elements you need to include that script in the page. So that is step 2. Google and apply it to the page.
5. Create a Button and a text box in the page. Give them both and id property. This will help with making things happen in the javascript.
6. When you click the button I want you to get the data out of the text box and put it into the global todos variable in javascript.
7. Once you have loaded the todos variable you can list out the data in the todo-list div in the html.

# Bonus
Change the todo array in the javascript to be json object that has a completed boolean it it. List out the todos with a checkbox and when the box is checked set the completed flag to true in the json object. Also, when items are completed you no longer need to show them in todo-list in the html.

# Helpful links
* https://www.w3schools.com/html/default.asp
* https://www.w3schools.com/css/default.asp
* https://www.w3schools.com/js/default.asp
