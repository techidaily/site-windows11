---
title: Essentials of Implementing Windows LAW Filters Effectively
date: 2024-07-11T21:30:46.728Z
updated: 2024-07-12T21:30:46.728Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Essentials of Implementing Windows LAW Filters Effectively
excerpt: This Article Describes Essentials of Implementing Windows LAW Filters Effectively
keywords: WinLAW Filter Guide,Laws Enforcement Tools,Windows Compliance Filters,Law Filter Integration,Effective LAW Filtering,Implementing WinLAW,Windows Legal Toolset
thumbnail: https://thmb.techidaily.com/e2a22d0e1eb69e31073b9f86edc15bd17dc9ed7433f25f15297fff8ea322d744.jpg
---

## Essentials of Implementing Windows LAW Filters Effectively

 Some media players come with them since their creators realize there's no reason to reinvent the wheel. But you can also download them as a standalone solution and install them yourself.

 The result will be broader and better compatibility with most major video and audio formats, increased control over the playback process, and an improved audiovisual experience.

 They're known as "LAV filters" and are a popular and free way to improve your computer's media playback capabilities. Here's a quick guide on how to use them.

## What Are LAV Filters?

 LAV Filters are DirectShow filters that act as alternative decoders of audio and video streams for media players like MediaPlayer Classic Home Cinema (MPC-HC).

 Compatible with many formats, from MP4 to MKV and AAC to FLAC, they are highly configurable and come with various options for adjusting output to better match your equipment.

 The best part is that these open-source filters are regularly updated, making them problem-free, ever-evolving, and quick to adopt new features.

## How to Install LAV Filters for Use With Your Media Player

 Most modern media players come with options to replace their default decoding with LAV filters. MPC-HC has the LAV filters built-in. Other players can "collaborate" with LAV filters if you install them manually.

 If you're using a newer version of MPC-HC, you can skip this section and proceed to configure LAV Filters. For other media players, install LAV Filters like this:

