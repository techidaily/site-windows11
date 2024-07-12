---
title: Outdated PCs Upgraded to Modern Windows 11 Standards
date: 2024-07-11T21:12:07.278Z
updated: 2024-07-12T21:12:07.278Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Outdated PCs Upgraded to Modern Windows 11 Standards
excerpt: This Article Describes Outdated PCs Upgraded to Modern Windows 11 Standards
keywords: Old PC Upgrade,Windows 11 Modernization,11 Upgrade Pathway,Outdated Systems Revamp,New Windows Standards,Modern OS Transition,PC Compatibility Shift
thumbnail: https://thmb.techidaily.com/f99b0547d8a95f637159e251c131a6578ae71b255445af767dc74d5fd38281e0.jpg
---

## Outdated PCs Upgraded to Modern Windows 11 Standards

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
<li><a href="https://facebook-videos.techidaily.com/new-12-essential-websites-for-stunning-fb-profile-pictures-for-2024/"><u>[New] 12 Essential Websites for Stunning FB Profile Pictures for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/silencing-the-audio-stutter-taming-winirq-errors/"><u>Silencing the Audio Stutter: Taming WinIRQ Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-activities-gain-more-in-less-time-with-flow-launcher/"><u>Streamline Activities: Gain More in Less Time With Flow Launcher</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-evolution-unveiling-the-latest-system-updates/"><u>Windows 11'S Evolution: Unveiling the Latest System Updates</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-music-back-from-nokia-c12-plus-by-fonelab-android-recover-music/"><u>Simple ways to get lost music back from Nokia C12 Plus</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-listening-history-keeper-iphone-2024/"><u>[Updated] Listening History Keeper - iPhone 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/reconnecting-to-ea-servers-in-a-windows-environment/"><u>Reconnecting to EA Servers in a Windows Environment</u></a></li>
<li><a href="https://audio-editing.techidaily.com/audiobook-creation-simplified-your-comprehensive-step-by-step-tutorial/"><u>Audiobook Creation Simplified Your Comprehensive Step-by-Step Tutorial</u></a></li>
<li><a href="https://windows11.techidaily.com/scrutinizing-underused-windows-features-for-system-checks/"><u>Scrutinizing Underused Windows Features for System Checks</u></a></li>
<li><a href="https://windows11.techidaily.com/prioritize-and-achieve-a-guide-to-top-6-win-11-task-management-tools/"><u>Prioritize & Achieve - A Guide to Top 6 Win 11 Task Management Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/snip-and-sketch-vs-prtsc-the-best-tools-for-windows-users/"><u>Snip & Sketch Vs. PrtSc: The Best Tools for Windows Users</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/-to-prevent-thumbnail-absence-on-shorts-videos/"><u>Steps to Prevent Thumbnail Absence on Shorts Videos</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-2024-approved-how-to-reduce-background-noise-using-imovie-an-overview/"><u>Updated 2024 Approved How to Reduce Background Noise Using iMovie An Overview</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-spark-your-creativity-with-these-free-tools/"><u>[New] Spark Your Creativity with These Free Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-remedy-for-rearranged-character-inputs/"><u>Quick Remedy for Rearranged Character Inputs</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-overcome-run-as-command-issues/"><u>Strategies to Overcome 'Run As' Command Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-to-activate-rgb-settings-in-windows-11/"><u>Step-by-Step to Activate RGB Settings in Windows 11</u></a></li>
<li><a href="https://animation-videos.techidaily.com/looking-for-love-animated-gifs-here-are-5-free-sources-for-you-for-2024/"><u>Looking for Love Animated GIFs? Here Are 5 Free Sources For You for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-steam-service-problems-for-a-smooth-windows-11-experience/"><u>Solving Steam Service Problems for a Smooth Windows 11 Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-control-for-apps-and-browsers/"><u>Unveiling Windows Control for Apps & Browsers</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-affordable-sound-mastery-the-best-free-audio-editor-applications-for-windows-and-macos-users-today-for-2024/"><u>Updated Affordable Sound Mastery The Best Free Audio Editor Applications for Windows & macOS Users Today for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-picking-a-software-dependency-provider/"><u>The Ultimate Guide to Picking a Software Dependency Provider</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-steam-friendship-disconnect-on-pcs/"><u>Steps to Resolve Steam Friendship Disconnect on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-registry-shortcomings-solutions/"><u>Unveiling Windows Registry Shortcomings: Solutions</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-a-closer-look-at-stale-vr-landscapes-what-changes/"><u>[Updated] A Closer Look at Stale VR Landscapes  What Changes?</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-in-2024-masterpiece-episodes-for-airwaves/"><u>[New] In 2024, Masterpiece Episodes for Airwaves</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-deal-with-the-samsung-galaxy-f15-5g-screen-black-but-still-works-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Deal With the Samsung Galaxy F15 5G Screen Black But Still Works? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-how-to-give-a-makeover-to-existing-images-and-videos-with-ig-filters/"><u>[New] How to Give a Makeover to Existing Images and Videos with IG Filters</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-task-execution-windows-keyboard-tips-and-tricks/"><u>Speedy Task Execution: Windows Keyboard Tips & Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-to-prevent-not-working-on-your-pc/"><u>Swift Solutions to Prevent 'Not Working' On Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-absence-of-thumbnail-images-on-windows-11-screens/"><u>Troubleshooting Absence of Thumbnail Images on Windows 11 Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-power-settings-for-cpu-state-insights/"><u>Unlocking Power Settings for CPU State Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/7-tricks-for-rejuvenating-non-responsive-windows-service-explorer/"><u>7 Tricks for Rejuvenating Non-Responsive Windows Service Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-full-potential-mastering-multiple-screens-in-win11/"><u>Unlock Full Potential: Mastering Multiple Screens in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/why-is-nvidia-control-panel-inaccessible-on-win11/"><u>Why Is Nvidia Control Panel Inaccessible on Win11?</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-optimize-your-reach-the-best-video-aspect-ratios-for-linkedin/"><u>Updated In 2024, Optimize Your Reach The Best Video Aspect Ratios for LinkedIn</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-role-of-gaming-in-e-commerce-for-2024/"><u>The Role of Gaming in E-Commerce for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/reestablishing-clear-audio-conversations-on-valorant-pc/"><u>Reestablishing Clear Audio Conversations on Valorant PC</u></a></li>
<li><a href="https://windows11.techidaily.com/tracing-untapped-functions-within-windows-system-health-tools/"><u>Tracing Untapped Functions Within Windows' System Health Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-overcome-endless-startup-in-bios-for-windows-systems/"><u>Steps to Overcome Endless Startup in BIOS for Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/tracking-windows-logins-identifying-successes-and-failures/"><u>Tracking Windows Logins: Identifying Successes & Failures</u></a></li>
</ul></div>
