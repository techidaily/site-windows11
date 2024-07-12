---
title: "Polishing Old Videos: Windows MadVR Techniques Unveiled"
date: 2024-07-11T22:05:58.577Z
updated: 2024-07-12T22:05:58.577Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Polishing Old Videos: Windows MadVR Techniques Unveiled"
excerpt: "This Article Describes Polishing Old Videos: Windows MadVR Techniques Unveiled"
keywords: VR Video Enhancement,Windows Animation SDK,MadVR Integration,Advanced Video Polishing,Virtual Reality Rendering,Video Optimization Techniques,Modernizing Old Videos
thumbnail: https://thmb.techidaily.com/f6689b1ce3b098830c1181e612252ff5b928460b4d7d4122dbd300e015bd5d6c.jpg
---

## Polishing Old Videos: Windows MadVR Techniques Unveiled

 You've just purchased a new monitor, perfect for gaming and using apps. But, when you tried to watch your offline media, the quality was a blocky and blurry mess. Shouldn't everything look better on your brand-new monitor?

 Welcome to the world of modern high-res displays, where most of our older video files can only cover one-fourth of the screen... at best. To improve the quality of these older videos, you need to use smart filters and upscalers, and madVR is one of the best for Windows.

## What Is MadVR?

 MadVR is a powerful post-processing filter "enhancer" for many popular media players. It offers a range of sophisticated algorithms to upscale and improves video quality. Unlike apps like the [top video editors for YouTube](https://www.makeuseof.com/free-video-editors-youtube-2022/) that we've already covered, it works in real-time, "improving" your videos as they play.

 With some tweaking, madVR can make lower-resolution videos look better on high-resolution displays, and reduce the effects of compression on highly-compressed files. The more compressed the file, the more striking the improvement.

 MadVR is heavily optimized yet relatively lightweight, so you can use it on older PCs without worrying about resources.

Best of all, it is open-source and free to use.

## How to Add MadVR to MPC-HC

 You can use madVR with many media players. Still, for this tutorial, we'll use the popular Media Player Classic - HomeCinema, better known as "MPC-HC". It's old and has ceased development, but it remains one of the best solutions for playing media when paired with madVR.

1. Start by downloading its latest version from [madVR's official site](https://madvr.com/) . We assume you've downloaded and installed the media player part of the equation from [MPC-HC's official site](https://mpc-hc.org/) .  
![madVR Official Site](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/madvr-official-site.jpg)
2. Extract madVR's downloaded archive into any folder of your choice. You can extract it directly in MPC-HC's installation folder, but if you want to use it in more than one player, it's best to extract it in a folder of its own.
3. Launch MPC-HC and choose**View** \>**Options** .  
![MPC HC Options Menu Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/mpc-hc-options-menu-entry.jpg)
4. Look for the**External Filters** options page on the list on the left and click on it — it's the fourth entry if viewing the list in fully collapsed view.
5. Click on**Add Filter** at the top right.  
![MPC HC Add Filter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/mpc-hc-add-filter.jpg)

1. Click on**Browse** at the bottom left of the new**Select Filter** window. Point the requester to the folder where you extracted madVR and select the**madVR.ax** file. Click**OK** to return to the**Select Filter** window. Locate**madVR** among the entries, select it, and click**OK** .  
![MPC HC Select Filter MadVR](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/mpc-hc-select-filter-madvr.jpg)
2. Click on the newly-added**madVR** entry on the**External Filters** list. Choose**Prefer** from the options on the right.  
![MPC HC MadVR Prefer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/mpc-hc-madvr-prefer.jpg)
3. Expand the**Playback** entry from the list on the left and choose**Output** .
4. Click on the drop-down menu under**DirectShow Video** and select**madVR** .
5. Press**OK** to save the changes. Close and relaunch MPC-HC to ensure it will be using the madVR renderer.

## Tweaking the MadVR Settings

 After adding and enabling madVR in MPC-HC, if you start playing a video file with it, you'll see a new icon for madVR appear in the Windows tray. Right-click on it and choose**Edit madVR Settings** to configure the renderer according to your gear and preferences.

### 1\. Setting Up the Basics With MadVR

 Expand the**devices** group from the list on the left, and choose your display device. Change its**device type** to reflect its type. For most, it will probably be**Digital Monitor / TV** . Do the same for your other display devices if you use more than one.

![MadVR Devices](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/madvr-devices.jpg)

 Expand the**processing** group, and choose**deinterlacing** . If you're a fan of anime, disable**only look at pixels in the frame center** .

![MadVR Deinterlacing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/madvr-deinterlacing.jpg)

 Move to**artifact removal** , and pause for a second. Now's the time to drag and drop a video, preferably a highly-compressed one, onto MPC-HC's window, and let it play in the background. This way, you'll be able to check how your madVR settings affect how videos look.

 Try enabling the options in this section one by one and, if available, progressively increasing their strength. You can click on**Apply** at any time to check their effect on your video.

![MadVR Artifact Removal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/madvr-artifact-removal.jpg)

 When your video starts looking "off", with annoyingly pronounced "edges" around elements, dial your last settings down a notch. If playing a lot of MPEG4/HEVC content (encoded with DivX/XviD/H.264/H.265/NVENC), make sure to try out**reduce compression artifacts** . Setting its quality to**very high** and enabling**process chroma channels, too** come with higher requirements but can also further reduce the annoying "(macro)blocks" on highly-compressed files.

![MadVR Reduce Compression Artifacts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/madvr-reduce-compression-artifacts.jpg)

 Do the same for the options in the**image enhancements** section. Since their result depends on both the active video and your perception of what looks best, we'll leave the choice of which you should enable and their values up to you. Remember that you can see their effect in any active video immediately after hitting the**Apply** button on the window.

![MadVR Image Enhancements](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/madvr-image-enhancements.jpg)

### 2\. Performing Upscaling With MadVR

 Move to the**scaling algorithms** and start from**chroma upscaling** . All options here take advantage of modern GPUs, so you can choose any you want without wasting resources. For each option, madVR will show you how it affects the video on the top right of its window.

**Positive** results are marked with**green bars** and**negative** ones with**red bars** . The longer the bar, the more noticeable the effect. Also, enable the**SuperRes** filter and increase its strength to 2 or 3 to take advantage of madVR's scaling chops.

![MadVR Chroma Upscaling](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/madvr-chroma-upscaling.jpg)

 Modern GPUs are pretty good at downscaling. Thus, you can choose**DXVA2** from the**image downscaling** page to have the task entirely performed by your GPU. However, the other options also "run" on the GPU, either on its texture units or as pixel shaders, and may offer even crisper visuals. It's worth trying them all out to see which you prefer.

![MadVR Image Downscaling](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/madvr-image-downscaling.jpg)

 Move to**image upscaling** , and notice how the options here are split into two lists:**Upscaling** and**Doubling** .**Upscaling** lists advanced algorithms that analyze each frame and try to create more visual detail from what already exists.

**Doubling** lists various methods that also "make a video look larger than it is" but with simpler "show-each-pixel-more-than-once" methods (hence "pixel doubling"). This writer's personal preference is**Jinc** , but fans of Anime will also want to try**super-XBR** .

![MadVR Image Upscaling](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/madvr-image-upscaling.jpg)

 As before, we won't suggest specific settings for the options on**upscaling refinement** . Enable them one by one, play with their values, and click**Apply** to find what you like. If you see strange artifacts, lines, or elements of your video look "glitchy", change the last option on this page to**Refine the image only once after upscaling is complete** .

![MadVR Upscaling Refinement](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/madvr-upscaling-refinement.jpg)

### 3\. Adjusting the Quality With MadVR

 If your videos look jerky in motion, expand the**Rendering** section, and on the**Smooth Motion** page, place a checkmark on**enable smooth motion frame rate conversion** . This may lead to the "soap opera effect," which refers to how TV shows look compared to movies (because of their higher framerate).

![MadVR Smooth Motion](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/madvr-smooth-motion.jpg)

 For the highest quality, you can visit the**Trade Quality for Performance** page and disable some or all of the default settings. However, these will make less of a difference compared to the other options.

![MadVR Quality Or Performance](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/madvr-quality-or-performance.jpg)

## A Final Note About MadVR

 Keep in mind that not all videos are equal. Your madVR settings will need tweaking depending on the video you're watching. You can use "mild" defaults for general improvement of all videos on your monitor, but madVR is best when you invest a minute in fine-tuning it for each video.

 Still, madVR has its limitations. It can improve how videos look and perform smart upscaling, but it's still a filter, tailored for real-time media reproduction, not a full-blown upscaling app. If you want the best upscaling quality for your videos, you'll have to use a dedicated app and invest some time to do it manually, as we saw on our guide on [how to upscale a video to 4K](https://www.makeuseof.com/how-to-upscale-video-to-4k/) .

 However, if you configure madVR with relatively mild settings, it will essentially be a "set it and forget it" affair. After its initial configuration, it will start enhancing every video you play with MPC-HC. Plus, if you enable it in any other media player, you won't have to reconfigure its settings; it will make your videos look just as good there.

 Still, you may need to make occasional tweaks here and there to make a video look its best. One video might need less sharpening, while another might look better with a higher "reduce compression artifacts" value.

## Getting Optimal Playback With MadVR

 And that's how madVR can go beyond being just a video renderer and become a full-blown hobby. Don't be alarmed if you find yourself trying to upgrade every video and constantly adjusting madVR's settings. You'll be joining a club of many.


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
<li><a href="https://windows11.techidaily.com/revolutionizing-mouse-interactions-on-windows-via-clicklock-techniques/"><u>Revolutionizing Mouse Interactions on Windows via ClickLock Techniques</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-data-from-motorola-moto-g84-5g-by-fonelab-android-recover-data/"><u>Undelete lost data from Motorola Moto G84 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-lost-thermal-management-directive-for-pcs/"><u>Restoring Lost Thermal Management Directive for PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/top-essential-gratis-tools-for-windows-11-enthusiasts/"><u>Top Essential Gratis Tools for Windows 11 Enthusiasts</u></a></li>
<li><a href="https://windows11.techidaily.com/revising-account-lockout-count-after-multiple-login-failures-in-windows-11/"><u>Revising Account Lockout Count After Multiple Login Failures in Windows 11</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/snapshot-showdown-youtube-shorts-challenge-to-the-titans-of-tiktok/"><u>Snapshot Showdown  YouTube Shorts Challenge to the Titans of TikTok</u></a></li>
<li><a href="https://windows11.techidaily.com/skyrocketing-vm-potential-in-windows-implement-these-top-strategies/"><u>Skyrocketing VM Potential in Windows - Implement These Top Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/systematic-approach-to-eliminate-flashing-on-windows/"><u>Systematic Approach to Eliminate Flashing on Windows</u></a></li>
<li><a href="https://howto.techidaily.com/xiaomi-14-pro-not-receiving-texts-10-hassle-free-solutions-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Xiaomi 14 Pro Not Receiving Texts? 10 Hassle-Free Solutions Here | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-inventory-of-videography-items-for-exploration/"><u>[New] Inventory of Videography Items for Exploration</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-hp-notebook-efficient-screen-capture-strategies/"><u>[New] 2024 Approved  HP Notebook  Efficient Screen Capture Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-guide-to-brightening-the-windows-11-pointer/"><u>The Essential Guide to Brightening the Windows 11 Pointer</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-adopting-nature-positive-policies-in-urban-governance/"><u>2024 Approved  Adopting Nature-Positive Policies in Urban Governance</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-mastering-video-presentation-utilizing-lc-and-bb-techniques-on-facebook/"><u>2024 Approved  Mastering Video Presentation  Utilizing LC and BB Techniques on Facebook</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-windows-taskbar-recovery/"><u>Strategies for Windows Taskbar Recovery</u></a></li>
<li><a href="https://techidaily.com/undeleted-lost-videos-from-90-gt-by-fonelab-android-recover-video/"><u>Undeleted lost videos from 90 GT</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-unleash-creative-potential-tips-and-tricks-for-filming-with-logitech-cam/"><u>[New] 2024 Approved  Unleash Creative Potential  Tips and Tricks for Filming with Logitech Cam</u></a></li>
<li><a href="https://windows11.techidaily.com/pro-tip-unearthing-windows-apps-installed-locations-quickly/"><u>Pro Tip: Unearthing Windows Apps' Installed Locations Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/the-complete-surface-computing-firmware-upgrade-manual/"><u>The Complete Surface Computing Firmware Upgrade Manual</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-2024-approved-the-ultimate-guide-to-vlc-slow-motion-video-playback/"><u>Updated 2024 Approved The Ultimate Guide to VLC Slow Motion Video Playback</u></a></li>
<li><a href="https://windows11.techidaily.com/the-blueprint-for-a-more-effective-and-reliable-windows-11/"><u>The Blueprint for a More Effective and Reliable Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-lessening-high-cpu-demand-from-tiworkerexe-tasks/"><u>Strategies for Lessening High CPU Demand From TiWorker.exe Tasks</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-circumvent-no-more-files-alert/"><u>Strategies to Circumvent No More Files Alert</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-best-websites-to-download-a-youtube-ringtone/"><u>2024 Approved  Best Websites To Download A YouTube Ringtone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-top-9-secure-virtual-meeting-solutions-for-startups/"><u>In 2024, Top 9 Secure Virtual Meeting Solutions for Startups</u></a></li>
<li><a href="https://windows11.techidaily.com/purify-your-setup-tiny11s-no-fuss-features/"><u>Purify Your Setup: Tiny11's No-Fuss Features</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-insufficient-spec-on-game-captures/"><u>Troubleshooting Insufficient Spec on Game Captures</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-eliminate-windows-error-xc0f1103f-on-geforce/"><u>Steps to Eliminate Windows Error XC0F1103F on GeForce</u></a></li>
<li><a href="https://windows11.techidaily.com/tactile-hover-over-customizing-your-click-experience-in-win11/"><u>Tactile Hover Over: Customizing Your Click Experience in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-biometric-control-in-w11-for-domain-users/"><u>Secure Biometric Control in W11 for Domain Users</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-capturing-screenshots-like-a-pro-the-best-recorder-reviews-for-2024/"><u>[New] Capturing Screenshots Like a Pro  The Best Recorder Reviews for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-streamlining-video-production-leveraging-siri-features-in-tiktok-filmmaking/"><u>[Updated] 2024 Approved  Streamlining Video Production  Leveraging Siri Features in TikTok Filmmaking</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-winscomrssvrdll-anomaly-during-boot-up/"><u>Tackling the Winscomrssvr.dll Anomaly During Boot-Up</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-list-of-pokemon-go-joysticks-on-apple-iphone-se-drfone-by-drfone-virtual-ios/"><u>In 2024, List of Pokémon Go Joysticks On Apple iPhone SE | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-0xa00f4243-overlapping-camera-usage-in-apps/"><u>Troubleshooting 0xA00F4243: Overlapping Camera Usage in Apps</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-the-ultimate-checklist-finding-videos-on-fb-today/"><u>In 2024, The Ultimate Checklist  Finding Videos on FB Today</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-in-2024-from-voice-to-verse-a-novices-guide-to-creating-a-polished-podcast-masterpiece/"><u>New In 2024, From Voice to Verse A Novices Guide to Creating a Polished Podcast Masterpiece</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-exploring-the-world-of-virtual-identities-with-discord-avatars/"><u>In 2024, Exploring the World of Virtual Identities with Discord Avatars</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-2-ways-to-transfer-text-messages-from-oneplus-open-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 2 Ways to Transfer Text Messages from OnePlus Open to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-extensive-review-the-hero4-black-journey/"><u>In 2024, Extensive Review  The Hero4 Black Journey</u></a></li>
<li><a href="https://windows11.techidaily.com/the-magic-behind-the-scenes-in-photo-app-delete/"><u>The Magic Behind the Scenes in Photo App Delete</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-music-manifesto-constructing-your-signature-youtube-playlists/"><u>In 2024, Music Manifesto  Constructing Your Signature YouTube Playlists</u></a></li>
</ul></div>
