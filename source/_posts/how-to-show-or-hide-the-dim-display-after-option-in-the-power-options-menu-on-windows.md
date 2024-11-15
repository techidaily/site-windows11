---
title: How to Show or Hide the “Dim Display After” Option in the Power Options Menu on Windows
date: 2024-11-11T16:21:31.403Z
updated: 2024-11-15T17:09:27.829Z
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
<a href="https://aligracehair.sjv.io/c/5597632/1997662/19272" target="_top" id="1997662">
  <img src="//a.impactradius-go.com/display-ad/19272-1997662" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997662/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Show or Hide the “Dim display after” Option Using the Registry Editor

 Considering how vital the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is for the smooth operation of Windows, you might want to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you edit it. Afterward, open the Registry Editor by pressing **Win + R**, typing **regedit** in the text box, and clicking **OK**.

![regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/regedit.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135353/19272" target="_top" id="2135353">
  <img src="//a.impactradius-go.com/display-ad/19272-2135353" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135353/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Click **Yes** to bypass the UAC prompt.

 In the address bar of the Registry Editor, copy and paste the following text into it:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\7516b95f-f776-4464-8c53-06167f40cc99\17aaa29b-8b43-4b94-aafe-35f64daaf1ee

 On the right panel, double-click the **Attributes** entry to open it up for editing.

![the attributes entry in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-dim-display-after-attributes-entry.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123734/7443" target="_top" id="2123734">
  <img src="//a.impactradius-go.com/display-ad/7443-2123734" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123734/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then, in the **Value data** text box, enter **1** to hide **Dim display after** in the Power Options menu or **2** to show it.

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

 Now you can open the Power Options menu (see [how to open the power options on Windows 10](https://www.makeuseof.com/windows-10-open-power-options/)) and check under **Display** to see if the **Dim display after** option is there or not.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118311/7443" target="_top" id="2118311">
  <img src="//a.impactradius-go.com/display-ad/7443-2118311" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118311/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://article-files.techidaily.com/new-2024-approved-click-into-art-ultimate-edits-for-stunning-snaps/"><u>[New] 2024 Approved Click Into Art Ultimate Edits for Stunning Snaps</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-revolutionary-6-sustainable-minecraft-homes/"><u>[New] In 2024, Revolutionary 6 Sustainable Minecraft Homes</u></a></li>
<li><a href="https://some-guidance.techidaily.com/controler-facilement-le-format-video-convertissez-votre-mkv-en-avi-sans-frais-via-notre-service-en-ligne-videaste-pro-expertise/"><u>Contrôler Facilement Le Format Vidéo: Convertissez Votre MKV en AVI Sans Frais via Notre Service en Ligne - Vidéaste Pro-Expertise</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/decode-and-resolve-why-isnt-my-apple-watch-capturing-every-move/"><u>Decode and Resolve: Why Isn't My Apple Watch Capturing Every Move?</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-windows-junk-uninstall-list-revealed/"><u>Essential Windows Junk: Uninstall List Revealed</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-steps-for-ms-office-installation-on-windows-1011/"><u>Guiding Steps for MS Office Installation on Windows 10/11</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-nubia-red-magic-8s-pro-drfone-by-drfone-virtual/"><u>In 2024, 9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Nubia Red Magic 8S Pro | Dr.fone</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-apple-iphone-12-pro-to-other-iphone-without-icloud-drfone-by-drfone-transfer-from-ios/"><u>In 2024, How to Transfer Photos from Apple iPhone 12 Pro to other iPhone without iCloud | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-error-code-0x0001-on-nvidias-geforce-with-windows-11/"><u>Resolving Error Code 0X0001 on Nvidia's GeForce with Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-vanished-windows-badge-icons/"><u>Reviving Vanished Windows Badge Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-phone-integration-for-retailers-using-windows-11-and-intel-unison/"><u>Seamless Phone Integration for Retailers Using Windows 11 & Intel Unison</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/step-by-step-process-to-get-a-clean-canvas-in-figma/"><u>Step-by-Step Process to Get a Clean Canvas in Figma</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-disregard-error-components-not-present-in-win10win11/"><u>Steps to Disregard Error: Components Not Present in Win10/Win11</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/top-10-animation-software-for-creating-stunning-animated-videos-for-2024/"><u>Top 10 Animation Software for Creating Stunning Animated Videos for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-12-prominent-xiaomi-redmi-k70-fingerprint-not-working-solutions-by-drfone-android/"><u>Top 12 Prominent Xiaomi Redmi K70 Fingerprint Not Working Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-virtual-machines-matching-windows-11-specs/"><u>Winning Virtual Machines Matching Windows 11 Specs</u></a></li>
</ul></div>

