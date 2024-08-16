---
title: Uninstalling the Default Software on Win11 PCs
date: 2024-08-15T15:46:15.604Z
updated: 2024-08-16T15:46:15.604Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Uninstalling the Default Software on Win11 PCs
excerpt: This Article Describes Uninstalling the Default Software on Win11 PCs
keywords: Win11 Uninstall Guide,Default App Removal,Windows 11 Cleanup,System Default Deletion,Built-In Software Removal,Win11 Exclusive Tools,PC Customization Tips
thumbnail: https://thmb.techidaily.com/13632811731c559bc127701456401507af159186a9de22e1aa59a5e7f9127b24.jpg
---

## Uninstalling the Default Software on Win11 PCs

 Microsoft Store is the go-to place for Windows users if they want to install an app. The app library is slowly expanding, and you will find all the popular apps without any difficulty. But sometimes the Microsoft Store application behaves abnormally and requires troubleshooting.

 But what if it still doesn’t work, even after repairing and resetting? There is no uninstall option in the Settings app, so it is possible to uninstall Microsoft Store? Well, it is possible to remove and reinstall the Microsoft Store app. Here’s how.

## Why Should You Uninstall the Microsoft Store App?

 Microsoft Store houses all the useful and popular applications for Windows devices. Moreover, it guarantees safe and malware-free application downloads. But if the app fails to start or doesn’t work properly, removing it makes sense.

 But don’t worry. You can remove the app and then reinstall it if you want. Reinstallation can fix persistent issues with the current version of the Microsoft Store app. It will remove the current app installation and all its related files and corrupt data. After that, you can reinstall the Microsoft app with a single command.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
## How to Uninstall Microsoft Store App From Windows 11

 You can remove the Microsoft Store app from Windows 11 using the winget tool and run it using the command prompt. In addition, you can use the PowerShell cmdlet to remove the Microsoft Store application package from your system or use a batch file.

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Using Winget

 Winget is a handy Windows package manager tool available with the newer releases of Windows 10 and 11\. It makes it ridiculously easy to search and manage applications on your system. You can use it to remove any application, even the Microsoft Store app from your system. Here’s how:

1. Press the**Win + R** key to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**cmd** and press the**Ctrl + Shift + Enter** keys to launch the Command Prompt with administrator privileges.
2. Now, we need to locate the ID of the Microsoft Store app installed on the system. Type the following command in the command prompt window and press the enter key:**Winget list Store**
3. Winget will list all the installed programs on your system containing the string “store” in their name. Find the Microsoft Store app in the list and**copy** its**ID** .
4. After that, you need to run the uninstall command using winget. The syntax is**winget uninstall \[app ID\]** . So, the command will be:  
winget uninstall Microsoft.WindowsStore_8wekyb3d8bb
5. Press enter to execute the command and wait for it to execute successfully.  
![Uninstall Microsoft Store App using winget](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-winget.jpg)
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Type**exit** in the command prompt window and press enter to close it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
### 2\. Using PowerShell

 Before winget was officially integrated into Windows 10 and 11, there was a method to [remove the Microsoft Store app using PowerShell](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) . The method still works and all you need to do is list the package name and then use the**Remove-AppxPackage** cmdlet to uninstall the Microsoft Store app from your system. Make sure to run PowerShell with elevated permissions.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 3\. Using a Batch File

 If you want to save the hassle of typing commands every time you want to uninstall the Microsoft Store app, you can use a batch file. It will help you to remove Microsoft Store app from your system in a couple of clicks whenever the normal troubleshooting methods don’t work for you. Repeat the following steps:

1. Press**Win + D** to switch to the Desktop. Right-click on the Desktop and select the**New > Text Document** option.
2. Open the newly created text document file on the desktop. A Notepad window will pop up. Paste the following text in it:  
@echo off winget uninstall "Microsoft Store" exit
3. Now, press**Ctrl + Shift + S** to open the "Save as" window. Name the batch file as**UninstallStore.bat** and keep the**Save as** type option as**All files** .  
![Uninstall Microsoft Store App using batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-batch-file.jpg)
<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Click on the**Save** button. Close the Notepad window.
5. Press**Win + D** to switch to the desktop again. Right-click on the batch file and select the**Run as administrator** option from the context menu.
6. A command prompt window will open, run the Microsoft Store app uninstallation command, and close automatically. You don’t need to interact with the window.
7. Open the Start menu and search for Microsoft Store. You won’t find any matching app on your system.

