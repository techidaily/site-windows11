---
title: Add Compatibility Tool to Windows' Quick Access
date: 2024-07-03T11:17:06.817Z
updated: 2024-07-04T11:17:06.817Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Add Compatibility Tool to Windows' Quick Access
excerpt: This Article Describes Add Compatibility Tool to Windows' Quick Access
keywords: Quick Access Tool Addon,Compatibility Enhancer,Windows QuickTool,Compatibility Update,QuikAccess Accessory,Windows EasyTool,Compatibility Windows Fix
thumbnail: https://thmb.techidaily.com/8bb1efcd08c2d3c3707b37b1d9ac64c15c4d68acde1a08c23a7f1acea10d7dc6.jpg
---

## Add Compatibility Tool to Windows' Quick Access

 There are many ways to run the Compatibility Troubleshooter, but the easiest way is to do it from the context menu by right-clicking on a program and selecting**Troubleshoot Compatibility** . However, sometimes, this option can go missing, and the good news is that you can add it back with a couple of registry tweaks. Keep on reading to find out how.

## What to Do Before Tweaking the Registry Editor

 Before you go about making big changes to your Windows PC, it’s always a good idea to have some sort of backup in case things go wrong. To do that, we highly recommend reading our guide on [creating a system restore with Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) . If you want, you can also read our other guide on [how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) if you want to have a copy of it somewhere.

## How to Add a "Troubleshoot Compatibility" Option to the Context Menu With the Registry Editor

 Now that you know how to keep the Windows registry safe, it's time to change it with the Registry Editor. We are going to start by adding the**Troubleshoot Compatibility** option to the context menu for EXE files. Afterward, the steps for adding it to other programs are going to be similar. To do that, follow the steps below:

1. Press**Win + R** to open the Run dialog box, enter**regedit** in the text box, and hit the**Enter** key to open the Registry Editor.
2. First, we are going to add the Troubleshoot Compatibility option for the EXE files. Start by copying and pasting the below key path in the address of the Registry Editor and hit the**Enter** key:  
HKEY_CLASSES_ROOT\cmdfile\shellEx\ContextMenuHandlers
3. Right-click the**ContextMenuHandlers** key and then select**New > Key** and name it**Compatibility** . If it is already there, move on to the next step.  
![Adding a new key to the ContextMenuHandler key for the EXE files](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/new-key-compatibility-troubleshooter-context-menu.jpg)
4. Select the**Compatibility** key, double-click**Default** on the right, and set**Value data** to**{1d27f844-3a1f-4410-85ac-14651078412d}** .  
![Entering value data for a string value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enter-value-data.jpg)

 Next, you’re going to repeat the steps above to add the**Troubleshoot Compatibility** to the context menu of other BAT and CMD files. Just replace the key path in step two with**HKEY\_CLASSES\_ROOT\\batfile\\shellEx\\ContextMenuHandlers\\** for BAT files and**HKEY\_CLASSES\_ROOT\\cmdfile\\shellEx\\ContextMenuHandlers\\** for CMD files.

 Now when you right-click an EXE, BAT, or CMD file, you should see the**Troubleshoot Compatibility** option in the context menu.

![The Troubleshoot compatibility option in the context menu on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/troubleshoot-compatibility-context-menu.jpg)

 Now you have one more way to [run the Program Compatibility Troubleshooter](https://www.makeuseof.com/run-program-compatibility-troubleshooter-windows/) .

## Run the Program Compatibility Troubleshooter Easily

 The Program Compatibility Troubleshooter is one of the best ways to fix compatibility issues on Windows. If you use it often, it helps to have the tool close. With the instructions above, you can add it to and run it from the context menu, which is extremely convenient.


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
<li><a href="https://windows11.techidaily.com/master-the-windows-accessibility-hub-in-5-simple-steps/"><u>Master the Windows Accessibility Hub - In 5 Simple Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/extend-the-time-windows-11-spends-in-shutdown-with-ongoing-jobs/"><u>Extend the Time Windows 11 Spends in Shutdown with Ongoing Jobs</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-curtail-excessive-wmi-worker-use/"><u>Tips to Curtail Excessive WMI Worker Use</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-ai-to-enhance-shopping-on-the-ms-store/"><u>Leveraging AI to Enhance Shopping on the MS Store</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-obs-troubleshooting-techniques-for-win-11-users/"><u>Mastering OBS Troubleshooting Techniques for Win 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-file-management-through-explores-sidebar/"><u>Streamlining File Management Through Explore's Sidebar</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-mend-windows-network-proxy-errors/"><u>Steps to Mend Windows Network Proxy Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reset-freezes-and-crashes-in-virtual-worlds/"><u>How to Reset Freezes & Crashes in Virtual Worlds</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11-secrets-with-devhome-insights/"><u>Unlocking Windows 11 Secrets with DevHome Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/simple-steps-for-stellar-cursors-in-windows-1011/"><u>Simple Steps for Stellar Cursors in Windows 10/11</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-samsung-galaxy-s23-tactical-edition-drfone-by-drfone-virtual-android/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On Samsung Galaxy S23 Tactical Edition | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-your-nokia-g42-5g-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>In 2024, How to Mirror Your Nokia G42 5G Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-iosandroid-tutorial-uploading-audio-to-social-network/"><u>[Updated] 2024 Approved  IOS/Android Tutorial  Uploading Audio to Social Network</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-20-essential-free-online-photo-tinkering-apps-for-2024/"><u>[Updated] 20 Essential Free Online Photo Tinkering Apps for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-forgotten-the-voicemail-password-of-nokia-c02-try-these-fixes-by-drfone-android/"><u>In 2024, Forgotten The Voicemail Password Of Nokia C02? Try These Fixes</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-master-techniques-for-longevity-in-gopro-batteries/"><u>In 2024, Master Techniques for Longevity in GoPro Batteries</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-building-brands-on-video-a-guide-to-partnering-with-popular-youtubers/"><u>In 2024, Building Brands on Video  A Guide to Partnering with Popular YouTubers</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-car-locator-apps-for-samsung-galaxy-a05-drfone-by-drfone-virtual-android/"><u>Top 5 Car Locator Apps for Samsung Galaxy A05 | Dr.fone</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-the-ultimate-list-of-top-10-podcast-editors-including-both-cost-free-and-paid-variants/"><u>2024 Approved The Ultimate List of Top 10 Podcast Editors, Including Both Cost-Free and Paid Variants</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-best-storage-deals-cloud-pricing-of-future-year/"><u>[Updated] Best Storage Deals  Cloud Pricing of Future Year</u></a></li>
</ul></div>
