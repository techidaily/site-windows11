---
title: "Troubleshooting OBS Errors: Unknown Failure Recorded"
date: 2024-08-22T21:42:12.174Z
updated: 2024-08-23T21:42:12.174Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Troubleshooting OBS Errors: Unknown Failure Recorded"
excerpt: "This Article Describes Troubleshooting OBS Errors: Unknown Failure Recorded"
keywords: Fix OBS Glitches,Solve OBS Crash,OBS Error Resolution,Remedy OBS Errors,Troubleshoot OBS Failures,Unpack OBS Faults,Correct OBS Malfunction
thumbnail: https://thmb.techidaily.com/aef9f8cb7b85429cf28cb38f2d49cc0528e1c43a7556fd8a130e20454901702b.jpg
---

## Troubleshooting OBS Errors: Unknown Failure Recorded

 OBS Studio is a great program to record and stream online. However, some users can't utilize OBS Studio because of a recording error that occurs when they try to record their screens. Instead of recording, OBS Studio throws up this message: "An unspecified error occurred while recording."

 The error usually appears when an important DLL file is missing, or there's corruption in the OBS Studio installation directory. As such, if you also see the same error, then try the below solutions to eliminate the problem for good.

## 1\. Restart OBS Studio

![Closing the OBS Studio Process in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/end-task.jpg)

 Whether you're[seeing a black screen](https://www.makeuseof.com/windows-11-obs-black-screen-fix/) or getting the "An unspecified error occurred while recording" error, the best way to fix any OBS Studio issue is to restart it. Restarting OBS Studio will clear the system resources and kill any temporary bugs or glitches that might be causing the error.

 To restart OBS Studio, open the**Task Manager** (see how to[open the Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) ), right-click on OBS Studio, and choose**End Task.** Then, search for OBS Studio in the**Start Menu** and choose**Open** from the right pane.

## 2\. Temporarily Disable Your Graphics Driver

 The error is likely to occur if there's corruption in the GPU log file that is used by the OBS Studio. To remove the corruption, you'll have to disable the graphics driver before launching the OBS Studio. Doing this will force the program to create a new GPU log.

Here's what you need to do:

1. Open the**Power User Menu** by pressing the**Win + X** hotkey and choose**Device Manager** from the context menu.
2. In the Device Manager, double-click on the**Display adapters** node to expand it.
3. Right-click on the dedicated graphics driver and choose**Disable device.**  
![Disable Device option in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-device-option-1.jpg)
4. Click**Yes** to the prompt that appears.

 Your screen might flicker after disabling the dedicated graphics driver. But worry not; it'll become normal after the generic driver is started.

 Now, launch the OBS Studio and open your project. Then, open the Device Manager again > access the Display adapters node > right-click on the dedicated graphics driver and choose**Enable device.**

![Enable Device option in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-device.jpg)

 That's it! Return to OBS Studio and check if you are able to record.

## 3\. Allow OBS Studio Through Your Firewall

 OBS Studio might fail to record and throw the error at hand if it's blocked under Windows Firewall. To fix this, you'll have to whitelist OBS Studio from the Windows Firewall blocked app list. Here's how to do that:

1. Press the**Win** key to open the**Start Menu.**
2. Type**Windows Firewall** in the search bar and press Enter.
3. Choose **Allow an app or feature through Windows Defender Firewall** option from the left sidebar.  
![Allow an app or feature through Windows Defender Firewall option in Windows Firewall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/allow-an-app-or-feature-through-windows-defender-firewall-option.jpg)
4. Click the**Change settings** button.
5. Click on**Allow another app** and then choose**Browse** from the**Add an app** prompt.  
![Add an app prompt in the Windows Firewall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/add-an-app.jpg)
6. Navigate to the location where you have installed the OBS Studio.
7. Select the**obs-ffmpeg-mux** executable file and click**Open.**  
![obs-ffmpeg-mux file in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/obs-ffmpeg-mux-file.jpg)
8. Click**Add.**
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
9. Check both the**Private** and**Public** boxes for**obs-ffmpeg-mux** and click**OK** to save the settings.  
![Private and Public boxes for OBS File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/private-and-public-boxes.jpg)

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
Restart your computer and check if the problem continues.

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Fix the Missing DLL Files

