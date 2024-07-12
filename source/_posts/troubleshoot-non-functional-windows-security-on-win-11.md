---
title: Troubleshoot Non-Functional Windows Security on Win 11
date: 2024-07-11T21:46:10.627Z
updated: 2024-07-12T21:46:10.627Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshoot Non-Functional Windows Security on Win 11
excerpt: This Article Describes Troubleshoot Non-Functional Windows Security on Win 11
keywords: Fix Win 11 Secure Errors,Win 11 Security Troubleshooting,Resolve Win 11 Auth Failures,Windows 11 Security Fixes,Win 11 Security Recovery Steps,Remedy Windows 11 Lockout Issue,Solutions for Win 11 Security Halt
thumbnail: https://thmb.techidaily.com/23f15d03527dcdfd4e30255dbd41a14d668e3faafe915e31c07d32bad6007903.png
---

## Troubleshoot Non-Functional Windows Security on Win 11

 Windows Security is a free and default antivirus program provided by Microsoft to protect your PC from outside threats. However, there are times when the security software might stop working properly, or in some cases, not start at all. And to top off, if you’re also not using a third-party antivirus app, you're basically wide open to a myriad of security attacks.

 It's therefore crucial that Windows security is working at its best; this will keep your computer security airtight. In this article, we’ve laid down some of the best tricks that will help you fix Windows Security on your Windows 11\.

