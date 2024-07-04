---
title: "Boost Up Your PC: Set Auto Update + Modify AMD Video"
date: 2024-07-03T11:11:18.028Z
updated: 2024-07-04T11:11:18.028Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Boost Up Your PC: Set Auto Update + Modify AMD Video"
excerpt: "This Article Describes Boost Up Your PC: Set Auto Update + Modify AMD Video"
keywords: Boost PC Auto Update,AMD Video Settings,Enhance PC Performance,Optimize Video Rendering,PC Auto Software Upgrade,Custom AMD Video Tuning,Improve PC Graphics
thumbnail: https://thmb.techidaily.com/b034e397cf58f21c63fc5dd80cb149d6528213f9e99cf7ed2375f403fbf9fc3e.jpg
---

## Boost Up Your PC: Set Auto Update + Modify AMD Video

 AMD Software Adrenaline Edition on Windows lets you manage your AMD graphics card, game stats, perform driver updates, and more. Sometimes, after an update, it may fail to launch with the error Windows update has replaced your AMD graphics driver.

 The full error reads Windows update may have automatically replaced your AMD graphics driver. This error is due to a conflict between the AMD Software Adrenaline Edition driver and the UWP AMD graphics driver installed by Windows.

 To fix the problem, you’ll need to stop Windows from installing AMD Radeon drivers automatically and perform a manual reinstall. Here’s how to do it.

