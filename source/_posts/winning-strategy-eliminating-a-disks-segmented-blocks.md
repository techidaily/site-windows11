---
title: "Winning Strategy: Eliminating a Disk's Segmented Blocks"
date: 2024-09-09T12:08:04.958Z
updated: 2024-09-10T12:08:04.958Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Winning Strategy: Eliminating a Disk's Segmented Blocks"
excerpt: "This Article Describes Winning Strategy: Eliminating a Disk's Segmented Blocks"
keywords: Winning Strategies,Disk Cleanup Techniques,Segment Removal Methods,Optimal Data Deletion,Efficient File Organization,Block Elimination Tactics,Advanced Storage Management
thumbnail: https://thmb.techidaily.com/36f771b0e455ffd27a9b597a4a43e9338a94fa4efcb33fd8811a101c2c676422.png
---

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2120866/26400?prodsku=mars" target="_top" id="2120866">
  <img src="//a.impactradius-go.com/display-ad/26400-2120866" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2120866/26400?prodsku=mars" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Winning Strategy: Eliminating a Disk's Segmented Blocks

 Your Windows computer provides several options for deleting unwanted drive partitions, whether you are looking to consolidate space, restructure data allocation, or simply start over. However, before you do that, make sure to backup or move any important data on the partition, as the process removes all the data on the drive.

 This guide will show you how to delete a drive partition using the Settings app, Disk Management tool, Command Prompt, and PowerShell.

## 1\. How to Delete a Drive Partition on Windows Using the Settings App

 The Windows Settings app makes it easy to manage drive partitions and perform advanced storage-related tasks. It also provides the most straightforward way to delete a drive partition on Windows.To delete a drive partition via the Settings app:

