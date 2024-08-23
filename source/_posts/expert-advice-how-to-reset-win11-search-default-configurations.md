---
title: "Expert Advice: How to Reset Win11 Search Default Configurations"
date: 2024-08-22T21:34:02.818Z
updated: 2024-08-23T21:34:02.818Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Expert Advice: How to Reset Win11 Search Default Configurations"
excerpt: "This Article Describes Expert Advice: How to Reset Win11 Search Default Configurations"
keywords: Windows 11 Reset Search,Change Win11 Search Default,Win11 Search Config Reset,Reset Search Settings Win11,Search Defaults Win11 Fix,Win11 Default Search Reset,Adjust Win11 Search Settings
thumbnail: https://thmb.techidaily.com/85d1b13c1ebb0877b2226a27f70682a117714d804f026be8d035e08eecc94b3e.jpg
---

## Expert Advice: How to Reset Win11 Search Default Configurations

 Like any other computer program, Windows Search can sometimes develop issues that require you to reset its settings to work properly. This article explains two simple ways to reset Windows Search settings back to default. Let's look at each one in detail.

## Why Should You Reset Windows Search Settings?

 Windows Search tracks files and folders on your hard drive, so you can find them more quickly. However, over time search settings and preferences can become corrupted, leading to incorrect search results or slow performance. To get the most effective results from Windows Search, you should periodically reset your search settings.

 Resetting search settings on Windows can improve search speed and accuracy. It gets rid of useless data and resolves errors or conflicts due to stored information. This can ultimately enhance your computer’s performance and provide a more efficient search experience.

 Let's now explore how to reset Windows Search settings.

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
![Reset Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-search.jpg)
6. Select this key, right-click on it, and choose **Modify**.
7. Set the value to **0** and click **OK** to save the changes.

 If the SetupCompletedSuccessfully key is missing, you will have to manually create it. To do this, right-click on the Windows Search key and select **New > DWORD (32-bit) Value**. Name this newly created key as **SetupCompletedSuccessfully** and set its value to **0**.

 After performing the steps above, close the Registry Editor and restart your computer for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Use Windows PowerShell

 If you prefer command-line solutions, you can use PowerShell to reset Windows Search settings. It involves running a few simple commands to restore search settings. Here's how to do it.

