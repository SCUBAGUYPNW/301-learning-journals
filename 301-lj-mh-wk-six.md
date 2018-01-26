Learning Journal for: Mitch Hall

This was the first week of the 301 class. There are a few differences from 201. More pair programing, and now we have additional assignments on a site called Code Wars.

Code Wars
Did three assignments on the Code Wars site.
Replace all dots
My head is at the wrong end
Abbreviate a two word name

Replace all dots was fairly straight forward, we just ran a search and replace to find all the dots in a string and replace those dots with dashes. 

My head is at the wrong end was again, some fairly straight forward code. Just a one word built in function to reverse the order of an array.

Abbreviate a two word name was a little trickier than the other two, but I was able to find working code with a little web sleuthing. Not sure exactly why one section works though. 

The code is: let firstLetters = name.split(' ').map(function (s) { return s.charAt(0); }).join('.');
That dot after join adds a dot between the two initials pulled out by the rest of this line, but I am not sure why it works to add a dot between the two letters.

References: http://guides.instructure.com/m/4210/l/141852-canvas-overview-video
http://guides.instructure.com/m/4210/c/56054
https://github.com/codefellows/code-301-prework/blob/master/README.md#code-301-pre-work-intermediate-software-development
https://www.codecademy.com/learn/jquery
http://learn.shayhowe.com/advanced-html-css/responsive-web-design/  Lesson 4 on Responsive Web Design (Essential)

https://smacss.com/ (Reference; be sure to read Ch.1-3, and then skim the rest)
http://www.anotheruiguy.com/ux-design-dev/_book/rwd/README.html to RWD (Reference)


Read
JS & jQ: pp 293-325

(Context: 293-301; Essential: 310-325, 354-358; Reference: 302-309)

Read
JS & jQ: pp 326-366

(Essential: 326-353; Context: 354-361; Reference: 362-366)


Ixius Procopios
Nov 26, 2017 Nov 26, 2017 at 8:13pm
Manage Discussion Entry
Jquery uses css selectors to grab elements from the DOM and lets you attach methods to them. JQ's library simplifies vanilla JS by having premade functions that can be called anywhere throughout the JS part of the code as long as the library is added in some way. Via downloading the library or calling a CDN. You can use it to update the Dom by adding new elements, content or attributes. Use it to change CSS rules via JS(though I wouldn't advice doing this often personally. It's easier to write the rule in the style sheet and update the selector via JQ.) And handle your events but that's later in the chapter.

 

One thing I struggled with was the difference between .html() and .text(). The main thing to remember is .html() updates the entire element and contains HTML, while .text() will only have the text.

 

No Questions.

 Reply Reply to Comment
Collapse SubdiscussionAmber Kim
Amber Kim
Nov 28, 2017 Nov 28, 2017 at 8:44pm
Manage Discussion Entry
JQuery functions can do more than one thing. They can grab information from the DOM and they can also set new information into the DOM.

What are particular instances when using JQuery is not ideal?

 Reply Reply to Comment
Collapse SubdiscussionTiger Hsu
Tiger Hsu
Nov 29, 2017 Nov 29, 2017 at 6:38pm
Manage Discussion Entry
JQuery is almost always used; I think only people that use the basic DOM are first time learners that look at this stuff.

 Reply Reply to Comment
Collapse SubdiscussionChris Lesesne
Chris Lesesne
Nov 28, 2017 Nov 28, 2017 at 10:47pm
Manage Discussion Entry
The concept of chaining in JQuery involves performing multiple methods on a selector in a particular order, all in one line of code. Using dot notation, this allows you to perform many functions with less lines of code. The only drawback is that if one method in the chain does not work, the remaining methods in the chain also will not work.

Question:

- I could use more clarification on how memory is allocated to JQuery selectors/objects and when it is most appropriate to store them in variables?

 Reply Reply to Comment
Collapse SubdiscussionArthur Allen
Arthur Allen
Nov 29, 2017 Nov 29, 2017 at 6:58am
Manage Discussion Entry
I can't wait to use these new techniques, they seem easier than the old method.  I'm guessing we'll have to use all of them at once, which will again make me feel overwhelmed.  It's all pretty dense until I get a chance to use it.  For instance, on page 322 they show how to increment a padding-left setting, though I don't yet see why that would be useful.  How would one delineate a loop for incrementing a padding-left setting?  From where to where would you set it, and why?

 Reply Reply to Comment
Collapse SubdiscussionArthur Allen
Arthur Allen
Nov 29, 2017 Nov 29, 2017 at 7:24am
Manage Discussion Entry
Yes, I know you would want to change the padding in response to changing screen sizes, but you would want that change to be instant, not delayed in a loop.

 Reply Reply to Comment
Collapse SubdiscussionArthur Allen
Arthur Allen
Nov 29, 2017 Nov 29, 2017 at 5:54pm
Manage Discussion Entry
I turned this in this morning, before I had finished reading the whole assignment.  This was in case I was late to class and couldn't turn it in before 6:30.  Of course, the question was answered on the next page, and I was at work and couldn't check the example.  Now that I can check it, I can't find the actual js code on the executable example so I can't run a console.log to see what is going on with padding-left.

 Reply Reply to Comment
Collapse SubdiscussionCody Green
Cody Green
Nov 29, 2017 Nov 29, 2017 at 12:46pm
Manage Discussion Entry
i guess one of the parts that was most clear to me was the Chaining part it just makes sense and is going to make life easy being able to define exactly what i want a thing to do in the same line of code instead of having to call back to it later to make it animate or fade in.  i dont have a real question just gonna take some reading and practice with the getters and setters really and just trying to read this again and excited to start practicing this 

 

 Reply Reply to Comment
Collapse Subdiscussiondtcomer@gmail.com
dtcomer@gmail.com
Nov 29, 2017 Nov 29, 2017 at 3:22pm
Manage Discussion Entry
The concept most clear is that jquery can be used to chain actions/methods  together. So instead of several lines of code to get an element, make it do something, another  line to make it do something else or wait for something, and yet another line of code....all manipulating the same element, one line of code can do all of it.

 

To overwhelmed for one question....don't even know where to start...asking questions

 Reply Reply to Comment
Collapse SubdiscussionTrevor Dobson
Trevor Dobson
Nov 29, 2017 Nov 29, 2017 at 3:45pm
Manage Discussion Entry
Getting and setting attribute values was the clearest concept to me.  It seemed to be pretty self explanatory.  One question this reading raised for me is how to decide when you should be using JQ.  Will it be pretty clear that you should be using JQ or is there a standard for when you should use it.

 Reply Reply to Comment
Collapse SubdiscussionBrandon Buchholz
Brandon Buchholz
Nov 29, 2017 Nov 29, 2017 at 4:41pm
Manage Discussion Entry
Explain one concept from this chapter that was most clear to you.
The concept of getting elements using simple selectors(css) an it being  much faster and requiring less code seemed really easy to understand. Also, by using jQuery and css tags the idea that you no longer have to set up loops was also easy to understand. 
Additionally, what is one question you have from the reading?
The only question I have is what are some of the common mistakes when using jQuery? 
 Reply Reply to Comment
Collapse SubdiscussionIxius Procopios
Ixius Procopios
Nov 29, 2017 Nov 29, 2017 at 6pm
Manage Discussion Entry
It's really easy to get tunnel vision with. One of my teachers use to say "It's like having a hammer that can sometimes make everything look like nails when they'er not nails." There are a bunch of methods with JQ, it makes a lot of things easier and your code cleaner.  You'll get so use to it, that you might try to solve everything with it! Even if it's not the best way to do it. ..There have been times where I made something way to complicated with JQ that could have been solved with a for loop. 

 Reply Reply to Comment
Collapse SubdiscussionAaron Bruce
Aaron Bruce
Nov 29, 2017 Nov 29, 2017 at 4:49pm
Manage Discussion Entry
JQuery allows the use of Javascript control over selecting elements, blocks, classes, etc. with minimal use of html work. This means that you will only really need to have classes and IDs labeled in your html file while being able to pull, store, assign, and reassign data to them using JQuery in the .js file. Jquery essentially cleans up a lot of unnecessary lines of code when compared to the standard Javascript code of declaring variables and adding functions for each.

 

//User Login Form .on('click')
$('.icon-button, .userLoginForm').hide();
$('.loginButton').on('click', function(event) {
     event.preventDefault();
     $('.userLoginForm, .loginButton2').fadeIn(700);
     $('.loginButton, .signUpButton').fadeOut(700);

});

This JQuery function is part of a project to use JQuery objects and functions in order to find html classes and  ~do things~ with them such as initially hiding elements with classes 'icon-button' and 'userLoginForm' and then upon clicking another element with the class of 'loginButton' will start the function to make the elements with classes 'userLoginForm' and 'loginButton2' fade into view at 700 milliseconds while fading out the elements with classes 'loginButton' and 'signUpButton' at a speed of 700 milliseconds as well.

 Reply Reply to Comment
Collapse SubdiscussionDevin Cunningham
Devin Cunningham
Nov 29, 2017 Nov 29, 2017 at 6pm
Manage Discussion Entry
One concept that really clicked for me was using the same syntax as CSS. Its smart and easier to only have to remember elements by their Class, ID, attribute, name etc just like CSS and be able to call those same names in JS.

No questions so far.

 Reply Reply to Comment
Collapse SubdiscussionRyan Johnson
Ryan Johnson
Dec 3, 2017 Dec 3, 2017 at 9:57pm
Manage Discussion Entry
I like the idea of using CSS syntax and the $ selector. Brilliant concept because it makes everything so simple and logical.

 Reply Reply to Comment
Collapse SubdiscussionEric Cobb
Eric Cobb
Nov 29, 2017 Nov 29, 2017 at 6:10pm
Manage Discussion Entry
Very interesting. Not a whole lot was very "clear" due to my struggle with js, but it is something I can refer back to.

 Reply Reply to Comment
Collapse SubdiscussionRafael Malave
Rafael Malave
Nov 29, 2017 Nov 29, 2017 at 6:21pm
Manage Discussion Entry
jQuery makes coding a lot easier by using simple selectors and common tasks take less code. With jQuery we don't need to loop through multiple elements like we do with Javascript, we can update all elements with the same method. We can also chain methods together.

 Reply Reply to Comment
Collapse SubdiscussionAriel Altaras
Ariel Altaras
Nov 29, 2017 Nov 29, 2017 at 6:24pm
Manage Discussion Entry
JQuery is a more efficient way to find, select and modify parts of the DOM. It works in all browsers as well, eliminating the need for different code to accommodate older browsers.

One question I have is what some other good uses of JQuery would be.

Edited by Ariel Altaras on Nov 29, 2017 at 6:26pm
 Reply Reply to Comment
Collapse SubdiscussionMichael Brown
Michael Brown
Nov 29, 2017 Nov 29, 2017 at 6:25pm
Manage Discussion Entry
I felt the entire reading was fairly clear and easy to understand. The part that stuck out to as being the clearest would probably be the part about chaining on multiple jQuery methods. It falls in line with keeping your code D.R.Y, keeping related information together which makes the coding process smooth and speeds things up a bit.

 Reply Reply to Comment
Collapse SubdiscussionOvi Parasca
Ovi Parasca
Nov 29, 2017 Nov 29, 2017 at 6:29pm
Manage Discussion Entry
One thing that is very clear and that i like is using the events, such as ready, load, unload, error, scroll, etc. Coming from a strong background in iOS development i rely very much on events, in iOS we have viewDidLoad, viewDidAppear, viewWillRotate, etc. Those are events to use very much to change the behavior of a page such as change the GUI (on Rotate), or load/release any data i used for setup. These are very useful and i've been waiting to learn more about these in this course.

One thing i had a question on is why is everything in JQuery in quotes? i.e.: 

'padding-left' : '+=75',
'color' : '#000';

Numbers and colors have be in quotes all the time? 

 

 Reply Reply to Comment
Collapse SubdiscussionAmber Kim
Amber Kim
Nov 29, 2017 Nov 29, 2017 at 10:49pm
Manage Discussion Entry
My guess is that they are being passed in as strings?

 Reply Reply to Comment
Collapse SubdiscussionTiger Hsu
Tiger Hsu
Nov 29, 2017 Nov 29, 2017 at 6:32pm
Manage Discussion Entry
jqury is really fancy stuff now, it allows to target using $ symbol.

Selecting the DOM element using $(document).action.

There is also a website https://jquery.com/ that I've used for

mostly for the animations.

 

Edited by Tiger Hsu on Nov 29, 2017 at 6:36pm
 Reply Reply to Comment
Collapse SubdiscussionDarcy Knore
Darcy Knore
Dec 1, 2017 Dec 1, 2017 at 4:45pm
Manage Discussion Entry
Explain one concept from this chapter that was most clear to you.
Chaining content.. pretty simple concept, but useful and efficient: "the process of placing several methods in the same selector.:

Getting and Setting content & CSS properties...  also cool as it continues to increase our ability to manipulate the webpage in different ways:  sounds like this allows us to "retrieve and update content" and "retrieve and set the values of css properties".

One question you have from the reading.
Not sure I have any questions... still trying to synthesize information and figure out practically how i would apply it in writing code.

 

 Reply Reply to Comment
Collapse SubdiscussionRyan Johnson
Ryan Johnson
Dec 3, 2017 Dec 3, 2017 at 9:54pm
Manage Discussion Entry
jQuery makes coding simpler...'write less, do more.' This concept stands out above all others in this chapter to me in that you use less code to affect the same result as you would using java script, but that being said I have been getting lost in this chapter with all of the things you need to know and little but very important details when it comes to using jQuery effectively. 

Is jQuery more affective than js react and other languages like it or just the predecessor to bigger and better things?

 Reply Reply to Comment
Collapse SubdiscussionAlicia Lycan
Alicia Lycan
Dec 4, 2017 Dec 4, 2017 at 6:06pm
Manage Discussion Entry
I understand the concept of jquery methods can retrieve information and update the contents of elements. A selector can return one or more elements, the jquery object contains a references to each element. 

Is jquery as affective as other languages? Or is it simply the next building block above javascript? 

Edited by Alicia Lycan on Dec 4, 2017 at 6:11pm
 Reply Reply to Comment
Collapse SubdiscussionDambergN
DambergN
Dec 4, 2017 Dec 4, 2017 at 6:28pm
Manage Discussion Entry
one that was pretty clear to me is the event listener, I have used that in the past for clicks, detecting certain button presses or for the change of a mouses X, Y coordinates for our 201 project.  Understanding a concept is one thing, but implementing it and making it work is usually where the questions come from.

 Reply Reply to Comment
Collapse SubdiscussionAyanle (ah-yan-leh)
Ayanle (ah-yan-leh)
Dec 9, 2017 Dec 9, 2017 at 10:44am
Manage Discussion Entry
I never really understood how the .each() method worked. Reading the book was not as insightful as I'd hoped. JB's lecture on that topic had really explained the concept better. I don't have much of any question from the reading but I need to tinker with the sample code it has to gain better understanding. That way, I don't have to wait until class time to get better understanding.

 Reply Reply to Comment
Collapse SubdiscussionRonnie Lewis
Ronnie Lewis
Dec 31, 2017 Dec 31, 2017 at 1am
Manage Discussion Entry
jQuery makes the most sense to me in it's most basic form, select something, and give it an action. Keeping that in mind has made things more clear to me.

Moving forward, I think one of the hardest parts will be trying to remember it's more complex uses that really simply things. Are there any indicators when approaching a task that will help with this?

 

 Reply Reply to Comment
Collapse SubdiscussionMitchel Hall
Mitchel Hall
Yesterday Jan 25 at 9:33pm
Manage Discussion Entry
It's clear to me that JQuery is very helpful if you can remember or have a quick reference to know what is possible with JQuery. Then once you know what is possible, you then have to figure out how to actually do it. 


Read
http://tutorialzine.com/2015/01/learn-handlebars-in-10-minutes/ (Essential)
http://handlebarsjs.com/ (Reference)


Discussion:

Handel bars is great for templating and lets you keep your HTML and content, which lets it change and update easily.

It's what's known as declarative. Meaning, your view will be a specific way given a specific case. It lets you define the relationship with the View and whatever's effecting it.

 

Q: To my understanding React yields an equivalent result. Whats the cost/benefit of using Handelbars over React?

 Reply Reply to Comment
