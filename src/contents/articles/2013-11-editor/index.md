---
title: Choosing an editor or IDE
author: Kai Grossjohann
date: 2013-11-23
tags: editor, hacking
template: article.jade
---

I had been using one editor for many years, now I'm searching and I'm not sure
I've found the right one.  Life was much simpler when I always knew which tool
to turn to, but life is much richer now that I have many tools to look at.

---

Some time back, I've used Emacs for ten years, for everything that had to do
with hacking.  I used it for hacking Emacs Lisp, I used it for hacking Perl, I
used it for hacking Java.  And then I decided that I had to see what else the
world had to offer.  So I investigated Eclipse, given that I was a Java hacker
at the time.  Eclipse was providing awesome features that were very useful for
hacking Java: I could navigate to a method that was being invoked, I could
complete class names and method names -- bliss.

Then I had a reason to hack PHP, and the only place I could do it was on the
server which didn't have a proper development environment.  So I started using
vim pretty extensively for that.  Somehow I could make do without missing the
IDE completion and navigation features I had gotten used to from Eclipse.

Then I had another reason to hack PHP, and this time I decided I wanted to
investigate another IDE.  PHP tools for Eclipse pretty much sucked at that
point, I recall that I could open a class by name, but there was no method
completion and so on.  Then I discovered that JetBrains made PhpStorm for a
reasonable price, and I had heard good things about IntelliJ IDEA from the same
company.  PhpStorm is really nice.  It knows more about completion than I
thought possible.  And if it doesn't know then it's easy to put a PhpDoc comment
into the code that tells it.

And it turns out that PhpStorm includes the functionality of WebStorm, so I can
also hack JavaScript with it.  I decided that I'd like to learn what Node.js is
all about.  I'm not sure about the completion features, just yet.

I had also read good things about LightTable, but somehow I couldn't get that to
fly with Node.js.  Yes, it opens my project, and yes, I can select a file
easily.  But where is the navigation?  Where is the completion?  I haven't found
out yet.
