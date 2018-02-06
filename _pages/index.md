---
permalink: /index.html
layout: default
title: Home
---

{% assign post = site.posts.first %}

<div class="logo">
	<img src="/img/logo.svg" alt="Scriptkitties">
</div>

## About
Scriptkitties is an online community of people who share a passion for free
software promotion and development.

* Latest post: [{{ post.title }}]({{ post.url }}) ({{ post.date | date: "%-d %B %Y" }})

### IRC
Our main communication platform is IRC.  Our current main channel is
`#scriptkitties` on [Freenode](https://freenode.net/). Those who are recognized
as official Scriptkitties members have `+V` on this channel. Some of them can
also be recognized outside of the channel, with their `@scriptkitties/nickname`
hostmask.

## Projects
We work on a number of projects, which can all be found on
[Github](https://github.com/scriptkitties/). All our projects are completely
free as in freedom, using only free software licenses.
