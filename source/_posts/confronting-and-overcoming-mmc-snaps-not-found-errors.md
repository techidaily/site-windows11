---
title: Confronting and Overcoming MMC Snaps Not Found Errors
date: 2024-06-25T12:43:55.648Z
updated: 2024-06-26T12:43:55.648Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Confronting and Overcoming MMC Snaps Not Found Errors
excerpt: This Article Describes Confronting and Overcoming MMC Snaps Not Found Errors
keywords: MMC Snap Fix Error,MMC Tools Troubleshoot,NTFS Filesystem Glitch,Windows MMC Snapping,SnapNotFound MMC,Repair MMC Shortcuts,Overcoming MMC Crashes
thumbnail: https://thmb.techidaily.com/03226297e1d4f4326afb184b72adefb3e6177057903e76b2e2845e825a7f6538.jpg
---

## Confronting and Overcoming MMC Snaps Not Found Errors

 The "MMC could not create the snap-in" error has been around for some time and still seem to bug some users now and then. The error occurs when you try to open an administrative tool such as an Event Viewer, Task Scheduler, and so forth.

 Sometimes, the error may also pop up after a Blue Screen of Death (BSOD), causing one or more apps to crash. This error often occurs if the registry configuration of the snap-in is malfunctioning. Here we show a few ways to fix to help you resolve the "MMC could not create the snap-in" error and restore administrative tools access in Windows.

## 1\. Fix the Broken Registry Configuration for the Snap-In

