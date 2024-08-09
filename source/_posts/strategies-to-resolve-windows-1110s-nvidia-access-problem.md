---
title: Strategies to Resolve Windows 11/10'S NVidia Access Problem
date: 2024-08-08T06:02:30.306Z
updated: 2024-08-09T06:02:30.306Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategies to Resolve Windows 11/10'S NVidia Access Problem
excerpt: This Article Describes Strategies to Resolve Windows 11/10'S NVidia Access Problem
keywords: Fix NVIDIA in Win11/10,Solve Win11 Graphics Issue,Tackle Win10 NVidia Errors,Remedy Win10/11 GPU Glitches,Windows NVidia Resolution,Overcome Win11/10 NVidia Problems,Address Win10 NVidia Compatibility
thumbnail: https://thmb.techidaily.com/5102f68d4f6f5865eb613c39e1e5be805ea96bcf031e721bf44a46da711c7234.jpg
---

## Strategies to Resolve Windows 11/10'S NVidia Access Problem

 The NVIDIA Control Panel is an app included on PCs with NVIDIA GPUs with which users can change graphical settings. However, some users can’t change NVIDIA Control Panel options because of an “Access denied” error. The message of that error says, “Failed to apply selected settings to your system.”

 The “Access denied” error is mostly reported to arise for 3D settings. As a result, NVIDIA Control Panel doesn’t apply (save) the settings users select. This is how you can resolve NVIDIA Control Panel’s “Access denied” error within Windows 11/10.

