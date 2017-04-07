---
layout: post
title: "Pushing jekyll blog to github"
date: 2017-03-30
catergories: learning
---

# Problem
I have got a small blog up and running in Jekyll and now I want to publish that blog so that other people can see its contents.

This post is about pushing a Jekyll blog to github 'pages'

# What is Github Pages.

Github pages allows githubs users to host small websites on github, under the url 'http://username.github.com' *for free*.

Jekyll generates simple static websits, i.e. simple html sites. 

# Uploading a jekyll site to github pages

1. Create a github account if you dont already have one.

	Well dur... :p
2. Initialize your jekyll site as a git repository
{% highlight bash %}
    cd myBlog && git init
{% endhighlight %}
3. Add new origin for your git project.
{% highlight bash %}
    git remote add origin https://github.com/user/repo.git
{% endhighlight %}
or whatever your ssh url is.
4. push to github
