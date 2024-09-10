---
title: Tips for Lowering Cpu Usage by WMI Service
date: 2024-09-09T12:06:06.249Z
updated: 2024-09-10T12:06:06.249Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tips for Lowering Cpu Usage by WMI Service
excerpt: This Article Describes Tips for Lowering Cpu Usage by WMI Service
keywords: Low CPU WMI Impact,Reduce WMI CPU Load,Optimize CPU via WMI,Slash WMI Resource Use,Cut PC CPU for WMI,Efficient CPU WMI Use,Decrease WMI Power Usage
thumbnail: https://thmb.techidaily.com/b88f149e018190d8db992f5fa62ce84a76816eeb035902ad86368ed1da64a17e.jpg
---

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134229/18498" target="_top" id="2134229">
  <img src="//a.impactradius-go.com/display-ad/18498-2134229" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134229/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Tips for Lowering Cpu Usage by WMI Service

 If your computer is heating up and the CPU fan is running loudly, it could mean there is an issue with the Windows Modules Installer Worker process. This process is part of the operating system and handles Windows updates. In some cases, it leads to slow speeds and even system crashes due to high CPU usage.

 In this article, we will discuss how to resolve CPU usage issues with Windows Modules Installer Worker.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118319/7443" target="_top" id="2118319">
  <img src="//a.impactradius-go.com/display-ad/7443-2118319" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118319/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Give It Some Time

 If your computer's "Windows Modules Installer Worker" process is using a lot of CPU power, it means that Windows is busy installing updates or doing system maintenance in the background. These tasks may take a few minutes to complete, and the CPU usage should go back to normal afterward.

 So if you're not in a hurry, give it some time and let it finishes before trying anything else.

## 2\. Restart Your Computer

 If there is no ongoing update process or system maintenance, and CPU usage is still abnormally high, restart your computer. This will kill all running programs, including "Windows Modules Installer Worker" and any other process that might be causing the issue.

 To restart your computer, open the **Start** menu or hit the **Windows** key. Select the **Power** icon and click **Restart** from the menu. Once your computer restarts, see if CPU usage is back to normal.

## 3\. Run the Windows Update Troubleshooter

 If restarting doesn't work, run the Windows Update troubleshooter. This tool scans for any issues with Windows Update and automatically fixes them, which might solve the "Windows Modules Installer Worker" high CPU usage issue.

 To run the troubleshooter, follow these steps:

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **Control Panel** in the dialog box and hit Enter. This will open the Control Panel.
3. Change the Control Panel view to **Large icons** or **Small icons**.
4. Locate and click on the **Troubleshooting** option.  
![Troubleshooting in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/troubleshooting-in-control-panel.jpg)
5. On the right side, click **Other troubleshooters**.  
![Other troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/other-troubleshooters.jpg)
6. Click **Run** next to **Windows Update**.  
![Run Windows Update Troubleshooter-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-windows-update-troubleshooter-1.jpg)

 The troubleshooter will now run and attempt to fix any Windows Update issues. After the troubleshooter finishes its scan and fixes any problems, see if it solves your problem.

## 4\. Restart the Windows Update Service

 Another solution is to restart Windows Update. This will reset the Windows Update settings and possibly fix any issues causing the high CPU usage. Here's how to do it:

1. [Open the Run command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **services.msc** in the dialog box and hit Enter. This will open the Services console.
3. Look for **Windows Update** in the list of services.
4. Right-click on it and select **Restart** from the menu.  
![Restart Windows Update Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restart-windows-update-service.jpg)

 Once the service has been restarted, check if the "Windows Modules Installer Worker" process is still using a lot of CPU power.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118326/7443" target="_top" id="2118326">
  <img src="//a.impactradius-go.com/display-ad/7443-2118326" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118326/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Set Windows Update to Manual Mode

 The Windows Modules Installer Worker process sometimes remains active even when there are no updates to install. This usually happens when the Windows Update service is set to Automatic.

 To fix this issue, you can change the Windows Update service to manual mode. This will prevent Windows from running the process all the time and reduce CPU usage.

 To change Windows Update into manual mode, do the following:

1. [Open the Services window](https://www.makeuseof.com/windows-11-open-services-app/).
2. Scroll down and right-click on **Windows Update**.
3. From the context menu, select the **Properties** option. You can also double-click on the service to open its Properties window
4. On the **General** tab, set the **Startup type** to **Manual** and click **OK**.  
![Set Windows Update to Manual](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/set-windows-update-to-manual.jpg)
5. Next, locate **Windows Modules Installer** in the list of services and repeat the same steps.

 Once done, restart your computer and see if CPU usage has reduced. If not, try the next solution.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014850/22899" target="_top" id="2014850">
  <img src="//a.impactradius-go.com/display-ad/22899-2014850" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014850/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Disable Windows Update

 If high CPU usage persists, you can disable Windows Update completely. This is not a recommended long-term solution since updates are crucial for security and performance. But if needed, you can disable it for now and check CPU usage.

 To disable Windows Update, do the following.

1. Click on Start and type **Services** in the search box.
2. Select Services from the results list. This will open the Services window.
3. Look for **Windows Update** in the list of services.
4. Right-click on it and select **Stop** from the context menu.  
![Stop Windows Update Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/stop-windows-update-service.jpg)
5. Upon stopping the Windows Update service, double-click on it to open its Properties window.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118311/7443" target="_top" id="2118311">
  <img src="//a.impactradius-go.com/display-ad/7443-2118311" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118311/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. On the **General** tab, click **Startup type** and select **Disabled** from the dropdown.  
![Disable Windows Update Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-windows-update-service.jpg)
7. Click **Apply** \> **OK** to save your changes.
<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123477/16836" target="_top" id="2123477">
  <img src="//a.impactradius-go.com/display-ad/16836-2123477" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123477/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After performing the above steps, close the Services window and restart your computer. Check if the "Windows Modules Installer Worker" process is still using CPU resources. Don't forget to enable Windows Update once you're done troubleshooting.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139121/17108" target="_top" id="2139121">
  <img src="//a.impactradius-go.com/display-ad/17108-2139121" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139121/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Clear the SoftwareDistribution Folder

 Another thing you can do is delete the Software Distribution folder. This folder holds temporary files used during Windows updates. However, if there are any corrupt or outdated files in this folder, it might cause high CPU usage.

 In that case, delete the folder and let Windows recreate it. To clear the SoftwareDistribution folder, follow these steps:

1. [Run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. In the Command Prompt window, type the following commands and hit Enter after each one:  
`net stop wuauserv  
net stop bits  
net stop cryptSvc  
net stop msiserver`
3. Upon executing the above commands, open Windows File Explorer and browse to the following location:  
C:\Windows\SoftwareDistribution\
4. In the SoftwareDistribution folder, use **Ctrl + A** to select all contents then delete them.  
![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/clear-softwaredistribution-folder.jpg)
5. If a pop-up menu asks for permission, click **Continue**.
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134493/18498" target="_top" id="2134493">
  <img src="//a.impactradius-go.com/display-ad/18498-2134493" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134493/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. After deleting the Software Distribution folder, you will need to restart the services you stopped previously. For this, launch the elevated command prompt again and run the following command:  
`net start wuauserv  
net start bits  
net start cryptSvc  
net start msiserver`

 Now close the Command Prompt window and restart your computer. Now check if the Windows Modules Installer Worker process still consumes CPU power.

## 8\. Try Some Generic Windows Fixes

 Aside from the solutions above, there are some generic fixes you can try to reduce high CPU usage. This includes [disabling unnecessary startup programs](https://www.makeuseof.com/windows-11-disable-startup-programs/) and [repairing corrupted system files](https://www.makeuseof.com/windows-built-in-repair-tools/). If you have downloaded any third-party programs, uninstall them and check if that helps.

 In addition, check if you have installed any updates recently. Corrupted or incompatible updates can cause high CPU usage issues. If the problem persists after performing these steps, [perform a system restore](https://www.makeuseof.com/use-system-restore-windows/).

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2129041/19576" target="_top" id="2129041">
  <img src="//a.impactradius-go.com/display-ad/19576-2129041" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2129041/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Optimizing High CPU Usage on Windows

 If Windows Modules Installer Worker is using too much CPU power, you now have solutions to try. Although this process usually utilizes computer resources while installing updates and shouldn't create issues, if you observe that it is using excessive CPU power for an extended period, you can try deactivating services, deleting files from the SoftwareDistribution folder, and implementing common fixes.

 In this article, we will discuss how to resolve CPU usage issues with Windows Modules Installer Worker.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-epic-virtual-realms-finest-10-budget-friendly-mmorpgs/"><u>[New] 2024 Approved Epic Virtual Realms Finest 10 Budget-Friendly MMORPGs</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-sun-salutations-and-beyond-youtubes-premier-yoga-pages/"><u>[New] 2024 Approved Sun Salutations & Beyond – YouTube's Premier Yoga Pages</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-customize-your-youtube-view-adjust-speed-settings-for-2024/"><u>[New] Customize Your YouTube View Adjust Speed Settings for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-frontier-visionaries-merging-media-triad/"><u>[Updated] 2024 Approved Frontier Visionaries Merging Media Triad</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-costlesscapture-revolutionizing-how-you-record-play/"><u>[Updated] CostlessCapture Revolutionizing How You Record Play</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-expert-recommendations-top-5-video-recording-software/"><u>[Updated] Expert Recommendations Top 5 Video Recording Software</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-strategies-for-winning-back-defective-windows-apps/"><u>Essential Strategies for Winning Back Defective Windows Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/extending-windows-11-shutdown-for-active-tasks-tips-and-tricks/"><u>Extending Windows 11 Shutdown for Active Tasks: Tips & Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/fixes-for-application-flood-conquering-0x80860010/"><u>Fixes for Application Flood: Conquering 0X80860010</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-crashes-caused-by-windows-0x0000011b-error/"><u>Fixing Crashes Caused by Windows' 0X0000011B Error</u></a></li>
<li><a href="https://windows11.techidaily.com/google-chrome-unresponsiveness-solved-expert-troubleshooting-tips/"><u>Google Chrome Unresponsiveness Solved: Expert Troubleshooting Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-awaken-divine-powers-within-windows-11-os/"><u>How to Awaken Divine Powers Within Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-clean-up-and-customize-your-windows-11-desktop/"><u>How to Clean Up and Customize Your Windows 11 Desktop</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-migrate-android-data-from-honor-x50-to-new-android-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Migrate Android Data From Honor X50 to New Android Phone? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-most-known-ways-to-find-someone-on-tinder-for-infinix-note-30-by-name-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Most-Known Ways to Find Someone on Tinder For Infinix Note 30 by Name | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-easy-guide-to-oppo-find-x6-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to Oppo Find X6 FRP Bypass With Best Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/making-windows-10-work-tips-if-you-cant-upgrade/"><u>Making Windows 10 Work: Tips if You Can't Upgrade</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/nvidia-quadro-graphics-driver-update-compatible-with-windows-11-systems/"><u>NVIDIA Quadro Graphics Driver Update - Compatible with Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-obstacles-in-installation-for-windo-users/"><u>Overcoming Obstacles in Installation for Windo Users</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-obstacles-fixing-outlook-issues-in-windows/"><u>Overcoming Obstacles: Fixing Outlook Issues in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-app-glitch-x80131500/"><u>Overcoming Windows App Glitch X80131500</u></a></li>
<li><a href="https://windows11.techidaily.com/pro-tips-for-capturing-uac-alerts-in-windows/"><u>Pro Tips for Capturing UAC Alerts in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/quieting-chrome-bugs-on-windows-systems/"><u>Quieting Chrome Bugs on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-lost-web-interfaces-of-router-on-windows/"><u>Resetting Lost Web Interfaces of Router on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-audio-communication-via-xbox-mic-and-windows-11/"><u>Restoring Audio Communication via Xbox Mic & Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-missing-alerts-a-guide-for-non-working-phone-link-on-pc/"><u>Restoring Missing Alerts: A Guide for Non-Working Phone Link on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/solve-your-nvidia-scanner-trouble-in-windows-environment/"><u>Solve Your Nvidia Scanner Trouble in Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-steam-broadcast-glitches-in-windows/"><u>Solving Steam Broadcast Glitches in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/stalled-opera-install-windows-fix-guide/"><u>Stalled Opera Install? Windows Fix Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-insert-isp-info-on-taskbar/"><u>Step-by-Step Guide: Insert ISP Info on Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-permanently-start-windows-terminal-as-admin/"><u>Steps to Permanently Start Windows Terminal as Admin</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-disabling-discordutation-at-windows-boot-up/"><u>Techniques for Disabling Discord'utation at Windows Boot-Up</u></a></li>
<li><a href="https://windows11.techidaily.com/the-threat-within-detecting-and-disabling-wacatacbml-trojan-on-pcs/"><u>The Threat Within: Detecting and Disabling Wacatac.B!ml Trojan on PCs</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-data-from-130-music-by-fonelab-android-recover-data/"><u>The way to get back lost data from 130 Music</u></a></li>
<li><a href="https://windows11.techidaily.com/thriving-on-windows-11-essential-methods/"><u>Thriving on Windows 11: Essential Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-fixing-non-responsive-pc-gamepad-issues/"><u>Tips for Fixing Non-Responsive PC Gamepad Issues</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/transform-your-channel-with-effective-youtube-link-protocols-for-2024/"><u>Transform Your Channel with Effective YouTube Link Protocols for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-chrome-cookie-and-cache-issues-for-download-problems-windows/"><u>Troubleshooting Chrome’ Cookie & Cache Issues for Download Problems, Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-print-spooler-down-on-windows-pcs/"><u>Troubleshooting Print Spooler Down on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-steps-for-bypassing-endless-logon-prompts/"><u>Troubleshooting Steps for Bypassing Endless Logon Prompts</u></a></li>
<li><a href="https://windows11.techidaily.com/tutorial-reverting-the-search-bar-design-of-windows-11/"><u>Tutorial: Reverting the Search Bar Design of Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/uniting-android-tabs-with-windows-11-for-enhanced-workflow/"><u>Uniting Android Tabs with Windows 11 for Enhanced Workflow</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-potential-of-ai-in-microsoft-store/"><u>Unlocking the Potential of AI in Microsoft Store</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>