---
title: "How to Change Reset Count After Login Failures: A Windows 11 Technique"
date: 2025-02-24T19:53:08.583Z
updated: 2025-03-02T11:43:45.521Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes How to Change Reset Count After Login Failures: A Windows 11 Technique"
excerpt: "This Article Describes How to Change Reset Count After Login Failures: A Windows 11 Technique"
keywords: Win11 Reset Counters,Login Fail Counter Fix,Change Login Errors,W11 Password Retry,Reset Failed Logins,Windows Login Tweak,Increase Login Attempts
thumbnail: https://thmb.techidaily.com/482b831c6b34c789ab00f688124bfef762b7175eaa7e3a93f998add3b31aa3c1.jpg
---

## How to Change Reset Count After Login Failures: A Windows 11 Technique

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

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-clips.techidaily.com/updated-polishing-profile-vids-tips-and-tricks/"><u>[Updated] Polishing Profile Vids Tips and Tricks</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/approved-earning-strategies-with-youtubes-adsense-payout-per-k-viewers/"><u>2024 Approved Earning Strategies with Youtube's AdSense Payout per K Viewers</u></a></li>
<li><a href="https://win-marvelous.techidaily.com/1728480382477-youtube/"><u>消えてしまったYouTube動画を完全に取り戻す簡単な方法ガイド</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-issue-32-bit-application-faces-critical-error-print-driver-host-not-responding/"><u>Fixing the Issue: 32-Bit Application Faces Critical Error - Print Driver Host Not Responding</u></a></li>
<li><a href="https://fox-sure.techidaily.com/how-do-you-know-when-to-refresh-your-wi-fi-driver-insights-from-yl-software-experts/"><u>How Do You Know When to Refresh Your Wi-Fi Driver? Insights From YL Software Experts</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-the-fundamentals-of-crafting-youtube-videos-from-scratch/"><u>In 2024, The Fundamentals of Crafting YouTube Videos From Scratch</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-overcoming-windows-activation-fault-error-0x803f700f/"><u>Mastery of Overcoming Windows Activation Fault: Error 0X803F700f</u></a></li>
<li><a href="https://windows11.techidaily.com/pro-tips-selecting-superior-windows-11-drawers/"><u>Pro Tips: Selecting Superior Windows 11 Drawers</u></a></li>
<li><a href="https://windows11.techidaily.com/starting-diagnostics-five-quick-steps-in-windows/"><u>Starting Diagnostics: Five Quick Steps in Windows</u></a></li>
<li><a href="https://fox-access.techidaily.com/the-definitive-list-of-5-drone-racing-headsets/"><u>The Definitive List of 5 Drone Racing Headsets</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/unlock-instagram-potential-with-advanced-cropping-methods-for-2024/"><u>Unlock Instagram Potential with Advanced Cropping Methods for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-restrictions-of-secure-boot-and-tpm-using-rufus/"><u>Unlocking the Restrictions of Secure Boot & TPM Using Rufus</u></a></li>
<li><a href="https://windows11.techidaily.com/why-do-computers-have-a-windows-batch-file/"><u>Why Do Computers Have a Windows Batch File?</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-advancements-what-the-new-update-brings-in/"><u>Windows 11 Advancements: What the New Update Brings In</u></a></li>
</ul></div>

