---
title: Clear the Way to Privacy with Simple Steps for MS Defender
date: 2024-07-11T22:30:11.744Z
updated: 2024-07-12T22:30:11.744Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Clear the Way to Privacy with Simple Steps for MS Defender
excerpt: This Article Describes Clear the Way to Privacy with Simple Steps for MS Defender
keywords: Privacy Tips MS Defender,MS Defender Security Guide,Enhance Privacy Protection,Secure Data MS Defender,Simple Privacy Steps,Optimize Online Safety,Improve Personal Privacy
thumbnail: https://thmb.techidaily.com/07ec08194f82a5c0eb7f1dbd160d4285a74e061c99e34448dc11e18d2afb1ddd.png
---

## Clear the Way to Privacy with Simple Steps for MS Defender

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-to-fixing-device-path-errors/"><u>Comprehensive Guide to Fixing Device Path Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-bsod-0x0000003b-and-resolution-steps-in-windows-os/"><u>Decoding BSOD -0X0000003B & Resolution Steps in Windows OS</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-pathfinding-your-way-from-adsense-to-accounts-aplenty/"><u>In 2024, Pathfinding Your Way From AdSense to Accounts Aplenty</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/sim-unlock-motorola-moto-g04-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>Sim Unlock Motorola Moto G04 Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-tweeting-videos-to-tweenish-animations-for-no-fee-for-2024/"><u>[Updated] Tweeting Videos to Tweenish Animations for No Fee for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-resource-unavailable-situations-on-windows-149-chars/"><u>Correcting 'Resource Unavailable' Situations on Windows (149 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/curtailing-windows-updates-and-restarts/"><u>Curtailing Windows Updates and Restarts</u></a></li>
<li><a href="https://windows11.techidaily.com/compulsory-uninstall-guide-for-windows-11-printers/"><u>Compulsory Uninstall Guide for Windows 11 Printers</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-common-downloads-dilemmas-on-windows-pcs/"><u>Combatting Common Downloads Dilemmas on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-windows-11s-application-could-not-be-started-error-xc000003e/"><u>Combatting Windows 11'S Application Could Not Be Started Error Xc000003e</u></a></li>
<li><a href="https://windows11.techidaily.com/counteracting-the-impact-of-vac-denial-in-steam-gaming/"><u>Counteracting the Impact of VAC Denial in Steam Gaming</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-the-spiritual-command-center-of-windows-11/"><u>Delving Into the Spiritual Command Center of Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-sound-malfunction-fixing-error-code-xc00d36b4/"><u>Combatting Sound Malfunction: Fixing Error Code Xc00d36b4</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-x80070091-error-in-windows-steps-for-empty-directory-problem-solving/"><u>Deciphering X80070091 Error in Windows - Steps for 'Empty Directory' Problem Solving</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-get-noticed-on-linkedin-the-art-of-creating-custom-video-thumbnails/"><u>In 2024, Get Noticed on LinkedIn The Art of Creating Custom Video Thumbnails</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/disable-screen-lock-on-lava-agni-2-5g-by-drfone-android-unlock-android-unlock/"><u>Disable screen lock on Lava Agni 2 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-filesystem-crashes-in-win11/"><u>Combatting FileSystem Crashes in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-windows-layout-fancywm-power-up/"><u>Customize Windows Layout: FancyWM Power Up</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-life360-shows-wrong-location-on-oneplus-ace-2v-drfone-by-drfone-virtual-android/"><u>How to Fix Life360 Shows Wrong Location On OnePlus Ace 2V? | Dr.fone</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-the-ultimate-guide-to-real-time-audio-recording-in-the-digital-age/"><u>New 2024 Approved The Ultimate Guide to Real-Time Audio Recording in the Digital Age</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-7-top-ways-to-resolve-apple-id-not-active-issue-for-apple-iphone-se-2022-drfone-by-drfone-ios/"><u>In 2024, 7 Top Ways To Resolve Apple ID Not Active Issue For Apple iPhone SE (2022) | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/from-ordinary-to-outstanding-transforming-your-meetings-with-zoom-filters/"><u>From Ordinary to Outstanding  Transforming Your Meetings with Zoom Filters</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-master-the-art-of-visual-storytelling-with-top-text-techniques/"><u>2024 Approved  Master the Art of Visual Storytelling with Top Text Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/cut-down-complications-opt-for-simplicity-in-win11/"><u>Cut Down Complications: Opt for Simplicity in Win11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/2024-approved-youtube-for-beginners-channel-building-monetization-tactics/"><u>2024 Approved  YouTube for Beginners  Channel Building, Monetization Tactics</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-building-a-strong-visual-narrative-in-youtube-videos/"><u>[Updated] 2024 Approved  Building a Strong Visual Narrative in YouTube Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/countering-compromised-windows-defender-on-win-11/"><u>Countering Compromised Windows Defender on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-non-deletable-keys-a-windows-guide/"><u>Correcting Non-Deletable Keys: A Windows Guide</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/a-guide-to-find-a-high-quality-video-marketing-agency/"><u>A Guide to Find a High-Quality Video Marketing Agency</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-quick-access-to-start-from-onedrive/"><u>Customizing Quick Access to Start From OneDrive</u></a></li>
<li><a href="https://android-frp.techidaily.com/latest-guide-how-to-bypass-poco-f5-pro-5g-frp-without-computer-by-drfone-android/"><u>Latest Guide How To Bypass Poco F5 Pro 5G FRP Without Computer</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-mastering-aquatic-cinematography-with-these-7-essential-strategies/"><u>2024 Approved  Mastering Aquatic Cinematography with These 7 Essential Strategies</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-how-to-make-vimeo-videos-for-2024/"><u>[Updated] How to Make Vimeo Videos for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-free-iphone-video-editor-apps-with-rotation-feature/"><u>New 2024 Approved Free iPhone Video Editor Apps with Rotation Feature</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/overview-of-the-best-vivo-v27e-screen-mirroring-app-drfone-by-drfone-android/"><u>Overview of the Best Vivo V27e Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/determining-public-ip-with-system-commands-windows/"><u>Determining Public IP with System Commands, Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-account-lockout-reset-in-successive-login-attempts-windows-1011/"><u>Configuring Account Lockout Reset in Successive Login Attempts Windows 10/11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-elevate-conference-quality-the-list-of-top-10-free-audio-capture/"><u>[New] Elevate Conference Quality  The List of Top 10 Free Audio Capture</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-twitching-online-highlighting-todays-trending-video-takes/"><u>[Updated] Twitching Online  Highlighting Today's Trending Video Takes</u></a></li>
<li><a href="https://windows11.techidaily.com/display-windows-notes-prominently-and-consistently/"><u>Display Windows Notes Prominently and Consistently</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/incorinasmatic-mix-sharing-songs-in-social-spaces/"><u>Incorinasmatic Mix  Sharing Songs in Social Spaces</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-access-issues-enabling-windows-logins-post-fail/"><u>Clearing Access Issues: Enabling Windows Logins Post-Fail</u></a></li>
<li><a href="https://windows11.techidaily.com/dive-into-deeper-game-experience-incorporating-achievements-in-vintage-titles-through-retroarch/"><u>Dive Into Deeper Game Experience: Incorporating Achievements in Vintage Titles Through Retroarch</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-procedure-call-failures-in-malwarebytes-for-windows-os/"><u>Combatting Procedure Call Failures in Malwarebytes for Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/counteracting-dxgierrordeviceremoved-in-win-1011/"><u>Counteracting DXGI_ERROR_DEVICE_REMOVED in Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/compilation-of-best-windows-11-art-software/"><u>Compilation of Best Windows 11 Art Software</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-absence-of-drive-letters-problems-and-cures-for-win-users/"><u>Decoding the Absence of Drive Letters: Problems & Cures for Win Users</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-mastering-durecorder-complete-breakdown/"><u>[Updated] Mastering DuRecorder  Complete Breakdown</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-home-screen-preferences-on-w11-os/"><u>Customizing Home Screen Preferences on W11 OS</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-prolonged-sky-journeys-the-ultimate-drone-lineup/"><u>In 2024, Prolonged Sky Journeys  The Ultimate Drone Lineup</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-new-guide-how-to-check-icloud-activation-lock-status-on-your-iphone-xs-max-by-drfone-ios/"><u>In 2024, New Guide How To Check iCloud Activation Lock Status On Your iPhone XS Max</u></a></li>
<li><a href="https://windows11.techidaily.com/controlling-elements-post-sleep-for-optimal-use/"><u>Controlling Elements Post-Sleep for Optimal Use</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-from-conference-call-to-online-showcase-google-meet-on-youtube/"><u>In 2024, From Conference Call to Online Showcase  Google Meet on YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-windows-tools-chkdsk-sfc-and-disms-functions/"><u>Delving Into Windows Tools: CHKDSK, SFC & DISM's Functions</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>