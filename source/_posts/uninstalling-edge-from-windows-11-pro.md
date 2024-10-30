---
title: Uninstalling Edge From Windows 11 Pro
date: 2024-10-25T16:39:59.153Z
updated: 2024-10-30T16:29:05.699Z
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

 Once you run the above commands, Microsoft Edge will be removed from your PC. If you want to install the browser in the future, you can do so by downloading it from the Microsoft Store.

 If you'd like to get more out of this tool, be sure to check out[the Windows Command Prompt commands you must know](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/) .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1972665/19272" target="_top" id="1972665">
  <img src="//a.impactradius-go.com/display-ad/19272-1972665" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972665/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047351/19272" target="_top" id="2047351">
  <img src="//a.impactradius-go.com/display-ad/19272-2047351" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047351/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. How to Uninstall Microsoft Edge Beta, Dev, or Canary Channel Builds Using the Settings App

 Unlike the stable version, removing a preview build of Microsoft Edge is relatively simple. You can uninstall it just like any other app. Here's how to do it using[Windows 11 Settings app](https://www.makeuseof.com/windows-11-settings-whats-new/) .

1. Press**Win + I** to open the Settings app.
2. Navigate to the**Apps** tab and click on**Installed apps** .
3. Scroll down to locate Microsoft Edge's preview build.
4. Click the**three-dot menu icon** next to it and select**Uninstall** .
5. Select**Uninstall** again when the confirmation pop-up appears.  
![Uninstall Microsoft Edge Beta From Windows 11 Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Beta-From-Windows-11-1.jpg)

 Aside from the Settings app, you can uninstall the browser from the Start menu or the Control Panel. See our guide to learn different[ways to uninstall built-in apps on Windows 11](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/) .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2052063/7443" target="_top" id="2052063">
  <img src="//a.impactradius-go.com/display-ad/7443-2052063" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2052063/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1918719/19272" target="_top" id="1918719">
  <img src="//a.impactradius-go.com/display-ad/19272-1918719" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918719/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-sharing-recording.techidaily.com/new-secrets-of-capturing-high-quality-xbox-games-on-screen-for-2024/"><u>[New] Secrets of Capturing High-Quality Xbox Games on Screen for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-ultimate-guide-to-high-quality-mac-frames-max-156-chars/"><u>[Updated] In 2024, Ultimate Guide to High-Quality Mac Frames (Max 156 Chars)</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-mastering-speed-removing-ssgnatures-immediately/"><u>[Updated] Mastering Speed Removing Ssgnatures Immediately</u></a></li>
<li><a href="https://tech-haven.techidaily.com/breaking-down-ai-concepts-in-simple-language/"><u>Breaking Down AI Concepts in Simple Language</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-error-0x80070570-a-guide-for-fixed-damaged-files/"><u>Bypassing Error 0X80070570: A Guide for Fixed Damaged Files</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-managing-applications-with-wpm-in-windows-11/"><u>Efficiently Managing Applications with WPM in Windows 11</u></a></li>
<li><a href="https://os-tips.techidaily.com/elevate-your-ipads-capabilities-introducing-orion-seamless-ipad-to-monitor-connectivity-for-enhanced-productivity/"><u>Elevate Your iPad's Capabilities: Introducing Orion - Seamless iPad to Monitor Connectivity for Enhanced Productivity</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-tiktok-to-see-more-content-on-your-realme-11-pro-drfone-by-drfone-virtual-android/"><u>How to Change Location on TikTok to See More Content On your Realme 11 Pro | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-photos-from-realme-note-50-by-fonelab-android-recover-photos/"><u>How to Rescue Lost Photos from Realme Note 50?</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-revive-non-starting-adobe-photoshop-on-ws11-and-11/"><u>How to Revive Non-Starting Adobe Photoshop on WS11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-swiftly-handle-stalled-gpsvc-process/"><u>How to Swiftly Handle Stalled GPSVC Process</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-infinix-hot-40i-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Infinix Hot 40i to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-audio-recorder-snag-with-error-9999-solution/"><u>Navigating Windows' Audio Recorder Snag with Error 9999 Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-task-execution-on-windows-adding-an-improved-run-utility/"><u>Optimizing Task Execution on Windows: Adding an Improved Run Utility</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windows-11-programs-for-faster-startups/"><u>Optimizing Windows 11 Programs for Faster Startups</u></a></li>
<li><a href="https://windows11.techidaily.com/seamlessly-access-lately-used-documents-in-windows/"><u>Seamlessly Access Lately Used Documents in Windows</u></a></li>
<li><a href="https://os-tips.techidaily.com/the-significance-of-heic-image-encoding-for-iphone-photography-key-facts-you-need-to-know/"><u>The Significance of HEIC Image Encoding for iPhone Photography: Key Facts You Need to Know</u></a></li>
</ul></div>

