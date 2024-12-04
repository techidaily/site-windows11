---
title: "Quick Guide: Turning Word Into a Reader-Only Application for Email Content"
date: 2024-11-26T20:33:42.324Z
updated: 2024-12-03T19:43:33.949Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/oP8grXxuy2o?si=uIRNhTYbecTcaC7J" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/f3PFn06LijE?si=zHrmlTOzrKxXe-k4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/PUDdKOsEN74?si=tkZf-KVinjuwmgx9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 Restart your PC for the changes to take effect. Following that, Word will open all your email attachments in reading view.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VlwHTQQMs?si=BXYwD1pKiaTuev4y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-docs.techidaily.com/aximizing-income-sourav-joshis-youtube-journey-for-2024/"><u>[New] Maximizing Income Sourav Joshi's YouTube Journey for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-ultimate-color-correctors-handbook/"><u>[Updated] The Ultimate Color Corrector's Handbook</u></a></li>
<li><a href="https://fake-location.techidaily.com/best-10-mock-location-apps-worth-trying-on-apple-iphone-6-drfone-by-drfone-virtual-ios/"><u>Best 10 Mock Location Apps Worth Trying On Apple iPhone 6 | Dr.fone</u></a></li>
<li><a href="https://driver-download.techidaily.com/effortless-guide-updating-your-netgear-wna3100-driver-software/"><u>Effortless Guide: Updating Your Netgear WNA3100 Driver Software</u></a></li>
<li><a href="https://some-techniques.techidaily.com/extreme-sports-showdown-hero5-black-versus-hero4-silver-for-2024/"><u>Extreme Sports Showdown Hero5 Black Versus Hero4 Silver for 2024</u></a></li>
<li><a href="https://ai-video.techidaily.com/new-in-2024-netflix-subtitle-translation-methods-comprehensive-guide/"><u>New In 2024, Netflix Subtitle Translation Methods Comprehensive Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-synapse-device-errors-in-windows/"><u>Steps to Resolve Synapse Device Errors in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-elevate-virtual-memory-usage-on-windows-11/"><u>Strategies to Elevate Virtual Memory Usage on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-windows-repairs-setting-up-shortcuts-for-troubleshooters/"><u>Streamlining Windows Repairs: Setting Up Shortcuts for Troubleshooters</u></a></li>
<li><a href="https://windows11.techidaily.com/sustaining-windows-11-taskbar-performance/"><u>Sustaining Windows 11 Taskbar Performance</u></a></li>
<li><a href="https://discover-extraordinary.techidaily.com/tecnicas-infalibles-para-restaurar-mensajes-eliminados-del-iphone-antes-del-ultimo-respaldo/"><u>Técnicas Infalibles Para Restaurar Mensajes Eliminados Del iPhone Antes Del Último Respaldo</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-ranked-2024-wireless-charger-picks-in-depth-review-by-tech-specialists-pcmag/"><u>Top-Ranked 2024 Wireless Charger Picks: In-Depth Review by Tech Specialists | PCMag</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/tutorial-to-change-itel-a05s-imei-without-root-a-comprehensive-guide-by-drfone-android/"><u>Tutorial to Change Itel A05s IMEI without Root A Comprehensive Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-purposes-of-vcplusplus-redistributions/"><u>Understanding Purposes of VC++ Redistributions</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-ways-to-weed-out-windows-11s-waits-and-delays/"><u>Winning Ways to Weed Out Windows 11'S Waits and Delays</u></a></li>
</ul></div>

