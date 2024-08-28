---
title: Strategies to Address File System Problems in Win11
date: 2024-08-27T16:03:50.315Z
updated: 2024-08-28T16:03:50.315Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategies to Address File System Problems in Win11
excerpt: This Article Describes Strategies to Address File System Problems in Win11
keywords: Win11 Filesys Fix Tips,Win11 Troubleshooting Guide,Resolving Win11 FS Issues,Win11 File Management,Win11 System Optimization,Addressing Win11 Errors,Enhancing Windows 11 Stability
thumbnail: https://thmb.techidaily.com/29cfc21c1254cb70322b91195c7081ab1c044155fd0a604dc9fcf1b208976460.jpg
---

## Strategies to Address File System Problems in Win11

 A file system error can occur in Windows 10 and 11 when you try to open files or Microsoft Store apps. When such an error occurs, a message pops up that says, “File system error (code).” File system errors have variable error codes like -2147219195, -2147219196, -2147163893, and -1073741521.

 The causes of such errors vary, but the result is much the same. Users can’t open the files or apps for which file system errors arise. These general resolutions can fix a wide variety of file system errors in Windows 10 and 11.

## 1\. Run the SFC and DISM Command Line Tools

 File system errors can often be related to system file corruption. Windows 11 and 10 have the same SFC and DISM command-line tools for repairing system files and Windows system image. Running those utilities in the Command Prompt could feasibly resolve numerous file system errors.

 Our guide on[how to run the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to initiate an SFC scan. You can also run a Deployment Image Servicing Management scan in the Command Prompt before or after running the SFC tool. To do so, you’ll need to execute the following command:

`DISM.exe /Online /Cleanup-image /Restorehealth`

## 2\. Scan Your Hard Drive

 Hard drive integrity issues such as bad sectors also cause file system errors to occur in Windows 11/10\. For that reason, scanning your hard drive with the Check Disk tool is a recommended troubleshooting method for file system errors. The Check Disk utility (otherwise CHKDSK) scans for and repairs bad drive sectors detected. This is how you can run CHKDSK in the Command Prompt:

1. Open the file and app search box by pressing the**Win + S** key combination.
2. Select Command Prompt’s**Run as administrator** option within the search results to launch the app with elevated privileges.
3. Then type this command in the Prompt’s window and press**Enter** :  
`chkdsk c: /f /r`
4. You’ll need to press**Y** to schedule the scan for a restart.  
![The chkdsk command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/chkdsk.jpg)
5. Exit the Command Prompt window.
6. Click**Start > Power** to select**Restart** . The CHKDSK scan will start after the restart.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
## 3\. Run the Windows Store App Troubleshooter

 If a file system error occurs when you try launching MS Store apps or opening files with them, the Windows Store App troubleshooter might be useful for fixing it. That troubleshooter is there to resolve issues that stop UWP apps from working as they should. These are the steps for opening the Windows Store App troubleshooter:

1. To access Settings, press the**Windows** logo key +**E** keyboard shortcut that opens that app.
2. Scroll down the tab and click a**Troubleshoot navigation** option.
3. Select**Other trouble-shooters** to bring up a list of tools for troubleshooting Windows.
4. Then press the**Run** button for launching the Windows Store App troubleshooter.  
![The troubleshooter list in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-store-apps-troubleshooter1.jpg)
5. Apply any suggestions the troubleshooter provides.  
![The Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-store-app-window.jpg)

## 4\. Check That the Windows License Manager Service Is Running

 Some file system errors can arise for opening files with UWP apps when the Windows License Manager service is disabled. That’s a service required for MS Store infrastructure support, and apps downloaded from the store don’t always work right when it’s disabled. This is how you can check that service is enabled and start it if necessary:

1. Bring up the Windows search tool and input**Services** inside its text box.
2. Select**Services** within the search results.
3. Double-click**Windows License Manager Service** to access its properties window.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-services-window2.jpg)
4. Click on the**Startup type** menu to open it and select**Automatic** .  
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
![The Windows License Manager server window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-license-service-manager.jpg)
5. If the service isn’t running, press**Start** within the properties window.
6. Select**Apply** to save settings for the Windows License Manager Service.
7. Click**OK** to close the Windows License Manager Service Properties window.

<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
## 5\. Reinstall Any Affected App

 This potential solution is more applicable to fixing file system errors that occur for opening specific UWP apps. Reinstalling the app for which the error arises might resolve it in such a scenario. For example, users confirmed reinstalling Microsoft Photos can resolve file system error -2147219196.

 You can remove UWP apps with some of the methods in our guide for uninstalling software in Windows 11\. You can uninstall most apps with the Apps & Features tool in Settings. However, you might need to use the PowerShell method in our guide to remove some pre-installed Windows 11 apps.