[Open the Microsoft Download Page](https://www.microsoft.com/en-us/download/100295) and download the ResetWindowsSearchBox.ps1 PowerShell script. Once downloaded, right-click on the file and select **Run with PowerShell**.

 If you see an error message _"Cannot be loaded because the running script is disabled on this system"_ you need to enable script execution first. To do that, [open PowerShell as a system administrator](http://www.makeuseof.com/windows-11-powershell-administrator/). Then type **Get-ExecutionPolicy** and press Enter.

![Restrict or Unrestrict the Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restrict-or-unrestrict-the-command.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
 If the output is **Restricted**, execute the following command to allow PowerShell scripts:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted

 After setting the execution policy, try running the ResetWindowsSearchBox.ps1 file again. Once the script is executed successfully, it resets Windows search settings.

![Reset Windows Search Via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-search-via-powershell.png)

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
 After resetting the Windows Search settings, you can restore the execution policy to its original settings. To do that, open PowerShell as an administrator again and execute the following command:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Restricted

 Once the execution policy is set back to its original value, restart your computer. The Windows Search settings should now be restored to their default state.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-non-playing-youtube-content-fixed-for-phonestablets/"><u>[New] 2024 Approved  Non-Playing YouTube Content  Fixed for Phones/Tablets</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-in-2024-how-to-manage-and-disable-recommended-podcast-episodes-in-spotify/"><u>[New] In 2024, How to Manage and Disable Recommended Podcast Episodes in Spotify</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-smooth-operations-direct-backup-of-camera-roll-images-to-social-media-apps-for-2024/"><u>[New] Smooth Operations  Direct Backup of Camera Roll Images to Social Media Apps for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-steps-to-secure-unmarked-stock-photos-for-business/"><u>[Updated] Steps to Secure Unmarked Stock Photos for Business</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-ultimate-non-twitter-social-sites-of-the-year/"><u>2024 Approved  Ultimate Non-Twitter Social Sites of the Year</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/apples-role-in-simplifying-educational-audio-archives-for-2024/"><u>Apple's Role in Simplifying Educational Audio Archives for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/dose-life360-notify-me-when-someone-checks-my-location-on-apple-iphone-14-drfone-by-drfone-virtual-ios/"><u>Dose Life360 Notify Me When Someone Checks My Location On Apple iPhone 14? | Dr.fone</u></a></li>
<li><a href="https://fox-http.techidaily.com/expedite-tech-advancement-how-to-embrace-macos-11-big-sur-for-2024/"><u>Expedite Tech Advancement  How to Embrace macOS 11 Big Sur for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/file-explorer-misses-out-on-sd-card-heres-fixing-it/"><u>File Explorer Misses Out on SD Card - Here's Fixing It</u></a></li>
<li><a href="https://windows11.techidaily.com/getting-started-with-the-windows-11-voice-chat/"><u>Getting Started with the Windows 11 Voice Chat</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-to-halt-safe-screensaver-modifications/"><u>Guidelines to Halt Safe Screensaver Modifications</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-the-file-not-displayed-problem-in-outlook-on-windows/"><u>Handling the File Not Displayed Problem in Outlook on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-dodge-perpetual-network-logon-errors-in-windows/"><u>How to Dodge Perpetual Network Logon Errors in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-enhance-your-os-with-psoft-menu-tools/"><u>How to Enhance Your OS with PSoft Menu Tools</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-hack-your-gmail-address-to-filter-messages-and-add-addresses/"><u>How to Hack Your Gmail Address to Filter Messages and Add Addresses</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-overcome-invalid-session-from-vac-steam-alert/"><u>How To Overcome Invalid Session From VAC Steam Alert</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-set-your-preferred-theme-and-font-in-the-windows-11-notepad/"><u>How to Set Your Preferred Theme and Font in the Windows 11 Notepad</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-hide-location-on-apple-iphone-12-mini-and-android-without-others-knowing-drfone-by-drfone-virtual-ios/"><u>In 2024, Hide location on Apple iPhone 12 mini and Android without others knowing | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-can-i-catch-the-regional-pokemon-without-traveling-on-honor-magic-6-lite-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Catch the Regional Pokémon without Traveling On Honor Magic 6 Lite | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-icloud-lock-from-iphone-xs-by-drfone-ios/"><u>In 2024, How to Bypass iCloud Lock from iPhone XS</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-streamline-your-video-upload-process-instagram-ready-sizing/"><u>In 2024, Streamline Your Video Upload Process  Instagram-Ready Sizing</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-ultimate-exploration-inside-xcreative-media-suite/"><u>In 2024, The Ultimate Exploration  Inside XCreative Media Suite</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-the-benefits-of-windows-11s-auto-hdr/"><u>Leveraging the Benefits of Windows 11'S Auto HDR</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-speech-recognition-in-seconds-whisper-guide/"><u>Mastering Speech Recognition in Seconds - Whisper Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-parent-lock-configurations/"><u>Mastering Windows 11 Parent Lock Configurations</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-powershell-activating-script-policies/"><u>Mastering Windows PowerShell: Activating Script Policies</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-resolve-it-admin-limited-warning/"><u>Methods to Resolve 'IT Admin Limited' Warning</u></a></li>
<li><a href="https://windows11.techidaily.com/minimizing-background-activity-windows/"><u>Minimizing Background Activity Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-microsoft-windows-update-setbacks-0xca00a009/"><u>Navigating Microsoft Windows Update Setbacks: 0XCA00A009</u></a></li>
<li><a href="https://windows11.techidaily.com/overhauling-dormant-windows-keys-for-functionality/"><u>Overhauling Dormant Windows Keys for Functionality</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/reasons-why-pokemon-gps-does-not-work-on-honor-80-pro-straight-screen-edition-drfone-by-drfone-virtual-android/"><u>Reasons why Pokémon GPS does not Work On Honor 80 Pro Straight Screen Edition? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-sound-error-error-0xc00d36b4-in-win11/"><u>Rectifying Sound Error: Error 0XC00D36B4 in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-code-0x0001-issue-geforce-software-w11/"><u>Solving Code 0X0001 Issue: GeForce Software W11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/solving-pairing-problems-a-guide-with-6-effective-strategies-for-your-apple-watch/"><u>Solving Pairing Problems: A Guide with 6 Effective Strategies for Your Apple Watch</u></a></li>
<li><a href="https://windows11.techidaily.com/steer-clear-of-windows-http-error-reduce-excessive-requests/"><u>Steer Clear of Window's HTTP Error: Reduce Excessive Requests</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-for-windows-users-converting-your-mp3s-into-professional-audio-cds-using-imgburn/"><u>The Ultimate Guide for Windows Users: Converting Your MP3s Into Professional Audio Cds Using ImgBurn</u></a></li>
<li><a href="https://some-skills.techidaily.com/top-10-webcams-elevating-audio-quality-in-podcasts-for-2024/"><u>Top 10 Webcams Elevating Audio Quality in Podcasts for 2024</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/unveiling-the-usage-shift-por-que-vs-por-que/"><u>Unveiling the Usage Shift: Por Que vs Por Qué</u></a></li>
<li><a href="https://change-location.techidaily.com/what-legendaries-are-in-pokemon-platinum-on-vivo-y200e-5g-drfone-by-drfone-virtual-android/"><u>What Legendaries Are In Pokemon Platinum On Vivo Y200e 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-mastering-cross-device-sticky-note-functionality/"><u>Windows 11: Mastering Cross-Device Sticky Note Functionality</u></a></li>
</ul></div>
