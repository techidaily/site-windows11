---
title: A User's Guide to Navigating File Explorer Tabs, Windows 11 Style
date: 2024-08-15T15:16:52.881Z
updated: 2024-08-16T15:16:52.881Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A User's Guide to Navigating File Explorer Tabs, Windows 11 Style
excerpt: This Article Describes A User's Guide to Navigating File Explorer Tabs, Windows 11 Style
keywords: File Explorer Navigation,Windows 11 File Explore,Tab Management in Win11,Navigate File Tabs W11,Guide to File Explorer Tabs,Using Windows 11 Explorer,Optimizing File Tab Usage
thumbnail: https://thmb.techidaily.com/26e5a5bed3537105229e89d2df536f43cfadace1d3a287d0f50c6226ff3d146f.png
---

## A User's Guide to Navigating File Explorer Tabs, Windows 11 Style

 Microsoft added the much-awaited tabs feature in Windows File Explorer in 2022\. While it is not the best implementation we had hoped for, it certainly gets the job done. You don’t have to open separate File Explorer windows to access two different locations on the disk. But there is still a lot missing from the tabs feature; you cannot drag tabs out from a File Explorer window.

 This feature is available in many browsers, but Microsoft took notice and is now testing the file drag feature in Windows 11 Insider builds. Here’s how to enable the feature on your system.

## Is Dragging File Explorer Tabs Out Really That Useful?

 If you recall your experience with using a web browser, you know that using a split screen has its advantages. If you want to stack two tabs side by side, you can just open two browser tabs, drag one out, and use snap layouts to arrange them. It is very easy to drag out a tab in a browser, but that feature is missing in the current version of File Explorer.

![Dragging out tabs in Chrome Browser](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dragging-out-tabs-in-chrome-browser.jpg)

 So, you can have two file locations open in two separate tabs in File Explorer. But if you have to stack them side by side, there is no such option. You will have to close one tab (if you like) and open another instance of File Explorer and then use the split-screen layout.

 Thankfully, the latest Insider build 25290 has a hidden feature that makes it possible to drag out tabs.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
## How to Enable the Drag-Out Feature in File Explorer

 This feature is exclusive to Windows 11 Insider builds and is in the testing phase. So, you will have to download and install the build version 25290 and then use the ViveTool to enable the feature.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
