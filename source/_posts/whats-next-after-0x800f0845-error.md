---
title: What's Next After 0X800f0845 Error?
date: 2024-08-31T22:16:33.695Z
updated: 2024-09-01T22:16:33.695Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes What's Next After 0X800f0845 Error?
excerpt: This Article Describes What's Next After 0X800f0845 Error?
keywords: X800F0845ErrorSolutions,Fixing0X800F0845,OSError0X800F0845Help,ErrorCode0X800F0845Tips,0X800f0845ErrorTroubleshoot,Resolve0X800F0845Error,UnderstandingOSError0X800F0845
thumbnail: https://thmb.techidaily.com/c08cfb9fc52b90a12972e5ec144ec0c7f63bc215d0f41358268b867a2994d1b8.jpg
---

## What's Next After 0X800f0845 Error?

 Windows Update brings new features to your PC while installing important security updates and bug fixes. So it's vital to keep your system updated to work and play hassle-free on Windows.

 However, some unexpected errors occur, resulting in updates failing to install on your system. And 0x800f0845 is one such error.

 But you can get past the 0x800f0845 error and continue to install essential updates by trying the following fixes.

## What Is the Windows Update 0x800f0845 Error?

 0x800f0845 is an error that mostly occurs while installing cumulative updates on your Windows PC. You may experience this update error if Windows components and services are corrupted or if there are damaged or missing system files. Sometimes, this error happens by the interactions of third-party apps with the system apps.

 You may not come to know of the error while updating, as Windows will appear to be updating normally with messages of the updates installing—such as**Updates are underway. Please keep your computer on** .

 However, just before your PC reboots, the following message on your computer screen may appear: **Something didn't go as planned. No need to worry—undoing changes. Please keep your computer on** . This message indicates a problem with the update. When your computer restarts, the cumulative update would have failed to install.

 You can check for the same by going to**Settings > Windows Update** and then clicking**Update history** . In**Update history** , you will get the message that the cumulative update has failed to install with the error code**0x800f0845** like the screenshot below.

![0x800f0845 Error in Windows Update History](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/0x800f0845-error-update-history.jpg)

 So what can you do now? Cumulative updates are quality updates, so these must be installed. Fortunately, as there are ways to get past the 0x800f0845 error and install the failed updates.

## 1\. Run the Windows Update Troubleshooter

 It's always better to try fixing Windows update errors first by using the Windows Update Troubleshooter. It scans your PC for problems, attempts to resolve them, and then applies the fixes.

