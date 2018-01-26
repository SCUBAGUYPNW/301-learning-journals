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

There is also a website https://jquery.com/ (Links to an external site.)Links to an external site. that I've used for

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
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for...in (Links to an external site.)Links to an external site.

 

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



