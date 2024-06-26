---
title: Mastering Domain User Biometric Control in Windows 11
date: 2024-06-25T12:17:37.905Z
updated: 2024-06-26T12:17:37.905Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Domain User Biometric Control in Windows 11
excerpt: This Article Describes Mastering Domain User Biometric Control in Windows 11
keywords: Windows 11 BioControl,User Biometrics W11,Win11 Security Checks,Digital ID Windows 11,Access Control W11,W11 User Authentication,Biometric Domains W11
thumbnail: https://thmb.techidaily.com/9eaae45a5ae000b67c414e7abf4faf363e86f993286beb6923a862b27612bc1e.jpg
---

## Mastering Domain User Biometric Control in Windows 11

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/improve-file-selection-techniques-activating-windows-11-boxes/"><u>Improve File Selection Techniques: Activating Windows 11 Boxes</u></a></li>
<li><a href="https://windows11.techidaily.com/ideal-mobile-software-for-windows-pc-owners-on-android/"><u>Ideal Mobile Software for Windows PC Owners on Android</u></a></li>
<li><a href="https://windows11.techidaily.com/faster-task-management-display-in-windows-11-os/"><u>Faster Task Management Display in Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-to-eradicate-mmc-snap-in-anomalies/"><u>Expert Tips to Eradicate MMC Snap-In Anomalies</u></a></li>
<li><a href="https://windows11.techidaily.com/trimming-down-linux-overheads-in-android-wsl-setup/"><u>Trimming Down Linux Overheads in Android WSL Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/surviving-windows-11-blue-screen-adopting-11-key-approaches/"><u>Surviving Windows 11 Blue Screen: Adopting 11 Key Approaches</u></a></li>
<li><a href="https://windows11.techidaily.com/realign-your-windows-clock-through-chrome-settings/"><u>Realign Your Windows Clock Through Chrome Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-detect-and-dislodge-suddenly-installed-rav-antivirus/"><u>How to Detect & Dislodge Suddenly Installed Rav Antivirus</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-window-11s-missing-clickables-problem/"><u>Solving Window 11'S Missing Clickables Problem</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-precision-in-photos-iphone-apps-for-accurate-cropping-for-2024/"><u>[New] Precision in Photos  IPhone Apps for Accurate Cropping for 2024</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-time-bending-techniques-in-final-cut-pro-x/"><u>Updated 2024 Approved Time-Bending Techniques in Final Cut Pro X</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-can-we-bypass-itel-a70-frp-by-drfone-android/"><u>How Can We Bypass Itel A70 FRP?</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/essential-guidelines-to-create-impactful-youtube-banners-for-2024/"><u>Essential Guidelines to Create Impactful YouTube Banners for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-9-superior-editing-platforms-for-every-drone-operators-level/"><u>In 2024, 9 Superior Editing Platforms for Every Drone Operator's Level</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-detect-and-stop-mspy-from-spying-on-your-apple-iphone-12-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Detect and Stop mSpy from Spying on Your Apple iPhone 12 Pro Max | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-quiet-the-room-with-a-boosted-windows-volume-free-solutions-for-all-users/"><u>In 2024, Quiet the Room with a Boosted Windows Volume - Free Solutions for All Users</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/android-video-editor-showdown-top-10-free-and-paid-picks-for-2024/"><u>Android Video Editor Showdown Top 10 Free and Paid Picks for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-behind-the-mascara-youtubes-top-makeup-artists-unveiled/"><u>[New] In 2024, Behind the Mascara  YouTube's Top Makeup Artists Unveiled</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-avs-video-editor-2023-is-it-worth-the-hype/"><u>In 2024, AVS Video Editor 2023 Is It Worth the Hype?</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>