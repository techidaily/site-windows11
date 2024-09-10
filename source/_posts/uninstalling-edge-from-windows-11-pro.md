---
title: Uninstalling Edge From Windows 11 Pro
date: 2024-09-09T12:13:48.574Z
updated: 2024-09-10T12:13:48.574Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Uninstalling Edge From Windows 11 Pro
excerpt: This Article Describes Uninstalling Edge From Windows 11 Pro
keywords: Uninstall Microsoft Edge,Remove Edge Browser,Disable Edge in Win11,Delete Edge App,Extract From Windows 11,Clear Edge on Pro Edition,Expunge Edge Browser
thumbnail: https://thmb.techidaily.com/0275b65ec50c26c096fbd58891ad5416742f7595ba3ecd2f30cf7442df5bd214.png
---

## Uninstalling Edge From Windows 11 Pro

 Although Microsoft Edge has made significant progress in recent years, it still lags far behind its biggest rival—Google Chrome. If you’re someone who does not like using Microsoft Edge, you may want to get rid of the browser entirely.

 It’s no secret that Microsoft wants users to use its own browser on Windows 11\. To that end, the company has made it difficult to remove the browser from Windows 11\. However, it’s still possible to do so. Here we'll show you three different ways to uninstall Microsoft Edge from your Windows 11 PC.

<!-- affiliate ads begin -->
<a href="https://smilemakers.pxf.io/c/5597632/2123899/26106" target="_top" id="2123899">
  <img src="//a.impactradius-go.com/display-ad/26106-2123899" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://smilemakers.pxf.io/i/5597632/2123899/26106" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. How to Uninstall Microsoft Edge Using the Command Prompt

 You can uninstall Microsoft Edge from your PC by running a few commands in the command prompt. The process requires you to know the version number of Microsoft Edge on your computer. Once you have that, you can get rid of the browser.

Here are the steps you need to follow.

1. Open Microsoft Edge on your PC.
2. Click the**three-dot menu icon** in the top right corner and select**Help and feedback > About Microsoft Edge** .
3. Copy Microsoft Edge's version number from the**About** section.  
![Check Microsoft Edge Version Number](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Microsoft-Edge-Version-Number.jpg)
4. Press**Win + X** and select**Terminal (Admin)** from the menu that appears.
5. Select**Yes** when the User Account Control (UAC) prompt shows up.
6. In the console, run the following commands to navigate to the directory where Microsoft Edge is installed:  
`cd/  
cd %Program Files (x86)%\Microsoft\Edge\Application\EdgeVersion\Installer`  
 Replace**EdgeVersion** in the above command with the actual version number noted earlier.
7. Paste the following command and press**Enter** to uninstall Microsoft Edge.  
`setup --uninstall --force-uninstall --system-level`  
![Uninstall Microsoft Edge Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Using-Command-Prompt.jpg)

<!-- affiliate ads begin -->
<span id="2127886">
					<video width="576" height="1024" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2127886.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2127886">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2127886.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2127886%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2127886/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Once you run the above commands, Microsoft Edge will be removed from your PC. If you want to install the browser in the future, you can do so by downloading it from the Microsoft Store.

 If you'd like to get more out of this tool, be sure to check out[the Windows Command Prompt commands you must know](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/) .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118311/7443" target="_top" id="2118311">
  <img src="//a.impactradius-go.com/display-ad/7443-2118311" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118311/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. How to Uninstall Microsoft Edge Using Windows PowerShell

 Like Command Prompt, you can also use Windows PowerShell to uninstall Microsoft Edge from your Windows 11 PC. Unlike the previous method, this one does not require you to know Microsoft Edge's version number. Here's how it works.

