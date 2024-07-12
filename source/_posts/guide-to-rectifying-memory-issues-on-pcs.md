---
title: Guide to Rectifying Memory Issues on PCs
date: 2024-07-11T22:04:34.460Z
updated: 2024-07-12T22:04:34.460Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Rectifying Memory Issues on PCs
excerpt: This Article Describes Guide to Rectifying Memory Issues on PCs
keywords: Fixing PC Memory Issues,Clear RAM Problems,Improve Computer Speed,Address Bad Memory,Resolve Memory Errors,Optimize System Performance,Enhance PC Functionality
thumbnail: https://thmb.techidaily.com/7677f4cd9df16c6a66672a56bd970deac980e4b074d81c3008e2f891a827245d.jpg
---

## Guide to Rectifying Memory Issues on PCs

 Using the Windows Memory Diagnostic tool, you can diagnose memory issues on your Windows computer. If there is a problem, it will return an error. One common Windows Memory Diagnostic error you may encounter is "Hardware problems were detected; contact manufacturer," followed by the "You have a memory problem" dialog.

 This error can be a false positive. You can also confirm the same by using a third-party memory diagnostic tool. In case of a hardware issue, you may need to replace the memory stick or repair the memory slot, if possible.

## What Causes the Windows Memory Diagnostic Hardware Problems Were Detected Error?

 This error is often triggered after a blue screen of death (BSOD) or the system freezing issues. The reason for the error can vary and include faulty memory slots and memory sticks. It can also be a false positive due to a Windows OS glitch.

## 1\. Check for Overclocking Issues

 Incorrect overclocking can cause hardware issues. While faster RAM can help you achieve good performance, it is important to consider the hardware limitations before applying the tweaks.

 If you have overclocked your RAM, try to lower the frequencies to see if the error goes away. Do this until you find a safe frequency, or reset it to factory default settings.

 If you are unsure about the default memory frequencies, try to perform a BIOS reset. Load the BIOS default, which should reset the RAM frequencies to its factory default. Refer to your motherboard manufacturer manual for specific instructions.

## 2\. Run the Hardware Troubleshooter

 The built-in Windows hardware troubleshooter can scan for hardware-related issues and even try to perform a repair if possible. If you haven’t tried already, run the hardware troubleshooter using the Command Prompt to resolve the problem.

 Note that it is a legacy troubleshooter, and you may not find it in the Windows 11 version newer than 22H2\.

 To run the Windows Hardware Troubleshooter:

1. Press the **Win** key and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator**. Click **Yes** if prompted by the User Account Control dialog.  
![run windows hardware troubleshooter command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-windows-hardware-troubleshooter-command-prompt.jpg)
3. In the Command Prompt window, type the following command and press **Enter**:  
`msdt.exe -id DeviceDiagnostic`
4. In the **Hardware and Devices** dialog, click **Next**. By default, the troubleshooter is set to apply any repairs available. To disable automatic repair, click **Advanced** and uncheck the **Apply repairs automatically** option.  
![hardware and devices troubleshooter windows 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/hardware-and-devices-troubleshooter-windows-1.jpg)
5. It will scan your computer for issues, which may take a few minutes. If an issue is detected, select to automatically apply the repair.
6. If the suggested problem is unrelated to memory, you can skip it to see the next problem. The troubleshooter will detect additional issues. If an issue is found, apply the fixes and check for any improvements.

## 3\. Remove and Reinsert Your Memory Sticks

 If you work with multiple memory sticks, remove all the sticks and wipe the card to remove dust and debris. Reboot the computer and check for any improvements.

 Still not working? Remove all but one stick and reboot your computer to see if the error is resolved. If not, repeat the procedure with all the sticks individually to determine and detect a faulty memory stick. If you find a faulty memory module, you can get a replacement or claim a warranty if available.

 If the issue persists, check your memory (RAM) slots for fault. Insert a memory stick into one of the slots and reboot your computer. If there is no error, test other slots and check if you can find a malfunctioning slot.

 If you determine a faulty RAM slot to have caused the issue, repairing it is tedious. First, RAM slots aren’t easily accessible like memory sticks. Second, to replace the slot, you’ll need to find a spare but compatible motherboard with working slots and then solder the connections onto your motherboard.

 If repairing the slots is not possible, your only option is a motherboard replacement. Depending on your system configuration, this can be an expensive solution. Or you can continue to use the system without utilizing the faulty memory slot, albeit with reduced performance.

