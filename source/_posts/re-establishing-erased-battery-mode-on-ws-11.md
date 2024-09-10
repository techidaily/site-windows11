---
title: Re-Establishing Erased Battery Mode on WS 11
date: 2024-09-09T12:07:27.841Z
updated: 2024-09-10T12:07:27.841Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Re-Establishing Erased Battery Mode on WS 11
excerpt: This Article Describes Re-Establishing Erased Battery Mode on WS 11
keywords: Restore Battery Saver,Reset Power Save,Reboot Energy Mode,Reenable Low Power,Revive Battery Sleep,Reactivate Slumber State,Refuel Battery Reserve
thumbnail: https://thmb.techidaily.com/1501cba3c5f4c4b803b623584f546bd1f9723b8ea081222f679c45ec271effc3.jpg
---

## Re-Establishing Erased Battery Mode on WS 11

 Windows 11 and 10 come with preset power plans: High Performance, Power Saver, Balanced, and sometimes Ultimate Performance. You can switch between these plans to get the best performance, more battery life or a bit of both worlds. Some laptop manufacturers, like HP, have their own power plan, like HP Recommended.

 However, often after installing a Windows update, default power plans can go missing, or you may see only one power plan. This can also happen if you have made changes to your power plans recently. In any case, here are a few troubleshooting steps to help restore the missing default power plans on Windows 11 and 10 running systems.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134238/18498" target="_top" id="2134238">
  <img src="//a.impactradius-go.com/display-ad/18498-2134238" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134238/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Check Which Power Plan Is Missing

![check missing power plans control panel windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-missing-power-plans-control-panel-windows-11.jpg)

