---
title: Bypassing the GPSVC Wait Issue on PCs
date: 2024-07-11T22:15:56.781Z
updated: 2024-07-12T22:15:56.781Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bypassing the GPSVC Wait Issue on PCs
excerpt: This Article Describes Bypassing the GPSVC Wait Issue on PCs
keywords: Bypass GPSVC Error,Fix PC GPSVC Delay,Resolve GPSVC On PC,Avoid GPSVC Lockup,Unblock PC GPSVC Wait,Eliminate PC GPSVC Latency,Stop PC GPSVC Stall
thumbnail: https://thmb.techidaily.com/f48c4b3b1ae7e8d504b5fa9d1d43efb4b89cbd743a49407bfffb933b836abc89.png
---

## Bypassing the GPSVC Wait Issue on PCs

 The "Please wait for the GPSVC" loop in Windows is a frustrating issue that can cause the system to get stuck upon a shutdown attempt. This loop is related to the Group Policy Client Service (GPSVC).

 Below, we take a look at the different causes of this problem, followed by the solutions you can try to fix it.

## What Does “Please Wait for the GPSVC” Mean?

 The "Please wait for the GPSVC" statement occurs while the system is waiting for the Group Policy Client Service (GPSVC) to complete certain active processes. This service works by managing and applying the group policies in your Windows system.

 The time this service takes to complete the process can depend upon factors such as the complexity of the Group Policy settings, network connectivity, and the performance of the system. While it is generally recommended to avoid interrupting the process till it completes, there are times when this loop can take forever to end.

 This normally happens due to one or more of the following reasons:

* **Group Policy errors**: The Group Policy settings in your computer may have been corrupted, which is preventing the GPSVC process from completing successfully.
* **Third-party software conflicts**: A third-party software or services might be conflicting with the GPSVC process, causing it to get stuck in a loop.
* **System file corruption**: If the essential system files on which the Group Policy or the GPSVC processes depend become corrupted or damaged, it can lead to the system getting stuck in loops, improper shutdowns, disk errors, or malware infections.
* **Malware or viruses**: Malware can also interrupt system processes deliberately. The malware or virus in your system might be attempting to gain control over your system by interfering with GPE.

 It is essential to note that the exact cause of this loop can vary, depending upon different circumstances. However, regardless of what the cause might be, the troubleshooting methods we have listed below are sure to help you fix the issue for good.

## Setting Up Your PC for Troubleshooting

 To start the troubleshooting, you must be able to access your system. This can be done in two ways; you can either [perform a Windows reboot](https://www.makeuseof.com/windows-restart-methods/) to break the loop using the Ctrl + Alt + Delete menu or enter the Safe Mode.

 If you have tried rebooting but the error pops up again, you can boot into the Safe Mode through Windows Recovery Environment.

 This will launch the system with a set of only the necessary drivers and services. Once you are in Safe Mode, you can take further steps to diagnose the issue and fix it.

 Here is how you can do that:

1. Shut down your computer and use the power button to restart.
2. When the computer is loading, use the power button to force shutdown again. You can do this by pressing and holding the power button).
3. Repeat this twice and on the third attempt, Windows will boot into the Recovery Environment automatically.
4. Choose **Troubleshoot** \> **Advanced options**.  
![WinRE-Advanced-Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/winre-advanced-options.jpg)
5. Click on **Startup settings** and select **Restart**.
6. Wait for the computer to restart and then press the 4, 5, or 6 keys to boot into Safe Mode.

 Once you are in Safe Mode, proceed with the solutions we have listed below.

## 1\. Restart the Group Policy Client Service

 The GPSVC service itself might be dealing with a temporary glitch or a corruption error that is causing it to malfunction. The easiest way to fix issues with the service is by restarting it.

 Here is how you can do that:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "services.msc" in Run and click **Enter**.
3. In the following window, look for the Group Policy Client service and right-click on it.
4. Choose **Properties** from the context menu.  
![Access the Group Policy Client properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/group-policy-client-properties.jpg)
5. Now, click on the **Stop** button, wait for a few seconds, and click **Start**.
6. Expand the dropdown for Startup type and choose **Automatic**.
7. Click **Apply** \> **OK** to save the changes.

 You can now exit the Services window and check if the issue is resolved.

