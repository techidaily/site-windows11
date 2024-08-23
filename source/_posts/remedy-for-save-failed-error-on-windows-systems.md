---
title: Remedy for Save Failed Error on Windows Systems
date: 2024-08-22T21:33:15.627Z
updated: 2024-08-23T21:33:15.627Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Remedy for Save Failed Error on Windows Systems
excerpt: This Article Describes Remedy for Save Failed Error on Windows Systems
keywords: Fix Windows Save Fail,Resolve Save Error Win,Stop Windows Save Issue,Cure Save Error PC,Eradicate Save Fails Win,Eliminate Save Errors OS,Overcome Save Glitches PC
thumbnail: https://thmb.techidaily.com/f66305bee95e2c8cfda71737bc488d60f6c275330b2e729ec458216f465e024e.png
---

## Remedy for Save Failed Error on Windows Systems

 Users have reported error 0x80070005 or 0x80070539 arises when they try to set new apps to save to different external drive locations with Settings. Those error codes have the same message that says, “We couldn’t set your default save location.” This means users can’t change the default save location for apps.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

## 1\. Set Your User Account to Administrator

 If you’re utilizing a standard Windows account, [change your user account type](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) to an administrative one. A standard user account will prevent you from applying any more complicated system changes. Changing the save location for apps is something you might need admin privileges for.

![The Account type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-account-type-window.jpg)

## 2\. Rename the WindowsApps Directory

 This error can arise because the WindowsApps folder where apps save is corrupted. Renaming the WindowsApps folder on the drive or partition you want to save apps can address such an issue. To do so, rename that folder as follows:

1. If you’re trying to set apps to save on an external drive, connect that hard drive to your PC.
2. [Open the File Explorer folder navigator](https://www.makeuseof.com/windows-open-file-explorer/) and click **This PC**.
3. Double-click the drive/partition you want to set as your default save location for apps.
4. Then, right-click on the WindowsApps folder and select its **Rename** context menu option. You should find that directory within the drive’s root directory.  
![The Rename option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-button.jpg)
5. Rename the folder to **WindowsApps.old** and press **Enter**.
6. Thereafter, try changing the default save location for apps again via Settings.

 If that still doesn’t work, then proceed to the next resolution.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
## 3\. Delete or Rename the WpSystem Folder

 Many users confirm that renaming or deleting the WpSystem folder fixes error 0x80070005\. WpSystem is a folder created to store app data. Try renaming that folder to **WpSystem.old** on the drive you can’t set to be a save location for apps, as outlined for the previous method. The WpSystem will be in the same directory as the WindowsApps folder.

 Alternatively, delete the WpSystem folder. You can [erase a file or folder in Explorer](https://www.makeuseof.com/windows-11-delete-select-files/) by right-clicking it and selecting **Delete**. If you can’t find that folder or this potential solution doesn’t work, try the next resolution.

![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-option.jpg)

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Set Full System Permission for the System Volume Folder

 Setting full permission for the System Volume folder is another confirmed fix for error 0x80070005\. Follow these steps to set full permission for the System Volume directory:

1. Go into File Explorer and click the three-dot **See more** menu > **Options**. In Windows 10, click **Options** on the **View** tab.
2. Select **View** on the Folder Options window.
3. Deselect the **Hide protected operating system files (Recommended)** option.  
![The Hide protected operating system files checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hide-protected-operating-system-files.jpg)
4. Select the **Show hidden files, folders and drives** radio button.
5. Click **Apply** to save the new Explorer settings.

1. Select the drive you need to set as the default save location for apps.
2. Right-click the System Volume Information folder and select **Properties**.
3. Click **Security > Advanced** to bring up an Advanced Security Settings window.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/security-tab.jpg)
4. Press the **Continue** button.
<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
<!-- affiliate ads end -->
5. Next, click **Add** to view a Permission Entry window.

1. Click the **Select a principal** option.
2. Input **SYSTEM** inside the object name box.  
![The Select User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/select-user-group.jpg)
3. Click on the **OK** button.
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Select the **Full control permission** setting.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/full-control-option.jpg)
5. Then select the **OK** options on the Permission Entry and Advanced Security Settings windows.
<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Close all remaining open windows. Then, restart your PC and try changing the default save location.

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Set a New Default Save Location in Windows 11/10

 Many users have needed to fix error 0x80070005 and have done so by applying the potential solutions in this guide. The WpSystem folder is often the source of the error, and resolution two is the most widely confirmed method for fixing this issue.

 However, some users have also fixed the issue by applying the less widely cited fourth method.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-record-videos.techidaily.com/new-earning-through-eyes-the-actual-youtube-view-count-needed-for-2024/"><u>[New] Earning Through Eyes  The Actual YouTube View Count Needed for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-from-fragmented-to-flawless-mastering-kinemaster-edits/"><u>[New] From Fragmented to Flawless  Mastering Kinemaster Edits</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-insights-on-engaging-top-tier-visual-storytellers/"><u>[New] Insights on Engaging Top-Tier Visual Storytellers</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-expert-strategies-for-high-quality-gopro-4k-footage-editing/"><u>[Updated] Expert Strategies for High-Quality GoPro 4K Footage Editing</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-single-frame-snipping-capturing-stillness-from-videos-in-photos/"><u>[Updated] Single-Frame Snipping  Capturing Stillness From Videos in Photos</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-stream-to-success-obs-youtube-broadcast-basics/"><u>[Updated] Stream to Success  OBS Youtube Broadcast Basics</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-tailored-video-experience-creating-a-structured-watch-later-list-on-youtube/"><u>[Updated] Tailored Video Experience  Creating a Structured 'Watch Later' List on YouTube</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-amusing-tones-bestringeonsite-roundup/"><u>2024 Approved  Amusing Tones  Bestringeonsite Roundup</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-best-youtube-video-reaction-ideas/"><u>2024 Approved  Best YouTube Video Reaction Ideas</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/approved-free-vs-paid-youtubes-exclusive-picks-for-superior-opening-tutorials/"><u>2024 Approved  Free vs Paid  YouTube's Exclusive Picks for Superior Opening Tutorials</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-best-tools-to-hard-reset-nubia-red-magic-9-proplus-drfone-by-drfone-reset-android-reset-android/"><u>3 Best Tools to Hard Reset Nubia Red Magic 9 Pro+ | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/access-bings-intelligent-search-features-across-both-android-and-ios-devices/"><u>Access Bing's Intelligent Search Features Across Both Android & iOS Devices</u></a></li>
