---
title: Streamlining Troubleshoot Processes in Win10/Win11
date: 2024-10-04T02:46:11.429Z
updated: 2024-10-07T03:48:25.827Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Streamlining Troubleshoot Processes in Win10/Win11
excerpt: This Article Describes Streamlining Troubleshoot Processes in Win10/Win11
keywords: Windows Troubleshooting Guide,Win10 Diagnostics Toolkit,Win11 Quick Fix Guide,System Health Checker,Optimize PC Repair,Tech Support Streamline,Efficient OS Maintenance
thumbnail: https://thmb.techidaily.com/73f237caff1293d1dd4178031db987cf4821ccb81a94a966ce0f48ea51b79037.jpg
---

## Streamlining Troubleshoot Processes in Win10/Win11

 Users often utilize the pre-installed Windows 11/10 troubleshooters available in Settings to fix update, sound, internet, microphone, video playback, Bluetooth, and UWP app issues. However, sometimes those troubleshooters display messages in their windows that say, “An error occurred while troubleshooting.” Or the message might say, “An error occurred while loading the troubleshooter.”

 The full error messages and codes can vary slightly and appear after users select to run the troubleshooters. Consequently, the affected Windows troubleshooters don’t work. This is how you can fix troubleshooters not working on Windows 11/10 PCs.

## 1\. Scan and Repair System Files

 Some users have said the system file and image repair tools helped them fix Windows 11/10 troubleshooting tools not working. System File Checker is the command-line tool for repairing system file corruptions. Deployment Image Servicing and Management is a utility you can run to address issues with the Windows image. Try running both those tools in the Command Prompt, as covered within this [guide for repairing corrupted Windows files](https://www.makeuseof.com/system-file-checker-sfc-windows/).

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/sfc-scannow-command4.jpg)

## 2\. Enable or Restart Required Services

 Windows troubleshooters can stop working because required services are disabled or not running. Enabling and starting services like Cryptographic Services, Windows Update, BITS, and Windows Installer is a potential resolution for fixing troubleshooters users confirm to work. Try starting those required services like this:

1. Bring up the service management app with a method in this [guide to opening Services](https://www.makeuseof.com/windows-11-open-services-app/).
2. Double-click **Cryptographic Services** to bring up a settings window.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/cryptographic-services.jpg)
3. Click on the **Startup type** drop-down menu and choose the **Automatic** setting if a different option is selected.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2005196/22899" target="_top" id="2005196">
  <img src="//a.impactradius-go.com/display-ad/22899-2005196" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2005196/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Next, select the **Start** option for the service to run.  
![The Cryptographic Services Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/cryptographic-services-window.jpg)
5. Click on the **Apply** and **OK** options to set your selected settings.
6. Repeat the previous steps for the Windows Update, Windows Installer, and the Background Intelligent Transfer Service.

 If those services are already running and set to an automatic startup, try restarting them. Right-click the service in the Services window and select a **Restart** option.

## 3\. Flush the DNS Cache and Reset the Winsock Catalog

 Network issues can cause some troubleshooters for which an internet connection is more essential to malfunction. Flushing the DNS cache and resetting the Winsock catalog can address such network issues. This potential fix is especially recommended for fixing the Windows Update troubleshooter. You can flush the DNS cache and reset the Winsock catalog by executing two commands like this:

