---
title: Steps to Resolve 'Unavailable' Files Notification in Office Email App
date: 2024-09-09T18:25:50.906Z
updated: 2024-09-15T18:17:43.701Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Resolve 'Unavailable' Files Notification in Office Email App
excerpt: This Article Describes Steps to Resolve 'Unavailable' Files Notification in Office Email App
keywords: Fix Unavailable File Error,Office Email File Not Available,Solving Missing Office Emails,Clearing Office Download Issue,Stop 'Unavailable' Email Notification,Resolve File Unavailability,Overcoming Office Email Errors
thumbnail: https://thmb.techidaily.com/662c307b916403e88dc997e74395824da6bd2c6533fd74096afaf9205f685325.jpg
---

## Steps to Resolve 'Unavailable' Files Notification in Office Email App

 Do you keep getting the "this file cannot be previewed" error when previewing attachments in Outlook? The good news is that you don't need to download attachments every time you want to view them, as it is possible to fix this annoying issue.

 Below, we share eight quick and easy fixes for resolving the “this file cannot be previewed” error in Outlook for Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Install Relevant Apps to Preview Files

 Outlook may fail to preview attachments if the appropriate app for the file format is not installed on your PC. For instance, if you don’t have a[PDF reader app on your PC](https://www.makeuseof.com/tag/6-pdf-readers-windows/) , Outlook may display the “this file cannot be previewed because there is no previewer installed for it” error.

 To avoid this, ensure that the appropriate app or software for the file format is available on your computer. After that, Outlook should be able to preview your files without any problems.

## 2\. Disable Preview Handler in PowerToys

 Using Microsoft PowerToys is an excellent way to[boost your productivity on Windows computers](https://www.makeuseof.com/set-up-windows-pc-maximum-productivity/) . However, these PowerToys utilities can sometimes interfere with app processes and prevent apps from working properly.

 Several users on the forums reported fixing Outlook’s “this file cannot be previewed” error by disabling the Preview Handler feature. You can also give this method a shot.

1. Open the**PowerToys** app using the search menu.
2. Switch to the**File Explorer add-ons** tab using the left sidebar.
3. Under the**Preview Pane** section, disable the toggle next to**Portable Document Format** .  
![Disable Preview Handlers in PowerToys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disable-preview-handlers-in-powertoys.jpg)

## 3\. Enable Attachment Preview in Outlook

 It's possible that Outlook is failing to preview attachments because the file previewer feature is disabled in the app. To overrule this possibility, you need to check the attachment handling settings in Outlook.

1. Open the**Outlook** app on your PC.
2. Click the**File** menu in the top left corner.
3. Select**Options** from the left sidebar.
4. Navigate to the**Trust Center** tab and click the**Trust Center Settings** button.
5. In the**Attachment Handling** tab, clear the**Turn off Attachment Preview** checkbox.
6. Click on**Attachment and Document Previewers** and make sure all the previewers are active. Then, click**OK** .
7. Restart the Outlook app after this and see if you can preview attachments.  
![Attachment Handling in Outlook](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/attachment-handling-in-outlook.jpg)

## 4\. Change Outlook User Interface Settings

 Another thing you can do is tweak the User Interface Settings in Outlook and see if that gets the app to load attachment previews on Windows. Here are the steps for the same:

1. Open the Outlook app and click the**File** menu at the top.
2. Select**Options** from the left column.
3. In the Outlook Options window, navigate to the**General** tab.
4. Under the**User Interface Settings** section, select**Optimize for compatibility** option.  
![Optimize Outlook for Compatibility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/optimize-outlook-for-compatibility.jpg)

 Restart the Outlook app after this and check if the issue is still there.

## 5\. Clear Outlook Cache

 Outlook, like most apps, stores cache files on your computer to reduce loading times. Although this data is supposed to improve app performance, it’s not uncommon for it to become corrupted over time. When this happens, Outlook may malfunction or throw strange errors. You can try deleting the Outlook cache and see if that helps.

To delete Outlook cache data on Windows, use these steps:

1. Right-click on the Start icon or press**Win + X** to open the Power User menu.
2. Select**Run** from the list.
3. Type**%localappdata%\\Microsoft\\Outlook** in the text box and press**Enter** .
4. In the**RoamCache** folder that appears, select all the files and click the**trash icon** at the top to delete them.  
![Delete Outlook Cache Data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-outlook-cache-data.jpg)

## 6\. Enable Windows Firewall

 Have you disabled Windows Defender Firewall on your computer? That could prevent Outlook from previewing attachments.

 Here's how to check if the Windows Defender Firewall is enabled on your PC.

1. Press**Win + S** to open the search menu.
2. Type**Windows Security** in the search box and press**Enter** .
3. Select**Firewall & network protection** tab from the left pane.
4. Choose a network profile.
5. Enable the toggle for**Windows Defender Firewall** .  
![Enable Microsoft Defender Firewall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-microsoft-defender-firewall.jpg)

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2005183/22899" target="_top" id="2005183">
  <img src="//a.impactradius-go.com/display-ad/22899-2005183" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2005183/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Modify Registry Files

 Incorrect[Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) settings could also cause such anomalies. If that's the case, you'll need to correct the Registry settings manually on your PC.

 Since Registry files contain important settings for Windows and its apps, you should only use this method if you’re familiar with editing Registry files. Also, it’s a good idea to back up all the Registry files before you proceed. If you need help with that, check our guide on[how to back up Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the text box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > ​SOFTWARE > ​Microsoft > ​Windows > ​CurrentVersion > ​PreviewHandlers** .
5. Look for the following string values and check the associated**Data** on the right side.  
`{00020827-0000-0000-C000-000000000046} = Microsoft Excel previewer  
{21E17C2F-AD3A-4b89-841F-09CFE02D16B7} = Microsoft Visio previewer  
{65235197-874B-4A07-BDC5-E65EA825B718} = Microsoft PowerPoint previewer  
{84F66100-FF7C-4fb4-B0C0-02CD7FB668FE} = Microsoft Word previewer  
{DC6EFB56-9CFA-464D-8880-44885D7DC193} = Adobe PDF Preview Handler for Vista`  
![Preview Handlers in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/preview-handlers-in-registry.jpg)
6. If any of the above-mentioned values are missing, right-click on an empty spot and select**New > String Value** .

<!-- affiliate ads begin -->
<span id="2135471">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2135471.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2135471">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2135471.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2135471%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2135471/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Double-click on the newly created string value.
8. Enter the name of the application handler in the**Value data** field and click**OK** .
9. Right-click on the string value, select**Rename** and type the value associated with the application handler.
10. Exit the Registry Editor window and restart your PC.  
![Edit String in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/edit-string-in-registry.jpg)

## 8\. Run the Microsoft Office Repair Tool

 Microsoft Office includes a repair tool for fixing Office apps on Windows. So, if nothing works, you can run this tool to repair the Outlook app. Here's how:

1. [Use one of the many ways to open the Control Panel](https://www.makeuseof.com/windows-open-control-panel/) .
2. Go to**Programs and Features** .
3. Locate and select**Microsoft Office** on the list. Then, click the**Change** button at the top.
4. Select**Quick Repair** and then click**Repair** .  
![Repair Microsoft Office](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/repair-microsoft-office.jpg)

<!-- affiliate ads begin -->
<span id="1304648">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1304648.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1304648">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1304648.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1304648%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1304648/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Wait for the process to finish and check if you can preview files. If you can't, repeat the above steps to perform an**Online Repair** . As suggestive of its name, this process does necessitate an active internet connection on your computer.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134218/18498" target="_top" id="2134218">
  <img src="//a.impactradius-go.com/display-ad/18498-2134218" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134218/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Preview Your Outlook Attachments Again on Windows

 One of these eight fixes should take care of the “this file cannot be previewed” error in Outlook. If not, you can consider reinstalling the Outlook app as a last resort.

 If you're tired of dealing with the Outlook app's recurring problems, there are plenty of excellent email clients for Windows.

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
<li><a href="https://youtube-zero.techidaily.com/024-approved-from-zero-to-viral-video-top-10-user-friendly-youtube-concepts/"><u>[New] 2024 Approved From Zero to Viral Video Top 10 User-Friendly YouTube Concepts</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-secrets-unlocked-banishing-instagram-video-fails/"><u>[New] 2024 Approved Secrets Unlocked Banishing Instagram Video Fails</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-the-ultimate-guide-to-single-platform-gaming-in-apex-legends/"><u>[Updated] In 2024, The Ultimate Guide to Single-Platform Gaming in Apex Legends</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-in-2024-unique-identity-creation-accessible-logo-base-and-personal-customization-for-no-cost/"><u>[Updated] In 2024, Unique Identity Creation Accessible Logo Base & Personal Customization for No-Cost</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/breaking-down-madden-19-standout-modes-marred-by-ageing-formula/"><u>Breaking Down Madden '19: Standout Modes Marred by Ageing Formula</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatgpt-in-the-professional-sphere-6-compelling-reasons-for-skill-acquisition/"><u>ChatGPT in the Professional Sphere: 6 Compelling Reasons for Skill Acquisition</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-windows-data-source-configuration-interface/"><u>Exploring Windows Data Source Configuration Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/fixes-for-reactivating-the-windows-firewall-system/"><u>Fixes for Reactivating the Windows Firewall System</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-transform-your-speech-the-7-top-vocal-changer-mobile-apps/"><u>In 2024, Transform Your Speech The 7 Top Vocal Changer Mobile Apps</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/nahimic-driver-enhancement-made-simple-recent-improvements-revealed/"><u>Nahimic Driver Enhancement Made Simple – Recent Improvements Revealed</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlined-methods-program-size-modification-via-keyboard-in-win11/"><u>Streamlined Methods: Program Size Modification via Keyboard in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-new-interface-redesigned-widgets-chooser-for-win11/"><u>Tailoring New Interface: Redesigned Widgets Chooser for Win11</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/top-review-of-the-eero-pro-wireless-router-ensuring-seamless-wi-fi-connectivity-across-every-room/"><u>Top Review of the Eero Pro Wireless Router: Ensuring Seamless Wi-Fi Connectivity Across Every Room</u></a></li>
</ul></div>
