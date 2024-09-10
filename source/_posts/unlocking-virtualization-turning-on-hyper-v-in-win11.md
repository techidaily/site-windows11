---
title: "Unlocking Virtualization: Turning On Hyper-V in Win11"
date: 2024-09-09T12:01:06.528Z
updated: 2024-09-10T12:01:06.528Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlocking Virtualization: Turning On Hyper-V in Win11"
excerpt: "This Article Describes Unlocking Virtualization: Turning On Hyper-V in Win11"
keywords: Hyper-V Enablement,Windows 11 Virtualization,Win11 Hyper-V Activation,Virtual Machine Setup,Win11 VM Optimization,Enabling Hyper-V Features,Windows 11 VM Unlocking
thumbnail: https://thmb.techidaily.com/aa75ccceb27df582eb4900ae099d99b1731677ace1a8dcb38cd4f8698fb9bdda.jpg
---

## Unlocking Virtualization: Turning On Hyper-V in Win11

 Hyper-V is Microsoft's in-house virtualization solution for Windows 11\. It lets you create virtual machines and run them on virtual hardware. That said, if you want to use Hyper-V on your computer, you will need to enable it first.

 In this article, we show you the how to enable Hyper-V in Windows 11 and create virtual machines without third-party tools.

## What Are the Use Cases for Hyper-V?

 Hyper-V is a native virtualization tool that allows you to run multiple operating systems on your system virtually without affecting your host OS.

 With Hyper-V, you don’t have to rely on third-party hypervisor solutions such as VirtualBox and VMware Workstation. [Hyper-V has plenty of use cases for individuals](https://www.makeuseof.com/tag/reasons-start-using-virtual-machine/), and even more for organizations.

 Some Hyper-V virtual machine use cases include:

* Run and test software for an older version of Windows or non-Windows OS
* Test software on multiple operating systems using multiple virtual machines on a single host system.
* Offers disaster recovery features including live migration and failover clustering for increased uptime.
* Create and run virtual machines in isolation for improved security.

## Prerequisites to Enable Hyper-V on Windows 11

![check Windows 11 edition](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/check-Windows-11-edition.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130875/7443" target="_top" id="2130875">
  <img src="//a.impactradius-go.com/display-ad/7443-2130875" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130875/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Hyper-V is available as an optional feature on Windows 11 Pro, Enterprise, and Education. To check your edition of Windows, go to **Settings > System > About**. Then, check the **Windows specifications** section to find your Windows edition.

 If you have the Home edition, here’s how to [install Hyper-V on Windows 11 Home](https://www.makeuseof.com/install-hyper-v-windows-11-home/). All you have to do is run a bat script to install Hyper-V on non-compatible systems.

 Depending on how many virtual machines and types of applications you intend to run, you may need more resources to run the virtual machines smoothly.

 In addition, you need to enable Hardware Virtualization in BIOS. It is an essential feature to run virtual machines on your Windows system but often disabled by default.

## How to Enable Hardware Virtualization in BIOS

 On compatible systems, you can enable Hardware Virtualization in BIOS. The below steps are for an HP computer. If you are using a custom-made PC or laptop from another manufacturer, refer to the user manual for detailed instruction. If not, refer to our general guide to [enter the BIOS on Windows](https://www.makeuseof.com/tag/enter-bios-computer/).

 To enable Hardware Virtualization in BIOS:

1. Shut down your PC if it is powered on.
2. Press the **Power** button to power on the system and start pressing the **Esc** key to view the **Startup Menu.**
3. In the **Startup Menu**, press **F10** to enter the **BIOS setup.**  
![Startup menu hp laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/Startup-menu-hp-laptop.jpg)
4. In the BIOS Setup Utility, use the arrow key and open the **Configuration** tab.
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137214/26400" target="_top" id="2137214">
  <img src="//a.impactradius-go.com/display-ad/26400-2137214" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137214/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Next, use the down arrow key to highlight the **Virtualization Technology** option.  
![enable hardware virtualization bios hp laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hardware-virtualization-bios-hp-laptoop.jpg)
6. Hit **Enter** and then select **Enabled** from the options.
7. Press **F10** to save the changes and exit **BIOS**.
8. Your PC will restart and apply the changes. This may take a while, so wait till your system is fully restarted.

 After restart, you can enable Hyper-V on Windows 11\. Here’s how to do it.

## 1\. Turn On Hyper-V in Windows 11 Via Control Panel

![enable hyper v windows features control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hyper-v-windows-features-control-panel.png)

 You can enable Hyper-V using the Windows Features dialog. You can access Windows Features to [add or remove optional features in Windows 11](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) from the Control Panel. Here’s how to do it.

1. Press **Win + R** to open **Run**.
2. Type **control** and click **OK** to open the Control Panel.
3. In the Control Panel, go to **Programs > Programs and Features.**
4. In the left pane, click on **Turn Windows features on or off.**
5. In the **Windows Features** dialog, select **Hyper-V.** If you expand Hyper-V, you will see **Hyper-V Management Tools** and **Hyper-V Platforms.**
6. Make sure both the options are selected and click **OK**. Since these are optional features, Windows will begin to install and enable them on your PC. This process may take some time to complete.
7. Once completed, click on **Restart Now** to restart, and apply the changes.

 After the restart, search for **Hyper-V** and click on **Hyper-V Manager** to create virtual machines in Windows 11\.

## 2\. Add Hyper-V to Windows 11 Using Command Prompt

![enable hyper v command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hyper-v-command-prompt.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135411/19272" target="_top" id="2135411">
  <img src="//a.impactradius-go.com/display-ad/19272-2135411" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135411/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Command Prompt offers a fast and efficient way to perform repetitive tasks. You can use the DISM (Deployment Image Servicing and Management) command-line tool to access and install optional Windows features via Command Prompt.

 Follow these steps to enable Hyper-V on Windows 11 using Command Prompt:

1. Press the **Win** key, and type **cmd**. Then, right-click on **Command Prompt** and select **Run as Administrator.**
2. In the Command Prompt window, type the following command and hit Enter to execute:  
`DISM /Online /Enable-Feature /All /FeatureName:Microsoft-Hyper-V`
3. The Deployment Image Servicing and Management tool will start enabling the Hyper-V feature and show the progress on the Command Prompt.
4. Once the operation is completed successfully, you will need to restart your PC. So, press **Y** on your keyboard to confirm the action.

 After your PC restarts, you can open and [use the Hyper-V Manager to create virtual machines](https://www.makeuseof.com/tag/create-virtual-machine-using-windows-10-hyper-v/).

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123477/16836" target="_top" id="2123477">
  <img src="//a.impactradius-go.com/display-ad/16836-2123477" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123477/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Enable Hyper-V Using PowerShell

![enable hyper v windows 11 powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hyper-v-windows-11-powershell.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123739/7443" target="_top" id="2123739">
  <img src="//a.impactradius-go.com/display-ad/7443-2123739" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123739/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If you prefer Windows PowerShell over Command Prompt, you can also enable Hyper-V using the shell application.

 However, unlike Command Prompt, PowerShell uses the enable-WindowsOptional features cmdlet to enable optional features in a Windows image.

 To enable Hyper-V using PowerShell:

1. Press the **Win** key, and type **powershell**. Then, right-click on **PowerShell** and select **Run as Administrator.**
2. In the PowerShell window, type the following shell command and hit Enter:  
`Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V-All`
3. PowerShell will run the cmdlet and initiate the Hyper-V enabling process. If successful, you will be asked to restart your PC.
4. Type **Y** to confirm, and your PC will restart to apply the changes and enable a new feature.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134238/18498" target="_top" id="2134238">
  <img src="//a.impactradius-go.com/display-ad/18498-2134238" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134238/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Disable Hyper-V in Windows 11

 While Hyper-V is safe to enable and use, you can disable it as easily using PowerShell. Useful if the virtualization tool causes conflict with your antivirus solution and other apps.

 To disable Hyper-V using PowerShell:

* Open **PowerShell** as administrator.
* In the PowerShell window, type the following command and press Enter:  
`Disable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V-All`
* Wait for the success message to appear and close PowerShell.
* Restart your PC to apply the changes.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115949/19272" target="_top" id="2115949">
  <img src="//a.impactradius-go.com/display-ad/19272-2115949" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115949/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Configure Hyper-V Settings

![hyper v manager windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hyper-v-manager-windows-11.jpg)

 Once Hyper-V is up and running, you can configure some settings to optimize your virtual machines for optimal performance. Here are a few settings you can configure before creating a virtual machine. You can access these settings from the right pane in Hyper-V Manager.

* **Hyper-V Settings:** You can configure your virtual hard disk and virtual machine location, configure NUMA spanning storage migration, and allow enhanced session mode. On the user side, it lets you configure the virtual machine's keyboard and the mouse release key.
* **Virtual Switch Manager:** It lets you create External, Internal, or Private switches. Virtual switches are bound to the physical network adapter to access the network.
* **Integration services:** You can choose from and enable/disable a host of integration services, including Heartbeat, Key-Value pair exchange, Time synchronization, and Volume shadow copy requestor (VSS) to enhance the performance and functionality of your virtual machine.

![Windows admin center console home](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-admin-center-console-home.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137209/26400" target="_top" id="2137209">
  <img src="//a.impactradius-go.com/display-ad/26400-2137209" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137209/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 While the MMC-based Hyper-V manager is functional and built into the OS, consider using the relatively new Windows Admin Center. It is a browser-based management app that lets you manage your servers, virtual machines, local users and groups, and more.

 Download [Windows Admin Center](https://www.microsoft.com/en-in/windows-server/windows-admin-center) from the official Microsoft page and run the installer to give it a go. Once installed, open the app, and it will launch in your default browser, giving you access to a host of management tools.

<!-- affiliate ads begin -->
<span id="1834906">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1834906.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16836-1834906">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1834906.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2F25home.pxf.io%2Fc%2F5597632%2F1834906%2F16836'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1834906/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Many Ways to Enable Hyper-V in Windows 11

 Hyper-V is a type 1 hypervisor, which means it runs directly on a computer’s hardware. It comes pre-installed, free to use without restriction, and offers linear performance on a consumer-grade system.

 That said, dedicated virtual machines such as the VMWare WorkStation Pro is available on multiple platforms, can be used on older systems, and is more suitable for enterprise solutions. Check out our comparison comparing the three popular hypervisors to find the one that works for you.

 In this article, we show you the how to enable Hyper-V in Windows 11 and create virtual machines without third-party tools.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-tips.techidaily.com/new-in-2024-ghostly-pause-recorder-tutorial/"><u>[New] In 2024, Ghostly Pause Recorder Tutorial</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-streaming-showdown-obs-and-shadowtoolkit/"><u>[Updated] 2024 Approved Streaming Showdown OBS & ShadowToolkit</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-no-root-audio-recording-on-android-devices-tutorial/"><u>[Updated] In 2024, No-Root Audio Recording on Android Devices [Tutorial]</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-musical-milestones-celebrate-your-growth-with-these-15-vids/"><u>[Updated] Musical Milestones Celebrate Your Growth with These 15 Vids</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-the-future-is-here-free-innovative-fb-story-enhancers/"><u>[Updated] The Future Is Here Free, Innovative FB Story Enhancers</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-infinix-hot-30i-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Infinix Hot 30i</u></a></li>
<li><a href="https://article-tips.techidaily.com/affordable-aerial-acrobats-best-bargain-drones-for-(500/"><u>Affordable Aerial Acrobats Best Bargain Drones for <$500</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-uninstall-tactics-for-windows-11-os-108-chars/"><u>Essential Uninstall Tactics for Windows 11 OS (108 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-disconnections-in-external-display-setup-on-windows/"><u>Fixing Disconnections in External Display Setup on Windows</u></a></li>
<li><a href="https://hardware-help.techidaily.com/from-hot-to-cold-the-groundbreaking-thermal-techniques-of-pcie-60-surpassing-previous-generations/"><u>From Hot to Cold: The Groundbreaking Thermal Techniques of PCIe 6.0 Surpassing Previous Generations</u></a></li>
<li><a href="https://windows11.techidaily.com/get-up-to-speed-on-windows-11s-user-friendly-taskbar-search-feature/"><u>Get up to Speed on Windows 11’S User-Friendly Taskbar Search Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-microsoft-store-error-code-0x00000000-in-windows-11-and-11/"><u>How to Fix the Microsoft Store Error Code 0X00000000 in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-application-dependency-resolution-with-wpm/"><u>Mastering Application Dependency Resolution with WPM</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-window-11-search-bar-camouflage/"><u>Mastering the Art of Window 11 Search Bar Camouflage</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-process-of-fixing-disabled-hard-drive-on-your-windows-11-pc/"><u>Mastering the Process of Fixing Disabled Hard Drive on Your Windows 11 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-window-11-stealthy-hiding-of-linguistic-signal/"><u>Mastering Window 11: Stealthy Hiding of Linguistic Signal</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-security-pin-fix-strategies/"><u>Mastering Windows Security: PIN Fix Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/open-windows-11s-memory-lane-file-history-guide/"><u>Open Windows 11'S Memory Lane - File History Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/perfecting-papyrus-best-note-taking-tabs-in-windows/"><u>Perfecting Papyrus: Best Note-Taking Tabs in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-window-11s-system-monitor-screen/"><u>Personalize Window 11'S System Monitor Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-access-to-windows-photos-functions-via-shortcuts/"><u>Quick Access to Windows Photos Functions via Shortcuts</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-to-turn-off-windows-11-notifies/"><u>Quick Guide to Turn Off Windows 11 Notifies</u></a></li>
<li><a href="https://windows11.techidaily.com/rapid-dns-flush-techniques-for-win11-devices/"><u>Rapid DNS Flush Techniques for Win11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/reactive-steps-for-faulty-windows-performance-tracking-tool/"><u>Reactive Steps for Faulty Windows Performance Tracking Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/redefining-innovation-in-windows-with-enhancements/"><u>Redefining Innovation in Windows with Enhancements</u></a></li>
<li><a href="https://driver-install.techidaily.com/refresh-graphics-drivers-for-better-windows-10-viewing/"><u>Refresh Graphics Drivers for Better Windows 10 Viewing</u></a></li>
<li><a href="https://windows11.techidaily.com/reigniting-disappearing-windows-on-your-screen-top-6-fixes-for-win11/"><u>Reigniting Disappearing Windows on Your Screen: Top 6 Fixes for Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/reinvigorating-deactivated-alerts-of-phone-link-app-in-windows/"><u>Reinvigorating Deactivated Alerts of Phone Link App in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-not-available-status-codes-in-windows-os/"><u>Resolving 'Not Available' Status Codes in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-smooth-os-operation-via-pct-steps/"><u>Securing Smooth OS Operation via PCT Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/slash-clutter-not-performance-unnecessary-windows-applications-you-can-delete/"><u>Slash Clutter, Not Performance: Unnecessary Windows Applications You Can Delete</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-unacceptable-connections-in-microsoft-os/"><u>Solving Unacceptable Connections in Microsoft OS</u></a></li>
<li><a href="https://windows11.techidaily.com/speeding-up-purchases-on-microsofts-digital-shelf/"><u>Speeding Up Purchases on Microsoft's Digital Shelf</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-to-unlocking-windows-11-desktop-toolbar/"><u>Step-by-Step to Unlocking Windows 11 Desktop Toolbar</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-counteract-error-x80300024-in-winxp/"><u>Steps to Counteract Error X80300024 in WinXP</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-tackle-corrupted-files-and-directories-win10-11-edition/"><u>Strategies to Tackle 'Corrupted' Files & Directories: Win10-11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/taking-control-a-comprehensive-guide-to-touchpad-adjustment-on-windows-11/"><u>Taking Control: A Comprehensive Guide to Touchpad Adjustment on Windows 11</u></a></li>
<li><a href="https://article-tips.techidaily.com/the-best-ios-camera-apps-to-elevate-your-iphone-imagery/"><u>The Best iOS Camera Apps to Elevate Your iPhone Imagery</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-steps-for-boosting-vm-efficiency-with-virtualbox-v70-in-windows-11/"><u>The Essential Steps for Boosting VM Efficiency with VirtualBox v7.0 in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-harnessing-powertoys-10-must-knows/"><u>The Ultimate Guide to Harnessing PowerToys' 10 Must-Knows</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-speedy-windows-11-boot-turn-on-quick-startup/"><u>Tips for Speedy Windows 11 Boot: Turn on Quick Startup</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-how-you-use-your-computer-find-these-6-win-trackers/"><u>Transform How You Use Your Computer: Find These 6 Win Trackers</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-resolving-winrars-sum-verification-failures/"><u>Troubleshooting: Resolving WinRAR's Sum Verification Failures</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-secure-access-a-comprehensive-look-at-fixes-for-key-errors-in-win11/"><u>Unlocking Secure Access: A Comprehensive Look at Fixes for Key Errors in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unplugging-and-plugging-in-your-wireless-mouse-quick-fixes/"><u>Unplugging and Plugging In Your Wireless Mouse - Quick Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-windows-11-writability-creating-self-extractables/"><u>Unraveling Windows 11' Writability: Creating Self-Extractables</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-design-faux-pas-a-list-of-7/"><u>Windows 11'S Design Faux Pas: A List of 7</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>