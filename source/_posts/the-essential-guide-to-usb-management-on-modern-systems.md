---
title: The Essential Guide to USB Management on Modern Systems
date: 2024-08-31T22:10:10.912Z
updated: 2024-09-01T22:10:10.912Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Essential Guide to USB Management on Modern Systems
excerpt: This Article Describes The Essential Guide to USB Management on Modern Systems
keywords: USB Basics,System USB Control,Manage USB Devices,USB Troubleshooting,Data Transfer USBs,Storage Management,USB Speed Optimization
thumbnail: https://thmb.techidaily.com/b47fd0e753c3df7e85d7c99e9dd6f25592469353c9ed51bdab027cc3c0e36d8f.jpg
---

## The Essential Guide to USB Management on Modern Systems

 Want to prevent others from stealing your PC data through removable storage devices? Or do you want to protect your device from harmful files contained on removable storage devices?

 In this article, we’ll explore how you can prevent others from installing removable storage devices on Windows. That way, your device won't read any removable storage devices without your permission. Lastly, we’ll also show you how to allow others to install specific removable storage devices.

## How to Prevent Others From Installing Any Removable Storage Devices

 Let's start by checking out how you can prevent others from installing any removable storage device into your PC. You can do this using either the Local Group Policy Editor or the Registry Editor.

### Using the Local Group Policy Editor

