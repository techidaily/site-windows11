---
title: Steps to Reinstall Non-Loading Drivers in Windows 11
date: 2024-12-02T17:47:49.498Z
updated: 2024-12-03T23:31:46.745Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Reinstall Non-Loading Drivers in Windows 11
excerpt: This Article Describes Steps to Reinstall Non-Loading Drivers in Windows 11
keywords: Reinstall Driver,Windows 11 Driver Fix,Non-Loading Drivers Remedy,Load Non-Driver Issue,Windows 11 Update Drivers,Drivers Install Procedure,Windows Driver Reinstall Guide
thumbnail: https://thmb.techidaily.com/b1aabf9182a40f39eacfea832a56e2883c1058666aaa24cc7d5f400170f744e3.jpeg
---

## Steps to Reinstall Non-Loading Drivers in Windows 11

 Windows loads drivers every time you power on your PC. However, some users face the "A driver can't load on this device" error after they boot to the desktop. This error can arise while installing an unsigned driver or due to a meddlesome application.

 In this guide, we will discuss some methods to resolve this issue and restore your PC drivers to a normal working state.

## 1\. Check for Optional Windows Updates

 Optional updates can contain driver updates for your device components. So, you must check for available driver updates in the Windows Update Settings. Repeat the following steps:

1. Press **Win + I** to launch the Settings app.
2. Click on the **Windows Update** icon.
3. Now click on the **Advanced options**.
4. Scroll down to the **Additional Options** section. Click on the **Optional Updates** option.
5. Check if any optional updates related to the device you are facing issues with are available. Download and install it.  
![Install optional updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/install-optional-updates.jpg)
6. **Close** the Settings app.

 You can also visit the device manufacturer’s website to download the latest updated drivers, which will be digitally signed. These should pose no issues during installation.

## 2\. Disable the Memory Integrity Feature

 Memory Integrity is a security feature that leverages virtualization to protect unauthorized programs from making changes to important security processes. But this security setting can prevent a driver from loading old or unsigned drivers from running on your PC.

 So, you must disable Memory Integrity. Repeat the following steps:

1. Press **Win + I** to open the Settings app.
2. Click on the **Privacy & security** option in the left-hand side menu.
3. Now, click on the **Windows Security** option.
4. Scroll down and click on the **Device Security** option.
5. Navigate to the Core Isolation section. Click on the **Core isolation details** option.
6. Disable the **toggle** present below the **Memory Integrity** option.  
![Disable Memory Integrity](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/disable-memory-integrity.jpg)
7. **Restart** your PC to apply the changes.

 Now, check if the “a driver cannot load on this device” still pops up.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yDuvbv0QOYI?si=byottcEM_Rrvi4EL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Uninstall Any Recent System Updates

 If you are encountering an issue with a driver after installing a recent Windows update, you should consider removing that from your PC. Rolling back the update won’t remove any of your personal files.

 Check our guide on [ways to manually uninstall Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) for more information. But remember that it is not possible to remove all installed updates.

## 4\. Modify the System Registry

 Corrupt registry entries for the device can also be a reason for the hardware device encountering the driver issue. So, you must modify the system registry and remove those corrupt entries for the device.

 Make sure to manually export a [backup of your PC registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) onto a removable drive, so you always have the option to revert to the last working configuration.

 Repeat the following steps:

1. Right-click on the **Start** button to open the **Power User menu**. Click on the **Device Manager** option.
2. Locate the device facing driver issues and double-click on it to open its **Properties**.
3. Switch to the **Details** tab.
4. Click on the drop-down tab and click on the **Class GUID** option. It will display the GUID. **Copy** it to the clipboard.  
![Checking GUID in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/checking-guid-in-device-manager.jpg)
5. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **Regedit** and press the **Ctrl + Shift + Enter** keys to open the Registry editor.

