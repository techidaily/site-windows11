---
title: "Detailed Guide: Turning Secure Boot and TPM On/Off in VBox"
date: 2024-07-11T21:57:01.467Z
updated: 2024-07-12T21:57:01.467Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Detailed Guide: Turning Secure Boot and TPM On/Off in VBox"
excerpt: "This Article Describes Detailed Guide: Turning Secure Boot and TPM On/Off in VBox"
keywords: VM Secure Boot Guide,TPM Control in Virtualbox,Enable VBOX TPM,Disable Secure Boot VBox,Turnoff VBox TPM,On/Off Secure Boot VM,Manage VBox TPM Settings
thumbnail: https://thmb.techidaily.com/b2e687db976d53413ad200065943dddbaf2bd03eb2c28e9e47c24fc4c8af2aa4.jpg
---

## Detailed Guide: Turning Secure Boot and TPM On/Off in VBox

 VirtualBox released version 7.0 in October 2022\. It is the first hypervisor to support the emulation of TPM chips along with all the other system components. VirtualBox also offers a Secure Boot feature in EFI mode for virtual machines. The main reason behind these two features was Microsoft's list of elaborate system requirements for Windows 11.

 Without emulation of the TPM 2.0 chip, users couldn't install Windows 11 on a virtual machine. But with VirtualBox 7.0 it is possible to enable Secure Boot and TPM for any Windows virtual machine. This post will elaborate on the methods to enable or disable TPM and Secure Boot for any VirtualBox virtual machine.

