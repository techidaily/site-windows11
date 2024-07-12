---
title: "Shaping Windows 11: Square It Off"
date: 2024-07-11T21:34:23.089Z
updated: 2024-07-12T21:34:23.089Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Shaping Windows 11: Square It Off"
excerpt: "This Article Describes Shaping Windows 11: Square It Off"
keywords: Win11Upgrade,UpgradeWindows,NewOSFeatures,SquarifyWin,ModernUIWindows,WindowsSquareLayout,NewWindowsDesign
thumbnail: https://thmb.techidaily.com/212e21d96bc4724d21a24c1110e599b63bc2c397e891bb1e1f9fc06be1f08b00.jpg
---

## Shaping Windows 11: Square It Off

 With Windows 11, Microsoft brought several visual changes to its desktop operating system, including the notable addition of rounded corners for windows, menus, and dialog boxes. While the new design update has been widely embraced by many users, there are those who prefer a more traditional look with sharp corners.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

## 1\. How to Disable Rounded Corners in Windows 11 Using a Third-Party Tool

**Win11DisableOrRestoreRoundedCorners** is an open-source tool available on GitHub that can help you disable rounded corners on your Windows 11 PC. Since this tool modifies your PC's system files to remove the rounded corners, it's a good idea to [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before using it.

1. Head over to GitHub’s website to [download the Win11DisableOrRestoreRoundedCorners tool](https://github.com/valinet/Win11DisableRoundedCorners/releases).
2. Double-click the downloaded executable file to run it.
3. If you see the Microsoft Defender SmartScreen window, click on **More info** and then select **Run anyway**.
4. Select **Yes** when the User Account Control (UAC) prompt appears.  
![Microsoft Defender SmartScreen Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/microsoft-defender-smartscreen-window.jpg)

 Once you complete the above steps, a PowerShell window should appear and disable rounded corners on your PC. Here’s a glimpse of how your windows will look once the rounded corners are disabled.

![Square Corners in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/square-corners-in-windows-11.jpg)

 Note that this tool will not disable rounded corners in the Start menu or some modern apps. If you want to revert the changes later, simply run the downloaded EXE file again.

## 2\. How to Disable Rounded Corners in Windows 11 Using the Registry Editor

 Don't want to use a third-party tool? No problem. You can also disable rounded corners in Windows 11 by making changes to the Windows Registry. However, it's crucial to exercise caution, as modifying registry files without proper knowledge can be risky.

 Before you proceed, consider [backing up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/), just in case. After that, use these steps to disable rounded corners via the Registry Editor:

1. Press **Win + S** to open the search menu.
2. Type in **registry editor** and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Navigate to **Computer > HKEY\_CURRENT\_USER > Software > Microsoft > Windows > DWM**.
5. Right-click on the **DWM** key and select **New > DWORD (32-bit) Value**. Rename it to **UseWindowFrameStagingBuffer**.
6. Double-click the newly created DWORD and enter **0** in the **Value data** field. Then, click **OK**.
7. [Restart your PC](https://www.makeuseof.com/windows-restart-methods/) to apply the changes.  
![Disable Rounded Corners in Windows 11 via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-rounded-corners-in-windows-11-via-registry-editor.jpg)

 If you want to reverse the above change later, repeat the same steps mentioned earlier and change the value data for the **UseWindowFrameStagingBuffer** to **1**.

## 3\. How to Disable Rounded Corners in Windows 11 via Device Manager

 Another way to remove rounded corners in Windows 11 is by disabling the graphics driver on your PC. However, it is important to consider a few caveats. Firstly, disabling the graphics driver will result in reduced display performance, lower screen resolutions, and the deactivation of any visual effects. Secondly, this will also prevent you from running any graphics-intensive applications or games on your PC.

 If you are fine with these trade-offs, use these steps to disable rounded corners via Device Manager.

1. Press **Win + X** to open the Power User menu.
2. Select **Device Manager** from the list.
3. Double-click on **Display adapters** to expand it.
4. Right-click on your display driver and select **Disable device**.  
![Disable Graphics Driver on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-graphics-driver-on-windows-11.jpg)

 Once the graphics driver is disabled, you should see square corners on all windows and menus in Windows 11\. If you want to undo this change later, simply enable the graphics driver via Device Manager.

## Disabling Rounded Corners in Windows 11 Is Easy

 Using a third-party tool is arguably the most convenient way to remove rounded corners in Windows 11\. However, if you prefer to rely on the native methods, you can use the Registry Editor or Device Manager instead.

 Disabling rounded corners isn’t the only way to get the classic look of previous Windows versions. You can also use a third-party tool like the ExplorerPatcher to make Windows 11 look like Windows 10\.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://tiktok-videos.techidaily.com/new-the-cutting-edge-trendsetters-on-tiktok-for-2024/"><u>[New] The Cutting-Edge Trendsetters on TikTok for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-tricks-to-pinpoint-your-graphic-card-on-windows-11/"><u>Quick Tricks to Pinpoint Your Graphic Card on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/improve-file-selection-techniques-activating-windows-11-boxes/"><u>Improve File Selection Techniques: Activating Windows 11 Boxes</u></a></li>
<li><a href="https://windows11.techidaily.com/reinvigorate-windows-search-top-11-remedies-explored/"><u>Reinvigorate Windows Search: Top 11 Remedies Explored</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-access-to-greyed-out-pin-unlock-option/"><u>Restoring Access to Greyed-Out Pin Unlock Option</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-nuances-of-widget-alerts-in-windows/"><u>Navigating the Nuances of Widget Alerts in Windows</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-step-by-step-tiktok-usage-for-mac-and-pc-users/"><u>[Updated] 2024 Approved  Step-by-Step TikTok Usage for Mac and PC Users</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-xc0f1103f-flaw-with-nvidias-windows-software/"><u>Overcoming XC0F1103F Flaw with Nvidia's Windows Software</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-remove-the-show-more-options-entry-from-the-context-menu-on-windows-11/"><u>How to Remove the Show More Options Entry From the Context Menu on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11-multi-display-setup/"><u>Navigating Windows 11 Multi-Display Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reinvigorate-the-essential-wsreset-process/"><u>How to Reinvigorate the Essential WSReset Process</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-enhancing-gaming-the-ultimate-xbox-screen-recorders-guide/"><u>In 2024, Enhancing Gaming  The Ultimate Xbox Screen Recorder's Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-words-silent-mode-fix-for-pc-users/"><u>Microsoft Word's Silent Mode Fix for PC Users</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-dual-device-names-on-your-windows-network/"><u>Preventing Dual Device Names on Your Windows Network</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/expert-advice-capturing-and-storing-twitter-vids-on-phones/"><u>Expert Advice  Capturing and Storing Twitter Vids on Phones</u></a></li>
<li><a href="https://windows11.techidaily.com/reinitializing-your-steam-gaming-milestones/"><u>Reinitializing Your Steam Gaming Milestones</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/the-ultimate-guide-to-youtube-thumbnails-size-design-and-success-for-2024/"><u>The Ultimate Guide to YouTube Thumbnails Size, Design, and Success for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/power-preservation-pitfalls-the-reality-of-modern-standby/"><u>Power Preservation Pitfalls: The Reality of Modern Standby</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/get-stuck-in-a-loop-10-free-online-video-looping-tools-you-need/"><u>Get Stuck in a Loop 10 Free Online Video Looping Tools You Need</u></a></li>
<li><a href="https://windows11.techidaily.com/security-enhancement-manual-add-a-self-designed-lock-pattern/"><u>Security Enhancement Manual: Add a Self-Designed Lock Pattern</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-action-to-freeze-damaged-windows-pins/"><u>Immediate Action to Freeze-Damaged Windows PINs</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-the-absence-of-dxgidll-in-new-os-windows-11/"><u>Mending the Absence of Dxgi.dll in New OS, Windows 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/identify-some-outdated-your-hardware-drivers-with-windows-device-manager-on-windows-7-by-drivereasy-guide/"><u>Identify some outdated your hardware drivers with Windows Device Manager on Windows 7</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-essential-history-series-youtube-recommendations-for-learners-for-2024/"><u>[Updated] Essential History Series  YouTube Recommendations for Learners for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11s-network-failure-0x800704b3/"><u>Navigating Windows 11'S Network Failure 0X800704B3</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-ranked-the-best-5-iphones-for-effortless-podcast-access/"><u>[Updated] Ranked  The Best 5 iPhones for Effortless Podcast Access</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/2024-approved-the-future-of-audio-fabrication-creating-convincing-ai-voices-through-advanced-techniques/"><u>2024 Approved The Future of Audio Fabrication Creating Convincing AI Voices Through Advanced Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/harness-window-11-a-productivity-playbook/"><u>Harness Window 11: A Productivity Playbook</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-the-already-in-use-local-device-name-mistake-on-pcs/"><u>Remedy the 'Already in Use' Local Device Name Mistake on PCs</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-comprehensive-analysis-of-bandicam-as-a-recording-tool/"><u>[Updated] 2024 Approved  Comprehensive Analysis of Bandicam as a Recording Tool</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-unrivaled-unity-30plus-creative-biography-approaches-for-increasing-views-and-followers-with-filmora/"><u>[New] In 2024, Unrivaled Unity  30+ Creative Biography Approaches for Increasing Views and Followers with Filmora</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-in-search-for-auditory-perfection-try-these-top-rated-discord-bots/"><u>2024 Approved  In Search for Auditory Perfection? Try These Top-Rated Discord Bots</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-command-control-on-windows-with-sudo/"><u>Maximizing Command Control on Windows with Sudo</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-expert-chosen-speeds-modifying-tools-pc-phone/"><u>[Updated] Expert-Chosen Speeds Modifying Tools (PC, Phone)</u></a></li>
<li><a href="https://windows11.techidaily.com/reducing-powerful-usage-in-modern-host-computers/"><u>Reducing Powerful Usage in Modern Host Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-correct-the-internal-error-on-windows-1111-pro/"><u>Methods to Correct the Internal Error on Windows 11/11 Pro</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/overview-of-the-best-xiaomi-redmi-note-12-pro-4g-screen-mirroring-app-drfone-by-drfone-android/"><u>Overview of the Best Xiaomi Redmi Note 12 Pro 4G Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-icon-positioning-in-windows/"><u>Mastering Icon Positioning in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-missed-files-in-steam-and-windows-11/"><u>Overcoming Missed Files in Steam & Windows 11</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-detect-and-stop-mspy-from-spying-on-your-vivo-x-fold-2-drfone-by-drfone-virtual-android/"><u>How to Detect and Stop mSpy from Spying on Your Vivo X Fold 2 | Dr.fone</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-mac-video-editor-unlock-the-power-of-mkvtoolnix/"><u>New In 2024, Mac Video Editor Unlock the Power of MKVtoolnix</u></a></li>
<li><a href="https://windows11.techidaily.com/reinitializing-distro-and-catroot2-in-w11-a-step-by-step-guide/"><u>Reinitializing Distro & Catroot2 in W11: A Step-by-Step Guide</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-innovative-naming-strategies-elevating-your-filmora-channels-identity/"><u>[New] 2024 Approved  Innovative Naming Strategies  Elevating Your Filmora Channels' Identity</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-apex-chart-analyst-master-video-popularity/"><u>[Updated] Apex Chart Analyst  Master Video Popularity</u></a></li>
</ul></div>
