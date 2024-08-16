---
title: 9 Steps to Resolve Windows Hello Fingerprint Lockout
date: 2024-08-15T15:23:43.279Z
updated: 2024-08-16T15:23:43.279Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 9 Steps to Resolve Windows Hello Fingerprint Lockout
excerpt: This Article Describes 9 Steps to Resolve Windows Hello Fingerprint Lockout
keywords: Fix Windows Fingerprint,Unlock Windows Logon,Bypass Hello Lockout,Login After Lockout,Recover Fingerprint Error,Resolve Hello Failure,Reactivate Fingerprint Access
thumbnail: https://thmb.techidaily.com/5d29a63e1845651f830e0124c103033fe9ea8d7a1b11e86673f2ac375d1ce40d.jpeg
---

## 9 Steps to Resolve Windows Hello Fingerprint Lockout

 Using a fingerprint scanner is perhaps the most convenient way to log in to your Windows computer. It not only eliminates the need to type in a complex password or PIN every time you want to access your computer but also saves you time. But what if Windows Hello fingerprint authentication stops working on your computer?

 Fortunately, there are several ways to fix this annoying issue. So, let’s dive in and explore what you should do when Windows Hello fingerprint login isn’t working.

## 1\. Remove and Re-Register Your Fingerprint

 Your first step is to remove your Windows Hello fingerprint and register it again. This may sound basic, but it is one of the most straightforward ways to get your fingerprint reader to work again. Here are the steps you can follow.

1. Press **Win + I** to open the Settings app.
2. Head to **Accounts > Sign-in options**.
3. Under the **Windows Hello** section, click the **Remove** button.  
![Windows Sign-in Options window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Remove-Windows-Hello-Fingerprint-1.jpg)
4. Once removed, click the **Set up** button and follow the on-screen instructions to register your fingerprint again.

 If the issue persists or if you are unable to remove and re-add your fingerprint due to the "This option is currently unavailable" error on the Windows Hello page, there may be a problem with the Biometric drivers on your PC.

## 2\. Reinstall the Biometric Device Driver

 Biometric drivers on your PC help Windows communicate with your PC's fingerprint scanner. If these drivers are outdated or malfunctioning, you may run into problems.

 Most of the time, you can fix the problem by simply uninstalling and reinstalling the driver on your PC. Here’s how you can go about it.

1. Right-click on the **Start** icon to open the Power User menu.
2. Select **Device Manager** from the list.
3. Expand **Biometric devices**.  
![Biometric Driver selected in Device Manager window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Biometric-Driver-in-Device-Manager-1.jpg)
4. Right-click on your fingerprint scanner device and select **Uninstall device**.
5. Select **Uninstall** to confirm.

 Additionally, you should also expand the **Universal Serial Bus Controllers** section in the Device Manager and look for any entries with a yellow exclamation. If you find any, right-click on them one by one and select **Uninstall device** to remove them.

 Restart your PC after completing the above steps and check if the issue still occurs.

