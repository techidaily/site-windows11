---
title: "Streamlining Access Permissions: Biometrics on W11, Domains"
date: 2024-07-11T21:30:12.851Z
updated: 2024-07-12T21:30:12.851Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Streamlining Access Permissions: Biometrics on W11, Domains"
excerpt: "This Article Describes Streamlining Access Permissions: Biometrics on W11, Domains"
keywords: Bio-ID on Windows 11,Win11 Biometric Login,Domain Authentication,Access Control Tech,Secure Entry Systems,Permissions Streamlining,Identity Verification W11
thumbnail: https://thmb.techidaily.com/ae96135be8b387f3dfcd58e7778aa73a8a480a5ecd8a0532a8cb17367d809b46.jpg
---

## Streamlining Access Permissions: Biometrics on W11, Domains

 Biometric authentication allows you to quickly log in to the system using fingerprint, facial, or iris recognition. However, what if you want to prevent a domain user from logging in using biometrics?

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

## How to Allow or Block a Biometrics Log-On via the Local Group Policy Editor

 The quickest way to configure your computer to allow or block a biometrics scan for domain users is through the Local Group Policy Editor. Here are the steps you need to follow:

1. Press the **Win + R** key to open the **Run tool.**
2. Type **gpedit.msc** in the search bar and click OK.
3. In the Local Group Policy Editor, head towards the following location:  
`Computer Configuration > Administrative Templates > Windows Components > Biometrics`
4. Double-click on the **Allow domain users to log on using biometrics** policy in the right pane.  
![Allow domain users to log on using biometrics policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/allow-domain-users-to-log-on-using-biometrics-policy.jpg)
5. Choose the **Enabled** option to allow biometrics log on for the domain users. And choose the **Disabled** option to block biometrics log on for the domain users.  
![Enable option in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-option.png)
6. Click **Apply** \> **OK** to save the changes.

## How to Allow or Block a Biometrics Log-On Using the Registry Editor

 Another way to configure biometrics log-on for the domain users is through the Registry Editor. Here's how:

 Editing the registry is risky, as one wrong edit can make your system unstable. Therefore, make sure to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps.

