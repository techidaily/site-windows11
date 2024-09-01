---
title: Unleashing the Potential for In-Depth Storage Analysis with DiskUsage on Windows
date: 2024-08-31T22:08:24.479Z
updated: 2024-09-01T22:08:24.479Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unleashing the Potential for In-Depth Storage Analysis with DiskUsage on Windows
excerpt: This Article Describes Unleashing the Potential for In-Depth Storage Analysis with DiskUsage on Windows
keywords: DisKUsage Storage Analysis,Windows Disk Usage Insight,In-Depth DiskSpace Tracking,DiskStorage Performance Evaluation,Windows Storage Assessment Tool,Advanced Storage Monitoring,Data Management with DiskUsage
thumbnail: https://thmb.techidaily.com/00e1438c22966a36d893eecd9042143ec66d342044498e4db45f5bcf754631a6.jpg
---

## Unleashing the Potential for In-Depth Storage Analysis with DiskUsage on Windows

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
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
## Analyze Drive Space With DiskUsage

 Many of the available command line tools are extremely useful for maintaining and managing your Windows PC. And as this guide shows, DiskUsage.exe is a powerful alternative to graphical UI tools such as Storage Sense if you want to really dig down into how your drive space is being used.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-sharing-recording.techidaily.com/new-expert-analysis-which-editing-tool-trumps-the-other-filmora-or-democreator-in-2024/"><u>[New] Expert Analysis  Which Editing Tool Trumps the Other, Filmora or Democreator, In 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-dive-into-the-world-of-youtube-shorts-mastering-video-creation/"><u>[New] In 2024, Dive Into the World of YouTube Shorts  Mastering Video Creation</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/he-investors-edge-tapping-into-youtube-creators-earnings-for-2024/"><u>[New] The Investor’s Edge  Tapping Into YouTube Creators' Earnings for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-amusing-clip-loading-appraisal/"><u>[Updated] Amusing Clip Loading Appraisal</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-mp4-file-capture-comparative-study-and-reviews-for-2024/"><u>[Updated] MP4 File Capture  Comparative Study & Reviews for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-transforming-passion-into-a-fulfilling-design-career/"><u>2024 Approved  Transforming Passion Into a Fulfilling Design Career</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unmatched-value-top-tier-asmr-microphones-on-a-budget/"><u>2024 Approved  Unmatched Value  Top-Tier ASMR Microphones on a Budget</u></a></li>
