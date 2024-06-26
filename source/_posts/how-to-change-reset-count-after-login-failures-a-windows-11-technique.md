---
title: "How to Change Reset Count After Login Failures: A Windows 11 Technique"
date: 2024-06-25T12:36:48.101Z
updated: 2024-06-26T12:36:48.101Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/decoding-windows-modern-standbys-drawbacks/"><u>Decoding Windows Modern Standby's Drawbacks</u></a></li>
<li><a href="https://windows11.techidaily.com/remote-server-files-via-nas-sharing/"><u>Remote Server Files via NAS Sharing</u></a></li>
<li><a href="https://windows11.techidaily.com/reducing-powerful-usage-in-modern-host-computers/"><u>Reducing Powerful Usage in Modern Host Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-an-uninstall-shortcut-to-the-context-menu-in-windows-1110/"><u>How to Add an Uninstall Shortcut to the Context Menu in Windows 11/10</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-user-interface-integrating-emoji-15-into-win11/"><u>Boosting User Interface: Integrating Emoji 15 Into Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-media-maker-error-x8007043c-fix-guide/"><u>Windows' Media Maker Error X.8007043C Fix Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/reversing-camera-apps-loss-of-recorded-images/"><u>Reversing Camera App's Loss of Recorded Images</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-onedrives-abode-in-the-windows-11-ecosystem/"><u>Adjusting OneDrive's Abode in the Windows 11 Ecosystem</u></a></li>
<li><a href="https://extra-resources.techidaily.com/a-step-by-step-premiere-pro-for-softening-soundtracks/"><u>A Step-by-Step Premiere Pro for Softening Soundtracks</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-infinix-note-30i-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How to Change Your Infinix Note 30i Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ow-to-make-awesome-youtube-channel-art-ultimate-guide/"><u>[New] How to Make Awesome YouTube Channel Art [Ultimate Guide ]</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-honor-magic-vs-2-drfone-by-drfone-virtual-android/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On Honor Magic Vs 2 | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-a-comprehensive-guide-to-mastering-zoom-win10/"><u>[Updated] A Comprehensive Guide to Mastering Zoom (Win10)</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-vivo-s17-pro-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Vivo S17 Pro phone? | Dr.fone</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/uilding-a-brand-through-youtube-a-strategic-guide-for-2024/"><u>[New] Building a Brand Through YouTube  A Strategic Guide for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-esteemed-creators-best-of-breed-insta-hlv-makers/"><u>[New] 2024 Approved  Esteemed Creators  Best-of-Breed Insta HLV Makers</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/can-you-unlock-iphone-11-pro-max-after-forgetting-the-passcode-drfone-by-drfone-ios/"><u>Can You Unlock iPhone 11 Pro Max After Forgetting the Passcode? | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>