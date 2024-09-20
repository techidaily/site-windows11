---
title: How to Show or Hide the “Dim Display After” Option in the Power Options Menu on Windows
date: 2024-09-14T21:23:42.246Z
updated: 2024-09-20T20:16:04.032Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Show or Hide the “Dim Display After” Option in the Power Options Menu on Windows
excerpt: This Article Describes How to Show or Hide the “Dim Display After” Option in the Power Options Menu on Windows
keywords: Dim Display Control Windows,Hide/Show Display Option,Power Options Adjustments,Windows Display Settings,Change Display Mode Windows,Manage Screen Visibility Windows,Optimize Power Menu Windows
thumbnail: https://thmb.techidaily.com/344ccd42970473c822ce3d8647d1f132f07ed11b189d66bfa12739452e5e4fb4.jpg
---

## How to Show or Hide the “Dim Display After” Option in the Power Options Menu on Windows

 There are times when you need to step away from your PC, and if you’re gone long enough, the screen will automatically dim. Windows does this to preserve your battery, and you can adjust when your display should darken in the Power Options menu by editing the **Dim display after** option.

 If for some reason you can’t see the **Dim display after** option in the Power Options menu, or it’s there and you want to remove it, you can use PowerShell or the Registry Editor to show or hide it. Here’s how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Show or Hide the “Dim Display After” Option Using PowerShell

 First, launch Windows PowerShell. There are many [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/), but the easiest method is to press **Win + S** to open Windows Search. Then, enter **powershell** in the search box and click on **Windows PowerShell** when it appears in the search results.

![windows powershell in the windows search results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/windows-powershell-search.jpg)

 In PowerShell, enter the following command to show the **Dim Display after** option in the Power Options menu:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee -ATTRIB_HIDE

 To hide it, enter the following command:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee +ATTRIB_HIDE

 After entering the command you want, hit the **Enter** key on your keyboard for PowerShell to execute it. Afterward, the **Dim display after** option should appear or disappear accordingly in the Power Options menu.

## How to Show or Hide the “Dim display after” Option Using the Registry Editor

 Considering how vital the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is for the smooth operation of Windows, you might want to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you edit it. Afterward, open the Registry Editor by pressing **Win + R**, typing **regedit** in the text box, and clicking **OK**.

![regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/regedit.jpg)

 Click **Yes** to bypass the UAC prompt.

 In the address bar of the Registry Editor, copy and paste the following text into it:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\7516b95f-f776-4464-8c53-06167f40cc99\17aaa29b-8b43-4b94-aafe-35f64daaf1ee

 On the right panel, double-click the **Attributes** entry to open it up for editing.

![the attributes entry in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-dim-display-after-attributes-entry.jpg)

 Then, in the **Value data** text box, enter **1** to hide **Dim display after** in the Power Options menu or **2** to show it.

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

 Now you can open the Power Options menu (see [how to open the power options on Windows 10](https://www.makeuseof.com/windows-10-open-power-options/)) and check under **Display** to see if the **Dim display after** option is there or not.

## Controlling the “Dim Display After” Option in the Power Options Menu

 Now that you know how to show or hide **Dim display after**, you know what to do when you can’t find it in the Power Options menu or need to remove it. We recommend keeping it hidden and then bringing it up whenever you need it. This will make sure that no one messes with this important display setting when you’ve set it up perfectly.

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
<li><a href="https://screen-capture.techidaily.com/new-in-2024-essential-mac-tools-for-screen-capture-discovering-the-top-5/"><u>[New] In 2024, Essential Mac Tools for Screen Capture, Discovering the Top 5</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-amazon-prime-viewers-who-to-follow-on-twitter-now/"><u>[Updated] Amazon Prime Viewers - Who to Follow on Twitter, Now</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/android-unlock-code-sim-unlock-your-motorola-moto-g84-5g-phone-and-remove-locked-screen-by-drfone-android/"><u>Android Unlock Code Sim Unlock Your Motorola Moto G84 5G Phone and Remove Locked Screen</u></a></li>
<li><a href="https://tech-hub.techidaily.com/1722135539641-chatgpt-desktop-release-on-hold-no-problem-here-are-5-must-try-open-source-alternatives-for-immediate-use/"><u>ChatGPT Desktop Release On Hold? No Problem! Here Are 5 Must-Try Open Source Alternatives for Immediate Use!</u></a></li>
<li><a href="https://windows11.techidaily.com/improve-visual-quality-with-enhanced-scaling-on-windows-11/"><u>Improve Visual Quality with Enhanced Scaling on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/key-solutions-to-unlock-windows-firewall-access/"><u>Key Solutions to Unlock Windows Firewall Access</u></a></li>
<li><a href="https://extra-hints.techidaily.com/revolutionary-6-applications-to-enhance-photo-editing-experience/"><u>Revolutionary 6 Applications to Enhance Photo Editing Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-stalled-file-downloads-on-windows-11-and-11/"><u>Solutions for Stalled File Downloads on Windows 11 & 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/tips-and-tricks-for-setting-up-your-lava-yuva-2-pro-phone-pattern-lock-by-drfone-android/"><u>Tips and Tricks for Setting Up your Lava Yuva 2 Pro Phone Pattern Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/winx-blackout-strategies-to-restore-color-backgrounds/"><u>WinX Blackout: Strategies to Restore Color Backgrounds</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014850/22899" target="_top" id="2014850">
  <img src="//a.impactradius-go.com/display-ad/22899-2014850" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014850/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

