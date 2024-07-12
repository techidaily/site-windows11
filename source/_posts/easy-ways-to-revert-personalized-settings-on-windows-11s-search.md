---
title: Easy Ways to Revert Personalized Settings on Windows 11'S Search
date: 2024-07-11T21:11:50.746Z
updated: 2024-07-12T21:11:50.746Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Easy Ways to Revert Personalized Settings on Windows 11'S Search
excerpt: This Article Describes Easy Ways to Revert Personalized Settings on Windows 11'S Search
keywords: Win11 Search Reset,Personalize Restore Windows,Windows 11 Privacy Change,Revert Window Settings,Quick Search Options Fix,Customize Windows Search,Revive Search Preferences
thumbnail: https://thmb.techidaily.com/030f43c520c13566e766031892a27e4f35e056dc768bf0f9b9c3aff2261e980f.jpg
---

## Easy Ways to Revert Personalized Settings on Windows 11'S Search

 Like any other computer program, Windows Search can sometimes develop issues that require you to reset its settings to work properly. This article explains two simple ways to reset Windows Search settings back to default. Let's look at each one in detail.

## Why Should You Reset Windows Search Settings?

 Windows Search tracks files and folders on your hard drive, so you can find them more quickly. However, over time search settings and preferences can become corrupted, leading to incorrect search results or slow performance. To get the most effective results from Windows Search, you should periodically reset your search settings.

 Resetting search settings on Windows can improve search speed and accuracy. It gets rid of useless data and resolves errors or conflicts due to stored information. This can ultimately enhance your computer’s performance and provide a more efficient search experience.

 Let's now explore how to reset Windows Search settings.

