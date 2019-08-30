---
layout: post
title: Important Notes
subtitle: Things to know for when things go wrong
tags: [test, important, error]
comments: true
---

{: .box-warning}
**Important!** IF YOU ARE MAKING THIS WEBSITE FOR A PROJECT PAGE (not for a user page), make sure you are pushing edits to the gh-pages branch, not the master branch!

![Github gh-pages push screenshot](/example-website/img/github-push-ghpages.png){: .center-block :}

## Image URLs

To know where images you upload are stored, and how to refer to them, it might be handy to understand [HTML File Paths](https://www.w3schools.com/Html/html_filepaths.asp). But, if you're uploading to the 'img' folder in your Github account, then the image is probably stored in:
~~~
/img/
~~~
When placing images inside of posts (i.e., the lines that start with an exclamation point) you may need to be more specific about the image location, most likely **only** if you are making a project page, not a user page!
~~~
/project-name/img/
~~~
