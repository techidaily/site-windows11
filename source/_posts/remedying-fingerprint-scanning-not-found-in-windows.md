---
title: Remedying Fingerprint Scanning Not Found in Windows
date: 2024-09-05T02:15:10.506Z
updated: 2024-09-06T02:15:10.506Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Remedying Fingerprint Scanning Not Found in Windows
excerpt: This Article Describes Remedying Fingerprint Scanning Not Found in Windows
keywords: Fix Fingerprint Error,Resolve Unreadable Prints,Address FPS Missing,Correct Scanner Fail,Fix Scanning Gap,Eliminate Prints No Found,Mend Scan Not Detected
thumbnail: https://thmb.techidaily.com/43e39de2530caaef8af78f1650abc11434992b40c432e7b5caac8bd0f3cdf48f.png
---

## Remedying Fingerprint Scanning Not Found in Windows

 If you receive an error message that says, "we couldn't find a fingerprint scanner compatible with Windows Hello Fingerprint" when trying to set up Windows Hello fingerprint login, then your device either doesn't support fingerprint recognition, the fingerprint scanner (or reader) isn't working correctly, or Windows is unable to detect it.

 Windows may not detect the fingerprint scanner for several reasons: the fingerprint reader may have malfunctioned, the biometric drivers could be outdated or corrupted, or biometric recognition could be disabled in the BIOS. If you're tired of dealing with this problem, try these solutions.

## 1\. Ensure Your Device Supports Fingerprint Recognition

![blue graphic of digital fingerprint scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/blue-finger-scan.jpg)

 The Windows Hello fingerprint recognition feature requires your device to have a fingerprint reader. If you encounter the error "we could not find a fingerprint scanner compatible with Windows Hello Fingerprint" when setting up fingerprint recognition for the first time, make sure your device is equipped with a fingerprint reader compatible with Windows Hello.

 Usually, it is located near (or on) the power button or in the empty space above or below the keyboard. Look around and see if you can find a fingerprint reader. If you fail to find it, check your device's specifications on the manufacturer's website to see if it has a fingerprint scanner.

 If your device does not have a fingerprint reader, you cannot enable biometric authentication on it. However, if your device has a scanner, and you've used it many times before, ensure that it is working correctly.

## 2\. Make Sure the Fingerprint Reader Is Working Properly

![security fingerprint on keyboard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/data-1590455_1920-1.jpg)

 If your device has a fingerprint sensor, but Windows is unable to detect it, ensure the sensor hasn't gone bad. To test the fingerprint reader, sign in to another app where you've set up biometric login. If that app fails to accept biometric verification, use a dry cloth to wipe the dust off your fingerprint scanner.

 After that, try scanning your finger again. If the app fails to recognize the fingerprint scan even after thoroughly cleaning it, there is probably an issue with the scanner. So, have your device inspected by a technician. However, if the scanner works fine on other apps but not when you set up Windows Hello fingerprint login, then apply the remaining fixes.

## 3\. Roll Back the Driver or the Latest Windows Update

 Have you encountered the error under discussion after updating the biometric driver or installing a Windows update recently? If this is the case, you should roll back these updates. Don't know how to do that? Our guide on[how to roll back a driver update on Windows](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) describes the process. If you want to roll back a Windows update, then you need to[uninstall the most recent Windows Update](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) .

 Once you've undone both driver and Windows updates, try setting up Windows Hello biometric login again. If you continue to experience the same problem after rolling back these updates, it suggests that undoing these updates hasn't made a difference. In that case, you should reinstall the drivers and Windows update.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100527/7443" target="_top" id="2100527">
  <img src="//a.impactradius-go.com/display-ad/7443-2100527" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100527/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Ensure the Windows Biometric Service Is Configured Properly

 When the Windows biometric service is disabled, Windows Hello fingerprint recognition won't work. To ensure this service is enabled and configured correctly, follow these steps:

1. Type**"Services"** in Windows Search and open the**Services** app.  
![Open Services App From Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/1-open-services-app-from-windows-search.jpg)
2. Locate**Windows Biometric Service** .  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880931/19272" target="_top" id="1880931">
  <img src="//a.impactradius-go.com/display-ad/19272-1880931" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880931/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Locate Windows Biometric Service in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/2-locate-windows-biometric-service-in-windows-services-app.jpg)
