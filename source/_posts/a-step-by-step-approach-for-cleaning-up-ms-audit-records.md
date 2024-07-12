---
title: A Step-by-Step Approach for Cleaning Up MS Audit Records
date: 2024-07-11T22:20:22.676Z
updated: 2024-07-12T22:20:22.676Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Step-by-Step Approach for Cleaning Up MS Audit Records
excerpt: This Article Describes A Step-by-Step Approach for Cleaning Up MS Audit Records
keywords: MS Audit Cleanup Guide,Audit Record Reconciliation,Data Cleanse in Audits,MS Audit Rectification,Record Scrubbing Tips,Efficient MS Audit Clearing,Best Practices for Audit Purges
thumbnail: https://thmb.techidaily.com/3f45b4986206d046cd956542a295fe465671e73b81f9c11e8f6862999203849a.jpg
---

## A Step-by-Step Approach for Cleaning Up MS Audit Records

 Windows Defender is Microsoft's antivirus built into your Windows PC to protect you from viruses, malware threats, and attacks. It maintains a record of its scans and actions in its Protection History folder.

 Though Protection History gets deleted after some time, you might want to have more control to clear it by yourself. So let's see how you can clear Protection History in four ways.

## What Is the Microsoft Defender Protection History? Why Should You Clear It?

 One of the best antivirus for your PC, [Windows Defender keeps getting better with some powerful upgrades](https://www.makeuseof.com/microsoft-defender-riskai-upgrade/). The detections made by Windows Defender appear on the Protection History page—which means you can view actions that Microsoft Defender Antivirus has taken on your behalf. These would be scans done to identify and block malware and other threats. And also the recommendations (highlighted in red or yellow) for actions you should take.

 You also have access to all this information in a clear and easily understandable form, including Potentially Unwanted Apps that have been removed, or key services that have been turned off. The Protection History will also show the detections that appear while performing a Windows Defender Offline scan.

![Protection History Page in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/ProtectionHistory1.jpg)

 Though Windows Defender keeps the history of its detections for 30 days, you can clear it before that time if you need to—for example, when a lot of scan logs have accumulated. Clearing the Protection History would help you make space on your PC and keep Defender running smoothly. Remember, you must be signed in as an administrator to clear the protection history so [do check if you have administrative rights](https://www.makeuseof.com/check-windows-account-admin-rights/).

 Now let's see four easy ways to clear Protection History in Windows 10 and 11\.

## 1\. How to Clear the Microsoft Defender's Protection History Folder

 You can manually clear the Protection History by deleting the contents of the Service folder in the Windows Defender folder using File Explorer. Here's how:

1. Press **Windows + R** keys to bring up the Run box.
2. Copy and paste the path below and click on **OK** or hit **enter:** **C:\\ProgramData\\Microsoft\\Windows Defender\\Scans\\History**  
![Defender History Folder Path Typed in Run Box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/open-defender-history-folder-via-run.jpg)
3. You can also paste the **C:\\ProgramData\\Microsoft\\Windows Defender\\Scans\\History** path in the File Explorer navigation bar and then hit **enter**.  
![Defender History Folder Path in File Explorer Navigation Bar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/defender-history-folder-path-in-file-explorer.jpg)  
 Alternatively, you can navigate to the **Defender Protection History** folder using the above path in File Explorer. If you don't see the **ProgramData** folder when you open the Local Drive, select **View** and then tick the box next to **Hidden items**.  
![Click Hidden Items under View to See ProgramData Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Click-Hidden-Items-under-View-to-See-ProgramData-Folder.jpg)
4. Open the **Service** folder and select all the files inside it. **Right-click** and select **Delete** to clear all the files. Then exit File Explorer.  
![Select Files in History Folder and Delete Them](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Select-Files-in-History-Folder-and-Delete-Them.jpg)
5. Next, search for **Windows Security** and open it.
6. Under **Virus & threat protection** click on **Manage settings**.  
![Virus and Threat Protection Settings in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Virus-and-Threat-Protection-in-Windows-Security.jpg)
7. Finally, toggle the button to **Off** and then to **On** again, for **Real-Time protection** and **Cloud-delivered protection**.

## 2\. How to Clear the Microsoft Defender Protection History Using the Event Viewer

 You can also manually clear the Defender Protection History via the [Event Viewer](https://www.makeuseof.com/windows-event-viewer-guide/)—a useful app to analyze the event logs on your device. Here's how:

1. First, do a Windows search for **Event Viewer** and click on the app result under **Best match** to open **Event Viewer.**
2. Under the **Event Viewer (Local)** on the left pane, expand the **Applications and Services Logs**.
3. Under **Applications and Services Logs**, click on the down arrow next to the **Microsoft** folder.
4. Click on **Windows** in the left pane to open the list of Windows files on the middle pane.
5. Scroll down through the list of files on the middle pane to find **Windows Defender**.  
![Windows Defender selected in Event Viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Navigate-to-Windows-Defender-in-Event-Viewer.jpg)
6. Double-click on **Windows Defender**.
7. Then right-click on **Operational** and select **Open** to view all the past logs.  
![Open Operational Option to View Defender Logs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Open-Operational-Option-to-View-Defender-Logs.jpg)
8. Now you can right-click on **Operational** in the left pane and choose **Clear Log**. Or click on **Clear Log** on the right pane under **Actions**.  
![Options to Clear Log from Left Pane or Under Actions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Options-to-Clear-Log-Of-Windows-Defender.jpg)
9. Select **Clear** to clear the protection history. If you wish to save the protection history logs for future reference before clearing them, select **Save and Clear**.  
![Options to Clear Logs or Save and Clear Defender Logs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Clear-and-Save-and-Clear-Options-for-Defender-Logs.jpg)

## 3\. How to Clear the Microsoft Defender Protection History via PowerShell

 What if you want the Protection History to clear automatically after a specific number of days? You can also use a PowerShell command to do that. Let's see how to do this:

1. Type **PowerShell** in the search bar. Right-click on **Windows PowerShell** under **Best match** and select **Run as administrator**. Or choose **Run as administrator** on the right search pane.
2. Click **Yes** on the UAC prompt that appears.
3. The **Administrator: PowerShell** window will open up. Type or copy and paste the following command and then hit **enter**:

`Set-MpPreference -ScanPurgeItemsAfterDelay 7`

![Command to Clear Protection History in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/PowerShell-Command-to-Clear-Protection-History.jpg)

 The number **7** at the end of the command is the number of days after which the protection history logs will be cleared. Just change that number to specify when you want the protection history to be cleared. And it will be cleared automatically.

## 4\. How to Clear the Microsoft Defender Protection History Using the Group Policy Editor

 If you have a PC with Windows 10 Pro, Windows 11 Pro, or a higher version, you can also use the Group Policy Editor to clear the Defender Protection History automatically. Though there are solutions to [access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) too. But let's see how to clear Protection History via Group Policy Editor in Windows Pro and higher versions:

1. Press **Win + R** keys to open the Run box. Type **gpedit.msc** to open the **Local Group Policy Editor**. Or just type **gpedit** in the search bar and click on **Edit Group Policy** under **Best match** to open it.
2. In the **Local Group Policy Editor**, on the left pane under **Computer Configuration**, expand **Administrative Templates** by clicking on the down arrow next to it.
3. Inside the **Administrative Templates** folder, click on **Windows Components** and the list of its components would come up on the middle pane of the **Group Policy Editor**.
4. Then scroll down to find **Windows Defender Antivirus** and double-click on it.  
![Navigate to Windows Defender Antivirus in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Navigate-to-Windows-Defender-Antivirus-in-Group-Policy-Editor.jpg)
5. In the list of **Windows Defender** items, **double-click** on the **Scan** folder.
6. In the right pane, **double-click** on **Turn on removal of items from scan history folder**. Or click **Edit policy setting** in the middle pane. This policy setting defines the number of days items should be kept in the scan history folder before being permanently removed.  
![Turn on Removal of Items Policy in Defender Scan Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Edit-Removal-of-Items-Policy-in-Defender-Scan-Folder.jpg)
7. Next, select **Edit policy setting** to open the policy window. It would be showing **Not Configured** by default. To set the number of days, toggle on the button next to **Enabled**. The default number of days, which is **30**, would then be set. If you set the number of days to zero, items will be kept forever and will not be automatically removed. So just change the days to whenever you want the items to be removed. Finally, click **Apply** and then **OK**.  
![Specify Number of Days to Remove Scan Items in Defender](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Set-Number-of-Days-to-Remove-Scan-Items.jpg)

 Now, you won't need to manually clear Protection History every time—the items in the scan history folder would be deleted automatically after the days you've specified.

## Clear the Microsoft Defender Protection History Whenever You Want

 If you ever want to clear Defender Protection History, you know how easy it is to do it through any of the four ways discussed above. If you would want to refer to the Protection History logs later, you can use the Save and Clear option while clearing Protection History using Event Viewer.

 Though Protection History gets deleted after some time, you might want to have more control to clear it by yourself. So let's see how you can clear Protection History in four ways.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/boosting-windows-11-performance-run-command-upgrade-guide/"><u>Boosting Windows 11 Performance: Run Command Upgrade Guide</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-ultimate-iphone-video-editor-comparison-cameo-or-filmorago/"><u>[Updated] Ultimate iPhone Video Editor Comparison  Cameo or FilmoraGo</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-cartoon-video-creation-made-easy-10-best-mobile-apps/"><u>Updated Cartoon Video Creation Made Easy 10 Best Mobile Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/bringing-windows-backups-back-to-basics/"><u>Bringing Windows Backups Back to Basics</u></a></li>
<li><a href="https://windows11.techidaily.com/7-methods-for-correcting-unreachable-display-responses-in-windows/"><u>7 Methods for Correcting Unreachable Display Responses in Windows</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/top-10-reasons-why-you-should-learn-a-foreign-language-this-year/"><u>Top 10 Reasons Why You Should Learn a Foreign Language This Year</u></a></li>
<li><a href="https://windows11.techidaily.com/banish-baffling-silence-solutions-for-windows-spacebar/"><u>Banish Baffling Silence: Solutions for Windows Spacebar</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-windows-techniques-for-diverse-partition-merging/"><u>Advanced Windows Techniques for Diverse Partition Merging</u></a></li>
<li><a href="https://windows11.techidaily.com/a-novel-approach-to-combining-data-units-on-windows-11/"><u>A Novel Approach to Combining Data Units on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/edging-into-the-non-edge-process-quagmire/"><u>Edging Into the Non-Edge Process Quagmire</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-to-create-a-personalized-windows-text-recognition-program/"><u>Easy Steps to Create a Personalized Windows Text Recognition Program</u></a></li>
<li><a href="https://windows11.techidaily.com/blue-screen-decoded-understanding-and-fixing-0x0000003b-in-win-os/"><u>Blue Screen Decoded: Understanding and Fixing 0X0000003B in Win OS</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/in-2024-the-ultimate-list-of-subtitle-edit-alternatives-for-mac-users/"><u>In 2024, The Ultimate List of Subtitle Edit Alternatives for Mac Users</u></a></li>
<li><a href="https://screen-recording.techidaily.com/top-3g-networks-and-plans-for-gamers-on-a-budget/"><u>Top 3G Networks & Plans for Gamers on a Budget</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-invalid-captcha-on-steam/"><u>Bypassing Invalid CAPTCHA on Steam</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/pokemon-go-error-12-failed-to-detect-location-on-oppo-a38-drfone-by-drfone-virtual-android/"><u>Pokemon Go Error 12 Failed to Detect Location On Oppo A38? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/3-ways-to-check-if-windows-11-is-activated/"><u>3 Ways to Check If Windows 11 Is Activated</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/enhancing-narrative-flow-integrating-chapters-into-your-youtube-content/"><u>Enhancing Narrative Flow  Integrating Chapters Into Your YouTube Content</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-decoding-the-secrets-to-using-ez-grabber-for-2024/"><u>[New] Decoding the Secrets to Using EZ Grabber for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/7-must-know-factors-for-buying-your-ideal-windows-computer/"><u>7 Must-Know Factors for Buying Your Ideal WIndows Computer</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-ultimate-playtracker-insight/"><u>[Updated] 2024 Approved  Ultimate PlayTracker Insight</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-mouse-click-agility-nine-strategies-to-tweak-speeds/"><u>Boost Mouse Click Agility: Nine Strategies to Tweak Speeds</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-0x80070194-fixes-for-windows-onedrive/"><u>Bypassing 0X80070194: Fixes for Windows OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-file-system-in-windows-unveiled-max-156/"><u>Effective File System in Windows Unveiled (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/calendar-setup-made-simple-windows-11-edition/"><u>Calendar Setup Made Simple: Windows 11 Edition</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-ultimate-list-leading-vr-biking-rides/"><u>[New] Ultimate List  Leading VR Biking Rides</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-sculpt-your-tiktok-stardom-advanced-mac-based-editing-techniques/"><u>[New] In 2024, Sculpt Your TikTok Stardom  Advanced Mac-Based Editing Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/audible-improvements-for-windows-users-stepwise-audio-driver-revamp/"><u>Audible Improvements for Windows Users: Stepwise Audio Driver Revamp</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-boost-video-clarity-with-iphone-zoom-tools/"><u>2024 Approved  Boost Video Clarity with iPhone Zoom Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/creating-a-dual-disk-on-windows-independently/"><u>Creating a Dual Disk on Windows, Independently</u></a></li>
<li><a href="https://fake-location.techidaily.com/dose-life360-notify-me-when-someone-checks-my-location-on-vivo-x90s-drfone-by-drfone-virtual-android/"><u>Dose Life360 Notify Me When Someone Checks My Location On Vivo X90S? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/convenient-methods-for-local-policies-on-windows-11/"><u>Convenient Methods for Local Policies on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-offscreen-windows-errors/"><u>Addressing Offscreen Windows Errors</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-mastering-virtual-backgrounds-with-kinemasters-stepwise-guide-to-green-screen/"><u>In 2024, Mastering Virtual Backgrounds with Kinemaster's Stepwise Guide to Green Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-winos-stop-autominize-apps/"><u>Boosting WinOS: Stop Autominize Apps</u></a></li>
<li><a href="https://extra-information.techidaily.com/conveying-cinematic-dreams-through-screenwriting-for-2024/"><u>Conveying Cinematic Dreams Through Screenwriting for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/essential-techniques-for-designing-youtube-video-thumbnails-for-2024/"><u>Essential Techniques for Designing YouTube Video Thumbnails for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-how-to-counteract-crashes-in-win-11s-photo-viewer/"><u>[Updated] How to Counteract Crashes in Win 11'S Photo Viewer</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-high-cpu-usage-techniques-from-windows-resource-monitor/"><u>Decoding High CPU Usage: Techniques From Windows Resource Monitor</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-how-to-spy-on-text-messages-from-computer-and-apple-iphone-6-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Spy on Text Messages from Computer & Apple iPhone 6 Plus | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-classics-to-full-hd-perfection-with-windows-and-scummvm-expertise/"><u>Elevate Classics to Full HD Perfection with Windows & ScummVM Expertise</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-capabilities-directories-with-a-click-in-win11/"><u>Crafting Capabilities: Directories with a Click in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/craft-compelling-content-with-these-windows-tools/"><u>Craft Compelling Content with These Window's Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-lost-messages-how-to-fix-notifications-that-fail/"><u>Avoiding Lost Messages: How to Fix Notifications That Fail</u></a></li>
<li><a href="https://windows11.techidaily.com/1719355454943-opera-installer-dilemma-on-windows-solutions-now/"><u>Opera Installer Dilemma on Windows - Solutions Now</u></a></li>
</ul></div>