## 2\. Reset the Local Group Policy Settings

![Reset Group Policy using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Reset-Group-Policy-using-Command-Prompt.jpg)

 As we mentioned earlier, there can be an issue with the Local Group Policy settings. To check if this is the case in your situation, you can reset the Local Group Policy settings. This will restore the configurations to the default state, eliminating any potential conflicts that may have caused the issue.

 However, before you proceed, it is important to note that this will also remove any customizations or modifications you made via GPE.

 If that is not a problem, follow these steps to proceed:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "cmd" in Run and press **Ctrl** \+ **Shift** \+ **Enter** keys together.
3. Choose **Yes** in the User Account Control prompt.
4. In Command Prompt, execute the command below:  
`RD /S /Q "%WinDir%\System32\GroupPolicyUsers" && RD /S /Q "%WinDir%\System32\GroupPolicy"`
5. Once the command executes, proceed with the following command:  
`gpupdate.exe /force`
6. Finally, restart your computer and check if the issue is resolved.

## 3\. Modify the GPSVC Registry File

 There is also a chance that the GPSVC registry keys are missing or corrupt, which is preventing the service from functioning properly. Such issues can be fixed by modifying the relevant values as shown below.

 Before proceeding, we recommend that you [create a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/), just to be safe. Once that is done, follow these steps to proceed:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "regedit" in Run and click **Enter**.
