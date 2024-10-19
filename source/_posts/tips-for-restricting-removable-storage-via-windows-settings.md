---
title: Tips for Restricting Removable Storage via Windows Settings
date: 2024-10-13T17:41:34.220Z
updated: 2024-10-18T17:25:40.055Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tips for Restricting Removable Storage via Windows Settings
excerpt: This Article Describes Tips for Restricting Removable Storage via Windows Settings
keywords: Storage Limit Windows,Remove Device Control,Windows Security Tip,USB Accessibility Lock,Data Privacy Windows,Restrict Removable Storage,Secure Devices WIndows
thumbnail: https://thmb.techidaily.com/6bec6b49ef7ec1e5a2c1ba4a21123755124d462c63be6599c5bbe4007fea7d1f.jpg
---

## Tips for Restricting Removable Storage via Windows Settings

 Want to prevent others from stealing your PC data through removable storage devices? Or do you want to protect your device from harmful files contained on removable storage devices?

 In this article, we’ll explore how you can prevent others from installing removable storage devices on Windows. That way, your device won't read any removable storage devices without your permission. Lastly, we’ll also show you how to allow others to install specific removable storage devices.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Prevent Others From Installing Any Removable Storage Devices

 Let's start by checking out how you can prevent others from installing any removable storage device into your PC. You can do this using either the Local Group Policy Editor or the Registry Editor.

### Using the Local Group Policy Editor

![Using a Windows laptop on a brown desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Using-a-Windows-laptop-on-a-brown-desk.jpg)

<!-- affiliate ads begin -->
<span id="1155462">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1155462.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1155462">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1155462.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1155462%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1155462/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://aligracehair.sjv.io/c/5597632/2135405/19272" target="_top" id="2135405">
  <img src="//a.impactradius-go.com/display-ad/19272-2135405" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135405/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Using the Registry Editor

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

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
<a href="https://aligracehair.sjv.io/c/5597632/2080328/19272" target="_top" id="2080328">
  <img src="//a.impactradius-go.com/display-ad/19272-2080328" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080328/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, follow these steps:

1. Double-click on the **DenyRemovableDevices** value.
2. Set the **Value data** as **1** and then press **OK** to prevent others from installing storage devices into your PC. Alternatively, set the **Value data** as **0** and press **OK** to allow others to install removable storage devices on your PC.
3. Close the Registry Editor and restart your device to save these changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118320/7443" target="_top" id="2118320">
  <img src="//a.impactradius-go.com/display-ad/7443-2118320" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118320/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-blue.techidaily.com/new-accelerate-your-editing-with-these-10-pro-plugins-for-2024/"><u>[New] Accelerate Your Editing with These 10 Pro Plugins for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-simplify-your-tech-life-capture-and-store-youtube-streaming-effortlessly/"><u>[New] Simplify Your Tech Life Capture and Store YouTube Streaming Effortlessly</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-the-complete-guide-to-crafting-luts-in-3d-for-2024/"><u>[Updated] The Complete Guide to Crafting LUTs in 3D for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/boost-your-game-strategy-experience-the-best-free-voice-transformer-today-for-2024/"><u>Boost Your Game Strategy Experience the Best Free Voice Transformer Today for 2024</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-the-latest-nvidia-geforce-940mx-graphics-card-driver-downloads/"><u>Get the Latest NVIDIA GeForce 940MX Graphics Card Driver Downloads</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-disable-touch-screen-on-windows-10/"><u>How to Disable Touch Screen on Windows 10</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-oppo-reno-11-pro-5g-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Oppo Reno 11 Pro 5G If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/leading-dialogue-composers-circle-for-2024/"><u>Leading Dialogue Composer's Circle for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-telnet-activation-in-latest-windows-versions/"><u>Simplifying Telnet Activation in Latest Windows Versions</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-video-lags-in-chromes-youtube-viewing/"><u>Solving Video Lags in Chrome's YouTube Viewing</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-approach-enabling-wordpad-in-windows/"><u>Stepwise Approach: Enabling WordPad in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-avoid-perpetual-network-logon-errors/"><u>Strategies to Avoid Perpetual Network Logon Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/tech-tip-accessing-windows-11-sticky-notes-easily/"><u>Tech Tip: Accessing Windows 11 Sticky Notes Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-on-copy-and-paste-within-edges-protected-area-win-11-edition/"><u>Turn On Copy & Paste Within Edge's Protected Area, Win 11 Edition</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723015559920-windows-10-audio-problems-quick-solutions-for-bringing-back-the-sound/"><u>Windows 10 Audio Problems: Quick Solutions for Bringing Back the Sound!</u></a></li>
</ul></div>

