---
title: Altering Failed Logon Wait Duration Settings in Windows
date: 2024-06-25T12:44:42.643Z
updated: 2024-06-26T12:44:42.643Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Altering Failed Logon Wait Duration Settings in Windows
excerpt: This Article Describes Altering Failed Logon Wait Duration Settings in Windows
keywords: Login Delay Adjustment Windows,Increase Failure Wait Time PC,Modify Unsuccessful Logon Time,Extend Logon Wait Duration,Reduce Failed Login Retry Count,Boost Unauthorized Access Window,Raise Logon Error Delay Value
thumbnail: https://thmb.techidaily.com/f47c079fa1fce90a8221b9c2c003a393b4231e2fbb42dbd4e99eb8971ba63ab6.jpg
---

## Altering Failed Logon Wait Duration Settings in Windows

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
<li><a href="https://windows11.techidaily.com/streamline-your-win11-upgrades-eradicate-error-0xc1900101/"><u>Streamline Your Win11 Upgrades, Eradicate Error 0xC1900101</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-fatal-error-code-0x800f0831/"><u>Resolving Windows' Fatal Error: Code 0X800F0831</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-recovering-battlenet-login-on-pcs/"><u>Mastering the Art of Recovering Battle.net Login on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-back-chrome-color-loss/"><u>Winning Back Chrome Color Loss</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-and-simplify-game-setup-in-xbox-app/"><u>Streamline and Simplify Game Setup in Xbox App</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-network-path-with-fixed-ea-server-error-in-os/"><u>Restoring Network Path with Fixed EA Server Error in OS</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-unlock-and-reset-restricted-program-status/"><u>How to Unlock and Reset Restricted Program Status</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-printer-busy-errors-on-pcs/"><u>Troubleshooting Printer Busy Errors on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-record-audio-on-windows-11/"><u>How to Record Audio on Windows 11</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-how-to-fake-gps-on-android-without-mock-location-for-your-nokia-g42-5g-drfone-by-drfone-virtual/"><u>In 2024, How to Fake GPS on Android without Mock Location For your Nokia G42 5G | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/77-hilarious-tiktok-quiz-time/"><u>77 Hilarious TikTok Quiz Time</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-maximizing-video-impact-on-tiktok-using-computertablet/"><u>[Updated] 2024 Approved  Maximizing Video Impact on TikTok Using Computer/Tablet</u></a></li>
<li><a href="https://extra-resources.techidaily.com/step-into-expertise-modifying-numbers-on-tiktok-profiles/"><u>Step Into Expertise  Modifying Numbers on TikTok Profiles</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-streamlining-devices-how-to-delete-downloaded-videos/"><u>In 2024, Streamlining Devices  How to Delete Downloaded Videos</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-your-messages-after-blade-a73-5g-has-been-deleted-by-fonelab-android-recover-messages/"><u>Recover your messages after Blade A73 5G has been deleted</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-unlocking-asmr-potential-professional-filming-practices-revealed/"><u>[Updated] Unlocking ASMR Potential  Professional Filming Practices Revealed</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-mindful-browsing-a-compendium-of-online-destinations-to-find-tranquility-and-relaxation-this-year/"><u>In 2024, Mindful Browsing A Compendium of Online Destinations to Find Tranquility and Relaxation This Year</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-tecno-spark-10-4g-drfone-by-drfone-virtual-android/"><u>How to use Snapchat Location Spoofer to Protect Your Privacy On Tecno Spark 10 4G? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/this-is-how-you-can-recover-deleted-pictures-from-21-by-fonelab-android-recover-pictures/"><u>This is how you can recover deleted pictures from 21.</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>