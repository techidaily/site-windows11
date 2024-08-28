---
title: Steps for Securing Computer Against Unauthorized USB Clip Attacks
date: 2024-08-27T16:12:59.806Z
updated: 2024-08-28T16:12:59.806Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps for Securing Computer Against Unauthorized USB Clip Attacks
excerpt: This Article Describes Steps for Securing Computer Against Unauthorized USB Clip Attacks
keywords: USB Security Measures,Preventing Unauthorized Access,Protect Computer USBs,Defending Against Clip Hacking,Secure USB Devices,USB Data Breach Safety,Counter USB Threats
thumbnail: https://thmb.techidaily.com/3bbc4ff17b35bac37e3335e5a66057aab2f13c2b088afea3c5a850da277e1159.jpg
---

## Steps for Securing Computer Against Unauthorized USB Clip Attacks

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
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Using the Registry Editor

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
 Now, follow these steps:

1. Double-click on the **DenyRemovableDevices** value.
2. Set the **Value data** as **1** and then press **OK** to prevent others from installing storage devices into your PC. Alternatively, set the **Value data** as **0** and press **OK** to allow others to install removable storage devices on your PC.
3. Close the Registry Editor and restart your device to save these changes.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-capturecraftsman-the-ultimate-guide-to-instagram-media-size-adjustment/"><u>[New] 2024 Approved  CaptureCraftsman  The Ultimate Guide to Instagram Media Size Adjustment</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-the-monetary-reality-of-being-a-podcaster/"><u>[New] The Monetary Reality of Being a Podcaster</u></a></li>
<li><a href="https://youtube-web.techidaily.com/he-ultimate-guide-for-transforming-youtube-videos-into-animated-gifs/"><u>[New] The Ultimate Guide for Transforming YouTube Videos Into Animated GIFs</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-unlocking-virtual-meetings-googles-facetime-tutorial/"><u>[Updated] 2024 Approved  Unlocking Virtual Meetings  Google's Facetime Tutorial</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-best-practices-selecting-among-top-9-free-logo-designers-for-2024/"><u>[Updated] Best Practices  Selecting Among Top 9 Free Logo Designers for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-mastering-low-volume-transitions-within-fl-studio/"><u>[Updated] Mastering Low-Volume Transitions Within FL Studio</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-framing-photos-and-videos-playing-with-text-deformation/"><u>2024 Approved  Framing Photos & Videos  Playing With Text Deformation</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/efficient-setup-ps4-streaming-and-recording-via-obs/"><u>Efficient Setup  PS4 Streaming and Recording via OBS</u></a></li>
<li><a href="https://windows11.techidaily.com/expeditiously-mute-windows-11-pings/"><u>Expeditiously Mute Windows 11 Pings</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/expert-guide-to-enhancing-video-controls-and-performance-for-2024/"><u>Expert Guide to Enhancing Video Controls and Performance for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/expert-recommendations-the-best-handhited-hd-players/"><u>Expert Recommendations  The Best Handhited HD Players</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-semaphore-timeout-period-has-expired-error-0x80070079-in-windows-1110/"><u>How to Fix the “Semaphore Timeout Period Has Expired” Error 0X80070079 in Windows 11/10</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-remove-the-onedrive-icon-from-file-explorer-in-windows-11/"><u>How to Remove the OneDrive Icon From File Explorer in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-set-up-your-own-keyboard-shortcuts-in-windows-11/"><u>How to Set Up Your Own Keyboard Shortcuts in Windows 11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-optimize-youtube-watch-experience-boostslow-down-feature-usage/"><u>In 2024, Optimize YouTube Watch Experience  Boost/Slow Down Feature Usage</u></a></li>
<li><a href="https://windows11.techidaily.com/integrating-ios-calendar-with-windows-a-practical-guide/"><u>Integrating iOS Calendar with Windows: A Practical Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/merge-functionality-and-elegance-in-windows-10plus/"><u>Merge Functionality and Elegance in Windows 10+</u></a></li>
<li><a href="https://extra-information.techidaily.com/mobile-blur-apps-to-soften-images/"><u>Mobile Blur Apps to Soften Images</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-fixed-windows-update-blockades/"><u>Navigating Fixed Windows Update Blockades</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-access-to-command-prompt-easily-set-up-shortcuts/"><u>Quick Access to Command Prompt: Easily Set Up Shortcuts</u></a></li>
<li><a href="https://windows11.techidaily.com/removing-curved-edges-from-windows-11/"><u>Removing Curved Edges From Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-for-windows-11-dolby-atmos-audio/"><u>Step-by-Step for Windows 11: Dolby Atmos Audio</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/streamline-your-virtual-sessions-with-these-top-10-tools/"><u>Streamline Your Virtual Sessions with These Top 10 Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-reversing-loadlibrary-misload-on-windows/"><u>Techniques for Reversing LoadLibrary Misload on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-hidden-power-of-windows-firewall-management/"><u>The Hidden Power of Windows' Firewall Management</u></a></li>
<li><a href="https://windows11.techidaily.com/the-quickest-way-to-shift-your-windows-qbittorrent-software/"><u>The Quickest Way to Shift Your Windows qBittorrent Software</u></a></li>
<li><a href="https://windows11.techidaily.com/the-transformation-ai-integration-into-windows-11/"><u>The Transformation: AI Integration Into Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-address-steams-file-privilege-problem-in-win11/"><u>Tips to Address Steam's File Privilege Problem in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/turbocharge-your-windows-printer-with-quick-fixes/"><u>Turbocharge Your WIndows Printer with Quick Fixes</u></a></li>
<li><a href="https://article-tips.techidaily.com/unlock-the-full-potential-of-zoom-in-your-xbox-setup/"><u>Unlock the Full Potential of Zoom in Your Xbox Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-mechanics-of-windows-11s-efficient-file-safety-measures/"><u>Unveiling the Mechanics of Windows 11'S Efficient File Safety Measures</u></a></li>
<li><a href="https://windows11.techidaily.com/what-to-do-when-your-recent-discord-updates-breakdown-on-windows/"><u>What to Do When Your Recent Discord Updates Breakdown on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/winwm-energy-hack-lowering-gpu-draw-in-windows-11/"><u>WinWM Energy Hack: Lowering GPU Draw in Windows 11</u></a></li>
</ul></div>
