---
title: How to Adjust Lockout Frequency After Incorrect User Credentials for Windows 11
date: 2024-06-25T12:00:17.933Z
updated: 2024-06-26T12:00:17.933Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Adjust Lockout Frequency After Incorrect User Credentials for Windows 11
excerpt: This Article Describes How to Adjust Lockout Frequency After Incorrect User Credentials for Windows 11
keywords: Windows Lockout Fix,Correct Passwords Windows,Unlock Windows 11,Rekey Windows Password,Reset User Creds Win11,Bypass Windows Lockout,Updating Login Attempts Win11
thumbnail: https://thmb.techidaily.com/d11ab69328de06b2bbe702807d8f8d332f02dd668667f50f1987a428d6465f16.jpg
---

## How to Adjust Lockout Frequency After Incorrect User Credentials for Windows 11

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
<li><a href="https://windows11.techidaily.com/when-should-you-consider-purging-pagefilesys/"><u>When Should You Consider Purging Pagefile.sys?</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-steam-setup-obstacles-on-windows-11-devices/"><u>Overcoming Steam Setup Obstacles on Windows 11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-overcome-endless-startup-in-bios-for-windows-systems/"><u>Steps to Overcome Endless Startup in BIOS for Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/a-glimpse-at-future-ready-windows-with-update-22h2s-features/"><u>A Glimpse at Future-Ready Windows with Update #22H2's Features</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-chrome-challenges-fix-common-web-problems-on-windows-pc/"><u>Navigating Chrome Challenges: Fix Common Web Problems on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-browser-security-incorporating-trusted-websites-in-windows-11/"><u>Personalize Browser Security: Incorporating Trusted Websites in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/using-ports-without-built-in-pc-graphics-hardware/"><u>Using Ports Without Built-In PC Graphics Hardware</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-strategies-for-engagingdisengaging-focus-mode-in-terminal/"><u>Efficient Strategies for Engaging/Disengaging Focus Mode in Terminal</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/1714305405937-new-2024-approved-the-ultimate-guide-to-video-editing-on-windows-11-free-and-paid-tools/"><u>New 2024 Approved The Ultimate Guide to Video Editing on Windows 11 Free & Paid Tools</u></a></li>
<li><a href="https://unlock-android.techidaily.com/remove-the-lock-screen-fingerprint-of-your-infinix-smart-7-hd-by-drfone-android/"><u>Remove the Lock Screen Fingerprint Of Your Infinix Smart 7 HD</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/essential-steps-to-curate-youtube-music-selections/"><u>Essential Steps to Curate YouTube Music Selections</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-3-solutions-to-find-your-apple-iphone-15-current-location-of-a-mobile-number-drfone-by-drfone-virtual-ios/"><u>In 2024, 3 Solutions to Find Your Apple iPhone 15 Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713963780467-updated-in-the-realm-of-creating-graphic-presentation-people-also-ask-about-designing-professionally-sound-slideshow-word-presentations-heres-how-you-can-go/"><u>Updated In the Realm of Creating Graphic Presentation, People Also Ask About Designing Professionally Sound Slideshow Word Presentations. Heres How You Can Go About the Process for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/media-professionals-recommendations-best-5-web-video-recorders-for-2024/"><u>Media Professionals' Recommendations  Best 5 Web Video Recorders for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-easy-tutorial-for-activating-icloud-on-apple-iphone-6-safe-and-legal-by-drfone-ios/"><u>In 2024, Easy Tutorial for Activating iCloud on Apple iPhone 6 Safe and Legal</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-understanding-the-impact-activating-auto-hdr-feature-on-windows-11/"><u>[New] Understanding the Impact  Activating Auto HDR Feature on Windows 11</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/complete-testimonials-of-gecatas-recorder-for-2024/"><u>Complete Testimonials of Gecata's Recorder for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>