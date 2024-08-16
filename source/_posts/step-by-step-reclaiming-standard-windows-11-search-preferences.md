---
title: "Step-by-Step: Reclaiming Standard Windows 11 Search Preferences"
date: 2024-08-15T15:49:05.383Z
updated: 2024-08-16T15:49:05.383Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Step-by-Step: Reclaiming Standard Windows 11 Search Preferences"
excerpt: "This Article Describes Step-by-Step: Reclaiming Standard Windows 11 Search Preferences"
keywords: Win11 Search Guide,Customize Windows 11,Set Win11 Search,Default Win11 Search,Modify Windows 11 Search,Windows 11 Preferences,Restore Win11 Settings
thumbnail: https://thmb.techidaily.com/2e81f992123e17db59f89c6842ca48bb426d509215d95604071818ec4e7dc281.jpg
---

## Step-by-Step: Reclaiming Standard Windows 11 Search Preferences

 Like any other computer program, Windows Search can sometimes develop issues that require you to reset its settings to work properly. This article explains two simple ways to reset Windows Search settings back to default. Let's look at each one in detail.

## Why Should You Reset Windows Search Settings?

 Windows Search tracks files and folders on your hard drive, so you can find them more quickly. However, over time search settings and preferences can become corrupted, leading to incorrect search results or slow performance. To get the most effective results from Windows Search, you should periodically reset your search settings.

 Resetting search settings on Windows can improve search speed and accuracy. It gets rid of useless data and resolves errors or conflicts due to stored information. This can ultimately enhance your computer’s performance and provide a more efficient search experience.

 Let's now explore how to reset Windows Search settings.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Tweak the Registry Editor

 If you want to reset Windows Search settings back to default, you can modify the registry editor. It involves directly changing certain keys in the Windows Registry, which can sometimes become risky if done incorrectly.

 To avoid this issue, be sure to [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before proceeding. Once done, follow these steps.

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the dialog box and hit the Enter key.
3. When the UAC prompt appears on the screen, click **Yes** to continue.
4. In the Registry Editor window, navigate to the following path:  
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows Search  
 You can also copy and paste the path into the address bar at the top of the window and hit the Enter key. This will take you to the Windows Search section.
5. Now move to the right pane and search for the key named **SetupCompletedSuccessfully**.  
![Reset Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-search.jpg)
<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Select this key, right-click on it, and choose **Modify**.
7. Set the value to **0** and click **OK** to save the changes.

 If the SetupCompletedSuccessfully key is missing, you will have to manually create it. To do this, right-click on the Windows Search key and select **New > DWORD (32-bit) Value**. Name this newly created key as **SetupCompletedSuccessfully** and set its value to **0**.

 After performing the steps above, close the Registry Editor and restart your computer for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## 2\. Use Windows PowerShell

 If you prefer command-line solutions, you can use PowerShell to reset Windows Search settings. It involves running a few simple commands to restore search settings. Here's how to do it.

[Open the Microsoft Download Page](https://www.microsoft.com/en-us/download/100295) and download the ResetWindowsSearchBox.ps1 PowerShell script. Once downloaded, right-click on the file and select **Run with PowerShell**.

 If you see an error message _"Cannot be loaded because the running script is disabled on this system"_ you need to enable script execution first. To do that, [open PowerShell as a system administrator](http://www.makeuseof.com/windows-11-powershell-administrator/). Then type **Get-ExecutionPolicy** and press Enter.

![Restrict or Unrestrict the Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restrict-or-unrestrict-the-command.png)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->

 If the output is **Restricted**, execute the following command to allow PowerShell scripts:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted

 After setting the execution policy, try running the ResetWindowsSearchBox.ps1 file again. Once the script is executed successfully, it resets Windows search settings.

![Reset Windows Search Via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-search-via-powershell.png)
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->

 After resetting the Windows Search settings, you can restore the execution policy to its original settings. To do that, open PowerShell as an administrator again and execute the following command:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Restricted

 Once the execution policy is set back to its original value, restart your computer. The Windows Search settings should now be restored to their default state.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
## Easy Ways to Reset Windows Search

 Resetting Windows search settings can fix any issues you may have with your search experience. This guide will teach you how to reset Windows Search settings to their original values.


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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-a-journey-through-the-digital-landscape-six-engaging-quizzes-for-every-vlogger-admirer/"><u>[New] 2024 Approved  A Journey Through the Digital Landscape  Six Engaging Quizzes for Every Vlogger Admirer</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-essential-8-strategies-for-digital-sound-recording-for-2024/"><u>[New] Essential 8 Strategies for Digital Sound Recording for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-revamp-your-resonance-the-7-premier-voice-recorder-change-android-apps/"><u>[New] In 2024, Revamp Your Resonance  The 7 Premier Voice Recorder Change Android Apps</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-microcapture-video-logger-analysis-and-options-for-2024/"><u>[New] MicroCapture Video Logger Analysis & Options for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-pioneering-path-for-instantaneous-srt-to-text-conversions/"><u>[New] Pioneering Path for Instantaneous SRT to Text Conversions</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-quick-video-sharing-tweet-it-up-no-need-for-retweets-for-2024/"><u>[New] Quick Video Sharing  Tweet It Up - No Need for Retweets for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-the-right-way-to-close-a-long-term-but-unneeded-linkedin-account/"><u>[New] The Right Way to Close a Long-Term but Unneeded LinkedIn Account</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-changes-in-instagrams-algorithm-user-perspectives/"><u>[Updated] 2024 Approved  Changes in Instagram's Algorithm  User Perspectives</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-vdq-quickscreen-recorder-report-in-depth-analysis/"><u>[Updated] 2024 Approved  VDQ QuickScreen Recorder Report  In-Depth Analysis</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-discovering-the-secret-to-instagram-voice-change-for-2024/"><u>[Updated] Discovering the Secret to Instagram Voice Change for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-comprehensive-list-of-ios-compatible-ps2-games/"><u>[Updated] In 2024, Comprehensive List of iOS-Compatible PS2 Games</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-mobile-cinema-app-assessment-review-for-2024/"><u>[Updated] Mobile Cinema App Assessment Review for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-stepwise-approach-for-professional-screen-recordings-in-adobe-captive/"><u>[Updated] Stepwise Approach for Professional Screen Recordings in Adobe Captive</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-beyond-spectacle-delving-into-vrs-negatives/"><u>2024 Approved  Beyond Spectacle  Delving Into VR's Negatives</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-beyond-standard-views-a-detailed-look-at-the-z32x-model/"><u>2024 Approved  Beyond Standard Views  A Detailed Look at the Z32X Model</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-professional-grade-grid-tools-for-striking-instagram-posts/"><u>2024 Approved  Professional-Grade Grid Tools for Striking Instagram Posts</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-tech-tips-for-perfect-video-captures/"><u>2024 Approved  Tech Tips for Perfect Video Captures</u></a></li>
<li><a href="https://windows11.techidaily.com/ace-in-the-game-winning-at-full-screen-with-sonic-adventure-w11-edition/"><u>Ace in the Game: Winning at Full Screen with Sonic Adventure, W11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-user-folder-names-on-windows-11/"><u>Altering User Folder Names on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-performance-and-productivity-in-windows-1011/"><u>Boosting Performance & Productivity in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-graphics-glitch-d3d11-error-fixes-for-win11win10/"><u>Conquering Graphics Glitch: D3D11 Error Fixes for Win11/Win10</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-absent-msvcr110dll-in-windows/"><u>Correcting Absent msvcr110.dll in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-wins-system-alert-messages-in-windows-1011/"><u>Correcting WINS System Alert Messages in Windows 10/11</u></a></li>
<li><a href="https://games-able.techidaily.com/crafting-fun-experiences-on-discord-with-board-games/"><u>Crafting Fun Experiences on Discord with Board Games</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-cause-of-display-driver-non-startups/"><u>Deciphering the Cause of Display Driver Non-Startups</u></a></li>
<li><a href="https://windows11.techidaily.com/disable-automatic-snipping-tool-activation-by-prtscn-keypress-in-windows-11/"><u>Disable Automatic Snipping Tool Activation by PrtScn Keypress in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-guide-to-securing-edge-ms-defender-application-guard-on-windows-11/"><u>Easy Guide to Securing Edge: MS Defender Application Guard on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-system-interaction-in-command-prompt/"><u>Elevate Your System Interaction in Command Prompt</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/explosive-growth-video-expectations-sky-high-views/"><u>Explosive Growth  Video Expectations Sky-High Views</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-monochrome-issues-with-windows-store/"><u>Fixing Monochrome Issues with Windows Store</u></a></li>
<li><a href="https://windows11.techidaily.com/how-ai-copilot-enriches-windows-11-for-everyday-users/"><u>How AI Copilot Enriches Windows 11 for Everyday Users</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-does-the-stardust-trade-cost-in-pokemon-go-on-honor-90-lite-drfone-by-drfone-virtual-android/"><u>How does the stardust trade cost In pokemon go On Honor 90 Lite? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-specified-user-does-not-have-a-valid-profile-app-error-in-windows-10-and-11/"><u>How to Fix the Specified User Does Not Have a Valid Profile App Error in Windows 10 & 11</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-pause-life360-location-sharing-for-lava-yuva-2-drfone-by-drfone-virtual-android/"><u>How To Pause Life360 Location Sharing For Lava Yuva 2 | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-spy-on-text-messages-from-computer-and-asus-rog-phone-7-ultimate-drfone-by-drfone-virtual-android/"><u>How to Spy on Text Messages from Computer & Asus ROG Phone 7 Ultimate | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-best-ways-to-bypass-icloud-activation-lock-from-iphone-se-2022ipadipod-by-drfone-ios/"><u>In 2024, Best Ways to Bypass iCloud Activation Lock from iPhone SE (2022)/iPad/iPod</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-turn-off-find-my-iphone-11-when-phone-is-broken-by-drfone-ios/"><u>In 2024, How to Turn Off Find My iPhone 11 when Phone is Broken?</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-innovative-designs-in-syma-x8c/"><u>In 2024, Innovative Designs in Syma X8C</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-original-cinematic-footage-assessment-and-substitutes/"><u>In 2024, Original Cinematic Footage Assessment & Substitutes</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-professional-take-the-syma-x5c-ideal-first-timers-droning-companion/"><u>In 2024, Professional Take  The Syma X5C – Ideal First-Timer's Droning Companion</u></a></li>
<li><a href="https://windows11.techidaily.com/instant-permadelete-configuring-your-desktop-trash-bin-on-windows-11-devices/"><u>Instant PermaDelete: Configuring Your Desktop Trash Bin on Windows 11 Devices</u></a></li>
<li><a href="https://fox-that.techidaily.com/is-your-iphone-ignoring-the-wireless-charger-solve-it-with-these-7-methods/"><u>Is Your iPhone Ignoring the Wireless Charger? Solve It With These 7 Methods!</u></a></li>
<li><a href="https://windows11.techidaily.com/keep-your-disk-space-clear-with-auto-delete-in-win11/"><u>Keep Your Disk Space Clear with Auto-Delete in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-powershell-to-break-free-from-windows-file-blocks/"><u>Mastering PowerShell to Break Free From Windows File Blocks</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-performance-monitoring-pcs-ram-gpu-and-cpu/"><u>Maximizing Performance: Monitoring PC's RAM, GPU & CPU</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/organize-your-digital-life-how-to-clean-up-icloud-photos-without-losing-your-phones-collection/"><u>Organize Your Digital Life: How to Clean Up iCloud Photos Without Losing Your Phone's Collection</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-app-crashes-in-windows-dealing-with-unhandled-exceptions/"><u>Overcoming App Crashes in Windows: Dealing with Unhandled Exceptions</u></a></li>
<li><a href="https://windows11.techidaily.com/prevent-discord-from-checking-for-updates-on-startup/"><u>Prevent Discord From Checking for Updates on Startup</u></a></li>
<li><a href="https://windows11.techidaily.com/protecting-windows-users-best-free-software-downloaders/"><u>Protecting Windows Users: Best Free Software Downloaders</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-resolving-cant-connect-issues-in-windows-11/"><u>Quick Guide: Resolving 'Can't Connect' Issues in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-setup-guide-for-launching-windows-media-player/"><u>Quick Setup Guide for Launching Windows Media Player</u></a></li>
<li><a href="https://windows11.techidaily.com/reconnecting-bluetooth-on-windows-audio-only-fix-guide/"><u>Reconnecting Bluetooth on Windows: Audio Only Fix Guide</u></a></li>
<li><a href="https://extra-resources.techidaily.com/reigning-reddit-stars-10-all-time-favorites/"><u>Reigning Reddit Stars  10 All-Time Favorites</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagining-microsofts-device-link-capabilities-in-windows-11/"><u>Reimagining Microsoft's Device Link Capabilities in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-app-functionality-after-qt-plugin-initialization-breakdown/"><u>Restoring App Functionality After Qt Plugin Initialization Breakdown</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-diagnostics-enhancing-windows-11-troubleshooters/"><u>Reviving Diagnostics: Enhancing Windows 11 Troubleshooters</u></a></li>
<li><a href="https://extra-skills.techidaily.com/simplified-avi-to-gif-editing-with-filmora-on-windows-and-macos-platforms-for-2024/"><u>Simplified AVI to GIF Editing with Filmora on Windows & macOS Platforms for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-making-excel-viewable-in-notepad/"><u>Strategies: Making Excel Viewable in Notepad</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-secure-logins-with-5-tips-against-key-conflicts-in-win11/"><u>Streamlining Secure Logins with 5 Tips Against Key Conflicts in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-for-fixing-unopenable-windows-folders-on-double-click/"><u>Tactics for Fixing Unopenable Windows Folders on Double-Click</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-winerror-x80780119-resolution/"><u>Techniques for WinError X80780119 Resolution</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-nvidia-opengl-glitches-in-windows-11/"><u>Troubleshooting NVIDIA OpenGL Glitches in Windows 11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ultimate-guide-perfectly-matching-your-bose-soundlink-speakers/"><u>Ultimate Guide: Perfectly Matching Your Bose Soundlink Speakers</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-telnet-enablement-steps-explained/"><u>Windows 11 Telnet Enablement Steps Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-pause-auto-updates-no-more-prompts/"><u>Windows Pause Auto-Updates: No More Prompts!</u></a></li>
<li><a href="https://windows11.techidaily.com/winerror-correction-bypassing-the-perplexing-0x80072746-mail-issue/"><u>WinError Correction: Bypassing the Perplexing 0X80072746 Mail Issue</u></a></li>
</ul></div>
