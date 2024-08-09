---
title: Sustaining Operational Diagnostics in Modern Windows
date: 2024-08-08T06:13:30.636Z
updated: 2024-08-09T06:13:30.636Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Sustaining Operational Diagnostics in Modern Windows
excerpt: This Article Describes Sustaining Operational Diagnostics in Modern Windows
keywords: WinDiag Sustainability,ModWinOpTrends,ProgWndTechniques,OpsInnovationWindows,DiagProdWinStrat,ModernWinOpsTech,EfficientWinDiag
thumbnail: https://thmb.techidaily.com/bed92abb4b13bfb35e12a54bfe3958abc331bc9941bc7a8515fe1dd62e1cd32c.jpg
---

## Sustaining Operational Diagnostics in Modern Windows

 Users often utilize the pre-installed Windows 11/10 troubleshooters available in Settings to fix update, sound, internet, microphone, video playback, Bluetooth, and UWP app issues. However, sometimes those troubleshooters display messages in their windows that say, “An error occurred while troubleshooting.” Or the message might say, “An error occurred while loading the troubleshooter.”

 The full error messages and codes can vary slightly and appear after users select to run the troubleshooters. Consequently, the affected Windows troubleshooters don’t work. This is how you can fix troubleshooters not working on Windows 11/10 PCs.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## 1\. Scan and Repair System Files

 Some users have said the system file and image repair tools helped them fix Windows 11/10 troubleshooting tools not working. System File Checker is the command-line tool for repairing system file corruptions. Deployment Image Servicing and Management is a utility you can run to address issues with the Windows image. Try running both those tools in the Command Prompt, as covered within this [guide for repairing corrupted Windows files](https://www.makeuseof.com/system-file-checker-sfc-windows/).

<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/sfc-scannow-command4.jpg)

## 2\. Enable or Restart Required Services

 Windows troubleshooters can stop working because required services are disabled or not running. Enabling and starting services like Cryptographic Services, Windows Update, BITS, and Windows Installer is a potential resolution for fixing troubleshooters users confirm to work. Try starting those required services like this:

1. Bring up the service management app with a method in this [guide to opening Services](https://www.makeuseof.com/windows-11-open-services-app/).
2. Double-click **Cryptographic Services** to bring up a settings window.  
<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/cryptographic-services.jpg)
3. Click on the **Startup type** drop-down menu and choose the **Automatic** setting if a different option is selected.
4. Next, select the **Start** option for the service to run.  
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Disable Third-Party Security Software and Firewalls

 Many security software packages incorporate firewalls that can sometimes block Windows troubleshooters from connecting with Microsoft servers. If a third-party security app is on your PC, disable that software’s firewall component to ensure it can’t interfere with Windows troubleshooters. Then try running the troubleshooter with the firewall component disabled.

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
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The rename catroot2 folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/rename-catroot2-folder.jpg)
5. Restart services by entering and executing these commands:

`net start cryptsvc  
  
net start wuauserv  
  
net start bits  
  
net start msiserver`

## 6\. Modify TEMP and TMP Environment Variables

 Troubleshooter issues can also arise when the TEMP and TMP environment variables have been changed from their default values. To address this, set the TMP and TEMP environment variables to default values as follows:

1. Open the file finder by pressing the **Windows key + S** keyboard buttons.
2. Type **advanced system settings** inside the search box.
3. Click **View advanced system settings** to bring up a System Properties window.
4. Press the **Environment Variables** button on the **Advanced** tab.  
![The Environment Variables button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/environment-variables-button.jpg)
5. Check the **TEMP** and **TMP** values in the System variables box. If they’re not set to **C:\\Windows\\Temp**, proceed with the next few steps to edit their values.  
![The Environment Variables window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/environment-variables-window.jpg)

1. Double-click **TEMP** in the System variables box.
2. Erase the text in the **Variable** **value** box. Then input **%SystemRoot%\\TEMP** inside the **Variable** **value** box.  
![The Edit System Variable window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/edit-system-variable-window.jpg)
3. Click **OK** on the Edit System Variable window.
4. Repeat the previous three steps for the TMP variable.
5. Select **OK** on the Environment Variables window.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Enable Troubleshooters in Group Policy Editor

 Local Group Policy Editor includes policy options for disabling the Windows troubleshooters. If you’re a Windows 11/10 Pro or Enterprise user, it could be the case Group Policy has disabled the troubleshooters. That’s especially likely if the error message says troubleshooting is disabled. You can enable troubleshooting in Group Policy Editor like this:

