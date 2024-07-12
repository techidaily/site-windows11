---
title: Diagnosing and Repairing Win LSA Errors
date: 2024-07-11T21:48:38.627Z
updated: 2024-07-12T21:48:38.627Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Diagnosing and Repairing Win LSA Errors
excerpt: This Article Describes Diagnosing and Repairing Win LSA Errors
keywords: Fix LSA Errors,Diagnose SysLSA,Resolve Windows Boot Issue,Troubleshoot LSA Problems,Win OS SysLSA Repair,Eliminate LSA Failure,Correct LSA System Crash
thumbnail: https://thmb.techidaily.com/db587631bccc11018e71b0f197be1378b7d1dbbecd5a463368074dbdb88b8238.jpg
---

## Diagnosing and Repairing Win LSA Errors

 LSA protection is a vital security feature on Windows that prevents unauthorized access to system resources. However, corrupt system files or malware infections may lead to an error stating "this change requires you to restart your device". This error persists even after enabling Local Security Authority (LSA) protection or restarting the computer.

 It suggests an underlying problem that requires resolution to restore system security. If you have the same problem, these solutions might help.

## What Causes the LSA Protection Error?

 The exact cause of the “this change requires you to restart your device” error can vary, but it may be due to corrupted system files or malware infections. Malware can install malicious services and components that interfere with Windows' smooth functioning, including disabling Local Security Authority (LSA) protection. It can also occur if antivirus software incorrectly removes system files and causes instability.

 This error is usually triggered when Windows attempts to enable Local Security Authority (LSA) protection and fails. In some cases, the error may also appear after you enabled LSA protection and restarted your computer.

## 1\. Restart Your PC

 As the error message suggests, you first restart your Windows system. This minor step can fix several system-level errors and is worth a try. Restarting your computer involves shutting down all running programs and starting it up again.

## 2\. Scan for Malicious Programs

 If restarting the computer doesn't solve the issue, check your system for malicious software. Malware infections may corrupt system files and prevent LSA protection from working.

 To check if any malicious programs are on your system, do the following.

1. Press **Win + Q** on your keyboard to open the Taskbar search window.
2. Type **Windows Security** in the search bar and hit Enter.
3. On the left pane of Windows Security, click the **Virus & threat protection** tab.
4. Click **Scan options** on the right side of the screen.  
![Full Scan Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-scan-windows-security.jpg)
5. Select **Full scan** and click **Scan now**.

 Now wait for the scan to finish. If malicious programs are detected, Windows Security will remove them from your system automatically.

## 3\. Change the Group Policy Settings

 If the above steps don't help, you might need to configure LSA manually. It involves editing the Local Group Policy Editor and setting some specific settings. However, this tool only works with Windows 11 Professional and Enterprise editions.

 So, if you're running Windows Home Edition, you won't have access to Local Group Policy. To make this work, [enable the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/), then follow these steps:

1. Press **Win + R** on your keyboard to open the Run dialogue box.
2. Type **gpedit.msc** in the search box and hit Enter.
3. In the Local Group Policy Editor, expand **Computer Configuration** on the left side.
4. Then navigate to the following:  
Administrative Templates > System > Local Security Authority
5. Double-click **Configure LSASS to run as a protected process** in the right pane.  
![Change the Group Policy Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-the-group-policy-settings.jpg)
6. Now, in the window that appears, alter the settings from **Not Configured** to **Enabled**.
7. Under the Options section, click the drop-down menu for **Configure LSASS to run as a protected process** and select **Enabled with UEFI Lock**.  
![Set as Enabled with UEFI Lock](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-as-enabled-with-uefi-lock.jpg)
8. Now click **Apply > OK** to save the changes.

 After making the above changes, restart your computer and check if the error is resolved.

## 4\. Tweak the Registry Editor

 If you're running Windows Home edition, you can tweak the Registry Editor to modify Local Security Authority protection values. The steps are pretty straightforward, but be aware that making incorrect changes to the registry can cause serious problems. To be safe, [back up the Windows Registry data](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making any changes.

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the dialog box and press the Enter key.
3. If UAC prompts appear on the screen, click **Yes** to grant permission.
4. In the Registry Editor window, navigate to the following location:  
Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Lsa  
 You can also copy and paste the given path into the address bar at the top of the Registry window. Then, hit Enter to jump directly to the folder.