![delete-registry-key-mmc-snap-in-windows-registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/delete-registry-key-mmc-snap-in-windows-registry.jpg)

 If the registry configuration for the affected snap-in is broken, it may trigger the "MMC could not create the snap-in" error. To fix the issue, you’ll need to delete the corrupt registry entry associated with the snap-in. Here’s how to do it.

 Making incorrect modifications to the Windows Registry involves risk and may cause your system to malfunction. We recommend you [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [make a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) to be on the safe side.

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK**.
3. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\MMC\SnapIns`
4. The **SnapIns** key consists of multiple sub-keys. You need to locate the sub-key identical to the **CLSID** shown in the error message.
5. For example, if the error occurs when opening Event Viewer, you’ll likely see **CLSID: c7b8fb06-bfe1-4c2e-9217-7a69a95bbac4**, and so on. So, note down the **CLSID** shown in the error screen.

1. In the **Registry Editor**, select the sub-key folder with the same name as the error **CLSID**.
2. Next, right-click on the same sub-key folder and select **Delete**.
3. Click **Yes** to confirm the action.
4. Close the **Registry Editor** and restart your computer.
5. After the restart, open the administrative tool snap-in to see if the error is resolved.

## 2\. Enable .NET Framework

![enable net framework 3 5 windows features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-net-framework-3-5-windows-features.jpg)

 You can also fix this error by enabling .NET Framework 3.5\. The idea is that one of the snap-ins on your PC may need .NET Framework 3.5 to work. So, if the feature is disabled, you may encounter an error.

 Fortunately, you can easily enable the .NET Framework feature using the Turn Windows features on or off dialog. Here’s how to do it.

 To enable .NET Framework 3.5:

1. Press the **Win** key and type **Windows features** and click on **Turn Windows features on or off** from the search results.
2. In the **Windows Features** dialog, select the **.NET Framework 3.5 (include .NET 2.0 and 3.0)**.
3. Next, click the **Plus** icon to expand the section and select the options ‘**Windows Communications Foundation HTTP Activation**’ and **‘Windows Communications Foundation Non-HTTP Activation**’.
4. Next, click to **Apply** the changes and install the feature.
5. Once installed, you’ll be prompted to restart the computer. Restart your system, and the MMC snap-in should work now.

## 3\. Check for and Repair Corrupt System Files

![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dism-scan-health-restore-health-command-prompt.jpg)

 If you have one or more corrupt system files, it may cause issues with the system apps. You can run the System File Checker tool to determine if the problem is due to system file issues. It will scan and check the integrity of systems files and automatically repair them to fix the problem.

 Microsoft recommends running its built-in Windows image check and repair utility, Deployment Image Servicing and Management (DISM), before running the System File Checker utility.

 If you're not sure how to run either of these tools, we cover both in our guide on [how to repair corrupt Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

## 4\. Remove and Reinstall the Microsoft Visual C++ Redistributable

![repair microsoft visual c plus plus distributable package](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/repair-microsoft-visual-c-plus-plus-distributable-package.jpg)

 If the issue persists, try to fix and repair issues with the Visual C++ Redistributable package. If there are any issues with the package, it can cause the MMC snap-ins to stop working.

 To repair the Visual C++ Redistributable package:

1. Press **Win + R** to open Run.
2. Type "control" and click **OK** to open Control Panel.
3. In Control Panel, click on **Uninstall a program** under **Programs**.
4. Locate and select the **Microsoft Visual C++ Redistributable** entry and click **Uninstall**.
5. In the **Modify Setup** dialog, click **Repair**. The repair process may take a few minutes to complete.
6. Once done, restart your computer and check for any improvements.

 If the issue persists, reinstalling the Visual C++ Redistributable package may be required. To reinstall the package:

![uninstall microsoft visual c plus plus distributable package](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/uninstall-microsoft-visual-c-plus-plus-distributable-package.jpg)

1. Select the **Microsoft Visual C++ package** in Control Panel and click on **Uninstall**.
2. Click **Uninstall** in the **Modify Setup** dialog.
3. Click **Finish** to complete uninstallation. Repeat the process for all the Visual C++ Redistributable packages.
4. Once done, head over to the [Microsoft Visual C++ Redistributable package page](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170).
5. Download the latest version of the package available on your computer. Depending on your system compatibility, you can select from ARM64, X86, and X64 architecture versions.
6. Run the executable file to install the package and follow the on-screen instructions.
7. Once installed, restart your computer and check if MMC snap-ins are now working.

## Fix the MMC Snap-In and Restore Your Administrative Tools on Windows

 This error is triggered when a snap-in malfunctions, which is often a case of broken registry configuration. To fix the issue, you can delete the broken registry sub-key for the affected snap-in. Additionally, enable/re-enable the .NET Framework 3.5\. If not, scan the system for file integrity issues with the DISM and System File Checker utility.

 Alternatively, you can use the Remote Server Administration Tools (RSAT), which has additional features. RSAT is only available on the Pro and Enterprise edition of the Windows OS. However, you can run a PowerShell script to install it on the Windows Home version easily.

 Sometimes, the error may also pop up after a Blue Screen of Death (BSOD), causing one or more apps to crash. This error often occurs if the registry configuration of the snap-in is malfunctioning. Here we show a few ways to fix to help you resolve the "MMC could not create the snap-in" error and restore administrative tools access in Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/tailored-screenscape-designing-distinctive-displays-on-each-window-of-win-1011/"><u>Tailored Screenscape: Designing Distinctive Displays on Each Window of Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/reintroduce-disappearing-5ghz-network-on-windows-11/"><u>Reintroduce Disappearing 5GHz Network on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/photoshop-power-users-guide-to-windows-keys/"><u>Photoshop Power-Users Guide to Windows Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-non-existent-mmc-snaps/"><u>Unraveling the Mystery of Non-Existent MMC Snaps</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-pc-safety-introducing-your-unique-window-pin-design/"><u>Elevate PC Safety: Introducing Your Unique Window Pin Design</u></a></li>
<li><a href="https://windows11.techidaily.com/win11s-unnecessary-filler-heres-how-to-tackle-it/"><u>Win11's Unnecessary Filler? Here’s How To Tackle It</u></a></li>
<li><a href="https://windows11.techidaily.com/speed-up-taskbar-interaction-enabledisable-ai-on-win-11/"><u>Speed Up Taskbar Interaction: Enable/Disable AI on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windowed-discord-for-flawless-search-experience/"><u>Optimizing Windowed Discord for Flawless Search Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-the-endless-void-fixing-xbox-app-errors-in-win11/"><u>Avoiding the Endless Void: Fixing Xbox App Errors in Win11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/capture-words-from-your-speech-in-microsoft-word-easily/"><u>Capture Words From Your Speech in Microsoft Word Easily</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-how-to-make-reels-on-instagram-like-a-ninja-for-2024/"><u>[Updated] How to Make Reels on Instagram Like a Ninja for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-the-complete-manual-to-mobile-igtv-video-acquisition-for-2024/"><u>[New] The Complete Manual to Mobile IGTV Video Acquisition for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-streamlining-your-rl-gameplay-videography-for-2024/"><u>[Updated] Streamlining Your RL Gameplay Videography for 2024</u></a></li>
<li><a href="https://ai-video.techidaily.com/updated-in-2024-translate-video-from-japanese-to-english-online-for-free/"><u>updated In 2024, Translate Video From Japanese to English Online for Free</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-teleport-your-gps-location-on-vivo-y77t-drfone-by-drfone-virtual-android/"><u>How To Teleport Your GPS Location On Vivo Y77t? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-poco-x5-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Poco X5 to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-direct-download-and-conversion-best-youtube-to-mp3-software-for-2024/"><u>[Updated] Direct Download & Conversion  Best YouTube to MP3 Software for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-captioning-videos-efficiently-on-vimeo-platform/"><u>[New] Captioning Videos Efficiently on Vimeo Platform</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-you-cast-your-apple-iphone-14-pro-to-windows-pc-with-ease-drfone-by-drfone-ios/"><u>In 2024, How Can You Cast Your Apple iPhone 14 Pro to Windows PC With Ease? | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>