---
layout: post
title: "Showing and Hiding an Element"
date: 2012-01-04 13:12
comments: true
author: Daniel Marino
categories: effects
published: false
---

A couple of [effects](http://api.jquery.com/category/effects/) that are commonly used in jQuery are being able to [show](http://api.jquery.com/show/) and [hide](http://api.jquery.com/hide/) elements. This is also a pretty easy task with JavaScript. Let's look at a couple of jQuery examples first:

    $('#foo').show(); // Show the element #foo

    $('#foo').hide(); // Hide the element #foo

With JavaScript:

    // Show the element #foo
    document.getElementById('foo').style.display = 'block'; // could also use 'inline' or 'inline-block'

    // Hide the element #foo
    document.getElementById('foo').style.display = 'none';

The first thing we're doing is getting the element 'foo' by it's <code>id</code> attribute. The second thing we're doing is we're setting it's CSS <code>display</code> property to 'block' (to show it) or 'none' (to hide it).

The key thing we're really learning here is that you're actually setting a CSS property with JavaScript. This means that you can set any CSS property with JavaScript. We'll look more at setting styles with JavaScript in another article

Recently, I showed you how to [get an element by it's id attribute](/articles/get-element-by-id/).

### Resources

- [jQuery .show()](http://api.jquery.com/show/)
- [jQuery .hide()](http://api.jquery.com/hide/)
- [JavaScript getElementById() Method](https://developer.mozilla.org/en/DOM/document.getElementById)