---
title: "Quick Guide: Turning Word Into a Reader-Only Application for Email Content"
date: 2024-10-29T16:48:22.456Z
updated: 2024-10-30T16:53:49.045Z
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

 Once you complete the above steps, Word will open email attachments in reading view by default.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394">
  <img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2123738/7443" target="_top" id="2123738">
  <img src="//a.impactradius-go.com/display-ad/7443-2123738" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123738/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129740/7443" target="_top" id="2129740">
  <img src="//a.impactradius-go.com/display-ad/7443-2129740" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129740/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2118315/7443" target="_top" id="2118315">
  <img src="//a.impactradius-go.com/display-ad/7443-2118315" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118315/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-docs.techidaily.com/024-approved-deciphering-finances-how-much-do-youtubers-earn-per-ad/"><u>[New] 2024 Approved Deciphering Finances How Much Do YouTubers Earn Per Ad?</u></a></li>
<li><a href="https://youtube-data.techidaily.com/n-2024-million-viewer-milestone-and-associated-income-levels/"><u>[New] In 2024, Million-Viewer Milestone and Associated Income Levels</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-insiders-guide-to-powerful-win10-habits/"><u>[Updated] 2024 Approved Insider's Guide to Powerful Win10 Habits</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-2024-approved-mastering-the-art-of-free-yet-striking-image-acquisition/"><u>[Updated] 2024 Approved Mastering the Art of Free, Yet Striking Image Acquisition</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-in-2024-innovative-approaches-to-harvest-large-amounts-of-tiktok-media/"><u>[Updated] In 2024, Innovative Approaches to Harvest Large Amounts of TikTok Media</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/advancements-from-pci-sig-new-copperlink-cable-solutions-set-to-revolutionize-pcie-5-and-6-connections-keep-an-eye-out-for-the-upcoming-pcie-7-standard/"><u>Advancements From PCI-SIG: New CopperLink Cable Solutions Set to Revolutionize PCIe 5 and #6 Connections; Keep an Eye Out for the Upcoming PCIe 7 Standard</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/evaluating-tunefab-for-video-capture-excellence/"><u>Evaluating Tunefab for Video Capture Excellence</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-overcome-ms-store-setbacks-in-win-11-edition/"><u>How to Overcome MS Store Setbacks in Win 11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-basics-of-windows-pe-format/"><u>Navigating the Basics of Windows PE Format</u></a></li>
<li><a href="https://windows11.techidaily.com/network-assurance-on-pc-ensuring-reliable-win-net-access/"><u>Network Assurance on PC: Ensuring Reliable Win Net Access</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-pcs-pink-screens-a-step-by-step-guide/"><u>Overcoming PC's Pink Screens: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-transforms-mastering-the-art-of-amd-card-driver-updates/"><u>Windows 11 Transforms: Mastering the Art of AMD Card Driver Updates</u></a></li>
</ul></div>

