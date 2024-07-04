---
title: "Slowing Down Windows 10 Shutdown: Keep Programs Open"
date: 2024-06-25T11:58:43.255Z
updated: 2024-06-26T11:58:43.255Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Slowing Down Windows 10 Shutdown: Keep Programs Open"
excerpt: "This Article Describes Slowing Down Windows 10 Shutdown: Keep Programs Open"
keywords: Windows 10 Shutdown Guide,Delaying OS Shutdown,Programs Before Shutdown,Safe Windows Exit,Stubborn App Closure,Avoid Sudden Close,Extend Shutdown Process
thumbnail: https://thmb.techidaily.com/5c5beff306decd9e31c3216a57ffb320c5012e1719fd0426ca459ec8dc06e9a5.jpg
---

## Slowing Down Windows 10 Shutdown: Keep Programs Open

 Sometimes, when shutting down, restarting, or logging off from your Windows 10 machine, you may get an error message that interrupts or even cancels the operation. To prevent this from happening, you can make Windows wait longer when logging off.

 Making the system give it a little while longer could actually save you time. Here’s what you should do, should you be faced with this situation.

## Why Does Windows Show an Error Message While Logging Off?

 It may be that you have quite a few tasks running simultaneously, each possibly with unsaved data. If this is the case, each task or application attempts to save data before Windows logs off. This could be one reason for the error message. As a remedy, you may want to extend the time allotted for signing off to allow all tasks to finish what they are doing.

 Alternatively, it could just be a problem task. This may be true if it is a recurring issue. In this case, and if you’re sure none of the applications you are using will lose data, you could make Windows force a sign-off more quickly.

