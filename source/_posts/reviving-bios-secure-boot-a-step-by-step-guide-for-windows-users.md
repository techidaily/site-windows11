---
title: "Reviving BIOS Secure Boot: A Step-by-Step Guide for Windows Users"
date: 2024-11-17T18:27:43.201Z
updated: 2024-11-24T16:12:24.365Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Reviving BIOS Secure Boot: A Step-by-Step Guide for Windows Users"
excerpt: "This Article Describes Reviving BIOS Secure Boot: A Step-by-Step Guide for Windows Users"
keywords: BIOS Revival Tips,Secure Boot Overhaul,Windows Secure Boot Guide,Secure Boot Restoration,Enhancing BIOS Security,Windows System Update,BIOS Upgrade Steps
thumbnail: https://thmb.techidaily.com/e9e9b7ca60047014bff6bb18f8c482a86a228fe45f3ba370acbb24c0cc43ac69.jpg
---

## Reviving BIOS Secure Boot: A Step-by-Step Guide for Windows Users

 You need a secure boot-compatible computer to install Windows 11\. But there are other reasons to enable secure boot when available. It is a safety standard that prevents malicious codes from running on your PC during boot.

 But what if secure boot option is grayed out in BIOS? This can happen due to incorrect changes to your BIOS settings. You can load the default boot configuration to restore secure boot on Windows. Here is how to troubleshoot and fix the secure boot grayed-out problem in the BIOS.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xIP8ktrmOdg?si=zRnjbGzM6PDx2jCq&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Set Admin Password in BIOS

 You can set an administrator password in BIOS security to prevent unauthorized access to the setup utility. On some computers, you may need to enable an administrator password to enable secure boot.

 To set an administrator password, you need to access the BIOS Security tab. The following steps are for an HP Pavilion laptop. Refer to your manufacturer's manual for other OEM devices.

To set an administrator password in BIOS:

