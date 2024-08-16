---
title: Unlocking Battle.net Accessibility on 10/11 Systems
date: 2024-08-15T15:51:20.240Z
updated: 2024-08-16T15:51:20.240Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlocking Battle.net Accessibility on 10/11 Systems
excerpt: This Article Describes Unlocking Battle.net Accessibility on 10/11 Systems
keywords: Battle.Net Access,Unlock Net Game,Free Battle Access,Net Play Integration,Accessible Gaming,Bypass System Restrictions,Enhance Net Play
thumbnail: https://thmb.techidaily.com/d046e3f1a50f3eab0c2328a8c65f9cdfeb961e04c1487439cf5694d3a9ccaf02.jpg
---

## Unlocking Battle.net Accessibility on 10/11 Systems

 Battle.net is game launcher software with which users install and play Call of Duty: Warzone, Hearthstone, World of Warcraft, and Overwatch. However, users can’t launch Blizzard games when the Battle.net software doesn’t open on Windows. Battle.net may or may not display an error message when it doesn’t open, but that software doesn’t start either way.

 You can probably resolve whatever Battle.net startup issue you’re trying to fix in Windows, so long as your PC meets the software’s minimum system requirements. These general fixes can resolve a wide variety of Battle.net startup errors or crashes in a Windows 11/10.

## 1\. Set Battle.net to Run With Admin Rights

 This is a simple potential fix for Battle.net not opening that some users have confirmed works. Setting Battle.net to run as administrator will give that software elevated system access, which can resolve permission issues. You can configure Battle.net to always run with administrative rights like this:

1. Open Battle.net’s installation directory (folder) within File Explorer.
2. Next, click the**Battle.net Launcher.exe** file with your right mouse button and select**Properties** .
3. Click**Compatibility** on the Battle.net Launcher.exe Properties window.
4. Select**Run this program as administrator** if that checkbox isn’t selected.  
![The Run this program as an administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/run-this-program-as-administrator-option.jpg)
5. Press the Properties window’s**Apply** button.

 In addition, running the software in compatibility mode might help some users fix Battle.net not opening. You can do that by selecting the**Run this program in compatibility mode** option on the same**Compatibility** tab. Choose Windows 8 on the drop-down menu.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
## 2\. Delete the Battle.net and Blizzard Entertainment Data Folders

 Battle.net and Blizzard Entertainment are two cache folders for Blizzard’s game launcher software. The Battle.net software often doesn’t start right when those folders contain corrupted data. Deleting those directories will clear Battle.net’s cache.

This is how you can erase those folders in Windows 11/10:

1. First, make sure there aren’t any Battle.net background processes running by [opening Task Manager’s Process tab](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) . Disable any Battle.net processes you see there by selecting them and clicking**End task** .
2. Hold the**Windows** keyboard key and press**E** to view the Explorer file and folder manager.
3. Clear Explorer’s folder path bar, and input this directory location there: C:\\ProgramData  
![The Blizzard Entertainment folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/blizzard-entertainment-folder.jpg)
<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Right-click the Battle.net directory and select the**Delete** context menu option.  
![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-delete-button.jpg)
5. Next, erase the Blizzard Entertainment folder.
6. Try opening Battle.net again.

 This should hopefully clear any cache issues and Battle.net should open correctly.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
## 3\. Check the Secondary Logon Service Is Enabled

 The Secondary Logon service enables the starting of processes with alternative types of user credentials. That’s a required prerequisite service for Battle.net’s Blizzard agent. So, check Secondary Login is enabled and running like this:

1. To open Services, click the search box or magnifying glass on your Windows 11/10 taskbar. Type**services.msc** in the search box, and select the Services app.
2. Double-click**Secondary Logon** to view the properties window for that service.  
![The Secondary Logon service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/secondary-logon-service.jpg)
3. Set the**Startup type** option to**Automatic** .
4. Click the**Start** service button for Secondary Logon.  
![The Secondary Logon Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-logon-properties-window.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Remember to select**Apply** to save the setting.
6. Select**OK** to exit the Secondary Logon Properties window.
7. Click**Restart** on the Start menu in Windows 11/10.

 If you find Secondary Logon is already enabled, restart the service instead. Right-click Secondary Logon on the Services window to select**Restart** . Or you can click**Stop** and**Start** in the service’s properties window.

## 4\. Turn Off the Windows Defender Firewall

 Windows Defender Firewall will block Battle.net from connecting with Blizzard services if that software isn’t permitted through it. To test if that firewall is blocking the Battle.net client, temporarily disable it in the following steps:

1. First, open WDF in the Control Panel with a method in our guide for opening the Windows Defender Firewall applet.
2. Select the**Turn Windows Defender Firewall on or off** navigation option on the left of the applet.  
![The Windows Defender Firewall applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/windows-defender-control-panel-applet.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
3. Click the**Turn off Windows Defender Firewall** options for both the public and private network settings.  
![The Turn off Windows Defender Firewall radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/turn-off-windows-defender-firewall-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
4. Select**OK** to save the new WDF options.
5. Try opening Battle.net again with the firewall disabled.

 If Battle.net now starts, check Windows Defender Firewall’s app permission settings. Make sure the Battle.net software is allowed through that firewall. Check out our article about [allowing apps through the Windows Firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) for full instructions. Then you can turn WDF back on.

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Disable Third-Party Antivirus and Firewall Software

 Some third-party antivirus and firewall software can also block Battle.net from running. Antivirus utilities sometimes wrongly identify legitimate programs to be malware. So, temporarily disable third-party antivirus tools or firewalls before selecting to launch Battle.net if you don’t want to uninstall anything.

 You can usually find options for disabling third-party antivirus software on their context menus. So, right-click an antivirus icon in the system tray and look for an option to disable or turn off its shield on the menu that opens. If that works, you’ll know what’s causing the issue. Whitelist Battle.net in your antivirus tool’s exclusion settings.

## 6\. Disable the Proxy Server

 Proxy servers conflict with Battle.net’s login module, which can prevent the software from launching. Even if you can’t recall enabling a proxy server yourself, double-check the proxy server setting isn’t selected in Windows. You can disable the proxy server as follows:

1. Bring up the file and app search box in Windows.
2. Enter**inetcpl.cpl** in the Type here to search text box.
3. Select**inetcpl.cpl** to view Internet Properties.
4. Click**Connections** to access network options.
5. Next, click**LAN settings** to view a Local Area Network (LAN) window.  
![The LAN settings button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/LAN-settings-button.jpg)
6. Uncheck (deselect) the**Use a proxy server** option if its checkbox is selected.  
![The Use a proxy server checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-use-a-proxy-server-checkbox.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
7. Press the**OK > Apply** buttons.

 Malware can activate a proxy server setting on Windows. If you discover a proxy server enabled, but didn’t select it yourself, consider manually running an antivirus scan. Our [Windows Security (Defender) guide](https://www.makeuseof.com/windows-11-quick-security-guide/) tells you how to run a scan with the built-in antivirus utility on Windows.

## 7\. Set Windows 11/10 to Clean Boot

 Clean-booting Windows is when you boot a PC without any third-party startup programs or services automatically starting. Configuring a clean boot disables all such startup apps and services. Our [guide for performing a clean boot on Windows 11](https://www.makeuseof.com/clean-boot-windows-11/) provides details about how to remove all third-party software and services from the startup.

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-services-tab.jpg)

 After setting a clean boot, restart your PC and try launching Battle.net. Did that potential resolution work? If it did, clean booting likely eliminated a program or service conflicting with Battle.net. Then you can keep the boot configuration as it is or attempt to figure out what software or service caused the issue.

## 8\. Reinstall the Battle.net Software

 Finally, reinstall Battle.net Launcher if all else fails. Reinstalling that software will replace its files and ensure you’re utilizing the latest version. That won’t uninstall games installed with Battle.net.

![The Programs and Features Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-programs-and-features-applet.jpg)

 You can remove Battle.net in Control Panel’s Programs and Features applet, as outlined in our [guide for uninstalling Windows software](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) . After uninstalling the game launcher, open the [Battle.net desktop app](https://www.blizzard.com/en-us/apps/battle.net/desktop) download page; click**Download for Windows** on that page. Then double-click the**Battle.net-Setup.exe** file in whatever folder it downloaded to, and go through the setup wizard to install.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Enjoy Blizzard Battle.net Games Again

 When you’ve got Battle.net up and running again, you’ll be able to download, launch, and play Blizzard games. As there are many potential causes for Battle.net not starting, we can’t guarantee the solutions in this guide will resolve all startup issues for that software.

 However, those potential resolutions will address the most common causes for Battle.net not opening in Windows 11 and 10\. So, there’s a very good chance at least one will kick-start Blizzard’s gaming client on your PC.

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
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-enhance-your-watch-experience-with-faster-instagram-videos/"><u>[New] 2024 Approved  Enhance Your Watch Experience with Faster Instagram Videos</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-choreograph-comic-characters/"><u>[New] Choreograph Comic Characters</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-secrets-back-on-snapchat-screen/"><u>[Updated] 2024 Approved  Secrets Back on Snapchat Screen</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-immediate-cessation-of-recordings-in-qt-app/"><u>[Updated] Immediate Cessation of Recordings in QT App</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-mastering-the-art-of-screen-enhancement-in-teams-for-2024/"><u>[Updated] Mastering the Art of Screen Enhancement in Teams for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-video-valedictions-sign-off-strategies-for-online-platforms/"><u>[Updated] Video Valedictions  Sign-Off Strategies for Online Platforms</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-is-photoshops-image-smoothing-worth-the-hype/"><u>2024 Approved  Is Photoshop's Image Smoothing Worth the Hype?</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-techniques-for-successful-photo-background-alteration-on-fb/"><u>2024 Approved  Techniques for Successful Photo Background Alteration on FB</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatgpt-as-your-companer-a-solution-to-loneliness-and-social-disconnection/"><u>ChatGPT as Your Companer: A Solution to Loneliness and Social Disconnection</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/content-creators-arena-vs-beta-studio-evolutionary-path-for-2024/"><u>Content Creator's Arena  Vs. Beta Studio Evolutionary Path for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/effortless-setup-for-a-brand-new-canon-printer/"><u>Effortless Setup for a Brand-New Canon Printer</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-fixes-for-frozen-terminal-apps-on-windows/"><u>Essential Fixes for Frozen Terminal Apps on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-to-correct-0x8009030e-in-virtualization/"><u>Essential Steps to Correct 0X8009030E in Virtualization</u></a></li>
<li><a href="https://buynow-info.techidaily.com/expert-analysis-of-the-uniden-r3-superior-quality-and-extended-detection-range/"><u>Expert Analysis of the Uniden R3: Superior Quality and Extended Detection Range</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-correcting-invalid-profiles-on-windows-oses/"><u>Guide to Correcting Invalid Profiles on Windows OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-bypass-printer-settings-on-windows-11/"><u>How to Bypass Printer Settings on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-windows-update-asking-to-update-and-restart/"><u>How to Stop Windows Update Asking to Update and Restart</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-apple-iphone-xs-max-without-swiping-up-6-ways-by-drfone-ios/"><u>How To Unlock Apple iPhone XS Max Without Swiping Up? 6 Ways</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-resolution-for-windows-network-proxy-issue/"><u>Immediate Resolution for Windows Network Proxy Issue</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-best-3-software-to-transfer-files-tofrom-your-samsung-galaxy-a05s-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Best 3 Software to Transfer Files to/from Your Samsung Galaxy A05s via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-building-a-solid-foundation-youtube-video-script-basics/"><u>In 2024, Building a Solid Foundation  YouTube Video Script Basics</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-laughter-lane-top-7-comedy-content-concepts-for-vloggers/"><u>In 2024, Laughter Lane  Top 7 Comedy Content Concepts for Vloggers</u></a></li>
<li><a href="https://windows11.techidaily.com/independent-windows-version-improvement-tactics/"><u>Independent Windows: Version Improvement Tactics</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-the-absence-of-rockalldlldll-windows/"><u>Mending the Absence of Rockalldll.dll (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-display-glitches-in-windows-os/"><u>Overcoming Display Glitches in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/peering-into-microsofts-updating-mechanics-for-os/"><u>Peering Into Microsoft's Updating Mechanics for OS</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-tips-for-repairing-video-playback-errors/"><u>Quick Tips for Repairing Video Playback Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-resolving-iphone-photos-import-error-in-windows-pcs/"><u>Quick-Fix: Resolving iPhone Photos Import Error in Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-device-errors-in-windows-11/"><u>Remedying Device Errors in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-steam-data-write-functionality-in-windows/"><u>Restoring Steam Data Write Functionality in Windows</u></a></li>
<li><a href="https://sound-issues.techidaily.com/restoring-your-hearing-in-apex-legends-expert-tips-to-fix-sound-issues-and-enjoy-gameplay/"><u>Restoring Your Hearing in Apex Legends: Expert Tips to Fix Sound Issues and Enjoy Gameplay</u></a></li>
<li><a href="https://windows11.techidaily.com/rethinking-taskbar-design-top-strategies-to-elevate-windows-11-experience/"><u>Rethinking Taskbar Design: Top Strategies to Elevate Windows 11 Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionize-your-ad-targeting-strategies-with-innovative-insights-from-cookiebot/"><u>Revolutionize Your Ad Targeting Strategies with Innovative Insights From Cookiebot</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-installation-of-intel-wi-fi-adapters-for-gaming/"><u>Seamless Installation of Intel Wi-Fi Adapters for Gaming</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-ways-to-elude-windows-11-screensaver/"><u>Swift Ways to Elude Windows 11 Screensaver</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/system-service-exception-on-windows-10-solved/"><u>System Service Exception on Windows 10 [Solved]</u></a></li>
<li><a href="https://windows11.techidaily.com/transition-without-subsys-optimizing-for-upcoming-android-solutions/"><u>Transition Without Subsys: Optimizing for Upcoming Android Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-invisible-networks-microsoft-fix-it-guide/"><u>Unblocking Invisible Networks: Microsoft Fix-It Guide</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-pictures-from-oppo-find-n3-by-fonelab-android-recover-pictures/"><u>Undelete lost pictures from Oppo Find N3.</u></a></li>
<li><a href="https://windows11.techidaily.com/unobstructed-wireless-resurrecting-disconnected-networks/"><u>Unobstructed Wireless: Resurrecting Disconnected Networks</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-riddle-of-windows-winerror-woes/"><u>Unraveling the Riddle of Window's WinError Woes</u></a></li>
<li><a href="https://techidaily.com/update-your-hardware-drivers-with-device-manager-in-windows-11-and-10-and-7-by-drivereasy-guide/"><u>Update your hardware drivers with Device Manager in Windows 11 & 10 & 7</u></a></li>
<li><a href="https://howto.techidaily.com/vivo-x90s-not-connecting-to-wi-fi-12-quick-ways-to-fix-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Vivo X90S Not Connecting to Wi-Fi? 12 Quick Ways to Fix | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/wins-cmd-customize-to-reflect-your-style/"><u>Win's CMD: Customize to Reflect Your Style</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/worldwide-top-earners-in-the-streaming-sphere/"><u>Worldwide Top Earners in the Streaming Sphere</u></a></li>
<li><a href="https://windows11.techidaily.com/your-guide-to-selecting-a-new-window-home-or-premium-edition/"><u>Your Guide to Selecting a New Window : Home or Premium Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/zero-to-win-efficiently-handling-app-issues-in-windows-11/"><u>Zero-to-Win: Efficiently Handling App Issues in Windows 11</u></a></li>
</ul></div>