## Why Does Windows Automatically Replace Your AMD Graphics Drivers?

 By default, the Windows operating system installs the [Microsoft Basic Display Adapter](https://www.makeuseof.com/microsoft-basic-display-adapter-guide/) during the initial setup. It provides display graphics capabilities so that you can set up your new computer and install the necessary drivers.

 This basic display driver lets you configure your discrete graphics with the latest drivers using AMD Software. It also acts as a backup when your discrete GPU driver faults causing [black screen issues on Windows](https://www.makeuseof.com/fix-black-screen-on-windows-10-11/) .

 However, this error occurs when Windows updates install the UWP (Universal Windows Platform) driver for your AMD Radeon GPU. Since two versions of the same driver are installed, when you try to open the AMD Software Adrenaline Edition app it will trigger an error.

 AMD has addressed this issue and provided a quick fix. To fix the error, you'll need to stop Windows from automatically installing the AMD graphics drivers. Then, reinstall the AMD graphics driver using AMD software.

## 1\. Roll Back the AMD Graphics Driver

![amd radeon display adapter driver roll back](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/amd-radeon-display-adapter-driver-roll-back.jpg)

 An easy way to fix Windows replacing your AMD graphics error is to roll back the AMD graphics driver. A driver rollback removes the current driver and reinstalls the previous version saved on your computer. Fortunately, you can [roll back device drivers using the Windows Device Manager](http://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) .

 In Device Manager, look for and expand the**Display Adapters** section. Here, select the**AMD Radeon (TM) graphics** device and perform a driver rollback. Once done, restart your computer and check for any improvements. If the**Roll Back Driver** option is greyed out, you can't perform a rollback for the selected device.

 Once the error is resolved, you'll need to stop Windows from automatically downloading AMD drivers. If not, you’ll likely encounter the same error after each Windows update.

 You can [stop automatic driver updates on Windows](https://www.makeuseof.com/windows-stop-automatic-driver-updates/) using device installation settings,**Group Policy Editor** , and the**Windows Registry** . With the device installation settings for automatic driver download set to off, Windows won't download and install AMD graphics drivers automatically.

## 2\. Repair and Reinstall the AMD Software Driver

![amd radeon software installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/amd-radeon-software-installer.jpg)

 You can reinstall the AMD Software driver using the existing driver. This may fix temporary issues with the driver causing the conflict. Follow these steps to repair and reinstall the AMD graphics driver:

1. Press**Win + E** to open File Explorer and navigate to the following location:  
`C:\AMD\RadeonInstaller\RadeonInstaller\Radeon_Folder_with_verison_name`
2. Next, double-click to run the**Setup.exe** file.  
![run amd setup exe repair graphics driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/run-amd-setup-exe-repair-graphics-driver.jpg)
3. In the**AMD Radeon Software Installer** dialog, select the driver version to install.
4. Click**Install** and wait for the driver to install.

 If you encounter an AMD error 195, temporarily [disable Windows Defender Firewall](https://www.makeuseof.com/how-to-turn-off-windows-defender/) and**Real-Time Threat Protection** and try again.

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

 After the restart, you can [update your AMD Radeon graphics driver](https://www.makeuseof.com/update-amd-radeon-graphics-driver-windows-11/) using AMD Software. Install the driver and restart your PC to see if the error is resolved.

## 4\. Use a System Restore Point

 A restore point helps you recover your computer when a bad Windows update or driver installation causes the system to malfunction. You can use a restore point to undo the changes without affecting your data and files.

 Unfortunately, using a System Restore point requires you made one in the past. If you haven't made any, now's a good time to get into the habit of making them. Check out [how to make a System Restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) for more information.

To undo the recent changes using a restore point:

1. Press**Win + R** to open**Run** .
2. Type**rstrui.exe** and click**OK** .  
![select restore point](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/select-restore-point.jpg)
3. In the**System Restore** dialog, select the**Recommended** **restore** option. If not, select the**Choose a different restore point** option**.**
4. Select a**restore point** and click**Next** .  
![select restore point windows 11 finish](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/select-restore-point-windows-11-finish.jpg)
5. Read the description and click**Finish** .
6. System Restore will restart and restore your PC to the state it was in before the date of the selected restore point.

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
<li><a href="https://windows11.techidaily.com/overcome-stubborn-windows-terminals-a-step-by-step-guide/"><u>Overcome Stubborn Windows Terminals: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-system-integration-enable-windows-subsystem-for-linux/"><u>Seamless System Integration: Enable Windows Subsystem for Linux</u></a></li>
<li><a href="https://windows11.techidaily.com/taskers-curiosity-non-edge-process-puzzles/"><u>Tasker's Curiosity: Non-Edge Process Puzzles</u></a></li>
<li><a href="https://windows11.techidaily.com/dism-mastery-in-windows-11-system-image-repair/"><u>Dism Mastery in Windows 11 System Image Repair</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-to-mask-dimming-functionality-in-system-preferences/"><u>Tactics to Mask Dimming Functionality in System Preferences</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windowed-discord-for-flawless-search-experience/"><u>Optimizing Windowed Discord for Flawless Search Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/navigational-aid-embracing-apple-maps-in-windows-systems/"><u>Navigational Aid: Embracing Apple Maps in Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/command-prompt-curiosities-5-fun-filled-functions/"><u>Command Prompt Curiosities: 5 Fun-Filled Functions</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-reset-a-locked-itel-p55t-phone-by-drfone-android/"><u>In 2024, How to Reset a Locked Itel P55T Phone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-change-your-iphone-se-2022-apple-id-on-macbook-by-drfone-ios/"><u>In 2024, How To Change Your iPhone SE (2022) Apple ID on MacBook</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-13-powerful-video-editors-that-outshine-windows-movie-maker/"><u>Updated In 2024, 13 Powerful Video Editors That Outshine Windows Movie Maker</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-free-tools-for-marketing-mavens-the-best-fb-video-creators-reviewed/"><u>2024 Approved  Free Tools for Marketing Mavens  The Best FB Video Creators Reviewed</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-lava-yuva-3-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use GPS Joystick to Fake GPS Location On Lava Yuva 3 | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/how-to-clear-your-default-podcast-listings-on-spotify-for-2024/"><u>How to Clear Your Default Podcast Listings on Spotify for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/easy-to-follow-guide-for-configuring-streamlabs-obs-for-2024/"><u>Easy-to-Follow Guide for Configuring Streamlabs OBS for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-legendaries-are-in-pokemon-platinum-on-oneplus-11-5g-drfone-by-drfone-virtual-android/"><u>What Legendaries Are In Pokemon Platinum On OnePlus 11 5G? | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-revive-faded-iphone-hdri-select-4-effective-methods-in-premiere-pro/"><u>2024 Approved  Revive Faded iPhone HDRI  Select 4 Effective Methods in Premiere Pro</u></a></li>
</ul></div>