## 4\. Test Your RAM with MemTest86+

 If the troubleshooter fails to detect any issue, you can perform a memory test using the MemTest86+ utility. It is an open-source memory testing tool to check for fails in your computer memory.

 MemTest86+ is a bootable utility and cannot be used from within Windows. To test your RAM with Memetst86+, you’ll need a USB drive. You can use the Memtest86+ Windows installer to create a bootable drive and boot from it.

 As of writing this article, Memtest86+ wasn’t compatible with Windows Secure Boot. So, you’ll need to disable Secure Boot to use the utility.

 To perform a memory test using Memtest86+:

1. Connect a USB flash drive to your computer. Take a backup of important data in the drive, as all the data will be deleted during the process.
2. Next, go to the [metest86+ page](https://www.memtest.org/) and download the latest version available.
3. Run the installer and select your USB drive. Make sure to select the format option.  
![memtest86 plus create bootable usb drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/memtest86-plus-create-bootable-usb-drive.jpg)
4. Click **Next** and wait for the installer to create a bootable drive.
5. Next, if you haven’t already, [disable Secure Boot on your Windows computer](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/).
6. Next, power off your computer. You may also need to clear your motherboard CMOS to reset your BIOS to factory default settings. You can also [reset BIOS to its default configuration](https://www.makeuseof.com/tag/reset-bios-default-settings-computer/) from the BIOS menu.  
![memtest86 plus memory integrity test in progress](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/memtest86-plus-memory-integrity-test-in-progress.png)
7. Next, plug the Memtest86+ bootable USB drive into your computer and turn it on.
8. Boot into the Boot Menu and select the bootable USB drive as the boot device. The hotkey key to enter the Boot Menu may vary depending on your computer manufacturer. You can press **F9** on an **HP** computer, **F12** on a **Dell** computer and so on to access the **Boot Menu**.
9. Memtest86+ will automatically start the memory integrity check. Let Memtest86+ complete at least 2 passes; the more, the better. Press the **Esc** key to stop the test if there are no errors after multiple passes.

 If an error is detected during testing, it is likely a case of faulty RAM and may need replacement. But to be on the safer side, ensure you test each RAM separately to find the odd one out.

 Not all the errors detected by the Memtest86+ are due to faulty hardware. Some errors may occur due to compatibility issues. Check your RAM module and the motherboard specifications to determine any compatibility issues. You can also test the RAM modules by inserting them into a different motherboard and see if it works.

## 5\. Perform a Repair Reinstall or Clean Install Windows

 If the Windows Memory Diagnostic tool continues to show the hardware problem was detected error, even after the Memtest86+ passed the test, check if the problem is due to issues with the Windows operating system.

 To fix critical issues with your Windows image, you can perform a [repair reinstall of Windows 11 without deleting apps](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/). If that does not work, perform a clean install. This will reinstall the operating system but delete all your apps and data from the computer. So, backup any data you need before attempting a clean install.

## Fixing the Memory Diagnostic Tool "Hardware Problem Detected" Error

 When an error is detected with your memory modules, the Windows Memory Diagnostic tool will show an error. While memory-related issues are often due to faulty hardware, make sure to run the device hardware troubleshooter to detect and resolve minor glitches.

 Alternatively, perform a memory integrity check using the Memtest86 tool. If the memory modules pass the Memtest86, you may need to perform a Windows OS clean install to fix issues with the Windows system files.

 This error can be a false positive. You can also confirm the same by using a third-party memory diagnostic tool. In case of a hardware issue, you may need to replace the memory stick or repair the memory slot, if possible.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/preventing-microsoft-teams-instability-on-ws11ws10-devices/"><u>Preventing Microsoft Teams Instability on WS11/WS10 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/switching-your-windows-security-pin-quickly/"><u>Switching Your Windows Security Pin Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-your-creative-potential-with-win11s-photos-app-creating-dynamic-slideshows-and-image-spot-repair/"><u>Unlock Your Creative Potential with Win11's Photos App: Creating Dynamic Slideshows & Image Spot Repair</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-proxy-powerhouses-the-top-video-editing-apps-for-4k/"><u>New In 2024, Proxy Powerhouses The Top Video Editing Apps for 4K</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-folder-menu-enhancement-with-new-commands-win-11/"><u>Step-by-Step Guide: Folder Menu Enhancement with New Commands (Win 11)</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-top-12-stand-alone-screen-capture-apps/"><u>In 2024, Top 12 Stand-Alone Screen Capture Apps</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-prime-8-tripod-picks-for-exceptional-4k-footage/"><u>[New] Prime 8 Tripod Picks for Exceptional 4K Footage</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-wifi-wisdom-accelerating-network-speed-assessment/"><u>Windows WiFi Wisdom: Accelerating Network Speed Assessment</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11s-software-compatibility-tool/"><u>Navigating Windows 11’S Software Compatibility Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-docx-to-pdf-workflow-in-windows-11-systems/"><u>Simplified DOCX to PDF Workflow in Windows 11 Systems</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/top-list-premier-episodes-on-googles-playlist/"><u>Top List  Premier Episodes on Google's Playlist</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-the-essential-guide-to-uploading-and-sharing-youtube-vids-in-insta-stories/"><u>[New] 2024 Approved  The Essential Guide to Uploading and Sharing YouTube Vids in Insta Stories</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-honor-100-pro-location-on-skout-drfone-by-drfone-virtual-android/"><u>How to Change Honor 100 Pro Location on Skout | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-rapidly-rendering-fortnite-cover-images/"><u>[New] Rapidly Rendering Fortnite Cover Images</u></a></li>
<li><a href="https://apple-account.techidaily.com/top-notch-solutions-for-disabled-apple-id-from-iphone-xs-max-making-it-possible-by-drfone-ios/"><u>Top-Notch Solutions for Disabled Apple ID From iPhone XS Max Making It Possible</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-audioadvisor-dacast-and-what-it-should-be-for-2024/"><u>[New] AudioAdvisor  DaCast & What It Should Be for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/best-mac-screen-capture-tools-for-2024/"><u>Best Mac Screen Capture Tools for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-failed-capture-issue-in-win11-photoapp/"><u>Overcoming 'Failed Capture' Issue in Win11 PhotoApp</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-in-2024-elevate-your-game-top-10-online-gaming-intro-generators/"><u>New In 2024, Elevate Your Game Top 10 Online Gaming Intro Generators</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-dual-monitor-setup-problems/"><u>Resolving Dual Monitor Setup Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-your-screen-without-pin-in-windows-11/"><u>Unlock Your Screen Without PIN in Window's 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-challenge-of-0x8007045d-error-on-windows-11/"><u>Overcoming the Challenge of 0X8007045d Error on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-group-policy-editor-navigation-windows-11-style/"><u>Mastering Group Policy Editor Navigation, Windows 11 Style</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-videos-from-honor-x7b-to-ipad-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Videos from Honor X7b to iPad | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-cleanup-stripping-out-microsoft-store/"><u>Win11 Cleanup: Stripping Out Microsoft Store</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-to-resolve-instant-failure-in-adding-a-folder-in-onedrive/"><u>Swift Solutions to Resolve Instant Failure in Adding a Folder in OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-potential-of-windows-11s-configurable-fn-keys/"><u>Mastering the Potential of Windows 11'S Configurable FN Keys</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/8-prime-vocal-tracking-and-editing-apps-suitable-for-mac-and-windows-devices-for-2024/"><u>8 Prime Vocal Tracking & Editing Apps Suitable for Mac and Windows Devices for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-resolving-m365-error-30015-26-on-pcs/"><u>Understanding and Resolving M365 Error 30015-26 on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-deleting-account-info-from-windows-logon/"><u>Steps for Deleting Account Info From Windows Logon</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-top-rated-video-voice-over-software-for-pc-review-and-download-for-2024/"><u>New Top-Rated Video Voice Over Software for PC - Review and Download for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-future-of-personal-computing-transforming-window-11-widgets/"><u>The Future of Personal Computing: Transforming Window 11 Widgets</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-troubleshooting-silent-voice-calls-in-valorant/"><u>Windows Troubleshooting: Silent Voice Calls in Valorant</u></a></li>
<li><a href="https://windows11.techidaily.com/nine-pathways-out-of-the-window-11s-0x8004def5-puzzle/"><u>Nine Pathways Out of the Window 11'S 0X8004DEF5 Puzzle</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivating-inputs-post-sleep-on-latest-windows/"><u>Reactivating Inputs Post-Sleep on Latest Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-and-resolving-outlooks-error-0x80040610/"><u>Navigating Through and Resolving Outlook's Error 0X80040610</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-the-ultimate-guide-to-mastering-social-video-ads-on-facebook/"><u>[New] 2024 Approved  The Ultimate Guide to Mastering Social Video Ads on Facebook</u></a></li>
<li><a href="https://windows11.techidaily.com/pro-tips-for-buying-windows-11-vcs/"><u>Pro Tips for Buying Windows 11 VCs</u></a></li>
<li><a href="https://windows11.techidaily.com/proactive-measures-for-sticky-notes-longevity/"><u>Proactive Measures for Sticky Notes' Longevity</u></a></li>
<li><a href="https://windows11.techidaily.com/learn-9-keys-to-tweaking-windows-audio-properties/"><u>Learn 9 Keys to Tweaking Windows Audio Properties</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-revolutionize-your-video-collection-from-amateur-to-pro-in-minutes/"><u>New Revolutionize Your Video Collection From Amateur to Pro in Minutes</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-notebook-interface-with-themes-and-fonts/"><u>Streamline Your Notebook Interface with Themes & Fonts</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-get-and-use-pokemon-go-promo-codes-on-lenovo-thinkphone-drfone-by-drfone-virtual-android/"><u>In 2024, How to Get and Use Pokemon Go Promo Codes On Lenovo ThinkPhone | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/remediation-techniques-for-resource-occupancy-errors-149-chars/"><u>Remediation Techniques for Resource Occupancy Errors (149 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/nullify-specification-shortfalls-alerts-in-win11/"><u>Nullify Specification Shortfalls Alerts in Win11</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-leap-into-a-bigger-view-the-new-full-screen-fb-video-trend/"><u>[New] 2024 Approved  Leap Into a Bigger View  The New Full-Screen FB Video Trend</u></a></li>
<li><a href="https://windows11.techidaily.com/the-clarity-connoisseurs-guide-top-tips-for-perfecting-pc-displays/"><u>The Clarity Connoisseur's Guide: Top Tips for Perfecting PC Displays</u></a></li>
<li><a href="https://extra-hints.techidaily.com/adjustment-tips-for-subtle-audio-reduction-in-logic-pro-for-2024/"><u>Adjustment Tips for Subtle Audio Reduction in Logic Pro for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-quick-video-sharing-tweet-it-up-no-need-for-retweets/"><u>[Updated] In 2024, Quick Video Sharing  Tweet It Up - No Need for Retweets</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-workflow-multitask-with-windows-11-expertise/"><u>Optimizing Workflow: Multitask with Windows 11 Expertise</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-taskbar-tools-monitoring-cpu-ram-and-disk-use/"><u>Tailored Taskbar Tools: Monitoring CPU, RAM & Disk Use</u></a></li>
<li><a href="https://windows11.techidaily.com/sudos-arrival-in-windows-os-explained/"><u>Sudo's Arrival in Windows OS Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/3-ways-to-adjust-the-mouse-double-click-speed-on-windows/"><u>3 Ways to Adjust the Mouse Double-Click Speed on Windows</u></a></li>
</ul></div>
