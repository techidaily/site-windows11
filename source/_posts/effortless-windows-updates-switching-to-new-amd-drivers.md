---
title: "Effortless Windows Updates: Switching to New AMD Drivers"
date: 2024-07-29T04:28:43.581Z
updated: 2024-07-30T04:28:43.581Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Effortless Windows Updates: Switching to New AMD Drivers"
excerpt: "This Article Describes Effortless Windows Updates: Switching to New AMD Drivers"
keywords: Easy Windows Update,AMD Driver Switch,No Fuss Updates,Latest AMD Drivers,Streamlined System Fixes,Quick AMD Support,Hands-Off Driver Change
thumbnail: https://thmb.techidaily.com/dbe86ec4eee57de28307f7a87e5d2dc26b222d4d704a45568094d723e05d6df4.jpg
---

## Effortless Windows Updates: Switching to New AMD Drivers

 AMD Software Adrenaline Edition on Windows lets you manage your AMD graphics card, game stats, perform driver updates, and more. Sometimes, after an update, it may fail to launch with the error Windows update has replaced your AMD graphics driver.

 The full error reads Windows update may have automatically replaced your AMD graphics driver. This error is due to a conflict between the AMD Software Adrenaline Edition driver and the UWP AMD graphics driver installed by Windows.

 To fix the problem, you’ll need to stop Windows from installing AMD Radeon drivers automatically and perform a manual reinstall. Here’s how to do it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Why Does Windows Automatically Replace Your AMD Graphics Drivers?

 By default, the Windows operating system installs the[Microsoft Basic Display Adapter](https://www.makeuseof.com/microsoft-basic-display-adapter-guide/) during the initial setup. It provides display graphics capabilities so that you can set up your new computer and install the necessary drivers.

 This basic display driver lets you configure your discrete graphics with the latest drivers using AMD Software. It also acts as a backup when your discrete GPU driver faults causing[black screen issues on Windows](https://www.makeuseof.com/fix-black-screen-on-windows-10-11/) .

 However, this error occurs when Windows updates install the UWP (Universal Windows Platform) driver for your AMD Radeon GPU. Since two versions of the same driver are installed, when you try to open the AMD Software Adrenaline Edition app it will trigger an error.

 AMD has addressed this issue and provided a quick fix. To fix the error, you'll need to stop Windows from automatically installing the AMD graphics drivers. Then, reinstall the AMD graphics driver using AMD software.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Roll Back the AMD Graphics Driver

![amd radeon display adapter driver roll back](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/amd-radeon-display-adapter-driver-roll-back.jpg)

 An easy way to fix Windows replacing your AMD graphics error is to roll back the AMD graphics driver. A driver rollback removes the current driver and reinstalls the previous version saved on your computer. Fortunately, you can[roll back device drivers using the Windows Device Manager](http://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) .

 In Device Manager, look for and expand the**Display Adapters** section. Here, select the**AMD Radeon (TM) graphics** device and perform a driver rollback. Once done, restart your computer and check for any improvements. If the**Roll Back Driver** option is greyed out, you can't perform a rollback for the selected device.

 Once the error is resolved, you'll need to stop Windows from automatically downloading AMD drivers. If not, you’ll likely encounter the same error after each Windows update.

 You can[stop automatic driver updates on Windows](https://www.makeuseof.com/windows-stop-automatic-driver-updates/) using device installation settings,**Group Policy Editor** , and the**Windows Registry** . With the device installation settings for automatic driver download set to off, Windows won't download and install AMD graphics drivers automatically.

## 2\. Repair and Reinstall the AMD Software Driver

![amd radeon software installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/amd-radeon-software-installer.jpg)

 You can reinstall the AMD Software driver using the existing driver. This may fix temporary issues with the driver causing the conflict. Follow these steps to repair and reinstall the AMD graphics driver:

1. Press**Win + E** to open File Explorer and navigate to the following location:  
`C:\AMD\RadeonInstaller\RadeonInstaller\Radeon_Folder_with_verison_name`
2. Next, double-click to run the**Setup.exe** file.  
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![run amd setup exe repair graphics driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/run-amd-setup-exe-repair-graphics-driver.jpg)
3. In the**AMD Radeon Software Installer** dialog, select the driver version to install.
4. Click**Install** and wait for the driver to install.

 If you encounter an AMD error 195, temporarily[disable Windows Defender Firewall](https://www.makeuseof.com/how-to-turn-off-windows-defender/) and**Real-Time Threat Protection** and try again.

## 3\. Reinstall the AMDSoftware Graphics Driver

![amd software adrenaline edition uninstall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/amd-software-adrenaline-edition-uninstall.jpg)

 If the issue persists, try to remove and reinstall the AMD Software graphics driver. Once uninstalled, you can download the latest driver using the AMD Software.

To uninstall the AMD graphics driver:

1. Press**Win + I** to open**Settings** .
2. Open the**Apps** tab and click**Installed Apps** .
3. Next, search for**AMD Software** .  
![unisntall amd graphics driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/unisntall-adm-graphics-driver.jpg)
4. Click**Uninstall** and then**Uninstall** again to confirm the action.
5. Select**AMD Radeon Graphics** and click**Uninstall** .

 The AMD Software will start removing the driver from your computer. This process may take some time, and your monitor or display may flicker during the process. If it does, don't fret; it's just Windows getting used to the changes to your display drivers.

 Once done, click on**Finish** and restart your PC.

 When you uninstall a display driver, your secondary monitor can stop working. This will happen if your monitor's HDMI cable is directly connected to the port on your dedicated graphics unit. Your secondary display should work again as you reinstall the graphics driver.

 After the restart, you can[update your AMD Radeon graphics driver](https://www.makeuseof.com/update-amd-radeon-graphics-driver-windows-11/) using AMD Software. Install the driver and restart your PC to see if the error is resolved.

## 4\. Use a System Restore Point

 A restore point helps you recover your computer when a bad Windows update or driver installation causes the system to malfunction. You can use a restore point to undo the changes without affecting your data and files.

 Unfortunately, using a System Restore point requires you made one in the past. If you haven't made any, now's a good time to get into the habit of making them. Check out[how to make a System Restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) for more information.

To undo the recent changes using a restore point:

1. Press**Win + R** to open**Run** .
2. Type**rstrui.exe** and click**OK** .  
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![select restore point](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/select-restore-point.jpg)
3. In the**System Restore** dialog, select the**Recommended** **restore** option. If not, select the**Choose a different restore point** option**.**
4. Select a**restore point** and click**Next** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
![select restore point windows 11 finish](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/select-restore-point-windows-11-finish.jpg)
5. Read the description and click**Finish** .
6. System Restore will restart and restore your PC to the state it was in before the date of the selected restore point.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fixing the Windows Update May Have Automatically Replaced Your AMD Driver

 This error occurs if multiple versions of the same AMD Radeon graphics driver are installed on your computer. To fix the issue, perform a driver rollback for your AMD Radeon graphics in Device Manager. Once done, change the device installation setting to prevent Windows from automatically installing the OEM driver for your GPU.


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
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-unveiling-the-secrets-of-facebook-video-content-success/"><u>[New] In 2024, Unveiling the Secrets of Facebook Video Content Success</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-in-search-of-perfect-sound-top-10-podcast-microphones/"><u>[New] In Search of Perfect Sound  Top 10 Podcast Microphones</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-best-of-breed-pages-for-sparkling-3d-text/"><u>[Updated] Best of Breed Pages for Sparkling 3D Text</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-direct-obs-video-feed-for-instagram-for-2024/"><u>[Updated] Direct OBS Video Feed for Instagram for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-pioneering-teams-changing-vrs-course/"><u>[Updated] Pioneering Teams Changing VR's Course</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-understanding-fps-making-a-choice-between-30-and-60-hertz/"><u>[Updated] Understanding FPS  Making a Choice Between 30 & 60 Hertz</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-fast-footsteps-simple-recording-for-dell-pcs/"><u>2024 Approved  Fast Footsteps  Simple Recording for Dell PCs</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-realme-note-50-drfone-by-drfone-virtual-android/"><u>5 Hassle-Free Solutions to Fake Location on Find My Friends Of Realme Note 50 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/ai-driven-evolution-in-windows-software-design/"><u>AI-Driven Evolution in Windows Software Design</u></a></li>
<li><a href="https://windows11.techidaily.com/automate-peaceful-rest-for-your-windows-11-desktop/"><u>Automate Peaceful Rest for Your Windows 11 Desktop</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/crafting-the-ideal-playlist-video-integration-on-youtube-platform-for-2024/"><u>Crafting the Ideal Playlist  Video Integration on YouTube Platform for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/did-your-iphone-xs-max-passcode-change-itself-unlock-it-now-drfone-by-drfone-ios/"><u>Did Your iPhone XS Max Passcode Change Itself? Unlock It Now | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/fixes-for-stumbling-windows-discord-search-bar/"><u>Fixes for Stumbling Windows Discord Search Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/get-your-pcs-virtual-machine-game-strong-with-hyper-v/"><u>Get Your PC's Virtual Machine Game Strong with Hyper-V</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-disable-the-built-in-laptop-keyboard-in-windows/"><u>How to Disable the Built-In Laptop Keyboard in Windows</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-fix-pokemon-go-route-not-working-on-poco-x5-drfone-by-drfone-virtual-android/"><u>How to Fix Pokemon Go Route Not Working On Poco X5? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-mend-the-pairing-glitch-fixing-connection-issues-in-win-11/"><u>How to Mend the Pairing Glitch: Fixing Connection Issues in Win 11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-how-to-upload-tweets-no-retweets-on-mobile/"><u>In 2024, How to Upload Tweets - No Retweets on Mobile?</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-sleepy-tales-in-visual-format-analysis/"><u>In 2024, Sleepy Tales in Visual Format  Analysis</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-apple-iphone-6s-drfone-by-drfone-virtual-ios/"><u>In 2024, Why Your WhatsApp Location is Not Updating and How to Fix On Apple iPhone 6s | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/initiating-contact-accessing-windows-printer-administration-tools/"><u>Initiating Contact: Accessing Windows' Printer Administration Tools</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/most-efficient-techniques-for-real-time-youtube-video-recording-for-2024/"><u>Most Efficient Techniques for Real-Time YouTube Video Recording for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-boot-sector-problems-on-pc/"><u>Navigating Through Boot Sector Problems on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-windows-steam-streams-stopping-zero-rate-issues/"><u>Optimize Windows Steam Streams: Stopping Zero-Rate Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-deactivated-system-cooler-protocol-on-pcs/"><u>Overcoming Deactivated System Cooler Protocol on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-stuck-context-menus-a-quick-guide-to-solutions/"><u>Overcoming Stuck Context Menus: A Quick Guide to Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-store-error-code-0x80073cf3/"><u>Overcoming Windows Store Error Code 0X80073CF3</u></a></li>
<li><a href="https://windows11.techidaily.com/recovering-database-connections-resolving-malwarebytes-service-issues/"><u>Recovering Database Connections: Resolving Malwarebytes Service Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-code-0x0001-failures-for-nvidia-ge-in-w10w11/"><u>Rectifying Code 0X0001 Failures for Nvidia GE in W10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/redirect-to-file-explorer-using-the-onedrive-shortcut/"><u>Redirect to File Explorer Using the OneDrive Shortcut</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/reset-itunes-backup-password-of-iphone-12-mini-prevention-and-solution-by-drfone-ios/"><u>Reset iTunes Backup Password Of iPhone 12 mini Prevention & Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/sculpting-digital-art-the-most-impressive-new-additions-to-paint/"><u>Sculpting Digital Art: The Most Impressive New Additions to Paint</u></a></li>
<li><a href="https://windows11.techidaily.com/sidestep-windows-11-surveillance-measures/"><u>Sidestep Windows 11 Surveillance Measures</u></a></li>
<li><a href="https://windows11.techidaily.com/smart-task-management-microsofts-ai-copilot-for-windows-11-enhances-workflow/"><u>Smart Task Management: Microsoft's AI Copilot for Windows 11 Enhances Workflow</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-virtual-environments-ideal-for-windows-11-systems/"><u>Top 5 Virtual Environments Ideal for Windows 11 Systems</u></a></li>
<li><a href="https://some-skills.techidaily.com/understanding-vr-headsets-an-overview-for-2024/"><u>Understanding VR Headsets  An Overview for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/whats-wrong-with-windows-modern-standby/"><u>What's Wrong with Windows Modern Standby?</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-selective-deactivation-for-better-efficiency/"><u>Windows 11: Selective Deactivation for Better Efficiency</u></a></li>
</ul></div>