### 1\. Update to the Latest Insider Build

 To update to the latest insider build, head over to the Settings page and [check for Windows updates](https://www.makeuseof.com/tag/update-windows-software-guide/) . After that, install the latest 25920 build or newer on your system. You will have to restart your system for the changes to take effect.

 If you haven’t enrolled in the Windows Insider program and still want to try out this new feature, take the help of UUP Dump. You can easily [download the latest Windows Insider builds using UUP Dump](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/) . Install the build and then proceed to the next step.

### 2\. Enable the Feature Using ViveTool

 Now, you have the Insider build running on your system. You will have to use the ViveTool to enable the hidden experimental feature to drag tabs out of the File Explorer. But first,[download ViveTool from GitHub](https://github.com/thebookisclosed/ViVe/releases) and install the ViveTool on your system. After that, repeat the following steps:

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) on your system.
2. Type**cmd** in the text input area and then press**Ctrl + Shift + Enter** key to launch the command prompt with admin privileges.
3. Now, locate the ViveTool directory using the**cd** command. We placed the ViveTool in a folder named Vive on C drive, So the command to change to that directory will be**cd\\** .
4. Once you are in the C directory, type**cd Vive** and press the**Enter** key.
5. After that, type**vivetool /enable /id:39661369** command and press the**Enter** key.  
![Enabling Tabs Dragging Feature In File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enabling-tabs-dragging-feature-in-file-explorer.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
6. **Exit** the command prompt window after the ViveTool command executes successfully.
7. Restart your system to apply the changes.
8. Log into Windows and press**Win + E** to launch File Explorer. Now, open two tabs and click and hold on any of the open tabs.  
![Tabs Dragging Feature in Action in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tabs-dragging-feature-in-action-in-file-explorer.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
9. Try to drag the tabs out of File Explorer. It will open in a second window. You can stack them on each side if you like.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
## Can You Restore the Tab to the File Explorer Window?

 Yes, you can indeed restore the dragged tab back to a File Explorer window. But the process is very clunky. You have to drag and hold the tab onto another open tab in a different File Explorer window.

 If you aren’t able to accurately position the tab, it will not merge with the File Explorer tab bar. In Chrome browser, dragging out and restoring them to the same window is pretty easy. You can even hover the tab and position it between two open tabs.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Drag Tabs Out Like a Pro in File Explorer

 Microsoft is trying to make File Explorer more useful. But we cannot expect File Explorer to exactly work like a browser. After, it happens to be a means to access different types of files and open them with a compatible app or program in a new window. Still, dragging tabs out is a slick feature, and we hope Microsoft fixes the kinks and adds it in future updates.


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
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-alternate-escapades-where-the-gta-v-lives-are-missing/"><u>[New] 2024 Approved  Alternate Escapades - Where the GTA V Lives Are Missing</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-youtubes-tagging-system-unveiled/"><u>[New] 2024 Approved  YouTube's Tagging System Unveiled</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-youtube-phenomenon-forecast-for-2024/"><u>[New] YouTube Phenomenon Forecast for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-discover-top-6-short-video-download-sites-free-for-2024/"><u>[Updated] Discover Top 6 Short Video Download Sites (FREE) for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-screening-success-10-movies-that-energize-and-empower/"><u>2024 Approved  Screening Success  10 Movies That Energize & Empower</u></a></li>
<li><a href="https://windows11.techidaily.com/exiting-others-user-sessions-on-win-11/"><u>Exiting Others' User Sessions on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-windows-pathways-to-filefolder-secrets/"><u>Expert Windows Pathways to File/Folder Secrets</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-error-0x8019-in-windows-updates/"><u>Fixing Error 0X8019 in Windows Updates</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/flash-fiction-directorial-map/"><u>Flash Fiction Directorial Map</u></a></li>
<li><a href="https://windows11.techidaily.com/from-novice-to-pro-mastering-github-desktop-on-windows-11/"><u>From Novice to Pro: Mastering GitHub Desktop on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-the-license-will-expire-warning-in-win11/"><u>How to Stop the License Will Expire Warning in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-win11-from-showing-00-error-codes/"><u>How to Stop Win11 From Showing 00 Error Codes</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-iphone-13-with-imei-code-by-drfone-ios/"><u>How to Unlock iPhone 13 with IMEI Code?</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-change-lock-screen-wallpaper-on-samsung-galaxy-f15-5g-by-drfone-android/"><u>In 2024, How to Change Lock Screen Wallpaper on Samsung Galaxy F15 5G</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-tall-tales-reimagined-edits-for-vt-videos-on-fcpx/"><u>In 2024, Tall Tales Reimagined  Edits for VT Videos on FCPX</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-ultimate-live-capture-review-discovering-obs-dominance/"><u>In 2024, Ultimate Live Capture Review  Discovering OBS Dominance</u></a></li>
<li><a href="https://windows11.techidaily.com/managing-windows-modules-installer-resource-demand/"><u>Managing Windows Modules Installer Resource Demand</u></a></li>
<li><a href="https://windows11.techidaily.com/master-note-taking-on-win11-easy-as-pie/"><u>Master Note-Taking on Win11, Easy as Pie</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-fixes-for-hardware-detection-faults/"><u>Mastering Fixes for Hardware Detection Faults</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-sefx-windows-11-sfx-creation/"><u>Mastering SEFX: Windows 11 SFX Creation</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-for-resolving-process-termination-failure-on-pcs/"><u>Methods for Resolving 'Process Termination Failure' On PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-microphone-performance-with-xbox-app-windows-11/"><u>Optimizing Microphone Performance with Xbox App Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-grayscale-windows-backdrops-tips-for-enhancement/"><u>Overcoming Grayscale Windows Backdrops: Tips for Enhancement</u></a></li>
<li><a href="https://windows11.techidaily.com/preventive-measures-for-csgo-launch-woes-on-windows-11/"><u>Preventive Measures for CS:GO Launch Woes on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/priority-accessibility-attach-google-mail-taskbar-ready/"><u>Priority Accessibility: Attach Google Mail Taskbar-Ready</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-lsa-errors-on-windows-pcs/"><u>Quick Fixes for LSA Errors on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/reflect-on-one-misconception-about-cultural-relativism-mentioned-in-class-then-describe-how-you-would-address-this-misunderstanding-with-someone-from-a-diff21/"><u>Reflect on One Misconception About Cultural Relativism Mentioned in Class, Then Describe How You Would Address This Misunderstanding with Someone From a Different Culture</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-issues-for-microsoft-store-access-on-windows-11/"><u>Resolving Issues for Microsoft Store Access on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-unresizable-gif-error-tips-for-discord-on-windows-11/"><u>Resolving Unresizable GIF Error: Tips for Discord on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-reduce-cpu-consumption-fixing-dropbox-on-windows/"><u>Solutions to Reduce CPU Consumption: Fixing Dropbox on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-methodology-for-full-uninstallation-of-wsl/"><u>Step-by-Step Methodology for Full Uninstallation of WSL</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-ax201-wi-fi-6-error-on-windows/"><u>Steps to Resolve AX201 Wi-Fi 6 Error on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/systematic-steps-for-nullifying-your-windows-drive-partitions/"><u>Systematic Steps for Nullifying Your Windows Drive Partitions</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-pin-verification-hurdles-for-windows-1011-systems/"><u>Tackling PIN Verification Hurdles for Windows 10/11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-deal-with-missing-values-on-pcs-running-winos/"><u>Techniques to Deal with Missing Values on PCs Running WinOS</u></a></li>
<li><a href="https://tech-hub.techidaily.com/top-5-no-cost-artificial-intelligence-applications-for-crafting-professional-email-responses-using-chatgpt/"><u>Top 5 No-Cost Artificial Intelligence Applications for Crafting Professional Email Responses Using ChatGPT</u></a></li>
<li><a href="https://windows11.techidaily.com/top-7-photo-arrangers-for-a-clutter-free-pc-desktop/"><u>Top 7 Photo Arrangers for a Clutter-Free PC Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-winservicesexe-on-your-pc/"><u>Troubleshooting Winservices.exe on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-peak-performance-why-choose-windows-for-gaming/"><u>Unleashing Peak Performance: Why Choose Windows for Gaming</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-hidden-potential-in-vintage-video-gaming-titles-using-retroarch/"><u>Unlocking Hidden Potential in Vintage Video Gaming Titles Using Retroarch</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-microsoft-family-safety-potential/"><u>Unlocking Microsoft Family Safety Potential</u></a></li>
<li><a href="https://extra-information.techidaily.com/unlocking-your-podcast-potential-on-ios-from-script-to-success/"><u>Unlocking Your Podcast Potential on iOS  From Script to Success</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-vivetool-enable-unseen-features-on-windows-pcs/"><u>Unraveling ViVeTool: Enable Unseen Features on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-windows-odbc-command-center/"><u>Unveiling the Windows ODBC Command Center</u></a></li>
<li><a href="https://windows11.techidaily.com/win10win11-diagnostics-tackling-0x0000004e-faults/"><u>Win10/Win11 Diagnostics: Tackling 0X0000004E Faults</u></a></li>
<li><a href="https://windows11.techidaily.com/workaround-for-win10-and-11s-audacity-device-opening-issue/"><u>Workaround for Win10 & 11’S Audacity Device Opening Issue</u></a></li>
</ul></div>
