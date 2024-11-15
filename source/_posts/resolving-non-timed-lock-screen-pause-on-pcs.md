---
title: Resolving Non-Timed Lock Screen Pause on PCs
date: 2024-11-11T17:04:06.426Z
updated: 2024-11-15T16:56:08.727Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Non-Timed Lock Screen Pause on PCs
excerpt: This Article Describes Resolving Non-Timed Lock Screen Pause on PCs
keywords: Timed Lock Fix PC,Unfreeze Lock Screen,Lock Issue Resolution,End PC Screen Delay,Screen Pause Stop PC,Resume Lock Screen,Fix Non-Timed Lock
thumbnail: https://thmb.techidaily.com/0dca80060c58b2b6bbf1021b5cfac76e3fa6cc6f30bafd7ebd2e3f93bc51e809.jpg
---

## Resolving Non-Timed Lock Screen Pause on PCs

 Have you ever left your computer unattended for a while, only to return and find that it was still unlocked? Several users have reported problems getting their Windows computers to lock automatically after a certain period of inactivity.

 To help out, we have listed some useful tips that should get the lock screen timeout to work on your Windows 10 or 11 PC.

## 1\. Check Screen Timeout Settings

 Before we get to any advanced troubleshooting tips, it’s a good idea to double-check the screen timeout settings on Windows. Here are the steps for the same.

1. Press **Win + I** to open the Settings app.
2. Navigate to **System > Power & battery**.
3. Click on **Screen and sleep** to expand it.
4. Click the drop-down menus next to **On battery power, turn off my screen after** and **When plugged in, turn off my screen after** to select your preferred timeout.  
![Screen and Sleep Settings in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/screen-and-sleep-settings-in-windows.jpg)

 After setting your preferred timeout, observe if Windows locks your PC after the specified period.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135400/19272" target="_top" id="2135400">
  <img src="//a.impactradius-go.com/display-ad/19272-2135400" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135400/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Configure Screen Saver Settings

 Incorrectly configured screen saver settings on Windows can also be the cause of this issue. Here's how you can configure Windows to display the lock screen after you resume from a screensaver.

1. Press **Win + S** to open the search menu.
2. Type **change screen saver** in the box and select the first result that appears.
3. In the Screen Saver Settings window, set the preferred wait time.
4. Tick the **On resume, display logon screen** checkbox.
5. Hit **Apply** followed by **OK**.  
![Screen Saver Settings on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/screen-saver-settings-on-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1884002/19272" target="_top" id="1884002">
  <img src="//a.impactradius-go.com/display-ad/19272-1884002" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1884002/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you complete the above steps, Windows should lock your system once the screen saver activates.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012434/19272" target="_top" id="2012434">
  <img src="//a.impactradius-go.com/display-ad/19272-2012434" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012434/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Check Screen Saver Settings in the Local Group Policy

 If the issue remains even after you configure the screen saver settings, you will need to check the policies related to the screen saver and make sure they are configured correctly.

 As you may be aware, the Local Group Policy Editor is only available on Windows Pro, Enterprise, and Education editions. However, if you are using the Home edition, you can use a workaround to [access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To modify group policies related to screen saver, use these steps:

1. Press **Win + R** to open the Run dialog box.
2. Type **gpedit.msc** in the box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **User Configuration > Administrative Templates > Control Panel > Personalization**.
5. Double-click the **Enable Screen Saver** policy on your right.
6. Select the **Enabled** option.
7. Hit **Apply** and then click **OK**.
8. Similarly, enable the **Password protect the screen saver** policy as well.  
![Password Protect Screen Saver Policy in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/password-protect-screen-saver-policy-in-group-policy-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1006793/11832" target="_top" id="1006793">
  <img src="//a.impactradius-go.com/display-ad/11832-1006793" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1006793/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Restart your PC after applying the above changes and check if the issue is still there.

## 4\. Other Generic Fixes to Try

 If the above solutions do not work, you can try some generic Windows fixes to get the lock screen timeout working on Windows.

* **Disconnect External Devices:** It is possible that an external device connected to your system is keeping Windows awake. To test this, disconnect all external devices and see if the problem persists.
* **Reset Your Power Plan:** Issues with the power plan settings could also cause such problems. To fix this, you can try [resetting the power plan to default on Windows](https://www.makeuseof.com/reset-power-plans-to-default-in-windows/).
* **Install Windows Updates:** It's possible that the lock screen timeout problem is occurring due to a bug within the Windows build your PC is running. If that's the case, [installing Windows updates](https://www.makeuseof.com/update-windows-manually/) should help.
* **Try a Clean Boot:**[Performing a clean boot on Windows](https://www.makeuseof.com/how-perform-clean-boot-windows-10/) can help you determine whether a third-party program or service is causing issues with the lock screen timeout. Once you find the problematic program, consider removing it from your system to avoid such issues in the future.
* **Perform a System Restore:** If the issue has only started occurring recently, you can [perform a system restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) to undo recent changes and fix the problem.

## Get the Lock Screen Timeout Working Again on Windows

 When the lock screen timeout fails to work as expected, it can potentially put your Windows computer at risk. Hopefully, one or more of the above tips have helped you solve the problem and you are at peace.

 To help out, we have listed some useful tips that should get the lock screen timeout to work on your Windows 10 or 11 PC.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/efficient-energy-use-with-windows-pcs/"><u>Efficient Energy Use with Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-drag-fixes-for-your-win11-desktop/"><u>Effortless Drag Fixes for Your Win11 Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-development-workflow-navigating-windows-11s-dev-drive/"><u>Elevate Development Workflow: Navigating Windows 11'S Dev Drive</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-driver-enforcement-loading-unsigned-on-windows-108/"><u>Eliminating Driver Enforcement: Loading Unsigned On Windows 10/8</u></a></li>
<li><a href="https://windows11.techidaily.com/embrace-world-typography-on-windows-font-guide/"><u>Embrace World Typography on Windows - Font Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/erase-system-misses-message-on-windows-os/"><u>Erase System Misses Message on Windows OS</u></a></li>
<li><a href="https://howto.techidaily.com/gmail-not-working-on-samsung-galaxy-z-flip-5-7-common-problems-and-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Gmail Not Working on Samsung Galaxy Z Flip 5 7 Common Problems & Fixes | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-which-is-the-best-fake-gps-joystick-app-on-honor-x8b-drfone-by-drfone-virtual-android/"><u>In 2024, Which is the Best Fake GPS Joystick App On Honor X8b? | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/install-the-most-recent-hp-deskjet-3755-all-in-one-printer-driver-compatible-with-windows-11108and-7-systems/"><u>Install the Most Recent HP DeskJet 3755 All-In-One Printer Driver Compatible with Windows 11/10/8/^and 7 Systems</u></a></li>
<li><a href="https://extra-resources.techidaily.com/swirl-device-set/"><u>Swirl Device Set</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/top-rated-wireless-routers-in-2/"><u>Top Rated Wireless Routers in 2</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/top-strategies-for-utilizing-auto-gtp/"><u>Top Strategies for Utilizing Auto-GTP</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/what-pokemon-evolve-with-a-dawn-stone-for-realme-12-pro-5g-drfone-by-drfone-virtual-android/"><u>What Pokémon Evolve with A Dawn Stone For Realme 12 Pro 5G? | Dr.fone</u></a></li>
</ul></div>

