---
title: "Troubleshooting: Eliminating 'Enter Username/Password' Alerts in Windows"
date: 2024-06-25T12:27:19.028Z
updated: 2024-06-26T12:27:19.028Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Troubleshooting: Eliminating 'Enter Username/Password' Alerts in Windows"
excerpt: "This Article Describes Troubleshooting: Eliminating 'Enter Username/Password' Alerts in Windows"
keywords: Fix Login Prompt on PC,Disable User Credential Alert,Remove Password Entry Screen,Stop WinLogin Popup,End Username/Password Window,Eliminate Authenticate Warning,Bypass Windows Login Screen
thumbnail: https://thmb.techidaily.com/b4ed3f08ab6e820bb58ff66c5f5e67696c65d753e22482d093bffe3ae2ca67e1.png
---

## Troubleshooting: Eliminating 'Enter Username/Password' Alerts in Windows

 The network credentials on your PC are important because they prevent others from using your computer across the network. While this feature is essential to protect your important files and improve the overall security of your system, it can sometimes cause issues as well.

 A common problem is when the network credential manager keeps displaying the "Enter network credentials" dialog, even when you enter the correct credentials. In this guide, we will walk you through some troubleshooting methods you can try to fix this issue for good.

## 1\. Modify the Advanced Sharing Settings

 An incorrectly set Advanced Sharing setting is one of the most common causes of this error. Ideally, your PC should be allowed to manage homegroup connections. You can also use the Advanced Sharing settings page to disable password-protected sharing, which will allow you to share files without needing to log in.

 Here is how you can configure the Advanced Sharing settings correctly:

1. Locate the network icon on your taskbar and right-click on it.
2. Choose **Network and Internet settings** from the context menu.  
![Network and Internet settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/network-and-internet-settings.jpg)
3. In the following window, select **Network and Sharing Center**.
4. Choose **Change advanced sharing settings** option in the left pane.
5. Now, enable the **Allow Windows to manage homegroup connections (recommended)** option under Homegroup connections.
6. Click **Save changes** (you will need administrative access for this).
7. Now, expand the **All Networks** section and enable the **Turn off password protected sharing** option.  
![Turn off password sharing option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/turn-off-pasword-sharing.jpg)
8. Hit the **Save changes** button to complete the process.

 After you've transferred the files, re-enable password-protected sharing so that others don't get easy access to your PC.

## 2\. Use Your Microsoft Account Credentials or the Computer's Name

 You can also try logging onto the target PC using the Microsoft account credentials instead of the local username and password.

 Alternatively, you can also try using the name of the computer you are using alongside your username in the text field associated with the Username. Do not enter a space, bar, or any other symbol between the names.

 If the problem is associated with the credentials, one of these two methods is likely to help you get rid of it for good.

## 3\. Manually Add the Credentials of the Target Computer to the Credential Manager

 Another way to fix the issue is by manually adding the credentials of the targeted computer in the Credential Manager and seeing if that makes a difference.

 Here is how you can do that:

1. Type "Credential Manager" into Windows Search and click **Open**.
2. Select **Windows Credential** and click on **Add a Windows Credential**.  
![Windows credentials](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/windows-credentials-1.jpg)
3. Now, add the username, computer name, and password of the computer you are trying to access. Check if you can now share files with the other device successfully.

