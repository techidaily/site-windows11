---
title: Navigating Windows 11’S App Guard for Cam/Mic
date: 2024-08-31T22:06:00.538Z
updated: 2024-09-01T22:06:00.538Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Windows 11’S App Guard for Cam/Mic
excerpt: This Article Describes Navigating Windows 11’S App Guard for Cam/Mic
keywords: Windows 11 SecureApps,MicCaptureControl,CamAudioGuard,Windows11Protect,MicrophoneLockdown,CameraShieldWindows,VoiceInputSecurity
thumbnail: https://thmb.techidaily.com/a7150b4ff2ea7550c12f390526178357d28d5879ccd1eca0b9ed1b9c559e12d9.jpg
---

## Navigating Windows 11’S App Guard for Cam/Mic

 Microsoft's Application Guard for Edge is a great tool to shield your browsing from malicious interference. For extra protection, both the camera and microphone are deactivated by default in this environment; however, there may be times when you need these features enabled to utilize certain web applications.

 If that’s the case, follow this guide which will show you how to enable the camera and microphone in Application Guard for Edge on Windows 11\. ​​​​​​

## 1\. How to Enable the Camera and Microphone via Windows Settings

 To enable the camera and microphone in Application Guard for Edge, follow the steps below:

1. Click on Start, type**Settings** and press**Enter** .
2. On the left side of the screen, select**Privacy & security** .
3. Click the**Windows Security** option on the right.
4. Then, on the next screen, select**App & browser control** .
5. In the new window that opens, click**Change Application Guard settings** under Isolated browsing.
6. Look for the**Camera and microphone** option, and then toggle it on.  
![Enable Camera and Microphone in Application Guard Using Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-camera-and-microphone-in-application-guard-using-windows-settings.jpg)
7. If the UAC prompt appears, click**Yes** to continue.

 After you perform the above action, restart your computer for the changes to take effect. Upon restarting, all your camera and microphone settings should now be applied to the Application Guard for Edge.

 In case you need to turn off the feature again, just follow the same steps and toggle the Camera and microphone option to Off. That’s all there is to it.

## 2\. How to Enable the Camera and Microphone Using Registry Editor

 If you are more comfortable using the registry editor, you can enable your camera and microphone for Application Guard for Edge. All you need to do is open up the registry folder, make a few easy modifications, and restart your computer so that they can take effect.

 However, before you make any changes, it's essential that you[create a backup of the registry file](https://www.makeuseof.com/tag/backup-restore-windows-registry/) just in case something goes wrong.

 To enable your mic & camera with the help of this tool, follow these steps:

1. Search for**regedit** in the Windows search bar and click on the result to open the registry editor. To find out more, see[how to open the registry](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. When the UAC prompt appears, click**Yes** to confirm.
3. In the Registry Editor window, go to the following location:  
Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Hvsi  
 Copy and paste the given location into the address bar at the top of the registry window and press Enter to quickly jump to the folder.
4. If you don't see the**Hvsi** key there, you need to create it first. In order to do this, right-click on the**Microsoft** folder and select**New > Key** .
5. Name the file**Hvsi** , then hit**Enter** to save it.  
![Creating a new DWORD (32-bit) Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-dword-enableclipboard-key.jpg)
6. Right-click on Hvsi, choose**New > DWORD (32-bit) Value** , then name it**EnableCameraMicrophoneRedirection** .
7. Now double-click on the newly created DWORD key, and you will see a pop-up window appear.
8. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Camera and Microphone in Application Guard Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-camera-and-microphone-in-application-guard-using-registry-editor.jpg)
9. Then click**OK** to save the changes.

 Once you've done editing the registry, restart your computer to apply the changes. After restarting, Edge's Application Guard will be able to access your camera and microphone hardware for websites that require it.

 If you want to revert the changes, simply set the EnableCameraMicrophoneRedirection key’s value back to**0** and restart your computer.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
