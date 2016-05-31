---
layout: default
permalink: /
---

# A Course syllabus 
## (modeled after [Advanced JavaScript](https://github.com/advanced-js/syllabus/))

***If you are a teacher or interested in the design of the course, see the [meta](https://github.com/advanced-js/syllabus/blob/master/meta.md) document.***

* **Course:** [INF215](http://inf215.netedu.info)
* **Instructor:** Antonio Vantaggiato, [avantaggiato@sagrado.edu](mailto:avantaggiato@sagrado.edu)
* **Need help?**
    * [![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/advanced-js/syllabus?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
        * It sends message digests to people who aren't active in the room, so feel free to ask a question even if no one's around.
    * Look through and create [issues](https://github.com/advanced-js/syllabus/issues)
    * Office Hours during [Hacker Hours](http://hackerhours.org/) (see [schedule](http://www.meetup.com/hackerhours/events/calendar/))
   * [Email](mailto:alf9@nyu.edu) for 1-on-1 help, or to set up a time to meet

## Course Description

Learn best practices in JavaScript in this intensive, five-session course. Topics include data encapsulation, closures, binding, inheritance, and name spacing. Discover some of the lesser-known, yet useful, features of the language, such as how to debug JavaScript problems on different browsers and improve performance. Create interactive webpages using third-party JavaScript libraries.

## Course Overview

We will dive into the nuances of JavaScript, how prototypal inheritance compares to classical inheritance, and how this can be used to build dynamic and complex web applications.  Modern tools like jQuery and BackboneJS will be discussed, but students will learn the building blocks of these frameworks and after this course be able to understand what is happening under the hood.  The focus will be on development for browsers, though most applies to other systems like Node.js, Phonegap, etc.  Topics covered include:

* 1a
* 2b
* 3c

Topics will be demonstrated through live-code examples/slides, available at [advanced-js.github.io/deck](http://advanced-js.github.io/deck/).  Additional exercises will completed in-class.


## Homework/Projects

All assignments are listed within the [Course Outline](#course-outline).

### Workflow

If you're using GitHub Desktop, these general instructions will help:

* <https://guides.github.com/activities/forking/>
* <https://help.github.com/desktop/guides/contributing/>

Enabling `Edit`->`Automatically Sync after Committing` is recommended. Here are the steps:

1. Fork the repository for the exercise/project (found under [github.com/advanced-js](https://github.com/advanced-js)).
1. Clone the repository to your computer.
1. Open the `index.html` file in a browser and open the Developer Tools.
1. Modify the files to complete your solution.
1. Refresh the `index.html` page to see the results, and repeat.
1. Make sure all of your code is committed.
1. Push/sync up to GitHub.
1. [Create a pull request](https://help.github.com/articles/creating-a-pull-request/) on the original repository. All assignments are due at the start of the following class, unless otherwise specified.
1. You can continue to push fixes and improvements until the close date (listed in Classes) – just add a comment in the pull request to let me know it's been updated.

When the pull request is created, you should see a message saying that "the Travis CI build is in progress" – this means that your solution is being automatically checked for syntax errors.  If this "build" ends up failing (which will show a red "X"), click through the "details" link and scroll to the bottom to see what the errors were.  Per the [requirements](#requirements) below, please fix the issues and push up the changes.

Feedback will be given in the pull request, so please respond with your thoughts and questions!  You are welcome to open the pull request early as a work-in-progress if you are stuck and want to ask a question.  Note that your solution will also be live at `http://USERNAME.github.io/EXERCISE`.

## Course Outline

### Class 1

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Are you new to front-end web development? Here&#39;s a secret: no one else really knows what they&#39;re doing either.</p>&mdash; Nicolas (@necolas) <a href="https://twitter.com/necolas/status/291978260433219584">January 17, 2013</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

1. Introduction
    * Put name on sticky note on back of monitor
    * Discuss what the class is going to cover
    * Everyone introduce themselves
        * Name
        * What you "do"
        * What are your goals for the class?
        * What's something in JS (or technology) you worry that your peers understand but you don't?
1. Setup
    * How many people are comfortable with Git/GitHub?
    * Install [GitHub Desktop](https://desktop.github.com/)
        * If you are comfortable with Git already, you can skip this.
    * Sign up for GitHub
1. GitHub workflow
    * Walk through [workflow](#workflow)
    * Create pull request on [students repository](https://github.com/advanced-js/students)
1. Explain how slides work
1. Get through `countdown_exercise` slide
1. Talk through [requirements](#requirements)

#### Homework

* Join [the chat room](https://gitter.im/advanced-js/syllabus).
* [Set up your GitHub profile.](https://github.com/settings/profile)
* Access [NYU Classes](https://newclasses.nyu.edu) page, where grades will be posted.
    * [Documentation](https://wikis.nyu.edu/display/nyuclasses/Student+Quick-Start)
* Read [JavaScript Garden](http://bonsaiden.github.io/JavaScript-Garden/).
* Finish up and submit [echo](https://github.com/advanced-js/echo) and [countdown](https://github.com/advanced-js/countdown) exercises.
* Complete [blink](https://github.com/advanced-js/blink) exercise.

### Class 2

1. Look at various approaches for `countdown()`
    * Show recursive solution
1. Developer Tools walkthrough
    * Elements (HTML)
    * Console (JS)
    * Scripts (JS)
1. Pair program to build [Memory v1](https://github.com/advanced-js/memory) (see [pairing tips](#pairing-tips))
1. Cover OOP, though "oop_inheritance" slide
    * [Encapsulation example](http://jsbin.com/baqopu/1/edit?css,js,output)
    * Look at [Backbone.js Events](http://backbonejs.org/docs/backbone.html)

#### Homework

* Read [Mozilla's Introduction to Object-Oriented Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Introduction_to_Object-Oriented_JavaScript)
* [OOP exercise](https://github.com/advanced-js/oop), through V2
* [Memory v2](https://github.com/advanced-js/memory#v2) (individual)

## Resources

### Required Reading

* [Google JavaScript Style Guide](http://google-styleguide.googlecode.com/svn/trunk/javascriptguide.xml)
* [JavaScript Garden](http://bonsaiden.github.com/JavaScript-Garden/)
* [Mozilla's Introduction to Object-Oriented Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Introduction_to_Object-Oriented_JavaScript)
* [What’s so great about JavaScript Promises?](http://blog.parse.com/learn/engineering/whats-so-great-about-javascript-promises/)

### Beginner Materials

This class assumes you are confident with this material, but in case you need a brush-up...

* Codecademy – [JavaScript](https://www.codecademy.com/learn/javascript) and [jQuery](https://www.codecademy.com/learn/jquery)
* [Eloquent JavaScript](http://eloquentjavascript.net/index.html) by Marijn Haverbeke, Chapters 1-5
* [Want to learn JavaScript in 2015?](https://medium.com/@_cmdv_/i-want-to-learn-javascript-in-2015-e96cd85ad225)
* [How jQuery Works](https://learn.jquery.com/about-jquery/how-jquery-works/)
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
* [HTML5 Rocks](http://www.html5rocks.com)

#### GitHub

* Git and GitHub
    * [Official GitHub Help](https://help.github.com/)
    * [Recommended resources](http://hackerhours.org/resources.html#github)
* GitHub Pages
    * [Official site](https://pages.github.com/)
    * [Thinkful guide](http://www.thinkful.com/learn/a-guide-to-using-github-pages/)

#### HTML/CSS/JS Sandboxes

* [JS Bin](http://jsbin.com/) (recommended)
* [bl.ocks.org](http://bl.ocks.org/)
* [Cloud9](https://c9.io/)
* [CodePen](http://codepen.io/pen/)
* [JSFiddle](http://jsfiddle.net/)
* [Plunker](http://plnkr.co/)
* [rawgithub.com](http://rawgit.com/)

### More Examples

* [map/reduce](http://jsbin.com/ojapAsUR/2/edit?js) (in [Underscore](http://underscorejs.org/#map))

## Grading

* Class Participation – 30%
* Homework – 70%

## Statements on Plagiarism

