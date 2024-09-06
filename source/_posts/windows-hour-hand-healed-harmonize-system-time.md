---
title: "Windows Hour Hand Healed: Harmonize System Time"
date: 2024-09-05T02:15:52.393Z
updated: 2024-09-06T02:15:52.393Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Hour Hand Healed: Harmonize System Time"
excerpt: "This Article Describes Windows Hour Hand Healed: Harmonize System Time"
keywords: Windows Time Sync,Repairing Clock Gesture,System Time Harmony,Hour Hand Restoration,Windows Clock Fix,Time Alignment Tips,Healing Hour Movement
thumbnail: https://thmb.techidaily.com/daf5ba2a8491ccb029544c33871dfddf8c00a96e763bab0af0faf409f9f29c9c.jpg
---

## Windows Hour Hand Healed: Harmonize System Time

 Is your Windows system clock out of sync? Are you receiving an error message saying “Time synchronization failed”? It may cause various issues like missing reminders or emails with the wrong timestamp. Read this guide to learn how to fix the issue and synchronize your system clock accurately.

## What Causes Time Synchronization to Fail on Windows?

 Time synchronization issues on Windows can occur for several reasons. Here are some common causes.

1. **Incorrect timezone settings:** The time set on your PC must be accurate for synchronization to work properly. If the time zone is incorrect, synchronization will fail.
2. **Firewall settings:** Firewalls block the Windows Time service from connecting to its hosts. This prevents time synchronization from occurring.
3. **System viruses and malware:** Viruses or malicious software corrupt system files related to time synchronization, causing failure.
4. **Problems with the Windows Time service:** The Windows Time (W32Time) service controls time synchronization on your system. If it's not running properly, synchronization will fail.

 Now that you know the possible causes of time synchronization failure, let’s discuss how to fix this issue.

## 1\. Restart the Windows Time Service

 The Windows Time Service keeps the computer’s time and date synchronized with other computers on the network. If this service is stopped or not functioning, it leads to time synchronization issues.

 To restart the Windows Time Service, follow these steps:

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **services.msc** in the search box and hit Enter. This will open the Services window.
3. Locate the **Windows Time** service and right-click on it.
4. Select **Restart** from the context menu.  
![Restart Windows Time service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restart-windows-time-service.jpg)

 Once the service is restarted, close the window and check the time synchronization.

## 2\. Configure the Windows Time Service

 If restarting the Windows Time Service doesn't resolve the time synchronization issue, configure its settings to see if that helps.

 To configure the Windows Time Service, follow these steps:

