---
title: 6 Ways to Fix Network Adapter Not Working in Windows
date: 2024-07-03T11:14:42.348Z
updated: 2024-07-04T11:14:42.348Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 6 Ways to Fix Network Adapter Not Working in Windows
excerpt: This Article Describes 6 Ways to Fix Network Adapter Not Working in Windows
keywords: Windows Network Fixed,Adapter Connectivity Tips,Win Fix Network Errors,Fixing NET Adapter,Connected PC Network,Windows NET Issues,Solve Net Adapter Failure
thumbnail: https://thmb.techidaily.com/7a3b2432a9d08b9e553576af71c0365aa49f025a4ccec0f85070f5a5f457c917.jpg
---

## 6 Ways to Fix Network Adapter Not Working in Windows

 A network adapter is a vital component on your Windows PC that allows you to connect to the internet using both wired and wireless connections. If it stops working for any reason, it can disrupt your ability to use the internet or connect to other devices on your network.

 If you are experiencing the same issue, don't worry. This guide contains some useful troubleshooting tips that should get the network adapter working on your Windows 10 or 11 PC.

## 1\. Check the Network Adapter Status

 Device Manager on Windows makes it easy to view, manage, and update various hardware devices connected to your system. You can use it to examine the status of your network adapter and check if it is encountering any particular errors.

 Here's how you can go about checking the status of your network adapter on Windows.

1. Right-click the **Start icon** or use the **Win + X** keyboard shortcut to open the Power User menu.
2. Select **Device Manager** from the list.
3. Expand **Network adapters**.
4. Right-click on your network adapter and select **Properties**.
5. Select the **General** tab.
6. Check the message under **Device status**.  
![Check Network Adapter Status in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/check-network-adapter-status-in-windows.jpg)

 If you see an error under **Device status**, write it down and then look for solutions to fix that particular error first.

 Is the network adapter entry missing from the Device Manager? If so, you can ask Windows to scan your system's hardware again. To do so, click the **Action** menu in the Device Manager window and select **Scan for hardware changes**.

 Wait for the Device Manager window to detect the network adapter, and then check its status using the steps mentioned above.

## 2\. Run the Network Adapter Troubleshooter

 Your Windows computer comes equipped with a variety of troubleshooters designed to automatically identify and resolve issues. In this case, you can run the Network Adapter troubleshooter to scan your system for any irregularities and fix them.

 To run the network adapter troubleshooter, use these steps:

1. Press **Win + I** to open the Settings app.
2. In the **System** tab, click on **Troubleshoot**.
3. Select **Other troubleshooters**.
4. Click the **Run** button next to the **Network Adapter**.  
![Run the Network Adapter Troubleshooter on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Run-the-Network-Adapter-Troubleshooter-on-Windows.jpg)

 Wait for the troubleshooter to scan your PC and fix any problems. After that, check if the network adapter works fine.

## 3\. Disable and Re-enable the Network Adapter

 This may seem too simple, but disabling and re-enabling the network adapter can help. If it’s just a temporary glitch that’s causing the network adapter to malfunction, this should do the trick.

 To disable and re-enable the network adapter on Windows, use these steps:

1. Press **Win + S** to open the search menu.
2. Type **device manager** in the box and select the first result that appears.
3. Expand **Network adapters**.
4. Right-click on your network adapter and select **Disable device**.
5. Select **Yes** when the confirmation prompt appears.
6. Right-click on the network adapter again and select **Enable device**.  
![Enable Network Adapter Driver on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/enable-network-adapter-driver-on-windows.jpg)

 The Device Manager window will refresh and your network adapter should start working after that.

## 4\. Update or Reinstall the Network Adapter Driver

 The network adapter driver installed on your computer facilitates communication between Windows and your network hardware. If this driver is outdated or malfunctioning, Windows may have difficulty establishing network connections. You can try updating the network adapter driver to see if that gets things moving again.

 Follow these steps to update the network adapter driver on Windows.

