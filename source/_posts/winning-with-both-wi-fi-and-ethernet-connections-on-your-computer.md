---
title: Winning with Both Wi-Fi & Ethernet Connections on Your Computer
date: 2024-08-27T16:13:27.331Z
updated: 2024-08-28T16:13:27.331Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Winning with Both Wi-Fi & Ethernet Connections on Your Computer
excerpt: This Article Describes Winning with Both Wi-Fi & Ethernet Connections on Your Computer
keywords: Wi-Fi/Ethernet Winning Tips,Optimal Connectivity for PCs,Combo Wi-Fi Ethernet Usage,Effective Network Setups PC,Integrated Wi-Fi & Ethernet,Balancing Wi-Fi and Ethernet,Enhanced Computer Connections
thumbnail: https://thmb.techidaily.com/3376b29faa2d3197bcfcb2a2edc1961849ab5554465668491f874fa276d36a0e.jpg
---

## Winning with Both Wi-Fi & Ethernet Connections on Your Computer

 You can have your Windows computer connected to Wi-Fi and Ethernet simultaneously, but the system won't use both connections at the same. Windows automatically configures the network adapter order priority to provide the best Internet connection via Ethernet or Wi-Fi.

 However, if you have multiple ISP connections or have a local media server, you can configure your Windows laptop to use Wi-Fi and Ethernet simultaneously. To do this, you must disable packet priority for both Wi-Fi and Ethernet network adapter.