3. Click **Yes** in the User Account Control prompt.
4. In the Registry Editor, navigate to the location below:  
`​​​​​​​​​​​​​​Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Svchost`
5. Right-click on **Svchost** and choose **New** \> **Key**.
6. Name this key as **GPSvcGroup**.
7. Double-click on **GPSvcGroup** and right-click anywhere in the right pane.
8. Choose **New** \> **DWORD (32-bit) Value** and rename this value as **AuthenticationCapabilities**.
9. Double-click on **AuthenticationCapabilities** and select the Base to **Decimal**.
10. Type "12320" in Value data and click **OK**.  
![AuthenticationCapabilities key in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/authentican-key.jpg)
11. Now, create another key **CoInitializeSecurityParam** in a similar way.
12. Set its base to **Hexadecimal** and type "1" in Value data.  
![CoInitializeSecurityParam key in the Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/coinitializesecurityparam-key.jpg)
13. Click **OK** to save the changes and then restart your PC. Hopefully, upon reboot, you will no longer face the error.

 Apart from these specific fixes, you can also try [performing a system restore](https://www.makeuseof.com/tag/system-restore-factory-reset-work-windows-10/) or scanning the system [using the built-in SFC and DISM Windows tools](https://www.makeuseof.com/windows-built-in-repair-tools/). The former will help revert the system to an older, error-free state, while performing a system scan will help fix any corruption errors in the system that might be contributing to the problem.

## GPSVC Loops on Windows, Fixed

 The "Please Wait for the GPSVC" loop doesn't have to be a permanent problem. Hopefully, the solutions above will help you fix this issue for good. If the problem persists, it is always recommended to seek assistance from technical experts or Microsoft support.

 Below, we take a look at the different causes of this problem, followed by the solutions you can try to fix it.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/eliminating-windows-dism-failure-0x800f082f-quickly/"><u>Eliminating Windows' DISM Failure 0X800F082F Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-windows-pe-file-system/"><u>Decoding Windows' PE File System</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-your-gear-use-efficiently-using-windows-interfaces/"><u>Navigate Your Gear Use Efficiently Using Windows Interfaces</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-10-no-fuss-methods-to-record-audio-on-your-chromebook/"><u>New 2024 Approved 10 No-Fuss Methods to Record Audio on Your Chromebook</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-your-system-without-relying-on-bitlocker/"><u>Securing Your System without Relying on Bitlocker</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-11-usage-chronicles/"><u>Navigating Through Windows 11 Usage Chronicles</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-streamers-financial-compliance-check/"><u>In 2024, Streamer's Financial Compliance Check</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-combating-content-id-blocks-on-youtube-with-knowledge-for-2024/"><u>[New] Combating Content ID Blocks on YouTube with Knowledge for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/redoing-power-schemes-with-lost-settings-win-11/"><u>Redoing Power Schemes with Lost Settings (Win 11)</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-oneplus-nord-n30-5g-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Location is Not Updating and How to Fix On OnePlus Nord N30 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/curtailing-spontaneous-console-appearance-triggers/"><u>Curtailing Spontaneous Console Appearance Triggers</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-make-your-retro-games-look-like-they-used-to-with-retroarchs-shaders/"><u>How to Make Your Retro Games Look Like They Used to With RetroArch’s Shaders</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-call-issue-fixed-runtime-errors-in-malwarebytes-for-win10win11/"><u>Overcoming the Call Issue: Fixed Runtime Errors in Malwarebytes for Win10/Win11</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-android-gaming-elevated-in-depth-look-at-the-breakthrough-app-kinemaster-for-2024/"><u>[New] Android Gaming Elevated - In-Depth Look at the Breakthrough App, KineMaster for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/ease-into-accessibility-windows-fundamentals-for-novices/"><u>Ease Into Accessibility: Windows Fundamentals for Novices</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-surface-laptop-go-3-review-new-processor-same-old-drawbacks/"><u>Microsoft Surface Laptop Go 3 Review: New Processor, Same Old Drawbacks</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/make-every-frame-count-a-list-of-the-hottest-50-video-reducing-apps-for-your-phone-for-2024/"><u>Make Every Frame Count  A List of the Hottest 50 Video-Reducing Apps for Your Phone for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-hyper-v-for-efficient-linux-vm-creation-in-windows/"><u>Leveraging Hyper-V for Efficient Linux VM Creation in Windows</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-streamline-your-youtube-productions-with-pc-editing-techniques/"><u>2024 Approved  Streamline Your YouTube Productions with PC Editing Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-read-only-status-in-1011s-file-directories/"><u>Remedying Read-Only Status in 10/11'S File Directories</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-expert-tags-analyzer-software-fb-tweet-and-insta-edition-for-2024/"><u>[New] Expert Tags Analyzer Software  FB, Tweet & Insta Edition for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-performance-with-5-wsl-2-enhancements/"><u>Maximizing Performance with 5 WSL 2 Enhancements</u></a></li>
<li><a href="https://windows11.techidaily.com/rectify-windows-error-reestablishing-java-vm/"><u>Rectify Windows Error: Reestablishing Java VM</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-screen-glitches-in-windows-11-a-step-by-step-guide/"><u>Solving Screen Glitches in Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/the-rise-of-a-monetary-maestro-ajeys-youtube-earnings-story-for-2024/"><u>The Rise of a Monetary Maestro  Ajey's YouTube Earnings Story for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/harmonize-workflow-setting-active-hours-on-windows-11-for-peace-of-mind/"><u>Harmonize Workflow: Setting Active Hours on Windows 11 for Peace of Mind</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/guide-to-mirror-your-vivo-s18-to-other-android-devices-drfone-by-drfone-android/"><u>Guide to Mirror Your Vivo S18 to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-breaking-into-youtubes-top-100-with-effective-seo/"><u>[Updated] 2024 Approved  Breaking Into YouTube's Top 100 With Effective SEO</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-workspace-malfunctions-essential-tips-for-office-on-winos/"><u>Resolving Workspace Malfunctions: Essential Tips for Office on WINOS</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/can-you-unlock-apple-iphone-xs-max-after-forgetting-the-passcode-by-drfone-ios/"><u>Can You Unlock Apple iPhone XS Max After Forgetting the Passcode?</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-mastering-text-additions-on-tiktok/"><u>[New] In 2024, Mastering Text Additions on TikTok</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-artistic-excellence-foremost-ios-art-tools/"><u>[New] Artistic Excellence  Foremost iOS Art Tools</u></a></li>
<li><a href="https://unlock-android.techidaily.com/a-complete-guide-to-oem-unlocking-on-xiaomi-13t-by-drfone-android/"><u>A Complete Guide To OEM Unlocking on Xiaomi 13T</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-the-modern-creators-ultimate-tiktok-toolkit/"><u>[Updated] The Modern Creator’s Ultimate TikTok Toolkit</u></a></li>
<li><a href="https://windows11.techidaily.com/faster-task-management-display-in-windows-11-os/"><u>Faster Task Management Display in Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-windows-users-through-system-slumber/"><u>Guiding Windows Users Through System Slumber</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-fixing-common-apex-freezes-on-w11/"><u>Expert Advice: Fixing Common Apex Freezes on W11</u></a></li>
<li><a href="https://windows11.techidaily.com/seeking-entry-into-the-windows-11-insider-circle/"><u>Seeking Entry Into the Windows 11 Insider Circle</u></a></li>
<li><a href="https://windows11.techidaily.com/regaining-control-over-your-speakers-settings-in-windows/"><u>Regaining Control over Your Speakers' Settings in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/prevent-windows-stop-recurrent-file-explorer-launches/"><u>Prevent Windows: Stop Recurrent File Explorer Launches</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/bes-payment-system-a-monthly-breakdown/"><u>YouTube’s Payment System  A Monthly Breakdown</u></a></li>
<li><a href="https://audio-editing.techidaily.com/enhancing-accessibility-documenting-computer-audio-in-audacity-for-2024/"><u>Enhancing Accessibility Documenting Computer Audio in Audacity for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/what-legendaries-are-in-pokemon-platinum-on-samsung-galaxy-s24-drfone-by-drfone-virtual-android/"><u>What Legendaries Are In Pokemon Platinum On Samsung Galaxy S24? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-notepad-in-w11-with-intelligent-guide/"><u>Enhance Notepad in W11 with Intelligent Guide</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-elevate-photo-quality-discover-the-best-10-web-enhancement-software/"><u>2024 Approved  Elevate Photo Quality  Discover the Best 10 Web Enhancement Software</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-absent-windows-extras-a-comprehensive-guide/"><u>Reviving Absent Windows Extras: A Comprehensive Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-route-engaging-windows-11s-capture-utility/"><u>Quick Route: Engaging Windows 11'S Capture Utility</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-basics-top-settings-to-optimize-on-new-windows-11/"><u>Mastering the Basics: Top Settings to Optimize on New Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-efficiency-how-copilot-key-shapes-your-windows-11-experience/"><u>Mastering Efficiency: How Copilot Key Shapes Your Windows 11 Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-gl-driver-error-3-on-windows-11-a-step-by-step-guide/"><u>Resolving GL Driver Error 3 on Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11-align-your-sticky-notes-accurately/"><u>Navigating Windows 11: Align Your Sticky Notes Accurately</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-streamer-soundscape-the-top-5-headset-guidebook/"><u>[Updated] Streamer Soundscape  The Top 5 Headset Guidebook</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-unavailable-nvidia-cp-on-windows-11/"><u>Overcoming Unavailable Nvidia CP on Windows 11</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-brand-your-content-download-complimentary-templates-for-youtube-makers/"><u>[Updated] Brand Your Content  Download Complimentary Templates for YouTube Makers</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-unstoppable-methods-to-turn-off-ms-defender/"><u>Mastering Unstoppable Methods to Turn Off MS Defender</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-15-to-other-iphone-12-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 15 To Other iPhone 12 devices? | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-original-cinematic-footage-assessment-and-substitutes/"><u>[Updated] Original Cinematic Footage Assessment & Substitutes</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-searching-on-windows-techniques-beyond-ls-command/"><u>Seamless Searching on Windows: Techniques Beyond LS Command</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-can-i-use-a-fake-gps-without-mock-location-on-nokia-c32-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Use a Fake GPS Without Mock Location On Nokia C32? | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-in-2024-boosting-video-popularity-on-tiktoks-top-list/"><u>[Updated] In 2024, Boosting Video Popularity on TikTok's Top List</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-would-you-like-to-know-how-to-change-the-ratio-of-the-video-or-which-is-the-correct-aspect-ratio-for-uploading-to-the-online-platform-then/"><u>New 2024 Approved Would You Like to Know How to Change the Ratio of the Video or Which Is the Correct Aspect Ratio for Uploading to the Online Platform? Then, Go Through the Article to Get Complete Details About the Video Aspect Ratio</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/top-4-ways-to-trace-apple-iphone-13-pro-max-location-drfone-by-drfone-virtual-ios/"><u>Top 4 Ways to Trace Apple iPhone 13 Pro Max Location | Dr.fone</u></a></li>
</ul></div>
