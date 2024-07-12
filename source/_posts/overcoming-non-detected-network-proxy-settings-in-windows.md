---
title: Overcoming Non-Detected Network Proxy Settings in Windows
date: 2024-07-11T21:15:12.723Z
updated: 2024-07-12T21:15:12.724Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Non-Detected Network Proxy Settings in Windows
excerpt: This Article Describes Overcoming Non-Detected Network Proxy Settings in Windows
keywords: WiFi Anonymity Overcome,Bypassing Windows Proxies,Fixing Unseen Proxy Errors,Resolve Hidden Network Configs,Disable Untraceable IP,Address Non-Proxied Windows,Eliminate Stealthed Firewall
thumbnail: https://thmb.techidaily.com/412d065764cb0ba50733f600b7a0dabb6c2d4fd117a0cc25cd8642bbb251c9cc.png
---

## Overcoming Non-Detected Network Proxy Settings in Windows

 After having Windows troubleshoot a network error for you, you might have come across this message:

> Windows could not automatically detect this network's proxy settings.

 What does this mean, and how do you fix it? Let's take a look at Windows' proxy settings and the steps to repair this.

## 1\. Reboot Your Computer and Router

 Before you launch into any specific troubleshooting, it's always a good idea to restart your equipment first. There's a chance that this will clear up your issue in a few moments.

 Because this error is usually related to misconfigured settings on one computer, restarting your router likely won't have an effect. But it's still an [important network troubleshooting step](http://www.makeuseof.com/tag/7-simple-steps-diagnose-network-problem/) for problems of any kind.

 If the problem hasn't fixed itself after you reboot your computer and router, continue on with the more detailed steps.

## 2\. Review Proxy Settings in Windows

 Because this issue is related to your Windows proxy settings, that's a sensible first place to check. To access proxy settings in Windows 10, open**Settings** , select the**Network & Internet** category, and switch to the**Proxy** tab on the left sidebar. This is in the same place on Windows 11, except**Proxy** is an item in the list instead of appearing on a sidebar.

 Here you'll see a list of options related to proxy servers. If you don't use a proxy (as is the case for most home users), make sure that**Use a proxy server** near the bottom is turned off. Leave**Automatically detect settings** on if it is already.

![Windows 10 Proxy Settings Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/03/Windows-10-Proxy-Settings-Menu.png)

 For those who do connect with a proxy, such as people in a business or school environment, you might want to check with your system administrator to make sure you have the correct proxy details here. They'll be able to speak to any issues specific to your network.

 After this, try reconnecting to the network again and getting online. If you still get the error, turn off**Automatically detect settings** in the proxy options and try once more.

### What's a Proxy Server?

​​​​​​

 We don't want to bore you with the details while you try to fix this proxy setting issue. However, it's useful to understand [the basics of what a proxy actually is](http://www.makeuseof.com/tag/what-is-a-proxy-server/) and why Windows can run into problems with it.

 Essentially, a proxy server acts as a middleman between your computer and the internet. Instead of you connecting directly to the internet, you connect to the proxy server, which grabs information from the internet for you.

 These are most common in business and school use, where system administrators use them for security and efficiency. It's very unlikely that you would use a proxy server on your home network, unless you specifically set one up. This is why in most home cases, you should clear any proxy settings that might exist when you run into this issue.

## 3\. Run the Network Adapter Troubleshooter

 When you right-click on the network connection icon in your System Tray and choose to troubleshoot, it runs the**Internet Connections** troubleshooter. This is what results in the "Windows could not detect proxy settings" error. But there's another network troubleshooter you can run that might provide more help.

 On Windows 10, open**Settings** again and visit**Update & Security > Troubleshoot** , followed by**Additional troubleshooters** . On Windows 11, go to **Settings > System > Troubleshoot > Other troubleshooters** .

 Choose**Network Adapter** from the list and walk through the troubleshooter. As seasoned Windows users know, these troubleshooters don't always fix your problem, but it's still worth a try.

## 4\. Auto-Obtain IP Address and DNS Info

 As it turns out, there aren't many troubleshooting steps specific to proxy servers. We'll share more tips below, but bear in mind that the troubleshooting for this looks similar to [fixing the "No Internet Access" Windows error](https://www.makeuseof.com/tag/no-internet-access-fix-windows/) from this point on.

 While not technically related to your proxy settings, misconfigured IP address or DNS settings can cause this error too. To check these on Windows 10, browse to**Settings > Network & Internet > Status** . Click the**Change adapter options** button in the list to see all your network connections, then double-click on the one you're using.

 Here, click the**Properties** button and double-click**Internet Protocol Version 4** in the list. Make sure you have both**Obtain an IP address automatically** and**Obtain DNS server address automatically** selected. Misconfigured settings here will prevent you from getting online.

![Windows IP Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2018/01/Windows-IP-Settings.jpg)

 On Windows 11, go to**Settings > Network & internet** and choose**Wi-Fi** or**Ethernet** depending on the connection you're using. Then click your network name. If you don't see**Automatic (DHCP)** next to both**IP assignment** and**DNS server assignment** , click the**Edit** button next to both and set them to this value.

## 5\. Update or Roll Back Your Network Driver

 An outdated network driver may lead to connection problems. Similarly, you might have recently installed a botched update for your network driver. In either case, replacing the driver could clear the proxy message issue.

 To look at this, right-click on the Start button and choose**Device Manager** to open that utility. Expand the**Network adapters** section and double-click on the connection you use.

 Then, on the**Driver** tab, you can choose**Roll Back Driver** to uninstall the latest update and return to the previous one. Use this if you started experiencing this issue after updating—though it might not be available in all cases.

![Windows 10 Device Manager Update Roll Back](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2019/04/Windows-10-Device-Manager-Update-Roll-Back.png)

 Choose**Update Driver** and you can check for new updates over the internet. Since this likely won't find anything, you'll need to [manually update your drivers](https://www.makeuseof.com/tag/find-replace-outdated-windows-drivers/) by downloading them from the manufacturer.

## 6\. Reset Network Configuration via the Command Prompt

 Windows offers many network troubleshooting tools through the Command Prompt. A few quick commands can often clear up your issue in moments. If you're still having trouble at this point, right-click the Start button again and open a Command Prompt, PowerShell, or Windows Terminal window with administrator rights.

 Then input the following commands followed by**Enter** , one at a time. They will reset various network functions of your computer, such as clearing out old connection data and getting a new IP address from the router:

`netsh winsock reset`

`netsh int ip reset`

`ipconfig /release`

`ipconfig /renew`

`ipconfig /flushdns`

## 7\. Review Firewall, VPN, and Antivirus Software

![Windows 10 firewall settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/01/firewall-settings.png)

 You should next make sure you don't have a firewall, VPN, or security suite interfering with your network connection. Perhaps your chosen software had an update that changed an option you weren't aware of, or you just installed a new app that changed proxy settings for some reason.

 Try disabling your firewall, VPN, and antivirus software one at a time, then see if the error goes away. If it does, the issue lies with one of those apps. You'll need to configure them to avoid interfering with regular network activity.

## 8\. Scan for Malware

 Some malware can continually mess with your proxy settings to prevent you from getting online. If you run into the "Windows could not detect this network's proxy settings" message every time you reboot, you may be a victim of this.

 You should thus run a scan with a trusted anti-malware app, like [Malwarebytes](https://www.anrdoezrs.net/links/7251228/type/dlg/sid/UUmuoUeUpU36219/https://try.malwarebytes.com/get-premium/?cjdata=MXxOfDB8WXww&c=cj&s=4112715&k=14452255&utm%5Fsource=cj&utm%5Fmedium=aff&utm%5Fcontent=14452255&utm%5Fcampaign=AFF-CJ%5F4112715&tracking=cj&x-wts=cj&x-affid=4112715&ADDITIONAL%5FAFFID=cj-4112715&cjevent=c8d316be6e5311ee835c008b0a82b82a&clickid=c8d316be6e5311ee835c008b0a82b82a&pid=cj%5Fint) . This will detect any malware running on your system and get rid of it. If the scan finds any infections, take the recommended action and see if your connection works normally again.

## 9\. Utilize a Restore Point

[The System Restore feature in Windows](http://www.makeuseof.com/tag/system-restore-factory-reset-work-windows-10/) lets you return to a previous point at which your computer was working normally. If your issues started recently, you should try this to see if you can go back in time.

 To access it, head to**Settings > System > About** . On the right sidebar in Windows 10, click**System protection** (expand the Settings window horizontally if you don't see it). On Windows 11, you'll see**System protection** next to**Related links** in the**Device specifications** box once you've expanded it.

 In the resulting**System Properties** dialog box on the**System Protection** tab, click**System Restore** to open a new window. Windows will walk you through choosing a restore point and confirming the operation. Of course, if your computer hasn't created any restore points, you can't use this feature.

![choose a specific restore point and click on next](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/02/click-on-a-restore-point.png)

 Note that using a restore point will remove any programs and drivers you've installed since making that restore point. You can click**Scan for affected programs** on a restore point to see what effect it will have. Using a System Restore won't affect any of your personal files.

## 10\. Reset Your Network Settings

![Windows 10 Network Reset](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2019/04/Windows-10-Network-Reset.png)

 After trying everything above, you should resort to a full reset of your network configuration in Windows. You've already spent a lot of time working on this, and a reset should clear whatever persistent problem is blocking your connection with this "cannot detect proxy settings" error.

 Thankfully, Windows 10 makes it easy to reset your whole configuration. Open**Settings > Network & Internet** . On the**Status** tab, find**Network reset** at the bottom and click it. On Windows 11, this is under **Settings > Network & internet > Advanced network settings > Network reset** instead.

 Be aware that this will remove all network information from your computer, so you'll need to reconnect to saved networks again. If you're OK with this, click**Reset now** . Your computer will perform the reset, then restart.

## Windows Could Not Detect Proxy Settings: Resolved

 Now you know what to do when Windows cannot detect proxy settings. All network errors are frustrating, but you should be able to clear this one up without much work. It's most important to make sure that you have a proxy turned off (if you don't use one) or configured properly (if you do use one).

 Otherwise, some standard network troubleshooting should have you all patched up and ready to get back online.


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
<li><a href="https://windows11.techidaily.com/7-key-adjustments-for-obs-studio-connection-woes-on-pcs/"><u>7 Key Adjustments for OBS Studio Connection Woes on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/alleviating-video-driver-failures-on-win1110-os/"><u>Alleviating Video Driver Failures on Win11/10 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/7-ways-to-fix-the-application-made-too-many-requests-error-0x80860010-on-windows/"><u>7 Ways to Fix the Application Made Too Many Requests Error (0X80860010) on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-unavailable-display-settings-in-nvidia-software/"><u>Addressing Unavailable Display Settings in Nvidia Software</u></a></li>
<li><a href="https://windows11.techidaily.com/clandestine-data-storage-zip-archives-in-image-files-for-windows-enthusiasts/"><u>Clandestine Data Storage: ZIP Archives in Image Files for Windows Enthusiasts</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/digital-music-vault-youtube-edition/"><u>Digital Music Vault - YouTube Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/6-underestimated-downsides-of-saving-on-activation-keys/"><u>6 Underestimated Downsides of Saving on Activation Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/4-ways-to-check-your-network-adapter-speed-on-windows/"><u>4 Ways to Check Your Network Adapter Speed on Windows</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-download-and-preserve-tiktok-videos-free-of-apples-watermark/"><u>2024 Approved  Download and Preserve TikTok Videos Free of Apple's Watermark</u></a></li>
<li><a href="https://windows11.techidaily.com/best-slate-companions-selecting-top-7-windows-tabs/"><u>Best Slate Companions: Selecting Top 7 Windows Tabs</u></a></li>
<li><a href="https://windows11.techidaily.com/bluetooth-recovery-guide-9-steps-to-patch-up-your-pcs-link/"><u>Bluetooth Recovery Guide: 9 Steps to Patch Up Your PC's Link</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-unlock-chromebooks-full-potential-install-linux/"><u>Updated In 2024, Unlock Chromebooks Full Potential Install Linux</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-inaccuracy-of-power-usage-predictor-on-win-11-devices/"><u>Addressing Inaccuracy of Power Usage Predictor on Win 11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-slowdowns-in-gpsvc-windows-errors/"><u>Bypassing Slowdowns in GPSVC Windows Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/amplifying-security-the-art-of-longer-pin-codes-in-win11/"><u>Amplifying Security: The Art of Longer Pin Codes in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-taskbar-efficiency-win11-guide/"><u>Boosting Taskbar Efficiency: Win11 Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/circumventing-endless-credential-entry-alerts-in-windows/"><u>Circumventing Endless Credential Entry Alerts in Windows</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/creating-impactful-youtube-conclusion/"><u>Creating Impactful YouTube Conclusion</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-your-typing-on-win-1011-top-7-tricks-revealed/"><u>Accelerate Your Typing on WIN 10/11: Top 7 Tricks Revealed</u></a></li>
<li><a href="https://windows11.techidaily.com/augmenting-user-interface-windows-embellished-by-portables/"><u>Augmenting User Interface: Windows, Embellished by Portables</u></a></li>
<li><a href="https://windows11.techidaily.com/a-deeper-dive-into-user-experience-revamping-windows-11-widgets/"><u>A Deeper Dive Into User Experience: Revamping Windows 11 Widgets</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-realme-gt-neo-5-se-drfone-by-drfone-virtual/"><u>In 2024, 9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Realme GT Neo 5 SE | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/5-steps-to-reclaim-your-windows-daylight-look/"><u>5 Steps to Reclaim Your Windows' Daylight Look</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-2024-approved-unleash-your-creative-potential-top-audio-editing-software-for-pros/"><u>Updated 2024 Approved Unleash Your Creative Potential Top Audio Editing Software for Pros</u></a></li>
<li><a href="https://windows11.techidaily.com/adding-disk-usage-viewers-to-windows-menu-bar/"><u>Adding Disk Usage Viewers to Windows Menu Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-vagrant-boot-failures-on-win11plusvmware/"><u>Addressing Vagrant Boot Failures on Win11+VMware</u></a></li>
<li><a href="https://windows11.techidaily.com/circumventing-unyielding-power-switches-on-windows-11/"><u>Circumventing Unyielding Power Switches on Windows 11</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-how-to-use-aiseesoft-screen-recorder/"><u>[Updated] In 2024, How to Use Aiseesoft Screen Recorder</u></a></li>
<li><a href="https://windows11.techidaily.com/5-ways-to-check-your-device-uptime-on-windows-11/"><u>5 Ways to Check Your Device Uptime on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/building-artificially-inspired-pictures-in-paint-cocreator-win11/"><u>Building Artificially-Inspired Pictures in Paint Cocreator (Win11)</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-unlock-virtual-worlds-top-10-pc-games-for-ultimate-vr-experience/"><u>[New] 2024 Approved  Unlock Virtual Worlds  Top 10 PC Games for Ultimate VR Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/chrome-freezing-woes-on-win11-try-these-swift-solutions/"><u>Chrome Freezing Woes on Win11? Try These Swift Solutions.</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/the-ultimate-guide-to-premium-business-sims-of-24-mobilepc-for-2024/"><u>The Ultimate Guide to Premium Business Sims of '24 (Mobile/PC) for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-pitfalls-of-unknown-not-initialized-disks-on-windows/"><u>Avoiding Pitfalls of Unknown Not Initialized Disks on Windows</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-action-archetypes-choosing-the-best-7-first-person-shooters/"><u>In 2024, Action Archetypes  Choosing the Best 7 First-Person Shooters</u></a></li>
<li><a href="https://windows11.techidaily.com/asus-vs-rog-the-battle-for-the-ultimate-portable-pc/"><u>ASUS Vs. ROG: The Battle for the Ultimate Portable PC?</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-unlock-your-device-icloud-dns-bypass-explained-and-tested-plus-easy-alternatives-on-apple-iphone-xs-by-drfone-ios/"><u>In 2024, Unlock Your Device iCloud DNS Bypass Explained and Tested, Plus Easy Alternatives On Apple iPhone XS</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-leveraging-communication-to-enhance-interview-success/"><u>2024 Approved  Leveraging Communication to Enhance Interview Success</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-life360-on-windows-pc-for-xiaomi-redmi-note-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Life360 on Windows PC For Xiaomi Redmi Note 12 Pro+ 5G? | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-streamlining-group-chats-on-skype-for-dual-os-environments-for-2024/"><u>[New] Streamlining Group Chats on Skype for Dual OS Environments for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-get-creative-with-zero-cost-16-best-free-video-editing-software/"><u>Updated In 2024, Get Creative with Zero Cost 16 Best Free Video Editing Software</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-obstacles-downloading-icloud-on-windows/"><u>Bypassing Obstacles: Downloading iCloud on Windows</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-maximize-android-screen-brightness/"><u>In 2024, Maximize Android Screen Brightness</u></a></li>
<li><a href="https://windows11.techidaily.com/amplify-windows-efficiency-with-innovative-layouts/"><u>Amplify Windows Efficiency with Innovative Layouts</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-samsung-galaxy-xcover-7-location-by-number-drfone-by-drfone-virtual-android/"><u>How to Track Samsung Galaxy XCover 7 Location by Number | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/changing-onedrive-storage-address-in-windows-10/"><u>Changing OneDrive Storage Address in Windows 10</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-realme-c53-drfone-by-drfone-virtual-android/"><u>How to Get and Use Pokemon Go Promo Codes On Realme C53 | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-audience-connection-mastering-the-art-of-viewpoint-based-youtube-reaction-vids-2-pov-method/"><u>[New] 2024 Approved  Audience Connection – Mastering the Art of Viewpoint-Based YouTube Reaction Vids (2 POV Method)</u></a></li>
<li><a href="https://windows11.techidaily.com/adding-comprehensive-firewall-tools-to-windows-11s-menu-bar/"><u>Adding Comprehensive Firewall Tools to Windows 11’S Menu Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-list-of-fixes-for-disappearing-windows-in-windows-11/"><u>A Comprehensive List of Fixes for Disappearing Windows in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-launch-times-for-windows-11-apps/"><u>Accelerate Launch Times for Windows 11 Apps</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-metaverse-quest-10-innovative-sci-fi-films-worldwide-travels/"><u>In 2024, Metaverse Quest  10 Innovative Sci-Fi Films Worldwide Travels</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-olympic-snowboard-x-sprint-highlights-22/"><u>[Updated] Olympic Snowboard X Sprint Highlights '22</u></a></li>
<li><a href="https://windows11.techidaily.com/1719338165732-exploring-phonelinkexe-its-role-and-risks-in-windows-98/"><u>Exploring PhoneLink.exe: Its Role and Risks in Windows 9/8</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-non-operational-state-of-ccleaner-on-win1011-systems/"><u>Addressing Non-Operational State of CCleaner on Win10/11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/a-closer-look-at-windows-sound-system-segregation/"><u>A Closer Look at Windows' Sound System Segregation</u></a></li>
<li><a href="https://windows11.techidaily.com/christmas-tech-surprises-through-microsofts-marketplace/"><u>Christmas Tech Surprises Through Microsoft's Marketplace</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-integrating-zoom-and-fb-live-effortlessly/"><u>[New] Integrating ZOOM and FB Live Effortlessly</u></a></li>
<li><a href="https://windows11.techidaily.com/4-ways-to-fix-the-windows-powershell-cannot-be-loaded-because-running-scripts-is-disabled-error/"><u>4 Ways to Fix the Windows PowerShell Cannot Be Loaded Because Running Scripts Is Disabled Error</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-mastering-instagram-borders-a-list-of-top-quality-apps-and-tools/"><u>[Updated] In 2024, Mastering Instagram Borders  A List of Top-Quality Apps & Tools</u></a></li>
</ul></div>
