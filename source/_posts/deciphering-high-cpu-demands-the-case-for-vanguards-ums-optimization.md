---
title: "Deciphering High CPU Demands: The Case for Vanguard's UMS Optimization"
date: 2024-08-08T05:57:09.900Z
updated: 2024-08-09T05:57:09.900Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Deciphering High CPU Demands: The Case for Vanguard's UMS Optimization"
excerpt: "This Article Describes Deciphering High CPU Demands: The Case for Vanguard's UMS Optimization"
keywords: CPU Overheat Solutions,Vanguard UMS Reduction,Performance Optimization,High CPU Demanding,Software Energy Efficiency,Power Management Systems,Computational Resource Utilization
thumbnail: https://thmb.techidaily.com/45fa216ed9179ff239c54a97ced9b6daebc95dcdcc42950e7937059431f2b557.jpg
---

## Deciphering High CPU Demands: The Case for Vanguard's UMS Optimization

 Is the "Vanguard user-mode service" process consuming too much of your CPU resources when playing Valorant? This indicates that Riot Vanguard, an anti-cheat software that prevents unfair gameplay in Valorant, isn't working as it should. High CPU usage can cause lag and stutter in Valorant, completely ruining its performance.

 If you want to reduce the CPU usage of the Vanguard user-mode service process and play Valorant seamlessly, here are some fixes you can try.

<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Apply Some Preliminary Checks

 Start de-stressing your CPU by taking the following basic steps, as they may reduce resource usage immediately:

* Restart Valorant or any other game that spikes the Vanguard user-mode service's CPU consumption.
* Whitelist Vanguard from Windows Defender (see [how to allow apps through the Microsoft firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/)) and the antivirus software you use to ensure your security suites don't cause Vanguard to consume more CPU resources than necessary.
* Be sure to turn off any cheat software you're using to manipulate Valorant or any other Riot Games game.
* Use the Task Manager to filter the processes consuming the most CPU resources by descending order to determine if Vanguard overstresses the CPU the most. If another process turns out to be more burdensome, turn it off.

 If none of the above checks fixes the problem, apply the remaining fixes.

## 2\. Disable and Restart Valorant and Vanguard Processes

 First off, ensure that a temporary glitch hasn't fueled the high CPU usage by the Vanguard user-mode service process. The easiest way to rule out this possibility is to close Valorant, turn off the Vanguard services, and restart them.

 To disable them, right-click the Windows **Start** button and open the **Task Manager**. Here, locate the Vanguard and Valorant-related processes, right-click on each process, and select **End task**.

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
![Disable Vanguard-Related Processes From Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/2-disable-vanguard-related-processes-from-windows-task-manager.jpg)

 Once these processes are disabled, give Valorant a fresh start, which will automatically restart Vanguard. If restarting the processes doesn't make a difference and the process continues to overstretch the CPU, move on to the next step.

## 3\. Make the Vanguard User-Mode Service Process a Low Priority

 Windows allows users to limit the CPU resource usage of processes in two different ways. The first is to change the priority of the process, and the second is to turn on the efficiency mode. Using either of these methods limits the allocation of CPU resources to less essential processes, limiting their CPU usage.

 To change the priority of Vanguard-related processes, go to the **Details** tab, right-click on the **vgc.exe** or any other process, and select **Low** from the **Set Priority** menu.

![Change the Priority of the Vanguard User Mode Service Process in the Set Priority Menu in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/3-set-the-vanguard-user-mode-service-process-a-low-priority-in-the-set-priority-menu-in-windows-task-manager.jpg)

 If you choose the latter option to control CPU resource consumption, right-click on the same process and choose **Efficiency mode**.

![Enable the Efficiency Mode of Vgc in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/4-go-to-efficiency-mode-of-vgc-in-windows-task-manage.jpg)

