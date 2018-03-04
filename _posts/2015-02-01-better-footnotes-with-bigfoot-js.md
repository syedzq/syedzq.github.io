---
id: 438
title: Better Footnotes with Bigfoot.js
date: 2015-02-01T13:57:11+00:00
author: Zaid Syed
layout: post
guid: http://zaidsyed.com/blog/?p=438
permalink: /2015/02/01/better-footnotes-with-bigfoot-js/
---
You may have noticed a few design changes over the past few days on Command-Z, such as the new unified header in lieu of a sidebar, and a footer. These changes not only look better, but prepare the site for a responsive design coming up soon.

One of the smaller changes you may have noticed is the addition of **dynamic footnotes**. Footnotes now appear like this[[1]](#fn-1 "see footnote"){#fnref-1.footnote}. By clicking on it, a simple popover tooltip appears. It doesn&#8217;t interrupt your reading, and keeps the flow of the piece going. I tried doing this earlier with [AJS Footnotes](https://wordpress.org/plugins/ajs-footnotes/), a WordPress plugin. The syntax for calling the script was simple enough &#8211; put the footnote text inside a double parenthesis – &#8220;((footnote text))&#8221; – the script would simply convert this into normal MultiMarkdown footnotes, but also enable a tooltip that pops up when the reader hovers on the footnote text. The script wasn&#8217;t very reliable nor as smooth as I would have liked. I also wanted to stick to MultiMarkdown syntax as much as I could, so that when I previewed my writing in [Marked 2](https://itunes.apple.com/us/app/marked-2/id890031187?mt=12), the previewed text would be as close as possible to the actual published content.

I was envious of the way sites like [Marco.org](http://marco.org) and [Six Colors](http://sixcolors.com) handled their footnotes – beautiful footnotes, which, when you clicked them, opened up a beautiful popup tooltip with the footnote content. I found out later that this was possible through a simple jQuery plugin named [Bigfoot.js](http://www.bigfootjs.com).

Bigfoot.js is based on how [Instapaper](http://www.instapaper.com) handles footnotes, and handles simple footnote markup[[2]](#fn-2 "see footnote"){#fnref-2.footnote} and gets rid of the footnote list at the bottom of the post (though that is optional), and simply shows a footnote through an ellipsis \[&#8230;\] (or a number) button you can click to view the footnote. It&#8217;s a simple and easy way to view footnotes without cluttering your post.

Bigfoot.js also has a lot of customizability and actions you can implement in addition to styling your footnote buttons and the footnotes themselves. Two of my favorites are `actionOriginalFN` and `numberResetSelector`. `actionOriginalFN` allows you to set what the plugin does with the original footnote list as the bottom of posts. You can hide them (using the CSS declaration `display: none`, delete them, or keep them as they are. I choose to keep them for our friends on older browsers. `numberResetSelector` resets the numbers for numbered footnotes at the start of the element chosen. So, if I set `numberResetSelector` to `.post`, every time an element with the `.post` class ends, the number counter for footnotes resets, which means that the next post which footnotes starts at 1, and doesn&#8217;t continue from the previous post, if they are displayed on the same page.

If you are a blogger and use footnotes a lot, you should definitely check out [Bigfoot.js](http://www.bigfootjs.com).

<li id="fn-1">
  It really is much better. <a href="#fnref-1" title="return to article" class="reversefootnote">&#160;&#8617;</a>
</li>
<li id="fn-2">
  In WordPress, you can use footnotes with Markdown by connecting your WordPress.org site to <a href="http://jetpack.me">Jetpack</a>. By enabling the Markdown module in Jetpack settings, you can use MultiMarkdown footnote syntax in WordPress. <a href="#fnref-2" title="return to article" class="reversefootnote">&#160;&#8617;</a> </fn></footnotes>