3. If you see**"Running"** next to this service in the**Status** column, it's already running. If not, it's disabled.
4. In either case, right-click the service and select**Properties** .  
![Go to Properties of Windows Biometric Service in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3-go-to-properties-of-windows-biometric-service-in-windows-services-app.jpg)
5. Click on the dropdown menu next to**Startup type** and select**Automatic** .  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918684/19272" target="_top" id="1918684">
  <img src="//a.impactradius-go.com/display-ad/19272-1918684" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918684/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Select Automatic From the Startup Type Dropdown Menu in the Properties Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/4-select-automatic-from-the-startup-type-dropdown-menu-in-the-properties-window.jpg)
6. If it's already selected, click the**Stop** button to stop the service and then click**Start** again to restart it.  
![Click Start Button to Restart the Service in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/5-click-start-button-to-restart-the-service-in-windows-services-app.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027181/19272" target="_top" id="2027181">
  <img src="//a.impactradius-go.com/display-ad/19272-2027181" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027181/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Update or Reinstall the Biometric Drivers

 If the biometric service is already enabled, yet the fingerprint recognition feature isn't working, the biometric drivers could be outdated or corrupt. To ensure that isn't the case, update the biometric device drivers. To do so, follow these steps:

1. Type**"Device Manager"** in Windows Search and open the**Device Manager** app.
2. Expand the**Biometric devices** category.
3. Right-click on your fingerprint scanner device and select**Update driver** .  
![Update the Fingerprint Scanner Device in Windows Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/6-update-the-fingerprint-scanner-device-in-windows-device-manager.jpg)
4. Then, click on**Search automatically for drivers** .

 If updating the drivers does not fix the problem, right-click the biometric device again and select**Uninstall device** . After uninstalling the drivers, reboot your device, and Windows will automatically install them again. If you prefer, you can also download the relevant drivers from the manufacturer's website and install them manually.

## 6\. Disable Fast Startup

 According to some users on a[Microsoft community thread](https://answers.microsoft.com/en-us/windows/forum/all/fingerprint-reader-not-working/95cc0aef-2822-4b51-9f77-8697e6ace897) , disabling the Fast Startup feature has solved fingerprint recognition issues on their devices. Although Fast Startup speeds up your device's boot process, turning it on is known to cause unforeseen problems.

 So, if you also keep this feature enabled on your device, disable it to see if it makes a difference. Don't know how to do that? Refer to our guide on[enabling or disabling Fast Startup on Windows 11](https://www.makeuseof.com/windows-11-turn-on-or-off-fast-startup/) .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135375/19272" target="_top" id="2135375">
  <img src="//a.impactradius-go.com/display-ad/19272-2135375" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135375/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Ensure the Biometric Reader Isn't Disabled in BIOS

 Some laptops allow users to disable the fingerprint reader in BIOS. If you're setting up a fingerprint login for the first time and getting the error, ensure the fingerprint scanner isn't disabled in BIOS. Accessing BIOS and navigating to the option to enable or disable the biometric device varies between manufacturers.

 If you need guidance on accessing the BIOS and enabling the biometric device, visit your laptop manufacturer's website.

## 8\. When Nothing Else Works…

 If nothing else works, run the Hardware and Devices troubleshooter, enable biometrics in the Local Group Policy Editor, and check for account-specific issues. If these steps fail to resolve the issue, perform a system restore as a last resort. Our guide on[fixing Windows Hello fingerprint recognition](https://www.makeuseof.com/windows-hello-fingerprint-not-working/) explains how to make the above-mentioned changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123737/7443" target="_top" id="2123737">
  <img src="//a.impactradius-go.com/display-ad/7443-2123737" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123737/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get Rid of Annoying Fingerprint Recognition Errors

 If you encounter an error when setting up Windows Hello fingerprint recognition, it does not mean the feature can't be used. If your device supports biometric authentication, the above fixes will help you resolve the annoying error.

 If you are setting up a fingerprint login for the first time, make sure you do it correctly. Otherwise, you'll be constantly annoyed by the bothersome errors when using this fantastic feature.


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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-unlocking-potential-in-instagram-engagement-with-advanced-data-tools/"><u>[New] 2024 Approved  Unlocking Potential in Instagram Engagement with Advanced Data Tools</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-a-list-of-the-quickest-rising-youtube-spaces-for-encouragement/"><u>[New] In 2024, A List of the Quickest Rising YouTube Spaces for Encouragement</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-how-to-make-your-instagram-pop-with-sharing-gifs-in-4-easy-steps/"><u>[New] In 2024, How to Make Your Instagram Pop with Sharing GIFs in 4 Easy Steps</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-mastering-obs-for-live-skype-recording-for-2024/"><u>[New] Mastering OBS for Live Skype Recording for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-unleash-your-inner-tech-wizard-xbox-one-snapshot-secrets-revealed-for-2024/"><u>[New] Unleash Your Inner Tech Wizard  Xbox One Snapshot Secrets Revealed for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-fuse-fast-edits-for-stunning-windows-photos/"><u>[Updated] 2024 Approved  Fuse Fast Edits for Stunning Windows Photos</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-smooth-sailing-on-instagram-bypass-video-issues/"><u>[Updated] In 2024, Smooth Sailing on Instagram - Bypass Video Issues</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-capturing-the-essence-cinematic-techniques-at-their-best/"><u>2024 Approved  Capturing the Essence  Cinematic Techniques at Their Best</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-fiscal-landmarks-understanding-mr-beasts-financial-growth/"><u>2024 Approved  Fiscal Landmarks  Understanding Mr. Beast’s Financial Growth</u></a></li>
<li><a href="https://android-location.techidaily.com/3-effective-methods-to-fake-gps-location-on-android-for-your-nokia-g42-5g-drfone-by-drfone-virtual/"><u>3 Effective Methods to Fake GPS location on Android For your Nokia G42 5G | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/android-screen-stuck-general-infinix-note-30-pro-partly-screen-unresponsive-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Screen Stuck General Infinix Note 30 Pro Partly Screen Unresponsive | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/complete-guide-on-unlocking-iphone-12-pro-with-a-broken-screen-by-drfone-ios/"><u>Complete Guide on Unlocking iPhone 12 Pro with a Broken Screen?</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-virtual-machine-lineup-for-windows-11-users/"><u>Essential Virtual Machine Lineup for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-for-reviving-stalled-windows-11-menus/"><u>Guidelines for Reviving Stalled Windows 11 Menus</u></a></li>
<li><a href="https://buynow-info.techidaily.com/hilarity-ensues-as-martian-metropolis-emerges-amidst-chaotic-winds-and-playfulness/"><u>Hilarity Ensues as Martian Metropolis Emerges Amidst Chaotic Winds and Playfulness</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/how-and-where-to-find-a-shiny-stone-pokemon-for-apple-iphone-13-pro-max-drfone-by-drfone-virtual-ios/"><u>How and Where to Find a Shiny Stone Pokémon For Apple iPhone 13 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-activate-the-forgotten-windows-patcher/"><u>How to Activate the Forgotten Windows Patcher</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-entry-point-not-found-error-on-windows/"><u>How to Fix the Entry Point Not Found Error on Windows</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-any-poco-c65-phone-password-using-emergency-call-by-drfone-android/"><u>How To Unlock Any Poco C65 Phone Password Using Emergency Call</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-upgrade-or-downgrade-iphone-se-2022-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade iPhone SE (2022) Without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/identifying-and-correcting-incorrect-cpu-readouts-on-pc-monitor/"><u>Identifying and Correcting Incorrect CPU Readouts on PC Monitor</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-ultimate-guide-to-professional-photo-coloring/"><u>In 2024, The Ultimate Guide to Professional Photo Coloring</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/in-2024-unmatched-ai-tools-for-visual-storytelling/"><u>In 2024, Unmatched AI Tools for Visual Storytelling</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-cross-border-mouse-glance-using-powertoys-features/"><u>Master the Art of Cross-Border Mouse Glance Using PowerToys' Features</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-subsystem-top-practices-in-wsl-2-environments/"><u>Master the Subsystem: Top Practices in WSL 2 Environments</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-delete-confirmation-steps-on-modern-windows-pcs/"><u>Mastering Delete Confirmation Steps on Modern Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-efficiency-your-ultimate-guide-to-wsl-2-and-docker/"><u>Maximizing Efficiency: Your Ultimate Guide to WSL 2 & Docker</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-through-windows-key-settings-easily/"><u>Navigate Through Windows Key Settings Easily</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-computer-components-with-tom-a-detailed-guide-by-toms-hardware-experts/"><u>Navigating Computer Components with Tom - A Detailed Guide by Tom's Hardware Experts</u></a></li>
<li><a href="https://tech-hub.techidaily.com/navigating-relationships-with-ai-wisdom/"><u>Navigating Relationships with AI Wisdom</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-nvidia-connections-problems-on-win-11-os/"><u>Navigating Through NVIDIA Connections Problems on Win 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-memory-trouble/"><u>Navigating Through Windows' Memory Trouble</u></a></li>
<li><a href="https://windows11.techidaily.com/optimal-classic-gaming-experience-winning-with-scummvm-on-pc/"><u>Optimal Classic Gaming Experience: Winning with ScummVM on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-access-barrier-to-roblox-on-windows-pc/"><u>Overcoming Access Barrier to Roblox on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-hardware-limitations-in-windows-capture-errors/"><u>Overcoming Hardware Limitations in Windows Capture Errors</u></a></li>
<li><a href="https://games-able.techidaily.com/pro-gamers-guide-to-xbox-s-controller-dismantling/"><u>Pro Gamers' Guide to Xbox S Controller Dismantling</u></a></li>
<li><a href="https://windows11.techidaily.com/prolific-tools-in-windows-11-top-7-productivity-widgets/"><u>Prolific Tools in Windows 11: Top 7 Productivity Widgets</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-on-correction-of-network-error-0x800704b3-in-windows/"><u>Quick Guide on Correction of Network Error 0X800704B3 in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstallation-strategies-for-lost-render-device-in-ow2/"><u>Reinstallation Strategies for Lost Render Device in OW2</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstating-windows-notification-banners/"><u>Reinstating Windows Notification Banners</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-xc0f1103f-error-with-nvidias-software/"><u>Remedying XC0F1103F Error with NVIDIA's Software</u></a></li>
<li><a href="https://windows11.techidaily.com/reveling-in-windows-11s-covert-bar-locator/"><u>Reveling in Windows 11'S Covert Bar Locator</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-conversion-of-your-mp3-library-into-widespread-high-quality-audio-cds-with-imgburn/"><u>Seamless Conversion of Your Mp3 Library Into Widespread, High-Quality Audio Cds with ImgBurn</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-sound-management-in-windows-11/"><u>Simplifying Sound Management in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-windows-11-setup-without-internet/"><u>Step-by-Step: Windows 11 Setup Without Internet</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-approach-to-windows-11-arm-setup-from-iso/"><u>Stepwise Approach to Windows 11 ARM Setup From ISO</u></a></li>
<li><a href="https://windows11.techidaily.com/strategic-plan-to-secure-and-restore-notes/"><u>Strategic Plan to Secure and Restore Notes</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-app-overload-understanding-and-resolving-windows-0x80860010/"><u>Tackling App Overload: Understanding and Resolving Windows 0X80860010</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-printer-service-disabled-message-in-winos/"><u>Tackling Printer Service Disabled Message in WinOS</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-w11-tuning-lessen-resource-usage-for-users/"><u>Tailored W11 Tuning: Lessen Resource Usage for Users</u></a></li>
<li><a href="https://windows11.techidaily.com/the-8-best-video-cutting-apps-for-windows-11-and-11/"><u>The 8 Best Video Cutting Apps for Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-user-access-control-on-common-windows-systems/"><u>Transforming User Access Control on Common Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-the-other-users-microsoft-account-problem/"><u>Unblocking the Other User’s Microsoft Account Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-fixing-virtualbox-efail-windows-error/"><u>Understanding and Fixing Virtualbox E_FAIL (Windows) Error</u></a></li>
<li><a href="https://windows11.techidaily.com/what-is-hardware-accelerated-gpu-scheduling-on-windows-heres-how-to-disable-it/"><u>What Is Hardware-Accelerated GPU Scheduling on Windows? Here's How to Disable It</u></a></li>
<li><a href="https://windows11.techidaily.com/win-storage-management-finding-and-reducing-high-space-items/"><u>Win Storage Management: Finding and Reducing High-Space Items</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-xpvista7-hacks-beat-non-compatible-problems/"><u>Windows XP/Vista/7 Hacks: Beat Non-Compatible Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/wintools-insight-exploring-differences-in-chkdsk-and-sfcs-use/"><u>WinTools Insight: Exploring Differences in CHKDSK and SFC's Use</u></a></li>
</ul></div>
