---
title: "Get Started with Hyper-V: Windows 11 Homes Edition Setup Guide"
date: 2024-10-19T18:15:46.272Z
updated: 2024-10-24T20:21:00.455Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Get Started with Hyper-V: Windows 11 Homes Edition Setup Guide"
excerpt: "This Article Describes Get Started with Hyper-V: Windows 11 Homes Edition Setup Guide"
keywords: Hyper-V Windows 11,Windows 11 Home Setup,VMWare Beginner's Guide,Installing Virtualization,Get Started with Hyper-V,Homes Edition Basics,Virtual PC Windows 11
thumbnail: https://thmb.techidaily.com/20c69587162d153f03eefa64dab5fb5356740a9d42978b0299a0a4d322290d05.jpeg
---

## Get Started with Hyper-V: Windows 11 Homes Edition Setup Guide

 You can enable Hyper-V in Windows 11 as an optional feature included by default with the operating system. It lets you create virtual machines to install and run the guest OS on virtual hardware. However, Hyper-V is only available for the Pro, Education, and Enterprise edition of the OS. If you are using the Home edition, you have to rely on a third-party virtual machine manager.

 If you don’t want to use a third-party virtual machine manager, here is how to install Hyper-V on Windows 11 Home using a batch script hack.

## How to Enable Hardware Virtualization in Windows 11

![enable hardware virtualization bios hp laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hardware-virtualization-bios-hp-laptoop-1.jpg)

 Hyper-V is a bare-metal hypervisor and requires [Hardware Virtualization enabled in BIOS to work](https://www.makeuseof.com/what-is-virtualization-and-what-is-it-for/). Most modern systems support Hardware Virtualization, and you can enable it in BIOS.

 The below steps are for an HP laptop. Refer to the user manual or Knowledge Base resources on the computer manufacturer's website for other systems.

 To enable Hardware Virtualization in BIOS:

1. Shut down your PC if it is powered on.
2. Press the **Power** button to turn on the computer and then start pressing the **F10 key** to enter BIOS. The BIOS setup key varies depending on the manufacturer. So, use **F10, F2, F12, F1,** or **DEL** and see which one works for you.
3. Once in the BIOS Setup utility, open the **Configuration** tab.
4. Use the down arrow key and highlight **Virtualization Technology.**
5. Hit **Enter** and then select **Enabled**. Press **Enter** again to make the selection.
6. Next, press **F10** to save the changes and exit **BIOS**.
7. Your PC will restart with the Hardware Virtualization enabled. Now you can continue to install Hyper-V on your system.

<!-- affiliate ads begin -->
<span id="1743243">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1743243.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19272-1743243">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1743243.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Faligracehair.sjv.io%2Fc%2F5597632%2F1743243%2F19272'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1743243/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Install Hyper-V on Windows 11 Home

 The next step is to create and run a batch script to install the required files to enable Hyper-V in Windows 11 Home.

 Before you proceed with the next set of steps, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/). This will help you restore your computer to its current state if something goes wrong during the process.

 To enable Hyper-V in Windows 11 Home:

 1\. Open a new Notepad file. To do this, press **Win + R**, type notepad, and click **OK.**

![hyper v install windows 11 home script](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/hyper-v-install-windows-11-home-script.png)

 2\. In the Notepad file, copy and paste the following script:

`pushd "%~dp0"  
dir /b %SystemRoot%\servicing\Packages\*Hyper-V*.mum >hyper-v.txt  
for /f %%i in ('findstr /i . hyper-v.txt 2^>nul') do dism /online /norestart /add-package:"%SystemRoot%\servicing\Packages\%%i"  
del hyper-v.txt  
Dism /online /enable-feature /featurename:Microsoft-Hyper-V -All /LimitAccess /ALL  
pause`

 3\. Press **Ctrl + S** to open the save dialog.

 4\. In the file name field, type **hyperv.bat.** The **.bat** extension at the end of the file name is important to execute the script.

![save hyperv install script](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/save-hyperv-install-script.png)

 5\. Next, click the drop-down for **Save as type** and select **All Files.**

 6\. Click the **Save** button to save the file.

