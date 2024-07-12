---
title: Correcting Unpredictable Power Estimator Display on Windows 11
date: 2024-07-11T21:30:31.172Z
updated: 2024-07-12T21:30:31.172Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting Unpredictable Power Estimator Display on Windows 11
excerpt: This Article Describes Correcting Unpredictable Power Estimator Display on Windows 11
keywords: Power Usage Monitoring,Windows 11 Performance Fix,Predictability in Energy Display,Unpredictable Energy Estimator,Optimize Windows Power Display,Improve Windows 11 Battery Life,Correcting Power Display Issues
thumbnail: https://thmb.techidaily.com/3fbb28fdd30ab5cd77a4baca2551c9d92b27e18215ac7c02404eb389cacb68b2.jpg
---

## Correcting Unpredictable Power Estimator Display on Windows 11

 Keeping track of how much charge remains in your laptop battery is easy. By default, hovering over the battery icon in the System Tray displays an estimate of battery time remaining, along with a percentage. Occasionally, the time estimate goes missing, leaving you to work out how much usage time you have left by percentage alone.

 Here's how to get that useful battery time remaining estimate showing again if it has vanished from your notebook.

## Where Did the Time Estimate Go?

 There are a few possible reasons why the time estimate has disappeared. The change often happens after upgrading to Windows 11, but even simply updating the OS can cause it. A later update may fix the issue, but that isn't always the case.

![battery icon tooltip in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/battery-time.jpg)

 It isn't entirely obvious what the root cause is. It could be a conflict in the Registry, which can occur during the update process. It also seems to have been deliberately disabled by Microsoft in some updates. Perhaps because the company is working on power and battery settings for a future update.

