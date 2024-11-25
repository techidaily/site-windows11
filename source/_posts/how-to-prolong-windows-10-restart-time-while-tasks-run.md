---
title: How to Prolong Windows 10 Restart Time While Tasks Run
date: 2024-11-24T02:09:23.926Z
updated: 2024-11-24T22:02:29.992Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Prolong Windows 10 Restart Time While Tasks Run
excerpt: This Article Describes How to Prolong Windows 10 Restart Time While Tasks Run
keywords: Fast Windows 10 Boot,Minimize Restarts,Shorten Win10 Startup,Quick OS Launch,Optimized Win10 Speed,Decrease PC Booting,Reduce System Relaunch
thumbnail: https://thmb.techidaily.com/37c258031093435d71dd94d5151455426579049284afd82c0786b6e3dd815a4b.jpg
---

## How to Prolong Windows 10 Restart Time While Tasks Run

 Sometimes, when shutting down, restarting, or logging off from your Windows 10 machine, you may get an error message that interrupts or even cancels the operation. To prevent this from happening, you can make Windows wait longer when logging off.

 Making the system give it a little while longer could actually save you time. Here’s what you should do, should you be faced with this situation.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kTHQrw8e1gk?si=gTPIa7KjhSZ0Vz97&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Does Windows Show an Error Message While Logging Off?

 It may be that you have quite a few tasks running simultaneously, each possibly with unsaved data. If this is the case, each task or application attempts to save data before Windows logs off. This could be one reason for the error message. As a remedy, you may want to extend the time allotted for signing off to allow all tasks to finish what they are doing.

 Alternatively, it could just be a problem task. This may be true if it is a recurring issue. In this case, and if you’re sure none of the applications you are using will lose data, you could make Windows force a sign-off more quickly.

## What Should You Try First?

 The method described here basically forces Windows to wait longer while shutting down or logging off. However, if you have a misbehaving program interfering with Windows log-off, it could be something to look into. There are fixes you should try first if there is an[app preventing Windows from shutting down or logging off](https://www.makeuseof.com/this-app-preventing-windows-shutting-down-restarting-signing-out-error/) .

 If none of those options works, you can adjust how long Windows waits before logging off, which gives any running or buggy apps more time to sort themselves out.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iOVkXoUxLf4?si=QfC18T2cb5OkiaXo&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Make Windows Wait Longer When Logging Off

 There are two processes that you can turn to. With the first, WaitToKillAppTimeout, Windows grants apps 20 seconds to save data and close. If apps don’t respond, Windows considers them “hung.” HungAppTimeout, the second, tells Windows how many seconds to wait before considering apps to be hung and offering a force-close solution.

 Changing both these values involves[editing the registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) , so be wary, and[make a backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) copy before you tinker with it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yDuvbv0QOYI?si=byottcEM_Rrvi4EL&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pGHmqD53gc8?si=ymgHIB6Aa7_MoUUf&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2A. How to Set HungAppTimeout for Just Your User Account

 Doing this will change how long Windows waits for apps that it considers hung. This is just for your user account.

1. Open the Registry Editor.
2. Navigate to the following folder in the Registry:  
`HKEY_CURRENT_USER\Control Panel\Desktop`
3. In the pane on the right, look for the string named**HungAppTimeout** .
4. If the string doesn’t exist, create it by right-clicking in any empty space in the pane and choosing**New > String Value** . Rename it**HungAppTimeout** .
5. Double-click this string to edit its value – again, in milliseconds. (1000 milliseconds equals 1 second.) By default, the value data is set to 5000.
6. Increase this value to make Windows afford more time to hung apps and wait longer when shutting down or logging off. (Reduce this value to log off more quickly.)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aoMiYpYiFZs?si=qvYvGytDD17fvSXO&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-boxes.techidaily.com/new-in-2024-enhancing-zoom-video-clarity-user-guide/"><u>[New] In 2024, Enhancing Zoom Video Clarity User Guide</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-smooth-streaming-elite-stabilizers-reviewed/"><u>[New] In 2024, Smooth Streaming Elite Stabilizers Reviewed</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-unlock-the-magic-of-capturing-youtube-content-the-no-cost-way/"><u>[New] Unlock the Magic of Capturing YouTube Content - The No-Cost Way</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-android-and-iphones-leading-tools-for-enhanced-fb-likes/"><u>[Updated] Android & iPhone's Leading Tools for Enhanced FB Likes</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-bandicam-demystified-a-clearer-understanding-of-2023-functionality/"><u>[Updated] In 2024, Bandicam Demystified A Clearer Understanding of 2023 Functionality</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-the-essential-guide-to-making-top-tier-educational-videos/"><u>[Updated] In 2024, The Essential Guide to Making Top-Tier Educational Videos</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-quintessential-10-virtual-brawls/"><u>[Updated] Quintessential 10 Virtual Brawls</u></a></li>
<li><a href="https://howto.techidaily.com/android-screen-stuck-general-vivo-y36-partly-screen-unresponsive-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Screen Stuck General Vivo Y36 Partly Screen Unresponsive | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-retrieve-lost-pictures-from-narzo-60-5g-by-fonelab-android-recover-pictures/"><u>Best Android Data Recovery - Retrieve Lost Pictures from Narzo 60 5G.</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-updater-failures-eliminate-xerror-0x80246007-in-win1011/"><u>Fixing Updater Failures: Eliminate XError 0X80246007 in Win10/11</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/forgot-iphone-14-plus-backup-password-heres-what-to-do-drfone-by-drfone-ios/"><u>Forgot iPhone 14 Plus Backup Password? Heres What to Do | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-phone-link-app-notifications-not-working-on-windows/"><u>How to Fix Phone Link App Notifications Not Working on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-use-imessage-on-windows/"><u>How to Use iMessage on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-finding-administrative-rules-on-pcs/"><u>Master the Art of Finding Administrative Rules on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-window-10s-captions-with-minimal-trouble/"><u>Mastering Window 10'S Captions with Minimal Trouble</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-for-ms-store-crash-error-code-0x0-on-win-1011/"><u>Quick Fix for MS Store Crash: Error Code 0X0 on Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-must-have-apps-to-maximize-your-windows-workflow/"><u>Top 5 Must-Have Apps to Maximize Your Windows Workflow</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-frozen-epic-launcher-steps-for-win-users/"><u>Troubleshooting Frozen Epic Launcher: Steps for Win Users</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-full-potential-of-windows-startup-options/"><u>Unlocking the Full Potential of Windows Startup Options</u></a></li>
</ul></div>

