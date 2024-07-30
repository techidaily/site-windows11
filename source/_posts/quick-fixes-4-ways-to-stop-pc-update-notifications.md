---
title: "Quick Fixes: 4 Ways to Stop PC Update Notifications"
date: 2024-07-29T04:22:22.324Z
updated: 2024-07-30T04:22:22.324Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Quick Fixes: 4 Ways to Stop PC Update Notifications"
excerpt: "This Article Describes Quick Fixes: 4 Ways to Stop PC Update Notifications"
keywords: Pc No Updates Alerts,Stopping PC Updates,Eliminate PC Update Warnings,Disable Update Notifications,Fix PC Update Issues,Silence PC Update Alerts,Stop System Update Prompts
thumbnail: https://thmb.techidaily.com/a3a9fc7f1967fe6814b7bcf229ad0c8c09fecb880f152e3279a23ce2f1e6acd7.jpg
---

## Quick Fixes: 4 Ways to Stop PC Update Notifications

 By default, all your Office apps are set to update themselves automatically in the background. Although this approach keeps your Office apps updated with the latest features and improvements, these updates can sometimes overwhelm you or worse, cause new problems.

 Fortunately, there are several ways to disable automatic Office updates on Windows. Let's go over each of those methods one by one.

## 1\. How to Stop Automatic Office Updates via the Settings App

 Windows lets you check for any pending Office updates directly from the Settings app. This allows you to install Office updates along with other system updates. If you don’t want that, you can disable the**Receive updates for other Microsoft products** option in the Settings app. Here are the steps for the same.

1. Open the**Start menu** and click the**gear icon** to launch the Settings app.
2. Select**Windows Update** from the left sidebar.
3. Select**Advanced options** .
4. Disable the toggle next to**Receive updates for other Microsoft products** .  
![Stop Automatic Office Updates Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/stop-automatic-office-updates-using-the-settings-app.jpg)

## 2\. How to Stop Automatic Office Updates Using One of Its Apps

 You can also opt out of automatic Office updates by using one of its apps, such as Word or Excel. Here’s how you can go about it.

1. Open any Office app, such as Word.
2. Click the**File** menu in the top left corner.
3. Select**Account** from the left pane.
4. Click the**Update Options** drop-down menu in the Manage Account section and choose**Disable Updates** .
5. Select**Yes** to confirm.  
<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
![Stop Office Updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/stop-office-updates.jpg)

 Once you complete the above steps, your Office apps will not check for and install newer updates. Don't worry, you'll still be able to install updates manually.

 If you want to re-enable automatic updates later, use the same steps above and select**Enable Update** in the**Update Options** menu.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. How to Stop Automatic Office Updates Using the Group Policy Editor

 Another way to disable automatic Office updates is via the Group Policy Editor. It’s worth noting that you can only access the Group Policy Editor on Professional, Education, or Enterprise editions of Windows. If you're on Windows Home, be sure to check out [how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

 By default, the Group Policy Editor does not include any modules for managing Microsoft Office settings. So, in order to stop automatic Office updates via the Group Policy Editor, first, you’ll have to download and install Administrative Templates for Microsoft Office products. Here are the steps for the same.

