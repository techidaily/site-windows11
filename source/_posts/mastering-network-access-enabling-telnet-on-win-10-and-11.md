---
title: "Mastering Network Access: Enabling Telnet on Win 10 and 11"
date: 2024-09-05T02:14:02.574Z
updated: 2024-09-06T02:14:02.574Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Network Access: Enabling Telnet on Win 10 and 11"
excerpt: "This Article Describes Mastering Network Access: Enabling Telnet on Win 10 and 11"
keywords: Win 10 Telnet Setup,Windows 10 Remote Access,Win 11 Networking,Enable Telnet on PCs,Secure Telnet Win10,Win11 Remote Terminal,Telnet Security Windows
thumbnail: https://thmb.techidaily.com/8614a77f9e633f7b68cb429db560c3992306d2b5be6c80ea6d2432a854e4bb42.jpg
---

## Mastering Network Access: Enabling Telnet on Win 10 and 11

 Despite the vulnerability issues, Telnet is still used as a client-server protocol by Windows users. It is primarily used for initial network hardware configuration, remote access, port testing and forwarding, and other tasks that don't involve sensitive information transfer.

 You can enable Telnet on Windows 10 and 11 computers via Command Prompt or the Graphics User Interface (GUI) tool. Here we show you the many ways to enable Telnet on your Windows computer.

