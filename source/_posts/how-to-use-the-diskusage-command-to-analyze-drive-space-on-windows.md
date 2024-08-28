---
title: How to Use the DiskUsage Command to Analyze Drive Space on Windows
date: 2024-08-27T16:10:15.738Z
updated: 2024-08-28T16:10:15.738Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Use the DiskUsage Command to Analyze Drive Space on Windows
excerpt: This Article Describes How to Use the DiskUsage Command to Analyze Drive Space on Windows
keywords: DriveSpaceAnalysisWindows,DiskUsageCommandExplanation,WindowsDriveSpaceCheck,StorageSpaceMonitoringTool,AnalyzingDiskSpaceWindows,CommandForSpaceInspector,SpaceUtilityOnPCs
thumbnail: https://thmb.techidaily.com/267319de45b47bfed89a5beeea4e8662c6ef68d4fb035ab41968a0873cebbd66.jpg
---

## How to Use the DiskUsage Command to Analyze Drive Space on Windows

 The DiskUsage.exe tool can be used to analyze the contents of any drive or folder on Windows 11\. DiskUsage is accessed from the command line and includes many options for filtering and refining the file data that can be output. In certain situations, this can make it far more useful than GUI tools like Storage Sense.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

## View Disk Usage of Any Drive or Folder

 The simplest way to use the DiskUsage command line tool is to get an overview of how space is currently used in almost a drive or folder. We have used the tool on Windows 11, but it is also available on Windows 10\.

