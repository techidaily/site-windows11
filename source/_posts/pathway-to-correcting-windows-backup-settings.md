---
title: Pathway to Correcting Windows Backup Settings
date: 2024-09-09T12:03:46.928Z
updated: 2024-09-10T12:03:46.928Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Pathway to Correcting Windows Backup Settings
excerpt: This Article Describes Pathway to Correcting Windows Backup Settings
keywords: Fix Windows Backup Issues,Update Backup Settings,Adjust Windows Backup,Change Backup Schedule,Reset Backup Preferences,Modify Backup Options,Correct Backup Configuration
thumbnail: https://thmb.techidaily.com/d2e4e8d37dd44251b856b042284c1dfc0b019c21a2404b925ef4f20286104a39.jpg
---

<!-- affiliate ads begin -->
<span id="1993652">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Pathway to Correcting Windows Backup Settings

 System failure or data loss can cause huge amounts of damage and that’s why Windows offers a backup feature to protect your critical data. If your backups corrupt or otherwise function incorrectly, you can reset Windows Backup to its default settings. This guide will teach you some methods to reset Windows Backup to its default on Windows.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118312/7443" target="_top" id="2118312">
  <img src="//a.impactradius-go.com/display-ad/7443-2118312" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118312/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How Do I Know if I Need to Reset Windows Backup?

 You may need to reset Windows Backup if your backups aren't working, taking too long to create, or you can't access the stored files. If you are experiencing these issues, resetting Windows Backup may resolve them.

 For this, either use the Command Prompt or create a batch file. The steps for both methods are outlined below and should help you get your backups running again.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136618/26400" target="_top" id="2136618">
  <img src="//a.impactradius-go.com/display-ad/26400-2136618" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136618/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Is Resetting Window Backup Risky?

 While resetting Windows Backup is generally safe, there are some risks associated with it.

 Firstly, you may lose all existing backups if you reset Windows Backup. To ensure you don't lose data, [create a backup of the existing Windows files](https://www.makeuseof.com/tag/backup-windows-files-folders/) before resetting Windows Backup.

 Furthermore, the reset may affect some third-party apps. It's wise to check with your software vendor before resetting Windows Backup.

 If something goes wrong during the reset, you may have a corrupted backup configuration. In such cases, reinstall the operating system and start from scratch.

 Overall, resetting Windows Backup helps resolve existing issues, but take the necessary precautions to avoid potential risks.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139117/17108" target="_top" id="2139117">
  <img src="//a.impactradius-go.com/display-ad/17108-2139117" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139117/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Reset Windows Backup to Its Factory Settings

 Now you know how to proceed with caution, here's how to reset Windows Backup to its factory settings.

### 1\. Using Command Prompt

 If your current backup configuration isn't working, reset Windows Backup to its default settings. To get started, [run the Command Prompt with admin access](https://www.makeuseof.com/windows-run-command-prompt-admin/). In the Command Prompt window, run the following command:

`reg delete HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup /f`

 This will reset to the default configuration and remove all existing backups.

 After that, copy and paste the following command into the Command Prompt window and press **Enter**:

`reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup`

 This will recreate the WindowsBackup entry in the registry editor. Next, type in and run the below command to delete the Automatic Backup scheduled task on Windows:

`schtasks /delete /tn "Microsoft\Windows\WindowsBackup\AutomaticBackup" /f`

 Finally, execute the below command to delete the backup monitor scheduled task:

