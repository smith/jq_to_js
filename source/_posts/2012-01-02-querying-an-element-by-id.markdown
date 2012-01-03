---
layout: post
title: "Getting an HTML Element by it's ID Attribute"
date: 2012-01-02 20:12
comments: true
categories: selectors
published: false
---

Probably one of the best things about jquery is its selector engine. Its easy to take for granted the ability to query DOM elements by using simple CSS-like syntax. Unfortunately, this is not as easy as you would think using straight ahead JavaScript, at least not until you get used to it (and you will get used to it...). There is one method for querying a single DOM element that is super simple to learn, and that is the <code>getElementById()</code> method. It does exactly as its name implies - it allows you to get an element by its id attribute.*

The JavaScript code is very simple:

    document.getElementById('foo');

I'll admit, this code by itself isn't extremely useful by itself, but it is a fundlemental building block to being able to access and manipulate DOM elements. If you were to type that the JavaScript console in your browser of choice, you would see that it returns the element (make sure you replace "foo" with an actual id that exists on the page).

Whenever we query the DOM, we need to chain it to the 'document' which you could probably figure out, it refers to the entire web page. That's the easy version to explain it. There are much more in depth resources that can explain browsers, web pages, and their node structures than I ever could.

Soon I'll show you what you can do with a DOM element once you've selected it, as well as other methods for querying DOM selectors.