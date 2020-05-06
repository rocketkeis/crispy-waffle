---
layout: post                          # (required)
title: Hello World                    # (required)
date: 2020-04-29 11:00:00 +0800       # (required)
categories: [others]                  # (custom) must have corresponding file in categories/
tags: [first]                         # (custom) tags only for meta `property="article:tag"`
---

Trying out this Jekyll theme.

This repo is actually created on this day, but the markdown files are just some stuff I have lying around in my folders. The timestamps are not exact since I had only taken note of the dates.

## Inserting images

`<img src="{{ site.baseurl }}/images/best-dogs.jpg" alt="Best Dogs" width="400">`

<img src="{{ site.baseurl }}/images/best-dogs.jpg" alt="Best Dogs" width="400">

`![best dogs]({{ site.baseurl }}/images/best-dogs.jpg)`

![best dogs]({{ site.baseurl }}/images/best-dogs.jpg)

## Inserting links to other posts

`[Which Bugs to Prioritize](2020-04-24-which-bugs-to-prioritize.md)`

[Which Bugs to Prioritize](2020-04-24-which-bugs-to-prioritize.md)
