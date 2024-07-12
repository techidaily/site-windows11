---
title: "Navigating Chrome's Erroneous Threat Detection: A Guide"
date: 2024-07-11T21:14:08.794Z
updated: 2024-07-12T21:14:08.794Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Navigating Chrome's Erroneous Threat Detection: A Guide"
excerpt: "This Article Describes Navigating Chrome's Erroneous Threat Detection: A Guide"
keywords: Chrome Threat Alert,Fixing False Warnings,Error Detection in Chrome,Safe Browsing Tips,Ignore Chrome Alerts,Misled Browser Notifications,Avoiding Erroneous Threats
thumbnail: https://thmb.techidaily.com/db6e8bb5b9330de241494205e28fd162607bcee64226c4e5f87f88fc35435d44.jpg
---

## Navigating Chrome's Erroneous Threat Detection: A Guide

 Have you encountered an error that reads "failed - virus detected" when downloading specific files through Chrome? It usually occurs when Chrome or Windows Defender detects a virus in a potentially malicious file you're downloading. As a result, it halts the download process and displays this error message to prevent your computer from getting infected.

 Occasionally, Chrome raises false flags even if you're downloading a safe file from a reputable source. What can you do about this situation? What is the best way to verify that the file is safe? If it's safe, how do you bypass this error message? We will cover everything in this article.

