---
title: Guide to Reversing Customized Search in Windows 11
date: 2024-08-08T06:08:58.448Z
updated: 2024-08-09T06:08:58.448Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Reversing Customized Search in Windows 11
excerpt: This Article Describes Guide to Reversing Customized Search in Windows 11
keywords: Windows 11 Search Revival,Win11 Customize Search Guide,Reset Windows 11 Index,Restore Search Settings (Win11),Reversing Win11 Filter Options,Fixing Custom Search in Win11,Clear Win11 Customized Query
thumbnail: https://thmb.techidaily.com/0c4c453f95a612f76b387ff712305941e5398ae6df028882ef27bbdd6859fdde.jpg
---

## Guide to Reversing Customized Search in Windows 11

 Like any other computer program, Windows Search can sometimes develop issues that require you to reset its settings to work properly. This article explains two simple ways to reset Windows Search settings back to default. Let's look at each one in detail.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Why Should You Reset Windows Search Settings?

 Windows Search tracks files and folders on your hard drive, so you can find them more quickly. However, over time search settings and preferences can become corrupted, leading to incorrect search results or slow performance. To get the most effective results from Windows Search, you should periodically reset your search settings.

 Resetting search settings on Windows can improve search speed and accuracy. It gets rid of useless data and resolves errors or conflicts due to stored information. This can ultimately enhance your computer’s performance and provide a more efficient search experience.

 Let's now explore how to reset Windows Search settings.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Tweak the Registry Editor

 If you want to reset Windows Search settings back to default, you can modify the registry editor. It involves directly changing certain keys in the Windows Registry, which can sometimes become risky if done incorrectly.

 To avoid this issue, be sure to [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before proceeding. Once done, follow these steps.

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the dialog box and hit the Enter key.
3. When the UAC prompt appears on the screen, click **Yes** to continue.
4. In the Registry Editor window, navigate to the following path:  
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows Search  
 You can also copy and paste the path into the address bar at the top of the window and hit the Enter key. This will take you to the Windows Search section.
5. Now move to the right pane and search for the key named **SetupCompletedSuccessfully**.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
![Reset Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-search.jpg)
6. Select this key, right-click on it, and choose **Modify**.
7. Set the value to **0** and click **OK** to save the changes.

 If the SetupCompletedSuccessfully key is missing, you will have to manually create it. To do this, right-click on the Windows Search key and select **New > DWORD (32-bit) Value**. Name this newly created key as **SetupCompletedSuccessfully** and set its value to **0**.

 After performing the steps above, close the Registry Editor and restart your computer for the changes to take effect.

## 2\. Use Windows PowerShell

 If you prefer command-line solutions, you can use PowerShell to reset Windows Search settings. It involves running a few simple commands to restore search settings. Here's how to do it.

[Open the Microsoft Download Page](https://www.microsoft.com/en-us/download/100295) and download the ResetWindowsSearchBox.ps1 PowerShell script. Once downloaded, right-click on the file and select **Run with PowerShell**.

 If you see an error message _"Cannot be loaded because the running script is disabled on this system"_ you need to enable script execution first. To do that, [open PowerShell as a system administrator](http://www.makeuseof.com/windows-11-powershell-administrator/). Then type **Get-ExecutionPolicy** and press Enter.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
![Restrict or Unrestrict the Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restrict-or-unrestrict-the-command.png)

 If the output is **Restricted**, execute the following command to allow PowerShell scripts:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted

 After setting the execution policy, try running the ResetWindowsSearchBox.ps1 file again. Once the script is executed successfully, it resets Windows search settings.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35408920&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/FR-200-1.png" border="0">Glarysoft File Recovery Pro - Helps to recover your lost file/data, even permanently deleted data. </a>
<!-- affiliate ads end -->
![Reset Windows Search Via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-search-via-powershell.png)

 After resetting the Windows Search settings, you can restore the execution policy to its original settings. To do that, open PowerShell as an administrator again and execute the following command:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Restricted

 Once the execution policy is set back to its original value, restart your computer. The Windows Search settings should now be restored to their default state.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->
## Easy Ways to Reset Windows Search

 Resetting Windows search settings can fix any issues you may have with your search experience. This guide will teach you how to reset Windows Search settings to their original values.


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
<li><a href="https://youtube-webster.techidaily.com/ed-2024-approved-quick-step-by-step-turning-pictures-into-youtube-desktop-thumbnails/"><u>[Updated] 2024 Approved  Quick Step-By-Step  Turning Pictures Into YouTube Desktop Thumbnails</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-enhancing-meeting-success-with-microsoft-teams-snap-camera-for-2024/"><u>[Updated] Enhancing Meeting Success with Microsoft Teams Snap Camera for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-enhancing-visual-quests-hunt-for-pristine-pexels-images/"><u>[Updated] Enhancing Visual Quests  Hunt for Pristine Pexels Images</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-optimal-team-call-aesthetics-pre-call-and-post-call-tweaks/"><u>[Updated] Optimal Team Call Aesthetics  Pre-Call & Post-Call Tweaks</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-professional-photography-hacks-perfecting-motion-blur-with-adobe-tools-for-2024/"><u>[Updated] Professional Photography Hacks  Perfecting Motion Blur with Adobe Tools for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-pursuing-prolonged-iphone-night-sky-captures/"><u>2024 Approved  Pursuing Prolonged iPhone Night Sky Captures</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-who-takes-the-crown-in-action-camera-warfare/"><u>2024 Approved  Who Takes the Crown in Action Camera Warfare?</u></a></li>
<li><a href="https://windows11.techidaily.com/4-warning-signs-for-considering-pc-reset/"><u>4 Warning Signs for Considering PC Reset</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-typing-with-personal-hotkeys-in-windows/"><u>Accelerate Typing with Personal Hotkeys in Windows</u></a></li>
<li><a href="https://extra-information.techidaily.com/apple-music-add-on-for-smooth-video-playback/"><u>Apple Music Add-On for Smooth Video Playback</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-blocked-windows-guard-functions/"><u>Bypassing Blocked Windows Guard Functions</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-purpose-behind-windows-11-s-mode-feature/"><u>Deciphering the Purpose Behind Windows 11 S Mode Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/dive-into-ms-store-app-selection-2023-edition/"><u>Dive Into MS Store App Selection: 2023 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-webp-images-top-4-viewer-tools-on-windows-os/"><u>Elevate WebP Images: Top 4 Viewer Tools on Windows OS</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/elevate-your-meetings-with-teamsnap-expertise/"><u>Elevate Your Meetings with TeamSnap Expertise</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-for-correcting-windows-update-problems-0x30017/"><u>Expert Tips for Correcting Windows Update Problems (0X30017)</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-disconnection-problem-for-malwarebytes-in-windows-11/"><u>Fixing the Disconnection Problem for Malwarebytes in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-troubleshooters-not-working-in-windows-10-and-11/"><u>How to Fix the Troubleshooters Not Working in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-redo-on-windows-with-a-hotkey/"><u>How to Redo on Windows With a Hotkey</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-windows-from-always-entering-cmos-mode-at-start-up/"><u>How to Stop Windows From Always Entering CMOS Mode at Start-Up</u></a></li>
<li><a href="https://windows11.techidaily.com/identifying-programs-by-their-launch-shorthand-labels/"><u>Identifying Programs by Their Launch Shorthand Labels</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-the-nuances-of-windows-maintenance-and-update-scheduling/"><u>Navigate the Nuances of Windows Maintenance & Update Scheduling</u></a></li>
<li><a href="https://facebook.techidaily.com/1719152494885-newsfeed-no-more-complicated-facebooks-revolutionary-upgrade/"><u>Newsfeed No More Complicated – Facebook's Revolutionary Upgrade!</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-generic-sound-not-recognized-issue-in-windows-system/"><u>Overcoming Generic Sound Not Recognized Issue in Windows System</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-hurdle-of-non-responding-email-alerts-on-pcs/"><u>Overcoming the Hurdle of Non-Responding Email Alerts on PCs</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/panasonic-hx-a1-revolutionizing-wearable-cameras-for-the-outdoors-for-2024/"><u>Panasonic HX-A1  Revolutionizing Wearable Cameras for the Outdoors for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/reduce-keyboard-latency-in-win-os-with-top-7-hacks/"><u>Reduce Keyboard Latency in Win OS with Top 7 Hacks</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-lost-wi-fi-links-top-strategies-to-regain-internet-connection-on-windows-10/"><u>Reviving Lost Wi-Fi Links: Top Strategies to Regain Internet Connection on Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-windows-searches-using-everythingapp/"><u>Streamline Windows Searches Using EverythingApp</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/streamlining-sound-systems-uploads-for-your-youtube-hub/"><u>Streamlining Sound Systems  Uploads for Your Youtube Hub</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/the-secret-sauce-to-instagram-success-with-engaging-puzzles/"><u>The Secret Sauce to Instagram Success with Engaging Puzzles</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-ideas-into-art-the-best-drawing-apps-ranked-in-win10/"><u>Transforming Ideas Into Art: The Best Drawing Apps Ranked in Win10</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-integration-mastery-overcoming-add-on-installation-roadblocks/"><u>Windows Integration Mastery: Overcoming Add-On Installation Roadblocks</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-the-battle-against-installer-error-messages-on-pcs/"><u>Winning the Battle Against Installer Error Messages on PCs</u></a></li>
</ul></div>