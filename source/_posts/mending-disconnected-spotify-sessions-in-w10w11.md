---
title: Mending Disconnected Spotify Sessions in W10/W11
date: 2024-08-22T21:34:20.804Z
updated: 2024-08-23T21:34:20.804Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mending Disconnected Spotify Sessions in W10/W11
excerpt: This Article Describes Mending Disconnected Spotify Sessions in W10/W11
keywords: Fixing Spotify Pause,Resume Playback Error,Session Reconnect Issue,Stream Restore Trick,Music Sync W10/W11,Disconnected Audio Fix,Uninterrupted Spotify Play
thumbnail: https://thmb.techidaily.com/2b68f106433b091c014f2083746f9820ace97ab74d68e3b5f340250f5652e1ee.jpg
---

## Mending Disconnected Spotify Sessions in W10/W11

 Spotify is one of the best Windows apps for streaming and downloading music. However, some Spotify users can’t stream and download music with that app because of error code 4\. Error code 4 is a Spotify connectivity issue with a message that says, “No internet connection detected.” Yet, users can usually still open and view websites when that issue arises.

 Users who need to fix error code 4 can’t utilize the Spotify app online. That means things like radio and streaming don’t work. This is how you can fix Spotify error code 4 on a Windows 10 or 11 PC.

## 1\. Run the Flush DNS Command

