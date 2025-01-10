---
title: "Dealing with the 'Extract to Temp Directory' Glitch: Fix for Error 1152"
date: 2025-01-09T21:57:55.669Z
updated: 2025-01-10T21:22:53.807Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Dealing with the 'Extract to Temp Directory' Glitch: Fix for Error 1152"
excerpt: "This Article Describes Dealing with the 'Extract to Temp Directory' Glitch: Fix for Error 1152"
keywords: Extract To Temp Fix,Error 1152 Solution,Temp Folder Issue,Correcting Extract Glitch,Stop File Error 1152,Overcoming Temp Directory Error,Resolve Extract to Temp Problem
thumbnail: https://thmb.techidaily.com/db7a51fc88bb312b4c001dc26d2d013159de6bfbef053f36ef148640b15c567b.jpg
---

## Dealing with the 'Extract to Temp Directory' Glitch: Fix for Error 1152

 Error 1152 is an issue some users report occurring when trying to install certain Windows software packages. This InstallShield error has the following message, “1152: Error extracting files to the temporary location.” That error halts the installation of software.

 The error 1152 message highlights something has gone wrong with the extraction of files during installation. It also mentions extraction to a temporary location, a clue for a possible cause. This is how you can fix Error 1152 on a Windows 10 or 11 PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MHafwnWSEQk?si=rejNVNpJZH2SqNLy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Download the Affected Installation File Again

 This error can feasibly occur because of an issue with the downloaded installer file. Download process errors can corrupt files. So, try downloading the same setup file again, preferably from a different website source if you can. Then right-click the new installer file and select to run it with administrative rights.

## 2\. Set Full Control Permissions for the Temp Folder

 Setting full control permissions for the Temp folder has fixed error 1552 for many users. That highlights error 1152 occurs because the Temp folder has insufficient permissions. You can address such a potential cause by adjusting permission settings for the Temp folder like this:

1. Go to "C:\\Windows" in File Explorer, then right-click on the **temp** directory in the Windows folder and select **Properties**.
2. ![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/properties-option5.jpg)
3. Select **Security** within the tab bar.
4. Click on the **Edit** button to view a permission window.  
![The Edit button on the temp Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-button.jpg)
5. Next, click **Add** to bring up an object name selection window.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xq2r4ZKM-Po?si=fA2DdEB1op-atCkz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![The Select Users or Groups window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/select-user-or-groups-window.jpg)

1. Type **everyone** inside the object name box, then click **Check Names**.
2. Select **OK** to add the **Everyone** group.
3. Click **Everyone** within the Permission for Temp window.
4. Select the **Full control** permission checkbox.  
![Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/full-control-checkbox.jpg)
5. Apply and OK out of all windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jvwX82j3ci0?si=gAWoovjXgs3m1d7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. It’s also recommended to repeat those steps for the Temp folder in the local directory. You can reach that folder at the following path:  
`C:\Users\<user folder>\AppData\Local`

 If the **Security** tab says you need read permissions, click **Advanced** \> **Change**. Input **Everyone** in the group user box, as instructed above, select **System** on the Advanced Security window, and press the **Add** button. That will bring up another Select User or Group window in which you must input **Everyone** again. Then select the **Full control** checkbox from there.

## 3\. Clear the Temporary Files Folder

 Corrupted data in the Temp folder is also a known cause of error 1152\. You can address such a cause by clearing the data in that folder. There are a few ways you can do that, but erasing data in that folder with the Disk Cleanup tool is recommended.

 Our guide on [deleting temporary files on Windows 11](https://www.makeuseof.com/windows-11-delete-temporary-files/) includes instructions for erasing data in the Temp folder with Disk Cleanup and other methods.

![The Temporary files checkbox in the Disk Clean-up tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/temporary-files-checkbox.jpg)

## 4\. Perform a Clean Boot

 Performing a clean boot means restarting Windows 11/10 without any third-party background apps and services enabled. This is a recommended troubleshooting method for error 1152 because it could eliminate background items conflicting with your software installation. You might then be able to install the software as required after the clean boot.

 First, you must configure a clean boot by disabling third-party background items with Task Manager and System Configuration (MSConfig). To do that, follow the instructions in our [how to clean boot Windows](https://www.makeuseof.com/clean-boot-windows-11/) guide. Then restart your PC with the third-party items disabled and try running the affected installer file.

![The Hide all Microsoft services checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hide-all-microsoft-services-checkbox.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vca--yEhtdo?si=7ijqjyP-oi3LYze1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mMYEK2gtY5c?si=ytxNz_JHZkTrwb4b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Install the Windows Software You Need Again

 There aren’t that many confirmed resolutions for error 1152\. However, the ones covered here have worked for many users who’ve needed to fix that Windows software installation issue.

 The error 1152 message highlights something has gone wrong with the extraction of files during installation. It also mentions extraction to a temporary location, a clue for a possible cause. This is how you can fix Error 1152 on a Windows 10 or 11 PC.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-2023-ranking-top-6-apps-for-fb-lite-video-downloads/"><u>[Updated] In 2024, 2023 Ranking Top 6 Apps for FB Lite Video Downloads</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/assessing-the-limitations-samsung-and-ubreakifix-partnership-analysis/"><u>Assessing the Limitations: Samsung and uBreakiFix Partnership Analysis</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/bypassreset-oneplus-phone-screen-passcodepatternpin-by-drfone-android-unlock-android-unlock/"><u>Bypass/Reset OnePlus Phone Screen Passcode/Pattern/Pin</u></a></li>
<li><a href="https://screen-recording.techidaily.com/essential-8-android-group-calls-over-4-users-in-2024/"><u>Essential 8 Android Group Calls Over 4 Users, In 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-the-audio-device-not-installed-error-effectively-for-windows-users/"><u>Fix the 'Audio Device Not Installed' Error Effectively for Windows Users</u></a></li>
<li><a href="https://buynow-help.techidaily.com/in-depth-evaluation-the-conveniently-small-yet-imperfect-criacr-bluetooth-fm-transmitter-cp24-edition/"><u>In-Depth Evaluation: The Conveniently Small yet Imperfect CRIACR Bluetooth FM Transmitter - CP24 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/rejuvenating-win11-drive-non-destructive-freeing-methods-max-156-chars/"><u>Rejuvenating Win11 Drive: Non-Destructive Freeing Methods (Max 156 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-problematic-windows-protection-protocol/"><u>Resolving Problematic Windows Protection Protocol</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-accessibility-to-essential-windows-command-center/"><u>Restoring Accessibility to Essential Windows Command Center</u></a></li>
<li><a href="https://location-social.techidaily.com/set-your-preferred-job-location-on-linkedin-app-of-your-motorola-moto-g34-5g-drfone-by-drfone-virtual-android/"><u>Set Your Preferred Job Location on LinkedIn App of your Motorola Moto G34 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/steering-users-clear-of-disconnection-hurdles-from-nvidia/"><u>Steering Users Clear of Disconnection Hurdles From Nvidia</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-entering-windows-11-home-settings/"><u>Step-by-Step: Entering Windows 11 Home Settings</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-how-to-fix-cant-cast-to-device-issue-on-windows-10/"><u>Troubleshooting Guide: How to Fix 'Can't Cast to Device' Issue on Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/uncovering-and-correcting-cant-access-mail-errors-in-windows-11-mail-app/"><u>Uncovering and Correcting Can't Access Mail Errors in Windows 11 Mail App</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-windows-timers-for-efficient-pomodoros/"><u>Winning Windows Timers for Efficient Pomodoros</u></a></li>
</ul></div>

