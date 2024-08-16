---
title: Sudo's Arrival in Windows OS Explained
date: 2024-08-15T15:50:14.636Z
updated: 2024-08-16T15:50:14.636Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Sudo's Arrival in Windows OS Explained
excerpt: This Article Describes Sudo's Arrival in Windows OS Explained
keywords: Windows Sudo Guide,Sudo Functionality,Windows Operating System,Understanding Sudo,Windows Security Features,OS Command Line Usage,Sudo in Windows Update
thumbnail: https://thmb.techidaily.com/c80fad792e3cb229a3e653969139437b39335328a63ecf71a877586d96fe497a.jpg
---

## Sudo's Arrival in Windows OS Explained

### Key Takeaways

* The sudo command on Windows lets you run commands with elevated privileges.
* Microsoft is introducing sudo in Windows 11 to make using the command line more convenient.
* Enable sudo via Settings, the Command Prompt, or PowerShell.

 If you're a fan of tweaking your Windows setup, you often need to run "elevated" or Administrator-level commands. You're probably used to doing this by running a Command Prompt as administrator, but it's about to get a lot easier with sudo on Windows.

## What Does the sudo Command Do?

 Despite the general focus on configuring everything through the Settings apps and easy-to-use configuration wizards on Windows, every once in a while, you still need to type in commands. Many of these won't work with your standard user account. Instead, you need to run them as an administrator. Requiring administrator permissions is still a relatively new concept in Windows, but it was prevalent for far longer in older operating systems.

 It was so prevalent that operating system developers thought about a solution to the problem decades ago. Unix installations had, and still do have, a `su` command, which means "switch user." This would allow you to switch accounts to any other user, but could also let you run as the administrator, or superuser, account of the system by default.

 This solution worked, but logging in as the administrator to run one command seemed like overkill. As a solution, developers created the sudo command, which means either "switch user and do," or "superuser do," depending on various opinions. Long story short, the sudo command lets you easily run one command with elevated privileges—we've covered [the differences between su and sudo](http://www.makeuseof.com/sudo-vs-su/) if you're curious.

 This means that the sudo command is roughly equivalent to right-clicking on the Command Prompt app, selecting **Run as administrator**, and running a command, like `do_something`. With the help of the sudo command, you don't need to worry about remembering to run the Command Prompt as administrator. Instead, simply type `sudo do_something`, and the command will work in exactly the same way.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
## Which Windows Versions Can Run the sudo Command?

 Microsoft is adding the sudo command to Windows 11, and considering that support for Windows 10 is winding down, we don't expect to see the command coming there anytime soon. At the time of writing, the sudo command is only available for Windows Insider participants (builds 26045 and later), specifically those on the Developer and [Windows Canary channels](https://www.makeuseof.com/what-is-windows-insider-canary-channel/).

 Unlike some features that Microsoft tests in these versions, it seems fairly likely that sudo is going to arrive on the operating system soon.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
