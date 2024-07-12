---
title: Guide to Subduing File Explorer's Default Views
date: 2024-07-11T21:48:50.391Z
updated: 2024-07-12T21:48:50.391Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Subduing File Explorer's Default Views
excerpt: This Article Describes Guide to Subduing File Explorer's Default Views
keywords: Subdue Explore Views Guide,Taming File Viewer Display,Mastery in File Explorer Normals,Halt Default File Explorer View,Conquering Default Options,Suppress Explorer Window Views,Override Explorers Initial Screens
thumbnail: https://thmb.techidaily.com/6c8487e0b404251fb12aeaebde28154ddd618ecb4b5d51b0cd4522eee48c4e1f.jpg
---

## Guide to Subduing File Explorer's Default Views

 Microsoft was hoping to launch the tabs feature in the File Explorer app for Windows 10\. But it scrapped the idea later on. However, with the Windows 11 22H2 update, users can now try out the tabs feature in File Explorer. The participants of the Windows Insider Program got early access to the feature and Microsoft could soon apply the tabs idea to Windows Notepad as well.

 But what if you want to turn the File Explorer Tabs feature off? An immediate idea would be to uninstall the update, but that is a temporary workaround. You can use ViVeTool to enable or disable the tabs feature or any other new feature of Windows 11.

## What Is ViVeTool?

 ViVeTool is an open-source command line tool that can enable or disable Windows operating system features. Microsoft continuously works on many experimental features and does a lot of testing before rolling out a stable version of a feature. But if you are impatient, you can use ViVeTool to enable an otherwise hidden feature. It is free and the developers recently launched a GUI version of the tool as well.

## How to Disable File Explorer Tabs In Windows 11

 You can disable the File Explorer Tabs by either using the ViVeTool or the ViVeTool GUI version. The latter is much simpler to use because you can search for a feature and activate or deactivate it in one click. But before doing that, download and install both of these tools on your system. Also,[create a system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) for added precaution, in case the tool wrecks something on your Windows 11 computer.