5. In the right pane, double-click on **RunAsPPL** to open Edit DWORD (32-bit) Value.  
![Change RunAsPPL regsitry values](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-runasppl-regsitry-values.jpg)
6. Change the Value data from 0 to **2** and click **OK**.
7. Similarly, find the **RunAsPPLBoot** key and set its value to **2**.  
 If you don't find the **RunAsPPL** and **RunAsPPLBoot** keys in the LSA folder, you'll need to create them manually. To do this, right-click on the LSA folder and select **New > DWORD (32-bit) Value**. Name the new value **RunAsPPL** and set its value to 2\. Then repeat this process for the **RunAsPPLBoot** key.

 Once you're done, close the Registry Editor and restart your computer. This should fix the problem.

## 5\. Reset the Windows Security App

 Windows Security is an integrated antivirus program built into the Windows OS. It's responsible for scanning your system and removing malicious content. If there's something wrong with the Windows Security app, it might trigger this error. To fix the issue, reset the app and see if it helps. Here's how to do it:

1. Press **Win + I** on your keyboard to open the system settings.
2. Select **Apps** on the left side of the window.
3. Click **Installed apps** in the right pane
4. Scroll down the list of apps until you see **Windows Security**. You can also type Windows Security into the search bar to find it quickly.
5. Now click the three dots icon and select **Advanced options** from the menu.
6. On the next page, scroll down to the **Reset** section and click **Reset**.  
![Reset Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-windows-security.jpg)
7. If the confirmation window pops up, click **Reset** to continue.

 Wait for the reset process to finish and restart your computer. After restarting, check if the error is still present.

