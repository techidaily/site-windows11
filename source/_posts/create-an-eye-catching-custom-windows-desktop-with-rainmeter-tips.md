---
title: Create an Eye-Catching Custom Windows Desktop with Rainmeter Tips
date: 2024-08-31T22:01:33.692Z
updated: 2024-09-01T22:01:33.692Z
tags:
  - windows
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/a-laptop-with-a-customized-rainmeter-screen.jpg
---

## Create an Eye-Catching Custom Windows Desktop with Rainmeter Tips

### Key Takeaways

* Rainmeter is a desktop customization tool for Windows that allows users to create custom skins, including widgets, visualizers, meters, and mini apps.
* Personalizing your desktop with Rainmeter is easy thanks to a strong community providing resources and thousands of skins for free.
* Customize your Rainmeter theme by editing INI files or using the GUI settings menu, allowing you to modify fonts, colors, layouts, and more.

 Rainmeter is the oldest desktop customization tool for Windows. It lets you create and display custom skins on your desktop—widgets, visualizers, meters, mini apps, you name it. With a few simple clicks, Rainmeter can totally change the look of your boring old Windows desktop.

##  What is Rainmeter and How to Install it

[Rainmeter](https://www.rainmeter.net/)is third-party software that allows you to create custom widgets, visualizations, and more for your desktop—all you need is the app and some time to kill.

 Rainmeter has a strong community built around it which shares resources and thousands of skins for free. The app is pretty lightweight and easy on your hardware resources, so the only limit is your imagination and creativity. I recommend checking out the [Rainmeter subreddit](https://www.reddit.com/r/Rainmeter/) or looking it up on [DeviantArt](https://www.deviantart.com/rainmeter) to see what others have created with it. I found these on the subreddit.

Close 

 If this showcase piques your interest, let’s go ahead and give Rainmeter a try on your computer. I’ll walk you through the step-by-step process of setting up a desktop using Rainmeter.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
###  Installing Rainmeter

 First, let’s install Rainmeter. You can do that using one of two ways: the command line or the regular executable installer.

 The simplest way is using the good old executable installer. Head over to the [Rainmeter download](https://www.rainmeter.net/) page and save the installer file anywhere on your computer.

 Double-click to launch the installer and click “Next” a bunch of times to complete the installation. Run Rainmeter when it’s done.

Close 

 Alternatively, you can use the command line if your system already has [Winget](https://activate-lock.techidaily.com/3-effective-ways-to-bypass-activation-lock-on-iphone-xs-by-drfone-ios/)or [Chocolatey](https://fox-boxes.techidaily.com/updated-luminouslabs-top-10-free-and-paid-filters-compare/) set up. If you don’t know what those are, Winget and Chocolatey are package managers that let you install apps with a single command (just like in Linux). I recommend setting up Winget on your computer to save yourself the hassle of installing apps the manual way.

 Open Powershell as Administrator, type the following command, and hit Enter.

winget install rainmeter

![Installing Rainmeter using Winget.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/ksnip_20240605-200229.png) 

 Wait for the installation to finish. Once done, search “rainmeter” in the Start menu to launch the app.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
###  Creating a Blank Canvas

 By default, Rainmeter comes with a few basic widgets, but we won’t be using them. So let’s clear up our desktop to make room for a fresh theme. Right-click on all the skins you see and click “Unload Skin” (a skin is just a self-contained widget or app, by the way).

Close 

 Now let’s hide the desktop icons. Right click anywhere on the desktop, hover over View, and uncheck “Show Desktop Icons.”

![Context menu for hiding desktop icons.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/ksnip_20240605-203230.png) 

 The only thing left to deal with is the Taskbar. You can set the Taskbar to auto-hide, but it will reappear when you hover the cursor near it. To auto-hide it, right-click on the taskbar and click “Taskbar Settings.” On the Settings page, toggle “Automatically Hide Taskbar in Desktop Mode.”

Close 

 With that, we have a completely blank canvas, ready for our theme.

![Blank desktop with hidden icons.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/ksnip_20240605-204005.png) 

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  How to Set Up a Base Theme

 Explore Deviantart, /r/Rainmeter, [Rainmeter forums](https://forum.rainmeter.net/), or [Flickr](https://www.flickr.com/groups/lifehacker-desktop-showandtell/pool/with/51233198009) to find skins and themes you like. I’m using a skin called Inside Dream. You can [download it](https://visualskins.com/skin/inside-dream) and follow along if you'd like, or grab your own.

 Once you’ve downloaded the archived package, extract it anywhere and double-click the file with the ".rmskin" extension. Click “Install” on the next dialog box.

Close 

 Launch Rainmeter, and you’ll find your newly installed theme in the right column. Click to expand it and view all the skins in the package. Select the ".ini" file and click “Load”. If the skin doesn’t automatically appear on the desktop, click “Refresh.” Repeat these steps to load as many skins as you want.

![Learning the Rainmeter interface.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/ksnip_20240605-215114.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
 You can drag to arrange skins in a layout of your choice. Be sure “Draggable” is checked for the active skin you’re trying to reposition (right-click on the skin to find that menu). Inside Dream replaced my desktop shortcuts with a shortcut bar and added a visualizer, clock, and greeting. The visualizer automatically picks up audio played from any app.

 There’s one more thing you need to know about skins: you’re not limited to a single Rainmeter package when building your design. You can actually install multiple themes and load skins from any of the installed packages to mix and match however you like. You can see the four Rainmeter packages that I have installed on my computer, though they're not all active. 

![Installed skins on Rainmeter.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/ksnip_20240628-134717.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
 I didn't like the visualizer skin in Inside Dream. It looked pretty but didn't have any music controls, s I installed a second package called [RetroColor](https://www.deviantart.com/apexxx-sensei/art/RetrOcOlOr-792148096) and loaded the music skin from it.

![Loading a music widget skin using Rainmeter.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/ksnip_20240628-134400.png) 

 The result could look something like this. but feel free to mix and match to create a design that works for you.

## ![Custom theme in Rainmeter.](https://static0.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/ksnip_20240628-135734.png) How to Customize Your Theme

 The base theme looks good, but it needs some tweaking to actually make it functional. There are two ways to customize a skin. You can either use the INI file, or you can use the GUI settings menu if the Rainmeter package supports it.

 In my setup, the Inside Dream package doesn’t have a dedicated settings menu. RetroColor does. However, both can be edited using the INI files for each skin. The INI files have the code underlying the skin that makes it work. You can edit it to make the skin your own.

 The settings on RetroColor are presented as just another skin. It lets you tweak some basic stuff like the clock formatting, temperature units, the media player of your choice (the player that connects with the media control widget), and the colors.

![Changing custom skin settings in Rainmeter.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/ksnip_20240628-140016.png) 

 The Inside Dream skin package doesn’t have a dedicated settings menu. You can only edit it using the INI files. I’m going to edit the dock shortcuts as an example. Right now the Photoshop button says "Photoshop CC" and doesn’t lead anywhere. Here’s how you can fix that shortcut.

 Right-click on the dock and click “Edit Skin.” Alternatively, select Dock.ini in the Rainmeter manager and click “Edit.”

Close 

 Dock.ini will open in Notepad. Locate the Photoshop shortcut in the text (you can use CTRL+F if you can’t find it). Replace the path to the shortcut with the shortcut to your installation of Photoshop, then save the INI file. There you have it. The dock shortcut has been updated, and it's working.

 Be sure to right-click on a skin and hit "Refresh" if it doesn't automatically update.

Close 

 You can replace or modify every UI element within a skin using the INI files. You can replace the fonts, colors, layouts, and more just by tweaking the code.

---

 Now you know how to give your Windows a makeover.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>


