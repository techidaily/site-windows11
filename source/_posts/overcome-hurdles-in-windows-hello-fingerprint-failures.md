---
title: Overcome Hurdles in Windows Hello Fingerprint Failures
date: 2024-08-15T16:01:19.077Z
updated: 2024-08-16T16:01:19.077Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcome Hurdles in Windows Hello Fingerprint Failures
excerpt: This Article Describes Overcome Hurdles in Windows Hello Fingerprint Failures
keywords: Fix Windows Hello Errors,Bypass Fingerprint Lock,Overcoming Fingerprint Access,Solve Windows Biometric Issues,Troubleshoot Fingerprint Login,Resolving Fingerprint Failures,Enhance Windows Authenticate
thumbnail: https://thmb.techidaily.com/93116893fd34c4239c7adfcfb1ed2eb9afdd0b3ec4eb0ecc53392c491facd138.png
---

## Overcome Hurdles in Windows Hello Fingerprint Failures

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

<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->
## 3\. Run the Hardware and Devices Troubleshooter

 Windows 10 and 11 include a number of [troubleshooters for resolving various system-related issues](https://www.makeuseof.com/windows-11-troubleshooters/). In this case, you should run the Hardware and Devices troubleshooter. It will scan your computer’s fingerprint scanner for any issues and attempt to fix them.

 Follow these steps to run the Hardware and Devices troubleshooter on Windows:

1. Press **Win + R** to open the Run dialog box.
2. Type **msdt.exe -id DeviceDiagnostic** in the Open field and press **Enter**.
3. In the Hardware and Devices window, click **Next**.  
![Hardware and Devices Troubleshooter Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Hardware-and-Devices-Troubleshooter-Window.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->

 Wait for Windows to diagnose any issues with your computer. If any issues are detected, follow the on-screen instructions to apply the recommended fixes.

<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Turn Off Fast Startup

 Fast Startup is a handy Windows feature that speeds up your PC's boot time after shutdown. However, this feature might sometimes prevent Windows from loading properly. When this happens, the fingerprint scanner may not work on your Windows 10 or 11 PC.

 Use one of the many ways to [disable Fast Startup on your Windows computer](https://www.makeuseof.com/windows-11-turn-on-or-off-fast-startup/) and see if that gets the fingerprint scanner to work.

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->

 Restart your PC one more time and check if the issue is still there.

## 7\. Create a New User Account

 An issue with your current user account can also cause certain Windows features to stop working. This usually happens when your user account files get corrupted. If you suspect that to be the case, you can [create and switch to a new user account](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/) to fix the issue. Here’s how you can go about it.

1. Press **Win + I** to open the Settings app.
2. Head to **Accounts > Other users**.
3. Click the **Add account** button.
4. In the Microsoft account window, click on **I don't have this person's sign-in information** and follow the on-screen prompts to create a new user account.  
![Microsoft Account Sign In Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Microsoft-Account-Sign-In-Window.jpg)

 Set up Windows Hello fingerprint login for your new user account and see if you can sign in with your fingerprint.

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

 Windows will restart and revert to the specified restore point. After that, the fingerprint should work as before.

## 9\. Install the Latest Windows Updates

 Microsoft regularly releases software updates for Windows 10 and Windows 11 to add new features, improve performance, and—crucially for our purposes—fix bugs. If the fingerprint not working issue is caused by a system bug, updating Windows to its most recent version should help.

 You can check for new updates by going to the **Windows Update** tab in the **Settings** app. Download and install any pending updates on your PC. Hopefully, this will resolve the issue.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
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
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-experts-guide-to-best-terria-mods/"><u>[New] In 2024, Expert's Guide to Best Terria Mods</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-direct-conversion-convert-and-upload-mp3-songs-on-youtube/"><u>[Updated] 2024 Approved  Direct Conversion  Convert & Upload MP3 Songs on YouTube</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-integrated-iptv-channel-distribution/"><u>[Updated] 2024 Approved  Integrated IPTV Channel Distribution</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-laughter-logic-lab-for-2024/"><u>[Updated] Laughter Logic Lab for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-prime-facebook-extra-tools-secure-file-grabber-firefox-version-for-2024/"><u>[Updated] Prime Facebook Extra Tools  Secure File Grabber, Firefox Version for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-iphone-savvy-crafting-elegant-time-stretched-videos/"><u>2024 Approved  IPhone Savvy  Crafting Elegant Time-Stretched Videos</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/cerebral-advantages-of-multilingualism/"><u>Cerebral Advantages of Multilingualism</u></a></li>
<li><a href="https://video-capture.techidaily.com/cutting-edge-techniques-for-professional-obs-edits/"><u>Cutting-Edge Techniques for Professional OBS Edits</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-guide-brother-mfc-7360n-printer-drivers-for-windows-11-8-and-7-free-download/"><u>Easy Guide: Brother MFC-7360N Printer Drivers for Windows 11, 8 & 7 - Free Download</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-approaches-reviving-your-windows-11-search-feature/"><u>Effective Approaches: Reviving Your Windows 11 Search Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-use-of-notes-on-modern-windows-systems/"><u>Efficient Use of Notes on Modern Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-entry-to-sticky-notes-in-windows-11/"><u>Effortless Entry to Sticky Notes in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/effortlessly-experience-multiple-languages-on-windows-os/"><u>Effortlessly Experience Multiple Languages on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-pc-experience-with-smart-windows-app-restarts/"><u>Elevate Your PC Experience with Smart Windows App Restarts</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-disk-read-errors-on-windows-os/"><u>Eliminating Disk Read Errors on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-local-storage-for-onedrive-windows-guide/"><u>Enabling Local Storage for OneDrive - Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-images-on-windows-11-six-proven-scaling-strategies/"><u>Enhance Images on Windows 11: Six Proven Scaling Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-productivity-setting-up-windows-to-delete-files-automatically/"><u>Enhance Productivity: Setting Up Windows to Delete Files Automatically</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-typing-speed-mastering-windows-powertools/"><u>Enhance Typing Speed: Mastering Windows' PowerTools</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-system-navigating-the-smooth-windows-11-upgrade-process/"><u>Enhance Your System: Navigating the Smooth Windows 11 Upgrade Process</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-workflow-with-a-customized-windows-outlook-schedule/"><u>Enhance Your Workflow with a Customized Windows Outlook Schedule</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-gameplay-selecting-the-ideal-install-drives/"><u>Enhancing Gameplay: Selecting the Ideal Install Drives</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-underperforming-systems-with-intel-gpu-fixes/"><u>Enhancing Underperforming Systems with Intel GPU Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-windows-experience-finding-your-missing-system-tab/"><u>Enhancing Window's Experience: Finding Your Missing System Tab</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-wsl2-android-resource-management/"><u>Enhancing WSL2: Android Resource Management</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-complete-screen-images-with-snip-and-sketch-tips/"><u>Ensuring Complete Screen Images with Snip & Sketch Tips.</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-seamless-remote-device-connectivity-on-windows/"><u>Ensuring Seamless Remote Device Connectivity on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-directory-not-empty-fault-in-win11-os/"><u>Eradicating Directory Not Empty Fault in Win11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/escape-into-blissful-functionality-with-these-windows-fixes/"><u>Escape Into Blissful Functionality with These Windows Fixes</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/free-capture-precision-best-apps-for-windows-desktop-recording/"><u>Free Capture Precision  Best Apps for Windows Desktop Recording</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-corrupt-video-files-of-smart-8-pro-using-video-repair-utility-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>How to Fix corrupt video files of Smart 8 Pro using Video Repair Utility on Windows?</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-full-tutorial-to-bypass-your-honor-magic-5-face-lock-by-drfone-android/"><u>In 2024, Full Tutorial to Bypass Your Honor Magic 5 Face Lock?</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-learn-how-to-lock-stolen-your-iphone-13-properly-by-drfone-ios/"><u>In 2024, Learn How To Lock Stolen Your iPhone 13 Properly</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-revolutionize-tiktok-live-top-techniques-from-desktop-viewers/"><u>In 2024, Revolutionize TikTok Live  Top Techniques From Desktop Viewers</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/legally-safe-chants-and-tunes-the-ultimate-meditation-list-for-2024/"><u>Legally Safe Chants & Tunes - The Ultimate Meditation List for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/restoring-rightful-representation-amidst-misguided-chatter/"><u>Restoring Rightful Representation Amidst Misguided Chatter</u></a></li>
<li><a href="https://driver-install.techidaily.com/startech-driver-issues-in-windows-1087-solved/"><u>StarTech Driver Issues in Windows 10/8/7 [Solved]</u></a></li>
<li><a href="https://data-wizards.techidaily.com/video-file-non-playable-post-restoration/"><u>Video File Non-Playable Post Restoration</u></a></li>
<li><a href="https://tech-revival.techidaily.com/what-security-concerns-exist-for-chatgpt-users/"><u>What Security Concerns Exist for ChatGPT Users?</u></a></li>
</ul></div>
