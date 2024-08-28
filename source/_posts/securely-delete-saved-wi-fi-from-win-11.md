---
title: Securely Delete Saved Wi-Fi From Win 11
date: 2024-08-27T16:08:25.804Z
updated: 2024-08-28T16:08:25.804Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Securely Delete Saved Wi-Fi From Win 11
excerpt: This Article Describes Securely Delete Saved Wi-Fi From Win 11
keywords: Wi-Fi Security (Win 11),Win 11 Wi-Fi Remove,Secure Network Deletion,Wi-Fi History Clearance (Win),Safe Wi-Fi Removal Win11,Protect Wi-Fi Info Delete,Secure Wi-Fi Clearance (Win11)
thumbnail: https://thmb.techidaily.com/1b6976e6cb0861a8e856af8d9b91eb1dc370f068cc6322414a1134e31c0876a0.jpg
---

## Securely Delete Saved Wi-Fi From Win 11

 By default, Windows 11 remembers any Wi-Fi network you connect to. This allows Windows to automatically connect to the network whenever it is in range. If you don’t want that to happen, you can simply remove the network from your PC.

 From time to time, you may want to remove some old Wi-Fi networks that you once connected to but never will again. In this guide, we'll show you four different ways to remove a saved Wi-Fi network from Windows 11.

## The Benefits of Removing Old Wi-Fi Networks From Windows 11

 While having a long list of saved Wi-Fi networks isn’t necessarily a bad thing, there may be times when you want to remove specific Wi-Fi networks from your PC.

 For example, if you previously connected your PC to a free public network but do not intend to use it again, it is best to simply remove the network. Or perhaps you don't want your PC to automatically connect to a specific network when it’s in range. Besides, forgetting and rejoining a network also happens to be an effective solution for fixing minor connection issues.

 Over time, your PC may accumulate a long list of Wi-Fi networks that you won't be connecting to. In such cases, it makes sense to remove old and unused Wi-Fi networks from your PC.

## 1\. Remove a Saved Wi-Fi Network Using the Quick Settings Panel

 The Quick Settings panel on Windows provides access to some commonly used settings. It also makes it simple to remove a saved Wi-Fi network from Windows 11.

 Press**Win + A** to open the Quick Settings panel. Click the sideways-facing arrow next to the**Wi-Fi** button. You'll see a list of Wi-Fi networks, including the one to which you're currently connected. Right-click on the network you want to remove and select**Forget** .

