---
layout: post
title: "Showing and Hiding an Element"
date: 2012-01-05 10:00
comments: true
author: Daniel Marino
categories: effects
published: true
---

A couple of commonly used [effects](http://api.jquery.com/category/effects/) in jQuery are the <code>show()</code> and <code>hide()</code> methods. These effects do precisely as named - they show and hide elements on the web page. Let's look at a couple of jQuery examples:

    $('#foo').show(); // Show the element #foo

    $('#foo').hide(); // Hide the element #foo

These effects are simple to achieve with JavaScript. The first thing we'll do is get the element <code>#foo</code> by it's <code>id</code> attribute, just like we learned in the [previous article](/articles/get-element-by-id/). The second thing we'll do is set <code>#foo</code>'s CSS display property to <code>block</code> to show it or <code>none</code> to hide it. We could also just as easily use any CSS display property other than <code>none</code> to show the element (such as <code>inline</code> or <code>inline-block</code>). Here are the JavaScript examples:

    // Show the element #foo
    document.getElementById('foo').style.display = 'block'; // could also use 'inline' or 'inline-block'

    // Hide the element #foo
    document.getElementById('foo').style.display = 'none';

The first thing you probably noticed is that the jQuery version is significantly less code than the JavaScript version. That will often be the case, but remember we're not loading the entire jQuery library in the JavaScript version, so we're saving ourselves from having to load all that extra code. This will cut down on page load and script execution time.

A key thing to take away here is that we're setting a CSS property with JavaScript. In fact, you can set any CSS property with JavaScript. This is essentially what is going on behind the scenes for the [effects](http://api.jquery.com/category/effects/) module of jQuery. We'll get more in depth with setting and getting styles in future articles.

### Resources

- [jQuery show()](http://api.jquery.com/show/)
- [jQuery hide()](http://api.jquery.com/hide/)
- [JavaScript getElementById() Method](https://developer.mozilla.org/en/DOM/document.getElementById)
- [JavaScript element.style](https://developer.mozilla.org/en/DOM/element.style)