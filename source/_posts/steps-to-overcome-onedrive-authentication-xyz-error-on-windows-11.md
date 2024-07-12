---
title: Steps to Overcome ONEDRIVE Authentication XYZ Error on Windows 11
date: 2024-07-11T21:18:30.652Z
updated: 2024-07-12T21:18:30.652Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Overcome ONEDRIVE Authentication XYZ Error on Windows 11
excerpt: This Article Describes Steps to Overcome ONEDRIVE Authentication XYZ Error on Windows 11
keywords: Fix OneDrive Login Error,Resolve XYZ OneDrive Issue,Overcome OneDrive Auth Error,Windows 11 OneDrive Troubleshoot,Fix OneDrive on PC Login Error,Resolve Authentication XYZ in OneDrive,Unlock OneDrive Access on Win11
thumbnail: https://thmb.techidaily.com/4f0baa4676690f713a7c64c49fa175c4aff67762b3efda1ae17d3bfe6d387995.jpg
---

## Steps to Overcome ONEDRIVE Authentication XYZ Error on Windows 11

 Microsoft's cloud storage service OneDrive simplifies file management on Windows. However, you might experience issues when signing in to OneDrive, like the 0x8004dec5 error. This article will guide you on how to resolve OneDrive sign-in error 0x8004dec5 specifically on Windows 11\.