## How to Enable the sudo Command on Windows

 If the sudo command isn't yet available for your version of Windows, you'll need to [sign up for Windows Insider](https://www.makeuseof.com/windows-11-insider-program-join/). This is a simple process, but be warned: the Developer and Canary options can be unstable, so don't use them on a PC you're not willing to lose data on.

 Once you're running a version of Windows that has the sudo command available, enabling it is a simple process. Open the **Settings** app, then select **System** on the left and **For developers** from the main area of the window.

 Here, scroll down and enable the checkbox that reads **Enable sudo**.

![Enabling sudo on Window in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-window-in-the-settings-app.jpg)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Enable sudo via the Command Prompt

 If you're more command-line oriented, you can also enable sudo via the Commmand Prompt. Somewhat ironically, this requires you to run an elevated CMD window. Press the **Windows** key, type "command," then right-click on **Command Prompt** (or **PowerShell**) and select **Run as administrator**.

 In this prompt, run the following command:

`sudo config --enable enable`

![Enabling sudo on Windows via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-windows-via-powershell.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Use the sudo Command on Windows

 After you've enabled the sudo command on Windows, it's simple to use. Simply prepend the `sudo` command to any command you'd typically need to run as an administrator, then accept the prompts that follow.

 An example from Microsoft uses the `netstat` command:

`sudo netstat -ab  
`

![Running a command on Windows via sudo](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/running-a-command-on-windows-via-sudo.jpg)

 This feature may seem a tad unnecessary—and for many people, it is. That said, if you spend your day running command after command on Windows and wish for the simplicity of the sudo command, its addition will make your life easier.

 Microsoft seems committed to its implementation of sudo, even going so far as to release [sudo on GitHub](http://github.com/microsoft/sudo) as open source. If reading this entices you to learn more about what goes on under the hood in Windows, make sure to take a look at our list of [commands every Windows user should know](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/).

 If you're a fan of tweaking your Windows setup, you often need to run "elevated" or Administrator-level commands. You're probably used to doing this by running a Command Prompt as administrator, but it's about to get a lot easier with sudo on Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-hints.techidaily.com/new-10-best-screenshot-enhancers-iphoneandroid-sticker-magic/"><u>[New] 10 Best Screenshot Enhancers  IPhone/Android Sticker Magic</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-deciphering-user-insights-in-youtube-comments/"><u>[New] 2024 Approved  Deciphering User Insights in YouTube Comments</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-secure-smooth-cinematography-the-best-stabilizer-brands-guide/"><u>[New] Secure Smooth Cinematography  The Best Stabilizer Brands Guide</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-step-by-step-building-time-lapse-shots-on-samsung-gear/"><u>[New] Step-by-Step  Building Time Lapse Shots on Samsung Gear</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-choosing-the-best-a-dive-into-obs-and-twitch-streaming/"><u>[Updated] In 2024, Choosing the Best  A Dive Into OBS & Twitch Streaming</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-instagrammable-vs-trendy-will-likebeat-tiktok-for-2024/"><u>[Updated] Instagrammable Vs. Trendy  Will LikeBeat TikTok for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-spectra-adjustment-suite/"><u>[Updated] Spectra Adjustment Suite</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-unlock-fb-seo-potential-with-keyword-rich-strategies-for-2024/"><u>[Updated] Unlock FB SEO Potential with Keyword-Rich Strategies for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-elevate-your-video-game-top-10-keyword-strategy-resources/"><u>2024 Approved  Elevate Your Video Game  Top 10 Keyword Strategy Resources</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-exclusive-selection-best-desktop-pcs/"><u>2024 Approved  Exclusive Selection  Best Desktop Pcs</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-your-free-tool-to-record-androids-precision/"><u>2024 Approved  Your Free Tool to Record Android's Precision</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-vm-performance-on-windows-6-precise-tips-and-tricks/"><u>Accelerate VM Performance on Windows: 6 Precise Tips & Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-personalized-settings-alomwares-pathway-to-customization/"><u>Achieve Personalized Settings - AlomWare's Pathway to Customization</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-edge-guards-camera-and-mic-use/"><u>Activating Edge Guards: Camera & Mic Use</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-the-crashes-resource-monitor-on-windows-11/"><u>Addressing the Crashes: Resource Monitor on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-xp709-crash-in-windows/"><u>Addressing XP709 Crash in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-failed-logon-wait-duration-settings-in-windows/"><u>Altering Failed Logon Wait Duration Settings in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/biggest-discounts-black-friday-612-windows-10-forever/"><u>Biggest Discounts: Black Friday - $6.12, Windows 10 Forever</u></a></li>
<li><a href="https://windows11.techidaily.com/blending-digital-worlds-androidpc-connections-made-simple/"><u>Blending Digital Worlds: Android/PC Connections Made Simple</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-through-windows-tpm-restrictions-with-ease/"><u>Breaking Through Windows TPM Restrictions with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-0x80070194-fixes-for-windows-onedrive/"><u>Bypassing 0X80070194: Fixes for Windows OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-a-driverirqlnotlessorequal-in-windows/"><u>Clearing Up A DRIVER_IRQL_NOT_LESS_OR_EQUAL in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/confronting-error-code-xc0f1103f-in-nvidias-geforce-now/"><u>Confronting Error Code Xc0f1103f in NVIDIA's GeForce Now</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-oculus-install-error-on-wincx-a-helpful-guide/"><u>Conquering Oculus Install Error on WinCX: A Helpful Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-error-mcuicntexe-not-found-in-win-8xp/"><u>Correcting Error: McUICnt.exe Not Found in Win 8/XP</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-xbox-mic-connectivity-issues-in-windows-11-devices/"><u>Correcting Xbox Mic Connectivity Issues in Windows 11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-tips-to-access-pcs-health-metrics/"><u>Decoding Tips to Access PC's Health Metrics</u></a></li>
<li><a href="https://windows11.techidaily.com/distinguishing-characteristics-of-exe-and-msi-files/"><u>Distinguishing Characteristics of EXE and MSI Files</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-troubleshooting-roadblocks-for-compatibility-issues/"><u>Eliminate Troubleshooting Roadblocks for Compatibility Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/empowering-windows-users-introducing-a-customized-run-helper-app/"><u>Empowering Windows Users: Introducing a Customized Run Helper App</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/experts-insight-best-car-tracking-gadgets-for-2024/"><u>Expert's Insight  Best Car Tracking Gadgets for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fasten-up-your-windows-devices-with-top-fixes-for-slow-web-linkage/"><u>Fasten Up Your Windows Devices with Top Fixes for Slow Web Linkage</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/from-raw-recordings-to-professional-vids-webcam-edition/"><u>From Raw Recordings to Professional Vids - Webcam Edition</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-from-realme-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock from Realme Phones with/without a PC</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-iphone-14-pro-max-data-from-ios-icloud-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How to Recover iPhone 14 Pro Max Data From iOS iCloud? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-non-existent-lock-screen-countdown/"><u>How to Rectify Non-Existent Lock Screen Countdown</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-android-unlock-code-sim-unlock-your-nokia-105-classic-phone-and-remove-locked-screen-by-drfone-android/"><u>In 2024, Android Unlock Code Sim Unlock Your Nokia 105 Classic Phone and Remove Locked Screen</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-special-features-virtual-location-on-motorola-moto-g23-drfone-by-drfone-virtual-android/"><u>In 2024, How To Use Special Features - Virtual Location On Motorola Moto G23? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-10-vivo-y100i-android-sim-unlock-apk-by-drfone-android/"><u>In 2024, Top 10 Vivo Y100i Android SIM Unlock APK</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-unleashing-potential-the-instagram-success-story-guide/"><u>In 2024, Unleashing Potential - The Instagram Success Story Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-pc-performance-top-6-monitoring-apps-recommended-for-win/"><u>Optimize PC Performance: Top 6 Monitoring Apps Recommended for Win</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-win-strategies-boosting-frames-in-cs-go/"><u>Quick Win Strategies - Boosting Frames in CS GO</u></a></li>
<li><a href="https://windows11.techidaily.com/remedial-tactics-for-loading-errors-in-discord-software/"><u>Remedial Tactics for Loading Errors in Discord Software</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-device-disconnection-problems-for-windows-users-with-virtualbox/"><u>Resolving Device Disconnection Problems for Windows Users with VirtualBox</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-your-windows-11-9-solutions-for-lost-bluetooth/"><u>Reviving Your Windows 11: 9 Solutions for Lost Bluetooth</u></a></li>
<li><a href="https://windows11.techidaily.com/significance-of-redistributing-visual-cplusplus/"><u>Significance of Redistributing Visual C++</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-windows-repeatedly-entering-cmos-settings/"><u>Solutions for Windows Repeatedly Entering CMOS Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/stopping-google-chrome-alerts-tips-for-windows/"><u>Stopping Google Chrome Alerts: Tips for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-controlling-file-compression-in-windows-11/"><u>Strategies for Controlling File Compression in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-complete-list-of-windows-11s-narrator-keyboard-shortcuts/"><u>The Complete List of Windows 11'S Narrator Keyboard Shortcuts</u></a></li>
<li><a href="https://windows11.techidaily.com/the-phasing-out-of-microsofts-windows-xp-7-and-81-lifeline/"><u>The Phasing Out of Microsoft's Windows XP, 7 & 8.1 Lifeline</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-photomontage-artisans-blueprint-for-2024/"><u>The PhotoMontage Artisan's Blueprint for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-samsung-galaxy-z-fold-5-by-drfone-android/"><u>The Top 5 Android Apps That Use Fingerprint Sensor to Lock Your Apps On Samsung Galaxy Z Fold 5</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-your-computers-clock-display-with-animated-screensaver-apps/"><u>Transform Your Computer's Clock Display with Animated Screensaver Apps</u></a></li>
<li><a href="https://activate-lock.techidaily.com/ultimate-guide-on-iphone-7-plus-icloud-activation-lock-bypass-by-drfone-ios/"><u>Ultimate Guide on iPhone 7 Plus iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-power-of-shortcuts-for-app-size-adjustment-on-windows-11/"><u>Unlocking the Power of Shortcuts for App Size Adjustment on Windows 11</u></a></li>
</ul></div>