## 1\. Run the NVIDIA Control Panel as an Administrator

 Firstly, try running the NVIDIA Control Panel with elevated admin permissions, which has worked for some users. To do that, press the**Windows** logo +**S** keyboard buttons and input NVIDIA Control Panel. Right-click NVIDIA Control Panel and select**Run as administrator** .

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-as-administrator-option2.jpg)

 Should this potential fix work, then it would be better to set the NVIDIA Control Panel to always run with administrative rights. However, that UWP app is located within a protected folder. You’ll need to[take ownership of the WindowsApps folder](https://www.makeuseof.com/windows-10-11-own-folder/) to set permanent admin rights for the NVIDIA Control Panel.

 If you take ownership of the WindowsApps folder, open the NVIDIACorp subfolder to reach the NVIDIA Control Panel file. Then you’ll need to set the nvcplui.exe file to run with admin rights. Follow the steps in this how to[set an app to always run as an administrator guide](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) to set elevated permissions for the nvcplui.exe file. The path for the NVIDIA Control Panel folder is:

`C:\Program Files\WindowsApps\NVIDIACorp.NVIDIAControlPanel_8.1.964.0_x64__56jybvy8sckqj`

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
## 2\. Select the Repair and Reset Options for the NVIDIA Control Panel

 The NVIDIA Control Panel app has**Repair** and**Reset** troubleshooting options you can select in Settings. Both options can be useful for fixing apps when they’re not working right. So, try selecting the**Repair** option first and then**Reset** to clear the app’s data if repairing isn’t enough. Check out this[article about resetting apps in Windows](https://www.makeuseof.com/windows-reset-app/) for details about how to apply this potential fix.

![The Repair and Reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-reset-options.jpg)

## 3\. Start or Restart the NVIDIA Display Container Service

 The NVIDIA Display Container is an important GPU service that runs numerous other NVIDIA background tasks. Make sure that service is running or restart it if it is. You can start or restart NVIDIA Display Container like this:

1. Click the**Type here to search** button or the Search box on the taskbar to access the Windows file finder tool.
2. Input**services** inside the file search utility.
3. Select**Services** to launch that app.
4. Then double-click**NVIDIA Display Container** to view the settings for that service.  
![The Services app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-services-app.jpg)  
 Screenshot captured by Jack Slater - No attribution required
5. Click on the**Startup type** menu and select**Automatic** from there.
6. Next, select**Start** if the NVIDIA Display Container service is stopped. Or select**Stop** \>**Start** to restart that service.  
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
![The NVIDIA Display Container service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/nvidia-display-container-service.jpg)
7. Click**Apply** to set the NVIDIA Display Container service’s settings.
8. Close the NVIDIA Display Container Properties window by clicking**OK** .

## 4\. Update Your NVIDIA Graphics Card Driver

 The most widely confirmed fix for the “Access denied” error is to manually update the NVIDIA graphics driver. Thus, this is often an issue caused by outdated or faulty NVIDIA drivers. This[guide to updating NVIDIA drivers](https://www.makeuseof.com/how-update-nvidia-graphics-card-drivers-windows/) provides further details about how to apply this potential solution by manually downloading the latest GPU driver available from the NVIDIA site.

 When you’ve downloaded the latest NVIDIA driver package for your GPU, bring up the directory that includes its setup file. Double-click the NVIDIA driver package file to view its setup wizard and select the**Custom** option. Then select the**Perform a clean installation** checkbox and click**Next** to install.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Perform a clean installation checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/perform-a-clean-installation.jpg)

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
## 5\. Roll Back the NVIDIA Driver

 If the “Access denied” error arises after installing a new NVIDIA driver, rolling back that driver to a previous one could be a viable potential solution. You’ll only be able to do that if the previous NVIDIA GPU driver file is still available. Our[article about rolling back drivers](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) includes guidelines for how to apply this potential fix.

 If the**Roll Back** option is grayed out, you might still be able to roll back to a previous NVIDIA graphics driver with the System Restore utility. Rolling Windows back to a restoration point restores drivers installed before the selected date. However, that will only work if your PC has a restore point that predates the driver update.

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
![The Roll Back Driver button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/roll-back-driver-option.jpg)

 This[post about creating and utilizing restore points](https://www.makeuseof.com/windows-11-create-restore-point/) tells you how to roll back Windows. Select a restore point that will restore the previous NVIDIA graphics driver. You can click**Scan for affected** programs in System Restore to check if a chosen restoration point will restore an NVIDIA graphics driver.

## 6\. Restore a Previous Version of the DRS Folder

 Some NVIDIA Control Panel users have said they fixed the “Access denied” error by restoring a DRS folder version backup. Note that you’ll only be able to apply this potential fix if you’ve got File History enabled or restore points saved on your PC. This is how you can restore a previous DRS folder version in Windows 11/10:

1. First, bring up File Explorer by clicking the taskbar button with the folder library icon.
2. Then click the**View** button to select a**Show** option.
3. Select the**Hidden Items** option.  
![The Hidden items checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/hidden-items-option.jpg)
4. Clear Explorer’s address bar to input the following path:  
`C:\ProgramData\NVIDIA Corporation`
5. Then right-click the DRS folder and select**Properties** .
6. Click the**Previous Versions** tab.  
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Previous Versions tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/previous-version-tab.jpg)
7. Select the most recent folder version shown in that tab.
8. Click the**Restore** button.

 To select the same**Hidden Items** option in Windows 10, you’ll need to open the**View** tab in Explorer. Then select the checkbox labeled**Hidden Items** on that tab.

## 7\. Turn Off the Game Bar

 It’s also recommended to turn off the Game Bar in case that’s causing any issues with the NVIDIA Control Panel. This potential resolution applies more to Windows 10 since Windows 11’s Settings app doesn’t include a specific option for disabling the Game Bar. You can turn off the Game Bar in Windows 10 like this:

1. Open Settings by clicking the cog icon on the Start menu.
2. Click the**Gaming** category.
3. Then turn off the**Enable Xbox Game Bar** option.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->
![The Xbox Game Bar setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-xbox-game-bar-option.jpg)

## Change Your Settings in the NVIDIA Control Panel Again

 Many users have resolved NVIDIA Control Panel’s “Access denied” error with the potential fixes covered above. So, the probability one of them will also fix that issue on your PC is good. With that issue sorted, you can change all settings in the NVIDIA Control Panel as required.

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
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-how-to-use-snap-camera-for-microsoft-teams/"><u>[New] In 2024, How to Use Snap Camera for Microsoft Teams</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-viral-velocity-15-dynamic-steps-to-skyrocketing-follower-count-and-fame-on-instagram/"><u>[New] Viral Velocity  15 Dynamic Steps to Skyrocketing Follower Count and Fame on Instagram</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-mastering-sound-windows-10-recorder-tips/"><u>[Updated] Mastering Sound  Windows 10 Recorder Tips</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/3-ways-to-unlock-iphone-14-without-passcode-or-face-id-drfone-by-drfone-ios/"><u>3 Ways to Unlock iPhone 14 without Passcode or Face ID | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/5-key-strategies-to-boost-your-writing-with-chatgpt-a-content-creators-guide/"><u>5 Key Strategies to Boost Your Writing with ChatGPT: A Content Creator's Guide</u></a></li>
<li><a href="https://vp-tips.techidaily.com/beyond-reality-the-future-of-virtual-experiences-for-2024/"><u>Beyond Reality  The Future of Virtual Experiences for 2024</u></a></li>
<li><a href="https://facebook.techidaily.com/boosting-protection-in-mail-applications-implementing-robust-2fa-systems/"><u>Boosting Protection in Mail Applications - Implementing Robust 2FA Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/downloading-and-instaling-windows-11-arm-a-streamlined-process/"><u>Downloading & Instaling Windows 11 ARM - A Streamlined Process</u></a></li>
<li><a href="https://windows11.techidaily.com/downloading-woes-fixing-file-transfer-issues-in-windows-11/"><u>Downloading Woes: Fixing File Transfer Issues in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/easily-enlarge-or-decrease-taskbar-in-win11/"><u>Easily Enlarge or Decrease Taskbar in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-techniques-for-deactivating-win11s-hyper-v/"><u>Easy Techniques for Deactivating Win11's Hyper-V</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-desktop-organization-fixing-gmails-taskbar-spot/"><u>Effective Desktop Organization: Fixing Gmail's Taskbar Spot</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-hardware-diagnosis-tools/"><u>Effective Hardware Diagnosis Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-methods-to-restore-functioning-asana-on-windows-machines/"><u>Effective Methods to Restore Functioning Asana on Windows Machines</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-pc-mainteninas-auto-update-switch-latest-amd-video/"><u>Effortless PC Mainteninas: Auto Update, Switch Latest AMD Video</u></a></li>
<li><a href="https://windows11.techidaily.com/effortlessly-accessing-windows-mixer-settings/"><u>Effortlessly Accessing Window's Mixer Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-pcs-outlook-speeds-on-windows/"><u>Elevate Your PC's Outlook Speeds on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-chrome-profiles-errors-on-your-workstation/"><u>Eliminating Chrome Profiles Errors on Your Workstation</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-faulty-printer-response-in-ad-ds-win-10-and-11/"><u>Eliminating Faulty Printer Response in AD DS, WIN 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-icon-grouping-in-windows-11/"><u>Eliminating Icon Grouping in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-windows-notepad-system-breakdowns/"><u>Eliminating Windows Notepad System Breakdowns</u></a></li>
<li><a href="https://windows11.techidaily.com/empower-windows-11-notepad-via-smart-assistant/"><u>Empower Windows 11 Notepad via Smart Assistant</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-device-detection-for-razer-gear-in-windows-11/"><u>Enabling Device Detection for Razer Gear in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-text-interaction-on-windows-pdfs-step-by-step-guide/"><u>Enabling Text Interaction on Windows PDFs: Step by Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-tech-performance-with-live-interface-elements/"><u>Enhance Tech Performance with Live Interface Elements</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-computer-experience-with-worldwide-mouse-expertise-in-powertoys/"><u>Enhance Your Computer Experience with Worldwide Mouse Expertise in PowerToys</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-view-remove-windows-overscan-effects/"><u>Enhance Your View: Remove Windows Overscan Effects</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-continuous-access-to-your-digital-post-its/"><u>Ensuring Continuous Access to Your Digital Post-Its</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-data-verification-in-winrar-archives-with-six-solutions/"><u>Ensuring Data Verification in WinRAR Archives with Six Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicate-performance-hiccups-a-guide-to-optimizing-warhammer-on-windows/"><u>Eradicate Performance Hiccups: A Guide to Optimizing Warhammer on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-overload-in-win-based-software-with-ease/"><u>Eradicating Overload in Win-Based Software with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/error-in-snipper-find-9-steps-for-swift-remedy/"><u>Error in Snipper? Find 9 Steps for Swift Remedy</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-app-on-itel-p40-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to Recover Deleted Photos from Android Gallery App on Itel P40</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-messages-from-your-infinix-hot-30-5g-by-fonelab-android-recover-messages/"><u>How to recover old messages from your Infinix Hot 30 5G</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-3-effective-ways-to-bypass-activation-lock-from-apple-iphone-6s-plus-by-drfone-ios/"><u>In 2024, 3 Effective Ways to Bypass Activation Lock from Apple iPhone 6s Plus</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-6-ways-to-transfer-contacts-from-realme-12-5g-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 6 Ways To Transfer Contacts From Realme 12 5G to iPhone | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-all-you-need-to-know-about-mega-greninja-for-vivo-y100a-drfone-by-drfone-virtual-android/"><u>In 2024, All You Need To Know About Mega Greninja For Vivo Y100A | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-innovative-audio-dramatic-writing/"><u>In 2024, Innovative Audio Dramatic Writing</u></a></li>
<li><a href="https://extra-support.techidaily.com/monitor-mastery-understanding-the-benefits-of-ultrawide-vs-uhd-4k-for-2024/"><u>Monitor Mastery  Understanding the Benefits of UltraWide vs UHD 4K for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/prestigious-music-archives-for-vfx-artists-for-2024/"><u>Prestigious Music Archives for VFX Artists for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/virtual-vice-versa-10-alternative-action-games/"><u>Virtual Vice-Versa  10 Alternative Action Games</u></a></li>
</ul></div>
