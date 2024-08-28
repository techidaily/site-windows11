---
title: "Safeguard Privacy: Erasing MS Defender Logs in Windows 10/11"
date: 2024-08-27T16:06:13.680Z
updated: 2024-08-28T16:06:13.680Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Safeguard Privacy: Erasing MS Defender Logs in Windows 10/11"
excerpt: "This Article Describes Safeguard Privacy: Erasing MS Defender Logs in Windows 10/11"
keywords: Delete MS Defender Logs,Clear Privacy Data,Wipe Windows Defender Traces,Remove Defender Records,Purge Security Logs,Erase Antivirus Files,Cleanup Surveillance Info,Wipe Defender Files,Remove Privacy Traces,Clean Surveillance Data,Erase Logs Safely,Delete Security Records,Purge Antivirus Info (Rephrased,Clear Privacy Footprint
thumbnail: https://thmb.techidaily.com/459b794516e41ca817af82c1c22066d193c455f4891dd7a8e040210befb5bf6c.jpg
---

## Safeguard Privacy: Erasing MS Defender Logs in Windows 10/11

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
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Then right-click on **Operational** and select **Open** to view all the past logs.  
![Open Operational Option to View Defender Logs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Open-Operational-Option-to-View-Defender-Logs.jpg)
8. Now you can right-click on **Operational** in the left pane and choose **Clear Log**. Or click on **Clear Log** on the right pane under **Actions**.  
<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
![Options to Clear Log from Left Pane or Under Actions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Options-to-Clear-Log-Of-Windows-Defender.jpg)
9. Select **Clear** to clear the protection history. If you wish to save the protection history logs for future reference before clearing them, select **Save and Clear**.  
![Options to Clear Logs or Save and Clear Defender Logs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Clear-and-Save-and-Clear-Options-for-Defender-Logs.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. How to Clear the Microsoft Defender Protection History via PowerShell

 What if you want the Protection History to clear automatically after a specific number of days? You can also use a PowerShell command to do that. Let's see how to do this:

1. Type **PowerShell** in the search bar. Right-click on **Windows PowerShell** under **Best match** and select **Run as administrator**. Or choose **Run as administrator** on the right search pane.
2. Click **Yes** on the UAC prompt that appears.
3. The **Administrator: PowerShell** window will open up. Type or copy and paste the following command and then hit **enter**:

`Set-MpPreference -ScanPurgeItemsAfterDelay 7`

![Command to Clear Protection History in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/PowerShell-Command-to-Clear-Protection-History.jpg)

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The number **7** at the end of the command is the number of days after which the protection history logs will be cleared. Just change that number to specify when you want the protection history to be cleared. And it will be cleared automatically.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
 Now, you won't need to manually clear Protection History every time—the items in the scan history folder would be deleted automatically after the days you've specified.

## Clear the Microsoft Defender Protection History Whenever You Want

 If you ever want to clear Defender Protection History, you know how easy it is to do it through any of the four ways discussed above. If you would want to refer to the Protection History logs later, you can use the Save and Clear option while clearing Protection History using Event Viewer.

 Though Protection History gets deleted after some time, you might want to have more control to clear it by yourself. So let's see how you can clear Protection History in four ways.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-tips.techidaily.com/harting-your-course-building-plays-on-youtube-for-2024/"><u>[New] Charting Your Course  Building Plays on YouTube for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-direct-links-sharing-twitch-content-with-friends-on-fb/"><u>[New] In 2024, Direct Links  Sharing Twitch Content with Friends on FB</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-leveraging-whatsapps-features-for-twitter-video-distribution/"><u>2024 Approved  Leveraging WhatsApp's Features for Twitter Video Distribution</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-sound-in-obs-studio-resolving-no-audio-on-win-11/"><u>Amplify Sound in OBS Studio - Resolving No Audio on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-resolving-11-windows-11-errors/"><u>Essential Guide: Resolving 11 Windows 11 Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-installation-failed-for-discord-on-windows-11-and-11/"><u>Fix 'Installation Failed' For Discord on Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-it-faster-quick-solutions-for-winning-at-powerpoint-prints-in-windows/"><u>Fix It Faster: Quick Solutions for Winning at PowerPoint Prints in Windows</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-a-step-by-step-guide-to-finding-your-apple-id-on-your-apple-iphone-13-by-drfone-ios/"><u>In 2024, A Step-by-Step Guide to Finding Your Apple ID On Your Apple iPhone 13</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-art-of-adding-soundtracks-to-instagram-visuals/"><u>In 2024, The Art of Adding Soundtracks to Instagram Visuals</u></a></li>
<li><a href="https://windows11.techidaily.com/lost-features-a-step-by-step-guide-to-find-windows-11s-enhancement/"><u>Lost Features? A Step-by-Step Guide to Find Windows 11'S Enhancement</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-mouse-cursor-visibility-and-clarity-windows-edition/"><u>Maximizing Mouse Cursor Visibility and Clarity - Windows Edition</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/methods-to-transfer-from-apple-iphone-12-pro-to-android-drfone-by-drfone-transfer-from-ios/"><u>Methods to Transfer from Apple iPhone 12 Pro to Android | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-windows-1011-photography-troubles-with-ease/"><u>Navigate Windows 10/11 Photography Troubles with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-error-signals-in-windows-a-guide-to-using-command-prompt-for-diagnostics/"><u>Navigating Error Signals in Windows: A Guide to Using Command Prompt for Diagnostics</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-pink-screen-crisis-on-your-system/"><u>Navigating the Pink Screen Crisis on Your System</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/obs-and-youtube-a-beginners-live-stream-blueprint-for-2024/"><u>OBS and Youtube  A Beginner's Live Stream Blueprint for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-failed-task-runner-in-windows/"><u>Overcoming Failed Task Runner in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-hypervisorbsod-top-5-fixes-for-windows-os/"><u>Overcoming HYPERVISOR_BSOD: Top 5 Fixes for Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-microsofts-dism-hurdle-code-0x800f082f/"><u>Overcoming Microsoft's DISM Hurdle: Code 0X800F082F</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-solution-fixing-try-connecting-your-device-on-win-11/"><u>Quick Solution: Fixing 'Try Connecting Your Device' On Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstating-default-organization-of-windows-files/"><u>Reinstating Default Organization of Windows Files</u></a></li>
<li><a href="https://windows11.techidaily.com/reversing-the-access-entry-corrupted-windows-malfunction/"><u>Reversing the 'Access Entry Corrupted' Windows Malfunction</u></a></li>
<li><a href="https://windows11.techidaily.com/stopping-self-initiated-file-explorer-windows/"><u>Stopping Self-Initiated File Explorer Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-opening-windows-stubborn-folders-on-double-click/"><u>The Ultimate Guide: Opening Windows' Stubborn Folders on Double-Click</u></a></li>
<li><a href="https://windows11.techidaily.com/transition-smoothly-chrome-adaptation-tips-for-windows-11/"><u>Transition Smoothly: Chrome Adaptation Tips for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/turning-offlight-on-notepadwindows/"><u>Turning Offlight On NotepadWindows</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/unlocking-earnings-potential-essential-view-numbers-for-2024/"><u>Unlocking Earnings Potential  Essential View Numbers for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-puzzle-of-windows-subsystem-for-linux-error-4294967295/"><u>Unraveling the Puzzle of Windows Subsystem for Linux Error 4294967295</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-in-2024-s-hottest-4k8k-video-editing-tools-a-comprehensive-guide/"><u>Updated In 2024, S Hottest 4K/8K Video Editing Tools A Comprehensive Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/what-is-telegram-messenger-and-how-does-it-work/"><u>What Is Telegram Messenger and How Does It Work?</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/what-legendaries-are-in-pokemon-platinum-on-honor-magic-v2-drfone-by-drfone-virtual-android/"><u>What Legendaries Are In Pokemon Platinum On Honor Magic V2? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-system-deciphering-report-creation-and-analysis/"><u>Windows System Deciphering: Report Creation & Analysis</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>