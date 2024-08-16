---
title: "Mastering Windows PowerShell: Activating Script Policies"
date: 2024-08-15T16:20:35.839Z
updated: 2024-08-16T16:20:35.839Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Windows PowerShell: Activating Script Policies"
excerpt: "This Article Describes Mastering Windows PowerShell: Activating Script Policies"
keywords: PowerShell Policy Basics,Enabling Scripts,Admin Control PowerShell,Secure Shell Policies,Windows Server Management,Policy Configuration Powershell,Script Security in Windows,PowerShell Policies,Admin Controls PS,Secure Shell Policy,Windows Server Powershell,Enable Script Policies,Config PowerShell Policies,Secure Scripts Windows
thumbnail: https://thmb.techidaily.com/dc4cacbc8b493fc632f86712912ebd59bbc9ecbefdaf01df729929788c56ed4e.jpeg
---

## Mastering Windows PowerShell: Activating Script Policies

 iPowerShell, by default, lets you run commands (cmdlets) via its console. To execute a script, you can create a notepad file with the script code, save it with a .ps1 file extension, and execute it via the PowerShell console. You can also directly paste the script onto the console for execution.

 However, if it’s your first time executing a script via PowerShell, you’ll encounter the "running script is disabled" error. By default, script execution on PowerShell is disabled as a security measure to prevent malicious scripts from running on your system. Here we show you the two ways to enable the scrip execution policy on Windows PowerShell.

## How to Check Your Existing Execution Policy

![Powershell set execution policy undefined](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/powershell-set-execcution-policy-undefined.jpg)

 You can use a PowerShell cmdlet to get your current execution policy. Knowing your current execution policy is necessary to know if you need a policy change or not.

To get your current execution policy for the current user:

