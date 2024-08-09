---
title: Steps to Tackle Physical RAM Limitations on Windows VMware
date: 2024-08-08T06:12:35.912Z
updated: 2024-08-09T06:12:35.912Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Tackle Physical RAM Limitations on Windows VMware
excerpt: This Article Describes Steps to Tackle Physical RAM Limitations on Windows VMware
keywords: Overcoming RAM in Virtual Machines (Windows),Optimizing Windows VM Memory Usage,Enhance VMRAM Capacity Efficiently,Managing Windows VM RAM Limitations,Strategies for VM Resources on Windows,Boosting Physical RAM in Virtual Hosts,Tackling Memory Constraints in VMware Windows
thumbnail: https://thmb.techidaily.com/9cc152d1aca0892df1ca5596ac3ad03cce388893be920721cefd3090f694d72e.png
---

## Steps to Tackle Physical RAM Limitations on Windows VMware

 VMware Workstation is one of the best virtualization software packages for Windows. However, some users see an error message when they try to start virtual machines in VMware Workstation. That error message says, “not enough physical memory is available to power on this virtual machine,” and virtual machines won’t start up.

 This VMware issue can arise when there’s more than enough RAM available on a PC. However, there are numerous possible causes for the “not enough physical memory” error. This is how you can fix the “not enough physical memory” WMware error in Windows 10 and 11.

## 1\. Configure VMware to Run as an Administrator

 Not running VMware as an administrator places restrictions on its system permissions and access to resources. So, run the software with elevated rights to ensure a lack of permissions isn’t causing any issues.

 You can check out[how to run any program as an administrator on Windows](https://www.makeuseof.com/tag/ways-to-run-a-program-as-administrator-in-windows/) for more help, or you can set VMware to always run as an administrator like this:

1. If there’s a VMware shortcut on your desktop, right-click it and select**Open** file location. Manually open VMware’s installation directory in File Explorer if you can’t right-click a shortcut for the software.
2. Then click the VMware EXE file with the right mouse button to select its**Properties** context menu option.
3. Select**Compatibility** to view that tab’s settings.
4. Click the checkbox for the**Run this program as administrator** option to select it.  
![The Compatibility tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-compatibility-tab2.jpg)
5. Select**Apply** to save the new administrator option for VMware.
6. Then select**OK** to close WMware’s properties window.

## 2\. Edit the Config File

 Lots of users have been able to fix the “not enough physical memory” by editing VMWare’s**config.ini** file. Those users disabled a Host parameter within the software’s configuration file. To disable that Host parameter, open and edit VMware’s**config.ini** file as follows:

1. Press**Win + E** to access File Explorer.
2. Open this VMware directory in Explorer:  
`C:\ProgramData\VMware\VMware Workstation`
3. Right-click the**config.ini** file and select**Open with** .  
<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Open with option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-open-with-option.jpg)
4. Select**Notepad** to view the configuration file in that text editor.
5. Then **input vmmon.disableHostParameters = “TRUE”** at the bottom of the configuration file as in the image below.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->
![WMware's config.ini file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-config-ini-file.jpg)
6. Click**File** on Notepad’s menubar.
7. Select the menu’s**Save** option.  
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
![The Save option in Notepad](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-save-option-in-notepad.jpg)

## 3\. Expand the Virtual Memory for the Virtual Machine

 The “not enough physical memory” error can occur because not enough virtual memory has been allocated to the virtual machine. You can expand a virtual machine’s memory allocation in VMWare like this:

1. Open your VMware software.
2. Right-click the virtual machine for which you need to fix the error and select**Settings** .
3. Increase the virtual machine’s memory allocation with the bar slider. That amount should always be higher than your PC’s available RAM.  
![The memory bar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-memory-bar.jpg)
4. Click**OK** to apply.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
## 4\. Update VMware

 The “not enough physical memory” error will more likely arise on outdated WMware versions. So, ensure you’re utilizing the latest version of the software. This is how you can update VMware:

1. Bring up the VMware window.
2. Click the**Help** menu.
3. Select**Software Updates** to view that window.  
<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Software Updates option in VMware](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-software-updates-option.jpg)
4. Then click the**Check for Updates** button.  
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
![The Check for updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-check-for-updates-option4.jpg)
5. Press the**Get More Information** button for an available update.

1. Log into an account profile on the website that opens.
2. Select the**Download Now** option on the website for the latest VMware Workstation version.
3. Then you’ll need to select an**Accept** option for the EULA agreement.
4. Click another**Download Now** option.
5. Then click File Explorer’s taskbar shortcut.
6. Go to the downloads folder that includes the WMware setup wizard.
7. Double-click the downloaded VMware installer to open it. Go through the setup wizard to install the latest VMware version.