Collapse SubdiscussionAmber Kim
Amber Kim
Dec 4, 2017 Dec 4, 2017 at 7:12pm
Manage Discussion Entry
I haven't read it yet so I don't know if it's any good, but I found this after a quick google: https://www.slant.co/versus/181/10513/~handlebars-js_vs_react

 Reply Reply to Comment
Collapse SubdiscussionAmber Kim
Amber Kim
Dec 4, 2017 Dec 4, 2017 at 7:10pm
Manage Discussion Entry
Handlebar.js reminds me of text editors in email newsletter apps like mailchimp where you can create email templates, put placeholder items like you do with curly braces in handlebars.js for certain information like people's names. I wonder if any of them actually do use handlebars.js?

When you have the email template and set 'shortcodes', it makes it easy for people who don't code to tell the app where to put certain data automatically.

 Reply Reply to Comment
Collapse SubdiscussionChris Lesesne
Chris Lesesne
Dec 5, 2017 Dec 5, 2017 at 5:53pm
Manage Discussion Entry
Using 'handlebars.js' allows you to generate HTML in a separate section from your JavaScript in your script file to write cleaner code. It allows you to write different templates to your page with simple syntax depending upon the goals of the application you are creating.

Questions: 

- In which types of applications/projects is using handlebars.js most useful or preferred?

 Reply Reply to Comment
Collapse SubdiscussionArthur Allen
Arthur Allen
Dec 5, 2017 Dec 5, 2017 at 8:17pm
Manage Discussion Entry
One benefit of Handlebars is that it separates the generation of HTML from the rest of your JavaScript so you can write cleaner code.  I'm still not sure how it works until I see it in action.

 Reply Reply to Comment
Collapse SubdiscussionTrevor Dobson
Trevor Dobson
Dec 6, 2017 Dec 6, 2017 at 11:04am
Manage Discussion Entry
A benefit of using handlebars is cleaner code.  This is such a new concept to me I don't even know where to begin with questions.  Like everything else in coding it is something I will just have to start using before I know what questions to ask.

 Reply Reply to Comment
Collapse Subdiscussiondtcomer@gmail.com
dtcomer@gmail.com
Dec 6, 2017 Dec 6, 2017 at 12:48pm
Manage Discussion Entry
It appears that by using handlebars.js, it allows you to not have to manipulate the DOM by using at least 2 lines of code. 
The way we do it now we have to use or create a template, then we have to figure out how to update or create items using the template.

It looks like handlebars.js allows both things to happen with one line of code.

 

 

 Reply Reply to Comment
Collapse SubdiscussionTiger Hsu
Tiger Hsu
Dec 6, 2017 Dec 6, 2017 at 5:04pm
Manage Discussion Entry
Better lines of code with least DOM event listeners in place. This is a better way to orgainze and make the templates run better and the scripts better.

 

 Reply Reply to Comment
Collapse SubdiscussionEric Cobb
Eric Cobb
Dec 6, 2017 Dec 6, 2017 at 2:21pm
Manage Discussion Entry
If understanding it correctly, it appears to assist the user in writing cleaner code and provides helpers with the js. 

 Reply Reply to Comment
Collapse SubdiscussionBrandon Buchholz
Brandon Buchholz
Dec 6, 2017 Dec 6, 2017 at 3:12pm
Manage Discussion Entry
What is one benefit to using handlebars.js?
One benefit of using handlebars.js is that your HTML code is cleaner and easier to read.
Any questions you have after the reading?
No questions just need to start using it so it sinks in better.
 Reply Reply to Comment
Collapse SubdiscussionAlicia Lycan
Alicia Lycan
Dec 6, 2017 Dec 6, 2017 at 3:47pm
Manage Discussion Entry
One benefit to using handlebars.js is the handlebars expressions support nested values which allows us to easily access any data from a JavaScript object. 

Question: Is there a built in way to loop through the properties of an object? 

 Reply Reply to Comment
Collapse SubdiscussionAriel Altaras
Ariel Altaras
Dec 6, 2017 Dec 6, 2017 at 4:24pm
Manage Discussion Entry
I'm not sure exactly what you're looking to loop through, but it looks like maybe #each would do this.

 Reply Reply to Comment
Collapse SubdiscussionJames
James
Dec 8, 2017 Dec 8, 2017 at 11:48pm
Manage Discussion Entry
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for...in

 

 Reply Reply to Comment
