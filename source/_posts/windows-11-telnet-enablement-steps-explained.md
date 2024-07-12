---
title: Windows 11 Telnet Enablement Steps Explained
date: 2024-07-11T21:33:31.725Z
updated: 2024-07-12T21:33:31.725Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Windows 11 Telnet Enablement Steps Explained
excerpt: This Article Describes Windows 11 Telnet Enablement Steps Explained
keywords: Windows 11 Setup Guide,Enabling Telnet (Win11),Win11 Telnet Configuration,Enable Telnet in Win11,Configuring Win11 Telnet,Step by Step Telnet on Win11,Win11 Networking Tools
thumbnail: https://thmb.techidaily.com/d9d28999ab80c3fe303824be9f1e02b9cc335e9a7ef77a5fdd8ceeee3dcb3523.jpg
---

## Windows 11 Telnet Enablement Steps Explained

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
<li><a href="https://windows11.techidaily.com/addressing-razer-device-absence-in-win-1011-via-synapse/"><u>Addressing Razer Device Absence in Win 10/11 via Synapse</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-to-extending-windows-1011-contextual-commands/"><u>Step-by-Step Guide to Extending Windows 10/11 Contextual Commands</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-enhancing-multilingual-reach-adding-subtitles-in-vimeo/"><u>[New] Enhancing Multilingual Reach  Adding Subtitles in Vimeo</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-top-ranked-graphics-cards-for-optimal-online-streaming-quality/"><u>In 2024, Top-Ranked Graphics Cards for Optimal Online Streaming Quality</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-msvcr110dll-absence-a-solution-walkthrough/"><u>Tackling the Msvcr110.dll Absence: A Solution Walkthrough</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-unwanted-hibernation-usb-tweaks-for-windows-11/"><u>Avoid Unwanted Hibernation - USB Tweaks for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/why-sudo-is-revolutionizing-windows-systems/"><u>Why Sudo Is Revolutionizing Windows Systems</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-professional-windows-11-screen-capture-tool/"><u>[Updated] In 2024, Professional Windows 11 Screen Capture Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/taskers-edge-enigma-hidden-processes/"><u>Tasker's Edge Enigma: Hidden Processes?</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-top-12-best-tycoon-games-to-kill-time/"><u>In 2024, Top 12 Best Tycoon Games to Kill Time</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-taking-control-importing-snapchat-snaps-to-your-phones-gallery-for-2024/"><u>[New] Taking Control  Importing Snapchat Snaps to Your Phone's Gallery for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unplugged-no-more-six-methods-to-restore-functioning-network-hardware-on-your-pc/"><u>Unplugged No More: Six Methods to Restore Functioning Network Hardware on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-solve-missing-dll-rockalldlldll-error/"><u>Steps to Solve Missing DLL: Rockalldll.dll Error</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-service-disruptions-with-steam-windows-11-style/"><u>Addressing Service Disruptions with Steam, Windows 11 Style</u></a></li>
<li><a href="https://windows11.techidaily.com/black-friday-extravaganza-save-big-612-forever-win10/"><u>Black Friday Extravaganza: Save Big - $6.12 Forever Win10</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-language-input-change-keyboard-layouts-in-win-11/"><u>Simplifying Language Input: Change Keyboard Layouts in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/utilizing-windows-widgets-for-real-time-resource-tracking/"><u>Utilizing Windows Widgets for Real-Time Resource Tracking</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-could-not-create-vm-problems-in-microsoft-os/"><u>Remedying 'Could Not Create VM' Problems in Microsoft OS</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-continuous-play-fixing-fall-guys-errors-in-windows-os/"><u>Ensuring Continuous Play: Fixing Fall Guys Errors in Windows OS</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-life360-notify-when-you-log-out-on-tecno-phantom-v-flip-drfone-by-drfone-virtual-android/"><u>Does Life360 Notify When You Log Out On Tecno Phantom V Flip? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/time-tinkering-tools-top-windows-programs-for-date-adjustment/"><u>Time Tinkering Tools: Top Windows Programs for Date Adjustment</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-memory-integrity-on-windows-11-methods-77/"><u>Unlocking Memory Integrity on Windows 11: Methods 7/7</u></a></li>
<li><a href="https://windows11.techidaily.com/delaying-windows-11-shutdown-managing-ongoing-processes/"><u>Delaying Windows 11 Shutdown: Managing Ongoing Processes</u></a></li>
<li><a href="https://some-skills.techidaily.com/superior-cameras-for-clear-smooth-podcast-sessions-for-2024/"><u>Superior Cameras for Clear, Smooth Podcast Sessions for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/accurate-assessment-of-system-resources-in-windows-11/"><u>Accurate Assessment of System Resources in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-and-discord-fixing-the-deadly-js-error-quickly/"><u>Win 11 and Discord: Fixing The Deadly JS Error Quickly</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-reverse-engineering-a-youtube-ban/"><u>In 2024, Reverse Engineering a YouTube Ban</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-windows-backup-configuration-recollection/"><u>Steps for Windows Backup Configuration Recollection</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11s-printer-interface-max-48-chars/"><u>Unlocking Windows 11'S Printer Interface (Max 48 Chars)</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-ultimate-checklist-for-installing-vrecorder/"><u>[Updated] 2024 Approved  Ultimate Checklist for Installing VRecorder</u></a></li>
<li><a href="https://windows11.techidaily.com/expedite-photo-corrections-ps-and-windows-strategy/"><u>Expedite Photo Corrections: PS & Windows Strategy</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/how-to-get-windows-photo-viewer-running-smoothly-on-win-11-for-2024/"><u>How to Get Windows Photo Viewer Running Smoothly on Win 11 for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-reset-account-lockout-counter-post-failed-sign-in-attempts/"><u>Adjusting Reset Account Lockout Counter Post-Failed Sign-In Attempts</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-print-guide-to-making-your-powerpoint-shine-on-a-windows-system/"><u>The Ultimate Print Guide to Making Your PowerPoint Shine on a Windows System</u></a></li>
<li><a href="https://extra-hints.techidaily.com/instant-conferencing-zoom-in-the-eyes-of-gmail/"><u>Instant Conferencing  Zoom in the Eyes of Gmail</u></a></li>
<li><a href="https://some-approaches.techidaily.com/total-sphere-camera-systems-for-2024/"><u>Total Sphere Camera Systems for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-5-quick-methods-to-bypass-xiaomi-frp-by-drfone-android/"><u>In 2024, 5 Quick Methods to Bypass Xiaomi FRP</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-updating-obstacles-a-compreeher-guide-to-fixes/"><u>Clearing Updating Obstacles: A Compreeher Guide to Fixes</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-reclaiming-credibility-from-a-youtube-ban/"><u>In 2024, Reclaiming Credibility From a YouTube Ban</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-window-11-safety-with-best-in-class-password-protectors/"><u>Elevating Window 11 Safety with Best-in-Class Password Protectors</u></a></li>
<li><a href="https://windows11.techidaily.com/find-your-windows-11-backdrops-saving-spot/"><u>Find Your Windows 11 Backdrop's Saving Spot</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-streaming-powerhouses-face-off-streamlabs-versus-obs-analysis/"><u>[New] 2024 Approved  Streaming Powerhouses Face-Off  Streamlabs versus OBS Analysis</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-battlenet-accessibility-on-1011-systems/"><u>Unlocking Battle.net Accessibility on 10/11 Systems</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-7-top-ways-to-resolve-apple-id-not-active-issue-for-iphone-xs-max-by-drfone-ios/"><u>In 2024, 7 Top Ways To Resolve Apple ID Not Active Issue For iPhone XS Max</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-frp-on-realme-v30-by-drfone-android/"><u>In 2024, How to Bypass FRP on Realme V30?</u></a></li>
<li><a href="https://extra-resources.techidaily.com/affordable-hd-action-cam-hits-top-list-for-2024/"><u>Affordable HD Action Cam Hits Top List for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-from-play-to-pixels-compreehensive-ps4-recording-with-obs-studio/"><u>In 2024, From Play to Pixels  Compreehensive PS4 Recording with OBS Studio</u></a></li>
<li><a href="https://windows11.techidaily.com/resuscitate-stalled-excel-performance-in-windows-environment/"><u>Resuscitate Stalled Excel Performance in Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/dodging-unsupported-issue-in-windows-5-fixes/"><u>Dodging 'Unsupported' Issue in Windows: 5 Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-speed-of-microsoft-edge-on-win10plus11/"><u>Enhancing Speed of Microsoft Edge on Win10+11</u></a></li>
<li><a href="https://network-issues.techidaily.com/no-picture-on-tv-despite-correct-hdmi-link/"><u>No Picture on TV Despite Correct HDMI Link</u></a></li>
<li><a href="https://windows11.techidaily.com/disarming-the-windows-11-afc-error-camera-app-solution/"><u>Disarming the Windows 11 AFC Error: Camera App Solution</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-optimal-hd-video-memory-creators/"><u>[New] Optimal HD Video Memory Creators</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-the-quickest-way-to-entertain-kapwing-memes/"><u>[Updated] In 2024, The Quickest Way to Entertain - Kapwing Memes</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-concealing-identity-swift-methods-for-picscanner/"><u>2024 Approved  Concealing Identity  Swift Methods for PicScanner</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-the-path-into-windows-11-insider-group/"><u>Discovering the Path Into Windows 11 Insider Group</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-windows-update-fixes-for-error-0x800736cc/"><u>Streamlining Windows Update Fixes for Error 0X800736CC</u></a></li>
<li><a href="https://windows11.techidaily.com/deleting-persistent-epic-launcher-without-hurdles-in-w11/"><u>Deleting Persistent Epic Launcher Without Hurdles in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/file-finder-simplicity-windowed-explorer-reduction-technique/"><u>File Finder Simplicity: Windowed Explorer Reduction Technique</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-tall-screen-editing-made-easy-using-fcpx-on-instagram/"><u>[New] Tall Screen Editing Made Easy  Using FCPX on Instagram</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-unlocking-your-macs-potential-a-beginners-pathway-to-capturing-pristine-audio-for-2024/"><u>Updated Unlocking Your Macs Potential A Beginners Pathway to Capturing Pristine Audio for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-unboxing-high-fidelity-gaming-recorders/"><u>In 2024, Unboxing High-Fidelity Gaming Recorders</u></a></li>
</ul></div>
