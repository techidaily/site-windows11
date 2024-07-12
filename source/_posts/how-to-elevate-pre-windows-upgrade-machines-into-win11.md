---
title: How to Elevate Pre-Windows Upgrade Machines Into Win11
date: 2024-07-11T21:32:52.738Z
updated: 2024-07-12T21:32:52.738Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Elevate Pre-Windows Upgrade Machines Into Win11
excerpt: This Article Describes How to Elevate Pre-Windows Upgrade Machines Into Win11
keywords: Windows11UpgradeTips,Win11PreBootPrep,BootPCforWin11,ElevateToWin11,UpgradePCsWin11,Win11ReadyMachines,LegacySystemUpgrade
thumbnail: https://thmb.techidaily.com/7deb0baa73b5dfc75fe84cd47c60ae37428dbd6443868bb9392e788fdb87eec8.jpg
---

## How to Elevate Pre-Windows Upgrade Machines Into Win11

 If you have installed Windows 11 on unsupported hardware, the upgrade process will be a tough task. When you try to look for an update, Windows 11 shows everything as up to date and has no option to install the 22H2 version.

 While you can use the ISO-based clean install method, the upgrade process lets you install the latest version without deleting your apps and other data. Here’s how to upgrade to Windows 11 22H2 on unsupported hardware using the Windows 11 setup file.

## How to Upgrade to Windows 11 22H2 on Unsupported Hardware

