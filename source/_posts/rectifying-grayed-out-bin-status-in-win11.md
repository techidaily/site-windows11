---
title: Rectifying Grayed Out Bin Status in Win11
date: 2024-07-11T22:01:49.366Z
updated: 2024-07-12T22:01:49.366Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Rectifying Grayed Out Bin Status in Win11
excerpt: This Article Describes Rectifying Grayed Out Bin Status in Win11
keywords: Fix Windows Bin Error,Clear Grayed Bins,Resolve Bin Issues,Enable Bin Access,Unblock Bin Icon,Restart Bin Status,Activate Bin Functions
thumbnail: https://thmb.techidaily.com/08b59308ea1479863a214168a367629cf0b1393331c870e52c284f342d82b8ac.jpeg
---

## Rectifying Grayed Out Bin Status in Win11

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
5. If it does not exist, you’ll need to create a new value. To do this, right-click on the **NonEnum** subkey folder in the left pane and select **New > DWORD (32-bit) Value**.
6. Rename the value as **{645FF040-5081-101B-9F08-00AA002F954E}**.
7. Next, double-click on the new DWORD value to open its properties.  
![registry editor nonnum new dword value edit 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value-edit-0.jpg)
8. Type **0** in the Value data field and click **OK** to save the changes.
9. Close Registry Editor and restart your computer. Sometimes, you’ll need to restart your computer for the new registry modifications to work.

 If the issue persists, try to [create a new user account with administrative rights](https://www.makeuseof.com/windows-11-create-local-user-account/), [perform a system restore](https://www.makeuseof.com/use-system-restore-windows/), or [repair corrupted Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

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
<li><a href="https://facebook-video-footage.techidaily.com/updated-perfecting-the-craft-of-youtube-short-video-making/"><u>[Updated] Perfecting the Craft of YouTube Short Video Making</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essence-of-personalization-through-ai-at-ms-store/"><u>The Essence of Personalization Through AI at MS Store</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-best-poco-m6-5g-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>In 2024, Best Poco M6 5G Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://windows11.techidaily.com/skyrocket-your-text-entry-speed-via-typingaid/"><u>Skyrocket Your Text Entry Speed via TypingAid</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-fb-watch-icon-recovery-tips-and-tricks-for-2024/"><u>[Updated] FB Watch Icon Recovery - Tips and Tricks for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-fixing-0x80071a90-windows-error/"><u>Essential Guide to Fixing 0X80071A90 Windows Error</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-from-ordinary-to-spectacular-making-wow-worthy-tiktok-videos-with-templates/"><u>[New] 2024 Approved  From Ordinary to Spectacular  Making Wow-Worthy TikTok Videos with Templates</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagining-your-pc-integrating-previous-apps-into-win-11/"><u>Reimagining Your PC: Integrating Previous Apps Into Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/top-6-windows-11-prime-fps-monitors-and-trackers/"><u>Top 6 Windows 11: Prime FPS Monitors & Trackers</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-proven-ways-in-how-to-hide-location-on-life360-for-samsung-galaxy-m14-4g-drfone-by-drfone-virtual-android/"><u>In 2024, Proven Ways in How To Hide Location on Life360 For Samsung Galaxy M14 4G | Dr.fone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-increase-your-social-media-impact-hot-tiktok-hashtags-for-growth/"><u>[New] Increase Your Social Media Impact  Hot TikTok Hashtags for Growth</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-debugs-top-windows-troubleshooting-apps/"><u>Deciphering Debugs: Top Windows Troubleshooting Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-for-an-effortless-in-place-windows-11-revamp/"><u>Step-by-Step Guide for an Effortless, In-Place Windows 11 Revamp</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-the-finest-free-car-performance-fixes/"><u>The Ultimate Guide to the Finest Free Car Performance Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-change-from-mkv-to-mp4-format-with-windows-tools/"><u>Easy Change From MKV to MP4 Format with Windows Tools</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-2024-approved-the-uncharted-territory-of-jazz-music-fundamentals/"><u>Updated 2024 Approved The Uncharted Territory of Jazz Music Fundamentals</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-of-registry-edits-in-cmd/"><u>Unveiling the Secrets of Registry Edits in CMD</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-0x80070194-winos-onedrive-fixes/"><u>Tackling the 0X80070194: WinOS OneDrive Fixes</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/accelerate-or-slow-down-on-the-screen-netflix-for-2024/"><u>Accelerate or Slow Down on the Screen (Netflix) for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-uncover-the-full-potential-of-vitas-video-editor-comprehensive-guide-2024/"><u>[New] Uncover the Full Potential of Vita's Video Editor - Comprehensive Guide 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-motorola-moto-g34-5g-drfone-by-drfone-virtual-android/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On Motorola Moto G34 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-black-windows-back-with-simple-steps/"><u>Turn Black Windows Back with Simple Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-9-compelling-arguments-for-pc-dominance-over-macs/"><u>Demystifying: 9 Compelling Arguments for PC Dominance over Macs</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-steam-data-flow-stopping-frustrating-speed-drops/"><u>Enhance Steam Data Flow: Stopping Frustrating Speed Drops</u></a></li>
<li><a href="https://windows11.techidaily.com/sound-revolution-for-your-pc-the-essential-guide-to-audio-drivers-updates/"><u>Sound Revolution for Your PC: The Essential Guide to Audio Drivers Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-windows-11-selection-home-edition-or-pro-level-choice/"><u>Tailored Windows 11 Selection: Home Edition or Pro-Level Choice</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-chrome-the-ultimate-guide-for-self-launched-tab-control/"><u>Stop Chrome: The Ultimate Guide for Self-Launched Tab Control</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-missing-initialization-message-on-windows-pc/"><u>Fixing 'Missing Initialization' Message on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-battlenet-speed-a-win-pc-strategy-guide/"><u>Boosting Battle.net Speed: A Win-PC Strategy Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-the-reparse-point-buffer-tag-error-with-onedrive/"><u>Remedying the Reparse Point Buffer Tag Error with OneDrive</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-how-to-stream-your-snapchat-moments-flawlessly/"><u>In 2024, How to Stream Your Snapchat Moments Flawlessly</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-resetting-rituals-the-ultimate-8/"><u>Windows Resetting Rituals: The Ultimate 8</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-dism-error-code-0x800f082f-on-windows-systems/"><u>Resolving DISM Error Code: 0X800F082F on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-pc-safety-introducing-your-unique-window-pin-design/"><u>Elevate PC Safety: Introducing Your Unique Window Pin Design</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/the-perfect-blueprint-for-iphones-as-portable-recorders-for-2024/"><u>The Perfect Blueprint for iPhones as Portable Recorders for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-deadly-windows-1011-error-0x8007045d/"><u>Bypassing Deadly Windows 10/11 Error 0X8007045D</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-methods-to-change-gps-location-on-samsung-galaxy-m14-4g-drfone-by-drfone-virtual-android/"><u>In 2024, Methods to Change GPS Location On Samsung Galaxy M14 4G | Dr.fone</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-master-quickfix-for-podcast-broadcasts/"><u>[New] 2024 Approved  Master Quickfix for Podcast Broadcasts</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-around-scheduler-setbacks-with-ease/"><u>Turn Around Scheduler Setbacks with Ease</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-top-10-ultra-hd-capture-tools-for-screen-recording/"><u>2024 Approved  Top 10 Ultra-HD Capture Tools for Screen Recording</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/full-guide-on-mirroring-your-samsung-galaxy-m14-5g-to-your-pcmac-drfone-by-drfone-android/"><u>Full Guide on Mirroring Your Samsung Galaxy M14 5G to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-maximizing-your-earnings-how-to-monetize-facebook-videos-successfully/"><u>[Updated] In 2024, Maximizing Your Earnings  How to Monetize Facebook Videos Successfully</u></a></li>
<li><a href="https://windows11.techidaily.com/top-solutions-for-windows-pin-access-issues-10plus11/"><u>Top Solutions for Windows PIN Access Issues (10+11)</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/the-silencers-guide-banishing-background-buzz-for-2024/"><u>The Silencer's Guide  Banishing Background Buzz for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-to-fix-error-code-0xc0000001-on-windows-pcs/"><u>Easy Steps To Fix Error Code 0XC0000001 on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-resolving-installation-issues-with-microsoft-store-apps/"><u>Steps for Resolving Installation Issues with Microsoft Store Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-11-entry-into-the-insider-trials/"><u>Unveiling Windows 11: Entry Into the Insider Trials</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/audio-aficionados-quandary-pick-between-podcast-and-youtube-for-2024/"><u>Audio Aficionados' Quandary  Pick Between Podcast and YouTube for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-office-activation-woes/"><u>Unlocking Windows Office Activation Woes</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-non-starting-windows-speech-to-text-feature/"><u>Fixing Non-Starting Windows Speech to Text Feature</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-expert-advice-where-to-download-high-quality-background-music/"><u>[New] Expert Advice  Where to Download High-Quality Background Music</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-sign-out-of-apple-id-from-apple-iphone-xs-max-without-password-by-drfone-ios/"><u>How to Sign Out of Apple ID From Apple iPhone XS Max without Password?</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-vivo-y02t-phone-with-broken-screen-by-drfone-android/"><u>How to Unlock Vivo Y02T Phone with Broken Screen</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-digital-chronicles-cutting-edge-methods-for-saving-your-vr-gaming-journey/"><u>[New] 2024 Approved  Digital Chronicles  Cutting-Edge Methods for Saving Your VR Gaming Journey</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-pinpointing-device-serial-numbers-on-windows/"><u>The Ultimate Guide to Pinpointing Device Serial Numbers on Windows</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-free-and-easy-the-best-online-tone-generator-sites/"><u>Updated In 2024, Free and Easy The Best Online Tone Generator Sites</u></a></li>
<li><a href="https://fix-guide.techidaily.com/quick-fixes-for-why-is-my-itel-a60s-black-and-white-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Quick Fixes for Why Is My Itel A60s Black and White | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-media-maker-error-x8007043c-fix-guide/"><u>Windows' Media Maker Error X.8007043C Fix Guide</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-fix-locked-apple-id-on-iphone-13-pro-max-by-drfone-ios/"><u>In 2024, How to Fix Locked Apple ID on iPhone 13 Pro Max</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-versatile-pc-software-beyond-inshot/"><u>[Updated] Versatile PC Software Beyond Inshot</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-optimal-viewing-times-on-instagram-videos/"><u>[New] In 2024, Optimal Viewing Times on Instagram Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/deactivating-file-read-only-mode-in-windows/"><u>Deactivating File Read-Only Mode in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-overlapping-security-measures-stick-to-one-windows-antivirus/"><u>Avoid Overlapping Security Measures: Stick to One Windows Antivirus</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-to-become-a-win-11-insider/"><u>Step-by-Step to Become a Win 11 Insider</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-timing-and-frequency-their-effect-on-youtube-rankings/"><u>In 2024, Timing & Frequency  Their Effect on YouTube Rankings</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-loadlibrary-error-87-misconfiguration/"><u>Eliminate LoadLibrary Error 87 Misconfiguration</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-exploring-hidden-gems-secrets-on-locating-superb-insta-ringtunes-and-creating-noteworthy-chimes/"><u>2024 Approved  Exploring Hidden Gems  Secrets on Locating Superb Insta-Ringtunes & Creating Noteworthy Chimes</u></a></li>
<li><a href="https://windows11.techidaily.com/crafted-alerts-full-charge-on-your-win-pclaptop/"><u>Crafted Alerts: Full Charge on Your WIN PC/Laptop</u></a></li>
</ul></div>
