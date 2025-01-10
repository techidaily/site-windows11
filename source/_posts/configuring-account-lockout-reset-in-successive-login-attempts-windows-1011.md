---
title: Configuring Account Lockout Reset in Successive Login Attempts Windows 10/11
date: 2025-01-09T20:29:37.811Z
updated: 2025-01-10T20:48:50.301Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Configuring Account Lockout Reset in Successive Login Attempts Windows 10/11
excerpt: This Article Describes Configuring Account Lockout Reset in Successive Login Attempts Windows 10/11
keywords: Windows Lockout Policy,Login Retry Limit,Secure Passwords,Reset Account Lockouts,Access Control Enhancements,Password Management Windows 10/11,User Security Settings Update,Lockout Policy Window,Retry Limit Security,Strong Passwords Essential,Reset User Lockouts,Access Control Windows,Password Settings Windows,Update Security Settings
thumbnail: https://thmb.techidaily.com/c01f488742f525379e15c90538d56863d279883606cc35ff29b3863a4d78b16e.jpg
---

## Configuring Account Lockout Reset in Successive Login Attempts Windows 10/11

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uzb-0C0xUYA?si=F4MPhdVqyVgx7_8X" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  
![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0Kr7Dpw0HuM?si=05wWDXdPgmC-oBBE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E3yY7lZ-FKA?si=g8VEuExP8GH59B69" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xIP8ktrmOdg?si=zRnjbGzM6PDx2jCq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_SbYznUy_zY?si=ThBkP934r3mizi48" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://snapchat-videos.techidaily.com/updated-fast-track-adding-snapchat-to-your-mac-for-2024/"><u>[Updated] Fast Track Adding Snapchat to Your Mac for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-mastering-youtube-frames-top-5-cost-free-techniques-for-2024/"><u>[Updated] Mastering YouTube Frames Top 5 Cost-Free Techniques for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-top-5-techniques-for-capturing-live-sound-over-the-web-for-2024/"><u>[Updated] Top 5 Techniques for Capturing Live Sound Over the Web for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-delve-deep-into-powerdirector-comprehensive-review-and-tutorial/"><u>2024 Approved Delve Deep Into PowerDirector - Comprehensive Review & Tutorial</u></a></li>
<li><a href="https://fox-web3.techidaily.com/adjusting-system-dates-times-and-time-zones-via-control-panel-a-guide-by-yl-computing/"><u>Adjusting System Dates, Times & Time Zones via Control Panel: A Guide by YL Computing</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-win-compatibility-troubleshooting-guide/"><u>Expert Tips: Win Compatibility Troubleshooting Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-activatedeactivate-vm-security-with-secure-boot-on-virtualbox-70/"><u>How to Activate/Deactivate VM Security with Secure Boot on VirtualBox 7.0</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-card-on-huawei-nova-y71-online-without-jailbreak-by-drfone-android/"><u>How to Unlock SIM Card on Huawei Nova Y71 online without jailbreak</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-motorola-moto-g73-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Can I use iTools gpx file to catch the rare Pokemon On Motorola Moto G73 5G | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-life360-notify-when-you-log-out-on-apple-iphone-11-drfone-by-drfone-virtual-ios/"><u>In 2024, Does Life360 Notify When You Log Out On Apple iPhone 11? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-ax201-wi-fi-6-error-on-windows/"><u>Steps to Resolve AX201 Wi-Fi 6 Error on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-windows-app-start-counter/"><u>Stop Windows App Start Counter</u></a></li>
<li><a href="https://tech-revival.techidaily.com/winxvideo-ai-advanced-video-and-image-optimization-suite-with-conversion-recording-and-editing-capabilities/"><u>WinxVideo AI – Advanced Video & Image Optimization Suite with Conversion, Recording, and Editing Capabilities</u></a></li>
<li><a href="https://windows11.techidaily.com/workaround-for-win10-and-11s-audacity-device-opening-issue/"><u>Workaround for Win10 & 11’S Audacity Device Opening Issue</u></a></li>
</ul></div>

