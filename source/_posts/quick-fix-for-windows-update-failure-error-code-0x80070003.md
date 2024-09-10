---
title: Quick Fix for Windows' Update Failure (Error Code 0X80070003)
date: 2024-09-09T12:04:31.943Z
updated: 2024-09-10T12:04:31.943Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick Fix for Windows' Update Failure (Error Code 0X80070003)
excerpt: This Article Describes Quick Fix for Windows' Update Failure (Error Code 0X80070003)
keywords: WinUpdateFix ErrorCode,Err0x80070003 Solution,Windows Update Troubleshoot,Fixing Windows UpdError,ZeroXUpdateFailure Fix,Solve Windows Error 70003,Update Failure Code 07003
thumbnail: https://thmb.techidaily.com/bf32c159170edbc355c721b22ee8ee6c67dda36feed408fdb0ec7f3ca8b4ddc2.jpg
---

## Quick Fix for Windows' Update Failure (Error Code 0X80070003)

 It's not unusual for Windows users to run into issues when installing updates or upgrading to the latest version of Windows. The problem with these error codes is that most of the time, they do not specify the cause of the error or what users can do to avoid it.

 A common error that users run into when trying to update their system is 0x80070003\. This error is accompanied by a message stating "Some update files are missing." Let's explore the reasons behind this issue and the solutions you can try to resolve it.

## Why Are Update Files Missing From Your PC?

 One or more of the following reasons might explain why you are experiencing the problem on your computer:

1. The Windows log file might have corrupt data files that are interfering with the update installation process in Windows. The best way to deal with corrupt files is by repairing them using the built-in Windows utilities. If that does not work, you can delete them to resolve the problem.
2. The essential system files have become corrupt. This scenario can be resolved by running the troubleshooting utilities described below. They can identify corrupt files and replace them with healthy ones.
3. The Windows update components required for the pending updates to install are not functioning properly, which is causing the system to throw the error Fortunately, repairing the corrupt components is easy and can be done within a few minutes using the Command Prompt.
4. The Windows Update service and other relevant services required by the system to install the pending updates are disabled or have become corrupt. In this case, you can simply restart the services to resolve the issue.

 Now that you know what might be causing the problem let’s see how to resolve this case of missing update files in Windows.

## 1\. Delete the Contents of the DataStore Folder

 The DataStore folder in Windows is a log file that stores information about all the updates installed in the system. This folder is located in the SoftwareDistribution folder, which is a directory of update-related information in Windows.

 In several cases, the underlying issue was caused due to the corrupt components of the DataStore folder, which were interfering with the system’s update process. An easy way to resolve this issue is by deleting the contents of this folder or removing the Data Store folder as a whole. Both methods are safe to execute.

 We have described the steps for doing this below. However, if you do not want to delete the DataStore folder or its contents, you can also repair them. For that, follow the next method below.

1. Launch File Explorer and navigate to the following location below:  
`C:\Windows\SoftwareDistribution`  
![Software distribution](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-software-distribution.jpg)
2. Locate the**DataStore** folder in the SoftwareDistribution folder and right-click on it.
3. Choose**Delete** from the context menu.  
![Delete the DataStore folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/software-distribution-datastore-delete-1.jpg)
4. Click**Yes** in the confirmation prompt to proceed.
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/2139563/4704" target="_top" id="2139563">
  <img src="//a.impactradius-go.com/display-ad/4704-2139563" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/2139563/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once the folder is deleted, open the Settings app and try installing the updates again.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115919/19272" target="_top" id="2115919">
  <img src="//a.impactradius-go.com/display-ad/19272-2115919" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115919/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Run System Scans

 The next thing you can do is scan the system for potential issues. The best way to do this is by using built-in system utilities like the System File Checker and DISM.

 The System File Checker (SFC) will scan the protected system files for inconsistencies. If it finds a file that is corrupt, SFC will replace it with its healthier cached counterpart. DISM, on the other hand, will repair the system image.

 We will be using the Command Prompt to run these tools. Make sure you are logged into Windows as an administrator before proceeding:

Here is all that you need to do:

