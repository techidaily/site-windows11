---
title: Tips for Restricting Removable Storage via Windows Settings
date: 2024-09-08T21:14:01.735Z
updated: 2024-09-15T21:57:41.165Z
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

 Now, follow these steps:

1. Double-click on the **DenyRemovableDevices** value.
2. Set the **Value data** as **1** and then press **OK** to prevent others from installing storage devices into your PC. Alternatively, set the **Value data** as **0** and press **OK** to allow others to install removable storage devices on your PC.
3. Close the Registry Editor and restart your device to save these changes.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135413/19272" target="_top" id="2135413">
  <img src="//a.impactradius-go.com/display-ad/19272-2135413" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135413/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-efficiently-record-your-screen-with-io-screen-recorder/"><u>[New] 2024 Approved Efficiently Record Your Screen with IO Screen Recorder</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-seamless-integration-utilizing-instagrams-music-stickers-expertise/"><u>[New] In 2024, Seamless Integration Utilizing Instagram's Music Stickers Expertise</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-capture-perfection-dive-into-top-12-websites-offering-stock-photos-without-cost-for-2024/"><u>[Updated] Capture Perfection Dive Into Top 12 Websites Offering Stock Photos Without Cost for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-boost-engagement-through-best-thumbnail-practices/"><u>[Updated] In 2024, Boost Engagement Through Best Thumbnail Practices</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-to-fix-google-hangouts-microphone-not-working/"><u>Easy to Fix Google Hangouts Microphone Not Working</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-part-of-the-touch-screen-not-working-on-vivo-s17e-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Part of the Touch Screen Not Working on Vivo S17e | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-expert-advice-for-capturing-evening-images/"><u>In 2024, Expert Advice for Capturing Evening Images</u></a></li>
<li><a href="https://windows11.techidaily.com/key-aspects-unraveling-windows-screen-savers/"><u>Key Aspects: Unraveling Windows Screen Savers</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-your-keyboard-use-with-winos-commands/"><u>Personalize Your Keyboard Use with WinOS Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-break-windows-stealthy-cam-policy/"><u>Techniques to Break Window's Stealthy Cam Policy</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722968172085-the-ideal-gas-law-relates-pressure-volume-temperature-and-the-number-of-moles-of-a-gas/"><u>The Ideal Gas Law Relates Pressure, Volume, Temperature, and the Number of Moles of a Gas</u></a></li>
<li><a href="https://technical-tips.techidaily.com/understanding-bing-the-comprehensive-guide/"><u>Understanding Bing: The Comprehensive Guide</u></a></li>
</ul></div>

