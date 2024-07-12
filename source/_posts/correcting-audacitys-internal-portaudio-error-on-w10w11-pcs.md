---
title: Correcting Audacity's Internal PortAudio Error on W10/W11 PCs
date: 2024-07-11T22:27:56.451Z
updated: 2024-07-12T22:27:56.451Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting Audacity's Internal PortAudio Error on W10/W11 PCs
excerpt: This Article Describes Correcting Audacity's Internal PortAudio Error on W10/W11 PCs
keywords: AudioErrorWin10,Win10PortAudioFix,AudiRecAudacityWin11,AudacityWindowsInternalError,PortAudioCorrectionW10,FixAudacityOnWin11,CorrectingAudacityWin11Err
thumbnail: https://thmb.techidaily.com/7fed1c054c54c404a50983c16bd1d7d403eb3f6cb3fe1e73cdb94850018ef126.jpg
---

## Correcting Audacity's Internal PortAudio Error on W10/W11 PCs

 Audacity is great music editing and recording software when it works. However, some users can’t utilize Audacity because of an Internal PortAudio error that occurs when they launch the software. Instead of launching, Audacity throws up this message: “Could not find any audio devices… Internal PortAudio error.”

 Although the Audacity window opens, users can’t play or record anything with that software when the Internal PortAudio error occurs. Does the same thing happen when you run Audacity? If it does, this is how you can fix the Internal PortAudio error in Windows 11 and 10.

## 1\. Run the Playing Audio Troubleshooter

 Windows has a "Playing Audio" troubleshooter to help users resolve audio playback issues. As the Internal PortAudio error breaks sound playback in Audacity, that troubleshooter could be useful for fixing this issue. You can access the Playing Audio troubleshooter in Windows 10 and 11 via the Control Panel like this:

1. Click a search box or magnifying glass icon on the Windows 11/10 taskbar.
2. Then type in**Control Panel** within the search utility.
3. Select**Control Panel** to open that app’s window.
4. If Control Panel opens in its category view, click**Large icons** on the**View by** menu.
5. Select**Troubleshooting** to access that applet.  
![The Control Panel applets window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-control-panel-items.jpg)

1. Next, select the**View all** navigation link on the left of the Control Panel window.  
![The Troubleshooting applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-troubleshooting-applet.jpg)
2. Click Playing Audio to launch that troubleshooter.  
![The troubleshooting list](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-troubleshooting-list.jpg)
3. Select the troubleshooter’s**Next** option to continue.
4. Then select one of the sound output device options to troubleshoot and click**Next** .
5. Apply the resolutions suggested within the Playing Audio troubleshooter.

## 2\. Enable the Windows Audio and Endpoint Builder Services

 Many Audacity users have confirmed enabling and running disabled Windows Audio and Endpoint Builder services can fix the Internal PortAudio error. So, this troubleshooting method will likely work if one of those services is disabled on your PC. This is how you can check and enable those services in Windows 11/10:

1. First, bring up the Windows search box and search for Services. You can also use one of the other [ways to open Services on Windows](https://www.makeuseof.com/windows-11-open-services-app/) .
2. Next, double-click**Windows Audio** to bring up further options for that service.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-audio-service.jpg)
3. If the service is disabled, select an**Automatic** startup option on the drop-down menu.  
![The Automatic service option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/automatic-service.jpg)
4. Then select the properties window’s**Start** option to run the service.
5. Click**Apply** and**OK** to save the options and exit the Audio Properties window.
6. Repeat steps four to eight for the Windows Audio Endpoint Builder service.

 If you find the above services to be enabled and running, restarting them could also feasibly fix the issue. To do that, click Stop in their properties windows and select**Yes** to confirm. Then click their**Start** options to restart them.

## 3\. Manually Enable all Playback and Recording Devices

 It could be the case that a disabled audio playback or recording device is causing the PortAudio error to arise. For that reason, it’s recommended to enable all disabled playback and recording devices you can find in the Sound window. You can do that with the following steps:

1. To access the Run dialog, press**Win + R** .
2. Type**mmsys.cpl** in Run’s command box.
3. Click**OK** to bring up the Sound window.
4. Then click the**Playback** tab if necessary.
5. Right-click any disabled playback device and select**Enable** . Repeat this step for all disabled devices listed.  
![The Enable option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-option.jpg)
6. Then select the**Recording** tab to view more devices.  
![The Recording tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/recording-tab.jpg)
7. Click disabled recording devices with the mouse’s right button to select their**Enable** options. Enable all disabled devices listed there.
8. Select the Sound window’s**Apply** option to save settings.
9. Click**OK** on the Sound window to exit, and then restart your Windows 11/10 desktop or laptop.