## 1\. Check Your Internet Connection

 If you’re having trouble signing in to OneDrive, first [check your internet connection](http://www.makeuseof.com/windows-check-wifi-network-strength/). Slow or spotty internet causes sign-in problems. So, check your connection speed and make sure it’s strong enough for OneDrive. If necessary, reset your router or modem to restore the connection.

 If your internet connection is working, restart your computer and sign in to OneDrive again. This simple step fixes minor errors in the operating system that may cause the sign-in issue.

## 2\. Run the Network Troubleshooter

 If your internet connection is stable, but you’re still having OneDrive sign-in problems, you can run the Internet Connections Troubleshooter. This diagnosis tool scans for network problems and repairs any issues it finds.

 To run the Internet Connection Troubleshooter, follow these steps:

1. Right-click on Start and select **Run** from the menu list.  
![Open Internet Connections](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/open-internet-connections.jpg)
2. In the dialog box, type the following command and click **OK**.  
`msdt.exe -id NetworkDiagnosticsWeb`
3. Click **Advanced** and check **Apply repairs automatically**.  
![Run the Internet Connections troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-the-internet-connections-troubleshooter.jpg)
4. Now click **Next** and follow the on-screen instructions to finish the troubleshooting process.

 Once it’s done, sign into OneDrive and see if the error is fixed. If not, try the next solution.

## 3\. Tweak the Registry Editor

 If the problem persists, remove cached Office account identities from the registry. This requires changing a few settings in the Windows registry which is a database of your operating system, so proceed with caution.

 If you’re not sure what you’re doing, have an experienced technician make the changes for you. To avoid damaging your system, [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making these changes.

1. Press **Win + R** on your keyboard to open the Run dialog.
2. Type **regedit** in the search box and click **OK**.
3. If the UAC window pops up on the screen, click **Yes** to proceed.
4. In the Registry Editor window, navigate to the path as follows:  
`HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Common\Identity`
5. Right-click on the **Identity** folder and select **Delete** from the menu.  
![Delete Identity Folder From Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/delete-identity-folder-from-registry.jpg)
6. Click **Yes** when asked to confirm your action.
7. Close Registry Editor and restart your computer.

 Now try signing in to OneDrive again. The sign-in error should now be resolved.

## 4\. Remove Cached Credentials Folders

 If you're not comfortable tweaking the registry editor, remove cached Office account identities using Windows Explorer. Here's how to do it.

1. Press **Win + E** to open File Explorer.
2. In the File Explorer window, navigate to the following location:  
`C:\Users\Username\AppData\Local\Microsoft\IdentityCache`
3. Press **Ctrl + A** to select all files and delete them.  
![Clear Identity Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/clear-identity-folder.jpg)
4. Now navigate to this location, and replace **Username** with your own Windows username.:  
`C:\Users\Username\AppData\Local\Microsoft\OneAuth  
`
5. Select all the files here and hit the **Delete** button.

 Once you've removed all cached Office account identities, restart your computer and try signing in to OneDrive again.

## 5\. Unlink and Re-Link Your OneDrive Account

 If you have a valid OneDrive account, but still can’t sign in due to the 0x8004dec5 error code, unlink and relink your account. This will reset the connection and fix the problem.

 To unlink OneDrive, follow these steps.

1. Go to the right side of the taskbar and click on the **OneDrive** icon.
2. Click **Help & Settings** (the gear icon) and select **Settings** from the menu list.
3. In the Settings window, go to the **Account** tab.
4. Under your OneDrive account, click **Unlink this PC**.  
![Unlink OneDrive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/unlink-onedrive.jpg)
5. Click **Unlink account** to confirm your action.  
![Unlink OneDrive Account on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/unlink-onedrive-account-on-windows.jpg)

 After unlinking the account, you now need to relink it. To do that, open the OneDrive Settings window again and click **Add an Account**. Enter your OneDrive credentials and sign in to the account.

 When it’s done, close the Settings window. Now open OneDrive and sign in with your new account credentials. The sign-in error should now be resolved.

## 6\. Reset the OneDrive App

 In some cases, resetting the OneDrive application solves the sign-in errors. This restores the app to its default settings and removes any corrupted system files.

 To reset the OneDrive app, follow these steps.

1. Press **Win + X** on your keyboard and select **Installed apps** from the list.
2. In the list of installed apps, scroll down to **OneDrive**.
3. Click the three dots and select the **Advanced options**.
4. Scroll down to the **Reset** section and click on the **Reset** button.  
![Reset OneDrive app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-onedrive-app.jpg)
5. Click **Reset** again to confirm your action.

 After the reset, try signing in to OneDrive and seeing if error 0x8004dec5 is fixed.

## 7\. Get the Latest Windows Updates

 Microsoft releases new patches that improve Windows performance. If your computer didn't receive the latest updates, it may cause OneDrive sign-in errors. To fix this problem, install the pending Windows updates and try signing in to OneDrive again.

 To download and install the latest Windows updates, use these steps.

1. Press **Win + I** on your keyboard to open the Settings window (see our guide on [how to open the Windows system settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/)).
2. From the left sidebar, click on the **Windows Update** tab.
3. Now click **Check for updates** and wait while Windows checks for available updates.  
![Check for updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/check-for-updates.jpg)
4. If you find new updates, download and install them.

 After performing the above action, restart your computer. Now try signing in to OneDrive and seeing if the error is fixed.

## 8\. Uninstall and Reinstall OneDrive

 If the error persists even after trying the above solutions, it's likely that the OneDrive app is malfunctioning. In that case, reinstall the application. It fixes corrupted files and solves sign-in issues. Here's how to do it.

1. [Open Control Panel](https://www.makeuseof.com/windows-11-open-control-panel/).
2. Set the View by option to **Category**, then click **Programs** \> **Uninstall a program**.
3. Find **OneDrive** in the list of installed programs and click **Uninstall**.  
![Uninstall OneDrive-2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/uninstall-onedrive-2.jpg)
4. If you get a confirmation prompt, click **Yes**.

 Now follow the instructions to complete the process. After that, [visit Microsoft's official website](https://www.microsoft.com/en-us/microsoft-365/onedrive/download?) to download and install OneDrive.

## Fixing OneDrive's 0x8004dec5 Sign In Error

 Following the steps mentioned above should resolve the 0x8004dec5 OneDrive sign-in error. Corrupt files, outdated Windows versions, or compatibility issues usually cause it. A basic troubleshooting step would be to restart your computer and reset the OneDrive app. If that doesn't fix it, unlink and relink your account, or reinstall OneDrive.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/reimagining-your-pc-integrating-previous-apps-into-win-11/"><u>Reimagining Your PC: Integrating Previous Apps Into Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-for-seamlessly-entering-fullscreen-mode/"><u>Expert Advice for Seamlessly Entering Fullscreen Mode</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/in-2024-unlock-your-creative-potential-best-free-software-to-produce-music-on-pc-and-mac-2023-edition/"><u>In 2024, Unlock Your Creative Potential Best Free Software to Produce Music on PC & Mac, 2023 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-resolving-installation-issues-with-microsoft-store-apps/"><u>Steps for Resolving Installation Issues with Microsoft Store Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-the-reparse-point-buffer-tag-error-with-onedrive/"><u>Remedying the Reparse Point Buffer Tag Error with OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-customize-and-reset-your-command-prompt/"><u>Guide to Customize and Reset Your Command Prompt</u></a></li>
<li><a href="https://windows11.techidaily.com/skyrocket-your-text-entry-speed-via-typingaid/"><u>Skyrocket Your Text Entry Speed via TypingAid</u></a></li>
<li><a href="https://android-location.techidaily.com/10-free-location-spoofers-to-fake-gps-location-on-your-tecno-camon-20-premier-5g-drfone-by-drfone-virtual/"><u>10 Free Location Spoofers to Fake GPS Location on your Tecno Camon 20 Premier 5G | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/hard-reset-tecno-spark-10-5g-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset Tecno Spark 10 5G in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-highlights-of-short-track-speed-skating-olympics-2022/"><u>[New] Highlights of Short Track Speed Skating Olympics 2022</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-verizon-apple-iphone-14-by-drfone-ios/"><u>In 2024, How to Unlock Verizon Apple iPhone 14</u></a></li>
<li><a href="https://windows11.techidaily.com/instructions-for-resetting-customized-windows-settings/"><u>Instructions for Resetting Customized Windows Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-hurdles-in-windows-hello-fingerprint-failures/"><u>Overcome Hurdles in Windows Hello Fingerprint Failures</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-windows-11-video-tools-list/"><u>Essential Windows 11 Video Tools List</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-the-maze-of-windows-error-code-0xc00000f/"><u>Navigating Through the Maze of Windows Error Code 0Xc00000f</u></a></li>
<li><a href="https://review-topics.techidaily.com/online-signatures-for-txt-file-by-ldigisigner-sign-a-word-sign-a-word/"><u>Online signatures for .txt file</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-windows-8-avi-file-editor-simple-and-efficient-video-editing-solution/"><u>Updated 2024 Approved Windows 8 AVI File Editor Simple and Efficient Video Editing Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-discord-updates-from-triggering-at-system-startup/"><u>Preventing Discord Updates From Triggering at System Startup</u></a></li>
<li><a href="https://windows11.techidaily.com/meeting-prep-101-test-your-windows-webcam-microphone/"><u>Meeting Prep 101: Test Your Windows Webcam, Microphone</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-error-printer-spooler-not-active-on-windows/"><u>Overcoming Error: “Printer Spooler Not Active” On Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-your-input-cant-be-opened-vlc-error/"><u>Eradicating 'Your Input Can't Be Opened' VLC Error</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-to-become-a-win-11-insider/"><u>Step-by-Step to Become a Win 11 Insider</u></a></li>
<li><a href="https://windows11.techidaily.com/essentials-of-implementing-windows-law-filters-effectively/"><u>Essentials of Implementing Windows LAW Filters Effectively</u></a></li>
<li><a href="https://windows11.techidaily.com/sound-revolution-for-your-pc-the-essential-guide-to-audio-drivers-updates/"><u>Sound Revolution for Your PC: The Essential Guide to Audio Drivers Updates</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-the-modern-readers-pathway-to-capturing-internet-television/"><u>[New] In 2024, The Modern Reader's Pathway to Capturing Internet Television</u></a></li>
<li><a href="https://windows11.techidaily.com/maintaining-constant-calc-display-in-windows/"><u>Maintaining Constant Calc Display in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-stable-windows-printer-connections/"><u>Ensuring Stable Windows-Printer Connections</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-roadmap-to-selecting-top-tier-visual-storytellers-for-2024/"><u>The Roadmap to Selecting Top-Tier Visual Storytellers for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/the-ultimate-how-to-for-youtube-ad-creators/"><u>The Ultimate How-To for YouTube Ad Creators</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-unveiling-tiktoks-symbolic-world-a-detailed-guidebook/"><u>2024 Approved  Unveiling TikTok’s Symbolic World  A Detailed Guidebook</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-do-you-know-how-to-zoom-on-facebook-livestream-videos-through-this-article-you-will-find-multiple-ways-and-detailed-steps-to-zoom-in-on-the-fa/"><u>2024 Approved Do You Know How to Zoom on Facebook Livestream Videos? Through This Article, You Will Find Multiple Ways and Detailed Steps to Zoom in on the Facebook Livestream Videos</u></a></li>
<li><a href="https://fake-location.techidaily.com/ispoofer-is-not-working-on-itel-a70-fixed-drfone-by-drfone-virtual-android/"><u>iSpoofer is not working On Itel A70? Fixed | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-shift-script-moving-windows-11-selected-files/"><u>Quick Shift Script: Moving Windows 11 Selected Files</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-enhance-copy-paste-efficiency-across-browsers/"><u>How to Enhance Copy-Paste Efficiency Across Browsers</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-sniping-techniques-alternatives-to-windows-snipping-capability/"><u>Quick Sniping Techniques: Alternatives to Windows' Snipping Capability</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-for-an-effortless-in-place-windows-11-revamp/"><u>Step-by-Step Guide for an Effortless, In-Place Windows 11 Revamp</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-nvidia-setup-not-available-glitch/"><u>Fixing the 'Nvidia Setup Not Available' Glitch</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-monochrome-errors-with-marketplace/"><u>Fixing Monochrome Errors with Marketplace</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-the-ultimate-guide-to-splice-a-detailed-review/"><u>Updated 2024 Approved The Ultimate Guide to Splice A Detailed Review</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-whats-an-av1-format-and-how-does-it-impact-your-life/"><u>Updated Whats an AV1 Format and How Does It Impact Your Life?</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-win-os-extract-issues-saving-time-with-error-1152-solution/"><u>Overcoming Win OS Extract Issues: Saving Time with Error 1152 Solution</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-7-best-video-player-for-mac/"><u>2024 Approved  7 Best Video Player for Mac</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-dism-error-code-0x800f082f-on-windows-systems/"><u>Resolving DISM Error Code: 0X800F082F on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/initiating-chatgpt-with-windows-operating-system/"><u>Initiating ChatGPT with Windows Operating System</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-instagram-reels-slow-motion-techniques-unveiled/"><u>[Updated] In 2024, Instagram Reels Slow-Motion Techniques Unveiled</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-youtube-behavior-manual/"><u>Unified YouTube Behavior Manual</u></a></li>
</ul></div>
