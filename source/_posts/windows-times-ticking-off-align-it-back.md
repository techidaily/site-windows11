---
title: Windows Time's Ticking Off? Align It Back!
date: 2024-08-15T16:07:58.075Z
updated: 2024-08-16T16:07:58.075Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Windows Time's Ticking Off? Align It Back!
excerpt: This Article Describes Windows Time's Ticking Off? Align It Back!
keywords: Windows Time Adjustment,Clock Sync Issue,System Time Error,Realign Windows Time,Time Discrepancy Fix,Windows Timestamp Correction,Aligning OS Time Correctly
thumbnail: https://thmb.techidaily.com/12fbcccb55845f8983544f25e1cc6b0c0aa528d408cbc232f59c597fcdf5f91a.png
---

## Windows Time's Ticking Off? Align It Back

 Is your Windows system clock out of sync? Are you receiving an error message saying “Time synchronization failed”? It may cause various issues like missing reminders or emails with the wrong timestamp. Read this guide to learn how to fix the issue and synchronize your system clock accurately.

## What Causes Time Synchronization to Fail on Windows?

 Time synchronization issues on Windows can occur for several reasons. Here are some common causes.

1. **Incorrect timezone settings:** The time set on your PC must be accurate for synchronization to work properly. If the time zone is incorrect, synchronization will fail.
2. **Firewall settings:** Firewalls block the Windows Time service from connecting to its hosts. This prevents time synchronization from occurring.
3. **System viruses and malware:** Viruses or malicious software corrupt system files related to time synchronization, causing failure.
4. **Problems with the Windows Time service:** The Windows Time (W32Time) service controls time synchronization on your system. If it's not running properly, synchronization will fail.

 Now that you know the possible causes of time synchronization failure, let’s discuss how to fix this issue.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
