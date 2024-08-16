---
title: Rectifying 0X800700E9 Error Within Xbox Game Pass & Windows 11
date: 2024-08-15T15:28:05.160Z
updated: 2024-08-16T15:28:05.160Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Rectifying 0X800700E9 Error Within Xbox Game Pass & Windows 11
excerpt: This Article Describes Rectifying 0X800700E9 Error Within Xbox Game Pass & Windows 11
keywords: Xbox Game Pass Error Fix,Xbox Error 0X800700e9,Xbox-Windows Game Crash,Fixing 0X800700E9 in Windows,Resolve Xbox Error on PC,Xbox Sync Issue Windows 11,Troubleshoot Xbox Game Pass Error
thumbnail: https://thmb.techidaily.com/5323ab269b6d5447358ffbce683d20a8b0db809b59cc59254c5cb25869dff46a.jpg
---

## Rectifying 0X800700E9 Error Within Xbox Game Pass & Windows 11

 The Xbox Game Pass is a popular Microsoft subscription service for games. However, some users encounter a 0x800700e9 error when they try to download and install Xbox Game Pass titles via the Xbox app or Microsoft Store. The 0x800700e9 error code message says “Something unexpected happened,” which provides no clue as to how to resolve that issue.

 Users can’t download and install Xbox Game Pass content because of error 0x800700e9\. However, you can fix error 0x800700e9 with these potential resolutions.

## 1\. Run the Microsoft Store App Troubleshooter

 The Windows Store App troubleshooter might help fix the error 0x800700e9\. This is how you can access the Windows Store App troubleshooter in Windows 11:

