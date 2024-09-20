---
title: Tips for Restricting Removable Storage via Windows Settings
date: 2024-09-13T21:26:41.556Z
updated: 2024-09-20T21:28:31.567Z
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
<a href="https://aligracehair.sjv.io/c/5597632/2080347/19272" target="_top" id="2080347">
  <img src="//a.impactradius-go.com/display-ad/19272-2080347" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080347/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-resources.techidaily.com/new-10-pro-tips-to-perfectly-piece-your-images/"><u>[New] 10 Pro Tips to Perfectly Piece Your Images</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-mastering-screencapture-essential-techniques/"><u>[New] 2024 Approved Mastering ScreenCapture Essential Techniques</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-art-of-digital-makeup-on-video-platforms/"><u>[Updated] The Art of Digital Makeup on Video Platforms</u></a></li>
<li><a href="https://location-fake.techidaily.com/6-ways-to-change-spotify-location-on-your-vivo-g2-drfone-by-drfone-virtual-android/"><u>6 Ways to Change Spotify Location On Your Vivo G2 | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/handheld-optimization-unveiled-x-ally-leads-way/"><u>Handheld Optimization Unveiled, X-Ally Leads Way</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-select-and-add-different-mail-sounds-in-gmail-settings/"><u>How to Select and Add Different Mail Sounds in Gmail Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-techniques-for-enhancing-comics-experience-on-win11/"><u>Innovative Techniques for Enhancing Comics Experience on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/is-split-screen-not-working-on-windows-heres-what-to-do/"><u>Is Split Screen Not Working on Windows? Here's What to Do</u></a></li>
<li><a href="https://windows11.techidaily.com/key-techniques-for-windowsapps-file-reveal/"><u>Key Techniques for WindowsApps File Reveal</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/latest-m-audio-fast-track-driver-downloads-for-windows-versions-including-11-7-8-and-81/"><u>Latest M-Audio Fast Track Driver Downloads for Windows Versions Including 11, 7, 8 & 8.1</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/making-the-most-of-your-television-with-fb-live-for-2024/"><u>Making the Most of Your Television with FB Live for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-to-protected-windowsapps-directory/"><u>Navigating to Protected WindowsApps Directory</u></a></li>
<li><a href="https://windows11.techidaily.com/powerful-tools-to-simultaneously-release-numerous-zip-archives/"><u>Powerful Tools to Simultaneously Release Numerous Zip Archives</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/top-5-applicazioni-di-lettura-video-migliori-su-mac-2020-incluse-app-di-controllo-remoto-apple-e-apple-tv/"><u>Top 5 Applicazioni Di Lettura Video Migliori Su Mac (2020): Incluse App Di Controllo Remoto Apple E Apple TV</u></a></li>
</ul></div>

