---
title: Correcting Failed Video Drivers in Win11/10
date: 2024-07-11T21:59:07.503Z
updated: 2024-07-12T21:59:07.503Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting Failed Video Drivers in Win11/10
excerpt: This Article Describes Correcting Failed Video Drivers in Win11/10
keywords: Fix Video Driver Win11,Win10 Video Driver Troubleshoot,Resolve Video Issues Win10,Correcting Win11 Video Errors,Update Failed Video Drivers Windows,Fix Windows 10 Video Glitches,Diagnose Win10/Win11 Video Problems
thumbnail: https://thmb.techidaily.com/738b7371069538e959521966db00e5f006e9b11d983f215b33d6c4263c894748.png
---

## Correcting Failed Video Drivers in Win11/10

 Users have widely reported an error message that says “Video driver crashed and was reset” pops up when playing or trying to start Windows games. This error message crashes games whenever it arises. Players have reported that the issue usually occurs in games like Fortnite, ARK: Survival, Final Fantasy 7, and Sea of Thieves, among others.

 Although this issue is mainly reported for games, it can also crash high-resolution videos. It is a recurring error that can make games unplayable or videos unwatchable. This is how you can fix the “Video driver crashed” error on a Windows 11/10 PC.

## 1\. Utilize the Video Playback Troubleshooter

 The Video Playback troubleshooter might be useful for fixing the “Video driver crashed” error when that error affects video playback. That is a troubleshooter for fixing video playback issues, which the “Video driver crashed” error sometimes is. Our [how to run any Windows troubleshooter](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) guide provides instructions for accessing that troubleshooter and others.

 When you start that troubleshooting tool, you’ll have three options. Select the **I want to continue with this troubleshooter** option to initialize the automated video troubleshooting. The troubleshooter might automatically make some system changes or suggest you do something like installing a codec.

![The Video Playback troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-video-playback-troubleshooter.jpg)

## 2\. Update Your PC’s Graphics Driver

 Updating graphics drivers is one of the most widely confirmed ways to fix the “Video driver crashed” error. Even the error message itself suggests users update their graphics cards’ drivers. So, it’s quite likely this potential resolution will address the error if your graphics card driver needs updating.

 Our [how to update graphics drivers](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/) article covers the different methods for applying this potential resolution on a Windows PC. You could utilize driver updater software, but that won’t necessarily install the very latest driver available for your graphics card.

 Manually updating graphics drivers by downloading them from the NVIDIA, AMD, or Intel sites is a bit slower but will ensure you get the very latest driver package.

![The NVIDIA driver download page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-nvidia-driver-download-options.jpg)

## 3\. Reinstall Your PC’s Graphics Driver

 If your PC’s current graphics driver is the latest one available, it won’t be outdated, but there could still be an issue with that driver. In this case, you might still need to reinstall the driver to resolve this error.

 These are the steps for reinstalling a graphics driver:

1. [Open Device Manager](https://www.makeuseof.com/windows-open-device-manager/), which is accessible on the Power User menu (press **Windows** key + **X** to open).
2. Click the small arrow beside the **Display adapters** category.
3. Right-click your PC’s GPU and select **Uninstall device**.  
![The Uninstall device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-uninstall-device-option.jpg)
4. Select a checkbox option for deleting the driver and click **Uninstall**.  
![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-uninstall-option3.jpg)
5. Click on **Action > Scan for hardware changes** to reinstall the graphics driver.

 If the **Scan for hardware** changes option doesn’t reinstall the GPU’s driver, download the latest driver package for your graphics card from the [Intel](https://www.intel.com/content/www/us/en/download-center/home.html), [AMD](https://www.amd.com/en/support), or [NVIDIA](https://www.nvidia.com/download/index.aspx) websites. Double-click on the downloaded driver package file to open its setup window and select the installation option there.

## 4\. Lower Your Monitor’s Refresh Rate

 Some users have said on forums that lowering the frame rate can resolve the “Video driver crashed” error. So, that might be worth trying if your monitor has a higher maximum refresh rate. You can reduce the frame rate by lowering a monitor’s refresh rate as follows:

1. Open the file search tool (accessible with a **Windows** logo + **S** hotkey).
2. Input **advanced display settings**.
3. Select **View advanced display info** to open that part of Settings.
4. Then, select a lower setting in the **Refresh rate** drop-down menu.  
![The Refresh rate drop-down menu in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/advanced-display-settings.jpg)

 If you can access in-game settings, you might also be able to select a lower frame rate option from there. Look through an affected game’s graphical settings menu to see if it includes an FPS option for selecting lower or higher frame rates.

## 5\. Reduce an Affected Game’s Graphical Quality Settings

 The “Video driver crashed” error can sometimes occur when a game’s graphical settings are set too high. That’s more likely on lower-spec PCs with poorer GPUs that can’t handle higher graphics settings so well.

 A few players have said they fixed the “Video driver crashed” error by lowing in-game graphics options. So, that’s worth trying if you can reach in-game settings.

 There will probably be numerous in-game graphical options you can adjust. Lower the screen, texture, and shadow resolution settings that are included in many games. Then, select to apply the new graphical settings and restart the game.

![A game's Graphics Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/graphics-settings.jpg)

 Alternatively, you can try selecting a lower graphics preset option instead. Most games have three or more graphics presets that generally change graphical settings. Selecting a lower-quality preset will automatically reduce various graphics options.

 Some players have also reported this error occurring after enabling DirectX 12\. So, look for a DirectX setting in the graphics menu. If you can find it, make sure that option is set to DirectX 11\.

## 6\. Set a Higher TDR Delay Value

 TDR delay is the Timeout Detection and Recovery delay period. Setting a higher TDR delay value will give a graphics card more time to respond, which can resolve GPU errors such as the “Video driver crashed” error.

 You can set a higher TDR delay value by tweaking the registry like this:

1. Bring up the tool for finding files and input Registry Editor in its search box.
2. Select **Registry Editor** to view that app’s window.
3. Go to this **GraphicsDrivers** key by entering the following path inside the registry address bar:  
HKEY_LOCAL_MACHINE\System\CurrentControlSet\Control\GraphicsDrivers
4. If a **TDRDelay** DWORD already exists, you can skip to step six. If not, right-click **GraphicsDrivers** in Registry Editor’s left sidebar and select the **New** and **DWORD (32-bit) Value** options from the context menu.  
![The DWORD (32-bit) Value option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-dword-32-bit-value-option.jpg)
5. Input **TDRDelay** for the key’s title.
6. Double-click on the **TDRDelay** registry entry.
7. Delete the current number and enter **8** in the **Value data** box.  
![The Edit DWORD (32-bit) Value window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-edit-dword-window.jpg)
8. Select **OK** to finish.

 Restart the PC after applying this registry tweak. Then, try playing games or videos to see if this error still occurs.

## Enjoy Your Windows Games and Videos Again

 Those potential resolutions are among the most widely confirmed troubleshooting methods for fixing the “Video driver crashed” error. Many users have discussed how to fix the “Video driver crashed” error on forums and confirmed them to work.

 So, maybe one of them will fix the same issue on your PC, and then you can enjoy all your Windows games or videos again without further crashing.

 Although this issue is mainly reported for games, it can also crash high-resolution videos. It is a recurring error that can make games unplayable or videos unwatchable. This is how you can fix the “Video driver crashed” error on a Windows 11/10 PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://twitter-clips.techidaily.com/in-2024-tweet-treasure-trove-the-most-popular-tweeps/"><u>In 2024, Tweet Treasure Trove  The Most Popular Tweeps</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-windows-index-settings/"><u>Configuring Windows Index Settings</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-easy-to-follow-setting-up-snapchat-on-a-mac/"><u>[Updated] In 2024, Easy to Follow  Setting up Snapchat on a Mac</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-fatal-error-code-0x800f0831/"><u>Resolving Windows' Fatal Error: Code 0X800F0831</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-panels-revealed-recovering-offscreen-windows-in-edges-os/"><u>Hidden Panels Revealed: Recovering Offscreen Windows in Edges OS</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-your-blueprint-to-mastering-the-snapchat-boomerang-skill-for-2024/"><u>[New] Your Blueprint to Mastering the Snapchat Boomerang Skill for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/removing-geforce-graphical-overlay-feature/"><u>Removing GeForce Graphical Overlay Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaim-shift-control-with-easy-fixes/"><u>Reclaim Shift Control with Easy Fixes</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-extensive-insights-deconstructing-the-dji-inspire-1/"><u>[New] Extensive Insights  Deconstructing the DJI Inspire 1</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-endorsed-top-10-for-windows-free-app-safety/"><u>Expert-Endorsed Top 10 for Windows FREE App Safety</u></a></li>
<li><a href="https://windows11.techidaily.com/keep-your-data-and-save-space-win11s-secure-drive-management-methods-max-156-chars/"><u>Keep Your Data and Save Space: Win11's Secure Drive Management Methods (Max 156 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rejuvenate-your-windows-11-with-a-fresh-reboot/"><u>How to Rejuvenate Your Windows 11 with a Fresh Reboot</u></a></li>
<li><a href="https://windows11.techidaily.com/proactive-upgrade-implementing-tpm-and-secure-boot-on-w11-systems/"><u>Proactive Upgrade: Implementing TPM and Secure Boot on W11 Systems</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/photography-and-captioning-a-guide-to-dynamic-text/"><u>Photography & Captioning  A Guide to Dynamic Text</u></a></li>
<li><a href="https://windows11.techidaily.com/real-time-resource-management-tracking-cpu-memory-and-graphics/"><u>Real-Time Resource Management: Tracking CPU, Memory & Graphics</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-visual-voice-choir-discovering-video-driven-music/"><u>[Updated] 2024 Approved  Visual Voice Choir  Discovering Video-Driven Music</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/arnessing-youtubes-power-for-profit-mastering-short-video-earnings-for-2024/"><u>[New] Harnessing YouTube's Power for Profit  Mastering Short Video Earnings for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-it-fast-dealing-with-microsoft-store-errors-in-1011-systems/"><u>Fix It Fast: Dealing with Microsoft Store Errors in 10/11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/free-media-titans-for-effortless-windows-experience/"><u>Free Media Titans for Effortless Windows Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-lost-functionality-to-windows-netflix/"><u>Restoring Lost Functionality to Windows Netflix</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-best-zero-cost-4k-video-editing-tools-for-beginners-for-2024/"><u>New Best Zero-Cost 4K Video Editing Tools for Beginners for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/keeping-notes-prominent-on-windows-10-and-11/"><u>Keeping Notes Prominent on Windows 10 & 11</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-5-top-audio-tools-to-master-recording-your-voice-with-ease-for-2024/"><u>New 5 Top Audio Tools to Master Recording Your Voice with Ease for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/voice-logging-access-and-evaluation/"><u>Voice Logging Access & Evaluation</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-open-the-internet-options-in-windows-11/"><u>How to Open the Internet Options in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-windows-aggregatorhostexe-functions-risks-and-safety-concerns/"><u>Decoding Windows' AggregatorHost.exe: Functions, Risks, and Safety Concerns</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-mastering-personal-branding-essential-strategies-for-facebook-bio-crafting/"><u>[Updated] Mastering Personal Branding  Essential Strategies for Facebook Bio Crafting</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-night-photography-perfection-with-iphones/"><u>In 2024, Night Photography Perfection with iPhones</u></a></li>
<li><a href="https://extra-information.techidaily.com/slumber-series-evaluating-video-adaptations-of-literary-classics/"><u>Slumber Series  Evaluating Video Adaptations of Literary Classics</u></a></li>
<li><a href="https://fox-helps.techidaily.com/quick-guide-to-enhancing-colors-in-photoshop/"><u>Quick Guide to Enhancing Colors in Photoshop</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-recurring-disk-full-issues-in-windows/"><u>How to Stop Recurring Disk Full Issues in Windows</u></a></li>
<li><a href="https://howto.techidaily.com/authentication-error-occurred-on-infinix-note-30-vip-here-are-10-proven-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Authentication Error Occurred on Infinix Note 30 VIP? Here Are 10 Proven Fixes | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-unlocking-apple-iphone-15-pro-max-lock-screen-3-foolproof-methods-that-actually-work-drfone-by-drfone-ios/"><u>In 2024, Unlocking Apple iPhone 15 Pro Max Lock Screen 3 Foolproof Methods that Actually Work | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-limitations-for-power-use-in-winos/"><u>Bypassing Limitations for Power Use in WinOS</u></a></li>
<li><a href="https://some-techniques.techidaily.com/1716769555249-new-how-many-seconds-is-a-20mb-video/"><u>[New] How Many Seconds Is a 20Mb Video?</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-usb-resources-on-pcs/"><u>Enhancing USB Resources on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/chronicle-of-windows-seven-enduring-traits-in-the-new-era-of-11/"><u>Chronicle of Windows: Seven Enduring Traits in the New Era of 11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/make-every-frame-count-a-list-of-the-hottest-50-video-reducing-apps-for-your-phone/"><u>Make Every Frame Count  A List of the Hottest 50 Video-Reducing Apps for Your Phone</u></a></li>
<li><a href="https://windows11.techidaily.com/initiating-windows-11s-concealed-query-engine/"><u>Initiating Windows 11'S Concealed Query Engine</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-audio-amplification-for-online-photo-archiving/"><u>2024 Approved  Audio Amplification for Online Photo Archiving</u></a></li>
<li><a href="https://howto.techidaily.com/4-ways-to-fix-android-blue-screen-of-death-on-oppo-find-n3-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Ways to Fix Android Blue Screen of Death On Oppo Find N3 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/illuminating-text-adopting-notepads-dark-theme-windows/"><u>Illuminating Text: Adopting Notepad's Dark Theme (Windows)</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/eco-effect-filmmaking-youtubes-guide-to-green-magic-for-2024/"><u>Eco-Effect Filmmaking  YouTube's Guide to Green Magic for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/re-establishing-malwarebytes-service-connections-in-win-oses/"><u>Re-Establishing Malwarebytes' Service Connections in Win OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/escape-without-errors-tips-for-a-well-functioning-key-on-windows/"><u>Escape Without Errors: Tips for a Well-Functioning Key on Windows</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-ultimate-win10-screen-and-video-recording-tool/"><u>2024 Approved  Ultimate Win10 Screen & Video Recording Tool</u></a></li>
<li><a href="https://youtube-data.techidaily.com/lip-concoction-station/"><u>[New] Clip Concoction Station</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-the-top-6-computer-utilization-monitors-on-pcs/"><u>Discover the Top 6 Computer Utilization Monitors on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-routes-to-printer-control-in-windows-11-max-50-chars/"><u>Efficient Routes to Printer Control in Windows 11 (Max 50 Chars)</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-persistent-screen-recording-device/"><u>In 2024, Persistent Screen Recording Device</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-bridging-reality-and-simulation/"><u>[Updated] Bridging Reality and Simulation</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/in-2024-s-best-free-video-rotators-for-3gp-files-a-comprehensive-guide/"><u>In 2024, S Best Free Video Rotators for 3GP Files A Comprehensive Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-the-perfect-keys-list-for-win11s-narrator-control/"><u>Crafting the Perfect Keys List for Win11's Narrator Control</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-the-8-anomalies-in-windows-11s-ui/"><u>Dissecting the 8 Anomalies in Windows 11'S UI</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/oost-your-channels-a-guide-to-best-youtube-seo-resources/"><u>[New] Boost Your Channels  A Guide to Best YouTube SEO Resources</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-latest-guide-how-to-bypass-realme-gt-5-240w-frp-without-computer-by-drfone-android/"><u>In 2024, Latest Guide How To Bypass Realme GT 5 (240W) FRP Without Computer</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-the-art-of-crafting-compelling-video-covers/"><u>In 2024, The Art of Crafting Compelling Video Covers</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-enhancing-online-privacy-youtubes-access-controls/"><u>[Updated] 2024 Approved  Enhancing Online Privacy  YouTube's Access Controls</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-samsung-galaxy-a54-5g-drfone-by-drfone-virtual-android/"><u>How to Get and Use Pokemon Go Promo Codes On Samsung Galaxy A54 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-your-experience-altering-device-settings-in-windows-11/"><u>Customize Your Experience: Altering Device Settings in Windows 11</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-unveiling-social-media-puzzles-how-to-use-facebook-insights/"><u>[New] In 2024, Unveiling Social Media Puzzles  How to Use Facebook Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-devhome-the-essential-guide-to-win11/"><u>Discovering DevHome: The Essential Guide to Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-recurring-edge-shortcut-installations/"><u>Preventing Recurring Edge Shortcut Installations</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-prevalent-anydesk-errors-in-windows/"><u>Decoding Prevalent AnyDesk Errors in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-utorrent-client-not-downloading-files-or-stuck-on-connecting-to-peers-on-windows/"><u>How to Fix the uTorrent Client Not Downloading Files or Stuck on Connecting to Peers on Windows</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-navigating-the-intricacies-of-kinemasters-zooming-capabilities/"><u>2024 Approved  Navigating the Intricacies of Kinemaster's Zooming Capabilities</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-reverse-windows-enter-input-failure/"><u>Methods to Reverse Windows Enter Input Failure</u></a></li>
<li><a href="https://windows11.techidaily.com/easing-windows-woes-with-adobe-ps/"><u>Easing Windows Woes with Adobe PS</u></a></li>
</ul></div>
