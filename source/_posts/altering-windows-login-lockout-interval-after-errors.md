---
title: Altering Windows Login Lockout Interval After Errors
date: 2025-01-24T20:03:05.798Z
updated: 2025-01-30T02:37:13.068Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XA_wP7rS9ww?si=LarMG3sEHAhSoL6q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
3. This will pull up information, among other things, about how long this account lockout duration is currently set.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/htnQWyEOCgc?si=fy86hi8_hTtbWAnw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/epKTCSREjhI?si=Ez_hObK1FZrmEE7f" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=3YDfzJAZMDp1gFRz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-dive-into-9-premium-uncut-full-length-winter-wonderland-flicks/"><u>[New] In 2024, Dive Into 9 Premium, Uncut Full-Length Winter Wonderland Flicks</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-youtube-shorts-guide-what-is-it-and-how-to-make-shorts-video/"><u>[Updated] In 2024, YouTube Shorts Guide What Is It and How To Make Shorts Video?</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-reimagine-your-content-with-advanced-number-edits-in-tiktok/"><u>[Updated] Reimagine Your Content with Advanced Number Edits in TikTok</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-unleash-the-power-of-live-captures-an-introduction-to-vimeo-record/"><u>2024 Approved Unleash the Power of Live Captures An Introduction to Vimeo Record</u></a></li>
<li><a href="https://blog-min.techidaily.com/discover-the-stealthy-way-a-guide-to-clandestine-screen-capture-on-pc-and-mac/"><u>Discover the Stealthy Way: A Guide to Clandestine Screen Capture on PC and Mac</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/from-full-size-photos-to-miniature-expert-thumbnail-crafting-for-2024/"><u>From Full-Size Photos to Miniature Expert Thumbnail Crafting for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/full-guide-on-mirroring-your-tecno-spark-20c-to-your-pcmac-drfone-by-drfone-android/"><u>Full Guide on Mirroring Your Tecno Spark 20C to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/solve-your-inked-woes-a-guide-to-fixing-windows-pen-devices/"><u>Solve Your Inked Woes: A Guide to Fixing Windows Pen Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-w10w11-interruptexception-bsod-a-comprehensible-guide/"><u>Solving W10/W11 INTERRUPT_EXCEPTION BSOD: A Comprehensible Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-pc-functionality-addressing-11-windows-problems/"><u>Streamlining PC Functionality - Addressing 11 Windows Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/the-os-metamorphosis-insights-into-w10-and-w11-developments/"><u>The OS Metamorphosis: Insights Into W10 and W11 Developments</u></a></li>
<li><a href="https://techidaily.com/the-way-to-convert-mts-for-motorola-edge-40-pro-by-aiseesoft-video-converter-play-mts-on-android/"><u>The way to convert MTS for Motorola Edge 40 Pro</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/transformative-power-of-chatgpt-for-modern-professionals/"><u>Transformative Power of ChatGPT for Modern Professionals</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-system-restore-issue-0x80042306-in-win10/"><u>Unraveling System Restore Issue 0X80042306 in Win10</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-ram-cache-basics-and-cleansing-methods/"><u>Windows RAM Cache Basics and Cleansing Methods</u></a></li>
</ul></div>