<!-- affiliate ads begin -->
<span id="1304647">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1304647.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1304647">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1304647.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1304647%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1304647/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Depending on your system hardware specification, you may see three or four power plans in the Power Options panel. Balanced, Power Saver and High Performance are the most common in all Windows computers.

 However, higher-end hardware running Windows 11\\10 Pro can have the Ultimate Performance Power plan as well. It is a preset power plan to help boost your system performance in a professional setup. Even if available, enabling the[Ultimate Performance power plan may not be necessary for most users](https://www.makeuseof.com/should-you-enable-ultimate-performance-power-plan-windows-10/) .

 You can check the available and missing power plans on Windows from Control Panel:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK**
3. In the**Control Panel** , open**Hardware and Sound.**
4. Next, click on**Power Options** .
5. Expand the**Show additional plans** section.

## 1\. Change Power Mode From the Settings Panel

![change power mode windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/change-power-mode-windows-11.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118324/7443" target="_top" id="2118324">
  <img src="//a.impactradius-go.com/display-ad/7443-2118324" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118324/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
[On Windows 11, you can change the power mode from the Settings app](https://www.makeuseof.com/windows-11-change-power-plan/) . You can choose between the Best power efficiency, Balanced, and Best performance power modes in the Power & battery settings.

To change power mode on Windows 11:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, scroll down and click on**Power & battery** .
3. Click the drop-down for**Power mode** and select your preferred power plan.

 If the Power Mode doesn’t show any or some power schemes, you’ll need to restore it using the powercfg command-line utility.

## 2\. Reset the Default Power Plan Settings Using Power PowerShell

![](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reset-default-power-plans-windows-11-powershell.jpg)

 Before you try to restore the power plans, reset all the power plan settings to factory default. A reset will only fix issues that occurred due to incorrect configuration.

To reset Windows default power plans:

1. [Open PowerShell with administrator rights.](https://www.makeuseof.com/windows-11-powershell-administrator/)
2. In the PowerShell window, type the following command and press**Enter** :  
`powercfg -restoredefaultschemes`
3. The above command will reset default power schemes. Close PowerShell and check for any improvements.

## 3\. Restore the Missing Power Plan Using the Command Prompt

![restore default power plan windows 11 command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/restore-default-power-plan-windows-1-command-prompt.jpg)

<!-- affiliate ads begin -->
<span id="1938141">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938141.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938141">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938141.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938141%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938141/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You can restore the missing default power plans on Windows using the Command Prompt. We’ll use the**powercfg** command-line feature to duplicate the existing but missing power plans.

 Follow these steps to restore the missing control power schemes. Make sure to only execute the commands for the power control schemes that are missing. Otherwise, it will create duplicate entries for the same power plan in Power Options.

1. Press the**Win** key and type**cmd** .
2. Right-click on**Command Prompt** and select**Run as administrator** .
3. In the Command Prompt window, type the following command and press Enter:  
`[High Performance]  
powercfg -duplicatescheme 8c5e7fda-e8bf-4a96-9a85-a6e23a8c635c  
[Balanced]  
powercfg -duplicatescheme 381b4222-f694-41f0-9685-ff5bb260df2e  
[Power Saver]  
powercfg -duplicatescheme a1841308-3541-4fab-bc81-f71556f20b4a  
[Ultimate Performance]  
powercfg -duplicatescheme e9a42b02-d5df-448d-aa00-03f14749eb61`
4. If successfully executed, type**exit** and press**Enter** to close Command Prompt.

 Next, open**Control Panel** and go to**Power Options** to check if the missing power plans are restored on your Windows computer.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135406/19272" target="_top" id="2135406">
  <img src="//a.impactradius-go.com/display-ad/19272-2135406" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135406/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Enable the High Performance Power Plan Using Command Prompt

![enable high performance plan windows command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-high-performance-plan-windows-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118326/7443" target="_top" id="2118326">
  <img src="//a.impactradius-go.com/display-ad/7443-2118326" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118326/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You can use a different**powercfg** command to enable the High Performance power plan on Windows. This is useful if your system is missing only the High Performance power scheme. Here’s how to do it.

1. [Open Command Prompt with administrator rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
2. In the Command Prompt window, type the following command and press**Enter** :  
`powercfg /s SCHEME_MIN`
3. After the command is executed, close the Command Prompt window.
4. Next, go to **Control Panel > Hardware and Sound > Power Options** . Here, you can use the**High Performance** power plan.

 If the power plans are still missing, check if Modern Standby (S0) is enabled. If yes, you’ll need to disable Modern Standby to restore the missing power plans.

## 5\. Disable Modern Standby (S0) to Restore Default Power Plans

 If you have a Modern Standby (S0) compatible system, check if this sleep state is enabled. When enabled, the default power plans may be disabled to prevent any conflict when the system is in a low-power idle state.

 As you may have guessed already, in this situation, you’ll need to[disable Modern Standby (S0) on Windows](https://www.makeuseof.com/windows-disable-modern-standby/) to restore the default power plans on Windows. After you disable Modern Standby (S0), open Power Options to use the default power plans.

 Conversely, you may encounter BSOD and other critical errors after disabling Modern Standby (S0). If yes, enable Modern Standby again to fix the issues.

## 6\. Manually Create the Power Plans

 If you don’t want to use the preset power plans, you can create your own power plans on Windows. This should work irrespective of the Modern Standby state of your computer.

To create a custom Power Plan on Windows:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel.**
3. Go to**Hardware and Sound.**
4. Next, click on**Power Options** .  
![control panel create power plan windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/control-panel-create-power-plan-windows-11.jpg)
5. In the left pane, click on**Create a Power Plan.**  
![control panel create power plan power saver windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/control-panel-create-power-plan-power-saver-windows-11.jpg)
6. Next, select the power plan you want to restore and enter a name for the plan under the**Plan name field.**  
![control panel create power plan configure](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/control-panel-create-power-plan-configure.jpg)
7. Next, configure the settings for the new power plan.
<!-- affiliate ads begin -->
<span id="1983475">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983475.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983475">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983475.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983475%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983475/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Click**Create** .\`

 Your new custom power plan will appear in Power Options. To remove the power plan, unselect the plan and click on**Change plan** settings. Next, click on**Delete this plan** and click**OK** .

<!-- affiliate ads begin -->
<span id="1938136">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938136.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938136">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938136.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938136%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938136/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Restore the Missing Default Power Plans on Windows

 Power plans on your Windows laptops help you manage how your device uses power. If you don’t see the power schemes on Windows, try to reset the default power plans using PowerShell. Similarly, you can also use PowerShell to duplicate and restore the existing power plans.

 That said, not seeing the Ultimate Performance power plan in Power Options is not unusual. By default, it is only available on high-end Windows hardware and disabled to prevent battery draining. But you can still enable it using a PowerShell cmdlet. For most users, however, the balanced power plan offers a great balance between performance and battery life.


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
<li><a href="https://fox-access.techidaily.com/new-2024-approved-premium-5-display-picks-for-immersive-gameplay/"><u>[New] 2024 Approved Premium 5 Display Picks for Immersive Gameplay</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-a-comprehensive-look-at-djis-quadcopter-standard-flight/"><u>[New] A Comprehensive Look at DJI's Quadcopter Standard Flight</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-excellent-live-broadcast-achieving-ultra-hd-fb-video/"><u>[New] Excellent Live Broadcast Achieving Ultra-HD FB Video</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-2024-approved-securely-sharing-video-on-youtube-with-settings/"><u>[Updated] 2024 Approved Securely Sharing Video on YouTube with Settings</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-advanced-guide-to-excellence-full-screen-preview-in-premiere/"><u>2024 Approved Advanced Guide to Excellence Full Screen Preview in Premiere</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/cross-cultural-commencements-good-morning-variants-from-around-the-globe/"><u>Cross-Cultural Commencements: 'Good Morning' Variants From Around the Globe</u></a></li>
<li><a href="https://solve-marvelous.techidaily.com/empowering-user-confidentiality-through-pets-insights-from-the-abbyy-perspective/"><u>Empowering User Confidentiality Through PETs | Insights From the ABBYY Perspective</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-level-strategies-for-mastering-windows-voice-access/"><u>Expert-Level Strategies for Mastering Windows Voice Access</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-offline-issues-a-solution-for-steam-and-windows/"><u>Fixing Offline Issues: A Solution for Steam and Windows</u></a></li>
<li><a href="https://some-techniques.techidaily.com/harness-the-power-of-post-production-top-11-techniques-for-vibrant-colors-for-2024/"><u>Harness the Power of Post-Production Top 11 Techniques for Vibrant Colors for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-locate-missing-gateway-ubisofts-launcher/"><u>How To Locate Missing Gateway: Ubisoft's Launcher</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-recover-from-network-not-found-error-windows/"><u>How to Recover From 'Network Not Found' Error Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-tackle-high-cpu-usage-by-the-system-idle-process-effective-solutions/"><u>How to Tackle High CPU Usage by the 'System Idle Process': Effective Solutions</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-explore-popular-youtube-comment-sections/"><u>In 2024, Explore Popular YouTube Comment Sections</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-a-lost-motorola-moto-g13-for-free-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track a Lost Motorola Moto G13 for Free? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-passfab-apple-iphone-14-pro-max-backup-unlocker-top-4-alternatives-drfone-by-drfone-ios/"><u>In 2024, PassFab Apple iPhone 14 Pro Max Backup Unlocker Top 4 Alternatives | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-preparation-to-beat-giovani-in-pokemon-go-for-itel-s23-drfone-by-drfone-virtual-android/"><u>In 2024, Preparation to Beat Giovani in Pokemon Go For Itel S23 | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-ways-to-stop-parent-tracking-your-oppo-a56s-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to stop parent tracking your Oppo A56s 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/inside-look-windows-executable-and-linker-format-pe/"><u>Inside Look: Windows' Executable & Linker Format (PE)</u></a></li>
<li><a href="https://windows11.techidaily.com/leap-from-voice-to-phrase-transcribing-with-whisper-for-windows/"><u>Leap From Voice to Phrase: Transcribing with Whisper for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/minimizing-windows-extender-lowering-cpu-demand/"><u>Minimizing Windows Extender: Lowering CPU Demand</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-art-of-ping-utilization-windows-style/"><u>Navigating the Art of Ping Utilization Windows-Style</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-common-connectivity-hurdles-with-7-obs-fixes/"><u>Overcoming Common Connectivity Hurdles with 7 OBS Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/perfectly-setup-your-external-drives-in-newest-os-win11/"><u>Perfectly Setup Your External Drives in Newest OS, Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/rapid-rendezvous-initiating-startup-unlocking-notepad/"><u>Rapid Rendezvous: Initiating Startup, Unlocking Notepad</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstating-lost-gesture-control-on-pcs-running-windows/"><u>Reinstating Lost Gesture Control on PCs Running Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-dns-cache-a-quick-tutorial-for-windows-users/"><u>Resetting DNS Cache: A Quick Tutorial for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-dormant-wsreset-utility-on-computers/"><u>Restoring Dormant WSReset Utility on Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-disabled-pin-removal-tool-on-windows-11-pc/"><u>Reviving Disabled PIN Removal Tool on Windows 11 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-way-to-refresh-your-windows-update-system/"><u>Seamless Way to Refresh Your Windows Update System</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-microsoft-error-code-x00000000/"><u>Solutions to Microsoft Error Code X00000000</u></a></li>
<li><a href="https://windows11.techidaily.com/speeding-up-windows-printers-instantly/"><u>Speeding Up Windows Printers Instantly</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-monitorscape-crafting-individual-themes-for-each-window-of-win-1011/"><u>Tailored Monitorscape: Crafting Individual Themes for Each Window of Win 10/11</u></a></li>
<li><a href="https://fox-direct.techidaily.com/the-art-of-weaving-b-roll-into-main-footage-seamlessly-for-2024/"><u>The Art of Weaving B Roll Into Main Footage Seamlessly for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-how-to-for-creating-a-mobile-hotspot-with-win-11/"><u>The Ultimate How-To for Creating a Mobile Hotspot with Win 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/tips-and-tricks-for-setting-up-your-samsung-galaxy-a15-5g-phone-pattern-lock-by-drfone-android/"><u>Tips and Tricks for Setting Up your Samsung Galaxy A15 5G Phone Pattern Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-discrepancies-in-discords-windows-game-detection/"><u>Troubleshooting Discrepancies in Discord's Windows Game Detection</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-rejuvenating-a-dormant-windows-scan-tool/"><u>Troubleshooting: Rejuvenating a Dormant Windows Scan Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/unblock-file-uploads-mastering-chromes-sync-on-a-win-os/"><u>Unblock File Uploads: Mastering Chrome's Sync on a Win OS</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-messages-from-itel-by-fonelab-android-recover-messages/"><u>Undelete lost messages from Itel</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-efficiency-the-guide-to-windows-print-tools/"><u>Unlocking Efficiency: The Guide to Windows Print Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/updating-old-pcs-think-beyond-windows/"><u>Updating Old PCs? Think Beyond Windows</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/vrchat-not-working-discover-8-effective-strategies-for-a-smooth-experience/"><u>VRChat Not Working? Discover 8 Effective Strategies for a Smooth Experience</u></a></li>
</ul></div>
