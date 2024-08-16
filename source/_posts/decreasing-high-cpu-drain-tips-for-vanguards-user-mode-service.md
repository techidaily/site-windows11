---
title: "Decreasing High CPU Drain: Tips for Vanguard's User-Mode Service"
date: 2024-08-15T15:10:38.857Z
updated: 2024-08-16T15:10:38.857Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Decreasing High CPU Drain: Tips for Vanguard's User-Mode Service"
excerpt: "This Article Describes Decreasing High CPU Drain: Tips for Vanguard's User-Mode Service"
keywords: High Cpu Drain Reduction,Optimize Vanguard Service Use,User-Mode Service Efficiency,Minimize CPU Usage Impact,Enhance System Performance,Manage Vanguard Load Effectively,Improve Processing Resource Allocation
thumbnail: https://thmb.techidaily.com/9a22b51aefec4c58f2a1f5a5ec87dbc393141382248bd9298fb623a960664270.jpeg
---

## Decreasing High CPU Drain: Tips for Vanguard's User-Mode Service

 Is the "Vanguard user-mode service" process consuming too much of your CPU resources when playing Valorant? This indicates that Riot Vanguard, an anti-cheat software that prevents unfair gameplay in Valorant, isn't working as it should. High CPU usage can cause lag and stutter in Valorant, completely ruining its performance.

 If you want to reduce the CPU usage of the Vanguard user-mode service process and play Valorant seamlessly, here are some fixes you can try.

## 1\. Apply Some Preliminary Checks

 Start de-stressing your CPU by taking the following basic steps, as they may reduce resource usage immediately:

* Restart Valorant or any other game that spikes the Vanguard user-mode service's CPU consumption.
* Whitelist Vanguard from Windows Defender (see [how to allow apps through the Microsoft firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/)) and the antivirus software you use to ensure your security suites don't cause Vanguard to consume more CPU resources than necessary.
* Be sure to turn off any cheat software you're using to manipulate Valorant or any other Riot Games game.
* Use the Task Manager to filter the processes consuming the most CPU resources by descending order to determine if Vanguard overstresses the CPU the most. If another process turns out to be more burdensome, turn it off.

 If none of the above checks fixes the problem, apply the remaining fixes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Disable and Restart Valorant and Vanguard Processes

 First off, ensure that a temporary glitch hasn't fueled the high CPU usage by the Vanguard user-mode service process. The easiest way to rule out this possibility is to close Valorant, turn off the Vanguard services, and restart them.

 To disable them, right-click the Windows **Start** button and open the **Task Manager**. Here, locate the Vanguard and Valorant-related processes, right-click on each process, and select **End task**.

