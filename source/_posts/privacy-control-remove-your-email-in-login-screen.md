---
title: "Privacy Control: Remove Your Email in Login Screen"
date: 2024-11-20T02:44:31.653Z
updated: 2024-11-24T17:24:26.922Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Privacy Control: Remove Your Email in Login Screen"
excerpt: "This Article Describes Privacy Control: Remove Your Email in Login Screen"
keywords: Email Removal Login,Privacy Settings Change,Logout Email,Disable Email Sign-In,Hide Personal Info Login,Email Deletion Screen,Secure Login No Email
thumbnail: https://thmb.techidaily.com/2b3cfba87301486dbbd741d1b746c08f2612d680177b5f240dd8a8230542393a.jpg
---

## Privacy Control: Remove Your Email in Login Screen

 If you frequently use your computer in public places, it's a good idea to remove your email address from the Windows login screen. This means people can't get your email address if they see your screen over your shoulder.

 You can accomplish this using the Settings app, Group Policy Editor, or Registry Editor. In this post, we've covered all these methods in detail.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YpnYKIrpgZQ?si=94zicAHp1CH-0oso&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Hide Email Address From Windows Login Screen Using the Settings App

 The Windows Settings app provides a quick way to hide account information from the login screen. So, if you are in a rush, use the following steps to remove user email addresses from the Windows login screen.

1. Press**Win + I** or use one of the[many ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Accounts > Sign-in options** .
3. Under**Additional settings** , toggle off the switch next to **Show account details such as my email address on the sign-in screen** .  
![Hide Email From Windows Login Screen Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/d-COuhPT5mk?si=wLZU6jkkAdJuAn6h&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Hide Email Address From Windows Login Screen Using the Group Policy Editor

 The Group Policy Editor (or gpedit.msc) is a handy Windows tool for configuring advanced system settings. You can also this tool to hide your email address from the Windows login screen.

 Note that the Group Policy Editor is only available on Windows Professional, Education, and Enterprise editions. If your PC is running Windows Home, check out[how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

1. Press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the search box and select the first result that appears.
3. Use the left pane to navigate to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options** .
4. Double-click the **Interactive Logon: Display user information when the session is locked** policy on your right.
5. In the properties window, click the drop-down menu to select the**Do not display user information** option.
6. Click**Apply** followed by**OK** .  
![Hide Email From Windows Login Screen Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-group-policy-editor.jpg)
7. Next, double-click on the**Interactive logon: Do not display last user name** policy from the same section.
8. Select**Enabled** in the properties window.
9. Click**Apply** followed by**OK** to save changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0Kr7Dpw0HuM?si=05wWDXdPgmC-oBBE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. How to Hide Email Address From Windows Login Screen Using the Registry Editor

 If the above two methods don’t work for some reason, you can make changes to the Windows registry files to hide your email address from the login screen. For that, you’ll need to use the Registry Editor on Windows.

 When it comes to editing Registry files, it's important to be cautious as making incorrect changes can cause irreversible damage to your PC. We recommend you either back up all the registry files or create a restore point before you make any changes. If you need help with that, check our guides on[how to back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and[how to create a restore point in Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

 Once you’re done with that, use the following steps to hide your email address from the Windows login screen via Registry Editor.

1. Press**Win + X** to open the Power User menu and select**Run** from the list.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows > System** .
5. Right-click on the**System** key and select**New > DWORD (32-bit) Value** .
6. Rename the DWORD to**BlockUserFromShowingAccountDetailsOnSignin** .
7. Double-click on the newly created DWORD and enter**1** in the**Value data** field. Then, click**OK** .  
![Hide Email From Windows Login Screen Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-registry-editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vfq0vw0Spz8?si=2EAk6hW-Gb-o33_L&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Exit the Registry Editor and restart your PC for the changes to take effect.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_7AYCS7zBU0?si=7R9oIpE4hyEbtk3x&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Hiding Your Email Address From the Windows Login Screen Is Easy

 As we just saw, hiding your personal information from the Windows login screen barely takes a couple of minutes, regardless of the method you employ.

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
<li><a href="https://twitter-videos.techidaily.com/new-a-practical-guide-to-managing-twitter-archives/"><u>[New] A Practical Guide to Managing Twitter Archives</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-guide-to-excellent-voice-recorders-for-macs-for-2024/"><u>[New] Guide to Excellent Voice Recorders for Macs for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/comparing-the-best-of-gopro-cameras-for-2024/"><u>Comparing the Best of GoPro Cameras for 2024</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-and-installation-hp-officejet-pro-8600-printing-drivers-for-windows-operating-system/"><u>Download & Installation: HP Officejet Pro 8600 Printing Drivers for Windows Operating System</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/eliminating-code-nt000-nt004-nt005-errors-in-windows-device-manager-with-ease/"><u>Eliminating Code nT!000, NT!004, NT!005 Errors in Windows Device Manager with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/fast-forwarding-copy-and-paste-custom-hotkeys-for-text-snaps-in-win11/"><u>Fast-Forwarding Copy & Paste: Custom Hotkeys for Text Snaps in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/hacked-scans-halt-evaluating-windows-biometric-security-now/"><u>Hacked Scans Halt: Evaluating Window's Biometric Security Now</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-pc-screen-to-vivo-s17t-phones-drfone-by-drfone-android/"><u>How to Mirror PC Screen to Vivo S17t Phones? | Dr.fone</u></a></li>
<li><a href="https://article-files.techidaily.com/in-2024-earnings-trends-in-the-digital-audio-space/"><u>In 2024, Earnings Trends in the Digital Audio Space</u></a></li>
<li><a href="https://windows11.techidaily.com/maximize-efficiency-and-security-enabling-powershell-execution-policies/"><u>Maximize Efficiency and Security: Enabling PowerShell Execution Policies</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-not-written-memory-crisis-in-win/"><u>Navigating the 'Not Written' Memory Crisis in Win</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-11s-restricted-access-feature/"><u>Navigating Through Windows 11’S Restricted Access Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-setup-snags-clipchamp-on-the-latest-of-windows-11/"><u>Overcoming Setup Snags: ClipChamp on the Latest of Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-device-not-initialized-warning-in-win-11/"><u>Rectifying 'Device Not Initialized' Warning in Win 11</u></a></li>
<li><a href="https://win-amazing.techidaily.com/revive-your-computers-communication-abilities-with-a-fresh-serial-controller-drivers-install/"><u>Revive Your Computer's Communication Abilities with a Fresh Serial Controller Drivers Install</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-setup-guide-windows-hello-fingerprinting/"><u>Step-by-Step Setup Guide: Windows Hello Fingerprinting</u></a></li>
<li><a href="https://windows11.techidaily.com/time-traveling-your-data-modifying-windows-file-dates/"><u>Time Traveling Your Data: Modifying Windows File Dates</u></a></li>
<li><a href="https://techtrends.techidaily.com/transcode-webm-a-ogg-online-gratuitement-avec-movavi/"><u>Transcode WebM À OGG Online Gratuitement Avec Movavi</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/vsi-vidrecorder-verdicts-in-depth-overview-for-2024/"><u>VSI VidRecorder Verdicts In-Depth Overview for 2024</u></a></li>
</ul></div>

