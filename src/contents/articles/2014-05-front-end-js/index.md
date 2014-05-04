---
title: Front end Javascript development
author: Kai Grossjohann
date: 2014-05-04
tags: hacking, javascript, front-end
template: article.jade
---

Doing simple things with front-end Javascript development
really does turn out to be simple.  I'm trying to dip
my toes in front-end Javascript development (having the
opportunity to do some server-side Javascript development
in my day job).

---

Today, I had the chance to fix two little buttons that made
text on a web page larger or smaller.  It's really interesting
to see how easy this is to do.  Of course, it's just a very 
simple task in the first place, but given that I have so little
experience, I thought it might have turned out to be harder
for me.

Basically, the idea is that you have one HTML element that
contains all your content (you can use `body` if you can't find
another one).  And you write your CSS so that the font size
is a parameter of that element.  (I guess you can use relative
font sizes for other elements.)

Now changing the font size is just a matter of changing this
CSS in one central place, and jQuery makes it easy:

```javascript
$('#container').css('font-size')
```

This returns a string such as "16px" that tells you the font
size.  And you can change it with

```javascript
$('#container').css('font-size', '18px');
```

Very easy.

