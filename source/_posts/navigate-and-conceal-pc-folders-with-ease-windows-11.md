---
title: Navigate and Conceal PC Folders with Ease (Windows 11)
date: 2024-09-09T12:02:36.149Z
updated: 2024-09-10T12:02:36.149Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigate and Conceal PC Folders with Ease (Windows 11)
excerpt: This Article Describes Navigate and Conceal PC Folders with Ease (Windows 11)
keywords: Windows 11 Folder Hide,Easy PC Folder Navigation,Stealth File Management,Secure Data Concealment,Windows Navigate Tools,Easefolders (Windows),Privacy-Safe PC Storage
thumbnail: https://thmb.techidaily.com/ad227a8d5363831d078e6323942af2a72809395f7bf85c351306cae77a65bd05.jpg
---

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135407/19272" target="_top" id="2135407">
  <img src="//a.impactradius-go.com/display-ad/19272-2135407" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135407/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Navigate and Conceal PC Folders with Ease (Windows 11)

 If you’re running the latest version of Windows 11, the folders in This PC will be hidden by default. That's by design so you can pay more attention to your drives. However, there’s a way you can unhide them so you can access them.

 In this guide, we are going to show you how to add or remove the 3D Objects, Documents, Music, Video, Pictures, and Downloads in This PC by making a few Windows Registry tweaks.

## Before You Start Adding or Removing Folders in This PC…

 We are going to make changes to the Windows Registry by adding keys and values to it using the Registry Editor. To fire it up, press **Win + R** to bring up the Windows Run dialog box, enter **regedit** in the text box, and then click **OK**.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137221/26400" target="_top" id="2137221">
  <img src="//a.impactradius-go.com/display-ad/26400-2137221" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137221/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Before you proceed, we highly recommend reading our guide on [what the Windows Registry is and how to edit it](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) to familiarize yourself with what we will be doing next. Also important is knowing [how to back up the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). Considering this is the database that Windows stores the data it needs to operate properly, you will need this backup in case you make an error.

 For showing and hiding folders in This PC to work, make sure you’re running the latest version of Windows 11\. You'll know you have it if File Explorer has tabs.

 With the Registry Editor open, let's get to it.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137976/21526" target="_top" id="2137976">
  <img src="//a.impactradius-go.com/display-ad/21526-2137976" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137976/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Show or Hide the 3D Objects Folder in This PC

 For the **3D Objects** folder, you need to add a key to the registry and the folder will pop up in This PC. So, in the address bar of the Registry Editor, enter the below path and then hit the **Enter** key:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace

 Next, right-click the **NameSpace** key in the left panel and select **New > Key**. Then, name that key **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}**. If the name is a bit too hard to type out, just copy and paste it.

![new-key-namespace-regedit-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/new-key-namespace-regedit-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115913/19272" target="_top" id="2115913">
  <img src="//a.impactradius-go.com/display-ad/19272-2115913" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115913/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Once done, refresh File Explorer by hitting **F5**. Now you will see that the **3D Objects** folder has appeared in This PC.

![3d-objects-this-pc](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3d-objects-this-pc.jpg)

 To remove the folder again, just go back to the Registry Editor, right-click the **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}** key, and select **Delete**. After you refresh File Explorer, the folder will be gone.

## How to Show or Hide the Documents, Music, Videos, Pictures, and/or Downloads Folders in This PC

 To add the **Documents** folder to This PC, enter the below path in the address bar of the Registry Editor and then hit **Enter** on your keyboard to go where its key is located:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{d3162b92-9365-467a-956b-92703aca08af}

 Right-click the **HideIfEnabled** value in the right panel and select **Delete**.

![delete-hideifenabled-value-regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/delete-hideifenabled-value-regedit.jpg)

 Now, refresh File Explorer with **F5** and the **Documents** folder will appear in This PC.

 To hide it, right-click the key on the left panel and select **New > DWORD (32-bit) Value** and name it **HideIfEnabled**. Double-click the newly-created value in the right panel, set **Value data** to **22ab9b9**, and then click **OK**.

