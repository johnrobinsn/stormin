---
layout: post
title: Makin' Static...
comments: true
date: 2017-01-01 05:00:00 -0500
---

![Jekyll]({{ sitelurl }}/assets/jekyll_logo.png)

I've been using wordpress for my somewhat intermittent blog for well over ten years now, but for 2017 I wanted to give something new a try.  Don't get me wrong wordpress hasn't been all **_that_** bad...  But philosophically I am a big proponent of static delivery of services where possible.  When most folk set out to design a service they immediately want to stick an app server at it's center, when they would be better served to think about the stability and cacheability characteristics of their service and leverage that in their design.  Trading "just-in-time compute" for "precompute" lets you take better advantage of "plain old web servers" and edge caching for static object delivery.



So when I decided to dust off my blog recently, I surveyed the landscape to see what static blog/website tools were available.  Not too surprisingly, I decided to start this leg of my journey with [Jekyll](https://jekyllrb.com/).  [Jekyll](https://github.com/jekyll/jekyll) is the static website generator that powers github pages.  A static website generator takes your content, blog articles and configuration, and "compiles" it into a collection of static HTML/Javascript content that can be put on a plain old webserver and can be served up as static files.  Jekyll works well with [markdown](https://daringfireball.net/projects/markdown/) which is what I like to write in these days.  It is written in ruby, which _in an ideal world_ wouldn't matter except for the fact that the version of ruby that's installed on my El Capitan-based macbook pro is too old.  Since it's impolite (and probably ill-advised) to stomp on the system-installed version of ruby, I installed a ruby version manager, [rbenv](https://github.com/rbenv/rbenv).  This let me install a localized ruby install into my home directory.



After finally installing jekyll and poking around a bit, I've written my first _statically served_ blog entry for 2017.  **Yay!!**  For good measure I'm also serving the blog website out of github using github pages.  I'm up and running and it looks pretty good so far.  I'm still sorting out the best workflow and tuning things… I'll let you know how it goes.



> Note: For all of those that reached out to me about getting access to my old blog content… You can now get to it here.
>
> [http://wp.storminthecastle.com](http://wp.storminthecastle.com)



