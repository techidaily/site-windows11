---
title: How to Restart and Streamline Windows Update Processes
date: 2024-07-11T22:03:41.207Z
updated: 2024-07-12T22:03:41.207Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Restart and Streamline Windows Update Processes
excerpt: This Article Describes How to Restart and Streamline Windows Update Processes
keywords: Windows Update Optimization,Quick Windows Update Fix,Simplify Windows Updates,Speedup Windows Patching,Efficient Windows Update,Automate Windows Updates,Enhance Windows Update Speed
thumbnail: https://thmb.techidaily.com/773bcb287706a7e5add3e76fb4807bc2dd418c60c96896292c9c0c5d9f8bf9d7.jpg
---

## How to Restart and Streamline Windows Update Processes

 When addressing errors and issues associated with a system update, you may need to reset the Windows Update components. You can achieve this by running a few commands in the Command Prompt or by creating and executing a batch file.

 This guide will provide a detailed walkthrough for both methods, allowing you to effectively reset the Windows Update components.

## 1\. How to Reset the Windows Update Components Manually

 The most common method for resetting Windows Update components is through the Command Prompt. Here are the steps you can follow.

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt shows up.
3. Copy and paste the following commands one by one and press **Enter** after each command to stop each service related to Windows Update.  
`net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc`  
![Reset Windows Update Components Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-windows-update-components-using-command-prompt.jpg)
4. Run the following command to delete the **qmgr\*.dat** files.  
`Del "%ALLUSERSPROFILE%\Application Data\Microsoft\Network\Downloader\*.*"`
5. Enter **Y** to confirm.

1. Type the following commands and press **Enter** after each to delete all the Windows Update files.  
`rmdir %systemroot%\SoftwareDistribution /S /Q  
rmdir %systemroot%\system32\catroot2 /S /Q`
2. Type the following commands and press **Enter** after each to reset the BITS and Windows Update services to their default security descriptors.  
`sc.exe sdset bits D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
sc.exe sdset wuauserv D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)`
3. Now, run the following command to navigate to the **System32** folder.  
`cd /d %windir%\system32`
4. Copy and paste the following commands individually and press **Enter** after each to re-register all the BITS and Windows Update files.  
`regsvr32.exe /s atl.dll  
regsvr32.exe /s urlmon.dll  
regsvr32.exe /s mshtml.dll  
regsvr32.exe /s shdocvw.dll  
regsvr32.exe /s browseui.dll  
regsvr32.exe /s jscript.dll  
regsvr32.exe /s vbscript.dll  
regsvr32.exe /s scrrun.dll  
regsvr32.exe /s msxml.dll  
regsvr32.exe /s msxml3.dll  
regsvr32.exe /s msxml6.dll  
regsvr32.exe /s actxprxy.dll  
regsvr32.exe /s softpub.dll  
regsvr32.exe /s wintrust.dll  
regsvr32.exe /s dssenh.dll  
regsvr32.exe /s rsaenh.dll  
regsvr32.exe /s gpkcsp.dll  
regsvr32.exe /s sccbase.dll  
regsvr32.exe /s slbcsp.dll  
regsvr32.exe /s cryptdlg.dll  
regsvr32.exe /s oleaut32.dll  
regsvr32.exe /s ole32.dll  
regsvr32.exe /s shell32.dll  
regsvr32.exe /s initpki.dll  
regsvr32.exe /s wuapi.dll  
regsvr32.exe /s wuaueng.dll  
regsvr32.exe /s wuaueng1.dll  
regsvr32.exe /s wucltui.dll  
regsvr32.exe /s wups.dll  
regsvr32.exe /s wups2.dll  
regsvr32.exe /s wuweb.dll  
regsvr32.exe /s qmgr.dll  
regsvr32.exe /s qmgrprxy.dll  
regsvr32.exe /s wucltux.dll  
regsvr32.exe /s muweb.dll  
regsvr32.exe /s wuwebv.dll`
5. Type the following and press **Enter** to reset Winsock (Windows Sockets).  
`netsh winsock reset`
6. Copy and paste the following commands one by one and press **Enter** after each to restart the services related to Windows Update.  
`net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`

 Close the Command Prompt window and restart your PC to apply the changes. If you're interested in discovering more useful commands, check our guide on the [best Command Prompt commands](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/) for Windows.

