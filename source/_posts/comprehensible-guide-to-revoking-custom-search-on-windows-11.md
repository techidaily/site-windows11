---
title: Comprehensible Guide to Revoking Custom Search on Windows 11
date: 2024-07-11T22:21:37.984Z
updated: 2024-07-12T22:21:37.984Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Comprehensible Guide to Revoking Custom Search on Windows 11
excerpt: This Article Describes Comprehensible Guide to Revoking Custom Search on Windows 11
keywords: Windows 11 Search Reset,Revoke Windows Custom Search,Clearing Search History W11,Disable Windows Personalized Search,Revoking SOS on Windows 11,Remove WinSearch Settings,Unset Personalized Windows Search
thumbnail: https://thmb.techidaily.com/85be9153d8c81024583588a94ed9e00fc880777ac2a8c7cff5efd5d21044d91c.jpg
---

## Comprehensible Guide to Revoking Custom Search on Windows 11

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
<li><a href="https://tiktok-videos.techidaily.com/updated-essential-tips-for-bigger-head-visual-effects-on-tiktok-clips-3-key-techniques/"><u>[Updated] Essential Tips for Bigger-Head Visual Effects on TikTok Clips (3 Key Techniques)</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-the-ultimate-toolbox-for-unraveling-instagrams-hidden-data/"><u>[New] 2024 Approved  The Ultimate Toolbox for Unraveling Instagram's Hidden Data</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-disparities-microsoft-and-default-windows-login-types/"><u>Dissecting Disparities: Microsoft and Default Windows Login Types</u></a></li>
<li><a href="https://windows11.techidaily.com/compre-written-guide-to-repair-xbox-live-glitches/"><u>Compre Written Guide To Repair Xbox Live Glitches</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-bypass-icloud-activation-lock-with-imei-code-from-your-apple-iphone-7-by-drfone-ios/"><u>In 2024, Bypass iCloud Activation Lock with IMEI Code From your Apple iPhone 7</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-discord-setup-woes-on-windows-11/"><u>Correcting Discord Setup Woes on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-window-experience-mastering-the-start-menu/"><u>Enhance Your Window Experience: Mastering the Start Menu</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-10-password-cracking-tools-for-vivo-x90s-by-drfone-android/"><u>In 2024, Top 10 Password Cracking Tools For Vivo X90S</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-the-purpose-of-pagefilesys-within-os-structure/"><u>Dissecting the Purpose of Pagefile.sys Within OS Structure</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-windows-xc0f1103f-geforce-not-working/"><u>Correcting Windows' XC0F1103F GeForce Not Working</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-realme-12plus-5g-by-drfone-android/"><u>In 2024, 10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Realme 12+ 5G</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-seamless-srt-to-sub-a-comprehensive-guide/"><u>[New] Seamless SRT to SUB  A Comprehensive Guide</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-from-sluggish-to-speedy-select-android-tools/"><u>[Updated] From Sluggish to Speedy  Select Android Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/curbing-the-noise-quiet-explore-tab-behavior/"><u>Curbing the Noise: Quiet Explore Tab Behavior</u></a></li>
<li><a href="https://windows11.techidaily.com/combat-unknown-obs-record-error-on-windows-11-pc/"><u>Combat Unknown OBS Record Error on Windows 11 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-code-of-high-quality-visuals-with-windows-11-hdr/"><u>Deciphering the Code of High-Quality Visuals with Windows 11 HDR</u></a></li>
<li><a href="https://windows11.techidaily.com/defeating-defunct-windows-security-hurdles-in-win-11/"><u>Defeating Defunct Windows Security Hurdles in Win 11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/defeat-synthetic-followers-for-true-popularity-peak-for-2024/"><u>Defeat Synthetic Followers for True Popularity Peak for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/dial-back-the-dread-of-an-unresponsive-esc-button-in-windows/"><u>Dial Back the Dread of an Unresponsive Esc Button in Windows</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-mastering-the-art-of-crafting-compelling-video-testimonials/"><u>In 2024, Mastering the Art of Crafting Compelling Video Testimonials</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-camera-access-overlap-in-windows-apps/"><u>Correcting Camera Access Overlap in Windows Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-to-unfreezing-window-taskbar/"><u>Comprehensive Guide to Unfreezing Window TaskBar</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-in-2024-virtual-error-sounds-library-2023-complimentary-access-and-downloads/"><u>New In 2024, Virtual Error Sounds Library 2023 – Complimentary Access and Downloads</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-ultimate-guide-to-10-premium-vector-websites/"><u>[New] Ultimate Guide to 10 Premium Vector Websites</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-on-tecno-pova-5-pro-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock on Tecno Pova 5 Pro Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-edge-tips-for-individualized-pattern-security-on-windows/"><u>Cutting-Edge Tips for Individualized Pattern Security on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/decode-your-digital-identity-how-to-find-out-what-computer-you-have/"><u>Decode Your Digital Identity: How to Find Out What Computer You Have</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-nvidia-connect-failure-on-windows-11-systems/"><u>Fixing Nvidia Connect Failure on Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/cut-through-the-frustration-swift-solutions-for-ms-teams-error-80080300-in-win11/"><u>Cut Through the Frustration: Swift Solutions for MS Teams Error 80080300 in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-resource-locks-in-windows-11-environments/"><u>Disabling Resource Locks in Windows 11 Environments</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-crafting-wealth-with-facebook-video-ads-a-comprehensive-guide-for-2024/"><u>[Updated] Crafting Wealth with Facebook Video Ads  A Comprehensive Guide for 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/hardware-update-hp-laserjet-1102w-drivers-win/"><u>Hardware Update: HP LaserJet 1102W Drivers Win</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/determining-the-ideal-image-aspect-ratio-a-step-by-step-guide-for-2024/"><u>Determining the Ideal Image Aspect Ratio A Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/proven-ways-in-how-to-hide-location-on-life360-for-oppo-reno-9a-drfone-by-drfone-virtual-android/"><u>Proven Ways in How To Hide Location on Life360 For Oppo Reno 9A | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/supreme-top-4k-tvs-for-gamers-for-2024/"><u>Supreme Top 4K TVs for Gamers for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-become-a-better-self-the-20-best-exercising-soundtracks/"><u>2024 Approved  Become a Better Self  The 20 Best Exercising Soundtracks</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-error-code-zero-on-your-gaming-machine/"><u>Disabling Error Code Zero on Your Gaming Machine</u></a></li>
<li><a href="https://windows11.techidaily.com/disable-auto-updates-in-windows-and-office-instantly/"><u>Disable Auto-Updates in Windows & Office Instantly</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-lava-blaze-2-pro-get-deleted-phone-number-back-with-ease-and-safety-by-fonelab-android-recover-contacts/"><u>How to Lava Blaze 2 Pro Get Deleted Phone Number Back with Ease and Safety</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-empty-folder-warning-in-windows-11/"><u>Eliminating 'Empty Folder' Warning in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-elevated-privileges-for-power-users-a-guide/"><u>Enabling Elevated Privileges for Power Users: A Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/control-windows-11s-emphasis-and-search-highlight/"><u>Control Windows 11'S Emphasis and Search Highlight</u></a></li>
<li><a href="https://windows11.techidaily.com/consistent-experience-migrating-powertoys-on-new-pcs/"><u>Consistent Experience: Migrating PowerToys on New PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/curing-windows-security-hiccups-in-win-11-system/"><u>Curing Windows Security Hiccups in Win 11 System</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-craft-meme-magic-adobe-edition-for-2024/"><u>[Updated] Craft Meme Magic, Adobe Edition for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/directive-for-disabling-onedrive-symbol-in-windows-11s-filesystem-viewer/"><u>Directive for Disabling OneDrive Symbol in Windows 11’S Filesystem Viewer</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-sound-misstep-solving-xc00d36b4-on-windows/"><u>Decoding Sound Misstep: Solving XC00D36B4 on Windows</u></a></li>
<li><a href="https://network-issues.techidaily.com/exposing-uncharted-territory-of-dx-anomalies-in-legends/"><u>Exposing Uncharted Territory of DX Anomalies in Legends</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-clock-divergence-chrome-vs-windows/"><u>Correcting Clock Divergence: Chrome vs Windows</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-fast-video-editing-on-mac-tips-and-tricks-for-speedy-video-cutting/"><u>New In 2024, Fast Video Editing on Mac Tips and Tricks for Speedy Video Cutting</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-kickstarting-creativity-an-equipment-guide-for-beginners/"><u>[New] Kickstarting Creativity  An Equipment Guide for Beginners</u></a></li>
<li><a href="https://windows11.techidaily.com/dial-down-display-flicker-in-windows-11-devices/"><u>Dial Down Display Flicker in Windows 11 Devices</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-the-best-of-both-worlds-free-and-paid-3d-animation-software-for-artists-for-2024/"><u>New The Best of Both Worlds Free and Paid 3D Animation Software for Artists for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-html-display-issues-in-windows-11-email-client/"><u>Correcting HTML Display Issues in Windows 11 Email Client</u></a></li>
<li><a href="https://windows11.techidaily.com/disarming-error-dism-0x800f082f-on-microsoft-os/"><u>Disarming Error: DISM 0X800F082F on Microsoft OS</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-ultimate-list-of-premier-video-capture-apps-for-2024/"><u>[New] Ultimate List of Premier Video Capture Apps for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ng-peace-in-patience-slowing-down-your-online-video-experience-on-youtube-60-chars-a-bit-long-but-full-of-helpful-info-for-2024/"><u>Finding Peace in Patience  Slowing Down Your Online Video Experience on YouTube (60 Chars, a Bit Long but Full of Helpful Info) for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-mastering-whatsapp-call-recording-techniques-for-2024/"><u>[New] Mastering WhatsApp Call Recording Techniques for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensible-guide-to-counteracting-winerror-0x80071a90/"><u>Comprehensible Guide to Counteracting WinError 0X80071a90</u></a></li>
<li><a href="https://windows11.techidaily.com/converting-files-a-step-by-step-windows-process/"><u>Converting Files: A Step-by-Step Windows Process</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-identify-malfunctioning-hardware-drivers-with-windows-device-manager-on-windows-10-and-7-by-drivereasy-guide/"><u>How to identify malfunctioning hardware drivers with Windows Device Manager on Windows 10 & 7</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-speedy-steps-scribbling-down-slides-in-ppt/"><u>In 2024, Speedy Steps  Scribbling Down Slides in PPT</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-windows-error-code-31-and-network-adapter-issues/"><u>Demystifying Windows Error Code 31 and Network Adapter Issues</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-enhance-creativity-essential-tiktok-video-tricks-for-2024/"><u>[New] Enhance Creativity  Essential TikTok Video Tricks for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/outube-movie-maker-a-beginner-friendly-video-editing-companion/"><u>[New] YouTube Movie Maker  A Beginner-Friendly Video Editing Companion</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-this-article-you-will-learn-about-splitting-the-video-into-the-frames-in-ffmpeg-and-mentioning-the-easy-option-for-doing-the-same-task-in-a-few-seconds-b/"><u>In This Article, You Will Learn About Splitting the Video Into the Frames in FFmpeg and Mentioning the Easy Option for Doing the Same Task in a Few Seconds by Wondershare Filmora</u></a></li>
<li><a href="https://windows11.techidaily.com/controlling-clock-display-in-windows-11-taskbar/"><u>Controlling Clock Display in Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/command-prompt-mastery-the-fundamental-20-cmd-commands-to-know/"><u>Command Prompt Mastery: The Fundamental 20 CMD Commands to Know</u></a></li>
<li><a href="https://windows11.techidaily.com/darkeningwindowsnotepaddisplaysettings/"><u>DarkeningWindowsNotepadDisplaySettings</u></a></li>
<li><a href="https://windows11.techidaily.com/clear-path-to-app-removal-tackling-do-not-have-access-errors/"><u>Clear Path to App Removal: Tackling Do Not Have Access Errors</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-lava-blaze-2-pro-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Lava Blaze 2 Pro to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/clear-the-hurdle-of-ms-teams-error-80080300-with-actionable-steps/"><u>Clear the Hurdle of MS Teams Error 80080300 with Actionable Steps</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-how-to-spy-on-text-messages-from-computer-and-apple-iphone-x-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Spy on Text Messages from Computer & Apple iPhone X | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-proven-ways-in-how-to-hide-location-on-life360-for-oppo-reno-10-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Proven Ways in How To Hide Location on Life360 For Oppo Reno 10 Pro 5G | Dr.fone</u></a></li>
</ul></div>
