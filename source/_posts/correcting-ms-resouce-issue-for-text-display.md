---
title: Correcting Ms-Resouce Issue for Text Display
date: 2024-07-11T22:24:35.603Z
updated: 2024-07-12T22:24:35.603Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting Ms-Resouce Issue for Text Display
excerpt: This Article Describes Correcting Ms-Resouce Issue for Text Display
keywords: Fix Resource Error,Display Text Correction,MsResource Issue Resolution,Text Displacement Solution,Correcting MS Resource Link,Troubleshoot Text Error,Adjust MS Display Settings
thumbnail: https://thmb.techidaily.com/290fdfbe7988bc73a9658535e5e89697be7bda898900fabab3b9425630194609.jpg
---

## Correcting Ms-Resouce Issue for Text Display

 If you have performed an upgrade recently and noticed a weird "ms-resource:Appname/text" entry in the Start Menu, you are not alone. You may also encounter this error when opening a setting or app.

 This entry in the Start Menu is a trace for a built-in app that has been removed in the successive upgrade. Depending on where you are seeing the error, follow the steps in the article below to resolve this error on your computer.

## 1\. How to Fix the "ms-resource:Appname/Text" Error in the Start Menu

 You can remove the "ms-resource:Appname/Text" entry from the Start Menu by removing the affected application package using PowerShell. Additionally, you can kill the StartMenuExperienceHost.exe process in Task Manager to restart the service.

 Before attempting to remove the app, package, and restart the services, check if you have any Windows updates pending. If you are running a fresh install, try to install all the pending Windows updates. These updates often include bug fixes and may be the only thing you need to do to fix this issue.

![windows 11 update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-update.jpg)

 To check and install Windows updates:

1. Press **Win + I** to open the **Settings** app.
2. Open the **Windows Update** tab.
3. Click on **Check of updates**. Continue to download and install all pending updates.
4. Restart your computer to apply the updates and check if the issue is resolved.

 If the issue persists, you can use PowerShell to remove the affected app package and then restart the associated services to fix the problem.

 To remove the "ms-resource:Appname/Text" entry from the Start Menu:

1. Press the **Win** key and type **powershell**.
2. Right-click on **Windows** **PowerShell** and select **Run as administrator**.  
![remove holographicsfirstrun app powershell windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/remove-holographicsfirstrun-app-powershell-windows.jpg)
3. In the PowerShell window, type the following command and press **Enter**:  
`Get-AppxPackage -all *HolographicFirstRun* | Remove-AppPackage -AllUsers`

 Once you've run the command, be sure to restart your computer.

