---
title: Objective-C
layout: post
---

I spent the last 2 days learning and building my first real iOS app. I say 'real' because it's the first app that was meant to be distributed versus just running from the simulator which is how I 'learned' Objective-C eons ago.

The first app is just a simple (hopefully cute) app for my niece to play with. I'll link it if I ever distribute it to the app store.
But the important thing is that the whole process was actually very insightful to me.

### A few positive things that I learned: ###
+ XCode is not too bad.
   + Startup time is ridiculously fast compared to other IDEs *cough* Intellij.
   + The bundled simulator is great! I wish the android one was as nice.
   + It's a really clever IDE! I love how it can simplify so many things such as the creation of outlets and tying actions to controllers.
+ Objective-C is not as bad as I thought. (Or maybe it's just growing on me)
   + It's still not a pretty language to look at (why are somethings dot notionable now and others aren't? what is up with that ugly block syntax?) but it doesn't repulse me as much as it did years ago.
   + It's a superset of C which means that I can still just drop into C whenever I like! That's great cause I've always had a soft spot in my heart for C.

### A few negative things that I learned: ###
- XCode is *terrible*.
   - The default keybindings are confusing and there's a few things that are just missing.
   - Where is reformat code??
   - Way too many options that need to be set just to [distribute an app.](https://developer.apple.com/library/ios/#documentation/Xcode/Conceptual/ios_development_workflow/000-Introduction/introduction.html#//apple_ref/doc/uid/TP40007959)
   - Minor complaint here by why is the home button missing when I switch to the iPhone 5 view in the simulator?.
   - Simple functionality seem to be missing from the tool. Like selecting a bunch of controls to create an outlet group. Instead you have to create it by adding them one at a time.
- iOS development tools doesn't do a great job of handling the different devices that support iOS.
   - Unless you do everything in the 'apple approved way' which usually involves using XCode like it was an interface builder, you will probably have problems getting a consistent look and feel between iPhone4 to iPhone5 muchless iPad.
   - One thing that I struggled with for a bit was just having an image that would center and stretch itself regardless of iOS version. Seems like a silly problem to have but even webdevelopment face this issue at times.

Most of these thoughts are probably just me being new to this still but it's a fun journey so far.
I'm actually looking forward to more complicated project ideas now. :)
