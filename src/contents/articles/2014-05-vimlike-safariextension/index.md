---
title: Looking for a vim like Safari extension
author: Kai Grossjohann
date: 2014-05-01
tags: hacking, safari, vim
template: article.jade
---

I use Safari on my Mac because of its smooth integration into the Mac
experience, but then I found out that I do miss vi keyboard shortcuts.
"vimlike extended" to the rescue!

---

There seem to be a couple of Safari extensions that do vi or vim like
keyboard shortcuts.  One of them does link hinting only, but not h/j/k/l
scrolling.  So I'm happy I found one that does both:
[vimlike extended](https://github.com/sethfowler/vimlike-extended)

It's a bit embarrassing to admit that I don't know how to convert a source
tree into something that can be installed as a Safari extension.  I kind of
guessed I could just create a `xar` archive and name it `foo.safariextz`,
but that didn't work out: Safari told me  that there was an error installing
the extension.  But it didn't tell me what the error was.  So I'm happy that
"vimlike extended" comes with  a pre-built extension.

