---
title: The Significance of Aliases in Application Launches
date: 2024-08-22T21:42:03.641Z
updated: 2024-08-23T21:42:03.641Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Significance of Aliases in Application Launches
excerpt: This Article Describes The Significance of Aliases in Application Launches
keywords: Alias Importance,App Launch Identity,Username Advantage,Launching With Alias,Secure User Sign-In,Identity Protection,Safe Login Alternative
thumbnail: https://thmb.techidaily.com/d4d65dffa6d108b05861c08e391929dff0db7f6ebc3e8d7f9915a07380165e20.jpg
---

## The Significance of Aliases in Application Launches

 If you're trying to open an app like Microsoft Paint in the Run Dialog and see an error message, it could be caused by your app aliases. But what exactly are App Execution Aliases, where do you find them, and how do you use them?

## What Are App Execution Aliases?

 An alias is an alternative name given to something. The most obvious example is the codename given to a spy or undercover agent. On Windows, aliases have nothing to do with spying. Instead, they are used for streamlining tasks, such as entering commands.

 Windows 10 and 11 both allow aliases to be declared for some apps by default. The available apps vary but are often those commonly associated with command line tools. Giving an app an alias allows it to be executed using a shorter title rather than the full name or path.

 App aliases can be used in several[Windows Command Line Interfaces](https://www.makeuseof.com/what-is-cli-what-does-it-stand-for/) (CLI), including the Run Dialog, Command Prompt, and[PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) . If you use these tools with any regularity, app aliases can help to streamline entering commands.

## How to Enable App Execution Aliases in Settings

 You can enable and disable aliases for compatible apps in the main settings in both Windows 10 and 11\. If more than one app uses the same alias name, you can choose which has the alias applied to it.

In Windows 11:

1. Open**Settings > Apps** , and look for**Advanced app settings** .
2. In the advanced app settings, click**App execution aliases** to see the list of compatible apps.
3. Use the slider switches to enable or disable the alias for each app. You can see the alias name below each app.

![app aliases in windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win11.jpg)

In Windows 10:

1. If you're using Windows 10, you'll find the aliases in**Settings > Apps & features** .
2. Click the**App execution aliases** link near the top of the Apps & features page.
3. You can then enable and disable aliases using the switches.

![app aliases in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win10.jpg)

 By default, in both Windows 10 and 11, you can only enable or disable existing app aliases. But if you don't mind editing the Registry, you can create new aliases for many other apps.

<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Create App Execution Aliases in Registry Editor

 Before editing or creating registry keys, it is advisable to[create a full backup of the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . Of course, you should also ensure you understand how to restore the Registry from that backup.

 The process below for creating app execution aliases in the Registry Editor should be the same in both Windows 10 and 11.

1. Open**Windows Search** , type**Registry Editor** , and click on the search result to open it.
2. In the editor, navigate to **HKEY\_CURRENT\_USER\\Software\\Microsoft\\Windows\\CurrentVersion\\App Paths** .
3. Next, right-click on the**App Paths** key in the left-hand pane, and select**New > Key** .
4. Give the new key an alias name that relates to the app and ends with .exe. For example, if the alias is for Calendar, call it something like cal.exe.
5. With the alias selected, double-click the**Default** value in the right-hand pane.  
![editing app aliases in registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-regedit.jpg)
6. In the Value data field, you will need to enter the full path to the app executable file. For example**C:\\Program Files (x86)\\Calendar.exe** .
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Right-click in the right pane and select**New > String value** . Name the string**path** . The change the Value data to the same path as above, but without the app filename.

 You can now close the Registry Editor. The new App Execution Alias will now be available to use in the Windows CLIs.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-buy-youtube-subscribers-hundreds-of-subscribers-for-5/"><u>[New] 2024 Approved  Buy YouTube Subscribers - Hundreds of Subscribers for $5?</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-mastery-of-microscopic-minecraft-mapping/"><u>[New] Mastery of Microscopic Minecraft Mapping</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-unraveling-the-enigma-creating-hidden-snapstories/"><u>[Updated] In 2024, Unraveling the Enigma  Creating Hidden Snapstories</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-top-places-to-find-background-music-for-videos/"><u>[Updated] Top Places to Find Background Music for Videos</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-unlocking-the-potential-of-aiseesoft-for-video-documentation-for-2024/"><u>[Updated] Unlocking the Potential of Aiseesoft for Video Documentation for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-top-rated-dj-templates-free-access-for-music-makers/"><u>2024 Approved  Top-Rated DJ Templates  Free Access for Music Makers</u></a></li>
<li><a href="https://windows11.techidaily.com/5-great-free-podcast-editing-programs-for-windows/"><u>5 Great Free Podcast Editing Programs for Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/9-best-phone-monitoring-apps-for-xiaomi-redmi-13c-5g-drfone-by-drfone-virtual-android/"><u>9 Best Phone Monitoring Apps for Xiaomi Redmi 13C 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-list-of-10-ways-to-fine-tune-windows-11-screens/"><u>A Comprehensive List of 10 Ways to Fine-Tune Windows 11 Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-a-clean-desktop-with-automatic-trash-emptying-in-windows/"><u>Achieve a Clean Desktop with Automatic Trash Emptying in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-crisp-visuals-leveraging-background-blur-in-w11s-photos-app/"><u>Achieve Crisp Visuals: Leveraging Background Blur in W11's Photos App</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-code-0x887a0006-for-gpu-stalls-windows/"><u>Addressing Code 0X887A0006 for GPU Stalls Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-cpu-overload-with-wmi-service-tweaks/"><u>Addressing Cpu Overload with WMI Service Tweaks</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-settings-for-smooth-run-as-functionality/"><u>Adjusting Settings for Smooth 'Run As' Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/audio-capture-while-screen-recording-with-snipping-tool-max-156/"><u>Audio Capture While Screen Recording with Snipping Tool (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/automation-made-simple-windows-task-scheduler-batch/"><u>Automation Made Simple: Windows Task Scheduler Batch</u></a></li>
<li><a href="https://windows11.techidaily.com/becoming-an-expert-learner-with-these-7-windowing-strategies/"><u>Becoming an Expert Learner with These 7 Windowing Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/bless-your-pc-god-mode-enhancements/"><u>Bless Your PC: God Mode Enhancements</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-clarity-with-these-budget-friendly-tools/"><u>Boost Clarity with These Budget-Friendly Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-efficiency-with-top-practices-for-wsl-2-usage-on-pcs/"><u>Boost Efficiency with Top Practices for WSL 2 Usage on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-back-your-teams-screens/"><u>Bring Back Your Teams Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-black-screen-in-win11-fast-and-straightforward/"><u>Bypass Black Screen in Win11, Fast & Straightforward</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-the-gpsvc-wait-issue-on-pcs/"><u>Bypassing the GPSVC Wait Issue on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/calculating-wattage-your-windows-pcs-electricity-needs/"><u>Calculating Wattage: Your Windows PC’s Electricity Needs</u></a></li>
<li><a href="https://windows11.techidaily.com/clarifying-the-concept-of-windows-ram-caching/"><u>Clarifying the Concept of Window's RAM Caching</u></a></li>
<li><a href="https://windows11.techidaily.com/classic-game-storage-integrating-into-the-windows-photos-space/"><u>Classic Game Storage: Integrating Into the Windows Photos Space</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-chrome-display-glitches-on-pc/"><u>Clearing Chrome Display Glitches on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-color-issues-in-legacy-bios/"><u>Clearing Up Color Issues in Legacy BIOS</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-windows-11s-obstacle-overcoming-error-code-22/"><u>Clearing Windows 11'S Obstacle: Overcoming Error Code 22</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensible-guide-to-revoking-custom-search-on-windows-11/"><u>Comprehensible Guide to Revoking Custom Search on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/convenient-telnet-setup-for-modern-windows-systems-wins/"><u>Convenient Telnet Setup for Modern Windows Systems (Wins)</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-non-deletable-keys-a-windows-guide/"><u>Correcting Non-Deletable Keys: A Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-a-user-friendly-guide-for-shortcut-placement-on-desktop/"><u>Crafting a User-Friendly Guide for Shortcut Placement on Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-windows-11-a-guide-to-a-unique-environment/"><u>Customizing Windows 11: A Guide to a Unique Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-windows-cab-and-its-method-for-installed-content/"><u>Deciphering Windows CAB & Its Method for Installed Content</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-ftdibussys-a-windows-memory-security-paradox/"><u>Decoding ftdibus.sys: A Windows Memory Security Paradox</u></a></li>
<li><a href="https://windows11.techidaily.com/delve-into-multi-display-setup-in-windows-11/"><u>Delve Into Multi-Display Setup in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-what-windows-11s-new-updates-signify-for-users/"><u>Delving Into What Windows 11'S New Updates Signify For Users</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-resource-locks-in-windows-11-environments/"><u>Disabling Resource Locks in Windows 11 Environments</u></a></li>
<li><a href="https://windows11.techidaily.com/dive-into-windows-11-auditory-setup-and-use/"><u>Dive Into Windows 11 Auditory Setup and Use</u></a></li>
<li><a href="https://tech-haven.techidaily.com/enhance-your-android-phone-with-voice-control-capabilities-using-the-latest-voicegpt-app/"><u>Enhance Your Android Phone with Voice Control Capabilities Using the Latest VoiceGPT App</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-earn-on-youtube-beginners-path-to-profitability/"><u>In 2024, Earn on YouTube  Beginner's Path to Profitability</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-uncomplicated-guide-to-shooting-breatomed-time-lapses-with-gopro-hero5-black/"><u>In 2024, The Uncomplicated Guide to Shooting Breatomed Time-Lapses with GoPro Hero5 Black</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-will-the-ipogo-get-you-banned-and-how-to-solve-it-on-vivo-t2x-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Will the iPogo Get You Banned and How to Solve It On Vivo T2x 5G | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/inside-scoop-whats-next-for-the-new-m4-mac-mini-price-estimates-and-specs-unveiled/"><u>Inside Scoop: What's Next for the New M4 Mac Mini – Price Estimates and Specs Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/1719306890834-key-collectors-rejoice-get-the-perfect-pair-of-keys-and-essential-windows-11-612lifetime/"><u>Key Collectors Rejoice – Get the Perfect Pair of Keys & Essential Windows 11, $6.12/Lifetime</u></a></li>
<li><a href="https://extra-tips.techidaily.com/lightroom-guide-blending-high-dynamic-range-magic/"><u>Lightroom Guide  Blending High Dynamic Range Magic</u></a></li>
<li><a href="https://fix-guide.techidaily.com/proven-ways-to-fix-there-was-a-problem-parsing-the-package-on-oneplus-ace-2v-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Proven Ways to Fix There Was A Problem Parsing the Package on OnePlus Ace 2V | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/self-repair-options-to-optimize-your-windows-11-machine-easily/"><u>Self-Repair Options to Optimize Your Windows 11 Machine Easily</u></a></li>
</ul></div>