## 5\. Delete a Recent Windows Update

 The “not enough physical memory” error can be caused by a Windows update that conflicts with VMware. So, uninstalling a recent update could fix that issue for some users. Check out our guide about[uninstalling Windows updates](https://www.makeuseof.com/windows-11-uninstall-updates/) for further details on how to apply this potential solution.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![The Installed Updates Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-uninstall-update-option.jpg)

## 6\. Perform a Clean Boot

 Performing a clean boot will disable non-essential apps and services from the Windows startup. Clean booting can potentially resolve the “not enough physical memory” in two ways. Applying this troubleshooting method will ensure there aren’t any third-party programs conflicting with VMware and free up RAM for the software.

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-services-tab-in-msconfig.jpg)

 To disable all third-party startup programs and services, check out the guidelines in our guide on[how to clean boot in Windows](https://www.makeuseof.com/clean-boot-windows-11/) . This will perform a clean boot whenever you restart Windows.

 Try utilizing your VMware virtual machine after clean booting. If this works,

<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
## 7\. Set Up a New Virtual Machine

 If the issue persists despite applying the resolutions above, consider setting up a new virtual machine to replace the one that needs fixing. Download the latest ISO for the virtual machine’s platform. Then you can set up the virtual machine again, as outlined on the[VMware support page](https://kb.vmware.com/s/article/1018415) .

## Jump Into Your WMware Virtual Machine Again

 Those Windows fixes for the “Not enough physical memory” error have worked for many VMware Workstation users. So, there’s a decent enough chance one will kick-start your VMWare virtual machine too. However, users who still need more possible fixes for this issue can submit a support request via the[VMware Customer Connect](https://customerconnect.vmware.com/home?bmctx=89E60DF848C641FD518EB9F6B9A6E5334F602FA3A762B409625CD531863AC847&password=secure%5Fstring&contextType=external&username=string&challenge%5Furl=https:%2F%2Fcustomerconnect.vmware.com%2Fhome&request%5Fid=-8453692679675997712&authn%5Ftry%5Fcount=0&locale=en%5FGB&resource%5Furl=https%253A%252F%252Fcustomerconnect.vmware.com%252Fweb%252Fvmware%252Fchecksession) page.

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
<li><a href="https://twitter-videos.techidaily.com/new-end-audio-blackout-vocalize-tweet-videos-for-2024/"><u>[New] End Audio Blackout  Vocalize Tweet Videos for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-facing-the-reality-of-content-monetization-for-2024/"><u>[New] Facing the Reality of Content Monetization for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-reclaiming-acoustics-lost-in-social-media-videos/"><u>[New] In 2024, Reclaiming Acoustics Lost in Social Media Videos</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-experience-unlimited-recording-review-of-free-screen-tools-for-cameras-for-2024/"><u>[Updated] Experience Unlimited Recording – Review of Free Screen Tools for Cameras for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-top-5-ps1-games-emulators-resurrecting-console-legends-on-pc/"><u>[Updated] Top 5 PS1 Games Emulators - Resurrecting Console Legends on PC</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-ultimate-guide-to-top-6-creative-mojave-dwellings/"><u>[Updated] Ultimate Guide to Top 6 Creative Mojave Dwellings</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unlocking-superior-slow-motion-quality-through-fps-selection/"><u>2024 Approved  Unlocking Superior Slow Motion Quality Through FPS Selection</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-nubia-red-magic-8s-pro-drfone-by-drfone-virtual-android/"><u>5 Hassle-Free Solutions to Fake Location on Find My Friends Of Nubia Red Magic 8S Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/biometric-betrayal-windows-hellos-security-under-fire/"><u>Biometric Betrayal: Windows Hello's Security Under Fire?</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-windows-extract-error-1152-quickly/"><u>Eliminating Windows Extract Error 1152 Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/evaluating-your-systems-electrical-utilization-on-windows-os/"><u>Evaluating Your System’s Electrical Utilization on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-guidance-manual-time-zone-setup-for-windows-users/"><u>Expert Guidance: Manual Time Zone Setup for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/fast-track-installation-of-ms-office-works-on-w11/"><u>Fast-Track Installation of MS Office Works on W11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-interruptions-in-geforce-links-with-os-1011/"><u>Fixing Interruptions in GeForce Links with OS 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-correct-ipadiphone-images-not-displaying-in-windows-11-environment/"><u>How to Correct iPad/iPhone Images Not Displaying in Windows 11 Environment</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-the-roadmap-for-success-mastering-the-art-of-fb-reel-production/"><u>In 2024, The Roadmap for Success  Mastering the Art of FB Reel Production</u></a></li>
<li><a href="https://windows11.techidaily.com/initiating-printer-commands-via-edge-defender-smartscreen/"><u>Initiating Printer Commands via Edge Defender SmartScreen</u></a></li>
<li><a href="https://fox-glue.techidaily.com/key-concepts-of-interactive-storytelling-for-2024/"><u>Key Concepts of Interactive Storytelling for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/master-technique-for-silencing-firewall-in-win11/"><u>Master Technique for Silencing Firewall in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-enrollment-in-windows-11s-beta-testers-club/"><u>Mastering Enrollment in Windows 11'S Beta Testers Club</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-directx-12-without-onboard-graphics/"><u>Navigating Through DirectX 12 Without Onboard Graphics</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-autonomous-scrolling-on-os-windows/"><u>Preventing Autonomous Scrolling on OS Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-remedy-for-rearranged-character-inputs/"><u>Quick Remedy for Rearranged Character Inputs</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/kle-spirits-into-your-screens-animated-text-techniques/"><u>Sprinkle Spirits Into Your Screens  Animated Text Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-overcome-endless-startup-in-bios-for-windows-systems/"><u>Steps to Overcome Endless Startup in BIOS for Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-steam-friendship-disconnect-on-pcs/"><u>Steps to Resolve Steam Friendship Disconnect on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-overcome-run-as-command-issues/"><u>Strategies to Overcome 'Run As' Command Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-full-potential-mastering-multiple-screens-in-win11/"><u>Unlock Full Potential: Mastering Multiple Screens in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-power-settings-for-cpu-state-insights/"><u>Unlocking Power Settings for CPU State Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-evolution-unveiling-the-latest-system-updates/"><u>Windows 11'S Evolution: Unveiling the Latest System Updates</u></a></li>
</ul></div>
