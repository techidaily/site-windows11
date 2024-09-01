---
title: Microsoft Excel's Latest Update Introduces Advanced Data Consolidation Features
date: 2024-08-31T22:05:11.481Z
updated: 2024-09-01T22:05:11.481Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/08/microsoft-excel-logo-1.jpg
---

## Microsoft Excel's Latest Update Introduces Advanced Data Consolidation Features

Microsoft Excel now offers GROUPBY and PIVOTBY aggregation functions, which make it easier to collect and organize data into compact summaries or tables. Plus, a new PERCENTOF function allows you to quickly return percentages from raw data. These functions are still in beta and are currently limited to Microsoft 365 Insider builds.

 The [GROUPBY](https://support.microsoft.com/en-us/office/groupby-function-5e08ae8c-6800-4b72-b623-c41773611505) function is extremely simple and requires just three arguments—what to group by, the values that you want to aggregate, and the function that you'd like to use for aggregation. In an example provided by Microsoft, the function **\=GROUPBY(tbl\[Category\],tbl\[Sales\],SUM)** reduces some complicated sales information into a two-column table. The left side of the table lists product categories, while the right side contains sales numbers aggregated by the SUM function.

 Microsoft's demonstration of the GROUPBY function is shown below.

![Using the GROUPBY function in Microsoft Excel to split item sales into product categories with corresponding sales figures.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/1-5.png) 

Microsoft

 Excel's new [PIVOTBY](https://support.microsoft.com/en-us/office/pivotby-function-de86516a-90ad-4ced-8522-3a25fac389cf) function is extremely similar to GROUPBY, but it takes four arguments instead of three. Using the same dataset from the previous example, Microsoft uses the function **\=PIVOTBY(tbl\[Category\],tbl\[Year\],tbl\[Sales,MAX)** to show the largest sales by product category and year. Total sales for each product category are also included.

 Notice the use of the MAX function in this example. GROUPBY and PIVOTBY allow you to select from a list of Excel's lambda functions, which can remove some of the guesswork when aggregating data. Microsoft plans to expand etc lambda support to all functions that support lambda, meaning that some large functions will become more streamlined and legible.

![Using the PIVOTBY function in Microsoft Excel to split item sales into categories, with each year of sales separated into columns.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/2-2.png) 

Microsoft

 The GROUPBY and PIVOTBY functions aren't groundbreaking, but they're simple, tidy, and automatically updated by changes to your data. Also, you can pull some pretty interesting tricks by fooling around with the new functions' full arguments. Microsoft seems especially proud of text aggregation, which can be performed by using the GROUPBY function with the addition of a sorting argument and ARRAYTOTEXT.

 There's also the new PERCENTOF function. Microsoft says that [PERCENTOF](https://support.microsoft.com/en-us/office/percentof-function-7c66da0a-ac30-45d0-bfc7-834a8bd7c962) is "particularly useful" when paired with GROUPBY or PIVOTBY, as it can spit out complex percentage values with relatively few steps. (Technically speaking, PERCENTOF is logically equivalent to **\=SUM(data\_subset)/SUM(data\_all)**.)

 Microsoft Excel's new functions are currently limited to Microsoft 365 Insider builds. Do not use these functions in important spreadsheets, as they are still in beta and may be modified in a stable release.

 Source: [Microsoft](https://insider.microsoft365.com/en-us/blog/new-aggregation-functions-in-excel-groupby-and-pivotby)

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
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-your-easy-guide-to-revisiting-your-lately-watched-fb-videos/"><u>[New] 2024 Approved  Your Easy Guide to Revisiting Your Lately Watched FB Videos</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-nocturnal-notes-expert-advice-on-low-light-photos-for-2024/"><u>[New] Nocturnal Notes  Expert Advice on Low Light Photos for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-efficient-techniques-for-adobe-presenter-capture/"><u>[Updated] In 2024, Efficient Techniques for Adobe Presenter Capture</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-snapchat-integration-for-twitters-visual-content/"><u>[Updated] In 2024, Snapchat Integration for Twitter's Visual Content</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-the-novice-writers-guide-to-boosting-brand-visibility-through-content-creation-for-2024/"><u>[Updated] The Novice' Writers' Guide to Boosting Brand Visibility Through Content Creation for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-central-luts-in-post-production-filmmaking-revolution/"><u>2024 Approved  Central Luts in Post-Production  Filmmaking Revolution</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-snicker-snapshots-jokeframe/"><u>2024 Approved  Snicker Snapshots  JokeFrame</u></a></li>
<li><a href="https://location-fake.techidaily.com/6-ways-to-change-spotify-location-on-your-realme-v30t-drfone-by-drfone-virtual-android/"><u>6 Ways to Change Spotify Location On Your Realme V30T | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/cellular-network-not-available-for-voice-calls-on-nubia-z50s-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Cellular Network Not Available for Voice Calls On Nubia Z50S Pro | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-and-latest-updates-for-nvidia-geforce-rtx-3070-drivers-on-windows-11-and-10/"><u>Download & Latest Updates for NVIDIA GeForce RTX 3070 Drivers on Windows 11 and 10</u></a></li>
<li><a href="https://tech-haven.techidaily.com/explore-these-superior-open-source-platforms-to-craft-stunning-ai-imagery/"><u>Explore These Superior Open Source Platforms to Craft Stunning AI Imagery</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-taskbar-upgrades-in-windows-11/"><u>Exploring Taskbar Upgrades in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-network-issues-with-anydesk-in-win11/"><u>Fixing Network Issues with AnyDesk in WIn11</u></a></li>
<li><a href="https://windows11.techidaily.com/future-proofing-windows-how-to-leverage-vivetool-advantages/"><u>Future-Proofing Windows: How to Leverage ViVeTool Advantages</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-principles-to-consider-in-a-new-os-rollout/"><u>Guiding Principles to Consider in a New OS Rollout</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-modify-the-visual-cues-in-windows-11-search/"><u>How to Modify the Visual Cues in Windows 11 Search</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-remedy-the-usb-attachment-failure-in-virtualbox-instantly/"><u>How to Remedy the USB Attachment Failure in VirtualBox Instantly</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-corrupt-mp4-and-mov-files-of-realme-gt-5-240w-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair corrupt MP4 and MOV files of Realme GT 5 (240W)?</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-resurrect-a-freeze-fixing-error-code-x-in-windows-11/"><u>How to Resurrect a Freeze: Fixing Error Code X in Windows 11</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/how-to-track-a-lost-apple-iphone-6-plus-for-free-drfone-by-drfone-virtual-ios/"><u>How to Track a Lost Apple iPhone 6 Plus for Free? | Dr.fone</u></a></li>
<li><a href="https://driver-download.techidaily.com/hp-color-laserjet-m452dn-official-and-fast-printer-drivers-available-now/"><u>HP Color LaserJet M452dn - Official & Fast Printer Drivers Available Now</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-charging-notifications-in-modern-windows-os/"><u>Leveraging Charging Notifications in Modern Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/masterclass-guide-to-overcoming-opengl-glitch-3/"><u>Masterclass Guide to Overcoming OpenGL Glitch #3</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-nat-type-adjustment-in-modern-windows-oses/"><u>Mastering NAT Type Adjustment in Modern Windows OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-system-debugging-locating-and-resolving-error-codes-via-windows-command-prompt/"><u>Mastering System Debugging: Locating & Resolving Error Codes via Windows Command Prompt</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-batch-conversion-heic-to-jpeg-in-windows-11/"><u>Mastering the Art of Batch Conversion: Heic to JPEG in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-fixing-install-failed-on-windows-1011/"><u>Mastering the Art of Fixing Install Failed on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-keys-best-offers/"><u>Mastering Windows 11 Keys: Best Offers</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-visual-quality-with-w11s-auto-hdr/"><u>Maximizing Visual Quality with W11's Auto HDR</u></a></li>
<li><a href="https://windows11.techidaily.com/methodology-purging-onedrive-icon-in-file-explorer/"><u>Methodology: Purging OneDrive Icon in File Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-background-run-of-microsoft-edge-on-win11/"><u>Navigating the Background Run of Microsoft Edge on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-errors-fixing-the-termination-denial/"><u>Navigating Windows Errors - Fixing the Termination Denial</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windows-launch-directly-engage-file-explorer-through-onedrive/"><u>Optimizing Windows Launch: Directly Engage File Explorer Through OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-backspace-failures-in-windows-environments/"><u>Overcoming Backspace Failures in Windows Environments</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-game-pass-service-halt-in-win-os/"><u>Overcoming Game Pass Service Halt in Win OS</u></a></li>
<li><a href="https://windows11.techidaily.com/preserving-your-preferred-windows-volume-mixer-state/"><u>Preserving Your Preferred Windows Volume Mixer State</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-and-easy-guide-for-turning-onoff-windows-key/"><u>Quick & Easy Guide for Turning On/Off Windows Key</u></a></li>
<li><a href="https://windows11.techidaily.com/re-initiate-audio-playback-on-frozen-systems/"><u>Re-Initiate Audio Playback on Frozen Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/reducing-unrealcefsubprocess-power-footprint-on-windows-os/"><u>Reducing UnrealCEFSubprocess Power Footprint on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/reigniting-your-wifi-detection-capabilities-in-win11/"><u>Reigniting Your Wifi Detection Capabilities in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/safeguard-privacy-erasing-ms-defender-logs-in-windows-1011/"><u>Safeguard Privacy: Erasing MS Defender Logs in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/set-up-a-fast-safe-login-windows-hello-basics/"><u>Set Up a Fast, Safe Login: Windows Hello Basics</u></a></li>
<li><a href="https://windows11.techidaily.com/solve-your-windows-dilemma-help-strategies-revealed/"><u>Solve Your Windows Dilemma: Help Strategies Revealed!</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/step-by-step-guide-to-crafting-twitreacts/"><u>Step-by-Step Guide to Crafting TwitReacts</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-keeping-calculator-visible-at-top/"><u>Strategies for Keeping Calculator Visible at Top</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-overcoming-windows-administrative-restriction-on-installers/"><u>Strategies for Overcoming Windows' Administrative Restriction on Installers</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-to-overcome-onedrives-immediate-folder-addition-error/"><u>Swift Solutions to Overcome OneDrive's Immediate Folder Addition Error</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-knowledge-of-command-line-nicknames/"><u>The Essential Knowledge of Command Line Nicknames</u></a></li>
<li><a href="https://windows11.techidaily.com/the-insiders-guide-accessing-onedrive-offline-on-windows/"><u>The Insider's Guide: Accessing OneDrive Offline on WINDOWS</u></a></li>
<li><a href="https://windows11.techidaily.com/the-new-era-ai-enhancements-in-windows-platforms/"><u>The New Era: AI Enhancements in Windows Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-unsupported-app-packages-on-windows-xp/"><u>Troubleshooting Unsupported App Packages on Windows XP</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ultimate-guide-mastering-message-management-using-labels-in-gmail/"><u>Ultimate Guide: Mastering Message Management - Using Labels in Gmail</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-windows-arp-caches-deletion-guide/"><u>Understanding Windows ARP Caches: Deletion Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-outlook-preview-features-on-windows-11-platforms/"><u>Unveiling Outlook Preview Features on Windows 11 Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-terminal-the-art-of-color-selection/"><u>Windows Terminal: The Art of Color Selection</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->