Collapse SubdiscussionAriel Altaras
Ariel Altaras
Dec 6, 2017 Dec 6, 2017 at 4:20pm
Manage Discussion Entry
One benefit of using handlebars.js is that it automatically escapes data put into an expression, so it can be good for displaying user input more securely. (But there's an option to put in HTML if you want to.)

I can't think of any questions at the moment.

 

 Reply Reply to Comment
Collapse SubdiscussionDarcy Knore
Darcy Knore
Dec 6, 2017 Dec 6, 2017 at 4:50pm
Manage Discussion Entry
WOW.. this is great!  

One benefit of using handlebars.js:  easily looping through arrays.. also, easily reuse HTML content or functionality.

No questions per se... anxious to give it a try!

 Reply Reply to Comment
Collapse SubdiscussionTiger Hsu
Tiger Hsu
Dec 6, 2017 Dec 6, 2017 at 5:03pm
Manage Discussion Entry
I am not sure what exactly is handlebars.js I have never used it before. It seems to me that handlebars.js helps build templates by using a {{}} inside text context.

 

I believe that the handlebar, will help us insert various arrays into a sting. For instance.

Hello {{name}}
You have just won {{value}} dollars!
{{#in_ca}}
Well, {{taxed_value}} dollars, after taxes.
{{/in_ca}}

{
  "name": "Chris",
  "value": 10000,
  "taxed_value": 10000 - (10000 * 0.4),
  "in_ca": true
}


This would allow us to pull from any array with this.name object literals.

 Reply Reply to Comment
Collapse SubdiscussionDevin Cunningham
Devin Cunningham
Dec 6, 2017 Dec 6, 2017 at 6:17pm
Manage Discussion Entry
It helps you created cleaner code by allowing you to write your HTML code written by js separately from the rest of your js. It's going to make HTML easier to write when you have elements that need to be changed per user.

 Reply Reply to Comment
Collapse SubdiscussionRafael Malave
Rafael Malave
Dec 6, 2017 Dec 6, 2017 at 6:19pm
Manage Discussion Entry
One benefit to using handlebars is reusable templates for larger projects. One other benefit is the ability to create block helpers with handlebars.

 Reply Reply to Comment
Collapse SubdiscussionOvi Parasca
Ovi Parasca
Dec 6, 2017 Dec 6, 2017 at 6:29pm
Manage Discussion Entry
The main i got out of the readings is that Handlebars makes writing up a page easier and cleaner to read.

I'd like to do a hands-on example with Handlebars to fully grasp what it can do so i can have more questions.

 Reply Reply to Comment
Collapse SubdiscussionAaron Bruce
Aaron Bruce
Dec 9, 2017 Dec 9, 2017 at 8:09am
Manage Discussion Entry
Handlebars are a nice way to reduce the amount of code needed in your html as well as in your javascript file(s). It's a way to show data from objects with properties without the need for extended regular function expressions. Just make sure to include the script tag for handlebars CDN 

<script src="https://cdnjs.cloudflare.com/ajax/libs/handlebars.js/2.0.0/handlebars.js"></script> 

with the most updated version of course.

IN HTML
<h1>{{Property Name 1}}</h1>

<div>{{{Property Name 2}}}</div>


IN JAVASCRIPT OBJECT DATA FILE         Simply shows that if there is a <p> tag or some kind of other html tag that you want to show, then the corresponding
                                       handlebars placeholder must be within 3 pairs of curly braces instead of the standard 2 pairs.
let object = {

Property Name 1 = 'Hello',
Property Name 2 = '<p>World</p>'
}

 Reply Reply to Comment
Collapse SubdiscussionRyan Johnson
Ryan Johnson
Dec 12, 2017 Dec 12, 2017 at 8:36pm
Manage Discussion Entry
Great reminder and thanks for sharing the code snippet. 

 Reply Reply to Comment
Collapse SubdiscussionCody Green
Cody Green
Dec 9, 2017 Dec 9, 2017 at 9:22am
Manage Discussion Entry
im excited to work with handlebars it seems like it is just going to make sense and make templating a breeze for building out the html for our pages

 Reply Reply to Comment
Collapse SubdiscussionRyan Johnson
Ryan Johnson
Dec 12, 2017 Dec 12, 2017 at 8:35pm
Manage Discussion Entry
yeah templates! At lease adding a mustache makes building templates more exciting. : )

 Reply Reply to Comment
Collapse SubdiscussionAyanle (ah-yan-leh)
Ayanle (ah-yan-leh)
Dec 9, 2017 Dec 9, 2017 at 9:54am
Manage Discussion Entry
It will allow you to create templates/views for the different situations. Makes building single page solutions so much easier.

 Reply Reply to Comment
Collapse SubdiscussionMichael Brown
Michael Brown
Dec 11, 2017 Dec 11, 2017 at 4:30pm
Manage Discussion Entry
Handlebars seems to be an quicker way to get data elements connected to you html and displayed in the DOM.

 Reply Reply to Comment
Collapse SubdiscussionRyan Johnson
Ryan Johnson
Dec 12, 2017 Dec 12, 2017 at 8:33pm
Manage Discussion Entry
The main benefit of using handlebars in java script that I can see is that it makes a basic html page dynamic in a quick and simple approach to using language tools which are already well known.

What main stream websites use handlebars? Now I want to search through source code to find examples as this is used in the field.

 Reply Reply to Comment
Collapse SubdiscussionRonnie Lewis
Ronnie Lewis
Dec 31, 2017 Dec 31, 2017 at 4:22am
Manage Discussion Entry
Using Handlebars keeps your HTML page clean and it's usage is pretty straight forward.

 Reply Reply to Comment
Collapse SubdiscussionMitchel Hall
Mitchel Hall
Jan 16, 2018 Jan 16 at 4:16pm
Manage Discussion Entry
Looking forward to using this a few more times to really get a handle on it. No pun intended.  


Read
JS & jQ, Ch 8: pp 367-408

Context: 367-371, 384-387; Essential: 372-383, 388-399; Reference: 400-408
Note: You can totally skip over any parts about XML and JSONP

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/let (just take a look, no need to read closely or memorize)
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/const (just take a look, no need to read closely or memorize)

Chris Lesesne
Dec 10, 2017 Dec 10, 2017 at 12:25pm
Manage Discussion Entry
AJAX (Asynchronous JavaScript and XML) is a process for requesting data from a server that can be used to update a page (or portion of a page) with new content, without having to refresh the entire page each time. The data requested can be provided in JSON (JavaScript Object Notation), which is in text format, not object literal notation, and must be converted (parsed) into JavaScript so that it can be properly rendered to the page. Data, such as information completed in a form, can also be sent to a server using AJAX.

Question(s):

- What are some of the other benefits (besides more detailed control) to using the $.ajax() method instead of the other jQuery shorthand request methods?

 Reply Reply to Comment
Collapse SubdiscussionAmber Kim
Amber Kim
Dec 10, 2017 Dec 10, 2017 at 3:11pm
Manage Discussion Entry
The other, shorthand request methods are written on top of the ajax() method so that they use the ajax() method to function so maybe a benefit would be less layers - although I don't think it really matters and the way the shortcuts simplify understanding and readability is a huge plus to me.

 Reply Reply to Comment
Collapse SubdiscussionAmber Kim
Amber Kim
Dec 10, 2017 Dec 10, 2017 at 3:01pm
Manage Discussion Entry
You can use AJAX to send or receive information formatted as JSON. How often would we have to use the alternatives, XML or Html, compared to JSON?

 Reply Reply to Comment
Collapse Subdiscussiondtcomer@gmail.com
dtcomer@gmail.com
Dec 10, 2017 Dec 10, 2017 at 3:10pm
Manage Discussion Entry
AJAX and JSON relate to each other in that AJAX is a information gathering (pushing or receiving) function that lets you do those tasks, while, the page(s) load, using JSON.

Basically you use JSON code with AJAX requests to go get and/or present data retrieved from a server.

The concept now explains how a lot of the financial websites can provide you with the latest stock prices. I'm assuming there is a JSON call for information and AJAX is allowing it to update without refreshing the page.

 

My question would be....what/how do you set the time (refresh) of how often the updates occur? Is that controlled on the JS side or the AJAX side of things?

 Reply Reply to Comment
Collapse SubdiscussionArthur Allen
Arthur Allen
Dec 11, 2017 Dec 11, 2017 at 6:03pm
Manage Discussion Entry
AJAX allows you to add data to a browsing experience without loading the whole screen.  JSON is a data type used by AJAX.  There's a website I use for reading newspaper comics, but when you read the comments you have to click on each main comment to read their replies.  I'm hoping to find a way to bypass this by using techniques learned in this class.

 Reply Reply to Comment
Collapse SubdiscussionTiger Hsu
Tiger Hsu
Dec 13, 2017 Dec 13, 2017 at 12:32pm
Manage Discussion Entry
AJAX and JSON are related to each similar to that of warehouse; Packer and delivery driver.

In order to get the data products you need JSON is the warehouse packer that allows hold the data; and AJAX has sytax that allows GET.() & .POST() information to be viewed.

 Reply Reply to Comment
Collapse SubdiscussionTrevor Dobson
Trevor Dobson
Dec 13, 2017 Dec 13, 2017 at 12:54pm
Manage Discussion Entry
AJAX and JSON are related because JSON is one of the languages used in AJAX to load the information to the page.  AJAX makes it possible to load new information to a page without reloading the entire page and JSON is one of the languages used.  Is JSON the preferred language or is there a standard for when to use it?

 Reply Reply to Comment
Collapse SubdiscussionRyan Johnson
Ryan Johnson
Dec 17, 2017 Dec 17, 2017 at 10:47pm
Manage Discussion Entry
I was also wondering if using JSON with AJAX is personal preference over other libraries or if it is considered best practice?

 Reply Reply to Comment
Collapse SubdiscussionBrandon Buchholz
Brandon Buchholz
Dec 13, 2017 Dec 13, 2017 at 4:19pm
Manage Discussion Entry
In your own words, how do AJAX and JSON relate to each other?
JSON is a way of storing elements into an easier to read and retrieve format, and AJAX is a way of retrieving data without having to reload everything that is rendered on a page. To me it seems like a quicker way to bring in new elements that are dynamic without having to reload everything, which would take up more time.
What is one question you have from the reading?
No questions as of now.
 Reply Reply to Comment
Collapse SubdiscussionAriel Altaras
Ariel Altaras
Dec 13, 2017 Dec 13, 2017 at 4:49pm
Manage Discussion Entry
Ajax allows one part of a web page to be updated while the rest of the page doesn't have to reload. JSON is one of the types of information that can be sent to Ajax to communicate the new data to load.

One question I have is that the book implies that JSON only works with local sources, and talks about JSONP. Is this different now?

 Reply Reply to Comment
Collapse SubdiscussionAyanle (ah-yan-leh)
Ayanle (ah-yan-leh)
Dec 13, 2017 Dec 13, 2017 at 6:23pm
Manage Discussion Entry
AJAX is the procedure to communicate with server and the information that is sent to or from server can be JSON data. This type of data (JSON) allows different servers to efficiently communicate with JavaScript/HTML page the user is interacting with.

Edited by Ayanle (ah-yan-leh) on Dec 13, 2017 at 6:24pm
 Reply Reply to Comment
Collapse SubdiscussionOvi Parasca
Ovi Parasca
Dec 13, 2017 Dec 13, 2017 at 6:24pm
Manage Discussion Entry
AJAX can send/receive data over the web, it can read/write JSON data. Think of JSON as the cargo and AJAX as the vehicle transporting that data. In iOS i use AlamoFire (Swift) to do all my network calls, it's an open-source 3rd party framework that makes network request easy to create and makes my dev life so much easier. I almost always work with JSON and super very rarely with XML data. 

 Reply Reply to Comment
Collapse SubdiscussionIxius Procopios
Ixius Procopios
Dec 13, 2017 Dec 13, 2017 at 6:28pm
Manage Discussion Entry
Ajax is a method used to make a request to a server for data, you can't transfer objects over a network so JSON is a data type that can take objects that have been made into strings and move them across the network . No questions. 

 

 Reply Reply to Comment
Collapse SubdiscussionAlicia Lycan
Alicia Lycan
Dec 13, 2017 Dec 13, 2017 at 6:30pm
Manage Discussion Entry
AJAX is a mechanism used to launch HTTP requests to a server using JavaScript; there's no restriction on you only retrieving JavaScript or XML from this technique. You can quite happily return other data formats as well (HTML, plain text and JSON, etc.).

JSON is one of these formats. Specifically, a data interchange format, in contrast AJAX is a technique to communicate with a server after the initate page load has completed.

What is the significance of each technique in application?

 Reply Reply to Comment
Collapse SubdiscussionRafael Malave
Rafael Malave
Dec 13, 2017 Dec 13, 2017 at 7:31pm
Manage Discussion Entry
JSON is one of the data formats that can be returned from the server from an AJAX request. We can then use the data to render/update content dynamically on the page without refreshing the whole page.

 Reply Reply to Comment
Collapse SubdiscussionDarcy Knore
Darcy Knore
Dec 15, 2017 Dec 15, 2017 at 10:58pm
Manage Discussion Entry
How do AJAX and JSON relate to each other?

Ajax is a technique for loading data into part of a page without having to refresh the entire page. The data is often sent in a JSON format (JavaScript Object Notation).

Not any questions about the concept... mainly in the syntax and how to incorporate it into JS file.

 Reply Reply to Comment
Collapse SubdiscussionMichael Brown
Michael Brown
Dec 17, 2017 Dec 17, 2017 at 5:34pm
Manage Discussion Entry
Ajax and JSON work as partners in retrieving information from a server (or data file) and displaying it to the page without the need to refresh the page. It has methods that can be used to retrieve from and send information to the server.

 Reply Reply to Comment
Collapse SubdiscussionRyan Johnson
Ryan Johnson
Dec 17, 2017 Dec 17, 2017 at 10:44pm
Manage Discussion Entry
How do AJAX and JSON relate to each other?

The very first page of this chapter (pg.368) answers this question well. AJAX (Asynchronous JavaScript and XML) allows content to be loaded to a page asynchronously without refreshing the entire page. AJAX and JSON (JavaScript Object Notation) often work together because JSON is commonly used to store data on servers and AJAX loads this data in a quickly and seamlessly for a better user experience.

What is one question you have from the reading?

I don't feel like I quite understand what AJAX looks like to be able to identify it on a line of code in comparison to JSON and other libraries we are working with right now. What additional resources would you recommend to better grasp the syntax and use of AJAX beyond re-re-reading this chapter?

 Reply Reply to Comment
Collapse SubdiscussionDevin Cunningham
Devin Cunningham
Dec 18, 2017 Dec 18, 2017 at 9:30am
Manage Discussion Entry
I am with you on this one Ryan. I feel like a code demo or other resources would be beneficial.

 Reply Reply to Comment
Collapse SubdiscussionDevin Cunningham
Devin Cunningham
Dec 18, 2017 Dec 18, 2017 at 9:30am
Manage Discussion Entry
AJAX and JSON work together to update and store information. AJAX can make a call to JSON to get information and when it is making that call, it allows other code to run (asynchronous).

 Reply Reply to Comment
Collapse SubdiscussionCody Green
Cody Green
Dec 18, 2017 Dec 18, 2017 at 12:05pm
Manage Discussion Entry
when i read this the first time my eyes kind of glossed over but after a second reading and some practical application i understand it a little better

 Reply Reply to Comment
Collapse SubdiscussionAaron Bruce
Aaron Bruce
Dec 18, 2017 Dec 18, 2017 at 5:49pm
Manage Discussion Entry
AJAX (Asynchronous Javascript And XML) is used to make requests to pull data that is stored in JSON files. JSON (Javascript Object Notation) files are created so that information does not need to be stored on every local machine of users who want to access to updatin/adding new data like changing articles.

AJAX uses an asynchronous processing model so it will not conflict with a webpage's other processes or refresh the entire page again.

 Reply Reply to Comment
Collapse SubdiscussionEric Cobb
Eric Cobb
Dec 27, 2017 Dec 27, 2017 at 4:01pm
Manage Discussion Entry
AJAX allows you to request data from a server without having to refresh the page. JSON  is more text based and it is a way to store information in an organized and easier to read. I have several questions that will require more research from the reading. 

 Reply Reply to Comment
Collapse SubdiscussionRonnie Lewis
Ronnie Lewis
Jan 2, 2018 Jan 2 at 12:55am
Manage Discussion Entry
After reading and searching the web to best answer this question, I've learned that the two are not comparable, but relatable. AJAX is a technique for loading data into part of a page without having to refresh the entire page. The format of the data sent is JSON.

 Reply Reply to Comment
Collapse SubdiscussionDambergN
DambergN
Jan 11, 2018 Jan 11 at 12:01pm
Manage Discussion Entry
While var is a more general purpose data storage container, let and const are more specific to certain uses.  let can be used for more than just data storage but also store a function or set of functions.  You can do this with var as well but I think the standard is to use let for this case.  And const as it implies is a constant data container, a set of information that does not change, at least not often.

 Reply Reply to Comment
Collapse SubdiscussionMitchel Hall
Mitchel Hall
Jan 16, 2018 Jan 16 at 4:22pm
Manage Discussion Entry
Another section of knowledge that will take a while to fully sink in, but I certainly like what it helps us do with code. 

Read
https://gist.github.com/brookr/5977550  “How I Explained REST to My Brother" 

https://en.wikipedia.org/wiki/Representational_state_transfer "Representational State Transfer" (Wikipedia; just skim through this)

http://www.drdobbs.com/web-development/restful-web-services-a-tutorial/240169069 RESTful Web Services: A Tutorial (Dr. Dobbs; just skim through this) 

dtcomer@gmail.com
Dec 10, 2017

The concept of polymorphism relates to REST verbs like GET, PUT, and DELETE in explaining that these verbs can be used with universal meaning across a variety of objects. No matter the object (code, webpage, data type) GET verb will do the same function to any objects, same with PUT and DELETE.

 

I did not grasp the concept of why we were reading the REST concept. What is it that we are trying to learn with this?

 Reply Reply to Comment
Collapse SubdiscussionRyan Johnson
Ryan Johnson
Dec 13, 2017 Dec 13, 2017 at 5:40pm
Manage Discussion Entry
I second your question Denis.

 Reply Reply to Comment
Collapse SubdiscussionAmber Kim
Amber Kim
Dec 13, 2017 Dec 13, 2017 at 8:42pm
Manage Discussion Entry
My understanding is just how these verbs can be applicable to what we do with the data or objects we deal with. Getting the data, putting the data somewhere and deleting the data.

 Reply Reply to Comment
Collapse SubdiscussionArthur Allen
Arthur Allen
Dec 10, 2017 Dec 10, 2017 at 4:51pm
Manage Discussion Entry
Polymorphism allows for the flexible use of different types, and REST verbs allow for flexible access of the internet.  I still don't understand how this works.

 Reply Reply to Comment
Collapse SubdiscussionChris Lesesne
Chris Lesesne
Dec 10, 2017 Dec 10, 2017 at 11:41pm
Manage Discussion Entry
Polymorphism describes how a verb (or action) van be applied to multiple nouns (or resources). GET, PUT, and DELETE are all verbs that can be applied to web resources that are used by users and machines.

Question:

- How will AI and machine-learning impact or improve our use of RESTful Web services and how we approach software development in the future?

 Reply Reply to Comment
Collapse SubdiscussionTiger Hsu
Tiger Hsu
Dec 12, 2017 Dec 12, 2017 at 6:44pm
Manage Discussion Entry
I think machine-learning uses algorithms which are steps that involve if instance A happens then GET instance A; if instance B happens then GET instance B; so on thus forth. Algorithms are directions at which the computer performs something in order to solve a certain item.

 Reply Reply to Comment
Collapse SubdiscussionTiger Hsu
Tiger Hsu
Dec 12, 2017 Dec 12, 2017 at 6:39pm
Manage Discussion Entry
REST stands for the Representational State Transfer which is the backbone way which I think machines talk to

each other. GET retrieves data or reads a resource, PUT inserts a resource, POST updates the resource, and DELETE obviously clears the data.  As  remember it IP address can be used to GET,PUT and DELETE items.

126.12.3232 is like an address of where to deliver and find the certain mailing data.

 Reply Reply to Comment
Collapse SubdiscussionTrevor Dobson
Trevor Dobson
Dec 13, 2017 Dec 13, 2017 at 12:48pm
Manage Discussion Entry
Polymorphism relates to REST in the fact that REST uses a single standard to access requests of different types.  So GET, PUT, and DELETE can be used across the board.  How will we begin to apply the REST concept?

 Reply Reply to Comment
Collapse SubdiscussionEric Cobb
Eric Cobb
Dec 13, 2017 Dec 13, 2017 at 3:07pm
Manage Discussion Entry
Polymorphism is a way that says different nouns can have the same verb apply to them. You can "get" items (example used was laptop, books on a coffee table). 

"Get" "put" and "delete" are almost always universal verbs. 

 Reply Reply to Comment
Collapse SubdiscussionBrandon Buchholz
Brandon Buchholz
Dec 13, 2017 Dec 13, 2017 at 3:16pm
Manage Discussion Entry
How does the concept of polymorphism relate to REST verbs like GET, PUT, and DELETE? 

Polymorphism when it comes to REST verbs is helpful in that all systems know what is being asked regardless of the language, computer, etc. Being able to have the same understanding seems highly beneficial.
 Reply Reply to Comment
Collapse SubdiscussionAriel Altaras
Ariel Altaras
Dec 13, 2017 Dec 13, 2017 at 4:26pm
Manage Discussion Entry
The concept of polymorphism says that REST verbs should be applicable to all objects. We can GET, PUT, or DELETE anything, regardless of what it is.

No questions, but I feel like I have a much better understanding of caching!

 Reply Reply to Comment
Collapse SubdiscussionRyan Johnson
Ryan Johnson
Dec 13, 2017 Dec 13, 2017 at 5:35pm
Manage Discussion Entry
According to my define 'polymorphism' google search, polymorphism is defined as "the condition of occurring in several different forms." REST is similar in concept in that it exists in a state to be used in different ways for different applications, which change the state of REST for that specific use.

I was hoping to make my response less abstract. : )

 Reply Reply to Comment
Collapse SubdiscussionAyanle (ah-yan-leh)
Ayanle (ah-yan-leh)
Dec 13, 2017 Dec 13, 2017 at 6:16pm
Manage Discussion Entry
How does the concept of polymorphism relate to REST verbs like GET, PUT, and DELETE? 

REST allows us to use just one standardized process to perform different operations with data transfers. 

What is one question you have from the reading? 

The examples seem to be web/url related scenarios on REST concept. Are there other types not url related?

 Reply Reply to Comment
Collapse SubdiscussionOvi Parasca
Ovi Parasca
Dec 13, 2017 Dec 13, 2017 at 6:18pm
Manage Discussion Entry
RESTful calls change the objects in which they call, by modifying the object using GET/POST/PUT/PATCH/DELETE. The servers have the basic foundation of the data objects, the applications ingest the data, manipulate it and send it back.

I use REST calls almost on a daily basis and these get asked in Interviews all the time, so i'd recommend for anyone to become very familiar with these. We use REST calls for that requires the application to talk to anything using the web.

 Reply Reply to Comment
Collapse SubdiscussionAlicia Lycan
Alicia Lycan
Dec 13, 2017 Dec 13, 2017 at 6:27pm
Manage Discussion Entry
The concept of polymorphism is a way of saying that different nouns can have the same verb applied to them. Verbs like GET can be applied to many different nouns; GET, PUT, and DELETE are universal verbs. How does this concept refer to SQL?

 Reply Reply to Comment
Collapse SubdiscussionAmber Kim
Amber Kim
Dec 13, 2017 Dec 13, 2017 at 8:40pm
Manage Discussion Entry
It's good to be able to use the same verbs that apply for different objects. I don't have any questions at this time.

 Reply Reply to Comment
Collapse SubdiscussionDarcy Knore
Darcy Knore
Dec 15, 2017 Dec 15, 2017 at 10:01pm
Manage Discussion Entry
Polymorphism relates to REST verbs (such as GET, PUT, and DELETE) in that a single "verb" (ie. GET) can be applied to many different nouns.  

It's crazy to think about all that has happened in the past 17-20 years.. and, yet, some of the basic principles (such as RESTful web services, and http methods) are still being used.  Everything that happens on the "other side of screen" or the backend has always been a bit mysterious to me (or even what some of the acronyms stand for!)... it feels like some of these basic concepts are one step in the direction of starting to demystify things, though

 Reply Reply to Comment
Collapse SubdiscussionIxius Procopios
Ixius Procopios
Dec 16, 2017 Dec 16, 2017 at 4:40pm
Manage Discussion Entry
In regards to polymorphism, REST, GET, PUT, DELETE are actions taken on data. 

No questions. 

 Reply Reply to Comment
Collapse SubdiscussionRafael Malave
Rafael Malave
Dec 17, 2017 Dec 17, 2017 at 1:05pm
Manage Discussion Entry
As I understand it from the reading, polymorphism as it relates to REST, is when verbs like GET, can be applied to many different nouns.

 Reply Reply to Comment
Collapse SubdiscussionMichael Brown
Michael Brown
Dec 17, 2017 Dec 17, 2017 at 6:21pm
Manage Discussion Entry
Polymorphism relates to REST verbs in that these verbs are able to process different objects differently without the need to use a different words.

 Reply Reply to Comment
Collapse SubdiscussionDevin Cunningham
Devin Cunningham
Dec 18, 2017 Dec 18, 2017 at 9:35am
Manage Discussion Entry
For get, put, and delete, we can use them to relate to different nouns.

Edited by Devin Cunningham on Dec 18, 2017 at 9:37am
 Reply Reply to Comment
Collapse SubdiscussionCody Green
Cody Green
Dec 18, 2017 Dec 18, 2017 at 12:13pm
Manage Discussion Entry
the document how i explained REST to my brother was a nice change of pace compared to some of the other readings with the whole explaining it like im 5 kinda feel to it. 

 

it relates to those in the sense that they are universal and can be used in many ways .

no question yet.

 Reply Reply to Comment
Collapse SubdiscussionRonnie Lewis
Ronnie Lewis
Jan 2, 2018 Jan 2 at 2:23am
Manage Discussion Entry
How does the concept of polymorphism relate to REST verbs like GET, PUT, and DELETE?

polymorphic type is one whose operations can also be applied to values of some other type, or types.

The way I understand it is that something is polymorphic is one whose operations can also be applied to values of some other type, or types. Verbs like, GET, PUT, and DELETE are interchangeable between different nouns. You can GET, PUT, and DELETE all kinds of nouns.

The reading mentioned being able to access data in a different way, what are some of those other ways, and why are they not as good?

 

 

 

 

 Reply Reply to Comment
Collapse SubdiscussionDambergN
DambergN
Jan 11, 2018 Jan 11 at 11:46am
Manage Discussion Entry
An interesting read, basically its all about cross platform communication.  A universal language/protocol that can be used to have different applications and environments talk to each other.  It had always bugged me years ago how nothing could ever talk to each other, we have come a long way in the past few years.

 Reply Reply to Comment
Collapse SubdiscussionMitchel Hall
Mitchel Hall
Jan 12, 2018 Jan 12 at 2:12pm
Manage Discussion Entry
Still letting it percolate but I think the first link "How I explained REST to my Brother" probably helped the most.  From what I get out of it this you can have a device, lets say a Kindle Fire TV box that needs to open the Netflix app and then GET all the current movies and TV shows that Netflix offers. The Fire TV does not care where the information comes from or how it is retrieved, it just wants to make the request and get something back. So code can be written that says "When request is made do this specifically" or a general request can be sent out and computer A receives the request, does not have the information requested but knows that computer D does have the information and completes the link. At the same time the request is received by a bunch of other computers that do not know how to find the information requested so they simply ignore the request, or maybe there could be some functionality that allows them to listen in on the answer so in the future they know how to answer the request. After I think about it some more I could probably come up with an even better answer. 

 

Maybe another one would be...  I am interested in a certain show but I want to know other peoples opinions so I make the request for reviews of this show. So the reviews could be lots of different places but if they are categorized in a consistent way we could send out the general GET request and computer A goes, "Here is my review, oh, and I know computer G and K have their own reviews" and so on.  Maybe?

 Reply Reply to Comment
Collapse SubdiscussionAaron Bruce
Aaron Bruce
Jan 13, 2018 Jan 13 at 7:58pm
Manage Discussion Entry
REST stands for REpresentation State Transfer usually defined by the URL prefix (HTTP/HTTPS), using stateless protocol and standard operation in order to execute faster connections (GET, POST, PUT, DELETE) CRUD methods in code between websites.

 Read
Take a quick skim through the beginning sections of these pages:

Node.js introduction on tutorialspoint.com .
"An Introduction to Node.js" on sitepoint.com .
The Node Beginner Book
We'll be using Node.js as a tool going forward (it lets us run JS outside of the browser!), but for our purposes, you don't actually need to understand much of what Node is actually doing. You just need to know how to use it the way we are going to be using it in class and labs (to replace "live-server" and give us a local environment to work in that will be like the one we'll use for deployments starting in Week 3).

In fact, trying to dive into too many details of Node would be a distraction from the content we're actually intending to study, so resist the temptation for now. If Node is something you develop an interest in, well, that's what the JavaScript 401 is for! Or check out one of the Seattle Node.js meetups if they start having them again!

Here's a link to the Node.js docs. You don't need to read through anything here, but if you'd like to look around, go ahead. Node is a huge universe with lots of potential and opportunity.

https://canvas.instructure.com/courses/1245195/discussion_topics/6106548?module_item_id=15127261

Collapse SubdiscussionArthur Allen
Arthur Allen
Dec 12, 2017 Dec 12, 2017 at 9:26pm
Manage Discussion Entry
I've heard of Node from other students when I was in 301.  Aren't we working with nodes already in HTML?  Different things with the same terminology can get confusing.  And I never even tried to create a Live Server myself, I only watched along the instructor's Live Server.  I won't know what I'm missing.

 Reply Reply to Comment
Collapse SubdiscussionTiger Hsu
Tiger Hsu
Dec 15, 2017 Dec 15, 2017 at 12:12pm
Manage Discussion Entry
I think that Node.js can become much bigger and can be more in depth than we realize. I noticed that there are different types of "HTTPS requesting" technologies out there another one I have see was the docker framework.

 Reply Reply to Comment
Collapse SubdiscussionAmber Kim
Amber Kim
Dec 17, 2017 Dec 17, 2017 at 9:57pm
Manage Discussion Entry
I'm not sure about the 'node' terminology but I've tried some beginner tutorials on node.js in the terminal and it just seemed the same way of coding javascript only no webpage feedback - at least for the 'hello world' type tutorial I've gone through so far. And working with node.js in the terminal felt like working with the console in Chrome.

To turn on live sever, if I remember right, just go to your terminal in the folder with the index.html file you want to open up and type:

live-server

Not sure if it's the same for windows.

 Reply Reply to Comment
Collapse SubdiscussionTiger Hsu
Tiger Hsu
Dec 15, 2017 Dec 15, 2017 at 12:09pm
Manage Discussion Entry
Wow; this is gonna be really interesting! After reading the Node.js documentation I had played with the localhost/8888 example that they have and it is really interesting. So, the server.js file had a https:// event handler that I ran thru my command line. And I was able to build simple text elements . I have a better understanding that node.js  is like a bunch of event handlers but on a much bigger scale because it is using various machines to perform different callbacks.

 Reply Reply to Comment
Collapse SubdiscussionChris Lesesne
Chris Lesesne
Dec 17, 2017 Dec 17, 2017 at 7:02pm
Manage Discussion Entry
Nice! Looks like your response already helped answer my question about Node.js and event handlers!

 Reply Reply to Comment
Collapse SubdiscussionChris Lesesne
Chris Lesesne
Dec 17, 2017 Dec 17, 2017 at 6:59pm
Manage Discussion Entry
Since Node.js is described as a using a "single-threaded model with event looping", does that mean that it uses event handlers to determine the order/priority of data requests or function calls?

 Reply Reply to Comment
Collapse SubdiscussionAmber Kim
Amber Kim
Dec 17, 2017 Dec 17, 2017 at 9:52pm
Manage Discussion Entry
No questions right now. Just eager to start builing with it.

 Reply Reply to Comment
Collapse SubdiscussionBrandon Buchholz
Brandon Buchholz
Dec 17, 2017 Dec 17, 2017 at 10:44pm
Manage Discussion Entry
No questions yet, just eager to learn more in the upcoming lecture.

 Reply Reply to Comment
Collapse Subdiscussiondtcomer@gmail.com
dtcomer@gmail.com
Dec 17, 2017 Dec 17, 2017 at 11:37pm
Manage Discussion Entry
So the whole purpose of this nodeJS stuff is to use javascript to do server side stuff.

Question(s)

1. Why can node JS only operate on 1 thread?

2. How much "stuff" can that thread handle? Is there a way to know, we as developers, are maxing out the thread? How would you measure maxing out the thread? (size - MB/TB or time utilization - ms/ns)

 

 

 Reply Reply to Comment
Collapse SubdiscussionDevin Cunningham
Devin Cunningham
Dec 18, 2017 Dec 18, 2017 at 11:20am
Manage Discussion Entry
Once we get into node.js I am sure I will have questions.

 Reply Reply to Comment
Collapse SubdiscussionCody Green
Cody Green
Dec 18, 2017 Dec 18, 2017 at 12:01pm
Manage Discussion Entry
im excited to dive into some server side stuff and learn a bit about this. my question is in what way functionally is this going to be different from live-server for us? are we just replacing it s we can see and manipulate the backend?

 

 Reply Reply to Comment
Collapse SubdiscussionTrevor Dobson
Trevor Dobson
Dec 18, 2017 Dec 18, 2017 at 1:21pm
Manage Discussion Entry
I'm not even sure where to start with questions so I will let class play out which I am sure will answer most of my confusion.

 Reply Reply to Comment
Collapse SubdiscussionAriel Altaras
Ariel Altaras
Dec 18, 2017 Dec 18, 2017 at 3:47pm
Manage Discussion Entry
I feel like I have a decent basic understanding of node.js - it's a way to run JavaScript outside the browser, but it's also kind of a library. And it's the first step to learning "backend" JavaScript.

 Reply Reply to Comment
Collapse SubdiscussionRyan Johnson
Ryan Johnson
Dec 18, 2017 Dec 18, 2017 at 4:05pm
Manage Discussion Entry
The reading made node.js sound like more than 'kind of a library,' like there is huge potential in this language.

I am also excited to dive into the backend portion of this course using this tool this week.

 Reply Reply to Comment
Collapse SubdiscussionRyan Johnson
Ryan Johnson
Dec 18, 2017 Dec 18, 2017 at 3:59pm
Manage Discussion Entry
Trying to wrap my head around what node.js is and does while attempting to skim tonights readings is tough. I want to dive into all of these topics and languages for depth of understanding but I guess that will have to wait and will hopefully come with time.

Question- If node.js is truly a 'huge universe with lots of potential and opportunity,' how are you supposed to wrap your head around it and when do you know that you have accomplished that goal?

 Reply Reply to Comment
Collapse SubdiscussionAlicia Lycan
Alicia Lycan
Dec 18, 2017 Dec 18, 2017 at 3:59pm
Manage Discussion Entry
What's the difference between Node.js and AJAX? Can you explain more about event driven asynchronous callbacks?

 Reply Reply to Comment
Collapse SubdiscussionIxius Procopios
Ixius Procopios
Dec 18, 2017 Dec 18, 2017 at 4:56pm
Manage Discussion Entry
Node.js is back end while Ajax is front end. 

Ajax is used for updating the UI while Node is for building servers to access databases. They are often used together. 

 Reply Reply to Comment
Collapse SubdiscussionIxius Procopios
Ixius Procopios
Dec 18, 2017 Dec 18, 2017 at 4:52pm
Manage Discussion Entry
No questions really, but I feel like I'll run into them as we use it.

 Reply Reply to Comment
Collapse SubdiscussionAaron Bruce
Aaron Bruce
Dec 18, 2017 Dec 18, 2017 at 5:06pm
Manage Discussion Entry
Node.js is a server-side platform written in javascript, used to develop server-side and network apps. perks include:

asynchronous requests

event-driven

high execution speed

highly scalable

no buffering

uses MIT license

it also ships with useful modules so writing code from scratch every time  isn't always necessary

The main idea is to allow javascript to be used for backend computer coding.

 Reply Reply to Comment
Collapse SubdiscussionOvi Parasca
Ovi Parasca
Dec 18, 2017 Dec 18, 2017 at 6:09pm
Manage Discussion Entry
Being in the industry i've constantly heard "node" and "node.js", but honestly thought it was just another framework like React and TypeScript. But the reading best described to me as a runtime environment and a framework, so you can basically run your js code outside the browser. Super neat. I did see how node.js is single-threaded and i was wondering the potential hazards of being single-threaded are for node?

 Reply Reply to Comment
Collapse SubdiscussionRafael Malave
Rafael Malave
Dec 18, 2017 Dec 18, 2017 at 6:11pm
Manage Discussion Entry
I'm looking forward to using node.js to create more robust applications. It was mentioned we are going to build a single page application. I am curious to know how routing works on single page applications.. I know there are SEO issues to keep in mind with SPA's.

 Reply Reply to Comment
Collapse SubdiscussionAyanle (ah-yan-leh)
Ayanle (ah-yan-leh)
Dec 18, 2017 Dec 18, 2017 at 6:24pm
Manage Discussion Entry
I'm really excited that we've started on Node. 

 Reply Reply to Comment
Collapse SubdiscussionMichael Brown
Michael Brown
Dec 19, 2017 Dec 19, 2017 at 7:26pm
Manage Discussion Entry
No questions. Looking forward to seeing it in action more. This helps cement my understanding.

 Reply Reply to Comment
Collapse SubdiscussionEric Cobb
Eric Cobb
Dec 27, 2017 Dec 27, 2017 at 5:03pm
Manage Discussion Entry
Interesting read. Bookmarked it so I can refer back to it as needed. I currently don't have any questions worth mentioning at the moment. 

 Reply Reply to Comment
Collapse SubdiscussionRonnie Lewis
Ronnie Lewis
Jan 2, 2018 Jan 2 at 3:20am
Manage Discussion Entry
So, Node.js is backend JavaScript?

 Reply Reply to Comment
Collapse SubdiscussionDarcy Knore
Darcy Knore
Jan 4, 2018 Jan 4 at 5:12pm
Manage Discussion Entry
no questions really. trying to figure out how node.js fits in.. and how to even talk about/refer to it's role in web development.

 Reply Reply to Comment
Collapse SubdiscussionDambergN
DambergN
Jan 11, 2018 Jan 11 at 12:05pm
Manage Discussion Entry
to put it simply, nodejs is a server side application that allows you to use javascript which has primarily been a client side protocol to be used server side.  This is beneficial because you used to have to use a separate language like php or python.  But now you can learn one language and do both front end and back end development.

 Reply Reply to Comment
Collapse SubdiscussionMitchel Hall
Mitchel Hall
Jan 16, 2018 Jan 16 at 4:35pm
Manage Discussion Entry
Another fun one. The commands are not instantly intuitive, but I am sure with enough repetition they will be easier to use. 

Read 08: Intro to SQL Links

Read
http://sqlbolt.com/  (Essential)

https://leanpub.com/aprimeronsql/read  (Reference)

Collapse SubdiscussionTiger Hsu
Tiger Hsu
Dec 15, 2017 Dec 15, 2017 at 2:18pm
Manage Discussion Entry
One benefit to using a relational database system is how the tables relate to each other. For instance if you have two tables (items, customers) you need to relate them. One way to do this is by having another table with is the key and customer id matching pair so that a customer will show how many items they ordered.

One type of SQL statement that I understand is the INSERT INTO mytable VAL expression; this allows updated information onto the query.

 Reply Reply to Comment
Collapse SubdiscussionChris Lesesne
Chris Lesesne
Dec 17, 2017 Dec 17, 2017 at 11:19pm
Manage Discussion Entry
Using relational database systems allows you to specify sets of data you want to compare (either within a table or across multiple tables) and manipulate the data to be viewed in a way that best fits your analysis. For example, SQL statement: SELECT Age, Height FROM AthletesTable will filter and display the ages and heights for each athlete from the table 'AthletesTable'.

Question:

- What are some of the limitations of SQL database queries (where does it break down in efficiency) that aren't mentioned in the readings?

 Reply Reply to Comment
Collapse SubdiscussionAmber Kim
Amber Kim
Dec 19, 2017 Dec 19, 2017 at 12:57pm
Manage Discussion Entry
The only thing I got was that it was slower but that the tradeoff is good because of its simplicity.

 Reply Reply to Comment
Collapse SubdiscussionArthur Allen
Arthur Allen
Dec 18, 2017 Dec 18, 2017 at 8:43pm
Manage Discussion Entry
Relational database systems allow access to searchable information.  The Select statement declares data we are looking for.  (The examples started easy, but by the end I had to have the page give me the answers.  It would have been useful if they had retained my attempt to compare with the actual answer so I could have seen what I did wrong.)  I can sort-of see where some of the more serious research tools I've used use tools similar to those in this example, so they probably use SQL.  When creating new forms, do you have to enter everything as SQL commands, or can you paste in things made in a different format?

 Reply Reply to Comment
Collapse SubdiscussionAmber Kim
Amber Kim
Dec 19, 2017 Dec 19, 2017 at 12:55pm
Manage Discussion Entry
1. One benefit of using a relational database system? Simplicity.

2.  One SQL Statement:
DROP TABLE IF EXISTS mytable;
Removes the whole table

3. Question: How would we use/connect to SQL data when building an app. 

 Reply Reply to Comment
Collapse SubdiscussionJB Tellez
JB Tellez
Dec 20, 2017 Dec 20, 2017 at 12pm
Manage Discussion Entry
Great point Amber. We'll need a tool to use/connect to database. We'll talk about such tools in class tonight.

 Reply Reply to Comment
Collapse SubdiscussionAlicia Lycan
Alicia Lycan
Dec 20, 2017 Dec 20, 2017 at 9:23am
Manage Discussion Entry
One benefit of using a relational database system is that it allows multiple database users to access a database simultaneously. Built-in locking and transactions management functionality allow users to access data as it is being changed, prevents collisions between two users updating the data, and keeps users from accessing partially updated records.

One type of SQL statement is the SELECT statement which is used to select data from a database. The data returned is stored in a result table. 

 

Can information from a relational database be shared easily? Does it ever get too complex of information? 

 Reply Reply to Comment
Collapse SubdiscussionJB Tellez
JB Tellez
Dec 20, 2017 Dec 20, 2017 at 12:02pm
Manage Discussion Entry
"Easy" is a relative term, of course. But a relational database has a balance between ease and other concerns that works for a lot of folks.

 Reply Reply to Comment
Collapse Subdiscussiondtcomer@gmail.com
dtcomer@gmail.com
Dec 20, 2017 Dec 20, 2017 at 11:26am
Manage Discussion Entry
One benefit of the relational database system is the ability to perform a one to many search function. The fact that you can process data elements base on their key common attributes makes the processing capability huge.

 

No questions at this time.

 Reply Reply to Comment
Collapse SubdiscussionTrevor Dobson
Trevor Dobson
Dec 20, 2017 Dec 20, 2017 at 12:41pm
Manage Discussion Entry
A benefit of using a relational database system is its simplicity that allows for safe and scalable storage.  I understood the WHERE condition pretty well, you're just setting a condition to filter the returns.  No questions, just excited to start implementing this.

 Reply Reply to Comment
Collapse SubdiscussionDevin Cunningham
Devin Cunningham
Dec 20, 2017 Dec 20, 2017 at 2:43pm
Manage Discussion Entry
For the work I am in now, it would be beneficial to have all of our patients in databases so we could select certain demographics to market to. We could sort/choose exactly who we would want to run a campaign for. I understand any of the sorting methods pretty well. We could select patient emails where their age is between 24-35.

 Reply Reply to Comment
Collapse SubdiscussionAriel Altaras
Ariel Altaras
Dec 20, 2017 Dec 20, 2017 at 4:07pm
Manage Discussion Entry
One benefit of using a relational database is that it is possible to store the same information about a large number of the same type of item. To me they seem similar to objects in JavaScript, so a relational database would probably be very useful to store large numbers of objects.

One statement in SQL is ORDER BY which allows you to sort based on data in one column in ascending or descending order.

 Reply Reply to Comment
Collapse SubdiscussionAyanle (ah-yan-leh)
Ayanle (ah-yan-leh)
Dec 20, 2017 Dec 20, 2017 at 6:19pm
Manage Discussion Entry
There are a lot of benefits to using a relational database system. It primarily allows us to easily store and retrieve data from multiple related tables, like 'cars' and 'drivers.' This topic didn't touch on how to connect an express app with a postgres db. I have a lot of questions about how to connect and configure the two to work together.

 Reply Reply to Comment
Collapse SubdiscussionMichael Brown
Michael Brown
Dec 20, 2017 Dec 20, 2017 at 7:53pm
Manage Discussion Entry
One benefit of using a relational database is that it's an easy way to store and retrieve information. A WHERE statement is a way to locate (query) a database with conditionals using numeric or textual operators to better pinpoint and retrieve specific information.

Edited by Michael Brown on Dec 20, 2017 at 7:55pm
 Reply Reply to Comment
Collapse SubdiscussionOvi Parasca
Ovi Parasca
Dec 20, 2017 Dec 20, 2017 at 9:04pm
Manage Discussion Entry
Some benefits of using a relational database is that it's simple, safe and scalable.

CREATE TABLE creates a new table and DROP TABLE deletes a table. I don't have any questions yet aside from wanting to know which is better to use, a SQL db or a NoSQL database. Such as why use one over the other?

 Reply Reply to Comment
Collapse SubdiscussionBrandon Buchholz
Brandon Buchholz
Dec 21, 2017 Dec 21, 2017 at 2:16pm
Manage Discussion Entry
What is one benefit of using a relational database system?
One benefit is ease of use for users to query any table in the database, and combine related tables using special join functions to include relevant data contained in other tables in the results. 
Explain one type of SQL statement you understand.
SELECT tells what column you are wanting to look at and FROM is the name of the table that you are trying to view.
What is one question you have from the reading?
No questions, just have to get used to using the syntax.
 Reply Reply to Comment
Collapse SubdiscussionRyan Johnson
Ryan Johnson
Jan 4, 2018 Jan 4 at 5:39pm
Manage Discussion Entry
Great explanation of the use benefits.

 Reply Reply to Comment
Collapse SubdiscussionIxius Procopios
Ixius Procopios
Dec 21, 2017 Dec 21, 2017 at 4:24pm
Manage Discussion Entry
Advantages to a Relational database:

A table format is simple and easy to use and understand. These databases allow multiple users to access it while preventing conflicts and users from accessing partially updated records. You are also able to control access to the database to keep your data secured. Most importantly relational databases allow access through server's on networks, allowing users to access the data remotely.  

Creating tables from existing ones:

CREATE TABLE <new table> AS SELECT <selection> FROM<OLDTABLE>

No questions. 

 

 Reply Reply to Comment
Collapse SubdiscussionRafael Malave
Rafael Malave
Dec 21, 2017 Dec 21, 2017 at 5:50pm
Manage Discussion Entry
One benefit of using a relational database system is how efficient we can look at and/or modify data by searching for data with specific properties.

 Reply Reply to Comment
Collapse SubdiscussionRyan Johnson
Ryan Johnson
Jan 4, 2018 Jan 4 at 5:38pm
Manage Discussion Entry
That sounds so simple, why is it so complicated? : )

 Reply Reply to Comment
Collapse SubdiscussionCody Green
Cody Green
Dec 27, 2017 Dec 27, 2017 at 8:27pm
Manage Discussion Entry
the create table statement makes a ton of sense i think, relationable databases just make sense.

 Reply Reply to Comment
Collapse SubdiscussionEric Cobb
Eric Cobb
Jan 4, 2018 Jan 4 at 12:42pm
Manage Discussion Entry
SQL communicates to the query if I am understanding it correctly. A lot of useful information here that I will need to reflect on. 

 Reply Reply to Comment
Collapse SubdiscussionRyan Johnson
Ryan Johnson
Jan 4, 2018 Jan 4 at 5:36pm
Manage Discussion Entry
-What is one benefit of using a relational database system?

The relational database system as I understand it uses language that is intuitive to select, store and navigate through multiple data tables. The benefit of this system is that by storing information in a database it can be easily accessed and used by multiple systems or simply store data to be called and organized in a custom view for the end user.

-Explain one type of SQL statement you understand.

SELECT * FROM location

WHERE col_1;

This basic call will select ALL information in the location table for col_1 and execute the call with the ; to produce a view of the information in col_1 of the location table.

-What is one question you have from the reading?

Where can I find a good quality, comprehensive syntax overview of the SQL language? I need to see the bigger picture to better understand this language.

 Reply Reply to Comment
Collapse SubdiscussionRonnie Lewis
Ronnie Lewis
Jan 6, 2018 Jan 6 at 2:27am
Manage Discussion Entry
What is one benefit of using a relational database system?

It's a good way to answer questions about your data.

Explain one type of SQL statement you understand.

I understand all of the statements, but when it came to the practicing, DROP TABLE IF EXIST was the only one I got right the first time. You just type it in, add the table name at the end, and the magic happens!

 

 Reply Reply to Comment
Collapse SubdiscussionDarcy Knore
Darcy Knore
Jan 9, 2018 Jan 9 at 4:40pm
Manage Discussion Entry
1. What is one benefit of using a relational database system?

It increases/multiplies the scope of applications

2. Explain one type of SQL statement you understand.

UPDATE TABLE allows you to update tables with a given parameters... such as ADD, or DROP.

 Reply Reply to Comment
Collapse SubdiscussionDambergN
DambergN
Jan 11, 2018 Jan 11 at 12:10pm
Manage Discussion Entry
SQL databases are basically spreadsheets.  data is stored in tables made of rows and columns.  A database would be like a new spreadsheet while a table would be the sheet inside that database.  This makes data easily accessible and arrangable.

 Reply Reply to Comment
Collapse SubdiscussionAaron Bruce
Aaron Bruce
Jan 14, 2018 Jan 14 at 4:10pm
Manage Discussion Entry
SELECT * FROM table-name        will select all data from the specified table name

SELECT DISTINCT column-1, column-2 FROM table-name      will select specified column data from specified table

SELECT column-1 FROM table-1 INNER JOIN table-2 ON table-1.column-name = table-2.column-name

Will give both sets of data to the specified columns of the same name in two different tables

INSERT INTO table-name VALUES ($1, $2, $3, $4, $5)

Will insert new data into the columns of a table at the proper values, the values must match the column names in the same order

 Reply Reply to Comment
Collapse SubdiscussionMitchel Hall
Mitchel Hall
Jan 16, 2018 Jan 16 at 4:37pm
Manage Discussion Entry
SQL, tried to get good at this about 20 years ago, and just as I was starting to figure it out I moved onto a different "job". Nothing like starting over, again. 

Read 09: SQL Joins & Relations Links
21 21 unread replies. 24 24 replies.
Read
http://sqlbolt.com/lesson/select_queries_with_joins  (Essential)

https://leanpub.com/aprimeronsql/read#leanpub-auto-understanding-joins  (Reference)

Discuss
What does it mean to "normalize" a database?

Explain what an inner join accomplishes?

What is one question you have from the reading?

Collapse SubdiscussionTiger Hsu
Tiger Hsu
Dec 24, 2017 Dec 24, 2017 at 7:31pm
Manage Discussion Entry
According the resources given to us Database normalize means to reduce data redundancy thru update, insertion, and deletion anomaly. Normalize  minimally has one, two and third forms which help reduce clutter of tables.

Inner Join brings tables together; in the SQLbolt example one of the exercise was to inner joining two different tables, one table was movie titles and another consisted of revenue sales. INNER JOIN allowed the two tables to be brought together using the movie_id. key.

 

 Reply Reply to Comment
Collapse SubdiscussionArthur Allen
Arthur Allen
Dec 25, 2017 Dec 25, 2017 at 8:19pm
Manage Discussion Entry
Normalization means to organize a database to reduce redundancy.

The inner join matches different tables that have the same key.

This time I was unable to solve any of the SQLBolt challenges, and had to ask for the answer every time.  I thought I was following the example, and I'm not sure in any case exactly what I was doing wrong.  In lesson 8, they introduce outer joins but then they don't require it in a task until the last one.  I kept trying to use the dot notation, but the correct answer did not use it.  And on it goes.

 Reply Reply to Comment
Collapse SubdiscussionAmber Kim
Amber Kim
Dec 26, 2017 Dec 26, 2017 at 5:04pm
Manage Discussion Entry
Yes, the requirements weren't very clear at times and I didn't read about leaving out the dot notation.

 Reply Reply to Comment
Collapse SubdiscussionAmber Kim
Amber Kim
Dec 26, 2017 Dec 26, 2017 at 5:02pm
Manage Discussion Entry
Database normalization allows for data in a database to grow independently of each other. From my understanding, it's a way of structuring your data across multiple tables so that you can grow your data more freely without messing with one main big table that doesn't necessarily conform to how you need to store new information over time.

Inner join matches the rows from one table to another using a matching key.

What is the best way to keep track of all the different tables in a normalized database without letting things get too messy?

 Reply Reply to Comment
Collapse SubdiscussionCody Green
Cody Green
Dec 27, 2017 Dec 27, 2017 at 9:08pm
Manage Discussion Entry
normalizing is just organizing the columns and rows of a database.

inner join takes all rows for two tables if there is a match between the columns

dont really have a question at the moment will update after lecture with any questions

 Reply Reply to Comment
Collapse SubdiscussionChris Lesesne
Chris Lesesne
Dec 27, 2017 Dec 27, 2017 at 11:45pm
Manage Discussion Entry
Normalizing a database reduces the amount of duplicate data in a table and allows data to change without affecting other sets of data. An inner join displays the resulting row(s) of combined columns from two tables that match the specific conditions of a query (same primary key in the ON constraint).

 

 Reply Reply to Comment
Collapse SubdiscussionAlicia Lycan
Alicia Lycan
Dec 28, 2017 Dec 28, 2017 at 10:55am
Manage Discussion Entry
To "normalize" a database is to minimize duplicate data in a table, allowing data in a database to grow independently of each other. The tradeoff is queries can get a bit more complex, particularly when working with large data tables. 

An INNER JOIN matches rows from the first table and second table which have the same key (as defined by the ON constraint) creating a result row with the combined columns from both tables.

How will this help us when scraping a third-party database to push data into our own database and pull from when a user makes a query?

 Reply Reply to Comment
Collapse SubdiscussionTrevor Dobson
Trevor Dobson
Dec 28, 2017 Dec 28, 2017 at 11:03am
Manage Discussion Entry
Normalizing a database means to minimize duplicating data across the database.  An inner join allows you to grab data from rows with the same key that are part of different tables.  At this point I'm still not sure where to even start with questions.

 Reply Reply to Comment
Collapse SubdiscussionDevin Cunningham
Devin Cunningham
Dec 28, 2017 Dec 28, 2017 at 1:29pm
Manage Discussion Entry
Normalizing a DB means to organize the database to reduce data redundancy.

Inner join combines 2 tables into 1. Say if you had a table of dogs that had their name, breed, and age, and another table that had the same dogs but only listed their location, you could inner join the tables and have everything match up.

Mob coding last night at cowork cleared up a lot of questions.

 Reply Reply to Comment
Collapse Subdiscussiondtcomer@gmail.com
dtcomer@gmail.com
Dec 28, 2017 Dec 28, 2017 at 4:04pm
Manage Discussion Entry
What does it mean to normalize the database?

It means organizing the data in the tables of the database to reduce redundancy and improve processing times . It is like refactoring in code or making the database dryer.

I can't figure out what the inner join does what it does.

How do you tell whether to use inner/outer/left/right or full. What rules regulate how you approach this?

 Reply Reply to Comment
Collapse SubdiscussionRafael Malave
Rafael Malave
Dec 28, 2017 Dec 28, 2017 at 4:11pm
Manage Discussion Entry
To normalize means to break data down into pieces and store it across multiple orthogonal tables, this is useful because it minimizes duplicate data in any single table, and allows for data in the database to grow independently of each other. 

The inner join matches rows from the first table and a second table which have the same key to create a result row with the combined columns.

 Reply Reply to Comment
Collapse SubdiscussionAyanle (ah-yan-leh)
Ayanle (ah-yan-leh)
Dec 28, 2017 Dec 28, 2017 at 4:21pm
Manage Discussion Entry
What does it mean to "normalize" a database?

You are allowing each table to be independent of each other and to reduce duplication.

Explain what an inner join accomplishes?

You're getting a result only when there's a matching values in selected columns from 2 or more tables. I think this is most appropriate in a relational DB where Table A is a dependent of Table B.

What is one question you have from the reading?

None yet. I hope to apply these concepts in the next lab or two.

 Reply Reply to Comment
Collapse SubdiscussionBrandon Buchholz
Brandon Buchholz
Dec 28, 2017 Dec 28, 2017 at 4:25pm
Manage Discussion Entry
What does it mean to "normalize" a database?
To group data into different tables, which helps minimize duplicate data. Also, allows for data in the database to grow independently of each other. 
Explain what an inner join accomplishes?
It allows you to join two different tables that have the same key id as their first column.
What is one question you have from the reading?
None, just need to practice with it.
 Reply Reply to Comment
Collapse SubdiscussionAriel Altaras
Ariel Altaras
Dec 28, 2017 Dec 28, 2017 at 5pm
Manage Discussion Entry
Database normalization splits different data into separate tables to reduce duplication in a database.

An inner join matches rows between two tables where the rows have the same key (usually id). It matches all of the data row by row.

I don't know that I really have a question, but I'm seeing how normalized databases could be useful - for example storing data about several rows where one property has a limited number of options (like the buildings in the example used).

 Reply Reply to Comment
Collapse SubdiscussionOvi Parasca
Ovi Parasca
Dec 28, 2017 Dec 28, 2017 at 6:18pm
Manage Discussion Entry
- Normalize means to minimize duplicate data in a database and splitting up data into multiple tables, that way the data in those tables can change/update/delete without affecting the other tables in the database.

- Inner Join combines data from 2 tables by using a key to match them. 

- The Left Join, Right Join, Full Join sort of remind of when trying to fix merge conflicts, but ultimately i'd like to see how it works in a db so i can better visualize those Joins, because i believe to have an idea based on previous related knowledge but i feel timid to fully believe me haha.

 Reply Reply to Comment
Collapse SubdiscussionIxius Procopios
Ixius Procopios
Dec 28, 2017 Dec 28, 2017 at 7:12pm
Manage Discussion Entry
Database normalization:

Minimizes duplicate data in table

Gets data in database to grow independently of each other

Queries are more complex since they have to find data from different parts of database.

  

INNER JOIN

Used to combine row data across two separate tables using the primary key as defined by ON to make a row with columns from both tables. 

 

 

No questions

 

 Reply Reply to Comment
Collapse SubdiscussionEric Cobb
Eric Cobb
Jan 4, 2018 Jan 4 at 12:48pm
Manage Discussion Entry
normalization minimizes duplicate data in any single table and allows for data in the database to grow independently of each other. 

INNER JOIN means you can combine row data across two separate tables using this unique key. 

No additional questions at this time. 

 Reply Reply to Comment
Collapse SubdiscussionDarcy Knore
Darcy Knore
Jan 4, 2018 Jan 4 at 5:02pm
Manage Discussion Entry
What does it mean to "normalize" a database?

The process of organizing the columns and tables of a relational database to reduce data redundancy and improve data integrity.

Explain what an inner join accomplishes?

INNER JOIN matches rows from the first table and the second table which have the same key (as defined by the ON constraint) to create a result row with the combined columns from both tables.

no questions... still trying to get the hang of how to write queries to obtain data i need

 Reply Reply to Comment
Collapse SubdiscussionRyan Johnson
Ryan Johnson
Jan 4, 2018 Jan 4 at 5:57pm
Manage Discussion Entry
What does it mean to "normalize" a database?

Normalizing a database helps to reduce repetitious information and improves the quality of the data stored in the database tables.

Explain what an inner join accomplishes?

Inner Join matches columns from multiple tables by a common key which is defined by the ON command.

What is one question you have from the reading?

Too many to put here but that has mostly to do with my current grasp of this language.

 Reply Reply to Comment
Collapse SubdiscussionRonnie Lewis
Ronnie Lewis
Jan 6, 2018 Jan 6 at 3:35am
Manage Discussion Entry
What does it mean to "normalize" a database?

Normalizing a database is a way of organizing information so that it's not dependent on other data.

Explain what an inner join accomplishes?

Inner join allows you to integrate the results of two tables.

What is one question you have from the reading?

Are the key values important when joining? 

 

 Reply Reply to Comment
Collapse SubdiscussionDambergN
DambergN
Jan 11, 2018 Jan 11 at 12:16pm
Manage Discussion Entry
database normalization is the process much like refactoring code with the same concept of not repeating.  Instead of having the same data repeated on two separate tables you can use inner join and a relational ID to link the two pieces of information together.  Therefore saving space and being more efficient.  This is a cool concept but what about relating data across different databases?  Inner join implies its for internal aka same database.

 Reply Reply to Comment
Collapse SubdiscussionAaron Bruce
Aaron Bruce
Jan 14, 2018 Jan 14 at 4:57pm
Manage Discussion Entry
Normalization of a database means that it's table(s) will not have redundant data or data that does not relate directly to specified domains of the columns. EX: having 3 tables with a column NAME for employees working at company X, vs having 1 of those tables having that particular column.

This promotes speed efficiency and clarity within tables.

 

Inner Join is used when separate tables have one or multiple columns that have the same name and will make them equal each other

SELECT column-1 FROM table-1

INNER JOIN table-2 ON table-1.column-1 = table-2.column-1

 Reply Reply to Comment
Collapse SubdiscussionMichael Brown
Michael Brown
Jan 15, 2018 Jan 15 at 12:03pm
Manage Discussion Entry
Normalize is separating tables in a way that prevents duplication. Inner join connects two tables that have a Primary key and foreign key connection point available. No questions from the reading came to mind.

 Reply Reply to Comment
Collapse SubdiscussionMitchel Hall
Mitchel Hall
Yesterday Jan 25 at 3:14pm
Manage Discussion Entry
Database normalization, as I currently understand it is a process in which you organize tables in a database that relate to one another and allow for changes in one table to not adversely affect the data in another table. 

An inner join allows databases with a common Key, or reference to be related to one another so for instance a customer database would have a customers Name, address, and other such data but their purchase history would be in another table but they are joined together so when the customer is queried their purchase history is also available.

No pressing questions, gonna take a lot of work to get good at this but I understand it enough that I think I will get there.

Read 10: JS & jQ pp 528-543
24 24 unread replies. 26 26 replies.
Read
JS & jQ pp 528-543 (Essential)

http://eloquentjavascript.net/05_higher_order.html (Essential)


Collapse SubdiscussionArthur Allen
Arthur Allen
Dec 31, 2017 Dec 31, 2017 at 7:03pm
Manage Discussion Entry
I already knew about pop() because I had to use it on my 201 final project.  When a ball hit a brick, I had to shift all the other array elements behind it, then remove the last element with pop().

I've noticed with Codewars that most of the popular solutions are much more compact than mine, but I still maintain that mine are easier to read.  I'm still used to looping through for loops, and this will be hard to unlearn.

I've used recursive functions in Pascal, but this is the first time I've seen them in JavaScript.

I don't understand the exercise to use "reduce" to combine several arrays into one array.  Reduce will just add up the totals of each element, will it not?

 Reply Reply to Comment
Collapse SubdiscussionAmber Kim
Amber Kim
Jan 1, 2018 Jan 1 at 2:03pm
Manage Discussion Entry
I'm still also unsure about how to use reduce, map, etc. I think it will help me to use them in a project.

 Reply Reply to Comment
Collapse SubdiscussionAmber Kim
Amber Kim
Jan 1, 2018 Jan 1 at 2:02pm
Manage Discussion Entry
array.sort lets you define how you want an array to be sorted. When is abstraction not so good for helping to understand code?

 Reply Reply to Comment
Collapse SubdiscussionChris Lesesne
Chris Lesesne
Jan 1, 2018 Jan 1 at 2:07pm
Manage Discussion Entry
The '.filter()' array method acts on an array to return only the elements that meet a certain condition(s). It then makes a new array with those passed elements.

A "higher order function" can take in (or return) other functions as arguments, and allow us to take advantage of abstraction with functions as well, not just individual values.

Question(s):

- A more specific example where the '.apply()' method would be necessary when using higher-order functions?

 Reply Reply to Comment
Collapse SubdiscussionTiger Hsu
Tiger Hsu
Jan 1, 2018 Jan 1 at 6:29pm
Manage Discussion Entry
.filter(); array is very useful if you are looking for a certain 'string item'. I like it during some of the Kata code wars stuff.

 

 Reply Reply to Comment
Collapse SubdiscussionTiger Hsu
Tiger Hsu
Jan 1, 2018 Jan 1 at 6:25pm
Manage Discussion Entry
"higher order function" in my understanding is using a regular one function and being able to call it into another two function, using function one. One array method that I remembered was using the for each as a higher order function.

-taking a regular array function..

 for each (variable in object) {

statement
}
-Then making adding more statements to it in order to create a higher level function,
var a = ["a", "b", "c"];
a.forEach(function(entry) {
    console.log(entry);
});
calling the variable 'a' would allow each individual entry to be listed.

 Reply Reply to Comment
Collapse SubdiscussionRafael Malave
Rafael Malave
Jan 1, 2018 Jan 1 at 9:05pm
Manage Discussion Entry
Higher order functions are functions that operate on other functions, either by taking them as arguments or by returning them. One function of the functions I understand is the Array.prototype.map() function, which transforms an array by applying a function to all elements in the array. The map function returns a new array with all the elements transformed by the passed in function by iterating through the elements of the old array.

 Reply Reply to Comment
Collapse SubdiscussionDarcy Knore
Darcy Knore
Jan 1, 2018 Jan 1 at 9:25pm
Manage Discussion Entry
Explain one array method that you understand.
   The map() method transforms an array by applying a function to all of its elements and building a new array from the returned values. The new array will have the same length as the input array, but its content will have been “mapped” to a new form by the function.

  2. What is the meaning of the phrase "higher order function"? 

     Higher order function are functions that operate on other functions, either by taking them as arguments or by returning them.

No questions really... lot's of info. to digest / concepts to wrap my head around!!

 Reply Reply to Comment
Collapse SubdiscussionTrevor Dobson
Trevor Dobson
Jan 2, 2018 Jan 2 at 12:41pm
Manage Discussion Entry
I like the map method, it calls a provided function for each element in the array.  I used this in one of the code wars katas so I already had a little understanding of it.  Higher order functions operate on other functions.  They use them as either arguments or return them.  I don't really have any questions on the readings, it just shows how powerful these functions are and how many different tools you have to create clean dry code with less room for bugs.

 Reply Reply to Comment
Collapse SubdiscussionDevin Cunningham
Devin Cunningham
Jan 2, 2018 Jan 2 at 1:34pm
Manage Discussion Entry
Higher order functions are functions that can call other functions or functions that can create/change other functions.

"Summarizing with reduce" seems pretty straightforward. It loops through the array adding the current number to a variable then goes to the next number and adds it to that same variable until the end of the array then returns the value.

 Reply Reply to Comment
Collapse SubdiscussionAlicia Lycan
Alicia Lycan
Jan 2, 2018 Jan 2 at 4:07pm
Manage Discussion Entry
The map() array method modifies elements; calls a function on each element in an array and creates new array results.

"Higher order function" are functions that operate on other functions, either by taking them as arguments or by returning them.

When we talk about functional programming, how do these different function and method types play into that and help us be more efficient when working with large, complicated data sets?

 Reply Reply to Comment
Collapse SubdiscussionAriel Altaras
Ariel Altaras
Jan 2, 2018 Jan 2 at 4:37pm
Manage Discussion Entry
One array function I like is .reverse() which takes the items in an array and returns an array with their order reversed.

A higher order function is a function that acts on another function - taking another function as an argument or returning a function.

One question I have about the reading is how they're using arrays, it seems similar to tables in a database, but without a database.

Edited by Ariel Altaras on Jan 2 at 4:37pm
 Reply Reply to Comment
Collapse SubdiscussionAyanle (ah-yan-leh)
Ayanle (ah-yan-leh)
Jan 2, 2018 Jan 2 at 5:44pm
Manage Discussion Entry
Explain one array method that you understand.

They all make sense to me when used as a pure function but NOT in the context of a larger application. I want to see them in action within larger functions.

What is the meaning of the phrase "higher order function"?

Its a function that takes in a function or that returns a function. 

What is one question you have from the readings?

Based on this reading, it seems like we are going back to client side JavaScript focus but I want more Node/Postgres :) 

 Reply Reply to Comment
