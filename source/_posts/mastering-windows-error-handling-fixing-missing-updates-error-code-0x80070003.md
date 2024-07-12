---
title: "Mastering Windows Error Handling: Fixing Missing Updates (Error Code: 0X80070003)"
date: 2024-07-11T21:14:06.719Z
updated: 2024-07-12T21:14:06.719Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Windows Error Handling: Fixing Missing Updates (Error Code: 0X80070003)"
excerpt: "This Article Describes Mastering Windows Error Handling: Fixing Missing Updates (Error Code: 0X80070003)"
keywords: WinErrorHandlingBasics,UpdateMissingSolution,ErrorCode0X80070003Fix,WindowsUpdatesTroubleshoot,FixError0x80070003,MissingWindowsUpdateResolve,ErrorHandlingStepByStep
thumbnail: https://thmb.techidaily.com/734ba7f5cb5c21a47d1f0b28c0f28b69fa0ec96215f4c2ee497557b9ec2807d6.jpg
---

## Mastering Windows Error Handling: Fixing Missing Updates (Error Code: 0X80070003)

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

 Once the folder is deleted, open the Settings app and try installing the updates again.

## 2\. Run System Scans

 The next thing you can do is scan the system for potential issues. The best way to do this is by using built-in system utilities like the System File Checker and DISM.

 The System File Checker (SFC) will scan the protected system files for inconsistencies. If it finds a file that is corrupt, SFC will replace it with its healthier cached counterpart. DISM, on the other hand, will repair the system image.

 We will be using the Command Prompt to run these tools. Make sure you are logged into Windows as an administrator before proceeding:

Here is all that you need to do:

