---
title: How to Show or Hide the “Dim Display After” Option in the Power Options Menu on Windows
date: 2024-09-14T23:28:03.447Z
updated: 2024-09-15T22:58:23.741Z
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
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-2020s-windows-updates-a-quick-overview/"><u>[Updated] 2024 Approved 2020'S Windows Updates A Quick Overview</u></a></li>
<li><a href="https://win-answers.techidaily.com/1726029145172-adobe-premiere-pro/"><u>Adobe Premiere Pro: 効果的にビデオアスペクト比調整ガイド</u></a></li>
<li><a href="https://apple-account.techidaily.com/everything-to-know-about-apple-id-password-requirements-for-iphone-14-pro-by-drfone-ios/"><u>Everything To Know About Apple ID Password Requirements For iPhone 14 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-drive-unformatted-notice-in-windows-os/"><u>Fixing Drive Unformatted Notice in Windows OS</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/hilarious-tricks-and-gags-ultimate-guide-for-iphone-and-ipad-pranks-with-friends/"><u>Hilarious Tricks & Gags: Ultimate Guide for iPhone & iPad Pranks with Friends</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-achieving-flawless-hues-in-gopro-videos/"><u>In 2024, Achieving Flawless Hues in GoPro Videos</u></a></li>
<li><a href="https://sound-issues.techidaily.com/logitech-g230-microphone-not-working-heres-the-solution/"><u>Logitech G230 Microphone Not Working? Here's the Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-issues-with-touchpad-gestures-in-windows-systems/"><u>Overcoming Issues with Touchpad Gestures in Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-net-runtime-issue-on-your-system/"><u>Overcoming the .NET Runtime Issue on Your System</u></a></li>
<li><a href="https://program-issues.techidaily.com/1722988454128-the-elusive-rust-visual-flaw-is-finally-gone-find-out-how/"><u>The Elusive Rust Visual Flaw Is Finally Gone! Find Out How</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137219/26400" target="_top" id="2137219">
  <img src="//a.impactradius-go.com/display-ad/26400-2137219" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137219/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