1. Press**Win + S** to open the search menu. Type in**Windows PowerShell** and select**Run as administrator** .
2. Select**Yes** when the[User Account Control (UAC)](https://www.makeuseof.com/tag/user-account-control-windows-10/) prompt appears.
3. Paste the following command and press**Enter** .  
`get-appxpackage *edge*`  
![Uninstall Microsoft Edge With Windows PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Using-Windows-PowerShell-1.jpg)
4. Highlight the text next to**PackageFullName** and press**Ctrl + C** to copy it.
5. Run the following command to uninstall Microsoft Edge.  
`Remove-appxpackage <PackageFullName>`  
 Replace**<PackageFullName>** in the above command with the package name copied earlier.

 Once you execute the above command, Microsoft Edge will be uninstalled.

## 3\. How to Uninstall Microsoft Edge Beta, Dev, or Canary Channel Builds Using the Settings App

 Unlike the stable version, removing a preview build of Microsoft Edge is relatively simple. You can uninstall it just like any other app. Here's how to do it using[Windows 11 Settings app](https://www.makeuseof.com/windows-11-settings-whats-new/) .

1. Press**Win + I** to open the Settings app.
2. Navigate to the**Apps** tab and click on**Installed apps** .
3. Scroll down to locate Microsoft Edge's preview build.
4. Click the**three-dot menu icon** next to it and select**Uninstall** .
5. Select**Uninstall** again when the confirmation pop-up appears.  
![Uninstall Microsoft Edge Beta From Windows 11 Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Beta-From-Windows-11-1.jpg)

<!-- affiliate ads begin -->
<span id="1993654">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993654.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993654">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993654.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993654%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993654/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Aside from the Settings app, you can uninstall the browser from the Start menu or the Control Panel. See our guide to learn different[ways to uninstall built-in apps on Windows 11](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/) .

<!-- affiliate ads begin -->
<span id="1424533">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424533.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424533">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424533.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424533%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424533/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Stop Microsoft Edge From Reinstalling on Windows 11

 Although uninstalling Edge from your computer is easy, it does not prevent newer Windows updates from potentially reinstalling the browser. To get around this, you need to[edit a few registry files](https://www.makeuseof.com/windows-registry-file-guide/) on your PC. For that, use the following steps:

1. Press**Win + R** to open the Run dialog box.
2. Type**regedit** in the box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the Registry Editor window that appears, navigate to**HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft** key.
5. Right-click on the**Microsoft** key, go to**New** , and select**Key** from the submenu. Rename the key to**EdgeUpdate** .
6. Right-click on the**EdgeUpdate** key and select**New > DWORD (32-bit) Value** . Rename the DWORD to**DoNotUpdateToEdgeWithChromium** .
7. Double-click on the newly created DWORD and change its value data to**1** . Then, hit**OK** .  
![Edit DWORD in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/edit-dword-in-registry-editor.jpg)

 Once you complete the above steps, Windows will not reinstall Microsoft Edge with future updates.

<!-- affiliate ads begin -->
<span id="1495277">
					<video width="1536" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1495277.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/17189-1495277">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1495277.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:960px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ffunwhole.sjv.io%2Fc%2F5597632%2F1495277%2F17189'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1495277/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get Rid of Microsoft Edge

 With Windows 11, Microsoft tried everything possible to entice users to switch to Microsoft Edge. Unfortunately, it hasn't worked out very well, as many people still prefer to use alternatives like Google Chrome. If you are one of them, you can get rid of Microsoft Edge using the steps outlined above.

 Now that you've uninstalled Microsoft Edge, you might want to make your preferred web browser the default option on Windows 11.


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
<li><a href="https://vp-tips.techidaily.com/new-in-2024-perfect-your-content-with-tiktoks-number-manipulation-tricks/"><u>[New] In 2024, Perfect Your Content with TikTok's Number Manipulation Tricks</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-simplifying-video-cutting-in-windows-10-a-photoshop-free-guide/"><u>[Updated] Simplifying Video Cutting in Windows 10 A Photoshop-Free Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/1-mastering-excel-a-step-by-step-guide-on-implementing-the-less-than-or-equal-to-operator/"><u>1. Mastering Excel: A Step-by-Step Guide on Implementing the 'Less than or Equal To' Operator</u></a></li>
<li><a href="https://windows11.techidaily.com/1-mastering-excel-a-step-by-step-guide-to-revealing-hidden-data/"><u>1. Mastering Excel: A Step-by-Step Guide to Revealing Hidden Data</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/mp4mp3-mp4/"><u>大きく軽やかに！一度で全てのMP4をMP3にシームレス変換方法 - MP4オーディオ素材取り出し指南</u></a></li>
<li><a href="https://windows11.techidaily.com/change-excel-gridlines-hue-a-comprehensive-tutorial/"><u>Change Excel Gridlines Hue: A Comprehensive Tutorial</u></a></li>
<li><a href="https://extra-information.techidaily.com/delving-deeper-into-vlc-players-unseen-functions/"><u>Delving Deeper Into VLC Player's Unseen Functions</u></a></li>
<li><a href="https://fox-http.techidaily.com/discovering-cinematic-splendor-in-4k-lgs-digital-cinema-31mu97-b/"><u>Discovering Cinematic Splendor in 4K LG's Digital Cinema 31MU97-B</u></a></li>
<li><a href="https://windows11.techidaily.com/ditch-the-expensive-software-mastering-project-management-with-just-excel/"><u>Ditch the Expensive Software - Mastering Project Management with Just Excel</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-implementing-macros-into-your-quick-access-toolbar/"><u>Easy Steps: Implementing Macros Into Your Quick Access Toolbar</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-converting-dynamic-excel-equations-to-fixed-numbers-in-excel-2013/"><u>Efficiently Converting Dynamic Excel Equations to Fixed Numbers in Excel 2013</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-techniques-for-eliminating-borders-and-guides-in-your-excel-spreadsheets/"><u>Effortless Techniques for Eliminating Borders & Guides in Your Excel Spreadsheets</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-unit-transformation-techniques-with-microsoft-excel-tutorials/"><u>Effortless Unit Transformation Techniques with Microsoft Excel Tutorials</u></a></li>
<li><a href="https://windows11.techidaily.com/examining-disparities-in-file-types-exe-vs-msi/"><u>Examining Disparities in File Types: Exe vs Msi</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-level-strategies-for-mastering-windows-voice-access/"><u>Expert-Level Strategies for Mastering Windows Voice Access</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tune-fn-keys-for-windows-1011-efficiency/"><u>Fine-Tune FN Keys for Windows 10/11 Efficiency</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-recover-from-network-not-found-error-windows/"><u>How to Recover From 'Network Not Found' Error Windows</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-unlock-icloud-activation-lock-and-icloud-account-on-iphone-13-pro-max-by-drfone-ios/"><u>How to Unlock iCloud Activation Lock and iCloud Account On iPhone 13 Pro Max?</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-pokemon-emerald-master-ball-cheat-on-vivo-y100-drfone-by-drfone-virtual-android/"><u>How to Use Pokémon Emerald Master Ball Cheat On Vivo Y100 | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-methods-to-change-gps-location-on-nubia-red-magic-8s-proplus-drfone-by-drfone-virtual-android/"><u>In 2024, Methods to Change GPS Location On Nubia Red Magic 8S Pro+ | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-navigating-the-world-of-srt-alteration-in-macos-systems/"><u>In 2024, Navigating the World of SRT Alteration in macOS Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/inside-look-windows-executable-and-linker-format-pe/"><u>Inside Look: Windows' Executable & Linker Format (PE)</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-cell-references-seamlessly-linking-data-across-excel-workbooks/"><u>Mastering Cell References: Seamlessly Linking Data Across Excel Workbooks</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-comment-filtering-a-step-by-step-guide-on-searching-within-excel-comments/"><u>Mastering Comment Filtering: A Step-by-Step Guide on Searching Within Excel Comments</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-excels-essential-logical-operators-if-and-or-xor-and-not/"><u>Mastering Excel's Essential Logical Operators: IF, AND, OR, XOR, and NOT</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-number-formatting-how-to-precisely-add-prefixes-like-zeroes-in-excel-cells/"><u>Mastering Number Formatting: How To Precisely Add Prefixes Like Zeroes in Excel Cells</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-hidden-feature-starting-word-excel-and-powerpoint-with-enhanced-security-settings/"><u>Mastering the Hidden Feature: Starting Word, Excel, and PowerPoint with Enhanced Security Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-excels-latest-update-introduces-advanced-data-consolidation-features/"><u>Microsoft Excel's Latest Update Introduces Advanced Data Consolidation Features</u></a></li>
<li><a href="https://windows11.techidaily.com/minimizing-windows-extender-lowering-cpu-demand/"><u>Minimizing Windows Extender: Lowering CPU Demand</u></a></li>
<li><a href="https://win-answers.techidaily.com/modern-warfare-mw3-crash-mystery-solved-overcome-the-dauntinig-error-6068/"><u>Modern Warfare MW3 Crash Mystery Solved: Overcome the Dauntinig Error 6068</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-art-of-ping-utilization-windows-style/"><u>Navigating the Art of Ping Utilization Windows-Style</u></a></li>
<li><a href="https://extra-resources.techidaily.com/perfectly-pair-audio-visual-delights-top-6-music-video-apps-for-android/"><u>Perfectly Pair Audio-Visual Delights Top 6 Music Video Apps for Android</u></a></li>
<li><a href="https://windows11.techidaily.com/quelling-an-irritating-mouse-on-a-windows-10/"><u>Quelling an Irritating Mouse on a Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/rapid-rendezvous-initiating-startup-unlocking-notepad/"><u>Rapid Rendezvous: Initiating Startup, Unlocking Notepad</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-dns-cache-a-quick-tutorial-for-windows-users/"><u>Resetting DNS Cache: A Quick Tutorial for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-dormant-wsreset-utility-on-computers/"><u>Restoring Dormant WSReset Utility on Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-old-data-in-excel-a-step-by-step-guide/"><u>Restoring Old Data in Excel: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-disabled-pin-removal-tool-on-windows-11-pc/"><u>Reviving Disabled PIN Removal Tool on Windows 11 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-way-to-refresh-your-windows-update-system/"><u>Seamless Way to Refresh Your Windows Update System</u></a></li>
<li><a href="https://location-social.techidaily.com/simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-vivo-t2-5g-drfone-by-drfone-virtual-android/"><u>Simple and Effective Ways to Change Your Country on YouTube App Of your Vivo T2 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-microsoft-error-code-x00000000/"><u>Solutions to Microsoft Error Code X00000000</u></a></li>
<li><a href="https://windows11.techidaily.com/speeding-up-windows-printers-instantly/"><u>Speeding Up Windows Printers Instantly</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-eliminate-error-a00f425d-in-windows-11s-camera-app/"><u>Steps to Eliminate Error A00F425D in Windows 11'S Camera App</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-approach-to-toolbar-mastery-in-microsoft-win11/"><u>Tailored Approach to Toolbar Mastery in Microsoft Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-monitorscape-crafting-individual-themes-for-each-window-of-win-1011/"><u>Tailored Monitorscape: Crafting Individual Themes for Each Window of Win 10/11</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/top-rated-smart-lighting-solutions/"><u>Top-Rated Smart Lighting Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-discrepancies-in-discords-windows-game-detection/"><u>Troubleshooting Discrepancies in Discord's Windows Game Detection</u></a></li>
<li><a href="https://windows11.techidaily.com/unblock-file-uploads-mastering-chromes-sync-on-a-win-os/"><u>Unblock File Uploads: Mastering Chrome's Sync on a Win OS</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-insights-in-numbers-a-guide-to-excel-quick-analysis-for-impactful-data-graphs-and-charts/"><u>Unlocking Insights in Numbers: A Guide to Excel Quick Analysis for Impactful Data Graphs and Charts</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-are-there-better-alternatives-to-magix-samplitude-for-professional-sound-design/"><u>Updated Are There Better Alternatives to MAGIX Samplitude for Professional Sound Design?</u></a></li>
<li><a href="https://windows11.techidaily.com/updating-old-pcs-think-beyond-windows/"><u>Updating Old PCs? Think Beyond Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/upgrading-desktop-visuals-integrate-custom-weather-icon-into-windows-status-area/"><u>Upgrading Desktop Visuals: Integrate Custom Weather Icon Into Windows Status Area</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-cloud-download-vs-local-reinstall-how-do-they-differ/"><u>Windows Cloud Download Vs. Local Reinstall: How Do They Differ?</u></a></li>
</ul></div>
