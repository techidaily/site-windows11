---
title: Step-by-Step Tutorial on Locking Your System via the Windows 11 Command Line
date: 2024-08-31T22:01:00.000Z
updated: 2024-09-01T22:01:00.000Z
tags:
  - windows
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/52687750468_dc6bdda141_o-19.jpg
---

## Step-by-Step Tutorial on Locking Your System via the Windows 11 Command Line

### Quick Links

* [Lock Your Windows 10 PC Using Command Prompt](https://vp-tips.techidaily.com/new-audiovisual-adaptability-in-free-fire-for-2024/)
* [Set the Lock Screen Timeout Setting Using Command Prompt](https://eaxpv-info.techidaily.com/new-finding-a-different-way-to-naming-your-channel-with-filmora-for-2024/)

### Key Takeaways

* To lock your Windows PC using Command Prompt, run "**Rundll32.exe user32.dll,LockWorkStation"** in the Command Prompt
* To set the lock screen timeout, run "**powercfg.exe /SETACVALUEINDEX SCHEME\_CURRENT SUB\_VIDEO VIDEOCONLOCK <time>"** in Command Prompt as Admin
* Activate the lock screen timeout setting by running "**powercfg.exe /SETACTIVE SCHEME\_CURRENT"** after you set the timeout.

 One of the first rules of cyber security is to always lock your PC before stepping away. While it may not be the quickest way to lock your Windows 10 PC, you can do it using the Command Prompt.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
##  Lock Your Windows 10 PC Using Command Prompt

 First, [open the Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/) on your PC by opening the Start menu, typing “cmd” in the Windows Search bar, and then selecting “Command Prompt” from the search results.

![Click the Start button, search for 'cmd,' then open 'Command Prompt.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-launch-cmd.png) 

<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Command Prompt will now open. Here, run this command to lock your Windows 10 PC.

Rundll32.exe user32.dll,LockWorkStation

![Locking your PC with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-lock-pc-command-prompt.png) 

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
 Once executed, your PC will be locked. You'll have to sign back in with your PIN, password, or whatever sign-in method you usually use.

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Set the Lock Screen Timeout Setting Using Command Prompt

 Once you’ve locked your PC, the lock screen will generally be displayed for a certain amount of time before it time outs. You can set the amount of time that needs to pass before timing out using the Command Prompt.

 To do this, you’ll need to [open Command Prompt as an admin](https://screen-mirror.techidaily.com/how-to-screen-mirroring-xiaomi-14-ultra-drfone-by-drfone-android/). Do so by typing “cmd” in the Windows Search bar and then right-clicking “Command Prompt” from the results. Next, select “Run As Administrator” from the menu that appears.

![Launching Command Prompt as admin.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-launch-cmd.png) 

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 With Command Prompt open, run this command.

powercfg.exe /SETACVALUEINDEX SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK <time>

 Replace `<time>` with your desired amount of time in seconds. That means if you want to time out the lock screen after two minutes, you’d enter this command:

powercfg.exe /SETACVALUEINDEX SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK 120

![Change the timeout to 120.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-changing-timeout-to-120.png) 

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
 This command sets the lock screen timeout setting for your PC if it’s plugged in to a power source. To set the lock screen timeout setting for your PC if it’s running on battery, change`/SETACVALUEINDEX` to`/SETDCVALUEINDEX` and run the command as normal.

 Next, run this command:

powercfg.exe /SETACTIVE SCHEME_CURRENT

![Apply the setting to the currently active scheme.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-set-active.png) 

 Now your [lock screen](https://driver-download.techidaily.com/1722977751917-synaptics-drivers-download-and-update-for-windows-easily/) will timeout after the set amount of time. Give it a try!

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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-focussnap-recorder-for-screen-masters-for-2024/"><u>[New] FocusSnap Recorder for Screen Masters for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-expert-tips-for-enhancing-youtube-videos-through-seo-mastery/"><u>[New] In 2024, Expert Tips for Enhancing YouTube Videos Through SEO Mastery</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-effortless-and-easy-video-snapshots-of-win11/"><u>2024 Approved  Effortless & Easy Video Snapshots of Win11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-optimize-logitech-footage-background-free-method/"><u>2024 Approved  Optimize Logitech Footage - Background-Free Method</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-periscopes-unveiling-no-cost-entry-and-steps-to-signup/"><u>2024 Approved  Periscope's Unveiling  No Cost Entry & Steps to Signup</u></a></li>
<li><a href="https://fake-location.techidaily.com/best-10-mock-location-apps-worth-trying-on-honor-magic-v2-drfone-by-drfone-virtual-android/"><u>Best 10 Mock Location Apps Worth Trying On Honor Magic V2 | Dr.fone</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/bing-transformed-with-microsofts-artificial-intelligence/"><u>Bing Transformed with Microsoft’s Artificial Intelligence</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-music-files-on-google-pixel-8-by-fonelab-android-recover-music/"><u>Complete guide for recovering music files on Google Pixel 8</u></a></li>
<li><a href="https://driver-error.techidaily.com/device-cant-connect-missing-driver-issue/"><u>Device Can't Connect: Missing Driver Issue</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ng-exposure-cost-effective-promotion-hacks-for-youtubers-for-2024/"><u>Gaining Exposure  Cost-Effective Promotion Hacks for YouTubers for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/guide-to-reinventing-facebook-video-coverages-step-by-step-for-2024/"><u>Guide to Reinventing Facebook Video Coverages  Step-by-Step for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-win11-screensaver-failures-effectively/"><u>Handling WIN11 Screensaver Failures Effectively</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-unfortunately-contacts-has-stopped-error-on-motorola-moto-e13-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Unfortunately, Contacts Has Stopped Error on Motorola Moto E13 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reset-audio-driver-error-unresponsive-device-issue/"><u>How To Reset Audio Driver Error: Unresponsive Device Issue</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-successfully-update-usb-bluetooth-driver-software-on-windows-pcs/"><u>How to Successfully Update USB Bluetooth Driver Software on Windows PCs</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-apple-iphone-15-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade Apple iPhone 15 without iTunes? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-use-the-diskusage-command-to-analyze-drive-space-on-windows/"><u>How to Use the DiskUsage Command to Analyze Drive Space on Windows</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-best-virtual-background-for-google-meet/"><u>In 2024, Best Virtual Background for Google Meet</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-constructing-coherent-cinematic-introductions/"><u>In 2024, Constructing Coherent Cinematic Introductions</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-expertly-selected-8-filters-for-virtual-showcases/"><u>In 2024, Expertly Selected 8 Filters for Virtual Showcases</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-samsung-galaxy-a15-4g-drfone-by-drfone-virtual-android/"><u>In 2024, Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Samsung Galaxy A15 4G | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-professional-webcam-setup-on-macbook/"><u>In 2024, Professional Webcam Setup on MacBook</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-top-10-airplay-apps-in-vivo-y78plus-t1-edition-for-streaming-drfone-by-drfone-android/"><u>In 2024, Top 10 AirPlay Apps in Vivo Y78+ (T1) Edition for Streaming | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-10-realme-narzo-60-5g-android-sim-unlock-apk-by-drfone-android/"><u>In 2024, Top 10 Realme Narzo 60 5G Android SIM Unlock APK</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-turning-off-two-factor-authentication-on-apple-iphone-7-5-tips-you-must-know-by-drfone-ios/"><u>In 2024, Turning Off Two Factor Authentication On Apple iPhone 7? 5 Tips You Must Know</u></a></li>
<li><a href="https://windows11.techidaily.com/keep-your-laptop-cool-the-gamers-guide-to-temperature-control/"><u>Keep Your Laptop Cool: The Gamer’s Guide to Temperature Control</u></a></li>
<li><a href="https://windows11.techidaily.com/key-to-unveiling-windows-11-security-dashboard/"><u>Key to Unveiling Windows 11 Security Dashboard</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-window-tweaking-using-alomware-suite/"><u>Master the Art of Window Tweaking Using AlomWare Suite</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-boot-time-fixes-for-windows-audiovisual-issues/"><u>Mastering Boot-Time Fixes for Windows Audiovisual Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-print-device-non-response-windows-11/"><u>Overcoming Print Device Non-Response (Windows 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-runtime-issues-with-malwarebytes-in-modern-windows-systems/"><u>Overcoming Runtime Issues with Malwarebytes in Modern Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/path-retrieval-pro-unveiling-six-strategies-for-copying-windows-11-directory-structures/"><u>Path Retrieval Pro: Unveiling Six Strategies for Copying Windows 11 Directory Structures</u></a></li>
<li><a href="https://windows11.techidaily.com/perfect-window-dimensions-win11s-configurability/"><u>Perfect Window Dimensions: Win11's Configurability</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-lsasuxcomplision-error-on-windows-systems/"><u>Resolving LSASUX_COMPLISION ERROR on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/secretive-windows-11-aesthetic-designs/"><u>Secretive Windows 11 Aesthetic Designs</u></a></li>
<li><a href="https://windows11.techidaily.com/sifting-through-nvidia-drivers-for-entertainment-needs/"><u>Sifting Through Nvidia Drivers for Entertainment Needs</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-editing-adding-wordpad-command-keys-to-windows-ui/"><u>Simplifying Editing: Adding WordPad Command Keys to Windows' UI</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-windows-update-problem-error-0x8024800c/"><u>Solving Windows Update Problem: Error 0X8024800C</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-installing-and-setting-up-win11/"><u>Steps for Installing and Setting Up Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-addressing-blackwhite-monochrome-in-shop/"><u>Strategies for Addressing Black/White Monochrome in Shop</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-resolving-efail-0x80004005-error-in-windows-virtualbox/"><u>Strategies for Resolving E_FAIL (0X80004005) Error in Windows Virtualbox</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-latency-problem-with-gpsvc/"><u>Tackling the Latency Problem with GPSVC</u></a></li>
<li><a href="https://windows11.techidaily.com/tailor-your-workflow-perfecting-the-use-of-window-11s-search-box/"><u>Tailor Your Workflow: Perfecting the Use of Window 11'S Search Box</u></a></li>
<li><a href="https://windows11.techidaily.com/tech-savvy-access-three-ways-to-game-directories/"><u>Tech Savvy Access: Three Ways to Game Directories</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-vintage-films-with-a-windows-based-madvr-approach/"><u>Transforming Vintage Films with a Windows-Based MadVR Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/trim-your-digital-clutter-with-win11s-scheduled-deletion/"><u>Trim Your Digital Clutter with Win11's Scheduled Deletion</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/troubleshooting-the-kmodeexceptionnothandled-mistake-in-windows-11-and-windows-10/"><u>Troubleshooting the KMODE_Exception_Not_Handled Mistake in Windows 11 and Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-xbox-live-games-access-failures-on-windows-os/"><u>Troubleshooting: Xbox Live Games Access Failures on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-overcoming-display-errors-in-win1011/"><u>Understanding and Overcoming Display Errors in Win10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-winmcs-potential-solving-wi-fi-issues/"><u>Unleashing WinMC's Potential: Solving Wi-Fi Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-nextgen-access-mastering-upcoming-features-with-vivetool/"><u>Windows NextGen Access: Mastering Upcoming Features with ViVeTool</u></a></li>
</ul></div>
