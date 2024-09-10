---
title: Steps to Solve Error 0X80370102 During Windows Subsystem for Linux Installation
date: 2024-09-09T12:05:50.242Z
updated: 2024-09-10T12:05:50.242Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Solve Error 0X80370102 During Windows Subsystem for Linux Installation
excerpt: This Article Describes Steps to Solve Error 0X80370102 During Windows Subsystem for Linux Installation
keywords: Windows Subsystem Fix,WinSxS Error,WSL Install Troubleshoot,Linux Setup Issue Resolve,Linux On Windows Err0X8037,Subsystem Fix for Win10,Error 0X8037 Troubleshooting
thumbnail: https://thmb.techidaily.com/f55b120c68d76e4449cb5609ead97bf0a2f306573825bcc3d502f312c1d75f0b.png
---

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130875/7443" target="_top" id="2130875">
  <img src="//a.impactradius-go.com/display-ad/7443-2130875" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130875/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Steps to Solve Error 0X80370102 During Windows Subsystem for Linux Installation

 The 0x80370102 error occurs when the users attempt to install and run a Linux distribution using the 'Windows Subsystem for Linux' feature. In several cases, the error is caused when the users try to install both Linux and Debian distros and is typically related to problems with the hardware Virtualization feature in BIOS.

 Below, we take a look at the causes of this issue and the troubleshooting methods that will help you resolve the problem in no time.

## What Causes the Error 0x80370102 in Windows?

 The error at hand can be caused by a number of reasons, especially hardware issues. Here is a list of the most common reasons behind this issue:

