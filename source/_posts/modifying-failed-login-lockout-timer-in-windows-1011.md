---
title: Modifying Failed Login Lockout Timer in Windows 10/11
date: 2024-06-25T12:06:44.066Z
updated: 2024-06-26T12:06:44.066Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Modifying Failed Login Lockout Timer in Windows 10/11
excerpt: This Article Describes Modifying Failed Login Lockout Timer in Windows 10/11
keywords: Windows Login Lockout Fix,Change Lockout Timer Win10,Reset Failed Logins Time Win10,Adjusting Lockout Count Win10,Edit Lockout Settings in Win11,Shorten Lockout Timer Win11,Modify Login Cooldown Windows 11
thumbnail: https://thmb.techidaily.com/9bd169ce317850079833c4c232eaa6d389f824b0ea7ef26122a9f26ae8562eda.jpg
---

## Modifying Failed Login Lockout Timer in Windows 10/11

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
<li><a href="https://windows11.techidaily.com/reviving-system-8-routes-for-windows-restart/"><u>Reviving System: 8 Routes for Windows Restart</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-dynamic-ui-embracing-the-new-widget-era/"><u>Windows 11'S Dynamic UI: Embracing the New Widget Era</u></a></li>
<li><a href="https://windows11.techidaily.com/securely-shifting-your-streaming-application-across-hardware/"><u>Securely Shifting Your Streaming Application Across Hardware</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-command-line-capabilities-in-latest-windows-releases/"><u>Boost Command-Line Capabilities in Latest Windows Releases</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-compelling-desktop-imagery-on-windows-11/"><u>Crafting Compelling Desktop Imagery on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/detailed-process-of-downloading-and-setting-up-windows-11-arm-iso/"><u>Detailed Process of Downloading and Setting up Windows 11 ARM ISO</u></a></li>
<li><a href="https://windows11.techidaily.com/dive-into-digital-dreams-with-paint-cocreator-and-windows-11-creating-vivid-ai-visuals/"><u>Dive Into Digital Dreams with Paint Cocreator & Windows 11, Creating Vivid AI Visuals</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-permission-fixes-for-installer-problems/"><u>Streamlining Permission Fixes for Installer Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/monitor-positioning-tactics-in-windows/"><u>Monitor Positioning Tactics in Windows</u></a></li>
<li><a href="https://extra-hints.techidaily.com/securing-a-seamless-srt-upload-experience-on-social-networks/"><u>Securing a Seamless SRT Upload Experience on Social Networks</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-the-ultimate-checklist-for-maximizing-efficiency-with-twistedwave-audio-editor/"><u>New The Ultimate Checklist for Maximizing Efficiency with TwistedWave Audio Editor</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-the-ultimate-guide-to-screen-recording-with-filmora-scrn-best-practices-and-more-for-2024/"><u>Updated The Ultimate Guide to Screen Recording with Filmora Scrn Best Practices and More for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-360-degree-retail-exploration-tech/"><u>[Updated] 360-Degree Retail Exploration Tech</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/creating-captivating-mukbang-content-step-by-step/"><u>Creating Captivating Mukbang Content Step-By-Step</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-in-2024-the-ultimate-blueprint-for-telegram-marketplace-success/"><u>[New] In 2024, The Ultimate Blueprint for Telegram Marketplace Success</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-the-updated-method-to-bypass-nokia-c02-frp-by-drfone-android/"><u>In 2024, The Updated Method to Bypass Nokia C02 FRP</u></a></li>
<li><a href="https://extra-support.techidaily.com/prime-online-collections-for-3d-typography-for-2024/"><u>Prime Online Collections for 3D Typography for 2024</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-create-endless-gif-loops-with-these-free-tools/"><u>New 2024 Approved Create Endless GIF Loops with These Free Tools</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-unlock-the-secrets-of-high-quality-tiktok-filming/"><u>[New] In 2024, Unlock the Secrets of High-Quality TikTok Filming</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>