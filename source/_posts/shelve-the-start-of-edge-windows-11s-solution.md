---
title: "Shelve the Start of Edge: Windows 11'S Solution"
date: 2024-09-05T02:08:06.432Z
updated: 2024-09-06T02:08:06.432Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Shelve the Start of Edge: Windows 11'S Solution"
excerpt: "This Article Describes Shelve the Start of Edge: Windows 11'S Solution"
keywords: Win11EdgeUpdate,ShelveStartEdge,NewOSSolution,EdgeToWin11,Win11PerformanceBoost,WindowsLatestTech,EdgeRemovalStrategy
thumbnail: https://thmb.techidaily.com/a0ea0929e49147a7aa2982696f1085c4ea3dc3044596db757054a8f03e6ab91e.jpg
---

## Shelve the Start of Edge: Windows 11'S Solution

 Microsoft Edge is the default browser in Windows and comes pre-installed on the operating system without any easy way of getting rid of it. The browser uses "tab preloading," which preloads the Start and New Tab page while you sign in to your PC.

 For Edge lovers, it is a boon, but if you don’t use the default browser and prefer something else, it is a waste of resources. Fortunately, you can easily disable Edge's tab preloading in Windows 11\.

## 1\. How to Disable Edge Tab Preloading Using the Group Policy Editor

 Windows Pro, Education, and Enterprise users get the perks of the Group Policy Editor by default. You can use it to configure system policies on your PC and personalize it. If you're on Windows Home, check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

 Repeat the following steps to disable Edge tab preloading using the Group Policy Editor:

1. Press **Win + S** to open Windows Search. Type **gpedit.msc** in the text box and press the **Enter** key to open the Group Policy Editor.
2. Click on the **User Configuration** option in the left-hand side pane.
3. Navigate to **Administrative Templates > Windows Components > Microsoft Edge**.
4. Find the “**Allow Microsoft Edge to start and load the Start and New Tab page at Windows startup and each time Microsoft Edge is closed**” policy. Right-click on it and select the **Edit** option from the context menu.  
![Disable Microsoft Edge Tab Preloading Using GPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-gpe.jpg)
5. Click on the **Enabled** radio button.
6. Scroll down and click on the drop-down list next to the **Configure tab preloading** option. Select the **Prevent tab preloading** option.
7. Click on the **Apply** button. Then click on the **OK** button to save the changes.  
![Disable Microsoft Edge Tab Preloading Using GPE 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-gpe-2.jpg)
8. **Exit** the Group Policy Editor window.
9. **Restart** your PC for the policy changes to take effect and disable the tab preloading feature.

## 2\. How to Disable Edge Tab Preloading Using the Registry Editor

 If you use the Home version of Windows 11, it may be easier to take a different approach instead of going through the Group Policy Editor method. If you want, you can tweak the registry manually to disable the Edge tab preloading feature in Windows 11\. Repeat the following steps to do so:

 Before making changes to the Windows Registry, [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) for safety purposes.

1. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **regedit** in the text box and press the **Enter** key.
2. Go to the address bar at the top and click on it. Paste the following path in the text box and press the **Enter** key:  
HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\MicrosoftEdge\Main
3. Go to the right-hand side section and right-click on the empty area. Select **New > DWORD (32-bit) Value**.
4. Click on the newly created DWORD value and name it “**AllowPrelaunch**”.
5. Right-click on the **AllowPrelaunch** value and select the **Modify** option from the context menu.
6. Go to the **Value Data** field and type **0** in it. Set the **Base** to **Hexadecimal** and click on the **OK** button.  
![Disable Microsoft Edge Tab Preloading Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-registry-editor.jpg)

 Now, you need to create a new subkey and add a new DWORD value:

1. Right-click on the Microsoft Edge key and select the **New > Key** option.
2. Name the key “**TabPreloader**” and click on it to select it.
3. Go to the right-hand side section and right-click on it. Select **New > DWORD (32-bit) Value**.
4. Click on the DWORD value and name it “**AllowTabPreloading**”.
5. Right-click on the **AllowTabPreloading** value and select the **Modify** option.
6. Go to the **Value Data** field and type **0** in it. Set the **Base** to **Hexadecimal** and click on the **OK** button.  
![Disable Microsoft Edge Tab Preloading Using Registry Editor 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-registry-editor-2.jpg)
7. **Close** the Registry Editor window.
8. **Restart** your PC to apply the changes made to the registry.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118323/7443" target="_top" id="2118323">
  <img src="//a.impactradius-go.com/display-ad/7443-2118323" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118323/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. How to Disable Edge Tab Preloading Using CMD or PowerShell

 If you find the Registry Editor method too cumbersome, you can use the Command Prompt or PowerShell to modify the Registry and disable Edge tab preloading. Here’s how to do it:

1. [Open the Command Prompt with administrator privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/) on your PC.
2. Execute the following commands to add two new registry entries:  
`reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\MicrosoftEdge\Main" /v AllowPrelaunch /t REG_DWORD /d 00000000 /f  
 reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\MicrosoftEdge\TabPreloader" /v AllowTabPreloading /t REG_DWORD /d 00000000 /f`