1. [Open Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and double-click **Computer Configuration** in that utility.
2. Then double-click **Administrative Templates** \> **System** \> **Troubleshooting and Diagnostics** \> **Scripted Diagnostics** to view policy settings for troubleshooting.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Scripted Diagnostic policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/scripted-diagnostic-policies.jpg)
3. Double-click the **Troubleshooting: Allow users to access and run Troubleshooting Wizards** policy.
4. Click **Enabled** to re-enable troubleshooters if the policy is disabled.  
![The Troubleshooting: Allow users to access and run Troubleshooting Wizards policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-allow-users-to-access-and-run-troubleshooters.jpg)
5. Press the **Apply** \> **OK** buttons.
6. Repeat the previous three steps for the **Troubleshooting: Allow users to access online troubleshooting content** and **Configure Security Policy for Scripted Diagnostics** policies.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 8\. Utilize the System Restore Tool

 System Restore is a utility that undoes system changes by rolling Windows back to earlier times. This tool might undo some changes that caused the troubleshooter error. A lot depends on whether you can select a restore point that will roll Windows back to a time when you could utilize all troubleshooters without issues.

 Check out this [how to utilize System Restore](https://www.makeuseof.com/use-system-restore-windows/) article for instructions about how you can roll back Windows with that tool. Select a restore point that will roll Windows back to a date when all troubleshooters worked on your PC. The oldest restore point available is your best bet if you’re not sure.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-system-restore-window.jpg)

 Utilizing System Restore comes with this caveat: software installed after a restoration date gets removed. This means you may need to reinstall some lost software after performing a restore. Clicking **Scan for affected programs** in System Restore shows you what software a restore point deleted.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
## 9\. Factory Reset Your Windows PC

 If troubleshooters still don’t work after applying all the resolutions above, resetting Windows is the last thing you should try. That might seem drastic for fixing troubleshooters, but reinstalling Windows with a reset will likely resolve deeper system issues that have broken them. This potential resolution will wipe all the software and apps you installed.

 The best way to apply this potential resolution is to utilize the "Reset this PC" tool, as outlined in our article about [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/). Selecting **Keep my files** in that tool will save your user files. Also, keep the **Restore preinstalled apps** option set to **Yes** to retain preinstalled software.

![The Reset this PC window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/reset-this-pc.jpg)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
## Fix Your Windows Issues With the Troubleshooters Once More

 Although most users can probably live without Windows troubleshooters, there’s no denying their usefulness for fixing computing issues. The potential resolutions above will likely resolve most errors that prevent Windows troubleshooters from initiating their troubleshooting. Then you can utilize the troubleshooters to help you fix Windows 10 or 11 issues again.

 The full error messages and codes can vary slightly and appear after users select to run the troubleshooters. Consequently, the affected Windows troubleshooters don’t work. This is how you can fix troubleshooters not working on Windows 11/10 PCs.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-files.techidaily.com/new-cutting-edge-optics-top-recommendations-for-best-4k-cinematography/"><u>[New] Cutting-Edge Optics  Top Recommendations for Best 4K Cinematography</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-scheduling-podcast-drops-with-peak-engagement-times/"><u>[New] Scheduling Podcast Drops with Peak Engagement Times</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-top-10-firefox-screen-recorders-and-add-ons-for-2024/"><u>[New] Top 10 Firefox Screen Recorders and Add-Ons for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-break-it-down-free-techniques-to-go-frame-by-frame-on-youtube-for-2024/"><u>[Updated] Break It Down  Free Techniques to Go Frame by Frame on YouTube for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-cultivating-a-distinctive-presence-in-the-marketplace-for-2024/"><u>[Updated] Cultivating a Distinctive Presence in the Marketplace for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-perfect-recording-companion-10-best-on-spotify-platforms-for-2024/"><u>[Updated] Perfect Recording Companion  10 Best on Spotify Platforms for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-enhancing-productivity-a-guide-to-ez-grabbers-use/"><u>2024 Approved  Enhancing Productivity  A Guide to EZ Grabber's Use</u></a></li>
<li><a href="https://windows11.techidaily.com/3-ways-to-check-if-windows-11-is-activated/"><u>3 Ways to Check If Windows 11 Is Activated</u></a></li>
<li><a href="https://windows11.techidaily.com/4-ways-to-check-the-hardware-ids-of-your-devices-on-windows/"><u>4 Ways to Check the Hardware IDs of Your Devices on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/7-reasons-to-choose-windows-10-over-windows-11/"><u>7 Reasons to Choose Windows 10 Over Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-overview-using-bluescreenview/"><u>A Comprehensive Overview: Using BlueScreenView</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-overhauling-the-settings-app-in-win11/"><u>A Guide to Overhauling the Settings App in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/a-step-by-step-approach-for-cleaning-up-ms-audit-records/"><u>A Step-by-Step Approach for Cleaning Up MS Audit Records</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-telnet-on-windows-3-key-methods/"><u>Activating Telnet on Windows: 3 Key Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-non-operational-state-of-ccleaner-on-win1011-systems/"><u>Addressing Non-Operational State of CCleaner on Win10/11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-unavailable-display-settings-in-nvidia-software/"><u>Addressing Unavailable Display Settings in Nvidia Software</u></a></li>
<li><a href="https://windows11.techidaily.com/alter-ip-settings-with-confidence-windows-11/"><u>Alter IP Settings with Confidence (Windows 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/analyzing-space-efficiency-of-windows-software/"><u>Analyzing Space Efficiency of Windows Software</u></a></li>
<li><a href="https://windows11.techidaily.com/androidios-to-windows-pc-microphone-conversion-guide/"><u>Android/iOS to Windows PC Microphone Conversion Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-decreased-size-of-your-windows-11-icons/"><u>Avoid Decreased Size of Your Windows 11 Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/bootstrapping-your-windows-version-patch-edition/"><u>Bootstrapping Your Windows Version: Patch Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-the-workflow-of-windows-11s-recovery-features/"><u>Breaking Down the Workflow of Windows 11'S Recovery Features</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-back-sound-on-systems-running-low-volume-errors/"><u>Bring Back Sound on Systems Running Low Volume Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-the-blockade-fixing-obs-studios-server-error-window/"><u>Bypassing the Blockade: Fixing OBS Studio's Server Error Window</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-steam-cloud-errors/"><u>Clearing Up Steam Cloud Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/concealing-windows-11s-taskbar-search-function/"><u>Concealing Windows 11'S Taskbar Search Function</u></a></li>
<li><a href="https://windows11.techidaily.com/create-your-own-windows-speech-recognition-app-with-autohotkey-and-whisper/"><u>Create Your Own Window's Speech Recognition App with AutoHotkey and Whisper</u></a></li>
<li><a href="https://windows11.techidaily.com/cut-costs-not-compromise-top-5-free-media-software/"><u>Cut Costs, Not Compromise: Top 5 Free Media Software</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-edge-windows-11-shortcut-personalization-techniques/"><u>Cutting-Edge Windows 11 Shortcut Personalization Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/detailed-steps-to-fully-remove-wsl/"><u>Detailed Steps to Fully Remove WSL</u></a></li>
<li><a href="https://windows11.techidaily.com/ditch-default-home-port-on-w11-settings-interface/"><u>Ditch Default Home Port on W11 Settings Interface</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/elevate-your-driving-pleasure-with-essential-sj4000-gear-for-2024/"><u>Elevate Your Driving Pleasure with Essential SJ4000 Gear for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-contacts-from-honor-play-40c-by-fonelab-android-recover-contacts/"><u>How to recover deleted contacts from Honor Play 40C.</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-exploring-the-differences-between-srgb-and-rgb/"><u>In 2024, Exploring the Differences Between Srgb & Rgb</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/in-depth-lenovo-yoga-a940-evaluation/"><u>In-Depth Lenovo Yoga A940 Evaluation</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-s-hottest-vlog-editor-apps-for-ios-and-android-devices/"><u>New 2024 Approved S Hottest Vlog Editor Apps for iOS and Android Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-netflix-freeze-in-windows-software/"><u>Overcoming Netflix Freeze in Windows Software</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/pathways-to-acquiring-facebooks-distinguished-verification-for-2024/"><u>Pathways to Acquiring Facebook's Distinguished Verification for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/silent-capture-effective-strategies-to-remove-noise-from-iphone-videos-for-2024/"><u>Silent Capture Effective Strategies to Remove Noise From iPhone Videos for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/top-7-skype-hacker-to-hack-any-skype-account-on-your-nokia-c210-drfone-by-drfone-virtual-android/"><u>Top 7 Skype Hacker to Hack Any Skype Account On your Nokia C210 | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>