1. Press **Win + R** to open the Run dialog box.
2. Type **devmgmt.msc** in the text box and press **Enter** to open the Device Manager.
3. Expand **Network adapters**.
4. Right-click on the problematic device and select **Update driver**.
5. Select the **Search automatically for drivers** option.
6. Click on **Search for updated drivers on Windows Update**.  
![Search for Updated Network Adapter Driver on Windows Update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/search-for-updated-network-adapter-driver-on-windows-update.jpg)

 Windows will now check if any updates are available for your drivers and download them.

 If the problem persists even after updating the network adapter driver, it is likely that the driver is corrupted. In that case, you will need to uninstall the driver from your PC.

 If you need help with that, check out [how to uninstall drivers in Windows](https://www.makeuseof.com/windows-11-uninstall-drivers/). After removing the driver, restart your PC, and Windows will automatically reinstall the missing driver during boot.

## 5\. Reset the Winsock Catalog

 Winsock (short for Windows Sockets) is a programming interface that allows your apps and programs to communicate with network protocols and services. If there’s an issue with this program, you could experience various network-related problems, including the one discussed here.

 You can try resetting the Winsock data on your PC to see if that restores normalcy. To do so, use these steps:

1. Press **Win + S** to open the search menu.
2. Type **Windows PowerShell** in the text box and select **Run as administrator**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Type the following command in the console and press **Enter**.  
`netsh winsock reset`  
![Winsock Reset Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/winsock-reset-command.jpg)

[Restart your PC](https://www.makeuseof.com/windows-restart-methods/) after running the above command to complete the reset process. After that, the network adapter should work as before on your Windows computer.

## 6\. Try Generic Fixes

 If you are here, it’s safe to assume that none of the above tips have helped. In that case, you can try some generic fixes to see if they work.

* **Install Windows Updates:** A buggy or outdated Windows build could cause the network adapter to stop working on your PC. Try [installing any pending Windows updates](https://www.makeuseof.com/update-windows-manually/) and see if that fixes the issue.
* **Turn Off VPN:** At times, using a VPN connection can contribute to such network-related issues. Try disabling your VPN temporarily and see if that solves the problem.
* **Reset Network Settings:** Another thing you can do to fix this particular issue is [reset the network settings on Windows](https://www.makeuseof.com/reset-network-settings-windows-11/). Doing so will restore all network settings on your PC to their original default configurations, effectively resolving any present issues.
* **Perform a System Restore:** Recent modifications to your system might be responsible for the network adapter malfunction. If that’s the case, you can [use system restore to revert Windows](https://www.makeuseof.com/use-system-restore-windows/) to its earlier state and undo any bad changes.

## Get the Network Adapter Working on Your Windows Computer

 Without a clear indication of what’s wrong, troubleshooting your network adapter can be tricky. However, following the solutions listed above should make the process a little easier.

 Once the network adapter starts working again, consider making some minor tweaks to improve your PC’s internet connection speed.

 If you are experiencing the same issue, don't worry. This guide contains some useful troubleshooting tips that should get the network adapter working on your Windows 10 or 11 PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/9-ways-to-fix-windows-hello-fingerprint-recognition-not-working/"><u>9 Ways to Fix Windows Hello Fingerprint Recognition Not Working</u></a></li>
<li><a href="https://windows11.techidaily.com/1719327539921-master-the-art-of-microsoft-support-for-problems/"><u>Master the Art of Microsoft Support for Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/jumpstart-your-system-reviving-windows-11s-error-detection/"><u>Jumpstart Your System: Reviving Windows 11'S Error Detection</u></a></li>
<li><a href="https://windows11.techidaily.com/configure-ideal-window-space-for-your-apps-in-win11/"><u>Configure Ideal Window Space for Your Apps in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-external-monitors-without-graphics-card/"><u>Enabling External Monitors without Graphics Card</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-virtualbox-0x80004005-failure-on-windows-pcs/"><u>Addressing VirtualBox 0X80004005 Failure on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/7-things-to-try-when-the-epic-games-launcher-fails-to-send-a-security-code-on-windows/"><u>7 Things to Try When the Epic Games Launcher Fails to Send a Security Code on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-no-supported-devices-found-in-windows-11/"><u>Overcoming No Supported Devices Found in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/bluetooth-recovery-guide-9-steps-to-patch-up-your-pcs-link/"><u>Bluetooth Recovery Guide: 9 Steps to Patch Up Your PC's Link</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/what-is-ai-voice-wondershare-virbo-glossary-for-2024/"><u>What Is AI Voice? | Wondershare Virbo Glossary for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-harness-filmora-transforming-your-tiktok-react-videos-instantly/"><u>[New] In 2024, Harness Filmora  Transforming Your TikTok React Videos Instantly</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-cultivating-productive-collaboration-a-pathway-to-effective-collab-videos/"><u>In 2024, Cultivating Productive Collaboration  A Pathway to Effective Collab Videos</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-from-recordings-to-live-streaming-on-youtube-and-twitch-with-obs/"><u>[New] 2024 Approved  From Recordings to Live  Streaming on YouTube & Twitch with OBS</u></a></li>
<li><a href="https://review-topics.techidaily.com/insert-signature-in-word-2007-by-ldigisigner-sign-a-word-sign-a-word/"><u>Insert signature in Word 2007</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-check-distance-and-radius-on-google-maps-for-your-asus-rog-phone-8-pro-drfone-by-drfone-virtual-android/"><u>How to Check Distance and Radius on Google Maps For your Asus ROG Phone 8 Pro | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-fast-favorites-todays-highest-youtube-tracks/"><u>[New] 2024 Approved  Fast Favorites  Today's Highest Youtube Tracks</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-the-power-of-virality-enhancing-brand-presence-on-tiktok/"><u>[New] The Power of Virality  Enhancing Brand Presence on TikTok</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/how-to-turn-mundane-games-into-epic-scenes/"><u>How to Turn Mundane Games Into Epic Scenes</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-your-xiaomi-redmi-k70-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>How to Mirror Your Xiaomi Redmi K70 Screen to PC with Chromecast | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>