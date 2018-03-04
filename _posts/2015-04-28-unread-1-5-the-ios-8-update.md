---
id: 893
title: 'Unread 1.5: The iOS 8 Update'
date: 2015-04-28T10:24:35+00:00
author: Zaid Syed
layout: post
guid: http://zaidsyed.com/blog/?p=893
permalink: /2015/04/28/unread-1-5-the-ios-8-update/
image: /blog/images/IMG_1224.png
---
<img src="http://zaidsyed.com/images/IMG_1224.png" alt="IMG 1224" title="IMG_1224.png" border="0" width="599" height="528" />
  
Unread is one of the best RSS readers available for iOS today. Originally created by [Jared Sinclair](http://jaredsinclair.com/archived-unread "Unread - Jared Sinclar"), and acquired by Supertop in late 2014, it’s come a long way since the original version shipped by Sinclair in early 2014.

For the unacquainted, Unread is a beautiful RSS reader, featuring beautiful typography, a swipe-based reading interface, and emphasis on the beauty of words. The swipe-based interface is especially forward-thinking. Even with the gigantic iPhone 6 Plus, support for lazy swiping<sup id="fnref-893-1"><a href="#fn-893-1" rel="footnote">1</a></sup> means that you can save a lot of thumb-ache.

Today’s update to Unread is a pretty major one, and it’s really great.

Here’s Supertop’s release notes on Unread 1.5:

> [NEW](#) Readability is now available from article view. Enjoy the full text of truncated posts or linked pages from linked list blogs in Unread&#8217;s article interface.
    
> [NEW](#) Fully integrated native iOS 8 sharing.
    
> [NEW](#) 1Password extension integration to get your accounts set up quickly and logging in to paywalled sites in the browser.
    
> [NEW](#) The &#8220;actions&#8221; option of the accessibility rotor now lets you perform relevant actions, such as &#8220;Star&#8221;, &#8220;Mark Read&#8221;, etc.
    
> [NEW](#) Font upgrades: Cyrillic and Greek character sets are now supported.
    
> [CHANGE](#) Images now go full screen on single tap, tap and hold for options.
    
> [CHANGE](#) In-app browser no longer maintains full history through restarts.
    
> [CHANGE](#) Self-signed SSL certs for Fever are now accepted.
    
> [CHANGE](#) After adding an account, Unread no longer pushes on the account dashboard.
    
> [CHANGE](#) When notifications appear, VoiceOver now reads them out.
    
> [CHANGE](#) Fever now works with self signed certificates.
    
> [FIX](#) Swiping back from the web view works reliably.
    
> [FIX](#) Unread can now share gifs properly (previously only the first frame was shared).
    
> [FIX](#) A bug where the article view could go blank on when returning to the app is fixed.
    
> [FIX](#) AirPlay stream no longer stops when the screen locks.
    
> [FIX](#) Mute switch no longer affects audio when playing back media from blog posts.
    
> [FIX](#) Line spacing for multi-line &#8216;sup&#8217; text in articles is now legible.
    
> [FIX](#) Some ordered list numbers were getting clipped on the left.
    
> [FIX](#) Release Notes screen now opens properly.
    
> [FIX](#) Cache size can no longer get far too big.
    
> [FIX](#) Huge internal refactor to make iPad and iPhone apps build off the same project: this will hugely reduce the overhead for future updates and features. Note: They are still separate apps on the store.
    
> [FIX](#) Improve reliability of internal article database, fixing a bunch of crashes.
    
> [FIX](#) Feedly could silently stop updating.
    
> [FIX](#) Sign in now works properly with keyboard shortcuts when tapping between fields.
    
> [FIX](#) VoiceOver no longer reads elements from views behind the current view.
    
> [FIX](#) Corrections to accessibility text on Unlock and Tutorial screens.
    
> [FIX](#) Background fetch now cancels itself if it runs out of time, so iOS doesn&#8217;t kill the app.
    
> We also spent a lot of time not making a Watch app. We love our new wrist computers but reading articles on them is just silly.
    
> Massive thanks to our friends Jim (@jim&#95;rutherford) and Glen (@slaine&#95;) who helped us out with this release.
    
> We have put a lot of work into this free update. If this makes you happy, you can tip us in the app and leave us a nice review on the App Store. 

There’s a lot to digest from that. Here’s a quick summary.

> [NEW](#) Readability is now available from article view. Enjoy the full text of truncated posts or linked pages from linked list blogs in Unread&#8217;s article interface. 

This is a godsend. I love linked list blogs, but Unread hasn’t had proper support for them. When reading my RSS at night, with dark mode enabled, I hate having to switch to the built-in browser to read the article linked. With Readability available on article views, directly shows linked posts in Unread’s view. This is also helpful if you subscribe to a feed which only shows truncated posts, like [iDownloadBlog](idownloadblog.com "iDownloadBlog").

> [NEW](#) Fully integrated native iOS 8 sharing.
    
> [NEW](#) 1Password extension integration to get your accounts set up quickly and logging in to paywalled sites in the browser. 

You may be surprised to hear that an app like Unread has only added native iOS 8 sharing now. Previously, to use this in Unread, you’d have to swipe right for sharing options, go through a custom share sheet, and then tap “More…” to access the native share sheet. The custom share sheet is gone, and now when you tap “Share” only the native share sheet will be shown. Though Apple’s UI doesn’t match Unread’s it’s still a very welcome update.

Also new in this version of Unread is _proper_ support for the 1Password extension. Prior to this, tapping the “1Password” button when allowing Unread to access an RSS service like Feedly used 1Password’s built-in URL schemes to view your credentials. Then, you were left alone to copy the password and switch back to Unread. It wasn’t a huge problem, but it’s dated and pre-iOS 8 <sup id="fnref-893-2"><a href="#fn-893-2" rel="footnote">2</a></sup>.

Now, Unread makes use of 1Password’s iOS 8 extension. This means you not only save time switching between apps (rather than the extension appearing in a modal view as it does now), but also get a much cleaner experience. You can use this to sign up with your RSS services, and also log in to paywalled (websites requiring you to subscribe to read) websites.

There’s also an indication to Supertop’s future plans regarding Unread hidden in their release notes.

> We also spent a lot of time not making a Watch app. We love our new wrist computers but reading articles on them is just silly. 

Touché.

Unread 1.5 is available on the App Store as freemium (and separate) apps for [iPhone](https://itunes.apple.com/app/id911364254 "Unread for iPhone") and [iPad](https://itunes.apple.com/us/app/unread-for-ipad-rss-news-reader/id911472824 "Unread for iPad").

<li id="fn-893-1">
  Swiping right-to-left on an articles brings up sharing options rather than stretching your thumb to reach clunky toolbars.&#160;<a href="#fnref-893-1" rev="footnote">&#8617;</a>
</li>
<li id="fn-893-2">
  Although I wished more apps did this pre-iOS 8.&#160;<a href="#fnref-893-2" rev="footnote">&#8617;</a> </fn></footnotes>