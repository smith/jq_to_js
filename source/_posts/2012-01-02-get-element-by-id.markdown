---
layout: post
title: "Getting an HTML Element by it's ID Attribute"
date: 2012-01-02 20:12
comments: true
author: Daniel Marino
categories: selectors
---

One of the greatest features jQuery is known for is its impressive selector engine. Its easy to take for granted the ability to query the DOM for elements by using simple CSS-like syntax. With JavaScript, it requires a little more effort (and in some cases a lot more effort). However, there is one method for getting a single DOM element that is easy to learn and remember, and that is the <code>getElementById()</code> method. It does exactly as its name implies - it allows you to get an element by its <code>id</code> attribute.

    document.getElementById('foo');

I'll admit, this code by itself isn't extremely useful, but it is a fundlemental building block to being able to access and manipulate  elements within a web page. Soon I'll show you what you can do with a DOM element once you've selected it, as well as other methods for querying DOM selectors.