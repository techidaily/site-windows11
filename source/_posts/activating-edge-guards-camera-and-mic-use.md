---
title: "Activating Edge Guards: Camera & Mic Use"
date: 2024-07-11T22:19:24.964Z
updated: 2024-07-12T22:19:24.964Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Activating Edge Guards: Camera & Mic Use"
excerpt: "This Article Describes Activating Edge Guards: Camera & Mic Use"
keywords: Edge Guard Activation,Microphone Control,Camera Security Enable,Phone Safety Lockdown,Privacy Mode Engage,Secure Call Function,Device Surveillance On
thumbnail: https://thmb.techidaily.com/5996397f505d52b0f60ffe77c36fd8859621590a57dd0707f44eeaa06c560dbc.jpg
---

## Activating Edge Guards: Camera & Mic Use

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
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-share-and-celebrate-with-instagram-videos/"><u>[Updated] In 2024, Share & Celebrate with Instagram Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-change-your-username-in-windows-11/"><u>How to Change Your Username in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-asking-too-many-hands-at-once-errors/"><u>Troubleshoot Asking Too Many Hands at Once Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-power-of-your-keyboard-for-app-dimension-control-in-win11/"><u>Unlock the Power of Your Keyboard for App Dimension Control in Win11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-expanding-digital-presence-stream-to-youtube-plus-additional-platforms-for-2024/"><u>[Updated] Expanding Digital Presence  Stream to YouTube + Additional Platforms for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-infinite-twitterscape-embracing-the-hd-experience/"><u>[Updated] Infinite Twitterscape - Embracing the HD Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-batched-taskbar-visual-elements/"><u>Correcting Batched Taskbar Visual Elements</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/time-lapse-video-editing-top-picks-for-free-and-paid-tools-for-2024/"><u>Time-Lapse Video Editing Top Picks for Free and Paid Tools for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-nvidia-control-panel-not-opening-in-windows-11/"><u>How to Fix the NVIDIA Control Panel Not Opening in Windows 11</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-essential-guide-to-photo-backdrop-removal-in-picsart-for-2024/"><u>The Essential Guide to Photo Backdrop Removal in Picsart for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/a-systematic-approach-to-undoing-windows-programs-changes/"><u>A Systematic Approach to Undoing Windows Programs Changes</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-enable-the-home-section-in-the-settings-app-in-windows-11/"><u>How to Enable the Home Section in the Settings App in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-ride-on-windows-discover-top-5-budget-enhancers/"><u>Elevate Your Ride on Windows: Discover Top 5 Budget Enhancers</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-package-control-with-winget-on-win11/"><u>Navigating Package Control with Winget on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-windows-11-lock-screen-swiftly/"><u>Bypass Windows 11 Lock Screen Swiftly</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-optimal-window-size-on-windows-11/"><u>Configuring Optimal Window Size on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-batch-convert-heic-images-to-jpeg-format-in-windows-10-and-11/"><u>How to Batch Convert HEIC Images to JPEG Format in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/activatingdeactivating-windows-setup-service-on-pcs/"><u>Activating/Deactivating Windows Setup Service on PCs</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-audience-enhancement-with-audition-fades/"><u>2024 Approved  Audience Enhancement with Audition Fades</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-nokia-g22-drfone-by-drfone-virtual-android/"><u>How to get the dragon scale and evolution-enabled pokemon On Nokia G22? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-failed-office-activation-on-pcs-and-laptops/"><u>Conquering Failed Office Activation on PCs and Laptops</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-fixing-disk-read-errors/"><u>Master the Art of Fixing Disk Read Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprerant-users-resourceful-approach-to-processes-and-themes-in-windows-11/"><u>A Compreran't User's Resourceful Approach to Processes and Themes in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-user-mastery-group-and-admin-essentials-guide/"><u>Windows 11 User Mastery: Group & Admin Essentials Guide</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-delete-icloud-account-remove-your-apple-id-permanently-on-apple-iphone-6s-by-drfone-ios/"><u>How To Delete iCloud Account Remove Your Apple ID Permanently On Apple iPhone 6s</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-cut-trim-and-edit-avi-videos-with-the-best-tools-windows-mac-android-iphone-online/"><u>Updated In 2024, Cut, Trim, and Edit AVI Videos with the Best Tools Windows, MAC, Android, iPhone, Online</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-to-address-missing-windows-1011-search-data/"><u>Guidelines to Address Missing Windows 10/11 Search Data</u></a></li>
<li><a href="https://windows11.techidaily.com/decorating-windows-11-with-a-christmas-twist/"><u>Decorating Windows 11 with a Christmas Twist</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-not-a-valid-profile-warning-in-win1011/"><u>Troubleshooting 'Not a Valid Profile' Warning in Win10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-edge-windows-photo-management-software/"><u>Cutting-Edge Windows Photo Management Software</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-snipeater-glitches-fix-strategies-here/"><u>Navigating SnipEater Glitches: Fix Strategies Here</u></a></li>
<li><a href="https://youtube-help.techidaily.com/increasing-youtube-views-through-consistency-in-creative-commons-compliance-for-2024/"><u>Increasing YouTube Views Through Consistency in Creative Commons Compliance for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/configure-ideal-window-space-for-your-apps-in-win11/"><u>Configure Ideal Window Space for Your Apps in Win11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/pokemon-go-error-12-failed-to-detect-location-on-motorola-moto-g24-drfone-by-drfone-virtual-android/"><u>Pokemon Go Error 12 Failed to Detect Location On Motorola Moto G24? | Dr.fone</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-audio-file-conversion-simplified-top-6-software-solutions/"><u>In 2024, Audio File Conversion Simplified Top 6 Software Solutions</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-maximizing-reach-in-tiktok-ads-methods-and-highlighted-campaigns/"><u>[Updated] In 2024, Maximizing Reach in TikTok Ads  Methods & Highlighted Campaigns</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-free-avi-video-rotation-tools-top-picks-for-windows-mac-android-and-iphone/"><u>New In 2024, Free AVI Video Rotation Tools Top Picks for Windows, MAC, Android, and iPhone</u></a></li>
<li><a href="https://windows11.techidaily.com/creative-walls-for-your-pc-windows-1011-guide/"><u>Creative Walls for Your PC: Windows 10/11 Guide</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-frp-hijacker-by-hagard-download-and-bypass-your-oppo-a78-frp-locks-by-drfone-android/"><u>In 2024, FRP Hijacker by Hagard Download and Bypass your Oppo A78 FRP Locks</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-email-management-gmail-in-outlook-windows-edition/"><u>Effortless Email Management: Gmail in Outlook, Windows Edition</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-from-struggling-youtuber-to-industry-leader-the-hub-of-creator-studios-wisdom/"><u>[Updated] 2024 Approved  From Struggling Youtuber to Industry Leader  The Hub of Creator Studio's Wisdom</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-customizing-the-twitter-interface-an-experts-tutorial-for-video-images/"><u>[Updated] In 2024, Customizing the Twitter Interface  An Expert's Tutorial for Video Images</u></a></li>
<li><a href="https://screen-recording.techidaily.com/1715860863400-in-2024-easy-gaming-memories-start-recording-now/"><u>In 2024, Easy Gaming Memories  Start Recording Now!</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-apple-iphone-11-pro-max-drfone-by-drfone-virtual-ios/"><u>Why Your WhatsApp Location is Not Updating and How to Fix On Apple iPhone 11 Pro Max | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-preeminent-windows-calls-8-top-picks-for-2024/"><u>[Updated] Preeminent Windows Calls  8 Top Picks for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/unleashing-creativity-the-top-10-final-cut-pro-movies/"><u>Unleashing Creativity The Top 10 Final Cut Pro Movies</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-top-picks-affordable-high-quality-4k-home-theatres/"><u>[Updated] Top Picks  Affordable, High Quality 4K Home Theatres</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-how-to-erase-past-safety-checks-on-windows/"><u>Expert Tips: How to Erase Past Safety Checks on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-output-amplitude-for-external-windows-11-audio/"><u>Elevating Output Amplitude for External Windows 11 Audio</u></a></li>
<li><a href="https://windows11.techidaily.com/erase-your-black-screen-and-clear-cursor-issues-in-win11/"><u>Erase Your Black Screen & Clear Cursor Issues in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooters-guide-unlocking-photoshop-on-windows-1011/"><u>Troubleshooters' Guide: Unlocking Photoshop on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-potential-in-vintage-gear-installation-of-22h2-win11/"><u>Unleash Potential in Vintage Gear: Installation of 22H2 Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/device-dialogue-diplomacy-android-plus-pc-sync-guide/"><u>Device Dialogue Diplomacy: Android + PC Sync Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/what-actions-can-you-take-if-windows-ignores-powershell/"><u>What Actions Can You Take if Windows Ignores PowerShell?</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-the-mold-unleashing-dormant-windows-11-powers/"><u>Breaking the Mold: Unleashing Dormant Windows 11 Powers</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/updated-iosandandroid-best-apps-to-create-animoji-and-memoji-videos/"><u>Updated IOS&Android Best Apps to Create Animoji and Memoji Videos</u></a></li>
<li><a href="https://printer-issues.techidaily.com/fixing-online-offline-print-status-anomaly/"><u>Fixing Online-Offline Print Status Anomaly</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-a-guide-to-copying-file-and-folder-navigational-trails-via-6-steps/"><u>Windows 11: A Guide to Copying File and Folder Navigational Trails, via 6 Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-innovation-best-windows-devices-for-24/"><u>Exploring Innovation - Best Windows Devices for '24</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/captivating-creations-the-best-video-effects-on-tiktok/"><u>Captivating Creations  The Best Video Effects on TikTok</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-create-a-viral-hit-10-best-music-video-producers/"><u>New In 2024, Create a Viral Hit 10 Best Music Video Producers</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-microsoft-store-app-on-win11-pcs/"><u>Enabling Microsoft Store App on Win11 PCs</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-beyond-the-basics-5-advanced-tips-for-using-the-16x9-ratio-calculator/"><u>New In 2024, Beyond the Basics 5 Advanced Tips for Using the 16X9 Ratio Calculator</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-the-gap-enabling-smooth-steam-connection/"><u>Mending the Gap: Enabling Smooth Steam Connection</u></a></li>
<li><a href="https://windows11.techidaily.com/harmonious-hardware-connections-android-pc-junctions/"><u>Harmonious Hardware Connections: Android-PC Junctions</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-hardware-utilization-four-ways-to-open-the-disk-manager-in-windows-11/"><u>Boost Hardware Utilization: Four Ways to Open the Disk Manager in Windows 11</u></a></li>
</ul></div>
