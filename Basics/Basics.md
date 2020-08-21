- [1. Where is JavaScript used anyway?](#1-where-is-javascript-used-anyway)
- [2. What is JavaScript?](#2-what-is-javascript)
  - [2.1. The definition:](#21-the-definition)
    - [2.1.1. Explanation](#211-explanation)
- [3. A Briefer History of JavaScript](#3-a-briefer-history-of-javascript)
- [4. Why is it called a “Scripting Language” ?](#4-why-is-it-called-a-scripting-language-)
- [5. Why the name JavaScript?](#5-why-the-name-javascript)
- [6. What is ECMA Script, LiveScript?](#6-what-is-ecma-script-livescript)
- [7. What is V8 Engine? What is Spider-Monkey?](#7-what-is-v8-engine-what-is-spider-monkey)
- [8. What to do from here?](#8-what-to-do-from-here)

# 1. Where is JavaScript used anyway?

I‘m sure you‘ve seen a Create-Account Page: ![Login UI Page](./media/UI_1.jpg)

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
>
> #### If a web-page is compared to a human body, then:

**HTML** is the skeletal system of the body. **CSS** is the muscles, skin, hair,
(everything that makes the body attractive and not just a bunch of bones stuck
together.) Finally, **JavaScript** is the brain of the body. The skeletal system
and muscles of the body may be amazing in themselves, but without the brain,
they‘re of no use. The brain commands the body parts to function according to
desired outcomes.

# 2. What is JavaScript?

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

## 2.1. The definition:

JavaScript® (often shortened to JS) is a lightweight, interpreted, or
just-in-time compiled object-oriented language with first-class functions. While
it is well-known as the scripting language for Web pages, many non-browser
environments also use it, such as Node.js, Apache CouchDB and Adobe Acrobat.

JS is a prototype-based, multi-paradigm, single-threaded, dynamic language,
supporting object-oriented, imperative, and declarative (e.g. functional
programming) styles.

---

### 2.1.1. Explanation

Let’s go over all those terms one-by-one:

Firstly, JS (From now on, I will be referring to JavaScript® as **JS** for
simplicity) is a language that

> 🧩 Explanation:

# 3. A Briefer History of JavaScript

The first mainstream browser “Mosaic” was developed in Jan 1993, by Marc
Andreessen for UNIX Systems. Later that year in September, it found its way on
to Macintosh and Windows.

But there was no JavaScript yet.

Later on, Marc went about to co-found the company “Netscape”. And within a
couple of years, The Netscape Navigator already had 80% of the browser market
share.

Marc realised that websites needed to be more dynamic in order to help withs

In 1990, Sir Tim Berners Lee developed the first internet browser on a NeXT
Computer System.

But, nobody knew what the internet was back then.

# How does JS run? Is it Interpreted or Compiled?

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

# 4. Why is it called a “Scripting Language” ?

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

# 5. Why the name JavaScript?

# 6. What is ECMA Script, LiveScript?

# 7. What is V8 Engine? What is Spider-Monkey?

# 8. What to do from here?
