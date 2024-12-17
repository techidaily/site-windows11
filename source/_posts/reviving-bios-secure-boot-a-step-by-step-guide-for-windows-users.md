---
title: "Reviving BIOS Secure Boot: A Step-by-Step Guide for Windows Users"
date: 2024-12-09T23:15:03.496Z
updated: 2024-12-16T18:51:37.380Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2Iv3DjT2Fyw?si=pR_z8ZDDVGF2MvKJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Update BIOS

![system information bios version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/system-information-bios.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qv4Qm7kpeMs?si=9fv5SOS5a2DvixTK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the issue persists, your problem may be due to outdated BIOS firmware. While you don't need to update your system BIOS as frequently, the newer version tends to bring bug fixes, performance improvements, and newer hardware support.

 A BIOS update is recommended if your motherboard or laptop manufacturer recommends it. Any updates will be available via the laptop or motherboard manufacturer's websites.

### Prepare Your Computer for a BIOS Update

 Before you update your BIOS, you'll need to[suspend BitLocker protection](https://www.makeuseof.com/windows-10-disable-or-suspend-bitlocker/) . You may also need to[temporarily turn off Windows Security protection](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) and third-party antivirus.

 Next, check your current BIOS version. You don't want to install an older version of BIOS on your computer. So, press the**Win** key, type**system information** , and open the System Information app from the search results. In the System Information dialog, locate and check the**BIOS Version/Date** entry. Note down the BIOS version, for example,**AMI F.27, 3/17/2022** .

 Unlike other driver and software feature updates, updating your BIOS can be tricky. You can update BIOS from within BIOS, where the BIOS Setup Utility can check your laptop manufacturer's website for BIOS updates. This option, however, is not available for all computers.

![HP download bios firmware update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hp-download-bios-firmware-update.jpg)

 Alternatively, you can also manually install BIOS from within Windows. For example, on an HP computer, go to the[HP Drivers page](https://support.hp.com/drivers) . Select your device manually or let the website detect the device for you.

 Next, check for the pending drivers and BIOS updates. If detected, download the HP Notebook System BIOS Update (Intel / AMD Processors). Make sure to compare the version with the version installed on your PC. If same or older, you don't need to update your BIOS.

 To update BIOS, run the firmware file and follow the on-screen instructions. Your computer will restart into the BIOS Update utility. Select**Apply Update Now** and wait for the update to finish installing. Once done, boot into BIOS and check if the Secure Boot option is available. Make sure to enable your antivirus and BitLocker protection again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KF793jv1LIc?si=fJOogQJ2f8JUfTzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Load the BIOS Defaults Settings

![load BIOS default settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/load-bios-default-settings.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GFHH14XlFCk?si=2HcjQbDx5eG0ZQAt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can restore your BIOS to its factory default settings to fix issues occurring due to corrupt BIOS configuration. While loading the default settings will not affect your data, we recommend you back up any and all the important data on your computer before proceeding with a BIOS reset.

To load BIOS defaults settings:

1. Boot into**BIOS** and open the**Exit** tab.
2. Next, select the**Load Setup Defaults** option and press**Enter** .
3. Select**Yes** and press**Enter** . This will load setup default values for all SETUP items.
4. Select**Save Changes** and**Exit** .
5. Boot into**BIOS** again and check if the secure boot option is restored.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-upgrading-minecraft-stability-via-ram-adjustment/"><u>[Updated] 2024 Approved Upgrading Minecraft Stability via RAM Adjustment</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-methods-to-fix-error-code-0x80041015/"><u>Effective Methods to Fix Error Code 0X80041015</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-run-windows-11-news-and-video-sites-without-strain/"><u>Efficiently Run Windows 11 News & Video Sites without Strain</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-webp-experience-with-these-4-windows-viewer-tools/"><u>Elevate WebP Experience with These 4 Windows Viewer Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-uninstall-troubles-with-epic-games-hub-w11/"><u>Eliminating Uninstall Troubles with Epic Games Hub W11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-windows-0x800704b3-network-hurdles/"><u>Eliminating Windows' 0X800704B3 Network Hurdles</u></a></li>
<li><a href="https://windows11.techidaily.com/elusive-archive-tucked-away-zip-and-images-on-windows-11/"><u>Elusive Archive Tucked Away: ZIP & Images on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-windows-event-viewer-functionality/"><u>Enhancing Windows Event Viewer Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-hypervisorerr-bsod-in-windows-1011/"><u>Eradicating HYPERVISOR_ERR: BSOD in Windows 10/11</u></a></li>
<li><a href="https://android-location.techidaily.com/for-people-wanting-to-mock-gps-on-zte-blade-a73-5g-devices-drfone-by-drfone-virtual/"><u>For People Wanting to Mock GPS on ZTE Blade A73 5G Devices | Dr.fone</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/how-to-successfully-overcome-whea-unrecoverable-bsod-mistakes/"><u>How to Successfully Overcome WHEA Unrecoverable BSOD Mistakes</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-successfully-restore-and-improve-your-voicemod-experience/"><u>How to Successfully Restore and Improve Your Voicemod Experience</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-and-where-to-find-a-shiny-stone-pokemon-for-honor-play-40c-drfone-by-drfone-virtual-android/"><u>In 2024, How and Where to Find a Shiny Stone Pokémon For Honor Play 40C? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-fix-honor-magic-vs-2-find-my-friends-no-location-found-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Honor Magic Vs 2 Find My Friends No Location Found? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-simulate-gps-movement-with-location-spoofer-on-oppo-find-x7-drfone-by-drfone-virtual-android/"><u>In 2024, How To Simulate GPS Movement With Location Spoofer On Oppo Find X7? | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/navigating-compression-related-distortion-on-youtube-for-2024/"><u>Navigating Compression-Related Distortion on YouTube for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/textual-brilliance-in-media-exploring-the-best-effects-for-2024/"><u>Textual Brilliance in Media Exploring the Best Effects for 2024</u></a></li>
</ul></div>