Collapse SubdiscussionMichael Brown
Michael Brown
Jan 2, 2018 Jan 2 at 5:46pm
Manage Discussion Entry
Higher order function means that a function can take another function as an argument or return a function as a result. Filter() is an method that takes an array and performs an action on it based on the function its given as its argument. That action returns a new array that is filtered down to only those elements that pass through the "filtering process".

 Reply Reply to Comment
Collapse SubdiscussionOvi Parasca
Ovi Parasca
Jan 2, 2018 Jan 2 at 6:24pm
Manage Discussion Entry
The For Each method, this method iterates through an array returning each element regardless of type. For Each (or just For in some languages) is useful when needed to change every or most elements in an array. I often times debate between a for each and enumeration, i use the latter when i need the index as well.

A Higher-Order Function is a function that either takes in another function or returns a function itself. I find higher-order function very useful, but don't use them too often in Objective-C/Swift, but i've found that it comes very handy when needing to use recursion. I don't think i have any questions from the reading, just would like to to hopefully see a few more realistic examples of a higher-order function in a class demo.

 Reply Reply to Comment
Collapse SubdiscussionRyan Johnson
Ryan Johnson
Jan 7, 2018 Jan 7 at 2:38pm
Manage Discussion Entry
I second your motion for more realistic examples of higher-order functions in class demos. 

 Reply Reply to Comment