## 1\. Enable Telnet on Windows Using Control Panel

 You can enable Telnet Client using the Classic Control Panel. Since it is an optional feature, you can enable it using the Windows Optional Feature dialog. You can use it[add or remove other users' optional features on Windows](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) .

To enable Telnet Client using Control Panel:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel.**
3. In Control Panel, Click on**Uninstall a Program** under**Programs and Features.**  
![turn windows features on or off control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/turn-windows-features-on-or-off-control-panel.jpg)
4. In the left pane, click on the**Turn Windows feature on or off.**  
![enable telnet client windows features dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-windows-features-dialog.jpg)
5. In the Windows Features dialog, scroll down and select**Telnet Client.**
6. Click**OK** and wait for the feature to install. Once installed, restart your PC to apply the changes and enable the feature.

If you need to disable Telnet:

1. Open the**Windows Features** dialog and unselect**Telnet Client.**
2. Click**OK** and wait for the feature to uninstall.
3. Click on**Restart** now to reboot your PC and apply the changes.

## 2\. Enable Telnet Client Using Windows PowerShell

![enable telnet client powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-powershell.jpg)

 You can use the Enable-WindowsOptionalFeature cmdlet to enable Telnet Client using Windows PowerShell. Useful if you are unable to turn on the feature using the Windows Features dialog and it is also faster than the GUI method.

To enable Telnet using Windows PowerShell:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Windows Terminal(Admin)** and click**Yes** to open the terminal app as administrator. If you are using Windows 10, type**PowerShell** in**Windows Search** and open**Windows PowerShell** administrator.
3. In the PowerShell window, type the following command and press**Enter** to enable Telnet:  
`Enable-WindowsOptionalFeature -Online -FeatureName TelnetClient`
4. This process may take several minutes, so wait for it to complete and return a status report. If successful, you’ll see the result as**Online:True.**
5. If you want to disable Telnet Client, use the following command instead:  
`Disable-WindowsOptionalFeature -Online -FeatureName TelnetClient`
6. Close PowerShell and restart your PC.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094429/7443" target="_top" id="2094429">
  <img src="//a.impactradius-go.com/display-ad/7443-2094429" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094429/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Install Telnet Client Using Command Prompt

![enable telnet command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082530/7443" target="_top" id="2082530">
  <img src="//a.impactradius-go.com/display-ad/7443-2082530" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082530/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If you prefer Command Prompt over PowerShell, you can use the DISM /Online command to enable the optional features on your Windows 11 computer.

Follow these steps to install Telnet using Command Prompt:

1. Press the**Win** key and type**cmd** .
2. Right-click on**Command Prompt** and select**Run as administrator.**
3. In the Command Prompt window, type the following command and press**Enter** :  
`dism /online /Enable-Feature /FeatureName:TelnetClient`
4. Command Prompt will start enabling the feature and display the operation completed successfully message.
5. If you need to disable Telnet, type the following command and press**Enter** :  
`dism /Online /Disable-Feature /FeatureName:TelnetClient`
6. Wait for the success message.
7. Type**exit** and press**Enter** to close Command Prompt.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484944/16446" target="_top" id="1484944">
  <img src="//a.impactradius-go.com/display-ad/16446-1484944" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484944/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Check the Telnet Client Status on Your PC

![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948937/19272" target="_top" id="1948937">
  <img src="//a.impactradius-go.com/display-ad/19272-1948937" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948937/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You can check if the Telnet client is enabled on your PC using a Command Prompt command. When enabled, the Telnet command will open a new CMD to connect to remote servers and perform other tasks.

1. Launch Command Prompt as administrator (see[how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
2. In the Command Prompt window, type**Telnet** and press**Enter** .
3. A new CMD with Microsoft Telnet will open.

<!-- affiliate ads begin -->
<span id="2135472">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2135472.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2135472">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2135472.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2135472%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2135472/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## All the Ways to Enable Telnet On Your Windows 11 Computer

 Telnet is a built-in remote access utility that you can use to troubleshoot firewall and network issues. While it is still part of Windows, system administrators now prefer the more secure SSH protocol to access computers over an unsecured network.

 The major disadvantage of Telnet is that it is not secure and prone to a man-in-the-middle attack. If not for particular situations, switch to a more secure network protocol such as SSH and Mosh with better password and public key authentication.


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
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-mastering-slack-and-filmora-scheduling-meetings-flawlessly/"><u>[New] 2024 Approved  Mastering Slack & Filmora  Scheduling Meetings Flawlessly</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-uncover-hubs-sites-that-connect-you-with-youtube-branding-deals/"><u>[New] 2024 Approved  Uncover Hubs  Sites That Connect You with YouTube Branding Deals</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-step-by-step-starting-a-skype-call-on-android/"><u>[Updated] Step-by-Step  Starting a Skype Call on Android</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-superior-smartphone-editors-elevating-your-gopro-shots/"><u>[Updated] Superior Smartphone Editors Elevating Your GoPro Shots</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-the-ultimate-guide-to-10-leading-pc-vr-headsets/"><u>[Updated] The Ultimate Guide to 10 Leading PC VR Headsets</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-ultimate-guide-to-organizing-fb-giveaways/"><u>[Updated] The Ultimate Guide to Organizing FB Giveaways</u></a></li>
<li><a href="https://windows11.techidaily.com/1-mastering-error-free-excel-sheets-a-step-by-step-guide-to-automatic-spelling-correction/"><u>1. Mastering Error-Free Excel Sheets: A Step-by-Step Guide to Automatic Spelling Correction</u></a></li>
<li><a href="https://windows11.techidaily.com/1-mastering-image-to-excel-conversion-a-step-by-step-guide-for-microsoft-windows/"><u>1. Mastering Image-to-Excel Conversion: A Step-by-Step Guide for Microsoft Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/1-seamless-integration-microsoft-office-and-libreoffice-working-together-smoothly/"><u>1. Seamless Integration: Microsoft Office and LibreOffice Working Together Smoothly</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2023-guide-ios-device-live-recording-techniques/"><u>2023 Guide  IOS Device Live Recording Techniques</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-boosting-earnings-in-the-quick-flicks-of-youtube-shorts/"><u>2024 Approved  Boosting Earnings in the Quick Flicks of YouTube Shorts</u></a></li>
<li><a href="https://howto.techidaily.com/8-workable-fixes-to-the-sim-not-provisioned-mm2-error-on-vivo-y200e-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Workable Fixes to the SIM not provisioned MM#2 Error on Vivo Y200e 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/beginning-your-journey-with-windows-live-mesh-2011-the-ultimate-guide-for-seamless-data-management/"><u>Beginning Your Journey with Windows Live Mesh 2011 – The Ultimate Guide for Seamless Data Management</u></a></li>
<li><a href="https://tech-revival.techidaily.com/bypass-wasteful-chatgpt-plugins-top-6-to-skip-now/"><u>Bypass Wasteful ChatGPT Plugins - Top 6 to Skip Now!</u></a></li>
<li><a href="https://windows11.techidaily.com/check-out-the-most-recent-updates-to-microsoft-office-suite-whats-new/"><u>Check Out the Most Recent Updates to Microsoft Office Suite: What's New?</u></a></li>
<li><a href="https://windows11.techidaily.com/complete-guide-securing-data-with-cell-locking-techniques-in-excel/"><u>Complete Guide: Securing Data with Cell Locking Techniques in Excel</u></a></li>
<li><a href="https://screen-capture.techidaily.com/comprehensive-look-at-razer-kiyo-webcam-for-2024/"><u>Comprehensive Look at Razer Kiyo Webcam for 2024</u></a></li>
<li><a href="https://buynow-help.techidaily.com/discover-the-premier-smartwatch-selection-available-this-year/"><u>Discover the Premier Smartwatch Selection Available This Year</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-strategies-for-tracking-edits-and-modifications-in-real-time-with-excel-online/"><u>Effective Strategies for Tracking Edits and Modifications in Real-Time with Excel Online</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-techniques-to-compress-data-within-cells-using-microsoft-excel/"><u>Effective Techniques to Compress Data Within Cells Using Microsoft Excel</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-methods-for-identifying-and-enclosing-erroneous-data-points-in-microsoft-excel/"><u>Efficient Methods for Identifying and Enclosing Erroneous Data Points in Microsoft Excel</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-planning-tasks-using-excels-gantt-chart-technique/"><u>Efficiently Planning Tasks Using Excel's Gantt Chart Technique</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-your-data-visualization-tutorial-on-secondary-axis-management-in-excel-charts/"><u>Enhancing Your Data Visualization: Tutorial on Secondary Axis Management in Excel Charts</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/how-to-respond-to-unexpected-content-rejections-by-fb-platform-for-2024/"><u>How to Respond to Unexpected Content Rejections by FB Platform for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-top-7-skype-hacker-to-hack-any-skype-account-on-your-vivo-t2-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Skype Hacker to Hack Any Skype Account On your Vivo T2 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/master-microsoft-excel-a-comprehensive-guide-with-12-tricks-for-correcting-faulty-formulas/"><u>Master Microsoft Excel: A Comprehensive Guide with 12 Tricks for Correcting Faulty Formulas</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-excel-a-step-by-step-guide-to-searching-and-substituting-text-and-numbers/"><u>Mastering Excel: A Step-by-Step Guide to Searching and Substituting Text & Numbers</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-unit-conversions-a-step-by-step-guide-using-microsoft-excel/"><u>Mastering Unit Conversions: A Step-by-Step Guide Using Microsoft Excel</u></a></li>
<li><a href="https://techidaily.com/nas-device-compatibility-issues-with-windows-11-update-24h2/"><u>NAS Device Compatibility Issues with Windows 11 Update 24H2</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/precision-editing-embedding-times-in-video-posts-for-2024/"><u>Precision Editing  Embedding Times in Video Posts for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/er-10-sound-scaling-options-pcs-and-phones-for-2024/"><u>Premier 10 Sound Scaling Options  PCs & Phones for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-adding-images-to-your-microsoft-excel-spreadsheet/"><u>Step-by-Step Guide: Adding Images to Your Microsoft Excel Spreadsheet</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-properly-formatting-telephone-digits-in-excel-spreadsheets/"><u>Step-by-Step Guide: Properly Formatting Telephone Digits in Excel Spreadsheets</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-removing-a-pivottable-from-your-microsoft-excel-spreadsheet/"><u>Step-by-Step Guide: Removing a PivotTable From Your Microsoft Excel Spreadsheet</u></a></li>
<li><a href="https://windows11.techidaily.com/top-13-essential-microsoft-excel-datetime-formulas-every-user-must-master/"><u>Top 13 Essential Microsoft Excel Date/Time Formulas Every User Must Master</u></a></li>
<li><a href="https://windows11.techidaily.com/top-6-tips-for-creating-simple-and-legible-excel-sheets/"><u>Top 6 Tips for Creating Simple and Legible Excel Sheets</u></a></li>
<li><a href="https://windows11.techidaily.com/ultimate-guide-to-harnessing-the-power-of-goal-seek-in-excel/"><u>Ultimate Guide to Harnessing the Power of Goal Seek in Excel</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-power-of-automatic-data-coloring-tips-for-setting-up-excels-conditional-formatting-rules/"><u>Unlocking the Power of Automatic Data Coloring: Tips for Setting Up Excel's Conditional Formatting Rules</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-latest-update-excels-enhanced-task-automation-on-windows/"><u>Unveiling the Latest Update: Excel's Enhanced Task Automation on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-of-locating-data-positions-with-excel-match-function-a-comprehensive-guide/"><u>Unveiling the Secrets of Locating Data Positions with Excel MATCH Function: A Comprehensive Guide</u></a></li>
</ul></div>
