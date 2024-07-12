---
title: Deciphering Minimum/Max CPU in Power Preferences
date: 2024-07-11T22:29:07.074Z
updated: 2024-07-12T22:29:07.074Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Deciphering Minimum/Max CPU in Power Preferences
excerpt: This Article Describes Deciphering Minimum/Max CPU in Power Preferences
keywords: CPU Performance Settings,CPU Min & Max Values,Optimize CPU Power Mode,Adjusting CPU Speed,Energy Efficient CPU,Limit CPU Frequency,Tailored CPU Preferences
thumbnail: https://thmb.techidaily.com/0d94a1daa7c27cd73a9d8298e21e0d777d1adaffd7b41de949895538a87e46dd.jpg
---

## Deciphering Minimum/Max CPU in Power Preferences

 Have you ever tried to tweak the minimum and maximum processor states on your Windows PC, only to find them hidden? Or perhaps you want to hide the options to prevent others from tampering with them?

 Whichever you're trying to do, we're here to help by showing you how to add or remove them in the Power Options menu.

## How to Show or Hide the Minimum or Maximum Processor State Using Command Prompt

 To use Command Prompt to show or hide these power states, press**Win + R** to open Windows Run. Then, enter**cmd** in the text box and hit the**Enter** key on your keyboard. You can also use one of the many [ways to open the Command Prompt on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .

![Cmd in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-cmd.jpg)

To show the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c -ATTRIB_HIDE`

To hide the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c +ATTRIB_HIDE`

To show the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec -ATTRIB_HIDE`

To hide the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec +ATTRIB_HIDE`

 After you have typed in the command you want in the CMD window, hit the**Enter** key on your keyboard to run it.

## How to Show or Hide the Minimum or Maximum Processor State Using the Registry Editor

 You can also show or hide these options using the Registry Editor. However, before you do so, create a restore point as a backup in case you make a mistake and need to return your Windows computer to a previously-working state. Check out [how to create a restore point in Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) for more information.

 After creating the system restore point, press**Win + R** to open the Run dialog box. Then, enter**regedit** in the text box and hit the**Enter** key to open the Registry Editor.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 On the UAC prompt, click**Yes** to continue.

 To get to the key for the minimum processor state in the Registry editor, copy and paste the following file path into the Registry Editor’s address bar and hit**Enter** :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\bc5038f7-23e0-4960-96da-33abaf5935ec`

 Right-click the**Attributes** value in the right panel and select**Modify** .

![modifying the attributes value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-modify-attributes.jpg)

 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

 For the maximum processor state, enter the below file path in the Registry Editor's address bar to get to its key:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\893dee8e-2bef-41e0-89c6-b55d0929964c`

 Double-click the**Attributes** entry to modify it, and then change**Value data** to**1** to hide the maximum processor state or**2** to show it.

## Add or Remove the Minimum and Maximum Processor States From Power Options

 Setting the minimum or maximum processor state on your Windows computer is vital to helping you get the performance you want from it. If you can’t see these options in the Power Options menu, you can easily reveal them with either Command Prompt or the Registry Editor. And after you’re done tweaking the states, you can hide them for their protection.


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
<li><a href="https://windows11.techidaily.com/decoding-the-windows-startup-journey/"><u>Decoding the Windows Startup Journey</u></a></li>
<li><a href="https://windows11.techidaily.com/control-over-edges-ongoing-tasks-in-win11-environment/"><u>Control Over Edge's Ongoing Tasks in Win11 Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-os-issues-mastering-the-art-of-finding-and-fixing-error-messages-using-commands/"><u>Decoding OS Issues: Mastering the Art of Finding & Fixing Error Messages Using Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-frequent-rainmeter-anomalies-in-windows-environment/"><u>Decoding Frequent Rainmeter Anomalies in Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-windows-11-a-guide-to-a-unique-environment/"><u>Customizing Windows 11: A Guide to a Unique Environment</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-on-samsung-galaxy-f34-5g-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos on Samsung Galaxy F34 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-webp-image-save-in-google-chrome-windows-edition/"><u>Disabling WebP Image Save in Google Chrome, Windows Edition</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-5-tricks-for-instantly-boosting-youtube-subscribers-for-2024/"><u>[Updated] 5 Tricks for Instantly Boosting YouTube Subscribers for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-down-the-memory-usage-of-your-security-app/"><u>Cutting Down the Memory Usage of Your Security App</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-exceptional-uav-selection-for-optimal-gopro-footage/"><u>[Updated] Exceptional UAV Selection for Optimal GoPro Footage</u></a></li>
<li><a href="https://extra-tips.techidaily.com/spectacular-sites-featuring-rich-3d-and-golden-text/"><u>Spectacular Sites Featuring Rich 3D and Golden Text</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-common-errors-in-windows-onedrive/"><u>Correcting Common Errors in Windows' OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/compact-pc-capacity-concealed-by-slowness/"><u>Compact PC, Capacity Concealed by Slowness</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-and-disabling-read-only-properties-in-win11/"><u>Deciphering and Disabling Read-Only Properties in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-your-workspace-pinning-techniques-for-w11/"><u>Customize Your Workspace: Pinning Techniques for W11</u></a></li>
<li><a href="https://extra-information.techidaily.com/building-a-vivid-world-with-animated-clips-in-movie-maker/"><u>Building a Vivid World with Animated Clips in Movie Maker</u></a></li>
<li><a href="https://windows11.techidaily.com/curbing-high-cpu-utilization-by-tiworkerexe-programs/"><u>Curbing High CPU Utilization by TiWorker.exe Programs</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-the-meaning-behind-windows-folders-x-marks/"><u>Demystifying: The Meaning Behind Windows' Folders X-Marks</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-immediate-failure-effective-strategies-to-tackle-onedrive-folder-issues-on-pc/"><u>Conquering Immediate Failure: Effective Strategies to Tackle OneDrive Folder Issues on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-the-clutter-fixing-windows-error-0x80072014/"><u>Clearing the Clutter: Fixing Windows Error 0X80072014</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-quick-reference-how-to-insert-vimeo-media-into-powerpoint-files/"><u>2024 Approved  Quick Reference  How to Insert Vimeo Media Into PowerPoint Files</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/grow-with-integrity-selecting-reputable-tiktok-leads/"><u>Grow with Integrity  Selecting Reputable TikTok Leads</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-routes-to-windows-11s-system32/"><u>Direct Routes to Windows 11'S System32</u></a></li>
<li><a href="https://windows11.techidaily.com/coordinating-connections-dual-net-usage-on-a-single-windows-pc/"><u>Coordinating Connections: Dual Net Usage on a Single Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-gray-out-issue-with-volume-extend-in-win/"><u>Correcting Gray Out Issue with Volume Extend in Win</u></a></li>
<li><a href="https://windows11.techidaily.com/cure-the-save-issue-in-microsoft-oses/"><u>Cure the Save Issue in Microsoft OSes</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-iphones-ultimate-podcast-downloading-manual-for-2024/"><u>[Updated] IPhone's Ultimate Podcast Downloading Manual for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-essential-tips-for-minecraft-recording-with-macos/"><u>[Updated] Essential Tips for Minecraft Recording with MacOS</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/process-of-screen-sharing-vivo-g2-to-pc-detailed-steps-drfone-by-drfone-android/"><u>Process of Screen Sharing Vivo G2 to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ransforming-viewers-into-fans-with-top-yt-video-reacts-for-2024/"><u>[New] Transforming Viewers Into Fans with Top YT Video Reacts for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/controlling-application-spaces-in-windows-task-mgr/"><u>Controlling Application Spaces in Windows Task Mgr</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-disparities-unveiling-the-distinctive-aspects-of-each-login-type/"><u>Delving Into Disparities: Unveiling The Distinctive Aspects of Each Login Type</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/editing-videos-on-mac-os-x-yosemite-a-beginners-guide-for-2024/"><u>Editing Videos on Mac OS X Yosemite A Beginners Guide for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/jump-cut-strategies-for-compelling-vlogs-for-2024/"><u>Jump Cut Strategies for Compelling Vlogs for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-windows-11s-obstacle-overcoming-error-code-22/"><u>Clearing Windows 11'S Obstacle: Overcoming Error Code 22</u></a></li>
<li><a href="https://windows11.techidaily.com/confirm-if-your-system-is-a-win11-recipe/"><u>Confirm if Your System Is a Win11 Recipe</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-unveiling-the-secrets-to-slow-motion-screenshots-in-snapchat/"><u>[Updated] In 2024, Unveiling the Secrets to Slow-Motion Screenshots in Snapchat</u></a></li>
<li><a href="https://windows11.techidaily.com/clear-sighted-making-your-windows-11-taskbar-glossy/"><u>Clear-Sighted: Making Your Windows 11 Taskbar Glossy</u></a></li>
<li><a href="https://windows11.techidaily.com/converting-heic-photos-to-jpeg-on-windows-1011/"><u>Converting HEIC Photos to JPEG on Windows 10/11</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-latest-guide-how-to-bypass-samsung-galaxy-a05s-frp-without-computer-by-drfone-android/"><u>In 2024, Latest Guide How To Bypass Samsung Galaxy A05s FRP Without Computer</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-do-you-remove-restricted-mode-on-apple-iphone-7-drfone-by-drfone-ios/"><u>In 2024, How Do You Remove Restricted Mode on Apple iPhone 7 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/dive-into-windows-powertoys-the-ultimate-guide-to-its-best-uses/"><u>Dive Into Windows PowerToys: The Ultimate Guide to Its Best Uses</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-top-10-for-mac-gif-capturing-expert-reviews-for-2024/"><u>[New] Top 10 for Mac GIF Capturing  Expert Reviews for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/clean-slate-optimizing-windowed-file-space/"><u>Clean Slate: Optimizing Windowed File Space</u></a></li>
<li><a href="https://printer-issues.techidaily.com/dismantling-hp-printer-fault-0xoxc4eb827f/"><u>Dismantling HP Printer Fault 0xOXC4EB827F</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/redefining-fluency-tomorrows-techniques-for-todays-students/"><u>Redefining Fluency: Tomorrow's Techniques for Today's Students</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-best-spy-watches-for-your-nokia-c12-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Best Spy Watches For your Nokia C12 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/control-your-machines-invisible-operations-on-window-11/"><u>Control Your Machine's Invisible Operations on Window 11</u></a></li>
<li><a href="https://windows11.techidaily.com/1720600438278-windowsstellar-data-recovery/"><u>「Windowsで失われたファイルを取り戻せる無料ソフトStellar Data Recovery」</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-windows-11-notifications-to-exclude-extras/"><u>Customize Windows 11 Notifications to Exclude Extras</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-capturing-elegance-with-bokeh-effects-in-stories/"><u>[New] 2024 Approved  Capturing Elegance with Bokeh Effects in Stories</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-aim-for-picture-perfect-facebooks-hd-streaming-for-2024/"><u>[Updated] Aim for Picture-Perfect  Facebook's HD Streaming for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-high-cpu-demands-the-case-for-vanguards-ums-optimization/"><u>Deciphering High CPU Demands: The Case for Vanguard's UMS Optimization</u></a></li>
</ul></div>