1. Shut down your PC.
2. Press the**Power** to restart and then start pressing the**F10** key to enter BIOS Setup Utility. Other manufacturers like Dell, Asus, and Lenovo use F2 to access the BIOS utility.
3. In the BIOS Setup Utility, use the right and left arrow keys to open the**Security** tab.  
![bios set administrator password 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/bios-set-administrator-password-1.jpg)
4. Next, select**Administrator Password** and press**Enter** . On other computers, you may see the**Set Supervisor Password** option instead.
5. Here, type your new administrator password and then repeat the password in the**Confirm New Password** field.
6. Press**Enter** to save the password.  
![bios set administrator password](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/bios-set-administrator-password.jpg)
7. Next, press**F10** to save the changes and exit**BIOS** .
8. Boot into**BIOS** again, and**Secure Boot** should be available for use.

 You can remove the administrator password after enabling Secure Boot. To do this, open the**Security** tab in BIOS and select**Administrator Password** . Next, enter your administrator password, but leave the**Enter New Password** and**Confirm New Password** fields blank. Press**Enter** again to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aqeO4ed766s?si=AWtKHxP4hvQRd_lk&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Disable Fast Boot in BIOS

 Fast Boot is a UEFI/BIOS feature. When enabled, it skips the check for a USB device, such as a bootable drive to speed up the boot process. However, the same can also prevent you from enabling secure boot in BIOS.

 To fix the issue, boot into the BIOS Setup Utility and disable Fast Boot. This feature may not be available on all computers. If not available, skip to the next solution.

 Note that the fast boot feature is different from Fast Startup. Fast Boot is a BIOS feature, whereas[Fast Startup is a Windows feature to speed up the boot process](https://www.makeuseof.com/what-is-windows-fast-startup-why-disable-it/) .

To disable fast boot in BIOS:

1. Boot into**BIOS**
2. Use the right and left arrow keys to open the**Advanced** tab.
3. Next, select**Boot Options** and press**Enter** .
4. Select**Fast Boot** and set it to**Disabled** .
5. Press**Enter** to save the changes.
6. Press**F10** to save the changes and exit.
7. After the computer restarts, boot into BIOS to see if you can access Secure Boot.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hHPljBHrvkA?si=HwdfDM9rlbABSIrx&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Restore the BIOS Security Settings to Factory Defaults

 You can restore BIOS security settings to factory defaults to enable secure boot. If you have made major changes to the BIOS security settings, a reset will remove the custom configuration and restore the factory default security settings. Most BIOS utilities allow you to perform a restore in the BIOS Security tab.

To restore BIOS Security settings to factory defaults:

1. Boot into BIOS.
2. Open the**Security** tab using the arrow keys.
3. Use the down arrow keys and select**Restore Security settings to factory defaults** .  
![restore bios factory settings default](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/restore-bios-factory-settings-default.jpg)
4. Read the description in the**Security Feature Reset Request** dialog. Here you'll need to enter a pass code to complete the reset request.

5. So, enter the shown**pass code** and press**Enter** .  
![restore bios factory settings default pass code](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/restore-bios-factory-settings-default-pass-code.jpg)
6. Press**F10** to save the changes and exit**BIOS** .

7. Boot into BIOS again and check if the greyed-out secure boot problem is resolved.

## 4\. Update BIOS

![system information bios version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/system-information-bios.jpg)

 If the issue persists, your problem may be due to outdated BIOS firmware. While you don't need to update your system BIOS as frequently, the newer version tends to bring bug fixes, performance improvements, and newer hardware support.

 A BIOS update is recommended if your motherboard or laptop manufacturer recommends it. Any updates will be available via the laptop or motherboard manufacturer's websites.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9wiIVztRIqQ?si=GBgdwQ78k5hbeFDv&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Prepare Your Computer for a BIOS Update

 Before you update your BIOS, you'll need to[suspend BitLocker protection](https://www.makeuseof.com/windows-10-disable-or-suspend-bitlocker/) . You may also need to[temporarily turn off Windows Security protection](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) and third-party antivirus.

 Next, check your current BIOS version. You don't want to install an older version of BIOS on your computer. So, press the**Win** key, type**system information** , and open the System Information app from the search results. In the System Information dialog, locate and check the**BIOS Version/Date** entry. Note down the BIOS version, for example,**AMI F.27, 3/17/2022** .

 Unlike other driver and software feature updates, updating your BIOS can be tricky. You can update BIOS from within BIOS, where the BIOS Setup Utility can check your laptop manufacturer's website for BIOS updates. This option, however, is not available for all computers.

![HP download bios firmware update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hp-download-bios-firmware-update.jpg)

 Alternatively, you can also manually install BIOS from within Windows. For example, on an HP computer, go to the[HP Drivers page](https://support.hp.com/drivers) . Select your device manually or let the website detect the device for you.

 Next, check for the pending drivers and BIOS updates. If detected, download the HP Notebook System BIOS Update (Intel / AMD Processors). Make sure to compare the version with the version installed on your PC. If same or older, you don't need to update your BIOS.

 To update BIOS, run the firmware file and follow the on-screen instructions. Your computer will restart into the BIOS Update utility. Select**Apply Update Now** and wait for the update to finish installing. Once done, boot into BIOS and check if the Secure Boot option is available. Make sure to enable your antivirus and BitLocker protection again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kiW7sLvL65k?si=IHSeRFsYCrfqpn2o&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Load the BIOS Defaults Settings

![load BIOS default settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/load-bios-default-settings.jpg)

 You can restore your BIOS to its factory default settings to fix issues occurring due to corrupt BIOS configuration. While loading the default settings will not affect your data, we recommend you back up any and all the important data on your computer before proceeding with a BIOS reset.

To load BIOS defaults settings:

1. Boot into**BIOS** and open the**Exit** tab.
2. Next, select the**Load Setup Defaults** option and press**Enter** .
3. Select**Yes** and press**Enter** . This will load setup default values for all SETUP items.
4. Select**Save Changes** and**Exit** .
5. Boot into**BIOS** again and check if the secure boot option is restored.

## Fixing the Grayed Out Secure Boot Option in BIOS

 Secure Boot in BIOS is greyed out if the administrator password is not set. In other instances, incorrect BIOS security settings and outdated BIOS can cause the issue. As a last resort, try to restore BIOS settings to factory defaults to restore Secure Boot in BIOS.

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
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-5-effective-ways-of-resizing-your-igtv-videos/"><u>[New] 2024 Approved 5 Effective Ways of Resizing Your IGTV Videos</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-keeping-track-of-changed-followers-on-instagram/"><u>[New] In 2024, Keeping Track of Changed Followers on Instagram</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-tiktok-earnings-gurus-choice-top-6-tools/"><u>[Updated] 2024 Approved TikTok Earnings Gurus' Choice Top 6 Tools</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-odins-last-hope-the-ragnarok-revelation/"><u>[Updated] In 2024, Odin's Last Hope The Ragnarok Revelation</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-lightning-leap-into-facebook-id-sleuthing/"><u>[Updated] Lightning Leap Into Facebook ID Sleuthing</u></a></li>
<li><a href="https://windows11.techidaily.com/custom-windows-11-taskbar-placement-hacks/"><u>Custom Windows 11 Taskbar Placement Hacks</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-data-consumption-by-windows-programs/"><u>Decoding Data Consumption by Windows Programs</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/find-your-dream-laptop-in-july-2astock-the-hottest-deals-and-discounts-techsavvy/"><u>Find Your Dream Laptop in July 2Astock: The Hottest Deals and Discounts | TechSavvy</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/fixing-auto-focus-issues-on-your-iphone-camera-for-crisp-images/"><u>Fixing Auto-Focus Issues on Your iPhone Camera for Crisp Images</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-projector-disconnected-error-on-your-pc/"><u>Fixing Projector Disconnected Error on Your PC</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-your-realme-c53-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>In 2024, How to Mirror Your Realme C53 Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-new-horizinas-with-ease-top-8-windows-11-avoidances/"><u>Navigating New Horizinas with Ease: Top 8 Windows 11 Avoidances</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-gameplay-low-lag-high-fps-on-roblox-pcs/"><u>Optimizing Gameplay: Low Lag, High FPS on Roblox PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-for-printer-not-available-errors/"><u>Quick Fix for Printer Not Available Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-clearing-xbox-game-pass-errors-on-windows-11-systems/"><u>Strategies for Clearing Xbox Game Pass Errors on Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/swapping-windows-11s-standard-programs-best-choices/"><u>Swapping Windows 11'S Standard Programs: Best Choices</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723212125104-troubleshooting-audio-issues-on-windows-11-get-your-volume-back/"><u>Troubleshooting Audio Issues on Windows 11 - Get Your Volume Back</u></a></li>
<li><a href="https://change-location.techidaily.com/ultimate-guide-to-get-the-meltan-box-pokemon-go-for-vivo-y56-5g-drfone-by-drfone-virtual-android/"><u>Ultimate guide to get the meltan box pokemon go For Vivo Y56 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-guide-syncing-with-apples-calendar-app/"><u>Windows 11 Guide: Syncing with Apple's Calendar App</u></a></li>
</ul></div>

