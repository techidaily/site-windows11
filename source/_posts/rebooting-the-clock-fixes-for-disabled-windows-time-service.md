---
title: "Rebooting the Clock: Fixes for Disabled Windows Time Service"
date: 2024-09-05T02:11:44.426Z
updated: 2024-09-06T02:11:44.426Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Rebooting the Clock: Fixes for Disabled Windows Time Service"
excerpt: "This Article Describes Rebooting the Clock: Fixes for Disabled Windows Time Service"
keywords: Windows Time Fix Guide,TimeService Reboot Help,Disable Windows Time Error,Windows Time Service Troubleshooting,Clock Fix for WindoWS,Restart Time Service on PC,Reset Windows Time Settings
thumbnail: https://thmb.techidaily.com/55d1895b35f08f3d82ecb412a2b84639eef0d00ef22964bfc70576f31a7b8bbc.jpg
---

## Rebooting the Clock: Fixes for Disabled Windows Time Service

 Start your Windows computer and notice that the time is wrong. It might be a minor issue, or you accidentally changed the setting. But what if Windows Time Service is missing entirely?

 Fortunately, restoring the Windows Time Service is not complicated. This guide will discuss quickly restoring the missing Windows Time Service and setting the correct time on your computer.

## 1\. Reboot Your PC

 Restart your computer before attempting any major troubleshooting. While it may sound simple, restarting the computer resolves minor errors and glitches that prevent the service from running. It flushes out temporary files and refreshes the operating system to ensure everything works correctly.

1. Press **Alt + F4** to bring up the Shutdown dialog
2. Select **Restart** from the drop-down menu and then hit **OK**.

 Once the computer restarts, check if Windows Time Service is available. If it's still missing, move on to the next step.

## 2\. Change the Time Server

 If restarting the computer does not work, you must change the time server. Changing the time server synchronizes your system clock with an online one, displaying your computer's correct date and time.

 Follow the steps to change the time server:

