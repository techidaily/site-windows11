---
title: "The Edge Dilemma: Ethical Choices Amidst Societal Controls"
date: 2024-08-08T06:09:08.591Z
updated: 2024-08-09T06:09:08.591Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes The Edge Dilemma: Ethical Choices Amidst Societal Controls"
excerpt: "This Article Describes The Edge Dilemma: Ethical Choices Amidst Societal Controls"
keywords: Ethics vs Society,Moral Dilemmas,Societal Constraints,Ethical Decisions,Edge Analysis,Social Boundaries,Controlled Choices
thumbnail: https://thmb.techidaily.com/4f442cf2fb2227aedd89e7821028b21747d22144c354cf210b05071a53d43806.jpg
---

## The Edge Dilemma: Ethical Choices Amidst Societal Controls

 Microsoft's Application Guard for Edge is a great tool to shield your browsing from malicious interference. For extra protection, both the camera and microphone are deactivated by default in this environment; however, there may be times when you need these features enabled to utilize certain web applications.

 If that’s the case, follow this guide which will show you how to enable the camera and microphone in Application Guard for Edge on Windows 11\. ​​​​​​

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
## 1\. How to Enable the Camera and Microphone via Windows Settings

 To enable the camera and microphone in Application Guard for Edge, follow the steps below:

1. Click on Start, type**Settings** and press**Enter** .
2. On the left side of the screen, select**Privacy & security** .
3. Click the**Windows Security** option on the right.
4. Then, on the next screen, select**App & browser control** .
5. In the new window that opens, click**Change Application Guard settings** under Isolated browsing.
6. Look for the**Camera and microphone** option, and then toggle it on.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
![Enable Camera and Microphone in Application Guard Using Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-camera-and-microphone-in-application-guard-using-windows-settings.jpg)
7. If the UAC prompt appears, click**Yes** to continue.

 After you perform the above action, restart your computer for the changes to take effect. Upon restarting, all your camera and microphone settings should now be applied to the Application Guard for Edge.

 In case you need to turn off the feature again, just follow the same steps and toggle the Camera and microphone option to Off. That’s all there is to it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## 2\. How to Enable the Camera and Microphone Using Registry Editor

 If you are more comfortable using the registry editor, you can enable your camera and microphone for Application Guard for Edge. All you need to do is open up the registry folder, make a few easy modifications, and restart your computer so that they can take effect.

 However, before you make any changes, it's essential that you[create a backup of the registry file](https://www.makeuseof.com/tag/backup-restore-windows-registry/) just in case something goes wrong.

 To enable your mic & camera with the help of this tool, follow these steps:

1. Search for**regedit** in the Windows search bar and click on the result to open the registry editor. To find out more, see[how to open the registry](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. When the UAC prompt appears, click**Yes** to confirm.
3. In the Registry Editor window, go to the following location:  
Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Hvsi  
 Copy and paste the given location into the address bar at the top of the registry window and press Enter to quickly jump to the folder.
4. If you don't see the**Hvsi** key there, you need to create it first. In order to do this, right-click on the**Microsoft** folder and select**New > Key** .
5. Name the file**Hvsi** , then hit**Enter** to save it.  
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Creating a new DWORD (32-bit) Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-dword-enableclipboard-key.jpg)
6. Right-click on Hvsi, choose**New > DWORD (32-bit) Value** , then name it**EnableCameraMicrophoneRedirection** .
7. Now double-click on the newly created DWORD key, and you will see a pop-up window appear.
8. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
![Enable Camera and Microphone in Application Guard Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-camera-and-microphone-in-application-guard-using-registry-editor.jpg)
9. Then click**OK** to save the changes.

 Once you've done editing the registry, restart your computer to apply the changes. After restarting, Edge's Application Guard will be able to access your camera and microphone hardware for websites that require it.

 If you want to revert the changes, simply set the EnableCameraMicrophoneRedirection key’s value back to**0** and restart your computer.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Your Camera and Mic Is Now Supported in Edge Application Guard

 Application Guard for Edge is a tool that serves as an extra layer of protection from malicious websites and other threats. By default, your camera and microphone are disabled to ensure maximum security. In this guide, we've explained two quick ways in which you can easily activate these features - via Windows Settings or Registry Editor.


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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-executing-the-last-goodbye-to-your-instagram-account/"><u>[New] 2024 Approved  Executing the Last Goodbye to Your Instagram Account</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-classic-chimes-catalogue-websites-of-worth/"><u>[New] Classic Chimes Catalogue  Websites of Worth</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-in-2024-fine-tuning-your-fly-top-tips-for-choosing-drone-propellers/"><u>[New] In 2024, Fine-Tuning Your Fly  Top Tips for Choosing Drone Propellers</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-prime-maker-of-free-fb-photovideo-content/"><u>[Updated] In 2024, Prime Maker of FREE FB Photo/Video Content</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-user-folder-names-on-windows-11/"><u>Altering User Folder Names on Windows 11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/best-virtual-reality-finger-guards-unveiled-for-2024/"><u>Best Virtual Reality Finger Guards Unveiled for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-performance-and-productivity-in-windows-1011/"><u>Boosting Performance & Productivity in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-power-start-cmd-as-administrator/"><u>Boosting Power: Start CMD as Administrator</u></a></li>
<li><a href="https://windows11.techidaily.com/can-you-get-rid-of-the-windows-bt-directories/"><u>Can You Get Rid of the Windows ~BT Directories?</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-absent-msvcr110dll-in-windows/"><u>Correcting Absent msvcr110.dll in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-wins-system-alert-messages-in-windows-1011/"><u>Correcting WINS System Alert Messages in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-cause-of-display-driver-non-startups/"><u>Deciphering the Cause of Display Driver Non-Startups</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-mysteries-of-ram-in-windows-devices/"><u>Decoding the Mysteries of RAM in Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-guide-to-securing-edge-ms-defender-application-guard-on-windows-11/"><u>Easy Guide to Securing Edge: MS Defender Application Guard on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-managing-events-with-windows-11-calendar/"><u>Efficiently Managing Events with Windows 11 Calendar</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-empty-folder-warning-in-windows-11/"><u>Eliminating 'Empty Folder' Warning in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-monochrome-issues-with-windows-store/"><u>Fixing Monochrome Issues with Windows Store</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-wire-free-audio-on-windows-airpods/"><u>Guide to Wire-Free Audio on Windows (AirPods)</u></a></li>
<li><a href="https://windows11.techidaily.com/guides-to-mastering-your-fax-interface-with-w11s-tools/"><u>Guides to Mastering Your Fax Interface with W11's Tools</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-nokia-c300-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Nokia C300 in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-show-wi-fi-password-on-tecno-spark-go-2024-by-drfone-android/"><u>How to Show Wi-Fi Password on Tecno Spark Go (2024)</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-resolve-your-apple-iphone-14-keeps-asking-for-outlook-password-drfone-by-drfone-ios/"><u>In 2024, Resolve Your Apple iPhone 14 Keeps Asking for Outlook Password | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/instant-permadelete-configuring-your-desktop-trash-bin-on-windows-11-devices/"><u>Instant PermaDelete: Configuring Your Desktop Trash Bin on Windows 11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/live-transcribing-made-easy-the-whisper-way/"><u>Live Transcribing Made Easy - The Whisper Way</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-powershell-to-break-free-from-windows-file-blocks/"><u>Mastering PowerShell to Break Free From Windows File Blocks</u></a></li>
<li><a href="https://windows11.techidaily.com/prevent-discord-from-checking-for-updates-on-startup/"><u>Prevent Discord From Checking for Updates on Startup</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-setup-guide-for-launching-windows-media-player/"><u>Quick Setup Guide for Launching Windows Media Player</u></a></li>
<li><a href="https://windows11.techidaily.com/reconnecting-bluetooth-on-windows-audio-only-fix-guide/"><u>Reconnecting Bluetooth on Windows: Audio Only Fix Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-diagnostics-enhancing-windows-11-troubleshooters/"><u>Reviving Diagnostics: Enhancing Windows 11 Troubleshooters</u></a></li>
<li><a href="https://win-able.techidaily.com/solving-persistent-black-screens-on-persona-5-strikers-gameplay/"><u>Solving Persistent Black Screens on Persona 5 Strikers Gameplay</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-making-excel-viewable-in-notepad/"><u>Strategies: Making Excel Viewable in Notepad</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-creative-processes-with-these-8-windows-best-apps/"><u>Streamline Creative Processes With These 8 Window's Best Apps</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/synthesizing-creativity-with-magix-music-maker-2024-review/"><u>Synthesizing Creativity with Magix Music Maker 2024 Review</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-winerror-x80780119-resolution/"><u>Techniques for WinError X80780119 Resolution</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-password-creation-companion-for-windows-users/"><u>The Ultimate Password Creation Companion for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/ultimate-bundle-premier-cost-free-windows-11-assistants/"><u>Ultimate Bundle: Premier Cost-Free Windows 11 Assistants</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-telnet-enablement-steps-explained/"><u>Windows 11 Telnet Enablement Steps Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-pause-auto-updates-no-more-prompts/"><u>Windows Pause Auto-Updates: No More Prompts!</u></a></li>
</ul></div>
