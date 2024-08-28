---
title: Unveiling the Cause of WinMedia Error
date: 2024-08-27T16:06:47.579Z
updated: 2024-08-28T16:06:47.579Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unveiling the Cause of WinMedia Error
excerpt: This Article Describes Unveiling the Cause of WinMedia Error
keywords: WinMedia Error Fix,Resolve WinMedia Issue,Stop WinMedia Error,WinMedia Glitch Remedy,Address WinMedia Faults,Troubleshoot WinMedia Problem,Overcome WinMedia Failure
thumbnail: https://thmb.techidaily.com/65fba9a952c6564fd879ce858daef732be8f2531c9874f65aafa43e482841322.jpg
---

## Unveiling the Cause of WinMedia Error

 Windows Media Player is old software, but many users still utilize it for playing music and video. However, some WMP users have reported a “server execution failed” error message pops up when they try to play media files in Windows Media Player. Consequently, users can’t listen to music or watch videos in Windows Media Player.

 Windows Media Player isn’t much good when it doesn’t play music or video. There are plenty of alternative media players, but you don’t have to ditch WMP because of the “server execution failed” error. This is how you can fix the “server execution failed” error.

## 1\. Try Restarting the Windows Media Player Process

 Some WMP users have confirmed that ending the Windows Media Player process in Task Manager can fix the “Server execution failed” error. That’s a very simple potential resolution that amounts to little more than restarting the software, albeit via Task Manager. You can end the Windows Media Player process in Task Manager like this:

1. Open Task Manager by simultaneously pressing the **Ctrl** \+ **Shift** \+ **Esc** key combination for launching that utility.
2. Click **Processes** to view that tab if it doesn’t open with Task Manager.
3. Select the **Windows Media Player** process in Task Manager.  
![The Processes tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-process-tab.jpg)
4. Press the **End task** button to terminate the selected WMP process.
5. Then exit Task Manager and open Windows Media Player to see if the error persists.

## 2\. Run the Video Playback Troubleshooter

 Windows 11 and 10 both include a Video Playback troubleshooter that might be useful for resolving the “Server execution failed” error. That’s a troubleshooter for resolving video playback issues, and some users have said it helped them fix this issue. These are the steps for running the Video Playback troubleshooting tool:

1. First, [bring up Settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/) the quick way by holding the **Windows** logo key and pressing **I**.
2. Then select **System** and the **Troubleshoot** navigation option included within that tab.
3. Click **Other trouble-shooters** to proceed to a list of troubleshooting utilities.
4. Open the Video Playback troubleshooter by clicking its **Run** option.  
![The Run button for the Video Playback troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-video-playback-troubleshooter.jpg)
5. Select **I want to continue** **with this troubleshooter** in Video Playback.  
![The Video Playback troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/video-playback-troubleshooter.jpg)
6. Apply any possible fixes the Video Playback troubleshooter offers.

 To utilize the same Video Playback troubleshooter in Windows 10, select the Update & Security settings category. Then you can reach the Video Playback repair utility by selecting **Troubleshoo**t > **Additional troubleshooters**. Select Video Playback and click **Run the troubleshooter**.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Register DLL Files

 Registering the jscript and vbscript DLL files is a widely confirmed fix for the “Server execution failed” error. You can register those files by executing a couple of simple regsvr commands like this:

1. [Open Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/#:~:text=In%20the%20Run%20dialog%20box,Command%20Prompt%20with%20administrative%20privileges.) to utilize that app with elevated privileges.
2. Then input this regsvr command and hit **Enter**: regsvr32 jscript.dll  
![The regsvr32 jscript.dll](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-regsvr32-command.jpg)
3. Click **OK** on RegSvr32 confirmation box.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Next, execute this command to register the VBScript file: regsvr32 vbscript.dll  
![The regsvr32 vbscript.dll command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-regsver32-vbscript-command.jpg)
5. Then select **OK** again.
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
6. Go to your Start menu and select **Restart** from there.

## 4\. Disable the Windows Media Player Network Sharing Service

 Windows Media Player Network Sharing is a service required for sharing WMP libraries via the UPnP protocol. That’s not a service needed for playing media files on one PC, and some WMP users have fixed the “Server execution failed” error by disabling that service. This is how you can disable that service:

1. Click on the taskbar’s magnifying glass icon or search box.
2. Enter a **services** keyword to find the app that matches that search phrase.
3. Run Services by clicking that app within your search results.
4. Double-click **Windows Media Player Network Sharing** to access that service’s property settings.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-services-window2.jpg)
5. Select the **Disabled** option on the **Startup** menu.  
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
![The Disabled option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-disabled-option.jpg)
6. Click **Stop** just below the **Startup type** menu.
<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Select **Apply** \> **OK** to save settings and exit the Windows Media Player Network Sharing Service Properties window.

