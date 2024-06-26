---
title: Setting New Reset Limit on Account Lockouts in Windows 10/11
date: 2024-06-25T12:44:24.619Z
updated: 2024-06-26T12:44:24.619Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Setting New Reset Limit on Account Lockouts in Windows 10/11
excerpt: This Article Describes Setting New Reset Limit on Account Lockouts in Windows 10/11
keywords: WinLockResetLimit,ResetWindowsLock,PCAccountLockNew,UpdateWindowsLocks,ChangeLockTimeWin,SetLockTimeoutWin,AdjustPCLockPeriod
thumbnail: https://thmb.techidaily.com/971a75711e8320cab50ce3d6d3f20ecd50a3ca9874f23293eacb87d6417f00bb.jpg
---

## Setting New Reset Limit on Account Lockouts in Windows 10/11

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  
![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.
4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/finding-out-your-internets-public-ip-with-win-cli/"><u>Finding Out Your Internet's Public IP with Win CLI</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-the-root-of-windows-update-problems-0xc1900101/"><u>Eliminating the Root of Windows Update Problems (0xC1900101)</u></a></li>
<li><a href="https://windows11.techidaily.com/skyrocket-your-text-entry-speed-via-typingaid/"><u>Skyrocket Your Text Entry Speed via TypingAid</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-win11-upgrades-eradicate-error-0xc1900101/"><u>Streamline Your Win11 Upgrades, Eradicate Error 0xC1900101</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-error-code-xc0f1103f-with-nvidias-geforce-now/"><u>Eradicating Error Code Xc0f1103f with NVIDIA's GeForce Now</u></a></li>
<li><a href="https://windows11.techidaily.com/top-techniques-to-quell-input-delay-on-windows-11/"><u>Top Techniques to Quell Input Delay on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-decision-making-with-microsofts-ai-hub/"><u>Efficient Decision-Making with Microsoft's AI Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/rise-above-ethernet-ceiling-overcome-the-windows-100mbps-limit/"><u>Rise Above Ethernet Ceiling: Overcome the Windows 100Mbps Limit</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-pathway-merging-emulated-game-titles-with-playnite-software/"><u>Guiding Pathway: Merging Emulated Game Titles with Playnite Software</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-premier-list-best-android-cloud-saving-options/"><u>2024 Approved  The Premier List  Best Android Cloud Saving Options</u></a></li>
<li><a href="https://location-social.techidaily.com/proven-ways-in-how-to-hide-location-on-life360-for-oppo-reno-11f-5g-drfone-by-drfone-virtual-android/"><u>Proven Ways in How To Hide Location on Life360 For Oppo Reno 11F 5G | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-cutting-edge-taggification-top-7-affordable-online-extractors-for-youtube-for-2024/"><u>[New] Cutting-Edge Taggification  Top 7 Affordable Online Extractors for YouTube for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/n-2024-crafting-gifs-like-a-pro-industry-leaders-tools/"><u>[New] In 2024, Crafting GIFs Like a Pro  Industry Leaders' Tools</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-apple-id-unlock-on-iphone-8-how-to-fix-it-by-drfone-ios/"><u>In 2024, Apple ID Unlock On iPhone 8? How to Fix it?</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-fix-oem-unlock-missing-on-poco-f5-pro-5g-by-drfone-android/"><u>In 2024, How To Fix OEM Unlock Missing on Poco F5 Pro 5G?</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-safeguarding-against-scams-as-you-seek-to-amass-one-million-youtube-watches/"><u>[New] Safeguarding Against Scams as You Seek to Amass One Million YouTube Watches</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/unique-video-monikers-brainstorming-insights/"><u>Unique Video Monikers  Brainstorming Insights</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-hits-and-misses-the-photographers-account/"><u>In 2024, Hits and Misses  The Photographer's Account</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-ultimate-guide-best-music-video-creators-for-everyone/"><u>New Ultimate Guide Best Music Video Creators for Everyone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>