---
title: "Access Control: Microphone and Camera via Edge Protection"
date: 2024-07-11T21:11:37.028Z
updated: 2024-07-12T21:11:37.028Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Access Control: Microphone and Camera via Edge Protection"
excerpt: "This Article Describes Access Control: Microphone and Camera via Edge Protection"
keywords: Edge Security Access,Microphone Cam Control,Edge Privacy Settings,Edge Device Management,Edge Encryption Safety,Secure Edge Cameras,Audio-Visual Edge Protect
thumbnail: https://thmb.techidaily.com/b41dfc1747c954c2591d35270b4a20079e5707f867334ccdc51bba558ecb898b.jpg
---

## Access Control: Microphone and Camera via Edge Protection

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

 However, before you make any changes, it's essential that you [create a backup of the registry file](https://www.makeuseof.com/tag/backup-restore-windows-registry/) just in case something goes wrong.

 To enable your mic & camera with the help of this tool, follow these steps:

1. Search for**regedit** in the Windows search bar and click on the result to open the registry editor. To find out more, see [how to open the registry](https://www.makeuseof.com/windows-11-open-registry-editor/) .
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
<li><a href="https://windows11.techidaily.com/how-to-bypass-windows-defenders-exclusive-software-lockdown/"><u>How to Bypass Windows Defender's Exclusive Software Lockdown</u></a></li>
<li><a href="https://windows11.techidaily.com/enablingdisabling-text-emphasis-in-windows-11/"><u>Enabling/Disabling Text Emphasis in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/get-rid-of-the-standout-wallpaper-icon-in-win11/"><u>Get Rid of the Standout Wallpaper Icon in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-windows-upgrade-glitch-error-0xc1900101/"><u>Decoding Windows Upgrade Glitch: Error #0xC1900101</u></a></li>
<li><a href="https://windows11.techidaily.com/keyboard-and-mouse-failure-windows-11-sleep-troubleshoot/"><u>Keyboard & Mouse Failure: Windows 11 Sleep Troubleshoot</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-visibility-of-missing-cameras-on-device-management-screen/"><u>Enhance Visibility of Missing Cameras on Device Management Screen</u></a></li>
<li><a href="https://extra-information.techidaily.com/understanding-imovies-editing-edge/"><u>Understanding iMovie's Editing Edge</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/boost-views-with-your-own-youtube-thumbnail-design-for-2024/"><u>Boost Views with Your Own YouTube Thumbnail Design for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/masterful-methods-to-overcome-security-errors-in-windows-11/"><u>Masterful Methods to Overcome Security Errors in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-compact-icons-arrangement-in-system-interface/"><u>Fixing Compact Icons Arrangement in System Interface</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-2024-approved-chromebook-voice-memos-made-simple-8-easy-techniques/"><u>Updated 2024 Approved Chromebook Voice Memos Made Simple 8 Easy Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-system-stability-post-windows-update-with-wsl-in-focus/"><u>Enhancing System Stability Post-Windows Update with WSL in Focus</u></a></li>
<li><a href="https://windows11.techidaily.com/monitoring-login-trials-detecting-successfulfailed-windows-access/"><u>Monitoring Login Trials: Detecting Successful/Failed Windows Access</u></a></li>
<li><a href="https://windows11.techidaily.com/howtomakenotepadwindowssmoothatnight/"><u>HowToMakeNotepadWIndowsSmoothAtNight</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/select-and-download-exclusive-tailored-audio-templates-for-2024/"><u>Select & Download Exclusive Tailored Audio Templates for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tuning-win11-startup-processes/"><u>Fine-Tuning Win11 Startup Processes</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-a-compreenas-guide-for-enhancing-your-facecam-recordings/"><u>[New] 2024 Approved  A Compreenas Guide for Enhancing Your Facecam Recordings</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11-for-sticky-note-usage/"><u>Navigating Windows 11 for Sticky Note Usage</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-the-10-best-free-dvd-players-compatible-with-windows-10/"><u>New In 2024, The 10 Best Free DVD Players Compatible with Windows 10</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-unlocking-sound-customization-adjusting-loudness-in-videoaudio-archives/"><u>2024 Approved Unlocking Sound Customization Adjusting Loudness in Video/Audio Archives</u></a></li>
<li><a href="https://windows11.techidaily.com/discerning-win-credentials-success-from-failure-scenarios/"><u>Discerning Win Credentials Success From Failure Scenarios</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-restore-windows-photo-viewer-in-windows-1111/"><u>How to Restore Windows Photo Viewer in Windows 11/11</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-front-doors-windows-desktop-sites/"><u>Digital Front Doors: Windows Desktop Sites</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-tweak-the-mouse-pointer-accessibility-settings-on-windows-11/"><u>How to Tweak the Mouse Pointer Accessibility Settings on Windows 11</u></a></li>
<li><a href="https://some-skills.techidaily.com/top-ranked-ai-enhanced-image-maker-for-2024/"><u>Top-Ranked AI Enhanced Image Maker for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-secure-transfer-of-textual-data-via-edges-guardspace-win11-version/"><u>Enabling Secure Transfer of Textual Data via Edges Guardspace, Win11 Version</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-2022-olympic-highlights-in-short-track-racing/"><u>In 2024, 2022 Olympic Highlights in Short Track Racing</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-whirlwind-wonders-your-itinerary-of-outrageous-tiktok-battles/"><u>[New] Whirlwind Wonders  Your Itinerary of Outrageous TikTok Battles</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-easily-unlock-your-lava-agni-2-5g-device-sim-by-drfone-android/"><u>In 2024, Easily Unlock Your Lava Agni 2 5G Device SIM</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-through-utorrent-sync-failures-on-windows-devices/"><u>Guiding Through uTorrent Sync Failures on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/easily-solve-nvidiae-experience-scanner-woes-on-windows/"><u>Easily Solve Nvidia'e Experience Scanner Woes on Windows</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2023s-top-social-moment-infographics-for-2024/"><u>[Updated] 2023'S Top Social Moment Infographics for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/perfecting-iphoneipad-screenshots-a-youtube-guide/"><u>Perfecting iPhone/iPad Screenshots  A YouTube Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-microsoft-store-error-0x00000000-in-windows-os/"><u>Eliminating Microsoft Store Error 0X00000000 in Windows OS</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/unleashing-classic-psp-gaming-best-ios-emulators-ranked-for-2024/"><u>Unleashing Classic PSP Gaming  Best iOS Emulators Ranked for 2024</u></a></li>
</ul></div>
