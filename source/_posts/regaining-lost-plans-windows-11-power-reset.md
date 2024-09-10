---
title: "Regaining Lost Plans: Windows 11 Power Reset"
date: 2024-09-09T12:13:41.793Z
updated: 2024-09-10T12:13:41.793Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Regaining Lost Plans: Windows 11 Power Reset"
excerpt: "This Article Describes Regaining Lost Plans: Windows 11 Power Reset"
keywords: Win11 Power Save,Plan Recovery Pro,Reset Windows Fix,11 Restart Help,Loss Plans Reinstate,OS Power Refresh,Resetting Windows 11
thumbnail: https://thmb.techidaily.com/f1a796c007bdb54a5d32d237286b0c583ae30258c2ed2bd3a37271e2bf51c230.jpg
---

## Regaining Lost Plans: Windows 11 Power Reset

 Windows 11 and 10 come with preset power plans: High Performance, Power Saver, Balanced, and sometimes Ultimate Performance. You can switch between these plans to get the best performance, more battery life or a bit of both worlds. Some laptop manufacturers, like HP, have their own power plan, like HP Recommended.

 However, often after installing a Windows update, default power plans can go missing, or you may see only one power plan. This can also happen if you have made changes to your power plans recently. In any case, here are a few troubleshooting steps to help restore the missing default power plans on Windows 11 and 10 running systems.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135416/19272" target="_top" id="2135416">
  <img src="//a.impactradius-go.com/display-ad/19272-2135416" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135416/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Check Which Power Plan Is Missing

![check missing power plans control panel windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-missing-power-plans-control-panel-windows-11.jpg)

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
<a href="https://aidotcom.pxf.io/c/5597632/2129043/19576" target="_top" id="2129043">
  <img src="//a.impactradius-go.com/display-ad/19576-2129043" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2129043/19576" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130528/26400" target="_top" id="2130528">
  <img src="//a.impactradius-go.com/display-ad/26400-2130528" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130528/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Restore the Missing Power Plan Using the Command Prompt

![restore default power plan windows 11 command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/restore-default-power-plan-windows-1-command-prompt.jpg)

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

## 4\. Enable the High Performance Power Plan Using Command Prompt

![enable high performance plan windows command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-high-performance-plan-windows-command-prompt.jpg)

<!-- affiliate ads begin -->
<span id="1983584">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983584.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983584">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983584.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983584%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983584/22993" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014849/22899" target="_top" id="2014849">
  <img src="//a.impactradius-go.com/display-ad/22899-2014849" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014849/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115942/19272" target="_top" id="2115942">
  <img src="//a.impactradius-go.com/display-ad/19272-2115942" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115942/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![control panel create power plan configure](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/control-panel-create-power-plan-configure.jpg)
