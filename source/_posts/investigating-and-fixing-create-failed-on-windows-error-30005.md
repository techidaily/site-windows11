---
title: Investigating and Fixing Create Failed on Windows Error 30005
date: 2024-07-11T21:22:45.090Z
updated: 2024-07-12T21:22:45.090Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Investigating and Fixing Create Failed on Windows Error 30005
excerpt: This Article Describes Investigating and Fixing Create Failed on Windows Error 30005
keywords: Window Error 30005,WinError3K,WINDOWS Troubleshooting,FileCreationFailure,WindowsErrorSolution,SystemFileCorrection,DebuggingWindowsIssue
thumbnail: https://thmb.techidaily.com/afcb9c2878394644f41c39d4475ac640d665c752413696b921520d8ad80368e6.jpg
---

## Investigating and Fixing Create Failed on Windows Error 30005

 When you launch a game on your PC or Steam client, do you encounter a message that reads "error 30005: CreateFile failed with 32"? It mostly occurs when running games protected by Easy Anti-Cheat, an anti-cheat service used by multiplayer games to prevent hacking.

 If you have encountered this error, you're probably trying to run a game protected by this service, but there is some issue with the service itself or game files, which is preventing the game from launching.

 So, what causes this error, and how do you fix it?

## What Causes the Error 30005: CreateFile Failed With 32 on Windows?

 Here are a few major causes that may have resulted in the "error 30005: CreateFile failed with 32" issue on your device:

* A hack you've installed altered the game files, which Easy Anti-Cheat deemed suspicious.
* Your game files have been corrupted, and Easy Anti-Cheat has flagged these changes as unauthorized.
* The Easy Anti-Cheat service is being blocked by Windows Defender or antivirus software.
* Easy Anti-Cheat has failed to create the file in its installation folder since the file from the previous session already exists.
* You have mistakenly disabled the Easy Anti-Cheat process or service to reduce its resource consumption.
* The Easy Anti-Cheat software installation has been corrupted and requires repair or a fresh reinstallation.

 Now that you know why you might be experiencing this error, let's discuss how you can fix it.

## 1\. First, Perform Some Preliminary Checks

 You should first perform the following preliminary checks before moving on to the main fixes:

* Are you using any hacking software of files to gain an advantage in the game? If so, you should remove them.
* Close any other program running alongside the game.
* Close any graphics optimization software you are using.
* Have you made any modifications to the game files? If you've done any, you should reinstall the game unless you know how to reverse these changes.

 You can begin applying the remaining fixes if none of the above checks help.

## 2\. Delete the EasyAntiCheat.Sys File

 The EasyAntiCheat.sys file contains the launch information for the game. Every time you launch the game, and the Easy Anti-Cheat service confirms that the game files have not been modified, it gets created automatically.

 In most cases, Easy Anti-Cheat creates this file successfully; occasionally, it fails. When that happens, the game displays this error message. To ensure that's not the case here, you'll have to delete this file manually, so Easy Anti-Cheat can recreate it when you relaunch the game.

 To do this, follow these steps:

1. Go to the directory folder of the game you're having trouble with. Most of the time, you will find it in a subfolder of the **Program Files (x86)** folder on the drive where your operating system is installed.
2. Open the **EasyAntiCheat** or **EasyAntiCheat\_EOS** folder.
3. Locate the **EasyAntiCheat.sys** or **EasyAntiCheat\_EOS.sys** file in the folder.
4. To delete the file, right-click on it and select **Delete**.  
![Deleting the EasyAntiCheat.Sys File in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/1-deleting-the-easyanticheat-sys-file-in-windows-file-explorer.jpg)
5. Grant administrator permission if it is requested in the UAC window.
6. Relaunch the game.

 If you encounter the same error again, proceed to the next step.

### Can't Uninstall the EasyAntiCheat.Sys File?

 Some users have reported encountering an error when deleting the EasyAntiCheat.sys file that says that the file cannot be deleted since the app is running. This message indicates that Easy Anti-Cheat is running in the background, so you must turn off the program before uninstalling it. Here's how you can do it:

1. Right-click the Windows **Start** button and select **Task Manager**.
2. Locate Easy Anti-Cheat in the list of running processes.
3. Right-click the process and select **End task**.  
![Disable EasyAntiCheat Software in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disable-easyanticheat-priority.jpg)