1. Open up your web browser and head over to Microsoft Download Center to [download the Administrative Template files (ADMX/ADML) for Office apps](https://www.microsoft.com/en-us/download/details.aspx?id=49030) .  
![Download Office Administrative Templates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/download-office-administrative-templates.jpg)
2. Double-click the downloaded**EXE file** to run it.
3. Accept the license terms and click the**Continue** button.
4. The installer will prompt you for a location to extract the contents. Select an empty folder and hit**OK** .
5. Go to the location where you extracted the files and open the**admx** folder.
6. Select all the**admx files** and press**Ctrl + C** to copy them.
7. Head to**C: > Windows > PolicyDefinitions** folder.
8. Paste all the admx files in the**PolicyDefinitions** folder.  
![Copy Office ADMX files to PolicyDefinitions Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-office-admx-files-to-policydefinitions-folder.jpg)
9. Return to the folder where you extracted the files and open the**admx** folder again.
10. Open the**en-US** folder and copy all the**adml files** within.
11. Head to**C: > Windows > PolicyDefinitions** \>**en-US** folder and paste all the**adml files** .  
![Copy Office ADML files to PolicyDefinitions Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-office-adml-files-to-policydefinitions-folder.jpg)

 After completing the above steps, you’re all set to disable automatic Office updates via the Group Policy Editor. Here are the steps you can follow.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the box and select the first result that appears. This will open the Local Group Policy Editor.
3. Use the left pane to navigate to **Local Computer Policy > Computer Configuration > Administrative Templates > Microsoft Office 2016 > Updates** .
4. Double-click the**Enable Automatic Updates** policy on your right.  
<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Stop Automatic Office Updates Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/stop-automatic-office-updates-using-group-policy-editor.jpg)
5. Select the**Disabled** option.
6. Hit**Apply** followed by**OK** .
7. Next, press**Win + R** to open the Run dialog.
8. Type**cmd** in the text box and press**Ctrl + Shift + Enter** to [open Command Prompt with administrative privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
9. Type**gpupdate /force** in the console and hit**Enter** to apply the Group Policy changes.

 If you want to re-enable automatic updates for Office apps later, simply set the**Enable Automatic Updates** policy to**Enabled** .

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. How to Stop Automatic Office Updates With the Registry Editor

 You can also use the Registry Editor to make the above policy change and disable automatic Office updates on your computer. Since Registry Editor holds important settings for Windows and its apps, you should only use this method if you’re comfortable editing the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) .

 If you decide to use this method, make sure you back up all the registry files or create a restore point beforehand. If you need help, refer to our guide on [how to create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) and follow the steps outlined there.

 Once you've done that, use the following steps to disable automatic Office updates via the Registry Editor.

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **Computer > HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft** .  
![Registry Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor.jpg)
5. Right-click the**Microsoft** key and select**New > Key** .

