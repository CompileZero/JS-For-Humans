- [1. Why to Learn JavaScript?](#1-why-to-learn-javascript)
    - [1.0.1. This is one of the very important questions that need to be answered before diving in.](#101-this-is-one-of-the-very-important-questions-that-need-to-be-answered-before-diving-in)
- [2. Where is JavaScript used anyway?](#2-where-is-javascript-used-anyway)
- [3. What is JavaScript?](#3-what-is-javascript)
  - [3.1. The definition:](#31-the-definition)
    - [3.1.1. Explanation](#311-explanation)
- [4. A Briefer History of JavaScript](#4-a-briefer-history-of-javascript)
- [5. How does JS run? Is it Interpreted or Compiled?](#5-how-does-js-run-is-it-interpreted-or-compiled)
- [6. Why is it called a “Scripting Language” ?](#6-why-is-it-called-a-scripting-language-)
- [7. Why the name JavaScript?](#7-why-the-name-javascript)
- [8. What is ECMA Script, LiveScript?](#8-what-is-ecma-script-livescript)
- [9. What is V8 Engine? What is Spider-Monkey?](#9-what-is-v8-engine-what-is-spider-monkey)
- [10. What to do from here?](#10-what-to-do-from-here)

# 1. Why to Learn JavaScript?

### 1.0.1. This is one of the very important questions that need to be answered before diving in.

This is what I feel about the future.

In the future, I believe there would be only 2 languages that would be ruling the software-world: JavaScript & Python. (I know it's quite far-fetched, but just listen to my arguments.)

Ofcourse, there are a multitude of languages used for hardware programming, production & engineering, education, medical sciences, military, space research and many other domains. But, every software that the a non-technical "common man" uses, irrespective of its domain, would move to the cloud, and would use Machine Learning to make things easier and more automated.

The world is moving towards a dcentralized, cloud-based, microservice architecture. Let me explain what that means.

So, when you say that softwares would run on the cloud, this just means, that your browsers work as the Operating System for your software applications. For example, Microsoft Excel works on Windows 10 and MacOS Operating System. But Google Docs, runs inside the Chrome Browser. So, Chrome Browser becomes the Operating System for running a software like Google Docs.

Since 2015, there are 100s (if not 1000s) of companies shifting moving their entire softwares to the cloud. In the future, I believe almost every software: from entertainment to education, from health to food, would run on the web, inside the browser.

When this happens, there's going to be only 1 language that rules everything. And thats JavaScript (atleast for now).

There are already a lot of JavaScript Frameworks, and new are coming up to make JavaScript Development easier for developers, and it does not make sense to develop a project using Vanilla (pure) JavaScript. But it's really important to understand the core concepts of JavaScript, so that you can pickup any JavaScript Framework now, or in the future, and quite easily catch up.

# 2. Where is JavaScript used anyway?

I‘m sure you‘ve seen a Create-Account Page, on any website: ![Login UI Page](./media/UI_1.jpg)

In the above image:

1. There is a toggle-button group, asking whether you are a “Brand/Business” or
   an “Agency”
2. There are 4 text-fields, which ask for your personal details.
3. There are 2 checkboxes, which ask whether you agree to the terms and whether
   you want to sign up to newsletter
4. And finally, there is the “Create Account” Button.

Now let’s look at this image from the Web-Browser‘s Perspective (Take Google
Chrome for example):

1. There is an HTML Code which tells the browser the following:
   1. The page contains 3 labels, 2 toggle-buttons, 4 text-fields, 2 checkboxes
      and a submit-button.
   2. There is a parent “div”(group) which contains all the above components,
      and some child “div(s)” which separate groups of components(there is a div
      for the toggle-buttons, text-fields and checkboxes)
2. There is a CSS code which tells the browser:
   1. That the highlight color for all those components is blue
   2. The font-family is Montserrat
   3. The text-color is gray
   4. And many more attributes like spacing, width and height, margin, padding
      etc. of the components.
3. Finally, there is another piece of code (JavaScript) that tells the browser:
   1. What to do when the user clicks on “Agency” Toggle Button
   2. Which error message to display when all the text-fields are not filled
      correctly.
   3. What to do when “Sign up” Checkbox is checked/unchecked.
   4. And finally, what action(s) to take when “Create Account” button is
      clicked.

> ### 🎐 Analogy
> #### If a web-page is compared to a human body, then:
> **HTML** is the skeletal system of the body. **CSS** is the muscles, skin, hair, (everything that makes the body attractive and not just a bunch of bones stuck together.) Finally, **JavaScript** is the brain of the body. The skeletal system and muscles of the body may be amazing in themselves, but without the brain, they‘re of no use. The brain sends instructions and commands to the body parts to behave and function in a certain manner.

# 3. What is JavaScript?

JavaScript was initially created to make web pages “alive” and interactive
(having complex animations, clickable buttons, popup menus, etc.).

They can be written right in a web page’s HTML and run automatically as the page
loads.

```html
<html>
  <head>
    <title>My First Page</title>
  </head>
  <body>
    <!-- Create a button, which shows on the HTML Page -->
    <button type="button" onClick="firstFunction()">Click Me!</button>

    <!-- Script tag tells HTML that there's a JavaScript Code here-->
    <script>
      // Function Definition of *firstFunction*
      function firstFunction() {
        alert("Hello World");
      }
    </script>
  </body>
</html>
```

The programs in this language are called scripts. Scripts are provided and
executed as plain text. They don’t need special preparation or compilation to
run.

In this aspect, JavaScript is very different from another language called Java.

## 3.1. The definition:

JavaScript® (often shortened to JS) is a lightweight, interpreted, or
just-in-time compiled object-oriented language with first-class functions. While
it is well-known as the scripting language for Web pages, many non-browser
environments also use it, such as Node.js, Apache CouchDB and Adobe Acrobat.

JS is a prototype-based, multi-paradigm, single-threaded, dynamic language,
supporting object-oriented, imperative, and declarative (e.g. functional
programming) styles.

---

### 3.1.1. Explanation

Let’s go over all those terms one-by-one:

Firstly, JS (From now on, I will be referring to JavaScript® as **JS** for
simplicity) is a language that

> 🧩 Explanation:

# 4. A Briefer History of JavaScript

The first mainstream browser “Mosaic” was developed in Jan 1993, by Marc
Andreessen for UNIX Systems. Later that year in September, it found its way on
to Macintosh and Windows.

But there was no JavaScript yet.

Later on, Marc went about to co-found the company “Netscape”. And within a
couple of years, The Netscape Navigator already had 80% of the browser market
share.

Marc realised that websites needed to be more dynamic and that just HTML and CSS
could not suffise that. Developers needed a glue language to add aliveness and
interactivity to websites.

A man named Brenden Eich was hired for the job.

And 10 days later, JavaScript was born. Well, it wasn‘t called JavaScript back
then, it was called “Mocha”.

It had syntax like Java, First-Class functions like Scheme, Dynamic Typing like
Lisp, and Prototypal Inheritance like Self.

Mocha was eventually renamed to “LiveScript” and shipped with the first beta
releases of Netscape 2.0. But then in December 1995, they renamed it to
JavaScript, because it sounded like the cool lightweight cousin to the hottest
programming language of the day, Java!

In 1990, Sir Tim Berners Lee developed the first internet browser on a NeXT
Computer System.

But, nobody knew what the internet was back then.

# 5. How does JS run? Is it Interpreted or Compiled?

Let‘s first understand the basic difference between an interpreted language and
a compiled language.

> 📚 Interpreted Language: A programming language, wherein code is executed line
> by line. The interpreter looks at every line, and if it‘s syntax is valid, it
> will execute, and otherwise give a runtime error. Python is a famous
> interpreted language.

> 📚 Compiled Language: A programming Language, wherein code is converted into a
> machine understandable code by a compiler and then executed by the system.
> JAVA is a famous compiled language. The compiler converts the `.java` code
> into a `.bin` file, which is then executed by the JVM (Java Virtual Machine).

JS was initially launched as an interpreted language. But today, it‘s a
technology affecting every single human being on the planet, and the way JS runs
in the browser has significantly changed. JavaScript is now universally
JIT(Just-In-Time) compiled, either to bytecode (like Java and C#), or directly
to machine code (like C and C++). And modern engines offer an optimization
phase, similar to most traditional compiled languages.

V8 Engine, which runs on the Chrome Browser as well as the Node Environment
compiles JavaScript directly to native machine code before executing it.

Even the SpiderMonkey Engine (Firefox) includes a just-in-time compiler (JIT)
that compiles JavaScript to machine code.

JavaScript tells a browser what to do and how to process things just the same
way that a shell script, php, or any other scripting language does for their
respective hosts.

# 6. Why is it called a “Scripting Language” ?

A scripting/extension language is a programming language that allows some
control of a single (or many) software application(s). Languages chosen for
scripting purposes are often much higher-level than the language used by the
host application. The idea of a scripting language is one that instructs a host
to carry out a series of actions (a lot like an actor reading from a script).

In simpler terms, JavaScript is not a programming language in strict sense.
Instead, it is a scripting language because it uses the browser to do the work.
Eg.:- If you command an image to be replaced by another one, JavaScript tells
the browser to go do it. And so, the programs written in this language are
called scripts. They can be written right in a web page’s HTML and run
automatically as the page loads.

# 7. Why the name JavaScript?

# 8. What is ECMA Script, LiveScript?

# 9. What is V8 Engine? What is Spider-Monkey?

# 10. What to do from here?

