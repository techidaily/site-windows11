---
title: Keeping Windows' Time Set Unaltered by Users
date: 2024-08-08T06:06:19.072Z
updated: 2024-08-09T06:06:19.072Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Keeping Windows' Time Set Unaltered by Users
excerpt: This Article Describes Keeping Windows' Time Set Unaltered by Users
keywords: Unchangeable Windows Timestamp,Windows Stable Time Settings,Maintain Windows System Time,Keeping User Time at Default,No Alteration Windows Time,Preserve Windows Time Standard,Prevent User Time Adjustments
thumbnail: https://thmb.techidaily.com/14a22e63716263e4dbf21490561e8b1d60bb16b34f9d12286d81f3b90aa95801.jpg
---

## Keeping Windows' Time Set Unaltered by Users

 You’re using your Windows device and notice something strange in the date and time settings. Someone has changed the settings without your knowledge or permission. This makes it difficult to stay on schedule with tasks and activities. In this guide, we’ll show how to stop anonymous users from changing date and time settings on Windows computers.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
## How To Prevent Users From Changing the Date and Time on Windows

 There are two ways to prevent users from changing Windows date and time. The first is to use Group Policy Editor, a system administration tool designed to control computer behavior in an organization. While the second way is to use Registry Editor, which allows you to modify Windows registry settings.

 For both methods, you need administrative access to the computer to change it. Once you’ve made the changes, nobody can alter the date and time settings. Let’s look at each method in more detail.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Use the Group Policy Editor

 If your computer is part of an organization and users often change the date and time, use Group Policy Editor to stop it. This will prevent those with limited access to the computer from altering the date and time. However, this method only works for Windows Pro, Enterprise, or Education Editions.

 So, if you have Windows Home Edition, this won’t work. In that case, you must first [activate the Group Policy Editor for Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). If it seems complicated, skip it and try the next solution instead.

 Follow these steps to prevent users from changing the date and time:

1. Press **Win + R** on your keyboard to open the Run window.
2. Type **gpedit.msc** in the text box and press Enter. This will open the Group Policy Editor window.
3. On the left side of the window, navigate to the following path:  
Computer Configuration > Administrative Templates > System > Locale Services
4. In the right-side pane, double-click on **Disallow user override of locale settings**.  
<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1896607/21553" target="_top" id="1896607"><img src="//a.impactradius-go.com/display-ad/21553-1896607" border="0" alt="" width="750" height="422"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1896607/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Disallow user override of locale settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/disallow-user-override-of-locale-settings.jpg)
5. In the pop-up window, check the **Enabled** radio button.
6. Then click **Apply** \> **OK** to save the changes.

 This will block anyone from changing the date and time settings on your computer. However, if you have administrative access to the computer, you can still alter the settings.

 If you want to revert to the default settings later, open Group Policy Editor again and change the value of Disallow user override of locale settings back to Not Configured or Disabled. This way, users can change the time and date again.

