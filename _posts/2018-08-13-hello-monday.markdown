---
layout: post
title: "Hello, Monday"
date:   2018-08-13 00:00:00 -0600
categories: learn daily
---

# Hello, world!

I've been thinking about having a place to document my learnins instead of my notebooks and transient servers, and have tried to do it a few times but never really stuck with it... hopefully using Github Pages I'll make this routine to track progress of my projects, or at least use it as a pseudo wiki of sorts.
<br>
<br>

---
Minor note before we get started: this 'blog' is run on the static HTML generator [Jekyll](https://github.com/jekyll/jekyll) written in Ruby.

I learned a little neat thing about Jekyll in testing: tried to setup a 'test post' with a file of the format (YYYY-MM-DD-name-of-post.markdown) used inside of the _posts directory, it refused to be published until it was day of (local machine time)... kinda neat, makes it possible to write articles ahead of time and keep them from showing up until the day hits.
- It looks like there's a guard in place to [filter these 'publishable' posts](https://github.com/jekyll/jekyll/blob/035ea729ff5668dfc96e7f56a86d214e5a633291/lib/jekyll/readers/post_reader.rb#L41)... but why it didn't throw some notice in the log like it should is odd...
  - Maybe a discrepancy between time on my local machine and the hosting server at github? Or I'm missing something obvious at first glance?

---
<br>

Little things like the above are what I hope to tack in here.

We'll see how it goes.
