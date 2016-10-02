---
layout: post
title:  "Why I started new CI tool?"
date:   2016-07-30 18:18:18
categories: blog
comments: true
---

During my career as a devops in SCM team I've tested a lot of Continuous Integration systems. Personally QuickBuild is my favourite but this systems has its own problems. The most important ia problem with versioning build configurations. I need to write a lot of groovy code to maintain compatibility with older builds. I was thinking about system with QB powers like build promotion, parallel and sequential steps, build dependencies, etc. and versioning of build configuration in yaml file.

I've decided to write this system in Elixir programming language because I'm interested to functional programming and fan of ruby programming language. I'm writing code for my own satisfaction but I was glad if anyone would use esioci. Curently I'm only one and first user (yes I use esioci to build my personal C/C++ project ;))
