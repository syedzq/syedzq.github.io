---
id: 682
title: 'CloudClip Review: A Free Clipboard Management Service for iOS and Mac'
date: 2015-02-19T14:17:48+00:00
author: Zaid Syed
layout: post
guid: http://zaidsyed.com/blog/?p=682
permalink: /2015/02/19/cloudclip-review-a-free-clipboard-management-service-for-ios-and-mac/
---
![CloudClip Review: A Free Clipboard Management Service for iOS and Mac](http://zaidsyed.com/images/cloudclip-review/cloudclip-presentation.png)
  
While I was reading Federico Viticci&#8217;s excellent [iPad Air 2 Review](http://www.macstories.net/stories/ipad-air-2-review-why-the-ipad-became-my-main-computer/), I was suddenly tempted to use an iPad. Viticci&#8217;s article is not exactly a review, but rather an explanation as to why Federico uses an iPad for his work. It&#8217;s so eloquently written, that, as Myke Hurley sums up in [Connected #25](http://www.relay.fm/connected/25), “did a better job of making me want an iPad than Apple ever did.”

So, yesterday, I dug up the old third-generation family iPad (this is from 2012) and started to reformat it to my needs. I installed the various apps I had on my iPhone that I wanted to use on the larger display. Apps like [Instapaper](https://itunes.apple.com/us/app/instapaper/id288545208?mt=8) and [Unread](https://itunes.apple.com/app/id911364254) come to mind. When I got around to downloading [Scribe](https://itunes.apple.com/en/app/scribe-copy-anything.../id789738555), my cross-platform clipboard manager of choice, I realized it was not universal, and had no iPad-optimized version. Of course, when I was strictly iPhone-and-Mac only, this problem hadn&#8217;t existed.

I absolutely detest using an app scaled up to 2x, with an incongruent aspect ratio, so I found myself in the market for an alternative. I tried out [Clips](https://itunes.apple.com/en/app/clips-copy-paste-anywhere/id917638056?mt=8) and I liked it a lot – I even shelled over two bucks for the Pro version with syncing between iPad and iPhone. After using it for a week, I still knew that I needed the clipboard management system I chose to have OS X support, too, since I was now using all of Apple&#8217;s three major product lines &#8211; the Mac, iPad _and_ the iPhone, I had to make sure that the clipboard manager I chose could sync my clipboard history between my three devices. So I created a list of criteria that I needed my new clipboard manager of choice to have:

  * It should have native apps for all three platforms, preferably with an established syncing system in place; 
  * It should be either free or cost less than $5 in total for all three platforms, as I&#8217;m a student with not much disposable income;
  
    And the least important one, 
  * It should have a good design and should integrate with the OS well. 

After spending a good half hour on “research”, I found what I think, on paper, may be the best service that satisfied all of my criteria to a well enough degree: [CloudClip, by Thinkbitz Software Studio](http://cloudclipapp.com). It&#8217;s not mentioned a lot by the people I follow, and doesn&#8217;t seem to be very popular, but it seemed to be the best out of the other apps I tried out.

CloudClip is built around the idea of syncing everything and anything. You don&#8217;t have to curate what you copy, it&#8217;s built more like a beautiful dumping ground for all your links and clips. CloudClip&#8217;s purpose is to sync your clipboard history between your &#8220;iOS devices and your Mac&#8221;. In this way, it still treats the Mac like the hub of all your content, as Apple&#8217;s ideology was, pre-2011 before the introduction of iCloud, after which the Mac was just another device, with the cloud being the &#8220;content hub&#8221;.
  
![CloudClip's UI.](http://zaidsyed.com/images/cloudclip-review/cloudclip-ipad.png)
  
It&#8217;s fairly easy to set up. You can download the universal (!) app from the [App Store](https://itunes.apple.com/us/app/cloudclip/id563356503), and it only takes a few minutes due to the low size (4.1MB) of the app.

When you first open CloudClip for iOS, you&#8217;re presented with a simple introduction to what the app does:
  
![A simple introduction to the app's features upon first launch.](http://zaidsyed.com/images/cloudclip-review/cloudclip-introduction.gif)
  
As you can see from the GIF above, it shows the features of the service in an easy-to-digest format.

Here&#8217;s the gist of what you can do with CloudClip:

  * Share text between your iOS devices and your Mac; 
  * Interact with clips by tapping on them to copy them, or by swiping to take action to them or delete them, and: 
  * Use Quick Buttons to quickly act on certain recognized text formats — for example, URLs will be recognized, and tapping the Quick Button next to the clip allows you to open the URL in Safari. 

Conveniently, this review is organized based on the three main features of the service.

## Syncing

Setting up CloudClip on iOS apps is straightforward, and the same can be said for the Mac version. You can download it from its own [App Store](https://itunes.apple.com/us/app/cloudclip-manager/id563362017?mt=12) — under the name &#8220;CloudClip Manager&#8221;. However, since CloudClip seems to be iOS-first, its Mac counterpart doesn&#8217;t look nearly as nice as the mobile app, especially since it&#8217;s a menu bar app. It doesn&#8217;t even feature the same introduction. You&#8217;re very much meant to start from iOS.

![The Mac app is a simple menu bar applet that runs in the background.](http://zaidsyed.com/images/cloudclip-review/cloudclip-mac.png)

CloudClip syncs using iCloud, and although it doesn&#8217;t have any other syncing options, such as through Wi-Fi, Bluetooth, or even Dropbox, iCloud worked fine for me – most of the time. The first few times, it handled the syncing well, and in under 10 seconds. Shortly after, it started to choke, as I connected my third-generation iPad to iCloud Drive, and ended up having various duplicates as well as certain clips which didn&#8217;t sync at all. Even though it syncs using iCloud, using apps like the afore-mentioned Clips worked well with sync, so the problem may lie either in CloudClip&#8217;s implementation of CloudKit, or more likely, my iPad was not suitable for CloudClip&#8217;s syncing. Since the syncing feature is the core feature of CloudClip, I was really forced to reconsider my usage of this service, since it couldn&#8217;t sync properly to my iPad<sup id="fnref-682-2"><a href="#fn-682-2" rel="footnote">1</a></sup>.

CloudClip doesn&#8217;t offer easy clipping integration for iOS 8. To clip text in iOS, you have to copy the text wanted, and open the app, which is not the most efficient way to add clips – I preferred the Action Extensions and Today View widget of Clips rather than CloudClip&#8217;s &#8216;primitive&#8217; clipping feature. However, a feature which isn&#8217;t shown at all in the app is the URL scheme – `cloudclip://add/(url encoded text)`. It&#8217;s a fairly simple scheme, and serves me well, as I&#8217;ve created Launch Center Pro actions, Draft actions and even a [Workflow](https://itunes.apple.com/us/app/workflow-powerful-automation/id915249334?mt=8) to enable a crude action extension for it. It simply allows you to select text in an app like Safari, and perform the action on it, and saves it to CloudClip. You can download the workflow [here](https://workflow.is/workflows/854bedf6da0845848b0ee9a310a1ab79) I&#8217;m glad the app developer included the URL scheme, but probably should update CloudClip to implement iOS action extensions so that non-power users can also get in some of the&#8230;action<sup id="fnref-682-3"><a href="#fn-682-3" rel="footnote">2</a></sup>.

CloudClip&#8217;s syncing feature is dependent on iCloud, and while it may not work with older devices, such as my third-generation iPad, it&#8217;s solid and syncs very quickly. As for the clipping process itself, you have to go the extra mile and download or create your own workflow to integrate with CloudClip&#8217;s URL scheme, but it works for, and that&#8217;s what matters. However, CloudClip&#8217;s more advanced features are probably geared towards pro-users like myself.

## Interacting with Clips in CloudClip

CloudClip also presents an easy way to copy text from their app. On iOS, you simply tap the clip to copy, whereas on Mac, you can click the clip to copy it to the device&#8217;s clipboard.

CloudClip also advertises a way to take action to your clips – although it&#8217;s very limited. On iOS, you slide a clip over, and you get two options: you can delete the clip, commonplace for a lot of apps using UITableView, such as Mail or Messages, and a &#8216;More&#8217; section:

![CloudClip's limited action menu.](http://zaidsyed.com/images/cloudclip-review/cloudclip-action-menu.gif)

This section gives you four options: you can, once again, copy a clip, &#8220;View Details&#8221; (I&#8217;ll get back to this one later), message the text or email it, both straightforward.

As you can see, there&#8217;s sadly no integration with iOS 8&#8217;s universal share sheets<sup id="fnref-682-4"><a href="#fn-682-4" rel="footnote">3</a></sup>, which is unfortunate – as a developer myself, I know that it&#8217;s not very difficult to integrate iOS 8&#8217;s share sheet with `UIActivityViewController`.

What does &#8220;View Details&#8221; do? This:
  
![View Details. I'm not sure what it does.](http://zaidsyed.com/images/cloudclip-review/cloudclip-view-details.png)

Essentially, it opens the clip in a new view, and tells you the time and date it was clipped – again no other integrations.

## Quick Buttons

One of my favorite features is how CloudClip sorts clips into different types, with different ways of taking action to them. Tapping the clip copies it, but pressing the button to the right allows you to take action to it — links open in Safari<sup id="fnref-682-1"><a href="#fn-682-1" rel="footnote">4</a></sup>, addresses in Maps, longer clips can be expanded, phone numbers can be dialed, and email addresses can be emailed to. CloudClip not only stores _all_ your clips, but also scans them to allow you to take action on them as fast as possible.

CloudClip recognizes five types of text clips: long text clips, links to web pages, both location and email addresses and phone numbers. Long text clips open in the (pretty useless) &#8220;View Details&#8221; view, web pages in Safari, email addresses opens Mail&#8217;s compose sheet with an email directed to that email addresses, addresses open in Maps, and phone numbers start a new call with the clipped phone number. On the Mac app, you are given to options: Open and Copy. By clicking &#8220;Open&#8221; you can launch the clipping in the appropriate app, with the exception of phone numbers, which is worrying as a) they do not even get synced to the Mac app, and b) because OS X Yosemite allows you to place calls through your iPhone.

Nevertheless, it&#8217;s a great feature that saves time when you just need to open the clip in the most logical app.

## Other Features

There are a few preferences in the settings that are worth going over:

**&#8220;Clear All Clips&#8221;** – Lets you clear all clippings. Doing so on once device erases them all on other devices.

**&#8220;Automatically Add Clips&#8221;** – Allows you to toggle whether or not CloudClip automatically imports your clipboard when you launch the app on iOS, or whenever you copy (⌘C/X) something on your Mac.

**&#8220;Run In Background&#8221;** &#8211; iOS only. The app can still add clips while it&#8217;s running in the background for a few minutes. I&#8217;d rather it just use Background App Refresh. It also notifies you when the app&#8217;s background state expires, so you can open it _again_ to sustain the background processes.

**&#8220;Ignore 1Password&#8221;** &#8211; OS X only. CloudClip ignores any copying you do from 1Password, so that your passwords don&#8217;t randomly show up in CloudClip when you have Automatically Add Clips enabled. It&#8217;s a nice option, and well thought-out.

But by far the best preference in the settings panel is the ability to set default apps for Quick Buttons to open clips to. On iOS, you can set a default browser and a default maps app. The Mac version doesn&#8217;t have this feature, presumably because you can set a universal default browser.

So far, I&#8217;ve tried this feature with five browsers: Safari (obviously), Google Chrome, Dolphin, Puffin Browser and Opera Mini. Out of these five, CloudClip recognized three: Safari, Chrome and Dolphin.

As for the default maps app, it recognized Apple Maps and Google Maps, but not Waze, also a popular choice among people.

## Wrap-Up

We can revisit the criteria I stated that I needed in a clipboard manager to see if CloudClip is a good clipboard management app.

The first criterion was whether it had native apps for all three devices, with a good syncing system. It did, even though the Mac app wasn&#8217;t exactly that creative. The sync worked well with two of my devices – the iPhone and the Mac, however, not the most important one, the iPad. Even though it may be the iPad&#8217;s fault, this may mean I cannot go on using this service if this continues to happen after the iPad gets fixed.

My second criterion was the price. It&#8217;s completely free, and not ad-supported, which means I do not have to worry about having limited features or about losing any money. However, by paying for a more robust solution. As I mentioned before, if Clips ends up gaining Mac support, nothing&#8217;s going to stop me from switching back, not even a price tag.

Lastly, I needed it to have a nice design with good integration with the system. It does have a nice design, and skin-deep integration. But that&#8217;s not enough for my needs. I was unable to find a better solution that satisfied all three criteria.

If you don&#8217;t care about pricing, but just want a good clipboard manager for all three platforms, you can check out the amazing [Command-C](http://danilo.to/command-c) by Danilo Torrisi. Until then, I&#8217;m gonna keep waiting until Clips gets OS X support.

But for free, CloudClip is still an amazing tool with a good design.

CloudClip is available completely for free on the [iOS](https://itunes.apple.com/us/app/cloudclip/id563356503) and [Mac App Stores](https://itunes.apple.com/us/app/cloudclip-manager/id563362017?mt=12).

<li id="fn-682-2">
  It was technically my iPad&#8217;s fault. Later on, I found that the sleep/wake button on my iPad stopped working, so when I used AssistiveTouch to power it off, I was unable to turn it back on. After that, CloudClip&#8217;s syncing worked really well between my Mac and my iPhone.&#160;<a href="#fnref-682-2" rev="footnote">&#8617;</a>
</li>
<li id="fn-682-3">
  Pun not intended.&#160;<a href="#fnref-682-3" rev="footnote">&#8617;</a>
</li>
<li id="fn-682-4">
  I&#8217;ve actually checked when the app was last updated – September 20. However, it only fixed crashes on iOS 8 and added iPhone 6/6 Plus support, as well as pull to refresh. It looks like the huge features that came with iOS 8 was not a high priority for the developer (who I couldn&#8217;t get in touch with).&#160;<a href="#fnref-682-4" rev="footnote">&#8617;</a>
</li>
<li id="fn-682-1">
  Or your browser of choice — CloudClip allows you to choose both a preferred browser <em>and</em> a preferred maps application for addresses.&#160;<a href="#fnref-682-1" rev="footnote">&#8617;</a> </fn></footnotes>