1. Open Command Prompt as an administrator (see[how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for instructions).
2. Click**Yes** in the User Account Control prompt.
3. In the Command Prompt window, type the command mentioned below and hit**Enter** .  
`sfc /scannow`  
![SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/sfc-scannow.jpg)
4. Wait for the command to execute, and then execute the following command:  
`Dism /Online /Cleanup-Image /ScanHealth`  
![DISM scanhealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/scanhealth.jpg)
5. Next, proceed with the following command:  
<!-- affiliate ads begin -->
<span id="1424529">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424529.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424529">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424529.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424529%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424529/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
`Dism /Online /Cleanup-Image /RestoreHealth`  
![DISM restorehealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/restorehealth.jpg)
6. Once this command is executed, close the Command Prompt window and check if you can now download the targeted updates.
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130533/26400" target="_top" id="2130533">
  <img src="//a.impactradius-go.com/display-ad/26400-2130533" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130533/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 While you are at it, you can also[run the Windows Update troubleshooter](https://www.makeuseof.com/tag/windows-update-troubleshooter/) . This tool also works like the utilities we just described above. It will scan the system for errors and suggest you relevant fixes that can be applied using the troubleshooter as well.

<!-- affiliate ads begin -->
<span id="1993651">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993651.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993651">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993651.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993651%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993651/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Repair the Update Components

 As we mentioned earlier, the update components can also deal with some kind of corruption, leading to the problem under discussion.

 The good news is that repairing these components is quite simple, and we will also use the Command Prompt in this method. We recommend[creating a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed. This will help you revert to the current system state in case something goes wrong during the execution of the method.

Once the restore point is created, follow these steps:

1. Open a Run dialog box (see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) to learn how).
2. Type cmd in the text field of Run and press Ctrl + Shift + Enter to open Command Prompt as an administrator.
3. Click**Yes** in the User Account Control prompt.
4. Once you are inside the Command Prompt, execute the commands below one by one:  
`<code>net stop wuauserv  
net stop cryptSvc  
net stop bits  
net stop msiserver`  
``` `` ```
5. Once all the services are stopped, execute the following commands. These will clear the update cache in the system:  
`<code>ren %systemroot%\softwaredistribution softwaredistribution.bak  
ren %systemroot%\system32\catroot2 catroot2.bak`  
``` `` ```
6. Now, proceed with the following commands one by one to start the Windows update services again:  
`<code>net start wuauserv  
net start bits  
net start cryptsvc  
net start trustedinstaller  
net start appidsvc`  
![Restart the update services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/restart-the-services.jpg)
7. After the commands are executed, restart your computer. Hopefully, you will be able to install the pending updates on reboot.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135404/19272" target="_top" id="2135404">
  <img src="//a.impactradius-go.com/display-ad/19272-2135404" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135404/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get the Missing Update Files Back on Windows

 Hopefully, by now, you should have successfully resolved the annoying update error. In case you are still facing the issue, you can use the Microsoft update catalog to install the updates manually. It may also be a good idea to report this issue to the Microsoft support team so they can launch an official fix for the problem.


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
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-precision-audio-capturing-techniques-in-overwatch/"><u>[New] 2024 Approved Precision Audio Capturing Techniques in Overwatch</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-embarking-on-a-virtual-odyssey-through-yt-stories/"><u>[New] In 2024, Embarking on a Virtual Odyssey Through YT Stories</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-essential-tips-for-steam-gamers-recordings/"><u>[New] In 2024, Essential Tips for Steam Gamers' Recordings</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-the-invisible-trail-hidden-steps-for-tracking-whatsapp-calls/"><u>[Updated] 2024 Approved The Invisible Trail Hidden Steps for Tracking WhatsApp Calls</u></a></li>
<li><a href="https://windows11.techidaily.com/2-seamless-integration-how-wsl-is-becoming-more-user-friendly-on-windows-pcs/"><u>2. Seamless Integration: How WSL Is Becoming More User-Friendly on Windows PCs</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-elite-driving-sims-best-five-titles/"><u>2024 Approved Elite Driving Sims Best Five Titles</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-mastering-the-art-of-instagram-video-bordering/"><u>2024 Approved Mastering the Art of Instagram Video Bordering</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-sparkle-with-style-triple-highlight-techniques-for-insta/"><u>2024 Approved Sparkle with Style Triple Highlight Techniques for Insta</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-ultimate-upscaling-preferred-platforms-for-tapping-snapalert-rhythms/"><u>2024 Approved Ultimate Upscaling Preferred Platforms for Tapping SnapAlert Rhythms</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-unleash-creativity-your-comprehensible-guide-to-sharing-animated-messages-in-snapchat/"><u>2024 Approved Unleash Creativity Your Comprehensible Guide to Sharing Animated Messages in Snapchat</u></a></li>
<li><a href="https://howto.techidaily.com/4-ways-to-fix-android-blue-screen-of-death-on-vivo-y78plus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Ways to Fix Android Blue Screen of Death On Vivo Y78+ | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/bypassing-the-hurdle-steps-for-successfully-uploading-an-instagram-story-again/"><u>Bypassing the Hurdle: Steps for Successfully Uploading an Instagram Story Again</u></a></li>
<li><a href="https://extra-resources.techidaily.com/canvasknotter-your-ultimate-photo-blend-tool-for-2024/"><u>CanvasKnotter Your Ultimate Photo Blend Tool for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723862797045-catch-your-favorite-dell-s32gaming-monitor-at-an-unbeatable-price-just-229-top-ranked-quality-guaranteed/"><u>Catch Your Favorite Dell S32^Gaming Monitor at an Unbeatable Price: Just $229 – Top-Ranked Quality Guaranteed!</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/cutting-edge-content-tips-for-excelling-in-facebook-video-sharing/"><u>Cutting-Edge Content Tips for Excelling in Facebook Video Sharing</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-the-benefits-of-arm-based-copilotplus-computers-why-theyre-perfect-for-me/"><u>Exploring the Benefits of ARM-Based Copilot+ Computers: Why They're Perfect for Me</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-the-evolution-a-compelling-overview-of-windows-wallpaper-developments/"><u>Exploring the Evolution: A Compelling Overview of Windows Wallpaper Developments</u></a></li>
<li><a href="https://windows11.techidaily.com/from-ios-to-windows-mastering-the-use-of-imessage/"><u>From iOS to Windows: Mastering the Use of iMessage</u></a></li>
<li><a href="https://windows11.techidaily.com/further-issues-discovered-new-windows-updates-causing-devastating-bluescreens/"><u>Further Issues Discovered: New Windows Updates Causing Devastating Bluescreens</u></a></li>
<li><a href="https://windows11.techidaily.com/get-superior-performance-for-windows-apps-on-macoslinux-with-crossover-24-at-promo-rates/"><u>Get Superior Performance for Windows Apps on macOS/Linux with CrossOver 24 at Promo Rates!</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-failed-to-launch-lunar-client-error-on-windows/"><u>How to Fix the “Failed to Launch Lunar Client” Error on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-shutdown-box-opening-by-itself-in-windows-11/"><u>How to Fix the Shutdown Box Opening By Itself in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-set-up-troubleshooter-shortcuts-in-windows-10-and-11/"><u>How to Set Up Troubleshooter Shortcuts in Windows 10 & 11</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changeadd-location-filters-on-snapchat-for-your-apple-iphone-6-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Change/Add Location Filters on Snapchat For your Apple iPhone 6 | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-top-10-free-iphone-composition-tools-for-stunning-images/"><u>In 2024, Top 10 Free iPhone Composition Tools for Stunning Images</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-ultimate-guide-from-itel-p55-5g-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide from Itel P55 5G FRP Bypass</u></a></li>
<li><a href="https://windows11.techidaily.com/inside-look-7-windows-activities-harboring-risks/"><u>Inside Look: 7 Windows Activities Harboring Risks</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-microsoft-code-companion-for-programmers/"><u>Leveraging Microsoft Code Companion for Programmers</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-customization-in-windows-11s-settings/"><u>Mastering Customization in Windows 11'S Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-use-of-windows-11-desktop-widgets/"><u>Mastering the Use of Windows 11 Desktop Widgets</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-routine-nircmds-win-commands-for-speed/"><u>Optimize Your Routine: NirCmd's Win Commands for Speed</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-in-use-file-conflicts-in-windows-environments-153-chars/"><u>Overcoming 'In-Use' File Conflicts in Windows Environments (153 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-deadly-windows-error-c0000022-breakdown/"><u>Overcoming the Deadly Window's Error C0000022 Breakdown</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-xboxs-stranded-issue-step-by-step-in-windows-11/"><u>Overcoming Xbox's Stranded Issue, Step-by-Step in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/perfect-images-at-fingertips-top-4-webp-viewer-windows/"><u>Perfect Images at Fingertips: Top 4 WebP Viewer Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-failed-attachment-of-usb-device-to-virtualbox/"><u>Quick Fixes for Failed Attachment of USB Device to VirtualBox</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-guide-for-flaky-windows-scheduled-jobs/"><u>Quick-Fix Guide for Flaky Windows Scheduled Jobs</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-typed-position-for-windows-11s-touch-interface/"><u>Resetting Typed Position for Windows 11'S Touch Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-major-windows-11-webcam-glitches-a-comprehensive-guide/"><u>Resolving Major Windows 11 Webcam Glitches: A Comprehensive Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-sync-immediate-notebook-access-after-boot-up/"><u>Seamless Sync: Immediate Notebook Access After Boot-Up</u></a></li>
<li><a href="https://windows11.techidaily.com/shine-bright-again-the-5-must-do-fixes-for-dead-backlight-on-windows/"><u>Shine Bright Again: The 5 Must-Do Fixes for Dead Backlight on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/speed-up-windows-apps-implement-effective-web-linking-strategies/"><u>Speed Up Windows Apps: Implement Effective Web Linking Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/start-with-style-not-sponsorship-in-w11/"><u>Start with Style, Not Sponsorship in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-conquering-dism-failure-error-0x800f082f/"><u>Strategies for Conquering DISM Failure Error 0X800F082F</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-stop-windows-task-moving-apps/"><u>Strategies to Stop Windows Task Moving Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharge-windows-5-top-auto-click-wizards/"><u>Supercharge Windows: 5 Top Auto Click Wizards</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-a-trouble-free-win11-with-ccleaner/"><u>Tips for a Trouble-Free Win11 with CCleaner</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-your-gaming-experience-how-microsofts-directsr-api-is-revolutionizing-pc-game-graphics/"><u>Transform Your Gaming Experience: How Microsoft's DirectSR API Is Revolutionizing PC Game Graphics</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-tips-for-correcting-error-4000-on-your-live-stream-platform/"><u>Ultimate Tips for Correcting Error 4000 on Your Live Stream Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-your-potential-the-best-three-tools-to-track-and-optimize-your-pc-gaming-experience/"><u>Unleash Your Potential: The Best Three Tools to Track and Optimize Your PC Gaming Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-chatbots-freedomgpt-edition-windows/"><u>Unleashing ChatBots: FreedomGPT Edition, Windows</u></a></li>
<li><a href="https://facebook.techidaily.com/unraveling-the-shifted-semantics-in-facebooks-changed-page-labels/"><u>Unraveling the Shifted Semantics in Facebook's Changed Page Labels</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-bluescreen-woes-here-are-11-quick-fix-tips-to-try/"><u>Win11 Bluescreen Woes? Here Are 11 Quick Fix Tips to Try</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-1011-users-guide-to-text-files-and-secure-passwords/"><u>Windows 10/11 Users' Guide to Text Files & Secure Passwords</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-decision-guide-home-features-vs-pro-benefits/"><u>Windows 11 Decision Guide: Home Features Vs. Pro Benefits</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-xp-a-timeless-operating-system-with-unparalleled-longevity/"><u>Windows XP: A Timeless Operating System with Unparalleled Longevity</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-at-gaming-on-windows-11-a-step-by-step-performance-optimization-tutorial/"><u>Winning at Gaming on Windows 11: A Step-by-Step Performance Optimization Tutorial</u></a></li>
</ul></div>
