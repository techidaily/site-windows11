---
title: How to Remove the OneDrive Icon From File Explorer in Windows 11
date: 2024-08-22T21:39:02.392Z
updated: 2024-08-23T21:39:02.392Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Remove the OneDrive Icon From File Explorer in Windows 11
excerpt: This Article Describes How to Remove the OneDrive Icon From File Explorer in Windows 11
keywords: Remove OneDrive Folder,Delete OneDrive Icon,Unlink OneDrive Files,Stop OneDrive Sync,Remove OneDrive Explorer,Disable OneDrive Search,Hide OneDrive From Windows 11
thumbnail: https://thmb.techidaily.com/76cb87841297f436650576e356aab992c1ddd1148ccda3c73b6601c2eaf3c2ce.jpg
---

## How to Remove the OneDrive Icon From File Explorer in Windows 11

 The OneDrive cloud storage client comes pre-installed on your Windows 11 computer. By default, you'll notice a OneDrive shortcut in the left pane of File Explorer, allowing quick access to your OneDrive files and folders.

 However, if you find the shortcut cluttering or ruining your File Explorer experience, you can remove it using a registry hack. Here's how to remove the OneDrive icon from File Explorer without uninstalling OneDrive.

## How to Remove OneDrive Shortcut From File Explorer via the Registry Editor

 You can remove the OneDrive icon from File Explorer using a registry hack. This way, you can get rid of the icon in File Explorer without uninstalling the OneDrive client. If you would rather remove the app entirely, follow our guide on[removing OneDrive on Windows 11](https://www.makeuseof.com/windows-11-disable-remove-onedrive/) .

 Note that modifying the Windows registry involves risk. We recommend you[create a system restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed with the steps below. A restore point will help you restore your computer in case something goes wrong.

 Once done, follow these steps to remove the OneDrive shortcut from File Explorer:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open Registry Editor. Click**Yes** if prompted by**User Account Control (UAC).**
3. Next, in the Registry Editor, navigate to the following location. Copy and paste the registry path in the editor for quicker navigation:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
4. In the right pane, right-click on**System.IsPinnedToNameSpaceTree** DWORD value and select**Modify** .  
![remove onedrive icon windows 11 registry editor modify system is pinned to name space free](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-modify-system-is-pinnedtonamespace-free.jpg)
5. In the**Value data** field, type**0** and click**OK** .  
![remove onedrive icon windows 11 registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor.jpg)
6. Next, navigate to the following location in Registry Editor:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace`
7. In the left pane, right-click on**{018D5C66-4533-4307-9B53-224DE2ED1FE6}** and select**Delete** to remove the entry.  
![remove onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
8. Once done, close the Registry Editor.
9. When you open File Explorer, the OneDrive icon will not be visible anymore.

## How to Show the OneDrive Icon Again in File Explorer

![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## Remove OneDrive Icon Without Uninstalling OneDrive

 This registry hack is a handy way to make the OneDrive icon disappear without deleting the app entirely from your PC. Alternatively, if you don’t use the service, you can completely remove OneDrive on Windows 11 or disable the service using Group Policy Editor.


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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-entry-into-the-world-of-google-meet-webinars-for-2024/"><u>[New] Entry Into the World of Google Meet Webinars for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-creating-compelling-solo-videos-on-a-budget/"><u>[New] In 2024, Creating Compelling Solo Videos on a Budget</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-unlocking-the-potential-in-depth-skype-call-recordings/"><u>[New] In 2024, Unlocking the Potential  In-Depth Skype Call Recordings</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-speed-dial-for-vimeo-video-loading/"><u>[New] Speed Dial for Vimeo Video Loading</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-top-6-secure-mc-domains/"><u>[Updated] 2024 Approved  Top 6 Secure MC Domains</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-unlocking-vimeos-potential-screen-and-webcam-capture-mastery/"><u>[Updated] 2024 Approved  Unlocking Vimeo's Potential  Screen and Webcam Capture Mastery</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-seamless-broadcasting-gamers-secrets-from-obs-for-2024/"><u>[Updated] Seamless Broadcasting  Gamers' Secrets From OBS for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-top-picks-best-free-cross-platform-video-communication-tools-for-2024/"><u>[Updated] Top Picks  Best Free Cross-Platform Video Communication Tools for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-step-by-step-recording-games-on-xbox-one/"><u>2024 Approved  Step-by-Step  Recording Games on Xbox One</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-facts-you-need-to-know-about-screen-mirroring-itel-a60-drfone-by-drfone-android/"><u>3 Facts You Need to Know about Screen Mirroring Itel A60 | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/avoid-common-mistakes-mastering-youtube-tags-wisely-for-2024/"><u>Avoid Common Mistakes - Mastering YouTube Tags Wisely for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/az-capture-tool-full-app-testing-and-options-guide/"><u>AZ Capture Tool  Full App Testing & Options Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-drawing-software-like-procreate-for-windows/"><u>Essential Drawing Software Like Procreate, For Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-for-steams-persistent-error-code-e84/"><u>Expert Tips for Steam's Persistent Error Code E84</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-ineffectual-system-defrag-functionality/"><u>Fixing Ineffectual System Defrag Functionality</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/framefraction-analysis/"><u>FrameFraction Analysis</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-frp-from-itel-by-drfone-android/"><u>How to Bypass FRP from Itel?</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-remove-google-frp-lock-on-motorola-moto-g-stylus-2023-by-drfone-android-unlock-remove-google-frp/"><u>How to remove Google FRP Lock on Motorola Moto G Stylus (2023)</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-wiped-call-history-on-huawei-nova-y71-by-fonelab-android-recover-call-logs/"><u>How to restore wiped call history on Huawei Nova Y71?</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-successfully-install-and-configure-two-screens-with-windows-7-a-comprehensive-guide/"><u>How to Successfully Install and Configure Two Screens with Windows 7: A Comprehensive Guide</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/in-2024-secrets-to-joining-friends-tiktok-live-events/"><u>In 2024, Secrets to Joining Friends' TikTok Live Events</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/list-of-pokemon-go-joysticks-on-oppo-k11-5g-drfone-by-drfone-virtual-android/"><u>List of Pokémon Go Joysticks On Oppo K11 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/low-cost-high-risks-9-concerns-with-sub-standard-windows-keys/"><u>Low Cost, High Risks: 9 Concerns with Sub-Standard Windows Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-logging-into-windows-11-with-password-instead-of-pin/"><u>Master the Art of Logging Into Windows 11 with Password Instead of PIN</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-your-files-adding-movecopy-to-windows-context-menu/"><u>Mastering Your Files: Adding 'Move'/'Copy' To Windows Context Menu</u></a></li>
<li><a href="https://win-howtos.techidaily.com/maximizing-gameplay-boosting-your-pcs-power-in-windows-11/"><u>Maximizing Gameplay: Boosting Your PC's Power in Windows 11</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/maximizing-impact-strategies-for-going-viral-on-instagram-for-2024/"><u>Maximizing Impact  Strategies for Going Viral on Instagram for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/meme-crafters-den-for-2024/"><u>Meme Crafter's Den for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-in-2024-essential-web-destinations-for-free-background-scores-bgm/"><u>New In 2024, Essential Web Destinations for Free Background Scores (BGM)</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-csgo-not-starting-in-windows-11/"><u>Overcoming CS:GO Not Starting in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-device-access-barriers-in-audacity-windows/"><u>Overcoming Device Access Barriers in Audacity (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-low-usb-support-error-in-windows/"><u>Overcoming Low USB Support Error in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/pioneering-windows-interface-next-chapter-after-11/"><u>Pioneering Windows Interface: Next Chapter After 11</u></a></li>
<li><a href="https://windows11.techidaily.com/propel-your-teams-potential-a-complete-guide-to-microsoft-teams-error-resolution-in-win11/"><u>Propel Your Teams' Potential: A Complete Guide to Microsoft Teams Error Resolution in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaiming-off-screen-windows-in-win11-6-step-guide/"><u>Reclaiming Off-Screen Windows in Win11: 6 Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstate-your-image-tiles-on-windows-11-quick-guide/"><u>Reinstate Your Image Tiles on Windows 11 – Quick Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-taskbar-freeze-on-windows-systems/"><u>Resolving Taskbar Freeze on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/revitalizing-network-safety-5-firewall-tips/"><u>Revitalizing Network Safety: 5 Firewall Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/safe-sailing-in-the-sea-of-windows-11-upgrades-top-8/"><u>Safe Sailing in the Sea of Windows 11 Upgrades (Top 8)</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-winrar-data-transfers-addressing-checksum-mistakes/"><u>Securing WinRAR Data Transfers: Addressing Checksum Mistakes</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-acquisition-download-tips-from-microsofts-app-marketplace/"><u>Speedy Acquisition: Download Tips From Microsoft's App Marketplace</u></a></li>
<li><a href="https://windows11.techidaily.com/stay-unplugged-avoiding-abrupt-updates-on-windows-11/"><u>Stay Unplugged: Avoiding Abrupt Updates on Windows 11</u></a></li>
<li><a href="https://fox-that.techidaily.com/step-by-step-guide-overcoming-icloud-synchronization-challenges/"><u>Step-by-Step Guide: Overcoming iCloud Synchronization Challenges</u></a></li>
<li><a href="https://windows11.techidaily.com/strategic-use-of-powertoys-locksmith-for-files/"><u>Strategic Use of PowerToys Locksmith for Files</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-mending-the-the-service-did-not-respond-windows-issue/"><u>Strategies for Mending the 'The Service Did Not Respond' Windows Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/take-charge-of-your-workspace-filter-and-theme-mastery-in-the-windows-11-task-manager/"><u>Take Charge of Your Workspace: Filter and Theme Mastery in the Windows 11 Task Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essentials-of-using-microsoft-family-safety/"><u>The Essentials of Using Microsoft Family Safety</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-future-in-flight-hubsan-h501s-hovering-highlights-for-2024/"><u>The Future in Flight  Hubsan H501S Hovering Highlights for 2024</u></a></li>
<li><a href="https://win-amazing.techidaily.com/troubleshoot-and-repair-xbox-input-device-driver-conflicts-in-win1187-issue-resolved/"><u>Troubleshoot and Repair Xbox Input Device Driver Conflicts in Win11/8/7 (Issue Resolved)</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-enhanced-windows-11-taskbar/"><u>Unlocking Enhanced Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/unpack-and-deploy-quick-apk-installation-guide-in-windows-11/"><u>Unpack and Deploy: Quick APK Installation Guide in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unshackling-power-the-fourfold-path-to-user-deactivation-in-windows-11/"><u>Unshackling Power: The Fourfold Path to User Deactivation in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/usb-ports-not-working-how-to-diagnose-and-fix-the-issue-in-windows/"><u>USB Ports Not Working? How to Diagnose and Fix the Issue in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-vintage-conversion-the-98-experience/"><u>Windows 11 Vintage Conversion: The ’98 Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-based-guide-recognizing-your-cpus-generational-status-8-ways/"><u>Windows-Based Guide: Recognizing Your CPU’s Generational Status (8 Ways)</u></a></li>
</ul></div>