1. Download their installer from [LAV Filters' Github page](https://github.com/Nevcairiel/LAVFilters/releases) .  
![LAV Filters Github Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-github-page.jpg)
2. Execute the downloaded installer and leave the default**Destination Location** as is.  
![LAV Filters Installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-installer.jpg)
3. Make sure all components are marked for installation on the installer's**Select Components** page. Skip**H.264 MVC 3D Decoder** if you don't have a 3D-capable display.  
![LAV Filters Installation Components Selection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-installation-components-selection.jpg)
4. Leave the rest of the options as they are and hit**Next** until you reach the**Completing the LAV Filters Setup Wizard** page.
5. Place a checkmark on all three**Open LAV X Configuration** , where "X" is Splitter, Audio, and Video.  
![LAV Filters Setup Completion Open Configuration Panels](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-setup-completion-open-configuration-panels.jpg)

 Although MPC-HC already comes with LAV filters, we're also using it in the following example to keep things simple. However, we made the steps "generic enough" to show you how to add LAV filter functionality to any media player that supports external filters, like PotPlayer.

1. Run your media player of choice and visit its**Options** ,**Settings** , or**Preferences** page. From there, locate its Filters (for example, in PotPlayer, you'll find them under the**Filter Control** sub-page of the app's options).
2. Disable**all** internal filters/methods related to "splitting" or "demuxing" files, audio, and video.  
![MPC HC Internal Filters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/mpc-hc-internal-filters.jpg)
3. Move to your media player's option page about "external filters" and select that you want to**Add** (a)**Filter** .  
![MPC HC External Filters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/mpc-hc-external-filters.jpg)
4. Choose all four entries related to the LAV Filters:**LAV Splitter** ,**LAV Splitter Source** ,**LAV Audio Decoder** , and**LAV Video Decoder** . You'll probably have to add them one by one.  
![MPC HC Adding External Filters LAV Filters Selection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/mpc-hc-adding-external-filters-lav-filters-selection.jpg)
5. Depending on your media player, ensure they also appear in that order (for example, PotPlayer offers extra up/down buttons for re-arranging them) and are enabled/have a checkmark next to them (PotPlayer) or are set to**Prefer** (old versions of MPC-HC).  
![MPC HC External Filters Prefer Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/mpc-hc-external-filters-prefer-option.jpg)
6. On PotPlayer, you'll also have to enable all formats for them when adding them from the**Source/Splitter** \>**Filter Management** panel. Click on each of the LAV filters and then enable the appropriate formats for it - file formats for the two**Splitters** , audio formats for the**Audio Decoder** , and video formats for the**Video Decoder** . Then, move to each**Filter Control** sub-section, like**Video Decoder** and**Audio Decoder** , and ensure the LAV filters are set as the default for all formats.
7. After a click on**OK** to close your media player's settings window, LAV Filters should have replaced its internal media-splitting and decoding functions. Close and re-run the app to ensure all changes have been applied.

## How to Configure LAV Filters for Your Media & Hardware

 You can configure the LAV filters from their entries in the Start menu. Click on the**Start** button or press the**Windows Key** on your keyboard. Then, type "LAV Filters" to locate them, and "run" each filter's configuration panel.

 In the last versions of MPC-HC, where the LAV filters are "baked-in", you can move to the app's**Options** and, from there, to the**Internal Filters** section. At the bottom of the page, you'll see three entries under**Internal LAV Filters settings** .

![MPC HC Internal LAV Filters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/mpc-hc-internal-lav-filters.jpg)

 Click on each to access the settings panel for the**Splitter** ,**Video decoder** , and**Audio decoder** LAV filters, respectively.

1. For the LAV Splitter, you can leave most options as they are. To have it auto-select your preferred language for audio and subtitles, enter its shortcode (like "en" for English) in the fields under**Audio** and**Subtitles** . Place a checkmark on**Enable System Tray Icon** on the bottom left of the window to have the LAV Splitter filter's options easily accessible from the Windows tray.  
![LAV Filters Splitter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-splitter.jpg)
2. For the**Audio Decoder** settings, if the "audio gear" where your PC "sends" its audio (headphones, speakers, monitor) can decode digital streams, enable the appropriate formats under**Bitstreaming** . We can't offer suggestions on how to do that since different audio equipment requires different settings. Leave**Fallback to PCM if Bitstreaming is not supported** so that if your audio gear can't play the above formats, you'll still hear audio.  
![LAV Filters Audio Bitstreaming](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-audio-bitstreaming.jpg)
3. If you're using a multi-speaker setup, monophonic streams will only play from a single speaker by default. If you'd prefer the classic approach of "expanding" the mono stream to two stereo speakers, enable**Expand Mono to Stereo** . We'd suggest you also enable**Expand 6.1 to 7.1** if you use a 7.1 speaker setup with your PC.
4. The next option,**Use Legacy 5.1 Channel Layout** , may be helpful if your speakers go haywire while playing 5.1 audio and you don't hear "properly placed" positional audio. If you don't know what to choose, and only know "you've got a bunch of speakers", check out our guide on [how to understand surround sound systems for beginners](https://www.makeuseof.com/understanding-surround-sound-systems/) .  
![LAV Filters Audio Expand Mono to Stereo](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-audio-expand-mono-to-stereo.jpg)
5. Make sure to also place a checkmark on**Enable System Tray Icon** for LAV Filters' Audio Decoder. Then, move to the**Mixing** tab.  
![LAV Filters Audio Enable System Tray Icon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-audio-enable-system-tray-icon.jpg)
6. If you play a lot of audio that doesn't match your sound output setup, for example, watching old movies with stereo sound on a 5.1 speaker setup, you can have LAV Filters upmix or downmix the sound to "morph" it for your audio gear. Place a checkmark before**Enable Mixing** and choose your speaker setup from the drop-down menu next to**Output Speaker Configuration** . You can also individually configure the sound levels for the center speaker, behind left and right speakers, and subwoofer (LFE).  
![LAV Filters Audio Mixing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-audio-mixing.jpg)
7. If you use the same media player for listening to music, you might want to ensure stereo sources (like most of your beloved music) will remain untouched (and "untainted") from any mixing shenanigans. For that, enable the option**Don't mix Stereo Sources** on the top right of this panel. Click**OK** to accept and save the changes.  
![LAV Filters Audio Dont Mix Stereo Sources](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-audio-dont-mix-stereo-sources.jpg)
8. Finally, for the video settings, choose the best hardware decoder for your GPU under**Hardware Acceleration** . At the time of writing (beginning of 2023),**DXVA2** and**CUVID** are better on Nvidia GPUs, while**D3D11** may work best on AMD's offerings. It's also worth trying those options out on newer Intel Arc GPUs since they use a different decoding engine than the one for which the option**Intel(R) QuickSync (old)** was built.  
![LAV Filters Video Hardware Acceleration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-video-hardware-acceleration.jpg)
9. Remember the option**Enable System Tray Icon** here, too. After enabling it, click**OK** to save the changes and close the last LAV Filters configuration panel.  
![LAV Filters Video Enable System Tray Icon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/lav-filters-video-enable-system-tray-icon.jpg)

 Although your videos will play perfectly with LAV filters, if you try to grab some screenshots of your favorite scenes, they might appear blurry. Thankfully, we have a guide on [how to save frame-perfect video screenshots on Windows using a media player](https://www.makeuseof.com/windows-media-player-frame-perfect-screenshot/) that can help you solve this problem, too.

## Achieve Optimal Playback With LAV Filters

 After making sure to close and re-run your media player, LAV Filters should be installed, configured, and ready to go. Try playing some media as usual, and you should see the LAV Filters' icons pop up on the Windows tray.

 More importantly, you should see an improvement compared to your media player's native decoding, smoother playback, and possibly lower CPU utilization!


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
<li><a href="https://extra-approaches.techidaily.com/quintessential-scripts-elevating-blockbusters-for-2024/"><u>Quintessential Scripts Elevating Blockbusters for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unpacking-essential-upgrades-in-februarys-win11-patch/"><u>Unpacking Essential Upgrades in February's Win11 Patch</u></a></li>
<li><a href="https://windows11.techidaily.com/disentangle-windows-11-taskbar-clusters/"><u>Disentangle Windows 11 Taskbar Clusters</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-health-check-up-top-13-restoration-techniques/"><u>Windows Health Check-Up: Top 13 Restoration Techniques</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-15-apps-to-hack-wifi-password-on-samsung-galaxy-a05s-by-drfone-android/"><u>In 2024, Top 15 Apps To Hack WiFi Password On Samsung Galaxy A05s</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-tecno-pova-6-pro-5g-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Tecno Pova 6 Pro 5G without Losing Data | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/disable-automatic-snipping-tool-activation-by-prtscn-keypress-in-windows-11/"><u>Disable Automatic Snipping Tool Activation by PrtScn Keypress in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-cause-of-display-driver-non-startups/"><u>Deciphering the Cause of Display Driver Non-Startups</u></a></li>
<li><a href="https://windows11.techidaily.com/win11s-guide-to-stable-background-fixes/"><u>Win11's Guide to Stable Background Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-wow-steps-to-overcome-error-132/"><u>Win11 WoW: Steps to Overcome Error #132</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-explainer-video-creation-made-easy-top-picks/"><u>In 2024, Explainer Video Creation Made Easy Top Picks</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-high-quality-capture-on-mac-a-review-of-top-10-software-for-2024/"><u>[New] High-Quality Capture on Mac  A Review of Top 10 Software for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-absent-msvcr110dll-in-windows/"><u>Correcting Absent msvcr110.dll in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-graphics-glitch-d3d11-error-fixes-for-win11win10/"><u>Conquering Graphics Glitch: D3D11 Error Fixes for Win11/Win10</u></a></li>
<li><a href="https://windows11.techidaily.com/using-windows-system-restore-feature-efficiently/"><u>Using Windows' System Restore Feature Efficiently</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/transform-your-snaps-with-cutting-edge-filter-techniques-for-2024/"><u>Transform Your Snaps with Cutting-Edge Filter Techniques for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-optimized-vimeo-video-exporting-apps/"><u>[New] In 2024, Optimized Vimeo Video Exporting Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-performance-and-productivity-in-windows-1011/"><u>Boosting Performance & Productivity in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-guide-to-securing-edge-ms-defender-application-guard-on-windows-11/"><u>Easy Guide to Securing Edge: MS Defender Application Guard on Windows 11</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-discover-the-perfect-aspect-ratio-for-twitter-videos-for-2024/"><u>New Discover the Perfect Aspect Ratio for Twitter Videos for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/device-duet-pairing-your-android-with-a-pc/"><u>Device Duet: Pairing Your Android with a PC</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-find-brush-sound-effect/"><u>New 2024 Approved Find Brush Sound Effect</u></a></li>
<li><a href="https://windows11.techidaily.com/ace-in-the-game-winning-at-full-screen-with-sonic-adventure-w11-edition/"><u>Ace in the Game: Winning at Full Screen with Sonic Adventure, W11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-revolution-essential-replacement-tools-to-consider/"><u>Win 11 Revolution: Essential Replacement Tools to Consider</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-user-folder-names-on-windows-11/"><u>Altering User Folder Names on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-steering-classic-games-to-your-pics/"><u>Windows 11: Steering Classic Games to Your Pics</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-ultimate-guide-to-polarr-photo-editor-proficiency/"><u>[New] The Ultimate Guide to Polarr Photo Editor Proficiency</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-set-10-key-ms-store-games-and-tools/"><u>Winning Set: 10 Key MS Store Games & Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-wins-system-alert-messages-in-windows-1011/"><u>Correcting WINS System Alert Messages in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/defining-windows-lockout-after-inactivity/"><u>Defining Windows Lockout After Inactivity</u></a></li>
</ul></div>