`schtasks /delete /tn "Microsoft\Windows\WindowsBackup\Windows Backup Monitor" /f`

 After executing the above commands, restart your computer. This will reset Windows Backup to its default settings.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134237/18498" target="_top" id="2134237">
  <img src="//a.impactradius-go.com/display-ad/18498-2134237" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134237/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Creating a Batch File

 If you're not comfortable with the command line interface, reset Windows Backup by creating a batch file.

 To do this, [open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and paste the below code.

`<code>reg delete HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup /f  
reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup  
schtasks /delete /tn "Microsoft\Windows\WindowsBackup\AutomaticBackup" /f  
schtasks /delete /tn "Microsoft\Windows\WindowsBackup\Windows Backup Monitor" /f`

 Click the **File** menu and select **Save as**. On the Save as dialog, type **reset-backup.bat** as the file name. Then choose **All Files** from the drop-down menu next to the Save as type. From the left panel, select **Desktop** and click the **Save** button.

 Now, close the Notepad window and right-click on the batch file. From the context menu, select **Run as administrator**. This will reset Windows Backup to its default settings.

 Lastly, restart your computer and you're done. These are two methods to reset Windows Backup to its default settings.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115920/19272" target="_top" id="2115920">
  <img src="//a.impactradius-go.com/display-ad/19272-2115920" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115920/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get Your Backups Working Again on Windows

 Whether you use the command line interface or create a batch file, it's easy to reset Windows Backup. Just remember to restart your computer after the process completes successfully.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-knowledge.techidaily.com/new-exploring-vegaspro-2019-edition-highlights/"><u>[New] Exploring VegasPro 2019 Edition Highlights</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-in-2024-the-ultimate-surveillance-avoidance-tips-for-instagrams-livestreams/"><u>[New] In 2024, The Ultimate Surveillance Avoidance Tips for Instagram's Livestreams</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-skyrocket-savings-on-clouds-compare-prices-s-lows-for-2024/"><u>[New] Skyrocket Savings on Clouds Compare Prices 'S Lows for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-undead-universe-discover-the-top-8-zombie-games-for-2024/"><u>[New] Undead Universe Discover the Top 8 Zombie Games for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-harmonious-hub-choosing-the-best-free-apps-for-your-youtube-music-streams/"><u>2024 Approved Harmonious Hub Choosing the Best Free Apps for Your YouTube Music Streams</u></a></li>
<li><a href="https://buynow-help.techidaily.com/choosing-between-tech-giants-why-fitbit-sense-takes-on-the-apple-watch-for-holistic-health-management/"><u>Choosing Between Tech Giants: Why Fitbit Sense Takes on the Apple Watch for Holistic Health Management</u></a></li>
<li><a href="https://windows11.techidaily.com/explore-the-full-potential-of-windows-powertoys-with-these-10-tips/"><u>Explore the Full Potential of Windows PowerToys with These 10 Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/exposing-the-wacatacbml-trojan-your-ultimate-windows-protection-plan/"><u>Exposing the Wacatac.B!ml Trojan - Your Ultimate Windows Protection Plan</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-correct-gl-error-3-with-nvidia-on-windows-oses/"><u>How to Correct GL Error 3 with Nvidia on WIndows OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-enable-controlled-folder-access-in-windows-11-and-11/"><u>How to Enable Controlled Folder Access in Windows 11 & 11</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-unfortunately-contacts-has-stopped-error-on-nokia-g310-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Unfortunately, Contacts Has Stopped Error on Nokia G310 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-prevent-auto-restart-events-on-win11/"><u>How to Prevent Auto-Restart Events on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-troubleshoot-high-cpu-usage-with-the-windows-resource-monitor/"><u>How to Troubleshoot High CPU Usage With the Windows Resource Monitor</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-wash-away-your-computers-defender-past/"><u>How to Wash Away Your Computer's Defender Past</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-easy-to-use-w10-screen-grabber-app/"><u>In 2024, Easy-to-Use W10 Screen Grabber App</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-market-victory-through-unwrapped-strategy/"><u>In 2024, Market Victory Through Unwrapped Strategy</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-law-filters-in-windows-an-experts-perspective/"><u>Leveraging LAW Filters in Windows – An Expert's Perspective</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-win11s-accessibility-keys/"><u>Mastering Win11's Accessibility Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-non-working-escape-keys-on-your-windows-system/"><u>Navigating Non-Working Escape Keys on Your Windows System</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-maze-of-chrome-profile-disruptions-on-desktop/"><u>Navigating the Maze of Chrome Profile Disruptions on Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-disconnection-issues-of-razer-hardware-in-win-1011/"><u>Overcoming Disconnection Issues of Razer Hardware in Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/precise-control-setup-adjusting-shortcut-locations-on-windows-11s-power-icon/"><u>Precise Control Setup: Adjusting Shortcut Locations on Windows 11'S Power Icon</u></a></li>
<li><a href="https://windows11.techidaily.com/regaining-access-post-failed-windows-login-attempt/"><u>Regaining Access Post Failed Windows Login Attempt</u></a></li>
<li><a href="https://windows11.techidaily.com/regaining-access-fixing-malwarebytes-service-errors-in-windows-1011/"><u>Regaining Access: Fixing Malwarebytes' Service Errors in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagining-your-windows-profile-a-new-username-approach/"><u>Reimagining Your Windows Profile: A New UserName Approach</u></a></li>
<li><a href="https://driver-error.techidaily.com/removing-autostart-of-win11s-bluetooth/"><u>Removing Autostart of Win11's Bluetooth</u></a></li>
<li><a href="https://windows11.techidaily.com/reversing-file-locks-on-windows-os/"><u>Reversing File Locks on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-lost-connection-re-list-bluetooth-in-dmi/"><u>Reviving Lost Connection: Re-List Bluetooth in DMI</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-connection-lost-5-easy-steps-for-a-fixed-usb-wi-fi-adapter/"><u>Seamless Connection Lost? 5 Easy Steps for a Fixed USB Wi-Fi Adapter</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-global-mouse-navigation-made-simple-with-powertoys/"><u>Seamless Global Mouse Navigation Made Simple with PowerToys</u></a></li>
<li><a href="https://windows11.techidaily.com/stay-ahead-postpone-windows-edge-tabs-on-w11/"><u>Stay Ahead: Postpone Windows Edge Tabs on W11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-tackle-missing-device-driver-issue-on-windows-startup/"><u>Steps to Tackle Missing Device Driver Issue on Windows Startup</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-cut-down-energy-use-of-wlanextexe/"><u>Strategies to Cut Down Energy Use of Wlanext.EXE</u></a></li>
<li><a href="https://android-transfer.techidaily.com/top-5-from-gionee-f3-pro-to-iphone-contacts-transfer-apps-and-software-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Top 5 from Gionee F3 Pro to iPhone Contacts Transfer Apps and Software | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-non-loading-drivers-in-windows-11/"><u>Troubleshooting Non-Loading Drivers in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-ignoring-local-lsa-warning/"><u>Troubleshooting Windows: Ignoring Local LSA Warning</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>