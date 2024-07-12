---
title: Streamlining Windows Update Fixes for Error 0X800736CC
date: 2024-07-11T21:41:50.751Z
updated: 2024-07-12T21:41:50.751Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Streamlining Windows Update Fixes for Error 0X800736CC
excerpt: This Article Describes Streamlining Windows Update Fixes for Error 0X800736CC
keywords: Windows Update Troubleshooting,Fix Error 0X800736CC,Error Code X736CC Resolution,Streamline Windows Updates,XPcc Error Fix Guide,Microsoft Update Solution,System Error 0X800736CC
thumbnail: https://thmb.techidaily.com/477a0b3e8eaad5a77258f27b87d4827ff92a53251f6cf584b61b0ab39b309f07.jpg
---

## Streamlining Windows Update Fixes for Error 0X800736CC

 Windows Update keeps your computer safe and secure with the latest security patches. However, you might encounter errors while installing these updates, like 0x800736cc. This error code stops you from deploying critical security updates, leaving your computer vulnerable. In this guide, we’ll show you some troubleshooting steps to fix this error.

## 1\. Restart Your PC

 The first thing you need to do is [restart your computer](https://www.makeuseof.com/windows-restart-methods/). Although it may seem too simplistic, you'd be surprised how often this resolves various issues. When your computer reboots, it clears temporary files and processes that could cause problems. This includes incomplete Windows updates that failed to install or encountered installation errors.

 A quick reboot can bypass the error and complete the update, so it should be your primary course of action before delving into more intricate troubleshooting methods.

## 2\. Run the Windows Update Troubleshooter

 If restarting the PC doesn't work, you can use the Windows Update Troubleshooter. This built-in utility solves minor problems that prevent Windows from updating correctly.

 To run the Windows Update Troubleshooter, follow these steps:

1. Press **Win + S** to open the Windows Search bar.
2. Type in **Troubleshoot** and select **Troubleshoot Settings** from the results list.
3. On the right sidebar, click **Other troubleshooters**.  
![Other troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/other-troubleshooters.jpg)
4. Under **Most frequent**, locate **Windows Update** and click **Run**.  
![Run Windows Update Troubleshooter-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-windows-update-troubleshooter-1.jpg)

 Follow the on-screen instructions to complete the troubleshooting process. It may take a few minutes for the tool to finish its job.

## 3\. Clear the Windows Update Cache

 Windows Update Cache stores temporary files and processes related to updates. If these files become corrupted, they can interfere with the update process and cause errors like 0x800736cc. In this case, clearing the cache can fix the problem.

 To clear the Windows Update Cache, do the following:

1. Open the Start menu.
2. Type **services.msc** in the search box and hit Enter. The Services window will open.
3. Scroll down and locate the **Windows Update** service. Then, right-click on it and select **Stop**. Doing so temporarily stops Windows Update.
4. Now, [open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to this location:  
`C:\Windows\SoftwareDistribution`
5. In the SoftwareDistribution folder, delete all files and folders. This is just temporary data, so removing it won't affect your computer.  
![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/clear-softwaredistribution-folder.jpg)
6. After deleting the files, head back to the Services window, right-click on the **Windows Update** service, and select **Start**. This step restarts the Windows Update service.

 Now restart your computer. It will allow Windows Update to recreate cache files from scratch.

## 4\. Disable your Antivirus Temporarily

 Security software interferes with Windows Update and causes errors. To avoid this issue, [temporarily disable your security program](http://www.makeuseof.com/how-to-turn-off-windows-defender/) before running updates. Once you have disabled it, restart the computer and install the update again. If it works, it was your security software that caused the issue.

 Remember that disabling security software leaves your computer vulnerable to malware attacks, so enable it immediately.

## 5\. Reset Windows Update Components

 Windows Update components include files and processes crucial to the update process. If these components become corrupted or damaged, Windows Update cannot run correctly. In this case, you must reset the components to their original state.

 Fortunately, there’s an easy way to do this. Microsoft provides a batch script called Reset Windows Update Tool that resets various Windows Update components with just a few clicks.

 To reset Windows Update components, follow these steps:

1. Click on Start and type **Notepad** in the search bar.
2. Right-click on Notepad and select **Run as administrator**.
3. If the User Account Control window pops up, click **Yes** to continue.
4. In the Notepad window, copy and paste the following code:  
`<code>net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc  
Del "%ALLUSERSPROFILE%\Application Data\Microsoft\Network\Downloader\*.*"  
rmdir %systemroot%\SoftwareDistribution /S /Q  
rmdir %systemroot%  
system32\catroot2 /S /Q  
sc.exe sdset bits D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
sc.exe sdset wuauserv D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
cd /d %windir%  
system32  
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
5. The above commands form part of a script to reset Windows Update components. After you paste the code into Notepad, click **File** and select **Save as**.
6. In the Save As window, select **All files** from the drop-down menu.
7. Type **ResetWindowsUpdate.bat** as the file name and save it to your desktop.  
![Reset Windows Update Components](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reset-windows-update-components.jpg)
8. Now, you have the batch script on your desktop. Right-click on it and select **Run as administrator**.
9. When the UAC pops up, click **Yes** to grant elevated privileges.

 The script will take a few minutes to run. When it's finished, close the Command Prompt window and restart your computer. Once your computer restarts, check if the 0x800736cc error is resolved.

## 6\. Try Generic Windows Update Fixes

 Besides the methods listed above, you can also try some generic Windows Update fixes. These methods usually work if a temporary issue or corrupted system files cause the error.

 Here are some generic Windows Update fixes you can try:

* [Repair Corrupted System Files](https://www.makeuseof.com/windows-built-in-repair-tools/) \- Run the System File Checker tool to scan and repair corrupted system files. If you need help with this, you can find detailed instructions in our [SFC guide](https://www.makeuseof.com/system-file-checker-sfc-windows/). You can also use the Deployment Image Service and Management (DISM) tool to replace broken files with healthy ones.
* [Perform a Clean Boot](https://www.makeuseof.com/clean-boot-windows-11/) \- Clean Boot can identify software conflicts causing the error. It disables all non-essential services and programs from running in the background. That way, you can isolate the problematic process and resolve the issue.
* [Manually Install the Update](https://www.makeuseof.com/update-windows-manually/) \- If Windows Update fails to install or is stuck, you can download and install it manually

## Fixing Windows Update Error 0x800736cc

 As you can see, multiple ways exist to fix the Windows Update error. We hope one of these methods has solved your problem, and you can now successfully install Windows Update. If nothing else works, you can restore your computer to a previous state or reinstall Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/altering-windows-service-for-installation-controls/"><u>Altering Windows Service for Installation Controls</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-blunders-fix-windows-color-management-fiascos/"><u>Bypassing Blunders: Fix Windows Color Management Fiascos</u></a></li>
<li><a href="https://screen-recording.techidaily.com/1715860187220-updated-the-ultimate-guide-to-setting-up-a-group-conversation-that-caters-to-all-systems-in-skype/"><u>[Updated] The Ultimate Guide to Setting up a Group Conversation that Caters to All Systems in Skype.</u></a></li>
<li><a href="https://windows11.techidaily.com/alter-ip-settings-with-confidence-windows-11/"><u>Alter IP Settings with Confidence (Windows 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-win-1011s-xc0f1103f-with-geforce-error/"><u>Addressing Win 10/11'S XC0F1103F with GeForce Error</u></a></li>
<li><a href="https://network-issues.techidaily.com/solutions-for-lenovo-screen-glitches/"><u>Solutions for Lenovo Screen Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-overcoming-windows-resolution-riddles/"><u>A Guide to Overcoming Windows Resolution Riddles</u></a></li>
<li><a href="https://windows11.techidaily.com/accessing-the-internet-without-a-browser-post-setup/"><u>Accessing the Internet Without a Browser Post-Setup</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-video-editing-pro-tips-controlling-speed-in-camtasia-for-2024/"><u>New Video Editing Pro Tips Controlling Speed in Camtasia for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/8-ways-to-fix-the-windows-pin-not-working-in-windows-11-and-11/"><u>8 Ways to Fix the Windows PIN Not Working in Windows 11 & 11</u></a></li>
<li><a href="https://article-helps.techidaily.com/stream-the-best-games-list-9/"><u>Stream the Best Games  List #9</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-key-frames-per-second-in-superior-slow-motion-imaging/"><u>2024 Approved  Key Frames per Second in Superior Slow Motion Imaging</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-win-valorant-loading-times-quickly/"><u>Accelerate Win-Valorant Loading Times Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/8-essential-fixes-for-resistant-windows-pin-locks/"><u>8 Essential Fixes for Resistant Windows PIN Locks</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-failures-fixing-vagrant-boot-problems-win11/"><u>Bypassing Failures: Fixing Vagrant Boot Problems Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-metric-monitoring-of-wifi-networks-via-win11-settings/"><u>Adjusting Metric Monitoring of Wifi Networks via Win11 Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/accessing-control-panel-with-ease-on-pcs/"><u>Accessing Control Panel with Ease on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/bootable-windows-11-flashdrive-top-3-efficient-techniques/"><u>Bootable Windows 11 Flashdrive: Top 3 Efficient Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-silencing-windows-11-alerts-benefits-unveiled/"><u>Avoid Silencing Windows 11 Alerts: Benefits Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-windows-11-pc-life-hacks-for-older-systems/"><u>Bypass Windows 11: PC Life Hacks for Older Systems</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-flash-dead-oneplus-ace-2-pro-safely-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Flash Dead OnePlus Ace 2 Pro Safely | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-frp-lock-on-tecno-camon-20-premier-5g-by-drfone-android-unlock-remove-google-frp/"><u>Remove FRP Lock on Tecno Camon 20 Premier 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-efficiency-best-keys-for-auto-clicking/"><u>Boost Efficiency: Best Keys for Auto Clicking</u></a></li>
<li><a href="https://windows11.techidaily.com/bigger-is-not-better-limited-minipc-zest/"><u>Bigger Is Not Better - Limited MiniPC Zest</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-flash-dead-poco-x5-pro-safely-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Flash Dead Poco X5 Pro Safely | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-why-obs-wont-start-on-your-pc/"><u>Breaking Down Why OBS Won't Start on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/begin-your-media-adventure-windows-media-player/"><u>Begin Your Media Adventure: Windows Media Player</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/supercharge-your-content-key-seo-elements-for-youtube-for-2024/"><u>Supercharge Your Content  Key SEO Elements for YouTube for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/banish-os-requirement-warning-labels-in-windows-11/"><u>Banish OS Requirement Warning Labels in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-win11-boot-time-quick-tips-for-speedier-launches/"><u>Boosting Win11 Boot Time: Quick Tips for Speedier Launches</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/unlock-apple-iphone-11-without-passcode-easily-drfone-by-drfone-ios/"><u>Unlock Apple iPhone 11 Without Passcode Easily | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/adapting-oculus-quest-3-for-windows-os-vr-environment/"><u>Adapting Oculus Quest 3 for Windows OS VR Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/adopting-a-context-menu-toolbar-alert-for-routine-update-checks-on-windows-11plus11/"><u>Adopting a Context Menu Toolbar Alert for Routine Update Checks on Windows 11+11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-11-year-old-video-sensation-unprecedented-wealth-accumulation/"><u>[New] 2024 Approved  11-Year-Old Video Sensation  Unprecedented Wealth Accumulation</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-a-found-iphone-6s-plus-drfone-by-drfone-ios/"><u>How To Unlock A Found iPhone 6s Plus? | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-integrating-technology-effective-school-vid-eds/"><u>2024 Approved  Integrating Technology  Effective School Vid Eds</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-budget-drone-expeditions-top-5-affordable-options/"><u>2024 Approved  Budget Drone Expeditions  Top 5 Affordable Options</u></a></li>
<li><a href="https://windows11.techidaily.com/camouflage-linguistic-separator-on-win11-status-bar/"><u>Camouflage Linguistic Separator on Win11 Status Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/beginners-blueprint-to-conquering-diablo/"><u>Beginner’s Blueprint to Conquering Diablo</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-prints-with-microsofts-edge-shield-windows-11/"><u>Activating Prints with Microsoft's Edge Shield (Windows 11)</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-begin-recording-webcam-via-vlc/"><u>[Updated] Begin Recording Webcam via VLC</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-streamline-your-collaboration-secrets-to-perfectly-planned-google-meets/"><u>[New] 2024 Approved  Streamline Your Collaboration  Secrets to Perfectly Planned Google Meets</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/in-2024-youtubes-music-magic-best-free-tools-for-wav-conversion/"><u>In 2024, YouTube's Music Magic  Best Free Tools for WAV Conversion</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-life-to-windows-11-desktops-with-interactive-wallpapers/"><u>Bring Life to Windows 11 Desktops with Interactive Wallpapers</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/ios-guide-your-step-by-step-vr-video-experience-for-2024/"><u>IOS Guide  Your Step-by-Step VR Video Experience for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-tips-for-adding-sound-in-snipping-tool-recordings-max-156/"><u>Advanced Tips for Adding Sound in Snipping Tool Recordings (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/backup-your-cortana-data-for-future-reference-windows/"><u>Backup Your Cortana Data for Future Reference (Windows)</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-pixels-of-hilarity-with-adobe-tools/"><u>[Updated] Pixels of Hilarity with Adobe Tools</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-downgrade-iphone-14-pro-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade iPhone 14 Pro without iTunes? | Dr.fone</u></a></li>
<li><a href="https://facebook.techidaily.com/english-footballs-giants-shun-online-channels-due-to-toxic-trolling/"><u>English Football's Giants Shun Online Channels Due to Toxic Trolling</u></a></li>
<li><a href="https://windows11.techidaily.com/banish-the-blues-of-a-non-opening-notepad-streamlined-fixes-for-windows-pcs/"><u>Banish the Blues of a Non-Opening Notepad: Streamlined Fixes for Windows PCs</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-streamline-your-soundscape-best-free-apps-to-download-youtube-songs-on-android/"><u>In 2024, Streamline Your Soundscape  Best Free Apps to Download YouTube Songs on Android</u></a></li>
<li><a href="https://windows11.techidaily.com/8-essential-steps-to-bring-back-lost-windows-files/"><u>8 Essential Steps to Bring Back Lost Windows Files</u></a></li>
<li><a href="https://windows11.techidaily.com/automation-made-simple-windows-task-scheduler-batch/"><u>Automation Made Simple: Windows Task Scheduler Batch</u></a></li>
<li><a href="https://windows11.techidaily.com/aoemi-made-simple-unifying-dual-window-desktops/"><u>AOEMi Made Simple: Unifying Dual Window Desktops</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/pokemon-go-no-gps-signal-heres-every-possible-solution-on-asus-rog-phone-7-drfone-by-drfone-virtual-android/"><u>Pokemon Go No GPS Signal? Heres Every Possible Solution On Asus ROG Phone 7 | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-step-into-the-world-of-vrecorder-downloading-and-using-for-2024/"><u>[New] Step Into the World of VRecorder  Downloading and Using for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-enhancing-video-experience-on-youtube-with-slower-playback-48-chars/"><u>[New] In 2024, Enhancing Video Experience on YouTube with Slower Playback (48 Chars)</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-the-ultimate-guide-to-fb-video-calls-best-practices/"><u>2024 Approved  The Ultimate Guide to FB Video Calls  Best Practices</u></a></li>
<li><a href="https://windows11.techidaily.com/1719369938575-run-a-free-locally-stored-gpt-on-your-pc-with-gpt4all/"><u>Run a Free, Locally-Stored GPT on Your PC with GPT4All.</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-exploring-the-metaphysics-of-metaverse-selling/"><u>[Updated] In 2024, Exploring the Metaphysics of Metaverse Selling</u></a></li>
</ul></div>