Collapse Subdiscussiondtcomer@gmail.com
dtcomer@gmail.com
Jan 2, 2018 Jan 2 at 6:40pm
Manage Discussion Entry
Still trying to get through postgres and sql

Not understanding higher order functions except as it relates to calculus and the mathematical realm. 

Not understanding as a computer function.

 Reply Reply to Comment
Collapse SubdiscussionIxius Procopios
Ixius Procopios
Jan 3, 2018 Jan 3 at 2:08pm
Manage Discussion Entry
Functions that operate on other functions, either by taking them as arguments or by returning them are called higher order functions.

Map: Transforms an array by apply a function to all of its elements and building a new array from the returned values. The new array will have the same length as the input array, but it's content will have been changed. 

 

 

 

 

 Reply Reply to Comment
Collapse SubdiscussionEric Cobb
Eric Cobb
Jan 4, 2018 Jan 4 at 1:05pm
Manage Discussion Entry
Higher order functions play off of other functions whether they use them as values or return them. 

I'm still grasping the concept but have no pressing questions at this time. There are some methods that make sense but most of them I have to reread to understand them. 

 Reply Reply to Comment
Collapse SubdiscussionRonnie Lewis
Ronnie Lewis
Jan 6, 2018 Jan 6 at 4:41am
Manage Discussion Entry
Explain one array method that you understand.