## 5\. Apply Full Access to Your Local User Folder

 Another possibility is that Windows Media Player can’t access media files in your user folder because of permission changes. Re-establishing full access to your local user folder will resolve such an issue. These are the steps for applying full access to a user folder:

1. [Open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and go to the following folder path:  
`C:\Users`
2. Right-click your user folder that includes media files and select **Properties**.  
![The Properties context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/properties-option.jpg)
3. Select **Security** on the properties window.
4. Click **Advanced** to bring up more security settings.
5. Next, click the **Change** option for the owner.  
![The Advanced Security Settings for Users window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/advanced-security-window.jpg)

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
1. Click **Advanced** \> **Find now** on the Select User or Group window.
2. Then choose your user account from there and click **OK** twice.  
![The Select User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/select-user-or-group.jpg)
3. Press **Add** on the Advanced Security Settings window.
4. Click **Select a Principal** to bring up a user group selection window.
5. Select your user account again, as covered in steps six and seven.
6. Click the **Full control** checkbox to select that basic permission setting.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-full-control-option.jpg)
7. Select **OK** on the Permissions Entry window and others open.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Disable Third-Party Startup Items

 Disabling all third-party startup items (apps and services) is called clean booting. The purpose of clean booting is to prevent software conflicts by stopping third-party background programs and services from starting automatically. This troubleshooting method is recommended to check if a third-party app or service conflict with Windows Media Player is causing the “Server execution failed” error on your PC.

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/services-tab-in-msconfig.jpg)

 Our guide to [clean-booting Windows](https://www.makeuseof.com/clean-boot-windows-11/) tells you how to apply this potential fix by disabling third-party apps and services with Task Manager and MSConfig. When you’ve done that, you’ll need to restart your PC open for a clean boot to take effect. Then open Windows Media Player and try playing some media files again.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Reinstall Windows Media Player

 Reinstalling Windows Media Player is a last resort potential resolution to try if none of the above works for you. However, you can’t reinstall WMP like regular software by uninstalling with Programs and Features and downloading a setup file. Instead, you’ll need to disable and re-enable WMP via Windows Features as follows:

1. Bring up the Windows uninstaller tool with a method within this article about [how to open Programs and Features](https://www.makeuseof.com/windows-open-programs-and-features-tool/).
2. Then click **Turn Windows features on or off** to bring up a utility for enabling/disabling features.  
![Programs and Features Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/programs-and-features-window.jpg)
3. Double-click Media Features to extend it.
4. Deselect the **Windows Media Player** checkbox and select **Yes**.  
![The Windows Media Player checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-windows-media-player-checkbox.jpg)
5. Click **OK** to disable Windows Media Player.
6. Restart Windows after disabling WMP.
7. Then reopen the Windows Features window.
8. Select the **Windows Media Player** checkbox.
9. Click **OK** to reinstall the software.

## Enjoy Your Music and Videos in Windows Media Player

 Many WMP users have fixed the “Server execution failed” error with the potential solutions outlined in this guide. So, don’t ditch Windows Media Player until you’ve at least tried applying most of those potential fixes. One will probably get the “Server execution failed” WMP error fixed on your Windows PC. Then you can enjoy all the music and videos in your Windows Media Player playlists again.

 Nevertheless, there are still plenty of freely available alternatives to Windows Media Player you can always consider. Software like VLC, 5KPlayer, and KMPlayer are among the best freeware media players for Windows.

 Windows Media Player isn’t much good when it doesn’t play music or video. There are plenty of alternative media players, but you don’t have to ditch WMP because of the “server execution failed” error. This is how you can fix the “server execution failed” error.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-the-how-to-manual-for-time-stamped-videos-on-youtubes/"><u>[New] 2024 Approved  The How-To Manual for Time-Stamped Videos on YouTubes</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-radiance-studios-review-pinnacle-suite-deep-dive-into-studio-25-2023/"><u>[New] Radiance Studios Review  Pinnacle Suite Deep Dive Into Studio 25, 2023</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-airborne-broadcasting-how-to-stream-with-dji-drones-for-2024/"><u>[Updated] Airborne Broadcasting  How to Stream with DJI Drones for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-dive-into-peace-with-these-soothing-games/"><u>2024 Approved  Dive Into Peace with These Soothing Games</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/discover-the-premier-collection-of-6-super-mario-rpgs-available-for-pc-players/"><u>Discover the Premier Collection of 6 Super Mario RPGs Available for PC Players</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-editing-at-hand-with-powertoys-tools/"><u>Expert Editing at Hand with PowerToys Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-non-initialized-disks-a-windows-guide/"><u>Fixing Non-Initialized Disks: A Windows Guide</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-oppo-reno-11f-5g-find-my-friends-no-location-found-drfone-by-drfone-virtual-android/"><u>How to Fix Oppo Reno 11F 5G Find My Friends No Location Found? | Dr.fone</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-fix-starcraft-ii-brood-war-non-launch-problems/"><u>How to Fix Starcraft II: Brood War Non-Launch Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-this-app-package-is-not-supported-for-installation-on-windows/"><u>How to Fix This App Package Is Not Supported for Installation on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-frozen-taskbar-and-menu/"><u>How to Reactivate Frozen Taskbar & Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-refresh-the-group-policy-settings-on-windows/"><u>How to Refresh the Group Policy Settings on Windows</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-pursuit-of-perfection-zooming-into-high-quality-video/"><u>In 2024, Pursuit of Perfection  Zooming Into High-Quality Video</u></a></li>
<li><a href="https://windows11.techidaily.com/integrate-bandwidth-status-into-windows-shell/"><u>Integrate Bandwidth Status Into Windows Shell</u></a></li>
<li><a href="https://fake-location.techidaily.com/is-pgsharp-legal-when-you-are-playing-pokemon-on-xiaomi-redmi-note-12-5g-drfone-by-drfone-virtual-android/"><u>Is pgsharp legal when you are playing pokemon On Xiaomi Redmi Note 12 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-unpredictable-printer-selections/"><u>Remedying Unpredictable Printer Selections</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-missed-game-content-with-steam-on-win11/"><u>Resolving Missed Game Content with Steam on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-unlisted-bluetooth-on-pc/"><u>Resolving Unlisted Bluetooth on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-11-invalid-computer-identifier/"><u>Resolving Windows 11: Invalid Computer Identifier</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-harmony-fixing-sticky-notebooks-in-w11/"><u>Restoring Harmony: Fixing Sticky Notebooks in W11</u></a></li>
<li><a href="https://fox-that.techidaily.com/step-by-step-fixes-for-wrong-person-detection-by-apples-image-app/"><u>Step-by-Step Fixes for Wrong Person Detection by Apple's Image App</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-black-screen-phenomenon-post-boot/"><u>Tackling Black Screen Phenomenon Post-Boot</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-to-reinforce-stability-and-persistence-of-nvidia-cp-saves/"><u>Tactics to Reinforce Stability and Persistence of Nvidia CP Saves</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-rectify-the-windows-activation-problem-0x803f700f/"><u>Techniques to Rectify the Windows Activation Problem: 0X803F700f</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-pc-failure-at-windows-11-upgrade/"><u>Troubleshooting PC Failure at Windows 11 Upgrade</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-hidden-functionality-essential-fixes-for-missing-windows-features/"><u>Unlock Hidden Functionality: Essential Fixes for Missing Windows Features</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-microsoft-services-by-linking-windows-product-key/"><u>Unlocking Microsoft Services by Linking Windows Product Key</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11-with-a-retired-windows-7-key/"><u>Unlocking Windows 11 with a Retired Windows 7 Key</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-file-system-errors-on-windows/"><u>Unraveling File System Errors on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-power-of-windows-nettools/"><u>Unveiling the Power of Windows NetTools</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>