---
title: How to Make Your Retro Games Look Like They Used to With RetroArch’s Shaders
date: 2024-08-15T16:08:16.587Z
updated: 2024-08-16T16:08:16.587Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Make Your Retro Games Look Like They Used to With RetroArch’s Shaders
excerpt: This Article Describes How to Make Your Retro Games Look Like They Used to With RetroArch’s Shaders
keywords: RetroGameShadingTips,RetroArtStyleRestore,RetroArcShaderUse,ShaderRetroUpgrade,ClassicGamesEnhance,VintageGameShadeBoost,GameShadesReviveOld
thumbnail: https://thmb.techidaily.com/744014ffd50adb1d07a7a2940727b9c6e249d35c9b35474b3c5a660491ebe0a3.png
---

## How to Make Your Retro Games Look Like They Used to With RetroArch’s Shaders

 People often recommend you play your favorite games using RetroArch's multi-emulator front end. However, you might still find they look slightly "off" compared to how you remember them from when you first played them decades ago. Thankfully, RetroArch supports various shaders, with which you can emulate the look of the ancient CRT on which you first met Mario, Sonic, and their friends.

 So, let's see how those shaders work and how you can configure them to turn your old games into their former, blurry, old-phosphor-distorted, and shadow-mask/Trinitron glory.

## How Do RetroArch Shaders Work?

 Shaders are snippets of code that run on the GPU and alter the appearance of graphics produced by a game or, in this case, an emulator.

 You can think of shaders as visual filters that can radically change how games look on your screen. To use a real-world example, consider how the world looks different when wearing tinted classes. The classes don't change the world around you; they affect your perception of the world's colors, brightness, and contrast.

 RetroArch comes with various shaders that allow you to apply dozens of effects on your games. Some change the games' colors; others try to make graphics look sharper to enhance details or smoother to reduce "jaggies" (the prominent pixels appearing because of the difference between your monitor's and the game's original target resolution). And many are not standalone shaders, but groups of multiple individual shaders to achieve more detailed visual results.

 However, since we are talking about emulation and retro gaming, the most popular are "CRT shaders". Those aim to make our modern flat-panel monitors look like the CRT screens on which we originally played the emulated games back in the day.

## The Different “Types” of Shaders in RetroArch

 RetroArch supports various graphic APIs. As we will see later, it also comes with shaders in multiple languages. And not all of them are compatible with all APIs.

 To complicate things further, one API might work better on your particular GPU compared to the rest and also might lead to better or worse results, depending on the emulator core you choose to play a game.

 You might need to experiment to achieve the best results for the combination of your hardware and the games you want to play.

 Most users on a relatively new PC with a GPU by Nvidia or AMD should first try the**Vulkan** API, followed by**OpenGL** , and then**Direct3D** .

 As we will see later, you can choose from three types of shaders:**CG** ,**GLSL** , and**Slang** . Ideally, go for the third option, Slang, which is compatible with the Vulkan, Direct3D, and OpenGL APIs. According to the official RetroArch documentation, it's the newest and recommended shader format.

 Your second option should be**GLSL** , but those shaders are only compatible with**OpenGL** and best for use on phones and tablets.

**CG** should be your last option, as they are officially considered old, deprecated, and not even supported by some versions of RetroArch.

