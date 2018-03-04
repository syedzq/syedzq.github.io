---
id: 1112
title: 'GA.TODAY for OS X: Google Analytics in Your Notification Center'
date: 2015-07-03T08:15:31+00:00
author: Zaid Syed
layout: post
guid: http://zaidsyed.com/?p=1112
permalink: /2015/07/03/ga-today-for-os-x-google-analytics-in-your-notification-center/
---
![](http://zaidsyed.com/images/ga-today-osx/ga-today-osx-1.png "GA.TODAY for OS X")
  
[Ryan Brink](https://twitter.com/ry_brink "Ryan Brink on Twitter") is back with the OS X version of GA.TODAY, the iOS version I’ve written [previously](http://zaidsyed.com/2015/01/12/ga-today-google-analytics-in-the-today-view/ "GA.TODAY: Google Analytics in the Today View on Command-Z") about.

GA.TODAY is a Today view widget for OS X’s Notification Center. OS X Yosemite brought a plethora of APIs allowing developers to extend their apps into the system, including sharing extensions, actions, and Today widgets.

After the success of [GA.TODAY for iOS](https://itunes.apple.com/us/app/ga.today/id936871747 "GA.TODAY for iOS"), Ryan Brink has brought GA.TODAY to the Mac, with the same features in a slightly better design.

Like most widget-first apps, when you first launch the ‘app’, GA.TODAY only allows you to login to your Google Analytics account — the majority of the development has taken place outside the app, in the Today widget.

Logging in to GA.TODAY is seamless and smooth. Instead of having custom username and password fields, Brink implemented a non-native modal window for logging in, which not only is more secure (implementing Google’s OAuth), but also plays friendly with two-factor authentication, without which you’d have to create app password deep into Google account settings. My only peeve with Brink’s implementation is the lack of support for keyboard shortcuts; the lack of the native ‘Edit’ menu has meant that it’s not possible to `⌘V` a password from 1Password or another password manager into the password field. It’s not much of an issue, especially when taking into account that this is a process you’d only have to got through once.
  
![](http://zaidsyed.com/images/ga-today-osx/ga-today-osx-2.png "Simple, at first.")
  
Once you’re logged in, you don’t need to open the app anymore, but rather, add the GA.TODAY widget in Notification Center. At first, the widget may seem simple — too simple. The widget shows a list of all your sites configured with Google Analytics, as well as, in accordance with the philosophy of the _Today_ view, page views and users from today, and current users.
  
![](http://zaidsyed.com/images/ga-today-osx/ga-today-osx-3.png)
  
Easy to miss, however, is the dropdown to reveal a ton of other statistics. Clicking the arrow next to the site shows beautifully organized graphs and charts plotting various data: page views and users per day, week, and month, all graphed. A pie chart shows where users are coming from, which is great for launch-day statistics for a new video, blog post or product launch. Recently, I published a [new interview on Yellow Signal](http://yellowsignal.com/interview-felicien-francois-developer-of-tweakstyle/ "Interview: Félicien François, Developer of TweakStyle"), and GA.TODAY helped us see how much attention the interview was accumulating, and from what sources traffic was coming from.

Clicking “More…” open the Google Analytics web app in the default browser, which is a nice touch.

GA.TODAY also allows the user to rearrange the order of sites in the Notification Center, available by clicking the information (i) button in the widget.

Unfortunately, GA.TODAY’s view preferences are reset when the Notification Center closes, which is a slight annoyance.

GA.TODAY doesn’t show everything; simplicity is one of my favorite aspects about this app. I’ve barely used some of the other features Google Analytics shows. Ultimately, GA.TODAY is for someone who doesn’t use all the features Analytics provides, but likes well-designed, native apps that feel at home on OS X.

GA.TODAY is a solid product, especially for a 1.0 product. In the future, I’d like to see some more information added, with options for users to rearrange and organize information.

GA.TODAY is available on the [Mac App Store for $1.99](https://itunes.apple.com/hk/app/ga.today-widget-for-google/id1006846646 "GA.TODAY on the Mac App Store.").