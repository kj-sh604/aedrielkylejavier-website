---
title: Redesigned my Blog Page with the Goal of Using the Least Amount of CSS, Possible
description: I had trouble sleeping tonight, so I decided to redesign the blog part of my website using as little css as possible **AND** create a workflow wherein I can create new articles by writing a single markdown file and just converting to HTML. Yes, of course, I am fully aware of all the static site generators out there, but for some reason (absolute stupidity and laziness on my part), when I started this blog, I decided to write articles manually using a HTML template that I gobbled up together. For a while it was okay, but now that I want to just dump more things on here — it's proving to be incredibly ineffecient and very much prone to a lot of broken links and unmaintainability
lang: en
viewport: width=device-width, initial-scale=1
---

<meta name="color-scheme" content="light dark">


I had trouble sleeping tonight, so I decided to redesign the blog part of my website using as little css as possible **AND** create a workflow wherein I can create new articles by writing a single markdown file and just converting to HTML. Yes, of course, I am fully aware of all the static site generators out there, but for some reason (absolute stupidity and laziness on my part), when I started this blog, I decided to write articles manually using a HTML template that I gobbled up together. For a while it was okay, but now that I want to just dump more things on here — and it was proving to be incredibly ineffecient and very much prone to a lot of broken links and unmaintainability.

### here's that old crusty blog…

[![Articles Page](2.png)](2.png)
Articles Page
\
\
[![Example Article](3.png)](3.png)
Example Article
\
\
[![after writing this short post, I was done with manually doing it](1.png)](1.png)
after writing this short blog post, I was done with manually doing it
\
\
\
I mean… the old crusty page looked okay, as you can see I don't really care about how this site looks, I just want it to work and be as minimal as possible and a place where people can read things that I am enthused to learn, opinions, and ya' know… stuff.
\
\
I came across this for the dark mode device recognition:\

`<meta name="color-scheme" content="light dark">`

Which I think it's pretty cool that it doesn't even need to use @media css arguments. 

and then I played around with pandoc and made [this Makefile](https://github.com/kj-sh604/makefile-blog-article) to compile markdown to a usable HTML output — which streamlines the process.

Also! with the simpler design it makes it easier to manipulate pandoc css styling (for the few things you do need css for) 

[![Looks like crap, but! it works and it makes things easy for me](4.png)](4.png)
Looks like crap, but! it works and it makes things easy for me
\
\
[![Looks like crap, but! it works and it makes things easy for me — in light mode](5.png)](5.png)
Looks like crap, but! it works and it makes things easy for me — in light mode

so yeah! you're most definitely seeing the new one now and the old one is not coming back. This is more simple, plain, and actually suprisingly readable.


yeah… rss feed coming soon. I'm definitely going to rewrite this, because I'm so sleepy I'm writing this with one eye open.
\
\
\
[\> next article](../01082023rust-uutils-for-some-reason)\
[\< previous article](../01062023groff-and-catv-is-now-here)
\
\
[\<\< all articles](../../articles/)\
[\^ home](../../)