## 1\. Turn on Windows Security

 In rare cases when a PC undergoes a malicious attack one of the first things that the malicious program does is [turn off all the antivirus defenses like Microsoft Defender](https://www.makeuseof.com/how-to-turn-off-microsoft-defender-windows-11/). If your PC has undergone such an attack recently, then it might be possible that you're facing the same issue.

 If that's indeed the case then you'll have to manually enable Windows Security on your PC. Follow these steps to continue:

1. Head to the **Start menu** search bar, type in 'security,' and select the best match.
2. From there, click on **Turn on** to enable the **Virus & threat protection** of your PC.
3. A new dialog box will pop up asking you to confirm if you want to go ahead with the changes; click on **Yes** to proceed.

![security at glance menu in windows security settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-security.jpg)

 The Windows Security app will be enabled instantly.

## 2\. Update Windows 11

 How long has it been since you last updated your Windows? If it’s been a while, it might be a good time to brush off the dust from your updates.

 Follow these steps to check for updates on your Windows PC:

1. Go to the **Start menu** search bar, type in ‘settings,’ and select the Best match. Alternatively, press **Win + I** together.
2. Scroll down and select **Windows Update**.
3. Now click on **Check for updates** and Windows will start checking for updates on your PC. (If any new updates are available, they’ll be displayed on the **Windows Update** screen.)
4. Finally, click on **Download & install** to get the ball rolling.

![windows update section in the settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/windows-update-1.png)

 When the updates download is complete, give your PC a quick restart and see if the problem with Windows Security persists. If it does, then jump below to the next method.

## 3\. Disable Third-Party Antivirus

 If you have an additional antivirus installed on your PC, it might be a good time to get rid of it.

 Running Windows Security along with third-party antivirus apps has been known to cause many kinds of disruption in Windows computers. So removing the additional antivirus might, in fact, be a fair approach—remove the antivirus and see if it can get everything back to normal.

 To get started, launch the **Settings** again. Go to **Apps > Apps & features**, search for the antivirus, and when you find it, click on options (three dots) and select **Uninstall**.

![apps and features in the apps settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/apps-and-feature.png)

 The third-party antivirus will be removed. Now restart your Windows 11 and see if the problem with Windows Security persists. It shouldn’t.

## 4\. Reset the Windows Security App

 Removing the third-party antivirus app from your PC should get your Windows Security back to work in most cases. However, in cases where it's not, it might be time to do a complete reset of your Security app.

 Follow these steps to reset the Windows Security app:

1. Go to the **Settings** menu again by pressing the **Windows key + I**.
2. Select **App > Apps & features** and type in ‘security’ in the search menu box.
3. An icon for Windows Security will pop open. From there, click on the **options** (three dots) and select **Advanced options**.
4. Now scroll down to **Reset** section and click on **Reset**.

 You’ll get a confirmation asking if you really want to reset the app, along with your whole app data. Click on **Reset** to go with it.

![reset and repair option in the windows security settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/reset-and-repair.jpg)

 You can also try the **Repair** option if you don't want to reset the app right off. It’s right there above the **Reset** option. As soon you click on **Repair**, the process will begin. When the Repair is complete, it’ll leave a tick option adjacent to **Repair** box.

## 5\. Run an SFC and DISM Scan

 SFC, short for System File Checker, is a Windows utility that can be fallen back upon when some of your Windows files malfunction. In short, it checks for file corruption and then tries to repair it.

 It is accessed through the Command prompt. To get started, go to the **Start menu** search bar, type in ‘command prompt,’ and then launch it as administrator.

 This launches your Command prompt in an elevated mode, something necessary to run the SFC utility.

 In the Command prompt, type the following command and hit **Enter**:

`sfc/ scannow`

 The tool will scan your PC and you should be able to run the Security app by the end.

![execution of sfc scan in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/sfc-scan-in-command-prompt.png)

 If the SFC tool doesn't work, don't fret just yet. Another tool that you can try your luck with is the DISM; it's not the same as SFC, but it works almost similarly. You can check out the [differences between SFC and DISM](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) if you'd like to learn more.

 Much like how the SFC tool helps you fix your PC, a DISM scan finds and fixes any issues with your system image that might be causing problems with your PC's functioning.

 Like with SFC scan above, you’ll have to launch the DISM as an administrator as well. Go to the **Start menu,** type in ‘DISM,’ and run it as administrator. When you launch the DISM scan, enter the following command and hit **Enter**:

`DISM /Online /Cleanup-Image /ScanHealth`

![execution of dsim scan in the command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/dsim-scan-command-prompt.png)

 As soon as the command finishes executing, your files would've been scanned and all the corruption issues would most possibly have been resolved.

 When you’re done, [simply restart your PC](https://www.makeuseof.com/windows-restart-methods/) for the changes to take effect, and see if the problem persists.

## 6\. Restart the Windows Security Service

 Windows Security makes use of a host of programs and services for smooth functioning on your PC. One of those handy services is the Windows Security Center service which monitors the security state of the important components of your system.

 So, if your Windows Security app stopped opening, or if it crashed midway, we suggest you restart your Windows Security Center Service right away. To get started, follow the steps below:

1. Press **Win + R** and type "services.msc" and hit the Enter key.
2. Here, scroll down to find and right-click on **Security-Center** and then select **Restart**.

![security services process in the services app on windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/services-app-windows-11.jpg)

 That's it. Follow any other on-screen instructions and wait for the service to reboot of the service. When that's done, restart your PC and the Windows Security service will be fixed by the next boot-up.

## 7\. Reset Your PC

 A panacea for almost all [the common Windows bugs](https://www.makeuseof.com/common-windows-11-problems/), the **Reset Your PC** setting resets your computer and brings it to its initial state. It’s far better than reinstalling the whole Windows, as you can reset your PC while also keeping your personal files and folders intact.

 To get started, follow the steps below:

1. Go to the **Start menu** search bar, type in ‘settings,’ and select the Best match.
2. In the **Settings** menu, click on **System > Recovery**.
3. In the **Recovery options** tab, click on Reset PC.
4. Then select **Keep my files > Local reinstall** and click on **Next**.

![two types of reset options in the reset this pc on windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/reset-this-pc-windows-11.png)

 That’s it. Follow the onscreen instructions ahead and your Windows will be formatted and reinstalled in no time. When your PC restarts, all your settings will be at ground zero again.

 The whole process is fairly straightforward, but if you face any difficulties during the reset, make sure you go through a [complete guide on Windows 10 factory reset](http://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) and verify if you're making any slip-ups in between the steps.

## Fixing the Issues With Windows Security

 Windows Security is a must-have for Windows health. However, the app can sometimes malfunction and stop working properly. Hopefully, one of the methods laid out above helped you get it working once again.

 But that's not all; There are a ton of ways you can dial up your PC’s security, so make sure you aren’t simply relying only on Windows security for your PC's cyber protection.

 It's therefore crucial that Windows security is working at its best; this will keep your computer security airtight. In this article, we’ve laid down some of the best tricks that will help you fix Windows Security on your Windows 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-recording.techidaily.com/speech-capture-device-scrutiny/"><u>Speech Capture Device Scrutiny</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-the-root-of-windows-update-problems-0xc1900101/"><u>Eliminating the Root of Windows Update Problems (0xC1900101)</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-installation-of-intel-wi-fi-drivers/"><u>Navigating the Installation of Intel Wi-Fi Drivers</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-in-2024-eliminating-audible-hum-techniques-for-silence-in-recorded-sounds/"><u>New In 2024, Eliminating Audible Hum Techniques for Silence in Recorded Sounds</u></a></li>
<li><a href="https://windows11.techidaily.com/harnessing-power-using-lav-filters-on-microsoft-windows/"><u>Harnessing Power: Using LAV Filters on Microsoft Windows</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/1714258720165-new-here-is-how-you-can-do-it-effectively-either-with-built-in-tools-provided-by-tiktok-or-with-additional-pieces-of-reverser-tools-to-reverse-a-tiktok-vide/"><u>New Here Is How You Can Do It Effectively, Either with Built-In Tools Provided by TikTok or with Additional Pieces of Reverser Tools to Reverse a TikTok Video for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-windows-watcher-functionality/"><u>Disabling Windows Watcher Functionality</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-2024-approved-the-ultimate-selection-of-5-premium-mac-audio-equipment/"><u>Updated 2024 Approved The Ultimate Selection of 5 Premium Mac Audio Equipment</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-top-9-steps-for-efficient-volume-management-in-windows-11/"><u>Discover Top 9 Steps for Efficient Volume Management in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-to-resolve-winerror-0x8007043c/"><u>Navigating to Resolve WinError 0X8007043C</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-visual-quality-with-hdr-on-windows-11/"><u>Maximizing Visual Quality with HDR on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-kali-installation-guide-for-windows-users/"><u>Effortless Kali Installation Guide for Windows Users</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-explore-online-communities-with-youtube-monetization-opportunities/"><u>[New] 2024 Approved  Explore Online Communities with YouTube Monetization Opportunities</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-turn-off-chrome-prompts-windows-users/"><u>How to Turn Off Chrome Prompts Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/journey-to-mastery-original-diablo-basics-explained/"><u>Journey to Mastery: Original Diablo Basics Explained</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-viral-video-quarterly-watch-for-2024/"><u>[New] Viral Video Quarterly Watch for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-maze-of-non-downloading-on-windows-devices/"><u>Navigating the Maze of Non-Downloading on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-change-your-cursor-on-windows/"><u>How to Change Your Cursor on Windows</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-secrets-unveiled-the-top-10-for-dominating-in-tiktok-marketing/"><u>[Updated] Secrets Unveiled  The Top 10 for Dominating in TikTok Marketing</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-system-appearance-with-custom-pointer-design/"><u>Enhancing System Appearance with Custom Pointer Design</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-printer-sharing-challenges-in-windows/"><u>Navigating Printer Sharing Challenges in Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-nokia-xr21-get-deleted-phone-number-back-with-ease-and-safety-by-fonelab-android-recover-contacts/"><u>How to Nokia XR21 Get Deleted Phone Number Back with Ease and Safety</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-forgotten-windows-add-ons-and-utilities-in-7-ways/"><u>Enabling Forgotten Windows Add-Ons and Utilities in 7 Ways</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-change-reset-count-after-login-failures-a-windows-11-technique/"><u>How to Change Reset Count After Login Failures: A Windows 11 Technique</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-pokemon-go-error-12-failed-to-detect-location-on-apple-iphone-8-drfone-by-drfone-virtual-ios/"><u>In 2024, Pokemon Go Error 12 Failed to Detect Location On Apple iPhone 8? | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-proper-techniques-for-easy-iphone-screen-recording/"><u>[Updated] Proper Techniques for Easy iPhone Screen Recording</u></a></li>
<li><a href="https://windows11.techidaily.com/lock-it-down-steps-to-activate-windows-controlled-access/"><u>Lock It Down: Steps to Activate Window’s Controlled Access</u></a></li>
<li><a href="https://windows11.techidaily.com/fast-track-to-windows-11-arm-with-easy-iso-setup-instructions/"><u>Fast Track to Windows 11 ARM with Easy ISO Setup Instructions</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-open-the-phone-dialer-in-windows-11/"><u>How to Open the Phone Dialer in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-aggregatorhostexe-in-windows-how-it-works-and-safety-aspects/"><u>Exploring AggregatorHost.exe in Windows: How It Works and Safety Aspects</u></a></li>
<li><a href="https://windows11.techidaily.com/free-windows-11-slideshows-the-seventh-way-unveiled/"><u>Free Windows 11 Slideshows - The Seventh Way Unveiled</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-unveiling-social-network-regulations-can-you-share-videos/"><u>[Updated] In 2024, Unveiling Social Network Regulations  Can You Share Videos?</u></a></li>
<li><a href="https://network-issues.techidaily.com/windows-11-black-screen-after-fall-creators-update-solved/"><u>Windows 11 Black Screen After Fall Creators Update [Solved]</u></a></li>
</ul></div>