## What Should You Try First?

 The method described here basically forces Windows to wait longer while shutting down or logging off. However, if you have a misbehaving program interfering with Windows log-off, it could be something to look into. There are fixes you should try first if there is an[app preventing Windows from shutting down or logging off](https://www.makeuseof.com/this-app-preventing-windows-shutting-down-restarting-signing-out-error/) .

 If none of those options works, you can adjust how long Windows waits before logging off, which gives any running or buggy apps more time to sort themselves out.

## Make Windows Wait Longer When Logging Off

 There are two processes that you can turn to. With the first, WaitToKillAppTimeout, Windows grants apps 20 seconds to save data and close. If apps don’t respond, Windows considers them “hung.” HungAppTimeout, the second, tells Windows how many seconds to wait before considering apps to be hung and offering a force-close solution.

 Changing both these values involves[editing the registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) , so be wary, and[make a backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) copy before you tinker with it.

### 1A. How to Set WaitToKillAppTimeout for Just Your User Account

 Do this to change how long Windows waits for apps when logging off just from your user account.

1. Open the Registry editor. See[how to open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-open-registry-editor/) for more information.
2. Navigate to the following folder in the registry:  
`HKEY_CURRENT_USER\Control Panel\Desktop`
3. In the pane on the right, look for the string named**WaitToKillAppTimeout** .
4. If you don’t see it, you’ll need to create it by right-clicking in any empty space in the pane and selecting**New > String Value** . Rename it**WaitToKillAppTimeout** .
5. Double-click this string to edit its value, which is in milliseconds. (1000 milliseconds equals one second.) By default, the value data is set to 20,000 (or 20 seconds).
6. Increase this value to make Windows wait on running apps longer before shutting down or logging off. (Decreasing its value will log you off more quickly.)

### 1B. How to Change WaitToKillAppTimeout for All Users

This will apply altered log-off rules to all users on the PC.

1. Open the Registry editor.
2. Navigate to the following folder in the registry:  
`HKEY_USERS\.DEFAULT\Control Panel\Desktop`
3. Follow steps three to six from method 1A to change how long Windows waits for apps to finish closing properly when logging off for all users.

### 2A. How to Set HungAppTimeout for Just Your User Account

 Doing this will change how long Windows waits for apps that it considers hung. This is just for your user account.

1. Open the Registry Editor.
2. Navigate to the following folder in the Registry:  
`HKEY_CURRENT_USER\Control Panel\Desktop`
3. In the pane on the right, look for the string named**HungAppTimeout** .
4. If the string doesn’t exist, create it by right-clicking in any empty space in the pane and choosing**New > String Value** . Rename it**HungAppTimeout** .
5. Double-click this string to edit its value – again, in milliseconds. (1000 milliseconds equals 1 second.) By default, the value data is set to 5000.
6. Increase this value to make Windows afford more time to hung apps and wait longer when shutting down or logging off. (Reduce this value to log off more quickly.)

### 2B. How to Change HungAppTimeout for All Users

This will allow you to change the default value for all users.

1. Open the Registry Editor.
2. Navigate to the following folder in the registry:  
`HKEY_USERS\.DEFAULT\Control Panel\Desktop`
3. Follow steps 3 to 6 from method 2A to change how long Windows waits when logging off for all users.

## Give Apps More Time to Close When Logging Off

 If apps keep interrupting Windows when you shut down or log off, it would be wise to give them a little more time to finish up and close properly. That way, they won’t interrupt the log-off process and have you intervene manually.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/top-8-windows-11-no-nos-common-pitfalls-to-skip/"><u>Top 8 Windows 11 No-Nos: Common Pitfalls to Skip</u></a></li>
<li><a href="https://windows11.techidaily.com/explore-the-best-techniques-to-streamline-your-windows-folder-system/"><u>Explore the Best Techniques to Streamline Your Windows Folder System</u></a></li>
<li><a href="https://windows11.techidaily.com/switching-your-windows-security-pin-quickly/"><u>Switching Your Windows Security Pin Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-challenge-of-non-working-win-plus-printer-feature-in-windows/"><u>Tackling the Challenge of Non-Working Win + Printer Feature in Windows.</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-camera-access-notification-controls-on-win11/"><u>Mastering Camera Access Notification Controls on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-issues-with-the-epic-games-launcher-for-win-users/"><u>Preventing Issues with the Epic Games Launcher for Win Users</u></a></li>
<li><a href="https://windows11.techidaily.com/switching-file-permissions-disabling-read-only-on-win-os/"><u>Switching File Permissions: Disabling Read-Only on Win OS</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-window-11-email-app-error-code-0x800713f/"><u>Overcoming Window 11 Email App Error Code 0X800713F</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-overcome-java-vm-not-found-on-pc/"><u>How to Overcome Java VM Not Found On PC</u></a></li>
<li><a href="https://windows11.techidaily.com/what-is-ftdibussys-on-windows-and-why-does-it-disable-memory-integrity/"><u>What Is ftdibus.sys on Windows and Why Does It Disable Memory Integrity?</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-premier-ai-for-stunning-photo-creation/"><u>[Updated] Premier AI for Stunning Photo Creation</u></a></li>
<li><a href="https://unlock-android.techidaily.com/unlock-your-infinix-hot-40is-potential-the-top-20-lock-screen-apps-you-need-to-try-by-drfone-android/"><u>Unlock Your Infinix Hot 40is Potential The Top 20 Lock Screen Apps You Need to Try</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-music-from-honor-magic5-ultimate-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Music from Honor Magic5 Ultimate to iPod | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-joint-filmmaking-and-gaining-followers-quickly/"><u>2024 Approved  Joint Filmmaking & Gaining Followers Quickly</u></a></li>
<li><a href="https://howto.techidaily.com/bricked-your-vivo-y55s-5g-2023-heres-a-full-solution-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Bricked Your Vivo Y55s 5G (2023)? Heres A Full Solution | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-laugh-track-in-the-air-parody-anthems/"><u>In 2024, Laugh Track in the Air  Parody Anthems</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/in-2024-unlocking-the-full-potential-of-audacity-a-comprehensive-installation-and-removal-manual-for-ubuntu-users/"><u>In 2024, Unlocking the Full Potential of Audacity A Comprehensive Installation and Removal Manual for Ubuntu Users</u></a></li>
<li><a href="https://extra-support.techidaily.com/lifelike-linkage-logistics-softwares-substance-over-hardwares-hustle-for-2024/"><u>Lifelike Linkage Logistics  Software's Substance over Hardware's Hustle for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-faster-than-light-instagram-video-experience-for-mobile-users/"><u>In 2024, Faster-Than-Light Instagram Video Experience for Mobile Users</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-undelete-lost-call-logs-from-oppo-a38-by-fonelab-android-recover-call-logs/"><u>Best Android Data Recovery - undelete lost call logs from Oppo A38</u></a></li>
</ul></div>