1. Press **Win + I** to open the Settings app.
2. In the **System** tab, click on **Storage**.
3. Expand **Advanced storage settings** and click **Disks & volumes**.
4. Click the **Properties** button next to the drive you wish to delete.
5. Under the **Format** section, click the **Delete** button.
6. Select **Delete volume** to confirm.  
![Delete a Drive Partition Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-the-settings-app.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137212/26400" target="_top" id="2137212">
  <img src="//a.impactradius-go.com/display-ad/26400-2137212" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137212/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Once you complete the steps, the partition and everything on it will be gone.

<!-- affiliate ads begin -->
<span id="1983539">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983539.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983539">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983539.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983539%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983539/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. How to Delete a Drive Partition on Windows Using the Disk Management Utility

 Another way to delete a drive partition on Windows is via the Disk Management tool. If you want to use that, follow these steps:

1. Press **Win + R** to open the Run dialog box.
2. Type **diskmgmt.msc** in the text field and press **Enter**.
3. In the Disk Management window, right-click the unwanted partition and click the **Delete Volume** option.
4. Select **Yes** to confirm.  
![Delete a Drive Partition Using the Disk Management Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-the-disk-management-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115925/19272" target="_top" id="2115925">
  <img src="//a.impactradius-go.com/display-ad/19272-2115925" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115925/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Don't want to get rid of a drive altogether? You can also choose to [hide the drive on Windows](https://www.makeuseof.com/how-to-hide-a-drive-in-windows/) using the Disk Management tool.

<!-- affiliate ads begin -->
<a href="https://bluettiit.sjv.io/c/5597632/2114267/17093" target="_top" id="2114267">
  <img src="//a.impactradius-go.com/display-ad/17093-2114267" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettiit.sjv.io/i/5597632/2114267/17093" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. How to Delete a Drive Partition on Windows With the Command Prompt

 Not a fan of GUI? No problem. Windows also lets you delete a drive partition using the Command Prompt. Here are the steps for the same.

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the menu that appears.
2. Select **Yes** when the User Account Control (UAC) prompt shows up.
3. In the console, run the following commands to view a list of drives connected to your system.  
`diskpart  
list volume`
4. Note down the number associated with the drive you want to delete in the **Volume** column.
5. Type the following command and press **Enter** to select the volume. Make sure you replace **N** in the command with the drive number noted earlier.  
`select volume N`
6. Copy and paste the following command and press **Enter** to delete the partition.  
`delete volume`  
![Delete a Drive Partition Using the Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-the-command-prompt.jpg)

 Enjoy working with the Command Prompt? If so, you will surely love our guide on [customizing the Command Prompt on Windows](https://www.makeuseof.com/windows-customize-command-prompt/).

## 4\. How to Delete a Drive Partition on Windows via PowerShell

 Windows PowerShell is another command-line tool that you can use to delete a disk partition. Here are the steps you need to follow.

1. Press **Win + S** to open the search menu.
2. Type in **Windows PowerShell** and select **Run as administrator**.
3. Select **Yes** when the User Account Control (UAC) prompt appears to [open PowerShell with admin rights](https://www.makeuseof.com/windows-powershell-always-open-as-administrator/).
4. Run the following command to view a list of drives on your PC:  
`Get-volume`
5. Note down the letter assigned to the drive you want to delete in the **DriveLetter** column.
6. Copy and paste the following command to delete the partition. Replace **X** in the command with the actual drive letter noted in the previous step.  
`Remove-Partition -DriveLetter X`
7. Type **Y** and press **Enter** to confirm.  
![Delete a Drive Partition Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-a-drive-partition-using-powershell.jpg)

 Once you run the above commands, PowerShell will delete the specified partition.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123480/16836" target="_top" id="2123480">
  <img src="//a.impactradius-go.com/display-ad/16836-2123480" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123480/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## There Are Many Ways to Delete Drive Partitions on Windows

 As we just saw, deleting a drive partition on Windows is a simple process, regardless of the method you use. Once you delete a partition, the space on that drive will be unallocated. You can then create a new partition on the empty space or use the space to expand an existing partition.

 This guide will show you how to delete a drive partition using the Settings app, Disk Management tool, Command Prompt, and PowerShell.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-beam-it-up-a-step-by-step-approach-to-youtube-video-luminance/"><u>[New] 2024 Approved Beam It Up A Step-By-Step Approach to YouTube Video Luminance</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-fostering-self-assurance-against-virtual-hostility/"><u>[New] 2024 Approved Fostering Self-Assurance Against Virtual Hostility</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/rom-zero-to-hero-youtube-tech-required-for-2024/"><u>[New] From Zero to Hero YouTube Tech Required for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-in-2024-highest-echelon-writers-club/"><u>[New] In 2024, Highest Echelon Writers Club</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-livestream-lifters-for-modern-audiences/"><u>[New] In 2024, Livestream Lifters for Modern Audiences</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/outube-to-webm-the-finest-video-converters-unveiled/"><u>[New] YouTube-to-WebM The Finest Video Converters Unveiled</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-from-watcher-to-participant-tiktok-live-integration/"><u>[Updated] 2024 Approved From Watcher to Participant TikTok Live Integration</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-best-android-videography-6-must-try-music-videos-apps/"><u>[Updated] Best Android Videography 6 Must-Try Music Videos Apps</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-deciphering-complete-fbm-call-transcripts-guide/"><u>[Updated] In 2024, Deciphering Complete FBM Call Transcripts Guide</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-utilizing-skys-bounty-to-brighten-indoors/"><u>[Updated] Utilizing Sky's Bounty to Brighten Indoors</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-perfecting-imovie-posts-on-vimeo-for-enhanced-viewership/"><u>2024 Approved Perfecting iMovie Posts on Vimeo for Enhanced Viewership</u></a></li>
<li><a href="https://win-blog.techidaily.com/adobe-troubleshooting-guide-fixing-application-launch-problem-with-error-message-0xc0000022/"><u>Adobe Troubleshooting Guide: Fixing Application Launch Problem with Error Message 0Xc0000022</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/comparing-top-voip-services-is-vonage-leading-in-quality/"><u>Comparing Top VoIP Services: Is Vonage Leading in Quality?</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-guide-to-downloading-and-updating-fingerprint-recognition-drivers-for-windows-users/"><u>Easy Guide to Downloading & Updating Fingerprint Recognition Drivers for Windows Users</u></a></li>
<li><a href="https://driver-download.techidaily.com/ensuring-compatibility-and-performance-the-process-of-enhancing-usb-serial-device-drivers/"><u>Ensuring Compatibility & Performance: The Process of Enhancing USB Serial Device Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-inaccessible-folders-in-windows-outlook-a-comprerani-guide/"><u>Fixing Inaccessible Folders in Windows Outlook: A Comprerani Guide</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fixing-locked-out-display-configurations-in-nvidia/"><u>Fixing Locked-Out Display Configurations in NVIDIA</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-adjust-inaccurate-task-manager-cpu-indicators/"><u>Guide to Adjust Inaccurate Task Manager CPU Indicators</u></a></li>
<li><a href="https://win-able.techidaily.com/1722997084130-guide-resolve-your-world-of-warcraft-crash-problems-swiftly-and-effectively/"><u>Guide: Resolve Your World of Warcraft Crash Problems Swiftly & Effectively!</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-to-rectify-window-11s-non-responsive-menu-bar/"><u>Guidelines to Rectify Window 11'S Non-Responsive Menu Bar</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-downgrade-iphone-15-plus-without-losing-any-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade iPhone 15 Plus without Losing Any Data? | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-unbrick-a-dead-motorola-defy-2-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Unbrick a Dead Motorola Defy 2 | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-5-ways-to-track-infinix-smart-8-without-app-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Ways to Track Infinix Smart 8 without App | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-dose-life360-notify-me-when-someone-checks-my-location-on-honor-x50i-drfone-by-drfone-virtual-android/"><u>In 2024, Dose Life360 Notify Me When Someone Checks My Location On Honor X50i? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-can-we-unlock-our-realme-c51-phone-screen-by-drfone-android/"><u>In 2024, How Can We Unlock Our Realme C51 Phone Screen?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-spy-on-text-messages-from-computer-and-motorola-moto-g04-drfone-by-drfone-virtual-android/"><u>In 2024, How to Spy on Text Messages from Computer & Motorola Moto G04 | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-vivo-v30-pro-phone-without-any-data-loss-by-drfone-android/"><u>In 2024, How to Unlock Vivo V30 Pro Phone without Any Data Loss</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-start-now-best-online-learning-for-new-youtubers/"><u>In 2024, Start Now Best Online Learning for New YouTubers</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-tips-and-tricks-mastering-voiceover-on-tiktok/"><u>In 2024, Tips and Tricks Mastering Voiceover on TikTok</u></a></li>
<li><a href="https://windows11.techidaily.com/is-wsl-functional-post-windows-11-install-solutions-explored/"><u>Is WSL Functional Post-Windows 11 Install? Solutions Explored</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/linguistic-insights-into-turk-korean-exchange/"><u>Linguistic Insights Into Turk-Korean Exchange</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-app-packages-with-winget-on-win11-tips-and-tricks/"><u>Mastering App Packages with Winget on Win11 - Tips and Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-web-control-panel-adjustments-in-windows-11/"><u>Mastering Web Control Panel Adjustments in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/morning-magic-startup-seamlessly-unlock-notepad-quickly/"><u>Morning Magic: Startup Seamlessly, Unlock Notepad Quickly</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-cutting-edge-gear-with-precision-at-toms-hardware-destination/"><u>Navigating Cutting-Edge Gear with Precision at Tom's Hardware Destination</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-intricacies-of-w11s-auto-hdr/"><u>Navigating the Intricacies of W11's Auto HDR</u></a></li>
<li><a href="https://windows11.techidaily.com/navigational-aid-for-windows-component-services-utility/"><u>Navigational Aid for Windows' Component Services Utility</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-vram-in-windows-a-comprehensive-guide-for-gamers/"><u>Optimizing VRAM in Windows - A Comprehensive Guide for Gamers</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-0x800700e1-in-win10-and-11-pcs/"><u>Overcoming 0X800700E1 in Win10 & 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-excessive-cpu-activity-a-solution-guide/"><u>Overcoming Excessive CPU Activity: A Solution Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-failed-rpc-calls-a-windows-focused-guide/"><u>Overcoming Failed RPC Calls: A Windows-Focused Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/pinpoint-win-logins-the-differentiator-between-right-and-wrong-entries/"><u>Pinpoint Win Logins: The Differentiator Between Right & Wrong Entries</u></a></li>
<li><a href="https://windows11.techidaily.com/prime-virtual-machines-elevating-windows-11-tech/"><u>Prime Virtual Machines Elevating Windows 11 Tech</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-at-hand-assigning-shortcuts-for-win-11-problem-tools/"><u>Quick Fixes at Hand: Assigning Shortcuts for Win 11 Problem Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-solutions-to-csgo-opens-issue-w11/"><u>Quick Solutions to CS:GO Opens Issue W11</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-tips-how-to-overcome-restricted-file-viewers-in-windows/"><u>Quick Tips: How to Overcome Restricted File Viewers in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/redefine-restoring-windows-11-explorer-view-order/"><u>Redefine: Restoring Windows 11 Explorer View Order</u></a></li>
<li><a href="https://driver-install.techidaily.com/1720063059113-revamp-gameplay-install-logitec-widow-7-drivers-now/"><u>Revamp Gameplay - Install Logitec Widow 7 Drivers Now</u></a></li>
<li><a href="https://windows11.techidaily.com/revisiting-the-classics-uncovering-7-older-windows-functionalities-in-11/"><u>Revisiting the Classics: Uncovering 7 Older Windows Functionalities in 11</u></a></li>
<li><a href="https://windows11.techidaily.com/sound-expertise-for-beginners-in-microsofts-new-os/"><u>Sound Expertise for Beginners in Microsoft's New OS</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-overcome-msstore-error-0x00000000-in-windows-10/"><u>Steps to Overcome MsStore Error 0X00000000 in Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlined-windows-11-upsize-an-in-place-methodology-overview/"><u>Streamlined Windows 11 Upsize: An In-Place Methodology Overview</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-adapt-windows-settings-via-hotkey-techniques/"><u>Swiftly Adapt Windows Settings via Hotkey Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-negate-erroneous-security-alarms-from-chrome-web-app/"><u>Techniques to Negate Erroneous Security Alarms From Chrome Web App</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/the-blue-enigma-whats-behind-the-symbol-on-facebook-messenger-for-2024/"><u>The Blue Enigma What's Behind the Symbol on Facebook Messenger for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-complete-process-for-adding-widgets-on-windows-11/"><u>The Complete Process for Adding Widgets on Windows 11</u></a></li>
<li><a href="https://program-issues.techidaily.com/the-ultimate-fix-for-valorants-pc-latency-techniques-to-improve-your-gameplay/"><u>The Ultimate Fix for Valorant's PC Latency : Techniques to Improve Your Gameplay</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/the-ultimate-guide-to-video-quality-exploring-the-differences-between-8k-4k-and-1080p-resolutions/"><u>The Ultimate Guide to Video Quality: Exploring the Differences Between 8K, 4K and 1080P Resolutions</u></a></li>
<li><a href="https://video-capture.techidaily.com/top-10-switch-knockouts-the-ultimate-list-for-2024/"><u>Top 10 Switch Knockouts The Ultimate List for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/top-techniques-for-maximizing-windows-11-features/"><u>Top Techniques for Maximizing Windows 11 Features</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-and-personalize-your-pc-with-alomwares-mastery/"><u>Transform and Personalize Your PC With AlomWare's Mastery</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-chrome-blackout-on-pcs/"><u>Troubleshooting Chrome Blackout on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-memory-feature-disabled-in-win11/"><u>Troubleshooting Memory Feature Disabled in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-non-operational-event-viewer/"><u>Troubleshooting Non-Operational Event Viewer</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/troubleshooting-fixing-inability-of-adobe-premiere-pro-to-locate-suitable-video-playback-components/"><u>Troubleshooting: Fixing Inability of Adobe Premiere Pro to Locate Suitable Video Playback Components</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-the-resistance-to-windows-11s-latest-release/"><u>Understanding the Resistance to Windows 11'S Latest Release</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-silent-keys-troubleshooting-tactics-for-windows-pcs/"><u>Unlock Silent Keys: Troubleshooting Tactics for Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/whats-next-after-0x800f0845-error/"><u>What's Next After 0X800f0845 Error?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/why-wont-my-usb-to-hdmi-adapter-connect-solving-common-issues/"><u>Why Won't My USB to HDMI Adapter Connect? Solving Common Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-mastery-constructing-clutter-free-directories/"><u>Windows 11 Mastery: Constructing Clutter-Free Directories</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>