## 4\. Create a New User Account on Both Devices

 There are times when user accounts become corrupt and stop you from performing certain actions. If this has happened, either on your PC or the target computer, it can interrupt the file-sharing process.

 To fix this problem, first, try [switching to a different user account](https://www.makeuseof.com/windows-11-switch-user-accounts/) on your own computer and see if that works. If this strategy fails, then we recommend [creating a new user account](https://www.makeuseof.com/windows-11-create-local-user-account/) on both devices with the same username and password. Make sure that both accounts have administrative privileges. While you are at it, we also suggest temporarily disabling any third-party antivirus program that you might be using, as it can sometimes block network access.

 If the root of your issue was a corrupt user account, this should be enough to fix the issue.

## 5\. Restart the Credential Manager Service

 The issue might also be with the Credential Manager service itself instead of the targeted computer or the network settings of your device. In this method, we will first enable the Credential Manager service if the service is disabled.

 If it is working already, then we will proceed with restarting the service and see if that does the trick.

 Here is what you need to do:

1. Press **Win** \+ **R** to open Run.
2. Type services.msc in the Run and click **Enter**.
3. In the following window, look for the Credential Manager service and right-click on it.
4. Choose **Properties** from the context menu.
5. If the service is disabled, click on the **Start button** to enable it.
6. In case it is working already, click on the **Stop button**, wait for a few seconds, and then hit the **Start button**.
7. ![Credential Manager properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/credential-manager-properties.jpg)  
 Make sure that the Startup type is set to **Automatic**.  
![Credential Manager service properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/credential-manager-service.jpg)
8. Click **Apply** \> **OK** to save the changes.

 Now try connecting to the targeted computer and see if you can do so without any problems.

## 6\. Make Changes to the Local Security Policy

 Several users also managed to fix the problem by modifying the settings of the "Accounts: Limit local account use of blank passwords to console logon only" policy. Here is how you can give it a try too:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "secpol.msc" in Run and click **Enter**.
3. In the following window, navigate to the following location:  
Local Policies > Security Options > Accounts: Limit local account use of blank passwords to console logon only
4. Choose **Disabled** and click **Apply** \> **OK** to save the changes.  
![Make changes to the Local Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-security-policy.jpg)
5. Restart your computer and check if the issue is resolved.

## 7\. Try Using Safe Mode With Networking

 If the credentials you are entering and all the network configurations on the system are correct, something might have gone wrong on a system level.

 In this case, you can boot into Safe Mode to determine the cause of the issue. Safe Mode starts Windows with only the basic set of drivers and apps — the ones that are essential for the operating system to function.

 There are several types of Safe Mode including Minimal, Alternate Shells, Active Directory Repair, and Network. In this method, we will be booting Windows into Safe Mode with Networking. This mode launches Windows with the drivers and programs required to connect the system to the internet or other devices over the network.

 If the error at hand does not appear in Safe Mode, then there is a chance that malware or other software issues are causing the problem.

 Here is what you need to do:

1. Head over to the Start menu and click on the **Power button**.
2. Choose **Restart** while holding the **Shift key**.
3. Wait for the Windows to boot into the recovery mode and then choose **Troubleshoot** \> **Advanced Options**.
4. Navigate to **Startup Settings** \> **Restart**.
5. In the following window, press the **F5 key** on your keyboard to boot into Safe Mode with Networking.  
![Pick safe mode with Networking option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/Tweak-Startup-Settings-1.jpg)
6. Once you are logged into Safe Mode, try connecting to the device you were previously trying to connect to. If the error does not appear in Safe Mode, then you might want to report this issue to Microsoft’s official support team and wait for a fix from their side.

 In case you cannot access this Windows state using the steps outlined above, you can try [other ways of booting into Safe Mode](https://www.makeuseof.com/windows-11-boot-safe-mode/).

## Share Data Over Network Without Issues

 Windows has made it simpler to share your files and other data across networks, but there are times when you run into unexpected errors. Hopefully, one of the methods mentioned above did the trick for you in fixing the issue under consideration.

 A common problem is when the network credential manager keeps displaying the "Enter network credentials" dialog, even when you enter the correct credentials. In this guide, we will walk you through some troubleshooting methods you can try to fix this issue for good.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/navigating-windows-1011s-auto-restart-settings/"><u>Navigating Windows 10/11'S Auto-Restart Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/revising-account-lockout-count-after-multiple-login-failures-in-windows-11/"><u>Revising Account Lockout Count After Multiple Login Failures in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-your-smartphone-writescreen-functionality-for-windows-11/"><u>Unlocking Your Smartphone' Writescreen Functionality for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/masterful-methods-to-overcome-security-errors-in-windows-11/"><u>Masterful Methods to Overcome Security Errors in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/managing-storage-with-onedrive-rearrange-for-win-11/"><u>Managing Storage with OneDrive – Rearrange for Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-enhance-copy-paste-efficiency-across-browsers/"><u>How to Enhance Copy-Paste Efficiency Across Browsers</u></a></li>
<li><a href="https://windows11.techidaily.com/choosing-between-windows-11-home-and-pro-your-ideal-edition/"><u>Choosing Between Windows 11 Home & Pro: Your Ideal Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-win-ethernet-no-internet-error/"><u>Resolving Win Ethernet No Internet Error</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-microphone-setup-with-the-latest-windows-11-features/"><u>Streamlining Microphone Setup with the Latest Windows 11 Features</u></a></li>
<li><a href="https://windows11.techidaily.com/black-friday-extravaganza-save-big-612-forever-win10/"><u>Black Friday Extravaganza: Save Big - $6.12 Forever Win10</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-oppo-reno-11-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How PGSharp Save You from Ban While Spoofing Pokemon Go On Oppo Reno 11 5G? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-a-filmmakers-essential-guide-to-free-royalty-free-audiosites/"><u>[New] In 2024, A Filmmaker's Essential Guide to Free Royalty-Free Audiosites</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-quick-solved-how-to-add-subtitles-to-a-video-on-iphones/"><u>Updated 2024 Approved Quick Solved How to Add Subtitles to a Video on iPhones</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-silencing-sounds-techniques-for-audio-deletion-in-imovie-videos/"><u>Updated In 2024, Silencing Sounds Techniques for Audio Deletion in iMovie Videos</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-from-raw-footage-to-final-cut-chroma-mastery/"><u>2024 Approved  From Raw Footage to Final Cut  Chroma Mastery</u></a></li>
<li><a href="https://extra-skills.techidaily.com/narrative-nexus-cutting-edge-storytelling-channels-of-the-year-for-2024/"><u>Narrative Nexus  Cutting-Edge Storytelling Channels of the Year for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-top-10-password-cracking-tools-for-zte-blade-a73-5g-by-drfone-android/"><u>In 2024, Top 10 Password Cracking Tools For ZTE Blade A73 5G</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/winning-game-recording-guide-for-w11-users-for-2024/"><u>Winning Game Recording Guide for W11 Users for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-five-best-free-fb-video-downloader-hacks/"><u>In 2024, Five Best Free FB Video Downloader Hacks</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-ice-warriors-battle-the-spectacular-winter-olympics-snowboard-showdown/"><u>In 2024, Ice Warriors Battle - The Spectacular Winter Olympics Snowboard Showdown</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>