## How to Enable the Battery Time Estimate in the Registry

 Whatever the cause of its disappearance, the battery time estimate is still part of the OS. And with a bit of Registry tweaking, it can be brought back into view.

 As always, it is a good idea to [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you make any changes. This is only a minor edit and shouldn't cause problems, but it's better to be safe than sorry.

1. Click Windows Search and type**Regedit** to find the Registry Editor. You don't need to choose Run as Administrator. Just select the search result.
2. With the Registry Editor open, navigate to: **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Power** .
3. If there is no**Power** key, right-click on**Control** in the navigation panel, and select**New > Key** . Name the new registry key**Power** .  
![power values in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-key.jpg)
4. Right-click the Power key and select**New > DWORD (32-bit) Value** . Set the name of this DWORD as**EnergyEstimationEnabled** .
5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .
7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out [how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

## Fix a Missing Battery Time Estimate on Windows

 Not being able to easily see the estimate of battery time remaining probably isn't going to keep you up at night. But it is a handy feature if using your laptop away from a power source. Luckily, a few minutes spent editing the Registry will fix the problem, so you always know how long it will be before your battery dies.


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
<li><a href="https://windows11.techidaily.com/top-10-uses-for-windows-powertoys-tools/"><u>Top 10 Uses for Windows PowerToys Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-clutter-software-uninstallation-tricks-for-windows-11-106-chars/"><u>Eliminating Clutter: Software Uninstallation Tricks for Windows 11 (106 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-windows-updates-0x80242016-hurdles/"><u>Avoiding Windows Update's 0X80242016 Hurdles</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/how-to-create-captions-in-final-cut-pro-x-a-comprehensive-guide-for-2024/"><u>How to Create Captions in Final Cut Pro X A Comprehensive Guide for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-savvy-buyers-guide-to-finding-windows-11-deals/"><u>The Savvy Buyer's Guide to Finding Windows 11 Deals</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/graphics-drivers-restored-no-more-errors/"><u>Graphics Drivers Restored, No More Errors</u></a></li>
<li><a href="https://printer-issues.techidaily.com/repairing-unresponsive-printers/"><u>Repairing Unresponsive Printers</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-down-energy-waste-without-slowing-down-games/"><u>Cutting Down Energy Waste Without Slowing Down Games</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-xiaomi-redmi-note-12-proplus-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Xiaomi Redmi Note 12 Pro+ 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/what-is-a-keygen-examining-its-impacts-and-cleanup-techniques-for-pcs/"><u>What Is a Keygen? Examining Its Impacts and Cleanup Techniques for PCs</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-unpacking-features-a-deep-dive-into-free2xs-tools/"><u>[New] 2024 Approved  Unpacking Features  A Deep Dive Into Free2X's Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-windows-operations-formulating-and-scrutinizing-reports/"><u>Understanding Windows Operations: Formulating & Scrutinizing Reports</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-non-compliance-overcoming-intel-hd-graphics-errors/"><u>Addressing Non-Compliance: Overcoming Intel HD Graphics Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/a-stepwise-guide-to-banishing-the-onedrive-icon-from-explorer/"><u>A Stepwise Guide to Banishing the OneDrive Icon From Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-back-color-to-extend-volume-option-in-diskmgmt/"><u>Bring Back Color to Extend Volume Option in DiskMgmt</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-mastering-the-art-of-leaving-a-discord-server/"><u>[New] Mastering the Art of Leaving a Discord Server</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/how-can-you-use-clownfish-voice-changer-on-discord-fortnite-skype/"><u>How Can You Use Clownfish Voice Changer on Discord/ Fortnite/ Skype</u></a></li>
<li><a href="https://animation-videos.techidaily.com/are-you-head-over-heels-with-3d-animation-design-for-2024/"><u>Are You Head Over Heels With 3D Animation Design for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-non-admin-privilege-levels-in-windows-os/"><u>Adjusting Non-Admin Privilege Levels in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/9-ways-to-fix-the-0x8004def5-onedrive-error-code-on-windows-11/"><u>9 Ways to Fix the 0X8004def5 OneDrive Error Code on Windows 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-close-up-confidence-navigating-google-meets-zoom-feature/"><u>[New] Close-Up Confidence  Navigating Google Meet's Zoom Feature</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-track-imei-number-of-realme-gt-3-through-google-earth-by-drfone-android/"><u>In 2024, How To Track IMEI Number Of Realme GT 3 Through Google Earth?</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-windows-11-stumbling-blocks-the-most-crucial-tips/"><u>Avoiding Windows 11 Stumbling Blocks: The Most Crucial Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-to-rectify-windows-security-faults/"><u>Comprehensive Guide to Rectify Windows Security Faults</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-ultimate-tutorial-on-winning-spotify-advertising-for-2024/"><u>The Ultimate Tutorial on Winning Spotify Advertising for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/2024-approved-the-ultimate-avs-video-editor-review-a-beginners-guide/"><u>2024 Approved The Ultimate AVS Video Editor Review A Beginners Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-windows-11s-functionality-top-strategies-for-widget-upgrades/"><u>Enhancing Windows 11'S Functionality: Top Strategies for Widget Upgrades</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-times-ticking-off-align-it-back/"><u>Windows Time's Ticking Off? Align It Back!</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-cutting-edge-tips-for-drone-video-refining/"><u>2024 Approved  Cutting-Edge Tips for Drone Video Refining</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-facts-you-need-to-know-about-screen-mirroring-nokia-g310-drfone-by-drfone-android/"><u>3 Facts You Need to Know about Screen Mirroring Nokia G310 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-to-managing-comic-files-in-windows-11/"><u>Comprehensive Guide to Managing Comic Files in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-power-of-search-implementing-it-in-win11s-task-monitor/"><u>Unlock the Power of Search: Implementing It in Win11's Task Monitor</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-fix-pokemon-go-route-not-working-on-infinix-smart-8-pro-drfone-by-drfone-virtual-android/"><u>How to Fix Pokemon Go Route Not Working On Infinix Smart 8 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-turn-off-corner-shaping/"><u>Mastering Windows 11: Turn Off Corner Shaping</u></a></li>
<li><a href="https://windows11.techidaily.com/unmasking-profit-making-mechanisms-for-w11-at-microsoft/"><u>Unmasking Profit Making Mechanisms for W11 at Microsoft</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-windows-cars-keyboard-magic-boosts-speed/"><u>Top 5 Windows Cars: Keyboard Magic Boosts Speed</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-top-video-editing-software-for-windows-imovie-equivalent-2023/"><u>New 2024 Approved Top Video Editing Software for Windows IMovie Equivalent 2023</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-pioneers-shaping-the-future-of-vr-experiences/"><u>[Updated] Pioneers Shaping The Future Of VR Experiences</u></a></li>
<li><a href="https://driver-install.techidaily.com/flawless-functionality-windows-11-and-new-acer-drivers/"><u>Flawless Functionality: Windows 11 & New Acer Drivers</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-uncovering-tiktoks-hidden-block-list/"><u>In 2024, Uncovering TikTok's Hidden Block List</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-access-your-fb-links-easily-download-8-best-online-utilities/"><u>[New] In 2024, Access Your FB Links Easily  Download 8 Best Online Utilities</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-dream-team-top-windows-apps-for-a-winning-start/"><u>Digital Dream Team: Top Windows Apps for a Winning Start</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-enhance-creativity-in-video-editing-these-7-sources/"><u>[Updated] Enhance Creativity in Video Editing - These 7 Sources</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-personalize-with-direct-drawing/"><u>Windows 11: Personalize with Direct Drawing</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-error-code-x80131500-at-store/"><u>Breaking Down Error Code: X80131500 at Store</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-fn-keys-to-maximize-pc-efficiency-in-wins/"><u>Customizing FN Keys to Maximize PC Efficiency in Wins</u></a></li>
<li><a href="https://location-fake.techidaily.com/4-methods-to-turn-off-life-360-on-poco-x6-pro-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>4 Methods to Turn off Life 360 On Poco X6 Pro without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-your-view-simple-fixes-for-windows-11-screen-haze/"><u>Transform Your View: Simple Fixes for Windows 11 Screen Haze</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-instantaneous-windows-photo-explorer/"><u>In 2024, Instantaneous Windows Photo Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-using-windows-11s-compatibility-fixer/"><u>Essential Guide to Using Windows 11’S Compatibility Fixer</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-top-5-chromebook-sniping-apps-essential-clients-reviewed/"><u>In 2024, Top 5 Chromebook Sniping Apps  Essential Clients Reviewed</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-unheard-voices-on-youtube-livestream-success-beyond-1000-supporters/"><u>[Updated] In 2024, Unheard Voices on YouTube  Livestream Success Beyond 1000 Supporters</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-your-windows-10-past-insights-on-activity-logs/"><u>Unlocking Your Windows 10 Past: Insights on Activity Logs</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/all-about-stardew-valley-on-the-mysterious-ginger-island/"><u>All About Stardew Valley on the Mysterious Ginger Island</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-error-trouble-with-compatibility-tool-here-are-quick-solutions/"><u>Windows Error: Trouble with Compatibility Tool? Here Are Quick Solutions.</u></a></li>
</ul></div>