## Before We Get Started…

 Before implementing the fixes, ensure Chrome is up-to-date. In some cases, outdated Chrome can cause unforeseen issues. Among them could be halting the download for no apparent reason. Therefore, it's imperative to [update Chrome](https://www.makeuseof.com/how-to-update-chrome-firefox-edge-desktop-mobile/#how-to-update-and-view-the-current-version-of-chrome-on-desktop) to rule out this possibility.

 In addition, try closing the browser and restarting it to see if that resolves the problem. You should also [clear your cache and cookies](https://www.makeuseof.com/how-to-clear-cookies-cache-in-chrome/) to ensure they won't interfere with the download process.

## 1\. Ensure the File You're Downloading Is Safe

 Even when downloading a file from a legitimate source, it's imperative to ensure it is safe to download. Follow the below steps to ensure the file is virus-free:

1. Visit [VirusTotal's official website](https://www.virustotal.com/gui/home/url) .
2. Copy the download link of the file you are having trouble downloading.
3. Paste the downloaded link into the**URL** search bar.  
![pasting the downloaded link of the file into the url search bar on the virustotal official website](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/pasting-the-downloaded-link-of-the-file-into-the-url-search-bar-on-the-virus-totals-official-website.jpg)
4. Press**Enter** to continue.  
![scan results of a file being downloaded checked on the virus totals official website](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/scan-results-of-a-file-being-downloaded-checked-on-the-virus-totals-official-website.jpg)

 After the scan is complete, see if it returns a clean result. If the tool detects some viruses, you'd be better off not downloading the file. If the scan comes back clean but you're still getting the error, it's time to try something else

## 2\. Does the Issue Pertain to a Particular File?

 Check if the error occurs only when downloading a specific file. If so, maybe you need to download it from another source.

 Thus, try downloading the same file from another website, preferably an official one, and see if you are successful. If not, or if you continue to experience errors while downloading multiple files, the problem is more widespread.

 Apply the remaining fixes only if you are absolutely certain that the file you are downloading is safe.

## 3\. Disable Any Security Extensions

 Any security extensions you're using, especially virus scanners, might interfere with the download process and force Chrome to stop it midway. It is, therefore, advisable to disable all security extensions on your browser that you think may hinder the download process. Not sure how to go about it? See [how to disable or remove browser extensions](https://www.makeuseof.com/tag/how-to-clean-up-your-browser-extensions-the-easy-way/) in all browsers.

## 4\. Exclude the Downloads Folder From Windows Defender

 By default, Microsoft Defender scans every folder on your computer. As such, it will prevent your download from completing if it detects a virus. By excluding the destination folder where your file is being downloaded, you may get rid of the error.

 Unless you have changed the download location, follow the below steps to exclude the Downloads folder in Windows Defender:

1. In the Windows Search, search for**"Windows Security"** and open the app.
2. In the left-sidebar, click**Virus & threat protection** .
3. In the right-hand pane, click**Manage settings** .  
![Opening Manage Settings Option under Virus and Threat Protection Settings in Windows Security App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Image-5-Opening-Manage-Settings-Option-under-Virus-and-Threat-Protection-Settings--in-Windows-Security-App.jpg)
4. Under**Exclusions** , click**Add or remove exclusions** .
5. Click on**Add an exclusion** button and select**Folder** .  
![Adding an Exclusion for Downloads Folder in Windows Security Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Image-6-Adding-an-Exclusion-for-Downloads-Folder-in-Windows-Security-Settings.jpg)
6. Browse to the**Downloads** folder or any other location you have set as a download location.

 By following the above steps, you will prevent Windows Defender from scanning the files in the Downloads folder, so if Windows Defender is causing the error even when the file you're downloading is safe, you won't encounter it again.

## 5\. Add the File to Windows Defender's Whitelist

 Microsoft's Windows Defender Firewall is notorious for blocking even completely safe files and processes from downloading or running. Therefore, you may need to allow it in Windows Defender exclusively to download the file. Here's how you can do it:

1. In Windows Search (**Win + S**), search for**"Windows Security"** and open it.
2. In the left-sidebar, click**Virus & threat protection** .
3. In the right-hand pane, click on**Protection history** .  
![Checking Protection History under Virus and Threat Protection in Windows Security App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Image-7-Checking-Protection-History-under-Virus-and-Threat-Protection-in-Windows-Security-App.jpg)
4. Locate and expand the blocked app or file.
5. Expand the**Actions** dropdown menu and click**Allow** .

 This time, you should not encounter any errors when downloading the file. If the problem persists, tweak Chrome's security settings.

## 6\. Temporarily Disable Microsoft Defender Firewall

 Excluding the Downloads folder and adding the file to Microsoft Defender's whitelist should prevent the Windows built-in security scanner from scanning this file and allow it to download successfully. However, if you still encounter the same error, we suggest temporarily disabling the Microsoft Defender firewall.

 If you have never disabled the firewall before, refer to our guide on [how to disable the Microsoft Defender Firewall in Windows 11](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) .

 Don't forget to turn on Microsoft Defender after downloading the file, as it's the first line of defense against malware and threats your computer faces.

## 7\. Tweak Chrome's Security Settings

 If Chrome still considers your file a threat, you should disable its Safe Browsing feature in its settings. Here are the steps you need to follow:

1. Click on**three vertical dots** in the top-right corner and go to**Settings** .
2. In the left-sidebar, click**Privacy and security** .
3. In the right-hand pane, click**Security** .  
![Go to Security Settings in Chrome](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/tweaking-chromes-security-settings-by-clicking-on-security-option-under-the-privacy-and-security-tab-in-chrome-settings.jpg)
4. Check the circle for**No Protection (not recommended)** .  
![check the ircle for no protection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/checking-the-circle-for-no-protection-not-recommended-option-in-chromes-security-settings.jpg)

 You might be able to download files successfully by disabling Safe Browsing, but once you disable it, Chrome's built-in security won't protect you from malware and malicious downloads. Therefore, after downloading your files, be sure to turn Safe Browsing back on again.

## 8\. Tweak the Windows Registry Editor

 Does Windows Defender still block downloading the completely safe file? If so, let's tweak Registry Editor to force antivirus to stop scanning downloaded attachments. You can do that by following the below steps:

1. In Windows Search, type**"Registry Editor"** and open the program.
2. In path explorer, copy and paste the following path:  
HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies\
3. Right-click on the**Policies** key, select**New > Key** and name it**"Attachments."**  
![Tweaking Windows Registry Editor by Renaming Newly Created Registry Key under Policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Image-11-Tweaking-Windows-Registry-Editor-by-Renaming-Newly-Created-Registry-Key-under-Policies.jpg)
4. Right-click on**Attachments** and navigate to**New > DWORD (32-bit) Value** .  
![Creating the DWORD (32-bit) String Value in the Attachments Key in Registry Editor App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Image-12-Creating-the-DWORD-(32-bit)-String-Value-in-the-Attachments-Key-in-Registry-Editor-App.jpg)
5. Rename the newly created String Value to**ScanWithAntiVirus** .
6. Double-click on**ScanWIthAntiVirus** and enter**"1"** under**Value data** .  
![Changing the Value Data by Double-clicking on Newly Renamed ScanWIthAntiVirus String Value in Registry Editor App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Image-13-Changing-the-Value-Data-by-Double-clicking-on-Newly-Renamed-ScanWIthAntiVirus-String-Value-in-Registry-Editor-App.jpg)
7. Click**OK** .

 Because tweaking Registry Editor can be tricky and harmful, we recommend you ask an expert to perform this fix if you don't know how to edit Registry Editor manually.

## 9\. Run a Malware Scan

 If you still experience the problem under discussion after applying the fixes listed above, you should ensure your device has not been infected, causing it to behave abnormally. It's possible for malware hidden inside your device to prevent Chrome from downloading files. So, you should make sure that's not the case here.

 Run a malware scan to rule out this possibility. While you can use any third-party antivirus software to scan your device for threats, we recommend [running Microsoft Defender's offline scan](https://www.makeuseof.com/how-to-remove-malware-using-microsoft-defenders-offline-scan/) for complete virus removal.

## Get Rid of the "Failed - Virus Detected" Error in Chrome for Windows

 Our guide should have helped you scan your file and bypass the "Failed - Virus detected" error message if it was a false positive. If none of the fixes have worked for you and the error persists, you'd be better off switching browsers. Among the popular choices, Firefox, Edge, and Opera GX are highly regarded.

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
<li><a href="https://some-techniques.techidaily.com/2024-approved-how-to-switch-between-normal-and-picture-in-picture-views-in-youtube/"><u>2024 Approved  How to Switch Between Normal and Picture In Picture Views in Youtube</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-and-discord-fixing-the-deadly-js-error-quickly/"><u>Win 11 and Discord: Fixing The Deadly JS Error Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-razer-device-absence-in-win-1011-via-synapse/"><u>Addressing Razer Device Absence in Win 10/11 via Synapse</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/vimeo-chapter-how-to-add-chapters-to-vimeo-video/"><u>Vimeo Chapter  How to Add Chapters to Vimeo Video?</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-switching-picture-in-picture-on-macios-effortlessly/"><u>In 2024, Switching Picture-in-Picture on Mac/iOS Effortlessly</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-retweeted-gifs-iphoneandroid-step-by-step-savings/"><u>In 2024, Retweeted Gifs  IPhone/Android Step-by-Step Savings</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-battlenet-accessibility-on-1011-systems/"><u>Unlocking Battle.net Accessibility on 10/11 Systems</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-diy-video-setups-perfect-self-portraits-for-youtubers/"><u>[Updated] In 2024, DIY Video Setups  Perfect Self-Portraits for YouTubers</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-the-ultimate-guide-to-gaming-intro-makers-for-windows-and-mac-free-paid-and-everything-in-between-for-2024/"><u>Updated The Ultimate Guide to Gaming Intro Makers for Windows and Mac Free, Paid, and Everything In Between for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/disarming-the-windows-11-afc-error-camera-app-solution/"><u>Disarming the Windows 11 AFC Error: Camera App Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/taskers-edge-enigma-hidden-processes/"><u>Tasker's Edge Enigma: Hidden Processes?</u></a></li>
<li><a href="https://windows11.techidaily.com/deleting-persistent-epic-launcher-without-hurdles-in-w11/"><u>Deleting Persistent Epic Launcher Without Hurdles in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-memory-integrity-on-windows-11-methods-77/"><u>Unlocking Memory Integrity on Windows 11: Methods 7/7</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-speed-of-microsoft-edge-on-win10plus11/"><u>Enhancing Speed of Microsoft Edge on Win10+11</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-which-is-superior-for-screen-recording-obs-studio-or-fraps-for-2024/"><u>[Updated] Which Is Superior for Screen Recording – OBS Studio or Fraps for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-msvcr110dll-absence-a-solution-walkthrough/"><u>Tackling the Msvcr110.dll Absence: A Solution Walkthrough</u></a></li>
<li><a href="https://windows11.techidaily.com/black-friday-extravaganza-save-big-612-forever-win10/"><u>Black Friday Extravaganza: Save Big - $6.12 Forever Win10</u></a></li>
<li><a href="https://windows11.techidaily.com/utilizing-windows-widgets-for-real-time-resource-tracking/"><u>Utilizing Windows Widgets for Real-Time Resource Tracking</u></a></li>
<li><a href="https://windows11.techidaily.com/time-tinkering-tools-top-windows-programs-for-date-adjustment/"><u>Time Tinkering Tools: Top Windows Programs for Date Adjustment</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/2024-approved-linuxs-leading-picks-for-sound-recording-an-in-depth-look-at-top-tools-and-proven-techniques/"><u>2024 Approved Linuxs Leading Picks for Sound Recording An In-Depth Look at Top Tools & Proven Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11s-printer-interface-max-48-chars/"><u>Unlocking Windows 11'S Printer Interface (Max 48 Chars)</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-is-a-sim-network-unlock-pin-get-your-vivo-y36-phone-network-ready-by-drfone-android/"><u>In 2024, What Is a SIM Network Unlock PIN? Get Your Vivo Y36 Phone Network-Ready</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-continuous-play-fixing-fall-guys-errors-in-windows-os/"><u>Ensuring Continuous Play: Fixing Fall Guys Errors in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-solve-missing-dll-rockalldlldll-error/"><u>Steps to Solve Missing DLL: Rockalldll.dll Error</u></a></li>
<li><a href="https://windows11.techidaily.com/dodging-unsupported-issue-in-windows-5-fixes/"><u>Dodging 'Unsupported' Issue in Windows: 5 Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/unplugged-no-more-six-methods-to-restore-functioning-network-hardware-on-your-pc/"><u>Unplugged No More: Six Methods to Restore Functioning Network Hardware on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-window-11-safety-with-best-in-class-password-protectors/"><u>Elevating Window 11 Safety with Best-in-Class Password Protectors</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-print-guide-to-making-your-powerpoint-shine-on-a-windows-system/"><u>The Ultimate Print Guide to Making Your PowerPoint Shine on a Windows System</u></a></li>
<li><a href="https://windows11.techidaily.com/why-sudo-is-revolutionizing-windows-systems/"><u>Why Sudo Is Revolutionizing Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-reset-account-lockout-counter-post-failed-sign-in-attempts/"><u>Adjusting Reset Account Lockout Counter Post-Failed Sign-In Attempts</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-unwanted-hibernation-usb-tweaks-for-windows-11/"><u>Avoid Unwanted Hibernation - USB Tweaks for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-windows-update-fixes-for-error-0x800736cc/"><u>Streamlining Windows Update Fixes for Error 0X800736CC</u></a></li>
<li><a href="https://windows11.techidaily.com/accurate-assessment-of-system-resources-in-windows-11/"><u>Accurate Assessment of System Resources in Windows 11</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-procuring-immersive-dragon-roar-soundscape-for-2024/"><u>Updated Procuring Immersive Dragon Roar Soundscape for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-the-path-into-windows-11-insider-group/"><u>Discovering the Path Into Windows 11 Insider Group</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-service-disruptions-with-steam-windows-11-style/"><u>Addressing Service Disruptions with Steam, Windows 11 Style</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-stream-apple-iphone-11-pro-max-to-computer-drfone-by-drfone-ios/"><u>How to Stream Apple iPhone 11 Pro Max to Computer? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-updating-obstacles-a-compreeher-guide-to-fixes/"><u>Clearing Updating Obstacles: A Compreeher Guide to Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/delaying-windows-11-shutdown-managing-ongoing-processes/"><u>Delaying Windows 11 Shutdown: Managing Ongoing Processes</u></a></li>
</ul></div>