## Why You May Need to Use Both the Wi-Fi and Ethernet Connections Simultaneously

 While you may not get an additional speed advantage when using the same ISP for your Wi-Fi and Ethernet, you can have both connections up and running as a backup for critical Internet-dependent services. Also, if you have access to multiple ISP connections, you can[merge multiple connections to increase your internet speed](https://www.makeuseof.com/how-to-merge-internet-connections/) .

 Additionally, it is also useful if you have a local server and want to be connected to both the Internet and the local server simultaneously. You can connect to the local media server via Ethernet and access the internet over Wi-Fi without dropping the connection.

 On the flip side, there are chances of packet loss due to duplicate packets being transmitted via both the Wi-Fi and Ethernet connection. Lower-end routers may also notice decreased speed due to increased load on your network device. This is part of the reasons[why you may want to replace your ISP's router](http://www.makeuseof.com/tag/reasons-replace-isp-router/) .

## How to Configure Windows to Use Wi-Fi and Ethernet Connections Simultaneously

 Since Windows automatically prioritizes the network adapter to use only one adapter at a time, you'll need to disable the packet priority option in the network adapter's network configuration. Doing so will allow Windows to use multiple connections simultaneously.

To disable packet priority and VLAN on Windows:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel** .
3. Next, go to**Network and Internet** and click on**Network and Sharing Center.**  
![control panel network change adapter settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/control-panel-network-change-adapter-settings.jpg)
4. In the left pane, click on**Change adapter settings.**
5. Right-click on your**Ethernet network adapter** and select**Properties** . Alternatively, double-click on the**Ethernet adapter** and then click on**Properties** .  
![ethernet properties configure networking control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/ethernet-properties-configure-networking-control-panel.jpg)

1. In the**Networking** tab, click the**Configure** button.
2. Next, open the**Advanced** tab.
3. Select**Priority and VLAN** under the**Property** section.
4. Click the drop-down under**Value** .  
![priority vlan disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/priority-vlan-disabled.jpg)
5. Select**Priority and VLAN Disabled.**
6. Click**OK** to save the changes.
7. Next, you need to repeat the steps for your Wi-Fi adapter. So, open Properties for your Wi-Fi adapter and set its**Priority and VLAN** value to**Priority & VLAN Disabled** .
8. Click**OK** to save the changes.

 With the network adapter priority option disabled, Windows will now use both network connections simultaneously.

<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Set the Network Priority for Wi-Fi or Ethernet Using Interface Metric

 By default, Windows uses an automatic metric to detect and use the best network connectivity option available. However, if you need, you can manually set network priority to force Windows to use Ethernet or Wi-Fi as the preferred connectivity option.

To change network priority on Windows:

1. Press**Win + R** to open**Run** .
2. Type**ncpa.cpl** and click**OK** .  
![ncpa cpl open control panel network and sharing center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/ncpa-cpl.jpg)
3. Right-click on your Ethernet adapter and select**Properties** . If you want to prioritize your Wi-Fi adapter, choose that instead.
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Next, select**Internet Protocol Version 4 (TCP/IPv4)** and click on**Properties** .  
![tcp ip v4 properties control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tcp-ip-v4-properties-control-panel.jpg)
5. Click the**Advanced** button in the**Properties** dialog.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
6. Next, uncheck**Automatic metric** and type**5** in the**Interface metric** field.
7. Click**OK** on all the open windows to save the changes.
8. Note that if you use Internet Protocol Version 6 (IPv6) protocol, you’ll need to assign an interface metric for it as well.

 With the changes saved, Windows will prioritize your preference when multiple network adapters are connected to your computer. To undo the changes, open**Advanced TCP/IP Settings** and check the**Automatic** **metric** option. Then, click**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Make Your Computer Use Your Wi-Fi and Ethernet at the Same Time

 You can configure the network adapter on your computer to use both Wi-Fi and Ethernet connection simultaneously. While it has many advantages, it won't increase your Internet speed. Instead, you’ll need multiple Internet connections powering your Wi-Fi and Ethernet networks to see increased speed.

 Alternatively, if you have multiple Wi-Fi connections at home or office, you can configure your Windows computer to automatically switch to the strongest Wi-Fi network available when you move around.


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
<li><a href="https://youtube-tips.techidaily.com/n-2024-composing-correspondents-curtains/"><u>[New] In 2024, Composing Correspondents' Curtains</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-discovering-8-honestly-endorsed-promotional-strategies-for-2024/"><u>[Updated] Discovering 8 Honestly-Endorsed Promotional Strategies for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-dissecting-the-prospects-of-active-presenter-for-techies/"><u>[Updated] Dissecting the Prospects of Active Presenter for Techies</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-expeditious-approaches-to-slide-storage-for-2024/"><u>[Updated] Expeditious Approaches to Slide Storage for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-is-your-channels-income-regular-via-youtube-for-2024/"><u>[Updated] Is Your Channel's Income Regular via YouTube for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-a-detailed-guide-to-streamlabs-obs/"><u>2024 Approved  A Detailed Guide to Streamlabs OBS</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-step-by-step-including-in-apples-premium-catalog/"><u>2024 Approved  Step-by-Step  Including in Apple's Premium Catalog</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-techniques-for-elongated-iphone-photography/"><u>2024 Approved  Techniques for Elongated iPhone Photography</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-youtube-creator-summit-a-getaway-for-youtubes-top-talent/"><u>2024 Approved  The YouTube Creator Summit - A Getaway for YouTube's Top Talent</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-best-route-generator-apps-you-should-try-on-asus-rog-phone-7-ultimate-drfone-by-drfone-virtual-android/"><u>5 Best Route Generator Apps You Should Try On Asus ROG Phone 7 Ultimate | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/excellent-fps-software-for-windows-gamers-the-creme-de-la-creme-list/"><u>Excellent FPS Software For Windows Gamers: The Crème De La Crème List</u></a></li>
<li><a href="https://win-answers.techidaily.com/google-meet-webcam-troubles-heres-how-you-can-get-it-working-again/"><u>Google Meet Webcam Troubles? Here's How You Can Get It Working Again!</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-prolong-windows-10-restart-time-while-tasks-run/"><u>How to Prolong Windows 10 Restart Time While Tasks Run</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-turn-off-the-screen-lock-on-my-oppo-a58-4g-by-drfone-android-unlock-android-unlock/"><u>How to turn off the screen lock on my Oppo A58 4G</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-brand-consistency-in-action-inserting-logoswatermarks-into-videos/"><u>In 2024, Brand Consistency in Action  Inserting Logos/Watermarks Into Videos</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-building-trust-through-words-docu-script-insights/"><u>In 2024, Building Trust Through Words  Docu-Script Insights</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-forgot-iphone-se-2020-backup-password-heres-what-to-do-drfone-by-drfone-ios/"><u>In 2024, Forgot iPhone SE (2020) Backup Password? Heres What to Do | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-interactive-tips-youtube-to-facebook-shareability/"><u>In 2024, Interactive Tips  YouTube to Facebook Shareability</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-premier-racing-experience-series-top-5/"><u>In 2024, Premier Racing Experience Series (Top 5)</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-two-ways-to-sync-contacts-from-poco-m6-pro-4g-to-gmail-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Two Ways to Sync Contacts from Poco M6 Pro 4G to Gmail | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-understanding-key-differences-in-panoramic-and-vr-cinematography/"><u>In 2024, Understanding Key Differences in Panoramic and VR Cinematography</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-what-you-want-to-know-about-two-factor-authentication-for-icloud-on-your-apple-iphone-6s-by-drfone-ios/"><u>In 2024, What You Want To Know About Two-Factor Authentication for iCloud On your Apple iPhone 6s</u></a></li>
<li><a href="https://windows11.techidaily.com/instant-admin-access-to-command-prompt-in-windows/"><u>Instant Admin Access to Command Prompt in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/m06-headphones-seamless-wireless-interfacing-unveiled/"><u>M06 Headphones: Seamless Wireless Interfacing Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/making-the-right-windows-11-call-home-vs-premium-features/"><u>Making the Right Windows 11 Call: Home Vs. Premium Features</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-camera-fix-up-windows-11s-error-code-a00f4289-demystified/"><u>Mastering Camera Fix-Up: Windows 11'S Error Code A00F4289 Demystified</u></a></li>
<li><a href="https://windows11.techidaily.com/maximize-graphics-performance-with-1-6-tools-for-windows-pcs/"><u>Maximize Graphics Performance with #1-#6 Tools for Windows PCs</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/melodyrecorder-free-an-experts-evaluation/"><u>MelodyRecorder Free  An Expert's Evaluation</u></a></li>
<li><a href="https://windows11.techidaily.com/microphone-woes-troubleshooting-in-google-meet-on-windows/"><u>Microphone Woes: Troubleshooting in Google Meet on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/move-your-onedrive-step-by-step-for-windows-11/"><u>Move Your OneDrive: Step-by-Step for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-intel-hd-error-in-meeting-minimum-requirements/"><u>Navigating Through Intel HD Error in Meeting Minimum Requirements</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-remote-desktop-windows-problems/"><u>Navigating Through Remote Desktop Windows Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-corruption-write-restoration-in-windows-systems/"><u>Preventing Corruption: Write Restoration in Windows Systems</u></a></li>
<li><a href="https://apple-account.techidaily.com/protecting-your-privacy-how-to-remove-apple-id-from-iphone-6s-by-drfone-ios/"><u>Protecting Your Privacy How To Remove Apple ID From iPhone 6s</u></a></li>
<li><a href="https://windows11.techidaily.com/repairing-lopsided-one-side-windows-headphone-sounds/"><u>Repairing Lopsided One-Side Windows Headphone Sounds</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-failures-of-file-segmentation-service/"><u>Resolving Failures of File Segmentation Service</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-usb30-device-failure-on-windows-oses/"><u>Resolving USB3.0 Device Failure on Windows OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/seamlessly-navigate-anywhere-the-art-of-cross-border-mouse-usage/"><u>Seamlessly Navigate Anywhere - The Art of Cross-Border Mouse Usage</u></a></li>
<li><a href="https://windows11.techidaily.com/securely-resetting-dns-on-the-latest-windows-version/"><u>Securely Resetting DNS on the Latest Windows Version</u></a></li>
<li><a href="https://windows11.techidaily.com/skyrocket-success-in-windows-11-with-these-top-5-apps/"><u>Skyrocket Success in Windows 11 With These Top 5 Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/skyrocketing-yuzu-speeds-on-windows-devices/"><u>Skyrocketing Yuzu Speeds on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-language-shift-keyboard-shortcuts-for-windows-11-users/"><u>Speedy Language Shift: Keyboard Shortcuts for Windows 11 Users</u></a></li>
<li><a href="https://driver-download.techidaily.com/step-by-step-tutorial-on-easy-window-battery-driver-updates-for-better-performance/"><u>Step-by-Step Tutorial on Easy Window Battery Driver Updates for Better Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-folder-integration-overcoming-onedrives-error/"><u>Streamlining Folder Integration: Overcoming OneDrive's Error</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-system-performance-with-lav-filters-in-windows/"><u>Streamlining System Performance with LAV Filters in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-obstacle-of-file-creation-windows-error-30005/"><u>Tackling the Obstacle of File Creation - Windows Error 30005</u></a></li>
<li><a href="https://location-social.techidaily.com/top-7-skype-hacker-to-hack-any-skype-account-on-your-poco-x6-drfone-by-drfone-virtual-android/"><u>Top 7 Skype Hacker to Hack Any Skype Account On your Poco X6 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-on-windows-11s-direct-image-viewing/"><u>Turn On Windows 11'S Direct Image Viewing</u></a></li>
<li><a href="https://windows11.techidaily.com/turning-classic-computers-into-modern-windows-11-hubs-with-tools/"><u>Turning Classic Computers Into Modern Windows 11 Hubs with Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-full-potential-of-windows-11-calendar/"><u>Unlocking Full Potential of Windows 11 Calendar</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-transform-your-videos-free-online-video-quality-improvement-tools/"><u>Updated Transform Your Videos Free Online Video Quality Improvement Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-setting-up-microsoft-pc-manager/"><u>Win 11: Setting Up Microsoft PC Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-stop-intelligent-assistant/"><u>Windows 11: Stop Intelligent Assistant</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-tricks-bringing-off-screen-apps-back-to-life-with-6-tips/"><u>Windows Tricks: Bringing Off-Screen Apps Back to Life with 6 Tips</u></a></li>
</ul></div>
