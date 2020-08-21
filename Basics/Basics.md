- [1. Where is JavaScript used anyway?](#1-where-is-javascript-used-anyway)
  - [1.1 The definition:](#11-the-definition)
- [2. Why is it called a “Scripting Language” ?](#2-why-is-it-called-a-scripting-language-)
- [3. Why the name JavaScript?](#3-why-the-name-javascript)
- [4. What to do from here?](#4-what-to-do-from-here)

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

# What is JavaScript?

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

## 1.1 The definition:

JavaScript® (often shortened to JS) is a lightweight, interpreted, or
just-in-time compiled object-oriented language with first-class functions. While
it is well-known as the scripting language for Web pages, many non-browser
environments also use it, such as Node.js, Apache CouchDB and Adobe Acrobat.

JS is a prototype-based, multi-paradigm, single-threaded, dynamic language,
supporting object-oriented, imperative, and declarative (e.g. functional
programming) styles.

---

### Explanation

Let’s go over all those terms one-by-one:

Firstly, JS (From now on, I will be referring to JavaScript® as **JS** for
simplicity) is a language that

> 🧩 Explanation:

# 2. Why is it called a “Scripting Language” ?

JS is not interpreted like everybody thinks. Well, atleast not now.

Let‘s go back in time. During the early days of JavaScript, it used to be
interpreted.

> 📚 Interpreted Language: A programming language, wherein code is executed line
> by line. It‘s the exact opposite of a compiled language. Python is a famous
> interpreted language.

> 📚 Compiled Language: A programming Language, wherein code is converted into a
> machine understandable code by a compiler and then executed by the system.
> JAVA is a famous compiled language. Here the compiler converts the `.java`
> code into a `.bin` file, which is then executed by the JVM (Java Virtual
> Machine).

JavaScript is not a programming language in strict sense. Instead, it is a
scripting language because it uses the browser to do the dirty work. If you
command an image to be replaced by another one, JavaScript tells the browser to
go do it. Because the browser actually does the work, you only need to pull some
strings by writing some relatively easy lines of code. That’s what makes
JavaScript an easy language to start with.

A scripting language, script language or extension language is a programming
language that allows some control of a single or many software application(s).
Languages chosen for scripting purposes are often much higher-level than the
language used by the host application…

In this case, the application is the browser. And about compilation:Scripts are
often, but not always, interpreted from the source code or “semi-compiled” to
bytecode which is interpreted, unlike the applications they are associated with,
which are traditionally compiled to native machine code for the system on which
they run

But JS has matured considerably over the last few years, with advanced features
such as lambdas, classes (for better or worse), destructuring, iterators and
modules that bring its capabilities on par with most other modern languages. No
longer restricted to the browser, is it also commonly found running standalone
on the server under NodeJS.

Javascript is now universally JIT compiled, either to bytecode (like Java and
C#), or directly to machine code (like C and C++). And modern engines offer an
optimization phase, similar to most traditional compiled languages.

V8 (Chrome, Node) V8 compiles JavaScript directly to native machine code before
executing it.

Chakra Code (Edge) Chakra Core [can] do parallel JIT compilation…

SpiderMonkey (Firefox) SpiderMonkey 38 includes a just-in-time compiler (JIT)
that compiles JavaScript to machine code…

The idea of a scripting language is one that instructs a host to carry out a
series of actions (a lot like an actor reading from a script).

Javascript tells a browser what to do and how to process things just the same
way that a shell script, php, or any other scripting language does for their
respective hosts. “the same way that a shell script, php, or any other scripting
language does for their respective hosts "

# A Briefer History of JavaScript

# 3. Why the name JavaScript?

# What is ECMA Script, LiveScript?

# What is V8 Engine? What is Spider-Monkey?

# 4. What to do from here?
