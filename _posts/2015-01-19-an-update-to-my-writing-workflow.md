---
id: 370
title: An Update to My Writing Workflow
date: 2015-01-19T13:12:39+00:00
author: Zaid Syed
layout: post
guid: http://zaidsyed.com/blog/?p=370
permalink: /2015/01/19/an-update-to-my-writing-workflow/
---
Readers of my blog know that I have two types of posts: articles and linked list posts. Articles are your average usually lengthy posts I write somewhat infrequently, which I write in [Typed](http://realmacsoftware.com/typed), my Markdown editor of choice. I then copy over my Markdown code (or the HTML source) onto a WordPress post, add categories and publish it &#8211; straightforward enough.

For linked list posts (when you click on the title, it takes you to another article or website), I usually had a more convoluted process. The plugin I use for linked list posts ([DFLL by YJSoon](http://yjsoon.com/dfll-plugin)) offers a custom field option in which I paste the URL of the article or website I want to link to. I then write the body of the text, include a blockquote of the most interesting part of the article, and usually write a paragraph or two offering my thoughts on it. It&#8217;s served me well, but it&#8217;s a bit cumbersome, which is why I&#8217;m a bit lazy on publishing linked list posts frequently.

Recently I found a WordPress feature called &#8216;Press This&#8217; &#8211; found in the &#8216;Writing&#8217; section of the WordPress admin settings, when enabled, it&#8217;s a bookmarklet you can drag to your bookmarks bar (à la [Command-C](http://danilo.to/command-c)). When you&#8217;re browsing an article you like, clicking the bookmarklet instantly opens a new window containing an &#8216;Add New Post&#8217; editor from WordPress. It automatically scrapes the title and URL of the webpage and contains a link to the webpage in question on the first line of the document. It&#8217;s even better when you select an interesting paragraph on the webpage and click the bookmarklet &#8211; the editor now also contains the quote in blockquote format.

Since DFLL has support for &#8216;Press This&#8217;, it automatically makes the link of the webpage the linked list URL, and removes it from the document. I can then add whatever commentary I have on the webpage or article, before publishing it &#8211; much more of a timesaver.

I did, however, experience a problem with the bookmarklet. It runs some JavaScript code upon click, parsing the metadata of the webpage and populating the WordPress editor with the title and URL of the webpage. And error in the bookmarklet prevented any websites not hosted on the same domain from being &#8220;pressed&#8221;.

I managed to resolve the issue by replacing `u='+e(l.href)+'` from the JavaScript with `u='+e(l.href.replace(/\//g,'\\/'))+'`.

It finally worked, and has definitely shaved off a few minutes of work in creating linked list posts.