---
layout: post
title: Getting started with web development
---

_A comprehensive roadmap of getting started with web development._

**Something to note: You can't learn to code by just watching tutorials or reading articles; you have to get your hands dirty by writing code, facing errors and building real world projects. In this article I will recommend projects you can build after completing each step.**

## First things first: HTML and CSS

Now thats something most of us already know. For those who don't, HTML decides the structure of websites and CSS is used to control the styling(fonts, colors, animations etc).

_[Learning Resource](https://m.youtube.com/playlist?list=PL4cUxeGkcC9ivBf_eKCPIAYXWzLlPAm6G)_

_Project recommendation: a well formatted website listing all suits of Tony Stark._

## Lets start coding now

![html is a programming language]({{ site.baseurl }}/images/web-dev-images/html_programming_language.jpg "Yeah, html is a programming language")

Javascript (yeah its a real programming language) should be your next step. Javascript decides how your website will behave, what happens on clicking buttons, what data gets sent to the server etc.
If javascript is your first programming language, it can be overwhelming.
Loops, conditionals, arrays, objects, DOM manipulation, local storage, asynchronous javascript....wohh!!! **This is the point where a lot of people start feeling that they are too dumb and coding isn't for them. But don't give up yet, you are smarter than you think.**

_Resources: [This is too long, just skim through it.](https://www.youtube.com/watch?v=jS4aFq5-91M) [This one is for asynchronous javascript](https://www.youtube.com/watch?v=PoRJizFvM7s)_

_Project recommendation: a todo list website which utilizes local storage_

## Frontend: The wicked world of Javascript frameworks

You can create perfectly functional websites with just HTML, CSS and JS. But as your web app grows, writing and maintaining vanilla js code becomes really tough. This is where javascript frameworks come in, they make a developer's life easy. The thing with javascript frameworks is: there a TOO MANY OF THEM.

![There are just TOO MANY of them]({{ site.baseurl }}/images/web-dev-images/javascript_frameworks.png "There are just TOO MANY of them")

So which one should you choose? Angular is slightly tough to get started with, Svelte and Vue are newer frameworks that are easier to work with and performant than Angular and React but I would say go with React( actually its a library not a framework): its powerful, easy to learn, has a very large community, lots of tutorials plus if you know React you can easily get into the world of android and ios development by learning something called React Native: a framework based on React. The performance trade-off shouldn't matter to a beginner.

At this point you can also consider using a service like Firebase, it provides you a database which you can connect to your app and other necessary features like user authentication(sign in with gmail, google etc), hosting.

_Resources: [using react with firebase](https://www.youtube.com/watch?v=jCY6DH8F4oc)_

_Project recommendation: Extend the todo list app you created, add google authentication, store tasks in firestore._

## Backend and Database: flex about being a web developer after this

Backend refers to the code which runs on the server. This code handles requests which our users make from the frontend and makes changes to the database. There are a lot of choices in backend frameworks as well: Express, Deno, Django, Flask, Ruby on Rails, Gin, Beego etc.

Choose Django(its really powerful but the project structure is extremely intimidating) or Flask if Python is your love. Gin and Beego are go frameworks. If javascript is something you are comfortable with then go with Express. My personal opinion: go with Express. It has a large community and is a very popular option with the frontend framework I recommended, React.

![This is really a genuine concern]({{ site.baseurl }}/images/web-dev-images/sql-or-nosql-thats-the-query.jpg "There are just TOO MANY of them")

Databases are primarily of two types: [SQL and NO-SQL](https://www.programiz.com/sql/database-introduction). For a start going with MongoDB is not a bad idea, its a popular NoSQL choice.

_Resources: [MERN Tutorial](https://www.youtube.com/watch?v=ngc9gnGgUdA)_

_Project recommendation: Twitter clone_

## This is the start and not the end

The world of web development is ever evolving. So, your journey doesn't end but actually starts after following all the above steps. Build tons of projects. There are so many things you can learn after this. Learn typescript, its a statically typed (avoid bugs in production by making your life hell while writing code) replacement of javascript. Try to get deeper into the framework you have worked with, also don't shy away from exploring other frameworks which suit your project.

Thats all for today, thank you for patiently reading till the end. If you have anything to add or any questions or suggestions, feel free to hit me up on my socials([twitter](https://twitter.com/devout_coder), [insta](https://instagram.com/devout_coder)).
