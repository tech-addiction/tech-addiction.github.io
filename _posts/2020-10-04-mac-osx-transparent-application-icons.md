---
title: Mac OSX transparent application icons for less impulse usage
author: Tech-Addiction
date: 2020-10-04 14:00:00 -0400
categories: [Strategies]
tags: [macosx, icns]
pin: true
---

Whenever I open my computer, I have a certain goal in mind that I need to use the computer to accomplish. This is often quickly sidetracked by impulses to do other tasks, sometimes for the best and sometimes not. One of my goals to reduce tech addiction is to reduce the factors that play into these impulses.

Mac OSX has a dock which contains pinned applications and currently open applications. This is how a lot of people navigate to their applications. One of the downfalls of this approach is whenever you need to click on an icon, you are presented with other applications and their bright colorful icons which may impulse you to click on them.

Instead of navigating via the dock, here is another way. Cmd + Tab will let you cycle through your open applications. Cmd + Space will open the Finder which allows you to type in an application name to open it. This is faster than using your mouse to scroll over the dock and click the right application.

To prevent impulse clicking, I find that making applications just text instead of their original icons helps a lot. To do this you can replace all non system app icons with a transparent icon.


Here is an example of a cluttered dock with one transparent icon:
![Image of Cluttered Dock](https://tech-addiction.com/images/dock_with_one_empty.png)

Our goal is to replace all icons with transparent ones, such that if we view the dock there is no emotional connection of the icon to the application:
![Image of Transparent Dock](https://tech-addiction.com/images/dock_all_empty.png)

You can find the transparent.icns file [here on Github](https://github.com/tech-addiction/MacOSX-Transparent-Icns) or download a .zip of the files via [Direct Download](https://github.com/tech-addiction/MacOSX-Transparent-Icns/archive/main.zip)

Instructions how to use the transparent.icns file are [here on Github](https://github.com/tech-addiction/MacOSX-Transparent-Icns#usage).

Caveat: After Mac OSX 10.6 the icons for standard Mac OSX applications are read only and cannot be changed unless you turn off System Integrity Protection. I do not recommend doing that tho, instead I now just replace the icons on non standard applications.