![Apps & features in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/apps-features-window.jpg)

 When you’ve uninstalled the app, reinstall it from the MS Store. Bring up the Microsoft Store, and input the app’s title in its search box. Then select the app to reinstall in the search results, and click the**Get** button for it.

## 6\. Set Up a New Local User Account on Windows

 File system errors can arise because of user account issues. Such errors might not arise if you set up and utilize a new local user account in Windows 11\. That might not be the most ideal resolution, but you can migrate user files to a newly established account.

 Our guide on[how to fix Windows issues by creating new accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/) includes full instructions for how to apply this solution.

![The Add account button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/add-account-button.jpg)

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
## 7\. Restore Windows to an Earlier Date

 System Restore is a troubleshooting tool that can potentially address various causes for file system errors, be it system file corruption, app conflicts, or recent Windows updates. It fixes many things by restoring Windows to an earlier date (system snapshot). However, restoring Windows to an earlier time will only likely work if you can select a restore point that predates the file system error on your PC.

 To apply this potential solution, read through our guide to[utilizing System Restore and creating restore points](https://www.makeuseof.com/windows-11-create-restore-point/) . Select a restoration date that will take your PC back to a time when there wasn’t a system file error on it. The oldest restore point available is the most likely one to do that.

![The System Restore tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/system-restore-window.jpg)

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
 However, restoring Windows to a previous time removes software not installed on the restoration point’s date. So, it’s likely you’ll have to reinstall some apps after rolling back Windows. Clicking**Scan for affected programs** in System Restore provides an overview of software that will be removed for a restore point.

<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 8\. Reset Windows

 This final system file error solution is the most drastic of all since it amounts to reinstalling Windows 10 or 11\. Factory resetting restores Windows to a default system state, which can fix many errors caused by registry, third-party software, and system file issues. If you can’t fix a system file error with any other potential fix in this guide, then resetting is the last thing to try.

 Windows 11 and 10 have a Reset this PC tool that makes it easy to factory reset the platform. That tool also includes an option that enables you to keep user files in the process. Our guide on[how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) includes instructions for applying this potential resolution with this tool.

<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get File System Errors Sorted in Windows

 Users often report file system errors on support forums much the same as BSOD (Blue Screen of Death) and missing DLL file issues. You can't ignore them when they stop you from opening important user files or apps. Whatever file system error you need to fix in Windows 10 and 11, you’ll probably be able to resolve it with at least one of the potential resolutions above.

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
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-unlocking-your-content-with-vimeo-links/"><u>[New] 2024 Approved  Unlocking Your Content with Vimeo Links</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-transform-your-zoom-presentations-with-stunning-visuals/"><u>[New] Transform Your Zoom Presentations with Stunning Visuals</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-expert-recommended-5-ps1-game-simulators-on-your-pc/"><u>[Updated] 2024 Approved  Expert-Recommended 5 PS1 Game Simulators on Your PC</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-auditory-appeal-modifying-voices-in-instagrams-storytelling/"><u>[Updated] Auditory Appeal  Modifying Voices in Instagram's Storytelling</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-becoming-a-social-media-storyteller-on-facebook/"><u>[Updated] Becoming a Social Media Storyteller on Facebook</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-newbies-pathway-to-stunning-photo-edits-in-ps/"><u>[Updated] Newbie's Pathway to Stunning Photo Edits in PS</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-streamline-screen-capturing-in-todays-remote-meetings-for-2024/"><u>[Updated] Streamline Screen Capturing in Today’s Remote Meetings for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-luminous-landscapes-designing-visuals-that-dazzle-viewers/"><u>2024 Approved  Luminous Landscapes  Designing Visuals that Dazzle Viewers</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/approved-youtubes-time-warp-watch-lists-in-the-reverse-order/"><u>2024 Approved  YouTube's Time Warp  Watch Lists in the Reverse Order</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/2024-approved-srt-subtitle-translation-tools-and-techniques/"><u>2024 Approved SRT Subtitle Translation Tools and Techniques</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/copycat-cinema-steps-for-satirical-video-making-for-2024/"><u>Copycat Cinema  Steps for Satirical Video Making for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/demystifying-wireless-networking-the-complete-breakdown-of-ieee-80211-be-ax-ac-bgn-and-a-variants/"><u>Demystifying Wireless Networking: The Complete Breakdown of IEEE 802.11 Be, Ax, Ac, B/G/N & A Variants</u></a></li>
<li><a href="https://extra-tips.techidaily.com/discovering-the-ultimate-mobile-photo-experience-ios-11/"><u>Discovering the Ultimate Mobile Photo Experience  IOS 11</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-how-to-activating-hyper-v-for-win11-users/"><u>Essential How-To: Activating Hyper-V for Win11 Users</u></a></li>
<li><a href="https://screen-recording.techidaily.com/from-playtime-to-prestige-capturing-sims-mastery-for-2024/"><u>From Playtime to Prestige  Capturing Sims Mastery for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-fix-bluetooth-absence-in-device-mgr/"><u>Guide to Fix Bluetooth Absence in Device Mgr</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-eliminate-user-accounts-from-windows-11-a-revo-uninstaller-approach/"><u>How to Eliminate User Accounts From Windows 11: A Revo Uninstaller Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-blackouts-during-win-based-gameplay/"><u>How to Fix Blackouts During Win-Based Gameplay</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-properly-utilize-system-restore-on-microsoft-windows/"><u>How to Properly Utilize System Restore on Microsoft Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-realign-read-aloud-settings-on-word-app/"><u>How To Realign Read Aloud Settings on Word App</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-salvage-your-failed-zip-extraction-in-windows-11/"><u>How To Salvage Your Failed ZIP Extraction in Windows 11</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-infinix-hot-30-5g-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Infinix Hot 30 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-take-a-screenshot-of-uac-prompts-on-windows/"><u>How to Take a Screenshot of UAC Prompts on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-measures-for-repairing-post-windows-upgrade-failures/"><u>Immediate Measures for Repairing Post-Windows Upgrade Failures</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-quick-conversion-at-no-expense-fb-videos-to-mp4-and-hd-now/"><u>In 2024, Quick Conversion at No Expense - FB Videos to MP4 & HD Now</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-ultimate-pcmobile-mkv-viewer/"><u>In 2024, Ultimate PC/Mobile MKV Viewer</u></a></li>
<li><a href="https://howto.techidaily.com/motorola-razr-40-ultra-not-connecting-to-wi-fi-12-quick-ways-to-fix-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Motorola Razr 40 Ultra Not Connecting to Wi-Fi? 12 Quick Ways to Fix | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/muting-mayhem-reverse-sound-suppression-in-windows/"><u>Muting Mayhem? Reverse Sound Suppression in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-file-access-harness-the-power-of-win11s-checkboxes/"><u>Optimize File Access: Harness the Power of Win11's Checkboxes</u></a></li>
<li><a href="https://windows11.techidaily.com/redesigned-navigation-top-7-updates-to-window-11s-file-explorer/"><u>Redesigned Navigation: Top 7 Updates to Window 11'S File Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/regain-access-to-hidden-5ghz-networks-on-your-windows-pc/"><u>Regain Access to Hidden 5GHz Networks on Your Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-zoom-crash-code-1132-in-windows-os/"><u>Resolving Zoom Crash Code: 1132 in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/skirting-microsofts-app-verification-system-on-pc/"><u>Skirting Microsoft's App Verification System on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-frozen-grammarly-on-your-computer-system/"><u>Solving Frozen Grammarly on Your Computer System</u></a></li>
<li><a href="https://tech-revival.techidaily.com/step-by-step-guide-setting-up-kodi-on-your-windows-11-pc/"><u>Step-by-Step Guide: Setting Up Kodi on Your Windows 11 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-fix-xbox-game-download-failures-on-pc/"><u>Steps to Fix Xbox Game Download Failures on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-recover-from-a-blank-login-display-window/"><u>Steps to Recover From a Blank Login Display Window</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-disk-read-failed-problem/"><u>Tackling the “Disk Read Failed” Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/the-vision-enhancers-guide-top-9-remedies-for-blurry-displays/"><u>The Vision Enhancers' Guide: Top 9 Remedies for Blurry Displays</u></a></li>
<li><a href="https://windows11.techidaily.com/top-tools-that-makes-your-laptops-os-change-more-manageable/"><u>Top Tools that Makes Your Laptop's OS Change More Manageable</u></a></li>
<li><a href="https://windows11.techidaily.com/transformative-tools-in-the-studio-4-microsoft-paint-redesigns/"><u>Transformative Tools in the Studio: 4 Microsoft Paint Redesigns</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-code-0x0001-for-nvidia-experience-in-windows/"><u>Troubleshooting Code 0X0001 for Nvidia Experience in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-fixing-your-non-responsive-xbox-one-controller/"><u>Troubleshooting Guide: Fixing Your Non-Responsive Xbox One Controller</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-the-lost-vcruntime1n40dll-file-expert-tips-and-tricks/"><u>Troubleshooting the Lost VCRUNTIME1n40.dll File - Expert Tips & Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-the-store-error-a-fix-for-windows-x800704cf/"><u>Unblocking the Store Error: A Fix for Windows' X800704CF</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-airpods-windows-symbiosis/"><u>Unlocking AirPods-Windows Symbiosis</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-full-potential-of-your-systems-ram-with-windows/"><u>Unlocking the Full Potential of Your System's RAM with Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-power-of-cross-platform-note-taking-in-win11/"><u>Unveiling the Power of Cross-Platform Note Taking in Win11</u></a></li>
</ul></div>
