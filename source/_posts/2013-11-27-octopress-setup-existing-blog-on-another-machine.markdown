---
layout: post
title: "Octopress-Setup existing blog on another machine"
date: 2013-11-27 22:41
comments: true
categories: 
---
I am enjoying tinkering with [Octopress](http://octopress.org) and at present it feels like I will use it at-least for foreseeable future. And so today I decided to install Octopress on my other machine. It's a mac if you must ask. After setting up Octopress and pulling from my [Github](https://github.com/deepak-kapoor) repo, I was ready to make some changes to the blog. These are the steps I followed so that I could contribute to my existing Octopress blog which is hosted on Github.

{% codeblock %}
$ git clone http://github.com/deepak-kapoor/deepak-kapoor.github.io.git
$ cd deepak-kapoor.github.io.git
$ git checkout source
$ mkdir _deploy
$ cd _deploy
$ git init
$ git remote add origin http://github.com/deepak-kapoor/deepak-kapoor.github.io.git
$ git pull origin master
$ cd ..
{% endcodeblock %}
After this setup I was up and running. This is the first post from the new machine.