---
title: The Essential Guide to USB Management on Modern Systems
date: 2024-10-19T18:13:29.471Z
updated: 2024-10-24T18:27:23.401Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123731/7443" target="_top" id="2123731">
  <img src="//a.impactradius-go.com/display-ad/7443-2123731" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123731/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The Local Group Policy Editor (LGPE) is a reliable tool for troubleshooting system errors. Interestingly, you can also use it for other tasks such as [preventing others from changing your Windows desktop background](https://www.makeuseof.com/stop-others-change-windows-desktop-background/).

 Now, here’s how to use the LGPE to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **Computer Configuration > Administrative Templates > System > Device Installation > Device Installation Restrictions**.
4. Double-click on the **Prevent installation of removable devices** option on the right-hand side.

![Clicking the prevent installation of removable devices option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-prevent-installation-of-removable-devices-option.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2141683/17092" target="_top" id="2141683">
  <img src="//a.impactradius-go.com/display-ad/17092-2141683" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettide.pxf.io/i/5597632/2141683/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Select **Enabled** on the next screen to prevent others from installing removable storage devices into your PC. Alternatively, select **Disabled** or **Not Configured** to restore the default settings.

 Finally, press **Apply** and then press **OK** to save these changes.

 Struggling to access the LGPE on Windows Home? There are a few tricks you can apply to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). But if that sounds complicated to you, then skip to the Registry Editor method.

### Using the Registry Editor

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

<!-- affiliate ads begin -->
<a href="https://smilemakers.pxf.io/c/5597632/2123899/26106" target="_top" id="2123899">
  <img src="//a.impactradius-go.com/display-ad/26106-2123899" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://smilemakers.pxf.io/i/5597632/2123899/26106" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2130873/7443" target="_top" id="2130873">
  <img src="//a.impactradius-go.com/display-ad/7443-2130873" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130873/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, follow these steps:

1. Double-click on the **DenyRemovableDevices** value.
2. Set the **Value data** as **1** and then press **OK** to prevent others from installing storage devices into your PC. Alternatively, set the **Value data** as **0** and press **OK** to allow others to install removable storage devices on your PC.
3. Close the Registry Editor and restart your device to save these changes.

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
<li><a href="https://windows11.techidaily.com/a-comprehensive-guide-for-pcs-memory-tool-issues/"><u>A Comprehensive Guide for PC's Memory Tool Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-isdonedll-error-in-modern-windows-editions/"><u>Addressing ISDone.dll Error in Modern Windows Editions</u></a></li>
<li><a href="https://some-approaches.techidaily.com/apple-watch-an-ideal-gift-that-keeps-on-giving-with-easy-family-passdowns/"><u>Apple Watch: An Ideal Gift That Keeps on Giving with Easy Family Passdowns</u></a></li>
<li><a href="https://some-guidance.techidaily.com/beginners-guide-easy-steps-to-prepare-your-first-windows-laptop/"><u>Beginner's Guide: Easy Steps to Prepare Your First Windows Laptop</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-productivity-crafting-shortcuts-to-store-uwp-apps-on-windows/"><u>Boosting Productivity: Crafting Shortcuts to Store UWP Apps on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/clipchamp-patch-enable-installation-in-windows-11/"><u>ClipChamp Patch: Enable Installation in Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-and-where-to-find-a-shiny-stone-pokemon-for-lava-blaze-2-pro-drfone-by-drfone-virtual-android/"><u>How and Where to Find a Shiny Stone Pokémon For Lava Blaze 2 Pro? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-icloud-lock-from-iphone-14-pro-max-by-drfone-ios/"><u>How to Bypass iCloud Lock from iPhone 14 Pro Max</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-change-screen-order-in-pc/"><u>How to Change Screen Order in PC</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-navigating-the-financial-frontier-of-youtube-creators/"><u>In 2024, Navigating the Financial Frontier of YouTube Creators</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-the-game-changer-elevating-your-virtual-reality-film-quality/"><u>In 2024, The Game Changer Elevating Your Virtual Reality Film Quality</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-extended-display-setup-without-performance-hit/"><u>Mastering Extended Display Setup Without Performance Hit</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-improve-steam-download-speeds-on-windows/"><u>Strategies to Improve Steam Download Speeds on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-gaming-e84-fix-for-steam-windows/"><u>Streamline Your Gaming: E84 Fix for Steam Windows</u></a></li>
<li><a href="https://discover-excellent.techidaily.com/wie-man-die-aktivierung-der-solid-state-drive-ssd-in-den-systemvorlagen-bios-erledigt/"><u>Wie Man Die Aktivierung Der Solid State Drive (SSD) in Den Systemvorlagen (BIOS) Erledigt</u></a></li>
</ul></div>