I think the most straightforward method is reverse() which simply reverses the items in an array.

What is the meaning of the phrase "higher order function"?

I think of higher order functions as the parent function, it's the function that encompasses the other functions.

What is one question you have from the readings?

It's going to take a lot of practice to know when to use certain array methods, but what are some good ways of spotting them?

 Reply Reply to Comment
Collapse SubdiscussionRyan Johnson
Ryan Johnson
Jan 7, 2018 Jan 7 at 2:11pm
Manage Discussion Entry
Explain one array method that you understand.

The .filter function, similar to forEach, works to remove specific data from an array but displays the requested data in a separate array without affecting the original array's contents.

What is the meaning of the phrase "higher order function"?

Higher order functions are functions that operate on other functions and are named for the mathematical approach as in order of operations and using information from other sources to produce to secondary result.

What is one question you have from the readings?

Still struggling to grasp Functional Programming as a concept. I understand the components that are contained in the concept (map, filter, reduce, etc...) but how to define the difference between what we have been learning and functional programming I'm still struggling with.

 Reply Reply to Comment
Collapse SubdiscussionCody Green
Cody Green
Jan 7, 2018 Jan 7 at 9:53pm
Manage Discussion Entry
the filter makes a lot of sense to me being able to filter an array and get rid of anything that doesnt pass a test 

a higher order function takes in one or more functions as arguments, or returns a function as a result. no questions yet just trying to grind all this into my brain.

 Reply Reply to Comment
Collapse SubdiscussionDambergN
DambergN
Jan 11, 2018 Jan 11 at 12:27pm
Manage Discussion Entry
Higher functions are basically refactored code that take up less lines but perform the same function.  Like the reading said it is more complicated and leaves more room for bugs to hide, however refactoring code into these higher functions increase speed and efficiency.  I wish there was a way to write out code no re-factored to make sure everything works, then let another program refactor it for you after the fact.  That would just be a personal preference.  It would also be neat if you wrote some higher functions and could have an interpreter insert the code in its complete form so you could see it do its work and troubleshoot.

 Reply Reply to Comment
Collapse SubdiscussionAaron Bruce
Aaron Bruce
Jan 14, 2018 Jan 14 at 3:47pm
Manage Discussion Entry
Higher Order Function: Takes in function(s) as arguments

                                      Returns a function as a result

 

Array methods, such as document.getElementById() are used to select a single element from an array of elements. This is helpful when trying to isolate and compare/render only certain parts of an array. 

 Reply Reply to Comment
Collapse SubdiscussionBrandon Buchholz
Brandon Buchholz
Jan 16, 2018 Jan 16 at 2pm
Manage Discussion Entry
Explain one array method that you understand.
The map method which takes an array, and applies a function to each item in the array and returns a new array with the mutated values.
 

What is the meaning of the phrase "higher order function"? 
Higher order functions take in other functions and uses them as arguments. It makes code cleaner, and more readable as well. They also allow the use of abstract over actions, not just values.
 Reply Reply to Comment
Collapse SubdiscussionMitchel Hall
Mitchel Hall
Yesterday Jan 25 at 3:24pm
Manage Discussion Entry
The forEach method feels to be the most self-explanatory. 

From what I understand, higher order functions are functions that are used by other functions. They can return the other function or take in the other function as an argument. 

Read
https://devcenter.heroku.com/articles/how-heroku-works  (Essential)

https://devcenter.heroku.com/articles/getting-started-with-nodejs#introduction : 

Essential sections: "Intro" thru "View Logs", inclusive;
Essential section for lab work: "Define Config Variables"Link 

https://apprenda.com/library/paas/iaas-paas-saas-explained-compared/

 

https://en.wikipedia.org/wiki/List_of_HTTP_status_codes

Collapse SubdiscussionArthur Allen
Arthur Allen
Jan 1, 2018 Jan 1 at 5:26pm
Manage Discussion Entry
Heroku is launched from Git.  You can monitor processes of your application on Git by looking at logs created by Heroku.

In my case, I had to use "winpty heroku login" to deploy Heroku, and I had to Google the error message I got to get that option.

 Reply Reply to Comment
Collapse SubdiscussionAlicia Lycan
Alicia Lycan
Jan 4, 2018 Jan 4 at 9:33am
Manage Discussion Entry
Heroku manages app deployments with Git, to deploy your app to Heroku, use the git push command to push the code from your local repository's master branch to your heroku remote.

The console command to deploy from Git to Heroku is: git push heroku master.

 Reply Reply to Comment
