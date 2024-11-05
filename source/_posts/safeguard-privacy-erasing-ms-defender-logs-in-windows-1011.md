---
title: "Safeguard Privacy: Erasing MS Defender Logs in Windows 10/11"
date: 2024-10-30T10:34:37.269Z
updated: 2024-11-05T03:31:53.719Z
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
<span id="1993647">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993647.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993647">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993647.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993647%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993647/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Then right-click on **Operational** and select **Open** to view all the past logs.  
![Open Operational Option to View Defender Logs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Open-Operational-Option-to-View-Defender-Logs.jpg)
8. Now you can right-click on **Operational** in the left pane and choose **Clear Log**. Or click on **Clear Log** on the right pane under **Actions**.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918714/19272" target="_top" id="1918714">
  <img src="//a.impactradius-go.com/display-ad/19272-1918714" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918714/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Options to Clear Log from Left Pane or Under Actions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Options-to-Clear-Log-Of-Windows-Defender.jpg)
9. Select **Clear** to clear the protection history. If you wish to save the protection history logs for future reference before clearing them, select **Save and Clear**.  
![Options to Clear Logs or Save and Clear Defender Logs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Clear-and-Save-and-Clear-Options-for-Defender-Logs.jpg)

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2135315/14409" target="_top" id="2135315">
  <img src="//a.impactradius-go.com/display-ad/14409-2135315" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2135315/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082533/7443" target="_top" id="2082533">
  <img src="//a.impactradius-go.com/display-ad/7443-2082533" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082533/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. How to Clear the Microsoft Defender Protection History via PowerShell

 What if you want the Protection History to clear automatically after a specific number of days? You can also use a PowerShell command to do that. Let's see how to do this:

1. Type **PowerShell** in the search bar. Right-click on **Windows PowerShell** under **Best match** and select **Run as administrator**. Or choose **Run as administrator** on the right search pane.
2. Click **Yes** on the UAC prompt that appears.
3. The **Administrator: PowerShell** window will open up. Type or copy and paste the following command and then hit **enter**:

`Set-MpPreference -ScanPurgeItemsAfterDelay 7`

![Command to Clear Protection History in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/PowerShell-Command-to-Clear-Protection-History.jpg)

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2129041/19576" target="_top" id="2129041">
  <img src="//a.impactradius-go.com/display-ad/19576-2129041" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2129041/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The number **7** at the end of the command is the number of days after which the protection history logs will be cleared. Just change that number to specify when you want the protection history to be cleared. And it will be cleared automatically.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130885/7443" target="_top" id="2130885">
  <img src="//a.impactradius-go.com/display-ad/7443-2130885" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130885/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-lab.techidaily.com/ed-how-to-light-your-youtube-video-for-2024/"><u>[Updated] How To Light Your YouTube Video for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-frame-by-frame-magic-best-video-screenshots/"><u>2024 Approved Frame-by-Frame Magic Best Video Screenshots</u></a></li>
<li><a href="https://windows11.techidaily.com/7-unique-windows-methods-for-launching-applications/"><u>7 Unique Windows Methods for Launching Applications</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/a-guide-xiaomi-redmi-note-12-4g-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>A Guide Xiaomi Redmi Note 12 4G Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723964494295-catch-the-steal-of-a-lifetime-premium-corsairs-1000w-small-form-factor-psu-at-an-unbeatable-price/"><u>Catch the Steal of a Lifetime - Premium Corsair's 1000W Small Form Factor PSU at an Unbeatable Price!</u></a></li>
<li><a href="https://windows11.techidaily.com/evaluating-hidden-gems-in-windows-system-monitors/"><u>Evaluating Hidden Gems in Windows' System Monitors</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-a-honor-80-pro-straight-screen-edition-easily-by-drfone-android/"><u>How To Unlock a Honor 80 Pro Straight Screen Edition Easily?</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-soundtrack-your-life-a-complete-guide-to-adding-personalized-ringtones-and-sounds/"><u>In 2024, Soundtrack Your Life A Complete Guide to Adding Personalized Ringtones & Sounds</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-techniques-for-an-opening-windows-terminal/"><u>Mastering Techniques for an Opening Windows Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-touchpad-sensitivity-in-windows-11-devices/"><u>Mastering Touchpad Sensitivity in Windows 11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/reduce-precision-jumps-turn-off-mouse-speed-on-your-pc/"><u>Reduce Precision Jumps: Turn Off Mouse Speed on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-steps-to-launch-wordpad-on-windows/"><u>Seamless Steps to Launch WordPad on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-resolving-windows-11s-isdonedll-problems/"><u>Strategies for Resolving Windows 11'S ISDone.dll Problems</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ior-sound-modification-equipment-for-video-artists-for-2024/"><u>Superior Sound Modification Equipment for Video Artists for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-inactive-mail-signals-on-desktop-os/"><u>Tackling Inactive Mail Signals on Desktop OS</u></a></li>
<li><a href="https://technical-tips.techidaily.com/transforming-businesses-with-apple-vision-pro-5-leading-organizations-showcase-success-stories-powered-analysis/"><u>Transforming Businesses with Apple Vision Pro: 5 Leading Organizations Showcase Success Stories | Powered Analysis</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/which-is-better-the-galaxy-s10plus-or-the-new-galaxy-s20-expert-review/"><u>Which Is Better: The Galaxy S10+ or the New Galaxy S20? Expert Review</u></a></li>
</ul></div>