1. [Open Windows PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. Type the following command in the PowerShell console and hit Enter:  
`get-executionpolicy`
3. Since you have encountered an error when executing the script, the return will likely show**Restricted** as your current execution policy.
4. If you need to view the execution policy for all the supported scopes:  
`get-executionpolicy -list`

 You’ll need to change the execution policy to RemoteSigned to run local scripts without the error. You can change the execution policy from the Settings app and PowerShell.

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Enable PowerShell Execution Policy Using the Settings App

 You can change and set the PowerShell execution policy to RemoteSigned using the Settings app. All you have to do is tweak the PowerShell settings in the developers' section to change the execution policy to enable PowerShell script execution.

To change execution policy using Settings:

1. Press**Win + I** to open Se**t** tings.
2. Open the**Privacy & Security** tab in the left pane.
3. Next, click on**For developers.**  
![windows 11 for developers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-for-developers.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
4. Click to expand the**PowerShell** section.
5. Toggle the switch to **change the execution policy to allow local PowerShell scripts to run without signing - Require signing for remote scripts** .  
![enable powershell script execution windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-powershell-script-execution-windows-11-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
6. Once done, open PowerShell, type get**executionpolicy,** and press**Enter** . The execution policy for the current user is now set to**RemoteSigned.**
7. If you need to disable the execution policy, toggle the PowerShell switch and set it to**Off** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->
## How to Allow Scripts to Run in PowerShell using PowerShell

![Powershell set execcution policy remotesigned](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/powershell-set-execcution-policy-remotesigned.jpg)

 You can use a[PowerShell cmdlet](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) to set the execution policy to RemoteSigned. The command-line interface makes it easy to change execution policy quickly without using the Settings app.

 Also, the Settings app can only enable or disable the RemoteSigned execution policy. Whereas PowerShell lets you set other policies and scopes as well.

To change the execution policy using PowerShell:

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Set-ExecutionPolicy RemoteSigned`
3. If prompted, press**A** to confirm the action. This will set the**RemoteSigned** execution policy for all users. If you want to set the execution policy for the**Current User** only, use the Scope parameter followed by the username.
4. For example, to set the**RemoteSigned** execution policy for**CurrentUser** , use the following command:  
`Set-ExecutionPolicy RemoteSgined -Scope CurrentUser`
5. Replace**CurrentUser** in the above command with other users (Scope) as per your requirement.

## How to Remove Script Execution Policy Using PowerShell

![set-execution-policy-undefined](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-execution-polify-undefined.jpg)

 If you want to disable script execution, set the execution policy to**Undefined** using th**e Set\_ExecutionPolicy** cmdlet. This is a default state and prevents PowerShell from executing any scripts.

To disable script execution using PowerShell:

1. Open PowerShell with elevated permission.
2. Next, type the following command and press enter to disable script execution for all users:  
`Set-ExecutionPolicy undefined`
3. The above command will set the execution policy default (undefined) for all the users. If you want to disable script execution for a specific scope, use the following command:  
`Set-ExecutionPolicy undefined -Scope CurrentUser`
4. The above command will disable script execution for**CurrentUser** .

## Understanding Execution Policies and Scopes

 Simply put, PowerShell’s execution policy is a policy that controls how PowerShell executes config files and scripts. The intended purpose is to prevent users from accidentally running malicious scripts. The seven PowerShell execution policies are **Default, Restricted, RemoteSigned, AllSigned, Unrestricted, Bypass, and Undefined** .

 The below table briefly explains all the PowerShell execution policies:

| Execution Policy | Enforcement                                                                                                    |
| ---------------- | -------------------------------------------------------------------------------------------------------------- |
| Default          | Sets the default execution policy as Restricted on Windows Client and RemoteSigned on Windows Server.          |
| AllSigned        | Allows execution of publisher signed scripts.                                                                  |
| Bypass           | Unrestricted execution of scripts for larger applications.                                                     |
| RemoteSigned     | Allows locally written script execution. Requires digital signatures for scripts downloaded from the internet. |
| Restricted       | Doesn’t allow script execution, but only individual PowerShell commands.                                       |
| Undefined        | Sets execution policy to Restricted for Windows clients and RemoteSigned for Windows Server.                   |
| Unrestricted     | Allow unsigned script execution with a warning for the scripts downloaded from the internet.                   |

<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Execution Policy Scope

 You can set execution policy for a particular scope in PowerShell. The five execution policy scopes are**MachinePolicy, UserPolicy, Process, CurrentUser,** and**LocalMachine** .

The below table briefly explains all the execution policy scopes:

| Execution Policy Scope | Enforcement                                                                              |
| ---------------------- | ---------------------------------------------------------------------------------------- |
| UserPolicy             | Configured by a Group Policy for the current user.                                       |
| Machine Policy         | Configured by a Group Policy for all the users.                                          |
| CurrenUser             | Configured for the current user and stored in HKEY\_CURRENT\_MACHINE registry subkey.    |
| LocalMachine           | Configured for all users and stored in HKEY\_CURRENT\_MACHINE registry subkey.           |
| Process                | Affects current PowerShell session and automatically deleted when the session is closed. |

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
## Add or Remove PowerShell Script Execution Policy on Windows

 Script execution on PowerShell is disabled by default for Windows clients and set to RemoteSigned for Windows server. Power users, however, can change execution policies to run local, signed, and unsigned PowerShell scripts.

 Alternatively, you can bypass the PowerShell execution policy by pasting the script into a PowerShell console or ECHO your script into PowerShell standard input. This is useful if you want to execute scripts without changing the execution policy.


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
<li><a href="https://extra-guidance.techidaily.com/new-quick-guide-adding-zoom-to-your-email-communications/"><u>[New] Quick Guide  Adding Zoom to Your Email Communications</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ransform-your-footage-a-complete-youtube-studio-editing-course/"><u>[New] Transform Your Footage  A Complete YouTube Studio Editing Course</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-whats-shaking-the-breaking-down-of-top-8-social-videos/"><u>[New] What's Shaking? The Breaking Down of Top 8 Social Videos</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-unlocking-the-power-of-your-everyday-webcam/"><u>[Updated] 2024 Approved  Unlocking the Power of Your Everyday Webcam</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-ensuring-seamless-apple-podcast-addition/"><u>[Updated] Ensuring Seamless Apple Podcast Addition</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-press-record-on-your-pc-with-simplicity/"><u>[Updated] Press 'Record' On Your PC with Simplicity</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-smartphones-role-in-video-content-making-youtube-thumbnails-stand-out/"><u>2024 Approved  The Smartphone's Role in Video Content  Making YouTube Thumbnails Stand Out</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-error-code-963-on-google-play-of-samsung-galaxy-f34-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Error Code 963 on Google Play Of Samsung Galaxy F34 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/9-ways-to-fix-windows-hello-fingerprint-recognition-not-working/"><u>9 Ways to Fix Windows Hello Fingerprint Recognition Not Working</u></a></li>
<li><a href="https://android-unlock.techidaily.com/a-perfect-guide-to-remove-or-disable-google-smart-lock-on-oppo-reno-11f-5g-by-drfone-android/"><u>A Perfect Guide To Remove or Disable Google Smart Lock On Oppo Reno 11F 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-service-disruptions-with-steam-windows-11-style/"><u>Addressing Service Disruptions with Steam, Windows 11 Style</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-reset-account-lockout-counter-post-failed-sign-in-attempts/"><u>Adjusting Reset Account Lockout Counter Post-Failed Sign-In Attempts</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-infinix-zero-30-5g-drfone-by-drfone-reset-android-reset-android/"><u>All About Factory Reset, What Is It and What It Does to Your Infinix Zero 30 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-workflow-efficiency-mastering-flow-launcher/"><u>Boost Workflow Efficiency: Mastering Flow Launcher</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-forth-dormant-windows-11-control-panel-options/"><u>Bring Forth Dormant Windows 11 Control Panel Options</u></a></li>
<li><a href="https://windows11.techidaily.com/classic-interface-reclamation-tips/"><u>Classic Interface Reclamation Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-how-windows-sustains-ongoing-optimization/"><u>Deciphering How Windows Sustains Ongoing Optimization</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-windows-modern-standbys-drawbacks/"><u>Decoding Windows Modern Standby's Drawbacks</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/discovering-and-using-in-phone-fm-radios-on-apple-and-android-devices-for-free-broadcasting/"><u>Discovering and Using In-Phone FM Radios on Apple and Android Devices for Free Broadcasting</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/effortless-file-removal-with-stellar-file-eraser-5-pro-pack-customize-and-schedule-on-windows/"><u>Effortless File Removal with Stellar File Eraser 5 Pro Pack - Customize and Schedule on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-window-11-safety-with-best-in-class-password-protectors/"><u>Elevating Window 11 Safety with Best-in-Class Password Protectors</u></a></li>
<li><a href="https://windows11.techidaily.com/enhanced-windows-file-navigation-a-guide-excluding-ls/"><u>Enhanced Windows File Navigation: A Guide Excluding LS</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-various-windows-techniques-for-program-activation/"><u>Exploring Various Windows Techniques for Program Activation</u></a></li>
<li><a href="https://windows11.techidaily.com/facing-down-rounded-corners-in-windows-11/"><u>Facing Down Rounded Corners in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-for-rockalldlldll-not-found-on-windows-devices/"><u>Fix for 'Rockalldll.dll' Not Found on Windows Devices</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722960597481-get-the-latest-drivers-for-your-insignia-usb-to-vga-converter-now/"><u>Get the Latest Drivers for Your Insignia USB-to-VGA Converter Now!</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-page-could-not-be-loaded-error-in-the-microsoft-store-for-windows/"><u>How to Fix the Page Could Not Be Loaded Error in the Microsoft Store for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-keep-windows-full-screen-without-mobility-features/"><u>How To Keep Windows Full Screen without Mobility Features</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-share-location-in-messenger-on-tecno-spark-20c-drfone-by-drfone-virtual-android/"><u>How to Share Location in Messenger On Tecno Spark 20C? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-6-plus-to-other-iphone-14-pro-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 6 Plus To Other iPhone 14 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-or-downgrade-apple-iphone-11-pro-max-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade Apple iPhone 11 Pro Max Without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-4-ways-to-transfer-contacts-from-apple-iphone-13-pro-max-to-iphone-quickly-drfone-by-drfone-transfer-from-ios/"><u>In 2024, 4 Ways to Transfer Contacts from Apple iPhone 13 Pro Max to iPhone Quickly | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-gunners-gratitude-discovering-our-top-7-shooter-games/"><u>In 2024, Gunner's Gratitude  Discovering Our Top 7 Shooter Games</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-lock-your-oppo-a78-5g-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>In 2024, Lock Your Oppo A78 5G Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/installation-essentials-intel-network-adapters-for-windows-users/"><u>Installation Essentials: Intel Network Adapters for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-group-policy-editor-navigation-windows-11-style/"><u>Mastering Group Policy Editor Navigation, Windows 11 Style</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-your-computers-windows-key-settings/"><u>Mastering Your Computer’s Windows Key Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-maze-of-directdraw-fixes-on-modern-microsoft-oses/"><u>Navigating the Maze of DirectDraw Fixes on Modern Microsoft OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11s-software-compatibility-tool/"><u>Navigating Windows 11’S Software Compatibility Tool</u></a></li>
<li><a href="https://extra-tips.techidaily.com/perfect-pairing-10-films-for-fun-filled-family-nights/"><u>Perfect Pairing  10 Films for Fun-Filled Family Nights</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-your-windows-dashboard-incorporate-portable-apps/"><u>Personalize Your Windows Dashboard: Incorporate Portable Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/proactive-measures-for-sticky-notes-longevity/"><u>Proactive Measures for Sticky Notes' Longevity</u></a></li>
<li><a href="https://windows11.techidaily.com/quash-insufficient-requirement-notice-windows-11/"><u>Quash Insufficient Requirement Notice Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-dual-monitor-setup-problems/"><u>Resolving Dual Monitor Setup Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-excessive-ram-allocation-in-connected-devices-interface/"><u>Resolving Excessive RAM Allocation in Connected Devices Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-network-path-with-fixed-ea-server-error-in-os/"><u>Restoring Network Path with Fixed EA Server Error in OS</u></a></li>
<li><a href="https://fox-that.techidaily.com/step-by-step-guide-to-fix-your-phones-unprovisioned-sim-card-problem/"><u>Step-by-Step Guide to Fix Your Phone’s Unprovisioned SIM Card Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-counteract-d3d11-hardware-failures-in-w11w10/"><u>Strategies to Counteract D3D11 Hardware Failures in W11/W10</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-the-walls-of-windows-icons/"><u>Taming the Walls of Windows Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/tech-enthusiasts-rejoice-black-friday-offer-for-lifetime-612-windows-11-savings/"><u>Tech Enthusiasts Rejoice - Black Friday Offer for Lifetime $6.12 Windows 11 Savings</u></a></li>
<li><a href="https://windows11.techidaily.com/the-future-of-personal-computing-transforming-window-11-widgets/"><u>The Future of Personal Computing: Transforming Window 11 Widgets</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-windows-11-screens-with-custom-wallpaper-panes/"><u>Transform Windows 11 Screens with Custom Wallpaper Panes</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/ultimate-collection-highest-ranking-8-4k-players/"><u>Ultimate Collection  Highest Ranking 8 4K Players</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-your-creative-potential-with-win11s-photos-app-creating-dynamic-slideshows-and-image-spot-repair/"><u>Unlock Your Creative Potential with Win11's Photos App: Creating Dynamic Slideshows & Image Spot Repair</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-optimal-sleep-cycles-for-windows-devices/"><u>Unlocking Optimal Sleep Cycles for Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-your-smartphone-writescreen-functionality-for-windows-11/"><u>Unlocking Your Smartphone' Writescreen Functionality for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-application-startup-hexadecimal-issue-error/"><u>Unraveling The Application Startup Hexadecimal Issue (Error)</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-2024-approved-finest-text-to-speech-male-voice-tools-for-natural-output/"><u>Updated 2024 Approved Finest Text-to-Speech Male Voice Tools for Natural Output</u></a></li>
</ul></div>