1. Rename the key as**Office** .
2. Right-click on the**Office** key and select**New > Key** .
3. Rename the key as**16.0** .
4. Right-click the**16.0** key and select**New > Key** .
5. Rename the key as**Common** .
6. Within the**Common** key, create another key named**OfficeUpdate** .
7. Right-click the**OfficeUpdate** key and select**New > DWORD (32-bit) Value** . Name this new DWORD**EnableAutomaticUpdates** .
8. Double-click**EnableAutomaticUpdates** DWORD and set its**Value Data** to**0** .
9. Click**OK** .  
<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Turn Off Automatic Office Updates Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-off-automatic-office-updates-using-registry-editor.jpg)

 After completing the above steps, restart your computer. Following that, Office apps won’t update automatically on your computer. If you want to undo this change, open the Registry Editor again and delete the**EnableAutomaticUpdates** DWORD.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## Stop Automatic Office Updates on Windows

 It is almost always preferable to keep your Office apps up to date so that you can benefit from new features and security updates. Hence, if you disable automatic Office updates for some reason, don’t forget to check for new updates manually every once in a while.


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
<li><a href="https://youtube-tips.techidaily.com/024-approved-captivate-audiences-unveiling-secrets-for-striking-youtube-banners/"><u>[New] 2024 Approved  Captivate Audiences  Unveiling Secrets for Striking YouTube Banners</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-conquer-chrome-multitasking-learn-to-utilize-pip-effectively/"><u>[New] Conquer Chrome Multitasking  Learn to Utilize PIP Effectively</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-beyond-glitter-the-pure-reality-of-recordcast-experience/"><u>[New] In 2024, Beyond Glitter  The Pure Reality of RecordCast Experience</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-instagram-video-reduction-tips-for-mac-users/"><u>[New] Instagram Video Reduction Tips for Mac Users</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-unlock-the-full-potential-of-your-reels-with-these-6-essentials/"><u>[Updated] 2024 Approved  Unlock the Full Potential of Your Reels with These 6 Essentials</u></a></li>
<li><a href="https://windows11.techidaily.com/5-key-fixes-to-stop-rpc-failures-in-windows/"><u>5 Key Fixes to Stop RPC Failures in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/best-digital-journals-navigate-your-pen-for-windows/"><u>Best Digital Journals: Navigate Your Pen for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/defining-windows-corners-straighten-them-out/"><u>Defining Windows' Corners: Straighten Them Out</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-non-response-from-printmanagement-msc-errors/"><u>Eliminating Non-Response From 'Printmanagement' MSC Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/expanding-linux-horizons-through-windows-apps/"><u>Expanding Linux Horizons Through Windows Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-update-issue-with-error-0x8024800c/"><u>Fixing Windows Update Issue with Error 0X8024800C</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/how-to-add-a-streamline-of-youtube-playlists-on-your-website-for-2024/"><u>How to Add a Streamline of YouTube Playlists on Your Website for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-double-clicking-not-opening-folders-on-windows-1110/"><u>How to Fix Double-Clicking Not Opening Folders on Windows 11/10</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-reset-your-oppo-lock-screen-password-by-drfone-android/"><u>How to Reset your Oppo Lock Screen Password</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-architecting-an-inspiring-tiktok-conclusion/"><u>In 2024, Architecting an Inspiring TikTok Conclusion</u></a></li>
<li><a href="https://windows11.techidaily.com/key-to-performance-enhancement-with-windows-lav-filters-use/"><u>Key to Performance Enhancement with Window's LAV Filters Use</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-use-of-toolbars-an-insight-into-mspcm-windows-11/"><u>Mastering the Use of Toolbars: An Insight Into MSPCM, Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-user-isolation-for-security-in-win-11/"><u>Mastering User Isolation for Security in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/peeling-back-the-layers-of-runtime-brokers-on-pcs/"><u>Peeling Back the Layers of Runtime Brokers on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-vmwares-non-boot-windows-11-mistakes/"><u>Preventing VMware's Non-Boot Windows 11 Mistakes</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-bypassing-the-components-not-found-issue-on-w10w11/"><u>Quick Fix: Bypassing the Components Not Found Issue on W10/W11</u></a></li>
<li><a href="https://network-issues.techidaily.com/ready-os-post-com-firmware-fixes/"><u>Ready OS Post-COM Firmware Fixes</u></a></li>
<li><a href="https://extra-skills.techidaily.com/sleepy-story-vids-assessment-and-overview-for-2024/"><u>Sleepy Story Vids  Assessment & Overview for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-screen-settings-with-these-10-win-11-tricks/"><u>Streamline Your Screen Settings with These 10 Win 11 Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-to-mask-dimming-functionality-in-system-preferences/"><u>Tactics to Mask Dimming Functionality in System Preferences</u></a></li>
<li><a href="https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-vivo-x90s-drfone-by-drfone-virtual-android/"><u>Thinking About Changing Your Netflix Region Without a VPN On Vivo X90S? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/top-10-password-cracking-tools-for-nubia-red-magic-8s-proplus-by-drfone-android/"><u>Top 10 Password Cracking Tools For Nubia Red Magic 8S Pro+</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-the-red-x-on-your-pcs-file-system/"><u>Understanding the Red X on Your PC's File System</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-your-devices-through-windows-live-panels/"><u>Understanding Your Devices Through Windows Live Panels</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-speed-tackling-torrent-stagnation-in-windows/"><u>Unlocking Speed: Tackling Torrent Stagnation in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unmasking-wintoys-your-essential-introduction-to-an-underused-powerhouse-tool-in-windows/"><u>Unmasking WinToys: Your Essential Introduction to an Underused Powerhouse Tool in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-access-denial-in-windows-11-with-these-5-steps/"><u>Unraveling Access Denial in Windows 11 with These 5 Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-cause-of-unregistered-packages-in-windows/"><u>Unraveling the Cause of Unregistered Packages in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/utilizing-portable-gpus-no-internal-graphic-needed/"><u>Utilizing Portable GPUs: No Internal Graphic Needed</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-tips-implementing-scheduled-file-purging/"><u>Win11 Tips: Implementing Scheduled File Purging</u></a></li>
</ul></div>