## 4\. Change the Processor Affinity

 The processor affinity setting in Task Manager allows you to limit the number of processors a process can use. Using this setting, you can instruct the process to use only a few processors while leaving others free. In general, the fewer processors a process is permitted to use, the lower its overall resource consumption will be.

 In light of that, changing the processor affinity for the Vanguard process may resolve the issue at hand. To do that, right-click the **vgc.exe** or any other process you want to change the affinity for, then click **Set affinity**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Click on Set Affinity Option of Vgc exe in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/5-click-on-set-affinity-option-of-vgc-exe-in-windows-task-manager.jpg)

 Here, uncheck the boxes besides most of the **CPUs** and keep only a few of them checked.

![Disable Unnecessary CPUs From Processor Affinity Settings in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/6-disable-unnecessary-cpus-from-processor-affinity-settings-in-windows-task-manager.jpg)

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
## 5\. Stop the Vanguard Service and Restart It

 You may also be able to fix the high CPU resource usage of the Vanguard user-mode service by stopping and starting the Vgc service. Follow these steps to do that:

1. Type **"Services"** in Windows Search and open the **Services** app.
2. Locate the **Vgc** service, right-click on it, and hit **Properties**.  
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Go to Properties of Vgc Service in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/7-go-to-properties-of-vgc-service-in-windows-services-app.jpg)
3. Navigate to the **General** tab, and click on the **Stop** button.
4. After that, restart the service by clicking on the **Start** button again.  
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Stop the Vgc Service in the General Tab of Properties Window in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/8-stop-the-vgc-service-in-the-general-tab-of-properties-window-in-windows-services-app.jpg)
5. Also, choose **Automatic** from the dropdown menu next to **Startup type**.  
![Choose Automatic From the Dropdown Menu Next to Startup Type in General Tab of Properties Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/9-choose-automatic-from-the-dropdown-menu-next-to-startup-type-in-general-tab-of-properties-window.jpg)

## 6\. Disable Third-Party Overlays

 Riot Vanguard is an anti-cheat program. It prevents cheating and bans users who attempt to hack into the game. It does this by detecting unauthorized changes made to the game files and settings using third-party cheat software.

 As reported by some users, using the in-game overlays can also spike CPU resource usage for the Vanguard user-mode service process. Turning off the third-party overlays resulted in a reduction in resource consumption for those users.

 Therefore, if you're using any third-party app to enable in-game overlay, especially Discord, turn it off. Hopefully, this will reduce CPU usage.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
![Check the Assigned Hotkey Under Toggle Overlay Lock in the Discord's Game Overlay Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/7-check-the-assigned-hotkey-under-toggle-overlay-lock-in-the-discord-s-game-overlay-settings.jpg)

## 7\. Move Valorant to a Different Drive

 Installing Valorant on the same drive as your operating system has been reported to cause problems. If you've also installed the game on the same drive where your OS resides, it's possible that Windows security could be hindering Vanguard's activity, making it consume more resources.

 To ensure that's not the case, you should move Valorant to a different drive. Not sure how to do that? Refer to our guide on [how to move the installed apps and programs in Windows 10 or 11.](https://www.makeuseof.com/tag/move-installed-apps-programs-windows-10/)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 8\. Install a Fresh Copy of Vanguard

 If none of the potential fixes have worked, you can use the least desirable option; uninstall Vanguard and reinstall it. However, you need to stop the Vgc service first, as described in the above step; otherwise, you may encounter issues when uninstalling the software. You should also close Valorant and exit Vanguard from the system tray before uninstallation.

 Once that's done, follow the instructions in our [guide on uninstalling software on Windows 11](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) and uninstall Vanguard. Afterward, rerun Valorant and Riot Vanguard will be installed automatically.

![installing riot vanguard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/installing-riot-vanguard-1.jpg)

 Valorant and other Riot Games products require Vanguard to function. If Valorant (or any other game) fails to install Vanguard on its own after uninstallation, restart your device once and then run the game again.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
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

