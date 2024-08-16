---
title: Why Do Computers Have a Windows Batch File?
date: 2024-08-15T16:19:59.379Z
updated: 2024-08-16T16:19:59.379Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Why Do Computers Have a Windows Batch File?
excerpt: This Article Describes Why Do Computers Have a Windows Batch File?
keywords: Batch Files in Computing,Windows System Scripts,Programming Command Files,Computer OS Integration,Operating Systems Tasking,Execution Batch Processes,Software Automation Windows
thumbnail: https://thmb.techidaily.com/a929b0d993c705dcd1293af7219e5e597567df393d17dd26d0130a00b3701a6a.JPG
---

## Why Do Computers Have a Windows Batch File?

 Deleting the hidden "$Windows.\~BT" folder and recovering gigabytes of space on your hard drive is tempting. But what is this cryptically named folder for, and how critical is it to your Windows installation?

## What Is the “$Windows.\~BT” Folder, and Should You Delete It?

 Windows creates the "$Windows.\~BT" folder when you upgrade the operating system to a newer build. This folder contains all the essential files for the upgrade process, like temporary installation files and logs from the previous Windows installation.

 Windows automatically removes the "$Windows.\~BT" folder after 10 days. As manually deleting this folder will [remove old Windows installation files](https://www.makeuseof.com/tag/delete-old-windows-update-files/), you won't be able to roll back to the previous Windows build using the **Go back** option in the Recovery menu within that time (for example, to [downgrade from Windows 11 to Windows 10](https://www.makeuseof.com/windows-11-downgrade-to-windows-10/)). Hence, you should only get rid of this folder if you are satisfied with the current Windows build on your PC. You can also safely delete the massive folder if Windows fails to do it automatically after the grace period.

 But you shouldn't just delete this hidden folder like any other folder on the desktop. Instead, you should turn to the Disk Cleanup tool or the Command Prompt.

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Find and Delete the "$Windows.\~BT" Folder

 As "$Windows.\~BT" is a hidden folder, you need to [configure Windows to show hidden files and folders](https://www.makeuseof.com/windows-11-show-hidden-files-folders/) to find it in File Explorer. Once you do, the **C:\\$Windows.\~BT** directory will become visible.

 You can’t delete the "$Windows.\~BT" folder directly, though. To do so, you need to run the Disk Cleanup tool. Here's how:

1. Press **Win + R** to open the Run dialog box.
2. Type **cleanmgr** in the box and press **Enter**.
3. Use the dropdown menu to select the system drive (usually **C:**) and click **OK**.
4. Click the **Clean up system files** button.
5. Under **Files to delete**, use the checkboxes to select these options: **Previous Windows Installations**, **Windows Update Cleanup**, **Windows upgrade log files**, **Temporary Windows installation files**, and **Temporary files**.
6. Click **OK**.
7. Choose **Delete Files** to confirm.  
![Delete the $Windows.~BT Folder Using the Disk Cleanup Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/delete-the-windows-bt-folder-using-the-disk-cleanup-tool.jpg)
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the "$Windows.\~BT" folder shows up even after you run the Disk Cleanup tool, you'll need to execute a few commands in Command Prompt. For that, [open Command Prompt with administrative rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) and then run the following commands one by one.

`takeown /F C:\$Windows.~BT\* /R /A
icacls C:\$Windows.~BT\*.* /T /grant administrators:F
rmdir /S /Q C:\$Windows.~BT\`

 Once you run the above commands, the "$Windows.\~BT" folder will be deleted for good.

 Now that you understand the purpose of the "$Windows.\~BT" folder, you can decide how to handle it. Beyond the "$Windows.\~BT" folder, you may also come across folders like "Windows.old," "$WinREAgent," "$SysReset," and others which can also be deleted safely using the Disk Cleanup tool.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-techniques.techidaily.com/new-getting-started-with-photography-the-leading-cams/"><u>[New] Getting Started with Photography  The Leading Cams</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-the-artisans-guide-to-podcast-scriptwriting-including-free-samples/"><u>[New] The Artisan's Guide to Podcast Scriptwriting (Including Free Samples)</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-the-future-of-action-cam-unveiled-intova-x/"><u>[New] The Future of Action Cam Unveiled  Intova X</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-top-10-tools-revolutionizing-the-art-of-virtual-performer-sound-design/"><u>[New] Top 10 Tools Revolutionizing the Art of Virtual Performer Sound Design</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-the-ultimate-guide-to-discovering-whatsapp-hacks/"><u>[Updated] 2024 Approved  The Ultimate Guide to Discovering WhatsApp Hacks</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-duplex-monitoring-transcription-for-2024/"><u>[Updated] Duplex Monitoring Transcription for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-unplugged-entertainment-essential-free-apps-for-offline-playing/"><u>[Updated] In 2024, Unplugged Entertainment  Essential Free Apps for Offline Playing</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-pros-guide-to-capturing-every-angle/"><u>[Updated] Pro's Guide to Capturing Every Angle</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-elevate-your-streaming-experience-six-insightful-quizzes-for-fandom-enthusiasts/"><u>2024 Approved  Elevate Your Streaming Experience  Six Insightful Quizzes for Fandom Enthusiasts</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-methods-to-mirror-vivo-y77t-to-roku-drfone-by-drfone-android/"><u>3 Methods to Mirror Vivo Y77t to Roku | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/access-hurdles-rejoin-your-shared-windows-zone/"><u>Access Hurdles: Rejoin Your Shared Windows Zone</u></a></li>
<li><a href="https://windows11.techidaily.com/banishing-0x800704b3-error-from-your-win1011-system/"><u>Banishing 0X800704B3 Error From Your Win10/11 System</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-back-color-to-extend-volume-option-in-diskmgmt/"><u>Bring Back Color to Extend Volume Option in DiskMgmt</u></a></li>
<li><a href="https://extra-tips.techidaily.com/clarifying-video-margins-imovie-crop-explanation-for-2024/"><u>Clarifying Video Margins  IMovie Crop Explanation for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/comprehensive-bg3-gear-checklist-and-more/"><u>Comprehensive BG3 Gear Checklist & More</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-to-managing-comic-files-in-windows-11/"><u>Comprehensive Guide to Managing Comic Files in Windows 11</u></a></li>
<li><a href="https://win-able.techidaily.com/diagnosing-and-repairing-the-problem-when-steelseries-gg-engine-stops-responding-in-windows/"><u>Diagnosing and Repairing the Problem: When SteelSeries GG Engine Stops Responding in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-the-hidden-potential-in-windows-powertoys-10-applications/"><u>Discover the Hidden Potential in Windows PowerToys' 10 Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-combatting-windows-not-found-problem/"><u>Essential Tips: Combatting Windows Not Found Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-how-to-activate-intel-wireless-functionality/"><u>Essential Tips: How to Activate Intel Wireless Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-endure-no-more-teams-login-troubles-in-windows/"><u>How to Endure No More Teams Login Troubles in Windows</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-google-pixel-7a-phone-without-password-by-drfone-android/"><u>How To Unlock Google Pixel 7a Phone Without Password?</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-apple-iphone-8-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, 9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Apple iPhone 8 Plus | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-all-you-need-to-know-about-mega-greninja-for-infinix-smart-8-drfone-by-drfone-virtual-android/"><u>In 2024, All You Need To Know About Mega Greninja For Infinix Smart 8 | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-best-3-software-to-transfer-files-tofrom-your-oppo-a38-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Best 3 Software to Transfer Files to/from Your Oppo A38 via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-infinix-smart-7-hd-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>In 2024, Infinix Smart 7 HD ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-productivity-with-windows-11-calendar/"><u>Maximizing Productivity with Windows 11 Calendar</u></a></li>
<li><a href="https://win-blog.techidaily.com/minecraft-black-screen-malfunction-effective-solutions-and-insights-by-solved/"><u>Minecraft Black Screen Malfunction: Effective Solutions and Insights by [SOLVED]</u></a></li>
<li><a href="https://windows11.techidaily.com/n-series-window-enigma-deciding-factors/"><u>N-Series Window Enigma: Deciding Factors</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-bt-speakers-volume-level-on-windows-11-pcs/"><u>Optimizing BT Speakers Volume Level on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-system-limit-fixing-gpt-windows-problems/"><u>Overcoming System Limit: Fixing GPT Windows Problems</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-pictures-from-vivo-by-fonelab-android-recover-pictures/"><u>Possible solutions to restore deleted pictures from Vivo .</u></a></li>
<li><a href="https://extra-skills.techidaily.com/pro-tips-15-expertly-chosen-tripods-for-gopro-cameras-for-2024/"><u>Pro Tips  15 Expertly Chosen Tripods for GoPro Cameras for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-error-code-0xc00000f-quickly/"><u>Resolving Windows Error Code 0Xc00000f Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-vibrance-to-dull-desktop-windows-effects/"><u>Restoring Vibrance to Dull Desktop Windows Effects</u></a></li>
<li><a href="https://windows11.techidaily.com/rise-above-ethernet-ceiling-overcome-the-windows-100mbps-limit/"><u>Rise Above Ethernet Ceiling: Overcome the Windows 100Mbps Limit</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-synthesis-how-meditation-transforms-cognition-and-emotion/"><u>Seamless Synthesis: How Meditation Transforms Cognition & Emotion</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-into-a-single-source-for-phone-calls-with-unison-w11/"><u>Simplifying Into a Single Source for Phone Calls with Unison W11</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/smooth-steps-top-20-chill-out-country-hits-for-grooving-tiktok/"><u>Smooth Steps  Top 20 Chill-Out Country Hits for Grooving (TikTok)</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-0x80072efd-in-win1110s-microsoft-store/"><u>Solving 0X80072EFD in Win11/10's Microsoft Store</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-amend-non-interactive-menu-bar-on-windows-11/"><u>Steps to Amend Non-Interactive Menu Bar on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-code-4-error-a-compre-cookie-guide/"><u>Tackling the Code 4 Error: A Compre Cookie Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/top-10-uses-for-windows-powertoys-tools/"><u>Top 10 Uses for Windows PowerToys Tools</u></a></li>
<li><a href="https://extra-information.techidaily.com/top-5-android-clippers-essential-image-editing-apps/"><u>Top 5 Android Clippers  Essential Image Editing Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-windows-cars-keyboard-magic-boosts-speed/"><u>Top 5 Windows Cars: Keyboard Magic Boosts Speed</u></a></li>
<li><a href="https://windows11.techidaily.com/transformingnotepadlighttodarkwin/"><u>TransformingNotepadLightToDarkWin</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-power-of-search-implementing-it-in-win11s-task-monitor/"><u>Unlock the Power of Search: Implementing It in Win11's Task Monitor</u></a></li>
<li><a href="https://windows11.techidaily.com/unmasking-profit-making-mechanisms-for-w11-at-microsoft/"><u>Unmasking Profit Making Mechanisms for W11 at Microsoft</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-youtubes-ultimate-playlist-of-irresistible-sounds/"><u>Updated 2024 Approved YouTubes Ultimate Playlist of Irresistible Sounds</u></a></li>
<li><a href="https://facebook.techidaily.com/what-is-a-ghost-in-online-chatting/"><u>What Is a 'Ghost' In Online Chatting?</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-geo-blocking-and-how-to-bypass-it-on-samsung-galaxy-f54-5g-drfone-by-drfone-virtual-android/"><u>What is Geo-Blocking and How to Bypass it On Samsung Galaxy F54 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-times-ticking-off-align-it-back/"><u>Windows Time's Ticking Off? Align It Back!</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>