## 2\. How to Reset the Windows Update Components Using a Batch File

 Another way to reset Windows Update components is to [create and run a batch file in Windows](https://www.makeuseof.com/tag/write-simple-batch-bat-file/). Here are the steps to make one:

1. Press **Win + S** to open the search menu.
2. Type **Notepad** in the search box and press **Enter**.
3. Copy and paste the following command in the Notepad window.  
`net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc  
Del "%ALLUSERSPROFILE%\Application Data\Microsoft\Network\Downloader\*.*"  
rmdir %systemroot%\SoftwareDistribution /S /Q  
rmdir %systemroot%  
system32\catroot2 /S /Q  
sc.exe sdset bits D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
sc.exe sdset wuauserv D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
cd /d %windir% system32  
regsvr32.exe /s atl.dll  
regsvr32.exe /s urlmon.dll  
regsvr32.exe /s mshtml.dll  
regsvr32.exe /s shdocvw.dll  
regsvr32.exe /s browseui.dll  
regsvr32.exe /s jscript.dll  
regsvr32.exe /s vbscript.dll  
regsvr32.exe /s scrrun.dll  
regsvr32.exe /s msxml.dll  
regsvr32.exe /s msxml3.dll  
regsvr32.exe /s msxml6.dll  
regsvr32.exe /s actxprxy.dll  
regsvr32.exe /s softpub.dll  
regsvr32.exe /s wintrust.dll  
regsvr32.exe /s dssenh.dll  
regsvr32.exe /s rsaenh.dll  
regsvr32.exe /s gpkcsp.dll  
regsvr32.exe /s sccbase.dll  
regsvr32.exe /s slbcsp.dll  
regsvr32.exe /s cryptdlg.dll  
regsvr32.exe /s oleaut32.dll  
regsvr32.exe /s ole32.dll  
regsvr32.exe /s shell32.dll  
regsvr32.exe /s initpki.dll  
regsvr32.exe /s wuapi.dll  
regsvr32.exe /s wuaueng.dll  
regsvr32.exe /s wuaueng1.dll  
regsvr32.exe /s wucltui.dll  
regsvr32.exe /s wups.dll  
regsvr32.exe /s wups2.dll  
regsvr32.exe /s wuweb.dll  
regsvr32.exe /s qmgr.dll  
regsvr32.exe /s qmgrprxy.dll  
regsvr32.exe /s wucltux.dll  
regsvr32.exe /s muweb.dll  
regsvr32.exe /s wuwebv.dll  
netsh winsock reset  
netsh winsock reset proxy  
net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`
4. Click the **File** menu at the top, then **Save as**.  
![Save a Notepad File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/save-a-notepad-file.jpg)
5. Enter **Reset Windows Components.bat** in the name field and specify your preferred location for saving the file.
6. Click the **Save as type** drop-down menu to select **All files**, then click on **Save**.
7. Locate the saved batch file on your PC. Right-click on it and select **Run as administrator** from the context menu.
8. Select **Yes** when the User Account Control (UAC) prompt appears.  
![Reset Windows Update Components Using a Batch File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-windows-update-components-using-a-batch-file.jpg)

 Once you've executed the batch file, feel free to keep it around. That way, the next time you encounter problems with Windows Update, you can run the file again without having to repeat the above steps.

## Reset the Windows Update Components to Fix Problems

 Downloading and installing Windows updates may not always be smooth. In such cases, resetting the Windows Update components can prove effective. However, if that doesn't work, you may have to try your luck with other Windows Update fixes.

 This guide will provide a detailed walkthrough for both methods, allowing you to effectively reset the Windows Update components.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-ultimate-guide-to-gopro-hero5-time-lapse-photography/"><u>2024 Approved  The Ultimate Guide to GoPro Hero5 Time-Lapse Photography</u></a></li>
<li><a href="https://windows11.techidaily.com/what-to-do-when-the-audio-services-are-not-responding-on-windows/"><u>What to Do When the Audio Services Are Not Responding on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-uncovering-the-missing-taskbar-in-full-screen/"><u>Guide to Uncovering the Missing Taskbar in Full Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-wizardry-workshop-end-multiple-programs-together/"><u>Windows Wizardry Workshop: End Multiple Programs Together</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-game-drives-in-xbox-app/"><u>The Ultimate Guide to Game Drives in Xbox App</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-resolving-your-sound-cards-irq-mess/"><u>Decoding and Resolving Your Sound Card's IRQ Mess</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tuning-windows-11s-online-threat-detection/"><u>Fine-Tuning Windows 11'S Online Threat Detection</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-reversing-silent-blocks-on-tiktok-features/"><u>[New] In 2024, Reversing Silent Blocks on TikTok Features</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-error-495-while-downloadupdating-android-apps-on-realme-c55-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Error 495 While Download/Updating Android Apps On Realme C55 | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-15-recommended-stop-motion-films-of-all-time/"><u>[Updated] 15 Recommended Stop Motion Films of All Time</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-pc-hardware-requirement-errors/"><u>Fixing Windows PC Hardware Requirement Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-integrating-alternative-antiviruses-with-ms-defender/"><u>Tips for Integrating Alternative Antiviruses with MS Defender</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-tutorial-for-managing-archive-files-via-cmd/"><u>The Ultimate Tutorial for Managing Archive Files via CMD</u></a></li>
<li><a href="https://windows11.techidaily.com/from-spoken-voice-to-textual-output-in-seconds-whispers-guide/"><u>From Spoken Voice to Textual Output in Seconds - Whisper's Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-direct-access-to-windows-11-dialer-feature/"><u>Unlocking Direct Access to Windows 11 Dialer Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/visual-disk-management-in-context-menus-for-win-11/"><u>Visual Disk Management in Context Menus for Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/a-glimpse-at-future-ready-windows-with-update-22h2s-features/"><u>A Glimpse at Future-Ready Windows with Update #22H2's Features</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-second-shuffle-solved/"><u>Windows Second Shuffle Solved</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-bridging-the-gap-converting-snapchats-flash-into-files-for-2024/"><u>[Updated] Bridging the Gap  Converting Snapchat's Flash Into Files for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-achieve-unified-fileset-in-two-windows-pcs-via-aoemi/"><u>How to Achieve Unified Fileset in Two Windows PCs via AOEMi</u></a></li>
<li><a href="https://windows11.techidaily.com/highest-rated-windows-encryption-software-guide-150-chars/"><u>Highest Rated Window's Encryption Software Guide (150 Chars)</u></a></li>
<li><a href="https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-vivo-y36i-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix the Error of Unfortunately the Process.com.android.phone Has Stopped on Vivo Y36i | Dr.fone</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-what-is-an-ai-presentation-maker-wondershare-virbo-glossary-for-2024/"><u>New What Is an AI Presentation Maker? | Wondershare Virbo Glossary for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-strategies-for-isolating-unfamiliar-users-in-win-11/"><u>Effective Strategies for Isolating Unfamiliar Users in Win 11</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-detailed-guide-to-screen-record-skype-via-obs/"><u>In 2024, Detailed Guide to Screen Record Skype via OBS</u></a></li>
<li><a href="https://extra-resources.techidaily.com/pixelcasting-app-reviews/"><u>PixelCasting App Reviews</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-permission-fixes-for-installer-problems/"><u>Streamlining Permission Fixes for Installer Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-defaults-permissions-restoration-guide/"><u>Unlocking Defaults: Permissions Restoration Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/a-beginners-guide-to-accessibility-tools-on-windows/"><u>A Beginner's Guide to Accessibility Tools on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-performance-monitor-not-working-on-windows/"><u>How to Fix the Performance Monitor Not Working on Windows</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-focus-on-the-main-sound-in-video-capturing-free-advice/"><u>[Updated] 2024 Approved  Focus on the Main Sound in Video Capturing (Free Advice)</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-productivity-crafting-shortcuts-to-store-uwp-apps-on-windows/"><u>Boosting Productivity: Crafting Shortcuts to Store UWP Apps on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-archive-file-history-in-windows-11/"><u>Unlocking the Archive: File History in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/cease-windows-tally-of-new-software-activities/"><u>Cease Windows' Tally of New Software Activities</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-how-to-share-videos-on-twitter-on-your-phone-without-retweeting/"><u>In 2024, How to Share Videos on Twitter on Your Phone Without Retweeting?</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-laptops-screen-with-yellowish-discoloration/"><u>Correcting Laptop's Screen with Yellowish Discoloration</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-guide-for-pcs-memory-tool-issues/"><u>A Comprehensive Guide for PC's Memory Tool Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/unblock-your-computers-usb-hub-windows-fix-guide/"><u>Unblock Your Computer's USB Hub: Windows Fix Guide</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-momentum-at-rest-best-idle-pc-games/"><u>[Updated] 2024 Approved  Momentum at Rest  Best Idle PC Games</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-change-your-vivo-y78t-location-on-twitter-drfone-by-drfone-virtual-android/"><u>How to Change your Vivo Y78t Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-adjust-lockout-frequency-after-incorrect-user-credentials-for-windows-11/"><u>How to Adjust Lockout Frequency After Incorrect User Credentials for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/decisive-actions-for-dictating-a-successful-window-update/"><u>Decisive Actions for Dictating a Successful Window Update</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-productivity-masterful-windows-shortcuts-guide/"><u>Boosting Productivity: Masterful Windows Shortcuts Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-your-potential-7-proven-techniques-to-master-windows-based-studying/"><u>Unlock Your Potential: 7 Proven Techniques to Master Windows-Based Studying</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-isdonedll-error-in-modern-windows-editions/"><u>Addressing ISDone.dll Error in Modern Windows Editions</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-mkv-file-trimming-made-simple-top-3-mac-apps-for-2024/"><u>Updated MKV File Trimming Made Simple Top 3 Mac Apps for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/choosing-between-windows-11-home-and-pro-your-ideal-edition/"><u>Choosing Between Windows 11 Home & Pro: Your Ideal Edition</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-2024-how-to-record-shots-and-edit-them-using-wonderware-filmora-to-create-the-super-jump-effect-a-complete-guide-for-beginners/"><u>In 2024, How to Record Shots and Edit Them Using Wonderware Filmora to Create the Super Jump Effect? A Complete Guide for Beginners</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-in-2024-master-amazon-live-features-pro-tips-and-future-trends/"><u>Updated In 2024, Master Amazon Live Features, Pro Tips and Future Trends</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-powerful-literary-trailer-vids/"><u>2024 Approved  Powerful Literary Trailer Vids</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-failed-app-install-in-windows-store/"><u>Troubleshooting Failed App Install in Windows Store</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehending-the-safeguarded-state-of-windows-11/"><u>Comprehending the Safeguarded State of Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/clipchamp-patch-enable-installation-in-windows-11/"><u>ClipChamp Patch: Enable Installation in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/boldly-block-wi-fi-signals-in-windows/"><u>Boldly Block Wi-Fi Signals in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/three-steps-to-validate-windows-11-activation/"><u>Three Steps to Validate Windows 11 Activation</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-change-screen-order-in-pc/"><u>How to Change Screen Order in PC</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-mp3-conversion-made-simple-3-effective-techniques-for-podcast-files-for-2024/"><u>Updated MP3 Conversion Made Simple 3 Effective Techniques for Podcast Files for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-best-free-subtitles-and-downloader-guide/"><u>[New] In 2024, Best Free Subtitles & Downloader Guide</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-seamless-integration-of-snap-camera-for-enhanced-online-participation/"><u>[New] Seamless Integration of Snap Camera for Enhanced Online Participation</u></a></li>
</ul></div>