1. Right-click the**Windows icon** on the taskbar and select**Settings** . Or use the[many ways to open Settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. On the left pane in**Settings** , click**System** . On the**System** page, click**Troubleshoot** on the right pane.
3. In the**Troubleshoot** page, select**Other troubleshooters** .  
![Select Other Trouble-shooters in Troubleshoot Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/troubleshoot-other-trouble-shooters.jpg)
4. Then click**Run** on the**Windows Update** troubleshooter.  
![Run Windows Update Troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-windows-update-troubleshooter.jpg)

 The Windows Update troubleshooter will automatically run its scans to diagnose problems. After troubleshooting completes, you'll get the message that changes have been made to your system and you should try attempting the tasks you were doing earlier.

![Windows Update Troubleshooting Complete Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-update-troubleshooting-complete.jpg)

 So close the troubleshooter and restart your computer. Then try updating Windows again and check if the failed update gets installed.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
## 2\. Temporarily Disable Your Antivirus Software

 Sometimes, third-party antivirus installed on your PC may cause problems when you're updating Windows. So try temporarily disabling it and then installing updates.

 Your antivirus may have options to disable it temporarily. Or right-click on the Windows icon on the taskbar and select**Task Manager** .

 In**Task Manager** , click the**Startup** tab and look for your antivirus software. Then, right-click on it and choose**Disable** .

Try updating Windows now and see if the update gets installed.

## 3\. Run the System File Checker and the DISM Tool

 Corrupted Windows system files could also be the cause of the 0x800f0845 error. To scan, repair, and replace such damaged files, run the System File Checker or SFC scan.

 And if the SFC doesn't work properly, and can’t repair your system files, you should run the DISM or Deployment Image Servicing and Management tool. DISM is a command-line tool that can be used to service and repair Windows images, including those used for Windows Recovery and Windows Setup.

 To know how to run the SFC and DSIM, you can explore our guide on[CHKSDK, SFC, and DISM, and how they work](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) .

 These scans will take a few minutes to run. If the 0x800f0845 error was caused by corrupted files, it should have been fixed. So try updating Windows again.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
## 4\. Reset Windows Update Components

 Error 0x800f0845 could occur if some Windows Update components have got corrupted. You could reset Windows components to get the Windows update running fine again. Here's how:

[Open Windows Terminal](https://www.makeuseof.com/windows-11-open-windows-terminal/) using one of the many ways. Or type**Windows Terminal** in**Windows Search** . Then, right-click**Windows Terminal** under**Best match** and select**Run as administrator.**

 First, you need to stop the update services. In the Windows Terminal window, type the following four commands one by one, making sure that you press**enter** after each command:

`net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc`

 Then to set up a new SoftwareDistribution folder, you need to rename it. So enter the following command and press**enter** :

`Ren %systemroot%\SoftwareDistribution SoftwareDistribution.old`

 Next, rename the catroot2 folder for Windows to set up a new one. Type the following command and press**enter** :

`Ren %systemroot%\System32\catroot2 catroot2.old`

 Finally, you need to restart the stopped services. Type the following four commands one after the other, while pressing**enter** after each command:

`net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`

 Once you have run all the commands, the update error should have got fixed. Restart your PC and try installing the updates again.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
## 5\. Install the Update Manually via the Microsoft Update Catalog

 What if none of the above solutions works for you? No worries, just install the update manually from the Microsoft Update Catalog.

1. Open your browser to search for and visit the[Microsoft Update Catalog website](https://www.catalog.update.microsoft.com/Home.aspx) .
2. Copy the number of the cumulative update or any other update that failed to install from the**Windows Update history** page. Type the update number in the**Search bar** on the**Microsoft Update Catalog** page and hit the**Search** button.  
![Search For Update On Microsoft Update Catalog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/search-on-microsoft-update-catalog.jpg)
3. The matching updates will show up on the results page. Check the update that applies to your Windows PC—whether it is for Windows 10 or 11, and whether it is for an ARM64-based system or an x64-based system.  
![Microsoft Update Catalog Search Results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/microsoft-update-catalog-search-results.jpg)
4. To know the build of your PC, search for**About** in**Windows Search** and click on**About your PC** under**Best match** . In the**About** page, under**Device specifications** , check your**System type** to know whether it is x64-based or another.  
![Device Specifications in About Your PC Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/screenshot-10065.jpg)  
 Select the update that matches your system in Microsoft Update Catalog and click the**Download** button.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
5. The**Download** page will open with the file download link. Click on the link to download the update.  
![Download Update From Microsoft Update Catalog Link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/download-update-from-link.jpg)
6. Double-click on the downloaded file to open the**Windows Update Standalone Installer** and click**Yes** when prompted to download the update.  
![Windows Update Standalone Installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-update-standalone-installer.jpg)  
 The update will begin installing and this could take some time.  
![Cumulative Update Installation in Progress](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/cumulative-update-installing-progress.jpg)  
 Finally, the**Installation complete** window will appear.  
![Click Restart Now to Complete Installation](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restart-now-to-complete-installation.jpg)
7. Just click the**Restart Now** button to complete the installation.
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
8. After your PC restarts, go to the**Windows Update history** page.  
![Cumulative Update Successfully Installed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/cumulative-update-successfully-installed.jpg)  
 The update that failed to install would have been successfully installed—as you can see in the screenshot above, the KB5023706 update was installed.
<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Stay Updated for a Secure and Smooth Windows Experience

 Update errors like 0x800fo845 can be annoying, especially when you've spent considerable time on an update that fails to install. Try the fixes discussed above to install important updates and enjoy a smooth, secure, and hassle-free Windows experience.


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
<li><a href="https://youtube-tips.techidaily.com/utting-edge-studio-lights-for-online-filmmakers/"><u>[New] Cutting-Edge Studio Lights for Online Filmmakers</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-mastering-online-video-earnings/"><u>[New] Mastering Online Video Earnings</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-channel-transformation-optimal-video-concepts-to-elevate-creativity/"><u>[Updated] 2024 Approved  Channel Transformation  Optimal Video Concepts to Elevate Creativity</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-steps-to-cure-intermittent-obs-frames/"><u>[Updated] 2024 Approved  Steps to Cure Intermittent OBS Frames</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-the-comprehensible-guide-to-leveraging-videos-for-social-media-success-for-2024/"><u>[Updated] The Comprehensible Guide to Leveraging Videos for Social Media Success for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unveiling-windows-11s-hidden-know-how-for-media-importing/"><u>[Updated] Unveiling Windows 11'S Hidden Know-How for Media Importing</u></a></li>
<li><a href="https://howto.techidaily.com/11-proven-solutions-to-fix-google-play-store-not-working-issue-on-infinix-smart-8-hd-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Proven Solutions to Fix Google Play Store Not Working Issue on Infinix Smart 8 HD | Dr.fone</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-unique-perspectives-mastering-drone-footage/"><u>2024 Approved  Unique Perspectives  Mastering Drone Footage</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-wallet-friendly-skydock-sufficient-file-space/"><u>2024 Approved  Wallet-Friendly SkyDock  Sufficient File Space</u></a></li>
<li><a href="https://facebook.techidaily.com/data-for-dollars-tracking-trends-and-targets/"><u>Data for Dollars: Tracking Trends and Targets</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-apple-homepod-mini-exceptional-sound-intelligent-siri-functionality-and-more/"><u>Deciphering the Apple HomePod Mini – Exceptional Sound, Intelligent Siri Functionality, and More!</u></a></li>
<li><a href="https://fox-glue.techidaily.com/easy-tips-to-create-a-funny-meme-for-2024/"><u>Easy Tips to Create a Funny Meme for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/file-trailblazing-in-windows-11-the-top-6-techniques-to-duplicate-paths/"><u>File Trailblazing in Windows 11: The Top 6 Techniques to Duplicate Paths</u></a></li>
<li><a href="https://buynow-help.techidaily.com/find-what-you-need-for-free-with-oodle-classified-ads/"><u>Find What You Need for Free with Oodle Classified Ads</u></a></li>
<li><a href="https://howto.techidaily.com/fix-samsung-galaxy-m14-4g-android-system-webview-crash-2024-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Samsung Galaxy M14 4G Android System Webview Crash 2024 Issue | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/forza-horizon-cuestion-de-la-vida-o-muerte/"><u>Forza Horizon Cuestión De La Vida O Muerte</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-battlefield-bliss-exploring-the-7-best-massive-wars/"><u>In 2024, Battlefield Bliss  Exploring the 7 Best Massive Wars</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-tecno-pova-6-pro-5g-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Tecno Pova 6 Pro 5G to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-pinterest-vid-lifting-the-top-free-online-tools-list/"><u>In 2024, Pinterest Vid Lifting  The Top Free, Online Tools List</u></a></li>
<li><a href="https://windows11.techidaily.com/keep-your-file-explorer-running-smoothly-in-windows-11/"><u>Keep Your File Explorer Running Smoothly in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-file-access-toggling-windows-11-filters/"><u>Mastering File Access: Toggling Windows 11 Filters</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-maze-finding-windows-11s-mac-addresses/"><u>Navigating the Maze: Finding Windows 11'S MAC Addresses</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-execution-codewords-for-apps/"><u>Navigating Through Execution Codewords for Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-virtualbox-usb-connectivity-glitches-and-errors/"><u>Navigating Through VirtualBox USB Connectivity Glitches & Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-file-limit-anomaly-in-windows/"><u>Overcoming File Limit Anomaly in Windows</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1723808052068-overcoming-school-blocks-for-fortnite-tips-and-tricks-revealed/"><u>Overcoming School Blocks for Fortnite - Tips and Tricks Revealed!</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-paste-feature-efficacy-in-win-11/"><u>Restoring Paste Feature Efficacy in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-adding-outlook-preview-to-windows-devices/"><u>Step-by-Step: Adding Outlook Preview to Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-windows-troubleshooting-with-8-tips/"><u>Streamlining Windows Troubleshooting with 8 Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-unstartable-speech-to-text-on-windows-systems/"><u>Tackling Unstartable Speech to Text on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/tailor-filenames-in-bulk-using-windows-powertools/"><u>Tailor Filenames in Bulk Using Windows PowerTools</u></a></li>
<li><a href="https://windows11.techidaily.com/the-complete-checklist-for-epic-launcher-savings/"><u>The Complete Checklist for Epic Launcher Savings</u></a></li>
<li><a href="https://windows11.techidaily.com/the-path-to-gaming-bliss-guide-to-drive-selection/"><u>The Path to Gaming Bliss: Guide to Drive Selection</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-nvidia-cp-non-saving-on-win11/"><u>Troubleshooting Nvidia CP Non-Saving on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-sound-service-lag/"><u>Troubleshooting Windows Sound Service Lag</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-default-windows-11-terminal-features/"><u>Unlock Default Windows 11 Terminal Features</u></a></li>
<li><a href="https://windows11.techidaily.com/unmasking-windows-remote-desktop-glitch-dark-screen/"><u>Unmasking Windows Remote Desktop Glitch: Dark Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/win-lol-skirting-startup-snags-and-stalls/"><u>Win: LOL – Skirting Startup Snags and Stalls</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-dormancy-practical-tips-and-tricks/"><u>Windows Dormancy: Practical Tips & Tricks</u></a></li>
</ul></div>
