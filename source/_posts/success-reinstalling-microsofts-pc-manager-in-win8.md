---
title: Success! Reinstalling Microsoft's PC Manager in Win8
date: 2024-07-11T21:26:03.108Z
updated: 2024-07-12T21:26:03.108Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Success! Reinstalling Microsoft's PC Manager in Win8
excerpt: This Article Describes Success! Reinstalling Microsoft's PC Manager in Win8
keywords: Win8 MSConfig,Reinstall Manager,Restore Windows,System Repair Tool,Registry Fixer,Error Resolution,Software Refresh
thumbnail: https://thmb.techidaily.com/f35b950c7a8f4cdd1989c1e04c70b04dbfa6ce641c77398dacbaad68cbaf2be6.jpg
---

## Success! Reinstalling Microsoft's PC Manager in Win8

 Microsoft PC Manager is a maintenance app that lets you optimize your system performance. It offers superfast malware removal, a one-click speed boost, and a full computer security check. At the time of writing, the app is in open beta. Therefore, it's very common to face issues with it.

 One of the more common issues is that the app fails to install on a Windows computer. As such, if Microsoft PC Manager fails to install on your computer, here are some fixes you can try.

## 1\. Restart Your Computer

 This is a common troubleshooting method, but it's essential for a reason. The reason that Microsoft PC Manager won't install on your system could be due to a temporary bug. Before you dive into the more advanced troubleshooting fixes, consider restarting y [our computer](https://www.makeuseof.com/windows-restart-methods/) (see [how to restart your Windows PC](https://www.makeuseof.com/windows-restart-methods/) ) to put it back on a clean slate.

 If you still can't install the application after a system restart, try the next solution on the list.

## 2\. Temporarily Disable Your Antivirus

 Most antivirus programs come with a security feature that stops installing malicious applications onto the computer. Unfortunately, they can sometimes block trusted applications like the Microsoft PC Manager. If this is the case with you as well, consider disabling the antivirus program temporarily as a solution.

 If you're using the Windows Security app as the default security program on your computer, here's how to disable it:

1. Open the Settings menu by pressing the**Win + I** hotkeys.
2. Select**Privacy & security** from the left panel.
3. In the Security section, select the**Windows Security** option.
4. Click the**Open Windows Security** button.
5. In the Windows Security app, click the**Virus & threat protection** option in the left panel.
6. Click**Manage settings** under Virus & threat protection settings.
7. Disable the toggle next**Real-time protection.**  
![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/real-time-protection-option.jpg)

 If you're using a third-party antivirus program, you can disable it by right-clicking on its icon in the system tray and choosing the "Disable" option from the context menu. You can also go through the antivirus support pages to learn more about how to disable it.

 After disabling the security program, give a quick restart to your computer and check if the problem continues.

## 3\. Use the Program Troubleshooter

 Windows 10 and 11 offer different troubleshooting options that you can use to detect and fix common issues. They don't always eliminate the problem, but they're worth a try when you are unable to install Microsoft PC Manager on your computer.

 In Windows 10, you can access the program troubleshooter by following the below steps:

1. Open Settings, and then select**Update & Security** .
2. Choose the**Troubleshoot** option. Then, select**Additional troubleshooters.**
3. In the Additional troubleshooters window, highlight the**Program Compatibility Troubleshooter** option and click the**Run the troubleshooter** button.

 The troubleshooter window will appear and scan your computer for issues.

 If you've Windows 11, open the Settings menu, and navigate to**System** \>**Troubleshoot** \>**Other troubleshooters** . Click the**Run** button next to Program Compatibility Troubleshooter.

![Program Compatibility Troubleshooter in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Program-Compatiblity-Troubleshooter.jpg)

 If running the built-in troubleshooter wasn't helpful, download and run the Program Install and Uninstall troubleshooter from [Windows Support](https://support.microsoft.com/en-us/topic/fix-problems-that-block-programs-from-being-installed-or-removed-cca7d1b6-65a9-3d98-426b-e9f927e1eb4d) .

## 4 . Clear the Temp Folder

![Delete content of the Temp folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Temp-folder.jpg)

 Programs and apps installed on your store temporary files in the Temp folder. But for various reasons, the Temp folder can get corrupted and cause the issue at hand.

 The solution, in this case, is to clear the Temp folder. Don't worry; deleting the Temp folder is not going to have any adverse effect on your computer's data.

To delete the Temp folder, follow the below instructions:

1. Open the Run dialog box by pressing the**Win + R** hotkeys.
2. In the Run dialog box, type**Temp** and click**OK.** It'll open the Temp folder.
3. Select everything inside the Temp folder by pressing the**Ctrl + A** hotkeys.
4. Press the**Shift + Delete** hotkeys to clear the Temp folder's content permanently.

## 5 . Download Any Available Windows Updates

 Windows regularly releases updates to add new features and fix bugs and glitches. And from what it looks like, Microsoft PC Manager can fail to install on your computer due to a temporary glitch.

 To download any available Windows update, follow the below instructions:

1. Open the Settings menu and select**Windows Update** from the left panel.
2. Click the**Check for updates** option.  
![The Check for updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-check-for-updates-option.jpg)

 Windows will now look for and download any available updates. Once the update is installed, restart your computer and check for the issue.

## 6\. Fix Any Corrupted Files on Your Computer

 Another reason behind this issue is corruption within the system files. Fortunately, you can detect and fix these files by running an SFC scan. However, before we run the SFC scan, it is best to do a preliminary scan to ensure that the SFC tool is working properly.

 The Deployment Image Servicing and Management tool (DISM) is an integrated Windows utility that offers a wide range of functionalities. In this case, the DISM Restorehealth command makes sure that our next fix will work properly. Work through the below steps:

1. Open the Start menu, type**Command** **Prompt** in the search bar, and select the**Run** **as administrator** option. It'll open Command Prompt with admin rights.
2. In the elevated Command Prompt window, type**DISM /online /cleanup-image /restorehealth** and press**Enter** .
3. Wait until the command is executed. Depending on your computer's health, the process can take up to 15 minutes. Sometimes the process will stick, but wait for it to complete.
4. After the process is complete, type**sfc /scannow** and press**Enter** .

## 7\. Reset Your Computer

![Reset PC button in Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Reset-PC-.jpg)

 If you're still unable to install the Microsoft PC Manager, you can use the Windows Reset function. This will reinstall Windows, but it will keep all your personal files intact. Here's how to do it:

1. Navigate to Settings > System > Recovery.
2. Select the**Reset PC** button.

Next, follow the on-screen to complete the reset process.

## Optimize Your System With Microsoft PC Manager

 Microsoft PC Manager is the new way to optimize your system performance. The application is still in the beta phase; thus, it's common for it to run into issues now and then. If the Microsoft PC Manager fails to install on your computer, you now know what's causing the problem and how to fix it.

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
<li><a href="https://windows11.techidaily.com/elevate-your-system-launch-by-configuring-services-in-windows-11/"><u>Elevate Your System Launch by Configuring Services in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-the-essence-of-windows-11s-registry-structure/"><u>Dissecting the Essence of Windows 11'S Registry Structure</u></a></li>
<li><a href="https://howto.techidaily.com/fix-cant-take-screenshot-due-to-security-policy-on-samsung-galaxy-a14-4g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Cant Take Screenshot Due to Security Policy on Samsung Galaxy A14 4G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/safeguard-files-with-windows-controlled-access-feature/"><u>Safeguard Files with Window's Controlled Access Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/improving-memory-footprint-in-ms-teams/"><u>Improving Memory Footprint in MS Teams</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-pokemon-emerald-master-ball-cheat-on-vivo-x90s-drfone-by-drfone-virtual-android/"><u>How to Use Pokémon Emerald Master Ball Cheat On Vivo X90S | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-examining-youtubers-monthly-revenue-strategies/"><u>[Updated] 2024 Approved  Examining YouTubers' Monthly Revenue Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-interfaces-windows-following-11/"><u>Innovative Interfaces: Windows Following 11</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-inside-disconitro-navigating-the-premium-experience-with-ease/"><u>[New] In 2024, Inside DiscoNitro  Navigating the Premium Experience with Ease</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-ultimate-guide-to-remote-podcast-recording/"><u>[New] Ultimate Guide to Remote Podcast Recording</u></a></li>
<li><a href="https://howto.techidaily.com/11-proven-solutions-to-fix-google-play-store-not-working-issue-on-honor-70-lite-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Proven Solutions to Fix Google Play Store Not Working Issue on Honor 70 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/harness-the-power-of-windows-11-a-guide-to-7-effective-techniques-36/"><u>Harness the Power of Windows 11: A Guide to 7 Effective Techniques (36)</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-develop-windows-custom-text-to-voice-software-using-whisper-and-ahk/"><u>How to Develop Window's Custom Text-To-Voice Software Using Whisper & AHK</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/crafting-impressive-big-heads-on-tiktok-a-detailed-walkthrough-3-steps/"><u>Crafting Impressive Big Heads on TikTok  A Detailed Walkthrough (3 Steps)</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-unlock-more-views-twitch-to-facebook-streaming-tips/"><u>[Updated] Unlock More Views  Twitch to Facebook Streaming Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-nonfunctional-wsreset-service-in-windows/"><u>How to Reactivate Nonfunctional WSReset Service in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-steps-to-launch-wordpad-on-windows/"><u>Seamless Steps to Launch WordPad on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-windows-volume-preserve-data/"><u>Enhance Windows Volume, Preserve Data</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-increasing-ram-to-achieve-peak-performance-in-minecraft/"><u>In 2024, Increasing RAM to Achieve Peak Performance in Minecraft</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-stepwise-approach-affordable-creation-of-engaging-youtube-intros/"><u>2024 Approved  Stepwise Approach  Affordable Creation of Engaging YouTube Intros</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-create-an-apple-developer-account-on-apple-iphone-12-pro-max-by-drfone-ios/"><u>How To Create an Apple Developer Account On Apple iPhone 12 Pro Max</u></a></li>
<li><a href="https://windows11.techidaily.com/cease-uncontrolled-system-shutdowns-on-windows-11/"><u>Cease Uncontrolled System Shutdowns on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-techniques-for-an-opening-windows-terminal/"><u>Mastering Techniques for an Opening Windows Terminal</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-premium-accelerated-photo-browser-for-windows/"><u>[Updated] Premium Accelerated Photo Browser for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-touchpad-sensitivity-in-windows-11-devices/"><u>Mastering Touchpad Sensitivity in Windows 11 Devices</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-mastering-the-art-of-uploading-videos-into-personalized-playlists/"><u>[New] Mastering the Art of Uploading Videos Into Personalized Playlists</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-pro-tip-guide-to-integrating-photos-and-videos-into-windows-10/"><u>[Updated] Pro-Tip Guide to Integrating Photos and Videos Into Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/method-for-handling-device-access-issues-with-audacity-win/"><u>Method for Handling Device Access Issues with Audacity (Win)</u></a></li>
<li><a href="https://facebook.techidaily.com/how-to-add-and-remove-shortcuts-on-facebook/"><u>How to Add and Remove Shortcuts on Facebook</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-tips-for-reactivating-file-explorer-ui/"><u>Easy Tips for Reactivating File Explorer UI</u></a></li>
<li><a href="https://windows11.techidaily.com/choosing-the-right-nearby-share-software-for-secure-collaboration/"><u>Choosing the Right Nearby Share Software for Secure Collaboration</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-hardware-utilization-in-windows-11/"><u>Decoding Hardware Utilization in Windows 11</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-use-ispoofer-on-poco-m6-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to use iSpoofer on Poco M6 5G? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-teleport-your-gps-location-on-vivo-s17t-drfone-by-drfone-virtual-android/"><u>How To Teleport Your GPS Location On Vivo S17t? | Dr.fone</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-2024-a-guide-to-color-grade-your-picture-in-lightroom/"><u>In 2024, A Guide to Color Grade Your Picture in LightRoom</u></a></li>
<li><a href="https://windows11.techidaily.com/decluttering-windows-11-icon-pile-up/"><u>Decluttering Windows 11 Icon Pile-Up</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-securely-enabling-controlled-folder-access-in-windows-11/"><u>Navigate Securely: Enabling Controlled Folder Access in Windows 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-reset-your-samsung-galaxy-f15-5g-lock-screen-password-by-drfone-android/"><u>In 2024, How to Reset your Samsung Galaxy F15 5G Lock Screen Password</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/best-top-vlog-editor-apps-for-iphone-and-android/"><u>Best Top Vlog Editor Apps for iPhone and Android</u></a></li>
<li><a href="https://windows11.techidaily.com/evaluating-hidden-gems-in-windows-system-monitors/"><u>Evaluating Hidden Gems in Windows' System Monitors</u></a></li>
<li><a href="https://windows11.techidaily.com/reduce-precision-jumps-turn-off-mouse-speed-on-your-pc/"><u>Reduce Precision Jumps: Turn Off Mouse Speed on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/getting-acquainted-with-apple-maps-on-windows-desktops/"><u>Getting Acquainted with Apple Maps on Windows Desktops</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-frameforge-review-the-ultimate-guide-to-capturing-tech/"><u>2024 Approved  FrameForge Review  The Ultimate Guide to Capturing Tech</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unlock-full-potential-advanced-tips-for-zooming-images-in-snapchat/"><u>[New] Unlock Full Potential  Advanced Tips for Zooming Images in Snapchat</u></a></li>
<li><a href="https://windows11.techidaily.com/ceasing-autonomous-openings-in-microsoft-shop-app/"><u>Ceasing Autonomous Openings in Microsoft Shop App</u></a></li>
<li><a href="https://windows11.techidaily.com/remedies-for-sudden-stoppages-of-windows-notepad-app/"><u>Remedies for Sudden Stoppages of Windows Notepad App</u></a></li>
<li><a href="https://windows11.techidaily.com/integrating-nas-into-mobile-device-setups/"><u>Integrating NAS Into Mobile Device Setups</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-white-or-gray-microsoft-store-display/"><u>Fixing White or Gray Microsoft Store Display</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-memory-test-failed-in-windows/"><u>Combatting 'Memory Test Failed' In Windows</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/in-2024-video-editing-for-beginners-a-microsoft-guide-for-windows-users/"><u>In 2024, Video Editing for Beginners A Microsoft Guide for Windows Users</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-ethical-approaches-to-achieve-one-million-youtube-subscribers/"><u>[Updated] Ethical Approaches to Achieve One Million YouTube Subscribers</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-unlock-hdri-magic-compreranial-sdr-to-high-dynamic-range-upgrade/"><u>[Updated] 2024 Approved  Unlock HDRI Magic  Compreranial SDR to High Dynamic Range Upgrade</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-customize-sound-levels-with-dedicated-win11-keys/"><u>How to Customize Sound Levels with Dedicated Win11 Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaim-default-speaker-levels-post-windows-update/"><u>Reclaim Default Speaker Levels Post-Windows Update</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-flaky-windows-apps-a-step-by-step-guide/"><u>Fixing Flaky Windows Apps: A Step-by-Step Guide</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-verizon-iphone-se-2022-by-drfone-ios/"><u>How to Unlock Verizon iPhone SE (2022)</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-restrictions-to-write-files-in-windows-11-os/"><u>Overcoming Restrictions to Write Files in Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-recover-and-reset-itunes-when-its-not-working/"><u>How to Recover and Reset iTunes When It's Not Working</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-how-to-deal-with-non-terminatable-errors/"><u>Bypassing Windows: How to Deal with Non-Terminatable Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/changing-terminals-default-backdrop/"><u>Changing Terminal's Default Backdrop</u></a></li>
</ul></div>