* Hyper-V and other relevant settings are disabled - Hyper-V, which is Microsoft's hardware virtualization product, lets you create and run the virtual machine. This service and other relevant services like the Virtualization setting should be enabled from the BIOS for you to be able to install and run distros.
* You are using Windows Insider Preview build - If you are not using a completely developed version of Windows, you are also likely to run into errors like the one at hand.
* The Lxssmanager.exe service is corrupt - the Lxssmanager.exe service manages the launch of new WSL instances. If this service is corrupt or just not working properly, you will not be able to install a Linux distribution to access via Windows Subsystem for Linux 2.

 Now that we know about the causes of this problem let’s have a look at the solutions that will hopefully fix the problem for good. However, before we proceed, we recommend that you[double-check if your computer supports hardware virtualization](https://www.makeuseof.com/tag/virtualization-issues-simple-solutions/) .

 In case you are using an Insider Build of Windows, consider installing a stable Windows version, since a version under development is prone to errors like this one.

<!-- affiliate ads begin -->
<span id="1983553">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983553.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983553">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983553.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983553%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983553/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Enable Hyper-V

 The first thing that we recommend doing is making sure that all the relevant services like Hyper-V and Virtualization are enabled. In this method, we will be enabling the Hyper-V feature using the Control Panel. We will also use the Task Manager utility to check if the Virtualization feature is working fine.

Here is how you can enable Hyper-V on your PC:

1. Press the**Win + R** keys together to open a Run dialog.
2. Choose the**Programs** option and then click on**Program and Features** .  
![Choose Programs and Features in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/program-and-features.jpg)
3. Click on**Turn Windows Feature on or off** in the left pane.  
![Turn Windows features on or off option in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-windows-features-on-or-off.jpg)
4. In the following dialog, checkmark the box associated with**Hyper-V** and click**OK** .  
![Enable Hyper-V in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/hyper-v-setting.jpg)
5. Once done, restart your computer and check if the issue is resolved. While you are at it, we also recommend checking if the Virtual Machine Platform feature is enabled by following the same steps. If it is disabled, enabling it should help you fix the issue as well.
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137218/26400" target="_top" id="2137218">
  <img src="//a.impactradius-go.com/display-ad/26400-2137218" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137218/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Next, we will check if Virtualization is enabled on the device. In most devices, it is disabled by default. Follow the steps below to proceed:

1. Press the**Ctrl + Shift + Esc** keys together to open Task Manager,
2. Click on the**More details** button to expand the Task Manager window.  
![More details option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/task-manager-more-details.jpg)
3. Head over to the**Performance** tab and click on CPU.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137379/7443" target="_top" id="2137379">
  <img src="//a.impactradius-go.com/display-ad/7443-2137379" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137379/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Under the CPU graph on the right side, check the status for**Virtualization** . In case you are not sure if your PC supports virtualization, view the Hyper-V support section in the same window. If it says Yes, then it implies that you can make use of hardware virtualization on your computer.  
![Virtualization in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/virtualization-setting.jpg)
5. Alternatively, open Run by pressing the**Win + R** keys together.
6. Type cmd in the text field and press**Ctrl + Shift + Enter** to open Command Prompt as admin.
7. Click**Yes** in the User Account Control Prompt.
8. Type systeminfo in Command Prompt and hit Enter.
9. Wait for the command to execute, and then head over to the**Hyper-V requirements** section. You should be able to see if the Virtualization is enabled from there.  
![Check Hyper-V requirements in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/hyper-v-requirements.jpg)

 If the service is disabled,[enabling the Hyper-V technology on Windows](https://www.makeuseof.com/windows-11-enable-hyper-v/) should fix the problem for you.

<!-- affiliate ads begin -->
<span id="1516072">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1516072.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1516072">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1516072.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1516072%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1516072/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Restart the LxssManager Service

 As we mentioned earlier, the LxssManager service should be working properly for you to install the Linux distribution and run it.

 If a service is acting up, the easiest way to fix it is by restarting it. In this method, we will use the Windows Services utility to make these changes.

Here is how you can do that:

1. Press the**Win + R** keys together to open a Run dialog.
2. Type services.msc in Run and click**OK** .
3. In the following window, look for the**LxssManager** service and right-click on it.
4. Choose**Properties** from the context menu.  
![LxssManager service properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lxssmanager-utility.jpg)
5. Now, click on the**Stop** button, wait for a few seconds, and then hit**Start** .  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123731/7443" target="_top" id="2123731">
  <img src="//a.impactradius-go.com/display-ad/7443-2123731" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123731/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Click on the Start button in the Properties dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/stop-button.jpg)
6. Once the service is restarted, check if the issue is resolved.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115932/19272" target="_top" id="2115932">
  <img src="//a.impactradius-go.com/display-ad/19272-2115932" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115932/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Enable Nested Virtualization and Change the RAM Settings

 Another fix that worked for users was enabling Nested virtualization, a feature that enables you to run Hyper-V inside a Hyper-V virtual machine. If this feature is disabled on your computer, enabling it will hopefully resolve the problem for you.

Here is how you can proceed:

1. Type Powershell in Windows search and click on**Run as administrator** .
2. Click**Yes** in the User Account Control prompt.
3. Type the following command in the Powershell window and click Enter to execute it.  
Set-VMProcessor <VMName> -ExposeVirtualizationExtensions $true  
![Execute the entered command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/powershell-command-hyperv.jpg)
4. Now, launch the Hyper-V manager and right-click on the virtual machine.
5. Choose**Settings** from the context menu.
6. Click on**Memory** in the left pane.
7. Now, increase the Startup RAM value by double and uncheck the box for**Enable Dynamic Memory** .  
![Modify the memory](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/configure-hyper-v-dynamic-memory.jpg)
8. Click**Apply** \>**OK** to save the changes.
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137215/26400" target="_top" id="2137215">
  <img src="//a.impactradius-go.com/display-ad/26400-2137215" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137215/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
9. Now, right-click on your virtual machine again and choose**Connect** .
10. Let the system restart and try installing/running Ubuntu again.

## The WslRegisterDistribution Error, Fixed

 Accessing Windows Subsystem for Linux is quite simple, but there are times when you can run into installation or functioning errors. The methods above should help you fix the WslRegisterDistribution error successfully. You can also contact the Microsoft support team if the error appears again to identify the real cause of the problem in your case and implement a relevant solution.


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
<li><a href="https://instagram-video-recordings.techidaily.com/new-viral-loop-creations-instagrams-boomerang-guide/"><u>[New] Viral Loop Creations Instagram's Boomerang Guide</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-share-your-tweets-as-snaps-easy-tutorials/"><u>[Updated] In 2024, Share Your Tweets as Snaps - Easy Tutorials</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-learn-the-basics-of-facebook-metrics-easily-for-2024/"><u>[Updated] Learn the Basics of Facebook Metrics, Easily for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-maximizing-mobile-video-quality-in-tweets-for-2024/"><u>[Updated] Maximizing Mobile Video Quality in Tweets for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-voice-over-techniques-creating-compelling-video-content-for-2024/"><u>[Updated] Voice Over Techniques Creating Compelling Video Content for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-blur-it-out-free-iphones-tips-for-crisp-image-edits/"><u>2024 Approved Blur It Out Free iPhones Tips for Crisp Image Edits</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-learn-iphones-burst-shot-magic/"><u>2024 Approved Learn iPhone's Burst Shot Magic</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-premium-picks-for-the-ultimate-gopro-experience/"><u>2024 Approved Premium Picks for the Ultimate Gopro Experience</u></a></li>
<li><a href="https://extra-resources.techidaily.com/creative-auditory-shifts-with-premiere-pro/"><u>Creative Auditory Shifts with Premiere Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-to-alter-windows-msi-service-status/"><u>Essential Steps to Alter Windows MSI Service Status</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-grayed-out-extend-button-revive-it-for-discmgmt/"><u>Fix Grayed-Out Extend Button, Revive It for DiscMgmt</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-sound-capture-in-obs-studio-on-windows-11-pcs/"><u>How to Reactivate Sound Capture in OBS Studio on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-run-an-unrestricted-chatgpt-alternative-on-windows-with-freedomgpt/"><u>How to Run an Unrestricted ChatGPT Alternative on Windows With FreedomGPT</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-with-location-spoofer-on-samsung-galaxy-a05-drfone-by-drfone-virtual-android/"><u>How To Simulate GPS Movement With Location Spoofer On Samsung Galaxy A05? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-unlock-and-fix-safe-operational-outlook-issues/"><u>How To Unlock and Fix Safe Operational Outlook Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/identifying-perfect-shutdown-procedures-for-windows/"><u>Identifying Perfect Shutdown Procedures for Windows</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-bypassing-google-account-with-vnrom-bypass-for-vivo-y27-4g-by-drfone-android/"><u>In 2024, Bypassing Google Account With vnROM Bypass For Vivo Y27 4G</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-syncing-youtube-audio-to-film-compositions/"><u>In 2024, Syncing YouTube Audio to Film Compositions</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-video-tales-in-reverse-perfecting-instagram-posts/"><u>In 2024, Video Tales in Reverse Perfecting Instagram Posts</u></a></li>
<li><a href="https://windows11.techidaily.com/leverage-efficiency-with-terminal-as-preferred-cli/"><u>Leverage Efficiency with Terminal as Preferred CLI</u></a></li>
<li><a href="https://extra-skills.techidaily.com/lightened-transition-tactics-for-2024/"><u>Lightened Transition Tactics for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/maintain-disk-space-utilize-automatic-deletion-in-windows-11/"><u>Maintain Disk Space: Utilize Automatic Deletion in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-secure-boot-settings-for-enhanced-vm-security/"><u>Mastering Secure Boot Settings for Enhanced VM Security</u></a></li>
<li><a href="https://windows11.techidaily.com/migrating-your-qbittorrent-setup-seamlessly-across-pcs/"><u>Migrating Your qBittorrent Setup Seamlessly Across PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/mobile-device-interaction-with-server-storage/"><u>Mobile Device Interaction with Server Storage</u></a></li>
<li><a href="https://windows11.techidaily.com/mystery-non-edge-processes-in-task-manager/"><u>Mystery: Non-Edge Processes in Task Manager?</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-for-swifter-loading-of-apps-from-microsoft-store/"><u>Navigating for Swifter Loading of Apps From Microsoft Store</u></a></li>
<li><a href="https://windows11.techidaily.com/never-delay-in-decision-making-terminal-as-admin-instantly/"><u>Never Delay in Decision Making: Terminal as Admin, Instantly</u></a></li>
<li><a href="https://windows11.techidaily.com/note-taking-evolution-embracing-obsidian-canvas/"><u>Note-Taking Evolution: Embracing Obsidian Canvas</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-sign-in-obstacles-to-microsofts-cloud-storage/"><u>Overcome Sign-In Obstacles to Microsoft's Cloud Storage</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-errors-for-smooth-navigation/"><u>Overcoming Windows Errors for Smooth Navigation</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-overcoming-windows-error-code-xffffff/"><u>Quick Guide: Overcoming Windows Error Code XFFFFFF</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-unfreezing-stuck-spotify-app-in-win11-pcs/"><u>Quick Guide: Unfreezing Stuck Spotify App in Win11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/reinvigorating-your-pc-delving-into-windows-8-revival-techniques/"><u>Reinvigorating Your PC: Delving Into Windows' 8 Revival Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-stalled-grammarly-checkup-in-windows-810/"><u>Reviving Stalled Grammarly Checkup in Windows 8/10</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-your-windows-interface-personalized-pin-design-process/"><u>Secure Your Windows Interface: Personalized Pin Design Process</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-boost-utorrent-downloads-in-windows/"><u>Strategies to Boost uTorrent Downloads in Windows</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/streamlining-the-process-of-google-voice-call-capture/"><u>Streamlining the Process of Google Voice Call Capture</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-troubled-waters-of-outlooks-winerror-x/"><u>Tackling the Troubled Waters of Outlook's WinError X</u></a></li>
<li><a href="https://windows11.techidaily.com/tech-nostalgia-unleashed-windows-11-to-the-past/"><u>Tech Nostalgia Unleashed: Windows 11 to the Past</u></a></li>
<li><a href="https://windows11.techidaily.com/the-5-best-fixes-for-hiberatus-computers/"><u>The 5 Best Fixes for Hiberatus Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/the-journey-to-disabling-user-account-control-uac-in-windows-11/"><u>The Journey to Disabling User Account Control (UAC) in WIndows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/top-writing-helpers-to-transform-your-windows-experience/"><u>Top Writing Helpers to Transform Your Windows Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/triumphant-tech-reboot-triple-effect-windows-fixes/"><u>Triumphant Tech Reboot: Triple-Effect Windows Fixes</u></a></li>
<li><a href="https://win-amazing.techidaily.com/troubleshooting-lg-hardware-resolve-usb-drivers-issues-on-win-1187-systems/"><u>Troubleshooting LG Hardware: Resolve USB Drivers Issues on Win 11/8/7 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-stuck-chrome-on-win11-easy-methods-here/"><u>Troubleshooting Stuck Chrome on Win11 – Easy Methods Here</u></a></li>
<li><a href="https://windows11.techidaily.com/tutorial-switching-to-quake-with-terminal/"><u>Tutorial: Switching to Quake with Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/tweaking-windows-lockscreensaver-timer/"><u>Tweaking Windows Lock/Screensaver Timer</u></a></li>
<li><a href="https://windows11.techidaily.com/unseen-users-missed-links-how-to-open-elusive-sites-on-windows/"><u>Unseen Users, Missed Links: How to Open Elusive Sites on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-arp-caching-explained-and-tips-for-clears/"><u>Windows ARP Caching Explained & Tips for Clears</u></a></li>
<li><a href="https://windows11.techidaily.com/wsl-enabling-linux-on-windows-rise/"><u>WSL Enabling: Linux on Windows Rise</u></a></li>
</ul></div>