1. Run the Command Prompt as an admin. If you need help, check out [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. In Command Prompt type **DiskUsage** followed by the path to the drive or folder you want to analyze.
3. For example, to view the disk usage of the Pictures folder, type: **DiskUsage C:\\Users\\UserName\\Pictures**, and press **Enter**.  
![The disk usage command in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-cmd.jpg)
4. To see the SizeOnDisk number in a human-readable format, e.g. KB, MB, or GB, add **/h** to the end of the command.
5. In our example, this looks like **DiskUsage C:\\Users\\UserName\\Pictures /h**.  
![Disk usage date displayed in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-data.jpg)

 You can use DiskUsage to analyze any folder in the same way. You can even check internal and external drives, including the C: drive. Bear in mind that analyzing a drive such as C: will spew out a huge list of files and folders in DiskUsage.

 If using DiskUsage.exe seems too complicated, you can easily view how disk space is being used with [Storage Sense](https://www.makeuseof.com/windows-11-storage-sense-guide/).

## List All Files Larger Than a Specified Size

 You can refine the data displayed in DiskUsage based on file size. So if, for example, you only want to include files over 500MB, you can set it to ignore smaller files.

1. To only include files above a specific size, you need to add the minFileSize option to the command.
2. As an example: **DiskUsage /minFileSize=6553600 C:\\Users\\UseName\\Downloads /h**.
3. This will only look for files in Downloads larger than 50MB and then display the disk space those files occupy in that location.
4. The file size number must be entered in bytes, so you might have to convert MB to Byte using an online conversion tool.

 For a more detailed view of large files, including file name as well as size, you can use the **/u** command modifier. This allows you to list a defined number of the largest files in the drive or folder.

1. To do this type: **DiskUsage C:\\Users\\UserName\\Downloads /h /u=15**.
2. The 15 largest files in the Downloads folder will now be listed in Command Prompt.  
![file data listed in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-list.jpg)
3. You can replace the number with any other you want to use. For example, to see the top 5 files taking up space, use **/u=5**.
4. Make sure to include the **/h** option so that the output is in a format that's easy to read.

 After identifying what is taking up the most space, you can use any one of these [methods to delete large files](https://www.makeuseof.com/windows-11-delete-select-files/).

<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Additional DiskUsage Command Options

 The DiskUsage tool contains several other useful options that you can use to filter the output. You can filter by filename, display reserved space, or the largest directories within the folder.

 For example, to filter by filename add **/n=installer** to the end of the command to display only files that contain the word installer.

 You can see a complete list of the options by typing **DiskUsage /?** and pressing **Enter**.

![A list of DiskUsage options in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-options.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Analyze Drive Space With DiskUsage

 Many of the available command line tools are extremely useful for maintaining and managing your Windows PC. And as this guide shows, DiskUsage.exe is a powerful alternative to graphical UI tools such as Storage Sense if you want to really dig down into how your drive space is being used.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-links.techidaily.com/new-2-methods-to-add-effects-on-tiktok-for-2024/"><u>[New] 2 Methods To Add Effects On TikTok for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-editcanvas-solutions/"><u>[New] 2024 Approved  EditCanvas Solutions</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-expert-strategies-for-effective-instagram-video-interactions/"><u>[New] 2024 Approved  Expert Strategies for Effective Instagram Video Interactions</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-apex-sporting-cameras-for-extreme-enthusiasts/"><u>[New] Apex Sporting Cameras for Extreme Enthusiasts</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/n-2024-rapid-process-converting-images-into-engaging-youtube-desktop-pics/"><u>[New] In 2024, Rapid Process  Converting Images Into Engaging YouTube Desktop Pics</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-stable-shooting-ultimate-iphoneandroid-tripod-hits/"><u>[New] Stable Shooting  Ultimate iPhone/Android Tripod Hits</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-steps-to-crossfade-audio-in-logic-pro-x/"><u>[New] Steps To Crossfade Audio In Logic Pro X</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-clickbait-crafting-secrets-to-facebooks-favorites-for-2024/"><u>[Updated] Clickbait Crafting  Secrets to Facebook's Favorites for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-mastering-canvass-skin-removal-an-experts-handbook/"><u>2024 Approved  Mastering Canvas's Skin Removal  An Expert's Handbook</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-picart-strategies-for-stunning-image-purification/"><u>2024 Approved  PicArt Strategies for Stunning Image Purification</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-revolutionize-your-videos-essential-obs-edits-at-hand/"><u>2024 Approved  Revolutionize Your Videos  Essential OBS Edits at Hand</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-shot-securement-keeping-cameras-still-on-arms-only/"><u>2024 Approved  Shot Securement  Keeping Cameras Still on Arms Only</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-step-by-step-conquering-tiktok-edit-mastery/"><u>2024 Approved  Step-by-Step  Conquering TikTok Edit Mastery</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-facts-you-need-to-know-about-screen-mirroring-honor-play-7t-drfone-by-drfone-android/"><u>3 Facts You Need to Know about Screen Mirroring Honor Play 7T | Dr.fone</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/8-ways-ai-chatbots-are-impacting-content-creation/"><u>8 Ways AI Chatbots Are Impacting Content Creation</u></a></li>
<li><a href="https://win-answers.techidaily.com/achieving-smooth-gameplay-overcoming-call-of-duty-warzone-pc-crashes/"><u>Achieving Smooth Gameplay: Overcoming Call of Duty Warzone PC Crashes</u></a></li>
<li><a href="https://windows11.techidaily.com/evolving-taskbar-in-windows-an-annual-look-back/"><u>Evolving Taskbar in Windows: An Annual Look-Back</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-system-error-allow-blocked-program/"><u>Fix System Error: Allow Blocked Program</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-fix-bluetooth-absence-in-device-mgr/"><u>Guide to Fix Bluetooth Absence in Device Mgr</u></a></li>
<li><a href="https://windows11.techidaily.com/harnessing-file-operations-techniques-to-archive-and-extract/"><u>Harnessing File Operations: Techniques to Archive and Extract</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-counteract-dxgi-errors-after-device-loss/"><u>How to Counteract DXGI Errors After Device Loss</u></a></li>
<li><a href="https://driver-install.techidaily.com/how-to-download-and-setup-gaomon-s620/"><u>How to Download and Setup Gaomon S620</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-overcome-lost-ark-not-starting-up-this-year/"><u>How to Overcome Lost Ark Not Starting Up This Year</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-prevent-recurring-crashes-for-thunder-tier-one-gaming-experience-on-pcs/"><u>How to Prevent Recurring Crashes for Thunder: Tier One Gaming Experience on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-properly-utilize-system-restore-on-microsoft-windows/"><u>How to Properly Utilize System Restore on Microsoft Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-realign-read-aloud-settings-on-word-app/"><u>How To Realign Read Aloud Settings on Word App</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-xiaomi-redmi-note-12r-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>How to Unlock Xiaomi Redmi Note 12R Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-measures-for-repairing-post-windows-upgrade-failures/"><u>Immediate Measures for Repairing Post-Windows Upgrade Failures</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-breakdown-of-funds-required-for-music-video-shooting/"><u>In 2024, Breakdown of Funds Required for Music Video Shooting</u></a></li>
<li><a href="https://extra-hints.techidaily.com/incredibly-swift-blackouts/"><u>Incredibly Swift Blackouts</u></a></li>
<li><a href="https://win-dash.techidaily.com/lenovo-x220-essential-drivers-download-and-installation-made-easy/"><u>Lenovo X220 Essential Drivers - Download & Installation Made Easy</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-vmware-start-issues-on-windows-11plusoses/"><u>Mastering VMware Start Issues on Windows 11+OSes</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-finding-authentic-clap-sound-implementations-for-projects/"><u>New Finding Authentic Clap Sound Implementations for Projects</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-file-access-harness-the-power-of-win11s-checkboxes/"><u>Optimize File Access: Harness the Power of Win11's Checkboxes</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-steams-missing-files-hurdle-on-win11-os/"><u>Overcoming Steam's Missing Files Hurdle on Win11 OS</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/peak-choice-top-five-high-definition-cameras-for-2024/"><u>Peak Choice  Top Five High Definition Cameras for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-saturated-load-on-windows-chatgpt/"><u>Preventing Saturated Load on Windows ChatGPT</u></a></li>
<li><a href="https://windows11.techidaily.com/proven-methods-for-mastering-the-mspcm-toolbar-windows-11-edition/"><u>Proven Methods for Mastering the MSPCM Toolbar, Windows 11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/reconfigure-windows-11-task-manager-interface-view/"><u>Reconfigure Windows 11 Task Manager Interface View</u></a></li>
<li><a href="https://windows11.techidaily.com/recovering-from-disrupted-asana-use-a-focused-approach-for-pc-users/"><u>Recovering From Disrupted Asana Use: A Focused Approach for PC Users</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-for-save-failed-error-on-windows-systems/"><u>Remedy for Save Failed Error on Windows Systems</u></a></li>
<li><a href="https://apple-account.techidaily.com/removing-device-from-apple-id-for-your-iphone-x-by-drfone-ios/"><u>Removing Device From Apple ID For your iPhone X</u></a></li>
<li><a href="https://windows11.techidaily.com/skirting-microsofts-app-verification-system-on-pc/"><u>Skirting Microsoft's App Verification System on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/smart-shopping-tips-for-finding-windows-11-keys/"><u>Smart Shopping Tips for Finding Windows 11 Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-frozen-grammarly-on-your-computer-system/"><u>Solving Frozen Grammarly on Your Computer System</u></a></li>
<li><a href="https://fake-location.techidaily.com/spoofing-life360-how-to-do-it-on-vivo-y200-drfone-by-drfone-virtual-android/"><u>Spoofing Life360 How to Do it on Vivo Y200? | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-instructions-turn-on-voice-over-with-siri-for-ios-and-macos-devices/"><u>Step-by-Step Instructions: Turn On Voice Over with Siri for iOS and macOS Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-fix-xbox-game-download-failures-on-pc/"><u>Steps to Fix Xbox Game Download Failures on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-recover-from-a-blank-login-display-window/"><u>Steps to Recover From a Blank Login Display Window</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-reverse-non-downloading-challenges-with-chrome-windows/"><u>Steps to Reverse Non-Downloading Challenges with Chrome, Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-undoing-changes-to-windows-app-configurations/"><u>Swiftly Undoing Changes to Windows App Configurations</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-windows-screen-size-sensitivities-a-step-by-step-approach/"><u>Taming Windows' Screen Size Sensitivities: A Step-by-Step Approach</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/the-ultimate-review-of-sns-hdr-vs-top-hdr-applications-for-2024/"><u>The Ultimate Review of SNS HDR Vs. Top HDR Applications for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/top-windows-improvements-what-to-expect-from-feb23/"><u>Top Windows Improvements: What to Expect From Feb23</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-outdated-systems-without-windows-os/"><u>Transform Outdated Systems without Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-productivity-tailored-clipboard-tools-on-windows/"><u>Unleash Productivity: Tailored Clipboard Tools on Windows</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/unlock-the-potential-of-your-instagram-content-with-video-edits/"><u>Unlock the Potential of Your Instagram Content with Video Edits</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-secrets-to-windows-camera-media-storage/"><u>Unlocking the Secrets to Windows Camera Media Storage</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-undetected-toolbar-for-windows-11-users/"><u>Unlocking the Undetected Toolbar for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-error-code-0x8007251d-on-pcs/"><u>Unraveling the Mystery of Error Code 0X8007251d on PCs</u></a></li>
<li><a href="https://hardware-help.techidaily.com/unveiling-gadgets-toms-hardware-deep-dives/"><u>Unveiling Gadgets: Tom's Hardware Deep-Dives</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-power-of-cross-platform-note-taking-in-win11/"><u>Unveiling the Power of Cross-Platform Note Taking in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-of-windows-process-aggregatehostexe/"><u>Unveiling the Secrets of Windows' Process AggregateHost.exe</u></a></li>
<li><a href="https://windows11.techidaily.com/what-are-the-best-bottleneck-calculators-for-windows-how-to-check-your-hardware-for-bottlenecks-manually/"><u>What Are the Best Bottleneck Calculators for Windows? How to Check Your Hardware for Bottlenecks Manually</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>