1. Open the Command Prompt app with elevated privileges. If you’re unsure how to access that app, check out this guide for [opening Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Input and execute this command for flushing the DNS cache:  
`ipconfig /flushdns`  
![The ipconfig /flushdns command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/ipconfig-flushdns-command.jpg)
3. To reset Winsock, execute this command:  
`netsh winsock reset`  
![The netsch winsock reset command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/netsch-winsock-reset-command.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037475/7443" target="_top" id="2037475">
  <img src="//a.impactradius-go.com/display-ad/7443-2037475" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Disable Third-Party Security Software and Firewalls

 Many security software packages incorporate firewalls that can sometimes block Windows troubleshooters from connecting with Microsoft servers. If a third-party security app is on your PC, disable that software’s firewall component to ensure it can’t interfere with Windows troubleshooters. Then try running the troubleshooter with the firewall component disabled.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043856/7443" target="_top" id="2043856">
  <img src="//a.impactradius-go.com/display-ad/7443-2043856" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043856/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Rename the Catroot2 and SoftwareDistribution Folders

 If you’re having issues with the Windows Update troubleshooter, try applying this potential solution. Users confirm renaming the catroot2 and SoftwareDistribution folders can fix the Windows Update troubleshooter not working. Those are folders that store data for Windows updates. Rename the catroot2 and SoftwareDistribution folders as follows:

1. Launch the Windows Command Prompt app with administrative rights.
2. Input these four separate commands, pressing **Enter** after each, to stop update services:  
`net stop cryptsvc  

net stop wuauserv  

net stop bits  

net stop msiserver`
3. Next, input this command and hit **Return** to rename the SoftwareDistribution folder:  
`ren c:\Windows\SoftwareDistribution SoftwareDistribution.old`  
![The ren command for the SoftwareDistribution folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/rename-softwaredistribution-folder.jpg)
4. Enter this command for renaming the catroot2 folder and press **Return**:  
`ren c:\Windows\System32\catroot2 catroot2.old`  
![The rename catroot2 folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/rename-catroot2-folder.jpg)
5. Restart services by entering and executing these commands:

`net start cryptsvc  
  
net start wuauserv  
  
net start bits  
  
net start msiserver`

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398455/3022" target="_top" id="398455">
  <img src="//a.impactradius-go.com/display-ad/3022-398455" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398455/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Modify TEMP and TMP Environment Variables

 Troubleshooter issues can also arise when the TEMP and TMP environment variables have been changed from their default values. To address this, set the TMP and TEMP environment variables to default values as follows:

1. Open the file finder by pressing the **Windows key + S** keyboard buttons.
2. Type **advanced system settings** inside the search box.
3. Click **View advanced system settings** to bring up a System Properties window.
4. Press the **Environment Variables** button on the **Advanced** tab.  
![The Environment Variables button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/environment-variables-button.jpg)
5. Check the **TEMP** and **TMP** values in the System variables box. If they’re not set to **C:\\Windows\\Temp**, proceed with the next few steps to edit their values.  

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484945/16446" target="_top" id="1484945">
  <img src="//a.impactradius-go.com/display-ad/16446-1484945" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484945/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Environment Variables window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/environment-variables-window.jpg)

1. Double-click **TEMP** in the System variables box.
2. Erase the text in the **Variable** **value** box. Then input **%SystemRoot%\\TEMP** inside the **Variable** **value** box.  
![The Edit System Variable window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/edit-system-variable-window.jpg)
3. Click **OK** on the Edit System Variable window.
4. Repeat the previous three steps for the TMP variable.
5. Select **OK** on the Environment Variables window.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135419/19272" target="_top" id="2135419">
  <img src="//a.impactradius-go.com/display-ad/19272-2135419" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135419/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Enable Troubleshooters in Group Policy Editor

 Local Group Policy Editor includes policy options for disabling the Windows troubleshooters. If you’re a Windows 11/10 Pro or Enterprise user, it could be the case Group Policy has disabled the troubleshooters. That’s especially likely if the error message says troubleshooting is disabled. You can enable troubleshooting in Group Policy Editor like this:

1. [Open Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and double-click **Computer Configuration** in that utility.
2. Then double-click **Administrative Templates** \> **System** \> **Troubleshooting and Diagnostics** \> **Scripted Diagnostics** to view policy settings for troubleshooting.  
![The Scripted Diagnostic policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/scripted-diagnostic-policies.jpg)
3. Double-click the **Troubleshooting: Allow users to access and run Troubleshooting Wizards** policy.
4. Click **Enabled** to re-enable troubleshooters if the policy is disabled.  
![The Troubleshooting: Allow users to access and run Troubleshooting Wizards policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-allow-users-to-access-and-run-troubleshooters.jpg)
5. Press the **Apply** \> **OK** buttons.

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098702/14409" target="_top" id="2098702">
  <img src="//a.impactradius-go.com/display-ad/14409-2098702" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098702/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Repeat the previous three steps for the **Troubleshooting: Allow users to access online troubleshooting content** and **Configure Security Policy for Scripted Diagnostics** policies.

## 8\. Utilize the System Restore Tool

 System Restore is a utility that undoes system changes by rolling Windows back to earlier times. This tool might undo some changes that caused the troubleshooter error. A lot depends on whether you can select a restore point that will roll Windows back to a time when you could utilize all troubleshooters without issues.

 Check out this [how to utilize System Restore](https://www.makeuseof.com/use-system-restore-windows/) article for instructions about how you can roll back Windows with that tool. Select a restore point that will roll Windows back to a date when all troubleshooters worked on your PC. The oldest restore point available is your best bet if you’re not sure.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-system-restore-window.jpg)

 Utilizing System Restore comes with this caveat: software installed after a restoration date gets removed. This means you may need to reinstall some lost software after performing a restore. Clicking **Scan for affected programs** in System Restore shows you what software a restore point deleted.

## 9\. Factory Reset Your Windows PC

 If troubleshooters still don’t work after applying all the resolutions above, resetting Windows is the last thing you should try. That might seem drastic for fixing troubleshooters, but reinstalling Windows with a reset will likely resolve deeper system issues that have broken them. This potential resolution will wipe all the software and apps you installed.

 The best way to apply this potential resolution is to utilize the "Reset this PC" tool, as outlined in our article about [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/). Selecting **Keep my files** in that tool will save your user files. Also, keep the **Restore preinstalled apps** option set to **Yes** to retain preinstalled software.

![The Reset this PC window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/reset-this-pc.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925549/19272" target="_top" id="1925549">
  <img src="//a.impactradius-go.com/display-ad/19272-1925549" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925549/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Fix Your Windows Issues With the Troubleshooters Once More

 Although most users can probably live without Windows troubleshooters, there’s no denying their usefulness for fixing computing issues. The potential resolutions above will likely resolve most errors that prevent Windows troubleshooters from initiating their troubleshooting. Then you can utilize the troubleshooters to help you fix Windows 10 or 11 issues again.

 The full error messages and codes can vary slightly and appear after users select to run the troubleshooters. Consequently, the affected Windows troubleshooters don’t work. This is how you can fix troubleshooters not working on Windows 11/10 PCs.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-adding-visual-time-indicators-to-your-youtube-links/"><u>[New] 2024 Approved Adding Visual Time Indicators to Your YouTube Links</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-complete-insight-gopro-silver-hero4-detailed-assessment/"><u>[New] Complete Insight GoPro Silver Hero4 Detailed Assessment</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-techs-elite-selection-the-top-10-video-recorders-online/"><u>[New] Tech's Elite Selection The Top 10 Video Recorders Online</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-explore-the-best-free-youtube-video-editor-apps-for-android/"><u>2024 Approved Explore the Best Free YouTube Video Editor Apps for Android</u></a></li>
<li><a href="https://techtrends.techidaily.com/can-you-talk-to-friends-via-messenger-without-having-a-facebook-profile/"><u>Can You Talk to Friends Via Messenger Without Having a Facebook Profile?</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/exclusive-insights-top-30-hidden-windows-11-tips-uncovered-for-2024/"><u>Exclusive Insights Top 30 Hidden Windows 11 Tips Uncovered for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-users-through-privilege-related-setup-hiccups/"><u>Guiding Users Through Privilege-Related Setup Hiccups</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-google-pixel-fold-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Google Pixel Fold If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-fake-gps-location-apps-on-android-of-your-xiaomi-redmi-12-5g-drfone-by-drfone-virtual/"><u>In 2024, 10 Fake GPS Location Apps on Android Of your Xiaomi Redmi 12 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-key-elements-impacting-youtube-content-visibility/"><u>In 2024, Key Elements Impacting YouTube Content Visibility</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-printer-service-offline-errors/"><u>Resolving Windows Printer Service Offline Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-the-background-load-a-windows-guide/"><u>Taming the Background Load: A Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-effective-toolbar-navigation-with-mspcm-on-w11/"><u>The Art of Effective Toolbar Navigation with MSPCM on W11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-unresponsive-inputs-in-win11s-sleep-mode/"><u>Troubleshooting Unresponsive Inputs in Win11's Sleep Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/unveil-sd-card-windows-explorer-fix-guide/"><u>Unveil SD Card: Windows Explorer Fix Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/w11-pros-best-offers-save-and-elevate-your-spend/"><u>W11 Pro's Best Offers: Save & Elevate Your Spend</u></a></li>
<li><a href="https://windows11.techidaily.com/win11s-ingenious-techniques-for-gathering-info/"><u>Win11's Ingenious Techniques for Gathering Info</u></a></li>
</ul></div>