<li><a href="https://howto.techidaily.com/4-solutions-to-fix-unfortunately-your-app-has-stopped-error-on-honor-80-pro-straight-screen-edition-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Solutions to Fix Unfortunately Your App Has Stopped Error on Honor 80 Pro Straight Screen Edition | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/budget-conscious-shooters-7-best-4k-cameras/"><u>Budget-Conscious Shooters' 7 Best 4K Cameras</u></a></li>
<li><a href="https://extra-information.techidaily.com/fixing-inertia-and-jello-distortions-in-uav-clips/"><u>Fixing Inertia and Jello Distortions in UAV Clips</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-overcoming-lol-launch-lag/"><u>Guide to Overcoming LOL Launch Lag</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-postpone-windows-10-shutdown-during-active-processes/"><u>Guide to Postpone Windows 10 Shutdown During Active Processes</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-sign-off-strangers-on-windows-11/"><u>Guide to Sign Off Strangers on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-you-through-windows-update-mishap-0xca000a009/"><u>Guiding You Through Windows Update Mishap: 0XCA0_00A009</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-force-delete-or-uninstall-a-printer-in-windows-10-and-11/"><u>How to Force Delete or Uninstall a Printer in Windows 10 & 11</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-hard-reset-on-nokia-c12-pro-drfone-by-drfone-reset-android-reset-android/"><u>How to Perform Hard Reset on Nokia C12 Pro? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-send-and-fake-live-location-on-facebook-messenger-of-your-vivo-y28-5g-drfone-by-drfone-virtual-android/"><u>How to Send and Fake Live Location on Facebook Messenger Of your Vivo Y28 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-bypassing-barriers-privately-share-youtube-video-via-google/"><u>In 2024, Bypassing Barriers  Privately Share YouTube Video via Google</u></a></li>
<li><a href="https://windows11.techidaily.com/including-d-drive-paths-in-file-explorer-list/"><u>Including D: Drive Paths in File Explorer List</u></a></li>
<li><a href="https://windows11.techidaily.com/legitimate-procedures-vs-chatbots-for-secure-win-11-access/"><u>Legitimate Procedures Vs. Chatbots for Secure Win 11 Access</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-craft-of-slide-show-presentations-tips-to-fix-prints-in-windows/"><u>Mastering the Craft of Slide Show Presentations: Tips to Fix Prints in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-vboxs-security-settings-secure-boot-and-tpm-management/"><u>Mastering VBox's Security Settings: Secure Boot & TPM Management</u></a></li>
<li><a href="https://windows11.techidaily.com/modify-default-task-manager-viewport-in-win11/"><u>Modify Default Task Manager Viewport in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-troubleshooting-of-windows-update-problems/"><u>Navigating Through Troubleshooting of Windows Update Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-pc-delays-in-warhammer-boltguns-quest-for-precision/"><u>Overcome PC Delays in Warhammer: Boltgun's Quest for Precision</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-update-issue-windows-11-error-code-0x800f0922/"><u>Overcome Update Issue: Windows 11 Error Code 0X800F0922</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-usb-device-errors-on-windows-pcs/"><u>Overcoming USB Device Errors on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/personalized-overheat-avoidance-bios-tutorial-for-win-users/"><u>Personalized Overheat Avoidance: BIOS Tutorial for Win Users</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-common-winx-update-error-0x80246007/"><u>Quick Fixes for Common WinX Update Error: 0X80246007</u></a></li>
<li><a href="https://windows11.techidaily.com/regaining-composure-post-high-living-days-for-windows-users/"><u>Regaining Composure Post-High Living Days, for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/security-refresh-windows-firewalls-five-commandments/"><u>Security Refresh: Windows Firewall's Five Commandments</u></a></li>
<li><a href="https://windows11.techidaily.com/six-simple-steps-for-briefly-pausing-windows-11s-safety-measures/"><u>Six Simple Steps for Briefly Pausing Windows 11'S Safety Measures</u></a></li>
<li><a href="https://windows11.techidaily.com/smooth-operations-at-low-cost-leverage-w11-pro-key/"><u>Smooth Operations at Low Cost: Leverage W11 Pro Key</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-securing-computer-against-unauthorized-usb-clip-attacks/"><u>Steps for Securing Computer Against Unauthorized USB Clip Attacks</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-spontaneous-scrolls-a-winworlders-guide/"><u>Stop Spontaneous Scrolls: A Winworlder's Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/strategic-shopping-for-cost-efficient-windows-11-keys/"><u>Strategic Shopping for Cost-Efficient Windows 11 Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-decrease-high-cpu-consumption-by-dropbox-on-windows/"><u>Strategies to Decrease High CPU Consumption by Dropbox on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-overcome-iphone-photographic-transfer-issues-on-w11-systems/"><u>Strategies to Overcome iPhone Photographic Transfer Issues on W11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-overcome-zero-x-error-in-the-microsoft-email-on-windows-11/"><u>Strategies to Overcome Zero X Error in the Microsoft Email on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-pc-toggle-folders-visibility-windows-11/"><u>Streamline Your PC: Toggle Folders Visibility (Windows 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/strengthen-your-safe-space-top-5-corrections-in-windows-features/"><u>Strengthen Your Safe Space: Top 5 Corrections in Windows Features</u></a></li>
<li><a href="https://driver-install.techidaily.com/systematic-uninstall-install-cycle-for-wacom-devices-on-windows/"><u>Systematic Uninstall-Install Cycle for Wacom Devices on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-windows-update-failures-error-x712/"><u>Tackling Windows Update Failures: Error X712</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-win1011-audio-error-xc00d36b4/"><u>Troubleshooting Win10/11 Audio Error XC00D36B4</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-overcoming-launchers-security-code-delivery-issues-on-windows/"><u>Troubleshooting: Overcoming Launcher's Security Code Delivery Issues on Windows</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/ultimate-guide-to-catch-the-regional-located-pokemon-for-apple-iphone-11-drfone-by-drfone-virtual-ios/"><u>Ultimate Guide to Catch the Regional-Located Pokemon For Apple iPhone 11 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/unique-apps-for-a-stylish-windows-clock-display/"><u>Unique Apps for a Stylish Windows Clock Display</u></a></li>
<li><a href="https://windows11.techidaily.com/unjamming-windows-tackling-access-issues-head-on/"><u>Unjamming Windows: Tackling Access Issues Head-On</u></a></li>
<li><a href="https://windows11.techidaily.com/unseen-boundaries-personal-growth-under-microphone-and-camera-censorship/"><u>Unseen Boundaries: Personal Growth Under Microphone & Camera Censorship</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-s-top-free-mkv-splitters-trim-and-edit-with-ease/"><u>Updated In 2024, S Top Free MKV Splitters Trim and Edit with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11s-vanishing-icons-restoration-strategies/"><u>Win 11'S Vanishing Icons - Restoration Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-1110-hacks-swift-recovery-of-synapse-functions/"><u>Windows 11/10 Hacks: Swift Recovery of Synapse Functions</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-with-both-wi-fi-and-ethernet-connections-on-your-computer/"><u>Winning with Both Wi-Fi & Ethernet Connections on Your Computer</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>