---
title: "Quick Guide: Turning Word Into a Reader-Only Application for Email Content"
date: 2025-01-15T19:18:55.096Z
updated: 2025-01-22T17:57:15.185Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Iz2LYWd8EqI?si=G_3CqFRAmeVPczjj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Change Microsoft Word Startup Settings to Always Open Email Attachments in Reading View

 You can modify Word's startup settings to specify how your documents are handled. From there, you can set Word to open all email attachments in reading mode by default. Here's how:

1. Open Microsoft Word on your PC using the search menu.
2. Click the**File** menu in the top left corner.
3. Select**Options** from the left pane. This will open the**Word Options** window.
4. In the**General** tab, scroll down to**Start up options** .
5. Check the box that reads **Open e-mail attachments and other uneditable files in reading view** and click on**OK** .  
![Word Startup Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Word-Startup-Options.jpg)

 Once you complete the above steps, Word will open email attachments in reading view by default.

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/hZsnjxeSh1U?si=hZIfzQPDNX5KtOCg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/q4-YQ9Wjtfg?si=6afn1fydg_Wb9B8z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/9ECz3oZ8NrQ?si=86vkwkDJo9HQXpzt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Restart your PC for the changes to take effect. Following that, Word will open all your email attachments in reading view.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4DJKH1uY7P0?si=tCG66XVlbwSKoATj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-cutting-edge-ppt-techniques-for-s2t-integration-advocates/"><u>[New] 2024 Approved Cutting-Edge PPT Techniques for S2T Integration Advocates</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-the-essential-guide-to-facebooks-latest-features/"><u>[New] 2024 Approved The Essential Guide to Facebook's Latest Features</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/2024s-elite-selection-of-compact-laptop-recharge-units/"><u>2024'S Elite Selection of Compact Laptop Recharge Units</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/enhancing-aerial-video-the-best-gimbals-reviewed/"><u>Enhancing Aerial Video The Best Gimbals Reviewed</u></a></li>
<li><a href="https://windows11.techidaily.com/from-novice-to-pro-setting-up-hyper-v-on-win-11-for-home-users/"><u>From Novice to Pro: Setting Up Hyper-V on Win 11 for Home Users</u></a></li>
<li><a href="https://techidaily.com/how-to-exit-recovery-mode-on-apple-iphone-11-pro-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Exit Recovery Mode on Apple iPhone 11 Pro? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-music-from-oneplus-ace-2v-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Music from OnePlus Ace 2V to iPod | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/increase-dynamic-display-speed-of-task-manager-win-11/"><u>Increase Dynamic Display Speed of Task Manager Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-errors-in-windows-memory-check-tool/"><u>Overcoming Errors in Windows Memory Check Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-stubborn-windows-key-issues/"><u>Overcoming Stubborn Windows Key Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-unverified-app-errors-in-windows/"><u>Overcoming Unverified App Errors in Windows</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/1113561-9780307986917-supernormal/"><u>Supernormal | Free Book</u></a></li>
<li><a href="https://windows11.techidaily.com/upgrade-taskbar-appearance-instructions-to-include-a-weather-icon-in-windows-11-system-tray/"><u>Upgrade Taskbar Appearance: Instructions to Include a Weather Icon in Windows 11 System Tray</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/what-is-aim-unraveling-the-legacy-of-aol-instant-messenger/"><u>What Is AIM? Unraveling the Legacy of AOL Instant Messenger</u></a></li>
</ul></div>

