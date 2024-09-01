---
title: Tackling the Troubled Waters of Outlook's WinError X
date: 2024-08-31T22:12:34.606Z
updated: 2024-09-01T22:12:34.606Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling the Troubled Waters of Outlook's WinError X
excerpt: This Article Describes Tackling the Troubled Waters of Outlook's WinError X
keywords: Outlook Error Handling,WinError Solutions,Microsoft Office Troubleshoot,Windows Application Fixes,Outlook Crash Prevention,Email Client Issue Resolution,XboxWinError Guide
thumbnail: https://thmb.techidaily.com/acc116e7f31959c80ee46ff620abee605b240216ab77712435cda97b5c53cabd.jpg
---

## Tackling the Troubled Waters of Outlook's WinError X

 The Mail app error 0x80072746 often occurs when users try to access their newly received emails, and it indicates network-related issues within Windows. This error message typically points towards a problem with the mail server or the network connection.

 Below, we take a look at the different troubleshooting methods that can help fix this issue for good.

## 1\. Allow svchost.exe in the Firewall

 The 0x80072746 error in the Mail app commonly occurs when a third-party firewall interferes with a critical Windows program called svchost.exe.

 This process is responsible to host various essential services necessary for the proper functioning of your Windows operating system. Among these services, the Mail app heavily relies on svchost.exe to establish network connections and download messages.

 If you have installed a third-party security program on your computer, there is a possibility that it is mistakenly blocking svchost.exe. This might be preventing the Mail app from fetching or sending emails, leading to the 0x80072746 error.

 To address this issue, you can check your firewall settings and whitelist svchost.exe. Alternatively, you can [temporarily disable the security program](https://www.makeuseof.com/windows-features-error-0x80071a90/)and check if that fixes the problem.

![Disable antivirus in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-antivirus-windows.jpg)

 It's worth noting that the exact steps of performing this action can vary depending on the specific program you are using. Typically, this information is available in the application settings of the app.

## 2\. Modify VPN Settings

 Active VPNs can also interfere with the Mail app's ability to establish network connections, leading to the problem at hand.

 If you are using a VPN on your computer, you can try the following steps to troubleshoot the issue:

* **Disconnect from the VPN**: Temporarily disable the VPN and then try loading messages in the Mail app again. If this fixes the problem, it implies that VPN was causing the problem.
* **Whitelist Mail app or email server**: Launch the VPN settings and look to whitelist the Mail app or email server’s IP address to prevent VPN from interfering with the program’s network connections.
* **Modify VPN protocols or settings**: If it is essential to use the VPN while using the Mail app, you can modify the protocol and check if that makes any difference.

 Here is how you can modify the VPN settings to resolve the Mail app error:

1. Press the **Win** \+ **I** keys together to open the Settings app.
2. Choose **Network & Internet** \> **VPN**.  
![VPN settings in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/vpn-settings-windows.jpg)
3. Enable the **Allow VPN over metered network** option.  
![Allow VPN over metered network in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/vpn-over-metered-network.jpg)
4. Now, head over to the "Related settings" section and choose **Change adapter options**.
5. Right-click on your LAN (Wi-Fi) connectivity and choose **Properties** from the context menu.
6. Select **Internet Protocol Version 6 (TCP/PV6)** and click **OK** to save the changes.

 You can now close the Settings app and check if the issue is resolved.

<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
## 3\. Set Up Your Account Manually

 Another reason behind the Mail error 0x80072746 is incorrect server settings and incompatibility with specific email providers, which typically occurs when you rely on the automatic setup process.

 You can eliminate these potential issues with the automatic configuration process by setting up your account manually.

 Therefore, if you previously configured your Mail account using the automatic setup process, you might want to try setting it up manually this time in order to bypass any errors or conflicts.

 Here is how you can do that:

1. Launch the Mail client and click on the **gear icon** at the bottom.
2. Choose **Manage Accounts**.  
![Manage accounts option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/manage-accounts.jpg)
3. Select the problematic email and choose **Delete account from this device** from the options available.  
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
![Delete the account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/delete-mail-app.jpg)
4. Confirm your action in the next window.
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Once the email account is removed, launch the official website of your email provider and copy the manual settings for IMAP. If these settings are not available, choose POP3\.

1. Now, head back to the Mail client and launch the settings.
2. Head over to the Manage Account section and choose **Add account**.  
![Add account option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/add-account.jpg)
3. Scroll down and choose **Advanced Setup**.  
![Choose Advanced setup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/advanced-setup-option.jpg)
4. Click on **Internet email** and enter the manual settings you copied earlier.  
![Click Internet email](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/internet-email-option.jpg)
5. Finally, click on **Sign in** and check if the issue is resolved.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Update the Mail App

 Your Mail app might also be outdated, which is preventing it from being fully compatible with the latest email server configurations and security protocols, leading to the error at hand.

 To check if this is the case, you can head over to Microsoft Store and check for the pending updates that might be available for the Mail app. If you find any, take your time to install them and then check if the Mail app can display emails.

 Follow these steps to proceed:

1. Click on the **Microsoft Store icon** in the taskbar to launch the program.
2. Choose the **Library icon** in the bottom left pane.
3. In the following window, click on the **Get updates** button. This should display all the available updates for the installed apps. MS Store will begin to download them automatically.  
![The Get updates button in MS Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-get-updates-button.jpg)
4. Wait for the updates to download and check if the problem is resolved.
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 While you are at it, we also recommend installing any system updates that might be available in the Settings app.

## 5\. Fix Corruption Issues Within the Mail App

 If updating the application did not help, there are also some other fixes that can help you resolve any corruption issues within the Mail app that might be leading to the problem. This involves [repairing and resetting the Mail application](https://www.makeuseof.com/mail-app-cant-get-mail-windows/).

 The Repair option attempts to fix any damaged or missing files that might be contributing to the error, while the Reset option will restore the default, error-free state of the application. It is important to note, however, that while these solutions are effective at fixing the underlying problem, you are likely to lose your settings and preferences within the Mail app.

## Multiple Ways to Fix the Windows Mail App

 Encountering issues with the Mail app can be incredibly frustrating, especially if you rely on it for your important work. Hopefully, the solutions listed above will help you fix the 0x80072746 error once and for all.

 To avoid problems like this from occurring in the future, we recommend keeping your Mail app up-to-date and whitelisting it in the firewall as well as the VPN.

 Below, we take a look at the different troubleshooting methods that can help fix this issue for good.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-friendly.techidaily.com/new-heartfelt-cinematic-experiences-for-hopeful-hearts/"><u>[New] Heartfelt Cinematic Experiences for Hopeful Hearts</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-boosting-instagram-video-speed-onlinemobile/"><u>[New] In 2024, Boosting Instagram Video Speed Online/Mobile</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-navigating-the-path-to-an-official-instagram-business-page/"><u>[New] In 2024, Navigating the Path to an Official Instagram Business Page</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-the-definitive-path-from-twitter-video-to-creatively-crafted-gifs/"><u>[New] In 2024, The Definitive Path From Twitter Video to Creatively Crafted GIFs</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-uncharted-visual-narrative-evaluation-and-parallel-proposals-for-2024/"><u>[New] Uncharted Visual Narrative Evaluation & Parallel Proposals for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-2024-approved-igniting-laughter-a-path-to-meme-fame/"><u>[Updated] 2024 Approved  Igniting Laughter  A Path to Meme Fame</u></a></li>
<li><a href="https://fox-glue.techidaily.com/10-insider-secrets-for-smarter-pixlr-usage-for-2024/"><u>10 Insider Secrets for Smarter Pixlr Usage for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-explore-these-innovative-5-iphone-apps-transforming-podcasts/"><u>2024 Approved  Explore These Innovative 5 iPhone Apps Transforming Podcasts</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-techno-gamers-monetization-guide/"><u>2024 Approved  Techno Gamers' Monetization Guide</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-ways-to-track-vivo-y100i-power-5g-without-them-knowing-drfone-by-drfone-virtual-android/"><u>3 Ways to Track Vivo Y100i Power 5G without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/a-guide-to-free-access-of-c-spans-broadcasted-content-for-2024/"><u>A Guide to Free Access of C-Span's Broadcasted Content for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-vpna-to-fake-gps-location-on-lava-yuva-2-pro-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use VPNa to Fake GPS Location On Lava Yuva 2 Pro | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/elevate-your-online-presence-making-exceptional-facebook-reels-for-2024/"><u>Elevate Your Online Presence  Making Exceptional Facebook Reels for 2024</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/enhance-pdf-and-doc-interaction-top-chatgpt-applications/"><u>Enhance PDF & Doc Interaction: Top ChatGPT Applications</u></a></li>
<li><a href="https://facebook.techidaily.com/enhancing-visibility-and-impact-8-key-differences-between-pages-and-profiles/"><u>Enhancing Visibility and Impact: 8 Key Differences Between Pages & Profiles</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/exploring-alternative-powertrains-a-comprehensive-guide-to-bevs-phevs-fcevs-and-hybrids/"><u>Exploring Alternative Powertrains: A Comprehensive Guide to BEVs, PHEVs, FCEVs, and Hybrids</u></a></li>
<li><a href="https://windows11.techidaily.com/expose-the-invisible-uncover-windows-11s-concealed-settings/"><u>Expose the Invisible: Uncover Windows 11'S Concealed Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-most-serious-javascript-problems-in-discord-on-w10w11-pcs/"><u>Fixing the Most Serious Javascript Problems in Discord on W10/W11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/from-phones-playground-to-pc-realm-android-games-via-microsoft-and-google/"><u>From Phone's Playground to PC Realm: Android Games via Microsoft & Google</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-convert-mkv-to-mp4-in-windows/"><u>How to Convert MKV to MP4 in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-hide-the-language-bar-from-the-windows-11-taskbar/"><u>How to Hide the Language Bar From the Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-a-frozen-qbittorrent-tracker/"><u>How to Reactivate a Frozen qBittorrent Tracker</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-ways-to-track-oppo-f23-5g-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Track Oppo F23 5G without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-oppo-a78-5g-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Oppo A78 5G</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-unlock-apple-id-without-phone-number-from-apple-iphone-15-by-drfone-ios/"><u>In 2024, Unlock Apple ID without Phone Number From Apple iPhone 15</u></a></li>
<li><a href="https://buynow-help.techidaily.com/in-depth-analysis-of-the-sony-cat-s42-exceptional-ruggedness-with-average-specs/"><u>In-Depth Analysis of the Sony CAT S42: Exceptional Ruggedness with Average Specs</u></a></li>
<li><a href="https://technical-tips.techidaily.com/inside-rumors-surrounding-the-upcoming-tesla-phone-projected-release-details-and-cost-estimates/"><u>Inside Rumors Surrounding the Upcoming Tesla Phone: Projected Release Details and Cost Estimates</u></a></li>
<li><a href="https://windows11.techidaily.com/integrating-aguard-technology-into-windows-11s-edge-web-experience/"><u>Integrating Aguard Technology Into Windows 11'S Edge Web Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/journey-into-creativity-initiating-ms-paint-on-win11/"><u>Journey Into Creativity: Initiating MS Paint on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-multiview-tech-with-windows/"><u>Mastering Multiview Tech with Windows</u></a></li>
<li><a href="https://screen-recording.techidaily.com/mastering-pc-games-screenshots-top-6-methods-for-2024/"><u>Mastering PC Games Screenshots  Top 6 Methods for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-rectifying-fatal-javascript-glitch-in-win-based-discord/"><u>Mastering the Art of Rectifying Fatal Javascript Glitch in Win-Based Discord</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-xpatch-troubleshooting/"><u>Mastering Windows XPatch Troubleshooting</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-guide-navigating-and-controlling-windows-fn-key/"><u>Mastery Guide: Navigating and Controlling Windows' Fn Key</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-the-could-not-call-runtime-problem-in-malwarebytes-windows/"><u>Mending the Could Not Call Runtime Problem in Malwarebytes Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-and-local-unpacking-key-contrasts-in-windows-login-mechanisms/"><u>Microsoft & Local: Unpacking Key Contrasts in Windows Login Mechanisms</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-no-script-zone-essential-4-steps-for-ps-execution-restoration/"><u>Navigating the No-Script Zone: Essential 4 Steps for PS Execution Restoration</u></a></li>
<li><a href="https://windows11.techidaily.com/no-more-maintenance-alert-post-support-for-windows-781/"><u>No More Maintenance Alert: Post-Support for Windows 7/8.1</u></a></li>
<li><a href="https://windows11.techidaily.com/overhaul-your-privacy-by-switching-off-windows-trackers/"><u>Overhaul Your Privacy by Switching Off Windows Trackers</u></a></li>
<li><a href="https://windows11.techidaily.com/quickfire-processes-identifying-graphic-card-model-windows-11/"><u>Quickfire Processes: Identifying Graphic Card Model, Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reducing-disk-overuse-from-ntoskrnlexe-on-systems/"><u>Reducing Disk Overuse From Ntoskrnl.exe on Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/reverting-lost-presets-for-win-11-sleep-mode/"><u>Reverting Lost Presets for Win 11 Sleep Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/running-the-troubleshooter-in-windows-settings/"><u>Running the Troubleshooter in Windows Settings</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/samsung-galaxy-tab-s3-worthy-purchase-or-oversold-product/"><u>Samsung Galaxy Tab S3: Worthy Purchase or Oversold Product?</u></a></li>
<li><a href="https://windows11.techidaily.com/scripting-changes-to-fn-key-settings-in-win-1011/"><u>Scripting Changes to FN Key Settings in Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-up-safe-browsing-for-kids-on-windows-11/"><u>Setting Up Safe Browsing for Kids on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-integration-how-to-set-up-linux-in-your-win10-box/"><u>Simplified Integration: How to Set Up Linux in Your Win10 Box</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-your-response-invalid-captcha-mistake/"><u>Solving 'Your Response Invalid' CAPTCHA Mistake</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-windows-11-search-issue-unlocking-the-settings-apps-search-bar/"><u>Solving Windows 11 Search Issue: Unlocking the Settings App's Search Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/steady-app-placement-tips-for-windows-task-manager/"><u>Steady App Placement Tips for Windows Task Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-address-file-system-problems-in-win11/"><u>Strategies to Address File System Problems in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-overcome-blue-screen-on-win11s-hypervisor/"><u>Swift Solutions: Overcome Blue Screen on Win11's HYPERVISOR</u></a></li>
<li><a href="https://windows11.techidaily.com/tackle-microsoft-store-login-challenges/"><u>Tackle Microsoft Store Login Challenges</u></a></li>
<li><a href="https://windows11.techidaily.com/the-seamless-interweaving-of-folders-and-files/"><u>The Seamless Interweaving of Folders & Files</u></a></li>
<li><a href="https://windows11.techidaily.com/the-secret-behind-timeless-game-aesthetics-retroarcs-shaders/"><u>The Secret Behind Timeless Game Aesthetics - RetroArc's Shaders</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-choosing-between-snipping-tool-and-printscreen/"><u>The Ultimate Guide to Choosing Between Snipping Tool and PrintScreen</u></a></li>
<li><a href="https://windows11.techidaily.com/top-windows-climate-trackers-windows-1011/"><u>Top Windows Climate Trackers (Windows 10/11)</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-mail-error-code-zero-x-eight-oh-three-one-f/"><u>Troubleshooting Windows Mail Error Code: Zero X Eight Oh Three One F</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-windows-hello-tips-for-fingerprint-issues/"><u>Unblocking Windows Hello: Tips for Fingerprint Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/uncover-the-file-location-for-your-desktop-images/"><u>Uncover the File Location for Your Desktop Images</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-fixing-winscomrssvdll-errors-in-windows-78/"><u>Understanding and Fixing WinscomrssvDll Errors in Windows 7/8</u></a></li>
<li><a href="https://extra-tips.techidaily.com/unlock-3d-text-magic-with-adobes-creative-suite/"><u>Unlock 3D Text Magic with Adobe's Creative Suite</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-full-potential-of-windows-11-search-here/"><u>Unlock the Full Potential of Windows 11 Search Here</u></a></li>
<li><a href="https://win-amazing.techidaily.com/upgraded-hid-standard-compatible-mouse-drivers-enhance-your-device-performance/"><u>Upgraded HID Standard Compatible Mouse Drivers: Enhance Your Device Performance</u></a></li>
<li><a href="https://howto.techidaily.com/why-does-my-realme-gt-3-keep-turning-off-by-itself-6-fixes-are-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Does My Realme GT 3 Keep Turning Off By Itself? 6 Fixes Are Here | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11s-error-740-a-strategic-plan-for-correction-and-compensation/"><u>Win 11’S Error 740: A Strategic Plan for Correction and Compensation</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>