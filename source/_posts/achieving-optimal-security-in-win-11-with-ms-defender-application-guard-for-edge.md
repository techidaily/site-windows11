---
title: Achieving Optimal Security in Win 11 with MS Defender Application Guard for Edge
date: 2024-07-11T21:12:42.624Z
updated: 2024-07-12T21:12:42.624Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Achieving Optimal Security in Win 11 with MS Defender Application Guard for Edge
excerpt: This Article Describes Achieving Optimal Security in Win 11 with MS Defender Application Guard for Edge
keywords: Win 11 Secure,MS Defender Safe,AppGuard Security,Edge Protection Win,Optimal Defense Win,Win 11 Guarding,Defender Edge Security
thumbnail: https://thmb.techidaily.com/13632811731c559bc127701456401507af159186a9de22e1aa59a5e7f9127b24.jpg
---

## Achieving Optimal Security in Win 11 with MS Defender Application Guard for Edge

 If you work in an environment that deals with sensitive data, then you must install Microsoft Defender Application Guard for Edge on your Windows computer. It opens Microsoft Edge in an isolated container so that suspicious or potentially harmful files will not be able to access trusted resources.

 In this guide, we will show you different methods to install Microsoft Defender Application Guard for Edge on your Windows 11 PC.

## 1\. How to Install Microsoft Defender Application Guard Using Windows Settings

 Installing Microsoft Defender Application Guard for Edge on your Windows PC is a quick and simple process. You just need to access the Windows Settings app, and then follow a few steps to enable the feature. Here's how to do it:

1. Press**Win + I** on your keyboard to open the Settings app. See our guide if you're [having trouble opening Windows Settings](https://www.makeuseof.com/fixes-unable-to-open-windows-settings/) .
2. On the left, click**Privacy and security** , and then on the right, click**Windows Security** .
3. Under the Protection areas, click**App & browser control** .
4. Then, on the Windows Security page, click the**Install Microsoft Defender Application Guard** link below Isolated browsing.  
![How to Install Microsoft Defender Application Guard Using Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/how-to-install-microsoft-defender-application-guard-using-windows-security.jpg)
5. If you see the UAC prompt on your computer screen, click Yes to confirm your action.
6. Next, check the box next to**Microsoft Defender Application Guard** and click**OK** .  
![Add Microsoft Defender Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/add-microsoft-defender-application-guard-for-edge.jpg)

 Once you perform the above steps, you must need to restart your computer to finish installing the requested changes. This way you can install the feature on your computer.

 If you have already installed Microsoft Defender Application Guard and want to uninstall it, the process is quite easy. All you need to do is follow the steps mentioned above until you reach the Windows Security page.

![Uninstall Microsoft Defender Application Guard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-defender-application-guard.jpg)

 Then click**Uninstall Microsoft Defender Application Guard** and uncheck the box next to**Microsoft Defender Application Guard** .

## 2\. How to Install Microsoft Defender Application Guard Using the Control Panel

 You can also install Microsoft Defender Application Guard for Edge on your Windows 11 computer using the classic Control Panel. Here's how to do it:

1. Search for**Control Panel** in the Start menu and open it.
2. Select**Programs and Features** from the menu items.
3. From the left pane, click**Turn Windows features on or off** .
4. Tick the box next to**Microsoft Defender Application Guard** and click**OK** .
5. Then restart your computer for the changes to take effect.

 In order to uninstall it, follow the same steps and uncheck the box next to**Microsoft Defender Application Guard** . Then click OK and reboot your computer to save the changes.