3. **Close** the Command Prompt window and **restart** your PC.  
![Disable Microsoft Edge Tab Preloading Using CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-cmd.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484909/16446" target="_top" id="1484909">
  <img src="//a.impactradius-go.com/display-ad/16446-1484909" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484909/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2002019/7443" target="_top" id="2002019">
  <img src="//a.impactradius-go.com/display-ad/7443-2002019" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2002019/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. How to Disable Edge Tab Preloading Using the Ultimate Windows Tweaker App

 You can also use a third-party app like the Ultimate Windows Tweaker to disable Edge tab preloading in Windows 11\. Download the [Ultimate Windows Tweaker](https://www.thewindowsclub.com/ultimate-windows-tweaker-4-windows-10) app and install it on your PC. After that, repeat the following steps:

1. Press **Win + S** to open the Windows Search app. Type **Ultimate Windows Tweaker** and then click on the **Run as administrator** option.
2. Click on the **Search For Tweaks** option. Type “**edge tab**” in the search box and click on the **Go** button.  
![Disable Microsoft Edge Tab Preloading Using Ultimate Windows Tweaker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-ultimate-windows-tweaker.jpg)
3. Click on the **Disable Edge Tab Preloading** checkbox to enable it. Then, click on the **Apply Tweaks** button.  
<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863035/11832" target="_top" id="863035">
  <img src="//a.impactradius-go.com/display-ad/11832-863035" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/863035/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Disable Microsoft Edge Tab Preloading Using Ultimate Windows Tweaker 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-ultimate-windows-tweaker-2.jpg)
4. **Close** the Ultimate Windows Tweaker app and **restart** your PC to apply the changes.
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826">
  <img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027195/19272" target="_top" id="2027195">
  <img src="//a.impactradius-go.com/display-ad/19272-2027195" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027195/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Disable Edge Tab Preloading for Good on Windows 11

 Edge tab preloading serves no useful purpose if you use other browsers. You can disable it using the Group Policy Editor or the Registry Editor. Lastly, if you want a GUI app to disable the feature, you can use the Ultimate Windows Tweaker app.

 For Edge lovers, it is a boon, but if you don’t use the default browser and prefer something else, it is a waste of resources. Fortunately, you can easily disable Edge's tab preloading in Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-activity-recording.techidaily.com/new-quicksnap-studio-pro-for-2024/"><u>[New] QuickSnap Studio Pro for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/11-proven-solutions-to-fix-google-play-store-not-working-issue-on-samsung-galaxy-s23plus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Proven Solutions to Fix Google Play Store Not Working Issue on Samsung Galaxy S23+ | Dr.fone</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-unlock-iphones-full-potential-4-pro-tips-for-brightening-hdr-in-premiere/"><u>2024 Approved  Unlock iPhone's Full Potential  4 Pro Tips for Brightening HDR in Premiere</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-unveiling-the-practicality-of-smoothing-in-camera-jitters/"><u>2024 Approved  Unveiling the Practicality of Smoothing In-Camera Jitters</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-insights-into-utilizing-microsofts-system-restore-feature/"><u>Essential Insights Into Utilizing Microsoft's System Restore Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-incompatible-fingerprint-error-on-windows-os/"><u>Fixing Incompatible Fingerprint Error on Windows OS</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/gratis-android-capture-free-your-devices-potential/"><u>Gratis Android Capture  Free Your Device's Potential</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/how-to-change-powerpoint-video-speed-for-2024/"><u>How to Change PowerPoint Video Speed for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-your-windows-license-will-expire-soon-error-on-windows-10-and-11/"><u>How to Fix the “Your Windows License Will Expire Soon” Error on Windows 10 and 11</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-locate-and-replace-missing-d3dx9nineteenth-error-files/"><u>How to Locate and Replace Missing D3dx9_nineteenth Error Files</u></a></li>
<li><a href="https://win-able.techidaily.com/how-to-resolve-playstation-4-modern-warfare-3-mw3-not-working-problems/"><u>How to Resolve PlayStation 4 Modern Warfare 3 MW3 Not Working Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-solve-microsoft-office-365-glitches-error-30015-26/"><u>How to Solve Microsoft Office 365 Glitches: Error 30015-26</u></a></li>
<li><a href="https://windows11.techidaily.com/ifas-best-laptops-of-2023-now/"><u>IFA's Best Laptops of 2023, Now!</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-can-i-catch-the-regional-pokemon-without-traveling-on-samsung-galaxy-s24-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Catch the Regional Pokémon without Traveling On Samsung Galaxy S24 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/keyboard-shortcut-wisdom-shrinking-down-software-in-win11/"><u>Keyboard Shortcut Wisdom: Shrinking Down Software in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-resolve-non-installed-windows-store-apps/"><u>Methods to Resolve Non-Installed Windows Store Apps</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-expert-techniques-for-crafting-complex-audio-edits-with-keyframes-in-premiere-pro-mac-edition/"><u>New Expert Techniques for Crafting Complex Audio Edits with Keyframes in Premiere Pro, Mac Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-lossed-renderer-failures-in-overwatch-2-gameplay/"><u>Overcoming Lossed Renderer Failures in Overwatch 2 Gameplay</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-playback-problem-in-wmp/"><u>Overcoming Playback Problem in WMP</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-resource-drain-tackling-edges-view2-process/"><u>Overcoming Resource Drain: Tackling Edge's View2 Process</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-zero-error-in-windows-11-with-procedures/"><u>Overcoming Zero-Error in Windows 11 with Procedures</u></a></li>
<li><a href="https://windows11.techidaily.com/revamping-robustness-of-win11s-cleanup-companion-ccleaner/"><u>Revamping Robustness of Win11's Cleanup Companion, CCleaner</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-camera-apps-error-0xa00f425d-on-windows-devices/"><u>Solving Camera App's Error 0xA00F425D on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/speed-ahead-overcoming-low-valorant-download-speeds-in-windows/"><u>Speed Ahead: Overcoming Low Valorant Download Speeds in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-hypervisorbsod-in-windows-a-top-ten-approach/"><u>Stop HYPERVISOR_BSOD in Windows: A Top-Ten Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-translations-hotkey-tips-for-windows-11-language-switching/"><u>Streamline Translations: Hotkey Tips for Windows 11 Language Switching</u></a></li>
<li><a href="https://windows11.techidaily.com/tidy-up-win11-desktop-by-removing-highlighted-icon/"><u>Tidy up Win11 Desktop by Removing Highlighted Icon</u></a></li>
<li><a href="https://windows11.techidaily.com/tidying-up-your-pc-a-compact-guide-to-uninstallation-in-windows-11-108-chars/"><u>Tidying Up Your PC: A Compact Guide to Uninstallation in Windows 11 (108 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/top-7-sketch-tools-on-windows-11/"><u>Top 7 Sketch Tools on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-steps-for-reclaiming-lost-vpn-links-in-winpc/"><u>Unveiling Steps for Reclaiming Lost VPN Links in WinPC</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/verizons-premier-upgrade-bargains-hot-monthly-discounts-unveiled/"><u>Verizon’s Premier Upgrade Bargains: Hot Monthly Discounts Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-cs-go-launch-guide/"><u>Windows 11 CS GO Launch Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-woes-get-your-arrows-back-to-normal/"><u>Windows Woes? Get Your Arrows Back to Normal</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>