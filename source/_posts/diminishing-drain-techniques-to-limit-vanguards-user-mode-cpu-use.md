---
title: "Diminishing Drain: Techniques to Limit Vanguard's User-Mode CPU Use"
date: 2024-08-08T05:57:57.479Z
updated: 2024-08-09T05:57:57.479Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Diminishing Drain: Techniques to Limit Vanguard's User-Mode CPU Use"
excerpt: "This Article Describes Diminishing Drain: Techniques to Limit Vanguard's User-Mode CPU Use"
keywords: Vanguard CPU Limit,Reduce User Mode CPU,Diminish Device Processes,Cutting Down Overuse,Efficient CPU Use,Minimize Resource Draining,Optimizing Performance
thumbnail: https://thmb.techidaily.com/d91a8e4d3e328994798cbf4d4f5c1573225bbff13640403fc40b5c32e2b3cd22.jpg
---

## Diminishing Drain: Techniques to Limit Vanguard's User-Mode CPU Use

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
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Disable and Restart Valorant and Vanguard Processes

 First off, ensure that a temporary glitch hasn't fueled the high CPU usage by the Vanguard user-mode service process. The easiest way to rule out this possibility is to close Valorant, turn off the Vanguard services, and restart them.

 To disable them, right-click the Windows **Start** button and open the **Task Manager**. Here, locate the Vanguard and Valorant-related processes, right-click on each process, and select **End task**.

![Disable Vanguard-Related Processes From Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/2-disable-vanguard-related-processes-from-windows-task-manager.jpg)

 Once these processes are disabled, give Valorant a fresh start, which will automatically restart Vanguard. If restarting the processes doesn't make a difference and the process continues to overstretch the CPU, move on to the next step.

## 3\. Make the Vanguard User-Mode Service Process a Low Priority

 Windows allows users to limit the CPU resource usage of processes in two different ways. The first is to change the priority of the process, and the second is to turn on the efficiency mode. Using either of these methods limits the allocation of CPU resources to less essential processes, limiting their CPU usage.

 To change the priority of Vanguard-related processes, go to the **Details** tab, right-click on the **vgc.exe** or any other process, and select **Low** from the **Set Priority** menu.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Change the Priority of the Vanguard User Mode Service Process in the Set Priority Menu in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/3-set-the-vanguard-user-mode-service-process-a-low-priority-in-the-set-priority-menu-in-windows-task-manager.jpg)

 If you choose the latter option to control CPU resource consumption, right-click on the same process and choose **Efficiency mode**.

![Enable the Efficiency Mode of Vgc in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/4-go-to-efficiency-mode-of-vgc-in-windows-task-manage.jpg)

## 4\. Change the Processor Affinity

 The processor affinity setting in Task Manager allows you to limit the number of processors a process can use. Using this setting, you can instruct the process to use only a few processors while leaving others free. In general, the fewer processors a process is permitted to use, the lower its overall resource consumption will be.

 In light of that, changing the processor affinity for the Vanguard process may resolve the issue at hand. To do that, right-click the **vgc.exe** or any other process you want to change the affinity for, then click **Set affinity**.

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Click on Set Affinity Option of Vgc exe in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/5-click-on-set-affinity-option-of-vgc-exe-in-windows-task-manager.jpg)

 Here, uncheck the boxes besides most of the **CPUs** and keep only a few of them checked.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
