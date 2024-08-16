---
title: "Curbing the Noise: Quiet Explore Tab Behavior"
date: 2024-08-15T15:12:03.048Z
updated: 2024-08-16T15:12:03.048Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Curbing the Noise: Quiet Explore Tab Behavior"
excerpt: "This Article Describes Curbing the Noise: Quiet Explore Tab Behavior"
keywords: Silent Exploration Guide,Quiet App Interface,Peaceful Navigation Tips,Soft Touch Experience,Calm App Usage,Low-Volume Browse,Serene Search Strategy
thumbnail: https://thmb.techidaily.com/c92572eed4dd2bbe96a0af1968717f74dd3686117855d1fc2a4babce9d7f3f12.png
---

## Curbing the Noise: Quiet Explore Tab Behavior

 Microsoft was hoping to launch the tabs feature in the File Explorer app for Windows 10\. But it scrapped the idea later on. However, with the Windows 11 22H2 update, users can now try out the tabs feature in File Explorer. The participants of the Windows Insider Program got early access to the feature and Microsoft could soon apply the tabs idea to Windows Notepad as well.

 But what if you want to turn the File Explorer Tabs feature off? An immediate idea would be to uninstall the update, but that is a temporary workaround. You can use ViVeTool to enable or disable the tabs feature or any other new feature of Windows 11.

## What Is ViVeTool?

 ViVeTool is an open-source command line tool that can enable or disable Windows operating system features. Microsoft continuously works on many experimental features and does a lot of testing before rolling out a stable version of a feature. But if you are impatient, you can use ViVeTool to enable an otherwise hidden feature. It is free and the developers recently launched a GUI version of the tool as well.

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Disable File Explorer Tabs In Windows 11

 You can disable the File Explorer Tabs by either using the ViVeTool or the ViVeTool GUI version. The latter is much simpler to use because you can search for a feature and activate or deactivate it in one click. But before doing that, download and install both of these tools on your system. Also,[create a system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) for added precaution, in case the tool wrecks something on your Windows 11 computer.