## 3\. How to Install Microsoft Defender Application Guard Using Local Group Policy Editor

 Another method to install Microsoft Defender Application Guard is through the Local Group Policy Editor. This method requires some advanced knowledge and might be challenging for some users but don't worry; if you follow the steps, you'll be okay.

 You'll also find that if you're on Windows Home, the below instructions won't work. This is because it's not enabled by default on Home. Fortunately, you can learn [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before you perform this fix.

 Follow the steps given below to install Microsoft Defender Application Guard using Local Group Policy Editor:

1. Press the**Win + R** shortcut key to launch the Run window.
2. Type**gpedit.msc** in the dialog box and press Enter or click**OK** .
3. In the Local Group Policy Editor window, navigate to the following path:  
`Computer Configuration > Administrative Templates > Windows Components > Microsoft Defender Application Guard`
4. Now go to the right pane and double-click on the **Turn On Microsoft Defender Application Guard in Managed Mode** policy.  
![Microsoft Defender Application Guard Using Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/microsoft-defender-application-guard-using-local-group-policy-editor.jpg)
5. This will open a new window, select the**Enabled** checkbox.
6. You can now go to**Options** and change it to**2** or**3** .  
![Turn on Microsoft Defender Application Guard in Managed Mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/turn-on-microsoft-defender-application-guard-in-managed-mode.jpg)
7. Once done, click**Apply** and then**OK** to save all the changes you have made.

 Now restart your computer and Microsoft Defender Application Guard will be installed on your PC.

## 4\. How to Install Microsoft Defender Application Guard Using Command Prompt

 If you are comfortable with the command prompt, you can also install Microsoft Defender Application Guard using the Command Prompt. Follow the steps here:

1. Right-click on Start and select**Run** from the menu list.
2. In the dialog box, type**cmd** and then press**Ctrl + Shift + Enter** on your keyboard.
3. If UAC prompts, click**Yes** to run the command prompt with admin access.
4. In the elevated command prompt window, type the following command and hit Enter:  
`Dism /online /Enable-Feature /FeatureName:"Windows-Defender-ApplicationGuard"​`
5. When Command Prompt asks you to restart, type**Y** and hit Enter to complete this operation.

 Once you restart your computer, Microsoft Defender Application Guard will be installed and ready to use. In case you want to uninstall the Application Guard, you can do so by using the same command prompt steps. Just make sure to run the following command instead:

`Dism /online /Disable-Feature /FeatureName:"Windows-Defender-ApplicationGuard"​`

 At this point, you may be asked to restart your computer. To proceed, type**Y** and press Enter. After restarting, you will have successfully installed Microsoft Defender Application Guard on your system.

## 5\. How to Install Microsoft Defender Application Guard Using Windows PowerShell

 Alternatively, you can use Windows PowerShell to install Microsoft Defender Application Guard for Edge on Windows 11\. This is also a command-line process but is different from the Command Prompt application. Follow these steps to install Microsoft Defender Application Guard using Windows PowerShell:

1. Open Windows PowerShell with admin access. If you need help, see our guide on [how to open Windows PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. Once you're in the PowerShell window, type the following command:  
`Enable-WindowsOptionalFeature -Online -FeatureName "Windows-Defender-ApplicationGuard"​`
3. Now press**Enter** on your keyboard to execute it.
4. When PowerShell asks you to restart your computer, type**Y** and hit Enter.

 Upon restarting the computer, you will have successfully installed Microsoft Defender Application Guard on your system. Now you can make sure that you are browsing in a secure and protected environment.

 If you ever want to uninstall Microsoft Defender Application Guard, you can do so by using the same PowerShell command. Just make sure to use**Disable** \-WindowsOptionalFeature instead of**Enable** . So, this way the command should look like this:

`Disable-WindowsOptionalFeature -Online -FeatureName "Windows-Defender-ApplicationGuard"​`

 Now press Enter on your keyboard to execute the command and restart your system. Once it is done, Microsoft Defender Application Guard will be uninstalled from your PC.

 This is how you can install and uninstall Microsoft Defender Application Guard using Windows PowerShell on Windows 11.

## Get Microsoft Defender Application Guard and Stay Safe

 Microsoft Defender Application Guard uses isolated secure containers to protect your device from malicious files and threats. In the above-described methods, you can follow the installation steps and remain safe while browsing the web.


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
<li><a href="https://windows11.techidaily.com/how-to-fix-the-windows-11-version-22h2-update-not-installing/"><u>How to Fix the Windows 11 Version 22H2 Update Not Installing</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-creating-clip-sensations-tiktoks-viral-guide-for-2024/"><u>[New] Creating Clip Sensations  TikTok's Viral Guide for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/confronting-and-overcoming-mmc-snaps-not-found-errors/"><u>Confronting and Overcoming MMC Snaps Not Found Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-window-11-ui-elements-larger-icons/"><u>Customizing Window 11 UI Elements - Larger Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/curbing-the-constant-appearance-of-edge-icons/"><u>Curbing the Constant Appearance of Edge Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-variances-between-exe-and-msi-software-packages/"><u>Unveiling the Variances Between EXE & MSI Software Packages</u></a></li>
<li><a href="https://discord-videos.techidaily.com/selective-top-5-socially-engaging-media-animations/"><u>Selective Top 5 Socially Engaging Media Animations</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-potential-of-painting-with-microsoft-paint-on-windows-11/"><u>Unlock the Potential of Painting with Microsoft Paint on Windows 11</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-fundamentals-of-creating-persuasive-social-media-messages/"><u>2024 Approved  Fundamentals of Creating Persuasive Social Media Messages</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-makeover-evolving-file-explorer-here-are-the-changes/"><u>Windows 11 Makeover: Evolving File Explorer, Here Are the Changes</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2023-play-facebook-videos-on-tv-for-2024/"><u>2023 | Play Facebook Videos on TV for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/epic-backup-strategies-to-avoid-loss/"><u>Epic Backup Strategies to Avoid Loss</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-step-by-step-guide-to-skyrocketing-video-views/"><u>2024 Approved  Step-by-Step Guide to Skyrocketing Video Views</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/step-by-step-guide-to-store-instagram-photosvideos-on-iphones/"><u>Step-by-Step Guide to Store Instagram Photos/Videos on iPhones</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-error-0x80071a90-explained-simply/"><u>Fixing Windows Error 0X80071A90 Explained Simply</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-windows-discord-speed-a-step-by-step-guide/"><u>Boosting Windows Discord Speed: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-unearthing-absent-settings-in-control-panel/"><u>Windows 11: Unearthing Absent Settings in Control Panel</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-chronicle-custodians-circle-top-7-treasures/"><u>2024 Approved  Chronicle Custodians Circle - Top 7 Treasures</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-error-no-audio-output-on-win-10-devices/"><u>Tackling Error: No Audio Output on Win 10 Devices</u></a></li>
<li><a href="https://some-techniques.techidaily.com/go-incognito-with-instagram-live-streaming-tips-for-2024/"><u>Go Incognito with Instagram Live Streaming Tips for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unraveling-iphones-audio-mystery-ringtone-adjustments/"><u>2024 Approved  Unraveling iPhone's Audio Mystery  Ringtone Adjustments</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-playlist-passport-traveling-tunes-throughout-platforms/"><u>[New] 2024 Approved  Playlist Passport  Traveling Tunes Throughout Platforms</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/crafting-captivating-content-uploading-h-videos-for-igtv-success/"><u>Crafting Captivating Content  Uploading H-Videos for IGTV Success</u></a></li>
<li><a href="https://windows11.techidaily.com/a-step-by-step-approach-to-fixing-to-do-sync-issues/"><u>A Step-by-Step Approach to Fixing To Do Sync Issues</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/balancing-content-creation-and-employment-for-2024/"><u>Balancing Content Creation and Employment for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-productivity-on-windows-by-adjusting-with-alomware/"><u>Boost Productivity on Windows by Adjusting with AlomWare</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/the-ultimate-guide-to-twitter-video-aspect-ratios-for-2024/"><u>The Ultimate Guide to Twitter Video Aspect Ratios for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/ace-windows-with-key-based-configuration-tweaks/"><u>Ace Windows with Key-Based Configuration Tweaks</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-masterclass-in-image-moods-zenithcams-spectacle/"><u>In 2024, Masterclass in Image Moods  ZenithCams Spectacle</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-lightning-speed-seamless-transformation-from-srt-to-text-format/"><u>In 2024, Lightning Speed  Seamless Transformation From SRT to Text Format</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-the-application-encountered-an-unrecoverable-error-in-roblox-on-windows/"><u>How to Fix the “The Application Encountered an Unrecoverable Error in Roblox on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/androidiphone-to-windows-recording-connection-guide/"><u>Android/iPhone to Windows Recording Connection Guide</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-hosting-youtube-webinars-for-no-charge/"><u>[New] 2024 Approved  Hosting YouTube Webinars for No Charge</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-deadly-c0000022-breakdown-in-windows-10/"><u>Fixing the Deadly C0000022 Breakdown in Windows 10</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-embark-on-elevating-voice-startup-steps-for-an-engaging-product-vlog-channel/"><u>2024 Approved  Embark on Elevating Voice  Startup Steps for an Engaging Product Vlog Channel</u></a></li>
<li><a href="https://windows11.techidaily.com/enforcing-originality-windows-screensaver-non-alterability/"><u>Enforcing Originality: Windows Screensaver Non-Alterability</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-absence-of-files-alert-in-windows-11/"><u>Addressing Absence of Files Alert in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-chromes-black-pixels-issue/"><u>Bypassing Chrome's Black Pixels Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-intellij-unison-not-working-a-guide-for-users-of-windows-11/"><u>Fixing IntelliJ Unison Not Working: A Guide for Users of Windows 11</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-unlock-the-full-power-of-apples-siri-with-integrated-voice-control-on-tiktok/"><u>[Updated] 2024 Approved  Unlock the Full Power of Apple's Siri with Integrated Voice Control on TikTok</u></a></li>
<li><a href="https://unlock-android.techidaily.com/rootjunky-apk-to-bypass-google-frp-lock-for-xiaomi-redmi-note-13-5g-by-drfone-android/"><u>Rootjunky APK To Bypass Google FRP Lock For Xiaomi Redmi Note 13 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-something-went-wrong-with-outlook-on-pcs/"><u>Decoding Something Went Wrong with Outlook on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-restore-absentee-application-association-windows/"><u>How To Restore Absentee Application Association (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-error-0x80300024-on-a-windows-pc/"><u>Addressing Error 0X80300024 on a Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/automating-network-drives-on-win11/"><u>Automating Network Drives on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-preserves-7-ancient-features-for-modern-use/"><u>Windows 11 Preserves 7 Ancient Features for Modern Use</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-master-the-use-of-winservicesexe-on-windows/"><u>How to Master the Use of Winservices.exe on Windows</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-reviewing-ion-air-pro-3-capturing-life-in-high-definition/"><u>[New] 2024 Approved  Reviewing ION Air Pro 3 - Capturing Life in High Definition</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reestablish-connectivity-for-print-devices-on-pcs/"><u>How to Reestablish Connectivity for Print Devices on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-1011-auto-cleanup-a-step-by-step-guide/"><u>Windows 10/11 Auto-Cleanup: A Step-by-Step Guide</u></a></li>
</ul></div>