![Disable Vanguard-Related Processes From Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/2-disable-vanguard-related-processes-from-windows-task-manager.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->

 Once these processes are disabled, give Valorant a fresh start, which will automatically restart Vanguard. If restarting the processes doesn't make a difference and the process continues to overstretch the CPU, move on to the next step.

## 3\. Make the Vanguard User-Mode Service Process a Low Priority

 Windows allows users to limit the CPU resource usage of processes in two different ways. The first is to change the priority of the process, and the second is to turn on the efficiency mode. Using either of these methods limits the allocation of CPU resources to less essential processes, limiting their CPU usage.

 To change the priority of Vanguard-related processes, go to the **Details** tab, right-click on the **vgc.exe** or any other process, and select **Low** from the **Set Priority** menu.

![Change the Priority of the Vanguard User Mode Service Process in the Set Priority Menu in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/3-set-the-vanguard-user-mode-service-process-a-low-priority-in-the-set-priority-menu-in-windows-task-manager.jpg)

 If you choose the latter option to control CPU resource consumption, right-click on the same process and choose **Efficiency mode**.

![Enable the Efficiency Mode of Vgc in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/4-go-to-efficiency-mode-of-vgc-in-windows-task-manage.jpg)

<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Change the Processor Affinity

 The processor affinity setting in Task Manager allows you to limit the number of processors a process can use. Using this setting, you can instruct the process to use only a few processors while leaving others free. In general, the fewer processors a process is permitted to use, the lower its overall resource consumption will be.

 In light of that, changing the processor affinity for the Vanguard process may resolve the issue at hand. To do that, right-click the **vgc.exe** or any other process you want to change the affinity for, then click **Set affinity**.

![Click on Set Affinity Option of Vgc exe in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/5-click-on-set-affinity-option-of-vgc-exe-in-windows-task-manager.jpg)
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Here, uncheck the boxes besides most of the **CPUs** and keep only a few of them checked.

![Disable Unnecessary CPUs From Processor Affinity Settings in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/6-disable-unnecessary-cpus-from-processor-affinity-settings-in-windows-task-manager.jpg)
<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->

## 5\. Stop the Vanguard Service and Restart It

 You may also be able to fix the high CPU resource usage of the Vanguard user-mode service by stopping and starting the Vgc service. Follow these steps to do that:

1. Type **"Services"** in Windows Search and open the **Services** app.
2. Locate the **Vgc** service, right-click on it, and hit **Properties**.  
![Go to Properties of Vgc Service in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/7-go-to-properties-of-vgc-service-in-windows-services-app.jpg)
3. Navigate to the **General** tab, and click on the **Stop** button.
4. After that, restart the service by clicking on the **Start** button again.  
![Stop the Vgc Service in the General Tab of Properties Window in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/8-stop-the-vgc-service-in-the-general-tab-of-properties-window-in-windows-services-app.jpg)
5. Also, choose **Automatic** from the dropdown menu next to **Startup type**.  
![Choose Automatic From the Dropdown Menu Next to Startup Type in General Tab of Properties Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/9-choose-automatic-from-the-dropdown-menu-next-to-startup-type-in-general-tab-of-properties-window.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 6\. Disable Third-Party Overlays

 Riot Vanguard is an anti-cheat program. It prevents cheating and bans users who attempt to hack into the game. It does this by detecting unauthorized changes made to the game files and settings using third-party cheat software.

 As reported by some users, using the in-game overlays can also spike CPU resource usage for the Vanguard user-mode service process. Turning off the third-party overlays resulted in a reduction in resource consumption for those users.

 Therefore, if you're using any third-party app to enable in-game overlay, especially Discord, turn it off. Hopefully, this will reduce CPU usage.

![Check the Assigned Hotkey Under Toggle Overlay Lock in the Discord's Game Overlay Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/7-check-the-assigned-hotkey-under-toggle-overlay-lock-in-the-discord-s-game-overlay-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Move Valorant to a Different Drive

 Installing Valorant on the same drive as your operating system has been reported to cause problems. If you've also installed the game on the same drive where your OS resides, it's possible that Windows security could be hindering Vanguard's activity, making it consume more resources.

 To ensure that's not the case, you should move Valorant to a different drive. Not sure how to do that? Refer to our guide on [how to move the installed apps and programs in Windows 10 or 11.](https://www.makeuseof.com/tag/move-installed-apps-programs-windows-10/)

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
## 8\. Install a Fresh Copy of Vanguard

 If none of the potential fixes have worked, you can use the least desirable option; uninstall Vanguard and reinstall it. However, you need to stop the Vgc service first, as described in the above step; otherwise, you may encounter issues when uninstalling the software. You should also close Valorant and exit Vanguard from the system tray before uninstallation.

 Once that's done, follow the instructions in our [guide on uninstalling software on Windows 11](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) and uninstall Vanguard. Afterward, rerun Valorant and Riot Vanguard will be installed automatically.

![installing riot vanguard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/installing-riot-vanguard-1.jpg)

 Valorant and other Riot Games products require Vanguard to function. If Valorant (or any other game) fails to install Vanguard on its own after uninstallation, restart your device once and then run the game again.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
## Don't Let Vanguard Overstress Your CPU

 The consumption of excessive CPU resources by a single process can affect the game's performance and degrade the overall system performance. Hopefully, you now better understand what causes the CPU spike for the Vanguard user-mode service process and the best ways to bring it down to a normal level.

 If none of the fixes above lower CPU consumption, your last resort should be to uninstall Valorant (or any other game) and reinstall it fresh.

 If you want to reduce the CPU usage of the Vanguard user-mode service process and play Valorant seamlessly, here are some fixes you can try.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-mastering-instagram-highlights-comprehensive-photography-tips/"><u>[New] 2024 Approved  Mastering Instagram Highlights  Comprehensive Photography Tips</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-videotwit-grabber-capture-tweets-visuals-for-ios-for-2024/"><u>[New] VideoTwit Grabber  Capture Tweets' Visuals for iOS for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-step-by-step-reposting-on-instagram/"><u>[Updated] 2024 Approved  Step-by-Step Reposting on Instagram</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/2024-approved-youtubers-spotlighting-niche-gaming-subcultures/"><u>2024 Approved  Youtubers Spotlighting Niche Gaming Subcultures</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/detailed-guide-of-ispoofer-for-pogo-installation-on-oppo-reno-8t-5g-drfone-by-drfone-virtual-android/"><u>Detailed guide of ispoofer for pogo installation On Oppo Reno 8T 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/evaluating-the-significance-of-audio-device-isolation-in-windows/"><u>Evaluating the Significance of Audio Device Isolation in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/examining-why-drive-letters-are-missing-from-windows-systems/"><u>Examining Why Drive Letters Are Missing From Windows Systems</u></a></li>
<li><a href="https://extra-hints.techidaily.com/exploring-essential-gif-sources-for-latest-iphones/"><u>Exploring Essential GIF Sources for Latest iPhones</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-honor-magic-5-lite-drfone-by-drfone-virtual-android/"><u>Fixing Foneazy MockGo Not Working On Honor Magic 5 Lite | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-11-ignore-or-prevent-expiry-errors/"><u>Fixing Windows 11: Ignore or Prevent 'Expiry' Errors?</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-cease-built-in-desktop-keyboard-in-windows-os/"><u>Guide to Cease Built-In Desktop Keyboard in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-clearing-winsec-error-limited-administrator/"><u>Guide to Clearing WinSec Error - 'Limited Administrator'</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-guarantee-windows-screensaver-immobility/"><u>How to Guarantee Windows Screensaver Immobility</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-install-and-activate-defender-application-guard-on-edge-for-enhanced-safety/"><u>How to Install and Activate Defender Application Guard on Edge for Enhanced Safety</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-tackle-winservicesexe-malfunctions/"><u>How To Tackle WinServices.exe Malfunctions</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-track-imei-number-of-infinix-note-30-through-google-earth-by-drfone-android/"><u>How To Track IMEI Number Of Infinix Note 30 Through Google Earth?</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-unlink-your-onedrive-from-your-microsoft-account-on-windows/"><u>How to Unlink Your OneDrive From Your Microsoft Account on Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-ways-to-stop-parent-tracking-your-samsung-galaxy-a15-4g-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to stop parent tracking your Samsung Galaxy A15 4G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/interactive-insights-microsofts-innovative-ai-hub/"><u>Interactive Insights: Microsoft's Innovative AI Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-fixing-nvidia-cp-errors-in-ws1110/"><u>Mastering the Art of Fixing Nvidia CP Errors in WS11/10</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-winerror-fixes-for-oculus-app-installation/"><u>Mastering WinError Fixes for Oculus App Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-servers-problems-quick-and-effective-tips/"><u>Navigating Through Servers Problems: Quick & Effective Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/rejuvenating-pcs-essential-13-tricks-for-restoring-systems/"><u>Rejuvenating PCs: Essential 13 Tricks for Restoring Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-pathway-to-start-elevated-powershell-on-win11-systems/"><u>Secure Pathway to Start Elevated PowerShell on Win11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-up-defender-application-guard-for-secure-edge-use-in-win-11/"><u>Setting Up Defender Application Guard for Secure Edge Use in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-unsupported-device-for-windows-hello-login/"><u>Solving 'Unsupported Device' For Windows Hello Login</u></a></li>
<li><a href="https://windows11.techidaily.com/stay-ahead-of-the-game-with-w11-pro-special-deals/"><u>Stay Ahead of the Game with W11 Pro Special Deals</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-to-correctly-handle-windows-updater-issue-error-0x80070003/"><u>Step-by-Step Guide to Correctly Handle Windows' Updater Issue (Error 0X80070003)</u></a></li>
<li><a href="https://windows11.techidaily.com/sustained-prominence-of-win-calculator-display/"><u>Sustained Prominence of Win Calculator Display</u></a></li>
<li><a href="https://windows11.techidaily.com/synchronize-access-controls-with-powertoys-locksmith/"><u>Synchronize Access Controls with PowerToys' Locksmith</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-crafting-a-better-windows-11/"><u>The Art of Crafting a Better Windows 11</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-ultimate-guide-to-hardware-by-tom-informed-choices-await/"><u>The Ultimate Guide to Hardware by Tom - Informed Choices Await!</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-error-non-working-windows-11-voice-access/"><u>Troubleshoot Error: Non-Working Windows 11 Voice Access</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-non-functional-shift-in-windows/"><u>Troubleshoot Non-Functional Shift in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unblock-onedrive-windows-methods-to-reclaim-file-storage/"><u>Unblock OneDrive: Windows Methods to Reclaim File Storage</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-power-of-component-services-in-windows-11/"><u>Unlocking the Power of Component Services in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/wake-lock-woes-keyboard-mouse-in-win11/"><u>Wake Lock Woes: Keyboard, Mouse in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/waking-up-off-screen-windows-mastering-6-strategies-in-win11/"><u>Waking Up Off-Screen Windows: Mastering 6 Strategies in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/why-does-tasker-show-other-processes/"><u>Why Does Tasker Show Other Processes?</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11s-official-app-three-ways-to-erase-it/"><u>Win 11'S Official App: Three Ways to Erase It</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-adjusting-your-personalized-fn-keys/"><u>Windows 11: Adjusting Your Personalized FN Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-paper-management-reboot-steps/"><u>Windows Paper Management Reboot Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-sign-in-how-to-delete-your-email/"><u>Windows Sign In: How to Delete Your Email</u></a></li>
</ul></div>
