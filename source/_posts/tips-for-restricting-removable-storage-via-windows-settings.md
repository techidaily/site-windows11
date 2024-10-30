---
title: Tips for Restricting Removable Storage via Windows Settings
date: 2024-10-29T16:22:45.567Z
updated: 2024-10-30T16:12:20.854Z
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
<a href="https://bluettius.sjv.io/c/5597632/2139114/17108" target="_top" id="2139114">
  <img src="//a.impactradius-go.com/display-ad/17108-2139114" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139114/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The Local Group Policy Editor (LGPE) is a reliable tool for troubleshooting system errors. Interestingly, you can also use it for other tasks such as [preventing others from changing your Windows desktop background](https://www.makeuseof.com/stop-others-change-windows-desktop-background/).

 Now, here’s how to use the LGPE to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **Computer Configuration > Administrative Templates > System > Device Installation > Device Installation Restrictions**.
4. Double-click on the **Prevent installation of removable devices** option on the right-hand side.

![Clicking the prevent installation of removable devices option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-prevent-installation-of-removable-devices-option.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997690/19272" target="_top" id="1997690">
  <img src="//a.impactradius-go.com/display-ad/19272-1997690" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997690/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Select **Enabled** on the next screen to prevent others from installing removable storage devices into your PC. Alternatively, select **Disabled** or **Not Configured** to restore the default settings.

 Finally, press **Apply** and then press **OK** to save these changes.

 Struggling to access the LGPE on Windows Home? There are a few tricks you can apply to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). But if that sounds complicated to you, then skip to the Registry Editor method.

### Using the Registry Editor

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934258/19272" target="_top" id="1934258">
  <img src="//a.impactradius-go.com/display-ad/19272-1934258" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934258/19272" style="position:absolute;visibility:hidden;" border="0" />
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

 Now, follow these steps:

1. Double-click on the **DenyRemovableDevices** value.
2. Set the **Value data** as **1** and then press **OK** to prevent others from installing storage devices into your PC. Alternatively, set the **Value data** as **0** and press **OK** to allow others to install removable storage devices on your PC.
3. Close the Registry Editor and restart your device to save these changes.

<!-- affiliate ads begin -->
<span id="1977006">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977006.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977006">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977006.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977006%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977006/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-guidance.techidaily.com/new-master-the-art-of-clean-up-a-guide-to-bg-elimination/"><u>[New] Master the Art of Clean-Up A Guide to BG Elimination</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-audio-anomalies-top-disruptive-apps-on-the-go/"><u>[Updated] Audio Anomalies Top Disruptive Apps on the Go</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-insta-share-tips-for-posting-youtube-videos-for-2024/"><u>[Updated] Insta-Share Tips for Posting YouTube Videos for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-minimca-homes-the-ultimate-guide-for-entry-level-builders-for-2024/"><u>[Updated] MiniMCA Homes The Ultimate Guide for Entry-Level Builders for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-science-of-attractiveness-building-engaging-audio-introductions/"><u>2024 Approved The Science of Attractiveness Building Engaging Audio Introductions</u></a></li>
<li><a href="https://win-workspace.techidaily.com/comment-activer-et-utiliser-efficacement-norton-ghost-dans-differents-environnements-windows-710811/"><u>Comment Activer Et Utiliser Efficacement Norton Ghost Dans Différents Environnements Windows (7/10/8/11)</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/essential-iphoneandroid-apps-for-aspiring-creators/"><u>Essential iPhone/Android Apps for Aspiring Creators</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-unlisted-device-detected-error-in-win1011/"><u>Fixing Unlisted Device Detected Error in Win10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/insights-into-ftdibussys-the-implications-for-windows-memory-safety/"><u>Insights Into ftdibus.sys: The Implications for Windows Memory Safety</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-inaudible-audio-on-wireless-devices/"><u>Resolving Inaudible Audio on Wireless Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/revamping-your-networks-first-line-of-defense/"><u>Revamping Your Network's First Line of Defense</u></a></li>
<li><a href="https://windows11.techidaily.com/the-audio-advantage-top-4-programs-for-surpassing-windows-100-limit/"><u>The Audio Advantage: Top 4 Programs for Surpassing Windows' 100% Limit</u></a></li>
<li><a href="https://windows11.techidaily.com/the-easy-switch-for-classic-gaming-in-the-windows-photo-hub/"><u>The Easy Switch for Classic Gaming in the Windows Photo Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-compressed-storage-on-windows-11/"><u>Unlocking Compressed Storage on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-successful-remote-steam-connectivity/"><u>Unlocking Successful Remote Steam Connectivity</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-2024-approved-silencing-the-chatter-essential-methods-for-muting-tiktok-audio/"><u>Updated 2024 Approved Silencing the Chatter Essential Methods for Muting TikTok Audio</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-google-play-services-keeps-stopping-on-motorola-razr-40-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What to Do if Google Play Services Keeps Stopping on Motorola Razr 40 | Dr.fone</u></a></li>
</ul></div>

