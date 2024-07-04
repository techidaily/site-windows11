---
title: Addressing Black/White Displays in Windows Store App
date: 2024-07-03T11:19:24.770Z
updated: 2024-07-04T11:19:24.770Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Black/White Displays in Windows Store App
excerpt: This Article Describes Addressing Black/White Displays in Windows Store App
keywords: Black Display Window App,White Screen Windows App,Windows Black Disp Issue,Color Screen Windows Store,Display Black Vs. Windows,Windows App Black/White Conflict,Resolve Windows Black Screen
thumbnail: https://thmb.techidaily.com/efc2d305e478474af3e17a5e089941fb3280acaab989de35873f384ab0ed53cb.jpg
---

## Addressing Black/White Displays in Windows Store App

 If you’re looking for a new app to install on your Windows computer, chances are you’re using Microsoft Store.

 Microsoft Store has the advantage that every listed app is certified by Microsoft, so there’s no chance of hidden malware or virus. Also, you can download movies and TV shows.

 But if the store is displaying a white or black screen, you will not be able to get any new apps or movies. However, you can easily get back Microsoft Store functionality by going through the steps below.

## 1\. Restart the Microsoft Store

 Microsoft Store showing a black or white screen might be due to a temporary glitch. In this case, restarting the app should be enough to fix it.

 Once you close Microsoft Store, press**Ctrl + Shift + Esc** to bring up Task Manager. Then, open the**Processes** tab. Right-click**Microsoft Store** and select**End task** to close any process that might be running in the background.

![Clost Microsoft Store tasks](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/end-microsoft-store-1.jpg)

Open Microsoft Store again and check if it’s now working.

 If you're encountering a lot of glitches that go away after a restart, you might be leaving your PC on for too long. Check out these [reasons why you should turn off your PC every night](https://www.makeuseof.com/reasons-why-should-shut-down-computer/) for some inspiration.

