---
title: Revising Account Lockout Count After Multiple Login Failures in Windows 11
date: 2024-07-29T04:20:51.738Z
updated: 2024-07-30T04:20:51.738Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Revising Account Lockout Count After Multiple Login Failures in Windows 11
excerpt: This Article Describes Revising Account Lockout Count After Multiple Login Failures in Windows 11
keywords: Windows 11 Login Issues,Account Lockout Remedies,Manage Failed Logins,Reduce Lockout Count,Win11 Security Settings,Prevent User Lockouts,Optimize Login Attempts
thumbnail: https://thmb.techidaily.com/cbb1e3102bf892cff8d3ec0a8653b920867c497d12f1be8e2ab6e11d350e85ee.jpg
---

## Revising Account Lockout Count After Multiple Login Failures in Windows 11

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  
<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.
4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://tiktok-video-files.techidaily.com/new-reigning-typefaces-for-triumph-best-tiktok-font-generator-list-of-23/"><u>[New] Reigning Typefaces for Triumph  Best TikTok Font Generator List of '23</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-unveiling-the-powerhouse-techniques-in-facebooks-360-streaming/"><u>[Updated] In 2024, Unveiling the Powerhouse Techniques in Facebook's 360 Streaming</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-reel-your-audience-in-creating-dynamic-reaction-content-on-youtube-2-pov-technique-for-2024/"><u>[Updated] Reel Your Audience In  Creating Dynamic Reaction Content on YouTube (2 POV Technique) for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-unveiling-the-eight-best-free-video-editing-software-for-social-media/"><u>[Updated] Unveiling the Eight Best FREE Video Editing Software for Social Media</u></a></li>
<li><a href="https://windows11.techidaily.com/11-ways-to-fix-the-windows-search-bar-not-showing-or-working-on-windows-11/"><u>11 Ways to Fix the Windows Search Bar Not Showing or Working on Windows 11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-five-cozy-seasons-ideal-backgrounds-to-warm-up-videos/"><u>2024 Approved  Five Cozy Seasons  Ideal Backgrounds to Warm Up Videos</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-integrating-slug-lines-into-your-writing-process/"><u>2024 Approved  Integrating Slug Lines Into Your Writing Process</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-rise-of-autofocus-aided-hdr-photography/"><u>2024 Approved  The Rise of Autofocus Aided HDR Photography</u></a></li>
<li><a href="https://windows11.techidaily.com/5-ways-to-check-your-device-uptime-on-windows-11/"><u>5 Ways to Check Your Device Uptime on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/7-must-know-factors-for-buying-your-ideal-windows-computer/"><u>7 Must-Know Factors for Buying Your Ideal WIndows Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-guide-to-tweaking-firewall-security/"><u>A Comprehensive Guide to Tweaking Firewall Security</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerated-tactics-for-gaming-hardware-recognition/"><u>Accelerated Tactics for Gaming Hardware Recognition</u></a></li>
<li><a href="https://windows11.techidaily.com/account-annihilation-simple-ways-to-render-user-non-existent-on-win11/"><u>Account Annihilation: Simple Ways to Render User Non-Existent on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/achieving-a-crystal-clarity-on-your-windows-taskbar/"><u>Achieving a Crystal Clarity on Your Windows Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-proxy-in-windows-11-for-enhanced-privacy/"><u>Adjusting Proxy in Windows 11 for Enhanced Privacy</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-windows-11-identity-new-username-guide/"><u>Altering Windows 11 Identity: New UserName Guide</u></a></li>
<li><a href="https://extra-hints.techidaily.com/an-all-inclusive-subtitle-handbook-from-basics-to-advanced-tips-for-2024/"><u>An All-Inclusive Subtitle Handbook  From Basics to Advanced Tips for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/are-the-icons-on-your-windows-desktop-overlapping-here-are-some-solutions/"><u>Are the Icons on Your Windows Desktop Overlapping? Here Are Some Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-disruption-fix-windows-gaming-woe-errors/"><u>Avoid Disruption, Fix Windows' Gaming WoE Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-game-breaking-interruptions-fixed-steams-error-code-e84/"><u>Avoid Game-Breaking Interruptions: Fixed Steam’s Error Code E84</u></a></li>
<li><a href="https://windows11.techidaily.com/avoidance-of-expiring-notification-in-windows-11-devices/"><u>Avoidance of ‘Expiring’ Notification in Windows 11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-sound-service-reboot-hurdles-at-system-ignition/"><u>Avoiding Sound Service Reboot Hurdles at System Ignition</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-boot-speed-with-simple-steps-in-windows-11-setup/"><u>Boosting Boot Speed with Simple Steps in Windows 11 Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/breach-limitation-threshold-unleash-higher-ethernet-speeds-on-windows/"><u>Breach Limitation Threshold: Unleash Higher Ethernet Speeds on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-roblox-error-262s-solutions/"><u>Breaking Down Roblox Error 262'S Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-the-cycle-of-unresponsive-photoshop-on-windows/"><u>Breaking the Cycle of Unresponsive Photoshop on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/building-a-linux-ecosystem-within-hyper-v-windows-environment/"><u>Building a Linux Ecosystem Within Hyper-V Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-failures-fixing-vagrant-boot-problems-win11/"><u>Bypassing Failures: Fixing Vagrant Boot Problems Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/changing-onedrive-storage-address-in-windows-10/"><u>Changing OneDrive Storage Address in Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/complete-approach-to-deleting-the-wsl-subsystem/"><u>Complete Approach to Deleting the WSL Subsystem</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-words-best-writing-software-for-windows-users/"><u>Conquer Words: Best Writing Software for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-windows-misaligned-thx-audio-feedback/"><u>Correcting Windows' Misaligned THX Audio Feedback</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-for-clarity-windows-terminal-as-main-app/"><u>Customize for Clarity: Windows Terminal As Main App</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-and-disabling-read-only-properties-in-win11/"><u>Deciphering and Disabling Read-Only Properties in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-why-many-dismiss-windows-11-now/"><u>Decoding Why Many Dismiss Windows 11 Now</u></a></li>
<li><a href="https://windows11.techidaily.com/decreasing-visual-noise-windows-11-tab-control/"><u>Decreasing Visual Noise: Windows 11 Tab Control</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-individual-user-settings-on-group-policy-level/"><u>Delving Into Individual User Settings on Group Policy Level</u></a></li>
<li><a href="https://windows11.techidaily.com/ditching-unnecessary-wallpaper-icon-in-win11/"><u>Ditching Unnecessary Wallpaper Icon in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/1719361633854-enhance-your-pcs-screen-glow-with-these-fixes/"><u>Enhance Your PC's Screen Glow with These Fixes</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-erase-an-apple-iphone-13-pro-without-apple-id-by-drfone-ios/"><u>How to Erase an Apple iPhone 13 Pro without Apple ID?</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-vivo-g2-phone-without-password-by-drfone-android/"><u>How To Unlock Vivo G2 Phone Without Password?</u></a></li>
<li><a href="https://extra-hints.techidaily.com/leading-edge-best-9-filter-tips-for-live-broadcasts/"><u>Leading Edge  Best 9 Filter Tips for Live Broadcasts</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/step-by-step-backdrop-blurring-techniques-on-youtube-videos-for-2024/"><u>Step-by-Step Backdrop Blurring Techniques on YouTube Videos for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-vivo-x100-pro-drfone-by-drfone-virtual-android/"><u>Thinking About Changing Your Netflix Region Without a VPN On Vivo X100 Pro? | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/where-is-the-best-place-to-catch-dratini-on-realme-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>Where Is the Best Place to Catch Dratini On Realme 12 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/yuneecs-breakthrough-in-high-res-aerial-vision-for-2024/"><u>Yuneec's Breakthrough in High-Res Aerial Vision for 2024</u></a></li>
</ul></div>