![Remove Wi-Fi Network From Quick Settings Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Remove-Wi-Fi-Network-From-Quick-Settings-Panel.jpg)

 Like using the Quick Settings on Windows? Check out[how to customize the Quick Settings panel on your Windows 11 computer](http://www.makeuseof.com/windows-11-customize-quick-settings-menu/) .

## 2\. Remove a Saved Wi-Fi Network via the Settings App

 If the Wi-Fi network you want to remove is not nearby, it will not appear in the Quick Settings panel. In that case, you can use the Windows 11 Settings app to remove it.

To forget a Wi-Fi network via the Settings app:

1. Press**Win + I** to open the Settings app.
2. Navigate to the**Network & internet** tab and click on**Wi-Fi** .
3. Click on**Manage known networks** .
4. Click the**Forget** button next to a network to delete it.  
![Remove Wi-Fi Network on Windows From the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Remove-Wi-Fi-Network-on-Windows-From-the-Settings-App.jpg)

<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 And that's about it. Once you click the**Forget** button, Windows will remove the network profile associated with that network.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
## 3\. Remove a Saved Wi-Fi Network With Command Prompt or PowerShell

 Another option for removing a saved Wi-Fi network is to use a command-line tool such as Command Prompt or Windows PowerShell. You can easily forget a Wi-Fi network by running a couple of commands in the terminal window. Here’s how you can go about it.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**command prompt** or**windows powershell** and select**Run as administrator** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the console, type the following command and press**Enter** to view a list of saved Wi-Fi networks on your PC.  
`netsh wlan show profiles`
5. Note down the name of the network profile you want to remove.
6. Paste the following command, replace**WIFIName** with the network name, and press**Enter** .  
`netsh wlan delete profile name="WIFIName"`  
![Delete a Saved Wi-Fi Profile Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Delete-a-Saved-Wi-Fi-Profile-Using-Command-Prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
 You can repeat the above command to remove as many networks as you want. Conveniently, the command-line tool also lets you remove all the saved Wi-Fi networks at once. To do so, use this command:

`netsh wlan delete profile name=* i=*`

## 4\. Remove a Saved Wi-Fi Network Using Registry Editor

 If you’re feeling adventurous, you can also use the Registry Editor to remove a saved Wi-Fi network from Windows. Since deleting registry files is risky, you should only use this method if the other ones do not work.

 If you decide to use this method, make sure you back up all your registry files just in case. If you need help, check our guide on[how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

To remove a Wi-Fi network using the Registry Editor:

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** and press**Enter** . This will open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **Computer > HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows NT > CurrentVersion > NetworkList > Profiles** .
5. Within the**Profiles** key, you’ll find several subkeys. Each key represents a network profile.
6. Select a subkey and look for the**ProfileName** DWORD on your right to identify the name of the network.
7. Once you find the key corresponding to your network, right-click on it and select**Delete** .
8. Select**Yes** to confirm.  
![Remove Wi-Fi Network on Windows Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Remove-Wi-Fi-Network-on-Windows-Using-Registry-Editor.jpg)

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Once you complete the above steps, the saved profile will be removed from your system.

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
## How to Reconnect to a Forgotten Wi-Fi Network on Windows 11

 You can always reconnect to a Wi-Fi network later after forgetting it. For that, you'll need to manually select the network and enter the password for authentication.

 To connect to a Wi-Fi network on Windows 11, press**Win + A** to open the Quick Settings panel. Click the arrow next to the Wi-Fi button to view a list of nearby networks. Select the network you want to connect to and click the**Connect** button. Enter the password for that network and you should be good.

![Connect to a Wi-Fi Network Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Connect-to-a-Wi-Fi-Network-Windows-11.jpg)

 Of course, this isn't the only way to connect to a Wi-Fi network on Windows. Refer to our guide on[different ways to connect to Wi-Fi on Windows](https://www.makeuseof.com/windows-ways-to-connect-to-wifi/) to learn more.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## Removing Saved Wi-Fi Networks From Windows 11

 Although there are no significant disadvantages to keeping old Wi-Fi networks on your PC, you may want to delete some of them just to keep things tidy. Luckily, Windows 11 offers ample ways to remove unused Wi-Fi networks.

 Aside from deleting old Wi-Fi networks, you can also manage wireless network profiles on Windows in a few different ways.


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
<li><a href="https://youtube-sure.techidaily.com/024-approved-the-ultimate-outro-checklist-for-youtube-success/"><u>[New] 2024 Approved  The Ultimate Outro Checklist for YouTube Success</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-smooth-transitions-in-photography-mastering-face-focused-motion-blur-in-picsart/"><u>[New] Smooth Transitions in Photography  Mastering Face-Focused Motion Blur in Picsart</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-easy-to-learn-art-of-earning-wealth-reddits-ultimate-guide/"><u>[Updated] The Easy-to-Learn Art of Earning Wealth  Reddit's Ultimate Guide</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-top-tips-tuning-your-snapchat-videos-for-maximum-impact/"><u>2024 Approved  Top Tips  Tuning Your Snapchat Videos for Maximum Impact</u></a></li>
<li><a href="https://howto.techidaily.com/8-solutions-to-solve-youtube-app-crashing-on-motorola-moto-g73-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Solutions to Solve YouTube App Crashing on Motorola Moto G73 5G | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/calls-on-honor-90-gt-go-straight-to-voicemail-12-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Calls on Honor 90 GT Go Straight to Voicemail? 12 Fixes | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/essential-tips-for-organizing-online-gatherings-google-meet-for-2024/"><u>Essential Tips for Organizing Online Gatherings (Google Meet) for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/excellent-fps-software-for-windows-gamers-the-creme-de-la-creme-list/"><u>Excellent FPS Software For Windows Gamers: The Crème De La Crème List</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-from-poco-c65-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock from Poco C65 Phones with/without a PC</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-prolong-windows-10-restart-time-while-tasks-run/"><u>How to Prolong Windows 10 Restart Time While Tasks Run</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-speed-up-the-yuzu-emulator-on-windows/"><u>How to Speed Up the Yuzu Emulator on Windows</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-unbrick-a-dead-vivo-y27-4g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Unbrick a Dead Vivo Y27 4G | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-realme-10t-5g-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Realme 10T 5G</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-activate-and-use-life360-ghost-mode-on-samsung-galaxy-s23-tactical-edition-drfone-by-drfone-virtual-android/"><u>In 2024, How To Activate and Use Life360 Ghost Mode On Samsung Galaxy S23 Tactical Edition | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-ideal-mac-video-logic-tool/"><u>In 2024, Ideal Mac Video Logic Tool</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-latest-guide-how-to-bypass-oppo-reno-11-5g-frp-without-computer-by-drfone-android/"><u>In 2024, Latest Guide How To Bypass Oppo Reno 11 5G FRP Without Computer</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-top-5-samsung-galaxy-s24-ultra-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>In 2024, Top 5 Samsung Galaxy S24 Ultra Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://windows11.techidaily.com/instant-admin-access-to-command-prompt-in-windows/"><u>Instant Admin Access to Command Prompt in Windows</u></a></li>
<li><a href="https://extra-tips.techidaily.com/investigating-ffmpeg-for-intact-audio-preservation/"><u>Investigating FFmpeg for Intact Audio Preservation</u></a></li>
<li><a href="https://windows11.techidaily.com/is-enhancement-or-extra-cost-justified-for-win-11s-add-ons/"><u>Is Enhancement or Extra Cost Justified for Win 11'S Add-Ons?</u></a></li>
<li><a href="https://windows11.techidaily.com/m06-headphones-seamless-wireless-interfacing-unveiled/"><u>M06 Headphones: Seamless Wireless Interfacing Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/making-the-right-windows-11-call-home-vs-premium-features/"><u>Making the Right Windows 11 Call: Home Vs. Premium Features</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-camera-fix-up-windows-11s-error-code-a00f4289-demystified/"><u>Mastering Camera Fix-Up: Windows 11'S Error Code A00F4289 Demystified</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-successful-files-transfer-in-windows/"><u>Mastering the Art of Successful Files Transfer in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-keeping-windows-time-unchanged/"><u>Mastery over Keeping Windows Time Unchanged</u></a></li>
<li><a href="https://windows11.techidaily.com/maximize-graphics-performance-with-1-6-tools-for-windows-pcs/"><u>Maximize Graphics Performance with #1-#6 Tools for Windows PCs</u></a></li>
<li><a href="https://extra-tips.techidaily.com/maximizing-b-roll-effective-techniques-for-enhancing-videos/"><u>Maximizing B-Roll  Effective Techniques for Enhancing Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-prevent-windows-pc-from-booting-into-bios/"><u>Methods to Prevent Windows PC From Booting Into BIOS</u></a></li>
<li><a href="https://windows11.techidaily.com/microphone-woes-troubleshooting-in-google-meet-on-windows/"><u>Microphone Woes: Troubleshooting in Google Meet on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/move-your-onedrive-step-by-step-for-windows-11/"><u>Move Your OneDrive: Step-by-Step for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-intel-hd-error-in-meeting-minimum-requirements/"><u>Navigating Through Intel HD Error in Meeting Minimum Requirements</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-remote-desktop-windows-problems/"><u>Navigating Through Remote Desktop Windows Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-corruption-write-restoration-in-windows-systems/"><u>Preventing Corruption: Write Restoration in Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/repairing-lopsided-one-side-windows-headphone-sounds/"><u>Repairing Lopsided One-Side Windows Headphone Sounds</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-failures-of-file-segmentation-service/"><u>Resolving Failures of File Segmentation Service</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-usb30-device-failure-on-windows-oses/"><u>Resolving USB3.0 Device Failure on Windows OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-taskbar-button-image-rendering/"><u>Restoring Taskbar Button Image Rendering</u></a></li>
<li><a href="https://windows11.techidaily.com/reversing-operation-failure-0x709-on-pc/"><u>Reversing Operation Failure 0X709 on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/seamlessly-navigate-anywhere-the-art-of-cross-border-mouse-usage/"><u>Seamlessly Navigate Anywhere - The Art of Cross-Border Mouse Usage</u></a></li>
<li><a href="https://windows11.techidaily.com/securely-resetting-dns-on-the-latest-windows-version/"><u>Securely Resetting DNS on the Latest Windows Version</u></a></li>
<li><a href="https://windows11.techidaily.com/skyrocket-success-in-windows-11-with-these-top-5-apps/"><u>Skyrocket Success in Windows 11 With These Top 5 Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/skyrocketing-yuzu-speeds-on-windows-devices/"><u>Skyrocketing Yuzu Speeds on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-language-shift-keyboard-shortcuts-for-windows-11-users/"><u>Speedy Language Shift: Keyboard Shortcuts for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-folder-integration-overcoming-onedrives-error/"><u>Streamlining Folder Integration: Overcoming OneDrive's Error</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-system-performance-with-lav-filters-in-windows/"><u>Streamlining System Performance with LAV Filters in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-obstacle-of-file-creation-windows-error-30005/"><u>Tackling the Obstacle of File Creation - Windows Error 30005</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-on-windows-11s-direct-image-viewing/"><u>Turn On Windows 11'S Direct Image Viewing</u></a></li>
<li><a href="https://windows11.techidaily.com/turning-classic-computers-into-modern-windows-11-hubs-with-tools/"><u>Turning Classic Computers Into Modern Windows 11 Hubs with Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-full-potential-of-windows-11-calendar/"><u>Unlocking Full Potential of Windows 11 Calendar</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-setting-up-microsoft-pc-manager/"><u>Win 11: Setting Up Microsoft PC Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-stop-intelligent-assistant/"><u>Windows 11: Stop Intelligent Assistant</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-tricks-bringing-off-screen-apps-back-to-life-with-6-tips/"><u>Windows Tricks: Bringing Off-Screen Apps Back to Life with 6 Tips</u></a></li>
</ul></div>