<li><a href="https://howto.techidaily.com/bricked-your-zte-nubia-flip-5g-heres-a-full-solution-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Bricked Your ZTE Nubia Flip 5G? Heres A Full Solution | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/faster-printouts-with-easy-windows-troubleshooting/"><u>Faster Printouts with Easy WIndows Troubleshooting</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-stalled-windows-outlook-conditional-rules/"><u>Fixing Stalled Windows Outlook Conditional Rules</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-activation-problem-eliminate-error-0x803f700f/"><u>Fixing Windows Activation Problem: Eliminate Error 0X803F700f</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723862837737-gamers-alert-enjoy-the-cutting-edge-technology-with-a-sceptre-curved-monitor-at-an-incredible-discounted-rate-of-79/"><u>Gamers Alert! Enjoy the Cutting-Edge Technology with a Sceptre Curved Monitor at an Incredible Discounted Rate of $79!</u></a></li>
<li><a href="https://buynow-info.techidaily.com/get-more-bang-for-your-buck-with-the-budget-friendly-arcshell-ar-5/"><u>Get More Bang for Your Buck with the Budget-Friendly Arcshell AR-5</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-fixing-winrars-failed-file-sums-and-verifications/"><u>Guide to Fixing WinRAR's Failed File Sums and Verifications</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-a-device-which-does-not-exist-was-specified-error-in-windows-10-and-11/"><u>How to Fix the “A Device Which Does Not Exist Was Specified” Error in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-discord-fatal-javascript-error-in-windows-11-and-11/"><u>How to Fix the Discord Fatal Javascript Error in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reduce-clutter-disabling-explorer-tabs/"><u>How to Reduce Clutter: Disabling Explorer Tabs</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-tecno-spark-20-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Tecno Spark 20 to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-fix-iphone-7-passcode-not-working-by-drfone-ios/"><u>In 2024, How to Fix iPhone 7 Passcode not Working?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-tracking-apps-to-track-nokia-c300-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Tracking Apps to Track Nokia C300 without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-two-ways-to-track-my-boyfriends-tecno-pova-5-pro-without-him-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Two Ways to Track My Boyfriends Tecno Pova 5 Pro without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-honor-magic5-ultimate-drfone-by-drfone-virtual-android/"><u>In 2024, Will Pokémon Go Ban the Account if You Use PGSharp On Honor Magic5 Ultimate | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/learn-to-circumvent-windows-11-lock-without-fuss/"><u>Learn to Circumvent Windows 11 Lock Without Fuss</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/logitechs-high-end-webcam-an-all-inclusive-review-for-2024/"><u>Logitech’s High-End Webcam  An All-Inclusive Review for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-win-1011-domain-services-printer-fixation-techniques/"><u>Mastering Win 10/11 Domain Services Printer Fixation Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/new-era-of-productivity-microsofts-ai-integration-in-windows-11-taskbar/"><u>New Era of Productivity: Microsoft's AI Integration in Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windows-for-productivity-add-software-actions/"><u>Optimizing Windows for Productivity: Add Software Actions</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-common-windows-error-with-lsassexe/"><u>Overcoming Common Windows Error with lsass.exe</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-operation-failure-code-0x0000011b-in-win11-system/"><u>Overcoming Operation Failure Code 0X0000011B in Win11 System</u></a></li>
<li><a href="https://windows11.techidaily.com/precision-and-convenience-meet-with-our-winning-window-timers-list/"><u>Precision & Convenience Meet With Our Winning Window Timers List</u></a></li>
<li><a href="https://windows11.techidaily.com/purpose-behind-visual-cplusplus-distributable/"><u>Purpose Behind Visual C++ Distributable</u></a></li>
<li><a href="https://windows11.techidaily.com/re-establishing-classic-navigation-in-win-11/"><u>Re-Establishing Classic Navigation in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/rebooting-to-reactivate-dormant-snapshots/"><u>Rebooting to Reactivate Dormant Snapshots</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-missing-apps-icon-issue/"><u>Rectifying Missing Apps Icon Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagining-the-look-of-basic-text-editor-in-windows-11/"><u>Reimagining the Look of Basic Text Editor in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/restarting-windows-security-fix-for-flawed-functions/"><u>Restarting Windows Security: Fix for Flawed Functions</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-a-smooth-setup-for-microsoft-works-in-w11/"><u>Securing a Smooth Setup for Microsoft Works in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-repair-disk-errors-in-windows-os/"><u>Steps to Repair Disk Errors in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-navigation-through-bluescreenview-features/"><u>Stepwise Navigation Through BlueScreenView Features</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-windows-install-9-methods-to-bypass-verification-lag/"><u>Streamlining Windows Install: 9 Methods to Bypass Verification Lag</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-your-wi-fi-networks-usage-metrics-with-windows-11/"><u>Tailoring Your Wi-Fi Network's Usage Metrics with Windows 11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-essential-meme-blueprint-building-impactful-gifs/"><u>The Essential Meme Blueprint  Building Impactful GIFs</u></a></li>
<li><a href="https://windows11.techidaily.com/top-7-windows-cryptography-tools-under-156-chars/"><u>Top 7 Windows Cryptography Tools (Under 156 Chars)</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-9-nokia-150-2023-monitoring-apps-for-parental-controls-drfone-by-drfone-virtual-android/"><u>Top 9 Nokia 150 (2023) Monitoring Apps for Parental Controls | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-absence-of-files-on-windows-11/"><u>Troubleshooting Absence of Files on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/uncover-and-fix-hidden-5ghz-connections-in-windows-11-easily/"><u>Uncover & Fix Hidden 5GHz Connections in Windows 11 Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-your-pcs-true-power-with-enhanced-vram-settings-in-windows-10-and-11/"><u>Unleash Your PC's True Power with Enhanced VRAM Settings in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-memory-write-hitches-in-windows/"><u>Unraveling 'Memory Write' Hitches in Windows</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-to-do-if-your-apple-iphone-11-pro-max-has-bad-esn-or-blacklisted-imei-by-drfone-ios/"><u>What to do if your Apple iPhone 11 Pro Max has bad ESN or blacklisted IMEI?</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-the-ipogo-get-you-banned-and-how-to-solve-it-on-vivo-y55s-5g-2023-drfone-by-drfone-virtual-android/"><u>Will the iPogo Get You Banned and How to Solve It On Vivo Y55s 5G (2023) | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>