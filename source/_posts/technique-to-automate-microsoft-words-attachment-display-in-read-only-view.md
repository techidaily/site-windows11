---
title: Technique to Automate Microsoft Word's Attachment Display in Read-Only View
date: 2024-12-23T18:11:48.991Z
updated: 2024-12-25T16:31:28.878Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Technique to Automate Microsoft Word's Attachment Display in Read-Only View
excerpt: This Article Describes Technique to Automate Microsoft Word's Attachment Display in Read-Only View
keywords: Auto Word Attachments,Read Only Word Display,Email Read Mode,Word Automation Trick,Save As PDF Adjustment,Microsoft Attachment View,Optimize Word Read-Only
thumbnail: https://thmb.techidaily.com/95080ee1192e9ec99602ccecb30de670936b2e86c3bafe48586480f26bd563d2.jpg
---

## Technique to Automate Microsoft Word's Attachment Display in Read-Only View

 Microsoft Word comes with a lot of security features that protect your computer from malicious files. One of these options allows you to open all email attachments in Word's reading view by default.

 If you want an extra layer of protection against email attachments, there are several ways to always open attached Word documents in reading view on Windows. Let’s go over them one by one.

## 1\. How to Change Microsoft Word Startup Settings to Always Open Email Attachments in Reading View

 You can modify Word's startup settings to specify how your documents are handled. From there, you can set Word to open all email attachments in reading mode by default. Here's how:

1. Open Microsoft Word on your PC using the search menu.
2. Click the**File** menu in the top left corner.
3. Select**Options** from the left pane. This will open the**Word Options** window.
4. In the**General** tab, scroll down to**Start up options** .
5. Check the box that reads **Open e-mail attachments and other uneditable files in reading view** and click on**OK** .  
![Word Startup Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Word-Startup-Options.jpg)

 Once you complete the above steps, Word will open email attachments in reading view by default.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LdVT_-3gESA?si=_HfjpbUEHSRKTXjt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/yr0yS_Ywrjs?si=QxzYiX1KmUaExmlo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n-66V-LRK3Y?si=fNeB2pXCePeQli6E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/8Y-k_3N-0OI?si=1J-aFBXLJl5b3x4h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Restart your PC for the changes to take effect. Following that, Word will open all your email attachments in reading view.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LI9nKlbhnw8?si=uUXFVbuEqXtFHHv0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-knowledge.techidaily.com/new-2024-approved-the-essential-blueprint-for-obtaining-premium-visuals-for-free/"><u>[New] 2024 Approved The Essential Blueprint for Obtaining Premium Visuals for Free</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-elevate-your-instagram-game-scouting-the-8-top-post-schedulers-for-2024/"><u>[New] Elevate Your Instagram Game Scouting the 8 Top Post Schedulers for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-in-2024-elite-cutting-edge-tools-for-app-editing/"><u>[New] In 2024, Elite Cutting-Edge Tools for App Editing</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-automating-youtube-playback-in-social-networks-a-focus-on-facebook/"><u>[Updated] In 2024, Automating Youtube Playback in Social Networks A Focus on Facebook</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-peak-level-illustration-tweaks/"><u>2024 Approved Peak Level Illustration Tweaks</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-streamlined-approach-to-validate-your-yt-identity/"><u>2024 Approved Streamlined Approach to Validate Your YT Identity</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-disconnect-onedrive-from-ms-account-on-windows-systems/"><u>Guide to Disconnect OneDrive From MS Account on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-highlight-the-mouse-cursor-in-windows-10-and-11/"><u>How to Highlight the Mouse Cursor in Windows 10 & 11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-navigating-image-purification-avoiding-obscuring-elements/"><u>In 2024, Navigating Image Purification Avoiding Obscuring Elements</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-where-is-the-best-place-to-catch-dratini-on-nokia-g310-drfone-by-drfone-virtual-android/"><u>In 2024, Where Is the Best Place to Catch Dratini On Nokia G310 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/making-your-files-automatically-accessible-in-win11/"><u>Making Your Files Automatically Accessible in Win11</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/master-your-gameplay-with-asus-vg2nvht-the-ultimate-choice-for-console-enthusiasts/"><u>Master Your Gameplay with Asus VG2nVHT – The Ultimate Choice for Console Enthusiasts</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11s-full-screen-with-sonic-games/"><u>Mastering Windows 11'S Full Screen with Sonic Games</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-up-jdk-on-windows-11-a-step-by-step-guide/"><u>Setting Up JDK on Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-10-password-cracking-tools-for-xiaomi-by-drfone-android/"><u>Top 10 Password Cracking Tools For Xiaomi</u></a></li>
<li><a href="https://windows11.techidaily.com/top-bargains-on-windows-11-product-codes/"><u>Top Bargains on Windows 11 Product Codes</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-off-superfluous-windows-notification-tabs/"><u>Turn Off Superfluous Windows Notification Tabs</u></a></li>
<li><a href="https://windows11.techidaily.com/what-sets-exe-installers-apart-from-standard-msis/"><u>What Sets Exe Installers Apart From Standard MSIs?</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-disk-duplication-cloning-without-extras/"><u>Winning Disk Duplication: Cloning Without Extras</u></a></li>
</ul></div>