![Using a Windows laptop on a brown desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Using-a-Windows-laptop-on-a-brown-desk.jpg)

 The Local Group Policy Editor (LGPE) is a reliable tool for troubleshooting system errors. Interestingly, you can also use it for other tasks such as [preventing others from changing your Windows desktop background](https://www.makeuseof.com/stop-others-change-windows-desktop-background/).

 Now, here’s how to use the LGPE to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **Computer Configuration > Administrative Templates > System > Device Installation > Device Installation Restrictions**.
4. Double-click on the **Prevent installation of removable devices** option on the right-hand side.

![Clicking the prevent installation of removable devices option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-prevent-installation-of-removable-devices-option.jpg)

 Select **Enabled** on the next screen to prevent others from installing removable storage devices into your PC. Alternatively, select **Disabled** or **Not Configured** to restore the default settings.

 Finally, press **Apply** and then press **OK** to save these changes.

 Struggling to access the LGPE on Windows Home? There are a few tricks you can apply to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). But if that sounds complicated to you, then skip to the Registry Editor method.

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Using the Registry Editor

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
 The Registry Editor is another reliable tool you can use for tweaking system settings and troubleshooting PC issues.

 However, this tool is quite sensitive. So, it’s often worth [backing up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first before editing its keys.

 Now, here’s how to use the Registry Editor to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **Regedit** and press **Enter** to open the Registry Editor.
3. Copy-paste the following command into the address bar and press **Enter**:

HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows

 From there, follow these steps:

1. Right-click on the **Windows** folder and select **New > Key**. From there, name this key as **DeviceInstall** and press **Enter**.
2. Right-click on the **DeviceInstall** key and select **New > Key**. Next, name the key as **Restrictions** and press **Enter**.
3. Click the **Restrictions** folder, right-click on a blank space on the right, and then select **New > DWORD (32-bit) Value**. From there, name the value as **DenyRemovableDevices** and press **Enter**.

![Clicking the DenyRemovableDevices value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-DenyRemovableDevices-value.jpg)

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
 Now, follow these steps:

1. Double-click on the **DenyRemovableDevices** value.
2. Set the **Value data** as **1** and then press **OK** to prevent others from installing storage devices into your PC. Alternatively, set the **Value data** as **0** and press **OK** to allow others to install removable storage devices on your PC.
3. Close the Registry Editor and restart your device to save these changes.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Prevent Others From Installing Specific Removable Storage Devices

 In some instances, you might want to prevent others from installing specific removable storage devices. So, let’s show you how you can do that using either the LGPE or the Registry Editor.


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
<li><a href="https://extra-information.techidaily.com/new-boosting-visual-and-auditory-composition-with-custom-filters-and-melodies-windows-10-photos/"><u>[New] Boosting Visual & Auditory Composition with Custom Filters & Melodies (Windows 10 Photos)</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-mastering-audio-capture-from-skype-for-mp3/"><u>[New] Mastering Audio Capture From Skype for MP3</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-premium-cloud-storage-services-a-guides-choice/"><u>[New] Premium Cloud Storage Services  A Guide's Choice</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-top-15-activities-for-podcast-enthusiasts-for-2024/"><u>[New] Top 15 Activities for Podcast Enthusiasts for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-exclusive-screenflow-examination-for-mac-users/"><u>[Updated] Exclusive ScreenFlow Examination for Mac Users</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-unveiling-this-years-premier-trivia-broadcasting-titles/"><u>2024 Approved  Unveiling This Year's Premier Trivia Broadcasting Titles</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-network-issues-with-anydesk-in-win11/"><u>Fixing Network Issues with AnyDesk in WIn11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/guide-to-make-your-shorts-thumbnail-pop-up-for-2024/"><u>Guide to Make Your Shorts' Thumbnail Pop Up for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-vivo-y100-location-on-skout-drfone-by-drfone-virtual-android/"><u>How to Change Vivo Y100 Location on Skout | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-remedy-the-usb-attachment-failure-in-virtualbox-instantly/"><u>How to Remedy the USB Attachment Failure in VirtualBox Instantly</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-8-best-apps-for-screen-mirroring-samsung-galaxy-a14-4g-pc-drfone-by-drfone-android/"><u>In 2024, 8 Best Apps for Screen Mirroring Samsung Galaxy A14 4G PC | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-samsung-galaxy-s23-tactical-edition-bootloader-easily-by-drfone-android/"><u>In 2024, How to Unlock Samsung Galaxy S23 Tactical Edition Bootloader Easily</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-mastering-audio-notes-essential-tips/"><u>In 2024, Mastering Audio Notes  Essential Tips</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-the-ultimate-guide-to-video-metadata-editing-on-mac-8-top-picks/"><u>In 2024, The Ultimate Guide to Video Metadata Editing on Mac 8 Top Picks</u></a></li>
<li><a href="https://android-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-motorola-edge-2023-phone-frp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Motorola Edge 2023 Phone FRP Lock</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/maintain-a-wakeful-macbook-techniques-for-disabling-auto-sleep-with-closed-lid/"><u>Maintain a Wakeful MacBook: Techniques for Disabling Auto-Sleep with Closed Lid</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-android-windows-integration-for-webcams/"><u>Mastering Android-Windows Integration for Webcams</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-visual-quality-with-w11s-auto-hdr/"><u>Maximizing Visual Quality with W11's Auto HDR</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-background-run-of-microsoft-edge-on-win11/"><u>Navigating the Background Run of Microsoft Edge on Win11</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-big-four-of-social-networking-facebook-twitter-instagram-and-youtube/"><u>Navigating the Big Four of Social Networking: Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windows-launch-directly-engage-file-explorer-through-onedrive/"><u>Optimizing Windows Launch: Directly Engage File Explorer Through OneDrive</u></a></li>
<li><a href="https://win-blog.techidaily.com/overcoming-constant-fuser-app-errors-and-stabilizing-your-desktop-experience/"><u>Overcoming Constant Fuser App Errors and Stabilizing Your Desktop Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-game-pass-service-halt-in-win-os/"><u>Overcoming Game Pass Service Halt in Win OS</u></a></li>
<li><a href="https://windows11.techidaily.com/power-through-print-settings-in-win11-quick-guide-max-48-chars/"><u>Power Through Print Settings in Win11 - Quick Guide (Max 48 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-and-easy-guide-for-turning-onoff-windows-key/"><u>Quick & Easy Guide for Turning On/Off Windows Key</u></a></li>
<li><a href="https://video-capture.techidaily.com/revolutionizing-personal-cinema-with-xiaomis-mi-11-lite-features/"><u>Revolutionizing Personal Cinema with Xiaomi's Mi 11 Lite Features</u></a></li>
<li><a href="https://windows11.techidaily.com/safeguard-privacy-erasing-ms-defender-logs-in-windows-1011/"><u>Safeguard Privacy: Erasing MS Defender Logs in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/set-up-a-fast-safe-login-windows-hello-basics/"><u>Set Up a Fast, Safe Login: Windows Hello Basics</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-strategy-to-erase-wsl-from-windows-11-operating-system/"><u>Stepwise Strategy to Erase WSL From Windows 11 Operating System</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-overcoming-windows-administrative-restriction-on-installers/"><u>Strategies for Overcoming Windows' Administrative Restriction on Installers</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-to-overcome-onedrives-immediate-folder-addition-error/"><u>Swift Solutions to Overcome OneDrive's Immediate Folder Addition Error</u></a></li>
<li><a href="https://windows11.techidaily.com/the-insiders-guide-accessing-onedrive-offline-on-windows/"><u>The Insider's Guide: Accessing OneDrive Offline on WINDOWS</u></a></li>
<li><a href="https://windows11.techidaily.com/the-new-era-ai-enhancements-in-windows-platforms/"><u>The New Era: AI Enhancements in Windows Platforms</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-your-devices-unwanted-power-naps-with-easy-tips/"><u>Troubleshoot Your Device's Unwanted Power Naps with Easy Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-unsupported-app-packages-on-windows-xp/"><u>Troubleshooting Unsupported App Packages on Windows XP</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-smooth-gaming-on-windows-eradicate-errors/"><u>Unleash Smooth Gaming on Windows, Eradicate Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-outlook-preview-features-on-windows-11-platforms/"><u>Unveiling Outlook Preview Features on Windows 11 Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-terminal-the-art-of-color-selection/"><u>Windows Terminal: The Art of Color Selection</u></a></li>
<li><a href="https://windows11.techidaily.com/winrar-archive-integrity-preventing-checksum-error-messages/"><u>WinRAR Archive Integrity: Preventing Checksum Error Messages</u></a></li>
</ul></div>
