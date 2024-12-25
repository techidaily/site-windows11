---
title: Setting Window' Cookie Expiry Post-Login Errors
date: 2024-12-22T18:28:11.503Z
updated: 2024-12-25T17:03:51.441Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Setting Window' Cookie Expiry Post-Login Errors
excerpt: This Article Describes Setting Window' Cookie Expiry Post-Login Errors
keywords: Cookie Setup Duration,Login Error Management,Post-Login Cookie TTL,Preventing Login Failures,Session Time To Live,Manage Cookies After Log In,Avoid Login Issues
thumbnail: https://thmb.techidaily.com/23bcbbd5e45bcabcdfd0dcf9f0d56055fdfa4178e94d0dd13999edb6b6a4b8b2.jpg
---

## Setting Window' Cookie Expiry Post-Login Errors

 Windows has a policy setting that can lock someone out from signing in if they enter the wrong local account password too many times. The user is not allowed to sign in for a set number of minutes after being locked out, but you can change this lockout duration.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l4R7_qNIQvY?si=2zJOPfEcm6_3udzn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change the Duration a User Is Locked Out of Their Account via Local Security Policy

 This method will work as long as the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press **Windows key + R** to open the **Run** dialogue.
2. Type “secpol.msc” into the text field and hit **Enter**.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, click on the **Account Lockout Policy** folder under **Account Policies**.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on **Account lockout duration**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gOyLy8DeizY?si=GkAmK0hChZw6_2tW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  
![Choose how long a local account is locked out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-set-local-account-lockout-duration.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LBCobAYzzcc?si=J3eSTQ3AdyxWAjGo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
3. This will pull up information, among other things, about how long this account lockout duration is currently set.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nyp7-xVwqHA?si=XCuZbpKLFIdrGQQh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fHWdQw1gRyI?si=ve9wZnPupiooLThG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Find the Balance Between Security and Convenience

 Setting account lockout duration too high will cause inconvenience, but if you set it to zero, an administrator will have to be contacted each time a user locks themselves out. Find a balance between security and convenience when it comes to changing how long a user is locked out after a set number of failed login attempts.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-calculating-youtubes-income-potential-with-cpm-rates/"><u>[Updated] 2024 Approved Calculating YouTube's Income Potential with CPM Rates</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-expert-tips-on-mastering-the-preview-application-on-mac/"><u>[Updated] Expert Tips on Mastering the Preview Application on Mac</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-the-ultimate-guide-to-android-video-calls/"><u>[Updated] In 2024, The Ultimate Guide to Android Video Calls</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/free-dvd-playback-made-easy-top-10-windows-10-players-for-2024/"><u>Free DVD Playback Made Easy Top 10 Windows 10 Players for 2024</u></a></li>
<li><a href="https://win-solutions.techidaily.com/free-online-converter-convert-mod-to-avi-with-moveavi/"><u>Free Online Converter: Convert MOD to AVI with MoveAVI</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-reactivating-and-fixing-secure-boot-grayout-issue-in-bios/"><u>Guide to Reactivating and Fixing Secure Boot Grayout Issue in BIOS</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-do-samsung-galaxy-a34-5g-screen-sharing-drfone-by-drfone-android/"><u>How To Do Samsung Galaxy A34 5G Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-set-active-hours-and-avoid-sudden-updates-on-windows-11/"><u>How to Set Active Hours and Avoid Sudden Updates on Windows 11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-making-everyday-moments-memorable-on-youtube/"><u>In 2024, Making Everyday Moments Memorable on YouTube</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722904106277-master-the-art-of-removing-cache-and-cookies-in-leading-web-browsers-today/"><u>Master the Art of Removing Cache and Cookies in Leading Web Browsers Today!</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-setup-offline/"><u>Mastering Windows 11 Setup Offline</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-boot-time-windows-audio-recovery-procedures/"><u>Resolving Boot-Time Windows Audio Recovery Procedures</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-muted-microphone-issue-fixes-to-ensure-live-recording-obs-w11/"><u>Stop Muted Microphone Issue: Fixes to Ensure Live Recording, OBS W11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-resolving-nvidia-cp-access-denied-on-ws1110/"><u>Troubleshooting: Resolving Nvidia CP Access Denied on WS11/10</u></a></li>
<li><a href="https://windows11.techidaily.com/what-is-hardware-reserved-memory-on-windows/"><u>What Is Hardware Reserved Memory on Windows?</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-unlocked-enter-the-ease-of-access-center-fast/"><u>Windows Unlocked: Enter the Ease of Access Center Fast</u></a></li>
</ul></div>