1. Use one of the many [ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Click the**Troubleshoot** box that has a spanner icon.
3. Next, click**Other-troubleshooters** to access the Settings app’s list of troubleshooting tools.
4. Select**Run** for activating the Windows Store Apps.  
![The Run button for the Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-button-for-windows-store-apps-troubleshooter.jpg)
5. Apply any suggestions the troubleshooter provides.

 The Windows 10 troubleshooters are available within the**Update & Security** category of Settings. Click the**Troubleshoot** tab in that category and select**Additional troubleshooters** . Then you can select Windows Store Apps from there and click**Run** to access the tool.

## 2\. Turn Delivery Optimization On in Settings

 Delivery Optimization is a service that enables Windows Update downloads from other PCs. Error 0x800700e9 often arises when Delivery Optimization is disabled in Windows. You can turn on Delivery Optimization via Settings like this:

1. Open the**Windows Update** tab in Settings.
2. Click**Advanced options** to view more settings.
3. Select the**Delivery Optimization** navigation option.  
![The Delivery Optimization navigation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/delivery-optimization-navigation-option.jpg)
<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Turn on the**Allow downloads from other PCs** option to enable Delivery Optimization.  
![The Allow downloads from other PCs option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/allow-downloads-from-other-pcs-option.jpg)
5. Click the**Devices on my local network** radio button.

 You can enable Delivery Optimization in Windows 10’s Settings app much the same. However, you’ll need to select the**Windows Update** category. Then click the**Deliver Optimization** tab in the**Windows Update** category to access and turn on the same**Allow downloads from other PCs** setting.

<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Enable the Delivery Optimization and BITS Services

 Some Xbox Game Pass users have resolved error 0x800700e9 by enabling and running the Delivery Optimization and BITS services. You can enable and start those services via that app as follows:

1. To access Run, press**Win + R** .
2. Type**services.msc** inside Run’s**Open** command box.
3. Select**OK** to open Services.
4. Double-click the Delivery Optimization service.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/services-window2.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
5. Select**Start** if it’s not running.
6. Click**Automatic** on Delivery Optimization’s**Startup type** menu.  
![The Delivery Optimization Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/delivery-optimization-properties-window.jpg)
7. Select**Apply** \>**OK** to save the service’s new settings.
8. Repeat steps four to seven for the Background Intelligent Transfer service.

 If the services are already running, try restarting them. Right-click the services and select their**Stop** options. Then you can start those services again by right-clicking them and selecting**Restart** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
## 4\. Enable Delivery Optimization via the Windows Registry

 If the above methods didn't work for you, try enabling Delivery Optimization service by editing the registry. You can back up the registry or set up a restore point before editing the registry if you want to be extra careful. To apply this potential solution, edit the**DoSvc** key like this:

1. First, bring up Registry Editor, which you can open with one of the methods in our guide on [how to open Regedit](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Click inside the address bar at the top of Registry Editor and erase the current key location.
3. Input this**DoSvc** key location in the address bar and hit**Return** :  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\DoSvc`  
![The DoSvc key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dovsc-key.jpg)
4. Select the**DoSvc** key, and right-click the**Start** DWORD to select**Modify** .  
![The Modify option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/modify-option.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
5. Input**3** in the**Value** box and click**OK** .  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/start-dword-key.jpg)
6. Exit Regedit, and restart the PC.

## 5\. Reset or Repair the Xbox App

 Many users go through the Xbox app to get at their Xbox Game Pass titles on Windows. As such, you might be able to fix error 0x800700e9 by selecting**Reset and Repair** options for the Xbox app inside Settings.

 Check out our guide on [resetting apps in Windows 11 and 10](https://www.makeuseof.com/windows-reset-app/) to clear the Xbox app’s data. The**Repair** option for the Xbox app in Settings is available just above its**Reset** button.

![The Reset option for the Xbox app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reset-option.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
## 6\. Reset the Microsoft Store Cache

 A corrupted Microsoft Store cache data can cause download and installation issues to arise for apps available on Microsoft’s online store. So, resetting the Store’s cache could be another potential solution for the 0x800700e9 error. Try resetting Microsoft Store’s cache in the following steps:

1. Bring up the Windows Search by clicking the magnifying glass or**Search** box on your taskbar.
2. Type**WSReset.exe** within the search box to find that Run command file.
3. Click**WSReset.exe** to run the command.  
![The wsreset.exe Run command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/wsreset-exe-command.jpg)
4. Wait for MS Store to open automatically, and then try downloading Xbox Game Pass titles again.

## 7\. Reinstall the Microsoft Store

 Reinstalling the Microsoft Store can fix deeper issues with that app that could be causing error 0x800700e9\. Although you can’t select to uninstall Microsoft Store, you can still reinstall that app with a PowerShell command. Here are the steps for reinstalling the Microsoft Store via PowerShell:

1. Bring up Run with the**Win + R** keyboard shortcut, and input**PowerShell** within the text box.
2. Right-click PowerShell to bring up a context menu, and select the**Run as administrator** option.
3. Execute this PowerShell command for reinstalling Microsoft Store:  
`Get-AppxPackage -allusers Microsoft.WindowsStore | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall Microsoft Store command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reinstall-microsoft-store-command.jpg)
4. Wait for the command to finish, and then exit the command app.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## 8\. Reset Your Network

![The Network reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-reset-option.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Error 0x800700e9 can also sometimes occur because of network issues. Performing a network reset is a good way to troubleshoot issues in this area; however, do note that this will restore your network components to their factory defaults and erase your Wi-Fi and Ethernet connections.

 Have a look at our [how to reset your network settings on Windows](https://www.makeuseof.com/reset-network-settings-windows-11/) guide for details about how to apply this troubleshooting method.

## Enjoy Your Xbox Game Pass Games Again

 Fortunately, you don’t have to cancel your Xbox Game Pass subscription because of error 0x800700e9\. A lot of users have fixed this installation issue for Xbox Game Pass titles with the resolutions in this guide.

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
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-unveiling-hidden-potential-edit-wonders-on-snapchat-app/"><u>[New] 2024 Approved  Unveiling Hidden Potential  Edit Wonders on Snapchat App</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-developing-intriguing-video-segments-for-channels/"><u>[New] Developing Intriguing Video Segments for Channels</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-leveraging-the-power-of-visual-storytelling-in-fb-covers/"><u>[New] In 2024, Leveraging the Power of Visual Storytelling in FB Covers</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-innovating-photography-the-art-of-crafting-effective-gopro-time-lapse/"><u>[New] Innovating Photography  The Art of Crafting Effective GoPro Time-Lapse</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-transformative-role-of-luts-in-visual-artistry/"><u>[New] The Transformative Role of LUTs in Visual Artistry</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-ninja-level-strategies-for-instagram-video-magic/"><u>[Updated] 2024 Approved  Ninja-Level Strategies for Instagram Video Magic</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-elevate-your-banner-game-mastering-visual-branding-techniques-for-2024/"><u>[Updated] Elevate Your Banner Game  Mastering Visual Branding Techniques for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-photoshop-grading-made-simple-for-everyone/"><u>[Updated] Photoshop Grading Made Simple for Everyone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-how-to-download-and-share-tiktok-videos-on-iphone-no-watermark-present/"><u>2024 Approved  How to Download and Share TikTok Videos on iPhone, No Watermark Present</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-how-to-maximize-impact-with-onestreams-streaming-solutions/"><u>2024 Approved  How to Maximize Impact with OneStream's Streaming Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/5-strategies-for-resolving-the-no-support-windows-error/"><u>5 Strategies for Resolving the No-Support Windows Error</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-shared-printer-issues-on-windows-11/"><u>Addressing Shared Printer Issues on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/best-windows-laptops-a-forward-looking-2024-review/"><u>Best Windows Laptops: A Forward-Looking 2024 Review</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-task-monitor-in-win-11-accelerating-real-time-updates/"><u>Boosting Task Monitor in Win 11: Accelerating Real-Time Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/briskly-boost-printer-functionality/"><u>Briskly Boost Printer Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-missing-sign-in-screens-in-windows-11/"><u>Bypassing Missing Sign-In Screens in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/confronting-windows-search-failure-a-fixers-manual/"><u>Confronting Windows Search Failure: A Fixer's Manual</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-computer-recovery-top-10-tactics/"><u>Conquering Computer Recovery: Top 10 Tactics</u></a></li>
<li><a href="https://iphone-location.techidaily.com/does-itools-virtual-location-not-work-on-apple-iphone-6ipad-drfone-by-drfone-virtual-ios/"><u>Does iTools virtual location not work On Apple iPhone 6/iPad? | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/experience-enhanced-efficiency-with-chatgpts-desktop-version-over-website/"><u>Experience Enhanced Efficiency with ChatGPT's Desktop Version Over Website</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-code-0x800700e1-problems-in-windows-11/"><u>Fixing Code 0X800700E1 Problems in Windows 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/forgot-pattern-lock-heres-how-you-can-unlock-itel-p40plus-pattern-lock-screen-by-drfone-android/"><u>Forgot Pattern Lock? Heres How You Can Unlock Itel P40+ Pattern Lock Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-to-erase-steam-dns-information-on-pc/"><u>Guidelines to Erase Steam DNS Information on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-through-a-windows-systems-exception-breaking-point-issue/"><u>Guiding Through a Windows System's Exception Breaking Point Issue</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-3-ways-of-how-to-get-someones-apple-id-off-apple-iphone-14-pro-without-password-by-drfone-ios/"><u>In 2024, 3 Ways of How to Get Someones Apple ID Off Apple iPhone 14 Pro without Password</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-enhance-your-shorts-fresh-and-original-thumbnails-with-minimal-effort/"><u>In 2024, Enhance Your Shorts  Fresh and Original Thumbnails with Minimal Effort</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-premier-portals-to-retro-playstation-gaming-on-your-desktop/"><u>In 2024, Premier Portals to Retro PlayStation Gaming on Your Desktop</u></a></li>
<li><a href="https://tech-hub.techidaily.com/mastering-new-languages-with-the-aid-of-chatgpt-plus/"><u>Mastering New Languages with the Aid of ChatGPT Plus</u></a></li>
<li><a href="https://windows11.techidaily.com/1719278005537-mastery-of-solutions-for-non-operational-wwinplusp-in-pc/"><u>Mastery of Solutions for Non-Operational WWin+P in PC.</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/navigating-online-broadcasts-expertise-in-onestream-use-for-2024/"><u>Navigating Online Broadcasts  Expertise in OneStream Use for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11s-multi-task-abilities-efficiently/"><u>Navigating Windows 11'S Multi-Task Abilities Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/never-disable-wins-11-notifications-why/"><u>Never Disable Wins 11 Notifications: Why?</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-streamlining-your-workflow-importing-and-exporting-videos-in-adobe-premiere-2023/"><u>New 2024 Approved Streamlining Your Workflow Importing and Exporting Videos in Adobe Premiere 2023</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-in-2024-harnessing-the-power-of-suspenseful-music-for-compelling-and-memorable-score-development/"><u>New In 2024, Harnessing the Power of Suspenseful Music for Compelling and Memorable Score Development</u></a></li>
<li><a href="https://windows11.techidaily.com/perfect-pixels-for-every-window-11-display/"><u>Perfect Pixels for Every Window 11 Display</u></a></li>
<li><a href="https://windows11.techidaily.com/premium-collection-winning-windows-dsswitch-emulators-list/"><u>Premium Collection: Winning Windows DS/Switch Emulators List</u></a></li>
<li><a href="https://windows11.techidaily.com/purging-protection-logs-on-windows-1011-with-ease/"><u>Purging Protection Logs on Windows 10/11 with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/revive-hidden-desktop-icons-on-the-latest-windows/"><u>Revive Hidden Desktop Icons on the Latest Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-disabled-remove-option-for-pin-access-control/"><u>Reviving Disabled 'Remove' Option for PIN Access Control</u></a></li>
<li><a href="https://windows11.techidaily.com/six-secrets-to-spinning-pictures-in-w11-os/"><u>Six Secrets to Spinning Pictures in W11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/solve-non-responsive-function-keys-in-windows-11/"><u>Solve: Non-Responsive Function Keys in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-ensure-optimal-functionality-of-add-ons-in-windows-os/"><u>Strategies to Ensure Optimal Functionality of Add-Ons in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-prevent-microsoft-teams-freeze-in-ws11ws10/"><u>Strategies to Prevent Microsoft Teams Freeze in WS11/WS10</u></a></li>
<li><a href="https://windows11.techidaily.com/the-financial-engine-behind-windows-11/"><u>The Financial Engine Behind Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-offline-warriors-guide-to-microsoft-onedrive/"><u>The Offline Warrior's Guide to Microsoft OneDrive</u></a></li>
<li><a href="https://tech-hub.techidaily.com/transform-your-fitness-journey-setting-and-reaching-goals-with-chatgpt-guidance/"><u>Transform Your Fitness Journey: Setting and Reaching Goals with ChatGPT Guidance</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-windows-onedrive-error-for-immediate-folder-addition/"><u>Unraveling Windows OneDrive Error for Immediate Folder Addition</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-over-connection-issues-dissolving-ea-errors/"><u>Winning Over Connection Issues: Dissolving EA Errors</u></a></li>
</ul></div>