[Dynamic Link Libraries](https://www.makeuseof.com/what-are-dll-files-on-windows/) , aka DLL files, are special implementations of system libraries that contain various functions and variables that programs use when needed. If an important DLL file required by OBS Studio goes missing, you will see the "An unspecified error occurred while recording" error.

 To fix that, you will have to re-acquire the required DLL file. Here's how:

1. Navigate to the place where you have installed the OBS Studio.
2. Double-click on the obs-ffmpeg-mux file, and note down which of the following DLL file is missing.  
`avcodec-57.dll  
avformat-57.dll  
avutil-55.dll  
swresample-2.dll`
3. Follow our guide on[how to fix DLL files missing on Windows](https://www.makeuseof.com/tag/dll-files-missing-errors/) to repair the missing file.

Restart your computer and check for the issue.

## 5\. Edit the OBS-Ffmpeg-Mux Installation Folder

 If you're still facing the issue even after downloading the missing DLL file, then it indicates that OBS Studio is unable to find the required DLL. The solution, in this case, is to edit the Path environment so that OBS Studio finds the required DLL files.

You can do that by following the below instructions:

1. Press the**Win + I** key to open the**Settings** **app.**
2. In the System tab, choose the**About** option in the left pane.
3. Click the**Advanced system settings** option.  
![Advanced system settings option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/advanced-system-settings.jpg)
4. Click the**Environment Variables** button.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
![Environment Variables option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enviroment-variables.jpg)
5. Select**Path** under the**System Variables** section, and click the**Edit** button.
6. Paste the following path in the**Variable value** text box and click**OK.**  
`C:\Program Files (x86)\obs-studio\bin\32bit;`  
![Edit Variable in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/edit-variable.jpg)

<!-- affiliate ads begin -->
<span id="1993652">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 That's it! Now, start recording in OBS Studio and check if the problem persists.

## 6\. Check for Corrupted or Missing Files

 Sometimes, OBS Studio might fail to record due to corruption in its installation folder. The problem can also occur if an important file is missing.

 In either case, you can use the "Check File Integrity" feature to scan the OBS installation for corruption and redownload broken/ missing files. Here's how to use that feature:

1. Launch OBS Studio, click the**Help** option at the top, and choose the**Check File Integrity** option from the context menu.  
![Check File Integrity option in OBS Studio](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-file-integrity-option.jpg)
2. Click**Yes** to confirm your selection.

 OBS Studio will compare the available files with those on its server and download any missing or broken files.

 While you're at the OBS Studio home screen, check for and download any available updates. To do that, click**Help** and choose**Check for Updates** .

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
## 7\. Reinstall OBS Studio

 If you're still getting the error message, you're left with no option other than reinstalling OBS Studio. To do that, first[uninstall OBS Studio from Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) .

 Then, visit the[OBS Studio official website](https://obsproject.com/) , and download and install the latest version on your computer.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
## Enjoy Seamless Recording With OBS Studio

 OBS Studio makes it a cakewalk to record anything and upload it online. However, due to corruption in its installation folder or missing DLL files, it might throw the "An unspecified error occurred while recording" error. Fortunately, you can quickly get rid of this error by applying the above fixes.


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
<li><a href="https://youtube-blog.techidaily.com/024-approved-youtube-growth-hacking-for-new-videographers/"><u>[New] 2024 Approved  YouTube Growth Hacking for New Videographers</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-navigating-zoomed-details-for-team-collaboration-on-ms-teams/"><u>[New] Navigating Zoomed Details for Team Collaboration on MS Teams</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-top-rated-free-apps-to-download-reels-from-instagram-effortlessly-for-2024/"><u>[New] Top-Rated, Free Apps to Download Reels From Instagram Effortlessly for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-edit-like-a-pro-with-any-of-these-top-7-free-options/"><u>[Updated] 2024 Approved  Edit Like a Pro with Any of These Top 7 Free Options</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-step-by-step-approach-to-capturing-and-editing-in-adobe-connect-for-2024/"><u>[Updated] Step-by-Step Approach to Capturing and Editing in Adobe Connect for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unveiling-the-magic-of-moving-texts-a-guide-for-insta-pros/"><u>2024 Approved  Unveiling the Magic of Moving Texts  A Guide for Insta Pros</u></a></li>
<li><a href="https://extra-resources.techidaily.com/a-step-into-tomorrow-installation-guide-for-windows-11/"><u>A Step Into Tomorrow  Installation Guide for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/does-error-8024002e-prevent-windows-from-updating-try-these-fixes/"><u>Does Error 8024002E Prevent Windows From Updating? Try These Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/dual-monitors-double-delight-themed-wallpapers-for-win-1011/"><u>Dual Monitors, Double Delight: Themed Wallpapers for WIN 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/ease-definitions-into-your-workspace-quickly/"><u>Ease Definitions Into Your Workspace Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-way-to-show-images-in-windows-11/"><u>Easy Way to Show Images in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/efface-the-expiring-windows-license-notifications/"><u>Efface the Expiring Windows License Notifications</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-strategies-to-delete-print-sources-on-windows-11/"><u>Effective Strategies to Delete Print Sources on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiency-at-your-fingertips-uninstall-microsoft-edge-from-w11/"><u>Efficiency at Your Fingertips: Uninstall Microsoft Edge From W11</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-strategies-to-bypass-windows-11s-tpm-lockdown/"><u>Efficient Strategies to Bypass Windows 11'S TPM Lockdown</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-unlock-recovery-options-for-your-pc/"><u>Efficiently Unlock Recovery Options for Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-empty-folder-search-and-removal-guide-for-windows-users/"><u>Effortless Empty Folder Search and Removal Guide for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-jotting-in-windows-11-no-apps-required/"><u>Effortless Jotting in Windows 11: No Apps Required</u></a></li>
<li><a href="https://windows11.techidaily.com/effortlessly-connect-and-communicate-with-imessage-on-your-pc/"><u>Effortlessly Connect and Communicate with iMessage on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-pc-capabilities-a-comprehensible-wintoy-approach/"><u>Elevate PC Capabilities: A Comprehensible WinToy Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-pc-expertise-with-vivetool-on-windows/"><u>Elevate Your PC Expertise with ViVeTool on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-installation-error-fix-oculus-for-winxc-and-winxi/"><u>Eliminate Installation Error: Fix Oculus for WinXC and WinXI</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-search-issues-on-windows-11-os/"><u>Eliminating Search Issues on Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/elusive-wi-fi-on-windows-how-to-hide-itself/"><u>Elusive Wi-Fi on Windows: How To Hide Itself</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-workflow-top-windows-11-rdc-techniques/"><u>Enhance Your Workflow: Top Windows 11 RDC Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-performance-metrics-tracking-on-windows/"><u>Enhancing Performance Metrics Tracking on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-microsoft-edge-on-win11/"><u>Eradicating Microsoft Edge on Win11</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-reset-the-security-questions-of-your-apple-id-on-your-apple-iphone-12-pro-max-by-drfone-ios/"><u>How To Reset the Security Questions of Your Apple ID On Your Apple iPhone 12 Pro Max</u></a></li>
<li><a href="https://fox-that.techidaily.com/overcoming-itunes-refusal-6-steps-for-successful-transactions/"><u>Overcoming iTunes Refusal: 6 Steps for Successful Transactions</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-guide-how-to-fix-your-airpods-microphone-issues-on-windows-10/"><u>Troubleshooting Guide: How to Fix Your AirPods Microphone Issues on Windows 10</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-2024-approved-crafting-silent-elegance-the-art-of-audio-ducking-in-video-editing-with-adobe-premiere-pro-on-mac/"><u>Updated 2024 Approved Crafting Silent Elegance The Art of Audio Ducking in Video Editing with Adobe Premiere Pro on Mac</u></a></li>
</ul></div>
