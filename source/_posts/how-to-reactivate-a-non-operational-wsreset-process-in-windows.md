---
title: How to Reactivate a Non-Operational WSReset Process in Windows
date: 2024-06-25T11:59:24.612Z
updated: 2024-06-26T11:59:24.612Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Reactivate a Non-Operational WSReset Process in Windows
excerpt: This Article Describes How to Reactivate a Non-Operational WSReset Process in Windows
keywords: Reactivate WSReset,Reset Windows Fixing,WinReset Restart Guide,Revive Windows Reset,Non-Operational WinReset,Activate Dormant Reset,Reactivate Locked Process
thumbnail: https://thmb.techidaily.com/667b327336657b37d917ada8179b0c23c67339c9f07504ad9ddbf600b0c76aae.jpg
---

## How to Reactivate a Non-Operational WSReset Process in Windows

 WSReset.exe is an essential command line tool delivered with Windows to perform various tasks and troubleshoot issues. It resets the Windows application store and clears cache issues that may result in slow performance or errors.

 However, if you encounter problems with WSReset.exe or receive frequent errors, your computer may have an underlying issue that needs to be addressed. This article offers guidance on troubleshooting and fixing WSReset.

## How to Fix WSReset.exe Not Working on Windows

 Before you troubleshoot, let's see what WSReset.exe is used for. The WSReset.exe program resets Windows Store and clears any cache issues that might cause errors. It troubleshoots problems with the Windows Store and applications, including those that are not downloading or launching properly.

 Now let's move on to troubleshooting.