Collapse SubdiscussionAmber Kim
Amber Kim
Jan 4, 2018 Jan 4 at 8:13pm
Manage Discussion Entry
Looking forward to getting Heroku working with git!

 Reply Reply to Comment
Collapse SubdiscussionChris Lesesne
Chris Lesesne
Jan 4, 2018 Jan 4 at 9:45am
Manage Discussion Entry
Heroku is an application deployment platform that allows you to provide source code and dependencies to build the application. It also establishes a remote repository that is associated with your local Git repository in order to deploy the application.

console command: git push heroku master

 Reply Reply to Comment
Collapse SubdiscussionTrevor Dobson
Trevor Dobson
Jan 4, 2018 Jan 4 at 2:12pm
Manage Discussion Entry
Heroku uses Git to transport the code to Heroku.  Git push heroku master is the command used to deploy from git to heroku.  

 Reply Reply to Comment
Collapse SubdiscussionDarcy Knore
Darcy Knore
Jan 4, 2018 Jan 4 at 4:07pm
Manage Discussion Entry
1) How are Heroku and Git used in the deployment process?

The Heroku platform uses Git as the primary means for deploying applications.  When you create an application on Heroku, it associates a new Git remote, typically named heroku, with the local Git repository for your application.
2) What console command is used to deploy from Git to Heroku?

$ git push heroku master

 Reply Reply to Comment
Collapse SubdiscussionTiger Hsu
Tiger Hsu
Jan 4, 2018 Jan 4 at 4:46pm
Manage Discussion Entry
"$git push heroku master " is the command to deploy Heroku from Git, I still have not touched heroku yet but I have only downloaded it. Heroku seems like a very deep because it can host a web application and have various different add-on. One add on that I found most interesting was the post mail which allows for a add-on of a exchange.email server to an application if a user wishes to attach that type of service.

 

The link between Heroku and Git is the simply that Git is the local machine and the Heroku handles the live production deployment above all else.

 Reply Reply to Comment
Collapse SubdiscussionIxius Procopios
Ixius Procopios
Jan 4, 2018 Jan 4 at 4:53pm
Manage Discussion Entry
It's not often I say this but I'm pretty lost here.

I've installed Heroku but it threw an error:

! Login is currently incompatible with git bash/Cygwin/MinGW

 Reply Reply to Comment
Collapse SubdiscussionAyanle (ah-yan-leh)
Ayanle (ah-yan-leh)
Jan 4, 2018 Jan 4 at 6:15pm
Manage Discussion Entry
Given what you've read so far, how are Heroku and Git used in the deployment process?

Git would contain the files and Heroku would essentially be the interface between your user and the files. Heroku presents your work to the user as a webpage.

What console command is used to deploy from Git to Heroku?

git push

 

 Reply Reply to Comment
Collapse Subdiscussiondtcomer@gmail.com
dtcomer@gmail.com
Jan 4, 2018 Jan 4 at 6:21pm
Manage Discussion Entry
Not sure what a polyglot is or what it means. I have dabbled with something that Kony developed to do multi platform mobile app development. Not sure if this is referring to the same thing or not

I'm thinking GIT PUSH HEROKU MASTER is the command you would use to deploy from Git to Heroku

 Reply Reply to Comment
Collapse SubdiscussionOvi Parasca
Ovi Parasca
Jan 4, 2018 Jan 4 at 6:26pm
Manage Discussion Entry
Heroku uses Git to deploy the code via it's own heroku branch. You can use GitHub and Heroku together for continuous integreation, such as push to the heroku branch can spin off new builds. You can use git push heroku master to deply to the heroku master branch.

 Reply Reply to Comment
Collapse SubdiscussionAmber Kim
Amber Kim
Jan 4, 2018 Jan 4 at 8:12pm
Manage Discussion Entry
You can use Git to deploy your app directly to Heroku.

git push heroku master

is the command needed to deploy from Git to Heroku.

 Reply Reply to Comment
Collapse SubdiscussionDevin Cunningham
Devin Cunningham
Jan 5, 2018 Jan 5 at 2:33pm
Manage Discussion Entry
Installed and running! The setup and demo seemed pretty straightforward.

 

I can't get heroku to run through gitbash so I have to use cmd.

 Reply Reply to Comment
Collapse SubdiscussionRafael Malave
Rafael Malave
Jan 7, 2018 Jan 7 at 2:18pm
Manage Discussion Entry
Heroku integrates with GitHub to make it easy to deploy code living on GitHub to apps running on Heroku and can be used as a continuous integration tool.

We can push to heroku with 'git push heroku master'

 Reply Reply to Comment
Collapse SubdiscussionCody Green
Cody Green
Jan 7, 2018 Jan 7 at 9:57pm
Manage Discussion Entry
git push heroku master is the command to deploy going through the demo felt fine but the process of doing it was a little tricky for a minute having to readjust my thinking as to where things are in the mvc that way.

 

 Reply Reply to Comment
Collapse SubdiscussionAriel Altaras
Ariel Altaras
Jan 7, 2018 Jan 7 at 10:28pm
Manage Discussion Entry
Git and heroku work together to deploy apps. Heroku can be linked to a git branch, and can be deployed with the command:

git push heroku <branch>
 Reply Reply to Comment
Collapse SubdiscussionRonnie Lewis
Ronnie Lewis
Jan 8, 2018 Jan 8 at 3:19am
Manage Discussion Entry
Given what you've read so far, how are Heroku and Git used in the deployment process?

Git and Heroku help you move your application from your local system and you can deploy code with git push

What console command is used to deploy from Git to Heroku?

git push Heroku master

 

 Reply Reply to Comment
Collapse SubdiscussionEric Cobb
Eric Cobb
Jan 8, 2018 Jan 8 at 1:30pm
Manage Discussion Entry
 The Heroku platform uses Git as the primary means for deploying applications. The console command is " git push heroku master " 

 Reply Reply to Comment
Collapse SubdiscussionDambergN
DambergN
Jan 11, 2018 Jan 11 at 12:31pm
Manage Discussion Entry
From what I can tell heroku is a hosting service.  While I understand the appeal of these types of services and have used similar ones in the past, I have been burned by them and prefer to just run my own services off of my own equipment.  In fact I am currently looking for a self hosted version of github I can use for some of my own personal projects that I don't necessarily want to be public and don't want to pay the monthly fee.

 Reply Reply to Comment
Collapse SubdiscussionRyan Johnson
Ryan Johnson
Jan 12, 2018 Jan 12 at 10:16pm
Manage Discussion Entry
How are Heroku and Git used in the deployment process?

Heroku is used as a version control system managing deployments through Git, and is used as a server platform for site testing and development.

What console command is used to deploy from Git to Heroku?

Use console command $ git push heroku master to deploy git to heroku.

 Reply Reply to Comment
Collapse SubdiscussionAaron Bruce
Aaron Bruce
Jan 14, 2018 Jan 14 at 3:51pm
Manage Discussion Entry
Github and Heroku are both used to deploy local websites so that they can be accessed remotely without having to download all the files necessary to run the same website. 

Github uses origin as it's cloud name whereas heroku uses heroku

So, after creating a heroku repo, the command in the terminal is     git push heroku branch-name      instead of the standard         git push origin branch-name

 

 Reply Reply to Comment
Collapse SubdiscussionMichael Brown
Michael Brown
Jan 15, 2018 Jan 15 at 12:14pm
Manage Discussion Entry
The commands to deploy from Git to Heroku are:

heroku init

git push heroku master

Heroku and Git work together to manage application components. Git hands the codebase while Heroku manages the application and an connected datasources without need to pull information from your local machine. Heroku can  integrate directly into Github to access the information it needs. 

 Reply Reply to Comment
Collapse SubdiscussionBrandon Buchholz
Brandon Buchholz
Jan 16, 2018 Jan 16 at 2:06pm
Manage Discussion Entry
Given what you've read so far, how are Heroku and Git used in the deployment process?
Once you install the Heroku toolbelt you can sync it with github and deploy from your master branch automatically whenever you merge branches to master. Heroku also supplies logs to see how everything is talking back and forth to see if it is connecting properly or if there is an error.
 

What console command is used to deploy from Git to Heroku?
git push heroku master
 Reply Reply to Comment
Collapse SubdiscussionMitchel Hall
Mitchel Hall
Jan 16, 2018 Jan 16 at 4:46pm
Manage Discussion Entry
Another one that will take a few times doing it to really figure it out. 


Read 12: MVC blog post, History API, Page.js Readme
17 17 unread replies. 26 26 replies.
Read
http://blog.codinghorror.com/understanding-model-view-controller/  (Context)

JS&jQ: 424-427 (History API) (Essential)

https://github.com/visionmedia/page.js  (up to the section on "Plugins") (Reference)


Collapse SubdiscussionArthur Allen
Arthur Allen
Jan 7, 2018 Jan 7 at 10:26am
Manage Discussion Entry
If I have this right: in an art analogy (for instance), the model is the idea for a piece, the view is the sketch you might make to help you work with the idea to make the final piece, and the controller is the final piece itself (probably not the brushes and canvas that help make the final piece).

I'm familiar with features, presumably made in JSON, that don't add to the history of a browsing experience.  Examples include clicking to show more content of an article or adding a comment to a comment section.  In these cases you don't want to have to click extra times to go back, so it's good that they don't add to the history path.  Why can't you just use JSON for these features and use regular HTML at other times, and then you wouldn't have to worry about constructing a browsing history with .pushState()?  I'm guessing it's because JSON offers other features besides the ones I know about.

I've been reading so much formalized instruction that one sentence stood out.  I wonder if the use of "like" here was intentional: "If you're doing selective binding you'll like want to pass { click: false } to specify this yourself."  (Maybe they meant "likely".  If the page was still being updated, I could have pushed up a suggestion myself.)

 Reply Reply to Comment
Collapse SubdiscussionAmber Kim
Amber Kim
Jan 7, 2018 Jan 7 at 1:55pm
Manage Discussion Entry
Relating MVC to art is something I haven't thought about. :)

 Reply Reply to Comment
Collapse SubdiscussionTiger Hsu
Tiger Hsu
Jan 7, 2018 Jan 7 at 11:46am
Manage Discussion Entry
The model view controller ..

I had seen this MVC pseudo code somewhere and it was really neat to look at explaining how the Model View Controller is written as a web development application.

 

***https://yourherokuapp.com/profile1***

//routes

users/profile:id = users.profile.1

 

////controllers////

UsersClass tiger {

function get profile (tiger)

renderView('users/profile', tiger)

}

 

///models///

function {

data = this.data.get (SELECT * from USERS where id = 'tiger' )

render data;

};

 

///view///

profile {

<h1>profile:tiger </h1>

{{ user info}}

}

 

 Reply Reply to Comment
Collapse SubdiscussionAmber Kim
Amber Kim
Jan 7, 2018 Jan 7 at 1:53pm
Manage Discussion Entry
Models house all the data you need for something, View displays this data, and Controller acts like the go-to or manager between the two, telling each how they need to change and where they need to go when things change or need to change for both the Model and the View.

Is page.js still widely used even though it hasn't been maintained for years?

 Reply Reply to Comment
Collapse SubdiscussionArthur Allen
Arthur Allen
Jan 7, 2018 Jan 7 at 5:16pm
Manage Discussion Entry
They do link to other resources that can be used instead.

 Reply Reply to Comment
Collapse SubdiscussionAmber Kim
Amber Kim
Jan 7, 2018 Jan 7 at 6:40pm
Manage Discussion Entry
Awesome :)

 Reply Reply to Comment
Collapse SubdiscussionChris Lesesne
Chris Lesesne
Jan 7, 2018 Jan 7 at 11:49pm
Manage Discussion Entry
Model - where data/information is stored

View - displays data/information to a user based on their inputs/requests

Controller - serves as the connection/communicator between the model and the view; interprets requests from the user, obtains and processes the appropriate data held in the model, then delivers the results back to the view for the user

- The History API's '.pushState()' method adds entries (url's) to the history object, which keeps track of visited/revisited sites within a browser.

- What type of information is usually stored/passed into the 'state'  parameter of the .pushState() method?

 Reply Reply to Comment
Collapse SubdiscussionAlicia Lycan
Alicia Lycan
Jan 8, 2018 Jan 8 at 11:39am
Manage Discussion Entry
Model = the knowledge. A structure of objects; one part of the model is focused on corresponding with the data structure and the other part focuses on the owner's creative goal for the end user.

View = a visual representation of its model. Highlights certain parts of the model and hides others.

Controller = a link between the user and the system.

The History API.pushState() method allows the user to update the browser history stack using the pushState() method when using Ajax to load information. Information can be added to the history object when the Ajax request is made, and the user can be shown the right content when they press back or forward buttons.

How do we add the functionality to add information and access the history object in our book application?

 Reply Reply to Comment
Collapse SubdiscussionIxius Procopios
Ixius Procopios
Jan 8, 2018 Jan 8 at 12:49pm
Manage Discussion Entry
Url's no longer represent static objects on the server, they now represents the state of the application

Js knows how to render given that state

 

The url can be manipulated with pushstate()

It takes 3 parameters, the user history, the string that's the title of the page, and the actual url you want to display.

 

 

 Reply Reply to Comment
Collapse SubdiscussionTrevor Dobson
Trevor Dobson
Jan 8, 2018 Jan 8 at 1:14pm
Manage Discussion Entry
MVC breaks the web app down into 3 parts, the model is the skeleton of the app, its the basic layout.  The View is the styling, the user interface.  The Controller connects the two and is the brains behind it all.

the hisotory.pushtate() adds an entry to the history object.  it can take in 3 parameters; state, title, url.  Using this allows the user to use the forward and back buttons and they will see the correct content.

 Reply Reply to Comment
Collapse SubdiscussionDevin Cunningham
Devin Cunningham
Jan 8, 2018 Jan 8 at 3:42pm
Manage Discussion Entry
Model - The base structure of the website. The HTML code without any styling.

 

View - The way it is styled with CSS. The skin.

 

Controller - The web browser controls all the files that are sent to it. JS CSS HTML etc...

 

API .pushState() lets the browser create a history even when the URL is not updating/not loading a new page.

 Reply Reply to Comment
Collapse Subdiscussiondtcomer@gmail.com
dtcomer@gmail.com
Jan 8, 2018 Jan 8 at 4:14pm
Manage Discussion Entry
The model is the scenario you are trying to replicate

The view is the developers medium to present the replication to a user(s)

The controller is the the mechanism the developer uses to change the scenario into a form the view can present

The History API .pushState() method seems to allow for a way to modify a current history entry instead of creating a new one

 

 Reply Reply to Comment
Collapse SubdiscussionAriel Altaras
Ariel Altaras
Jan 8, 2018 Jan 8 at 5:23pm
Manage Discussion Entry
The Model is the content - for example HTML that holds the structure of the web page or a database that holds the content.

The View is what the user sees - the visual representation.

The Controller is what enables the user to see the model - it creates the view. In terms of web applications this would be the browser.

 

The History API .pushState() helps allow the back and forward browser buttons to function by feeding URLs to the browser history when AJAX calls are used. This is because the URL isn't always changed, so browser back/forward buttons wouldn't work right.

 Reply Reply to Comment
Collapse SubdiscussionOvi Parasca
Ovi Parasca
Jan 8, 2018 Jan 8 at 6:40pm
Manage Discussion Entry
The MVC is a very common design pattern in software development, it's the most common design pattern in iOS development. The Model contains the data essentially, the View is the CSS, and the Controller connects the view and the data, essentially the controller does the main logic. 

Pushstate() added a new page to the history queue, without reloading the page or changing the html url, but it does let you then go back and forward in the browser. I was confused about pushState() and i found an example online and made it clearer for me.

 

Here is the example, click the boxes then try to go back/forward in the browser.

http://jsfiddle.net/janfoeh/2SCbv/show/light/

 Reply Reply to Comment
Collapse SubdiscussionEric Cobb
Eric Cobb
Jan 8, 2018 Jan 8 at 6:57pm
Manage Discussion Entry
Model View Control is a software architectual pattern that uses a given application to connect three parts. I have no questions at this point. 

 Reply Reply to Comment
Collapse SubdiscussionRafael Malave
Rafael Malave
Jan 8, 2018 Jan 8 at 8:43pm
Manage Discussion Entry
The model is the representation of information, a view is the visual presentation of that information and the controller is like the brain that decides how the information should be changed or modified by the model and how to be visually presented by the view.