1. After the computer restarts, [open Task Manager](https://www.makeuseof.com/how-to-access-task-manager-on-windows-11/).
2. Next, open the **Details** tab in Task Manager. On Windows 11, click the three horizontal lines icon to access the details tab.
3. Now you need to locate both **StartMenuExperienceHost.exe** and **Explorer** **.exe**. On Windows 11, you can use the search feature in **Task Manager** to locate the processes.  
![end start menu experience host task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/end-start-menu-experience-host-task-manager.jpg)
4. Right-click on each process and **End Task**.
5. In Task Manager, click **Run new task**. On Windows 10 and older versions, click **File** and select **Run new task**.  
![run new task open tempstate folder file explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-new-task-open-tempstate-folder-file-explorer.jpg)
6. In the **Create new task** dialog, type the following path and click the **Browse** button.  
`%localappdata%\Packages\Microsoft.Windows.StartMenuExperienceHost_cw5n1h2txyewy`
7. In the File Explorer window, delete the **TempState** folder.
8. Go back to Task Manager, and click **Run new task**.
9. Type **explorer.exe** and select the **Create this task with administrative privileges** option.

 Once done, give your PC another restart.

## 2\. Re-Register Your Microsoft Store Apps

 You can [re-register Microsoft Store apps using PowerShell](https://www.makeuseof.com/reregister-microsoft-store-apps-windows/) to stop the error appearing when using Microsoft apps. Doing so should remove any leftover entries showing up in the Start Menu after the update.

 Wait for the process to complete. This may take a few minutes as the command will try to re-register all the apps, including existing ones. Once the process is complete, restart your computer and check for any improvements.

## 3\. Check the Microsoft Store for App Updates

 You may see the "ms-resource:Appname/Text" entry if Windows attempted an unsuccessful app installation. To fix the issue, check if an update exists for the app in the Microsoft Store.

 To determine the app name click on the app entry and check if you can find any information about the app. If not, right-click on the app entry in the **Start Menu** and select **Open File Location**.

![view application folder windows 11 run shell apps folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/view-application-folder-windows-11-run-shell-apps-folder.jpg)

 Alternatively, you can view the application directory to view the installed apps. Press **Win + R** to open Run, type **shell:appsfolder**, and click **OK**. It will open the **Applications** folder. Go through the apps to see if you can locate an app named **ms-resource:Appname/Text** or similar to the entry in the Start Menu.

 Once you have the app name, open the Microsoft Store. Search for the app and check if an update exists. Click **Update** to download and install the update. Once installed, restart your computer and check for any improvements.

## What if the "Ms-resource:Appname/Text" Error Appears When Launching an App?

 At times, you may encounter this error when opening a built-in Microsoft Store app. In this instance, you can run the Microsoft Store apps troubleshooter to fix the issue. Here are a few additional troubleshooting steps to fix this error when launching an app.

## 4\. Run the Microsoft Store Apps Troubleshooter

![The Run button for the Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-run-button-for-the-app-troubleshooter.jpg)

 You can use the built-in Microsoft Store Apps troubleshooter to fix issues with the store apps. Here’s how to do it.

1. Press **Win + I** to open **Settings**.
2. In the **System** tab, scroll down and click on **Troubleshoot**.
3. Next, click on **Other troubleshooters**.
4. Click the **Run** button for **Windows Store Apps**. Wait for the troubleshooter to launch and follow the on-screen instructions. It will scan your system against the common Microsoft Store app issues. Apply any recommended fixes and restart your computer to see if the issue is resolved.

 If you don’t see a Windows Store App troubleshooter option, you are likely running a newer version of the OS without this option. In this instance, try to repair the Microsoft Store app.

## 5\. Repair the Microsoft Store App

![repair microsoft store windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/repair-microsoft-store-windows-11.jpg)

 If the Windows Store Apps troubleshooter is missing or didn’t help, try to repair the Microsoft Store App. You can use the built-in repair option to find and fix common issues with the official app store.

 To repair the Microsoft Store app:

1. Press **Win + I** to open the **Settings** app.
2. Open the **Apps** tab and click on **Installed Apps.**
3. Locate and click the **three-dots** menu beside the **Microsoft Store** app.
4. Select **Advanced Options**.
5. Scroll down to the **Reset** section.
6. Click the **Repair** button, wait for the process to complete, and show a checkmark. If the repair is successful, restart your computer.

### Reset the Microsoft Store App

 In addition to performing a repair, you can also reset the Microsoft Store app to resolve common issues with the store apps. You can perform a reset from the Advanced Options section. Before that, run the wsreset.exe tool to clear the store cache to see if that helps.

 To reset the Microsoft Store App cache:

![wsreset.exe command in the Run tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsreset-exe-command.jpg)

1. Press **Win + R** to open the **Run** dialog.
2. Type **wsreset.exe** and click **OK**.

 Still not resolved? Try to [perform a Microsoft Store reset](https://www.makeuseof.com/windows-10-11-reset-microsoft-store/). Doing so will delete all app data, and you may need to sign in to your Microsoft account again.

## 6\. Other Troubleshooting Steps You Can Try

 If the issue persists, here are a few additional troubleshooting steps you can follow:

1. **Create a new user account** – Try to [create a new local user account](https://www.makeuseof.com/windows-11-create-local-user-account/) to see if the error exists in the new account. This is a handy workaround for a newly set up Windows computer.
2. **Perform a repair reinstall of Windows 11** – You can reinstall [Windows 11 without deleting your apps and files](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/). This is an upgrade reinstall and should fix any issues triggered due to issues with the system files.
3. **Perform a reset** – If an in-place upgrade doesn’t help, consider [performing a factory reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/). You can perform a complete reset while choosing to keep your files, but all your apps will be removed.
4. **Clean install** – [Performing a Windows clean install](https://www.makeuseof.com/how-to-clean-install-windows-11/) will erase everything on your computer and reinstall Windows 11 from scratch. Make sure to back up important data before attempting a clean install.

## Fixing the "ms-resource:Appname/Text" Error in Windows 11

 Often this entry in the start menu is a ghost entry from an unsuccessful or leftover installation of a Microsoft app. To remove the entry or restore the app, you can re-register the Microsoft app, remove the affected app package or run the Windows Store Apps Troubleshooter.

 If the issue persists, an in-place upgrade, factory reset, or a clean install may be necessary to resolve the issue. This is a time-consuming process, and you may need to set up your computer from scratch.

 This entry in the Start Menu is a trace for a built-in app that has been removed in the successive upgrade. Depending on where you are seeing the error, follow the steps in the article below to resolve this error on your computer.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://smart-video-editing.techidaily.com/in-2024-video-tag-management-made-easy-top-editors-for-windows-and-mac/"><u>In 2024, Video Tag Management Made Easy Top Editors for Windows and Mac</u></a></li>
<li><a href="https://windows11.techidaily.com/curtailing-spontaneous-terminal-trigger-activations/"><u>Curtailing Spontaneous Terminal Trigger Activations</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-analyze-and-align-image-ratios/"><u>Updated In 2024, Analyze and Align Image Ratios</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-bridging-devices-friend-up-with-discord-for-2024/"><u>[New] Bridging Devices  Friend Up with Discord for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-windows-screen-size-setsbacks-7-easy-solutions/"><u>Conquering Windows' Screen Size Setsbacks: 7 Easy Solutions</u></a></li>
<li><a href="https://some-techniques.techidaily.com/excellence-in-motion-best-4k-cameras-unveiled-for-2024/"><u>Excellence in Motion  Best 4K Cameras Unveiled for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/dism-tactics-restoring-windows-11-os-images/"><u>DISM Tactics: Restoring Windows 11 OS Images</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-overcoming-the-windows-virtualbox-efail-error/"><u>Decoding and Overcoming the Windows Virtualbox E_FAIL Error</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-update-or-downgrade-iphone-13-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade iPhone 13 Without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/disable-windows-11s-covert-surveillance/"><u>Disable Windows 11'S Covert Surveillance</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-erase-live-video-on-facebook-windows-android-tactics/"><u>[New] In 2024, Erase Live Video on Facebook  Windows, Android Tactics</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-dual-monitor-mishaps-on-your-pc/"><u>Correcting Dual Monitor Mishaps on Your PC</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-pushing-imagery-boundaries-mastering-ps-distortion-methods/"><u>2024 Approved  Pushing Imagery Boundaries  Mastering PS Distortion Methods</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-motorola-edge-2023-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Motorola Edge 2023 Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-fix-for-msvcr110dll-absence/"><u>Comprehensive Fix for msvcr110.dll Absence</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-folder-tab-glitches-in-windows-11/"><u>Conquering Folder Tab Glitches in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-device-disabled-issue-with-error-code-22-on-windows-11/"><u>Correcting Device Disabled Issue with Error Code 22 on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/critiquing-7-perplexing-windows-11-aesthetics/"><u>Critiquing 7 Perplexing Windows 11 Aesthetics</u></a></li>
<li><a href="https://vp-tips.techidaily.com/drone-buying-101-critical-facts-for-the-aspiring-owner/"><u>Drone Buying 101  Critical Facts for the Aspiring Owner</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-solution-to-stop-0xf0831-in-windows-11/"><u>Comprehensive Solution to Stop 0xF0831 in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/connected-scribbles-using-stickies-across-all-devices-in-win11/"><u>Connected Scribbles: Using Stickies Across All Devices in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-compatibility-issues-windows-troubleshooting-blueprint/"><u>Conquer Compatibility Issues: Windows Troubleshooting Blueprint</u></a></li>
<li><a href="https://windows11.techidaily.com/correct-keyboard-fixes-for-windows-11s-unresponsive-f-keys/"><u>Correct: Keyboard Fixes for Windows 11'S Unresponsive F Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/dial-up-the-velocity-fixing-your-stuttery-pc/"><u>Dial Up the Velocity: Fixing Your Stuttery PC</u></a></li>
<li><a href="https://windows11.techidaily.com/ditching-the-default-store-on-new-windows-11/"><u>Ditching the Default Store on New Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-inaccessible-steam-servers-in-home-pc-setups/"><u>Dealing With Inaccessible Steam Servers in Home PC Setups</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-realigning-your-personal-soundtracks-from-spotify-to-youtube-music/"><u>2024 Approved  Realigning Your Personal Soundtracks From Spotify to YouTube Music</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-overview-of-the-best-oppo-find-x6-pro-screen-mirroring-app-drfone-by-drfone-android/"><u>In 2024, Overview of the Best Oppo Find X6 Pro Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/conjoining-android-and-windows-11-tablets-effortlessly/"><u>Conjoining Android and Windows 11 Tablets Effortlessly</u></a></li>
<li><a href="https://windows11.techidaily.com/determining-hddssd-in-windows-a-step-by-step-guide/"><u>Determining HDD/SSD in Windows: A Step-by-Step Guide</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-the-art-of-muting-background-sounds-in-skype/"><u>[Updated] 2024 Approved  The Art of Muting Background Sounds in Skype</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-correcting-unspecified-obs-recording-glitches/"><u>Decoding and Correcting Unspecified OBS Recording Glitches</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-the-essential-handbook-of-personal-branding-mastering-facebook-biographies/"><u>[Updated] 2024 Approved  The Essential Handbook of Personal Branding - Mastering Facebook Biographies</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-systemsettings-executable-errors-on-windows-11/"><u>Correcting SystemSettings Executable Errors on Windows 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-from-photoshop-to-phun-best-software-conversion-tools-pc-mac/"><u>2024 Approved  From Photoshop to Phun  Best Software Conversion Tools, PC Mac</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-special-features-virtual-location-on-nokia-130-music-drfone-by-drfone-virtual-android/"><u>In 2024, How To Use Special Features - Virtual Location On Nokia 130 Music? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-camera-not-detected-error-on-windows-11-pcs/"><u>Correcting “Camera Not Detected” Error on Windows 11 PCs</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/exclusive-performers-webcasts-for-2024/"><u>Exclusive Performers' Webcasts for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/controlling-highlight-features-on-windows-11-pcs/"><u>Controlling Highlight Features on Windows 11 PCs</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-spotifys-1-hit-list-update/"><u>[Updated] In 2024, Spotify's #1 Hit List Update</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-a-plan-for-file-explorer-in-windows-11/"><u>Crafting a Plan for File Explorer in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-windows-11s-user-identity-framework/"><u>Dissecting Windows 11'S User Identity Framework</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-your-window-11-experience-dynamic-wallpapers-guide/"><u>Customize Your Window 11 Experience: Dynamic Wallpapers Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/ditch-default-home-port-on-w11-settings-interface/"><u>Ditch Default Home Port on W11 Settings Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/covertly-masking-taskbars-language-feature-in-win11/"><u>Covertly Masking Taskbar's Language Feature in Win11</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-essential-techniques-for-designing-youtube-video-thumbnails/"><u>[New] Essential Techniques for Designing YouTube Video Thumbnails</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-4-ways-to-unlock-apple-iphone-x-to-use-usb-accessories-without-passcode-by-drfone-ios/"><u>In 2024, 4 Ways to Unlock Apple iPhone X to Use USB Accessories Without Passcode</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/mastering-the-art-of-transferring-instagram-footage-to-pcmac/"><u>Mastering the Art of Transferring Instagram Footage to PC/Mac</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>