## Before Choosing a Shader

 Before moving to the shaders themselves, let's go over some other options in RetroArch that are just as important for how your emulated games will look.

 Note that, for this article, we take for granted that you have a basic setup of RetroArch up and running. If not, check our guide on [how to set up RetroArch on Windows](https://www.makeuseof.com/windows-retroarch-setup/) .

1. While using RetroArch's full-screen menu, move to**Settings** and enter the**Drivers** submenu.  
![Retroarch Settings Drivers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/retroarch-settings-drivers.jpg)
<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. Move to the**Video** option and choose the video driver for the graphics API you want to use (which, in our case, will be**Vulkan**).  
![Retroarch Settings Drivers Video Vulkan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/retroarch-settings-drivers-video-vulkan.jpg)
3. Return to the RetroArch menu's top level and launch any game you wish to play. In this article, we will use classic games for Sony's first PlayStation console with the**Beetle PSX-HW** emulation core.  
![Retroarch Selecting PSX Game](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/retroarch-selecting-psx-game.jpg)
<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
4. With the game up and running, return to RetroArch's menu (by default, it's accessible by pressing F1 on your keyboard). You will find yourself on a menu for the active game. Scroll down and choose the**Options** entry.  
![Retroarch Active Game Menu Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/retroarch-active-game-menu-options.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Scroll down to find the**Texture Filtering** entry. Although it's unrelated to the shaders we will see next, it's just as important for how your games look. Set its value to**Nearest** to have your game's graphics look as close to the original hardware as possible,**Bilinear** or**3-point** if you want to make them look smoother through playing, and**SABR** ,**xBR** , or**JINC2** for more advanced smoothing algorithms that make games look more cartoonish.  
![Retroarch Active Game Menu Options Texture Filtering JINC2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/retroarch-active-game-menu-options-texture-filtering-jinc2.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
## DIY Retrogame Remastering With RetroArch's Shaders

 Using shaders in RetroArch is as easy as selecting them through its menu. What's hard is finding the best one for what you prefer, making the games you like look how you remember them—and then tweaking them further to perfect RetroArch's visual output.

 Start by returning to the previous menu level (by default, using backspace). Scroll down to find and enter the Shaders submenu. Then...

1. Switch the**Video Shaders** toggle to**ON** to enable the use of shaders.  
![Retroarch Active Game Menu Shaders](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/retroarch-active-game-menu-shaders.jpg)
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. Choose**Load Shader Preset** to load a shader.  
![Retroarch Active Game Menu Shaders Load Shader Preset](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/retroarch-active-game-menu-shaders-load-shader-preset.jpg)
<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Move to the last folder,**shaders\_slang** , and enter it.  
![Retroarch Active Game Menu Shaders Slang Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/retroarch-active-game-menu-shaders-slang-folder.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. To help you make sense of its shader collection, RetroArch has them grouped in folders according to their type. For this article, we will go for a CRT shader to make games look like they did when displayed on old CRT monitors. You can find those shaders in the**CRT** subfolder.  
![Retroarch Active Game Menu Shaders Slang CRT folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/retroarch-active-game-menu-shaders-slang-crt-folder.jpg)
5. RetroArch offers many CRT shaders, each replicating different CRT screen "looks". Some merely add scanlines to mimic how CRT monitors looked uneven, with every other line a darker color. Others combine more effects like glow, blurring, color distortion, etc.  
![Retroarch Active Game Menu Shaders Slang CRT Royale Shader File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/retroarch-active-game-menu-shaders-slang-crt-royale-shader-file.jpg)
6. We went for the**CRT Royale** shader, which stacks various effects to achieve a look akin to Sony's old Trinitron TVs.  
![Retroarch Active Game Chrono Cross With CRT Royale Shader](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/retroarch-active-game-chrono-cross-with-crt-royale-shader.jpg)
7. You don't like how a game looks with the shader you chose? Return to the**Shaders** menu and flick the**Video Shader** toggle back to off and back to on. This action should unload your active shader and allow you to choose a new one.  
![Retroarch Active Game Menu Switching Shaders](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/retroarch-active-game-menu-switching-shaders.jpg)
8. If you find a shader you mostly like but feel looks a tad "off", don't seek further alternatives: tweak it! Return to the**Shaders** menu and scroll further down. The shader you chose will probably offer some options to tweak how it looks. For example, the**CRT Royale** shader is a package of various shaders you can tweak individually. By doing so, you can customize the amount of**bloom** , the impact of the**scanlines** , and so on.  
![Retroarch Active Game Menu Shaders CRT Royale Shader Customization](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/retroarch-active-game-menu-shaders-crt-royale-shader-customization.jpg)
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
9. After you tweak a shader's configuration, you won't see any change in your game's graphics. For that, you'll have to scroll up near the top of the same menu and select**Apply Changes** .  
![Retroarch Active Game Menu Shaders Apply Changes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/retroarch-active-game-menu-shaders-apply-changes.jpg)

<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Can You Use Multiple Shaders, and Is It Even Worth Doing?

 RetroArch allows you to use multiple shaders on top of each other, and you are free to mix them and experiment as you please. Still, as a rule of thumb, avoid mixing shaders that try to achieve similar results.

 For example, you might further improve the visuals of your games by combining a**CRT** with an**anti-aliasing** shader, but not by trying to stack three different CRT shaders on top of each other. In an extreme example, by stacking scanlines on top of scanlines, you might end up looking at a black screen instead of improved visuals.

 Shaders are great for making your games look the way you remember them, but they can't help you beat that final level boss. Don't fret, we won't tell anyone if you check our guide on [how to use RetroArch to make old games easier to beat](https://www.makeuseof.com/how-to-use-retroarch-cheat-retro-games/) !

## Retro Games, the Way You Remember Them

 As you will see for yourself when you use shaders with your emulated games, there's no going back after trying them out. Old games weren't meant to be played on modern flat-panel monitors.

 Our modern screens are great at presenting crisp and vivid graphics, but when playing old games, the result can look like a pixelated mess.

 Using RetroArch's shaders, you can bring your game's visuals closer to how they were intended to look on a classic CRT screen and, more importantly, to how you remember they used to look when you first played them.

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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-diving-deep-the-intricacies-of-the-mukbang-phenomenon/"><u>[New] 2024 Approved  Diving Deep  The Intricacies of the Mukbang Phenomenon</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-easy-to-follow-obs-setup-on-thriftier-tech/"><u>[New] Easy-to-Follow OBS Setup on Thriftier Tech</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-crafting-winning-titles-and-tags-for-your-youtube-videos/"><u>[New] In 2024, Crafting Winning Titles & Tags for Your YouTube Videos</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-framemaker-hd-recorder-tips/"><u>[New] In 2024, FrameMaker HD Recorder Tips</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2023-facebook-short-videos-and-everything-about-them-for-2024/"><u>[Updated] 2023 | Facebook Short Videos and Everything About Them for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-windows-10s-finest-film-and-multimedia-editing-apps-guide-for-2024/"><u>[Updated] Windows 10'S Finest Film and Multimedia Editing Apps Guide for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-effortless-video-integration-into-blog-posts-and-essays/"><u>2024 Approved  Effortless Video Integration Into Blog Posts & Essays</u></a></li>
<li><a href="https://howto.techidaily.com/6-fixes-to-unfortunately-whatsapp-has-stopped-error-popups-on-samsung-galaxy-m34-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Fixes to Unfortunately WhatsApp has stopped Error Popups On Samsung Galaxy M34 5G | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/accelerate-tasks-with-these-1nnovative-chatgpt-ready-pdf-management-addons/"><u>Accelerate Tasks with These 1Nnovative ChatGPT-Ready PDF Management Addons</u></a></li>
<li><a href="https://tech-haven.techidaily.com/command-your-conversations-leading-apps-to-share-chatgpt-logs/"><u>Command Your Conversations - Leading Apps to Share ChatGPT Logs</u></a></li>
<li><a href="https://windows11.techidaily.com/dodgy-deals-understanding-the-threats-of-low-price-windows-licenses/"><u>Dodgy Deals: Understanding the Threats of Low-Price Windows Licenses</u></a></li>
<li><a href="https://windows11.techidaily.com/drive-dynamics-streamlining-storage-space-in-win11/"><u>Drive Dynamics: Streamlining Storage Space in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/drive-success-top-5-windows-productivity-hacks-you-cant-miss/"><u>Drive Success: Top 5 Windows Productivity Hacks You Can't Miss</u></a></li>
<li><a href="https://driver-download.techidaily.com/easy-setup-installation-of-epson-wf-3540-printer-software-on-your-pc/"><u>Easy Setup: Installation of Epson WF-3540 Printer Software on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-command-line-master-20-key-cmd-commands/"><u>Efficient Command Line: Master 20 Key CMD Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-windows-partition-integration-strategies/"><u>Efficient Windows Partition Integration Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-resolving-windows-audio-glitches-error-code-9999/"><u>Efficiently Resolving Windows Audio Glitches: Error Code 9999</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-windows-method-to-determine-ram-specifications/"><u>Effortless Windows Method to Determine RAM Specifications</u></a></li>
<li><a href="https://windows11.techidaily.com/effortlessly-create-win-11-boot-drive-using-these-3-methods/"><u>Effortlessly Create Win 11 Boot Drive Using These 3 Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-internet-safety-in-windows-11-trusted-site-listing/"><u>Elevate Internet Safety in Windows 11: Trusted Site Listing</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-usability-and-style-for-windows-1011-in-8-ways/"><u>Elevate Usability and Style for Windows 10/11 in 8 Ways</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-game-amplifying-graphics-power-in-windows-1011/"><u>Elevate Your Game: Amplifying Graphics Power in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-device-safety-with-custom-lock-patterns-in-windows-11/"><u>Elevating Device Safety with Custom Lock Patterns in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-no-errors-comprehensible-guide-to-fixing-win11-issues/"><u>Eliminate No Errors: Comprehensible Guide to Fixing Win11 Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-old-wallpaper-3-efficient-methods/"><u>Eliminate Old Wallpaper: 3 Efficient Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-we-encountered-an-error-oculus-w11w10-guide/"><u>Eliminating We Encountered an Error: Oculus W11/W10 Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/embarking-on-a-journey-with-ai-copilot-in-windows-11/"><u>Embarking on a Journey with AI Copilot in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/emergency-printer-deletion-in-windows-os-a-step-by-step-approach/"><u>Emergency Printer Deletion in Windows OS: A Step-by-Step Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/empowering-windows-11-android-phone-webcam-utilization/"><u>Empowering Windows 11: Android Phone Webcam Utilization</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-wordsmithing-effortlessly-with-top-apps-windows/"><u>Enhance Wordsmithing Effortlessly With Top Apps (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-qbittorrent-performance-after-a-halt/"><u>Enhancing qBittorrent Performance After a Halt</u></a></li>
<li><a href="https://windows11.techidaily.com/enriching-macos-with-windows-powered-innovations/"><u>Enriching macOS with Windows-Powered Innovations</u></a></li>
<li><a href="https://windows11.techidaily.com/enriching-windows-taskmanager-with-cli-tab-feature/"><u>Enriching Windows TaskManager with CLI Tab Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-high-visibility-of-taskmanager/"><u>Ensuring High Visibility of TaskManager</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicate-black-screen-on-win11-top-easy-fixes/"><u>Eradicate Black Screen on Win11: Top Easy Fixes!</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-glitch-windows-edition-geforce-x0001/"><u>Eradicating Glitch: Windows Edition, GeForce X0001</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-3d-paint-keyboard-tricks/"><u>Essential 3D Paint Keyboard Tricks</u></a></li>
<li><a href="https://vp-tips.techidaily.com/high-speed-windows-photo-explorer-tool-for-2024/"><u>High-Speed Window's Photo Explorer Tool for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-change-motorola-edge-40-pro-lock-screen-password-by-drfone-android/"><u>How To Change Motorola Edge 40 Pro Lock Screen Password?</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-a-network-locked-samsung-galaxy-z-fold-5-phone-by-drfone-android/"><u>How to Unlock a Network Locked Samsung Galaxy Z Fold 5 Phone?</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-best-htc-frp-bypass-guide-by-drfone-android/"><u>In 2024, Best HTC FRP Bypass Guide</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-fix-icloud-lock-on-your-apple-iphone-13-and-ipad-by-drfone-ios/"><u>In 2024, How to fix iCloud lock on your Apple iPhone 13 and iPad</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/increasing-viewership-and-revenue-famebits-roadmap-to-partnerships-for-2024/"><u>Increasing Viewership and Revenue  FameBit's Roadmap to Partnerships for 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/latest-driver-for-hp-officejet-4630-available/"><u>Latest Driver for HP Officejet 4630 Available</u></a></li>
<li><a href="https://extra-resources.techidaily.com/mastering-visual-storytelling-the-top-cinematic-secrets/"><u>Mastering Visual Storytelling  The Top Cinematic Secrets</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/pixelpioneer-mastering-the-art-of-screen-capture/"><u>PixelPioneer  Mastering the Art of Screen Capture</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-science-behind-effective-slug-lines-for-2024/"><u>The Science Behind Effective Slug Lines for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/unlocking-the-power-of-cross-platform-social-media-with-youtube-and-instagram-stories/"><u>Unlocking the Power of Cross-Platform Social Media with YouTube & Instagram Stories</u></a></li>
</ul></div>