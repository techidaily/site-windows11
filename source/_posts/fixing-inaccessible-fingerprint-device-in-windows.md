---
title: Fixing Inaccessible Fingerprint Device in Windows
date: 2024-08-31T22:13:49.006Z
updated: 2024-09-01T22:13:49.006Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Inaccessible Fingerprint Device in Windows
excerpt: This Article Describes Fixing Inaccessible Fingerprint Device in Windows
keywords: Fix Windows Fingerprint Errors,Access Windows ID Scanner,Resolve ID Reader Failures,Unlock Biometric Lock Issues,Address TouchID Glitches,Troubleshoot Fingerprint Sensor,Remedy InkPrint Recognition Problems
thumbnail: https://thmb.techidaily.com/6509a41b9c53db282ea10c9960943cd0bc0006742138202a2ce5d3d561a1baf2.jpg
---

## Fixing Inaccessible Fingerprint Device in Windows

 If you receive an error message that says, "we couldn't find a fingerprint scanner compatible with Windows Hello Fingerprint" when trying to set up Windows Hello fingerprint login, then your device either doesn't support fingerprint recognition, the fingerprint scanner (or reader) isn't working correctly, or Windows is unable to detect it.

 Windows may not detect the fingerprint scanner for several reasons: the fingerprint reader may have malfunctioned, the biometric drivers could be outdated or corrupted, or biometric recognition could be disabled in the BIOS. If you're tired of dealing with this problem, try these solutions.

## 1\. Ensure Your Device Supports Fingerprint Recognition

![blue graphic of digital fingerprint scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/blue-finger-scan.jpg)

 The Windows Hello fingerprint recognition feature requires your device to have a fingerprint reader. If you encounter the error "we could not find a fingerprint scanner compatible with Windows Hello Fingerprint" when setting up fingerprint recognition for the first time, make sure your device is equipped with a fingerprint reader compatible with Windows Hello.

 Usually, it is located near (or on) the power button or in the empty space above or below the keyboard. Look around and see if you can find a fingerprint reader. If you fail to find it, check your device's specifications on the manufacturer's website to see if it has a fingerprint scanner.

 If your device does not have a fingerprint reader, you cannot enable biometric authentication on it. However, if your device has a scanner, and you've used it many times before, ensure that it is working correctly.

## 2\. Make Sure the Fingerprint Reader Is Working Properly

![security fingerprint on keyboard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/data-1590455_1920-1.jpg)

 If your device has a fingerprint sensor, but Windows is unable to detect it, ensure the sensor hasn't gone bad. To test the fingerprint reader, sign in to another app where you've set up biometric login. If that app fails to accept biometric verification, use a dry cloth to wipe the dust off your fingerprint scanner.

 After that, try scanning your finger again. If the app fails to recognize the fingerprint scan even after thoroughly cleaning it, there is probably an issue with the scanner. So, have your device inspected by a technician. However, if the scanner works fine on other apps but not when you set up Windows Hello fingerprint login, then apply the remaining fixes.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Roll Back the Driver or the Latest Windows Update

 Have you encountered the error under discussion after updating the biometric driver or installing a Windows update recently? If this is the case, you should roll back these updates. Don't know how to do that? Our guide on[how to roll back a driver update on Windows](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) describes the process. If you want to roll back a Windows update, then you need to[uninstall the most recent Windows Update](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) .

 Once you've undone both driver and Windows updates, try setting up Windows Hello biometric login again. If you continue to experience the same problem after rolling back these updates, it suggests that undoing these updates hasn't made a difference. In that case, you should reinstall the drivers and Windows update.

## 4\. Ensure the Windows Biometric Service Is Configured Properly

 When the Windows biometric service is disabled, Windows Hello fingerprint recognition won't work. To ensure this service is enabled and configured correctly, follow these steps:

1. Type**"Services"** in Windows Search and open the**Services** app.  
![Open Services App From Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/1-open-services-app-from-windows-search.jpg)
2. Locate**Windows Biometric Service** .  
![Locate Windows Biometric Service in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/2-locate-windows-biometric-service-in-windows-services-app.jpg)
3. If you see**"Running"** next to this service in the**Status** column, it's already running. If not, it's disabled.
<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. In either case, right-click the service and select**Properties** .  
![Go to Properties of Windows Biometric Service in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3-go-to-properties-of-windows-biometric-service-in-windows-services-app.jpg)
5. Click on the dropdown menu next to**Startup type** and select**Automatic** .  
<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
![Select Automatic From the Startup Type Dropdown Menu in the Properties Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/4-select-automatic-from-the-startup-type-dropdown-menu-in-the-properties-window.jpg)
6. If it's already selected, click the**Stop** button to stop the service and then click**Start** again to restart it.  
![Click Start Button to Restart the Service in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/5-click-start-button-to-restart-the-service-in-windows-services-app.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
## 5\. Update or Reinstall the Biometric Drivers

 If the biometric service is already enabled, yet the fingerprint recognition feature isn't working, the biometric drivers could be outdated or corrupt. To ensure that isn't the case, update the biometric device drivers. To do so, follow these steps:

1. Type**"Device Manager"** in Windows Search and open the**Device Manager** app.
2. Expand the**Biometric devices** category.
3. Right-click on your fingerprint scanner device and select**Update driver** .  
![Update the Fingerprint Scanner Device in Windows Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/6-update-the-fingerprint-scanner-device-in-windows-device-manager.jpg)
4. Then, click on**Search automatically for drivers** .
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->

 If updating the drivers does not fix the problem, right-click the biometric device again and select**Uninstall device** . After uninstalling the drivers, reboot your device, and Windows will automatically install them again. If you prefer, you can also download the relevant drivers from the manufacturer's website and install them manually.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
## 6\. Disable Fast Startup

 According to some users on a[Microsoft community thread](https://answers.microsoft.com/en-us/windows/forum/all/fingerprint-reader-not-working/95cc0aef-2822-4b51-9f77-8697e6ace897) , disabling the Fast Startup feature has solved fingerprint recognition issues on their devices. Although Fast Startup speeds up your device's boot process, turning it on is known to cause unforeseen problems.

 So, if you also keep this feature enabled on your device, disable it to see if it makes a difference. Don't know how to do that? Refer to our guide on[enabling or disabling Fast Startup on Windows 11](https://www.makeuseof.com/windows-11-turn-on-or-off-fast-startup/) .

## 7\. Ensure the Biometric Reader Isn't Disabled in BIOS

 Some laptops allow users to disable the fingerprint reader in BIOS. If you're setting up a fingerprint login for the first time and getting the error, ensure the fingerprint scanner isn't disabled in BIOS. Accessing BIOS and navigating to the option to enable or disable the biometric device varies between manufacturers.

 If you need guidance on accessing the BIOS and enabling the biometric device, visit your laptop manufacturer's website.

## 8\. When Nothing Else Works…

 If nothing else works, run the Hardware and Devices troubleshooter, enable biometrics in the Local Group Policy Editor, and check for account-specific issues. If these steps fail to resolve the issue, perform a system restore as a last resort. Our guide on[fixing Windows Hello fingerprint recognition](https://www.makeuseof.com/windows-hello-fingerprint-not-working/) explains how to make the above-mentioned changes.

## Get Rid of Annoying Fingerprint Recognition Errors

 If you encounter an error when setting up Windows Hello fingerprint recognition, it does not mean the feature can't be used. If your device supports biometric authentication, the above fixes will help you resolve the annoying error.

 If you are setting up a fingerprint login for the first time, make sure you do it correctly. Otherwise, you'll be constantly annoyed by the bothersome errors when using this fantastic feature.


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
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-enriched-browsing-experience-with-these-top-5-chrome-tools/"><u>[New] 2024 Approved  Enriched Browsing Experience with These Top 5 Chrome Tools</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-online-add-on-social-media-story-vault/"><u>[New] Online Add-On  Social Media Story Vault</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-election-enthusiasts-essentials-quintessential-voting-games/"><u>[Updated] Election Enthusiasts' Essentials  Quintessential Voting Games</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-optimizing-worker-output-the-influence-of-office-environment/"><u>[Updated] Optimizing Worker Output  The Influence of Office Environment</u></a></li>
<li><a href="https://iphone-location.techidaily.com/a-full-review-for-itools-virtual-location-and-top-5-alternatives-for-apple-iphone-12-pro-maxipad-drfone-by-drfone-virtual-ios/"><u>A Full Review for iTools Virtual Location and Top 5 Alternatives For Apple iPhone 12 Pro Max/iPad | Dr.fone</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/ai-innovation-duels-googles-gemini-vs-openais-chatgpt/"><u>AI Innovation Duels: Google's Gemini Vs. OpenAI’s ChatGPT</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-for-rectifying-display-driver-crashes/"><u>Essential Tips for Rectifying Display Driver Crashes</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-absent-mfc71udll-steps-for-windows-users/"><u>Fixing Absent Mfc71u.dll: Steps for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/gaming-without-the-heat-wave-tips-for-laptop-users/"><u>Gaming Without the Heat Wave: Tips for Laptop Users</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-disable-hyper-v-in-windows-11/"><u>Guide to Disable Hyper-V in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-keep-search-invisible-in-win-11-taskbar/"><u>How to Keep Search Invisible in Win 11 Taskbar</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-pause-life360-location-sharing-for-nokia-150-2023-drfone-by-drfone-virtual-android/"><u>How To Pause Life360 Location Sharing For Nokia 150 (2023) | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-repair-auto-detection-failure-in-windows-proxies/"><u>How to Repair Auto-Detection Failure in Windows Proxies</u></a></li>
<li><a href="https://windows11.techidaily.com/improve-efficiency-with-top-5-clock-screensaver-apps/"><u>Improve Efficiency with Top 5 Clock Screensaver Apps</u></a></li>
<li><a href="https://driver-install.techidaily.com/install-compatible-drivers-for-amd-radeon-200-series/"><u>Install Compatible Drivers for AMD Radeon 200 Series</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-auto-shutdown-for-idle-windows-1011-machines/"><u>Mastering Auto-Shutdown for Idle Windows 10/11 Machines</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/maximizing-impact-how-to-broadcast-effectively-via-streams/"><u>Maximizing Impact  How to Broadcast Effectively via Streams</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-recover-notification-banners/"><u>Methods to Recover Notification Banners</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-to-battery-saving-feature-in-windows/"><u>Navigating to Battery Saving Feature in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-security-updating-user-passwords-on-win-11/"><u>Optimizing Security: Updating User Passwords on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-update-error-0x800736cc-fix-guide/"><u>Overcoming Windows Update Error: 0X800736CC Fix Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/post-maintenance-world-what-comes-next-after-windows-781/"><u>Post-Maintenance World: What Comes Next After Windows 7/8.1?</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-normal-operations-for-deleted-characters/"><u>Restoring Normal Operations for Deleted Characters</u></a></li>
<li><a href="https://windows11.techidaily.com/skyrocket-productivity-with-mastered-windows-shortcut-combos/"><u>Skyrocket Productivity with Mastered Windows Shortcut Combos</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/snapchats-creative-frontier-mastering-more-than-120-stories-with-individual-flair/"><u>Snapchat's Creative Frontier  Mastering More than 120 Stories with Individual Flair</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-activate-windows-11-family-safeguards/"><u>Steps to Activate Windows 11 Family Safeguards</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-for-troubleshooting-the-most-elusive-win10-blues/"><u>Tactics for Troubleshooting the Most Elusive Win10 Blues</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-to-conceal-windows-11s-task-control-icon/"><u>Tactics to Conceal Windows 11'S Task Control Icon</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-to-overcome-disappearing-ubisoft-game-launcher/"><u>Tactics to Overcome Disappearing Ubisoft Game Launcher</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-repairing-disp-settings-missing-error/"><u>Tips for Repairing Disp Settings Missing Error</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/transitioning-to-windows-11-a-step-by-step-guide/"><u>Transitioning to Windows 11  A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/triggers-for-authentication-control-screen-windows-11/"><u>Triggers for Authentication Control Screen (Windows 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-disk-space-through-powershell-metrics-analysis/"><u>Understanding Disk Space Through PowerShell Metrics Analysis</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-microsoft-shop-glitch-0x80131500/"><u>Unraveling Microsoft Shop Glitch #0X80131500</u></a></li>
</ul></div>