## 4\. Select the Rescan Audio Devices

 If you’ve made some recent audio device changes on your PC, Audacity might not have detected them. Selecting Audacity’s**Rescan Audio Device** option can feasibly resolve the PortAudio error in such a scenario. This is how you can select that option:

1. Open the Audacity window.
2. Click**Transport** on Audacity’s menu bar.
3. Select the**Rescan Audio Devices** option.  
![The Rescan Audio Devices option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/rescan-audio-devices-option.jpg)
4. Wait for the rescan to finish, and then restart**Audacity** .

## 5\. Reinstall Audio Device Drivers

 The Internal PortAudio can also occur because of a sound device driver issue. In this case, reinstalling the drivers for all audio devices can fix this issue for some users. Trying reinstalling your PC’s audio device drivers as follows:

1. To open the Power User menu, right-click the Windows 11/10**Start** button.
2. Select**Device Manager** to bring up the window for that tool.
3. Click the arrow beside the**Audio inputs and outputs** category.  
![The Audio inputs and outputs category](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/audio-inputs-and-outputs.jpg)
4. Right-click your speaker’s audio device and select**Uninstall** .  
![The Uninstall device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-device.jpg)
5. Select**Uninstall** on the small window that opens.  
![The Uninstall button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-button.jpg)
6. Repeat the last two steps for all sound devices in the**Audio inputs and outputs** category.
7. If you utilize any sound devices with USB ports, double-click the**Universal Serial Bus** category and select to uninstall all host controllers listed there. Users who don’t have sound devices connected via USB can skip this step.
8. Restart your PC for automatic driver reinstallation. If some drivers aren’t reinstalled after the restart, select the**Action** \>**Scan for hardware** changes options in Device Manager.

## 6\. Update the Realtek Audio Codec Driver

 Does your PC have a Realtek audio codec driver? If so, it’s recommended to update that driver for the sake of fixing the Internal PortAudio error. Update that Realtek driver as follows:

1. [Open Programs and Features](https://www.makeuseof.com/windows-open-programs-and-features-tool/) to access that uninstaller tool.
2. Select Realtek High Definition Audio Driver or Realtek HD Manager.
3. Click**Uninstall** to remove the driver.  
![The Programs and Features applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/programs-and-features.jpg)
4. Then bring up the [Realtek audio driver](https://www.realtek.com/en/component/zoo/category/pc-audio-codecs-high-definition-audio-codecs-software) page.
5. Click the**Download** button for the latest compatible Realtek driver for your PC.
6. Open the folder containing the downloaded Realtek driver package.
7. Double-click the Realtek package to install the latest driver.

## 7\. Reinstall Audacity

 A corrupted Audacity installation is another potential reason for the Internal PortAudio error occurring. Reinstalling the sound editor will likely resolve Audacity installation issues. You can remove Audacity with one of the methods included in our [ways to uninstall Windows software](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) post.

 To reinstall the software, open the [Audacity](https://www.audacityteam.org/download/) download page. Click the**Download for Windows** link there to save the setup wizard. Then navigate to the directory your browser downloads to and double-click the**audacity-win-.3.2.5 x64.exe** file to reinstall Audacity.

![The download Audacity option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/download-audacity-options.jpg)

 Some users have said that reinstalling older, not newer, versions of Audacity resolved the Internal PortAudio error on their PCs. Although it’s recommended to install the latest version first, reinstalling an older version is another troubleshooting option worth considering. This [uptodown archives page](https://audacity.en.uptodown.com/windows/versions) includes a good library of older Audacity versions for download.

## Get the Internal PortAudio Error Sorted on Audacity for Windows

 Although there are plenty of audio editor alternatives to Audacity, few others match its sound recording and editing features. However, you probably won’t need to switch to an alternative music editor because of the Internal PortAudio error after applying the potential fixes above. They’re widely cited solutions that have resolved the PortAudio error for many Audacity users.

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
<li><a href="https://location-social.techidaily.com/in-2024-how-to-hidefake-snapchat-location-on-your-realme-narzo-60-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Hide/Fake Snapchat Location on Your Realme Narzo 60 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-surface-laptop-studio-2-the-near-perfect-companion/"><u>Discovering Surface Laptop Studio 2 - The Near-Perfect Companion</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-illusions-sketching-secrets-for-windows-users/"><u>Digital Illusions: Sketching Secrets for Windows Users</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-turning-tides-in-the-social-stream-boosting-post-performance-for-2024/"><u>[New] Turning Tides in the Social Stream  Boosting Post Performance for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-windows-11-security-filters-in-context-menu/"><u>Configuring Windows 11 Security Filters in Context Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/cross-network-stealth-securing-data-flow-in-winos/"><u>Cross-Network Stealth: Securing Data Flow in WinOS</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-stealthy-methods-to-watch-unseen-stories/"><u>[Updated] 2024 Approved  Stealthy Methods to Watch Unseen Stories</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-setting-up-outlook-preview-for-w10w11/"><u>Comprehensive Guide: Setting up Outlook Preview for W10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-active-directory-printer-problems-a-guide-for-win-10-users/"><u>Dealing with Active Directory Printer Problems: A Guide For WIN 10 Users</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-flying-innovations-unveiling-the-new-hubsan-x4-drone-review/"><u>[Updated] Flying Innovations  Unveiling the New Hubsan X4 Drone Review</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-advanced-windows-index-features/"><u>Configuring Advanced Windows Index Features</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/secrets-to-storing-and-viewing-digital-television-shows-for-2024/"><u>Secrets to Storing and Viewing Digital Television Shows for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-the-art-of-tracking-network-activity-via-netstat-in-win11/"><u>Discover the Art of Tracking Network Activity via Netstat in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/command-center-changing-your-onedrive-storage-territory-on-windows-10/"><u>Command Center: Changing Your OneDrive Storage Territory on Windows 10</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/in-2024-the-ultimate-guide-to-avchd-video-editing-software/"><u>In 2024, The Ultimate Guide to AVCHD Video Editing Software</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-perfecting-your-rl-game-captures-for-2024/"><u>[New] Perfecting Your RL Game Captures for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-best-practices-for-youtube-card-implementation/"><u>[New] Best Practices for YouTube Card Implementation</u></a></li>
<li><a href="https://windows11.techidaily.com/converting-oculus-quest-2-to-windows-vr-compatibility-level/"><u>Converting Oculus Quest 2 to Windows VR Compatibility Level</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-in-depth-analysis-best-valheim-seeds-for-growth/"><u>In 2024, In-Depth Analysis  Best Valheim Seeds for Growth</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-realme-narzo-n55-location-on-twitter-drfone-by-drfone-virtual-android/"><u>How to Change your Realme Narzo N55 Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-the-unseen-scroll-phenomenon-in-windows/"><u>Conquer the Unseen Scroll Phenomenon in Windows</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-unbranded-and-unbeatable-the-best-free-online-video-editors-for-2024/"><u>Updated Unbranded and Unbeatable The Best Free Online Video Editors for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/corrective-measures-for-xc0351000-hyprocvisor-not-found/"><u>Corrective Measures for XC0351000: Hyprocvisor Not Found</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-which-recording-tool-wins-a-bandicam-vs-camtasia-comparison/"><u>2024 Approved  Which Recording Tool Wins? - A Bandicam Vs. Camtasia Comparison</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-of-inactive-pc-device-engagement/"><u>Mastery of Inactive PC Device Engagement</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-pro-photography-insiders-top-picks-for-6-premium-4k-dslrs/"><u>2024 Approved  Pro Photography Insiders  Top Picks for 6 Premium 4K DSLRs</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-ultimate-blueprints-livestream-and-log-sports-matches-effectively/"><u>[Updated] Ultimate Blueprints  Livestream & Log Sports Matches Effectively</u></a></li>
<li><a href="https://windows11.techidaily.com/combating-writing-denials-in-windows-11-environment/"><u>Combating Writing Denials in Windows 11 Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/ditching-windows-11-standards-top-10-app-list/"><u>Ditching Windows 11 Standards: Top 10 App List</u></a></li>
<li><a href="https://windows11.techidaily.com/discreet-toolbar-tactics-concealing-items-in-windows-11/"><u>Discreet Toolbar Tactics: Concealing Items in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-zoom-anomalies-addressing-error-1132-in-windows-11/"><u>Correcting Zoom Anomalies: Addressing Error 1132 in Windows 11</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-top-whatsapp-video-status-creators/"><u>Updated 2024 Approved Top WhatsApp Video Status Creators</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/in-2024-engaging-book-video-summaries/"><u>In 2024, Engaging Book Video Summaries</u></a></li>
<li><a href="https://extra-tips.techidaily.com/crafting-captivating-unboxing-reels-top-tips-for-success-on-instagram/"><u>Crafting Captivating Unboxing Reels  Top Tips for Success on Instagram</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-factory-seal-on-windows-11/"><u>Disabling Factory Seal on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-how-to-activate-and-use-mouseclicklock-efficiently/"><u>Decoding How to Activate and Use MouseClickLock Efficiently</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-precision-audit-vll-application-review/"><u>In 2024, Precision Audit  VLL Application Review</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-cross-platform-capture-made-simple-for-pc-mac-and-ios/"><u>[New] 2024 Approved  Cross-Platform Capture Made Simple for PC, Mac & iOS</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/how-much-video-can-64gb128gb-hold-in-2024/"><u>How Much Video Can 64GB/128GB Hold, In 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/cut-down-clutter-how-to-set-up-autofiledeletion-on-winos/"><u>Cut Down Clutter: How to Set Up AutoFileDeletion on WINOS</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-occupied-files-a-guide-for-windows-11-users/"><u>Clearing Occupied Files: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-essential-techniques-in-post-production-of-gopro-clips/"><u>[Updated] 2024 Approved  Essential Techniques in Post-Production of GoPro Clips</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-overcoming-0x80072af9-errors/"><u>Decoding and Overcoming 0X80072AF9 Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/craft-an-individualized-look-for-your-schedule-in-windows-outlook/"><u>Craft an Individualized Look for Your Schedule in Windows Outlook</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-windows-process-aggregatorhostexe-use-and-risks/"><u>Deciphering Windows Process AggregatorHost.exe: Use and Risks</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/the-complete-rankings-of-mobile-apps-altering-your-speech/"><u>The Complete Rankings of Mobile Apps Altering Your Speech</u></a></li>
<li><a href="https://windows11.techidaily.com/convenient-telnet-setup-for-modern-windows-systems-wins/"><u>Convenient Telnet Setup for Modern Windows Systems (Wins)</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-why-many-dismiss-windows-11-now/"><u>Decoding Why Many Dismiss Windows 11 Now</u></a></li>
<li><a href="https://extra-skills.techidaily.com/screenplay-sage-answers-for-beginners-for-2024/"><u>Screenplay Sage  Answers for Beginners for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/diminishing-drain-techniques-to-limit-vanguards-user-mode-cpu-use/"><u>Diminishing Drain: Techniques to Limit Vanguard's User-Mode CPU Use</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-ascending-with-aerial-artistry-9-top-editors-for-diverse-levels/"><u>[Updated] Ascending with Aerial Artistry  9 Top Editors For Diverse Levels</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/when-struggling-to-find-a-suitable-game-recorder-for-your-pc-you-might-come-across-many-options-explore-the-best-game-recorders-for-sharing-game-highlights./"><u>When Struggling to Find a Suitable Game Recorder for Your PC, You Might Come Across Many Options. Explore the Best Game Recorders for Sharing Game Highlights</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-operational-obs-cam-after-fix-for-2024/"><u>[New] Operational OBS Cam After Fix for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-show-wi-fi-password-on-xiaomi-redmi-note-12-5g-by-drfone-android/"><u>In 2024, How to Show Wi-Fi Password on Xiaomi Redmi Note 12 5G</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/macaus-language-diversity-on-display/"><u>Macau’s Language Diversity on Display</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-messages-from-your-infinix-zero-30-5g-by-fonelab-android-recover-messages/"><u>How to recover old messages from your Infinix Zero 30 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/discerning-the-divergences-between-terminal-and-powershell/"><u>Discerning the Divergences Between Terminal & PowerShell</u></a></li>
<li><a href="https://windows11.techidaily.com/de-cluttering-notifications-tips-for-windows-11-users/"><u>De-Cluttering Notifications: Tips for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/creative-windows-users-heres-the-best-drawing-list/"><u>Creative Windows Users, Here’s the Best Drawing List</u></a></li>
<li><a href="https://windows11.techidaily.com/confronting-windows-security-blunders-with-ease/"><u>Confronting Windows Security Blunders with Ease</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-enhancing-your-youtube-reach-with-famebit-ad-sponsorships-for-2024/"><u>[Updated] Enhancing Your YouTube Reach with FameBit Ad Sponsorships for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/defeating-disk-defenders-sync-soundcard-irq-in-windows/"><u>Defeating Disk Defenders: Sync Soundcard IRQ in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-chrome-display-glitches-on-pc/"><u>Clearing Chrome Display Glitches on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-high-dpi-display-issues-in-windows/"><u>Clearing Up High DPI Display Issues in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-terminal-in-win11-start-fresh/"><u>Configuring Terminal in Win11: Start Fresh</u></a></li>
</ul></div>