![The flushdns command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/flushdns-command.jpg)

 One confirmed solution for error code 4 is to flush the DNS cache. The DNS (Domain Name System) cache is a local storage repository of IP addresses on your PC. Your web browser retrieves DNS lookup data from that cache.

 Clearing the DNS cache will flush out and refresh its data. You can clear the DNS cache by running a flush DNS command in Command Prompt or Run. Check out our guide about[how to flush the DNS](https://www.makeuseof.com/flush-dns-cache-windows-11/) on Windows for further details about how to apply this solution.

## 2\. Select the HTTP Option in Spotify

 Spotify includes alternative proxy settings you can select to configure how that app connects with the Internet. Changing the proxy option to**HTTP** can reputedly resolve error code 4\. You can select the**HTTP** option in Spotify as follows:

1. Open your Spotify app.
2. Click the username button at the top of Spotify to view its menu.
3. Select**Settings** to view Spotify’s options.  
![The Settings menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-settings-option.jpg)
4. Click the**Proxy type** drop-down menu to select**HTTP** .  
![The HTTP option in Spotify](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/http-option.jpg)
5. Then select**Restart App** to apply.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Change DNS Server Settings

 Error code 4 often occurs because Spotify can’t recognize your PC’s default DNS server set by your ISP. In such a scenario, the app can’t load required online resources correctly, resulting in error 4\. Many users have addressed that issue by changing their PCs’ DNS server to the universally recognized Google DNS.

 Our guide to[changing the DNS server in Windows](https://www.makeuseof.com/windows-11-alternate-ways-change-dns-server-settings/) post includes step-by-step guidelines for how to apply this solution via the Control Panel and Settings among other methods. You’ll need to set the preferred and alternative DNS server settings to Google addresses. Input**8.8.8.8** for the preferred DNS server and**8.8.4.4** for the alternative DNS setting.

![DNS server settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dns-server-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
<!-- affiliate ads end -->
## 4\. Tweak the Registry

 Some Spotify users have confirmed tweaking a DWORD value in the registry resolved error 4 for them. Those users changed the EnableActiveProbing DWORD’s value, which was set to 0 (disabled) on their PCs. These are the steps for fixing error code 4 by editing the registry:

1. Press the search box’s**Win + S** hotkey.
2. To locate the Registry Editor, enter**regedit** inside the**Type here to search** box.
3. Select Registry Editor inside the search tool.
4. Next, click within the address bar at the top of Registry Editor to clear the current location in it.
5. Go to the Internet key by inputting the following path:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\NlaSvc\Parameters\Internet`
6. Then right-click the**EnableActiveProbing** DWORD and select**Modify** .  
![The Modify option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/modify-option.jpg)
7. If**EnableActiveProbing** is set to**0** , clear the**Value data** box. Then input**1** inside that data box.  
![The Edit DWORD window for the EnableActiveProbing DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/edit-dword-window.jpg)
8. Select**OK** to save the new**EnableActiveProbing** value.
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Exclude Spotify From Your Antivirus Software

 You might need to fix error code 4 because of antivirus software interference with the Spotify app. Both third-party antivirus apps and Windows Security can feasibly block Spotify’s internet connectivity. You can select to exclude Spotify from antivirus protection by adding it to an exception (trusted software) list most security apps include.

![Windows Security's app exclusion settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-security-s-exclusion-list-settings.jpg)

 Our article about[setting Windows Security exclusions](https://www.makeuseof.com/windows-11-security-exclusions/) includes instructions for adding software to that app’s exception list. If you’re utilizing a third-party antivirus tool, look for an exclusion list within its settings tab. The antivirus software’s website will also likely include guidelines for how to use its exclusion list.

<!-- affiliate ads begin -->
<span id="1993652">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Turn Off the Windows Defender Firewall

 Windows Defender Firewall is a component of Windows Security for filtering network traffic. Turning that firewall off could resolve error 4 if Spotify isn’t allowed through it. You can turn off WDF as outlined in our guide to[disabling the Windows Defender firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) .

![The turn off firewall settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-firewall-s-allow-app-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Should this solution work, it’s not a good idea to keep the firewall disabled. Open Windows Defender Firewall’s allowed app list and select the Spotify checkboxes there to permit that app through it. Check out our how to guide about[allowing apps through the Windows firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) for further details.

![The firewall's allowed apps settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/allowed-app-settings.jpg)

 Of course, numerous standalone third-party firewalls can block Spotify much the same. If you have installed a third-party firewall, try disabling it to see if that resolves error 4\. Then add Spotify to its allowed apps and turn the firewall back on if it does.

## 7\. Reinstall Spotify

 Reinstalling Spotify could resolve unknown reasons for error code 4 arising and will at least ensure you’re using the latest app version. However, note that reinstalling the app will wipe your Spotify playlists. Back up (export) any playlists you wish to keep so you can restore them. Then reinstall Spotify with the following steps:

1. Press the Start menu button and select**All apps** (in Windows 11).
2. Scroll down to the Spotify app on the Start menu.
3. Right-click Spotify and select**Uninstall** .  
![Spotify's Uninstall option on the Start menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-start-menu-s-uninstall-option.jpg)
4. If you’ve installed the desktop Spotify app, Programs and Features will open from which you can select the software and click**Uninstall** . Users who’ve installed the UWP Spotify app can select**Uninstall** on a confirmation prompt.
5. Then open the[Spotify Windows](https://www.spotify.com/us/download/windows/) download page.
6. Click**Download** to get the installer for the desktop Spotify app.  
![The Download Spotify option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/download-option.jpg)
7. Open the Explorer file manager along with the folder in which Spotify downloaded.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
8. Double-click the**SpotifySetup.exe** file to bring up the setup wizard and install Spotify.

 Another option is to install the Spotify UWP (Universal Windows Platform) app on Microsoft Store. Click the**Get it From Microsoft Store** button on the linked Spotify download page to bring up that app’s MS store page. Then click the**Get in Store app** \>**Open Microsoft Store** options and select**Get** to install the UWP app.

## Enjoy Spotify Music Online Again

 There’s a very good chance at least one Windows troubleshooting method in this guide will resolve Spotify error code 4 on your PC. They’re user-confirmed fixes that address the most common reasons for error 4 arising. With that app connection issue sorted, you can then enjoy all the best online music and radio Spotify has to offer again.

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
<li><a href="https://extra-tips.techidaily.com/new-advanced-tips-for-maximum-digital-storage/"><u>[New] Advanced Tips for Maximum Digital Storage</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-from-basics-to-advanced-the-hand-trackers-playbook/"><u>[New] From Basics to Advanced  The Hand Tracker's Playbook</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-achieving-financial-freedom-joshis-youtube-tactics/"><u>[Updated] Achieving Financial Freedom  Joshi’s YouTube Tactics</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-mastering-instagram-engagement-the-5-key-strategies-for-influencers-today/"><u>2024 Approved  Mastering Instagram Engagement  The 5 Key Strategies for Influencers Today</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/create-a-compelling-title-using-action-words-or-powerful-adjectives-that-pique-users-curiosity-and-encourage-clicks-while-staying-true-to-the-content-of-the8/"><u>Create a Compelling Title Using Action Words or Powerful Adjectives that Pique Users' Curiosity and Encourage Clicks While Staying True to the Content of the Page.</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-empty-sections-of-navigation-view/"><u>Fixing Empty Sections of Navigation View</u></a></li>
<li><a href="https://windows11.techidaily.com/forewarned-is-forearmed-top-8-windows-11-no-nos-for-neophytes/"><u>Forewarned Is Forearmed: Top 8 Windows 11 No-Nos for Neophytes</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-restore-functional-drag-and-drop-in-windows-11/"><u>Guide: Restore Functional Drag-and-Drop in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/harnessing-powertoys-for-seamless-international-mouse-usage/"><u>Harnessing PowerToys for Seamless International Mouse Usage</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-spur-microsoft-edge-speed-in-windows-1011/"><u>How to Spur Microsoft Edge Speed in Windows 10/11</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-detailed-guide-of-ispoofer-for-pogo-installation-on-xiaomi-redmi-note-12-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Detailed guide of ispoofer for pogo installation On Xiaomi Redmi Note 12 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-shh-9-secrets-of-simple-stock-editing/"><u>In 2024, Shh! 9 Secrets of Simple Stock Editing</u></a></li>
<li><a href="https://extra-support.techidaily.com/inside-secrets-to-stunning-photography-with-canva-for-2024/"><u>Inside Secrets to Stunning Photography with Canva for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mastering-the-repair-of-x3daudiodll-error-essential-troubleshooting-techniques/"><u>Mastering the Repair of X3DAudio.dll Error: Essential Troubleshooting Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-overcoming-windows-activation-fault-error-0x803f700f/"><u>Mastery of Overcoming Windows Activation Fault: Error 0X803F700f</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-enhances-windows-11-with-ai-taskbar-companion-for-effortless-management/"><u>Microsoft Enhances Windows 11 with AI Taskbar Companion for Effortless Management</u></a></li>
<li><a href="https://windows11.techidaily.com/modifying-account-lockout-period-post-failed-logon/"><u>Modifying Account Lockout Period Post-Failed Logon</u></a></li>
<li><a href="https://windows11.techidaily.com/onoff-switch-controlling-windows-energy-saving-mode/"><u>On/Off Switch: Controlling Windows' Energy-Saving Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-0xc00000f-issue-on-your-pc-easily/"><u>Overcoming 0Xc00000f Issue on Your PC Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-printer-connection-glitches-in-windows/"><u>Overcoming Printer Connection Glitches in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/pro-tips-selecting-superior-windows-11-drawers/"><u>Pro Tips: Selecting Superior Windows 11 Drawers</u></a></li>
<li><a href="https://windows11.techidaily.com/race-the-rate-unveiling-windows-techniques-for-measuring-ethernet-speed/"><u>Race the Rate: Unveiling Windows Techniques for Measuring Ethernet Speed</u></a></li>
<li><a href="https://windows11.techidaily.com/reconnecting-solo-side-headphones-to-windows-os/"><u>Reconnecting Solo Side Headphones to Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/resolve-system-hiccups-with-these-10-windows-tools/"><u>Resolve System Hiccups with These 10 Windows Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-regedit-absent-on-windows-systems/"><u>Resolving Regedit Absent on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-security-fault-in-1011-edition/"><u>Resolving Windows Security Fault in 10/11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-your-computer-with-windows-hello-fingerprint/"><u>Securing Your Computer with Windows Hello Fingerprint</u></a></li>
<li><a href="https://windows11.techidaily.com/starting-diagnostics-five-quick-steps-in-windows/"><u>Starting Diagnostics: Five Quick Steps in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/tech-guide-extending-windows-menu-options-in-xp-7-8-and-10/"><u>Tech Guide: Extending Windows Menu Options in XP, 7, 8 & 10</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-essential-guide-for-avi-to-gif-editing-a-quick-filmora-workflow-on-windows-and-macos-for-2024/"><u>The Essential Guide for AVI-to-GIF Editing  A Quick Filmora Workflow on Windows & macOS for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-eradicate-the-abrupt-termination-error-in-roblox-games/"><u>Tips to Eradicate the Abrupt Termination Error in Roblox Games</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-invalid-system-name-in-windows-11/"><u>Troubleshooting Invalid System Name in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-restrictions-of-secure-boot-and-tpm-using-rufus/"><u>Unlocking the Restrictions of Secure Boot & TPM Using Rufus</u></a></li>
<li><a href="https://windows11.techidaily.com/why-do-computers-have-a-windows-batch-file/"><u>Why Do Computers Have a Windows Batch File?</u></a></li>
<li><a href="https://windows11.techidaily.com/win-your-way-out-of-secure-boot-stumbles-with-these-fixes/"><u>Win Your Way Out of Secure Boot Stumbles with These Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-advancements-what-the-new-update-brings-in/"><u>Windows 11 Advancements: What the New Update Brings In</u></a></li>
<li><a href="https://windows11.techidaily.com/workaround-to-avoid-discord-autostarting-on-pc/"><u>Workaround to Avoid Discord Autostarting on PC</u></a></li>
</ul></div>