1. Open the Run tool, type **regedit** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Biometrics\Credential Provider`
3. Right-click the **Credential Provider** key in the left sidebar, hover the cursor to **New,** and choose **DWORD (32-bit) Value**.  
![DWORD (32-bit) Value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/dword-32-bit-value.jpg)
4. Name the value **Domain Accounts.**  
![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  
![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
6. Click **OK** to save the changes.

## Control Biometrics Logins on Your Computer

 Securing sensitive information has now become more important than ever. If you want to allow or block a domain user from logging on using biometrics, you can do that using the above methods.

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-stream.techidaily.com/navigating-your-path-as-a-first-time-youtuber-sidestep-these-8-common-mistakes-for-2024/"><u>Navigating Your Path as a First-Time YouTuber  Sidestep These 8 Common Mistakes for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-efficiently-managing-windows-11-features/"><u>Mastering the Art of Efficiently Managing Windows 11 Features</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-leveraging-cg-central-luts-for-cinematic-color-enhancement/"><u>In 2024, Leveraging CG Central LUTs for Cinematic Color Enhancement</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-absent-bluetooth-devices-manager/"><u>Remedy Absent Bluetooth Devices Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-to-user-management-settings-in-windows-11-and-10/"><u>Navigate to User Management Settings in Windows 11 & 10</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-cross-os-installation-of-kali-linux/"><u>Simplifying Cross-OS Installation of Kali Linux</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2023-how-to-autoplay-facebook-videos/"><u>2023 | How to Autoplay Facebook Videos?</u></a></li>
<li><a href="https://windows11.techidaily.com/three-steps-to-validate-windows-11-activation/"><u>Three Steps to Validate Windows 11 Activation</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-permission-fixes-for-installer-problems/"><u>Streamlining Permission Fixes for Installer Problems</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-blitzburst-freezeframe-video/"><u>2024 Approved  BlitzBurst FreezeFrame Video</u></a></li>
<li><a href="https://windows11.techidaily.com/unblock-your-computers-usb-hub-windows-fix-guide/"><u>Unblock Your Computer's USB Hub: Windows Fix Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-archive-file-history-in-windows-11/"><u>Unlocking the Archive: File History in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-windows-update-blockage-error-e/"><u>Mending Windows Update Blockage, Error E</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-secrets-of-successful-recording-3-approaches-for-discos-broadcast/"><u>[New] Secrets of Successful Recording  3 Approaches for Disco's Broadcast</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-direct-access-to-windows-11-dialer-feature/"><u>Unlocking Direct Access to Windows 11 Dialer Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-np-setting-detection-mishap/"><u>Resolving Windows NP Setting Detection Mishap</u></a></li>
<li><a href="https://windows11.techidaily.com/revitalizing-the-old-guard-running-windows-11-on-pre-ultimate-pcs-via-to-go-and-rufus/"><u>Revitalizing the Old Guard: Running Windows 11 on Pre-Ultimate PCs via To Go & Rufus</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-integrating-alternative-antiviruses-with-ms-defender/"><u>Tips for Integrating Alternative Antiviruses with MS Defender</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-movie-magic-on-the-go-top-ios-apps-for-trailers/"><u>Updated Movie Magic on the Go Top iOS Apps for Trailers</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-a-deeper-look-into-magix-visual-processing/"><u>In 2024, A Deeper Look Into MAGIX Visual Processing</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-restore-error-0x80042306-quickly/"><u>Overcoming Windows Restore Error 0X80042306 Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-your-potential-7-proven-techniques-to-master-windows-based-studying/"><u>Unlock Your Potential: 7 Proven Techniques to Master Windows-Based Studying</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-solutions-freeing-up-stuck-windows-11-pins/"><u>Quick Solutions: Freeing Up Stuck Windows 11 PINs</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-in-2024-glowing-complexions-without-plugins-fcpx-video-editing-tips/"><u>New In 2024, Glowing Complexions without Plugins FCPX Video Editing Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-tutorial-for-managing-archive-files-via-cmd/"><u>The Ultimate Tutorial for Managing Archive Files via CMD</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-content-disconnected-error-on-windows-using-steam/"><u>Solving Content Disconnected Error on Windows Using Steam</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-failed-app-install-in-windows-store/"><u>Troubleshooting Failed App Install in Windows Store</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-economical-pc-graphics-saving-apps/"><u>[Updated] Economical PC Graphics Saving Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-workspace-incorrante-folders-into-context-menu/"><u>Streamline Your Workspace: Incorrante Folders Into Context Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-guide-for-crafting-personalized-audio-cds-from-your-mp3-collection-windows/"><u>Stepwise Guide for Crafting Personalized Audio CDs From Your MP3 Collection (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-error-0x80d03801-on-microsoft-store-pcs/"><u>Resolving Error 0X80D03801 on Microsoft Store PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/visual-disk-management-in-context-menus-for-win-11/"><u>Visual Disk Management in Context Menus for Win 11</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-google-meet-go-live-your-youtube-broadcast-companion/"><u>[New] In 2024, Google Meet Go Live - Your YouTube Broadcast Companion</u></a></li>
<li><a href="https://facebook.techidaily.com/report-facebook-twitter-and-snapchat-are-part-of-president-bidens-vaccination-campaign/"><u>Report: Facebook, Twitter, and Snapchat Are Part of President Biden's Vaccination Campaign</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaim-soundfulness-overcoming-muted-mouses-cry/"><u>Reclaim Soundfulness: Overcoming Muted Mouse's Cry</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-nubia-red-magic-9-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Live Location is Not Updating and How to Fix on your Nubia Red Magic 9 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-game-drives-in-xbox-app/"><u>The Ultimate Guide to Game Drives in Xbox App</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-complete-scrutiny-gopro-silver-hero4-version/"><u>[New] Complete Scrutiny  GoPro Silver Hero4 Version</u></a></li>
<li><a href="https://windows11.techidaily.com/snipping-tool-or-printscreen-best-windows-capture-strategy/"><u>Snipping Tool or Printscreen? Best Windows Capture Strategy</u></a></li>
<li><a href="https://windows11.techidaily.com/making-disabled-overlays-functional-again-on-windows-pc/"><u>Making Disabled Overlays Functional Again on Windows PC</u></a></li>
<li><a href="https://techidaily.com/xiaomi-wont-play-mov-videos-how-to-fix-by-aiseesoft-video-converter-play-mov-on-android/"><u>Xiaomi won't play MOV videos, how to fix ?</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-defaults-permissions-restoration-guide/"><u>Unlocking Defaults: Permissions Restoration Guide</u></a></li>
</ul></div>
