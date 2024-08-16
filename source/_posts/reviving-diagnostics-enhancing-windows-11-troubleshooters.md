---
title: "Reviving Diagnostics: Enhancing Windows 11 Troubleshooters"
date: 2024-08-15T15:59:24.347Z
updated: 2024-08-16T15:59:24.347Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Reviving Diagnostics: Enhancing Windows 11 Troubleshooters"
excerpt: "This Article Describes Reviving Diagnostics: Enhancing Windows 11 Troubleshooters"
keywords: Win11 Troubleshoot Guide,Diag Revive Toolkit,Enhance OS Troubleshooting,Windows Fixes Quickly,Diagnostic Improvement,ProgWin11 Solutions,Optimized System Repair
thumbnail: https://thmb.techidaily.com/46562a4985b29bb04ac045f40f195ad5a81e8c6a78d3deb58b3600f2a5e9d7c1.jpg
---

## Reviving Diagnostics: Enhancing Windows 11 Troubleshooters

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
4. Next, select the **Start** option for the service to run.  
![The Cryptographic Services Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/cryptographic-services-window.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->
5. Click on the **Apply** and **OK** options to set your selected settings.
6. Repeat the previous steps for the Windows Update, Windows Installer, and the Background Intelligent Transfer Service.

 If those services are already running and set to an automatic startup, try restarting them. Right-click the service in the Services window and select a **Restart** option.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
## 3\. Flush the DNS Cache and Reset the Winsock Catalog

 Network issues can cause some troubleshooters for which an internet connection is more essential to malfunction. Flushing the DNS cache and resetting the Winsock catalog can address such network issues. This potential fix is especially recommended for fixing the Windows Update troubleshooter. You can flush the DNS cache and reset the Winsock catalog by executing two commands like this:

1. Open the Command Prompt app with elevated privileges. If you’re unsure how to access that app, check out this guide for [opening Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Input and execute this command for flushing the DNS cache:  
`ipconfig /flushdns`  
![The ipconfig /flushdns command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/ipconfig-flushdns-command.jpg)
3. To reset Winsock, execute this command:  
`netsh winsock reset`  
![The netsch winsock reset command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/netsch-winsock-reset-command.jpg)

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
![The rename catroot2 folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/rename-catroot2-folder.jpg)
<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
5. Check the **TEMP** and **TMP** values in the System variables box. If they’re not set to **C:\\Windows\\Temp**, proceed with the next few steps to edit their values.  
![The Environment Variables window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/environment-variables-window.jpg)

1. Double-click **TEMP** in the System variables box.
2. Erase the text in the **Variable** **value** box. Then input **%SystemRoot%\\TEMP** inside the **Variable** **value** box.  
![The Edit System Variable window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/edit-system-variable-window.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
3. Click **OK** on the Edit System Variable window.
4. Repeat the previous three steps for the TMP variable.
5. Select **OK** on the Environment Variables window.

## 7\. Enable Troubleshooters in Group Policy Editor

 Local Group Policy Editor includes policy options for disabling the Windows troubleshooters. If you’re a Windows 11/10 Pro or Enterprise user, it could be the case Group Policy has disabled the troubleshooters. That’s especially likely if the error message says troubleshooting is disabled. You can enable troubleshooting in Group Policy Editor like this:

1. [Open Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and double-click **Computer Configuration** in that utility.
2. Then double-click **Administrative Templates** \> **System** \> **Troubleshooting and Diagnostics** \> **Scripted Diagnostics** to view policy settings for troubleshooting.  
![The Scripted Diagnostic policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/scripted-diagnostic-policies.jpg)
3. Double-click the **Troubleshooting: Allow users to access and run Troubleshooting Wizards** policy.
4. Click **Enabled** to re-enable troubleshooters if the policy is disabled.  
![The Troubleshooting: Allow users to access and run Troubleshooting Wizards policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-allow-users-to-access-and-run-troubleshooters.jpg)
<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Press the **Apply** \> **OK** buttons.
6. Repeat the previous three steps for the **Troubleshooting: Allow users to access online troubleshooting content** and **Configure Security Policy for Scripted Diagnostics** policies.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 8\. Utilize the System Restore Tool

 System Restore is a utility that undoes system changes by rolling Windows back to earlier times. This tool might undo some changes that caused the troubleshooter error. A lot depends on whether you can select a restore point that will roll Windows back to a time when you could utilize all troubleshooters without issues.

 Check out this [how to utilize System Restore](https://www.makeuseof.com/use-system-restore-windows/) article for instructions about how you can roll back Windows with that tool. Select a restore point that will roll Windows back to a date when all troubleshooters worked on your PC. The oldest restore point available is your best bet if you’re not sure.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-system-restore-window.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->

 Utilizing System Restore comes with this caveat: software installed after a restoration date gets removed. This means you may need to reinstall some lost software after performing a restore. Clicking **Scan for affected programs** in System Restore shows you what software a restore point deleted.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
## 9\. Factory Reset Your Windows PC

 If troubleshooters still don’t work after applying all the resolutions above, resetting Windows is the last thing you should try. That might seem drastic for fixing troubleshooters, but reinstalling Windows with a reset will likely resolve deeper system issues that have broken them. This potential resolution will wipe all the software and apps you installed.

 The best way to apply this potential resolution is to utilize the "Reset this PC" tool, as outlined in our article about [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/). Selecting **Keep my files** in that tool will save your user files. Also, keep the **Restore preinstalled apps** option set to **Yes** to retain preinstalled software.

![The Reset this PC window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/reset-this-pc.jpg)

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-capturing-and-keeping-your-social-media-moments/"><u>[New] 2024 Approved  Capturing and Keeping Your Social Media Moments</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-instagram-visual-mastery-crop-and-edit-videos-like-pros/"><u>[New] 2024 Approved  Instagram Visual Mastery  Crop and Edit Videos Like Pros</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-scrutinizing-magix-video-composer/"><u>[New] 2024 Approved  Scrutinizing MAGIX Video Composer</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-attention-magnet-article-initiator/"><u>[New] Attention Magnet  Article Initiator</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/resh-vlog-discussion-ideas-each-day/"><u>[New] Fresh Vlog Discussion Ideas Each Day</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-a-comprehensive-guide-to-the-12-superior-vlogging-cameras/"><u>[New] In 2024, A Comprehensive Guide to the 12 Superior Vlogging Cameras</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-essential-audio-enhancement-apps-for-youtubers-videos/"><u>[Updated] In 2024, Essential Audio Enhancement Apps for YouTubers' Videos</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-innovating-with-jujutsu-kaisen-characters-on-tiktok/"><u>[Updated] Innovating with Jujutsu Kaisen Characters on TikTok</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-mastering-soundtrack-addition-to-social-media-videos-on-facebook/"><u>[Updated] Mastering Soundtrack Addition to Social Media Videos on Facebook</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-aerial-stability-made-simple-selecting-the-right-drone-gimbals/"><u>2024 Approved  Aerial Stability Made Simple  Selecting the Right Drone Gimbals</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-crafting-the-rhythm-adding-beats-and-melodies-to-your-fb-vids/"><u>2024 Approved  Crafting the Rhythm  Adding Beats and Melodies to Your FB Vids</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-precision-in-preservation-expert-techniques-for-skype-call-recordings/"><u>2024 Approved  Precision in Preservation  Expert Techniques for Skype Call Recordings</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-worlds-top-12-screensaver-apps-no-end-in-view/"><u>2024 Approved  World's Top 12 Screensaver Apps (No End in View)</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-understanding-windows-program-files-format/"><u>A Guide to Understanding Windows' Program Files Format</u></a></li>
<li><a href="https://windows11.techidaily.com/augmented-folder-actions-power-up-your-file-management/"><u>Augmented Folder Actions: Power Up Your File Management</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-command-line-capabilities-in-latest-windows-releases/"><u>Boost Command-Line Capabilities in Latest Windows Releases</u></a></li>
<li><a href="https://windows11.techidaily.com/command-prompt-magic-utilize-windows-wsl-feature/"><u>Command Prompt Magic: Utilize Windows' WSL Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/concealed-item-choices-win-10plus-menu-tactics/"><u>Concealed Item Choices: Win 10+ Menu Tactics</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-success-vs-failure-in-user-credentials-entry-on-pcs/"><u>Decoding Success vs Failure in User Credentials Entry on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/discerning-win-credentials-success-from-failure-scenarios/"><u>Discerning Win Credentials Success From Failure Scenarios</u></a></li>
<li><a href="https://windows11.techidaily.com/easily-solve-nvidiae-experience-scanner-woes-on-windows/"><u>Easily Solve Nvidia'e Experience Scanner Woes on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-secure-transfer-of-textual-data-via-edges-guardspace-win11-version/"><u>Enabling Secure Transfer of Textual Data via Edges Guardspace, Win11 Version</u></a></li>
<li><a href="https://windows11.techidaily.com/enablingdisabling-text-emphasis-in-windows-11/"><u>Enabling/Disabling Text Emphasis in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-visibility-of-missing-cameras-on-device-management-screen/"><u>Enhance Visibility of Missing Cameras on Device Management Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tuning-win11-startup-processes/"><u>Fine-Tuning Win11 Startup Processes</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-bypass-windows-defenders-exclusive-software-lockdown/"><u>How to Bypass Windows Defender's Exclusive Software Lockdown</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-restore-windows-photo-viewer-in-windows-1111/"><u>How to Restore Windows Photo Viewer in Windows 11/11</u></a></li>
<li><a href="https://windows11.techidaily.com/howtomakenotepadwindowssmoothatnight/"><u>HowToMakeNotepadWIndowsSmoothAtNight</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-7-ways-to-unlock-a-locked-motorola-moto-g13-phone-by-drfone-android/"><u>In 2024, 7 Ways to Unlock a Locked Motorola Moto G13 Phone</u></a></li>
<li><a href="https://windows11.techidaily.com/keyboard-and-mouse-failure-windows-11-sleep-troubleshoot/"><u>Keyboard & Mouse Failure: Windows 11 Sleep Troubleshoot</u></a></li>
<li><a href="https://windows11.techidaily.com/monitoring-login-trials-detecting-successfulfailed-windows-access/"><u>Monitoring Login Trials: Detecting Successful/Failed Windows Access</u></a></li>
<li><a href="https://windows11.techidaily.com/revive-vanished-steam-game-icons-immediately/"><u>Revive Vanished Steam Game Icons Immediately</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-on-retrieving-program-installation-points-in-windows/"><u>Step-by-Step on Retrieving Program Installation Points in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-roblox-abrupt-terminations-on-microsoft-operating-systems/"><u>Tackling Roblox Abrupt Terminations on Microsoft Operating Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/time-to-get-back-on-track-recovering-windows-time-service/"><u>Time to Get Back on Track: Recovering Windows Time Service</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-invalid-temp-paths-on-w11-systems/"><u>Troubleshooting Invalid Temp Paths on W11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-code-three-ways-to-access-game-folders/"><u>Unlock the Code: Three Ways to Access Game Folders</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/video-anonymity-tips-for-blurring-private-data-for-2024/"><u>Video Anonymity  Tips for Blurring Private Data for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-audio-mastery-configuring-custom-volume-hotkeys/"><u>Win11 Audio Mastery: Configuring Custom Volume Hotkeys</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-graphics-troubleshoot-and-restart-for-clear-images/"><u>Windows 11 Graphics: Troubleshoot & Restart for Clear Images</u></a></li>
</ul></div>