**Download:** [ViVeTool](https://github.com/thebookisclosed/ViVe/releases)

**Download:** [ViVeTool GUI](https://github.com/PeterStrick/ViVeTool-GUI/releases)

### 1\. Disable File Explorer Tabs Using the ViVeTool

 Since it is a command line tool, you can access it from a terminal window. Here’s how to do it:

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**CMD** in the text input area and press**Ctrl + Shift + Enter** key to launch the command prompt with administrator privileges.
3. Type**cd Drive Name:\\path** . Here, you need to enter the exact location where you extracted the tool after downloading it. For example, we extracted it to a folder name Vive in C drive. So, our command is**cd C:\\Vive** .
4. Now, you will be in the directory where ViVeTool exists. Type**vivetool** and press the**Enter** key. You will see a bunch of parameters you can use with the tool.  
![Disable File Explorer Tabs Using the ViVeTool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool.jpg)
5. Type the following two commands, one by one in the CMD and press the**Enter** key.  
vivetool /disable /id:37634385  
vivetool /disable /id:36354489
6. You will see the “**Successfully set feature configuration(s)** ” if the command executes successfully.
7. Now,**restart** your system for the changes to take effect. The File Explorer Tabs feature will no longer be active on your system.

### 2\. Disable File Explorer Tabs Using the ViVeTool GUI version

 The GUI version of ViVeTool works similarly. You can manually enter the feature ID or use the search function to find a feature in the list. Repeat the following steps to disable File Explorer Tabs using the ViVeTool GUI.

1. Launch the ViVeTool GUI with admin privileges.
2. Click on the drop-down list and select the latest Windows build number. Wait for the tool to list all the feature IDs available for the Windows build.
3. Type**37634385** in the search bar. Select the highlighted feature and click on the**Perform Action** button.  
![Disable File Explorer Tabs Using the ViVeTool GUI version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool-gui-version.jpg)
4. Select the**Deactivate Feature** option. Similarly, find the feature ID**36354489** and deactivate it.
5. Now, close the ViVeTool GUI and**restart** your system.
6. Open the File Explorer and you won’t see the tabs feature anymore.

## Disable Any Windows 11 Feature Using ViVeTool

 File Explorer tabs are more useful than you think. But if you use another File Explorer program or can make do without it, ViVeTool is a great utility to disable/enable it. Moreover, it is completely free, and you can even enable other experimental features of Windows 11.


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
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-jazz-101-key-elements-you-must-understand/"><u>New 2024 Approved Jazz 101 Key Elements You Must Understand</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-transfer-apps-to-a-new-windows-11-pc/"><u>How to Transfer Apps to a New Windows 11 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/jumpstart-your-system-reviving-windows-11s-error-detection/"><u>Jumpstart Your System: Reviving Windows 11'S Error Detection</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-carryminatis-income-blueprint-journey-through-2023/"><u>[New] CarryMinati's Income Blueprint  Journey Through 2023</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-error-0x80071a90-explained-simply/"><u>Fixing Windows Error 0X80071A90 Explained Simply</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-window-11-ui-elements-larger-icons/"><u>Customizing Window 11 UI Elements - Larger Icons</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/crafting-a-youtube-future-scaling-up-or-staying-independent/"><u>Crafting a YouTube Future  Scaling Up or Staying Independent?</u></a></li>
<li><a href="https://windows11.techidaily.com/confronting-and-overcoming-mmc-snaps-not-found-errors/"><u>Confronting and Overcoming MMC Snaps Not Found Errors</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-premiere-mkv-player-suite-pcmobile/"><u>[New] Premiere MKV Player Suite (PC/Mobile)</u></a></li>
<li><a href="https://windows11.techidaily.com/androidiphone-to-windows-recording-connection-guide/"><u>Android/iPhone to Windows Recording Connection Guide</u></a></li>
<li><a href="https://driver-install.techidaily.com/upgrade-your-pc-with-latest-amd-rx-570-drivers-download-links/"><u>Upgrade Your PC with Latest AMD RX 570 Drivers Download Links</u></a></li>
<li><a href="https://howto.techidaily.com/quick-fixes-for-why-is-my-itel-a60-black-and-white-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Quick Fixes for Why Is My Itel A60 Black and White | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-something-went-wrong-with-outlook-on-pcs/"><u>Decoding Something Went Wrong with Outlook on PCs</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-top-9-free-online-movie-makers-for-2024/"><u>New Top 9 Free Online Movie Makers for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-chromes-black-pixels-issue/"><u>Bypassing Chrome's Black Pixels Issue</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-cashing-in-on-content-the-carminati-effect-ajay-for-2024/"><u>[New] Cashing In on Content  The Carminati Effect (AJay) for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-successfully-upgrade-to-virtualbox-70-on-windows-11-pcs/"><u>How to Successfully Upgrade to VirtualBox 7.0 on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-windows-11-version-22h2-update-not-installing/"><u>How to Fix the Windows 11 Version 22H2 Update Not Installing</u></a></li>
<li><a href="https://windows11.techidaily.com/ace-windows-with-key-based-configuration-tweaks/"><u>Ace Windows with Key-Based Configuration Tweaks</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-depth-look-at-vsdc-plus-top-competitors/"><u>In-Depth Look at VSDC, Plus Top Competitors</u></a></li>
<li><a href="https://windows11.techidaily.com/invisible-to-others-windows-network-concealment/"><u>Invisible to Others: Windows Network Concealment</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/the-complete-guide-to-vivo-y100i-power-5g-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>The Complete Guide to Vivo Y100i Power 5G FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reestablish-connectivity-for-print-devices-on-pcs/"><u>How to Reestablish Connectivity for Print Devices on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-intellij-unison-not-working-a-guide-for-users-of-windows-11/"><u>Fixing IntelliJ Unison Not Working: A Guide for Users of Windows 11</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-essential-photo-edits-guide-for-the-novice-photographer/"><u>[New] In 2024, Essential Photo Edits Guide for the Novice Photographer</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-stellar-visuals-enhancing-google-meet-collaboration/"><u>[New] Stellar Visuals  Enhancing Google Meet Collaboration</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-master-the-use-of-winservicesexe-on-windows/"><u>How to Master the Use of Winservices.exe on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-productivity-on-windows-by-adjusting-with-alomware/"><u>Boost Productivity on Windows by Adjusting with AlomWare</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-top-ranked-noise-reducer-app-boost-visual-impact-in-your-clips-for-2024/"><u>New Top-Ranked Noise Reducer App Boost Visual Impact in Your Clips for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/automating-network-drives-on-win11/"><u>Automating Network Drives on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-turn-off-desktop-input-on-your-win-device/"><u>How to Turn Off Desktop Input on Your Win Device</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-the-application-encountered-an-unrecoverable-error-in-roblox-on-windows/"><u>How to Fix the “The Application Encountered an Unrecoverable Error in Roblox on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-windows-discord-speed-a-step-by-step-guide/"><u>Boosting Windows Discord Speed: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-deadly-c0000022-breakdown-in-windows-10/"><u>Fixing the Deadly C0000022 Breakdown in Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/enforcing-originality-windows-screensaver-non-alterability/"><u>Enforcing Originality: Windows Screensaver Non-Alterability</u></a></li>
<li><a href="https://windows11.techidaily.com/epic-backup-strategies-to-avoid-loss/"><u>Epic Backup Strategies to Avoid Loss</u></a></li>
<li><a href="https://windows11.techidaily.com/curbing-the-constant-appearance-of-edge-icons/"><u>Curbing the Constant Appearance of Edge Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-restore-absentee-application-association-windows/"><u>How To Restore Absentee Application Association (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/a-step-by-step-approach-to-fixing-to-do-sync-issues/"><u>A Step-by-Step Approach to Fixing To Do Sync Issues</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-tiktok-voiceover-techniques-guide/"><u>2024 Approved  TikTok Voiceover Techniques Guide</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-engineering-unique-tiktok-outro-animations/"><u>2024 Approved  Engineering Unique TikTok Outro Animations</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-streamline-your-internet-use-with-these-5-chromium-addons-for-vids/"><u>[New] Streamline Your Internet Use With These 5 Chromium Addons for Vids</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-error-0x80300024-on-a-windows-pc/"><u>Addressing Error 0X80300024 on a Windows PC</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-2024-approved-sonic-spectrum-crafting-the-ideal-audio-backdrop-for-different-video-genres/"><u>Updated 2024 Approved Sonic Spectrum Crafting the Ideal Audio Backdrop for Different Video Genres</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/lasting-freedom-how-to-banish-youtube-shorts-permanently/"><u>Lasting Freedom  How To Banish YouTube Shorts Permanently</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-the-sound-of-silence-enhancing-video-quality-with-premiere-pros-easy-audio-filters-for-2024/"><u>Updated The Sound of Silence Enhancing Video Quality with Premiere Pros Easy Audio Filters for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-absence-of-files-alert-in-windows-11/"><u>Addressing Absence of Files Alert in Windows 11</u></a></li>
</ul></div>