<!-- affiliate ads begin -->
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Tweak the Registry Editor

 If you’re using Windows Home Edition or have disabled the Group Policy Editor, use the Registry Editor to protect date and time settings. This method is more advanced and has a higher risk of system damage.

 In that case, [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it. Doing so will restore settings if something goes wrong.

 Follow these steps to stop users from changing the time and date via the registry:

1. [Open the Run command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** in the field and press Enter. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. In the Registry Editor window, navigate to the following path:  
HKEY_CURRENT_USER\Software\Policies\Microsoft\Control Panel\International\
4. If the International folder doesn’t exist, create one. To do that, right-click on Control Panel and select **New** \> **Key**. Name it **International**.
5. Then right-click on **International** and select New > DWORD (32-bit) Value.
6. Name the newly created value **PreventUserOverrides**.
7. Double-click on the **PreventUserOverrides** DWORD value.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Use Registry Editor to Prevent Users From Chaning date and time settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/use-registry-editor-to-prevent-users-from-chaning-date-and-time-settings.jpg)
8. In the pop-up window, change the Value data to **1** and click **OK**.

 Once you’ve made the changes, close the Registry Editor window and restart your computer.

 To undo this restriction, delete the **PreventUserOverrides** DWORD value from the registry or change the value to **0**. Doing so will enable users to change the time and date again.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## Stop Windows Time and Date Changes

 Now stop unauthorized users from changing the date and time settings on your Windows computer. This keeps your tasks and activities on track. If necessary, you can always undo this restriction.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-videos.techidaily.com/new-the-boomerang-edge-captivating-your-instagram-audience/"><u>[New] The Boomerang Edge  Captivating Your Instagram Audience</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-the-seamless-swivel-rotating-your-media-masterpieces-on-social-sites/"><u>[Updated] 2024 Approved  The Seamless Swivel  Rotating Your Media Masterpieces on Social Sites</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-in-2024-leveraging-likes-uploading-and-sharing-twitter-videos-to-snapchat/"><u>[Updated] In 2024, Leveraging Likes  Uploading & Sharing Twitter Videos to Snapchat</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-revolutionize-with-a-stroke-premier-tablet-draw-tools/"><u>2024 Approved  Revolutionize with a Stroke  Premier Tablet Draw Tools</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-the-archivists-guide-reviving-yesteryears-vhs-artistry-in-todays-editing-space/"><u>2024 Approved  The Archivist's Guide  Reviving Yesteryear’s VHS Artistry in Today's Editing Space</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-camera-app-malfunction-in-windows-11/"><u>Addressing Camera App Malfunction in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-the-not-an-empty-directory-alert-error-code-0x80070091-in-win11/"><u>Conquering the Not an Empty Directory Alert (Error Code: 0X80070091) in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-windows-upgrade-glitch-error-0xc1900101/"><u>Decoding Windows Upgrade Glitch: Error #0xC1900101</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/discover-the-reasons-behind-your-cars-failing-sound-system/"><u>Discover the Reasons Behind Your Car's Failing Sound System</u></a></li>
<li><a href="https://windows11.techidaily.com/distinguishing-between-hdd-and-ssd-drives-on-pc/"><u>Distinguishing Between HDD & SSD Drives on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-window-experience-mastering-the-start-menu/"><u>Enhance Your Window Experience: Mastering the Start Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-reinstalling-failing-drivers-in-win11-system/"><u>Guide to Reinstalling Failing Drivers in Win11 System</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-through-utorrent-sync-failures-on-windows-devices/"><u>Guiding Through uTorrent Sync Failures on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-xbox-game-pass-0x800700e9-error-in-windows-11-and-11/"><u>How to Fix the Xbox Game Pass 0X800700e9 Error in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-halt-microsoft-edge-icons-regularity/"><u>How to Halt Microsoft Edge Icons' Regularity</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stabilize-an-unstable-printer-on-windows/"><u>How to Stabilize an Unstable Printer on Windows</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-best-photo-and-video-display-apps-for-iphone-series-78/"><u>In 2024, Best Photo & Video Display Apps for iPhone Series 7/8</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-top-10-collage-apps-for-android-top-picks/"><u>In 2024, Top 10 Collage Apps for Android (Top Picks)</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/in-2024-virtual-makeup-mavens-top-youtube-creators/"><u>In 2024, Virtual Makeup Mavens  Top YouTube Creators</u></a></li>
<li><a href="https://windows11.techidaily.com/invisible-disk-hiding-tricks-in-win11w10/"><u>Invisible Disk Hiding Tricks in Win11/W10</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/mac-vlc-trimmer-the-best-way-to-shorten-videos-without-sacrificing-quality-for-2024/"><u>Mac VLC Trimmer The Best Way to Shorten Videos Without Sacrificing Quality for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/master-the-pairing-process-of-a-logitech-mouse-in-simple-steps/"><u>Master the Pairing Process of a Logitech Mouse in Simple Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/playnite-extension-virtual-games-collection/"><u>Playnite Extension: Virtual Games Collection</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-and-fixing-invalid-temp-directories-on-win11/"><u>Preventing and Fixing Invalid Temp Directories on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/prying-into-hidden-taskbar-analysis-tool-in-windows-11/"><u>Prying Into Hidden Taskbar Analysis Tool in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reestablish-wi-fi-masterful-solutions-for-windows-usb-adapters/"><u>Reestablish Wi-Fi: Masterful Solutions for Windows USB Adapters</u></a></li>
<li><a href="https://windows11.techidaily.com/resolve-poor-internet-access-in-windows-apps-now/"><u>Resolve Poor Internet Access in Windows Apps Now</u></a></li>
<li><a href="https://windows11.techidaily.com/reversal-of-extra-privileges-win11-standardization-tutorial/"><u>Reversal of Extra Privileges: Win11 Standardization Tutorial</u></a></li>
<li><a href="https://windows11.techidaily.com/revive-the-disappearing-link-top-9-methods-for-win-11s-bluetooth-woes/"><u>Revive the Disappearing Link: Top 9 Methods for Win 11'S Bluetooth Woes</u></a></li>
<li><a href="https://windows11.techidaily.com/simple-steps-for-stellar-cursors-in-windows-1011/"><u>Simple Steps for Stellar Cursors in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-addressing-undetectable-disks/"><u>Strategies for Addressing Undetectable Disks</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-reducing-browsing-impact-on-system-performance/"><u>Tips for Reducing Browsing Impact on System Performance</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-your-pc-effective-ways-to-resolve-kernel-inpage-errors/"><u>Troubleshooting Your PC: Effective Ways to Resolve Kernel Inpage Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11-secrets-with-devhome-insights/"><u>Unlocking Windows 11 Secrets with DevHome Insights</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ways-to-trade-pokemon-go-from-far-away-on-tecno-spark-20c-drfone-by-drfone-virtual-android/"><u>Ways to trade pokemon go from far away On Tecno Spark 20C? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-desktop-from-chaotic-to-customized-in-minutes/"><u>Win11 Desktop: From Chaotic to Customized, in Minutes</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-update-halted-quick-solutions-for-a-perfect-installation/"><u>Windows Update Halted: Quick Solutions for a Perfect Installation</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>