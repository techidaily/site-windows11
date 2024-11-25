---
title: "Reboot and Reclaim: Resetting MS Store in Windows 10/11"
date: 2024-11-23T22:11:30.962Z
updated: 2024-11-24T16:52:58.624Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Reboot and Reclaim: Resetting MS Store in Windows 10/11"
excerpt: "This Article Describes Reboot and Reclaim: Resetting MS Store in Windows 10/11"
keywords: MS Store Reset Guide,Windows Store Repair,Windows 10/11 Cleanup,Removing Apps From Store,Resetting App Listings,Reclaiming Store Space,Optimizing MS Store
thumbnail: https://thmb.techidaily.com/0fffdaf6b0345d8277ec9fafebd3429c28f703cd8774f81e39bb2cfd9b5790b4.jpg
---

## Reboot and Reclaim: Resetting MS Store in Windows 10/11

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LeKJBWb6Jhk?si=AnViizAPiIT1YCRA&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gSKkJrJ57EA?si=WDOmInPE9EgQa_tB&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the[Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

To re-register Microsoft Store apps for the current user:

1. Press the**Win** key and type "powershell" into the Search bar.
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell console, type the following command and press**Enter** :  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
4. Wait for the command to execute and complete. You may see a blue loading graphic.
5. Once done, type**exit** and press**Enter** to close PowerShell.

 During the process, you may see some errors highlighted in red. It is due to PowerShell trying to reinstall existing apps on Windows. So, ignore the error and wait for the process to complete.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aIx71tPaWKg?si=lG5OiUe-M6eBJf5b&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pGHmqD53gc8?si=ymgHIB6Aa7_MoUUf&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3hS27nZVi9Y?si=_Zqj_l4a4XkPqT2S&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Install and Re-Register All Microsoft Store Apps on Windows 11

 Re-registering Windows apps is often necessary when Microsoft Store is not working. It can also help deal with other Windows settings and apps. If the issue persists, try the built-in Windows Store Apps troubleshooter to fix common Microsoft Store app issues.

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
<li><a href="https://screen-capture.techidaily.com/new-top-6-best-capture-cards-for-nintendo-switch-you-can-find/"><u>[New] Top 6 Best Capture Cards for Nintendo Switch You Can Find</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-techniques-to-archivalize-chat-communication-in-whatsapp/"><u>[Updated] 2024 Approved Techniques to Archivalize Chat Communication in WhatsApp</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-7-key-tools-to-convert-youtube-videos-easily/"><u>[Updated] 7 Key Tools to Convert YouTube Videos Easily</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-fine-tuning-minecrafts-ram-for-better-gaming-results-for-2024/"><u>[Updated] Fine-Tuning Minecraft's RAM for Better Gaming Results for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-unlock-social-media-8-free-fb-extractors-for-2024/"><u>[Updated] Unlock Social Media 8 FREE FB Extractors for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-ice-and-velocity-memorable-moments-from-the-winter-olympics-snowboard-race/"><u>2024 Approved Ice & Velocity Memorable Moments From the Winter Olympics Snowboard Race</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-perfecting-your-live-stream-our-picks-from-the-top-6-microphones/"><u>2024 Approved Perfecting Your Live Stream Our Picks From the Top 6 Microphones</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/detailed-guide-of-ispoofer-for-pogo-installation-on-honor-magic5-ultimate-drfone-by-drfone-virtual-android/"><u>Detailed guide of ispoofer for pogo installation On Honor Magic5 Ultimate | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-freeze-resolving-steam-problems-during-games-on-win-11/"><u>Fixing the Freeze: Resolving Steam Problems During Games on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/hdd-or-ssd-windows-methods-to-identify-storage-disks/"><u>HDD or SSD? Windows Methods to Identify Storage Disks</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-finger-movements-win11-keybindings-unveiled/"><u>Innovative Finger Movements: Win11 Keybindings Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/key-insights-into-microsoft-family-safety-usage/"><u>Key Insights Into Microsoft Family Safety Usage</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-high-dpi-adjustments-for-better-viewing/"><u>Mastering Window's High DPI Adjustments for Better Viewing</u></a></li>
<li><a href="https://win-able.techidaily.com/overcome-discord-network-issues-with-these-packet-loss-solutions/"><u>Overcome Discord Network Issues with These Packet Loss Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/regaining-lost-plans-windows-11-power-reset/"><u>Regaining Lost Plans: Windows 11 Power Reset</u></a></li>
<li><a href="https://windows11.techidaily.com/simplify-your-routine-nircmds-command-shortcuts-expertise/"><u>Simplify Your Routine: NirCmd's Command Shortcuts Expertise</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-turn-back-the-dial-from-dark-ui/"><u>Techniques to Turn Back the Dial From Dark UI</u></a></li>
<li><a href="https://tech-hub.techidaily.com/ultimate-list-of-favorite-chatgpt-triggers-found-on-github/"><u>Ultimate List of Favorite ChatGPT Triggers Found on GitHub</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-safeguards-restricted-by-admins/"><u>Unlocking Windows Safeguards Restricted by Admins</u></a></li>
</ul></div>