## 6\. Perform Some Generic Fixes

 There are also some generic fixes to resolve the issue. First, [run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) command to repair incorrect or damaged system files. You may also want to use the Deployment Image Servicing and Management tool to diagnose issues with local system images. If the problem persists, try [updating Windows to the latest version](https://www.makeuseof.com/update-windows-manually/) to resolve any glitches or bugs.

 Some antivirus and security programs can be too aggressive in protecting your system. They could prevent access to the LSA feature, leading to this problem. To be sure, you can [temporarily disable your security software](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) and check if it solves the issue.

## Fixing the LSA Protection Error on Windows

 Local Security Authority protection safeguards unauthorized access to system resources, such as passwords or other sensitive information. However, this feature might not work as expected due to LSA Protection Error. Thanks to the potential solutions discussed in this guide, solving the problem is easy.

 It suggests an underlying problem that requires resolution to restore system security. If you have the same problem, these solutions might help.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-lessons.techidaily.com/in-2024-comprehensive-guide-to-whatsapp-vocal-exchange/"><u>In 2024, Comprehensive Guide to WhatsApp Vocal Exchange</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-ios-system-of-apple-iphone-xr-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair iOS System of Apple iPhone XR? | Dr.fone</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/masks-and-mayhem-in-diverse-cultures/"><u>Masks & Mayhem in Diverse Cultures</u></a></li>
<li><a href="https://windows11.techidaily.com/future-proof-computing-with-top-windows-laptop-choices/"><u>Future-Proof Computing with Top Windows Laptop Choices</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-crafting-cohesive-soundscape-detailed-walkthrough-of-audio-normalization-in-davinci-resolve/"><u>New Crafting Cohesive Soundscape Detailed Walkthrough of Audio Normalization in DaVinci Resolve</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-pathway-merging-emulated-game-titles-with-playnite-software/"><u>Guiding Pathway: Merging Emulated Game Titles with Playnite Software</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-to-mask-dimming-functionality-in-system-preferences/"><u>Tactics to Mask Dimming Functionality in System Preferences</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-use-of-toolbars-an-insight-into-mspcm-windows-11/"><u>Mastering the Use of Toolbars: An Insight Into MSPCM, Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-change-the-default-pdf-reader-on-windows/"><u>How to Change the Default PDF Reader on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/ending-system-crashes-fix-for-code-0x0000011b-errors/"><u>Ending System Crashes: Fix for Code 0X0000011B Errors</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/mastering-the-craft-of-creating-captivating-podcast-titles-for-2024/"><u>Mastering the Craft of Creating Captivating Podcast Titles for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-to-switch-off-stuck-theme-on-pc/"><u>Essential Steps to Switch Off Stuck Theme on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-screen-settings-with-these-10-win-11-tricks/"><u>Streamline Your Screen Settings with These 10 Win 11 Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-grayed-out-bin-status-in-win11/"><u>Rectifying Grayed Out Bin Status in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-update-pitfalls-0x30017/"><u>Navigating Through Windows Update Pitfalls (0X30017)</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-bypass-enforced-driver-signatures-loading-unverified-drivers/"><u>Methods to Bypass Enforced Driver Signatures, Loading Unverified Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-1011-a-workshop-for-custom-pattern-crafting/"><u>Navigating Windows 10/11: A Workshop for Custom Pattern Crafting</u></a></li>
<li><a href="https://howto.techidaily.com/bricked-your-nokia-c12-pro-heres-a-full-solution-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Bricked Your Nokia C12 Pro? Heres A Full Solution | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/process-of-disabling-laptops-internal-keys-in-os/"><u>Process of Disabling Laptop's Internal Keys in OS</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-navigating-back-time-iphones-video-reversal-trick/"><u>2024 Approved  Navigating Back Time  IPhone's Video Reversal Trick</u></a></li>
<li><a href="https://change-location.techidaily.com/home-button-not-working-on-tecno-camon-20-premier-5g-here-are-real-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Home Button Not Working on Tecno Camon 20 Premier 5G? Here Are Real Fixes | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-pioneering-video-content-success-expert-rank-tracking-solutions/"><u>2024 Approved  Pioneering Video Content Success - Expert Rank Tracking Solutions</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-a-step-by-step-guide-to-youtube-image-branding-for-2024/"><u>[Updated] A Step-by-Step Guide to YouTube Image Branding for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-make-the-most-of-your-apple-iphone-11-pro-max-lock-screen-with-notifications-by-drfone-ios/"><u>In 2024, How to Make the Most of Your Apple iPhone 11 Pro Max Lock Screen with Notifications?</u></a></li>
<li><a href="https://windows11.techidaily.com/defining-windows-corners-straighten-them-out/"><u>Defining Windows' Corners: Straighten Them Out</u></a></li>
<li><a href="https://windows11.techidaily.com/navigational-aid-embracing-apple-maps-in-windows-systems/"><u>Navigational Aid: Embracing Apple Maps in Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-double-clicking-not-opening-folders-on-windows-1110/"><u>How to Fix Double-Clicking Not Opening Folders on Windows 11/10</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/instagram-reels-unlocking-the-ninja-mindset/"><u>Instagram Reels  Unlocking the Ninja Mindset</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-the-malfunction-of-defrag-in-windows-os/"><u>Mending the Malfunction of Defrag in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-vmwares-non-boot-windows-11-mistakes/"><u>Preventing VMware's Non-Boot Windows 11 Mistakes</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-in-2024-a-guide-to-find-a-high-quality-video-marketing-agency/"><u>Updated In 2024, A Guide to Find a High-Quality Video Marketing Agency</u></a></li>
<li><a href="https://windows11.techidaily.com/the-premier-lineup-of-zero-cost-must-haves-for-windows-11/"><u>The Premier Lineup of Zero-Cost Must-Haves for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-restricted-settings-due-to-user-level-administrator-controls/"><u>Eliminating Restricted Settings Due to User-Level Administrator Controls</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-motorola-moto-g84-5g-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Motorola Moto G84 5G to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-integration-windows-pc-plus-galaxy-via-samsung-flow/"><u>Seamless Integration: Windows PC + Galaxy via Samsung Flow</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-access-to-your-visual-data-with-windows-11/"><u>Immediate Access to Your Visual Data with Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-pictures-from-realme-by-fonelab-android-recover-pictures/"><u>How to Rescue Lost Pictures from Realme ?</u></a></li>
<li><a href="https://windows11.techidaily.com/key-to-performance-enhancement-with-windows-lav-filters-use/"><u>Key to Performance Enhancement with Window's LAV Filters Use</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-user-isolation-for-security-in-win-11/"><u>Mastering User Isolation for Security in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-reactivating-adobe-on-windows-os/"><u>Mastering the Art of Reactivating Adobe on Windows OS</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-ultimate-guide-to-secure-and-free-instagram-followers-iosandroid/"><u>In 2024, Ultimate Guide to Secure & Free Instagram Followers (iOS/Android)</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-update-issue-with-error-0x8024800c/"><u>Fixing Windows Update Issue with Error 0X8024800C</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-non-response-from-printmanagement-msc-errors/"><u>Eliminating Non-Response From 'Printmanagement' MSC Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-bypassing-the-components-not-found-issue-on-w10w11/"><u>Quick Fix: Bypassing the Components Not Found Issue on W10/W11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/failed-to-play-mp4-movies-with-huawei-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Failed to play MP4 movies with Huawei</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-stopping-discord-startup-and-updates/"><u>Troubleshooting: Stopping Discord Startup and Updates</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-how-to-share-tiktok-videos-to-facebook/"><u>2024 Approved  How to Share TikTok Videos to Facebook?</u></a></li>
<li><a href="https://windows11.techidaily.com/peeling-back-the-layers-of-runtime-brokers-on-pcs/"><u>Peeling Back the Layers of Runtime Brokers on PCs</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/rapid-fire-guide-to-successful-double-exposures/"><u>Rapid-Fire Guide to Successful Double Exposures</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-error-1-secure-your-minecraft-adventures/"><u>Overcome Error 1: Secure Your Minecraft Adventures</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713948747943-are-you-planning-to-make-a-product-review-video-but-wondering-how-to-set-up-your-background-if-so-then-youre-in-the-right-place-this-post-will-show-you-how-/"><u>Are You Planning to Make a Product Review Video but Wondering How to Set up Your Background? If so, Then Youre in the Right Place. This Post Will Show You How to Adjust the Background to Black for Your Product Review Video for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/precision-in-picture-editing-eliminating-backgrounds-effectively/"><u>Precision in Picture Editing: Eliminating Backgrounds Effectively</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-10-best-intro-video-makers-for-pc-a-comprehensive-review-for-2024/"><u>New 10 Best Intro Video Makers for PC A Comprehensive Review for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/5-quick-methods-to-bypass-zte-nubia-z60-ultra-frp-by-drfone-android/"><u>5 Quick Methods to Bypass ZTE Nubia Z60 Ultra FRP</u></a></li>
<li><a href="https://windows11.techidaily.com/expanding-linux-horizons-through-windows-apps/"><u>Expanding Linux Horizons Through Windows Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/recover-lost-windows-customizations-on-reboot/"><u>Recover Lost Windows Customizations on Reboot</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/efface-thin-borders-for-a-seamless-youtube-experience/"><u>Efface Thin Borders for a Seamless YouTube Experience</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-leading-speech-recording-software-for-mac-discovering-our-five-favorites/"><u>[New] 2024 Approved  Leading Speech Recording Software for Mac  Discovering Our Five Favorites</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-dismantle-spotlight-icons-in-win11/"><u>Guide to Dismantle Spotlight Icons in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-alomware-resource-for-windows-tweakers/"><u>The Ultimate AlomWare Resource for Windows Tweakers</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-capturing-and-organizing-uac-alert-snaps/"><u>Tips for Capturing and Organizing UAC Alert Snaps</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-itel-s23-phone-password-without-factory-reset-by-drfone-android/"><u>How to Unlock Itel S23 Phone Password Without Factory Reset?</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-choosing-and-changing-screensavers-in-win11/"><u>The Art of Choosing and Changing Screensavers in Win11</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/t-tips-on-jump-cuts-for-dynamic-video-editing/"><u>Expert Tips on Jump Cuts for Dynamic Video Editing</u></a></li>
<li><a href="https://windows11.techidaily.com/re-establish-missing-5ghz-connection-easily-in-windows-11/"><u>Re-Establish Missing 5GHz Connection Easily in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-cutting-back-cpu-overuse-in-windows-systems/"><u>Strategies for Cutting Back CPU Overuse in Windows Systems</u></a></li>
</ul></div>
