---
title: Interpreting Launch Identifiers for Applications
date: 2024-07-29T04:21:27.914Z
updated: 2024-07-30T04:21:27.914Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Interpreting Launch Identifiers for Applications
excerpt: This Article Describes Interpreting Launch Identifiers for Applications
keywords: Launch ID Explained,App Identifier Meaning,Launch Significance,Understanding Launch Codes,Launch Keyword Guide,Decoding Launch Symbols,App Launch Reference
thumbnail: https://thmb.techidaily.com/23dc4857279699198e48a622a7713386fd30f7f47908caf6a0fe50229057f885.jpg
---

## Interpreting Launch Identifiers for Applications

 If you're trying to open an app like Microsoft Paint in the Run Dialog and see an error message, it could be caused by your app aliases. But what exactly are App Execution Aliases, where do you find them, and how do you use them?

## What Are App Execution Aliases?

 An alias is an alternative name given to something. The most obvious example is the codename given to a spy or undercover agent. On Windows, aliases have nothing to do with spying. Instead, they are used for streamlining tasks, such as entering commands.

 Windows 10 and 11 both allow aliases to be declared for some apps by default. The available apps vary but are often those commonly associated with command line tools. Giving an app an alias allows it to be executed using a shorter title rather than the full name or path.

 App aliases can be used in several [Windows Command Line Interfaces](https://www.makeuseof.com/what-is-cli-what-does-it-stand-for/) (CLI), including the Run Dialog, Command Prompt, and [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) . If you use these tools with any regularity, app aliases can help to streamline entering commands.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Enable App Execution Aliases in Settings

 You can enable and disable aliases for compatible apps in the main settings in both Windows 10 and 11\. If more than one app uses the same alias name, you can choose which has the alias applied to it.

In Windows 11:

1. Open**Settings > Apps** , and look for**Advanced app settings** .
2. In the advanced app settings, click**App execution aliases** to see the list of compatible apps.
3. Use the slider switches to enable or disable the alias for each app. You can see the alias name below each app.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->
![app aliases in windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win11.jpg)

In Windows 10:

1. If you're using Windows 10, you'll find the aliases in**Settings > Apps & features** .
2. Click the**App execution aliases** link near the top of the Apps & features page.
3. You can then enable and disable aliases using the switches.

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![app aliases in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win10.jpg)

 By default, in both Windows 10 and 11, you can only enable or disable existing app aliases. But if you don't mind editing the Registry, you can create new aliases for many other apps.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
## Create App Execution Aliases in Registry Editor

 Before editing or creating registry keys, it is advisable to [create a full backup of the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . Of course, you should also ensure you understand how to restore the Registry from that backup.

 The process below for creating app execution aliases in the Registry Editor should be the same in both Windows 10 and 11.

1. Open**Windows Search** , type**Registry Editor** , and click on the search result to open it.
2. In the editor, navigate to **HKEY\_CURRENT\_USER\\Software\\Microsoft\\Windows\\CurrentVersion\\App Paths** .
3. Next, right-click on the**App Paths** key in the left-hand pane, and select**New > Key** .
4. Give the new key an alias name that relates to the app and ends with .exe. For example, if the alias is for Calendar, call it something like cal.exe.
5. With the alias selected, double-click the**Default** value in the right-hand pane.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
![editing app aliases in registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-regedit.jpg)
6. In the Value data field, you will need to enter the full path to the app executable file. For example**C:\\Program Files (x86)\\Calendar.exe** .
7. Right-click in the right pane and select**New > String value** . Name the string**path** . The change the Value data to the same path as above, but without the app filename.

 You can now close the Registry Editor. The new App Execution Alias will now be available to use in the Windows CLIs.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Using and Creating App Execution Aliases

 Entering commands into tools such as Command Prompt and PowerShell can be laborious. You can streamline that process by enabling or creating aliases for apps that commonly feature in those commands. Why type out a full path to an executable file when you can point to it with a few keystrokes?


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





<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-distribute-your-videos-a-vimeo-guide/"><u>[New] 2024 Approved  Distribute Your Videos  A Vimeo Guide</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-trailblazing-the-future-of-3d-color-grading-tools/"><u>[New] Trailblazing the Future of 3D Color Grading Tools</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-instagrams-video-content-regulations-simplified/"><u>[Updated] In 2024, Instagram's Video Content Regulations Simplified</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-seamless-video-transmission-success-in-facebook-messengers-iphoneandroid/"><u>[Updated] In 2024, Seamless Video Transmission Success in Facebook Messengers, iPhone/Android</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-art-of-video-edits-easy-techniques-on-your-windows-pc/"><u>[Updated] The Art of Video Edits  Easy Techniques on Your Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/5-strategies-for-resolving-the-no-support-windows-error/"><u>5 Strategies for Resolving the No-Support Windows Error</u></a></li>
<li><a href="https://howto.techidaily.com/8-workable-fixes-to-the-sim-not-provisioned-mm2-error-on-poco-c55-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Workable Fixes to the SIM not provisioned MM#2 Error on Poco C55 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-missing-sign-in-screens-in-windows-11/"><u>Bypassing Missing Sign-In Screens in Windows 11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-messages-files-on-itel-by-fonelab-android-recover-messages/"><u>Complete guide for recovering messages files on Itel</u></a></li>
<li><a href="https://windows11.techidaily.com/confronting-windows-search-failure-a-fixers-manual/"><u>Confronting Windows Search Failure: A Fixer's Manual</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-computer-recovery-top-10-tactics/"><u>Conquering Computer Recovery: Top 10 Tactics</u></a></li>
<li><a href="https://windows11.techidaily.com/debunking-myths-the-necessity-and-risks-of-pagefilesys/"><u>Debunking Myths: The Necessity and Risks of Pagefile.sys</u></a></li>
<li><a href="https://windows11.techidaily.com/five-innovative-ways-to-personalize-windows-11-search/"><u>Five Innovative Ways to Personalize Windows 11 Search</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-persistent-vscode-crashes-on-windows-11/"><u>Fixing Persistent VSCode Crashes on Windows 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/guide-to-premium-google-pixel-tones/"><u>Guide to Premium Google Pixel Tones</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-to-erase-steam-dns-information-on-pc/"><u>Guidelines to Erase Steam DNS Information on PC</u></a></li>
<li><a href="https://screen-capture.techidaily.com/high-quality-video-calling-solutions-top-10-best-apps-ranked/"><u>High-Quality Video Calling Solutions  Top 10 Best Apps Ranked</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-increase-virtual-memory-tips-and-tricks-for-windows-11/"><u>How to Increase Virtual Memory: Tips & Tricks for Windows 11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-step-by-step-iphone-ringer-update-guide/"><u>In 2024, Step-by-Step  IPhone Ringer Update Guide</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-things-you-must-know-for-screen-mirroring-apple-iphone-14-drfone-by-drfone-ios/"><u>In 2024, Things You Must Know for Screen Mirroring Apple iPhone 14 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-batch-filename-changes-with-powertoys/"><u>Mastering Batch-Filename Changes with PowerToys</u></a></li>
<li><a href="https://windows11.techidaily.com/1719278005537-mastery-of-solutions-for-non-operational-wwinplusp-in-pc/"><u>Mastery of Solutions for Non-Operational WWin+P in PC.</u></a></li>
<li><a href="https://windows11.techidaily.com/moment-by-moment-synchronize-windows-clock/"><u>Moment by Moment: Synchronize Windows Clock</u></a></li>
<li><a href="https://windows11.techidaily.com/never-disable-wins-11-notifications-why/"><u>Never Disable Wins 11 Notifications: Why?</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-obstacles-inaccessible-network-router-interface/"><u>Overcoming Obstacles: Inaccessible Network Router Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/premium-collection-winning-windows-dsswitch-emulators-list/"><u>Premium Collection: Winning Windows DS/Switch Emulators List</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-to-mending-directdraw-glitches-in-11-series-oses/"><u>Quick Guide to Mending DirectDraw Glitches in 11-Series OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagining-taskbar-functionality-essential-upgrades-to-improve-microsofts-user-interface/"><u>Reimagining Taskbar Functionality: Essential Upgrades to Improve Microsoft's User Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/revive-hidden-desktop-icons-on-the-latest-windows/"><u>Revive Hidden Desktop Icons on the Latest Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-disabled-remove-option-for-pin-access-control/"><u>Reviving Disabled 'Remove' Option for PIN Access Control</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-ensure-optimal-functionality-of-add-ons-in-windows-os/"><u>Strategies to Ensure Optimal Functionality of Add-Ons in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-windows-notepad-malfunctions/"><u>Taming Windows Notepad Malfunctions</u></a></li>
<li><a href="https://windows11.techidaily.com/the-offline-warriors-guide-to-microsoft-onedrive/"><u>The Offline Warrior's Guide to Microsoft OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-silent-reading-mode-on-ms-word-for-win-users/"><u>Troubleshooting Silent Reading Mode on MS Word for Win Users</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/updated-how-to-translate-video-from-japanese-to-english-online-in-2024/"><u>Updated How To Translate Video From Japanese to English Online, In 2024</u></a></li>
</ul></div>
