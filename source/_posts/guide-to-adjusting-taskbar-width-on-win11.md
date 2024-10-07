---
title: Guide to Adjusting Taskbar Width on Win11
date: 2024-10-05T23:13:48.969Z
updated: 2024-10-06T19:23:58.890Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Adjusting Taskbar Width on Win11
excerpt: This Article Describes Guide to Adjusting Taskbar Width on Win11
keywords: Win11 Taskbar Tweak,Resize Win11 Bar,Windows Taskbar Set,Win11 Gui Adjust,Taskbar Width Control,Win11 Display Fix,TitleBar Size Guide
thumbnail: https://thmb.techidaily.com/9452709ea5278a965307bf042e7d92a12b881e1c879f75105867000ed51ea454.jpg
---

## Guide to Adjusting Taskbar Width on Win11

 Ever looked at the Windows 11 Taskbar and thought it looks too small for your liking? Or maybe you feel it could be a little smaller? If that’s the case, you can change its size to suit your needs by making it bigger or smaller.

 Unlike Windows 10, you can’t just unlock the Taskbar and adjust its size freely in Windows 11\. While Microsoft has removed this way of going about it in Windows 11, there is a workaround that you can use, although it’s not as elegant.

## How Do I Make the Windows 11 Taskbar Bigger or Smaller?

 The only way to change the size of the Taskbar is to use the Registry Editor. However, we advise caution when dealing with the Windows Registry because if something goes wrong, you might experience performance issues on your Windows 11 PC. If you’re unfamiliar with it, we recommend reading our guides on[what the Windows Registry is](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) and[how to not mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/) .

 Once you’re all caught up or are already familiar with the Windows Registry, and you know what you’re doing, you can make the Taskbar bigger or smaller. To do that:

1. Start by pressing**Win + R** to open Windows Run.
2. Type**regedit** in the text box and hit the**Enter** key.
3. Then, click**Yes** on the UAC prompt to launch the Registry Editor.
4. Copy and paste the below text in the address bar of the Registry Editor and hit the**Enter** key:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. In the**Advanced** key, look for a value called**TaskbarSi** . If it’s not there, right-click**Advanced** , select**New > DWORD (32-bit) Value** , and name that value**TaskbarSi.**  
![creating a new dword in the advanced key in the Registry Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/new-dword-advanced-regedit.jpg)
6. Double-click**TaskbarSi** to edit it, and then enter**2** in the**Value data** text box and click**OK** to make the Taskbar bigger.  
![changing the taskbarsi value to 2 in the Registry Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/taskbarsi-value-2.jpg)

 Once you restart your computer, you will see the result: an enlarged Taskbar.

![an enlarged Taskbar on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-enlarged-taskbar.jpg)

 To make the Taskbar smaller, enter**0** in the**Value data** text box, click**OK** , and then restart your computer. You will then see that the Taskbar has shrunk.

![a smaller taskbar in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-small-taskbar.jpg)

 If you decide to go back to the Taskbar’s default size, you can easily set**Value data** to**1** or simply delete the**TaskbarSi** value.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043596/7443" target="_top" id="2043596">
  <img src="//a.impactradius-go.com/display-ad/7443-2043596" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043596/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Adjust the Taskbar’s Size to Suit Your Needs on Windows 11

 Even though you can’t make the Taskbar bigger or smaller on Windows 11 as easily as you can on Windows 10, a little know-how can help. And as long as you followed the instructions mentioned above correctly, you shouldn’t worry about messing up the Windows Registry. However, we still recommend that you use this method only if you know what you’re doing.

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
<li><a href="https://facebook-record-videos.techidaily.com/new-adding-visual-time-indicators-to-your-youtube-links-for-2024/"><u>[New] Adding Visual Time Indicators to Your YouTube Links for 2024</u></a></li>
<li><a href="https://data-recovery.techidaily.com/efficient-partition-rescue-apps-retrieve-accidentally-deleted-sections-of-your-hard-drive/"><u>Efficient Partition Rescue Apps: Retrieve Accidentally Deleted Sections of Your Hard Drive</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-for-resolving-printer-connections-in-windows/"><u>Essential Steps for Resolving Printer Connections in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/file-explorer-misses-out-on-sd-card-heres-fixing-it/"><u>File Explorer Misses Out on SD Card - Here's Fixing It</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-dodge-perpetual-network-logon-errors-in-windows/"><u>How to Dodge Perpetual Network Logon Errors in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-overcome-invalid-session-from-vac-steam-alert/"><u>How To Overcome Invalid Session From VAC Steam Alert</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-messages-from-zte-axon-40-lite-by-fonelab-android-recover-messages/"><u>How to retrieve erased messages from ZTE Axon 40 Lite</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-mastering-subscription-the-art-of-positive-engagement/"><u>In 2024, Mastering Subscription The Art of Positive Engagement</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-stepping-into-silence-fading-out-audio-in-adobe-premiere-pro/"><u>In 2024, Stepping Into Silence Fading Out Audio in Adobe Premiere Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-sound-error-error-0xc00d36b4-in-win11/"><u>Rectifying Sound Error: Error 0XC00D36B4 in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-easy-way-out-windows-11s-silencing-methods/"><u>The Easy Way Out: Windows 11'S Silencing Methods</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/tips-and-tricks-for-setting-up-your-realme-c51-phone-pattern-lock-by-drfone-android/"><u>Tips and Tricks for Setting Up your Realme C51 Phone Pattern Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-methods-for-resolving-windows-interface-dispute/"><u>Top 5 Methods for Resolving Windows Interface Dispute</u></a></li>
<li><a href="https://program-issues.techidaily.com/ultimate-guide-eliminating-minecraft-lag-issues/"><u>Ultimate Guide: Eliminating Minecraft Lag Issues</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/youtube-venture-made-easy-the-most-accessible-biz-channel-ideas-ranked/"><u>YouTube Venture Made Easy The Most Accessible Biz Channel Ideas Ranked</u></a></li>
</ul></div>

