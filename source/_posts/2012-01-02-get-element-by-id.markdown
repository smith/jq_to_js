---
layout: post
title: "Getting an HTML Element by its ID Attribute"
date: 2012-01-02 20:12
comments: true
author: Daniel Marino
categories: selectors
published: true
---

One of the greatest features jQuery is known for is its impressive [selector](http://api.jquery.com/category/selectors/) engine. Its easy to take for granted the ability to query the DOM for elements by using simple CSS-like syntax. For example, if you wanted to reference an element with an <code>id</code> of "foo", your jQuery script might look like:

    $('#foo') // Returns a jQuery object with the id 'foo'

With JavaScript, it requires a little more effort (and in some cases a lot more effort) to query DOM elements. However, there is one method for getting a single DOM element that is easy to learn and remember, and that is the <code>getElementById()</code> method. It does exactly as its name implies - it allows you to get an element by its <code>id</code> attribute.

    document.getElementById('foo') // Returns an Element object with the id 'foo'

I'll admit, this code by itself isn't extremely useful, but it is a fundamental building block to being able to access and manipulate elements within a web page. Soon I'll show you what you can do with a DOM element once you've selected it, as well as other methods for querying DOM selectors.

### Resources

- [jQuery ID Selector](http://api.jquery.com/id-selector/)
- [jQuery ID Selector Source](https://github.com/jquery/jquery/blob/master/src/core.js#L141-162)
- [JavaScript getElementById() Method](https://developer.mozilla.org/en/DOM/document.getElementById)