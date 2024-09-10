---
title: "Optimize Disk Space: Clear Temporary Windows Files Now"
date: 2024-09-09T11:59:14.736Z
updated: 2024-09-10T11:59:14.736Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Optimize Disk Space: Clear Temporary Windows Files Now"
excerpt: "This Article Describes Optimize Disk Space: Clear Temporary Windows Files Now"
keywords: Optimize Disk Usage,Delete Temp Files,Free Up Storage,Clear Cache Data,Speedup Computer,Unclutter System,Reduce RAM Use
thumbnail: https://thmb.techidaily.com/c01f488742f525379e15c90538d56863d279883606cc35ff29b3863a4d78b16e.jpg
---

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098701/14409" target="_top" id="2098701">
  <img src="//a.impactradius-go.com/display-ad/14409-2098701" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098701/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Optimize Disk Space: Clear Temporary Windows Files Now

 Temporary files, as the name implies, aren’t meant to stick around on your Windows computer forever. Although Windows makes it simple to delete temporary files, there can be times when these files refuse to leave.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123476/16836" target="_top" id="2123476">
  <img src="//a.impactradius-go.com/display-ad/16836-2123476" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123476/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Use the Disk Cleanup Tool

[Windows offers several options for clearing temporary files](http://www.makeuseof.com/windows-11-delete-temporary-files/) on your PC. If you are unable to delete temporary files via the Settings app or File Explorer, try using the Disk Cleanup tool instead.

 Here are the steps you can follow:

1. Press **Win + S** to access the search menu.
2. Type **disk cleanup** in the box and press **Enter**.
3. Use the drop-down menu to select the drive from which you want to clear temporary files.
4. Click **OK**.
5. Under **Files to delete**, use the checkboxes to select the files you want to remove.
6. Click **OK** to proceed.
7. Click the **Delete Files** to confirm.  
![Delete Temp Files Using Disk Cleanup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-temp-files-using-disk-cleanup.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118310/7443" target="_top" id="2118310">
  <img src="//a.impactradius-go.com/display-ad/7443-2118310" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118310/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Wait for a few moments until the Disk Cleanup tool clears all the temporary files.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115946/19272" target="_top" id="2115946">
  <img src="//a.impactradius-go.com/display-ad/19272-2115946" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115946/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Use Command Prompt

 If the Disk Cleanup utility fails to delete some or all of the temporary files on Windows, you can try using the Command Prompt instead. Don’t worry, the process isn’t as complex as it might sound.

 Follow these steps to continue:

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt appears.
3. Copy and paste the following command into the console and hit **Enter**.  
del /q /f /s %temp%\* && del /s /q C:\Windows\temp\*  
![Delete Temp Files Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-temp-files-using-command-prompt.jpg)

 Wait for the above command to run and delete the temporary files.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2120861/26400?prodsku=Saturn" target="_top" id="2120861">
  <img src="//a.impactradius-go.com/display-ad/26400-2120861" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2120861/26400?prodsku=Saturn" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Empty the SoftwareDistribution Folder

 Windows saves all the downloaded update files in the SoftwareDistribution folder before installing them. If a [Windows system update gets stuck](https://www.makeuseof.com/tag/windows-update-stuck/), the OS will not delete the temporary files associated with it.

 To fix this, you can try emptying the SoftwareDistribution folder manually using these steps:

1. Press **Win + S** to open the search menu.
2. Type **services** in the box and press **Enter**.
3. In the Services window, locate the **Windows Update** service. Right-click on it and select **Stop**.
4. Press **Win + R** to open the Run dialog box.
5. Type the following path in the text field and hit **Enter**.  
C:\Windows\SoftwareDistribution\Download
6. In the File Explorer window, press **Ctrl + A** to select all the files and click the **trash icon** at the top to delete them.
7. Return to the Services window, right-click on the **Windows Update** service, and select **Start**.  
![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/clear-softwaredistribution-folder.jpg)

 If you run into issues while emptying the SoftwareDistribution folder, you can [force delete files in Windows](https://www.makeuseof.com/windows-11-delete-stubborn-files/) using Command Prompt or a third-party tool.

## 4\. Edit Registry Files

 By default, the Disk Cleanup utility does not delete temporary files that are less than seven days old. This is because Windows marks these files as active. However, if you want to delete all the temporary files, regardless of their age, you can make changes to the Windows Registry.

 Since editing registry files is slightly risky, make sure to [back up all registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) as a precaution. Once done, follow these steps to edit registry files:

1. Press **Win + R** to open the Run dialog box.
2. Type **regedit** in the box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer > VolumeCaches > Temporary Files**.
5. In the right pane, double-click the **LastAccess** key.
6. Enter **0** in the Value data field.
7. Click **OK**.  
![Edit DWORD in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-dword-in-registry.jpg)

 Restart your PC after this and try to delete temporary files once again.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123750/7443" target="_top" id="2123750">
  <img src="//a.impactradius-go.com/display-ad/7443-2123750" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123750/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Boot Into Safe Mode

 It's possible that a third-party program or background service is preventing Windows from erasing temporary files on your system. Booting your PC in safe mode can help you avoid any interference, as Windows will only run with essential drivers and services.

 Use one of the many ways to [boot into safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) and try to delete temporary files one more time.

## Get Rid of Temporary Files on Windows

 Clearing temporary files is a great way to free up storage space without deleting any of your apps or important data.

 We hope that one of the above tips was helpful and you were able to delete the temporary files without any problems.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-screen-grab.techidaily.com/new-recording-rivalry-obs-versus-for-2024/"><u>[New] Recording Rivalry OBS Versus for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-streamline-editing-with-these-10-leading-software-tools-for-2024/"><u>[New] Streamline Editing with These 10 Leading Software Tools for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-cinematography-simplified-fades-made-easy-for-2024/"><u>[Updated] Cinematography Simplified Fades Made Easy for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-mastering-the-art-of-text-insertion-in-digital-pictures/"><u>[Updated] Mastering the Art of Text Insertion in Digital Pictures</u></a></li>
<li><a href="https://facebook.techidaily.com/crafting-content-that-resonates-increasing-fb-interactions/"><u>Crafting Content That Resonates: Increasing FB Interactions</u></a></li>
<li><a href="https://some-guidance.techidaily.com/download-free-hd-dvd-ripper-play-your-favorite-films-worry-free-on-ios-devices/"><u>Download Free HD DVD Ripper: Play Your Favorite Films Worry-Free on iOS Devices</u></a></li>
<li><a href="https://fox-that.techidaily.com/essential-guide-11-ways-to-solve-the-issue-of-silent-notifications-on-your-iphone-call-appearance/"><u>Essential Guide: 11 Ways to Solve the Issue of Silent Notifications on Your iPhone Call Appearance</u></a></li>
<li><a href="https://windows11.techidaily.com/expeditious-windows-11-app-accessibility/"><u>Expeditious Windows 11 App Accessibility</u></a></li>
<li><a href="https://windows11.techidaily.com/explore-the-full-potential-of-windows-powertoys-with-these-10-tips/"><u>Explore the Full Potential of Windows PowerToys with These 10 Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/get-up-to-speed-on-windows-11s-user-friendly-taskbar-search-feature/"><u>Get up to Speed on Windows 11’S User-Friendly Taskbar Search Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-enable-controlled-folder-access-in-windows-11-and-11/"><u>How to Enable Controlled Folder Access in Windows 11 & 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-whatsapp-messages-on-vivo-y55s-5g-2023-without-them-knowing-drfone-by-drfone-virtual-android/"><u>How to Track WhatsApp Messages on Vivo Y55s 5G (2023) Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-craft-clearer-crisper-youtube-videos-with-quality-tools/"><u>In 2024, Craft Clearer, Crisper YouTube Videos with Quality Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/one-step-further-batch-to-winexe-journey-unveiled/"><u>One Step Further: Batch-to-WinEXE Journey Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-disconnection-issues-of-razer-hardware-in-win-1011/"><u>Overcoming Disconnection Issues of Razer Hardware in Win 10/11</u></a></li>
<li><a href="https://win-solutions.techidaily.com/persistent-issues-keeping-the-sovled-warno-software-running-smoothly-on-your-computer/"><u>Persistent Issues: Keeping the SOVLED Warno Software Running Smoothly on Your Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-to-turn-off-windows-11-notifies/"><u>Quick Guide to Turn Off Windows 11 Notifies</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaiming-your-controllers-functionality-in-windows/"><u>Reclaiming Your Controller’s Functionality in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagining-your-windows-profile-a-new-username-approach/"><u>Reimagining Your Windows Profile: A New UserName Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-not-available-status-codes-in-windows-os/"><u>Resolving 'Not Available' Status Codes in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/reversing-file-locks-on-windows-os/"><u>Reversing File Locks on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-global-mouse-navigation-made-simple-with-powertoys/"><u>Seamless Global Mouse Navigation Made Simple with PowerToys</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-to-unlocking-windows-11-desktop-toolbar/"><u>Step-by-Step to Unlocking Windows 11 Desktop Toolbar</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-tackle-corrupted-files-and-directories-win10-11-edition/"><u>Strategies to Tackle 'Corrupted' Files & Directories: Win10-11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-task-execution-top-6-windows-performance-monitors/"><u>Streamline Task Execution: Top 6 Windows Performance Monitors</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-managing-your-windows-devices-via-printer-settings/"><u>The Ultimate Guide to Managing Your Windows Devices via Printer Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-disabling-windows-lsa-security-signal/"><u>Troubleshooting: Disabling Windows LSA Security Signal</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-resolving-winrars-sum-verification-failures/"><u>Troubleshooting: Resolving WinRAR's Sum Verification Failures</u></a></li>
<li><a href="https://windows11.techidaily.com/unheard-voices-a-guide-to-fixing-windows-microphone-issues-on-meet/"><u>Unheard Voices: A Guide to Fixing Windows Microphone Issues on Meet</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-design-faux-pas-a-list-of-7/"><u>Windows 11'S Design Faux Pas: A List of 7</u></a></li>
<li><a href="https://extra-hints.techidaily.com/zodiac-influence-in-your-digital-dossier-writing-compelling-biographies/"><u>Zodiac Influence in Your Digital Dossier Writing Compelling Biographies</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>