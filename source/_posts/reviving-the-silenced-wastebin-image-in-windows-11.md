---
title: Reviving the Silenced Wastebin Image in Windows 11
date: 2024-08-15T15:53:09.466Z
updated: 2024-08-16T15:53:09.466Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reviving the Silenced Wastebin Image in Windows 11
excerpt: This Article Describes Reviving the Silenced Wastebin Image in Windows 11
keywords: Windows 11 Wastebin Revival,Silenced Bin Image Update,Wastebin Image in Win11,Wastebin Icon Restoration,Win11 Bin Image Resurge,Silenced Bin Update Win11,Reinvigorated Wastebin Icon
thumbnail: https://thmb.techidaily.com/453561a8ca0d834b48f18b90c63e8754b707ad468e25eb7e04a5333cdbe19d66.jpg
---

## Reviving the Silenced Wastebin Image in Windows 11

 The Recycle Bin has been a staple on Windows for a long time, but not everyone wants it on the desktop. You can disable it via the Desktop Icon Settings, but there is a bug where if you try to re-enable it, the "Recycle Bin" option is grayed out and cannot be toggled.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

## 1\. How to Bring Back the Recycle Bin Using the Group Policy Editor

 The Group Policy Editor lets you show or hide the Recycle Bin icon from the desktop. Check if you have modified and accidentally disabled the Recycle Bin group policy recently. If so you can set the Remove Recycle Bin icon from the desktop policy to "Not Configured" which will restore it.

 You may not find the Local Group Policy Editor in Windows Home Edition. However, you can run a batch script to [enable Group Policy Editor on the Windows Home edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) or skip to the Registry Editor-based fix in the next step.

 To restore the Recycle Bin icon using the Group Policy Editor:

1. Press **Win + R** to open **Run**.
2. Type **gpedit.msc** and click **OK** to open the **Group Policy Editor**.  
![gpedit msc windows 11 run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/gpedit-msc-windows-11-run.jpg)
3. Next, navigate to the following location:  
`User Configuration > Administrative Templates > Desktop`
4. In the right pane, locate and double-click on the **Remove Recycle Bin icon from the desktop** option to open its properties.  
![edit remove recycle bin icon from settings gpedit policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-remove-recycle-bin-icon-from-settings-gpedit-policy.jpg)
5. In the **Properties** dialog, select **Not Configured**.  
![edit remove recycle bin icon from settings gpedit policy not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-remove-recycle-bin-icon-from-settings-gpedit-policy-not-configured.jpg)
6. Click **Apply** and **OK** to save the changes.

 Close the Group Policy Editor and check your desktop to see if you can access the Recycle Bin. If not, make sure the Recycle Bin is set to show in Desktop Icon Settings.

 To enable Recycle Bin in Desktop Icon Settings:

1. Press **Win + I** to open **Settings**.
2. Next, open the **Personalization** tab in the left panel.
3. Click on **Themes**.  
![desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/desktop-icon-settings-windows-11.jpg)
4. Click on **Desktop icon settings** under the **Related settings** section.
5. In the **Desktop Icon Settings** dialog, select **Recycle Bin**.  
![enable recycle bin desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/enable-recycle-bin-desktop-icon-settings-windows-11.jpg)
6. Click **Apply** and **OK** to save the changes.

 If you can’t access Group Policy Editor or if the issue persists, you can use the Registry Editor to fix this problem.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Modify the Recycle Bin Registry Settings

 Another way to resolve and restore the grayed-out Recycle Bin icon in the Desktop settings is via the Windows Registry. You can modify the registry entry value responsible for the settings and configurations of Recycle Bin working to restore the functionality.

 Making modifications to the Windows registry involves tweaking settings that may harm your device if performed incorrectly. We recommend you [create a Windows restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [take a Windows registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before attempting to modify the Windows registry.

 To modify the Recycle Bin registry value:

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK**. Click **Yes** if prompted by **User Account Control**.
3. In the Registry Editor, navigate to the following location. You can copy and paste the path in the editor for quicker navigation:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\NonEnum`
4. In the right pane, locate the **{645FF040-5081-101B-9F08-00AA002F954E}** DWORD (32-bit) value.  
![registry editor nonnum new dword value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value.jpg)
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
5. If it does not exist, you’ll need to create a new value. To do this, right-click on the **NonEnum** subkey folder in the left pane and select **New > DWORD (32-bit) Value**.
6. Rename the value as **{645FF040-5081-101B-9F08-00AA002F954E}**.
7. Next, double-click on the new DWORD value to open its properties.  
![registry editor nonnum new dword value edit 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value-edit-0.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
8. Type **0** in the Value data field and click **OK** to save the changes.
9. Close Registry Editor and restart your computer. Sometimes, you’ll need to restart your computer for the new registry modifications to work.

 If the issue persists, try to [create a new user account with administrative rights](https://www.makeuseof.com/windows-11-create-local-user-account/), [perform a system restore](https://www.makeuseof.com/use-system-restore-windows/), or [repair corrupted Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get Access to the Recycle Bin Desktop Icon Setting Again

 An incorrectly modified group policy can gray out the Recycle Bin icon in the Desktop Icon Settings dialog. Fortunately, it's an easy fix, and you should now have your Recycle Bin back to how you like it.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-files.techidaily.com/new-2024-approved-bridging-minds-online-the-ultimate-guide-to-facebook-video-screensharing/"><u>[New] 2024 Approved  Bridging Minds Online  The Ultimate Guide to Facebook Video Screensharing</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-adding-panoramic-movement-a-camtasa-guide-to-ken-burns/"><u>[New] Adding Panoramic Movement  A Camtasa Guide to Ken Burns</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ow-to-validate-your-youtube-profile-a-simple-guide-for-2024/"><u>[New] How to Validate Your YouTube Profile? A Simple Guide for 2024</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-in-2024-addressing-hearing-gaps-in-video-content-sharing/"><u>[New] In 2024, Addressing Hearing Gaps in Video Content Sharing</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-tips-for-smooth-and-efficient-photo-background-blurring/"><u>[New] Tips for Smooth and Efficient Photo Background Blurring</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-twitter-video-downloader-how-to-download-twitter-videos-to-iphone/"><u>[Updated] 2024 Approved  Twitter Video Downloader  How to Download Twitter Videos to iPhone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-capturing-quality-video-on-macbook/"><u>[Updated] Capturing Quality Video on MacBook</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-dominating-the-digital-space-with-trending-content-for-2024/"><u>[Updated] Dominating the Digital Space with Trending Content for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-essential-handbook-windows-pc-for-capturing-live-tv/"><u>[Updated] Essential Handbook  Windows PC for Capturing Live TV</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-ideal-web-microphone-solutions-for-2024/"><u>[Updated] Ideal Web Microphone Solutions for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-premier-10plus-free-video-intro-creators/"><u>[Updated] In 2024, Premier 10+ Free Video Intro Creators</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-ultimate-guide-to-toolwiz-photosapp-for-photographers/"><u>2024 Approved  The Ultimate Guide to Toolwiz PhotosApp for Photographers</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprerant-users-resourceful-approach-to-processes-and-themes-in-windows-11/"><u>A Compreran't User's Resourceful Approach to Processes and Themes in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-the-mold-unleashing-dormant-windows-11-powers/"><u>Breaking the Mold: Unleashing Dormant Windows 11 Powers</u></a></li>
<li><a href="https://windows11.techidaily.com/creative-walls-for-your-pc-windows-1011-guide/"><u>Creative Walls for Your PC: Windows 10/11 Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/device-dialogue-diplomacy-android-plus-pc-sync-guide/"><u>Device Dialogue Diplomacy: Android + PC Sync Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-email-management-gmail-in-outlook-windows-edition/"><u>Effortless Email Management: Gmail in Outlook, Windows Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-ride-on-windows-discover-top-5-budget-enhancers/"><u>Elevate Your Ride on Windows: Discover Top 5 Budget Enhancers</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-output-amplitude-for-external-windows-11-audio/"><u>Elevating Output Amplitude for External Windows 11 Audio</u></a></li>
<li><a href="https://windows11.techidaily.com/end-the-ebb-and-flow-top-strategies-for-smooth-windows-streaming/"><u>End the Ebb and Flow: Top Strategies for Smooth Windows Streaming</u></a></li>
<li><a href="https://windows11.techidaily.com/erase-your-black-screen-and-clear-cursor-issues-in-win11/"><u>Erase Your Black Screen & Clear Cursor Issues in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-how-to-erase-past-safety-checks-on-windows/"><u>Expert Tips: How to Erase Past Safety Checks on Windows</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/exploring-varieties-in-gesture-tech-for-2024/"><u>Exploring Varieties in Gesture Tech for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/four-essential-enhancements-needed-for-an-optimized-chatgpt-plugins-marketplace/"><u>Four Essential Enhancements Needed for an Optimized ChatGPT Plugins Marketplace</u></a></li>
<li><a href="https://windows11.techidaily.com/gpresult-command-guide-for-policy-reporting/"><u>GPResult Command Guide for Policy Reporting</u></a></li>
<li><a href="https://windows11.techidaily.com/harmonious-hardware-connections-android-pc-junctions/"><u>Harmonious Hardware Connections: Android-PC Junctions</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-batch-convert-heic-images-to-jpeg-format-in-windows-10-and-11/"><u>How to Batch Convert HEIC Images to JPEG Format in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-nvidia-control-panel-not-opening-in-windows-11/"><u>How to Fix the NVIDIA Control Panel Not Opening in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-install-hyper-v-on-windows-11-home/"><u>How to Install Hyper-V on Windows 11 Home</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-samsung-galaxy-a54-5g-pin-codepattern-lockpassword-by-drfone-android/"><u>How to Unlock Samsung Galaxy A54 5G PIN Code/Pattern Lock/Password</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-8-best-apps-for-screen-mirroring-xiaomi-redmi-k70-pc-drfone-by-drfone-android/"><u>In 2024, 8 Best Apps for Screen Mirroring Xiaomi Redmi K70 PC | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-a-working-guide-for-pachirisu-pokemon-go-map-on-samsung-galaxy-a05s-drfone-by-drfone-virtual-android/"><u>In 2024, A Working Guide For Pachirisu Pokemon Go Map On Samsung Galaxy A05s | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fixing-foneazy-mockgo-not-working-on-nokia-c12-drfone-by-drfone-virtual-android/"><u>In 2024, Fixing Foneazy MockGo Not Working On Nokia C12 | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-getting-the-pokemon-go-gps-signal-not-found-11-error-in-infinix-note-30-pro-drfone-by-drfone-virtual/"><u>In 2024, Getting the Pokemon Go GPS Signal Not Found 11 Error in Infinix Note 30 Pro | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-sharefake-gps-on-uber-for-vivo-g2-drfone-by-drfone-virtual-android/"><u>In 2024, How to share/fake gps on Uber for Vivo G2 | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-navigating-average-incomes-in-the-podcasting-industry/"><u>In 2024, Navigating Average Incomes in the Podcasting Industry</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-overview-of-the-best-infinix-smart-7-hd-screen-mirroring-app-drfone-by-drfone-android/"><u>In 2024, Overview of the Best Infinix Smart 7 HD Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-passfab-apple-iphone-8-backup-unlocker-top-4-alternatives-drfone-by-drfone-ios/"><u>In 2024, PassFab Apple iPhone 8 Backup Unlocker Top 4 Alternatives | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-tips-and-tricks-for-setting-up-your-infinix-note-30-5g-phone-pattern-lock-by-drfone-android/"><u>In 2024, Tips and Tricks for Setting Up your Infinix Note 30 5G Phone Pattern Lock</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/launch-your-zoom-meeting-in-a-flash-on-your-android-smartphonetablet-for-2024/"><u>Launch Your Zoom Meeting in a Flash on Your Android Smartphone/Tablet for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-the-gap-enabling-smooth-steam-connection/"><u>Mending the Gap: Enabling Smooth Steam Connection</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-security-entry-error/"><u>Navigating Through Windows 'Security Entry Error'</u></a></li>
<li><a href="https://windows11.techidaily.com/no-more-erratic-arrows-fixes-for-the-frustrated/"><u>No More Erratic Arrows: Fixes for the Frustrated</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-camera-app-malfunctions-windows-0xa00f429f-error/"><u>Overcoming Camera App Malfunctions: Windows' 0XA00F429F Error</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-11-zoom-malfunction-1132/"><u>Overcoming Windows 11 Zoom Malfunction #1132</u></a></li>
<li><a href="https://windows11.techidaily.com/quelling-overzealousness-after-a-peak-life-period-on-windows/"><u>Quelling Overzealousness After a Peak Life Period on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-pc-performance-hurdles-with-intel-graphics-updates/"><u>Remedying PC Performance Hurdles with Intel Graphics Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-system-crash-code-0xc0000001/"><u>Remedying System Crash Code 0xC0000001</u></a></li>
<li><a href="https://windows11.techidaily.com/revive-lost-control-secrets-for-steam-in-windows/"><u>Revive Lost Control: Secrets for Steam in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-storing-error-during-new-app-installation/"><u>Solutions for Storing Error During New App Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-stopping-auto-recommended-game-suggestion/"><u>Steps for Stopping Auto-Recommended Game Suggestion</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-separate-bunched-system-icons/"><u>Strategies to Separate Bunched System Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-audacity-paudio-operations-in-windows-os/"><u>Streamlining Audacity PAudio Operations in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-keyboard-magic-custom-shortcuts-w11-style/"><u>Tailored Keyboard Magic: Custom Shortcuts W11 Style</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-unmasking-user-ids-a-guide-to-sids-in-windows-11/"><u>The Art of Unmasking User IDs: A Guide to SIDs in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-comprehensive-manual-for-component-settings-in-w11/"><u>The Comprehensive Manual for Component Settings in W11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-comprehensive-method-of-setting-up-a-triple-monitor-configuration-on-any-computer/"><u>The Comprehensive Method of Setting Up a Triple Monitor Configuration on Any Computer</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/the-ultimate-blueprint-for-capturing-streaming-audio-online-for-2024/"><u>The Ultimate Blueprint for Capturing Streaming Audio Online for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-nokia-105-classic-drfone-by-drfone-virtual-android/"><u>Thinking About Changing Your Netflix Region Without a VPN On Nokia 105 Classic? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/timeless-upgrades-essential-time-saver-tools-for-pcs/"><u>Timeless Upgrades: Essential Time Saver Tools for PCs</u></a></li>
<li><a href="https://techtrends.techidaily.com/transition-from-gmail-with-ease-find-your-perfect-match-among-these-8-services/"><u>Transition From Gmail with Ease: Find Your Perfect Match Among These 8 Services</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-your-windows-11-pc-into-a-self-contained-internet-station/"><u>Turn Your Windows 11 PC Into a Self-Contained Internet Station</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/ultimate-guide-igniting-video-visionaries-in-your-channel-for-2024/"><u>Ultimate Guide  Igniting Video Visionaries in Your Channel for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/ultimate-vivacut-edit-pro-comprehensive-review-and-tutorial-2024/"><u>Ultimate VivaCut Edit Pro  Comprehensive Review & Tutorial 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-ftdibussys-the-impact-on-windows-memory-standards-and-safety/"><u>Unraveling ftdibus.sys: The Impact on Windows' Memory Standards and Safety</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-of-a-smoother-click-lock-in-windows/"><u>Unveiling the Secrets of a Smoother Click Lock in Windows</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-in-2024-what-is-ai-voice-text-to-speech-wondershare-virbo-glossary/"><u>Updated In 2024, What Is AI Voice Text to Speech? | Wondershare Virbo Glossary</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-10-post-fall-update-dark-screens-solved/"><u>Windows 10: Post-Fall Update, Dark Screens - Solved</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-layers-impact-on-linux-dominance/"><u>Windows Layer's Impact on Linux Dominance</u></a></li>
</ul></div>
