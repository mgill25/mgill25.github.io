---
layout: post
title: "Tortoise - An HTML Template Engine"
date: 2014-08-25 12:38:08
categories: code
tags: code projects python jinja tortoise
---

I've been working on a simple Template Engine, inspired from [Jinja2]. I call it
[Tortoise!]

[![Presenting][image]][Tortoise!]

So far, it supports all the basics that you would expect in Jinja or any similar template
engine, variables, conditionals, loops and such. I plan on adding some more jinja fancyness like filters, loaders,
and context processors as well!

My motivation for writing Tortoise was to understand some of the inner workings of Jinja2 (and other
Pocoo projects as well), so in the course of writing this, I went source-diving into Jinja2 code and 
learned quite a few tricks along the way. I might not have made use of those things in the code for Tortoise,
but the overall structure remains the same. A Lexer and a Parser, which generates the final HTML as output.

Also, shout-out to Alex Michael's [Microtemplates] code, the structure of which I stole shamelessly! :)

[Tortoise!]:https://github.com/NCR-Python/tortoise
[image]:http://i.imgur.com/TuPAib6.jpg
[Jinja2]: http://jinja.pocoo.org/
[Microtemplates]: http://alexmic.net/building-a-template-engine/
