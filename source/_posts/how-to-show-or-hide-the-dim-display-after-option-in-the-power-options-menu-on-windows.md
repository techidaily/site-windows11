---
title: How to Show or Hide the “Dim Display After” Option in the Power Options Menu on Windows
date: 2024-10-01T02:38:47.409Z
updated: 2024-10-06T18:16:56.096Z
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902289/19272" target="_top" id="1902289">
  <img src="//a.impactradius-go.com/display-ad/19272-1902289" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902289/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Show or Hide the “Dim display after” Option Using the Registry Editor

 Considering how vital the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is for the smooth operation of Windows, you might want to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you edit it. Afterward, open the Registry Editor by pressing **Win + R**, typing **regedit** in the text box, and clicking **OK**.

![regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/regedit.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134493/18498" target="_top" id="2134493">
  <img src="//a.impactradius-go.com/display-ad/18498-2134493" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134493/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Click **Yes** to bypass the UAC prompt.

 In the address bar of the Registry Editor, copy and paste the following text into it:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\7516b95f-f776-4464-8c53-06167f40cc99\17aaa29b-8b43-4b94-aafe-35f64daaf1ee

 On the right panel, double-click the **Attributes** entry to open it up for editing.

![the attributes entry in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-dim-display-after-attributes-entry.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137223/26400" target="_top" id="2137223">
  <img src="//a.impactradius-go.com/display-ad/26400-2137223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137223/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then, in the **Value data** text box, enter **1** to hide **Dim display after** in the Power Options menu or **2** to show it.

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134242/18498" target="_top" id="2134242">
  <img src="//a.impactradius-go.com/display-ad/18498-2134242" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134242/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://fox-direct.techidaily.com/2024-approved-bridging-format-gaps-with-srt-transformations/"><u>2024 Approved Bridging Format Gaps with SRT Transformations</u></a></li>
<li><a href="https://fox-that.techidaily.com/end-the-disconnect-dilemma-smart-solutions-for-continuous-airpod-functionality-with-iphone/"><u>End the Disconnect Dilemma: Smart Solutions for Continuous AirPod Functionality with iPhone</u></a></li>
<li><a href="https://win-amazing.techidaily.com/how-to-overcome-ralink-rt3290-driver-glitches-in-windows-operating-systems/"><u>How to Overcome Ralink RT3290 Driver Glitches in Windows Operating Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/hunt-for-group-policy-a-win-users-manual/"><u>Hunt for Group Policy: A Win User's Manual</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-decoding-vlc-player-mac-usage-tips/"><u>In 2024, Decoding VLC Player Mac Usage Tips</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-poco-m6-5g-phone-without-password-by-drfone-android/"><u>In 2024, How To Unlock Poco M6 5G Phone Without Password?</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-stop-motion-magic-top-rated-apps-for-iphone-and-android/"><u>In 2024, Stop Motion Magic Top-Rated Apps for iPhone and Android</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-top-vr-game-creators-to-watch/"><u>In 2024, Top VR Game Creators To Watch</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-unveil-the-8-greatest-places-to-download-3d-text-psd-files/"><u>In 2024, Unveil the 8 Greatest Places to Download 3D Text PSD Files</u></a></li>
<li><a href="https://windows11.techidaily.com/invoking-celestial-power-in-windows-11-setup/"><u>Invoking Celestial Power in Windows 11 Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11s-multimedia-control-panel/"><u>Mastering Windows 11'S Multimedia Control Panel</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-memory-usage-in-windows-clearing-cache/"><u>Optimizing Memory Usage in Windows: Clearing Cache</u></a></li>
<li><a href="https://windows11.techidaily.com/pinnacle-gpu-checks-top-6-windows-software-choices/"><u>Pinnacle GPU Checks: Top 6 Windows Software Choices</u></a></li>
<li><a href="https://windows11.techidaily.com/resolve-the-enigma-how-to-solve-no-mail-on-windows-11-apps/"><u>Resolve the Enigma: How to Solve No Mail on Windows 11 Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/revitalize-your-clockwork-restore-missing-windows-server-time/"><u>Revitalize Your Clockwork: Restore Missing Windows Server Time</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-share-cant-be-opened-error-in-experience/"><u>Troubleshooting Share Can't Be Opened Error in Experience</u></a></li>
<li><a href="https://buynow-help.techidaily.com/ultimate-guide-to-choosing-the-perfect-protective-cases-for-ipads-9gen-in-2-023/"><u>Ultimate Guide to Choosing the Perfect Protective Cases for iPads (9Gen) in 2 023</u></a></li>
</ul></div>