7. Next, configure the settings for the new power plan.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135363/19272" target="_top" id="2135363">
  <img src="//a.impactradius-go.com/display-ad/19272-2135363" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135363/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Click**Create** .\`

 Your new custom power plan will appear in Power Options. To remove the power plan, unselect the plan and click on**Change plan** settings. Next, click on**Delete this plan** and click**OK** .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135398/19272" target="_top" id="2135398">
  <img src="//a.impactradius-go.com/display-ad/19272-2135398" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135398/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-zero.techidaily.com/0-common-vlogging-fears-and-how-to-beat-them/"><u>[New] 10 Common Vlogging Fears and How To Beat Them</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-how-to-delete-youtube-comments-effortlessly/"><u>[Updated] 2024 Approved How to Delete YouTube Comments Effortlessly?</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-boosting-zoom-image-quality-professional-insights/"><u>[Updated] Boosting Zoom Image Quality Professional Insights</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-phantom-gag-craftsman/"><u>2024 Approved Phantom Gag Craftsman</u></a></li>
<li><a href="https://extra-information.techidaily.com/discovering-the-tech-marvel-in-apples-m1-max-clip/"><u>Discovering the Tech Marvel in Apple's M1 Max Clip</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-fixes-for-windows-remote-desktop-problems/"><u>Essential Fixes for Windows Remote Desktop Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-pathways-for-opening-hardware-spaces-on-w10w11/"><u>Essential Pathways for Opening Hardware Spaces on W10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/examining-windows-memory-management-insights-into-pagefilesys/"><u>Examining Windows' Memory Management: Insights Into Pagefile.sys</u></a></li>
<li><a href="https://windows11.techidaily.com/exposing-limits-the-cpu-performance-spectrum/"><u>Exposing Limits: The CPU Performance Spectrum</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-d3dx939-error-steps-to-recover-dll/"><u>Fixing D3DX9_39 Error: Steps to Recover DLL</u></a></li>
<li><a href="https://fox-access.techidaily.com/game-on-in-reality-discover-the-top-5-samsung-vr-titles-for-2024/"><u>Game On in Reality! Discover the Top 5 Samsung VR Titles for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-to-selectively-turn-off-windows-11-services/"><u>Guidelines to Selectively Turn Off Windows 11 Services</u></a></li>
<li><a href="https://change-location.techidaily.com/how-can-i-get-more-stardust-in-pokemon-go-on-vivo-y100a-drfone-by-drfone-virtual-android/"><u>How can I get more stardust in pokemon go On Vivo Y100A? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-alt-codes-not-working-on-windows/"><u>How to Fix ALT Codes Not Working on Windows</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-fix-locked-apple-id-from-iphone-15-by-drfone-ios/"><u>How to Fix Locked Apple ID from iPhone 15</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-internal-error-has-occurred-remote-desktop-connection-error-in-windows-11-and-11/"><u>How to Fix the “Internal Error Has Occurred” Remote Desktop Connection Error in Windows 11 & 11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-bandicam-screen-recorder-review/"><u>In 2024, Bandicam Screen Recorder Review</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-the-best-ispoofer-alternative-to-try-on-honor-x8b-drfone-by-drfone-virtual-android/"><u>In 2024, The Best iSpoofer Alternative to Try On Honor X8b | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/is-error-code-2e-blocking-windows-updates/"><u>Is Error Code 2E Blocking Windows Updates?</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-code-with-microsoft-copilot-on-windows/"><u>Mastering Code with Microsoft Copilot on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-microsoft-store-crash-fixes-for-error-0x0-on-pcs/"><u>Mastering Microsoft Store Crash Fixes for Error 0X0 on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-prevent-data-loss-in-unresponsive-usb-cases-windows/"><u>Methods to Prevent Data Loss in Unresponsive USB Cases (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-rectify-frozen-and-unresponsive-windows-discord-elements/"><u>Methods to Rectify Frozen and Unresponsive Windows Discord Elements</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-to-win-11s-insider-program-enrollment/"><u>Navigating to Win 11'S Insider Program Enrollment</u></a></li>
<li><a href="https://win-solutions.techidaily.com/oculus-graphics-troubles-identifying-and-resolving-driver-related-errors/"><u>Oculus Graphics Troubles: Identifying and Resolving Driver-Related Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-mcuicntexe-missing-problems-on-pcs/"><u>Overcoming McUICnt.exe Missing Problems on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/perfecting-image-clarity-windows-11s-background-blur-tricks/"><u>Perfecting Image Clarity: Windows 11'S Background Blur Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-your-pcs-clock-view-ideal-screensaver-creation-apps-in-windows-platform/"><u>Personalize Your PC's Clock View: Ideal Screensaver Creation Apps in Windows Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-systemsettings-errors-in-windows-11/"><u>Preventing SystemSettings Errors in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/quicken-pace-elevating-gameplay-with-better-frames/"><u>Quicken Pace: Elevating Gameplay with Better Frames</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-fingerprint-scanning-not-found-in-windows/"><u>Remedying Fingerprint Scanning Not Found in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-phantom-device-error-in-windows-11/"><u>Remedying Phantom Device Error in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-error-with-windows-shadow-copy-service/"><u>Resetting Error with Windows' Shadow Copy Service</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-windows-services-command-prompt-tool-a-list-of-7-remedies/"><u>Reviving Windows Services Command Prompt Tool: A List of 7 Remedies</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-up-a-safe-workspace-windows-sandbox-11/"><u>Setting Up a Safe Workspace: Windows Sandbox 11</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/sonic-boom-new-technology-reviewed-for-2024/"><u>Sonic Boom New Technology Reviewed for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-resolving-non-functional-windows-alt-keys/"><u>Steps for Resolving Non-Functional Windows Alt Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-mouse-accel-tips-for-win-11-users/"><u>Stop Mouse Accel: Tips for Win 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-excessive-gpu-load-in-games-on-pc/"><u>Tackling Excessive GPU Load in Games on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/the-network-navigator-guiding-you-through-obs-connectivity-troubles-7-ways/"><u>The Network Navigator: Guiding You Through OBS Connectivity Troubles (7 Ways)</u></a></li>
<li><a href="https://windows11.techidaily.com/touching-your-world-better-the-ultimate-guide-to-pc-touch-adjustment/"><u>Touching Your World Better: The Ultimate Guide to PC Touch Adjustment</u></a></li>
<li><a href="https://windows11.techidaily.com/turbo-valorant-setup-escape-the-01kbs-download-drought/"><u>Turbo Valorant Setup: Escape the 0.1KB/S Download Drought</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-your-windows-start-windows-media-player-now/"><u>Unleash Your Windows: Start Windows Media Player Now</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-torrent-speed-resetting-stalled-status-on-windows/"><u>Unlocking Torrent Speed: Resetting Stalled Status on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-error-code-80080300-with-microsoft-teams/"><u>Unraveling the Mystery of Error Code 80080300 with Microsoft Teams</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-non-essential-windows-applications-for-elimination/"><u>Unveiling Non-Essential Windows Applications for Elimination</u></a></li>
<li><a href="https://windows11.techidaily.com/upgrade-pcs-for-efficient-scalable-transcoding-using-tdarr/"><u>Upgrade PCs for Efficient, Scalable Transcoding Using Tdarr</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-woes-alternatives-without-upgrading/"><u>Windows 11 Woes: Alternatives Without Upgrading</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-family-safety-rescue-quick-corrections-listed-here/"><u>Windows Family Safety Rescue: Quick Corrections Listed Here</u></a></li>
</ul></div>
