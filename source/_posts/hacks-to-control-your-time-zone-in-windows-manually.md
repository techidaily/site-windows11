---
title: Hacks to Control Your Time Zone in Windows Manually
date: 2024-08-31T22:11:05.429Z
updated: 2024-09-01T22:11:05.429Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Hacks to Control Your Time Zone in Windows Manually
excerpt: This Article Describes Hacks to Control Your Time Zone in Windows Manually
keywords: TimeZone Hacking Tips,Windows Time Adjustment Guide,Manual Zone Shifting Windows,Automate Time Zones (Manual),Control Windows Clock Region,Direct Time Zone Modification,Change OS Timezone Settings
thumbnail: https://thmb.techidaily.com/190bc8b4a2b2c75fb28f94e31b443bd5a1a2add3f40bf2451de84693ef89aead.jpeg
---

## Hacks to Control Your Time Zone in Windows Manually

 Did you ever experience being in a different time zone while working on your Windows computer? You've checked Windows time settings and noticed that it's not set to your current location. Suddenly, you realize that the time zone is greyed out, and you can’t configure it automatically. What do you do next? There are several scenarios where Windows cannot automatically set the time zone, and here's how to fix them.

## 1\. Restart Your PC

 The first step when troubleshooting any Windows-related issue is to restart the computer. It seems obvious, but it often solves the problem. Rebooting flushes out cached data that could cause time zone problems. It also resets various temporary services that may prevent Windows from automatically setting the time zone.

 To restart your computer, save all your work and close any running applications. After that, open the Start menu and click **Restart**. Once your computer restarts, check if that fixes the issue.

## 2\. Turn on Location Services in the Settings

 If restarting your computer didn't fix the issue, check if location services are enabled. Location services allow Windows to automatically detect the time zone and set it accordingly.

 To verify location services, follow these steps:

1. Press **Win + I** to open the Settings window.
2. From the left navigation panel, click **Privacy & security**.
3. Under the **App permissions** section, select **Location**.
4. Make sure the **Location services** option is enabled. If it's not, switch the toggle to turn it on.  
![Enable Location Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-location-services.jpg)

 Now restart your computer and check if Windows can set the time zone automatically.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Set the Windows Time Service to Automatic

 If the location services are already enabled, but Windows still can't detect the time zone, the problem may be related to the Windows Time Service. This background service keeps your system clock synchronized with time servers.

 Windows won't detect the time zone if the service is not running. To fix this issue, set Windows Time Service to Automatic.

 Here's how to do that:

1. Press **Win + R** on your keyboard to open the Run window.
2. Type **services.msc** in the text box and press **Enter**.
3. Scroll down in the Services window and locate the **Windows Time** service.
4. Right-click the service and select **Properties**.
5. In the Properties window, set the **Startup type** to **Automatic**.  
![Windows Time Service Status](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-time-service-status.jpg)
6. Now check the **Service status**. If it reads **Stopped**, click the **Start** button to start the service.
7. Click **Apply** and **OK** to save the changes.

 Once you've done this, restart your PC and check the time zone settings.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Tweak the Registry Editor

 If Windows still fails to detect the time zone or the "Set time zone automatically" option is still grayed out, you may need to tweak your registry. This is a more technical solution and requires registry knowledge. If you're not good at registry editing, skip this step or ask a professional for help.

 Follow these steps to make the changes:

 Modifying the registry incorrectly may cause serious problems. Before making any changes, [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/).

