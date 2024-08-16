---
title: Exploring App Instance Identifiers and Practices
date: 2024-08-15T15:40:17.879Z
updated: 2024-08-16T15:40:17.879Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Exploring App Instance Identifiers and Practices
excerpt: This Article Describes Exploring App Instance Identifiers and Practices
keywords: App ID Analysis,Identifier Usage,Instance Management,DevOps Best Practices,App Access Controls,Security in App IDs,API Key Strategies
thumbnail: https://thmb.techidaily.com/68d72132debc55d7a219d5ad96f3f8ade10f55eb90774e1fcb8b0eea83e6c871.png
---

## Exploring App Instance Identifiers and Practices

 If you're trying to open an app like Microsoft Paint in the Run Dialog and see an error message, it could be caused by your app aliases. But what exactly are App Execution Aliases, where do you find them, and how do you use them?

## What Are App Execution Aliases?

 An alias is an alternative name given to something. The most obvious example is the codename given to a spy or undercover agent. On Windows, aliases have nothing to do with spying. Instead, they are used for streamlining tasks, such as entering commands.

 Windows 10 and 11 both allow aliases to be declared for some apps by default. The available apps vary but are often those commonly associated with command line tools. Giving an app an alias allows it to be executed using a shorter title rather than the full name or path.

 App aliases can be used in several [Windows Command Line Interfaces](https://www.makeuseof.com/what-is-cli-what-does-it-stand-for/) (CLI), including the Run Dialog, Command Prompt, and [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) . If you use these tools with any regularity, app aliases can help to streamline entering commands.

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Enable App Execution Aliases in Settings

 You can enable and disable aliases for compatible apps in the main settings in both Windows 10 and 11\. If more than one app uses the same alias name, you can choose which has the alias applied to it.

In Windows 11:

1. Open**Settings > Apps** , and look for**Advanced app settings** .
2. In the advanced app settings, click**App execution aliases** to see the list of compatible apps.
3. Use the slider switches to enable or disable the alias for each app. You can see the alias name below each app.

![app aliases in windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win11.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->

In Windows 10:

1. If you're using Windows 10, you'll find the aliases in**Settings > Apps & features** .
2. Click the**App execution aliases** link near the top of the Apps & features page.
3. You can then enable and disable aliases using the switches.

![app aliases in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win10.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->

 By default, in both Windows 10 and 11, you can only enable or disable existing app aliases. But if you don't mind editing the Registry, you can create new aliases for many other apps.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->
## Create App Execution Aliases in Registry Editor

 Before editing or creating registry keys, it is advisable to [create a full backup of the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . Of course, you should also ensure you understand how to restore the Registry from that backup.

 The process below for creating app execution aliases in the Registry Editor should be the same in both Windows 10 and 11.

1. Open**Windows Search** , type**Registry Editor** , and click on the search result to open it.
2. In the editor, navigate to **HKEY\_CURRENT\_USER\\Software\\Microsoft\\Windows\\CurrentVersion\\App Paths** .
3. Next, right-click on the**App Paths** key in the left-hand pane, and select**New > Key** .
4. Give the new key an alias name that relates to the app and ends with .exe. For example, if the alias is for Calendar, call it something like cal.exe.
5. With the alias selected, double-click the**Default** value in the right-hand pane.  
![editing app aliases in registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-regedit.jpg)
<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. In the Value data field, you will need to enter the full path to the app executable file. For example**C:\\Program Files (x86)\\Calendar.exe** .
7. Right-click in the right pane and select**New > String value** . Name the string**path** . The change the Value data to the same path as above, but without the app filename.

 You can now close the Registry Editor. The new App Execution Alias will now be available to use in the Windows CLIs.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
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
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-the-ultimate-hits-for-tiktok-stardom/"><u>[New] In 2024, The Ultimate Hits for TikTok Stardom</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-master-guide-ultimate-tips-for-maximizing-mobizens-screen-capture/"><u>[New] Master Guide  Ultimate Tips for Maximizing Mobizen's Screen Capture</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-mastering-video-creation-filmoras-key-edits-for-lovers/"><u>[New] Mastering Video Creation  Filmora’s Key Edits for Lovers</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-smooth-sailing-on-instagram-bypass-video-issues/"><u>[New] Smooth Sailing on Instagram - Bypass Video Issues</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-easy-and-swift-face-blur-on-piscart-tools-at-hand/"><u>[Updated] 2024 Approved  Easy and Swift Face-Blur on PiscArt Tools at Hand</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-expert-level-techniques-in-video-spinning-and-joining-on-android/"><u>[Updated] Expert-Level Techniques in Video Spinning and Joining on Android</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-hand-tracking-mastery-all-methods-unveiled/"><u>[Updated] Hand-Tracking Mastery  All Methods Unveiled</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-two-titans-clash-in-the-vr-arena/"><u>[Updated] Two Titans Clash in the VR Arena</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-uncomplicated-multisnap-storytelling-on-snapchat-for-2024/"><u>[Updated] Uncomplicated Multisnap Storytelling on Snapchat for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/11-ways-to-fix-the-windows-search-bar-not-showing-or-working-on-windows-11/"><u>11 Ways to Fix the Windows Search Bar Not Showing or Working on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/5-ways-to-check-your-device-uptime-on-windows-11/"><u>5 Ways to Check Your Device Uptime on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/7-curious-design-choices-that-differ-from-w10/"><u>7 Curious Design Choices That Differ From W10</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-guide-to-tweaking-firewall-security/"><u>A Comprehensive Guide to Tweaking Firewall Security</u></a></li>
<li><a href="https://windows11.techidaily.com/a-simple-guide-for-correcting-lsassexe-issue/"><u>A Simple Guide for Correcting 'lsass.exe' Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/a-step-by-step-solution-for-spotify-connectivity-fails/"><u>A Step-by-Step Solution for Spotify Connectivity Fails</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerated-tactics-for-gaming-hardware-recognition/"><u>Accelerated Tactics for Gaming Hardware Recognition</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-screen-flickers-on-microsoft-os/"><u>Addressing Screen Flickers on Microsoft OS</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-11-key-inactivity-issues/"><u>Addressing Windows 11 Key Inactivity Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-proxy-in-windows-11-for-enhanced-privacy/"><u>Adjusting Proxy in Windows 11 for Enhanced Privacy</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-windows-11-identity-new-username-guide/"><u>Altering Windows 11 Identity: New UserName Guide</u></a></li>
<li><a href="https://win-amazing.techidaily.com/approach-combine-knowledge-of-arc-blow-causes-with-mitigation-strategies-discussed-earlier/"><u>Approach: Combine Knowledge of Arc Blow Causes with Mitigation Strategies Discussed Earlier</u></a></li>
<li><a href="https://windows11.techidaily.com/arcade-mode-for-window-users-key-fixes-ahead/"><u>Arcade Mode for Window Users: Key Fixes Ahead!</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-sound-service-reboot-hurdles-at-system-ignition/"><u>Avoiding Sound Service Reboot Hurdles at System Ignition</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-productivity-with-these-5-essential-windows-folder-practices/"><u>Boost Productivity with These 5 Essential Windows Folder Practices</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-boot-speed-with-simple-steps-in-windows-11-setup/"><u>Boosting Boot Speed with Simple Steps in Windows 11 Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/breach-limitation-threshold-unleash-higher-ethernet-speeds-on-windows/"><u>Breach Limitation Threshold: Unleash Higher Ethernet Speeds on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-roblox-error-262s-solutions/"><u>Breaking Down Roblox Error 262'S Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/changing-onedrive-storage-address-in-windows-10/"><u>Changing OneDrive Storage Address in Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-parsing-setback-code-0xc00ce556/"><u>Conquering Parsing Setback: Code 0xC00CE556</u></a></li>
<li><a href="https://windows11.techidaily.com/controlling-application-spaces-in-windows-task-mgr/"><u>Controlling Application Spaces in Windows Task Mgr</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-windows-misaligned-thx-audio-feedback/"><u>Correcting Windows' Misaligned THX Audio Feedback</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-windows-xc0f1103f-geforce-not-working/"><u>Correcting Windows' XC0F1103F GeForce Not Working</u></a></li>
<li><a href="https://windows11.techidaily.com/custom-menus-on-windows-1111-with-psoft-tools/"><u>Custom Menus on Windows 11/11 with PSoft Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-graphics-output-for-enhanced-clarity/"><u>Customizing Graphics Output for Enhanced Clarity</u></a></li>
<li><a href="https://win-answers.techidaily.com/dead-by-daylight-continuous-crashes-top-solutions-for-a-smooth-gaming-experience/"><u>Dead by Daylight Continuous Crashes? Top Solutions for a Smooth Gaming Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-and-disabling-read-only-properties-in-win11/"><u>Deciphering and Disabling Read-Only Properties in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-code-of-high-quality-visuals-with-windows-11-hdr/"><u>Deciphering the Code of High-Quality Visuals with Windows 11 HDR</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-why-many-dismiss-windows-11-now/"><u>Decoding Why Many Dismiss Windows 11 Now</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/delete-gmail-account-withwithout-password-on-poco-by-drfone-android/"><u>Delete Gmail Account With/Without Password On Poco</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-microsoft-family-safety-functions/"><u>Demystifying Microsoft Family Safety Functions</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-the-meaning-behind-windows-folders-x-marks/"><u>Demystifying: The Meaning Behind Windows' Folders X-Marks</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-microsoft-store-failure-codes-x800704cf/"><u>Disabling Microsoft Store Failure Codes X800704CF</u></a></li>
<li><a href="https://windows11.techidaily.com/ditching-unnecessary-wallpaper-icon-in-win11/"><u>Ditching Unnecessary Wallpaper Icon in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/1719361633854-enhance-your-pcs-screen-glow-with-these-fixes/"><u>Enhance Your PC's Screen Glow with These Fixes</u></a></li>
<li><a href="https://extra-hints.techidaily.com/from-mundane-to-magical-a-guide-to-chromatic-brilliance/"><u>From Mundane to Magical  A Guide to Chromatic Brilliance</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/hilarity-highway-the-funniest-youtube-videos-on-twitter-for-2024/"><u>Hilarity Highway  The Funniest YouTube Videos on Twitter for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-unlock-icloud-lock-on-your-apple-iphone-11-pro-max-and-ipad-by-drfone-ios/"><u>How to Unlock iCloud lock on your Apple iPhone 11 Pro Max and iPad?</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-dose-life360-notify-me-when-someone-checks-my-location-on-xiaomi-redmi-13c-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Dose Life360 Notify Me When Someone Checks My Location On Xiaomi Redmi 13C 5G? | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/install-epson-s50-series-driver-on-windows-7810-free-download/"><u>Install Epson S50 Series Driver on Windows 7/8/10 - Free Download</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/july-2press-update-exploring-the-top-13-free-disk-check-software-options/"><u>July 2Press Update: Exploring the Top 13 Free Disk Check Software Options</u></a></li>
<li><a href="https://screen-recording.techidaily.com/leading-cost-free-switch-gaming-apps-for-2024/"><u>Leading Cost-Free Switch Gaming Apps for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/1719265109241-master-google-chromes-filesync-on-your-windows-device-now/"><u>Master Google Chrome's Filesync on Your Windows Device Now</u></a></li>
<li><a href="https://windows11.techidaily.com/1719355454943-opera-installer-dilemma-on-windows-solutions-now/"><u>Opera Installer Dilemma on Windows - Solutions Now</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/precision-playbacks-mastering-4-methods-of-recording-on-xbox/"><u>Precision Playbacks  Mastering 4 Methods of Recording on Xbox</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-and-fixing-stuttering-playback-in-forza-horizon-5/"><u>Troubleshooting and Fixing Stuttering Playback in Forza Horizon 5</u></a></li>
</ul></div>