![set-hideifenabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-hideifenabled.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2121332/18498" target="_top" id="2121332">
  <img src="//a.impactradius-go.com/display-ad/18498-2121332" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2121332/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Now when you refresh This PC in File Explorer, you will see that the **Documents** folder is gone.

 The steps to show or hide the other folders from this point on are the same. Just go to the respective key in the Registry Editor and either delete the **HideIfEnabled** value to show the folder in this PC or create the value and set it to **22ab9b9** to hide the folder.

 Here’s the path to the **Music** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{3dfdf296-dbec-4fb4-81d1-6a3438bcf4de}

 Here’s the path to the **Video** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{f86fa3ab-70d2-4fc7-9c99-fcbf05467f3a}

 Here’s the path to the **Pictures** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{24ad3ad4-a569-4530-98e1-ab02f9417aa8}

 Here’s the path to the **Downloads** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{088e3905-0323-4b02-9826-5d99428e115f}

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115944/19272" target="_top" id="2115944">
  <img src="//a.impactradius-go.com/display-ad/19272-2115944" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115944/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Choose the Folders You Want to Appear on This PC in Windows 11

 If you want to see folders on This PC, you can do so by making a couple of edits to the Windows Registry. While we do recommend that you know what you’re doing if you proceed, we have made the instructions relatively simple to follow so there's minimal chance of messing up the registry.

 As long as you take the necessary steps not to mess up the Windows Registry, you should be able to hide and show the folders you want easily.


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
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-recorded-reality-facebook-live-2023/"><u>[New] In 2024, Recorded Reality Facebook Live, 2023</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-efficient-ways-to-delete-previewed-content-from-youtubes-queue/"><u>[Updated] 2024 Approved Efficient Ways to Delete Previewed Content From YouTube's Queue</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-final-list-top-blu-ray-players-for-pcmacos-enthusiasts/"><u>[Updated] Final List Top Blu-Ray Players for PC/macOS Enthusiasts</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-google-docs-speech-to-text-a-complete-guidebook/"><u>2024 Approved Google Docs Speech-to-Text A Complete Guidebook</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-secure-storage-system-5-ways-to-upload-files/"><u>2024 Approved Secure Storage System 5 Ways to Upload Files</u></a></li>
<li><a href="https://youtube-data.techidaily.com/oad-youtube-playlists-without-hassle-our-guide/"><u>Download YouTube Playlists Without Hassle - Our Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-adjusting-low-power-modes-in-windows/"><u>Essential Tips: Adjusting Low-Power Modes in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-fixes-for-correcting-error-0x800700e1-on-windows-11-devices/"><u>Expert Fixes for Correcting Error 0X800700E1 on Windows 11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-value-cannot-be-determined-problem-on-windows-pcs/"><u>Fixing 'Value Cannot Be Determined' Problem on Windows PCs</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-is-a-sim-network-unlock-pin-get-your-vivo-g2-phone-network-ready-by-drfone-android/"><u>In 2024, What Is a SIM Network Unlock PIN? Get Your Vivo G2 Phone Network-Ready</u></a></li>
<li><a href="https://windows11.techidaily.com/keyboard-commands-for-optimal-windows-photo-editing/"><u>Keyboard Commands for Optimal Windows Photo Editing</u></a></li>
<li><a href="https://discover-blog.techidaily.com/leveraging-cookiebot-technology-for-advanced-web-engagement-insights/"><u>Leveraging Cookiebot Technology for Advanced Web Engagement Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-cr2-conversion-techniques-on-your-windows-system/"><u>Mastering CR2 Conversion Techniques on Your Windows System</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-network-configurations-in-windows-os/"><u>Mastering Network Configurations in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/mellowing-down-after-a-stormy-surge-in-windows-settings/"><u>Mellowing Down After a Stormy Surge in Windows Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-typing-hiccups-top-7-solutions-for-win-11s-key-lag/"><u>Navigate Typing Hiccups: Top 7 Solutions for Win 11'S Key Lag</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-updates-error-0x80246007-roadblock-on-1011/"><u>Navigating Windows Update's Error 0X80246007 Roadblock on 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-to-photoshopping-out-image-borders/"><u>Quick Guide to Photoshopping Out Image Borders</u></a></li>
<li><a href="https://windows11.techidaily.com/rebooting-the-clock-fixes-for-disabled-windows-time-service/"><u>Rebooting the Clock: Fixes for Disabled Windows Time Service</u></a></li>
<li><a href="https://windows11.techidaily.com/regaining-access-post-failed-windows-login-attempt/"><u>Regaining Access Post Failed Windows Login Attempt</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-empty-directory-issue-windows-1011-error-x80070091/"><u>Resolving Empty Directory Issue - Windows 10/11 Error X80070091</u></a></li>
<li><a href="https://windows11.techidaily.com/reverse-webp-images-in-chrome-for-windows-users/"><u>Reverse WebP Images in Chrome for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/revive-your-system-5-strategies-for-wins-secure-boot-errors/"><u>Revive Your System: 5 Strategies for Win's Secure Boot Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-deadlocked-files-on-windows-11-a-guide-1/"><u>Reviving Deadlocked Files on Windows 11: A Guide (1)</u></a></li>
<li><a href="https://windows11.techidaily.com/stay-ahead-postpone-windows-edge-tabs-on-w11/"><u>Stay Ahead: Postpone Windows Edge Tabs on W11</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-defenses-choose-just-one-antivirus-on-windows/"><u>Streamline Your Defenses: Choose Just One Antivirus on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-device-lockout-windows-11-error-code-22-resolution/"><u>Tackling Device Lockout: Windows 11 Error Code 22 Resolution</u></a></li>
<li><a href="https://windows11.techidaily.com/telnet-access-in-windows-11-made-simple/"><u>Telnet Access in Windows 11 Made Simple</u></a></li>
<li><a href="https://windows11.techidaily.com/the-secret-to-flawless-image-editing-in-windows-photo/"><u>The Secret to Flawless Image Editing in Windows Photo</u></a></li>
<li><a href="https://windows11.techidaily.com/top-techniques-for-disabling-windows-11-tpm/"><u>Top Techniques for Disabling Windows 11 TPM</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-windows-11-the-acoustic-journey-begins/"><u>Transforming Windows 11: The Acoustic Journey Begins</u></a></li>
<li><a href="https://win-able.techidaily.com/troubleshooting-critical-errors-the-ultimate-fix-for-gobi-fatal-error-in-back-4-blood/"><u>Troubleshooting Critical Errors: The Ultimate Fix for 'Gobi Fatal Error in Back 4 Blood'</u></a></li>
<li><a href="https://windows11.techidaily.com/unclutter-your-windows-desktop-space/"><u>Unclutter Your Windows Desktop Space</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-power-of-your-systems-fix-it-features/"><u>Unlock the Power of Your System's Fix-It Features</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-steps-to-powertoys-install-win11/"><u>Unraveling the Steps to PowerToys Install (Win11)</u></a></li>
<li><a href="https://buynow-help.techidaily.com/unveiling-nest-audios-charm-an-essential-addition-to-music-lovers-smart-home-collections/"><u>Unveiling Nest Audio's Charm: An Essential Addition to Music Lovers’ Smart Home Collections</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-solution-for-0x800713f-failure-in-email-app-win11/"><u>Unveiling Solution for 0X800713F Failure in Email App (Win11)</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-remote-problem-invisible-screen/"><u>Unveiling Windows Remote Problem: Invisible Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/update-mail-and-calendars-style-them-with-fav-photos/"><u>Update Mail & Calendars: Style Them with Fav Photos</u></a></li>
<li><a href="https://windows11.techidaily.com/upgrade-to-smart-speed-indicators-in-desktop-bar/"><u>Upgrade to Smart Speed Indicators in Desktop Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/your-route-to-a-maps-integrated-windows-experience/"><u>Your Route to a Maps-Integrated Windows Experience</u></a></li>
</ul></div>
