---
title: "Quick Guide: Turning Word Into a Reader-Only Application for Email Content"
date: 2024-12-24T20:02:49.062Z
updated: 2024-12-25T18:25:15.783Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/c1yHj02oP3w?si=mwi3FyP0p68gkBqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Change Microsoft Word Startup Settings to Always Open Email Attachments in Reading View

 You can modify Word's startup settings to specify how your documents are handled. From there, you can set Word to open all email attachments in reading mode by default. Here's how:

1. Open Microsoft Word on your PC using the search menu.
2. Click the**File** menu in the top left corner.
3. Select**Options** from the left pane. This will open the**Word Options** window.
4. In the**General** tab, scroll down to**Start up options** .
5. Check the box that reads **Open e-mail attachments and other uneditable files in reading view** and click on**OK** .  
![Word Startup Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Word-Startup-Options.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DxUX4R6Cf7c?si=prHevNQJivSkIfUt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you complete the above steps, Word will open email attachments in reading view by default.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XVsiIO7hWOc?si=UvWnqxaI_yHwEr74" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/mMYEK2gtY5c?si=ytxNz_JHZkTrwb4b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/dKjioJQaUh8?si=Ls_AeuvGsSyL5ny2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Restart your PC for the changes to take effect. Following that, Word will open all your email attachments in reading view.

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
<li><a href="https://fox-links.techidaily.com/updated-in-2024-extreme-weather-footage-showdown-black-hero5/"><u>[Updated] In 2024, Extreme Weather Footage Showdown Black Hero5</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-device-transcending-entry-editor-leader-of-2023/"><u>2024 Approved Device-Transcending Entry Editor Leader of 2023</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-free-srt-conversion-uncover-top-8-online-options/"><u>2024 Approved Free SRT Conversion Uncover Top 8 Online Options</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-honor-play-8t-drfone-by-drfone-reset-android-reset-android/"><u>All About Factory Reset, What Is It and What It Does to Your Honor Play 8T? | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/download-macx-premium-free-webm-and-mov-converter-for-macos/"><u>Download MacX - Premium Free WebM & MOV Converter for MacOS</u></a></li>
<li><a href="https://win-exclusive.techidaily.com/how-reliable-is-windows-defender-against-viruses-a-deep-dive-with-malwarefox-perspectives/"><u>How Reliable Is Windows Defender Against Viruses: A Deep Dive with MalwareFox Perspectives</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-open-the-control-panel-as-an-administrator-in-windows/"><u>How to Open the Control Panel as an Administrator in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/instructions-to-create-safe-dialogue-for-hardware-disconnect/"><u>Instructions to Create Safe Dialogue for Hardware Disconnect</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-smooth-video-transitions-taming-vlc-lags/"><u>Mastering Smooth Video Transitions: Taming VLC Lags</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-constant-display-of-edge-buttons/"><u>Preventing Constant Display of Edge Buttons</u></a></li>
<li><a href="https://windows11.techidaily.com/transitioning-to-kali-your-windows-pathway/"><u>Transitioning to Kali: Your Windows Pathway</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-over-wi-fi-errors-addressing-missing-actions-in-prompts/"><u>Winning Over Wi-Fi Errors: Addressing Missing Actions in Prompts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/zero-net-windows-update-a-self-service-manual/"><u>Zero-Net Windows Update: A Self-Service Manual</u></a></li>
</ul></div>

