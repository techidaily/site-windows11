---
title: Altering Windows Login Lockout Interval After Errors
date: 2024-07-03T11:10:33.627Z
updated: 2024-07-04T11:10:33.627Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Altering Windows Login Lockout Interval After Errors
excerpt: This Article Describes Altering Windows Login Lockout Interval After Errors
keywords: Windows Login Lockout,Alter Lockout Time,Reduce Lockout Errors,Lockout Interval Change,Account Security Settings,Password Reset Options,Prevent Lockout Failures
thumbnail: https://thmb.techidaily.com/b57bdcbb41c7763c82190be25c28d361f666df5033d9cd0a341320bf7b8e56fa.jpg
---

## Altering Windows Login Lockout Interval After Errors

 Windows has a policy setting that can lock someone out from signing in if they enter the wrong local account password too many times. The user is not allowed to sign in for a set number of minutes after being locked out, but you can change this lockout duration.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

## How to Change the Duration a User Is Locked Out of Their Account via Local Security Policy

 This method will work as long as the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press **Windows key + R** to open the **Run** dialogue.
2. Type “secpol.msc” into the text field and hit **Enter**.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, click on the **Account Lockout Policy** folder under **Account Policies**.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on **Account lockout duration**.  
![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  
![Choose how long a local account is locked out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-set-local-account-lockout-duration.jpg)

## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
3. This will pull up information, among other things, about how long this account lockout duration is currently set.
4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

## Find the Balance Between Security and Convenience

 Setting account lockout duration too high will cause inconvenience, but if you set it to zero, an administrator will have to be contacted each time a user locks themselves out. Find a balance between security and convenience when it comes to changing how long a user is locked out after a set number of failed login attempts.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/tailoring-your-pcs-protection-the-firewall-guide/"><u>Tailoring Your PC's Protection: The Firewall Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-defaults-permissions-restoration-guide/"><u>Unlocking Defaults: Permissions Restoration Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-in-use-device-naming-5-fixes-for-windows-errors/"><u>Avoiding In-Use Device Naming: 5 Fixes for Windows Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/biometric-betrayal-how-secure-is-your-windows-hello-lock/"><u>Biometric Betrayal: How Secure Is Your Windows Hello Lock?</u></a></li>
<li><a href="https://windows11.techidaily.com/perfecting-user-interaction-essential-modifications-for-windows-11s-taskbar/"><u>Perfecting User Interaction: Essential Modifications for Windows 11'S Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/brighten-up-a-step-by-step-guide-to-an-eye-catching-cursor/"><u>Brighten Up: A Step-by-Step Guide to an Eye-Catching Cursor</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-windows-pre-format-drive-errors/"><u>Solving Windows' Pre-Format Drive Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/skyrocket-your-typing-swift-input-strategies-for-win-1011-users/"><u>Skyrocket Your Typing: Swift Input Strategies for WIN 10/11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/decreasing-non-essential-tasks-windows-108/"><u>Decreasing Non-Essential Tasks Windows 10/8</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-how-to-activate-intel-wireless-functionality/"><u>Essential Tips: How to Activate Intel Wireless Functionality</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-boost-your-creativity-on-instagram-with-free-filters/"><u>[New] In 2024, Boost Your Creativity on Instagram with Free Filters</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-balancing-act-proper-techniques-for-stable-photos-for-2024/"><u>[New] Balancing Act  Proper Techniques for Stable Photos for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-laptop-and-mobile-entrance-into-online-gatherings-google-meet-for-2024/"><u>[New] Laptop & Mobile  Entrance Into Online Gatherings (Google Meet) for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-librevid-x-version-10-reviewed-highlights-and-downsides/"><u>[New] In 2024, LibreVid X Version 10 Reviewed  Highlights and Downsides</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-ideal-selections-economical-4k-home-theater-systems/"><u>2024 Approved  Ideal Selections  Economical 4K Home Theater Systems</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-want-to-learn-more-about-the-aiff-file-format-read-this-article-where-we-tell-you-everything-you-need-to-know/"><u>New Want to Learn More About the AIFF File Format? Read This Article, Where We Tell You Everything You Need to Know</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-subtitle-strategies-for-multilingual-instagram-videos/"><u>[New] Subtitle Strategies for Multilingual Instagram Videos</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlocking-made-easy-the-best-10-apps-for-unlocking-your-vivo-y78-5g-device-by-drfone-android/"><u>In 2024, Unlocking Made Easy The Best 10 Apps for Unlocking Your Vivo Y78 5G Device</u></a></li>
<li><a href="https://techidaily.com/the-way-to-recover-deleted-contacts-on-motorola-without-backup-by-fonelab-android-recover-contacts/"><u>The way to recover deleted contacts on Motorola without backup.</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/whats-the-best-orientation-horizontalvertical-on-facebook-for-2024/"><u>What's The Best Orientation  Horizontal/Vertical on Facebook for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>