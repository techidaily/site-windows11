---
title: Insider Tips for Manual Windows Security Scanning
date: 2024-09-09T11:58:21.001Z
updated: 2024-09-10T11:58:21.001Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Insider Tips for Manual Windows Security Scanning
excerpt: This Article Describes Insider Tips for Manual Windows Security Scanning
keywords: Windows Security Protips,Secure WinScan Guide,Manual WinDefend,Insider WinScan Tricks,Safeguard WinOS,Defendant for Windows,Windows Defense Tips
thumbnail: https://thmb.techidaily.com/dda7f892a14e315c0bfa7414c2e13f2432b695f38c3a471ddf15f2d24d24baec.jpg
---

## Insider Tips for Manual Windows Security Scanning

 Keyloggers, cryptojackers, spyware, and rootkits are all types of malware that hackers use to infect victims' devices. While some of these infections let hackers remotely connect to the victim's computer, others monitor the person's keystrokes, use the system's resources, or simply spy on the targeted person's activity.

 If you suspect that your Windows device might have been hacked, here are some practical steps you can take to check that.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115948/19272" target="_top" id="2115948">
  <img src="//a.impactradius-go.com/display-ad/19272-2115948" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115948/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Before We Get Started…

 Before investigating whether your device has been compromised, close all third-party and Windows applications. This will reduce the entries Task Manager or other[any alternatives to the Task Manager](https://www.makeuseof.com/tag/5-powerful-alternatives-windows-task-manager/) you might be using and allow you to effectively identify suspicious connections established on your computer.

 Afterward,[run a malware scan on your device using Microsoft Defender](https://www.makeuseof.com/how-to-remove-malware-using-microsoft-defenders-offline-scan/) or any reliable third-party antivirus software you usually use. This step will help you detect and automatically remove light infections inside your device, and they won't distract you when searching for more severe infections or security breaches.

 Once you have closed down all nonessential processes and carried out a malware scan, you can start looking for any malicious programs lurking on your system.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134248/18498" target="_top" id="2134248">
  <img src="//a.impactradius-go.com/display-ad/18498-2134248" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134248/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Inspect Your Device for Spyware or Hacking Attempts

 In the modern era, malware infections are usually programmed to actively (but secretly) operate on the victim's computer. For instance,[cryptojackers](https://www.makeuseof.com/what-is-cryptojacking-how-to-detect-it/) use victims' computer resources for crypto mining, keyloggers gather login credentials by monitoring keystrokes, and spyware tracks users' activity in real-time and shares it with the hackers.

 Each of these malware types relies on a remote connection to the hacker's server where the data is sent, the mining software runs, or whatever else the hacker is trying to accomplish. By identifying those suspicious connections established on our device, we can determine whether our device has actually been compromised.

### 1\. Check for Suspicious Connections

 You can check for suspicious connections on your computer in several ways, but the method we'll show you will use a built-in utility in Windows called the Command Prompt. Here's how you can find the remote connections set up with your device using Command Prompt:

1. Type**"Command Prompt"** in Windows Search.
2. Right-click the**Command Prompt** app and click**Run as administrator** .
3. Simply type the following command and hit**Enter** .  
netstat -ano

![Run Netstat-ano Command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/1-run-netstat-ano-command-in-command-prompt.jpg)

 The above command will show you all the TCP connections the apps, programs, and services have established to remote hosts.

 Pay attention mainly to the**State** column, where you'll find three main terms:**Established** ,**Listening** , and**Time\_Wait** . From these three, focus on the connections whose state identifies as**Established** . The**"Established"** state indicates a real-time connection between your computer and the remote IP address.

![Find the Suspicious Process with Established Connection in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/2-find-the-suspicious-process-with-established-connection-in-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2121335/18498" target="_top" id="2121335">
  <img src="//a.impactradius-go.com/display-ad/18498-2121335" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2121335/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Don't panic if you see a lot of established connections. Most of the time, these connections are made to a company server whose services you use, like Google, Microsoft, etc. However, you need to analyze each of these connections separately. This will help you determine if there are suspicious connections being made to a hacker's server.

 Do not close the Command Prompt; we will use the netstat information in the next steps.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137202/26400" target="_top" id="2137202">
  <img src="//a.impactradius-go.com/display-ad/26400-2137202" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137202/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Analyze Any Connections That Seem Suspicious

Here's how you can analyze the suspicious connections:

1. Copy the IP address from the**Foreign Address** column in the**Command Prompt** .
2. Go to a popular IP location lookup site, such as IPLocation.net.
3. Paste your copied IP address here and click the**IP Lookup** button.  
![click on the ip lookup button after pasting the copied ip address on ip location website](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/click-on-the-ip-lookup-button-after-pasting-the-copied-ip-address-on-ip-location-website.jpg)

<!-- affiliate ads begin -->
<span id="1983473">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983473.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983473">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983473.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983473%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983473/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 This website will provide you with information about the IP address. Check the ISP and organization that use this IP address. If the IP address belongs to a well-known company whose services you use, such as Google LLC, Microsoft Corporation, etc., there is nothing to worry about.

 However, if you see a suspicious company listed here whose services you don't use, there is a good chance that someone is spying on you. Thus, you will need to identify the process or service using this address for remote connection to ensure it isn't malicious.

### 3\. Find and Analyze Any Malicious Processes

 To locate the malicious program scammers may have been using to snoop on your device, you have to identify the associated process. Here's how to find it:

1. Note the**PID** next to the suspicious**Established** connection in Command Prompt.  
![Note the PID Next to the Suspicious Established Connection in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/4-note-the-pid-next-to-the-suspicious-established-connection-in-command-prompt.jpg)
2. Open Task Manager. (See the[different ways to open Task Manager in Windows 10](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) and[11](https://www.makeuseof.com/how-to-access-task-manager-on-windows-11/) )
3. Go to the**Details** tab.
4. Click the**PID column** to sort processes according to their PIDs.
5. Find the process with the same**PID** that you noted down earlier.  
![Find the Process with Relevant PID in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/5-find-the-process-with-relevant-pid-in-windows-task-manager.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettiit.sjv.io/c/5597632/2114267/17093" target="_top" id="2114267">
  <img src="//a.impactradius-go.com/display-ad/17093-2114267" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettiit.sjv.io/i/5597632/2114267/17093" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If the process belongs to a third-party service that you frequently use, you don't need to close it. However, you should still verify that this process belongs to the company you believe it does,as a hacker can hide their malicious processes under the guise of a malicious one. So, right-click on the suspicious process and select**Properties** .

![Select Properties by Right-clicking on the Suspicious Process in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/6-select-properties-by-right-clicking-on-the-suspicious-process-in-windows-task-manager.jpg)

 Then, navigate to the**Details** tab for more information about the process.

![Navigate to Details Tab in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/7-navigate-to-details-tab-in-windows-task-manager.jpg)

 If there is any discrepancy in process details or the process itself seems suspicious, it is best to remove the associated program.

### 4\. Remove Any Suspicious Programs

 To identify and remove the malicious apps behind these suspicious processes, follow these steps:

1. Right-click the shady process and select**Open file location** .  
![Click on Open File Location by Right-clicking on Malicious Process in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/8-click-on-open-file-location-by-right-clicking-on-malicious-process-in-windows-task-manager.jpg)
2. Once again, ensure the file is not associated with Windows or any other critical application.
<!-- affiliate ads begin -->
<span id="1983549">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983549.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983549">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983549.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983549%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983549/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. If you're sure it's malware, right-click it and delete it.  
![Delete the Suspicious File After Locating it in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/9-delete-the-suspicious-file-after-locating-it-in-windows-file-explorer.jpg)

<!-- affiliate ads begin -->
<span id="1983471">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983471.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983471">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983471.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983471%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983471/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134228/18498" target="_top" id="2134228">
  <img src="//a.impactradius-go.com/display-ad/18498-2134228" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134228/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 5\. Take Professional Help When Necessary

 Hopefully, following the above process will help you detect and remove the malicious program, thereby preventing hackers from spying on or stealing your personal information.

 However, you should be aware that hackers can conceal their malware from netstat output by programming it that way. Likewise, they can code the program so it does not appear in Task Manager. Seeing no suspicious connections in the netstat output or not finding the suspicious process in Task Manager doesn't mean your device is safe.

 Therefore, if you see signs of a hacked device in your system, such as high resource consumption in Task Manager, system slowdowns, unknown apps getting installed, Windows Defender turning off frequently, the creation of suspicious new user accounts, and similar, you should consult a professional. Only then can you be sure that your device is completely secure.

## Don't Let Hackers Spy on You for Long

 Microsoft consistently updates the Windows operating system to make it more secure, but hackers still find loopholes and hack into Windows devices. Hopefully, our guide will help you identify if any suspicious hacker is monitoring your activity. If you follow the tips correctly, you'll be able to remove the suspicious app and disconnect the connection to the hacker's server.

 If you're still suspicious and don't want to risk your precious data, you should seek professional assistance.


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
<li><a href="https://hardware-help.techidaily.com/download-hp-spectre-x360-drivers-for-windows/"><u>[Download] HP Spectre X360 Drivers For Windows</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/n-2024-evaluating-earnings-from-one-million-youtube-watches/"><u>[New] In 2024, Evaluating Earnings From One Million YouTube Watches</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-sharpen-your-snaps-the-elite-eight-of-grids-and-frames/"><u>[New] Sharpen Your Snaps  The Elite Eight of Grids and Frames</u></a></li>
<li><a href="https://article-files.techidaily.com/new-standout-literary-book-videos-for-2024/"><u>[New] Standout Literary Book Videos for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-leveraging-advanced-techniques-in-360-video-on-fb-live/"><u>[Updated] 2024 Approved  Leveraging Advanced Techniques in 360 Video on FB Live</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-comprehensive-directory-of-inexpensive-stock-images-for-2024/"><u>[Updated] Comprehensive Directory of Inexpensive Stock Images for 2024</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/canons-pocket-prodigy-an-insight-into-sx740-hs/"><u>Canon's Pocket Prodigy - An Insight Into SX740 HS</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/chuckle-hour-on-tiktok-joke-and-riddle-roundup-for-laughter-lovers-for-2024/"><u>Chuckle Hour on TikTok  Joke & Riddle Roundup for Laughter Lovers for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-7-innovative-fixes-for-rename-issue-in-win-11/"><u>Expert Advice: 7 Innovative Fixes for Rename Issue in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/exposing-6-incongruent-features-in-windows-11/"><u>Exposing 6 Incongruent Features in Windows 11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/from-theory-to-reality-exploring-chatgpts-applications/"><u>From Theory to Reality: Exploring ChatGPT's Applications</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-lost-data-from-galaxy-a15-4g-by-fonelab-android-recover-data/"><u>How to recover lost data from Galaxy A15 4G?</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-a-infinix-smart-8-pro-easily-by-drfone-android/"><u>How To Unlock a Infinix Smart 8 Pro Easily?</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-poco-x5-pro-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Poco X5 Pro to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-secure-file-management-using-powertoys/"><u>Mastery of Secure File Management Using PowerToys</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-efficiency-prioritizing-terminal-over-others/"><u>Maximizing Efficiency: Prioritizing Terminal Over Others</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-imessage-on-non-ios-devices-tips-and-tricks/"><u>Navigating iMessage on Non-iOS Devices: Tips and Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/no-expense-spared-try-these-5-top-tier-driver-upgrades/"><u>No Expense Spared? Try These 5 Top-Tier Driver Upgrades</u></a></li>
<li><a href="https://windows11.techidaily.com/optimal-web-access-a-comparative-study-of-browser-ram-use/"><u>Optimal Web Access: A Comparative Study of Browser RAM Use</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-audacity-audio-error-in-windows-1111/"><u>Overcoming Audacity Audio Error in Windows 11/11</u></a></li>
<li><a href="https://windows11.techidaily.com/proactive-defense-7-steps-to-thwart-windows-hackers/"><u>Proactive Defense: 7 Steps to Thwart Windows Hackers</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-for-erroneous-0x80246007-in-win11-uptime/"><u>Quick Fix for Erroneous 0X80246007 in Win11 Uptime</u></a></li>
<li><a href="https://driver-download.techidaily.com/quick-setup-with-zebra-gk42d-driver-software-download-now/"><u>Quick Setup with Zebra GK42d Driver Software – Download Now</u></a></li>
<li><a href="https://windows11.techidaily.com/realign-windows-clock-stop-time-discrepancy-woes/"><u>Realign Windows Clock: Stop Time Discrepancy Woes</u></a></li>
<li><a href="https://techtrends.techidaily.com/regles-de-remboursement-des-logiciels-winxdvd-chez-digiarty-guide-complet/"><u>Règles De Remboursement Des Logiciels WinXDVD Chez Digiarty - Guide Complet</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstating-credible-power-consumption-forecasts-on-windows-11/"><u>Reinstating Credible Power Consumption Forecasts on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-operative-bin-icon-on-windows-11/"><u>Restoring Operative Bin Icon on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/seamlessly-incorporate-gallery-view-into-file-explorer/"><u>Seamlessly Incorporate Gallery View Into File Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/show-more-pins-strategies-for-start-screen/"><u>Show More Pins: Strategies for Start Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/sidestep-w11s-onedrive-error-code-def5/"><u>Sidestep W11's OneDrive Error Code DEF5</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-qbittorrent-transfer-from-one-windows-to-another/"><u>Steps for qBittorrent Transfer From One Windows to Another</u></a></li>
<li><a href="https://windows11.techidaily.com/strategic-approaches-to-shutting-down-your-computer/"><u>Strategic Approaches to Shutting Down Your Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-your-win-based-software-overcome-too-many-requests/"><u>Streamlining Your Win-Based Software: Overcome Too Many Requests</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-application-launch-in-windows-11/"><u>Swift Application Launch in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/triumph-over-glitches-the-ultimate-guide-for-eradicating-error-0x800700e9-on-xbox-game-pass-and-windows-11/"><u>Triumph Over Glitches: The Ultimate Guide for Eradicating Error 0X800700E9 on Xbox Game Pass & Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-itunes-performance-issues-on-windows-pcs/"><u>Unlocking iTunes Performance Issues on Windows PCs</u></a></li>
</ul></div>
