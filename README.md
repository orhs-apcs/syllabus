# AP Computer Science Syllabus

* **Course Website:** [APCS](https://sites.google.com/site/sallenorhs/home/ap-computer-science)
* **Instructor:** Stephanie Allen, [sallen@eduhsd.k12.ca.us](mailto:sallen@eduhsd.k12.ca.us)
* **Need help?**
    * Look through and create [issues](https://github.com/advanced-js/syllabus/issues)
    * Office Hours during break or lunch M-F
    * [Email](mailto:sallen@eduhsd.k12.ca.us) for 1-on-1 help, or to set up a time to meet

## Course Description

AP Computer Science A emphasizes object-oriented programming methodology using Java, with a concentration on problem solving and algorithm development and is meant to be the equivalent of a first semester college-level course in Computer Science. The course is designed for students with no prior computing experience.  

Students will be learning all levels of the Java language including basic syntax, declaration of variables, if-else statements, for, while, and do-while loops, library classes, and GUI (graphical user interface) tools. This course will be especially helpful to students contemplating careers in computer science, business, statistics, insurance and engineering. Students may earn college credit by successfully passing the Computer Science Advanced Placement Exam in May. 

## Class Expectation

* Come prepared (Arrive on time, have all assignments completed. Use bathroom before entering classroom.)
* Be polite (Speak respectfully to teachers and students.  Do not disrupt another student’s learning.)
* Be productive (Complete all warm-ups and assignments on time. Be an active learner. Take notes.  No distractions. No sleeping.)
* No food or drinks are allowed in the lab at any time.
* Follow all Oak Ridge rules including the [Honor Code](#APCS Honor Code).
* Unless otherwise instructed by the teacher, students shall turn off, not use, and keep out of sight cell phones and other signaling devices during the class period. Furthermore, any listening, recording, or videotaping of peers, teachers, or visitor to the classroom without prior consent is prohibited. Consequences follow ORHS policy as stated in student handbook

## APCS Honor Code

AP Computer Science can be hard.  Object-oriented concepts can take time for some students to grasp. Some students in computer science will submit work that is not their own. In order to be successful in this class you must try to figure out the concepts by experimenting with your programs.  Do not be afraid see what will happen if you write your code in a particular way.  That is how you will learn.  By copying other’s code you are shortchanging your own learning and undermining the atmosphere of trust in our class.  

**You are expected to submit your own work in this course.** 
In particular, attempting to take credit for someone else’s work by turning it in as your own constitutes plagiarism, which is a serious violation of the Oak Ridge High School academic integrity policy.  This does not mean that any discussion of assignments is somehow a violation of the integrity policy. In computer science courses, it is usually appropriate to ask others for hints and debugging help or to talk generally about problem-solving strategies and program structure
 
**You must not share actual program code with other students.** 
In particular, you should not ask anyone to give you a copy of their code or, conversely, give your code to another student who asks you for it. Similarly, you should not discuss your algorithmic strategies to such an extent that you and your collaborators end up turning in exactly the same code. Discuss ideas together, but do the coding on your own. 

**You must be prepared to explain any program code you submit.** 
Sometimes students change their code by rewriting comments, changing variable names, and so forth, to disguise the fact that their work is copied from someone else. If you wrote the code yourself, you will be able to explain it.  I may ask you to modify a particular method or explain an algorithm you were expected to create.  If you are unable to do this, no credit will be given for the assignment. 

## Computer Security Policy

* Computers in our lab have a security software program. This software disables many of the features you might find common to other computers, including any home computer you might have. The software also monitors and records all use by the student and may be used for disciplinary purposes.
* Do not attempt to defeat or disable the security software. 
* Do not change the desktop environment, which includes the color, fonts, video display mode, screen saver, icon arrangement, and especially the wallpaper. 
* Do not download files onto your computer's hard drive without specific permission from your instructor. 
* Do not install any programs on your computer. 
* Do not delete or rename any file on your computer's hard drive or any other school computer unless it is one that you created. 
* Do not copy any software on any school computer for your personal use. This is illegal. If you want a copy, buy your own. 

### Requirements

These apply to real life, as well.

* [Travis CI](https://docs.travis-ci.com/) build should pass, which includes:
    * All HTML files should pass [W3C Markup Validation](http://validator.w3.org).
    * All written JS should pass [JSHint](http://jshint.com).
* Must apply "good programming style" learned in class
    * Functions should be "short" (see [Sandi Metz's rules for developers](https://robots.thoughtbot.com/sandi-metz-rules-for-developers)).
    * Optimize for readability.
        * ["Programs must be written for people to read, and only incidentally for machines to execute." -Harold Abelson](https://www.goodreads.com/quotes/9168-programs-must-be-written-for-people-to-read-and-only)
    * Avoid using anonymous callbacks within other functions, especially if the callback is more than one or two lines.
    * For projects, use Object-Oriented Programming.
* Any borrowed code must be properly [annotated](http://documentup.com/advanced-js/syllabus#statements-on-plagiarism/instructor).
* Bonus points for:
    * [Automated tests](#test-frameworks)
    * Creativity (as long as requirements are fulfilled)

## Course Outline

### Semester 1

* [Chapter 1: Computer Systems] (https://github.com/orhs-apcs/chapter-1)
* [Chapter 2: Objects and Primitive Data] (https://github.com/orhs-apcs/chapter-2)

## Resources

### Required Reading

* [Google JavaScript Style Guide](http://google-styleguide.googlecode.com/svn/trunk/javascriptguide.xml)
* [JavaScript Garden](http://bonsaiden.github.com/JavaScript-Garden/)
* [Mozilla's Introduction to Object-Oriented Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Introduction_to_Object-Oriented_JavaScript)
* [What’s so great about JavaScript Promises?](http://blog.parse.com/learn/engineering/whats-so-great-about-javascript-promises/)
* https://twitter.com/necolas/status/291978260433219584
* http://afeld.me/nerdery/1742468

### Beginner Materials

This class assumes you are confident with this material, but in case you need a brush-up...

* Codecademy – [JavaScript](https://www.codecademy.com/learn/javascript) and [jQuery](https://www.codecademy.com/learn/jquery)
* [Eloquent JavaScript](http://eloquentjavascript.net/index.html) by Marijn Haverbeke, Chapters 1-5
* [Want to learn JavaScript in 2015?](https://medium.com/@_cmdv_/i-want-to-learn-javascript-in-2015-e96cd85ad225)
* see also – [Other Lists](#other-lists)

### Recommended Reading

* [Functional JavaScript](http://shop.oreilly.com/product/0636920028857.do) by Michael Fogus
* [Front-end Job Interview Questions](https://github.com/h5bp/Front-end-Developer-Interview-Questions) by @darcyclarke (for testing yourself)
* [JavaScript Best Practices](http://www.thinkful.com/learn/javascript-best-practices-1/)
* [JavaScript Patterns](http://shichuan.github.io/javascript-patterns/) by @shichuan (thanks @iandrewfuchs)
* [JavaScript Patterns](http://www.amazon.com/JavaScript-Patterns-Stoyan-Stefanov/dp/0596806752) by Stoyan Stephanov
* [JavaScript Web Applications](http://www.amazon.com/JavaScript-Web-Applications-Alex-MacCaw/dp/144930351X/) by Alex MacCaw
* [JavaScript: The Good Parts](http://www.amazon.com/JavaScript-Good-Parts-Douglas-Crockford/dp/0596517742) by Douglas Crockford
* [Learning Advanced JavaScript slides](http://ejohn.org/apps/learn/) by John Resig
* [Static Web Apps](http://www.staticapps.org/)
* [Test-Driven JavaScript Development](http://www.amazon.com/Test-Driven-JavaScript-Development-Developers-Library/dp/0321683919) by Christian Johansen
* [The JavaScript Interpreter, Interpreted](http://www.slideshare.net/marthakelly/js-interpreter-interpreted) by Martha Girdler [(video)](https://www.youtube.com/watch?v=iSxNCYcPAFk)

#### Specific Topics

* [Classical Inheritance in JavaScript](http://www.crockford.com/javascript/inheritance.html) by Douglas Crockford
* [Partial Application in JavaScript](http://benalman.com/news/2012/09/partial-application-in-javascript/) by Ben Alman (thanks @michaelBenin)
* [HTML5 Rocks slides](http://slides.html5rocks.com/)
* [Learning JavaScript Design Patterns](http://addyosmani.com/resources/essentialjsdesignpatterns/book/) by Addy Osmani

#### Other Lists

* [JS: The Right Way](http://www.jstherightway.org/) (an overview of the JS landscape)
* [Code School](https://www.codeschool.com/paths/javascript)
* Thoughtbot's [Javascript Trail Map](https://upcase.com/javascript)
* [How To Learn JavaScript Properly](http://javascriptissexy.com/how-to-learn-javascript-properly/)
* [Superhero.js](http://superherojs.com)
* [Teach Yourself to Code](http://teachyourselftocode.com/javascript)

### Tools

* code validation: [JSLint](http://jslint.com) / [JSHint](http://jshint.com)
* debugging:
    * [Chrome Developer Tools](https://developer.chrome.com/devtools/index)
        * [Official debugging tutorial](https://developer.chrome.com/extensions/tut_debugging)
        * Tutorial: [JavaScript Diagnosis](http://www.macwright.org/2015/03/10/javascript-diagnosis.html)
    * [Firefox Developer Edition](https://www.mozilla.org/en-US/firefox/developer/)
* sharing code snippets: [gist.github.com](https://gist.github.com/)
* asking questions: [Stack Overflow](http://stackoverflow.com/)

#### GitHub

* Git and GitHub
    * [Official GitHub Help](https://help.github.com/)
    * [Recommended resources](http://hackerhours.org/resources.html#github)
* GitHub Pages
    * [Official site](https://pages.github.com/)
    * [Thinkful guide](http://www.thinkful.com/learn/a-guide-to-using-github-pages/)

## Grading

Percentages | Weights  
----------- | --------- 
90%  - 100% :   	A | Practice/Assignments - 20%
80%  -  89% :  	B | Labs/Programs - 10%
70%  -  79% :  	C | Chapter Exams - 50%
60%  -  69% :  	D | Final Exam - 20%
Below 60% :    	F |  