1. Open Command Prompt as an administrator (see [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for instructions).
2. Click**Yes** in the User Account Control prompt.
3. In the Command Prompt window, type the command mentioned below and hit**Enter** .  
`sfc /scannow`  
![SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/sfc-scannow.jpg)
4. Wait for the command to execute, and then execute the following command:  
`Dism /Online /Cleanup-Image /ScanHealth`  
![DISM scanhealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/scanhealth.jpg)
5. Next, proceed with the following command:  
`Dism /Online /Cleanup-Image /RestoreHealth`  
![DISM restorehealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/restorehealth.jpg)
6. Once this command is executed, close the Command Prompt window and check if you can now download the targeted updates.

 While you are at it, you can also [run the Windows Update troubleshooter](https://www.makeuseof.com/tag/windows-update-troubleshooter/) . This tool also works like the utilities we just described above. It will scan the system for errors and suggest you relevant fixes that can be applied using the troubleshooter as well.

## 3\. Repair the Update Components

 As we mentioned earlier, the update components can also deal with some kind of corruption, leading to the problem under discussion.

 The good news is that repairing these components is quite simple, and we will also use the Command Prompt in this method. We recommend [creating a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed. This will help you revert to the current system state in case something goes wrong during the execution of the method.

Once the restore point is created, follow these steps:

1. Open a Run dialog box (see [how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) to learn how).
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
<li><a href="https://ios-unlock.techidaily.com/in-2024-3-ways-to-unlock-apple-iphone-14-pro-without-passcode-or-face-id-by-drfone-ios/"><u>In 2024, 3 Ways to Unlock Apple iPhone 14 Pro without Passcode or Face ID</u></a></li>
<li><a href="https://windows11.techidaily.com/rapidly-access-apps-on-windows-11/"><u>Rapidly Access Apps on Windows 11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-concealed-visibility-mastering-visual-obscurity-in-videos/"><u>In 2024, Concealed Visibility  Mastering Visual Obscurity in Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/strip-windows-11-of-the-store-application/"><u>Strip Windows 11 of the Store Application</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-xc0000142-issue-in-windows-11-10/"><u>Correcting XC0000142 Issue in Windows 11, 10</u></a></li>
<li><a href="https://review-topics.techidaily.com/issues-playing-mkv-video-on-moto-g-stylus-5g-2023-by-aiseesoft-video-converter-play-mkv-on-android/"><u>Issues playing MKV video on Moto G Stylus 5G (2023)</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-pubg-save-problems-on-windows-systems/"><u>Eliminating PUBG Save Problems on Windows Systems</u></a></li>
<li><a href="https://extra-tips.techidaily.com/a-closer-look-ffmpeg-for-pristine-audio-extraction/"><u>A Closer Look  FFmpeg for Pristine Audio Extraction</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-deterrence-against-distractive-fb-video-ads/"><u>[Updated] In 2024, Deterrence Against Distractive FB Video Ads</u></a></li>
<li><a href="https://animation-videos.techidaily.com/5-must-try-ways-to-add-gif-in-text-message-on-android/"><u>5 Must Try Ways to Add GIF in Text Message on Android</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerated-cross-language-compreinasion-via-windows-keyboard-tricks/"><u>Accelerated Cross-Language Compreinasion via Windows Keyboard Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/revamp-desktop-by-removing-windows-11s-highlighted-icon/"><u>Revamp Desktop by Removing Windows 11'S Highlighted Icon</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-curtail-excessive-wmi-worker-use/"><u>Tips to Curtail Excessive WMI Worker Use</u></a></li>
<li><a href="https://windows11.techidaily.com/reconnecting-mic-during-windows-powerpoint-screencast/"><u>Reconnecting Mic During Windows PowerPoint Screencast</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-win1011-network-failure-code-0x800704b3/"><u>Resolving Win10/11 Network Failure: Code 0X800704B3</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-your-global-ip-on-win-os-via-cli/"><u>Demystifying Your Global IP on WIN OS via CLI</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-shadowrunners-speed-up-your-bf2-experience/"><u>Seamless Shadowrunners: Speed up Your BF2 Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-misentered-characters-in-windows-os/"><u>Dealing with Misentered Characters in Windows OS</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-tracing-path-to-diverse-aggravation-noise-files/"><u>New In 2024, Tracing Path to Diverse Aggravation Noise Files</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-change-location-on-facebook-marketplace-for-huawei-p60-drfone-by-drfone-virtual-android/"><u>3 Ways to Change Location on Facebook Marketplace for Huawei P60 | Dr.fone</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-2024-approved-how-to-make-a-slideshow-with-icecream-slideshow-maker/"><u>Updated 2024 Approved How to Make a Slideshow with Icecream Slideshow Maker</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionize-your-pc-clear-tpm-from-windows-11/"><u>Revolutionize Your PC: Clear TPM From Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/achieving-superior-desktop-images-in-windows-11/"><u>Achieving Superior Desktop Images in Windows 11</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-total-recording-tool-az-app-examination-guide/"><u>[New] 2024 Approved  Total Recording Tool - AZ App Examination Guide</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/guide-to-retrieving-and-saving-gifs-from-facebooks-domain-for-2024/"><u>Guide to Retrieving and Saving GIFs From Facebook's Domain for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-drawings-redefined-top-7-windows-10-art-tools-for-you/"><u>Digital Drawings Redefined: Top 7 Windows 10 Art Tools for You</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-ispoofer-is-not-working-on-xiaomi-13-ultra-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, iSpoofer is not working On Xiaomi 13 Ultra? Fixed | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-streamsavvy-beyond-the-dacast-boundary/"><u>[New] StreamSavvy  Beyond the DaCast Boundary</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-unmarked-manual-for-instagrams-livestream-privacy/"><u>[New] The Unmarked Manual for Instagram's Livestream Privacy</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-detailed-strategies-for-altering-facial-gender-display-in-digital-media/"><u>In 2024, Detailed Strategies for Altering Facial Gender Display in Digital Media</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-your-gameplay-overcoming-lags-in-warfare/"><u>Elevating Your Gameplay: Overcoming Lags in Warfare</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-edge-windows-gadgets-2024s-must-haves-list/"><u>Cutting-Edge Windows Gadgets - 2024'S Must-Haves List</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-guide-to-hyper-v-installation-in-win-11-home/"><u>A Comprehensive Guide to Hyper-V Installation in Win 11 Home</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-recording-real-time-google-meetings/"><u>2024 Approved  Recording Real-Time Google Meetings</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-firmware-enhancement-for-surface-devices/"><u>Seamless Firmware Enhancement for Surface Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-over-windows-missing-files-issue/"><u>Winning Over Windows' Missing Files Issue</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-how-to-use-igtv-hashtags-to-get-more-followers/"><u>[New] How to Use IGTV Hashtags to Get More Followers</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-does-the-stardust-trade-cost-in-pokemon-go-on-honor-90-gt-drfone-by-drfone-virtual-android/"><u>In 2024, How does the stardust trade cost In pokemon go On Honor 90 GT? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-overcoming-error-0x800700e1-in-windows-11-devices/"><u>Techniques for Overcoming Error 0X800700E1 in Windows 11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/step-into-safety-with-windows-canary-channel-feature/"><u>Step Into Safety with Windows' Canary Channel Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/precise-strategies-resetting-razers-system-integration/"><u>Precise Strategies: Resetting Razer's System Integration</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-deleting-search-box-art-in-win/"><u>Strategies for Deleting Search Box Art in Win</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-how-to-create-and-schedule-a-google-meet-in-2024/"><u>[New] How to Create and Schedule A Google Meet, In 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/the-art-of-tall-videos-editing-vertical-media-for-impactful-insta-feeds-for-2024/"><u>The Art of Tall Videos  Editing Vertical Media for Impactful Insta Feeds for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-beam-brighter-adopting-the-playful-cartoon-lens-on-snapchat/"><u>[Updated] Beam Brighter  Adopting the Playful Cartoon Lens on Snapchat</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-fifa-footage-analysis-trendy-video-patterns/"><u>[New] 2024 Approved  FIFA Footage Analysis  Trendy Video Patterns</u></a></li>
<li><a href="https://windows11.techidaily.com/revitalizing-your-stalled-windows-11-mobile-network-connection/"><u>Revitalizing Your Stalled Windows 11 Mobile Network Connection</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-the-ultimate-list-of-educational-animation-software-for-schools/"><u>Updated The Ultimate List of Educational Animation Software for Schools</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/plant-and-play-best-friends-games-in-the-agricultural-world/"><u>Plant & Play  Best Friends Games in the Agricultural World</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-desktop-experience-fixing-this-pc-spotlight/"><u>Elevate Desktop Experience: Fixing 'This PC' Spotlight</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/ways-to-find-unlocking-codes-for-oppo-a56s-5g-phones-by-drfone-android/"><u>Ways To Find Unlocking Codes For Oppo A56s 5G Phones</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-rpc-errors-on-windows-os/"><u>Quick Fixes for RPC Errors on Windows OS</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/in-2024-unlock-youtube-sounds-the-ultimate-audio-download-tutorial/"><u>In 2024, Unlock YouTube Sounds The Ultimate Audio Download Tutorial</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-google-chrome-to-full-color-in-windows/"><u>Restoring Google Chrome to Full Color in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-dxgierrordeviceremoved-in-modern-win-oses/"><u>Combatting DXGI_ERROR_DEVICE_REMOVED in Modern Win OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/win11s-file-explorer-glitches-learn-how-to-stop-them/"><u>Win11's File Explorer Glitches? Learn How To Stop Them</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-full-guide-on-mirroring-your-samsung-galaxy-s24plus-to-your-pcmac-drfone-by-drfone-android/"><u>In 2024, Full Guide on Mirroring Your Samsung Galaxy S24+ to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-essential-strategies-for-finding-fabulous-and-free-images-on-pexels/"><u>2024 Approved  Essential Strategies for Finding Fabulous and Free Images on Pexels</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-steams-online-potential-on-pc/"><u>Unlocking Steam's Online Potential on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-operational-optimization-top-windows-pct-strategies/"><u>Achieve Operational Optimization: Top Windows PCT Strategies</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-unlock-the-potential-of-your-channels-with-our-guide-to-discord-broadcasting/"><u>[Updated] Unlock the Potential of Your Channels with Our Guide to Discord Broadcasting</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-imaginary-device-issue-in-win-11-os/"><u>Resolving Imaginary Device Issue in Win 11 OS</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-explore-cheap-video-call-alternatives-compatible-with-windows-and-mac/"><u>2024 Approved  Explore Cheap Video Call Alternatives Compatible With Windows & Mac</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-avidemux-audio-troubleshooting-quick-solutions/"><u>New 2024 Approved Avidemux Audio Troubleshooting Quick Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/process-to-undo-system-image-fault-0x80780119/"><u>Process to Undo System Image Fault: 0X80780119</u></a></li>
<li><a href="https://windows11.techidaily.com/adeptly-disguise-wireless-networks-with-windows/"><u>Adeptly Disguise Wireless Networks with Windows</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-beyond-the-basics-advanced-techniques-for-improved-recordings/"><u>[Updated] 2024 Approved  Beyond the Basics  Advanced Techniques for Improved Recordings</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-transforming-mundane-footage-into-spectaculair-slow-mo-instareel/"><u>[Updated] In 2024, Transforming Mundane Footage Into Spectaculair Slow Mo InstaReel</u></a></li>
<li><a href="https://android-location-track.techidaily.com/solutions-to-spy-on-oneplus-ace-2-pro-with-and-without-jailbreak-drfone-by-drfone-virtual-android/"><u>Solutions to Spy on OnePlus Ace 2 Pro with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-your-security-settings-on-windows-11/"><u>Tailoring Your Security Settings on Windows 11</u></a></li>
<li><a href="https://change-location.techidaily.com/honor-play-8t-bootloop-problem-how-to-fix-it-without-data-loss-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Honor Play 8T Bootloop Problem, How to Fix it Without Data Loss | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-effortless-music-extraction-choose-the-right-apps-for-youtube-and-mp3/"><u>[New] 2024 Approved  Effortless Music Extraction  Choose the Right Apps for YouTube & MP3</u></a></li>
<li><a href="https://windows11.techidaily.com/win-prints-back-on-fixing-an-offline-printer/"><u>Win-Prints Back On! Fixing an Offline Printer</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-exploring-the-top-25-emoji-crafting-applications-on-discord/"><u>2024 Approved  Exploring the Top 25 Emoji Crafting Applications on Discord</u></a></li>
<li><a href="https://windows11.techidaily.com/adapting-the-oculus-quest-2-for-windows-os-virtual-reality/"><u>Adapting the Oculus Quest 2 for Windows OS Virtual Reality</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-launch-free-youtube-events-a-step-by-step-guide/"><u>2024 Approved  Launch Free Youtube Events  A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-hello-biometrics-endangered-by-recent-cyberattacks/"><u>Windows Hello Biometrics Endangered by Recent Cyberattacks</u></a></li>
</ul></div>
