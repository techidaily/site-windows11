---
title: "Streamlining Access Permissions: Biometrics on W11, Domains"
date: 2024-06-25T12:11:32.035Z
updated: 2024-06-26T12:11:32.035Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/quick-sniping-techniques-alternatives-to-windows-snipping-capability/"><u>Quick Sniping Techniques: Alternatives to Windows' Snipping Capability</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-geforce-experience-setting-retrieval-failure-on-windows-1111/"><u>Resolving 'GeForce Experience' Setting Retrieval Failure on Windows 11/11</u></a></li>
<li><a href="https://windows11.techidaily.com/what-is-bluescreenview-and-how-do-you-use-it/"><u>What Is BlueScreenView and How Do You Use It?</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-steam-library-folder-editability-in-win-11/"><u>Enabling Steam Library Folder Editability in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-power-saving-paradox-modern-standbys-dilemni/"><u>Windows' Power-Saving Paradox: Modern Standby's Dilemni</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-memory-write-error-windows-fixes/"><u>Disabling 'Memory Write' Error: Windows Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/enrich-your-windows-setup-with-personal-menus/"><u>Enrich Your Windows Setup with Personal Menus</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-full-potential-of-taskbar-in-win11/"><u>Unlock the Full Potential of Taskbar in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/rapid-and-secure-firmware-update-guide-for-surface-systems/"><u>Rapid & Secure Firmware Update Guide for Surface Systems</u></a></li>
<li><a href="https://extra-hints.techidaily.com/understanding-your-macs-capabilities-in-big-sur/"><u>Understanding Your Mac's Capabilities in Big Sur</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-stealth-mode-a-guide-to-living-large-unlabeled/"><u>In 2024, Stealth Mode  A Guide to Living Large, Unlabeled</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-in-2024-crack-free-filmora-discover-the-safe-and-legal-way-to-get-it/"><u>New In 2024, Crack-Free Filmora Discover the Safe and Legal Way to Get It</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-restore-a-bricked-vivo-y27-5g-back-to-operation-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Restore a Bricked Vivo Y27 5G Back to Operation | Dr.fone</u></a></li>
<li><a href="https://ai-voice.techidaily.com/new-top-10-free-ai-voice-generators-to-use-in-daily-life/"><u>New Top 10 Free AI Voice Generators to Use in Daily Life</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-amplifying-presence-top-30plus-bio-strategies-for-filmora-creators-to-grow-followers-for-2024/"><u>[New] Amplifying Presence  Top 30+ Bio Strategies for Filmora Creators to Grow Followers for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-maximize-impact-tweeting-with-videos/"><u>[Updated] In 2024, Maximize Impact  Tweeting with Videos</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/elevating-presentations-with-adobe-captivate-skills-for-2024/"><u>Elevating Presentations with Adobe Captivate Skills for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-fix-apple-iphone-6-plus-unavailable-issue-with-ease-drfone-by-drfone-ios/"><u>In 2024, How To Fix Apple iPhone 6 Plus Unavailable Issue With Ease | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/the-secret-to-viral-videos-get-the-best-thumbnail-size-guide-for-2024/"><u>The Secret to Viral Videos? Get the Best Thumbnail Size Guide for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>