With the pushState() method we can do things like change the URL in the browser without triggering a page refresh, and also listen for when a user presses the back button.

 Reply Reply to Comment
Collapse SubdiscussionRonnie Lewis
Ronnie Lewis
Jan 9, 2018 Jan 9 at 4:05am
Manage Discussion Entry
I think the best description of MVC was explained best in A Classic MVC blog post. The image paired with the brief description below it really cleared things up for me.   

Model

The HTML is the skeleton and it communicates information to the reader with text.

View

The CSS adds visual style to the content. 

Controller

The browser is responsible for combining and rendering the CSS and HTML into a set.

What does the History API .pushState() method accomplish?

The .pushState() method adds an entry to the history object.

What is one question you have from the readings?

It seems like SmallTalk was trying to simplify coding a long time ago. Do you think JS used some of the same ideas?

 

 Reply Reply to Comment
Collapse SubdiscussionDarcy Knore
Darcy Knore
Jan 9, 2018 Jan 9 at 4:18pm
Manage Discussion Entry
1. Briefly explain the meanings of Model, View, and Controller. 
In short, Model = HTML, View = CSS, Controller = Browser.
2. What does the History API .pushState()method accomplish?
Adds an entry to the history object.
No real questions.. trying to wrap my head around history API, and pushstate....
 Reply Reply to Comment
Collapse SubdiscussionCody Green
Cody Green
Jan 9, 2018 Jan 9 at 8:41pm
Manage Discussion Entry
The MVC pattern, in a nutshell, is this:

The model represents the data, and does nothing else. The model does NOT depend on the controller or the view.

The view displays the model data, and sends user actions (e.g. button clicks) to the controller. The view can:

be independent of both the model and the controller; or

actually be the controller, and therefore depend on the model.

The controller provides model data to the view, and interprets user actions such as button clicks. The controller depends on the view and the model. In some cases, the controller and the view are the same object.

 

History API gives developers the ability to modify a website's URL without a full page refresh.

 

no questions at the moment

 Reply Reply to Comment
Collapse SubdiscussionBrandon Buchholz
Brandon Buchholz
Jan 10, 2018 Jan 10 at 4:04pm
Manage Discussion Entry
Briefly explain the meanings of Model, View, and Controller. 
Model is the skeleton(html) that the app is built on, the View incliudes items like CSS that give apps styling, and the Controller is what blends together everything for display.
What does the History API .pushState() method accomplish?
It allows you to store history. Each tab or window in the browser keeps its own history of pages you have viewed.
 Reply Reply to Comment
Collapse SubdiscussionDambergN
DambergN
Jan 11, 2018 Jan 11 at 12:41pm
Manage Discussion Entry
Models are like a blueprint of information, View is the representation of the model, Controller is the connector between Models and View to determine what Models to be sent to the View.  History API .pushState() allows a page to be updated with new information without having to re-load all the data from the page.  One thing I am curious about, I understand that it makes navigating a page faster, but what about the initial loading of the page?  Does it still have to load all of the content for that page before it is view able, and couldn't this be taken to far?

 Reply Reply to Comment
Collapse SubdiscussionAaron Bruce
Aaron Bruce
Jan 14, 2018 Jan 14 at 4pm
Manage Discussion Entry
MODEL: queries using SQL commands to access table / database data.

CONTROLLER: receives requests from the VIEW and send directions to the MODEL, then receives results from the MODEL and sends whatever result data it was given to the VIEW as a response.

VIEW: is how the user interacts with the app and how the user will see the app design

.pushState() method, along with popState() method allow websites to not have to use redundant data, like for header, footer, etc.

 

Add event listeners that listen for a specific event such as click, hover etc.
When the above event is triggered, use XML Http Request to grab the new content.
The new content will then be used to overwrite the old content.
Use the pushState() method to update the URL.
 Reply Reply to Comment
Collapse SubdiscussionRyan Johnson
Ryan Johnson
Jan 16, 2018 Jan 16 at 5:12pm
Manage Discussion Entry
I like your break down of the .pushState() method into your four points. Thank you.

 Reply Reply to Comment
Collapse SubdiscussionMichael Brown
Michael Brown
Jan 15, 2018 Jan 15 at 12:32pm
Manage Discussion Entry
MVC is the separation of a web application into three components. The View referes to what the end user sees, the Model is the data, and the Controller controls the flow of information via requests and responses between both the View and Model.

.pushState() creates an entry in the history in the history object

 Reply Reply to Comment
Collapse SubdiscussionRyan Johnson
Ryan Johnson
Jan 16, 2018 Jan 16 at 5:10pm
Manage Discussion Entry
Briefly explain the meanings of Model, View, and Controller (MVC). 

The MVC is a pattern of architecture for creating user interfaces by dividing an application into three interweaving parts.

What does the History API .pushState() method accomplish?

This method allows for adding and modifying entries in the history of existing code, by taking in the parameters of state object, title and URL call access site content.

What is one question you have from the readings?

I need to struggle with this in the code to better understand it and ask questions.

Edited by Ryan Johnson on Jan 16 at 5:13pm
 Reply Reply to Comment
Collapse SubdiscussionMitchel Hall
Mitchel Hall
Yesterday Jan 25 at 3:32pm
Manage Discussion Entry
Model View Controller methodology allows for the separation of concerns to give a recognizable structure to the codebase and to make it easier to create and modify. The Model represents the data used by the application, the view is how that data is presented to the user of the application, and the controller governs what data needs to be retrieved from the model to be presented to the user in the view. 

 

I guess my question is I read documentation for the .pushState() method and I am still not sure what it does. Hopefully my classmates have a better handle on it. 

Discuss: Project Ideas & APIs
19 19 unread replies. 25 25 replies.
Discuss

Amber Kim
Jan 7, 2018 Jan 7 at 2:19pm
Manage Discussion Entry
Alicia and I are looking at an app that will display avalanche risk information for users. The model will come from the NWAC? website but we are still not sure whether or not they have API's for public use.

Another idea I am thinking of is to build a lead generation app that will connect to a mailing list API like those of MailChimp's or Mailerlite. Both companies have good documentation on their websites on how to connect your app with theirs. The first part would probably be an intake form that updates a mailing list's group and then the second part is displaying this group and relevant information in the app. I am unsure if this idea is good for the 301 project because it may be displaying information (the second part) that is normally password protected which we haven't learned to do so.

 Reply Reply to Comment
Collapse SubdiscussionAmber Kim
Amber Kim
Jan 8, 2018 Jan 8 at 6:43pm
Manage Discussion Entry
Update: I emailed NWAC and they were very generous and created a student API, documentation, and access for us.

Edited by Amber Kim on Jan 8 at 6:43pm
 Reply Reply to Comment
Collapse SubdiscussionCody Green
Cody Green
Jan 8, 2018 Jan 8 at 3:10pm
Manage Discussion Entry
i think a bar crawl builder would be fun you put in your address and what you want to drink possibly or other filters that we could get from the yelp API and get a mapped out plan from google maps API and maybe if possible have the API for lyft or uber to get a quote a ride at the end of your crawl if that is possible still trying to figure that one out. i also think it would be fun to put a BAC calculator on the site so you can see how much you could have before you go out but that's just for fun really would need fine print under it that said we wouldnt be liable for anything if i put that in. 

 

i think that could be a fun project.

 Reply Reply to Comment
Collapse SubdiscussionAmber Kim
Amber Kim
Jan 8, 2018 Jan 8 at 6:50pm
Manage Discussion Entry
Sounds like a fun app. Would it be hard to work with so many APIs?

 Reply Reply to Comment
Collapse SubdiscussionCody Green
Cody Green
Jan 9, 2018 Jan 9 at 5:58pm
Manage Discussion Entry
no idea. possibly.

 

 Reply Reply to Comment
Collapse SubdiscussionCody Green
Cody Green
Jan 9, 2018 Jan 9 at 9:04pm
Manage Discussion Entry
i also thought an app that took in information about radio stations from the yes API to determine which stations play the widest variety of music compared to which stations play the same song every hour on the hour.

 

 Reply Reply to Comment
Collapse SubdiscussionCody Green
Cody Green
Jan 9, 2018 Jan 9 at 9:07pm
Manage Discussion Entry
yes api might be dead

have to find another

 Reply Reply to Comment
Collapse SubdiscussionArthur Allen
Arthur Allen
Jan 13, 2018 Jan 13 at 5:17pm
Manage Discussion Entry
I have no idea.  I founded a team in 201, though full control was taken away from me.  I could still propose the same, unfulfilled game idea again, but I can't even get the base Columns code to work in JavaScript, and I don't think it would make much use of the ideas we learned in this class.  I'm hoping someone else in the team has a better idea.

 Reply Reply to Comment
Collapse SubdiscussionChris Lesesne
Chris Lesesne
Jan 14, 2018 Jan 14 at 12:30am
Manage Discussion Entry
My personal interest in long-term investing, and the very cool discussions around trading/cryptocurrency that between our classmates, have motivated me to build an application that would inspire those who are curious, yet hesitant about investing. The goal would be to help introduce an individual to the initial process of investing in our digital/information era, and recommend stocks based on their financial goals, personal interests, spending habits, and risk tolerance. The model could include real-time stock quote data, as well as current consumer buying trends, that would be used by the controller to calculate the best fitting stock choices and deliver the results to the view for the user. Examples of a useful APIs for this project would be Alpha Vantage API for equity data, Amazon's Product Advertising API for e-commerce consumer trend data, and/or eBay's API.

 Reply Reply to Comment
Collapse SubdiscussionAlicia Lycan
Alicia Lycan
Jan 15, 2018 Jan 15 at 1:30pm
Manage Discussion Entry
I really like this idea Chris, there's so much you could do with something like that, I'd use it!

 Reply Reply to Comment
Collapse SubdiscussionDevin Cunningham
Devin Cunningham
Jan 14, 2018 Jan 14 at 2:09pm
Manage Discussion Entry
An idea I had is a workout app for friends. On this app, you could display your schedule with info on where/when/what you are working out. Your friends could go to the app and check to see if they schedule lines up with yours and if so, they could "book" time to workout with you. This app could also have a GPS function so you could see how far out your friend is from the gym so you can meet at the same time. You wont have to text your friends anymore asking them where/when/what they are working out anymore!

 Reply Reply to Comment
Collapse SubdiscussionAriel Altaras
Ariel Altaras
Jan 14, 2018 Jan 14 at 11:15pm
Manage Discussion Entry
I'm wondering if Google Calender or similar has an API that could be useful for this app, so you could make a workout calendar and then link it up so your friends could see when you scheduled a workout.

 Reply Reply to Comment
Collapse SubdiscussionDevin Cunningham
Devin Cunningham
Jan 15, 2018 Jan 15 at 9:42am
Manage Discussion Entry
That would be awesome! Google calendar also links with ios calendar so schedule workouts would show up on Apple iPhones and watches.

 Reply Reply to Comment
Collapse SubdiscussionTiger Hsu
Tiger Hsu
Jan 14, 2018 Jan 14 at 6:38pm
Manage Discussion Entry
I am not 100 percent sure of what I want to do on a project, but I want have a project that is really fun and colorful. I think one API that I might want to use is the TCG for the Pokemon more so for an image search. I'm not sure how to utilize machine learning but It might be a fun project to incorporate as well.

Edited by Tiger Hsu on Jan 14 at 6:40pm
 Reply Reply to Comment
Collapse SubdiscussionAriel Altaras
Ariel Altaras
Jan 14, 2018 Jan 14 at 11:10pm
Manage Discussion Entry
I don't really have any concrete ideas for a project, but I do know that one of my favorite websites, ravelry.com, has an API (Links to an external site.)Links to an external site., so I might have fun doing something with that. It has a huge database of patterns, and one idea would be to create an app that recommends patterns based on what the user has already knit / crocheted. I'm not sure exactly what data is accessible through the API, so I'd have to do a bit more research. But one idea is to base this on projects made by other users that are similar to the user. So if Jane and Bob have knit a bunch of the same patterns, Jane may like other patterns that Bob has knit.

 Reply Reply to Comment
Collapse SubdiscussionDarcy Knore
Darcy Knore
Jan 15, 2018 Jan 15 at 11:38am
Manage Discussion Entry
a blog creating app... sort of like my blogspot? i know there are already products out there, but seems like it would be fun to learn how to do and have in repo.

 Reply Reply to Comment
Collapse SubdiscussionAlicia Lycan
Alicia Lycan
Jan 15, 2018 Jan 15 at 1:29pm
Manage Discussion Entry
I'd like to build an app with the NWAC (Northwest Avalanche Center) API, scraping their data off their site and sharing with the user in a more responsive, interactive meaningful way. For example, rather than looking at a spreadsheet the app could let you know what the conditions today are and let them save their favorite mountains/ski areas. The model might be the temperature and precipitation of each region? Who trusts the resorts telemetry data? Not me, so I think others might benefit from this app too! We already have the API so that's not an issue, just need to decrypt the key, looking forward to learning that.

 Reply Reply to Comment
Collapse SubdiscussionAyanle (ah-yan-leh)
Ayanle (ah-yan-leh)
Jan 15, 2018 Jan 15 at 4:20pm
Manage Discussion Entry
What ideas do you have for projects?

I really like the idea of having something that I can use for my work. Team collaboration tools like 'Slack' would be a good start.

What would your model be that you can control and update the view with?

I don't understand this question. Is this in the context of a project idea? If so, there would be several models: individual user and group.

What API(s) could you use to make this a reality?

idk

 

 Reply Reply to Comment
Collapse SubdiscussionTrevor Dobson
Trevor Dobson
Jan 15, 2018 Jan 15 at 4:45pm
Manage Discussion Entry
I would like to do an app for micro brews.  I would like it to recommend beers based on your preferences.  I could use the BreweryDB API.  

 Reply Reply to Comment
Collapse SubdiscussionOvi Parasca
Ovi Parasca
Jan 15, 2018 Jan 15 at 6:51pm
Manage Discussion Entry
I was thinking about doing something with the Pokemon API, along with integrating with Firebase.Auth() to perhaps keep a list of users and maybe their list of pokemon they've caught, badges won/attempted, etc. I think anyone who has played any pokemon games in the past may enjoy these api's and if the project can be expanded on maybe add a battle system?

 Reply Reply to Comment
Collapse SubdiscussionBrandon Buchholz
Brandon Buchholz
Jan 16, 2018 Jan 16 at 2:33pm
Manage Discussion Entry
What ideas do you have for projects?
I have an idea for an app that alerts you when you are shopping at a brick and morter store  to special discounts/or promotions based on your GPS location and proximity within the store. It would also have a database that could be updated with discounts that are for smaller groups i.e. military,senior citizens,AAA, etc.
What would your model be that you can control and update the view with?
It would need GPS to be enabled to use google maps. It would need a min proximity limit to be set up as well as a timer so that it would only ping when certain conditions are met, otherwise you would be constantly alerted while traveling.
What API(s) could you use to make this a reality?
Google Maps API
 Reply Reply to Comment
Collapse SubdiscussionEric Cobb
Eric Cobb
Jan 16, 2018 Jan 16 at 5:18pm
Manage Discussion Entry
I currently do not have any valuable ideas for projects. I was thinking we would most likely extend on our 201 project, but who knows. 

 Reply Reply to Comment
Collapse SubdiscussionRafael Malave
Rafael Malave
Jan 17, 2018 Jan 17 at 6:21pm
Manage Discussion Entry
A bit late. My team came up with a cryptocurrency site.

 Reply Reply to Comment
Collapse SubdiscussionMitchel Hall
Mitchel Hall
Yesterday Jan 25 at 4:41pm
Manage Discussion Entry
My idea would be to make a list of shows that will be removed from streaming sites and calculate how much time it would take to watch each of the shows the user is interested in before the show or movie is removed to see if it is even possible. Learned however that Netflix has their API locked down.

 

 Reply Reply to Comment
Collapse SubdiscussionAaron Bruce
Aaron Bruce
Yesterday Jan 25 at 7:54pm
Manage Discussion Entry
pokedex app!   Yeah yeah I'm submitting this on the 2nd to last day of project week lol.

Just for the points and it's an easy submission