## 1\. Run WSReset.exe as an Administrator

 WSReset.exe requires administrative privileges to run properly. If you're not running it as an administrator, it may fail to reset the Windows Store cache.

 To resolve this issue, [ensure you're using a Windows admin account](https://www.makeuseof.com/check-windows-account-admin-rights/), then try running WSReset.exe again.

## 2\. Run the Windows Store App Troubleshooter

 This problem also appears due to corrupt system files or Windows Store application issues. To fix these issues, Windows offers an embedded troubleshooter that identifies and resolves problems with the Store app.

 To run the troubleshooter, use the steps below.

1. Press **Win + I** on your keyboard to open the Settings menu.
2. Select **System** from the left sidebar.
3. In the right pane, click **Troubleshoot > Other troubleshooters**.  
![Other troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/other-troubleshooters.jpg)
4. On the troubleshooter page, scroll down to **Windows Store Apps** and click **Run**.  
![Run Windows Store Apps Troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-windows-store-apps-troubleshooter.jpg)

 As the troubleshooter scans, it detects and fixes any existing issues. Once that's done, restart your computer again and try running WSReset.exe again.

 If you use Windows 10 version, the process will be slightly different. Press **Win + R**, type **ms-settings:troubleshoot**, and hit Enter. In the Settings menu, click **Update & Security** \> **Troubleshoot** \> **Additional troubleshooters**.

![Windows Additional Troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Windows-Additional-Troubleshooters.jpg)

 Select **Windows Store Apps** from the list and click **Run the troubleshooter**.

## 3\. Repair and Reset Windows Store

 If WSReset.exe is still not working, chances are the Windows Store app might be corrupted or not functioning correctly. In that case, try [repairing and resetting the Windows Store](https://www.makeuseof.com/windows-10-11-reset-microsoft-store/). This will restore the application to its default settings and often solves errors

## 4\. Remove the Latest Windows Updates

 Although Microsoft releases regular Windows updates to improve overall system performance, sometimes these updates cause problems instead. WSReset.exe not working is one such issue related to a recent Windows update.

 Therefore, if you’ve recently applied any updates and are now facing issues with WSReset.exe, remove the update and see if this resolves the issue.

1. Press **Win + S** on your keyboard to open the search box.
2. Type **Control Panel** in the search box and select it from the results list.
3. Then navigate to **Programs** \> **Programs and Features** \> **Uninstall a program**.
4. From the left sidebar, select **View installed updates**. This will open the Settings window with the list of applied Windows updates.
5. Now look for the recent update and click **Uninstall** next to it.  
![Uninstall Windows Updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/uninstall-windows-updates.jpg)
6. Click **Uninstall** again when prompted.

 Follow the onscreen instructions and restart your computer when it's done.

## 5\. Clear the Microsoft Store Cache via the Registry

 If you're still having issues with WSReset.exe, clear the Microsoft Store cache via the registry. This wipes out temporary files, settings, or preferences that may cause this issue.

 It is a complex process for those unfamiliar with registry changes, as incorrect settings could cause major problems. However, if done correctly, this flushes the cache and solves WSReset.exe errors. To avoid data loss, back up your registry and be cautious when modifying it.

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **cmd** in the text field and press **Ctrl + Shift + Enter**. This will open the Command Prompt window with administrative privileges.
3. If the UAC prompt appears, select **Yes** to continue.
4. In the Command Prompt window, type the following command and press Enter:  
`wmic useraccount get name,sid`
5. Running this command will list all user accounts on your computer. Find the SID of your user account and copy it.  
![List all user account via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/list-all-user-account-via-command-prompt.jpg)
6. Next, open the Registry Editor. For this, click on **Start** \> type **regedit** in the search box, then select it from the results list.
7. If the UAC pop-up appears, click **Yes** to continue.
8. When the Registry Editor opens, navigate to the following registry key:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Appx\AppxAllUserStore`  
 You can also paste this path into the Registry Editor's address bar and press Enter. This will direct you to the AppxAllUserStore registry key.
9. In the **AppxAllUserStore** key, find the **SID** you copied earlier.  
![Clear the Microsoft Store Cache via the Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/clear-the-microsoft-store-cache-via-the-registry.jpg)
10. Right-click on it and select **Delete**.
11. If a confirmation pop-up appears, click **Yes**. This will clear the Microsoft Store cache.
12. Close the Registry Editor and restart your PC.

 Now, open the Command Prompt window with administrative privileges again and run WSReset.exe to see if it works properly. If so, you have successfully cleared the Microsoft Store cache via the registry.

## 6\. Reinstall the Microsoft Store

 Sometimes Windows Store files are corrupted or damaged. This may require you to [reinstall the Microsoft Store app](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/). The process replaces corrupted or missing files and prevents WSReset.exe from malfunctioning.

## 7\. Try Some Generic Fixes

 There are also some general solutions that work in various scenarios. These include [running a malware scan on your system](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) or [creating a new user account](https://www.makeuseof.com/windows-11-create-local-user-account/) and switching to it.

 If you're still encountering WSReset.exe errors, [restart your Windows computer](https://www.makeuseof.com/windows-restart-methods/). It refreshes your computer's memory and cleans out temporary files or settings.

 You could also [run System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) to fix errors and replace corrupt files. If none of the above-mentioned steps work, [perform a system restore](https://www.makeuseof.com/use-system-restore-windows/) and restore your computer to an earlier point when it was working fine.

## Resolving the WSReset.exe Issue on Windows

 Today WSReset.exe is a well-known tool among Windows users. Despite being simple, this can be tricky to troubleshoot if it fails to reset or clear the Windows Store. Hopefully, it's just a system glitch, and you can fix the problem using the suggestions provided in this article.

 However, if you encounter problems with WSReset.exe or receive frequent errors, your computer may have an underlying issue that needs to be addressed. This article offers guidance on troubleshooting and fixing WSReset.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/solutions-for-taskbar-transparency-in-maxed-browser-screens/"><u>Solutions for Taskbar Transparency in Maxed Browser Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windowed-play-top-6-windows-11-fps-counters/"><u>Mastering Windowed Play: Top 6 Windows 11 FPS Counters</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-change-the-task-manager-start-page-in-windows-11/"><u>How to Change the Task Manager Start Page in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tweaking-netconfigs-windows-11-edition/"><u>Tweaking NetConfigs: Windows 11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-overcoming-printer-not-connected-problems/"><u>Win11: Overcoming Printer Not Connected Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/reducing-heavy-resource-use-by-news-apps-in-windows-os/"><u>Reducing Heavy Resource Use by News Apps in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-disconnection-problem-for-malwarebytes-in-windows-11/"><u>Fixing the Disconnection Problem for Malwarebytes in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/easily-identify-last-opened-files-in-windows-explorer/"><u>Easily Identify Last Opened Files in Windows Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-11s-registry-a-guide-to-its-components/"><u>Unveiling Windows 11'S Registry: A Guide to Its Components</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-guide-to-perfect-everyday-tiktok-footage-expert-advice/"><u>2024 Approved  Guide to Perfect Everyday TikTok Footage  Expert Advice</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-screen-sharing-showdown-obs-vs-twitch-studio-face-off-for-2024/"><u>[New] Screen Sharing Showdown  OBS vs Twitch Studio Face-Off for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-create-dramatic-effects-top-strategies-for-epic-gopro-videos/"><u>[Updated] Create Dramatic Effects  Top Strategies for Epic GoPro Videos</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-a-lost-oppo-a2-for-free-drfone-by-drfone-virtual-android/"><u>How to Track a Lost Oppo A2 for Free? | Dr.fone</u></a></li>
<li><a href="https://youtube-web.techidaily.com/arch-of-success-pivotal-youtube-gatherings-after-vidcon-for-2024/"><u>In Search of Success  Pivotal YouTube Gatherings (After VidCon) for 2024</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-apple-id-is-greyed-out-from-iphone-14-plus-how-to-bypass-by-drfone-ios/"><u>In 2024, Apple ID is Greyed Out From iPhone 14 Plus How to Bypass?</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-brighten-and-sharpen-expert-tips-for-v22-video-enhancement/"><u>2024 Approved  Brighten and Sharpen  Expert Tips for V2.2 Video Enhancement</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/free-top-8-best-apps-to-get-likes-on-instagram/"><u>FREE Top 8 Best Apps to Get Likes on Instagram</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-efficient-use-of-obs-studio-for-android-devices-for-2024/"><u>[New] Efficient Use of OBS Studio for Android Devices for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-your-asus-rog-phone-8-location-on-twitter-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change your Asus ROG Phone 8 Location on Twitter | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>