## Why Does Windows 11 Need TPM and Secure Boot?

 Windows 11 needs both a TPM chip and Secure Boot to offer robust protection against threats and not allow any malware to run when the system boots up. Secure Boot only allows signed drivers to load and the TPM chip helps in BitLocker drive data protection. So, both these features are pretty important from a security standpoint. Check out our guide on [what Secure Boot is and how it works](https://www.makeuseof.com/what-is-secure-boot-how-does-it-work/) for more information.

 While Windows 11 can work without Secure Boot and a TPM 2.0 chip, it won't be able to offer that extra layer of system protection it would do otherwise. Many features like Core-isolation, Data Encryption won't work. If you want to enable or disable these features for Windows 10 or 11 virtual machines, you can do so in VirtualBox 7.0.

## How to Enable or Disable Secure Boot and TPM Support in VirtualBox 7.0

 Repeat the following steps to enable TPM 2.0 and Secure Boot in VirtualBox.

1. Press the**Win** key and search VirtualBox. Click on the first relevant search result to launch the app.
2. Click on a Windows virtual machine and then click on the**Settings** icon.
3. Navigate to the**System** settings option.
4. Find the**TPM** option. If it is set to none, click on the**arrow** icon to open the drop-down menu.
5. Select the TPM**v2.0** option from the list. Windows 11 won't work with anything lower but if you are using Windows 10 then you can pick**v1.2** from the list.
6. Scroll down and locate the**Extended Features** section. Click on the**Enable EFI (special OSes only)** option check box.
7. Then click on the**Enable Secure Boot** option check box.  
![Enable Secure Boot and TPM Support in VirtualBox 7.0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/enable-secure-boot-and-tpm-support-in-virtualbox-7-0.jpg)
8. Now, click on the**OK** button. The settings window will close automatically.
9. Go to the top area and click on the**Start** button to power on the Windows virtual machine.
10. Now, press the Win key and search Security. Open the**Windows security** app.
11. Navigate to the left-hand side menu and click on the**Device Security** option. Here, all Windows security features will be active.
12. To disable TPM and Secure Boot, reopen the virtual machine settings and set the TPM version to**None** . Uncheck the**Enable EFI (special OSes only)** option check box. Click on**OK** to save the changes.

### An Alternative Method to Check if TPM Is Active in the Windows Virtual Machine

Here's how to check TPM on Windows 11 virtual machine:

1. Press the**Win + R** key to launch the Run command box (see [how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**TPM.msc** and press the**Enter** key.  
![check TPM on Windows 11 virtual machine 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-1.jpg)
2. TPM utility will launch. Navigate to the Manufacturer Information section.  
![check TPM on Windows 11 virtual machine 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-2.jpg)
3. If the Specification version entry showcases 2.0, it means that TPM chip emulation is successful.

## Manage TPM and Secure Boot Features in VirtualBox With Ease

 You can choose to keep both features active or not. After installing Windows 11 as a virtual machine, you can turn TPM and Secure Boot off and not face any issues with the operating system. However, remember that these are important from a security perspective.


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
<li><a href="https://windows11.techidaily.com/integrating-your-android-into-windows-11-webstreaming/"><u>Integrating Your Android Into Windows 11 Webstreaming</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-keep-windows-notepad-running-without-interruptions/"><u>Strategies to Keep Windows Notepad Running without Interruptions</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-transition-from-ical-to-windows-calendar/"><u>Navigating the Transition: From iCal to Windows Calendar</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-elevate-your-meetings-best-tools-to-record-zoom/"><u>[Updated] In 2024, Elevate Your Meetings  Best Tools to Record Zoom</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-fix-oem-unlock-missing-on-samsung-galaxy-a14-4g-by-drfone-android/"><u>How To Fix OEM Unlock Missing on Samsung Galaxy A14 4G?</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-apex-servers-on-pc-7-ways-to-fix-no-server-errors-(156-chars/"><u>Mastering Apex Servers on PC: 7 Ways to Fix 'No Server' Errors (<156 Chars)</u></a></li>
<li><a href="https://location-social.techidaily.com/top-7-skype-hacker-to-hack-any-skype-account-on-your-honor-x9b-drfone-by-drfone-virtual-android/"><u>Top 7 Skype Hacker to Hack Any Skype Account On your Honor X9b | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-windows-from-always-entering-cmos-mode-at-start-up/"><u>How to Stop Windows From Always Entering CMOS Mode at Start-Up</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-inaccessible-files-on-windows-platform/"><u>Fixing Inaccessible Files on Windows Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-system-integration-enable-windows-subsystem-for-linux/"><u>Seamless System Integration: Enable Windows Subsystem for Linux</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-stability-issues-with-vscode-on-w11/"><u>Preventing Stability Issues with VSCode on W11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windowsapps-access-a-step-by-step-guide/"><u>Mastering WindowsApps Access: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-the-nuances-of-windows-maintenance-and-update-scheduling/"><u>Navigate the Nuances of Windows Maintenance & Update Scheduling</u></a></li>
<li><a href="https://windows11.techidaily.com/making-your-notes-pop-in-win-1011-os/"><u>Making Your Notes Pop in Win 10/11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-hurdle-of-non-responding-email-alerts-on-pcs/"><u>Overcoming the Hurdle of Non-Responding Email Alerts on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-disable-update-notifications-on-windows/"><u>How to Disable Update Notifications on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-rpc-failure-essential-steps-for-win-users/"><u>Overcoming RPC Failure: Essential Steps for Win Users</u></a></li>
<li><a href="https://windows11.techidaily.com/revealing-windows-11s-disguised-taskbar-investigation-tool/"><u>Revealing Windows 11'S Disguised Taskbar Investigation Tool</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/capture-kings-top-15-windows-tools-for-2024/"><u>Capture Kings  Top 15 Windows Tools for 2024</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/in-2024-demystifying-twitter-archives-for-users-and-analysts/"><u>In 2024, Demystifying Twitter Archives for Users & Analysts</u></a></li>
<li><a href="https://windows11.techidaily.com/inspect-font-characters-windows-11-route/"><u>Inspect Font Characters: Windows 11 Route</u></a></li>
<li><a href="https://change-location.techidaily.com/home-button-not-working-on-xiaomi-13-ultra-here-are-real-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Home Button Not Working on Xiaomi 13 Ultra? Here Are Real Fixes | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/new-dawn-for-old-gameshells-atlasos/"><u>New Dawn For Old Gameshells - AtlasOS</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-reinstating-original-size-for-win-11-icons/"><u>Guide to Reinstating Original Size for Win 11 Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-disabled-windows-shadow-copies/"><u>Resolving Disabled Windows Shadow Copies</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-reason-behind-photo-booth-video-stalls/"><u>[New] 2024 Approved  Reason Behind Photo Booth Video Stalls</u></a></li>
<li><a href="https://windows11.techidaily.com/reduce-keyboard-latency-in-win-os-with-top-7-hacks/"><u>Reduce Keyboard Latency in Win OS with Top 7 Hacks</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-troubleshooters-not-working-in-windows-10-and-11/"><u>How to Fix the Troubleshooters Not Working in Windows 10 & 11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/the-ultimate-watch-list-top-tweets-of-2023-for-2024/"><u>The Ultimate Watch List  Top Tweets of 2023 for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-a-muted-windows-taskbar/"><u>Remedying a Muted Windows Taskbar</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-engaging-audiences-perfecting-the-art-of-igtv-titles-and-summaries/"><u>[New] In 2024, Engaging Audiences  Perfecting the Art of IGTV Titles & Summaries</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-reinstalling-favorite-apps-on-new-windows-11-devices/"><u>Guide to Reinstalling Favorite Apps on New Windows 11 Devices</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-effortless-method-to-record-your-skype-sessions-on-pcmac/"><u>[Updated] 2024 Approved  Effortless Method to Record Your Skype Sessions on PC/Mac</u></a></li>
<li><a href="https://windows11.techidaily.com/revitalizing-vintage-directx-apps-using-modernized-dxvk-features/"><u>Revitalizing Vintage DirectX Apps Using Modernized DXVK Features</u></a></li>
<li><a href="https://windows11.techidaily.com/simplify-workflows-automate-using-to-dot-plus-ifttt/"><u>Simplify Workflows: Automate Using To-Dot + IFTTT</u></a></li>
<li><a href="https://windows11.techidaily.com/must-use-3d-paint-shortcuts-compiled/"><u>Must-Use 3D Paint Shortcuts Compiled</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-tracking-apps-to-track-realme-c33-2023-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Tracking Apps to Track Realme C33 2023 without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-perfecting-images-slideshow-and-fix-in-windows-11-photos-app/"><u>Guide to Perfecting Images: Slideshow & Fix in Windows 11 Photos App</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-getting-started-with-your-youtube-channel-essentials/"><u>[Updated] In 2024, Getting Started with Your YouTube Channel – Essentials</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-unleash-fast-the-ultimate-tiktok-download-playbook/"><u>[New] 2024 Approved  Unleash Fast  The Ultimate TikTok Download Playbook</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-error-code-0x80040610-in-depth-outlook-troubleshooting-guide/"><u>Resolving Windows Error Code 0X80040610: In-Depth Outlook Troubleshooting Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/from-edge-to-frontline-quick-fixes-for-lost-off-screen-windows/"><u>From Edge to Frontline: Quick Fixes for Lost Off-Screen Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaim-your-slack-notifications-fixes-for-windows-11/"><u>Reclaim Your Slack Notifications: Fixes for Windows 11</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/8-safe-and-effective-methods-to-unlock-your-apple-iphone-13-pro-max-without-a-passcode-by-drfone-ios/"><u>8 Safe and Effective Methods to Unlock Your Apple iPhone 13 Pro Max Without a Passcode</u></a></li>
<li><a href="https://windows11.techidaily.com/explore-the-best-techniques-to-streamline-your-windows-folder-system/"><u>Explore the Best Techniques to Streamline Your Windows Folder System</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-steams-server-disconnection-on-windows-machines/"><u>How to Rectify Steam's Server Disconnection on Windows Machines</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-cutting-edge-music-editing-software-roundup-the-top-10-compatible-apps-for-windows-and-mac-for-2024/"><u>Updated Cutting-Edge Music Editing Software Roundup The Top 10 Compatible Apps for Windows and Mac for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/new-horizons-in-customizing-win11-ui/"><u>New Horizons in Customizing Win11 UI</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-correct-non-empty-directory-error-code-0x80070091-in-win11/"><u>How to Correct Non-Empty Directory Error (Code: 0X80070091) in Win11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-aspect-ratios-unveiled-a-complete-youtube-manual/"><u>[Updated] In 2024, Aspect Ratios Unveiled  A Complete YOUTUBE Manual</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-past-share-permission-hurdles-in-win-os/"><u>Navigate Past Share Permission Hurdles in Win OS</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-proven-techniques-to-swell-your-social-media-following/"><u>[Updated] In 2024, Proven Techniques to Swell Your Social Media Following</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-step-1-to-50-building-a-foundation-for-mukbang-creation/"><u>In 2024, Step 1 to 50  Building a Foundation for Mukbang Creation</u></a></li>
</ul></div>