![run hyperv bat script administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/run-hyperv-bat-script-administrator.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151888/7443" target="_top" id="2151888">
  <img src="//a.impactradius-go.com/display-ad/7443-2151888" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151888/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 7\. Next, right-click on the **hyperv.bat** file and select **Run as administrator**. Click **Yes** if prompted by User Account Control.

 8\. The scrip will start executing in the Command Prompt to install Hyper-V. It may take a while, so wait till the process is complete.

 9.Once completed, you will see the Operation completed successfully message.

![install hyper v install windows 11 home](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/install-hyper-v-install-windows-11-home.png)

 10\. Type **Y** to confirm and restart your PC. If not, enter N to exit the Command Prompt.

 Note that you will need to restart your PC to apply the changes. After the restart, you should have Hyper-V installed in Windows 11 Home. Type Hyper-V in Windows search and click on Hyper-V Manager to create new a virtual machine.

 If it is still not available, you can [enable Hyper-V using the Windows Features dialog](https://www.makeuseof.com/windows-11-enable-hyper-v/), Command Prompt, and Windows PowerShell.

 Here's how you can quickly add Hyper-V to Windows 11 using Command Prompt:

1. Press the **Win** key and type **cmd**. Then right-click on **Command Prompt** and select **Run as administrator.**  
![enable hyper v command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hyper-v-command-prompt.png)
2. In the Command Prompt window, type the following command and press **Enter**:  
`<code>DISM /Online /Enable-Feature /All /FeatureName:Microsoft-Hyper-V`
3. The above command uses the Deployment Imaging Service and Management (DISM) tool to enable Microsoft Hyper-V and the necessary dependencies on your Windows computer. The operation completed successfully message means you have successfully enabled Hyper-V.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123733/7443" target="_top" id="2123733">
  <img src="//a.impactradius-go.com/display-ad/7443-2123733" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123733/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Disable Hyper-V on Windows 11 Home

![disable hyper v windows 11 windows features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/disable-hyper-v-windows-11-windows-features.jpg)

 You can disable Hyper-V in Windows 11 Home using the Windows Features dialog.

 To disable Hyper-V:

1. Press **Win + R** to open the **Run** dialog box.
2. Type **optionalfeatures.exe** and click **OK**.
3. In the **Windows Features** dialog, locate the Hyper-V option.
4. Uncheck the **Hyper-V** option and click **OK**. Wait for the uninstallation process to complete.
5. Next, click on **Restart Now** to restart your PC and apply the changes.

 Apart from Hyper-V, the Windows OS features another nifty virtualization solution, Windows Sandbox—a lightweight desktop environment to run applications in isolation. You can [enable Windows Sandbox from Windows Features](https://www.makeuseof.com/enable-set-up-windows-sandbox-windows-11/), but only on the Pro and Enterprise edition of the OS.

 Unlike Hyper-V, there is no batch script hack to install the sandbox app on the Home edition of Windows 11\. Instead, you can use one of the [Windows Sandbox Alternatives for Windows](https://www.makeuseof.com/windows-11-sandbox-alternatives/) to run and test applications in isolation.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144310/7443" target="_top" id="2144310">
  <img src="//a.impactradius-go.com/display-ad/7443-2144310" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144310/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Run Hyper-V on Windows 11 Home

 Microsoft has officially restricted the use of Hyper-V to the Pro, Education, and Enterprise edition of the OS. However, a little tweak in the BIOS and a handy batch script can help you install Hyper-V on Windows 11 Home.

 Once you have Hyper-V up and running, you can install Windows, Ubuntu, and other supported operating systems in a virtual machine.

 If you don’t want to use a third-party virtual machine manager, here is how to install Hyper-V on Windows 11 Home using a batch script hack.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-capture.techidaily.com/new-castrecorder-analysis/"><u>[New] CastRecorder Analysis</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-the-quickest-quads-2022-olympics-skate-for-2024/"><u>[New] The Quickest Quads 2022 Olympics Skate for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-windows-11-gamers-script-to-save-playbacks-for-2024/"><u>[New] Windows 11 Gamers' Script to Save Playbacks for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/combat-windows-audio-device-isolation-and-stop-the-cpu-usage-spike/"><u>Combat Window's Audio Device Isolation and Stop the CPU Usage Spike</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722975740753-effortless-driver-update-guide-for-synaptic-ps2-touchpads-get-started-now/"><u>Effortless Driver Update Guide for Synaptic PS/2 Touchpads - Get Started Now!</u></a></li>
<li><a href="https://solve-outstanding.techidaily.com/effortless-guide-transform-your-avchd-video-into-mp4-format-without-costs-on-windows-11/"><u>Effortless Guide: Transform Your AVCHD Video Into MP4 Format without Costs on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-disable-auto-open-of-search-menu-on-windows-11/"><u>How To Disable Auto-Open of Search Menu on Windows 11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-creative-vlog-ideas-for-daily-use/"><u>In 2024, Creative Vlog Ideas for Daily Use</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-infinix-hot-40i-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Infinix Hot 40i to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/leap-into-productivity-windows-11s-multiple-folder-creation-tricks/"><u>Leap Into Productivity: Windows 11'S Multiple Folder Creation Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-barriers-to-installing-games-from-the-microsoft-hub/"><u>Overcoming Barriers to Installing Games From the Microsoft Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/pinpointing-your-pcs-drive-type-with-windows/"><u>Pinpointing Your PC's Drive Type with Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-unresponsive-windows-11-activation-codes/"><u>Resolving Unresponsive Windows 11 Activation Codes</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/step-by-step-crafting-bespo-pointed-video-closures-on-the-dashboard-for-2024/"><u>Step-by-Step Crafting Bespo Pointed Video Closures on the Dashboard for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-artisans-guide-enteringleaving-focus-state-in-the-window-terminal/"><u>The Artisan's Guide: Entering/Leaving Focus State in the Window Terminal</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-ultimate-guide-to-memorable-anime-opens-for-2024/"><u>The Ultimate Guide to Memorable Anime Opens for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/transformative-ui-update-command-line-in-windows-11s-taskbar/"><u>Transformative UI Update: Command Line in Windows 11'S TaskBar</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-permissions-violation-during-setup/"><u>Troubleshooting Windows Permissions Violation During Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-resurrecting-old-folder-tools/"><u>Windows 11: Resurrecting Old Folder Tools</u></a></li>
</ul></div>