## Easily Remove the Microsoft Store From Windows

 Windows 10 and 11 don’t offer an option to uninstall Microsoft Store. So, you are only left at the mercy of a system restore or reset. However, you can now uninstall the Microsoft Store app from your system using any of the three methods mentioned above. You can also reinstall it using the PowerShell cmdlet and continue using the app again.


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
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-legal-tips-and-tricks-for-custom-watermarking-in-instagram/"><u>[New] 2024 Approved  Legal Tips and Tricks for Custom Watermarking in Instagram</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-unleashing-the-full-potential-of-your-channel-in-studio/"><u>[Updated] 2024 Approved  Unleashing the Full Potential of Your Channel in Studio</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-create-a-sports-highlight-video-for-2024/"><u>[Updated] How to Create a Sports Highlight Video for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-pinpointing-the-leading-10-secret-story-supporters/"><u>[Updated] In 2024, Pinpointing the Leading 10 Secret Story Supporters</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-pioneering-technology-cutting-edge-screen-capture-software-listings/"><u>[Updated] In 2024, Pioneering Technology  Cutting-Edge Screen Capture Software Listings</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-narrating-your-journey-channeling-authenticity-online/"><u>[Updated] Narrating Your Journey  Channeling Authenticity Online</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-the-art-of-tall-videos-editing-vertical-media-for-impactful-insta-feeds/"><u>[Updated] The Art of Tall Videos  Editing Vertical Media for Impactful Insta Feeds</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-motorola-razr-40-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Motorola Razr 40 Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-guide-to-using-w11s-auto-hdr/"><u>A Comprehensive Guide to Using W11's Auto HDR</u></a></li>
<li><a href="https://windows11.techidaily.com/activatingdeactivating-windows-setup-service-on-pcs/"><u>Activating/Deactivating Windows Setup Service on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/biometric-betrayal-how-secure-is-your-windows-hello-lock/"><u>Biometric Betrayal: How Secure Is Your Windows Hello Lock?</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-windows-11-lock-screen-swiftly/"><u>Bypass Windows 11 Lock Screen Swiftly</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/comprehensive-analysis-and-critique-of-the-kobo-clara-colour-what-readers-should-know/"><u>Comprehensive Analysis and Critique of the Kobo Clara Colour - What Readers Should Know</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-access-denial-during-system-installation/"><u>Conquering Access Denial During System Installation</u></a></li>
<li><a href="https://article-files.techidaily.com/correcting-unsteady-flight-footage-artifacts/"><u>Correcting Unsteady Flight Footage Artifacts</u></a></li>
<li><a href="https://fox-access.techidaily.com/crafting-stories-excellence-among-8-film-categories-for-2024/"><u>Crafting Stories  Excellence Among 8 Film Categories for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/decorating-windows-11-with-a-christmas-twist/"><u>Decorating Windows 11 with a Christmas Twist</u></a></li>
<li><a href="https://windows11.techidaily.com/dont-relininas-chatbots-for-secure-authenticated-win-11-keys/"><u>Don't Relininas Chatbots for Secure, Authenticated Win 11 Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-email-management-stick-a-new-icon-in-taskbar-border/"><u>Enhance Email Management: Stick a New Icon in Taskbar Border</u></a></li>
<li><a href="https://program-issues.techidaily.com/expert-advice-resolving-the-issue-with-a-malfunctioning-mystic-light-on-your-msi-gaming-rig/"><u>Expert Advice: Resolving the Issue with a Malfunctioning Mystic Light on Your MSI Gaming Rig</u></a></li>
<li><a href="https://extra-resources.techidaily.com/experts-selection-17-programs-for-flawless-picture-editing/"><u>Expert's Selection  17 Programs for Flawless Picture Editing</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-innovation-best-windows-devices-for-24/"><u>Exploring Innovation - Best Windows Devices for '24</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-glitch-windows-steam-play-links/"><u>Fixing the Glitch: Windows Steam Play Links</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/from-stage-to-smartphone-elizabethan-expressions-still-used/"><u>From Stage to Smartphone: Elizabethan Expressions Still Used</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722974555704-get-your-best-pc-gaming-experience-on-windows-download-nvidia-drivers-now/"><u>Get Your Best PC Gaming Experience on Windows: Download Nvidia Drivers Now</u></a></li>
<li><a href="https://windows11.techidaily.com/graphics-driver-restart-procedure-in-windows-11/"><u>Graphics Driver Restart Procedure in Windows 11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-icloud-lock-from-apple-iphone-15-by-drfone-ios/"><u>How to Bypass iCloud Lock from Apple iPhone 15</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-dampen-explore-tabs-in-windows-11-os/"><u>How to Dampen Explore Tabs in Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-enable-the-home-section-in-the-settings-app-in-windows-11/"><u>How to Enable the Home Section in the Settings App in Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-iphone-se-2020-data-from-itunes-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover iPhone SE (2020) Data From iTunes? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-the-mouse-from-freezing-in-excel/"><u>How to Stop the Mouse From Freezing in Excel</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-global-presence-via-instagram-100-inspiring-self-captions/"><u>In 2024, Global Presence via Instagram  100 Inspiring Self-Captions</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/language-tools-for-smooth-trips-essential-93-spanish-expressions/"><u>Language Tools for Smooth Trips: Essential 93 Spanish Expressions</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-through-fingertip-writing-options-in-windows-system/"><u>Navigate Through Fingertip Writing Options in Windows System</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-package-control-with-winget-on-win11/"><u>Navigating Package Control with Winget on Win11</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/optimize-iphoneandroid-video-quality-in-online-platforms-for-2024/"><u>Optimize iPhone/Android Video Quality in Online Platforms for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-no-audio-capture-in-obs-on-windows-11-pcs/"><u>Overcoming No Audio Capture in OBS on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/personalized-pixel-panorama-themed-displays-for-each-window-of-win-1011/"><u>Personalized Pixel Panorama: Themed Displays for Each Window of WIN 10/11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/pursuing-perfection-on-track-compiling-top-5-simulators/"><u>Pursuing Perfection on Track  Compiling Top 5 Simulators</u></a></li>
<li><a href="https://windows11.techidaily.com/reinvigorating-a-non-functional-windows-taskbar/"><u>Reinvigorating a Non-Functional Windows Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/reset-your-screen-quickly-when-black-hits/"><u>Reset Your Screen Quickly When Black Hits</u></a></li>
<li><a href="https://windows11.techidaily.com/saving-screen-time-by-hushing-file-explorer-tabs/"><u>Saving Screen Time by Hushing File Explorer Tabs</u></a></li>
<li><a href="https://windows11.techidaily.com/set-your-desktops-mood-with-spotlight-controls/"><u>Set Your Desktop's Mood with Spotlight Controls</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-your-pcs-protection-the-firewall-guide/"><u>Tailoring Your PC's Protection: The Firewall Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-the-typhoon-of-erratic-windows-mouse-wheel/"><u>Taming the Typhoon of Erratic Windows Mouse Wheel</u></a></li>
<li><a href="https://windows11.techidaily.com/taskbar-transformation-minimizing-apps-with-ease-and-speed/"><u>Taskbar Transformation: Minimizing Apps with Ease and Speed</u></a></li>
<li><a href="https://windows11.techidaily.com/the-comprehensive-guide-to-getting-most-out-of-windows-11s-startup-screen/"><u>The Comprehensive Guide to Getting Most Out of Windows 11'S Startup Screen</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-pioneers-guide-to-gopro-and-timelapse-magic-for-2024/"><u>The Pioneer's Guide to GoPro and Timelapse Magic for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooters-guide-unlocking-photoshop-on-windows-1011/"><u>Troubleshooters' Guide: Unlocking Photoshop on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-potential-in-vintage-gear-installation-of-22h2-win11/"><u>Unleash Potential in Vintage Gear: Installation of 22H2 Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-to-overcome-directdraw-challenges-in-11-series-windows/"><u>Unveiling the Secrets to Overcome DirectDraw Challenges in 11-Series Windows</u></a></li>
<li><a href="https://facebook.techidaily.com/whatsapp-halts-enforcement-of-upcoming-privacy-update/"><u>WhatsApp Halts Enforcement of Upcoming Privacy Update</u></a></li>
<li><a href="https://windows11.techidaily.com/window-brightness-prodigies-a-list-of-premier-tools-for-multiscreeners/"><u>Window Brightness Prodigies: A List of Premier Tools for Multiscreeners</u></a></li>
<li><a href="https://windows11.techidaily.com/1719268966849-windows-users-save-your-keys-from-failure/"><u>Windows Users: Save Your Keys From Failure!</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-at-workplace-presentations-fixing-powerpoints-print-problems-in-windows/"><u>Winning at Workplace Presentations: Fixing PowerPoint's Print Problems in Windows</u></a></li>
</ul></div>