[Windows 11 runs a hardware compatibility check](https://www.makeuseof.com/check-computer-compatible-windows-11-22h2/) during the upgrade process. To perform a successful upgrade, you’ll need to work around this hardware compatibility assessment. To achieve this, we’ll replace the appraiserress.dll file in Windows 11 ISO with the appraiserress.dll from Windows 10 ISO.

 If you have Windows 11 22H2 and Windows 10 ISO available, skip to the third step below. If not, follow all the steps to download the necessary ISOs and then perform an upgrade.

 While these steps shouldn’t cause any issues, it is better to [create a backup of any important Windows 11 data](https://www.makeuseof.com/windows-11-create-complete-backup/) on your system drive just in case something goes wrong and you need to perform a clean install.

## 1\. Download the Windows 11 22H2 ISO

![iso file download windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/iso-file-download-windows-11.jpg)

 You can [legally download the Windows 11 ISO](https://www.makeuseof.com/windows-11-download-iso/) from the Microsoft server directly or using Media Creation Tool. For this guide, we’ll use Media Creation Tool to download the ISO image file.

1. Go to the [Microsoft Software Download page](https://www.microsoft.com/software-download/windows11) .
2. Click on**Download Now** under**Create Windows 11 Installation Media.**
3. Run the**mediacreationtool.exe** file and accept the license terms.
4. Review the selected language and edition. To change the language, uncheck**Use the recommended options for this PC** and select your preferred language.
5. Click**Next** .
6. Select the**ISO file** option in the**Choose which media to use** dialog.
7. Select the download location and click**Save** . Make sure the selected partition has enough space available.
8. Media Creation Tool will start downloading the ISO to your local drive. This process may take some time, depending on your Internet connection. So wait for the download to complete.
9. Once the download is complete, click**Finish** and follow the next step to download Windows 10 ISO.

## 2\. Download a Windows 10 ISO

![windows 10 download ISO preference](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-10-download-iso-preference.jpg)

 You’ll need to modify the Windows 11 ISO by replacing the appraiserress.dll with a version available in Windows 10 ISO. This DLL file is responsible for performing a hardware check during an upgrade.

To download Windows 10 ISO:

1. Go to [Windows 10 download page](https://www.microsoft.com/en-us/software-download/windows10) .
2. Click the**Download Now** button under**Create Windows 10 installation media** .
3. Run the**mediacreationtool.exe** file to open Windows 10 Setup dialog.
4. Click on**Accept** .
5. In the**What do you want to do** screen, select**Create installation media** and click**Next** .
6. Check if the language, edition, and architecture preferences are set correctly. If not, click on**Use the recommended options for this** **device** and set your preferences.
7. Next, select the**ISO file** option and click**Next** .
8. Select the download location and click**Save** .
9. The downloading process may take several minutes to complete. So wait for the process to complete and click**Finish** once done.

 Once you have both the ISO files saved, follow the next step to extract and modify the Windows 11 ISO.

## 3\. Modify the Windows 11 ISO to Bypass Hardware Check During the Upgrade

 The following steps involve extracting the Windows 10 ISO and copying the appraiserress.dll file. Next, move the copied DLL file to the Windows 11 ISO’s sources folder. Here’s how to do it.

1. Right-click on the**Windows 10 ISO** file and select**Mount** . This will create a new virtual DVD Drive and open the ISO folder.  
![mount windows 10 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/mount-windows-10-iso.jpg)
2. Open the**Sources** folder and locate the**appraiserres.dll** file. Copy the**DLL** file and move it to a different folder.  
![copy appraiserres dll windows 10 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-appraiserres-dll-windows-10-iso.jpg)
3. Next, extract the Windows 11 ISO to a different folder. You can [use WinRAR to extract](https://www.win-rar.com/start.html?&L=0) the Windows 11 ISO file.  
![extract windows 11 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/extract-windows-11-iso.jpg)
4. Open the Windows 11 ISO's extracted folder and then the**Source** folder.
5. Next, copy and paste the**appraiserres.dll** file copied from Windows 10 ISO into Windows 11 ISO's**Sources** folder.

1. Select**Replace the file in the destination** to confirm the action.  
![replace the file in the destination appraiserrs ll windows 11 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/replace-the-file-in-the-destination-appraiserrs-ll-windows-11-iso.jpg)
2. Next, disconnect your PC from the Internet. This prevents the setup from downloading updated files during installation and overwriting the modified dll file.
3. Once the Internet is disabled, open the extracted Windows 11 ISO folder and double-click on the**Setup file** . Click**Yes** if prompted by UAC.
4. In the**Windows 11 Setup** dialog, click on**Change how Setup downloads updates.**  
![windows 11 setup not right now updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-11-setup-not-right-now-updates.jpg)
5. Next, select**Note right now.** This will prevent the Windows setup from finding and installing newer updates causing the upgrade process to fail on unsupported hardware.  
![windows 11 setup choose what to install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-11-setup-choose-what-to-install.jpg)
6. In the**Choose what to keep** screen, select**Keep personal files and apps.**
7. Click**Next** and then click on**Accept** .  
![windows 11 setup ready to install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-11-setup-ready-to-install.jpg)
8. Next, click on**Install** to install Windows 11 version 22H2 while keeping your personal files and apps.
9. Leave your computer idle until the installation process is complete. After the restart, you’ll have the latest Windows 11 22H2 running on your computer.

To check your Windows specification:

![check windows specification windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/check-windows-specification-windows-11.jpg)

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, scroll down and click on**About** .
3. Under Windows specifications, you’ll see**Version 22H2** if the upgrade was successful.

## 4\. Go Back to the Previous Version

![go back windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/go-back-windows-11.jpg)

 If you run into an issue after the upgrade, you can use the**Go back** option to undo the update and restore the earlier version of Windows 11\. However, the "Go back" option is only available for seven days since the upgrade. After that, the option will be greyed out.

To go back to the previous version:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, scroll down and click on**Recovery** .
3. Click on**Go back** under**Recovery options** . Then, follow the on-screen instructions to uninstall the Windows 22H2 update.

## Installing Windows 11 22H2 on Unsupported Hardware

 It is easy to bypass the Windows 11 system hardware requirements when you want to perform a clean install. However, to perform an upgrade, you’ll need to modify the appraiserress.dll file and then run the setup.

 While the upgrade is possible for now, the lack of future automatic Windows updates makes maintaining the PC a complicated task. If upgrading to Windows 11 is not a must, you can stick to Windows 10 on older hardware, which will continue to receive support until late 2025.


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
<li><a href="https://activate-lock.techidaily.com/new-guide-how-to-check-icloud-activation-lock-status-on-your-iphone-14-by-drfone-ios/"><u>New Guide How To Check iCloud Activation Lock Status On Your iPhone 14</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/why-does-the-pokemon-go-battle-league-not-available-on-honor-90-gt-drfone-by-drfone-virtual-android/"><u>Why does the pokemon go battle league not available On Honor 90 GT | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/the-elusive-guide-to-unseen-menu-adjustments-windows-style/"><u>The Elusive Guide to Unseen Menu Adjustments, Windows Style</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-your-console-dreams-choose-windows-for-games/"><u>Unlocking Your Console Dreams: Choose Windows for Games</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-adept-approaches-for-capturing-high-impact-presentations-for-2024/"><u>[New] Adept Approaches for Capturing High-Impact Presentations for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-saving-every-moment-on-mac-with-screen-recording-tutorial/"><u>[New] In 2024, Saving Every Moment on Mac with Screen Recording Tutorial</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-top-7-skype-hacker-to-hack-any-skype-account-on-your-motorola-razr-40-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Skype Hacker to Hack Any Skype Account On your Motorola Razr 40 | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-pixelated-projections-immersive-filmscape/"><u>2024 Approved  Pixelated Projections  Immersive Filmscape</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-application-failure-the-notorious-error-the-application-couldnt-start-xc000003e-on-win11-and-11/"><u>Navigating Application Failure: The Notorious Error The Application Couldn’t Start Xc000003e on Win11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/securely-clearing-email-details-post-login/"><u>Securely Clearing Email Details Post-Login</u></a></li>
<li><a href="https://windows11.techidaily.com/restore-and-revitalize-13-ways-to-rejuvenate-windows-systems/"><u>Restore & Revitalize: 13 Ways to Rejuvenate Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/1719261046850-experience-gptclone-at-home-for-free-on-windows/"><u>Experience GPTClone at Home for FREE on Windows</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-imovie-for-beginners-building-intriguing-openers-for-youtube/"><u>[Updated] In 2024, IMovie for Beginners  Building Intriguing Openers for YouTube</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-x-to-other-iphone-14-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone X To Other iPhone 14 devices? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-device-control-for-sleep-state-wakefulness/"><u>Unlocking Device Control for Sleep State Wakefulness</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-file-transfers-on-microsoft-store/"><u>Accelerating File Transfers on Microsoft Store</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-this-file-is-alone-error-on-pcs/"><u>Overcoming This File Is Alone Error on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/visualize-resource-consumption-windows-tray-update-guide/"><u>Visualize Resource Consumption: Windows Tray Update Guide</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/five-expert-tools-for-extracting-fb-content-for-2024/"><u>Five Expert Tools for Extracting FB Content for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-detect-and-stop-mspy-from-spying-on-your-motorola-moto-g-stylus-5g-2023-drfone-by-drfone-virtual-android/"><u>How to Detect and Stop mSpy from Spying on Your Motorola Moto G Stylus 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/1719293285605-windows-11-woes-re-opening-chrome-made-simple/"><u>Windows 11 Woes: Re-Opening Chrome Made Simple.</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-professional-sound-designers-method-eliminating-vocals-with-adobe-audition-step-by-step/"><u>Updated Professional Sound Designers Method Eliminating Vocals with Adobe Audition, Step by Step</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-social-spectacle-snatcher-hub/"><u>[New] 2024 Approved  Social Spectacle Snatcher Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/make-your-windows-life-easier-with-proper-installation-steps/"><u>Make Your Windows Life Easier with Proper Installation Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/investigating-and-fixing-create-failed-on-windows-error-30005/"><u>Investigating and Fixing Create Failed on Windows Error 30005</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-apple-images-not-importing-correctly-on-windows/"><u>Addressing Apple Images Not Importing Correctly on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/all-the-paint-3d-keyboard-shortcuts-you-must-know/"><u>All the Paint 3D Keyboard Shortcuts You Must Know</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-window-gloss-your-guide-to-a-clearer-taskbar-in-win11/"><u>Mastering Window Gloss: Your Guide to a Clearer Taskbar in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-office-suites-strict-safe-mode-on-windows-operations/"><u>Troubleshooting Office Suite's Strict Safe Mode on Windows Operations</u></a></li>
<li><a href="https://windows11.techidaily.com/reset-chronology-fix-windows-time-errors/"><u>Reset Chronology: Fix Windows Time Errors</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-in-2024-top-video-smoothening-software/"><u>New In 2024, Top Video Smoothening Software</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-windows-default-no-spotify-autoplay/"><u>Avoid Windows Default: No Spotify Autoplay</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-steady-as-a-rock-3-proven-methods-for-stabilizing-video-in-ae-for-2024/"><u>New Steady as a Rock 3 Proven Methods for Stabilizing Video in AE for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-non-existence-of-powershell-in-windows/"><u>Tackling the Non-Existence of PowerShell in Windows</u></a></li>
<li><a href="https://driver-install.techidaily.com/revolutionize-audiophile-experience-nvidias-new-win7-driver/"><u>Revolutionize Audiophile Experience: Nvidia's New Win7 Driver</u></a></li>
<li><a href="https://windows11.techidaily.com/unfreezing-and-reviving-windows-11s-stuck-media-player/"><u>Unfreezing and Reviving Windows 11'S Stuck Media Player</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-microsoft-m365-glitch-with-code-30015-26/"><u>Remedy Microsoft M365 Glitch with Code 30015-26</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-quickplay-quotient-top-10-lightning-gaming-apps/"><u>[Updated] Quickplay Quotient  Top 10 Lightning Gaming Apps</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/a-deep-dive-into-the-top-9-youtube-downloader-apps-for-android/"><u>A Deep Dive Into the Top 9 YouTube Downloader Apps for Android</u></a></li>
<li><a href="https://network-issues.techidaily.com/swift-restoration-rectify-legends-glitches/"><u>Swift Restoration: Rectify Legends Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-your-subnet-in-the-latest-os-win11/"><u>Optimizing Your Subnet in the Latest OS: Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/what-purpose-does-a-directory-like-windows-bt-serve/"><u>What Purpose Does a Directory Like Windows ~BT Serve?</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensible-approach-to-fixing-notepad-non-openness-in-windows/"><u>A Comprehensible Approach to Fixing Notepad Non-Openness in Windows</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/snapchat-mastery-the-essential-guide-to-smartphone-screen-recording/"><u>Snapchat Mastery  The Essential Guide to Smartphone Screen Recording</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-36-epic-tiktok-comedy-moments/"><u>2024 Approved  36 Epic TikTok Comedy Moments</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-memory-management-in-new-os/"><u>Mastering Memory Management in New OS</u></a></li>
<li><a href="https://fox-access.techidaily.com/the-filmmakers-guide-to-stunning-spherical-videos-9-must-knows/"><u>The Filmmaker's Guide to Stunning Spherical Videos (9 Must-Knows)</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-eliminate-background-noise-from-online-video-content/"><u>[Updated] 2024 Approved  Eliminate Background Noise From Online Video Content</u></a></li>
<li><a href="https://windows11.techidaily.com/optimal-system-settings-reducing-resource-drain-while-playing/"><u>Optimal System Settings: Reducing Resource Drain While Playing</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windowsstore-app-folder-hidden-entry-points/"><u>Unveiling WindowsStore App Folder Hidden Entry Points</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-in-2024-10-must-use-mp4-to-gif-converters-to-get-perfect-made-gif/"><u>Updated In 2024, 10 Must-Use MP4 to GIF Converters to Get Perfect-Made GIF</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-data-from-iphone-12-pro-max-to-other-iphone-15-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 12 Pro Max To Other iPhone 15 devices? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-7-ways-to-lock-apps-on-iphone-13-and-ipad-securely-drfone-by-drfone-ios/"><u>In 2024, 7 Ways to Lock Apps on iPhone 13 and iPad Securely | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-photo-wizardry-made-easy-mastering-slideshow-creation-and-spot-repair/"><u>Windows 11'S Photo Wizardry Made Easy: Mastering Slideshow Creation & Spot Repair</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-mastering-live-streamed-gaming-sessions/"><u>[New] In 2024, Mastering Live-Streamed Gaming Sessions</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-mastering-the-skill-how-to-securely-record-on-whatsapp/"><u>[Updated] Mastering the Skill  How to Securely Record on WhatsApp</u></a></li>
<li><a href="https://windows11.techidaily.com/proven-strategies-for-comprehensible-comic-consumption-on-win11/"><u>Proven Strategies for Comprehensible Comic Consumption on Win11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-pgsharp-legal-when-you-are-playing-pokemon-on-xiaomi-redmi-note-13-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Is pgsharp legal when you are playing pokemon On Xiaomi Redmi Note 13 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/restore-full-size-to-your-windows-11-icons/"><u>Restore Full Size to Your Windows 11 Icons</u></a></li>
</ul></div>