**Download:** [ViVeTool](https://github.com/thebookisclosed/ViVe/releases)

**Download:** [ViVeTool GUI](https://github.com/PeterStrick/ViVeTool-GUI/releases)

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
### 1\. Disable File Explorer Tabs Using the ViVeTool

 Since it is a command line tool, you can access it from a terminal window. Here’s how to do it:

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**CMD** in the text input area and press**Ctrl + Shift + Enter** key to launch the command prompt with administrator privileges.
3. Type**cd Drive Name:\\path** . Here, you need to enter the exact location where you extracted the tool after downloading it. For example, we extracted it to a folder name Vive in C drive. So, our command is**cd C:\\Vive** .
4. Now, you will be in the directory where ViVeTool exists. Type**vivetool** and press the**Enter** key. You will see a bunch of parameters you can use with the tool.  
![Disable File Explorer Tabs Using the ViVeTool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
5. Type the following two commands, one by one in the CMD and press the**Enter** key.  
vivetool /disable /id:37634385  
vivetool /disable /id:36354489
6. You will see the “**Successfully set feature configuration(s)** ” if the command executes successfully.
7. Now,**restart** your system for the changes to take effect. The File Explorer Tabs feature will no longer be active on your system.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Disable File Explorer Tabs Using the ViVeTool GUI version

 The GUI version of ViVeTool works similarly. You can manually enter the feature ID or use the search function to find a feature in the list. Repeat the following steps to disable File Explorer Tabs using the ViVeTool GUI.

1. Launch the ViVeTool GUI with admin privileges.
2. Click on the drop-down list and select the latest Windows build number. Wait for the tool to list all the feature IDs available for the Windows build.
3. Type**37634385** in the search bar. Select the highlighted feature and click on the**Perform Action** button.  
![Disable File Explorer Tabs Using the ViVeTool GUI version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool-gui-version.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Select the**Deactivate Feature** option. Similarly, find the feature ID**36354489** and deactivate it.
5. Now, close the ViVeTool GUI and**restart** your system.
6. Open the File Explorer and you won’t see the tabs feature anymore.

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://youtube-zero.techidaily.com/024-approved-launch-your-channel-8-entry-level-digital-course-series/"><u>[New] 2024 Approved  Launch Your Channel  8 Entry-Level Digital Course Series</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-2024-approved-speedy-shots-for-immersive-narratives/"><u>[New] 2024 Approved  Speedy Shots for Immersive Narratives</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-transforming-tweetstream-into-hd-visionary-content/"><u>[New] 2024 Approved  Transforming Tweetstream Into HD Visionary Content</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-assessing-magixs-multimedia-capabilities-for-2024/"><u>[New] Assessing MAGIX's Multimedia Capabilities for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-exploring-next-gen-vector-software-for-designers/"><u>[New] Exploring Next-Gen Vector Software for Designers</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-discover-who-youre-watching-6-quizzes-for-youtube-fans/"><u>[New] In 2024, Discover Who You're Watching  6 Quizzes for YouTube Fans</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-dive-into-high-definition-fb-streaming-in-1080p/"><u>[New] In 2024, Dive Into High Definition  FB Streaming in 1080P</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-invisible-pathways-advanced-techniques-for-chat-file-extraction/"><u>[New] In 2024, Invisible Pathways  Advanced Techniques for Chat File Extraction</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-secure-your-memories-long-term-webcam-video-storage-in-vlc-for-2024/"><u>[New] Secure Your Memories  Long-Term Webcam Video Storage in VLC for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unraveling-photoshops-magic-with-image-curving/"><u>[New] Unraveling Photoshop’s Magic with Image Curving</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-5-pioneering-portals-to-streamline-your-text-effects-search/"><u>[Updated] 5 Pioneering Portals to Streamline Your Text Effects Search</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-your-path-to-an-elite-online-presence-six-strategic-methods-for-instagram-fame/"><u>[Updated] In 2024, Your Path to an Elite Online Presence  Six Strategic Methods for Instagram Fame</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-step-by-step-guide-on-using-gaming-youtube-banner-templates/"><u>[Updated] Step-By-Step Guide on Using Gaming YouTube Banner Templates</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-strategies-for-effective-b-roll-application/"><u>[Updated] Strategies for Effective B-Roll Application</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-leading-edge-asmr-audio-gear-without-breaking-the-bank/"><u>2024 Approved  Leading-Edge ASMR Audio Gear Without Breaking the Bank</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-infinix-zero-5g-2023-turbo-drfone-by-drfone-virtual-android/"><u>4 solution to get rid of pokemon fail to detect location On Infinix Zero 5G 2023 Turbo | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/achieving-livestream-control-fifteen-innovative-techniques/"><u>Achieving Livestream Control  Fifteen Innovative Techniques</u></a></li>
<li><a href="https://howto.techidaily.com/android-safe-mode-how-to-turn-off-safe-mode-on-vivo-t2-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Safe Mode - How to Turn off Safe Mode on Vivo T2 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-for-fixing-iphone-image-import-issues-in-windows/"><u>Essential Tips for Fixing iPhone Image Import Issues in Windows</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/script-to-screen-youtube-tutorial-and-alternative-pathways/"><u>From Script to Screen  YouTube Tutorial & Alternative Pathways</u></a></li>
<li><a href="https://fake-location.techidaily.com/full-guide-to-fix-itoolab-anygo-not-working-on-samsung-galaxy-z-fold-5-drfone-by-drfone-virtual-android/"><u>Full Guide to Fix iToolab AnyGO Not Working On Samsung Galaxy Z Fold 5 | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/go-beyond-stills-with-vimeo-animations-a-gif-guide/"><u>Go Beyond Stills with Vimeo Animations  A GIF Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-enable-microphone-during-powerpoint-recording/"><u>How to Enable Microphone During PowerPoint Recording</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-halt-windows-push-notifications-for-updates/"><u>How to Halt Windows Push Notifications for Updates</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-spotify-location-after-moving-to-another-country-on-poco-c50-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Spotify Location After Moving to Another Country On Poco C50 | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-zte-axon-40-lite-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from ZTE Axon 40 Lite to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/locating-open-tcp-ports-in-windows-os/"><u>Locating Open TCP Ports in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/lockdown-the-background-on-your-modern-windows-11/"><u>Lockdown the Background on Your Modern Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-at-hand-essential-methods-to-decode-qr-codes-on-windows/"><u>Mastery at Hand: Essential Methods to Decode QR Codes on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-copy-pasting-like-a-pro-using-powertoys/"><u>Navigate Copy-Pasting Like a Pro Using PowerToys</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-auditory-balance-tips-on-reducing-unwanted-sibilance-and-whistles-for-2024/"><u>New Auditory Balance Tips on Reducing Unwanted Sibilance and Whistles for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-pc-embrace-the-power-of-self-cleaning-files-on-winos/"><u>Optimize Your PC: Embrace the Power of Self-Cleaning Files on WINOS</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-your-tech-experience-maintain-win-11-alerts/"><u>Optimizing Your Tech Experience: Maintain Win 11 Alerts</u></a></li>
<li><a href="https://win-solutions.techidaily.com/overcoming-installation-hurdles-effective-remedies-when-your-xbox-game-wont-load/"><u>Overcoming Installation Hurdles: Effective Remedies When Your Xbox Game Won’t Load</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-one-way-outlook-on-safe-windows-mode/"><u>Overcoming One-Way Outlook on Safe Windows Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-challenge-interrupt-exception-in-windows-os/"><u>Overcoming the Challenge: Interrupt Exception in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/peering-inside-windows-11-understanding-its-registry-essence/"><u>Peering Inside Windows 11: Understanding Its Registry Essence</u></a></li>
<li><a href="https://windows11.techidaily.com/personalizing-the-windows-11-task-manager-homepage/"><u>Personalizing the Windows 11 Task Manager Homepage</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-how-to-correct-windows-11s-keyboard-type-trouble-code-0x80049dd3/"><u>Quick Guide: How to Correct Windows 11'S Keyboard Type Trouble (Code: 0X80049DD3)</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-link-loss-in-winvpn-a-step-by-step-solution/"><u>Restoring Link Loss in WinVPN: A Step-By Step Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/separate-icons-simplify-win-11-ui/"><u>Separate Icons, Simplify Win 11 UI</u></a></li>
<li><a href="https://windows11.techidaily.com/shedding-darkness-8-ways-to-lighten-up-windows-desktops/"><u>Shedding Darkness: 8 Ways to Lighten Up Windows Desktops</u></a></li>
<li><a href="https://windows11.techidaily.com/skyrocket-above-the-100mbps-ethernet-threshold-in-windows/"><u>Skyrocket Above the 100Mbps Ethernet Threshold in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/smooth-save-experience-top-6-strategies-to-tackle-ppt-errors/"><u>Smooth Save Experience: Top 6 Strategies to Tackle PPT Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-correcting-winrars-incorrect-file-hashes/"><u>Solutions to Correcting WinRAR's Incorrect File Hashes</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-erase-office-365-error-30015-26-on-pcs/"><u>Solutions to Erase Office 365 Error 30015-26 on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-fix-audacitys-device-opens-error-in-windows-1011/"><u>Steps to Fix Audacity’s Device Opens Error in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resurrect-your-disconnected-controller/"><u>Steps to Resurrect Your Disconnected Controller</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-preventing-dxgi-errors/"><u>Strategies for Preventing DXGI Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-troublesome-windows-programming-issues-7-ways/"><u>Tackling Troublesome Windows Programming Issues (7 Ways)</u></a></li>
<li><a href="https://facebook.techidaily.com/taming-your-facebook-memories-privacy-controls/"><u>Taming Your Facebook Memories: Privacy Controls</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-ultimate-showdown-xsplits-efficacy-versus-obs/"><u>The Ultimate Showdown  XSplit's Efficacy Versus OBS</u></a></li>
<li><a href="https://techidaily.com/the-way-to-recover-deleted-photos-on-oneplus-nord-n30-5g-without-backup-by-fonelab-android-recover-photos/"><u>The way to recover deleted photos on OnePlus Nord N30 5G without backup.</u></a></li>
<li><a href="https://windows11.techidaily.com/time-capsule-trick-the-use-of-windows-7-key-for-activating-11/"><u>Time Capsule Trick: The Use of Windows 7 Key for Activating 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-best-spy-watches-for-your-motorola-moto-g04-drfone-by-drfone-virtual-android/"><u>Top 10 Best Spy Watches For your Motorola Moto G04 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-overcoming-windows-terminal-access-issues/"><u>Troubleshooting: Overcoming Windows Terminal Access Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/tutorial-navigating-to-windows-11-phone-dialer/"><u>Tutorial: Navigating to Windows 11 Phone Dialer</u></a></li>
<li><a href="https://windows11.techidaily.com/uncover-9-steps-for-altering-the-auditory-elements-of-windows-11/"><u>Uncover 9 Steps for Altering the Auditory Elements of Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/uncover-the-magic-of-reading-comics-on-windows-11/"><u>Uncover the Magic of Reading Comics on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-fixing-windows-roblox-code-403-issue/"><u>Understanding & Fixing Windows Roblox Code 403 Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-advanced-techniques-for-blurry-backgrounds-in-w11-photo-feature/"><u>Unveiling Advanced Techniques for Blurry Backgrounds in W11 Photo Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/visual-illusion-blending-image-and-archive-data-without-notice-win1011/"><u>Visual Illusion: Blending Image and Archive Data without Notice WIN10/11</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/what-legendaries-are-in-pokemon-platinum-on-apple-iphone-13-mini-drfone-by-drfone-virtual-ios/"><u>What Legendaries Are In Pokemon Platinum On Apple iPhone 13 mini? | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/which-pokemon-can-evolve-with-a-moon-stone-for-honor-magic-5-lite-drfone-by-drfone-virtual-android/"><u>Which Pokémon can Evolve with a Moon Stone For Honor Magic 5 Lite? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-offline-the-essential-manual/"><u>Win11 Offline: The Essential Manual</u></a></li>
<li><a href="https://techidaily.com/xiaomi-13t-won-t-play-mkv-movies-by-aiseesoft-video-converter-play-mkv-on-android/"><u>Xiaomi 13T won’t play MKV movies</u></a></li>
</ul></div>
