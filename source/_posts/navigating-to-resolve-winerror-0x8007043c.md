---
title: Navigating to Resolve WinError 0X8007043C
date: 2024-06-25T12:36:57.194Z
updated: 2024-06-26T12:36:57.194Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating to Resolve WinError 0X8007043C
excerpt: This Article Describes Navigating to Resolve WinError 0X8007043C
keywords: WinError Solution Guide,0X8007043C Fix Methods,Error Code 0X8007043C Resolution,System File Corruption Fix,Windows Error Log Analysis,Error Handling for 0X8007043C,Troubleshooting WinError 0X8007043C
thumbnail: https://thmb.techidaily.com/2406330bf931e26fe8a1a800921df2ca60aab8badbd84f3b12dc61e65092f344.jpg
---

## Navigating to Resolve WinError 0X8007043C

 The Media Creation Tool lets you upgrade your PC to a new Windows version or create a bootable Windows USB drive. At times, when you try to run the tool, you may encounter the error code 0x8007043C - 0x90017.

 The primary reason for this error is insufficient permission to run the tool or if it has been blocked from running on your PC. You can unblock it from the tool's properties to fix the error. Here is how to fix the Media Creation Tool 0x8007043C - 0x90017 error and perform an upgrade or create a bootable drive.

## 1\. Run the Media Creation Tool as an Administrator

 You can fix permission issues by executing the Media Creation Tool with administrator privileges. By default, the tool does not require administrator rights to run. But you can[manually run Windows apps as an administrator](https://www.makeuseof.com/tag/ways-to-run-a-program-as-administrator-in-windows/) to see if that resolves the error.

To run Media Creation Tool as administrator:

1. Open File Explorer and navigate to where you have saved the**mediacreationtool.exe** file.
2. Right-click on the**Mediacreationtool.exe** file and select**Run as administrator.**  
![run media creation tool as administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-media-creation-tool-as-administrator.jpg)
3. Click**Yes** when prompted by UAC. Wait for the tool to launch and check for any improvements.

## 2\. Unblock the Media Creation Tool

 Windows can block suspicious executable files from running to protect your computer. However, it can also block genuine files due to false positives.

 If you have downloaded the Media Creation Tool from the Microsoft website, check if the file is blocked on your PC. If yes, you can unblock the executable file from the Properties dialog. Here’s how to do it.

1. Navigate to the location where the Media Creation Tool is saved.
2. Select and right-click on the tool and select**Properties** .
3. In the**General** tab, locate the**Security** section.
4. Next, check the**Unblock** option.  
![unblock media creation tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/unblock-media-creation-tool.jpg)
5. Click**Apply** , and the security option will disappear.
6. Next, click**OK** to apply the changes.
7. Run the Media Creation Tool again, and it should work without the 0x8007043C - 0x90017 error.

## 3\. Install Any Pending Windows Updates

 If the error occurs during an upgrade, ensure you have installed all the latest updates available for your PC. Often Windows updates consist of performance improvements and bug fixes. Install all the updates to see if that helps you resolve any issues interrupting the upgrade process.

To update your Windows computer:

1. Press**Win + I** to open**Settings** .
2. Open the**Windows update** tab in the left pane.
3. Click on**Check for updates** to find the pending updates.  
![windows 11 update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-update.jpg)
4. If available, click on**Download & Install** and wait for the updates to install. Restart your PC and run the tool again to see if the error is resolved.

## 4\. Run the Windows Update Troubleshooter

 The built-in Windows Update troubleshooter is a great way to fix Windows Update issues on Windows 11\. It will scan the system for issues and try to fix them automatically.

To run the Windows Update Troubleshooter:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, scroll down and click on**Troubleshoot** .  
![Windows 11 settings troubleshoot](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-settings-troubleshoot.jpg)
3. Next, click on**Other troubleshooters.**  
![Windows-11-settings-troubleshoot-other-troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-settings-troubleshoot-other-troubleshooters.jpg)
4. Under the**Most frequent** section, click the**Run** button for**Windows Update.**  
![windows update troubleshooter run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-update-troubleshooter-run.jpg)
5. The update troubleshooter will initialize diagnostic and scan for issues. If found, it will apply the fix and show a status report. With the Windows Update dialog open, run Media Creation Tool and check if the error is resolved.
6. If not, click**No** in the Windows Update troubleshooter dialog.
7. Next, click on**View detailed** information. Here you can view the issues found and potential issues that were checked.

## 5\. Check for a Third-Party Antivirus Conflict

 Third-party antivirus can be overzealous and block genuine system modifications as malicious. You can disable the security app temporarily to determine if your third-party antivirus is triggering the error.

 Once disabled, relaunch the Media Creation Tool and check if the error persists. If not, check and reconfigure your antivirus settings or switch to one of the[best antivirus solutions on Windows](https://www.makeuseof.com/windows-11-antivirus-apps/) .

## 6\. Run the DISM and System File Checker Tool

 Deployment Image Servicing and Management (DISM) is a command-line tool to repair your Windows 10 and 11 images. It can look for corrupted or missing system files and repair them to fix critical errors on your PC.

 System File Checker utility can help you fix malfunctioning Windows functions. It will scan the system for issues and, if detected, restore the necessary files to fix the problem. You can run the DISM and System File Checker tools in tandem to get the best result. Here’s how to do it.

To run the DISM and System File Checker Tool:

1. Press the**Win** key and type**cmd** .
2. Right-click on**Command** **Prompt** and select**Run as administrator.**
3. In the Command Prompt window, type the following command to run the DISM tool:  
DISM.exe /Online /Cleanup-image /Restorehealth
4. ![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dism-scan-health-restore-health-command-prompt.jpg)  
 Press**Enter** to execute the command. It may take some time for the process to complete. Once the process reaches 100%, you can run the System File Checker tool.
5. Type the following command and press**Enter** to run the System File Checker utility:  
sfc /scannow
6. The verification can take several minutes. So wait for the verification to reach 100%. The return will indicate if any issue is found and if the tool was able to fix it.
7. Type**exit** and press**Enter** to close the Command Prompt.

## 7\. Use Rufus to Create a Bootable USB Drive

 While Media Creation Tools lets you create a bootable drive, it is not your only option. You can use a popular third-party app, Rufus, to[create a bootable Windows USB drive](https://www.makeuseof.com/windows-11-create-bootable-usb-drive/) . You can[download a Windows 11 ISO file](https://www.makeuseof.com/windows-11-download-iso/) from the Microsoft servers and then use it to create an installation media using Rufus.

 Rufus is safe to use and offers some customization, such as choosing a partition format. You can also download the ISO file using Rufus.

## 8\. Perform a Repair Reinstall or Clean Install Windows

 Before we do a full clean of Windows, consider performing a repair reinstall. This allows you to perform an in-place upgrade and[reinstall the Windows OS without deleting your files and apps](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/) .

 If all else fails, a clean install may be necessary. Make sure to create a backup of your data and then learn[how to clean install Windows 11](https://www.makeuseof.com/how-to-clean-install-windows-11/) .

## Fixing the Media Creation Tool Error 0x8007043C - 0x90017 Error

 The 0x8007043C - 0x90017 Media Creation Tool error is often due to an insufficient permission issue. You can unblock the utility in the Properties dialog to run the utility without the error. Only in rare instances, you may need to perform a clean install due to system file corruption.


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
<li><a href="https://windows11.techidaily.com/how-to-reactivate-lost-bluetooth-listings-dmi/"><u>How to Reactivate Lost Bluetooth Listings DMI</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensible-approach-to-fixing-notepad-non-openness-in-windows/"><u>A Comprehensible Approach to Fixing Notepad Non-Openness in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-desktop-aesthetics-best-pc-time-saver-apps-listed/"><u>Boost Desktop Aesthetics – Best PC Time Saver Apps Listed</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-win11-uis-image-summaries/"><u>Customize Win11 UI's Image Summaries</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-unstartable-windows-vms-with-vmware/"><u>Solutions for Unstartable Windows VMs with VMware</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-transition-from-ical-to-windows-calendar/"><u>Navigating the Transition: From iCal to Windows Calendar</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionize-your-security-crafting-unique-lock-patterns-for-windows-11/"><u>Revolutionize Your Security: Crafting Unique Lock Patterns for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-guidance-manual-time-zone-setup-for-windows-users/"><u>Expert Guidance: Manual Time Zone Setup for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-correct-non-empty-directory-error-code-0x80070091-in-win11/"><u>How to Correct Non-Empty Directory Error (Code: 0X80070091) in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-launch-hacks-opening-windows-11-apps-faster/"><u>Quick Launch Hacks: Opening Windows 11 Apps Faster</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/the-complete-tutorial-adding-soundtracks-to-gif-files-using-macos-tools/"><u>The Complete Tutorial Adding Soundtracks to GIF Files Using macOS Tools</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-ignite-your-creative-journey-blending-photography-and-videos-through-pixiz/"><u>In 2024, Ignite Your Creative Journey  Blending Photography & Videos Through Pixiz</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-sign-out-of-apple-id-from-iphone-14-pro-without-password-by-drfone-ios/"><u>In 2024, How to Sign Out of Apple ID From iPhone 14 Pro without Password?</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-a-deep-dive-into-ideal-instagram-post-times-for-2024/"><u>[Updated] A Deep Dive Into Ideal Instagram Post Times for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-mastering-the-art-of-ignoring-ig-suggestions/"><u>[Updated] In 2024, Mastering the Art of Ignoring IG Suggestions</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-chromes-best-deals-on-screen-recorder-free-tools-for-2024/"><u>[Updated] Chrome's Best Deals on Screen Recorder Free Tools for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-transformative-soundscape-design-proven-strategies-for-smooth-volume-fading-and-elevating-with-adobe-after-effects/"><u>New In 2024, Transformative Soundscape Design Proven Strategies for Smooth Volume Fading and Elevating with Adobe After Effects</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-the-ultimate-videopad-review-features-pricing-and-alternatives-for-2024/"><u>New The Ultimate Videopad Review Features, Pricing, and Alternatives for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-essential-tips-for-achieving-facebooks-trusted-marker/"><u>[Updated] 2024 Approved  Essential Tips for Achieving Facebook's Trusted Marker</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-trimming-mp4-content-a-focus-on-solo-soundtrack/"><u>In 2024, Trimming MP4 Content A Focus on Solo Soundtrack</u></a></li>
</ul></div>