## 1\. Tweak the Registry Editor

 If you want to reset Windows Search settings back to default, you can modify the registry editor. It involves directly changing certain keys in the Windows Registry, which can sometimes become risky if done incorrectly.

 To avoid this issue, be sure to [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before proceeding. Once done, follow these steps.

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the dialog box and hit the Enter key.
3. When the UAC prompt appears on the screen, click **Yes** to continue.
4. In the Registry Editor window, navigate to the following path:  
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows Search  
 You can also copy and paste the path into the address bar at the top of the window and hit the Enter key. This will take you to the Windows Search section.
5. Now move to the right pane and search for the key named **SetupCompletedSuccessfully**.  
![Reset Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-search.jpg)
6. Select this key, right-click on it, and choose **Modify**.
7. Set the value to **0** and click **OK** to save the changes.

 If the SetupCompletedSuccessfully key is missing, you will have to manually create it. To do this, right-click on the Windows Search key and select **New > DWORD (32-bit) Value**. Name this newly created key as **SetupCompletedSuccessfully** and set its value to **0**.

 After performing the steps above, close the Registry Editor and restart your computer for the changes to take effect.

## 2\. Use Windows PowerShell

 If you prefer command-line solutions, you can use PowerShell to reset Windows Search settings. It involves running a few simple commands to restore search settings. Here's how to do it.

[Open the Microsoft Download Page](https://www.microsoft.com/en-us/download/100295) and download the ResetWindowsSearchBox.ps1 PowerShell script. Once downloaded, right-click on the file and select **Run with PowerShell**.

 If you see an error message _"Cannot be loaded because the running script is disabled on this system"_ you need to enable script execution first. To do that, [open PowerShell as a system administrator](http://www.makeuseof.com/windows-11-powershell-administrator/). Then type **Get-ExecutionPolicy** and press Enter.

![Restrict or Unrestrict the Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restrict-or-unrestrict-the-command.png)

 If the output is **Restricted**, execute the following command to allow PowerShell scripts:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted

 After setting the execution policy, try running the ResetWindowsSearchBox.ps1 file again. Once the script is executed successfully, it resets Windows search settings.

![Reset Windows Search Via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-search-via-powershell.png)

 After resetting the Windows Search settings, you can restore the execution policy to its original settings. To do that, open PowerShell as an administrator again and execute the following command:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Restricted

 Once the execution policy is set back to its original value, restart your computer. The Windows Search settings should now be restored to their default state.

## Easy Ways to Reset Windows Search

 Resetting Windows search settings can fix any issues you may have with your search experience. This guide will teach you how to reset Windows Search settings to their original values.


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
<li><a href="https://windows11.techidaily.com/step-by-step-guide-to-extending-windows-1011-contextual-commands/"><u>Step-by-Step Guide to Extending Windows 10/11 Contextual Commands</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/step-by-step-tutorial-for-aspiring-mukbang-creators-for-2024/"><u>Step-by-Step Tutorial for Aspiring Mukbang Creators for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-extract-audio-from-webm-files-top-10-converter-tools/"><u>2024 Approved Extract Audio From WebM Files Top 10 Converter Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-failure-to-launch-on-windows-speech-recognition/"><u>Overcoming Failure to Launch on Windows Speech Recognition</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-file-restoration-top-8-techniques-for-windows/"><u>Mastering File Restoration: Top 8 Techniques for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-could-not-create-vm-problems-in-microsoft-os/"><u>Remedying 'Could Not Create VM' Problems in Microsoft OS</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-nitpicking-colors-8-tips-for-a-neutral-desktop/"><u>Navigating Nitpicking Colors: 8 Tips for a Neutral Desktop</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/1719581815703-bridging-worlds-essential-strategies-for-effective-intercultural-communication/"><u>Bridging Worlds: Essential Strategies for Effective Intercultural Communication</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-windows-backup-configuration-recollection/"><u>Steps for Windows Backup Configuration Recollection</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-exemplary-melodies-set-for-visual-narratives/"><u>In 2024, Exemplary Melodies Set for Visual Narratives</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-device-id-extraction-techniques-for-windows-users/"><u>Mastery of Device ID Extraction Techniques for Windows Users</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-picking-your-perfect-pair-dji-drones-face-off-with-gopro-and-insta360-cameras/"><u>[New] Picking Your Perfect Pair  DJi Drones Face-Off With GoPro and Insta360 Cameras</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-internet-connection-league-of-legends-on-windows/"><u>Mastering Internet Connection: League of Legends on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-reliability-of-your-windows-interface/"><u>Enhancing Reliability of Your Windows Interface</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-pros-approach-to-optimizing-zoom-settings/"><u>2024 Approved  The Pro's Approach to Optimizing Zoom Settings</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-card-on-motorola-g54-5g-online-without-jailbreak-by-drfone-android/"><u>How to Unlock SIM Card on Motorola G54 5G online without jailbreak</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-the-secret-sauce-of-compelling-tiktok-footage-on-mac/"><u>In 2024, The Secret Sauce of Compelling TikTok Footage on Mac</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-dissecting-the-livestream-battlefield-twitch-vs-youtube/"><u>2024 Approved  Dissecting the Livestream Battlefield  Twitch vs YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-freeze-flaws-in-adobes-pc-artist-suite/"><u>Mending Freeze Flaws in Adobe's PC Artist Suite</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-banner-bliss-savor-your-complimentary-set-of-designs/"><u>[New] Banner Bliss  Savor Your Complimentary Set of Designs!</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11s-s-mode-is-it-worth-considering/"><u>Navigating Windows 11'S 'S Mode': Is It Worth Considering?</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-nubia-red-magic-9-proplusfrp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Nubia Red Magic 9 Pro+FRP Lock</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-mastering-fbs-look-back-feature-edit-tutorial/"><u>[Updated] In 2024, Mastering FB's Look Back Feature  Edit Tutorial</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-files-6-methods-to-retrieve-windows-11-paths/"><u>Mastering Files: 6 Methods to Retrieve Windows 11 Paths</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-unveiling-the-best-practices-for-crafting-viral-instagram-reels/"><u>[Updated] 2024 Approved  Unveiling the Best Practices for Crafting Viral Instagram Reels</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/2024-approved-video-editing-for-dummies-10-essential-youtube-insights/"><u>2024 Approved  Video Editing for Dummies  10 Essential YouTube Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/resuscitate-stalled-excel-performance-in-windows-environment/"><u>Resuscitate Stalled Excel Performance in Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-setup-google-play-on-windows-11/"><u>Quick Setup: Google Play on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/eradicating-printers-from-windows-system/"><u>Eradicating Printers From Windows System</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-3-ways-to-change-location-on-facebook-marketplace-for-zte-axon-40-lite-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Change Location on Facebook Marketplace for ZTE Axon 40 Lite | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-switch-strikes-top-10-fighting-game-picks/"><u>[New] 2024 Approved  Switch Strikes  Top 10 Fighting Game Picks</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-controlling-windows-11s-content-filter/"><u>Guide: Controlling Windows 11’S Content Filter</u></a></li>
<li><a href="https://windows11.techidaily.com/recover-hidden-5ghz-link-in-windows-11-using-these-fixes/"><u>Recover Hidden 5GHz Link in Windows 11 Using These Fixes</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-the-exclusion-dilemma-is-someone-hidden-on-snapchat/"><u>[Updated] The Exclusion Dilemma  Is Someone Hidden On Snapchat?</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-quick-snapback-to-loss-prevention/"><u>[Updated] Quick Snapback to Loss Prevention</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-screen-resolution-problems-in-windows-os/"><u>Rectifying Screen Resolution Problems in Windows OS</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-vibrant-discourse-evaluation-ver-8/"><u>[New] 2024 Approved  Vibrant Discourse Evaluation - Ver. 8</u></a></li>
<li><a href="https://windows11.techidaily.com/multiply-your-efforts-mastering-multiple-directory-creation-in-win11plus11/"><u>Multiply Your Efforts: Mastering Multiple Directory Creation in Win11+11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-pen-pad-glitches/"><u>Overcoming Windows Pen-Pad Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/prtscn-and-snipping-tool-link-in-windows-11-prevent-connection/"><u>PrtScn & Snipping Tool Link in Windows 11: Prevent Connection</u></a></li>
<li><a href="https://windows11.techidaily.com/microsofts-surface-studio-2-a-step-towards-perfection/"><u>Microsoft's Surface Studio 2 - A Step Towards Perfection?</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-language-input-change-keyboard-layouts-in-win-11/"><u>Simplifying Language Input: Change Keyboard Layouts in Win 11</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-ensuring-legitimacy-of-your-youtube-sign-in/"><u>In 2024, Ensuring Legitimacy of Your YouTube Sign-In</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-facebook-dating-for-your-oneplus-ace-3-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location On Facebook Dating for your OnePlus Ace 3 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-fixing-windows-11s-5ghz-connectivity/"><u>Mastering the Art of Fixing Windows 11'S 5GHz Connectivity</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-pokemon-go-cooldown-chart-on-samsung-galaxy-s23-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, Pokémon Go Cooldown Chart On Samsung Galaxy S23 Ultra | Dr.fone</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-link-sounds-to-visual-elements-in-ppt/"><u>[Updated] In 2024, Link Sounds to Visual Elements in PPT</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-15-most-effective-live-sports-streaming-methods-for-2024/"><u>The 15 Most Effective Live Sports Streaming Methods for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-screen-capture-mastery-windows-edition-free-3-methods-for-2024/"><u>[New] Screen Capture Mastery  Windows Edition (Free, 3 Methods) for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-window-icon-positions/"><u>Mastery Over Window Icon Positions</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-how-to-deactivate-amdnvidia-vr-boosting/"><u>Guide: How to Deactivate AMD/Nvidia VR Boosting</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-change-the-windows-subsystem-for-androids-resource-usage/"><u>How to Change the Windows Subsystem for Android's Resource Usage</u></a></li>
</ul></div>
