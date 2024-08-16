---
title: Tackling Error 0X80042306 on Windows to Reset Successfully
date: 2024-08-15T16:05:43.479Z
updated: 2024-08-16T16:05:43.479Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling Error 0X80042306 on Windows to Reset Successfully
excerpt: This Article Describes Tackling Error 0X80042306 on Windows to Reset Successfully
keywords: WinErrorReset,X80042306 Fix,0X80042306 Solve,Windows Error Reset,System XP Error,Successful Reset Window,OS Error Code 0X80042306
thumbnail: https://thmb.techidaily.com/109f8e41f016b710f8a0ad598776af950e5e0ec716fb01a083b32b51c83dd241.jpg
---

## Tackling Error 0X80042306 on Windows to Reset Successfully

 The error code 0x80042306 occurs when attempting to create a restore point in Windows. It prevents the creation of new restore points in the system and typically occurs when your system does not have sufficient free space, there is a problem with the Volume Shadow Copy service (VSS), or a background process is conflicting with the restore utility.

 Below, we talk about the different troubleshooting methods you can try to fix the system restore error 0x80042306 in Windows. We recommend booting into the administrator account before you proceed.

## 1\. Make Sure You Have Sufficient Space

 Restore points require free space on the disk they are stored. This amount of space required by a restore point typically depends on on the size and complexity of your system configuration.

 If you do not have sufficient space on the disk, the restore utility is likely to return a 0x80042306 error. This is why, we recommend getting started by making sure that enough free space for the System Restore to function correctly. You can delete unnecessary items to increase the space manually, or [use the Disk Cleanup](https://www.makeuseof.com/tag/best-way-clean-windows-10-step-step-guide/) utility that is offered by Microsoft by default.

 Alternatively, you can also increase the amount of disk space allocated for System Restore in the System Protection settings. Here is how you can do that:

1. Type "Create a restore point" in the Windows search utility and click**Open** .
2. In the following dialog, head over to the**System Protection** tab.
3. Click on the**Configure** button and use the Max usage to slider to adjust the disk percentage according to your preference.  
![Adjust the Max usage slider](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restore-point-usage.jpg)
4. Click**Apply** \>**OK** to save the changes.

 Once the changes are made, check if you can now create a restore point without any issues.

<!-- affiliate ads begin -->

<!-- affiliate ads end -->
## 2\. Restart the Volume Shadow Copy Service

 You might also be facing the problem if the Volume Shadow Copy service is disabled or simply not functioning properly.

 This service allows the creation of backup copies for files and volumes in Windows. It is used to by the restore utility to create snapshots of the items that are being backed up and if it fails to work due to any reason, you might encounter the problem at hand.

 To ensure this service is working properly, you can restart it using the Services utility. Follow the steps below to proceed:

1. Press the**Win** +**R** keys together to open Run.
2. Type "services.msc" in Run and click**Enter** .
3. In the services window, scroll down to locate the**Volume Shadow Copy** service and right-click on it.  
![Volume Shadow Copy service in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/volume-shadow-copy.jpg)
4. Choose**Properties** from the context menu.
5. Now, click on the**Stop** button, wait for a few seconds, and hit**Start** again.
6. Make sure the Startup type is set to**Automatic** .  
![Start the VSS service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/start-vss-service.jpg)
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
7. Finally, click**Apply** \>**OK** to save the changes.

 Do the same for the Windows Backup service and check if the issue is resolved.

## 3\. Re-Register VSS Components

 If restarting the Volume Shadow Copy service did not work, then you can also try re-registering the VSS components via Command Prompt.

Here is how to proceed:

1. Press the**Win** +**R** keys together to open Run.
2. Type "cmd" in Run and press the**Ctrl** +**Shift** +**Enter** keys together to open Command Prompt as an administrator.
3. Click**Yes** in the User Account Control prompt.
4. Now, execute the following commands one by one:  
`cd /d %windir%\system32net stop vssnet stop swprvregsvr32 /s ole32.dllregsvr32 /s oleaut32.dllregsvr32 /s vss_ps.dllvssvc /registerregsvr32 /s /i  

swprv.dllregsvr32 /s /i eventcls.dllregsvr32 /s es.dllregsvr32 /s stdprov.dllregsvr32 /s vssui.dllregsvr32 /s msxml.dllregsvr32 /s  

msxml3.dllregsvr32 /s msxml4.dllvssvc /registernet start swprvnet start vss`
5. Once you have re-registered VSS components, close Command Prompt and try creating a restore point again.

 If an issue within the VSS components was causing the problem, restarting the components should fix it.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Create a Restore Point in Safe Mode

 In some cases, a conflicting background process can also prevent the System Restore utility from creating a restore point successfully. The best way to ensure there are no applications or programs in the background interrupting the functionality of System Restore, try creating a restore point in Safe Mode.

 This mode launches Windows with a minimal set of drivers and services, which can help isolate the issue and prevent any conflicts that may be occurring in normal mode.

Here is how you can boot in Safe Mode:

1. Type "System Configuration" in Windows search and click**Open** .
2. Head over to the**Boot** tab and under Boot Options, checkmark the Safe Boot option.
3. Choose**Minimal** and click on**Apply** \>**OK** to save the changes.  
![Minimal mode of Safe Boot](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/msconfig-boot-safe-mode-minimal.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->

 You can now restart your computer and upon reboot, you should enter the Safe Mode automatically. Try recreating a restore point and check if the problem is resolved.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 5\. Scan the System For Corruption Errors

![Running Sfc scan in CMD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/running-sfc-scan.jpg)

 The System Restore utility itself might be dealing with a corruption error, which is preventing it from functioning properly.

 To fix any corrupt system files, we suggest using the System File Checker (SFC) and Deployment Image Servicing and Management (DISM) tools. SFC works by scanning the protected system files for underlying problems. If an issue is discovered, it will replace the faulty file with its healthier cached counterpart.

 DISM, on the other hand, works by repairing corrupt system images. We have a guide on [how to use SFC and DISM in Windows](https://www.makeuseof.com/windows-built-in-repair-tools/) which you can refer to, to perform the steps correctly.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->
## System Restore Back On Track

 The System Restore utility in Windows is a powerful tool that can save you from losing important data in case of unexpected system issues. That said, it can be annoying if you cannot create a restore point easily, especially when you are trying to do it before performing a critical action.

 By following the methods outlined in this guideline, you can diagnose the error and take necessary steps to resolve it. We recommend making sure all the relevant services stay enabled, and your system is up-to-date to avoid any such issues in the future.


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
<li><a href="https://youtube-webster.techidaily.com/024-approved-audiovisual-powerhouses-select-best-laptops-for-editing/"><u>[New] 2024 Approved  Audiovisual Powerhouses  Select Best Laptops for Editing</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-free-toolkit-for-unrestricted-story-archiving/"><u>[New] 2024 Approved  FREE Toolkit for Unrestricted Story Archiving</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-superior-live-streaming-and-conferencing-apps/"><u>[New] 2024 Approved  Superior Live Streaming & Conferencing Apps</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-filmography-foundation-answer-hub/"><u>[New] Filmography Foundation  Answer Hub</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-in-2024-operational-handling-of-srt-in-oses/"><u>[New] In 2024, Operational Handling of SRT in OSes</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-the-ultimate-list-for-choosing-your-camera-and-gear/"><u>[New] In 2024, The Ultimate List for Choosing Your Camera & Gear</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-professional-editors-showdown-filmora-vs-democracy-creator-features/"><u>[New] Professional Editors Showdown  Filmora Vs. Democracy Creator Features</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-transform-your-farm-life-with-the-best-7-14-upgrades/"><u>[New] Transform Your Farm Life with the Best #7-14 Upgrades</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-explore-artistic-possibilities-premier-android-graphics-app-selection/"><u>[Updated] Explore Artistic Possibilities  Premier Android Graphics App Selection</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-youtubes-golden-age-of-video-gamers/"><u>[Updated] YouTube's Golden Age of Video Gamers</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-effortlessly-record-circles-iphone-techniques-for-fb-feed/"><u>2024 Approved  Effortlessly Record Circles  IPhone Techniques for FB Feed</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-in-depth-guide-to-game-capturing-roblox-and-mac-integration/"><u>2024 Approved  In-Depth Guide to Game Capturing  Roblox & Mac Integration</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-stunning-feats-in-figure-skating-22-moments/"><u>2024 Approved  Stunning Feats in Figure Skating '22 Moments</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-superior-iphone-editor-tools-pick-between-cameo-and-filmorago/"><u>2024 Approved  Superior iPhone Editor Tools  Pick Between Cameo and FilmoraGo</u></a></li>
<li><a href="https://location-fake.techidaily.com/4-methods-to-turn-off-life-360-on-vivo-x90s-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>4 Methods to Turn off Life 360 On Vivo X90S without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/a-perfect-guide-to-remove-or-disable-google-smart-lock-on-xiaomi-13t-pro-by-drfone-android/"><u>A Perfect Guide To Remove or Disable Google Smart Lock On Xiaomi 13T Pro</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/all-you-need-to-know-about-mega-greninja-for-oppo-reno-8t-drfone-by-drfone-virtual-android/"><u>All You Need To Know About Mega Greninja For Oppo Reno 8T | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/audio-visual-verification-a-windows-users-pre-meet-checklist/"><u>Audio Visual Verification: A Windows User’s Pre-Meet Checklist</u></a></li>
<li><a href="https://windows11.techidaily.com/bringing-print-functionality-to-microsofts-secure-edge/"><u>Bringing Print Functionality to Microsoft's Secure Edge</u></a></li>
<li><a href="https://windows11.techidaily.com/chronicle-of-windows-seven-enduring-traits-in-the-new-era-of-11/"><u>Chronicle of Windows: Seven Enduring Traits in the New Era of 11</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-windows-index-settings/"><u>Configuring Windows Index Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-the-perfect-keys-list-for-win11s-narrator-control/"><u>Crafting the Perfect Keys List for Win11's Narrator Control</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-prevalent-anydesk-errors-in-windows/"><u>Decoding Prevalent AnyDesk Errors in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-devhome-the-essential-guide-to-win11/"><u>Discovering DevHome: The Essential Guide to Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/easing-windows-woes-with-adobe-ps/"><u>Easing Windows Woes with Adobe PS</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-routes-to-printer-control-in-windows-11-max-50-chars/"><u>Efficient Routes to Printer Control in Windows 11 (Max 50 Chars)</u></a></li>
<li><a href="https://extra-resources.techidaily.com/embellishing-visual-narratives-with-fonts-in-ae/"><u>Embellishing Visual Narratives with Fonts in AE</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-usb-resources-on-pcs/"><u>Enhancing USB Resources on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/escape-without-errors-tips-for-a-well-functioning-key-on-windows/"><u>Escape Without Errors: Tips for a Well-Functioning Key on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/free-media-titans-for-effortless-windows-experience/"><u>Free Media Titans for Effortless Windows Experience</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/gpu-narrative-radeons-recent-revolution-for-2024/"><u>GPU Narrative  Radeon's Recent Revolution for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-panels-revealed-recovering-offscreen-windows-in-edges-os/"><u>Hidden Panels Revealed: Recovering Offscreen Windows in Edges OS</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-open-the-internet-options-in-windows-11/"><u>How to Open the Internet Options in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-recurring-disk-full-issues-in-windows/"><u>How to Stop Recurring Disk Full Issues in Windows</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-to-utilize-gpt-3-for-programming-tasks-a-guide-to-its-6-main-capabilities/"><u>How to Utilize GPT-3 for Programming Tasks: A Guide to Its 6 Main Capabilities</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-frp-from-oppo-a58-4g-by-drfone-android/"><u>In 2024, How to Bypass FRP from Oppo A58 4G?</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-pinnacle-performance-discover-the-top-8-webcams-today/"><u>In 2024, Pinnacle Performance  Discover the Top 8 Webcams Today</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-set-your-preferred-job-location-on-linkedin-app-of-your-oppo-a1-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Set Your Preferred Job Location on LinkedIn App of your Oppo A1 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/keep-your-data-and-save-space-win11s-secure-drive-management-methods-max-156-chars/"><u>Keep Your Data and Save Space: Win11's Secure Drive Management Methods (Max 156 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-recurring-edge-shortcut-installations/"><u>Preventing Recurring Edge Shortcut Installations</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/-your-screen-three-strategies-to-slow-youtube-videos-down-57-chars/"><u>Quiet Your Screen  Three Strategies to Slow YouTube Videos Down (57 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/re-establishing-malwarebytes-service-connections-in-win-oses/"><u>Re-Establishing Malwarebytes' Service Connections in Win OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/removing-geforce-graphical-overlay-feature/"><u>Removing GeForce Graphical Overlay Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/revealing-concealed-elements-a-guide-to-windows-11-ui/"><u>Revealing Concealed Elements: A Guide to Windows 11 UI</u></a></li>
<li><a href="https://windows11.techidaily.com/sling-verification-sluggishness-top-strategies-for-speedy-updates/"><u>Sling Verification Sluggishness: Top Strategies for Speedy Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-eliminating-nvidias-visual-boost/"><u>Step-by-Step: Eliminating NVIDIA's Visual Boost</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-getting-the-newest-insignia-drivers-installed-on-your-windows-device-easily/"><u>Step-by-Step: Getting the Newest Insignia Drivers Installed on Your Windows Device Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-photo-resizing-on-windows-11-6-steps/"><u>The Ultimate Guide to Photo Resizing on Windows 11 – 6 Steps</u></a></li>
<li><a href="https://unlock-android.techidaily.com/tips-and-tricks-for-setting-up-your-infinix-hot-40i-phone-pattern-lock-by-drfone-android/"><u>Tips and Tricks for Setting Up your Infinix Hot 40i Phone Pattern Lock</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-vivo-s18e-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive Vivo S18e Screen | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-guide-vmware-crashes-bsod-on-win11/"><u>Troubleshooting Guide: VMware Crashes, BSOD on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/what-is-ftdibussys-on-windows-and-why-does-it-disable-memory-integrity/"><u>What Is ftdibus.sys on Windows and Why Does It Disable Memory Integrity?</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-reboot-mastery-conducting-a-pure-boot/"><u>Windows 11 Reboot Mastery: Conducting a Pure Boot</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-unveiled-the-backup-and-sync-technological-advancements/"><u>Windows 11 Unveiled: The Backup & Sync Technological Advancements</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-window-wizardry-how-to-reactivate-off-screen-apps/"><u>Windows 11 Window Wizardry: How to Reactivate Off-Screen Apps</u></a></li>
</ul></div>
