---
title: Adjusting Reset Account Lockout Counter Post-Failed Sign-In Attempts
date: 2024-06-25T12:21:53.769Z
updated: 2024-06-26T12:21:53.769Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Reset Account Lockout Counter Post-Failed Sign-In Attempts
excerpt: This Article Describes Adjusting Reset Account Lockout Counter Post-Failed Sign-In Attempts
keywords: Sign-In Limits Adjustment,Account Lockout Reduce,Failed Login Policy Changes,Reset Counter Post-Sign In,Managing User Lockouts,Password Attempt Limit Update,Preventing Account Blocks
thumbnail: https://thmb.techidaily.com/90e284fb29c37a4c0c2a2e6970ee3fa6b56745fa434982e234c62e6bb83237e0.jpg
---

## Adjusting Reset Account Lockout Counter Post-Failed Sign-In Attempts

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
<li><a href="https://windows11.techidaily.com/fixing-windows-error-0x80071a90-explained-simply/"><u>Fixing Windows Error 0X80071A90 Explained Simply</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-resolving-m365-error-30015-26-on-pcs/"><u>Understanding and Resolving M365 Error 30015-26 on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-start-driver-verifier-manager/"><u>Steps to Start Driver Verifier Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-pin-gmail-to-the-taskbar-on-a-windows-pc/"><u>How to Pin Gmail to the Taskbar on a Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-solution-for-inaccessible-administrative-mode/"><u>Comprehensive Solution for Inaccessible Administrative Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehending-the-safeguarded-state-of-windows-11/"><u>Comprehending the Safeguarded State of Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-open-wordpad-in-windows/"><u>How to Open WordPad in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-deactivated-system-cooler-protocol-on-pcs/"><u>Overcoming Deactivated System Cooler Protocol on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-rearranged-characters-in-windows-os/"><u>Solutions for Rearranged Characters in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/time-is-money-restoring-windows-server-time-quickly/"><u>Time Is Money: Restoring Windows Server Time Quickly</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-quickshot-flipslow-mpeg/"><u>2024 Approved  QuickShot FlipSlow MPEG</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-metaverse-vs-multimeva-understanding-their-distinct-qualities/"><u>The Metaverse Vs. Multimeva  Understanding Their Distinct Qualities</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-apple-iphone-13-pro-screen-mirroring-you-must-know-drfone-by-drfone-ios/"><u>In 2024, Apple iPhone 13 Pro Screen Mirroring You Must Know | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/unveiling-secrets-to-pristine-bg-removal-techniques-in-figma/"><u>Unveiling Secrets to Pristine BG Removal Techniques in Figma</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/tart-your-youtube-channel-growth-with-key-editing-skills-from-sony-vegas-for-2024/"><u>Jumpstart Your YouTube Channel Growth with Key Editing Skills From Sony Vegas for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-from-tweeting-short-videos-to-interactive-shareable-customized-gifs/"><u>[Updated] From Tweeting Short Videos to Interactive, Shareable Customized GIFS</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-card-on-apple-iphone-12-pro-online-without-jailbreak-by-drfone-ios/"><u>How to Unlock SIM Card on Apple iPhone 12 Pro online without jailbreak</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-had-you-ever-thought-about-modifying-the-aspect-ratio-of-your-memorable-videos-do-you-have-any-idea-about-it-quickly-step-into-this-article-to-disco/"><u>Updated Had You Ever Thought About Modifying the Aspect Ratio of Your Memorable Videos? Do You Have Any Idea About It? Quickly Step Into This Article to Discover Insights on This Topic in Detail for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-listenleaders-vision-beyond-dacast/"><u>2024 Approved  ListenLeaders  Vision Beyond DaCast</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-snaps-in-a-flash-directly-upload-images-from-camera-roll/"><u>[New] 2024 Approved  Snaps in a Flash  Directly Upload Images From Camera Roll</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>