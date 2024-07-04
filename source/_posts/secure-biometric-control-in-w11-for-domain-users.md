---
title: Secure Biometric Control in W11 for Domain Users
date: 2024-06-25T11:56:57.633Z
updated: 2024-06-26T11:56:57.633Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Secure Biometric Control in W11 for Domain Users
excerpt: This Article Describes Secure Biometric Control in W11 for Domain Users
keywords: Bio-Secured Access,W11 Security Systems,Domain User Biometrics,Secure Authentication,Advanced Biometric Safeguards,User Identity Protection,Wifi Secure Entrance Control
thumbnail: https://thmb.techidaily.com/696965aa1a0f4c21fdfd456761bb63f354f50ffc3b27173b44a827d0fae8995e.jpg
---

## Secure Biometric Control in W11 for Domain Users

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
<li><a href="https://windows11.techidaily.com/overcoming-unavailable-nvidia-cp-on-windows-11/"><u>Overcoming Unavailable Nvidia CP on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/activation-indicators-for-windows-11-systems/"><u>Activation Indicators for Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/creating-a-dual-disk-on-windows-independently/"><u>Creating a Dual Disk on Windows, Independently</u></a></li>
<li><a href="https://windows11.techidaily.com/9-ways-to-fix-windows-hello-fingerprint-recognition-not-working/"><u>9 Ways to Fix Windows Hello Fingerprint Recognition Not Working</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-geforce-experiences-unable-to-retrieve-settings-error-in-windows-11-and-11/"><u>How to Fix GeForce Experience’s “Unable to Retrieve Settings” Error in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/file-finder-simplicity-windowed-explorer-reduction-technique/"><u>File Finder Simplicity: Windowed Explorer Reduction Technique</u></a></li>
<li><a href="https://windows11.techidaily.com/resurrecting-lost-wi-fi-link-windows-edition/"><u>Resurrecting Lost Wi-Fi Link: Windows Edition</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/expert-video-exposure-correction-tools/"><u>Expert Video Exposure Correction Tools</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-the-quickest-way-to-resize-a-video-for-any-screen-for-2024/"><u>Updated The Quickest Way to Resize a Video for Any Screen for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/identify-missing-drivers-with-windows-device-manager-on-windows-11-and-10-and-7-by-drivereasy-guide/"><u>Identify missing drivers with Windows Device Manager on Windows 11 & 10 & 7</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-leveraging-descriptive-power-for-3-engaging-instagram-video-stories/"><u>[New] In 2024, Leveraging Descriptive Power for 3 Engaging Instagram Video Stories</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-chorus-climaxes-ultimate-hits-to-accompany-your-promise-for-2024/"><u>[New] Chorus Climaxes  Ultimate Hits to Accompany Your Promise for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-12-leading-motion-capture-camcorders-now-with-global-positioning/"><u>In 2024, 12 Leading Motion Capture Camcorders Now With Global Positioning</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/master-the-airwaves-gratis-applications-to-revolutionize-your-vocal-artistry-for-2024/"><u>Master the Airwaves  Gratis Applications to Revolutionize Your Vocal Artistry for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-comparing-slack-and-discord-best-communication-tool-for-co-workers-for-2024/"><u>[Updated] Comparing Slack and Discord  Best Communication Tool for Co-Workers for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>