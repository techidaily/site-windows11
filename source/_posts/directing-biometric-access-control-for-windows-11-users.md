---
title: Directing Biometric Access Control for Windows 11 Users
date: 2025-01-10T22:31:48.213Z
updated: 2025-01-16T13:59:02.043Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Directing Biometric Access Control for Windows 11 Users
excerpt: This Article Describes Directing Biometric Access Control for Windows 11 Users
keywords: Bioaccess Control in Win11,Windows 11 Biometrics Secure,Win11 User Access Security,BIoMetric Entry for WinUsers,Windows 11 Facial Recognition,Biometric Gateway Win11,Windows 11 Fingerprint Authorize
thumbnail: https://thmb.techidaily.com/b7fdec82e5e2a50f89b07a18bb64e205705f93d7819f0fe370579d848f9daaea.jpg
---

## Directing Biometric Access Control for Windows 11 Users

 Biometric authentication allows you to quickly log in to the system using fingerprint, facial, or iris recognition. However, what if you want to prevent a domain user from logging in using biometrics?

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Dn-24B6AURY?si=ErES2KWVnintY6h9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Allow or Block a Biometrics Log-On via the Local Group Policy Editor

 The quickest way to configure your computer to allow or block a biometrics scan for domain users is through the Local Group Policy Editor. Here are the steps you need to follow:

1. Press the **Win + R** key to open the **Run tool.**
2. Type **gpedit.msc** in the search bar and click OK.
3. In the Local Group Policy Editor, head towards the following location:  
`Computer Configuration > Administrative Templates > Windows Components > Biometrics`
4. Double-click on the **Allow domain users to log on using biometrics** policy in the right pane.  
![Allow domain users to log on using biometrics policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/allow-domain-users-to-log-on-using-biometrics-policy.jpg)
5. Choose the **Enabled** option to allow biometrics log on for the domain users. And choose the **Disabled** option to block biometrics log on for the domain users.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=heERQcpMi77lqToE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Enable option in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-option.png)
6. Click **Apply** \> **OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Allow or Block a Biometrics Log-On Using the Registry Editor

 Another way to configure biometrics log-on for the domain users is through the Registry Editor. Here's how:

 Editing the registry is risky, as one wrong edit can make your system unstable. Therefore, make sure to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps.

1. Open the Run tool, type **regedit** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Biometrics\Credential Provider`
3. Right-click the **Credential Provider** key in the left sidebar, hover the cursor to **New,** and choose **DWORD (32-bit) Value**.  
![DWORD (32-bit) Value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/dword-32-bit-value.jpg)
4. Name the value **Domain Accounts.**  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4YCkNXJjC3c?si=9Tn8KiqKGTZi1o7E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fm0XhU5H8R4?si=cFPk6XK3X3CQSI7Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-help.techidaily.com/new-how-to-purge-personal-youtube-history-records/"><u>[New] How to Purge Personal YouTube History Records</u></a></li>
<li><a href="https://win-solutions.techidaily.com/banish-the-shadows-how-to-fix-fortnite-display-errors-on-windows-platforms/"><u>Banish the Shadows: How to Fix Fortnite Display Errors on Windows Platforms</u></a></li>
<li><a href="https://buynow-help.techidaily.com/beginners-guide-to-resilient-kids-photography-equipment/"><u>Beginner's Guide to Resilient Kids Photography Equipment</u></a></li>
<li><a href="https://tech-revival.techidaily.com/exploring-predictive-ai-its-method-and-mechanics-unfolded/"><u>Exploring Predictive AI: Its Method and Mechanics Unfolded</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-updates-in-windows-os/"><u>Exploring Updates in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-unstartable-windows-speech-to-text-error/"><u>Fixing Unstartable Windows Speech-to-Text Error</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-top-pick-for-mp4-recorders-on-market/"><u>In 2024, Top Pick for MP4 Recorders on Market</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-non-responsive-audio-controls-in-win1011/"><u>Overcoming Non-Responsive Audio Controls in Win10/11</u></a></li>
<li><a href="https://buynow-info.techidaily.com/small-sized-big-performance-in-depth-review-of-the-razer-book-13/"><u>Small-Sized, Big Performance: In-Depth Review of the Razer Book 13</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-failed-display-sharing-on-windows-devices/"><u>Solutions for Failed Display Sharing on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-overcoming-windows-steam-login-hurdles/"><u>Tips for Overcoming Windows Steam Login Hurdles</u></a></li>
</ul></div>