6. Paste the following path into the address bar and press the **Enter** key:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Class\`
7. Press **Ctrl + F** to open the **Find** window. **Paste** the copied GUID and click on the **Find Next** option.
8. Go to the right-hand side pane of the found GUID key. Find the **UpperFilters** value.
9. Right-click on it and select the **Delete** option.  
![Modify the System Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/modify-the-system-registry.jpg)
10. Similarly, find the **LowerFilters** value and then delete it as well. Some devices may not have this value.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gOyLy8DeizY?si=GkAmK0hChZw6_2tW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

11. **Restart** your PC for the changes to take effect.

## 5\. Reinstall or Remove the Concerned Application

 Some users face an eny.sys driver issue which controls RGB lighting on PCs. This is a problem for many MSI and ASUS PC users. It is not a system utility and if it encounters an error every time, you must reinstall the concerned RGB-lighting-controlled application.

 Reinstalling the latest version will ensure that the application comes with signed drivers and fixes the driver issues with Windows 11 PCs. Here’s how to do it:

1. Right-click on the **Start** button to open the **Power User menu**.
2. Click on the **Installed apps** option.
3. Find the concerned RGB-controlling application and click on the **ellipsis** icon. Select the **Uninstall** option.
4. Click on the **Uninstall** button.  
![Remove a meddlesome application](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/remove-a-meddlesome-application.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qfCSLAhd4FY?si=CUBztmilaeAwl1lw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After removing the app, restart your PC and check if the error pops up now. Now, visit the app manufacturer's website and download the recent version of the RGB-control app. Install it and check if it causes the driver error. If that is the case, then you must remove the application.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0OxkndZbIA4?si=TWJlkTbYKsVag8-q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Use System Restore

 System Restore is an excellent utility baked into Windows that helps you fix issues in one go. It will roll back your PC to an earlier state when there were no abrupt issues with your PC.

 Check our guide on [how to use System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) and revert to an earlier PC state without losing your personal files. However, all the installed apps and updates after the restore point will be removed, if you adopt this route.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0pSRlspzW-A?si=A82G3Yxwj_31cKDq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Your Driver Issues on Windows 11, Fixed

 These are the best methods you can use to fix the "A driver can't load on this device" error on your Windows 11 PC. Update all the device drivers, install optional updates, and disable memory integrity. After that, modify the system registry and remove the meddlesome RGB application to get rid of this problem.

 In this guide, we will discuss some methods to resolve this issue and restore your PC drivers to a normal working state.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-save-the-day-guide-to-downloading-and-converting-vimeo-videos-mp4/"><u>[Updated] 2024 Approved Save the Day Guide to Downloading and Converting Vimeo Videos (MP4)</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-behind-the-brand-pewdiepies-financial-figures-unveiled-for-2024/"><u>[Updated] Behind the Brand PewDiePie’s Financial Figures Unveiled for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-igtvs-top-10-talents-to-follow-today/"><u>[Updated] In 2024, IGTV's Top 10 Talents to Follow Today</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-ignite-fitness-goals-with-the-ultimate-music-mix/"><u>2024 Approved Ignite Fitness Goals with the Ultimate Music Mix</u></a></li>
<li><a href="https://win-blog.techidaily.com/come-ottenere-la-licenza-di-ultimo-uso-da-movavi-software-termini-e-condizioni-efficaci/"><u>Come Ottenere La Licenza Di Ultimo Uso Da Movavi Software: Termini E Condizioni Efficaci</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-unable-to-launch-java-vm-on-windows-systems/"><u>Fixing Unable to Launch Java VM on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-to-fix-non-working-google-writes-on-pc/"><u>Guidelines to Fix Non-Working Google' Writes on PC</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-realme-11x-5g-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>In 2024, How to Unlock Realme 11X 5G Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://windows11.techidaily.com/internal-naming-systems-a-detailed-approach-to-folders-in-explorer/"><u>Internal Naming Systems: A Detailed Approach to Folders in Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-hard-drive-images-in-windows-os/"><u>Mastering Hard Drive Images in Windows OS</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/navigating-network-communications-key-aspects-of-outbound-ip-addresses-by-abbyy/"><u>Navigating Network Communications: Key Aspects of Outbound IP Addresses by ABBYY</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-to-install-powertoys-on-win11-pro/"><u>Navigating to Install PowerToys on Win11 Pro</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-elite-car-beat-merging-software-for-mac-platforms-for-2024/"><u>New Elite Car Beat Merging Software for Mac Platforms for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/overhauling-the-default-administrator-model-for-windows-users/"><u>Overhauling the Default Administrator Model for Windows Users</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/questioning-the-benefit-of-ai-driven-chat-bots/"><u>Questioning the Benefit of AI-Driven Chat Bots</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/resolving-fb-message-app-video-not-sending-error-on-mobile-devices/"><u>Resolving FB Message App Video Not Sending Error on Mobile Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-your-input-not-recognized-by-vlc/"><u>Resolving Windows: Your Input Not Recognized by VLC</u></a></li>
<li><a href="https://windows11.techidaily.com/secrets-of-storage-the-top-6-win11-techniques-for-capturing-file-and-directory-paths/"><u>Secrets of Storage: The Top 6 Win11 Techniques for Capturing File & Directory Paths</u></a></li>
<li><a href="https://windows11.techidaily.com/traversing-the-digital-landscape-with-ease/"><u>Traversing the Digital Landscape with Ease</u></a></li>
</ul></div>