## 2\. Check Your Internet Connection

 There might be nothing wrong with Microsoft Store, but you’re simply having an internet connectivity problem. If you’re [dealing with an unstable WiFi connection](https://www.makeuseof.com/tag/fix-slow-unstable-wi-fi-connection/) or downloading a large file, Microsoft Store might display a black or white screen.

 If possible, access the store from a different device. If everything works as usual, the problem is limited to your computer.

## 3\. Run the Microsoft Store Troubleshooter

 Every time you run into an issue on your Windows computer, try running the corresponding troubleshooter. These tools are designed to fix any generic issues that you may encounter.

 So, for any trouble regarding the Microsoft Store, you should run the Windows Store Apps troubleshooter. Here’s how to do it:

1. Right-click the**Start** button and go to**Settings** .
2. Click**System > Troubleshoot** .
3. Select**Other trouble-shooters** .
4. Click the**Run** button next to**Windows Store Apps** .

![Run Windows app troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/store-troubleshooter-1.jpg)

 Windows will search for any issues and fix them automatically. Once the process is complete, try to launch Microsoft Store again.

## 4\. Delete the Microsoft Store Cache

 Like most apps, Microsoft Store uses cache to improve performance. But if the app’s cache somehow gets corrupted, you’ll run into all sorts of issues, including Microsoft Store displaying a black or white background every time you open the app. In this case, deleting the cache should fix the problem.

 Press**Win + R** to bring up a Run dialog. Then, type**wsreset.exe** , and press**Shift + Enter** to run the command with administrative rights.

 This should open a blank Command Prompt window for several seconds. Once it deletes the cache, Windows will close Command Prompt and launch the Microsoft Store app.

## 5\. Run the SFC Tool

 There’s a chance that Microsoft Store isn’t working as usual due to corrupt or damaged system files. To fix the issue, you should run the Windows System File Checker tool.

 First, launch Command Prompt with administrative rights. Then, type**sfc/ scannow** and press**Enter** .

 Make sure you don’t close the Command Prompt window until the scan is complete. Windows will search and automatically replace any corrupt or damaged system files.

![Run SFC scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/sfc-scan-1-3.jpg)

## 6\. Check Your System's Set Time and Region

 Microsoft Store servers must be synced with your system, so everything works properly. If your computer’s time and region, Microsoft Store will show a black, white, or even blue screen.

Go through the below steps to change the Windows region:

1. Press**Win + I** to bring up Windows Settings.
2. From the left-hand menu, click**Time & language** .
3. Select**Language & region** .
4. Set**Country or region** to your current region.
5. Restart your computer and check if Microsoft Store is working.

![Change Windows region](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-region-1.jpg)

 Also, you can [manually change Windows date and time settings](https://www.makeuseof.com/windows-11-change-date-time/) .

## 7\. Re-register the Microsoft Store

 If you couldn’t get Microsoft Store to work using the above solutions, you should re-register the app through PowerShell. The process is quite easy and fast.

 First, launch PowerShell with administrative rights. If you don't know how to do this, refer to [how to open PowerShell with administrative rights](https://www.makeuseof.com/windows-11-powershell-administrator/) .

 Then, copy the **Get-AppXPackage \*WindowsStore\* -AllUsers | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($\_.InstallLocation)\\AppXManifest.xml"}** command, and press**Enter** to run it.

## 8\. Reset Your Windows PC

 If Microsoft Store showing a black or white screen isn’t the only problem you noticed, there might be some deep corruption within your system files. In this case, you could try to [factory reset your Windows PC](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) . This will revert it back to its factory settings, so make sure you back up all essential data.

## Get the Microsoft Store Working Again

 It can be frustrating when you need to install a new app, but Microsoft Store isn’t working. Instead of looking for the same app on not-so-trustworthy websites, you can use the above solutions to fix Microsoft Store.

 But if you can’t find a specific app, there are several websites where you can download apps without compromising your system security.


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
<li><a href="https://windows11.techidaily.com/efficient-resource-scheduling-for-android-on-windows-wsl/"><u>Efficient Resource Scheduling for Android on Windows WSL</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-the-absence-of-dxgidll-in-new-os-windows-11/"><u>Mending the Absence of Dxgi.dll in New OS, Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-11s-insufficient-uninstall-rights/"><u>Fixing Windows 11'S Insufficient Uninstall Rights</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-pcs-duration-before-lockdown/"><u>Adjusting PC's Duration Before Lockdown</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-the-8-anomalies-in-windows-11s-ui/"><u>Dissecting the 8 Anomalies in Windows 11'S UI</u></a></li>
<li><a href="https://windows11.techidaily.com/approaches-to-fix-failed-launch-of-lunar-client-in-windows/"><u>Approaches to Fix Failed Launch of Lunar Client in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-interruptions-in-geforce-links-with-os-1011/"><u>Fixing Interruptions in GeForce Links with OS 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/method-to-rectify-the-zero-x-error-on-windows-11s-mail-app/"><u>Method to Rectify the Zero X Error on Windows 11’S Mail App</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-roadblocks-activating-non-functional-scripts-in-windows/"><u>Overcoming Roadblocks: Activating Non-Functional Scripts in Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-pokemon-emerald-master-ball-cheat-on-huawei-nova-y91-drfone-by-drfone-virtual-android/"><u>How to Use Pokémon Emerald Master Ball Cheat On Huawei Nova Y91 | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-secure-and-unshakable-direct-url-addition-on-your-tiktok-profile/"><u>[New] Secure & Unshakable  Direct URL Addition on Your TikTok Profile</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-the-anticipated-retro-inspired-ballads-and-blues-to-listen-to-for-2024/"><u>Updated The Anticipated Retro-Inspired Ballads & Blues to Listen To for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-professional-selections-best-5-interactive-capture-apps/"><u>[New] 2024 Approved  Professional Selections  Best 5 Interactive Capture Apps</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-get-tech-savvy-expert-guide-for-mac-screen-recording-via-shortcuts/"><u>[Updated] 2024 Approved  Get Tech-Savvy  Expert Guide for Mac Screen Recording via Shortcuts</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-revamp-your-tiktok-videos-insightful-strategies-for-backdrop-changes/"><u>[Updated] Revamp Your TikTok Videos  Insightful Strategies for Backdrop Changes</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/in-2024-unwatermark-your-tiktok-videos-top-online-tools-and-tricks/"><u>In 2024, Unwatermark Your TikTok Videos Top Online Tools and Tricks</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-masterful-melodies-discovering-the-top-software-for-capturing-guitars/"><u>New 2024 Approved Masterful Melodies Discovering the Top Software for Capturing Guitars</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-unlock-your-disabled-apple-iphone-12-mini-without-itunes-in-5-ways-by-drfone-ios/"><u>In 2024, Unlock Your Disabled Apple iPhone 12 mini Without iTunes in 5 Ways</u></a></li>
<li><a href="https://android-unlock.techidaily.com/the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-samsung-galaxy-s23-tactical-edition-device-by-drfone-android/"><u>The Ultimate Guide How to Bypass Swipe Screen to Unlock on Samsung Galaxy S23 Tactical Edition Device</u></a></li>
</ul></div>