![Disable Unnecessary CPUs From Processor Affinity Settings in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/6-disable-unnecessary-cpus-from-processor-affinity-settings-in-windows-task-manager.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
## 5\. Stop the Vanguard Service and Restart It

 You may also be able to fix the high CPU resource usage of the Vanguard user-mode service by stopping and starting the Vgc service. Follow these steps to do that:

1. Type **"Services"** in Windows Search and open the **Services** app.
2. Locate the **Vgc** service, right-click on it, and hit **Properties**.  
![Go to Properties of Vgc Service in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/7-go-to-properties-of-vgc-service-in-windows-services-app.jpg)
3. Navigate to the **General** tab, and click on the **Stop** button.
4. After that, restart the service by clicking on the **Start** button again.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
![Stop the Vgc Service in the General Tab of Properties Window in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/8-stop-the-vgc-service-in-the-general-tab-of-properties-window-in-windows-services-app.jpg)
5. Also, choose **Automatic** from the dropdown menu next to **Startup type**.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
![Choose Automatic From the Dropdown Menu Next to Startup Type in General Tab of Properties Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/9-choose-automatic-from-the-dropdown-menu-next-to-startup-type-in-general-tab-of-properties-window.jpg)

<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Disable Third-Party Overlays

 Riot Vanguard is an anti-cheat program. It prevents cheating and bans users who attempt to hack into the game. It does this by detecting unauthorized changes made to the game files and settings using third-party cheat software.

 As reported by some users, using the in-game overlays can also spike CPU resource usage for the Vanguard user-mode service process. Turning off the third-party overlays resulted in a reduction in resource consumption for those users.

 Therefore, if you're using any third-party app to enable in-game overlay, especially Discord, turn it off. Hopefully, this will reduce CPU usage.

![Check the Assigned Hotkey Under Toggle Overlay Lock in the Discord's Game Overlay Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/7-check-the-assigned-hotkey-under-toggle-overlay-lock-in-the-discord-s-game-overlay-settings.jpg)

## 7\. Move Valorant to a Different Drive

 Installing Valorant on the same drive as your operating system has been reported to cause problems. If you've also installed the game on the same drive where your OS resides, it's possible that Windows security could be hindering Vanguard's activity, making it consume more resources.

 To ensure that's not the case, you should move Valorant to a different drive. Not sure how to do that? Refer to our guide on [how to move the installed apps and programs in Windows 10 or 11.](https://www.makeuseof.com/tag/move-installed-apps-programs-windows-10/)

## 8\. Install a Fresh Copy of Vanguard

 If none of the potential fixes have worked, you can use the least desirable option; uninstall Vanguard and reinstall it. However, you need to stop the Vgc service first, as described in the above step; otherwise, you may encounter issues when uninstalling the software. You should also close Valorant and exit Vanguard from the system tray before uninstallation.

 Once that's done, follow the instructions in our [guide on uninstalling software on Windows 11](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) and uninstall Vanguard. Afterward, rerun Valorant and Riot Vanguard will be installed automatically.

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
![installing riot vanguard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/installing-riot-vanguard-1.jpg)

 Valorant and other Riot Games products require Vanguard to function. If Valorant (or any other game) fails to install Vanguard on its own after uninstallation, restart your device once and then run the game again.

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
<li><a href="https://some-techniques.techidaily.com/new-illuminating-colors-the-graders-journey/"><u>[New] Illuminating Colors  The Grader's Journey</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-boost-views-through-effective-youtube-thumbnail-selection/"><u>[New] In 2024, Boost Views Through Effective YouTube Thumbnail Selection</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-transform-your-tech-for-successful-social-media-livestreams/"><u>[New] In 2024, Transform Your Tech for Successful Social Media Livestreams</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-quick-start-guide-dells-simple-screen-recording-methods/"><u>[Updated] 2024 Approved  Quick Start Guide  Dell's Simple Screen Recording Methods</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-the-messenger-maestros-guide-to-capturing-social-media-videos/"><u>[Updated] 2024 Approved  The Messenger Maestro's Guide to Capturing Social Media Videos</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-fine-tune-viewing-the-ultimate-zoom-journey/"><u>[Updated] Fine-Tune Viewing  The Ultimate Zoom Journey</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-vpna-fake-gps-location-free-review-on-poco-m6-pro-4g-drfone-by-drfone-virtual-android/"><u>A Detailed VPNa Fake GPS Location Free Review On Poco M6 Pro 4G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/ace-in-the-game-winning-at-full-screen-with-sonic-adventure-w11-edition/"><u>Ace in the Game: Winning at Full Screen with Sonic Adventure, W11 Edition</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-you-when-your-samsung-galaxy-f54-5g-is-off-drfone-by-drfone-virtual-android/"><u>Can Life360 Track You When Your Samsung Galaxy F54 5G is off? | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/capture-every-click-with-spring-screen-recorder/"><u>Capture Every Click with Spring Screen Recorder</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-graphics-glitch-d3d11-error-fixes-for-win11win10/"><u>Conquering Graphics Glitch: D3D11 Error Fixes for Win11/Win10</u></a></li>
<li><a href="https://article-helps.techidaily.com/cutting-edge-techniques-in-image-fusion/"><u>Cutting-Edge Techniques in Image Fusion</u></a></li>
<li><a href="https://windows11.techidaily.com/defining-windows-lockout-after-inactivity/"><u>Defining Windows Lockout After Inactivity</u></a></li>
<li><a href="https://windows11.techidaily.com/device-duet-pairing-your-android-with-a-pc/"><u>Device Duet: Pairing Your Android with a PC</u></a></li>
<li><a href="https://windows11.techidaily.com/disable-automatic-snipping-tool-activation-by-prtscn-keypress-in-windows-11/"><u>Disable Automatic Snipping Tool Activation by PrtScn Keypress in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/disentangle-windows-11-taskbar-clusters/"><u>Disentangle Windows 11 Taskbar Clusters</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-system-interaction-in-command-prompt/"><u>Elevate Your System Interaction in Command Prompt</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-local-users-group-control-on-win1110/"><u>Essential Guide: Local Users, Group Control on WIN11/10</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/evaluating-the-huawei-p20-pro-outstanding-image-quality-on-an-impressive-android-device/"><u>Evaluating the Huawei P20 Pro: Outstanding Image Quality on an Impressive Android Device</u></a></li>
<li><a href="https://extra-hints.techidaily.com/high-def-phones-with-vlogging-extras/"><u>High-Def Phones with Vlogging Extras</u></a></li>
<li><a href="https://windows11.techidaily.com/how-ai-copilot-enriches-windows-11-for-everyday-users/"><u>How AI Copilot Enriches Windows 11 for Everyday Users</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-specified-user-does-not-have-a-valid-profile-app-error-in-windows-10-and-11/"><u>How to Fix the Specified User Does Not Have a Valid Profile App Error in Windows 10 & 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-remove-infinix-hot-40-pro-pin-by-drfone-android-unlock-android-unlock/"><u>How to remove Infinix Hot 40 Pro PIN</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-best-anti-tracker-software-for-nokia-150-2023-drfone-by-drfone-virtual-android/"><u>In 2024, Best Anti Tracker Software For Nokia 150 (2023) | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-activation-lock-on-apple-iphone-x-or-ipad-by-drfone-ios/"><u>In 2024, How to Bypass Activation Lock on Apple iPhone X or iPad?</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-poco-f5-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to get the dragon scale and evolution-enabled pokemon On Poco F5 5G? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-learn-how-everything-works-on-itel-s23plus-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Learn How Everything Works On Itel S23+ | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/keep-your-disk-space-clear-with-auto-delete-in-win11/"><u>Keep Your Disk Space Clear with Auto-Delete in Win11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/lively-film-reader-assessment-for-2024/"><u>Lively Film Reader Assessment for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/mastering-iphone-creating-and-editing-low-speed-video-clips-for-2024/"><u>Mastering iPhone  Creating & Editing Low-Speed Video Clips for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-performance-monitoring-pcs-ram-gpu-and-cpu/"><u>Maximizing Performance: Monitoring PC's RAM, GPU & CPU</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-app-crashes-in-windows-dealing-with-unhandled-exceptions/"><u>Overcoming App Crashes in Windows: Dealing with Unhandled Exceptions</u></a></li>
<li><a href="https://windows11.techidaily.com/protecting-windows-users-best-free-software-downloaders/"><u>Protecting Windows Users: Best Free Software Downloaders</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-resolving-cant-connect-issues-in-windows-11/"><u>Quick Guide: Resolving 'Can't Connect' Issues in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivating-hidden-remove-option-for-pin-access-control/"><u>Reactivating Hidden 'Remove' Option for PIN Access Control</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagining-microsofts-device-link-capabilities-in-windows-11/"><u>Reimagining Microsoft's Device Link Capabilities in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-the-elusive-gpeditmsc-error-in-windows/"><u>Remedying the Elusive Gpedit.msc Error in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-app-functionality-after-qt-plugin-initialization-breakdown/"><u>Restoring App Functionality After Qt Plugin Initialization Breakdown</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-secure-logins-with-5-tips-against-key-conflicts-in-win11/"><u>Streamlining Secure Logins with 5 Tips Against Key Conflicts in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-non-functional-inbox-alerts-on-windows-os/"><u>Tackling Non-Functional Inbox Alerts on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-for-fixing-unopenable-windows-folders-on-double-click/"><u>Tactics for Fixing Unopenable Windows Folders on Double-Click</u></a></li>
<li><a href="https://windows11.techidaily.com/the-importance-of-keeping-active-wins-11-notification-sounds/"><u>The Importance of Keeping Active Wins 11 Notification Sounds</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/the-top-10-to-11-screen-capturing-tools-for-every-mac-user/"><u>The Top 10 to 11 Screen Capturing Tools for Every Mac User</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-and-tricks-solving-the-try-connecting-bluetooth-issue/"><u>Tips and Tricks: Solving the 'Try Connecting' Bluetooth Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-preventing-windows-autolock-timed-out/"><u>Tips for Preventing Windows Autolock Timed Out</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-nvidia-opengl-glitches-in-windows-11/"><u>Troubleshooting NVIDIA OpenGL Glitches in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-role-of-ai-in-windows-11-updates/"><u>Unveiling the Role of AI in Windows 11 Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/winerror-correction-bypassing-the-perplexing-0x80072746-mail-issue/"><u>WinError Correction: Bypassing the Perplexing 0X80072746 Mail Issue</u></a></li>
</ul></div>