## Your Camera and Mic Is Now Supported in Edge Application Guard

 Application Guard for Edge is a tool that serves as an extra layer of protection from malicious websites and other threats. By default, your camera and microphone are disabled to ensure maximum security. In this guide, we've explained two quick ways in which you can easily activate these features - via Windows Settings or Registry Editor.


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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-exclusive-mcb-logo-designs-and-templates/"><u>[New] 2024 Approved  Exclusive MCB Logo Designs and Templates</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-seamless-integration-of-nvidia-screener-techniques/"><u>[New] 2024 Approved  Seamless Integration of NVIDIA Screener Techniques</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-your-ultimate-source-for-online-video-to-mp3-downloads/"><u>[New] 2024 Approved  Your Ultimate Source for Online Video to MP3 Downloads</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-banishing-auditory-distractions-a-guide-on-audacitys-noise-reduction-for-2024/"><u>[New] Banishing Auditory Distractions  A Guide on Audacity's Noise Reduction for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-audio-interface-mastery-your-podcast-setup-savior/"><u>[New] In 2024, Audio Interface Mastery  Your Podcast Setup Savior</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-peak-laughter-edit-suite/"><u>[New] Peak Laughter Edit Suite</u></a></li>
<li><a href="https://network-issues.techidaily.com/resolved-fluctuating-led-on-dell-laptop/"><u>[Resolved] Fluctuating LED on Dell Laptop</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-accelerate-lost-snap-content-find/"><u>[Updated] 2024 Approved  Accelerate Lost Snap Content Find</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-excellence-in-selfies-the-top-8-for-iphone/"><u>[Updated] 2024 Approved  Excellence in Selfies  The Top #8 for IPhone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-initiating-engagement-start-your-live-on-instagram/"><u>[Updated] 2024 Approved  Initiating Engagement  Start Your Live on Instagram</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-crafting-engaging-vids-with-template-magic-for-2024/"><u>[Updated] Crafting Engaging Vids with Template Magic for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-how-to-snappify-your-macs-viewport/"><u>[Updated] In 2024, How To Snappify Your Mac's Viewport</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-iphone-photography-excellence-follow-the-top-10-rules/"><u>[Updated] In 2024, IPhone Photography Excellence  Follow the Top 10 Rules</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-top-mobile-experiences-ios-and-androids-vr-hits-for-2024/"><u>[Updated] Top Mobile Experiences  IOS & Android's VR Hits for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unlocking-iphone-capabilities-crafting-and-transforming-slow-videos/"><u>[Updated] Unlocking iPhone Capabilities  Crafting & Transforming Slow Videos</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-view-count-value-how-much-does-1-million-matter-for-2024/"><u>[Updated] View Count Value  How Much Does 1 Million Matter for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/5-crucial-tasks-to-complete-when-starting-with-your-new-desktop/"><u>5 Crucial Tasks to Complete When Starting with Your New Desktop</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/elevate-your-sketches-essential-free-drawing-software-on-mac/"><u>Elevate Your Sketches - Essential Free Drawing Software on Mac</u></a></li>
<li><a href="https://windows11.techidaily.com/finding-fix-for-non-functional-vss-in-win/"><u>Finding Fix for Non-Functional VSS in Win</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-media-player-server-crash/"><u>Fixing Media Player Server Crash</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/going-back-in-time-your-android-movie-method/"><u>Going Back in Time  Your Android Movie Method</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-overcoming-lol-launch-lag/"><u>Guide to Overcoming LOL Launch Lag</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-postpone-windows-10-shutdown-during-active-processes/"><u>Guide to Postpone Windows 10 Shutdown During Active Processes</u></a></li>
<li><a href="https://sound-issues.techidaily.com/guide-how-to-get-your-conexant-smartaudio-hd-working-again-for-a-perfect-sound-experience-on-windows-11/"><u>Guide: How to Get Your Conexant SmartAudio HD Working Again for a Perfect Sound Experience on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-steps-for-ms-office-installation-on-windows-1011/"><u>Guiding Steps for MS Office Installation on Windows 10/11</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-google-frp-lock-on-asus-rog-phone-7-ultimate-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock on Asus ROG Phone 7 Ultimate Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-force-delete-or-uninstall-a-printer-in-windows-10-and-11/"><u>How to Force Delete or Uninstall a Printer in Windows 10 & 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-do-you-get-sun-stone-evolutions-in-pokemon-for-itel-p40-drfone-by-drfone-virtual-android/"><u>In 2024, How Do You Get Sun Stone Evolutions in Pokémon For Itel P40? | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-instructor-insights-choosing-the-prime-video-capturing-technology/"><u>In 2024, Instructor Insights  Choosing the Prime Video Capturing Technology</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-art-of-fast-forwarding-safely-expedite-your-spotify-experience/"><u>In 2024, The Art of Fast-Forwarding  Safely Expedite Your Spotify Experience</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-unlock-your-poco-x5-pro-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>In 2024, Unlock Your Poco X5 Pro Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/leverage-latest-proven-wsl-2-methods-on-windows-systems/"><u>Leverage Latest: Proven WSL 2 Methods on Windows Systems</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/mastering-wirecast-for-facebook-live-broadcasts/"><u>Mastering Wirecast for Facebook Live Broadcasts</u></a></li>
<li><a href="https://windows11.techidaily.com/modify-default-task-manager-viewport-in-win11/"><u>Modify Default Task Manager Viewport in Win11</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-run-lumafusion-on-mac-download-and-alternative-options-for-2024/"><u>New Run Lumafusion on Mac Download and Alternative Options for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-keyboard-interface-with-personalized-fn-keys-in-windows-11/"><u>Optimizing Keyboard Interface with Personalized FN Keys in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-task-failures-restore-windows-schedules/"><u>Overcome Task Failures, Restore Windows Schedules</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-usb-device-errors-on-windows-pcs/"><u>Overcoming USB Device Errors on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/personalized-overheat-avoidance-bios-tutorial-for-win-users/"><u>Personalized Overheat Avoidance: BIOS Tutorial for Win Users</u></a></li>
<li><a href="https://windows11.techidaily.com/regain-your-control-restoring-synapse-on-w10-and-w11/"><u>Regain Your Control: Restoring Synapse on W10 & W11</u></a></li>
<li><a href="https://windows11.techidaily.com/regaining-composure-post-high-living-days-for-windows-users/"><u>Regaining Composure Post-High Living Days, for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/reigniting-frozen-discord-overlay-a-stepwise-guide-for-windows-users/"><u>Reigniting Frozen Discord Overlay: A Stepwise Guide for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-error-code-0x0001-on-nvidias-geforce-with-windows-11/"><u>Resolving Error Code 0X0001 on Nvidia's GeForce with Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-vanished-windows-badge-icons/"><u>Reviving Vanished Windows Badge Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-phone-integration-for-retailers-using-windows-11-and-intel-unison/"><u>Seamless Phone Integration for Retailers Using Windows 11 & Intel Unison</u></a></li>
<li><a href="https://windows11.techidaily.com/security-refresh-windows-firewalls-five-commandments/"><u>Security Refresh: Windows Firewall's Five Commandments</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/sim-unlock-poco-f5-pro-5g-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>Sim Unlock Poco F5 Pro 5G Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/smooth-operations-at-low-cost-leverage-w11-pro-key/"><u>Smooth Operations at Low Cost: Leverage W11 Pro Key</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-disregard-error-components-not-present-in-win10win11/"><u>Steps to Disregard Error: Components Not Present in Win10/Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-spontaneous-scrolls-a-winworlders-guide/"><u>Stop Spontaneous Scrolls: A Winworlder's Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/strategic-shopping-for-cost-efficient-windows-11-keys/"><u>Strategic Shopping for Cost-Efficient Windows 11 Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-decrease-high-cpu-consumption-by-dropbox-on-windows/"><u>Strategies to Decrease High CPU Consumption by Dropbox on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-windows-update-failures-error-x712/"><u>Tackling Windows Update Failures: Error X712</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-picture-previews-in-windows-11-ui/"><u>Tailoring Picture Previews in Windows 11 UI</u></a></li>
<li><a href="https://unlock-android.techidaily.com/the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-tecno-pop-7-pro-by-drfone-android/"><u>The Top 5 Android Apps That Use Fingerprint Sensor to Lock Your Apps On Tecno Pop 7 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-access-denial-in-windows-11-a-quick-guide-to-5-solutions/"><u>Troubleshooting Access Denial in Windows 11: A Quick Guide to 5 Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/ultimate-list-wins-premier-video-trimming-tools/"><u>Ultimate List: Win's Premier Video Trimming Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/unique-apps-for-a-stylish-windows-clock-display/"><u>Unique Apps for a Stylish Windows Clock Display</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-a-flapping-discord-overlay-on-pc/"><u>Unraveling the Mystery of a Flapping Discord Overlay on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-superiority-win11-vs-macos-facts/"><u>Unveiling the Superiority: Win11 vs MacOS Facts</u></a></li>
<li><a href="https://howto.techidaily.com/why-your-samsung-galaxy-s23-screen-might-be-unresponsive-and-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Your Samsung Galaxy S23 Screen Might be Unresponsive and How to Fix It | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11s-vanishing-icons-restoration-strategies/"><u>Win 11'S Vanishing Icons - Restoration Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-1110-hacks-swift-recovery-of-synapse-functions/"><u>Windows 11/10 Hacks: Swift Recovery of Synapse Functions</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-virtual-machines-matching-windows-11-specs/"><u>Winning Virtual Machines Matching Windows 11 Specs</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-with-both-wi-fi-and-ethernet-connections-on-your-computer/"><u>Winning with Both Wi-Fi & Ethernet Connections on Your Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/wireless-gaming-ps3-pad-to-windows-network/"><u>Wireless Gaming: PS3 Pad to Windows Network</u></a></li>
</ul></div>