## 3\. Run the Hardware and Devices Troubleshooter

 Windows 10 and 11 include a number of [troubleshooters for resolving various system-related issues](https://www.makeuseof.com/windows-11-troubleshooters/). In this case, you should run the Hardware and Devices troubleshooter. It will scan your computer’s fingerprint scanner for any issues and attempt to fix them.

 Follow these steps to run the Hardware and Devices troubleshooter on Windows:

1. Press **Win + R** to open the Run dialog box.
2. Type **msdt.exe -id DeviceDiagnostic** in the Open field and press **Enter**.
3. In the Hardware and Devices window, click **Next**.  
![Hardware and Devices Troubleshooter Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Hardware-and-Devices-Troubleshooter-Window.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->

 Wait for Windows to diagnose any issues with your computer. If any issues are detected, follow the on-screen instructions to apply the recommended fixes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
## 4\. Turn Off Fast Startup

 Fast Startup is a handy Windows feature that speeds up your PC's boot time after shutdown. However, this feature might sometimes prevent Windows from loading properly. When this happens, the fingerprint scanner may not work on your Windows 10 or 11 PC.

 Use one of the many ways to [disable Fast Startup on your Windows computer](https://www.makeuseof.com/windows-11-turn-on-or-off-fast-startup/) and see if that gets the fingerprint scanner to work.

## 5\. Configure Windows Biometric Service to Start Automatically

 The Windows Biometric Service is an essential program for Windows Hello, as it captures and manages your fingerprint data. Ideally, the service should start automatically every time Windows boots. However, this might not happen if the service is not configured correctly.

 Use these steps to configure the Windows Biometric Service:

1. Open the **Services** app using the search menu.
2. Scroll down to locate the **Windows Biometric Service** on the list.
3. Right-click on it and select **Properties**.
4. Click the drop-down menu to change the **Startup type** to **Automatic**.
5. Hit **Apply** followed by **OK**.  
![Windows Biometric Service Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Windows-Biometric-Service-Properties.jpg)

 Restart your PC after this. Following that, you should be able to sign in with your fingerprint.

## 6\. Enable Biometrics via the Local Group Policy Editor

 Another reason why Windows Hello fingerprint sign-in may not work is if the feature is disabled from the Local Group Policy. It's important to note that Group Policy Settings are only available on Professional, Education, and Enterprise editions of Windows. If you are on Windows Home, you don't need to worry about this step.

 To enable fingerprint authentication via the Local Group Policy Editor, use these steps:

1. Press **Win + S** to open the search menu.
2. Type **gpedit.msc** in the search box and press **Enter** to [open the Local Group Policy Editor](https://www.makeuseof.com/tag/open-local-group-policy-editor-windows/).
3. Use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Components > Biometrics**.
4. Check if all the policies within the Biometrics folder are enabled. If not, double-click each policy one by one and set them to **Enabled**.  
![Biometric Policies in Local Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Local-Group-Policy-Editor-Window-1.jpg)

 Restart your PC one more time and check if the issue is still there.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Create a New User Account

 An issue with your current user account can also cause certain Windows features to stop working. This usually happens when your user account files get corrupted. If you suspect that to be the case, you can [create and switch to a new user account](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/) to fix the issue. Here’s how you can go about it.

1. Press **Win + I** to open the Settings app.
2. Head to **Accounts > Other users**.
3. Click the **Add account** button.
4. In the Microsoft account window, click on **I don't have this person's sign-in information** and follow the on-screen prompts to create a new user account.  
![Microsoft Account Sign In Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Microsoft-Account-Sign-In-Window.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Set up Windows Hello fingerprint login for your new user account and see if you can sign in with your fingerprint.

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 8\. Perform a System Restore

 If the fingerprint not working issue only occurred recently, you can use System Restore to revert Windows to a previous state. This will allow you to undo any changes that may have caused the issue. Note that this is only possible if you have previously [enabled System Restore on your PC](https://www.makeuseof.com/windows-11-enable-system-restore/).

 Follow these steps to perform a system restore on Windows:

1. Press **Win + S** to open the search menu.
2. Type **Create a restore point in the search box** and press **Enter**.
3. Under the **System Protection** tab, click on **System Restore**.
4. Click **Next**.
5. Select a restore point before the issue first appeared and hit **Next**.
6. Review all the details one more time before hitting **Finish**.  
![System Restore Dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/System-Restore-Dialog.jpg)
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Windows will restart and revert to the specified restore point. After that, the fingerprint should work as before.

## 9\. Install the Latest Windows Updates

 Microsoft regularly releases software updates for Windows 10 and Windows 11 to add new features, improve performance, and—crucially for our purposes—fix bugs. If the fingerprint not working issue is caused by a system bug, updating Windows to its most recent version should help.

 You can check for new updates by going to the **Windows Update** tab in the **Settings** app. Download and install any pending updates on your PC. Hopefully, this will resolve the issue.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fixing Windows Hello's Fingerprint Check

 It’s annoying when your PC's fingerprint scanner stops working all of a sudden. However, that shouldn’t force you to use your password or PIN to sign in to your computer.

 We hope one of the methods mentioned above has helped and you are able to sign in with your fingerprint again. However, if all else fails, you may want to consider resetting your Windows computer.

 Fortunately, there are several ways to fix this annoying issue. So, let’s dive in and explore what you should do when Windows Hello fingerprint login isn’t working.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-step-by-step-uploading-videos-to-instagram-on-desktop/"><u>[New] 2024 Approved  Step-by-Step  Uploading Videos to Instagram on Desktop</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-guide-audio-free-video-recording-methods-for-2024/"><u>[Updated] Guide  Audio-Free Video Recording Methods for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-pioneering-medical-messaging-in-digital-advertising/"><u>[Updated] Pioneering Medical Messaging in Digital Advertising</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-social-media-savvy-ig-filter-hits/"><u>[Updated] Social Media Savvy  IG Filter Hits</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-unparalleled-mac-capture-tools-assessed-for-2024/"><u>[Updated] Unparalleled Mac Capture Tools Assessed for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/chatgpt-secrets-revealed-perfect-your-tale-telling-skills-with-advanced-techniques/"><u>ChatGPT Secrets Revealed: Perfect Your Tale-Telling Skills with Advanced Techniques</u></a></li>
<li><a href="https://extra-tips.techidaily.com/choosing-between-the-dji-action-4-gopro-max-360-and-insta360-x3/"><u>Choosing Between the DJI Action 4, GoPro Max 360, and Insta360 X3</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/elevate-your-edits-10-essential-apps-for-instagram-videos/"><u>Elevate Your Edits  10 Essential Apps for Instagram Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-turn-off-hardware-assisted-gpgpus-on-widno/"><u>Essential Guide: Turn Off Hardware-Assisted GPGPUs on WIDNO</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-for-navigating-wpm-on-windows-11/"><u>Essential Tips for Navigating WPM on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-on-resolving-the-v22h2-windows-upgrade-not-installed-error/"><u>Expert Tips on Resolving the V22H2 Windows Upgrade Not Installed Error</u></a></li>
<li><a href="https://windows11.techidaily.com/finding-fixes-for-share-issue-on-nvidia-software/"><u>Finding Fixes for Share Issue on NVIDIA Software</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-activating-secure-file-confinement-on-win1011-os/"><u>Guide to Activating Secure File Confinement on Win10/11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/harmonizing-operations-combining-windows-11-and-tablet-for-peak-efficiency/"><u>Harmonizing Operations: Combining Windows 11 & Tablet for Peak Efficiency</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-bypass-printer-settings-on-windows-11/"><u>How to Bypass Printer Settings on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-connect-airpods-to-windows/"><u>How to Connect AirPods to Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-broken-video-files-of-oneplus-12-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair Broken video files of OnePlus 12 on Windows??</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-track-imei-number-of-lava-yuva-2-pro-through-google-earth-by-drfone-android/"><u>How To Track IMEI Number Of Lava Yuva 2 Pro Through Google Earth?</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-strategic-approach-to-dealing-with-youtube-copyright-claims/"><u>In 2024, Strategic Approach to Dealing With YouTube Copyright Claims</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-top-9-apple-iphone-6-plus-monitoring-apps-for-parental-controls-drfone-by-drfone-virtual-ios/"><u>In 2024, Top 9 Apple iPhone 6 Plus Monitoring Apps for Parental Controls | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/inside-the-workings-of-windows-snooze-systems/"><u>Inside the Workings of Windows Snooze Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/integrate-hardware-monitoring-seamlessly-using-windows-widgets/"><u>Integrate Hardware Monitoring Seamlessly Using Windows Widgets</u></a></li>
<li><a href="https://windows11.techidaily.com/keeping-windows-time-set-unaltered-by-users/"><u>Keeping Windows' Time Set Unaltered by Users</u></a></li>
<li><a href="https://windows11.techidaily.com/keyboard-command-compendium-for-ms-project-users/"><u>Keyboard Command Compendium for MS Project Users</u></a></li>
<li><a href="https://windows11.techidaily.com/launching-home-screen-in-windows-11-easily/"><u>Launching Home Screen in Windows 11 Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-the-absence-of-rockalldlldll-windows/"><u>Mending the Absence of Rockalldll.dll (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-pc-a-guide-to-spotting-huge-files-and-folders/"><u>Optimize Your PC: A Guide to Spotting Huge Files & Folders</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-silent-logins-on-windows-11-os/"><u>Overcoming Silent Logins on Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-slow-download-woes-in-battlenet-pcs/"><u>Overcoming Slow Download Woes in Battle.net PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/powertoys-guide-to-text-pasting-perfection/"><u>PowerToys' Guide to Text Pasting Perfection</u></a></li>
<li><a href="https://windows11.techidaily.com/preserve-your-files-as-you-boost-windows-drive/"><u>Preserve Your Files as You Boost Windows Drive</u></a></li>
<li><a href="https://windows11.techidaily.com/reinvigorating-your-snoozy-pcs-hibernate-mode/"><u>Reinvigorating Your Snoozy PC's Hibernate Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/rescue-a-crippled-windows-settings-application/"><u>Rescue a Crippled Windows Settings Application</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-steam-data-write-functionality-in-windows/"><u>Restoring Steam Data Write Functionality in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionize-your-windows-cars-with-these-five-essentials/"><u>Revolutionize Your Windows Cars with These Five Essentials</u></a></li>
<li><a href="https://windows11.techidaily.com/spotless-spooler-reset-tutorial/"><u>Spotless Spooler Reset Tutorial</u></a></li>
<li><a href="https://windows11.techidaily.com/stopping-autolock-on-your-computer-screen/"><u>Stopping AutoLock on Your Computer Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-correcting-0xc0000005-failures-on-pcs/"><u>Strategies for Correcting 0Xc0000005 Failures on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-revive-frozen-windows-terminal-apps/"><u>Strategies to Revive Frozen Windows Terminal Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/strategizing-onedrives-positioning-within-windows-directory-space/"><u>Strategizing OneDrive's Positioning Within Windows Directory Space</u></a></li>
<li><a href="https://windows11.techidaily.com/summoning-windows-11s-masked-search-facilitator/"><u>Summoning Windows 11'S Masked Search Facilitator</u></a></li>
<li><a href="https://windows11.techidaily.com/title-personalize-your-winos-desktop-space-configuration/"><u>Title: Personalize Your WINOS Desktop Space Configuration</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-missing-windows-update-installation/"><u>Troubleshooting Missing Windows Update Installation</u></a></li>
<li><a href="https://video-capture.techidaily.com/ultimate-mac-guide-to-saving-roblox-adventures/"><u>Ultimate Mac Guide to Saving Roblox Adventures</u></a></li>
<li><a href="https://windows11.techidaily.com/unobstructed-wireless-resurrecting-disconnected-networks/"><u>Unobstructed Wireless: Resurrecting Disconnected Networks</u></a></li>
<li><a href="https://windows11.techidaily.com/your-guide-to-selecting-a-new-window-home-or-premium-edition/"><u>Your Guide to Selecting a New Window : Home or Premium Edition</u></a></li>
</ul></div>