1. Press **Win + S** on your keyboard to open the Windows Search.
2. Type **regedit** in the search bar and press **Enter**.
3. If the UAC window pops up, click **Yes** to grant administrative privileges.
4. In the Registry Editor window, navigate to the following directory.  
`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\tzautoupdate`
5. In the right pane, double-click the **Start** (DWORD) value.  
![Modify Registry to change the Set time zone automatically setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modify-registry-to-change-the-set-time-zone-automatically-setting.jpg)
6. When the Edit DWORD Value window pops up, set the Value data to **3** and click **OK**.
7. After doing this, you must change the location setting. To do this, navigate to the following key:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\location`  
 You can also copy and paste the path into the Registry Editor address bar. Now press Enter and this directs you to the Location key.
8. Move to the right pane and double-click the **Value** (REG\_SZ) value.  
![Edit Registry to change the location setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/edit-registry-to-change-the-location-setting.jpg)
9. In the Edit String window, type **Allow** in the **Value data** field and click OK.
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After that, close the Registry Editor and restart your PC. Windows should detect the time zone automatically and set it correctly.

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Use the Group Policy Editor

 If you're comfortable with registry editing, use the Group Policy Editor instead. However, the tool is only compatible with Windows Pro and Enterprise editions. If you're not a Pro user, [activate the Group Policy for Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/), then follow these steps:

1. Right-click on Start and select **Run**.
2. Type **gpedit.msc** in the text field and click **OK**. The Local Group Policy Editor window will open.
3. On the left navigation panel, browse to the following path:  
`Computer Configuration > Administrative Templates > Windows Components > Location and Sensors > Windows Location Provider`
4. Go to the right pane and double-click on **Turn off Windows Location Provider**.  
![Turn off Windows Location Provider](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/turn-off-windows-location-provider.jpg)
5. In the pop-up window, check the **Not Configured** option.
6. Click **Apply** and **OK** to save the changes.

 Now close the Group Policy Editor and restart your PC. After restarts check if your Windows detects the time zone automatically.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
## 6\. Reset the Windows Time Service

 This problem may also occur if the Windows Time Service or time synchronization settings become corrupted. In that case, reset the service to its default settings and see if that helps. Here's how to do it:

1. Click on Start and type **cmd** in the search box.
2. Press **Ctrl + Shift + Enter** on your keyboard simultaneously. This opens the Command Prompt in administrator mode.
3. If the pop-up window appears, click **Yes** to grant permission.
4. In the Command Prompt window, type net **stop w32time** and press **Enter**. Running this command will stop the Windows Time Service.
5. Now, type **w32tm /unregister** in the Command Prompt window and hit **Enter**. This unregisters the service.
6. Next, type **w32tm /register** and press **Enter**. This will re-register the Windows Time Service.
7. After that, type net **start w32time** to restart the Windows Time Service.

 Once done, close the Command Prompt and restart your computer to check if it solves the problem.

## 7\. Try Some Generic Windows Fixes

 There are also generic fixes you can try:

1. **Run the System File Checker tool:**[running System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) scans for corrupted system files and replaces them if necessary.
2. **Perform a Clean Boot:** If that didn't work, [try a Windows clean boot](https://www.makeuseof.com/clean-boot-windows-11/). This determines if third-party applications interfere with Windows Time Service.
3. **Update Windows:** Finally, [update Windows to the latest version](https://www.makeuseof.com/update-windows-manually/) to ensure you have all the latest fixes and security patches.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
## Windows Can Now Automatically Set the Time Zone

 We hope the article helped you resolve timing issues on your Windows computer. It may occur due to missing or corrupted system files or incorrect time zone settings. Make sure to try these solutions and perform a System Restore if the problem persists.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-lab.techidaily.com/024-approved-top-15-youtube-recording-software-for-gamers/"><u>[New] 2024 Approved  Top 15 YouTube Recording Software for Gamers</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-step-by-step-mastering-the-art-of-vr-exploration-for-2024/"><u>[Updated] Step-by-Step  Mastering the Art of VR Exploration for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-hastyhit-freezevidsnapshot/"><u>2024 Approved  HastyHit FreezeVidSnapshot</u></a></li>
<li><a href="https://fox-info.techidaily.com/a-canvas-of-colors-advanced-theory-and-use-for-2024/"><u>A Canvas of Colors  Advanced Theory & Use for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-realme-c67-4g-drfone-by-drfone-reset-android-reset-android/"><u>All About Factory Reset, What Is It and What It Does to Your Realme C67 4G? | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/audacity-for-the-mac-enthusiast-advanced-recording-techniques-for-2024/"><u>Audacity for the Mac Enthusiast  Advanced Recording Techniques for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/digital-diaries-top-picks-for-personal-recorders/"><u>Digital Diaries  Top Picks for Personal Recorders</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/discover-the-science-of-openai-ai/"><u>Discover the Science of OpenAI AI</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-power-settings-on-windows-desktops/"><u>Exploring Power Settings on Windows Desktops</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-properly-download-and-install-the-latest-broadcom-gigabit-ethernet-driver-for-your-windows-10-pc-issues-resolved/"><u>How to Properly Download & Install the Latest Broadcom Gigabit Ethernet Driver for Your Windows 10 PC - Issues Resolved!</u></a></li>
<li><a href="https://windows11.techidaily.com/how-will-eliminating-taskbar-chat-from-windows-11-change-your-user-experience/"><u>How Will Eliminating Taskbar Chat From Windows 11 Change Your User Experience?</u></a></li>
<li><a href="https://fox-that.techidaily.com/imessage-signs-of-being-blocked-by-another-user-what-to-look-for/"><u>IMessage Signs of Being Blocked by Another User – What to Look For</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-unlock-icloud-activation-lock-and-icloud-account-on-iphone-xr-by-drfone-ios/"><u>In 2024, How to Unlock iCloud Activation Lock and iCloud Account On iPhone XR?</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-the-best-8-vpn-hardware-devices-reviewed-on-realme-v30t-drfone-by-drfone-virtual-android/"><u>In 2024, The Best 8 VPN Hardware Devices Reviewed On Realme V30T | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-oneplus-ace-2-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Location is Not Updating and How to Fix On OnePlus Ace 2 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/learn-to-unbind-your-onedrive-and-microsoft-profile-on-windows/"><u>Learn to Unbind Your OneDrive & Microsoft Profile on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/managing-antivirus-softwares-ram-consumption/"><u>Managing Antivirus Software’s RAM Consumption</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-app-migration-to-your-new-windows-11-laptop/"><u>Mastering App Migration to Your New Windows 11 Laptop</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-canary-vulnerability-alerts/"><u>Mastering Windows’ Canary Vulnerability Alerts</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-windows-11s-application-management-capabilities-with-winget/"><u>Maximizing Windows 11'S Application Management Capabilities with Winget</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-store-sign-in-woes-heres-how-to-fix-it/"><u>Microsoft Store Sign-In Woes? Here's How to Fix It</u></a></li>
<li><a href="https://windows11.techidaily.com/modernize-windows-shift-to-enhanced-tiled-workspace/"><u>Modernize Windows: Shift to Enhanced Tiled Workspace</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-blocked-app-warning-on-windows-os/"><u>Overcoming Blocked App Warning on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-pink-screens-with-ease-and-speed/"><u>Overcoming Windows Pink Screens with Ease and Speed</u></a></li>
<li><a href="https://windows11.techidaily.com/proactive-pc-management-keeping-windows-11s-amd-drivers-current/"><u>Proactive PC Management: Keeping Windows 11'S AMD Drivers Current</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-addressing-need-to-quit-in-roblox-on-pc/"><u>Quick Guide: Addressing Need To Quit in Roblox on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/race-the-rating-effective-techniques-for-measuring-network-adapter-speed-on-windows/"><u>Race the Rating: Effective Techniques for Measuring Network Adapter Speed on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/reconnecting-to-ea-servers-after-connection-failures-in-windows/"><u>Reconnecting to EA Servers After Connection Failures in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/regain-control-over-windows-11s-dropped-items/"><u>Regain Control Over Windows 11'S Dropped Items</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-the-empty-folder-message-on-windows-11/"><u>Remedying the Empty Folder Message on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resuscitation-guide-bring-back-function-of-wsreset-on-pcs/"><u>Resuscitation Guide: Bring Back Function of WSReset on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/revive-stalled-access-on-credential-store/"><u>Revive Stalled Access on Credential Store</u></a></li>
<li><a href="https://windows11.techidaily.com/secrets-resolving-uncontrolled-mouse-jitter-in-win11/"><u>Secrets: Resolving Uncontrolled Mouse Jitter in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/simplify-tasks-with-your-default-windows-terminal/"><u>Simplify Tasks With Your Default Windows Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-package-unregistered-photo-problems-in-windows-os/"><u>Solving 'Package Unregistered' Photo Problems in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-zerodxgierordevicelatencyerror-for-win11-users/"><u>Solving ZeroDXGIErorDeviceLatencyError for Win11 Users</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/sony-a6400-why-is-my-video-playback-failed-for-2024/"><u>Sony A6400  Why Is My Video Playback Failed for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-error-0x0000011b-on-windows-11/"><u>Steps to Resolve Error 0X0000011B on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-stuck-scrollbar-and-freezing-pages-in-microsoft-excel-on-windows/"><u>Stop Stuck Scrollbar & Freezing Pages in Microsoft Excel on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-windows-update-failures-with-these-fixes/"><u>Stop Windows Update Failures with These Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-coding-process-essential-wsl-2-tips-and-tricks-for-dev/"><u>Streamline Coding Process: Essential WSL 2 Tips and Tricks for Dev</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-tap-into-disk-access-4-ways-to-engage-with-disk-editor-settings-on-win11/"><u>Swiftly Tap Into Disk Access: 4 Ways to Engage with Disk Editor Settings on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-system-wake-up-shortening-boot-menu-hesitation-period/"><u>Tailoring System Wake-Up: Shortening Boot Menu Hesitation Period</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-guide-to-choosing-top-fps-counter-software-for-windows-11/"><u>The Essential Guide to Choosing Top FPS Counter Software for Windows 11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-ultimate-guide-to-earning-cash-online-with-no-skills-needed/"><u>The Ultimate Guide to Earning Cash Online with No Skills Needed</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-reactivating-explore-in-11os/"><u>The Ultimate Guide to Reactivating Explore in 11OS</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-for-functional-thx-audio/"><u>Troubleshooting Windows for Functional THX Audio</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-windows-notification-blockade-from-phone-link/"><u>Unblocking Windows Notification Blockade From Phone Link</u></a></li>
<li><a href="https://windows11.techidaily.com/unwrapping-the-mystery-microsoft-store-error-code-0x80073cf3/"><u>Unwrapping the Mystery: Microsoft Store Error Code 0X80073CF3</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-best-of-the-best-10-webm-to-mp4-converters-for-easy-conversion/"><u>Updated 2024 Approved Best of the Best 10 WebM to MP4 Converters for Easy Conversion</u></a></li>
<li><a href="https://windows11.techidaily.com/win-over-frozen-exe-files-on-your-computer/"><u>Win Over Frozen Exe Files on Your Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-restricted-interface-an-overview/"><u>Windows 11'S Restricted Interface: An Overview</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-startup-guide-navigating-accessibility-features/"><u>Windows Startup Guide: Navigating Accessibility Features</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>