## 3\. Repair Any Corrupted Game Files

 If your game files get corrupted, Easy Anti-Cheat will consider it unauthorized tampering. Therefore, repairing them is essential. Some game clients allow you to repair corrupt files from within the client; therefore, if the game you're running offers this functionality, go ahead and repair the corrupt files.

 If you have installed the game through Steam, you can repair your game files more easily. In our guide on [repairing game files using different launchers](https://www.makeuseof.com/how-to-verify-game-file-integrity-different-launchers/#how-to-verify-game-file-integrity-on-steam), we have covered the process for verifying the integrity of game files (or fixing corrupt game files) in Steam. So, follow the relevant instructions to repair corrupt files.

## 4\. Whitelist Easy Anti-Cheat in Windows Defender or Antivirus

 Even though Easy Anti-Cheat is a trusted service, Microsoft Defender or antivirus software you use may consider it a threat and block it. Once blocked, Easy Anti-Cheat won't be able to create the file it needs to, and the game launcher will display this error. Therefore, you should ensure it isn't the cause of the problem.

 Disable both programs to determine if Windows Defender or an antivirus program is causing the problem. Check out our guide on [how to disable Windows Defender](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/). There should be a similar option in your antivirus program's settings. Use that to disable it. Once both programs have been disabled, run the game again and see if the error occurs.

 If the game launches successfully this time, that confirms the problem lies with Windows Defender or a third-party antivirus program that you're using. If you don't enable either of these programs, you won't encounter this error again, but disabling them puts your device at risk.

 So, instead of doing that, you should whitelist Easy Anti-Cheat from Windows Defender and your antivirus program. Doing so will prevent either of these apps from blocking the Easy Anti-Cheat program, and both apps will continue to do their job of catching viruses.

 If you aren't familiar with the process to whitelist apps, check out our guide on [how to allow apps through Windows Firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/). Likewise, visit the official website of the antivirus you're using. There, you'll find the instructions to whitelist apps in that particular software.

## 5\. Disable Kernel-Mode Hardware-Enforced Stack Protection

 Activating Kernel-mode Hardware-enforced Stack Protection, a security feature on Windows, interferes with Easy Anti-Cheat software, as reported by a user in a [Microsoft Community forum](https://answers.microsoft.com/en-us/windows/forum/all/kernel-mode-hardware-enforced-stack-protection/e6a47f27-fd08-4ce1-bc64-ecc4306182d3). This feature prevents malicious software from interfering with the operating system but can sometimes conflict with safe programs, such as Easy Anti-Cheat.

 One user confirmed in a [Reddit thread](https://www.reddit.com/r/lostarkgame/comments/qn2utd/fix%5Ffor%5Feasyanticheat%5Ferror%5F30005%5Fcreate%5Ffile/) that turning off this security feature fixed the problem. If your processor supports this security feature, turn it off. Here's how you can do that:

1. Type **"Windows Security"** in Windows Search and open the **Windows Security** app.
2. Navigate to the **Device Security** tab in the left sidebar.
3. Click **Core isolation** in the right-hand pane.
4. Turn off the toggle under **Kernel-mode Hardware-enforced Stack Protection**.  
![Disable Kernel-mode Hardware-enforced Stack Protection in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disable-kernel-mode-hardware-enforced-stack-protection-in-windows-security.jpg)
5. Reboot your device.

 If the Kernel-mode Hardware-enforced Stack Protection feature isn't available in the Device Security settings, then your processor doesn't support it. If that is the case, you can skip this fix.

## 6\. Ensure the Easy Anti-Cheat Service Is Running

 Easy Anti-Cheat launches a service also named Easy Anti-Cheat when you install the program on your device. If this service isn't running, Easy Anti-Cheat will throw an error. To do so, follow these steps:

1. Open the **Services** app by typing **"Services"** in Windows Search.
2. Find the **Easy Anti-Cheat** service.
3. If it is already running, you don't need to do anything. If it isn't running already, right-click on it and click **Start**.

## 7\. Repair the Easy Anti-Cheat Program

 If none of the fixes work or the Easy Anti-Cheat software isn't working correctly, you should repair the program. Follow these steps to repair the client:

1. Go to the installation folder of your game. If you have installed the game through Steam, open the Steam client, right-click on the game, and select **Properties**. Choose **Local Files** from the left sidebar and click **Browse** on the right.  
![Clicking on the Browse Button in Local Files Tab in the Properties Window of a Game in Steam Client](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/3-clicking-on-the-browse-button-in-local-files-tab-in-the-properties-window-of-a-game-in-steam-client.jpg)
2. Close the Steam client and keep the installation folder open.
3. Go to the **Easy Anti-Cheat** folder.
4. Run the Easy Anti-Cheat setup file.  
![Running the Easy Anti-Cheat Setup File From Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/4-running-the-easy-anti-cheat-setup-file-from-windows-file-explorer.jpg)
5. In the UAC window, click **Yes**.
6. Click on **Repair Service**.  
![Repairing the Easy Anti-Cheat Service on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/easy-anticheat-software.jpg)
7. After that, click **Finish** and run the game.

## 8\. Reinstall Easy Anti-Cheat

 If you encounter the same error when you run the game again, it indicates that the issue has not been resolved. So, reinstall the Easy Anti-Cheat program as a last resort.

 To do that, follow the same steps explained above and run the Easy Anti-Cheat setup file again. Then, instead of clicking on **Repair**, click on **Uninstall** in the bottom-left corner.

![Uninstalling the Easy Anti-Cheat in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/uninstalling-the-easy-anti-cheat-in-windows-11.jpg)

 After that, click on **Install Easy Anti-Cheat**. Then click **Finish**.

## Error 30005: CreateFile Failed With 32, Fixed

 When Easy Anti-Cheat blocks hackers from entering multiplayer games and ruining your gaming experience, it's great; when we get errors due to it, we find it annoying. Hopefully, the fixes covered in this article will help you resolve the "error 30005: CreateFile failed with 32" problem. If none of these solutions work, you should reinstall the game or the game client as a last resort.

 When you launch a game on your PC or Steam client, do you encounter a message that reads "error 30005: CreateFile failed with 32"? It mostly occurs when running games protected by Easy Anti-Cheat, an anti-cheat service used by multiplayer games to prevent hacking.

 If you have encountered this error, you're probably trying to run a game protected by this service, but there is some issue with the service itself or game files, which is preventing the game from launching.

 So, what causes this error, and how do you fix it?



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/split-screen-style-selecting-separate-themes-for-each-windows-display/"><u>Split Screen Style: Selecting Separate Themes for Each Windows Display</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/sync-up-success-sharing-youtube-on-ig-stories/"><u>Sync Up Success  Sharing YouTube on IG Stories</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-expert-free-fb-imagecinematic-creator-kit/"><u>[Updated] 2024 Approved  Expert Free FB Image/Cinematic Creator Kit</u></a></li>
<li><a href="https://windows11.techidaily.com/integrating-google-play-store-into-win11-os/"><u>Integrating Google Play Store Into Win11 OS</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/edit-avi-videos-for-free-top-editor-choices/"><u>Edit AVI Videos for Free Top Editor Choices</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-increase-disk-size-in-windows-carefully/"><u>How to Increase Disk Size in Windows Carefully</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-explore-online-downloads-converting-youtube-to-mp3-made-simple/"><u>In 2024, Explore Online Downloads  Converting YouTube to MP3 Made Simple</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-financial-face-off-comparing-dailymotion-and-youtube-profitability-for-2024/"><u>[Updated] Financial Face-Off  Comparing Dailymotion & YouTube Profitability for 2024</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-how-to-track-whatsapp-messages-on-apple-iphone-15-plus-without-them-knowing-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Track WhatsApp Messages on Apple iPhone 15 Plus Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-up-a-permanent-delete-toolbar-in-windows-1011s-trash/"><u>Setting Up a Permanent Delete Toolbar in Windows 10/11'S Trash</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-cut-the-hassle-with-macos-easy-to-follow-video-size-adjustment-for-instagram/"><u>[Updated] In 2024, Cut the Hassle with MacOS  Easy-to-Follow Video Size Adjustment for Instagram</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-ensure-video-perfection-before-sharing-on-instagram/"><u>[Updated] 2024 Approved  Ensure Video Perfection Before Sharing on Instagram</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-comprehensive-giroptic-camera-experience/"><u>2024 Approved  Comprehensive Giroptic Camera Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/revitalizing-fall-guys-gaming-experience-after-disconnections-on-windows/"><u>Revitalizing Fall Guys Gaming Experience After Disconnections on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-disabling-onedrive-icon-on-windows-11-explore/"><u>Strategies for Disabling OneDrive Icon on Windows 11 Explore</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windowed-discord-for-flawless-search-experience/"><u>Optimizing Windowed Discord for Flawless Search Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-list-of-6-performance-monitor-apps-for-pcs/"><u>The Ultimate List of 6 Performance Monitor Apps For PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionize-your-security-crafting-unique-lock-patterns-for-windows-11/"><u>Revolutionize Your Security: Crafting Unique Lock Patterns for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-search-bar-autonomy-in-windows-11-interface/"><u>Preventing Search Bar Autonomy in Windows 11 Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-lost-nvidia-configuration-a-guide-for-winx-users/"><u>Restoring Lost NVIDIA Configuration: A Guide for WinX Users</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/avi-file-trimming-and-splitting-simplified-a-2023-update/"><u>AVI File Trimming and Splitting Simplified A 2023 Update</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-in-2024-top-10-online-platforms-for-sourcing-professional-quality-montage-tracks/"><u>Updated In 2024, Top 10 Online Platforms for Sourcing Professional-Quality Montage Tracks</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-oppo-reno-11-5g-by-drfone-android/"><u>In 2024, 10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Oppo Reno 11 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-new-era-of-filesystems-windows-11s-innovations/"><u>Navigating the New Era of Filesystems: Windows 11'S Innovations</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-run-adobe-ps-in-windows-without-trouble-or-failure/"><u>How to Run Adobe PS in Windows without Trouble or Failure</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-ipogo-will-be-the-new-ispoofer-on-nokia-c12-drfone-by-drfone-virtual-android/"><u>In 2024, iPogo will be the new iSpoofer On Nokia C12? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-adjusting-touchpad-sensitivity-in-windows/"><u>The Ultimate Guide to Adjusting Touchpad Sensitivity in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-image-enhancement-building-engaging-slideshows-and-fixing-windows-11-photo-flaws/"><u>The Art of Image Enhancement: Building Engaging Slideshows & Fixing Windows 11 Photo Flaws</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-remove-flashlight-from-iphone-13-pro-max-lock-screen-drfone-by-drfone-ios/"><u>How To Remove Flashlight From iPhone 13 Pro Max Lock Screen | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/how-to-find-the-best-videographer/"><u>How to Find the Best Videographer</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-workspace-multi-screen-setup-for-windows-11-users/"><u>Streamline Your Workspace: Multi-Screen Setup for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/silencing-the-cacophony-soundcard-irq-fixes/"><u>Silencing the Cacophony: Soundcard IRQ Fixes</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-pioneering-affordable-switch-emulators/"><u>[New] 2024 Approved  Pioneering Affordable Switch Emulators</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-photography-toolkit-a-comprehensive-app-analysis/"><u>In 2024, Photography Toolkit  A Comprehensive App Analysis</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-use-face-id-to-pay-for-apple-tvplus-on-iphone-se-2022-by-drfone-ios-unlock-ios-unlock/"><u>How to Use Face ID to Pay for Apple TV+ on iPhone SE (2022)</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-elevating-notetaking-on-windows/"><u>Master the Art of Elevating Notetaking on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/reconciling-windows-game-bar-with-inferior-hardware/"><u>Reconciling Windows Game Bar with Inferior Hardware</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-steam-library-synchronization-hitches/"><u>Navigating Through Steam Library Synchronization Hitches</u></a></li>
<li><a href="https://windows11.techidaily.com/refinement-of-your-touchpad-settings-for-optimal-interaction/"><u>Refinement of Your Touchpad Settings for Optimal Interaction</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-closed-folder-issues-via-double-clicks-in-w10w11/"><u>Resolving Closed Folder Issues via Double-Clicks in W10/W11</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-asus-rog-phone-7-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Asus ROG Phone 7</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-windows-no-audio-output-issue/"><u>Solving Windows: 'No Audio Output' Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/the-complete-gamers-manual-to-winning-with-windows/"><u>The Complete Gamers' Manual to Winning With Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-stabilizing-dwarf-fortress-on-win/"><u>Solutions for Stabilizing Dwarf Fortress on Win</u></a></li>
<li><a href="https://windows11.techidaily.com/tricks-save-and-access-onedrive-around-clients/"><u>Tricks: Save & Access OneDrive Around Clients</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-show-wi-fi-password-on-vivo-y200e-5g-by-drfone-android/"><u>In 2024, How to Show Wi-Fi Password on Vivo Y200e 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-11-eliminating-invisible-logins/"><u>Troubleshooting Windows 11: Eliminating Invisible Logins</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-keep-the-calculator-always-on-top-on-windows/"><u>How to Keep the Calculator Always on Top on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-tips-for-optimizing-wsl-2-on-modern-windows/"><u>Top 5 Tips for Optimizing WSL 2 on Modern Windows</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-reverse-rotation-riddle-on-social-media-platforms/"><u>2024 Approved  The Reverse Rotation Riddle on Social Media Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/reveal-hidden-5ghz-networks-on-windows-11-quick-remedies/"><u>Reveal Hidden 5GHz Networks on Windows 11: Quick Remedies</u></a></li>
</ul></div>