1. Press the **Windows key** to open the Start Menu.
2. Type **control panel** in the search box and click the result. This opens the Control Panel window.
3. Select **View by: Large icons** and click **Date and Time**.
4. Switch to the **Internet Time** tab and click **Change settings**.
5. Check the **Synchronize with an Internet time server** box and select a time server from the drop-down menu.  
![Change the Time Server](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/change-the-time-server.jpg)
6. Click the **Update now** button to synchronize your computer with the time server.
7. Once completed, click **OK** to save the changes and exit.

 After these steps, you should see the Windows Time Service running on your system. Check the time to ensure it is correct and make further adjustments.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997635/19272" target="_top" id="1997635">
  <img src="//a.impactradius-go.com/display-ad/19272-1997635" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997635/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Add More Time Servers

 If the Windows Time Service is still missing, you can try adding more time servers to the list. Multiple time servers increase the chance of finding an active server and keeping your system in sync. If one server goes down, your computer can automatically switch to another.

 The solution requires editing the Windows registry. Even a small mistake can damage your system, so proceed with caution. To avoid data loss, [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing.

 To add time servers, do the following:

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the dialog box and click **OK**.
3. If the UAC window pops up on the screen, click **Yes** to grant permission.
4. In the Registry Editor window, navigate to the following directory.  
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\DateTime\Servers  
 Copy and paste the path into the Registry Editor address bar and press Enter. This will take you to the Location key.
5. From the left navigation panel, right-click the Servers folder and select **New** \> **String Value**.  
![Add More Time Servers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/add-more-time-servers.jpg)
6. Name the new value **Server N**, and replace **N** with a number starting from 1.  
 You can't have the same number twice. That means if there are already 3 values named _Server 1_, _Server 2_, and _Server 3_, you must call the new one as **Server 4**.
7. Double-click the newly created value and add a time server address in the Value data field.
8. Here are some time server addresses:  
`time.windows.com  

time.nist.gov  

time-a-wwv.nist.gov  

time-c-wwv.nist.gov  

ntp-wwv.nist.gov`

 After adding the time server, click **OK** and close the Registry Editor window. Now restart your computer to apply the changes and check if Windows Time Service is available.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049370/7443" target="_top" id="2049370">
  <img src="//a.impactradius-go.com/display-ad/7443-2049370" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049370/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Re-register the Windows Time Service

 If the above steps fail, you can try re-registering the Windows Time Service. Re-registering a service refreshes its configuration and forces it to start again. Doing this may fix the missing Windows Time Service and recover clock synchronization.

 To re-register the Windows Time Service, follow these steps:

1. Press the **Win + S** keys to open the Windows Search.
2. Type **cmd** in the search box and simultaneously press **Ctrl + Shift + Enter**. This opens the Command Prompt with administrative privileges.
3. If the UAC window pops up, click **Yes** to grant permission.
4. Type the following command in the Command Prompt and press Enter:  
net stop w32time
5. This command will stop the Windows Time Service. Now type the following command to unregister the service and press **Enter**:  
w32tm /unregister
6. After that, run the following command to register the service:  
w32tm /register
7. Next, type the following command and hit **Enter**. This starts the Windows Time Service.  
net start w32time

 After performing these steps, close the Command Prompt window and restart your system. You should see that the Windows Time Service is running, and your clock syncs with the time server.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137380/7443" target="_top" id="2137380">
  <img src="//a.impactradius-go.com/display-ad/7443-2137380" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137380/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Repair Corrupted System Files

![SFC Command Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/sfc-command-preview.jpg)

 Corrupt system files can also cause Windows services to fail. So, if the Windows Time Service is still missing, try repairing corrupt system files. You can do this using the System File Checker tool. This tool scans your system for missing files and repairs the errors it finds.

 Wait for the scan to complete, and restart your computer. After that, check if the Windows Time Service is still missing. If it is, try running the Deployment Image Servicing and Management tool. This tool repairs corrupted system files and restores your Windows installation's health.

 If you're not sure how to run either of these tools, check out how to repair corrupt Windows files with its built-in tools for instructions.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094480/7443" target="_top" id="2094480">
  <img src="//a.impactradius-go.com/display-ad/7443-2094480" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094480/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Scan for Malware

 Sometimes, malware is to blame for Windows services acting a little odd. As such, it's worth [running a full system scan](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) and removing all detected threats.

![Full Scan Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-scan-windows-security.jpg)

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/798165/11305" target="_top" id="798165">
  <img src="//a.impactradius-go.com/display-ad/11305-798165" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i110150.net/i/5597632/798165/11305" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If you feel your PC isn't as secure as it could be, you could try downloading one of the [best antivirus apps for Windows](http://www.makeuseof.com/windows-11-antivirus-apps/). These will both actively block malicious program from installing themselves on your PC, and remove any that are currently infesting your computer.

 For those who prefer a command-line approach, you can [use Windows PowerShell to scan Windows for malware](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/).

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037359/7443" target="_top" id="2037359">
  <img src="//a.impactradius-go.com/display-ad/7443-2037359" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037359/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Restore the Missing Windows Time Service

 Hopefully, one or more of these tips worked for you. Missing Windows services can be a huge pain, but hopefully, one of these methods has brought back the Windows Time Service back to working order.

 Fortunately, restoring the Windows Time Service is not complicated. This guide will discuss quickly restoring the missing Windows Time Service and setting the correct time on your computer.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-foundations-of-easing-volume-control-in-audition/"><u>[New] 2024 Approved  Foundations of Easing Volume Control in Audition</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-leading-the-video-conversion-game-with-ipv-strategies/"><u>[New] 2024 Approved  Leading the Video Conversion Game with IPV Strategies</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-follower-fallout-on-instagram-how-to-spot-it/"><u>[Updated] 2024 Approved  Follower Fallout on Instagram  How to Spot It</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-selective-complementary-items-for-outstanding-gopros/"><u>2024 Approved  Selective Complementary Items for Outstanding GoPros</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-easy-ways-to-copy-contacts-from-realme-12-proplus-5g-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Easy Ways to Copy Contacts from Realme 12 Pro+ 5G to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-7-innovative-fixes-for-rename-issue-in-win-11/"><u>Expert Advice: 7 Innovative Fixes for Rename Issue in Win 11</u></a></li>
<li><a href="https://tech-hub.techidaily.com/explore-the-fresh-capabilities-now-available-in-chatgpt/"><u>Explore the Fresh Capabilities Now Available in ChatGPT</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-silence-your-license-will-end-soon-warning-on-woses/"><u>How To Silence Your License Will End Soon Warning on WOSes</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-cards-of-samsung-galaxy-z-fold-5-without-puk-codes-by-drfone-android/"><u>How To Unlock SIM Cards Of Samsung Galaxy Z Fold 5 Without PUK Codes</u></a></li>
<li><a href="https://windows11.techidaily.com/implementing-access-barriers-for-insiders-in-windows-11/"><u>Implementing Access Barriers for Insiders in Windows 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-4-most-known-ways-to-find-someone-on-tinder-for-tecno-pova-6-pro-5g-by-name-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Most-Known Ways to Find Someone on Tinder For Tecno Pova 6 Pro 5G by Name | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-mastering-lock-screen-settings-how-to-enable-and-disable-on-oppo-a79-5g-by-drfone-android/"><u>In 2024, Mastering Lock Screen Settings How to Enable and Disable on Oppo A79 5G</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-top-7-grand-strategy-masterpieces-for-epic-battles/"><u>In 2024, Top 7 Grand Strategy Masterpieces for Epic Battles</u></a></li>
<li><a href="https://windows11.techidaily.com/journey-to-windows-11-in-apples-ecosystem-with-parallels/"><u>Journey to Windows 11 in Apple's Ecosystem with Parallels</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/key-steps-to-preserve-and-broadcast-live-sports-successfully/"><u>Key Steps to Preserve & Broadcast Live Sports Successfully</u></a></li>
<li><a href="https://screen-capture.techidaily.com/mac-studio-screen-and-sounds-recording-feature-for-2024/"><u>Mac Studio  Screen & Sounds Recording Feature for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-clutter-free-windows-desktop/"><u>Master the Art of Clutter-Free Windows Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-computer-crisis-management-with-tools/"><u>Mastering Computer Crisis Management with Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-secure-file-management-using-powertoys/"><u>Mastery of Secure File Management Using PowerToys</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/mighty-thor-returns-odins-vow-for-2024/"><u>Mighty Thor Returns  Odin’s Vow for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/minimize-lag-troubleshooting-windows-extended-monitor-use/"><u>Minimize Lag: Troubleshooting Windows Extended Monitor Use</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-imessage-on-non-ios-devices-tips-and-tricks/"><u>Navigating iMessage on Non-iOS Devices: Tips and Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-common-spotify-connectivity-snags/"><u>Navigating Through Common Spotify Connectivity Snags</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-how-to-comment-on-youtube-live-chat/"><u>New 2024 Approved How to Comment on YouTube Live Chat</u></a></li>
<li><a href="https://windows11.techidaily.com/pinpoint-public-ip-with-commands-windows-edition/"><u>Pinpoint Public IP with Commands, Windows Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/propel-windows-video-workflow-adopt-distributed-power-by-tdarr-technology/"><u>Propel Window's Video Workflow: Adopt Distributed Power by Tdarr Technology</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivating-hidden-remove-pin-switch-on-windows-11/"><u>Reactivating Hidden Remove PIN Switch on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-missing-update-files-issue-error-code-0x80070003-in-windows/"><u>Resolving Missing Update Files Issue (Error Code 0X80070003) in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-unfunctional-enter-key-in-windows-os/"><u>Resolving Unfunctional Enter Key in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/smart-strategies-for-merging-content-on-win-11/"><u>Smart Strategies for Merging Content on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategic-approaches-to-shutting-down-your-computer/"><u>Strategic Approaches to Shutting Down Your Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-thx-not-responding-to-windows-commands/"><u>Tackling THX Not Responding to Windows Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/testing-your-mic-a-windows-procedure/"><u>Testing Your Mic: A Windows Procedure</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/three-ways-to-sim-unlock-oppo-reno-9a-by-drfone-android/"><u>Three Ways to Sim Unlock Oppo Reno 9A</u></a></li>
<li><a href="https://windows11.techidaily.com/triumph-over-glitches-the-ultimate-guide-for-eradicating-error-0x800700e9-on-xbox-game-pass-and-windows-11/"><u>Triumph Over Glitches: The Ultimate Guide for Eradicating Error 0X800700E9 on Xbox Game Pass & Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-steam-error-in-games-on-latest-windows-os/"><u>Troubleshooting Steam Error in Games on Latest Windows OS</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-music-from-xiaomi-redmi-note-12r-by-fonelab-android-recover-music/"><u>Undelete lost music from Xiaomi Redmi Note 12R</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-crossed-out-icons-their-purpose-and-meaning/"><u>Understanding Crossed Out Icons: Their Purpose and Meaning</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-whisper-techniques-concealing-commands-effectively/"><u>Window's Whisper Techniques: Concealing Commands Effectively</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>