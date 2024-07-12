---
title: "Secure Telnet Configuration: Three Essential Steps for Wins OSes"
date: 2024-07-11T22:02:54.270Z
updated: 2024-07-12T22:02:54.270Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Secure Telnet Configuration: Three Essential Steps for Wins OSes"
excerpt: "This Article Describes Secure Telnet Configuration: Three Essential Steps for Wins OSes"
keywords: Secure Telnet Setup,Windows Telnet Security,Telnet Configurations,WinOS Telnet Safety,Essential Telnet Steps,OS Telnet Protection,Telnet Security Guide
thumbnail: https://thmb.techidaily.com/b0ea6d61080761dc873cfd8c694bea1246e45e087ea28aa28a47640ed6e89f83.jpg
---

## Secure Telnet Configuration: Three Essential Steps for Wins OSes

 Despite the vulnerability issues, Telnet is still used as a client-server protocol by Windows users. It is primarily used for initial network hardware configuration, remote access, port testing and forwarding, and other tasks that don't involve sensitive information transfer.

 You can enable Telnet on Windows 10 and 11 computers via Command Prompt or the Graphics User Interface (GUI) tool. Here we show you the many ways to enable Telnet on your Windows computer.

## 1\. Enable Telnet on Windows Using Control Panel

 You can enable Telnet Client using the Classic Control Panel. Since it is an optional feature, you can enable it using the Windows Optional Feature dialog. You can use it [add or remove other users' optional features on Windows](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) .

To enable Telnet Client using Control Panel:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel.**
3. In Control Panel, Click on**Uninstall a Program** under**Programs and Features.**  
![turn windows features on or off control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/turn-windows-features-on-or-off-control-panel.jpg)
4. In the left pane, click on the**Turn Windows feature on or off.**  
![enable telnet client windows features dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-windows-features-dialog.jpg)
5. In the Windows Features dialog, scroll down and select**Telnet Client.**
6. Click**OK** and wait for the feature to install. Once installed, restart your PC to apply the changes and enable the feature.

If you need to disable Telnet:

1. Open the**Windows Features** dialog and unselect**Telnet Client.**
2. Click**OK** and wait for the feature to uninstall.
3. Click on**Restart** now to reboot your PC and apply the changes.

## 2\. Enable Telnet Client Using Windows PowerShell

![enable telnet client powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-powershell.jpg)

 You can use the Enable-WindowsOptionalFeature cmdlet to enable Telnet Client using Windows PowerShell. Useful if you are unable to turn on the feature using the Windows Features dialog and it is also faster than the GUI method.

To enable Telnet using Windows PowerShell:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Windows Terminal(Admin)** and click**Yes** to open the terminal app as administrator. If you are using Windows 10, type**PowerShell** in**Windows Search** and open**Windows PowerShell** administrator.
3. In the PowerShell window, type the following command and press**Enter** to enable Telnet:  
`Enable-WindowsOptionalFeature -Online -FeatureName TelnetClient`
4. This process may take several minutes, so wait for it to complete and return a status report. If successful, you’ll see the result as**Online:True.**
5. If you want to disable Telnet Client, use the following command instead:  
`Disable-WindowsOptionalFeature -Online -FeatureName TelnetClient`
6. Close PowerShell and restart your PC.

## 3\. Install Telnet Client Using Command Prompt

![enable telnet command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-command-prompt.jpg)

 If you prefer Command Prompt over PowerShell, you can use the DISM /Online command to enable the optional features on your Windows 11 computer.

Follow these steps to install Telnet using Command Prompt:

1. Press the**Win** key and type**cmd** .
2. Right-click on**Command Prompt** and select**Run as administrator.**
3. In the Command Prompt window, type the following command and press**Enter** :  
`dism /online /Enable-Feature /FeatureName:TelnetClient`
4. Command Prompt will start enabling the feature and display the operation completed successfully message.
5. If you need to disable Telnet, type the following command and press**Enter** :  
`dism /Online /Disable-Feature /FeatureName:TelnetClient`
6. Wait for the success message.
7. Type**exit** and press**Enter** to close Command Prompt.

## How to Check the Telnet Client Status on Your PC

![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)

 You can check if the Telnet client is enabled on your PC using a Command Prompt command. When enabled, the Telnet command will open a new CMD to connect to remote servers and perform other tasks.

1. Launch Command Prompt as administrator (see [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
2. In the Command Prompt window, type**Telnet** and press**Enter** .
3. A new CMD with Microsoft Telnet will open.

## All the Ways to Enable Telnet On Your Windows 11 Computer

 Telnet is a built-in remote access utility that you can use to troubleshoot firewall and network issues. While it is still part of Windows, system administrators now prefer the more secure SSH protocol to access computers over an unsecured network.

 The major disadvantage of Telnet is that it is not secure and prone to a man-in-the-middle attack. If not for particular situations, switch to a more secure network protocol such as SSH and Mosh with better password and public key authentication.


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
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-xiaomi-redmi-note-13-proplus-5g-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>How to Unlock Xiaomi Redmi Note 13 Pro+ 5G Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-league-of-legends-playability-on-pc/"><u>Restoring League of Legends Playability on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-unreachable-issues-with-malwarebytes-on-win11/"><u>Resolving Unreachable Issues with Malwarebytes on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/secret-menu-additions-a-step-by-step-guide-in-win-10/"><u>Secret Menu Additions: A Step-by-Step Guide in Win 10</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-music-from-galaxy-a23-5g-by-fonelab-android-recover-music/"><u>Undelete lost music from Galaxy A23 5G</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-all-time-highest-chart-youtubes-premier-video-list/"><u>[Updated] In 2024, All-Time Highest Chart  YouTube's Premier Video List</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-6-appsservices-to-trace-any-realme-10t-5g-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, Top 6 Apps/Services to Trace Any Realme 10T 5G Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-windows-update-error-0x8024800c/"><u>Tackling Windows Update: Error 0X8024800C</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-classic-14-animation-designs-with-text/"><u>2024 Approved  Classic 14 Animation Designs with Text</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-remedying-error-code-0x80300024/"><u>Understanding and Remedying Error Code: 0X80300024</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-path-not-found-issue-in-windows-xp7/"><u>Resolving Path Not Found Issue in Windows XP/7</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-non-persistent-print-device-selection/"><u>Troubleshooting: Non-Persistent Print Device Selection</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-security-refreshing-windows-group-policies/"><u>Streamlining Security: Refreshing Windows Group Policies</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/how-to-feature-music-on-instant-stories-for-2024/"><u>How to Feature Music on Instant Stories for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-code-workflows-with-windows-11s-developer-environment/"><u>Streamlining Code Workflows with Windows 11'S Developer Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-variances-microsoft-account-versus-conventional-local-login/"><u>Unveiling Variances: Microsoft Account Versus Conventional Local Login</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-defender-how-to-deactivate-it/"><u>Windows 11 Defender: How to Deactivate It</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-ea-server-connection-failure-in-windows/"><u>Resolving EA Server Connection Failure in Windows</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-elevate-video-flair-advanced-techniques-in-youtube-studio-editor/"><u>[New] Elevate Video Flair  Advanced Techniques in YouTube Studio Editor</u></a></li>
<li><a href="https://windows11.techidaily.com/switch-onoff-windows-filter-keys-guide/"><u>Switch On/Off: Window's Filter Keys Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-enhancing-your-search-system/"><u>Windows 11: Enhancing Your Search System</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-facebook-dating-for-your-realme-c51-drfone-by-drfone-virtual-android/"><u>How to Change Location On Facebook Dating for your Realme C51 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-overcoming-printer-not-connected-problems/"><u>Win11: Overcoming Printer Not Connected Problems</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-2024-approved-achieve-hollywood-grade-video-a-step-by-step-fcpx-guide/"><u>New 2024 Approved Achieve Hollywood-Grade Video A Step-by-Step FCPX Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-efficient-application-batch-deployment-via-winstall/"><u>Windows 11: Efficient Application Batch Deployment via Winstall</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-error-x80780119/"><u>Troubleshooting Windows' Error X80780119</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-work-with-non-verified-windows-apps/"><u>Techniques to Work with Non-Verified Windows Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-ideas-to-art-the-leading-7-drawing-apps-for-win10-users/"><u>Transforming Ideas to Art: The Leading 7 Drawing Apps for Win10 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/what-is-the-windows-portable-executable-file-format/"><u>What Is the Windows Portable Executable File Format?</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-screenshotting-windows-security-alerts/"><u>Techniques for Screenshotting Windows' Security Alerts</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-how-to-reroute-your-onedrive-storage/"><u>Windows 11: How to Reroute Your OneDrive Storage</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-potential-the-top-7-ways-to-optimize-windows-11-use-42/"><u>Unlocking Potential: The Top 7 Ways to Optimize Windows 11 Use (42)</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-science-behind-stopping-photo-booth-movies/"><u>[Updated] The Science Behind Stopping Photo Booth Movies</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-mastering-podcast-cover-art-top-decoding-strategies/"><u>[New] Mastering Podcast Cover Art  Top Decoding Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-an-old-pc-heres-why-you-might-want-to-ditch-windows/"><u>Reviving an Old PC? Here's Why You Might Want to Ditch Windows</u></a></li>
</ul></div>
