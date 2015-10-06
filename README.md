# Not Awesome: ES6 Classes

A curated list of resources on why ES6 (aka ES2015) classes are NOT awesome

Reverse-inspired by all of the awesome lists on GitHub, like [Awesome](https://github.com/sindresorhus/awesome), [Awesome Awesomeness](https://github.com/bayandin/awesome-awesomeness), [Awesome JavaScript](https://github.com/sorrycc/awesome-javascript), [Awesome React](https://github.com/enaqx/awesome-react), [Awesome Go](https://github.com/avelino/awesome-go), [Awesome Elm](https://github.com/isRuslan/awesome-elm), etc.

## Table of Contents

- [Introduction](#introduction)
- [Too Long; Didn't Read](#tldr)
- [Reading](#reading)
- [Videos](#videos)
- [Contribution Guidelines](#contribution-guidelines)
- [License](#license)

## Introduction

While ES6 brings several useful and syntactically pleasing new features to JavaScript, there are many people in the JS community who feel that adding class syntax to the language was a mistake. I share this sentiment, but I have encountered quite a few programmers in the wild who don't agree or simply don't seem to understand why some of us have this opinion. So, I wanted to create an online reference where people could come to learn specifically about this issue and why they might not actually need class syntax in JavaScript.

## TLDR

- JavaScript is a class-free, object-oriented, & functional programming language. It eschews [classical inheritance](https://en.wikipedia.org/wiki/Class-based_programming) in favor of [prototypal inheritance](https://en.wikipedia.org/wiki/Prototype-based_programming).
- Many believe prototypal inheritance to be more flexible and freeing than classical inheritance due to its less rigid nature.
- The ES6 class syntax, constructors, the `new` keyword, etc. are ideas taken from the classical inheritance model to make programmers coming from languages like C++, Java, C#, etc. more comfortable and do not really belong in JavaScript.
- While prototypal inheritance is very powerful in its own right, there is a growing movement among developers, both within and outside of the JS community (Ex: [Composition in Golang](https://talks.golang.org/2012/splash.article#TOC_15.)), to shift away from inheritance in favor of object composition. 
- ES6 class syntax is essentially syntactic sugar that will end up obfuscating the true nature of JavaScript and confusing the next generation of programmers learning it.
- Instead of ES6 classes, you should consider factory functions, object composition, and/or prototypal inheritance via the use of prototypes, object literals, Object.create(), Object.assign(), etc. while avoiding constructors and the `new` keyword altogether.

“If a feature is sometimes dangerous, and there is a better option, then always use the better option.” 

--Douglas Crockford

## Reading

- [Common Misconceptions About Inheritance in JavaScript](https://medium.com/javascript-scene/common-misconceptions-about-inheritance-in-javascript-d5d9bab29b0a)
- [Composition Over Inheritance](https://medium.com/humans-create-software/composition-over-inheritance-cb6f88070205)
- [Delegation vs Inheritance in JavaScript](https://javascriptweblog.wordpress.com/2010/12/22/delegation-vs-inheritance-in-javascript)
- [Factory Functions in JavaScript](https://medium.com/humans-create-software/factory-functions-in-javascript-video-d38e49802555)
- [How to Fix the ES6 `class` Keyword](https://medium.com/javascript-scene/how-to-fix-the-es6-class-keyword-2d42bb3f4caf)
- [Introducing the Stamp Specification -- Move Over, `class`: Composable Factory Functions Are Here](https://medium.com/javascript-scene/introducing-the-stamp-specification-77f8911c2fee)
- [Javascript OO Without Constructors](http://tobyho.com/2012/10/21/javascript-OO-without-constructors/)
- [JS Objects -- Part 1: Inherited a Mess](http://davidwalsh.name/javascript-objects)
- [JS Objects -- Part 2: Distractions](http://davidwalsh.name/javascript-objects-distractions)
- [JS Objects -- Part 3: De"construct"ion](http://davidwalsh.name/javascript-objects-deconstruction)
- [Myth: JavaScript Needs Classes](http://www.2ality.com/2011/11/javascript-classes.html)
- [The Many Talents of JavaScript for Generalizing Role Oriented Programming Approaches Like Traits and Mixins](http://peterseliger.blogspot.de/2014/04/the-many-talents-of-javascript.html#the-many-talents-of-javascript)
- [The Two Pillars of JavaScript -- Part 1: How to Escape the 7th Circle of Hell](https://medium.com/javascript-scene/the-two-pillars-of-javascript-ee6f3281e7f3)
- [Think Twice About ES6 Classes](http://christianalfoni.github.io/javascript/2015/01/01/think-twice-about-classes.html)
- [Web Reflection: Better JavaScript Classes](http://webreflection.blogspot.com/2010/01/better-javascript-classes.html)
- [Web Reflection: \[ES5\] Classes As Descriptor Objects](http://webreflection.blogspot.com/2010/01/es5-es5-classes-as-descriptor-objects.html)

## Videos

- [Ashley Williams: If You Wish to Learn ES6/2015 From Scratch, You Must First Invent the Universe](https://www.youtube.com/watch?v=DN4yLZB1vUQ)
- [Composition Over Inheritance](https://www.youtube.com/watch?v=wfMtDGfHWpA)
- [Composition vs. Inheritance](https://www.youtube.com/watch?v=dYUZiJEy0JE)
- [Douglas Crockford: The Better Parts - JSConfUY 2014](https://www.youtube.com/watch?v=bo36MrBfTk4)
- [Factory Functions in JavaScript](https://www.youtube.com/watch?v=ImwrezYhw4w)
- [Fluent 2013 - Eric Elliott, "Classical Inheritance is Obsolete: How to Think in Prototypal OO"](https://www.youtube.com/watch?v=lKCCZTUx0sI)
- [Nordic.js 2014 • Douglas Crockford - The Better Parts](https://www.youtube.com/watch?v=PSGEjv3Tqo0)
- [Source Decoded 3: Javascript -- Prototypes, Prototypal Inheritance Done Right](https://www.youtube.com/watch?v=Yvf_kUBZmXg)

## Contribution Guidelines

Please, ensure your pull request adheres to the following guidelines:

- Search previous suggestions before making a new one, as yours may be a duplicate.
- Make an individual pull request for each suggestion.
- Titles should be [capitalized](http://grammar.yourdictionary.com/capitalization/rules-for-capitalization-in-titles.html).
- Use the following format: `[Content Title](content link)`
- Choose corresponding section (Reading, Videos, etc.) for your suggestion. 
- New categories or improvements to the existing categorization are welcome. I would like to add a Tutorials/Examples section at some point. Feel free to get started on that if you have the time.
- The pull request and commit should have clear and useful titles.
- Each section's list, after your addition, should be sorted alphabetically.

## License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
