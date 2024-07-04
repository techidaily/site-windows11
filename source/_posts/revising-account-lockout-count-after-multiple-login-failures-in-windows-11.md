---
title: Revising Account Lockout Count After Multiple Login Failures in Windows 11
date: 2024-06-25T11:56:55.812Z
updated: 2024-06-26T11:56:55.812Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Revising Account Lockout Count After Multiple Login Failures in Windows 11
excerpt: This Article Describes Revising Account Lockout Count After Multiple Login Failures in Windows 11
keywords: Windows 11 Login Issues,Account Lockout Remedies,Manage Failed Logins,Reduce Lockout Count,Win11 Security Settings,Prevent User Lockouts,Optimize Login Attempts
thumbnail: https://thmb.techidaily.com/cbb1e3102bf892cff8d3ec0a8653b920867c497d12f1be8e2ab6e11d350e85ee.jpg
---

## Revising Account Lockout Count After Multiple Login Failures in Windows 11

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
<li><a href="https://windows11.techidaily.com/quick-launch-hacks-opening-windows-11-apps-faster/"><u>Quick Launch Hacks: Opening Windows 11 Apps Faster</u></a></li>
<li><a href="https://windows11.techidaily.com/analyzing-how-windows-11-fuels-microsofts-earnings/"><u>Analyzing How Windows 11 Fuels Microsoft's Earnings</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-command-prompt-tactics-for-registry-optimization/"><u>Expert Command Prompt Tactics for Registry Optimization</u></a></li>
<li><a href="https://windows11.techidaily.com/brighten-control-navigating-windows-11-display-settings/"><u>Brighten Control: Navigating Windows 11 Display Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-mend-the-pairing-glitch-fixing-connection-issues-in-win-11/"><u>How to Mend the Pairing Glitch: Fixing Connection Issues in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/a-practical-guide-to-running-ping-efficiently-on-pcs/"><u>A Practical Guide to Running Ping Efficiently on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-solutions-to-the-display-startup-failure-issue/"><u>Effective Solutions to the “Display Startup Failure” Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-through-windows-sound-settings-9-easy-methods-quickly/"><u>Navigate Through Windows' Sound Settings: 9 Easy Methods, Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-tackle-icons-not-aligned/"><u>Win 11: Tackle Icons Not Aligned</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-customizing-your-windows-11-notepad-appearance/"><u>Step-by-Step: Customizing Your Windows 11 Notepad Appearance</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-pioneering-emulation-tools-best-android-apps-for-mac-pc-users/"><u>[New] Pioneering Emulation Tools  Best Android Apps for Mac, PC Users</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-stream-side-stacking-pewdiepies-payday-portion/"><u>[Updated] Stream-Side Stacking  PewDiePie’s Payday Portion</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-branding-excellence-youtube-naming-masterclass/"><u>2024 Approved  Branding Excellence  YouTube Naming Masterclass</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-real-time-engagement-proven-strategies-for-facebook-video-screen-sharing/"><u>2024 Approved  Real-Time Engagement  Proven Strategies for Facebook Video Screen Sharing</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-step-into-premium-filmmaking-discover-these-8-online-backdrop-banks/"><u>In 2024, Step Into Premium Filmmaking  Discover These 8 Online Backdrop Banks</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-in-2024-best-8-speech-to-text-apps-for-android-and-iphone/"><u>Updated In 2024, Best 8 Speech to Text Apps for Android and iPhone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-video-selfie-verification-on-instagram-helpful-or-hype/"><u>[New] In 2024, Video Selfie Verification on Instagram - Helpful or Hype?</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-samsung-galaxy-a25-5g-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Samsung Galaxy A25 5G without Losing Data | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-vivo-y100i-power-5g-phone-without-pin-by-drfone-android/"><u>In 2024, How to Unlock Vivo Y100i Power 5G Phone without PIN</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-the-gamers-blueprint-securing-memorable-moments-with-4-methods-for-2024/"><u>[Updated] The Gamers' Blueprint  Securing Memorable Moments with 4 Methods for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>