1. [Open the Services window](https://www.makeuseof.com/windows-11-open-services-app/).
2. Double-click on **Windows Time** to open its properties window.
3. On the **General** tab, set the Startup Typeto **Automatic**.  
![Windows Time Service Status](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-time-service-status.jpg)
4. Now go to Service Status and click on the **Start** button. If the service is running, click on **Stop** and then **Start**.
5. Switch to the **Log On** tab and select **Local System account**.  
![Windows Time Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-time-properties-window.jpg)
6. Check the **Allow Service** **to Interact with desktop** option.
7. Click **Apply > OK** to save the changes.

 Now that you have configured the Windows Time Service, close the window. After that, restart your computer and check if time synchronization works.

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/1943647/22993" target="_top" id="1943647">
  <img src="//a.impactradius-go.com/display-ad/22993-1943647" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://homestyler.sjv.io/i/5597632/1943647/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://aligracehair.sjv.io/c/5597632/1959778/19272" target="_top" id="1959778">
  <img src="//a.impactradius-go.com/display-ad/19272-1959778" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959778/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948895/19272" target="_top" id="1948895">
  <img src="//a.impactradius-go.com/display-ad/19272-1948895" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948895/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Double-click on the new **String Value** and enter a valid time server URL in the Value data box.
8. Repeat the above steps until you have added all the time servers to the list.

 Once you are done, close the registry editor. After synchronization completes, close all windows and restart your computer. Then verify if the time is accurate.

## 5\. Scan for Malicious Programs

 If other methods fail to fix the time synchronization issue on your Windows computer, scan for malicious programs. Malicious software interrupts time synchronization processes and causes errors.

 To scan for malicious programs, follow these steps:

1. Press **Win + S** on your keyboard to open the Windows Search box.
2. Type **Windows Security** in the search box and hit Enter.
3. In the Windows Security window, click on **Virus & threat protection**.  
![Scan options in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/scan-options-in-windows-security.jpg)
4. Under **Current threats**, click **Scan options** and check **Full scan** from the list.  
<!-- affiliate ads begin -->
<span id="1983552">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983552.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983552">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983552.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983552%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983552/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Full Scan Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-scan-windows-security.jpg)
5. Now click **Scan now** to initiate a full scan.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006919/19272" target="_top" id="2006919">
  <img src="//a.impactradius-go.com/display-ad/19272-2006919" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006919/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you perform the above action, close the Windows Security window and restart your computer. If malicious programs were responsible for the issue, it should now keep the time synchronized correctly.

## 6\. Try Some Generic Fixes

 Besides the specific solutions mentioned above, there are some general fixes that troubleshoot time synchronization problems.

 Try these suggestions to fix time synchronization failed errors:

1. [Run the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/). This tool scans system files and replaces any corrupted files that cause the time synchronization to fail.
2. [Perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) and check if that helps. It’s possible that some software or process running on your PC interferes with time synchronization. Doing a clean boot identifies the culprit and solves the issue.
3. [Temporarily disable firewall and antivirus programs](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/). Firewall or antivirus settings can sometimes block the Windows Time service from connecting to its hosts, resulting in synchronization failure. Temporarily disabling your firewall and antivirus programs can resolve this issue.
4. [Run the Windows Network Connections tool](https://www.makeuseof.com/windows-open-network-connections-tool/) to diagnose and repair network issues.

 These fixes resolve time synchronization problems on your Windows computer.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043662/7443" target="_top" id="2043662">
  <img src="//a.impactradius-go.com/display-ad/7443-2043662" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043662/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fixing Time Synchronization Issues on Windows

 We hope this article resolved any timing issues you encountered on your Windows computer. If the issue continues, perform a system restore. This reverses any recent modifications that could cause the issue. Meanwhile, it is advised to regularly backup your data in case of sudden system failures.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-glue.techidaily.com/new-androidiphones-finest-top-10-cost-effective-image-enhancers-ranked/"><u>[New] Android/iPhone's Finest – Top 10 Cost-Effective Image Enhancers Ranked</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-discover-the-10-leading-no-cost-webcalls-for-businesses/"><u>[New] Discover the 10 Leading No-Cost Webcalls for Businesses</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-master-the-art-of-video-sending-from-youtube-to-dailymotion/"><u>[New] Master the Art of Video Sending  From YouTube to Dailymotion</u></a></li>
<li><a href="https://win-blog.techidaily.com/solved-firefox-keeps-freezing-2024-guide/"><u>[SOLVED] Firefox Keeps Freezing – 2024 Guide</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-quick-quality-edits-the-ultimate-guide-to-pixlr/"><u>[Updated] In 2024, Quick, Quality Edits  The Ultimate Guide to Pixlr</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-photographers-guide-to-digital-cropting/"><u>2024 Approved  The Photographer's Guide to Digital Cropting</u></a></li>
<li><a href="https://screen-recording.techidaily.com/capture-king-review-the-screen-recorder-showdown/"><u>Capture King Review  The Screen Recorder Showdown</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-inaccessible-folders-in-windows-outlook-a-comprerani-guide/"><u>Fixing Inaccessible Folders in Windows Outlook: A Comprerani Guide</u></a></li>
<li><a href="https://fox-info.techidaily.com/from-analog-to-digital-srt-conversion-into-modern-audio-standards-for-2024/"><u>From Analog to Digital  SRT Conversion Into Modern Audio Standards for 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/gtx-970-driver-latest-win-11-release/"><u>GTX 970 Driver Latest: Win 11 Release</u></a></li>
<li><a href="https://fox-that.techidaily.com/how-to-overcome-difficulties-in-sharing-subscriptions-among-families/"><u>How to Overcome Difficulties in Sharing Subscriptions Among Families</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-use-the-windows-canary-protection-tool/"><u>How to Use the Windows Canary Protection Tool</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-unlock-icloud-activation-lock-and-icloud-account-on-iphone-7-by-drfone-ios/"><u>In 2024, How to Unlock iCloud Activation Lock and iCloud Account On iPhone 7?</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-unlock-software-for-vivo-y27-4g-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>In 2024, The Best Android Unlock Software For Vivo Y27 4G Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-blueprint-of-film-narrative/"><u>In 2024, The Blueprint of Film Narrative</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-xiaomi-redmi-12-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Live Location is Not Updating and How to Fix on your Xiaomi Redmi 12 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-in-gaming-3-methods-for-directory-unlock/"><u>Mastery in Gaming: 3 Methods for Directory Unlock</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-for-rectifying-unlaunchable-lunar-client-warning/"><u>Methods for Rectifying Unlaunchable Lunar Client Warning</u></a></li>
<li><a href="https://buynow-info.techidaily.com/microsoft-flight-simulator-x-gold-edition-analysis-remaining-a-top-tier-choice-in-aeronautics-gaming/"><u>Microsoft Flight Simulator X Gold Edition Analysis: Remaining a Top-Tier Choice in Aeronautics Gaming</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-failed-rpc-calls-a-windows-focused-guide/"><u>Overcoming Failed RPC Calls: A Windows-Focused Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/overhauling-windows-11-camera-glitch-fix-for-error-code-a00f425d/"><u>Overhauling Windows 11 Camera Glitch: Fix for Error Code A00F425D</u></a></li>
<li><a href="https://windows11.techidaily.com/pinpoint-win-logins-the-differentiator-between-right-and-wrong-entries/"><u>Pinpoint Win Logins: The Differentiator Between Right & Wrong Entries</u></a></li>
<li><a href="https://techtrends.techidaily.com/psvr2-unveiled-latest-updates-on-release-dates-pricing-and-hardware-specifications/"><u>PSVR2 Unveiled: Latest Updates on Release Dates, Pricing & Hardware Specifications</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-and-easy-window-11-app-opener-techniques/"><u>Quick and Easy Window 11 App Opener Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/reactive-keys-reclaiming-shift-on-win/"><u>Reactive Keys: Reclaiming Shift on Win.</u></a></li>
<li><a href="https://windows11.techidaily.com/reducing-power-consumption-while-maintaining-peak-performance/"><u>Reducing Power Consumption While Maintaining Peak Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/skirting-legalities-shun-chatbots-for-windows-keys/"><u>Skirting Legalities: Shun Chatbots for Windows Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/solve-your-inked-woes-a-guide-to-fixing-windows-pen-devices/"><u>Solve Your Inked Woes: A Guide to Fixing Windows Pen Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-w10w11-interruptexception-bsod-a-comprehensible-guide/"><u>Solving W10/W11 INTERRUPT_EXCEPTION BSOD: A Comprehensible Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-boot-streamlining-your-win11-routines/"><u>Speedy Boot: Streamlining Your Win11 Routines</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-pc-functionality-addressing-11-windows-problems/"><u>Streamlining PC Functionality - Addressing 11 Windows Problems</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/tech-for-everyone-experts-analysis-for-2024/"><u>Tech for Everyone  Experts' Analysis for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-audio-advantage-top-4-programs-for-surpassing-windows-100-limit/"><u>The Audio Advantage: Top 4 Programs for Surpassing Windows' 100%% Limit</u></a></li>
<li><a href="https://windows11.techidaily.com/the-complete-process-for-adding-widgets-on-windows-11/"><u>The Complete Process for Adding Widgets on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-os-metamorphosis-insights-into-w10-and-w11-developments/"><u>The OS Metamorphosis: Insights Into W10 and W11 Developments</u></a></li>
<li><a href="https://windows11.techidaily.com/the-unseen-consequences-of-cost-saving-windows-activation/"><u>The Unseen Consequences of Cost-Saving Windows Activation</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-and-personalize-your-pc-with-alomwares-mastery/"><u>Transform and Personalize Your PC With AlomWare's Mastery</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-memory-feature-disabled-in-win11/"><u>Troubleshooting Memory Feature Disabled in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-silent-keys-troubleshooting-tactics-for-windows-pcs/"><u>Unlock Silent Keys: Troubleshooting Tactics for Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-compressed-storage-on-windows-11/"><u>Unlocking Compressed Storage on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-successful-remote-steam-connectivity/"><u>Unlocking Successful Remote Steam Connectivity</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-system-restore-issue-0x80042306-in-win10/"><u>Unraveling System Restore Issue 0X80042306 in Win10</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/unveiling-farsis-roots-benefits-of-mastery/"><u>Unveiling Farsi's Roots: Benefits of Mastery</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/upgrade-your-audio-experience-find-new-replacement-ear-cushions-for-old-headphones/"><u>Upgrade Your Audio Experience: Find New Replacement Ear Cushions for Old Headphones</u></a></li>
<li><a href="https://windows11.techidaily.com/whats-next-after-0x800f0845-error/"><u>What's Next After 0X800f0845 Error?</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-mastery-constructing-clutter-free-directories/"><u>Windows 11 Mastery: Constructing Clutter-Free Directories</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-ram-cache-basics-and-cleansing-methods/"><u>Windows RAM Cache Basics and Cleansing Methods</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>