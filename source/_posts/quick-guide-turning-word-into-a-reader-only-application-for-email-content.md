---
title: "Quick Guide: Turning Word Into a Reader-Only Application for Email Content"
date: 2024-12-12T16:25:13.354Z
updated: 2024-12-16T21:38:08.830Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Quick Guide: Turning Word Into a Reader-Only Application for Email Content"
excerpt: "This Article Describes Quick Guide: Turning Word Into a Reader-Only Application for Email Content"
keywords: Email Content Reader Only,Convert Words to Apps,Readers' Email Guide,Word to Reader App,Email Exclusive Access,Create Reader-Only App,Word Transformation Tool
thumbnail: https://thmb.techidaily.com/2abff2026ed0f77bee3d5444a73ceb2a838092ecb3114e177d3896df7011b647.jpg
---

## Quick Guide: Turning Word Into a Reader-Only Application for Email Content

 Microsoft Word comes with a lot of security features that protect your computer from malicious files. One of these options allows you to open all email attachments in Word's reading view by default.

 If you want an extra layer of protection against email attachments, there are several ways to always open attached Word documents in reading view on Windows. Let’s go over them one by one.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Change Microsoft Word Startup Settings to Always Open Email Attachments in Reading View

 You can modify Word's startup settings to specify how your documents are handled. From there, you can set Word to open all email attachments in reading mode by default. Here's how:

1. Open Microsoft Word on your PC using the search menu.
2. Click the**File** menu in the top left corner.
3. Select**Options** from the left pane. This will open the**Word Options** window.
4. In the**General** tab, scroll down to**Start up options** .
5. Check the box that reads **Open e-mail attachments and other uneditable files in reading view** and click on**OK** .  
![Word Startup Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Word-Startup-Options.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you complete the above steps, Word will open email attachments in reading view by default.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/L603QXgjb3I?si=sMYHfMGy2kNPSHPt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Change the Local Group Policy to Open Email Attachments in Reading View in Microsoft Word

 Another way to configure Word to open email attachments in reading view is to use the Group Policy Editor. It’s worth noting that you can only access the Group Policy Editor if you’re running the Professional, Education, or Enterprise edition of Windows. If you're on Windows Home, be sure to check out[how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the box and select the first result that appears. This will[open the Local Group Policy Editor](https://www.makeuseof.com/tag/open-local-group-policy-editor-windows/) .
3. Use the left pane to navigate to **User Configuration > Administrative Templates > Microsoft Word 2016 > Word Options > General** .
4. Double-click the**Open e-mail attachments in Reading View** policy on your right.
5. Select the**Enabled** option.
6. Hit**Apply** followed by**OK** .  
![Configure Word to Open Email Attachments in Reading View Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Configure-Word-to-Open-Email-Attachments-in-Reading-View-Using-Group-Policy-Editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gyGoQi7hsZk?si=8OcKcPUj2wSBmVZ1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. How to Tweak the Windows Registry to Open Email Attachments in Reading View in Microsoft Word

 The Registry Editor in Windows stores important settings for Windows and its apps. If you're comfortable editing registry files, you can also use the following method to configure Word to open email attachments in reading view.

 Since modifying registry files is risky, you should proceed with caution. Also, make sure you back up all the registry files first. If you need help, refer to our guide on[how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

 Once you’ve done that, here’s what you need to configure Word to open email attachments in reading view.

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > Software > Microsoft > Office > 16.0 > Word > Options** .
5. Right-click on the**Options** key and select**New > DWORD (32-bit) Value** . Name it**AutoReadingMode** .
6. Double-click the newly created DWORD and set the**Value data** to**1** .
7. Click**OK** .  
![Configure Word to Open Email Attachments in Reading View Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Configure-Word-to-Open-Email-Attachments-in-Reading-View-Using-Registry-Editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Restart your PC for the changes to take effect. Following that, Word will open all your email attachments in reading view.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RAnyQ0uj9Yg?si=Es4_ulcdM_-LuDcq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Opening Email Attachments in Microsoft Word's Reading View

 Email remains a prominent attack vector for hackers and cybercriminals. Configuring Microsoft Word to open email attachments in reading view is just one of many methods for avoiding malware. Another option is to check suspicious files for malware before opening them.

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
<li><a href="https://youtube-web.techidaily.com/urating-tunes-a-comprehensive-guide-to-youtube-lists-for-2024/"><u>[New] Curating Tunes A Comprehensive Guide to YouTube Lists for 2024</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/assessing-vulnerability-levels-in-chatgpt-systems/"><u>Assessing Vulnerability Levels in ChatGPT Systems</u></a></li>
<li><a href="https://activate-lock.techidaily.com/best-ways-to-bypass-icloud-activation-lock-on-apple-iphone-11-pro-maxipadipod-by-drfone-ios/"><u>Best Ways to Bypass iCloud Activation Lock on Apple iPhone 11 Pro Max/iPad/iPod</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-on-resolving-the-v22h2-windows-upgrade-not-installed-error/"><u>Expert Tips on Resolving the V22H2 Windows Upgrade Not Installed Error</u></a></li>
<li><a href="https://windows11.techidaily.com/finding-fixes-for-share-issue-on-nvidia-software/"><u>Finding Fixes for Share Issue on NVIDIA Software</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-windows-unable-to-use-enter-button/"><u>Fixing Windows: Unable to Use Enter Button</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-your-windows-10-ready-quick-guide-to-downloading-sound-blaster-z-drivers/"><u>Get Your Windows 10 Ready: Quick Guide to Downloading Sound Blaster Z Drivers</u></a></li>
<li><a href="https://some-techniques.techidaily.com/how-to-use-luts-to-obs-studio-and-download-free-lut-for-2024/"><u>How to Use LUTs to OBS Studio & Download Free LUT for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-the-blueprint-to-youtube-wealth-smart-strategies-for-facebook-video-marketing/"><u>In 2024, The Blueprint to YouTube Wealth Smart Strategies for Facebook Video Marketing</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/in-2024-your-go-to-list-asmr-on-phone-platforms/"><u>In 2024, Your Go-To List ASMR on Phone Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/integrate-hardware-monitoring-seamlessly-using-windows-widgets/"><u>Integrate Hardware Monitoring Seamlessly Using Windows Widgets</u></a></li>
<li><a href="https://windows11.techidaily.com/keyboard-command-compendium-for-ms-project-users/"><u>Keyboard Command Compendium for MS Project Users</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-slow-download-woes-in-battlenet-pcs/"><u>Overcoming Slow Download Woes in Battle.net PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/rescue-a-crippled-windows-settings-application/"><u>Rescue a Crippled Windows Settings Application</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionize-your-windows-cars-with-these-five-essentials/"><u>Revolutionize Your Windows Cars with These Five Essentials</u></a></li>
<li><a href="https://windows11.techidaily.com/stopping-autolock-on-your-computer-screen/"><u>Stopping AutoLock on Your Computer Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/summoning-windows-11s-masked-search-facilitator/"><u>Summoning Windows 11'S Masked Search Facilitator</u></a></li>
<li><a href="https://win11.techidaily.com/the-most-reliable-windows-photo-organizer-list/"><u>The Most Reliable Windows Photo Organizer List</u></a></li>
<li><a href="https://win-guides.techidaily.com/1728508779290-windows-10-c/"><u>Windows 10上保证安全清空 C:驱动器的三种方式</u></a></li>
</ul></div>