## 1\. Restart the Windows Time Service

 The Windows Time Service keeps the computer’s time and date synchronized with other computers on the network. If this service is stopped or not functioning, it leads to time synchronization issues.

 To restart the Windows Time Service, follow these steps:

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **services.msc** in the search box and hit Enter. This will open the Services window.
3. Locate the **Windows Time** service and right-click on it.
4. Select **Restart** from the context menu.  
![Restart Windows Time service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restart-windows-time-service.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->

 Once the service is restarted, close the window and check the time synchronization.

## 2\. Configure the Windows Time Service

 If restarting the Windows Time Service doesn't resolve the time synchronization issue, configure its settings to see if that helps.

 To configure the Windows Time Service, follow these steps:

1. [Open the Services window](https://www.makeuseof.com/windows-11-open-services-app/).
2. Double-click on **Windows Time** to open its properties window.
3. On the **General** tab, set the Startup Typeto **Automatic**.  
![Windows Time Service Status](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-time-service-status.jpg)
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
4. Now go to Service Status and click on the **Start** button. If the service is running, click on **Stop** and then **Start**.
5. Switch to the **Log On** tab and select **Local System account**.  
![Windows Time Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-time-properties-window.jpg)
<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
6. Check the **Allow Service** **to Interact with desktop** option.
7. Click **Apply > OK** to save the changes.

 Now that you have configured the Windows Time Service, close the window. After that, restart your computer and check if time synchronization works.

## 3\. Change the Time Server

 This method is suitable when the time synchronization service fails to sync with an internet time server. It syncs to a reliable internet clock manually.

 To modify internet time settings, follow these steps:

1. [Open the Run Command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **timedate.cpl** in the text box and press Enter. This will open the Date and Time window.
3. Switch to the **Internet Time** tab and click on **Change settings**.
4. Check the box next to **Synchronize with an Internet time server**.  
![Change the Time Server](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/change-the-time-server.jpg)
5. Select a different time server from the **Server** list.
6. Click **Update now** to sync your PC with the selected time server.

 Once you perform the above action, close all windows and restart your computer. After restarting, check if the time synchronization issue is fixed.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
## 4\. Add More Time Servers

 If changing the time server doesn't work, add more servers to the list. That way, Windows try different servers to keep time in sync. To add more time servers, follow these steps:

1. Press **Win + S** on your keyboard to open the Windows Search box.
2. Type **regedit** in the search box and hit Enter.
3. If UAC (User Account Control) dialog appears, click **Yes** to continue.
4. In the registry editor, navigate the following steps.  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\DateTime\Servers`
5. Right-click on the **Servers** key and select **New** \> **String Value**.  
![Add More Time Servers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/add-more-time-servers.jpg)
6. Name the new string value **ServerX**, where X is the server number.
7. Double-click on the new **String Value** and enter a valid time server URL in the Value data box.
8. Repeat the above steps until you have added all the time servers to the list.

 Once you are done, close the registry editor. After synchronization completes, close all windows and restart your computer. Then verify if the time is accurate.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 5\. Scan for Malicious Programs

 If other methods fail to fix the time synchronization issue on your Windows computer, scan for malicious programs. Malicious software interrupts time synchronization processes and causes errors.

 To scan for malicious programs, follow these steps:

1. Press **Win + S** on your keyboard to open the Windows Search box.
2. Type **Windows Security** in the search box and hit Enter.
3. In the Windows Security window, click on **Virus & threat protection**.  
![Scan options in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/scan-options-in-windows-security.jpg)
4. Under **Current threats**, click **Scan options** and check **Full scan** from the list.  
![Full Scan Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-scan-windows-security.jpg)
<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Now click **Scan now** to initiate a full scan.

 Once you perform the above action, close the Windows Security window and restart your computer. If malicious programs were responsible for the issue, it should now keep the time synchronized correctly.

## 6\. Try Some Generic Fixes

 Besides the specific solutions mentioned above, there are some general fixes that troubleshoot time synchronization problems.

 Try these suggestions to fix time synchronization failed errors:

1. [Run the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/). This tool scans system files and replaces any corrupted files that cause the time synchronization to fail.
2. [Perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) and check if that helps. It’s possible that some software or process running on your PC interferes with time synchronization. Doing a clean boot identifies the culprit and solves the issue.
3. [Temporarily disable firewall and antivirus programs](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/). Firewall or antivirus settings can sometimes block the Windows Time service from connecting to its hosts, resulting in synchronization failure. Temporarily disabling your firewall and antivirus programs can resolve this issue.
4. [Run the Windows Network Connections tool](https://www.makeuseof.com/windows-open-network-connections-tool/) to diagnose and repair network issues.

 These fixes resolve time synchronization problems on your Windows computer.

## Fixing Time Synchronization Issues on Windows

 We hope this article resolved any timing issues you encountered on your Windows computer. If the issue continues, perform a system restore. This reverses any recent modifications that could cause the issue. Meanwhile, it is advised to regularly backup your data in case of sudden system failures.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-prime-interactive-room-for-free-play/"><u>[New] In 2024, Prime Interactive Room for Free Play</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-enhance-tv-viewing-with-global-news-and-events-via-fb-live-roku-style-for-2024/"><u>[Updated] Enhance TV Viewing with Global News & Events via FB Live, Roku Style for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/5-ways-to-fix-the-hypervisorerror-blue-screen-on-windows-11-and-11/"><u>5 Ways to Fix the HYPERVISOR_ERROR Blue Screen on Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/7-techniques-for-reviving-a-stuck-dark-screen-mode/"><u>7 Techniques for Reviving a Stuck Dark Screen Mode</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-quick-guide-to-oppo-a2-frp-bypass-instantly-by-drfone-android/"><u>A Quick Guide to Oppo A2 FRP Bypass Instantly</u></a></li>
<li><a href="https://windows11.techidaily.com/achieving-perfect-boot-strategies-to-configure-startup-services-in-win11/"><u>Achieving Perfect Boot: Strategies to Configure Startup Services in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-customizable-rgb-in-windows-11-os/"><u>Activating Customizable RGB in Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-the-hotspot-offline-error-in-windows-11/"><u>Addressing the Hotspot Offline Error in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-time-display-in-the-taskbar-of-window-11/"><u>Adjusting Time Display in the Taskbar of Window 11</u></a></li>
<li><a href="https://windows11.techidaily.com/affordable-access-to-windows-11-licenses/"><u>Affordable Access to Windows 11 Licenses</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/americas-most-popular-foreign-language-programs/"><u>America's Most Popular Foreign Language Programs</u></a></li>
<li><a href="https://windows11.techidaily.com/banish-file-explorer-errors-essential-fixes-for-win11-users/"><u>Banish File Explorer Errors: Essential Fixes for Win11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/best-wsl-2-methods-for-efficient-windows-coding/"><u>Best WSL 2 Methods for Efficient Windows Coding</u></a></li>
<li><a href="https://windows11.techidaily.com/bluescreenview-explained-for-everyday-users/"><u>BlueScreenView Explained for Everyday Users</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-productivity-with-windows-11-strategies/"><u>Boosting Productivity with Windows 11 Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/circumventing-firewall-restriction-chrome-connectivity-solution/"><u>Circumventing Firewall Restriction: Chrome Connectivity Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/combating-computer-chaos-fixing-windows-non-responsive-keys/"><u>Combating Computer Chaos: Fixing Windows' Non-Responsive Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/concealing-the-taskbar-written-words-in-windows-11-ui/"><u>Concealing the Taskbar’ Written Words in Windows 11 UI</u></a></li>
<li><a href="https://windows11.techidaily.com/contrasting-the-workflow-of-cloud-based-and-disk-installed-windows-oses/"><u>Contrasting the Workflow of Cloud-Based & Disk Installed Windows OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/cost-saving-strategies-for-new-windows-11-users/"><u>Cost-Saving Strategies for New Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-edge-tweaks-for-your-pc-explore-alomwares-capabilities/"><u>Cutting-Edge Tweaks for Your PC: Explore AlomWare's Capabilities</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-access-issues-fixing-the-no-write-allowed-error/"><u>Dealing with Access Issues: Fixing the No Write Allowed Error</u></a></li>
<li><a href="https://windows11.techidaily.com/decode-and-dissolve-rectifying-win11-webcam-issue-error-a00f4289/"><u>Decode & Dissolve: Rectifying Win11 Webcam Issue - Error A00F4289</u></a></li>
<li><a href="https://windows11.techidaily.com/diagnosing-and-fixing-printmanagement-error-on-windows-os/"><u>Diagnosing and Fixing 'PrintManagement' Error on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/diagnosing-and-fixing-microsoft-windows-nearby-share-malfunction/"><u>Diagnosing and Fixing Microsoft Windows Nearby Share Malfunction</u></a></li>
<li><a href="https://windows11.techidaily.com/directx-essentials-downloading-installing-made-easy-for-pc-users/"><u>DirectX Essentials: Downloading, Installing Made Easy for PC Users</u></a></li>
<li><a href="https://some-techniques.techidaily.com/fast-facial-masking-on-piscart-a-convenient-guide-for-2024/"><u>Fast Facial Masking on PiscArt  A Convenient Guide for 2024</u></a></li>
<li><a href="https://facebook.techidaily.com/1719145917232-fortify-your-online-communications-facebooks-newly-launched-encrypted-chat-features-enhance-privacy/"><u>Fortify Your Online Communications: Facebook's Newly Launched Encrypted Chat Features Enhance Privacy.</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-frp-hijacker-by-hagard-download-and-bypass-your-vivo-s18-pro-frp-locks-by-drfone-android/"><u>In 2024, FRP Hijacker by Hagard Download and Bypass your Vivo S18 Pro FRP Locks</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-iphone-8-plus-backup-password-never-set-but-still-asking-heres-the-fix-drfone-by-drfone-ios/"><u>In 2024, iPhone 8 Plus Backup Password Never Set But Still Asking? Heres the Fix | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-unlock-the-power-of-speed-in-video-production/"><u>In 2024, Unlock the Power of Speed in Video Production</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-magnificent-art-of-pokemon-go-streaming-on-oppo-find-n3-drfone-by-drfone-virtual-android/"><u>The Magnificent Art of Pokemon Go Streaming On Oppo Find N3? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-messages-from-c55-by-fonelab-android-recover-messages/"><u>The way to get back lost messages from C55</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-the-perfect-match-for-all-audio-lovers-top-10-free-video-to-audio-conversion-services/"><u>Updated In 2024, The Perfect Match for All Audio Lovers Top 10 Free Video to Audio Conversion Services</u></a></li>
</ul></div>
